# helasuno README

This is a basic extension for the Helasuno language for Visual Studio Code.

Features:
* Syntax highlighting support.
* Snippet support for each implemented statement, often accessible via the first two letters of each statement.

### Snippets
| Snippet Command | Output |
|----|----|
| co | [auto line number] - [empty space for comment] |
| end | [auto line number] end |
| ge | [auto line number] get [empty space for variable name] = "[empty space for prompt]" |
| ju | [auto line number] jump [empty space for line number] |
| pa | [auto line number] pause [empty space for pause length] |
| se | [auto line number] set [empty space for variable name] = "[empty space for prompt]" |
| wr | [auto line number] write "[content to write]" |
| wl | [auto line number] writeln "[content to write to a line]" |

Special thanks to:
- the official Batch File TextMate grammar for number support [here](https://github.com/microsoft/vscode/blob/main/extensions/bat/syntaxes/batchfile.tmLanguage.json).
- Olaf Neumann's Regex Generator [here](https://regex-generator.olafneumann.org/)

## Release Notes

### 1.0.0

Initial release of the extension. This is still in development so do not consider this stable yet.
