Bash command line utilities
==========================

Replace in a set of files
-------------------------

> find . -name "*.hpp" -exec sed -i "s/ComposedValue/Expression/g" '{}' \;

Sort files by their number of lines
-----------------------------------

> wc -l `find . -name "*.cpp"` | sort -n -r | tail -n +2

Find the top 15 longest files
-----------------------------------

> wc -l \`find . -name "*.cpp"\` | sort -n -r | tail -n +2 | head -n 15
