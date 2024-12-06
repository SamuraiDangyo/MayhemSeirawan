![logo](https://github.com/user-attachments/assets/4b9cc739-fc1f-4bd7-8746-c4cc5a9dfbcd)

# MayhemSeirawan

Linux Xboard Seirawan Chess Engine

## Supported commands

```
MayhemSeirawan. Linux Xboard Seirawan Chess engine. Written in C++20 language

Supported commands:

help
  This help

ping [N]
  Responded by 'pong N'

level [movestogo] [time] [inc]
  Setup time control

random
  Add random element to eval

time [N]
  Setup time left for the engine

force
  Setup force mode. Act only after 'go' command

new
  Setup new game

list
  Show list of moves

play [ms = 5000]
  Watch a game

analyze
  Analyze position

undo
  Go back in history

.
  Respond ASAP

option
  Setup option in form of 'option hash=256'

variant
  Setup variant

setboard
  Setup board using FEN notation

logo
  Print ASCII art logo

p [fen = startpos]
  Print ASCII art board

perft [depth = 6] [fen = startpos]
  Calculate perft split numbers

bench [depth = 14]
  Show signature of the program

speed [ms = 5000]
  Show speed of the program

exit
  Exits the analyze mode

quit
  Exits the engine ASAP
```

## Sample game

```
[White "MayhemSeirawan 0.1"]
[Black "Fairy-Max 5.0b"]
[Result "1-0"]
[TimeControl "60+1"]
[Variant "seirawan"]
1. e4 {+0,77/8} Nh6/H {+0,08/6 1,3} 2. Nc3/E {+0,47/9 3} Nc6/E
{+0,12/7 2,7} 3. d4 {+0,99/12 3} d6 {-0,13/8 4} 4. Bg5/H {+1,25/13 3} f6
{+0,07/7 1,9} 5. Bxh6 {+1,62/16 3} Hxh6 {-0,17/10 9} 6. Hxh6 {+1,76/15 2,9}
gxh6 {-0,13/10 2,8} 7. Qh5+ {+1,97/13 2,8} Kd7 {-0,37/9 2,4} 8. Nf3
{+1,95/13 2,7} Qe8 {-0,13/9 3} 9. Qh4 {+1,62/14 2,7} Qg6 {+0,24/8 2,7} 10.
Nd5 {+1,93/14 2,6} f5 {+0,33/7 1,3} 11. exf5 {+2,42/14 2,5} Qxf5
{+0,12/8 1,5} 12. Ec3 {+2,47/13 2,5} Rg8 {+0,10/7 1,0} 13. Ee3
{+3,58/12 2,4} Qf7 {-0,16/8 1,0} 14. Bc4 {+4,08/12 2,4} Qg6 {-0,50/8 1,5}
15. Nf4 {+4,59/12 2,3} Qg7 {-1,60/8 1,2} 16. Be6+ {+4,53/12 2,3} Kd8
{-1,90/9 1,5} 17. Bxg8 {+4,61/14 2,2} Qxg8 {-1,76/9 1,3} 18. d5
{+4,45/14 2,2} Nb4 {-1,99/9 2,2} 19. O-O-O {+4,73/13 2,1} Nxa2+
{-0,96/8 1,7} 20. Kb1 {+4,92/15 2,1} Ea6 {-1,28/9 1,2} 21. Rhe1
{+4,99/14 2,0} Qf7 {-1,14/8 1,6} 22. Ne6+ {+5,14/13 2,0} Bxe6 {-1,39/9 2,0}
23. dxe6 {+4,98/13 1,9} Qg8 {-1,85/8 1,0} 24. Ne5 {+4,99/12 1,9} Qg7
{-2,23/8 2,0} 25. Ef5 {+6,36/13 1,9} Eb4 {-3,05/8 4} 26. Qg3 {+7,61/13 1,8}
Kc8 {-3,06/8 1,1} 27. Qxg7 {+8,98/15 1,8} Nc3+ {-7,72/11 1,7} 28. Kc1
{+12,84/17 1,8} Na2+ {-10,44/11 2,2} 29. Kd2 {+13,85/16 1,7} Ed5+
{-10,30/11 1,5} 30. Ke2 {+14,74/17 1,7} Bxg7 {-10,94/11 1,0} 31. Rxd5
{+15,22/16 1,7} Bf6 {-14,90/11 2,2} 32. Exf6 {+15,81/15 1,7} exf6
{-1000,07/12 1,0} 33. e7 {+104,85/14 0,3} Nc3+ {-1000,06/13 1,3} 34. Kf3
{+104,85/9} c5 {-1000,05/15 1,2} 35. e8=E# {+104,85/2}
{Xboard adjudication: Checkmate} 1-0
```
