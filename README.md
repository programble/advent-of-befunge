# Advent of Befunge

Advent of Code in Befunge

## [Day 1: Not Quite Lisp][day1]

[Solution](day01.bf)

Note: input must not end in a newline.

![Solution Code](img/day01.bf.png)

1. Blue: standard input loop, exiting on EOF (-1).
2. Purple: subtract ASCII value of `)` from input, resulting in `-1` for `(`
   and `0` for `)`.
3. Red: add the logical NOT of the result to itself, resulting in `-1` for `(`
   and `1` for `)`.
4. Yellow: subtract the result from the total and output it.

## [Day 2: I Was Told There Would Be No Math][day2]

[Solution](day02.bf)

```
>~:1+!#@_:25*-#v_$:::::84p92*1+4p55*4p57*1+4p86*4p552**2+4p::::24p74p82*2+4p5v>
^   0$_v#!-"x":<            vp4+3**255p4*67p4+2*75p4+1*55p41::::p4+7*85p4+3*8<
^      >"0"-\25**+
                            >                                                  v
"lw"*:"wh"*`!#v_$"wh"*>:"hl"*`!#v_$"hl"*>"lw"*"wh"*"hl"*++2*++:.0             ^>
              >       ^         >       ^
```

TODO: Explanation

## [Day 3: Perfectly Spherical Houses in a Vacuum][day3]

[Solution](day03.bf)

Note: none-standard Befunge, 255x255 program space.

TODO: Explanation

[day1]: http://adventofcode.com/day/1
[day2]: http://adventofcode.com/day/2
[day3]: http://adventofcode.com/day/3
