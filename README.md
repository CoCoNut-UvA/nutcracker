# NutCracker - CoCoNut DSL Syntax Highlighting extension for VS Code
This Visual Studio Code extension adds syntax highlighting support for
CoCoNut DSL code, normally contained in `.ccn` files. CoCoNut is a compiler
framework, which is primarily used in the Compiler Construction course at the
University of Amsterdam: https://github.com/CoCoNut-UvA/coconut

## Installation
There are two options to install NutCracker:
- Copy the extension into the `<user home>/.vscode/extensions` folder and
  restart Code.
- Install it from the Extensions Marketplace: TBA

## Known Issues
Since the current syntax highlighting is implemented using textmate grammars,
the parsing is somewhat limited. This means that in some cases, especially
newlines in the middle of a definition, the code isn't styled properly.

*The solution for this would probably be implementing an actual language server.
Feel free to contact me if you're interested in aiding with developing this.*

## Development
Pull requests are always welcome!

To develop this addon, it is useful to open up this repo in VS Code. You can
then simply press `F5` to open a new VS Code window with the extension loaded.

### Useful links - CoCoNut
- https://coconut-uva.github.io/coconut/dsl_syntax.html
- https://github.com/CoCoNut-UvA/coconut/blob/master/cocogen/frontend/scanAndParse/dsl-parser.y
- https://github.com/CoCoNut-UvA/coconut/blob/master/cocogen/frontend/scanAndParse/dsl-lexer.l

### Useful links - TextMate grammars
- https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide
- https://macromates.com/manual/en/language_grammars
- https://www.apeth.com/nonblog/stories/textmatebundle.html
