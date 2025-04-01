<p align="center">Catppuccin Marp Theme</p>

## Usage

1. Get [Marp](https://marp.app/#get-started)
2. Under markdown, import `catppuccin-{flavour}.theme`.

> Example in vscode, you can add to `setting.json`

```json
{
    // etc...
    "markdown.marp.themes": [
      "https://raw.githubusercontent.com/crsct/catppuccin-marp/master/css/catppuccin-macchiato.css",
    // if raw.githubusercontent.com not work, try use this
      "https://rainbowflesh.github.io/css/rosewater-teal.css",
    ]
    // etc...
}
```

then add to markdown file:

```markdown
---
marp: true
theme: catppuccin-macchiato
# theme: rosewater-teal-dawn
# theme: rosewater-teal-moon
---
```
