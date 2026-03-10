# nyu-colors

Python package providing [NYU brand color](https://www.nyu.edu/employees/resources-and-services/media-and-communications/nyu-brand-guidelines/designing-in-our-style/nyu-colors.html) constants and a `Color` enum.

## Installation

Install directly from GitHub:

```
pip install https://github.com/nyumathclinic/nyu-colors/archive/refs/heads/main.zip
```

## Usage

### Module-level constants

Each NYU brand color is available as a hex string constant:

```python
from nyu_colors import NYU_VIOLET, TEAL, MAGENTA

print(NYU_VIOLET)   # "#57068c"
print(TEAL)         # "#009b8a"
print(MAGENTA)      # "#fb0f78"
```

### Color enum

All colors are also accessible through the `Color` enum:

```python
from nyu_colors import Color

print(Color.NYU_VIOLET.value)    # "#57068c"
print(Color.ULTRA_VIOLET.value)  # "#8900e1"
```

## Available colors

| Color | Name | Hex |
|-------|------|-----|
| ![NYU Violet color swatch](https://placehold.co/20x20/57068c/57068c.png) | `NYU_VIOLET` | `#57068c` |
| ![Ultra Violet color swatch](https://placehold.co/20x20/8900e1/8900e1.png) | `ULTRA_VIOLET` | `#8900e1` |
| ![Medium Violet 1 color swatch](https://placehold.co/20x20/702b9d/702b9d.png) | `MEDIUM_VIOLET1` | `#702b9d` |
| ![Medium Violet 2 color swatch](https://placehold.co/20x20/7b5aa6/7b5aa6.png) | `MEDIUM_VIOLET2` | `#7b5aa6` |
| ![Light Violet 1 color swatch](https://placehold.co/20x20/ab82c5/ab82c5.png) | `LIGHT_VIOLET1` | `#ab82c5` |
| ![Light Violet 2 color swatch](https://placehold.co/20x20/eee6f3/eee6f3.png) | `LIGHT_VIOLET2` | `#eee6f3` |
| ![Deep Violet color swatch](https://placehold.co/20x20/330662/330662.png) | `DEEP_VIOLET` | `#330662` |
| ![Black color swatch](https://placehold.co/20x20/000000/000000.png) | `BLACK` | `#000000` |
| ![Dark Gray color swatch](https://placehold.co/20x20/404040/404040.png) | `DARK_GRAY` | `#404040` |
| ![Medium Gray 1 color swatch](https://placehold.co/20x20/6d6d6d/6d6d6d.png) | `MEDIUM_GRAY1` | `#6d6d6d` |
| ![Medium Gray 2 color swatch](https://placehold.co/20x20/b8b8b8/b8b8b8.png) | `MEDIUM_GRAY2` | `#b8b8b8` |
| ![Medium Gray 3 color swatch](https://placehold.co/20x20/d6d6d6/d6d6d6.png) | `MEDIUM_GRAY3` | `#d6d6d6` |
| ![Light Gray color swatch](https://placehold.co/20x20/f2f2f2/f2f2f2.png) | `LIGHT_GRAY` | `#f2f2f2` |
| ![White color swatch](https://placehold.co/20x20/ffffff/ffffff.png) | `WHITE` | `#ffffff` |
| ![Magenta color swatch](https://placehold.co/20x20/fb0f78/fb0f78.png) | `MAGENTA` | `#fb0f78` |
| ![Teal color swatch](https://placehold.co/20x20/009b8a/009b8a.png) | `TEAL` | `#009b8a` |
| ![Blue color swatch](https://placehold.co/20x20/59b2d1/59b2d1.png) | `BLUE` | `#59b2d1` |
| ![Yellow color swatch](https://placehold.co/20x20/f4ec51/f4ec51.png) | `YELLOW` | `#f4ec51` |

## License

Copyright 1831–2026 New York University. All Rights Reserved.
