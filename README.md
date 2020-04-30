# RE:PLACE{{pkg.displayName}} (Atom package)

Converts the selected JS lines to string (single-line/concatenated).<br/>

### **CONCATENATED**<br/>
![RE:PLACE{{pkg.name}} demo convert concatenated](https://github.com/alexmunteanu/RE:PLACE{{pkg.name}}/blob/master/images/demo_convert_concatenated.gif?raw=true)

### **SINGLE-LINE**<br/>
![RE:PLACE{{pkg.name}} demo convert single-line](https://github.com/alexmunteanu/RE:PLACE{{pkg.name}}/blob/master/images/demo_convert_single-line.gif?raw=true)

## Installation
- ### Via **apm**
  ```sh
  apm install RE:PLACE{{pkg.name}}
  ```
- ### From **Atom**
  - `Settings` > `Install` > Search packages for `RE:PLACE{{pkg.name}}`.
  - Click `Install` and then `reload` Atom.
- ### From **GitHub**
  - Download the [latest release](https://github.com/alexmunteanu/RE:PLACE{{pkg.name}}/releases/latest) and extract the archive directly to `/users/YOUR_USERNAME/.atom/packages`.

## Usage
- Make a selection.
- Then do one of the following:
  - Press `Ctrl + Alt + Shift + S` on **Windows** or `Cmd + Alt + Shift + S` on **Mac**.
  - Right click and choose `RE:PLACE{{pkg.displayName}}`.
  - From Atom's menu: `Packages` > `RE:PLACE{{pkg.displayName}}` > `Convert`.

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
