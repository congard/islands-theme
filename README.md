# Islands Theme

JetBrains-inspired Visual Studio Code theme. My goal is not to map the JetBrains theme 1-to-1, but rather create a comfortable theme with familiar colors.

The Islands theme is based on [zed-theme-jetbrains](https://github.com/artemevsevev/zed-theme-jetbrains.git).

> [!NOTE]
> Go support is the first priority; other languages will be added in the future.

![Go](images/vsc-golang.png)

Font: [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono)
<br>Icons: [JetBrains New UI File Icon Theme Extended](https://marketplace.visualstudio.com/items?itemName=fogio.jetbrains-file-icon-theme)

## Build

This project is a Visual Studio Code theme extension. It can be built and packaged into a `.vsix` installable using the VS Code CLI.

### Prerequisites

- [Node.js](https://nodejs.org/)
- [VS Code](https://code.visualstudio.com/)

### Install dependencies

```bash
npm install
```

### Package

```bash
npm run package
```

### Install locally

```bash
code --install-extension ./islands-theme-0.0.1.vsix
```