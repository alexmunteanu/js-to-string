# JS to string (Atom package)

Converts the selected JS lines to string (single-line/concatenated).

Concatenated

![js-to-string demo convert concatenated](https://raw.githubusercontent.com/alexmunteanu/js-to-string/master/images/demo_convert_concatenated.gif)

Single-line

![js-to-string demo convert single-line](https://raw.githubusercontent.com/alexmunteanu/js-to-string/master/images/demo_convert_single-line.gif)

## Installation

- Via **apm**

```sh
apm install js-to-string
```

- From **Atom**
  - `Settings` > `Install` \> Search packages for `js-to-string`.
  - Click `Install` and then `reload` Atom.
- From **GitHub**
  - Download the [latest release](https://github.com/alexmunteanu/RE:PLACE%7B%7Bpkg.name%7D%7D/releases/latest) and extract the archive directly to `/users/YOUR_USERNAME/.atom/packages`.
  - Run `npm install`.

## Usage

- Make a selection.
- Then do one of the following:
  - Press `Ctrl + Alt + Shift + S` on **Windows** or `Cmd + Alt + Shift + S` on **Mac**.
  - Right click and choose `JS to string`.
  - From Atom's menu: `Packages` > `JS to string` > `Convert`.

## Features

- **Auto-complete** selections:
  - the selection will be updated automatically so that the start and end lines are completely selected.
- **JS beautifier**:
  - the selected lines can be beautified before they're stringified.

## Options

- **String**:
  - `Style`: Choose between **single-line** or **concatenated**. Default: `concatenated`.
  - `Quotes`: Use **single** or **double quotes** to wrap the string. Default: `single`.
  - `Strip comments`: Generate the string without the commented-out lines. Default: `false`.
  - `Include whitespaces`: If this is unchecked, any tabs or new line characters will be stripped. Default: `true`.
  - `Add trailing character`: Insert a custom character after the quotes. Default: `true`.
  - `Trailing character`: The character that will be inserted at the end of the string, after the quotes. Default: `;`.
- **JS Beautifier**:
  - `Beautify`: The selected code will be first beautified before it's stringified. Default: `true`.
  - `Indent size`: Number of spaces used to represent a tab. Default: `2`.

## Buy me a beer

[![Donate](https://img.shields.io/badge/Donate-PayPal-success?style=for-the-badge&link=https://www.paypal.com/donate?hosted_button_id=Z8FGYYW9L28YC)](https://www.paypal.com/donate?hosted_button_id=Z8FGYYW9L28YC)
