# Config for Baseline Theme
[Cupertino](https://github.com/aaaaalexis/obsidian-cupertino) doesn't play nice with custom CSS. It's itself a styled fork of [Baseline](https://github.com/aaaaalexis/obsidian-baseline), so custom CSS against it usually doesn't work as it uses `!important` in its tweaks.

Baseline, however, is a reliable base theme and supports custom theming just fine. I have found it to work well on both Mac and iOS, thus serving as a robust default theme on all platforms. I'm styling Baseline with the minimal style settings defined in `baseline_style_settings.json`, which are mostly from the [MacOS Tahoe](https://aaaaalexis.github.io/obsidian-baseline/marketplace/) style from the Baseline marketplace.

On Mac, I'm using:
- `base_styles.css`: Set of theme agnostic styling.
- `catppuccin_syntax.css`: Catppuccin syntax highlighting for code blocks.
- `colored_folders.css`: Monochromatic color set for folders.
- `dark_theme_colors.css`: Color variables for a simple dark theme, similar to Flexoki.

On iOS, I'm additionally using:
- `sidebar_styles.css`: Styling the left/right side bars.
