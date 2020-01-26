# UIUC Beamer Theme
A simple beamer theme with a UIUC color scheme.

## Installation

Like other themes, this can be installed by copying the `uiuc` directory into your
![equation](https://latex.codecogs.com/pdf.latex?\inline&space;\large&space;\LaTeX)
installation folder. The precise folder depends on your
![equation](https://latex.codecogs.com/pdf.latex?\inline&space;\large&space;\LaTeX)
distribution.

## Usage

After installation, the theme can be applied by adding the following line to your `.tex` file below the document class
definition.

```text
\documentclass{beamer}
\usetheme{uiuc} % Apply theme to beamer presentation
...
```

The `uiuc` theme has the following options:

- `progress` - makes the page footer a progress bar.

Options to the theme can be applied by augmenting the theme declaration,

```text
\usetheme[option]{uiuc}
```

For example, the following will activate the `progress` option which makes the footer act as a progress bar.

```text
\usetheme[progress]{uiuc}
```

## Useful definitions

The theme also defines certain useful colors, abiding by
[Illinois's color standard](https://www.uillinois.edu/OUR/brand/color_palettes).
These colors are:

| | Name | Description |
| --- | --- | --- |
| ![UIblue](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-2767.png) | `UIblue` | Primary "U of I Blue" |
| ![UIblueSub](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-2728.png) | `UIblueSub` | Secondary accent blue for subheaders and points of interest |
| ![UIblueBold](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-2738.png) | `UIblueBold` | Secondary accent blue for knockout headers and overall mood |
| ![UIneutralLight](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-427.png) | `UIneutralLight` | Lightest neutral tone |
| ![UIneutralMedium](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-cool_gray6.png) | `UIneutralMedium` | Medium neutral tone |
| ![UIneutralDark](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-cool_gray10.png) | `UIneutralDark` | Darkest neutral tone |
| ![UrbanaOrange](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/campus-uc-orange.png) | `UrbanaOrange` | Urbana-Champaign orange accent color |
| ![UIteal](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-accent-teal.png) | `UIteal` | Teal accent color |
| ![UIgrayBlue](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-accent-cornflower.png) | `UIgrayBlue` | Gray-blue accent color |
| ![UIcitron](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-accent-citron.png) | `UIcitron` | Citron accent color |
| ![UIdarkYellow](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-accent-dkyellow.png) | `UIdarkYellow` | Dark-yellow accent color |
| ![UIsalmon](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-accent-salmon.png) | `UIsalmon` | Salmon accent color |
| ![UIperiwinkle](https://www.uillinois.edu/UserFiles/Servers/Server_1240/Image/img/palette-accent-periwinkle.png)  | `UIperiwinkle` | Periwinkle accent color |
