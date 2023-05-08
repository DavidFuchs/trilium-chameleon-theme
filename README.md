# trilium-chameleon-theme

A set of light and dark colour themes for Trilium.

Chameleon: A custom colour theme for Trilium. (https://github.com/DavidFuchs/trilium-chameleon-theme)
 
These light and dark themes makes liberal use of variables and relative brightness calculations to provide a theme that's both easy on
the eyes, and very simple to adjust to your preference. Accent colors, text colors, and background colors are all easily adjustable.
 
By default, the themes use a teal colour that I happen to like. But you can change the accent everywhere simply by modifying the variable
called `--palette-accent-hue` to a different number between 0 and 359. Red is 0, for example. Accent, text and background brightness can be similarly adjusted using variables:

```
  --palette-accent-hue: 185;
  --palette-accent-brightness: 40%;
  --palette-text-brightness: 70%;
  --palette-background-brightness: 20%;
```
 
# Installation

Installation instructions can be found at the top of the theme CSS files.

# Preview Images

![](https://github.com/DavidFuchs/trilium-chameleon-theme/raw/main/preview-dark.png)
![](https://github.com/DavidFuchs/trilium-chameleon-theme/raw/main/preview-light.png)

## Alternate Previews

These screenshots were taken after modifying the value of `--palette-accent-hue`.

### `--palette-accent-hue=20`:

![](https://github.com/DavidFuchs/trilium-chameleon-theme/raw/main/preview-dark-alternate.png)

### `--palette-accent-hue=320`:

![](https://github.com/DavidFuchs/trilium-chameleon-theme/raw/main/preview-light-alternate.png)