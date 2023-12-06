Please note these settings and extension recommendations are almost exclusively centered around using vscode for front-end work.

### Colour theme

Recommended colour theme for typescript:

```
{
    "workbench.colorTheme": "Atom Material Theme"
}
```

To compensate with some of the colours from this theme clashing with the default git colours, I recommend adding:

```
{
    "workbench.colorCustomizations": {
        "list.warningForeground": "#FFC0CB" // So warning doesn't mix with git modified
        "scollbarSlider.background": "#696969" // Normal theme too inivsible
    }
}
```

### Recommended ESLINT plugins

To complement the fix all being set true we can make the most out of this by adding:

- [simple import sort](https://www.npmjs.com/package/eslint-plugin-simple-import-sort)
- [unused imports](https://www.npmjs.com/package/eslint-plugin-unused-imports)
