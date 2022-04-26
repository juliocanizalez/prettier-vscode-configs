# Prettier / VScode Configurations

Configurations applied:

### For `d365`:

settings.json (VS Code):

```json
{
    "editor.tabSize": 4,
    "editor.formatOnSave": false
}
```

.prettierrc

```json
{
    "trailingComma": "es5",
    "tabWidth": 4,
    "semi": true,
    "singleQuote": true,
    "endOfLine": "lf"
}
```

### For `personal`:

settings.json (VS Code):

```json
{
    "editor.tabSize": 2,
    "editor.formatOnSave": true
}
```

.prettierrc

```json
{
    "trailingComma": "es5",
    "tabWidth": 2,
    "semi": false,
    "singleQuote": true,
    "printWidth": 120,
    "quoteProps": "consistent",
    "jsxSingleQuote": true,
    "bracketSpacing": true,
    "bracketSameLine": false,
    "arrowParens": "avoid",
    "endOfLine": "lf",
    "singleAttributePerLine": true
}
```
