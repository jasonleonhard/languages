### `graphviz` show a directed graph of many programming languages

## Install required software

    brew install graphviz

## Download or access this file: diagram.dot

    curl -s http://rigaux.org/language-study/diagram.html > diagram.dot

## Create .png from .dot or .gv

    dot -Tpng -O diagram.dot

## Rename as just .png

    mv diagram.dot.png diagram.png

## Open

    open diagram.png

![](https://github.com/jasonleonhard/languages/blob/master/diagram.png?raw=true)

## This would be enough but ....

## Create svg version

    dot -Tsvg diagram.dot -o diagram.svg

## For ease I have added this svg to our markup

![](./diagram.svg?raw=true)

### NOTE: you can search an svg with cmd-f

# Example: cmd-f `Rust`

You will find 1 instance

# example: cmd-f `bash`

You will find 3 instances

This makes it easier to find any language in the graph as there are several nodes

Hope you've enjoyed!
