# Hecaton rover sprites

White background keyed out (flood fill from borders, alpha=0), 600x600 RGBA.
The base art faces WEST as drawn, so:

- `rover_w.png` = original orientation (faces west)
- `rover_n.png` = rotated 90 CW (faces north/up)
- `rover_e.png` = rotated 180 (faces east/right)
- `rover_s.png` = rotated 90 CCW (faces south/down)

Generated with PIL from `Hecaton.png`. Use with Graphics1300 `Sprite` stretched to the cell size.
