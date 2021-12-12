# URV TFG Template

A base document written in **LaTeX** following the design guides of URV for the _**T**reball de **F**inal de **G**rau_.

It's also available as a template in [**Overleaf**](https://www.overleaf.com/latex/templates/urv-tfg-template/fmwwrpjwdwtq).


## Structure

```
URV-TFG-Template
├── anot.bib             # bibliography file
├── config.tex           # basic configuration for the template
├── .gitignore
├── imgs                 # images folder
│   └── ...
├── main.tex             # document entry point
├── post-preamble.tex    # configuration post \begin{document}
├── preamble.tex         # configuration pre \begin{document}
├── readme.md            # this file
├── sections
│   ├── abstract.tex     # page for the abstract in the 3 languages
│   ├── bibliography.tex # bibliography page
│   ├── examples.tex     # file with LaTeX examples
│   ├── index.tex        # index page
│   └── titlepage.tex    # title page
├── var_def.tex
└── .vscode
    └── settings.json    # 'LaTeX Workshop' extension settings for VSCode
```
## How to use it
Modify the `config.tex` to setup the variables (author name, project title, director name, ...) and the default language of the project.

It's recommended to create the new sections as new files un the sections folder to maintain the structure, although it's not enforced.

