# Back to the Code

## VSCode theme inspired by Back to the Future from a fan driving at 88mph 🚗 ⚡️

![Downloads](https://img.shields.io/vscode-marketplace/v/divyanshu013.back-to-the-code-vscode-theme.svg)
![Downloads](https://img.shields.io/vscode-marketplace/d/divyanshu013.back-to-the-code-vscode-theme.svg)
![Downloads](https://img.shields.io/vscode-marketplace/r/divyanshu013.back-to-the-code-vscode-theme.svg)

![Back to the Code Cover image](./assets/back-to-the-code-cover.jpg)

An easy on eyes gorgeous theme so you can always get **Back to the Code**.

## Installation

Find the theme on marketplace here or fire up the command palette with <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> and enter:
```
ext install back-to-the-code-vscode-theme
```

## Preview

![alt](./assets/back-to-the-code-ss.png)
![alt](./assets/back-to-the-code-ss2.png)

## My Coding Environment

- **OS** Ubuntu 16.04 (with [Numix](http://www.noobslab.com/2017/08/install-numix-theme-and-icons-in.html))
- **Primary font** [Fira Code with ligatures](https://github.com/tonsky/FiraCode)
- **Secondary font** [Flott Flott](https://www.google.co.in/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwj0yrecovPWAhUC6Y8KHcmTCSMQFggnMAA&url=https%3A%2F%2Fwww.dafont.com%2Fflottflott.font&usg=AOvVaw1bM3uloP1gLcvFInvJnAIg)
- **Customizations** [VS Code custom CSS plugin](https://github.com/be5invis/vscode-custom-css). Add the snippet to render the secondary font correctly and hide the feedback icon on VSC v1.17.1

```css
.mtki {
  font-family: 'flottflott';
  font-style: normal;
  font-weight: 400;
  font-size: 1.6em;
}

.send-feedback.mask-icon {
  display: none;
}

.statusbar-item.right.__CUSTOM_CSS_JS_INDICATOR_CLS .octicon.octicon-paintcan {
  display: none;
}
```

- **Import Cost** [Get the plugin](https://github.com/wix/import-cost) and add the following in VS Code user settings (<kbd>Ctrl</kbd> + <kbd>,</kbd>)

```json
"importCost.smallPackageColor": "mediumspringgreen",
"importCost.mediumPackageColor": "mediumspringgreen",
"importCost.largePackageColor": "coral"
```

## Bugs and Issues

Found an issue with the theme? Does it look weird with some particular code snippet? No worries, please report an [issue](https://github.com/divyanshu013/back-to-the-code/issues) with the snippet and a screenshot and I'll get back to it :grin:

## Bonus Content

- [Back to the Code Wallpaper 1](https://divyanshu013.deviantart.com/art/Back-to-the-code-wallpaper-dark-709931130)
- [Back to the Code Wallpaper 2](https://divyanshu013.deviantart.com/art/Back-to-the-code-wallpaper-709932529)
- [Color Palette Inspiration](https://i.imgur.com/z24sojs.jpg)

## License

MIT