# this is is trial file
git config --global user.name 'Zhennn'
git config --global user.email 'doreen950215@gmail.com'
git init
git status #檢查檔案狀態
git add README.md
git add re<tab>
git add .
git commit -m 'add new file and modufied'
git log
#add something
git log --online
        git diff <version.num> -- <file.name>
example:git diff 40fabf5 -- README.md

git checkout <version.num> -- <file.name>
eg git checkout 40fabf5 -- README.md
git reset --hard <version.num>
git reset --soft <version.num>

new file name = supplementary.md
.gitignore
new items