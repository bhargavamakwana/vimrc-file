![GitHub last commit](https://img.shields.io/github/last-commit/bhargavamakwana/vim-tutorials)
![GitHub repo size](https://img.shields.io/github/repo-size/bhargavamakwana/vim-tutorials)

# Jump start with VIM 

## Install and set up plugins

On your terminal run the following commands to install and setup VIM:


`chmod +x setup.sh`
<br>
`./setup.sh`

## Vim most essential commands

Often more than not, people who tend to hate vim are either reluctant to learn and memorize the commands, largely because that seems too much and in other cases there is no proper documentation about it. 

It is **highly recommended** to go through the help manual from the vim. It has all the essential commands, from beginner to advanced. However, some commands are already described below, which are used most frequently while coding.



1. `:tabnew` starts a new tab with specified file or an empty file if not specified.
2. `:tabn` switches to a new tab.
3. `:split` does a horizontal split of the screen. woth the same file or with different file if specified. 
4. `:vsplit` works same like split except does a horizontal split. 
5. `c` is a cut specifier which can be later used with `w` or other commands. Note the command after execution directs user into insert mode. 
6. `C` deletes a current line and directs you to insert mode. 
7. `^` is used to send cursor to the start of the line. 
8. `$` sends the cursor to the end of the line.
9. `A` appends like `a` but at the end of the current line.
10. `m + [letter] ` bookmarks a line with that letter. ` ' + [letter]` can be used to navigate to that line later. Can be used while working with big code where you want to locate to same function evry time you open a file.
11. `<<` or `<j` is used to ident to the left.  
12. `>>` or `>j` is used to ident to the right.
13. `==` or `=j` is used to properly ident. 
14. `~` is used to change the case of the character under cursor.
