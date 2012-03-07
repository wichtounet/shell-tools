Bash command line utilities
==========================

Replace in a set of files
-------------------------

> find . -name "*.hpp" -exec sed -i "s/ComposedValue/Expression/g" '{}' \;

Sort files by their number of lines
-----------------------------------

> wc -l src/*.cpp | sort -n -r | tail -n +2
