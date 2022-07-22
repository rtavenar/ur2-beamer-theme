# Thème Beamer Université de Rennes 2

Ceci est un thème [LaTeX Beamer](https://www.overleaf.com/learn/latex/Beamer) utilisant des éléments visuels de la charte graphique de l'Université de Rennes 2. Il est dérivé du [thème non-officiel de Jonkping University](https://github.com/JonkopingAI/ju-beamer-theme).

## Quickstart

1. **Copiez le contenu** du répertoire `sty/` dans votre projet Beamer.

3. **Sélectionnez le thème** dans votre présentation Beamer via `\usetheme{metropolis-ur2}`.

4. **Compilez avec LuaLaTeX** (or XeLaTeX) pour que les polices de caractères soient correctes ! Je recommande l'utilisation  
   de `latexmk` avec le fichier de configuration `latexmkrc` fourni copié dans votre répertoire de travail.

### Options \& Features

La [**présentation fournie en exemple**](./example.pdf) dans ce dépôt introduit les différentes options du thème.

## Examples

<img alt="Title slide from example.pdf" title="Title slide" src="https://github.com/rtavenar/ur2-beamer-theme/raw/main/slide_title.png" width="360" height="270"> <img alt="Section title slide from example.pdf" title="Example slide" src="https://github.com/rtavenar/ur2-beamer-theme/raw/main/slide_sectiontitle.png" width="360" height="270">

<img alt="Slide with code from example.pdf" title="Example slide" src="https://github.com/rtavenar/ur2-beamer-theme/raw/main/slide_code.png" width="360" height="270"> <img alt="Slide with blocks from example.pdf" title="Example slide" src="https://github.com/rtavenar/ur2-beamer-theme/raw/main/slide_blocks.png" width="360" height="270">


## Dépendances

Les packages TeX suivants sont utilisés :

- beamer
- tikz
- pgfopts
- etoolbox
- calc
- ifxetex
- ifluatex
- biblatex
- appendixnumberbeamer
- adjustbox
- booktabs
- fontawesome5
- graphicx
- hyperref
- minted
- tabularx
