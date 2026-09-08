# Schotter

A small generative art sketch inspired by Georg Nees' *Schotter*.

The program draws a grid of squares. Near the top, the squares are orderly. As
they move down the page, their position and rotation become more chaotic.

## How to run

```bash
python sketch.py
```

On Windows, this may also be:

```bash
py sketch.py
```

The script creates `sketch.svg`, which can be opened in a browser.

## Parameters

The main controls are near the top of `sketch.py`:

- `SEED` changes the random pattern.
- `COLS` and `ROWS` change the grid size.
- `CHAOS` changes how strongly the squares drift and rotate.
