# BROWNERD FIG

My favorite figlet is actually a typeface for print made by [Process Type Foundry](http://processtypefoundry.com/) called [FIG Serif](http://processtypefoundry.com/fonts/fig/). However, it is not usable outside of print. So, I spent the day making this into a usable figlet for dev use.

I've contacted Process Type Foundry to see if I can submit it for open source use. I hope they say yes. Fingers crossed.


## ORIGIN of FIGLET

"FIGlet" stands for "Frank, Ian and Glenn's LETters". You can read more about it's origins here [patorjk/figlet.js](https://github.com/patorjk/figlet.js/blob/master/doc/figfont.txt)


## FIGLET header explained

`flf2a$ 10 8 12 0 38 0` The first five characters "flf2a" must be at the beginning of every figlet file. This header and it's settings give the configurations needed to display your characters correctly.
---
Here is a [FIGlet](http://www.jave.de/figlet/figfont.html) diagram.

```
        flf2a$ 6 5 20 15 3 0 143 229
          |  | | | |  |  | |  |   |
         /  /  | | |  |  | |  |   \
Signature  /  /  | |  |  | |   \   Codetag_Count
  Hardblank  /  /  |  |  |  \   Full_Layout
       Height  /   |  |   \  Print_Direction
       Baseline   /    \   Comment_Lines
        Max_Length      Old_Layout
```

---

## Resources
If you ever want to make your own figlet these resources will help a bunch. Also, review the code of other figlets.

- [FIGfont](http://www.jave.de/figlet/figfont.html)
- [patorjk/figlet.js](https://github.com/patorjk/figlet.js/blob/master/doc/figfont.txt)
- [FIGlet and AOL Macro Fonts](http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20)


## Todo
If Process Type Foundry approves this figlet, then I will try to get it submitted for open use.

If you design a FIGfont, please send an e-mail announcement to
<figletfonts@onelist.com>, the FIGlet fonts mailing list, and email a copy
to ianchai@usa.net for him to put it at the ftp site.

### Make Atom and Sublime packages to use
- [Your first package](https://atom.io/docs/latest/your-first-package)
- [ASCII-Decorator](https://github.com/viisual/ASCII-Decorator)
