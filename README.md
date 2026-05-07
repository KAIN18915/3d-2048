# 3D 2048

A fully functional **3D version of the 2048 puzzle game**, playable in your browser.

🎮 **[Play Now](https://kain18915.github.io/3d-2048/)**

## Features

- 4×4×4 three-dimensional board (4 layers)
- Smooth CSS 3D perspective rendering
- Mouse drag / touch to rotate the view
- Tile movement in all 3 axes (X, Y, Z)
- Score tracking with local storage best score
- Responsive and mobile-friendly

## Controls

| Key | Action |
|-----|--------|
| `←↑↓→` or `WASD` | Move tiles on active layer |
| `Q` / `E` | Move tiles between layers (Z-axis) |
| `Z` | Layer up (view) |
| `R` | Rotate view |
| `N` | New game |
| Mouse drag | Rotate 3D view |

## How to Play

1. Tiles move in the direction you push them on the **active layer** (highlighted).
2. Use `Q` and `E` to push tiles **across layers** in 3D.
3. Same numbers **merge** and double when they collide.
4. Reach the **2048** tile to win — but keep going for a higher score!

## Running Locally

Just open `index.html` in any modern browser — no build tools required!

```bash
git clone https://github.com/KAIN18915/3d-2048.git
cd 3d-2048
open index.html
```

## License

MIT
