Based on the HTML (RAILS) Syntax.

## Installation

* Install [SublimeERB](https://github.com/eddorre/SublimeERB#installation)

git clone git@github.com:eddorre/SublimeERB.git ~/.sublime_erb

ln -fs ~/.sublime_erb/erb_block.py ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User


[
  { "keys": ["ctrl+shift+."], "command": "erb", "context":
    [
      { "key": "selector", "operator": "equal", "operand": "text.html.ruby, text.haml, source.yaml, source.css, source.scss, source.js, source.coffee, text.html.eco" }
    ]
  }
]
