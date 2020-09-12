## Match transcripts from the [American Checker Federation](http://www.usacheckers.com), formatted for deep learning

All matches adhered to ACF rules (e.g. if a jump is possible, then you must jump).

One line is one (anonymous) match taken from the ACF archives. Moves follow the notation illustrated in REF.png. Moves alternate sides and are separated by spaces. Move indices are separated by hyphens. Sequences of more than one jump share intermediate indices, meaning aa-bb-cc is read as "The piece at aa jumps to bb, then from bb to cc." Match results are separated from their move sequences by a tab. 1/2-1/2 means the game ended in a draw. 1-0 means Red (side to move first) won. 0-1 means White won.

However your deep learning project interprets the board, you can use these records to train a value or a policy network.
