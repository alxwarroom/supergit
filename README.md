# Supergit

Supergit is a powerful tool that enhances the git workflow by providing additional functionalities and automation. It simplifies common git tasks, improves collaboration, and boosts productivity.

## Usage

Clone supergit repository, copy git-push to your project root directory, use it.
```
git clone https://github.com/warroom17/supergit.git
cp supergit/git-push path/to/my/root/project
cd path/to/my/root/project
git alias gpush "message to commit"
```

## FEATURES WANTED:

### 1 - Optionally add files to be stage
The user should choose files to stage and commit. eg: ```gpush text1.txt text2.txt```

### 2 - Optionally update readme
The user should be able to optionally update his readme file.
The usage will be like: ```gpush "commit message" -r```
- This script should open REAME.md | readme.md in terminal
- Optionally add text after the -r option to append to readme file. 

### 3 - Create an installation script, install.sh
The user should easily install and use supergit on any directory without coping the git-push script.
Installing supergit with install.sh will be like:

```
git clone https://github.com/warroom17/supergit.git
cd supergit
chmod u+x install.sh
./install.sh
gpush "use and replace this quote with commit message anywhere"
```

### 4 - Gpush --amend
The user should commit with --amend option before push
Usage: ```gpush --amend``` or ```gpush -a```

### 5 - Make directories
The user should be able to make directories easily with the command mk.


## Contributors
- No commits on main branch
- Create a branch for every feature you are working on
- Pull requests most be reviewed by two members before merging to main branch
- Codes should be neatly organized and indented
