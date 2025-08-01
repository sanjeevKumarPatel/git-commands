# git-commands
<h1>Git Configuration</h1>
Git --version <br>
Git config -–global user.name “Sanjeev” <br>
Git config –-global user.email  “sanjeev@gmail.com” <br>
Git config –list <br>

<h1>Remote vs Local</h1>
remote means code on github<br>
local means code on our machine<br>

clone - Cloning a repository on our local machine<br>

git clone <- some link-><br>
status - displays the state of our code<br>
git status 

git commit  -m "Sanjeev first time update"
git add .
git push origin main


Remote setup

Git init
Git remote add origin < link >
Git remote -v (to verify remote)
Git branch  (to check branch)
Git branch -M Main (to rename br
Git push origin main
Git push -u origin Main ( next time we can write only git push , It will work )


Branch commands
Git branch
Git branch -M main (make main branch after the master branch)
Git checkout < branch name >
Git checkout -b <new branch name > to create new branch
Git branch -d < branch name > to delete any branch (If u are in the branch and want to delete the same branch then first you have to move in another branch then only you will be able to delete that branch)

Undoing changes

Staged changes

Git reset <file name>
Git reset


Git reset HEAD~1 (for one commit)

Commit changes for many commits

Git reset < commit hash >
Git reset –hard < commit hash >
