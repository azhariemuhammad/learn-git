# learn-git
## let's learn git basics today!
It's so much easy!


## Command GIT

// CONFIG
$ git config --global user.name "your_name"
$ git config --global user.email "your_email"

// untuk lihat config
$ git config --list

$ git add README.md atau git add .
$ git commit -m "your commit message"
//untuk lihat changes status:
$ git status
$ git push orgin master

// untuk buat file
touch index.html

// untuk buat folder
mkdir src


$ git branch feature/1
$ git checkout feature/1 // pindah ke branch yang baru dibuat
$ // tambahin files baru
$ git status
$ // push your code to remote

$ git checkout master
$ git status
$ git merge feature/1
$ git push ...

// on branch master
$ git branch -d feature/1