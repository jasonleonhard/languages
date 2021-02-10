# `graphviz` show a directed graph or tree

## Install required software

    brew install graphviz

## Download or access this file: diagram.dot

    curl -s http://rigaux.org/language-study/diagram.html > diagram.dot

## Create .png from .dot or .gv

    dot -Tpng -O diagram.dot

## rename as just .png

    mv diagram.dot.png diagram.png

## Open

    open diagram.png

![](https://github.com/jasonleonhard/languages/blob/master/diagram.png?raw=true)
