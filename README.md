huge thanks to d8vela / pymol_scripts

# step 1: link .pymolrc anywhere else (aka home dir) to this pymolrc file
ln -s ~/scripts/python_scripts/pymol_scripts/pymolrc .pymolrc

# step 2: set up alias in bashrc 
alias pymol="/Applications/MacPyMOL.app/Contents/MacOS/MacPyMOL $1"
alias bam='pymol -d bam'

# step 3: how to set up paths "/path/to/home/scripts/python_scripts/pymol_scripts" 

add new pml scripts to pymolrc lines
add python scripts into pymol_scripts followed by reference in --init--pymol doc
