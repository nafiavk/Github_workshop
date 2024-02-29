---

# Git and Github

## 

Git is a  locally stored platform which has a versioning system

Github 

To initialise git

git init

git add filename

To commit ( Consider why, how, effects, limitations while writing the meaningful message)

git commit -m "meaning ful message"

Things to take care:

- Dont do double `git init`

- dont move any sub folder out of the folder unless not required further

## Conceptual areas (Developing area, staging area and Local repository)

- Developing area: In the system, where the file is developed (pwd)

- .git ( is a local repository where all the updates are saved)

- staging area

git config --list  

git config --global user.name "Nafia"

git config --global

git status       ( to see the status of files {to be staged,to be committed, untracked})

to be staged: You have committed it before, made changes later and git recognise the new changes are not yet `add` not `commit`

to be committed: You have committed it before, made changes later and git recognise the new changes as `add` not `commit`

untracked: Is a complete new file has never `add` not `commit`

Just writing few lines to commit without a message

git log

git status : check in what conceptual area my file/folder is

git log: show the history of commits/ show all that you have saved in yoiur local repository/ shows you in the terminal what ugit shows in an interface

-`git log -n N`

-`git log --abrevv-commit`

-`git log --help`

git show:  shows the commits that you asked for comparison

-`git show id1 id2`

git diff: show the difference between, line by line with commit ids

-`git diff id1 id2`

README.txt

.gitignorev
