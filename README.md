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

![Solution Code](img/day02.bf.png)

1. Blue: standard input loop, exiting on EOF (-1).
2. Purple: check for newline (10).
3. Red: check for "x".
4. Yellow: on "x", discard the input and push 0 for the next number.
5. Green: subtract ASCII value of "0" to convert input to number. Multiply
   existing number by 10 and add the input number.
6. Cyan: on newline, the length, width and height will be on the stack. Replace
   each "l", "w", "h" in the pink and orange regions with their values.
7. Pink: find the smallest side by calculating each and performing greater-than
   comparisons.
8. Orange: calculate the areas of each side, add them, and multiply by two. Add
   the area of the smallest side. Add the area to the total, output, then push
   0 for the next input value.

## [Day 3: Perfectly Spherical Houses in a Vacuum][day3]

[Solution](day03.bf)

Note: none-standard Befunge, 255x255 program space.

TODO: Explanation

[day1]: http://adventofcode.com/day/1
[day2]: http://adventofcode.com/day/2
[day3]: http://adventofcode.com/day/3
