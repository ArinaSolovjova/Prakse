## Nepieciešanās bibliotēkas (tested on ubuntu 20.04)

- texlive-bibtex-extra/focal,focal,now 2019.202000218-1
- texlive-extra-utils/focal,focal,now 2019.202000218-1
- texlive-lang-all/focal,focal,now 2019.20200218-1
- texlive-latex-extra/focal,focal,now 2019.202000218-1
- texlive-xetex/focal,focal,now 2019.20200218-1
- Pyhon2 `minted` package
- Times New Roman fonts

## Kompilācija

```sh
xelatex -synctex=1 -interaction=nonstopmode -file-line-error --shell-escape main.tex
```
