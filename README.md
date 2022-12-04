# pep-explorer.github.io
An easy to use online explorer for Python Enhancement Proposals

[See Online](https://tonybaloney.github.io/pep-explorer/)


## Updating the index

The index is automatically updated by github actions every day 5:30 o'clock. In case you nevertheless want to update it, do:

(1) The pep/ directory is a git submodule for the actual PEP repository on Github

```bash
cd peps
git pull --rebase
cd ..
python3 genindex.py
```

(2) Then serve locally via:
```bash
python3 -m http.server
```

## Contributions

Contributions welcome! I am not a web designer, the page looks pretty basic!
