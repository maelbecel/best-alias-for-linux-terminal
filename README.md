# Best alias for linux terminal 
shell script executing by curl cmd to implement a list of predefined alias in the current <b>root</b> .bashrc/.zshrc, to save time, when you rush your terminal. 

# Install and and auto configure 

## bash
```
sudo curl -sL https://raw.githubusercontent.com/archidote/best-alias-for-linux-terminal/master/run.sh | bash -s bash
```
## zsh
```
sudo curl -sL https://raw.githubusercontent.com/archidote/best-alias-for-linux-terminal/master/run.sh | bash -s zsh > /dev/null 2>&1
```
<br>

# Delete 
## bash
If you want to delete the aliases added my this project, run this command : 
```
sudo curl -sL https://raw.githubusercontent.com/archidote/best-alias-for-linux-terminal/master/delete.sh | bash -s bash
```
## zsh
If you want to delete the aliases added my this project, run this command : 
```
sudo curl -sL https://raw.githubusercontent.com/archidote/best-alias-for-linux-terminal/master/delete.sh | bash -s zsh > /dev/null 2>&1
```

<br>

# Update 

Delete, and re-run the inital setup with curl according to you shell family 
