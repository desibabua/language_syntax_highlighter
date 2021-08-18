# Language syntax highlighter extension
It's a highly customizable VScode extension for syntax highlighting.
currently it's specified according to mal(make a lisp) language (unkown lisp lang).

## Getting started
1. Copy this folder inside ~/.vscode/extensions/
2. Add this code inside workspace's .vscode/settings
  ```
    "editor.tokenColorCustomizations": {
      "textMateRules": [
          {
              "scope": "language.boolean.mal",
              "settings": {
                  "foreground": "#5ad0f4"
              }
          },
          {
            "scope": "language.comments.mal",
            "settings": {
                "foreground": "#08b87e"
            }
        },
      ]
  }
```
3. Restart the visual studio code
