# JS to string (Atom package)

Converts the selected JS lines to string (single-line/concatenated).<br/>

### **CONCATENATED**<br/>
![js-to-string demo convert concatenated](https://github.com/alexmunteanu/js-to-string/blob/master/images/demo_convert_concatenated.gif?raw=true)

### **SINGLE-LINE**<br/>
![js-to-string demo convert single-line](https://github.com/alexmunteanu/js-to-string/blob/master/images/demo_convert_single-line.gif?raw=true)

## Installation
- ### Via **apm**
  ```sh
  apm install js-to-string
  ```
- ### From **Atom**
  - `Settings` > `Install` > Search packages for `js-to-string`.
  - Click `Install` and then `reload` Atom.
- ### From **GitHub**
  - Download the [latest release](https://github.com/alexmunteanu/js-to-string/releases/latest) and extract the archive directly to `/users/YOUR_USERNAME/.atom/packages`.

## Usage
- Make a selection.
- Then do one of the following:
  - Press `Ctrl + Alt + Shift + S` on **Windows** or `Cmd + Alt + Shift + S` on **Mac**.
  - Right click and choose `JS to string`.
  - From Atom's menu: `Packages` > `JS to string` > `Convert`.

## Features
- **Auto-complete** selections:
  - the selection will be updated automatically so that the start and end lines are completely selected
- **JS beautifier**:
  - the selected lines are beautified automatically before they're stringified

## Options
- **String**:
  - `Style`: Choose between **single-line** or **concatenated**. Default: `concatenated`
  - `Comma`: Use **single** or **double commas** to wrap the string. Default: `single`
- **JS Beautifier**:
  - `Indent size`: Number of spaces used to represent a tab. Default: `2`
