vim commands
---
by seyed ali hosseini
author:
  - 
    url: https://github.com/ali79hm
---
# start with vim
## open vim
we can open vim with one of this commands in console
```shell 
vim               # open vim
vim <fileName>    # open file with vim
vim -R <fileName> # open file with vim(read only)

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

 
