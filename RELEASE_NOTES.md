# Grandaku Master v1.0.2

Move-validation release.

## Changes

- Blocks illegal Sudoku moves before they are written to the board
- Rejects duplicate numbers in the same row
- Rejects duplicate numbers in the same column
- Rejects duplicate numbers in the same 3×3 block
- Incorrect solution guesses no longer remain on the board
- Rejected guesses still count toward the existing mistake limit
- Notes remain free-form so they can still be used as pencil marks

---

# Grandaku Master v1.0.1

Interface refinement release.

## Changes

- Removed keypad availability colour coding and greyed-out choices
- All number choices now remain fully visible and available
- Removed row, column, box and matching-number colour highlighting from the board
- Givens and entered numbers now use a consistent neutral visual treatment
- Restored the Hint button
- Hint fills the selected unsolved cell, or chooses an unsolved cell when necessary
- Increased ordinary cell borders to 2 px
- Increased 3×3 block boundaries to 5 px
- Retains the Grandaku Master World Champion celebration screen

---

# Grandaku Master v1.0.0

Initial named release of **Grandaku Master**.

## Included

- Grandaku Master branding across the browser title, PWA metadata and interface
- Easy, Medium and Hard Sudoku modes
- Notes / pencil mode
- Mistake tracking and timer
- Daily streaks
- Larger Sudoku digits
- Strong 3×3 block borders
- Custom soundtrack support
- Full-screen championship celebration on a completed puzzle
- Championship message: **You are the Grandaku Master World Champion**

Existing streak data from the earlier Grandoku-named build is migrated automatically.
