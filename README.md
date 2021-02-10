# `graphviz` show a directed graph or tree

## Install required software

    brew install graphviz

## Download or access this file: diagram.dot

    curl -s http://rigaux.org/language-study/diagram.html > diagram.dot

## Create .png from .dot or .gv

    dot -Tpng -O diagram.dot

## Open

    open diagram.dot.png

[REF](https://davebucklin.com/play/2018/06/29/timeline-of-programming-languages.html)
