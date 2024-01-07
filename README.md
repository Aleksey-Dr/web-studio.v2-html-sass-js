# [WEB STUDIO](https://aleksey-dr.github.io/web-studio.v2-html-sass-js/)

#### [Aleksey-Dr](https://github.com/Aleksey-Dr)

## Technologies
[![Technologies](https://skillicons.dev/icons?i=html,css,sass,js)](https://skillicons.dev)
[![Tools](https://skillicons.dev/icons?i=github,git,vscode,figma)](https://skillicons.dev)
___
### Additional settings
#### Settings [VSCode](https://code.visualstudio.com/)
Install the [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass) extension to work with [Sass](https://sass-lang.com/).

> [!TIP]
> Base settings for Live Sass Compiler (json):

```
"liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    },
    {
      "extensionName": ".min.css",
      "format": "compressed",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.excludeList": ["**/node_modules/**", ".vscode/**"],
  "liveSassCompile.settings.generateMap": true,
  "liveSassCompile.settings.autoprefix": ["defaults"]
```