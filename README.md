通用人工智能之梦：从大语言模型开始
============================
## build
1. textlive 2022 and vscode and vscode plugin: LaTeX Workshop.
2. vscode settings. find`latex-workshop.latex.tools`,change `latexmk` to :
```json
    "latex-workshop.latex.tools": [
        {
            "name": "latexmk",
            "command": "latexmk",
            "args": [
                "-xelatex",
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%"
            ],
            "env": {}
        }, 
        //...
    ]
```
