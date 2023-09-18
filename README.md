# Yodart Theme


[![IDE](https://img.shields.io/badge/IDE-VS_Code-purple)](https://img.shields.io/badge/IDE-VS_Code-purple)
[![Version](https://img.shields.io/badge/Version-1.0.1-blue)](https://img.shields.io/badge/Version-1.0.1-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Yodart Theme is a beautiful and customizable theme for Visual Studio Code that provides a pleasant coding experience. It is designed to be easy on the eyes and improve your productivity by making your code visually appealing.

## Installation

1. Launch Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
3. Search for "Yodart Theme" in the Extensions view search box.
4. Click the Install button to install the theme.
5. Once installed, click the gear icon in the lower-right corner of the window and select "Color Theme." Choose "Yodart Theme" from the list.

## Features

- Clean and elegant design.
- Carefully selected colors for syntax highlighting.
- Customized theme colors for improved readability.
- Support for various programming languages and file types.
- Continuously updated and maintained.

## Customization

You can customize the Yodart Theme to suit your preferences. To do so, follow these steps:

1. Open the command palette by pressing `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac).
2. Type "Preferences: Color Theme" and press Enter.
3. Select "Yodart Theme (Dark)" or "Yodart Theme (Light)" to activate the theme.
4. Modify the theme's settings in your `settings.json` file.

```json
{
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "keyword",
          "variable.language"
        ],
        "settings": {
          "foreground": "#ffcc00" // Your custom color
        }
      }
    ]
  }
}
