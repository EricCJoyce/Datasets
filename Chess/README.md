## Transcripts from grandmaster chess matches, formatted for deep learning

One line is one (anonymous) match taken from various tournament transcripts. Moves follow the notation illustrated in REF.png. Moves alternate sides and are separated by spaces. Move indices are separated by hyphens. Pawn promotions are tripartite, with uppercase symbols for white and lowercase symbols for black, e.g. 50-58-Q. Castling is identified by king moves of more than one square, e.g. 4-6 for white kingside. Match results are separated from their move sequences by a tab. 1/2-1/2 means the game ended in a draw. 1-0 means white (side to move first) won. 0-1 means black won.

Note that there is no indication about why matches were ended. Some of these were timed games decided by the clock.

However your deep learning project interprets the board, you can use these records to train a value or a policy network.

## Citation

If these data were helpful for your research, please consider citing this repository.

```
@misc{grandmaster_chess_2020,
  title={Transcripts from Grandmaster Chess Matches Formatted for Deep Learning},
  author={Eric C. Joyce},
  year={2020},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/EricCJoyce/Datasets}}
}
```
