# ECO Platform API guide

[This notebook](./notebook.ipynb) shows how you can use the ECO Platform API

## Build notebook

This is how you can convert the notebook to **markdown**, **html** and **python**

```bash
jupyter nbconvert --to markdown notebook.ipynb 
jupyter nbconvert --to html notebook.ipynb
jupyter nbconvert --to python notebook.ipynb 
```

and **latex** version:

```bash
wget https://github.com/jgm/pandoc/releases/download/2.19.2/pandoc-2.19.2-1-amd64.deb
sudo dpkg -i pandoc-2.19.2-1-amd64.deb
sudo apt update
sudo apt install texlive-xetex texlive-fonts-recommended texlive-latex-extra
jupyter nbconvert --to latex notebook.ipynb
xelatex notebook.tex
```

### License

This notebook is under the [MIT](./LICENSE) license
