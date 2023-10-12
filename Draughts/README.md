## International Draughts Transcripts

All matches adhere to [Fédération Mondiale de Jeu de Dames](https://www.fmjd.org/) rules (e.g. if a jump is possible, then you must jump, and you must make the longest possible jump).

One uncommented line is one match. Moves follow the notation illustrated in REF.png. Moves alternate sides and are separated by spaces. Move indices are separated by hyphens. Sequences of more than one jump share intermediate indices, meaning a-b-c is read as "The piece at `a` jumps to `b`, then from `b` to `c`." Match results are separated from their move sequences by a tab. 1/2-1/2 means the game ended in a draw. 1-0 means light (side to move first) won. 0-1 means dark won.

`tdl.zip` was generated during TD(lambda) training.

However your deep learning project interprets the board, you can use these records to train a value or a policy network.

## Citation

If these data were helpful for your research, please consider citing this repository.

```
@misc{joyce2023draughts,
  title={International Draughts Transcripts},
  author={Eric C. Joyce},
  year={2023},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/EricCJoyce/Datasets}}
}
```
