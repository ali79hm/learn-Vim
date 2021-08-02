vim commands
---
by seyed ali hosseini

  - 
    github: https://github.com/ali79hm
---
# start with vim
## open vim
we can open vim with one of this commands in console
```shell
#in console
vim               # open vim
vim <fileName>    # open file with vim
vim -R <fileName> # open file with vim(read only)
#in vim editor
:edit <filename>  # edit a file 
:edit <tab>       # List the files for editing
```
## exit from vim

```shell 
:q <enter>    # exit the vim 
:w <enter>    # save existing file 
:wq <enter>   # save the existing file and exit 
:q! <enter>   # save and discard changes
```

## see line numbers

```shell
:set number   # show line numbers
```
# vim tabs and windows
## tabs
```shell
:tabnew             # Open new tabVim
:tabnew <filename>  # Open new file in tab
:tabclose           # Close current tab
:tabnext            # Move to the next tab
:tabprevious        # Move to the previous tab
:tabfirst           # Move to the first tab
:tablast            # Move to the last tab
```
![example of vim tabs](picture/vim-tabs.png "example of vim tabs")
## windows
```shell
:new                //Open new window
:new <filename>         //Open file in new window
```
for switch between windows press ```ctrl```+```w``` twice (in command mode!)

![example of vim windows](picture/vim-windows.png "example of vim tabs")
# vim mods
### command mode
vim opens in command mode By default but if you switched to other modes you can go to command mode by pressing
```ecs```
on keyboard 

### insert mode
for editing text you should go to insert mode 

press ```i``` on keyboard for going to insert mode

# vim help
```shell
:help
:help <topic-name>
:helpgrep <phrase> # if, you don’t know the exact name of help topic
```
![example of vim help](picture/vim-help-modes.png "example of vim help")


# navigation

## navigate between lines
 
```shell
:<n>  # go to nth line (replace n with number)
:0    # go to start of file
:$    # go to end of file
```

## navigate in lines

```shell
$     # go to end of line
0     # go to beginning of line
w     # Move cursor to the beginning of the next word
e     # Move cursor to the end of the current word
b     # Move cursor to the end of the current word
```

