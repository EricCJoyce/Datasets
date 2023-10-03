## Checkers Transcripts

All matches adhered to [American Checker Federation](http://www.usacheckers.com) (ACF) rules (e.g. if a jump is possible, then you must jump).

Moves follow the notation illustrated in REF.png. Moves alternate sides and are separated by spaces. Move indices are separated by hyphens. Sequences of more than one jump share intermediate indices, meaning a-b-c is read as "The piece at `a` jumps to `b`, then from `b` to `c`." Match results are separated from their move sequences by a tab. 1/2-1/2 means the game ended in a draw. 1-0 means Red (side to move first) won. 0-1 means White won.

`ACF.txt`: one line is one (anonymous) match taken from the ACF archives.

`genetic.txt`: generated during the genetic algorithm. This file omits drawn matches.

`tdl.txt`: generated during TD(lambda) training. In this file, the starting position of each match appears first per line.

However your deep learning project interprets the board, you can use these records to train a value or a policy network.

## Citation

If these data were helpful for your research, please consider citing this repository.

```
@misc{checkers_2020,
  title={Checkers Transcripts},
  author={Eric C. Joyce},
  year={2020},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/EricCJoyce/Datasets}}
}
```
