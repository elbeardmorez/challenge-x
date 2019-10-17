# challenge-x

## description
challenge solutions, containing only my code and thus only my 'intellectual' property. they may require 'stubs' from challenge providers to create complete working solutions - those are deliberately not included. the solutions are in the form of patches from my master 'challenge' repository (also not exposed) in a vein attempt of obfuscation

worth noting is that writing code that is easily portable code between my favoured c++/c#/javascript/python language set sometimes results in me deliberately not using language-specific idioms. the extent to which i do, is usually dependent upon which language the actual 'solution' (as opposed to subsequent port(s)) is written in ..which is determined by `/dev/urandom` generated randomness

this repository contains a heck of a lot of my programming faux-pas, but i've decided that it's healthy to expose my limits and one would hope i can only get better!

## hackerrank
### attempts
- expert | 0
- advanced | 3
- hard | 15
- medium | 61
- easy | 219

### incomplete
- [algorithms|strings|advanced] ashton and string | 33.33/100
- [algorithms|implementation|medium] forming a magic square | 0/20
- [data structures|heap|hard] find the running median | 0/50
- [algorithms|implementation|medium] the bomberman game | 20/40
- [algorithms|implementation|medium] non-divisible subset | 9.33/20

### hardest / favourite successes
- [algorithms|strings|medium] common child | python solution
- [algorithms|strings|advanced] two two | c++ solution
- [algorithms|sorting|easy] big sorting | c# port

### 'cheated'
- [algorithms|implementation|medium] 3d surface area | convinced myself there was a bug. there wasn't :|

### bugs
i refuse to 'work around' bugs like others have done, hard-coding results on a per broken test case basis in order to dishonestly achieve the maximum score. doing so means they'll never get fixed! i have raised the following bugs through the hackerrank 'suggestions' medium with no feedback

#### live
- [algorithms|constructive algorithms|medium] bonetrousle | javascript, out of bounds use of ParseInt in stub
- [algorithms|graph theory|medium] journey to the moon | c# stub use 'int's (signed 32-bit) but output 11 4999949998, which is > 2^31-1
- [data structures|linked lists|easy] insert a node at the head of a linked list | c#, attempted use of pointer notation in locket code area, probably a c++ copy/paste error
- [data structures|linked lists|medium] cylce detection | javascript, use of 'int' in locked code area
- [python|regex and parsing|easy] validating uid | python, copy/paste error in test case 3
- [linux shell|text processing|easy] cut #1 | test case 2 output bares no correlation to input. copy/paste error
- [linux shell|text processing|easy] cut #2 | test case 2 output bares no correlation to input. copy/paste error
- [linux shell|text processing|easy] cut #3 | test case 2 output bares no correlation to input. copy/paste error
- [linux shell|text processing|easy] cut #4 | test case 2 output bares no correlation to input. copy/paste error
- [linux shell|text processing|easy] cut #6 | test case 2 output bares no correlation to input. copy/paste error. there all also line termination differences between test case 2 and 0 / 3
- [linux shell|text processing|easy] cut #7 | invalid / total nonsense example used for test case 0

#### fixed
- [data structures|linked lists|medium] cycle detection | python, tab char in locked code area
- [data structures|linked lists|easy] find merge point of two lists | javascript, use of 'int' in locked code area
- [data structures|linked lists|easy] find merge point of two lists | python, tab char in locked code area
- [data structures|linked lists|easy] insert a node at the tail of a linked list | python, tab char in locked code area
- [data structures|linked lists|easy] insert a node at the head of a linked list | python, tab char in locked code area
