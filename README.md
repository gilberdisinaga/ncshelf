# ncstack
ncstack is a file organizing utility for books (or anything, by modifying the file opener and some dialog's texts in order to avoid confusion). It has stack conception in mind wherein the books are arranged vertically, but recent books are inserted below the previous books instead of otherwise (could be rearranged manually in its specified menu).

## Demo
![](demo.gif)

## Dependencies
* dialog, sed, awk, grep
* zsh
* zathura (for reader, could be changed by editing the script)

## Setup
1. Git clone this repo
2. Empty the content of text files in `texts` directory
3. Edit `ncstack`'s default directory for adding books (line 35) for easy navigation
4. Run the script like any other shell script (using dot-slash prefix (./ncstack) on the directory where the repo is or placing it (`texts` and `ncstack`) on local bin directory)
5. Add some books
6. Enjoy, then!
