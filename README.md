# BROWNERD FIG

I have owned the [FIG](http://processtypefoundry.com/fonts/fig/) typeface from Process Type Foundry for years (since 2007).


## ORIGIN of FIGLET

"FIGlet" stands for "Frank, Ian and Glenn's LETters". Inspired  by Frank's .sig, Glenn wrote (most of) it, and Ian helped.

Most of the standard FIGlet fonts were inspired by signatures on various UseNet articles. Since typically hundreds of people use the same style of letters in their signatures, it was often not deemed necessary to give credit to any one font designer.


## FIGLETs explained

**flf2a$ 10 8 12 0 38 0**
---
[FIGlet](http://www.jave.de/figlet/figfont.html)

```
        flf2a$ 6 5 20 15 3 0 143 229    NOTE: The first five characters in
          |  | | | |  |  | |  |   |     the entire file must be "flf2a".
         /  /  | | |  |  | |  |   \
Signature  /  /  | |  |  | |   \   Codetag_Count
  Hardblank  /  /  |  |  |  \   Full_Layout
       Height  /   |  |   \  Print_Direction
       Baseline   /    \   Comment_Lines
        Max_Length      Old_Layout
```

* The two layout parameters are closely related and fairly complex.*
* See Interpretation of Layout Parameters.*


### Explanation of first line:
- flf2         -"magic number" for file identification
- a            - should always be 'a', for now
- $            - the "hardblank" prints as a blank, but can't be smushed
- 10           - height of a character
- 8            - (baseline) height of a character, not including descenders
- 9 + 3 = 12   - (M) max line length (excluding comment lines) + a few spaces
- 0            - Old Layout default settings
- 38           - number of comment lines
- 0            - Print direction default left to rigth
---
