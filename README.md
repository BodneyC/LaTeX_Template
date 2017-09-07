LaTeX Template
====

The purpose of this repository is to hold an ever-developing template for LaTeX projects; there is a preamble with packages I tend to use which are commented a little more neatly than I normally would.

The bulk of my TeX documents are imported using `\usepackage{import}` and exist in the folder `/texdocs/`, I have always done this and feel it is easier to manage the project in this way (particularly if it becomes a larger and more sectioned project).

Figures exist in `/figures/` and are included via:

```Tex
\usepackage{graphicx}
\graphicspath{ {./figures/} }
```

## Additional Information

- I am using TeX Live 2016 in Windows whilst making this template.
- This is by no means a guide on the use of Tex, if anyone is searching for that, [this](https://github.com/LewisVo/Begin-Latex-in-minutes) looks pretty good as a starter guide but I haven't actually used it.
