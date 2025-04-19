# TERMINAL COMMANDS

- List directory (-la to show hidden folders and files, -color highlight folders)
``` bash
    ls -la --color 
```

- Change directory
``` bash
    cd <path>
    cd <folder-name>
    cd ../
```

- Create folder
``` bash
    mkdir <folder-name>
```

- Remove folder
``` bash
    rmdir <folder-name>
    rm -rf <folder-name>
```

- Create file
``` bash
    touch <file-name.ext>   
```

- Remove file
``` bash
    rm <file-name.ext>
```

- Clear terminal
``` bash
    clear
    cls
```

- Display working directory
``` bash
    pwd
```

# GIT COMMANDS

- Set user and user email
``` bash
    git config --global user.name "Umutcan Ekinci"
    git config --global user.email "umutcannekinci@gmail.com"
```

- Display username and user email
``` bash
    git config user.name
    git config user.email
```

- Initialize repository. (Before initializing be sure that the repository is not initialized by checking status.)
``` bash
    git init
```

- Display the status
``` bash
    git status
```

- Track the file to commit it later (Working Directory -> Index - Staging)
``` bash
    git add <file>
    git add . (add all files)
```

- Commit (Index - Staging -> Local Repository)
``` bash
    git commit -m "<commit-message>"
```

- Add all files and commit 
``` bash
    git commit -a -m "<commit-message>"
```

- Shows the past commits.
``` bash
    git log
```

## .GITIGNORE FILE
- Add file
<file-name>

- Add all files with extension
*.<extension> 