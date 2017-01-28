
# Update vim pathogen

This script it used to update all your pathogen plugins for vim.

## Installation

This script use wget and git, so for using this script install git and wget :
```
sudo apt-get install git wget
```

## How to use it

### Simple use

```
updateVimPathogen
```

For each folder in folder of vim pathogen plugins (~/.vim/bundle), it performs a git pull

### Option List

#### Verbose

```
updateVimPathogen -v
```

Explain what is being done 

#### Update current directory

```
updateVimPathogen -c
```
Update current folder, just performs a git pull

#### 
