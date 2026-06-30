# Zed LALRPOP highlight

Small [Zed](http://zed.dev) extension that enables LALRPOP DSL syntax highlighting in Zed.

Heavily based on the existing [tree-sitter grammar](https://github.com/traxys/tree-sitter-lalrpop).


## Installing

[Following the guide](https://zed.dev/docs/extensions/developing-extensions#developing-an-extension-locally): 

1. Clone the repo
2. In Zed: Open the "Extensions" menu and click "Install Dev Extension" (top-right)
3. Select the folder of the repo (i.e `<path>/<to>/lalrpop-highlight`).

If you don't get an error, the extension should appear in your _installed_ section, and `*.lalrpop` files should automatically be highlighted.
