---
title: Knight fork loses immediately
date: 2022-06-30 17:20:20 -0500
categories: [chess, low ELO legends]
tags: [chess, blunders]
---
## Chess is hard

Welcome to low ELO legends! Where mistakes and inaccuracies do not matter because the winner is the player that manages to blunder the least! This results in very exciting chess where all three results are always possible!

## Set Up

Consider the following game, full of blunders and missed opportunities.

> 1.c4 e6 2. Nc3 Nf6 3. Nf3 d5 4. cxd5 Nxd5 5. e4 Nxc3 6. bxc3 c5 7. Bb5+ Bd7 8. Bc4 Nc6 9. O-O Bd6 10. d4 cxd4 11. Ng5 h6 12. Nxf7 Kxf7 13. Qf3+ Qf6 14. Qh5+ g6 15. Qd1 Be5 16. Bb2 Rad8 17. f4 Bc7 18. cxd4 Bc8 19. Qe1 Bb6 20. e5 Qf5 21. Kh1 Bxd4 22. Bxd4 Nxd4 23. Rd1 Nc2 24. Qe2 Rxd1 25. Rxd1 b6 26. Bd3 Nd4 27. Qf2 Qh5 28. Rf1

after `Rf1` I'd say both sides stand badly, but black is clearly better

![white plays Rf1][pos1]{: w="700" h="700" }
*Both sides stand badly, but white is clearly worst*

Since the purpose of `Rf1` was to move it out of the black queens’ way and attack the knight, my opponent wisely decided to maneuver it to a better square with `Nf5`, I decided that I was completely lost anyways and might as well get some sort of counterplay with `Qc2`. Engine recommends trading my bishop for the knight but since we are both low rated, chances are I still might find some way to win.

![black plays Nf2][pos2]{: w="350" h="350" .normal}
![white plays Qc2][pos3]{: w="350" h="350" .normal}

## Blunder Time

> After thinking for 9 seconds my opponent found the only move that loses the game.
{: .prompt-info }

 I don’t blame him at all, since in a rapid game with low time I’d play `Ng3+??` almost immediately.  I **expertly** played the only legal move `Kg1` and now white is `+3`.  `Qc7+` is now too strong. The best try for black is to retreat the knight back to `f5`. But that would defeat the purpose of `Ng3+` so my opponent decided to capture my rook. I'd hazard a guess he calculated that my king would capture back and he was perfectly fine. We instead play the crushing `Qc7+`

![black plays Ng3+??][pos4]{: w="350" h="350" .normal}
![white plays Kg1][pos5]{: w="350" h="350" .normal}
![black plays Nxf1?][pos6]{: w="350" h="350" .normal}
![white plays Qc7+][pos7]{: w="350" h="350" .normal}

## Consecuences
> As engines like to say: checkmate is now unavoidable
{: .prompt-info }

I usually take issue with that evaluation. Checkmate is now unavoidable with correct play and as I’ve established: this is very rarely the case. Here we need not be Kasparov to see that at the very least black is losing absolutely every piece in his back rank.

I evidently had not calculated nor seen that `Qc7+` was mate in 9, I just wanted some counterplay, and counterplay I got. Since every move was check, finding the mate was easy.

![white delivers mate][ending]{: w="500" h="500"  }

I got very lucky that the most obvious and attractive move for my opponent was the losing move, and that he underestimated or miscalculated `Qc7+`

| Game Information |
| ---------------------- |
| [devcam (1859) v. Ekkiout (1867)](https://lichess.org/GUJ1zkfb) |
| Rated Rapid game |
| Opening `English Opening: Anglo-Indian Defense, Hedgehog System` |

[pos1]: https://lichess.org/export/gif/2b4r/p4k2/1p2p1pp/4P2q/3n1P2/3B4/P4QPP/5R1K_b_-_-_5_28?color=white&lastMove=d1f1&variant=standard
[pos2]: https://lichess.org/export/gif/2b4r/p4k2/1p2p1pp/4Pn1q/5P2/3B4/P4QPP/5R1K_w_-_-_6_29?color=white&lastMove=d4f5&variant=standard
[pos3]: https://lichess.org/export/gif/2b4r/p4k2/1p2p1pp/4Pn1q/5P2/3B4/P1Q3PP/5R1K_b_-_-_7_29?color=white&lastMove=f2c2&variant=standard 
[pos4]: https://lichess.org/export/gif/2b4r/p4k2/1p2p1pp/4P2q/5P2/3B2n1/P1Q3PP/5R1K_w_-_-_8_30?color=white&lastMove=f5g3&variant=standard
[pos5]: https://lichess.org/export/gif/2b4r/p4k2/1p2p1pp/4P2q/5P2/3B2n1/P1Q3PP/5RK1_b_-_-_9_30?color=white&lastMove=h1g1&variant=standard
[pos6]: https://lichess.org/export/gif/2b4r/p4k2/1p2p1pp/4P2q/5P2/3B4/P1Q3PP/5nK1_w_-_-_0_31?color=white&lastMove=g3f1&variant=standard
[pos7]: https://lichess.org/export/gif/2b4r/p1Q2k2/1p2p1pp/4P2q/5P2/3B4/P5PP/5nK1_b_-_-_1_31?color=white&lastMove=c2c7&variant=standard
[ending]: /assets/games/2022-06-30-devcam-Ekkiout.gif
