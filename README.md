# permpatts.sty

A latex class for permutation patterns.

Required LaTeX packages (:
- [`stmaryrd`](https://www.ctan.org/pkg/stmaryrd?lang=en)
- [`amsmath`](https://www.ctan.org/pkg/amsmath?lang=en)
- [`xinttools`](https://www.ctan.org/pkg/xinttools?lang=en)
- [`tikz`](https://www.ctan.org/pkg/pgf?lang=en)
- [`mathabx`](https://www.ctan.org/pkg/mathabx?lang=en)

## Installation
### For pros
Clone this repository into the correct place in your `texmf` tree.

or 
### For noobs
Symlink the base directory of this repository into your `texmf` tree in the `tex/latex` directory.
The location of your `texmf` can be found using the command `kpsewhich -var-value=TEXMFHOME`.

The following commands will create the required directories if they do not exist and link the
repository, assuming you are in the base directory of the repository.

```bash
mkdir -p `kpsewhich -var-value=TEXMFHOME`/tex/latex
ln -s `pwd` `kpsewhich -var-value=TEXMFHOME`/tex/latex/permpatts
```
---
You may be required to install some extra packages into your TeX distribution.
Req

## Usage

In your latex document use `\usepackage{permpatts}` in the preamble.