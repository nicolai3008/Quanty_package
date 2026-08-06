# Quanty for VS Code

Syntax highlighting for [Quanty](http://quanty.org/) (`.qty`) scripts.

## Install

- **From source:** open this folder in VS Code, press `F5` to launch a dev host, open a `.qty` file.
- **From VSIX:** `vsce package`, then Extensions view → `...` → **Install from VSIX...**

## Structure

```
package.json                    # manifest
language-configuration.json     # brackets, comments
syntaxes/quanty.tmLanguage.json # highlighting rules
```

To add more highlighted keywords, edit `quanty-builtins` in the grammar file. Use **Developer: Inspect Editor Tokens and Scopes** to debug.

## License

MIT
