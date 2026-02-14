# Quick Start: Developing Royal Pine

## How to run locally
1. Open this folder in VS Code.
2. Press `F5` to open a new **Extension Development Host** window.
3. In the new window, change the theme to **Royal Pine** to see your changes in real-time.

## Project Structure
- `package.json`: The manifest file that links the theme and icons.
- `royal-pine-color-theme.json`: The main file where you change colors.
- `README.md`: The marketplace description.

## How to Package
To create a `.vsix` file for manual installation:
1. Run `npm install -g @vscode/vsce`
2. Run `vsce package`
3. Drag the resulting `.vsix` into your VS Code Extensions view.