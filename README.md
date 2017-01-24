# Enki Theme
A color scheme and UI theme for **Sublime Text** with clear, disparate colors to help differentiate between all syntactic aspects of code, including syntax highlighting for the console.

The UI theme itself is a **modified version** of
[@equinusocio's](https://github.com/equinusocio) amazing work,
[Material Theme](https://github.com/equinusocio/material-theme) and
[Material Theme Appbar.](https://github.com/equinusocio/material-theme-appbar)
Specifically, the overall UI colors have been changed in Material App Bar and Material Theme to better align with this color scheme.

<a href="http://kuuv.io/i/r2upwyz.png" target="_blank">
    <img src="http://kuuv.io/i/r2upwyz.png" alt="Preview" width="890">
</a>

Alternate color scheme:

<a href="http://kuuv.io/i/arkOGsr.png" target="_blank">
    <img src="http://kuuv.io/i/arkOGsr.png" alt="Preview" width="890">
</a>

Aster color scheme:

<a href="http://kuuv.io/i/pdPQizy.png" target="_blank">
    <img src="http://kuuv.io/i/pdPQizy.png" alt="Preview" width="890">
</a>

<a href="http://kuuv.io/i/3w2eucU.png" target="_blank">
    <img src="http://kuuv.io/i/3w2eucU.png" alt="Preview" width="890">
</a>



Light color scheme and UI theme:

<a href="http://kuuv.io/i/03N444z.png" target="_blank">
    <img src="http://kuuv.io/i/03N444z.png" alt="Preview" width="890">
</a>


## Installation
1. Download the package

    **Preferred Method:** With [Package Control](https://packagecontrol.io/installation) installed, open the command palette and type `install package` and search for `Enki Theme.`

    *Alternate Method:* [Download](http://github.com/enkia/enki-theme/archive/master.zip) or clone this repo into `Sublime Text 3/Packages` and rename the folder to 'Enki Theme'

2. Open preferences and change the color scheme and theme lines:

```json
"color_scheme": "Packages/Enki Theme/scheme/Enki.tmTheme",
"theme": "Enki-Theme.sublime-theme",
```

#### Alternate Dark Color Scheme

A color scheme for those who prefer something less purple:

```json
"color_scheme": "Packages/Enki Theme/scheme/Enki-Alt.tmTheme",
```

#### Aster Color Scheme

A color scheme for those who prefer fewer colors:

```json
"color_scheme": "Packages/Enki Theme/scheme/Enki-Aster.tmTheme",

// red instead of green:
"color_scheme": "Packages/Enki Theme/scheme/Enki-Aster-red.tmTheme",
```

#### Light Color Scheme and UI Theme:

A color scheme and UI theme for those who prefer something lighter:

```json
"color_scheme": "Packages/Enki Theme/scheme/Enki-Light.tmTheme",
"theme": "Enki-Theme-Light.sublime-theme",
```


## Options
Because this is essentially Material Theme, it comes packed with many of the same options as the original and one additional option:

```json
"enki_theme_color_expanded_folder": true, // Set expanded folder in sidebar to accent color
                                          // If no accent color is specified, it simply gets brighter

"enki_theme_bold_tab": true, // Bold tab labels
"enki_theme_compact_panel": true, // Compact panel
"enki_theme_compact_sidebar": true, // Compact side bar
"enki_theme_disable_fileicons": true, // Disable file icons
"enki_theme_disable_folder_animation": true, // Disable folder animation
"enki_theme_disable_tree_indicator": true, // Disable active file indicator
"enki_theme_panel_separator": true, // Panel Separator
"enki_theme_small_statusbar": true, // Smaller Status Bar
"enki_theme_small_tab": true, // Smaller tabs
"enki_theme_tabs_autowidth": true, // Automatically adjust width of tabs
"enki_theme_tabs_separator": true, // Add separator in between tabs
"enki_theme_tree_headings": true, // Show sidebar tree headings
```

Color options:

```json
  "enki_theme_accent_samon": true,
  "enki_theme_accent_bluegray": true,
  "enki_theme_accent_fuschia": true,
  "enki_theme_accent_white": true,
  "enki_theme_accent_green": true,

  "enki_theme_accent_lime": true,
  "enki_theme_accent_purple": true,
  "enki_theme_accent_pink": true,
  "enki_theme_accent_red": true, // Changed to a deeper shade
  "enki_theme_accent_orange": true,
  "enki_theme_accent_indigo": true,
  "enki_theme_accent_teal": true,
  "enki_theme_accent_blue": true,
  "enki_theme_accent_cyan": true,
  "enki_theme_accent_yellow": true,
```


<img src="http://kuuv.io/i/ulKbDfQ.gif" alt="Preview Accents" width="305">


Options to mimic the screenshot:

```json
  "enki_theme_accent_red": true, // or white for Light theme
  "enki_theme_compact_sidebar": true,
  "enki_theme_panel_separator": true,
  "enki_theme_small_statusbar": true,
  "enki_theme_small_tab": true,
  "enki_theme_tabs_autowidth": true,
  "enki_theme_tree_headings": false,

  "overlay_scroll_bars": "enabled",
  "line_padding_bottom": 2,
  "line_padding_top": 2,
  "bold_folder_labels": false, // or remove this line if you set it to true for Material Theme
  "always_show_minimap_viewport": true,
  "indent_guide_options": ["draw_normal", "draw_active"],
  "font_options": ["gray_antialias", "subpixel_antialias"], // for retina Mac & Windows
```

## Plugins
UI Plugins shown in screenshot:

* [Color Highlighter](https://packagecontrol.io/packages/Color%20Highlighter)
* [BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter)

## Iterm Color Schemes
Get schemes [here.](https://github.com/enkia/enki-theme/tree/master/iterm)

## Notes
* **Ruby developers:** Try removing Ruby Slim package if syntax appears muddled.
* **SCSS/SASS developers:** This theme is best used with the [SCSS - TextMate SCSS Official Bundle](https://packagecontrol.io/packages/SCSS) because the Sass package has fewer syntax definitions to work with. Unfortunately, it's no longer maintained. Feel free to download [my fork](https://github.com/enkia/SCSS.tmbundle) where I've made a few necessary updates.
* **Javascript developers:** This theme is best used with the [newly updated (see build 3114 notes)](https://www.sublimetext.com/3) default Javascript syntax definitions or the ones from the [Babel](https://packagecontrol.io/packages/Babel) package.
* **Color Scheme palettes:**
  [Color Palette 1,](http://colorpeek.com/#3f414d,425c7c,6d3b66,8d4d85,a966a9,d57cd5,d93232,c33c4a,ff435b,eb606b,d24d57,f99157,fac863,ca9b55,dbc08a,1abc9c,50b4dc,6189bb,7ba1d0,83aada,afbad4,e5e5e5)
  [Color Palette 2](http://colorpeek.com/#3f414d,425c7c,455682,62758b,1abc9c,65dec2,d93232,c33c4a,ff435b,eb606b,d24d57,f99157,fac863,ca9b55,dbc08a,1abc9c,50b4dc,6189bb,7ba1d0,83aada,afbad4,e5e5e5)
* **Font:** [Input](http://input.fontbureau.com/)


## Issues / Requests / Contributions
#### Color Scheme:
* If a syntax definition doesn't appear to be supported, please [submit an issue.](http://github.com/enkia/enki-theme/issues)
* Use the supplied YAML file for use with [PackageDev](https://packagecontrol.io/packages/PackageDev) if you'd like to contribute to the *color scheme.*

#### Theme:
Despite this being a modified version of the Material Theme, please submit UI issues here as a bug may have been introduced when modifying Material Theme.

This will be updated with all major bug fixes released by
[equinusocio](https://github.com/equinusocio) for
[Material Theme](https://github.com/equinusocio/material-theme) and
[Material Theme Appbar](https://github.com/equinusocio/material-theme-appbar)
but understand that since this is not the original UI theme, these updates will not occur immediately.

*Note:* There is **[a known issue](https://github.com/equinusocio/material-theme#known-issues)** that may affect some people that prevents one from seeing the bottom panel's input box upon installation. Fix it by resizing the bottom panel:

<a href="http://kuuv.io/i/etF8rY0.gif" target="_blank">
    <img src="http://kuuv.io/i/etF8rY0.gif" alt="Preview" width="890">
</a>


