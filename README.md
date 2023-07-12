# supergit

Git add, commit and push in one command + Common git usage patterns in one comand

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
The user should choose files to stage and commit. eg: gpush text1.txt text2.txt

### 2 - Optionally update readme
The user should be able to optionally update his readme file.
The usage will be like: ```git push "commit message" -r```
- This script should open REAME.md | readme.md in terminal
- Optionally add text after the -r option to append to readme file. 

### 3 - Create an insallation script, install.sh
The user should easily install and use supergit. Add install.sh script.
Installing supergit with install.sh will be like:

```
git clone https://github.com/warroom17/supergit.git
cd supergit
./install.sh
gpush "use and replace this quote with commit message anywhere"
```


## Contributors
- No commit on main branch
- Create a branche for every feature you are working on.
- Pull requests most be reviewed by two members before merging to main branch
