## Courier Chess Transcripts

For all documents, one uncommented line is one match. Moves follow the notation illustrated in REF.png. Moves alternate sides and are separated by spaces. Move indices are separated by hyphens. Since all pawns must promote to queens, promotions receive no extra annotation. There is no castling in Courier Chess. Match results are separated from their move sequences by a tab. 1/2-1/2 means the game ended in a draw. 1-0 means gold (side to move first) won. 0-1 means black won.

`mcts.txt` was generated using Monte Carlo tree search.

`trueonlinetdl.txt` was generated during True Online TD(lambda) training.

`tdl.txt` was generated during TD(lambda) training.

However your deep learning project interprets the board, you can use these records to train a value or a policy network.

## Citation

If these data were helpful for your research, please consider citing this repository.

```
@misc{joyce2022courier,
  title={Courier Chess Transcripts},
  author={Eric C. Joyce},
  year={2022},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/EricCJoyce/Datasets}}
}
```
