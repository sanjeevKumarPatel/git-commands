# git-commands
<br><h1>Git Configuration</h1>
<br>Git --version <br>
<br>Git config -–global user.name “Sanjeev” <br>
<br>Git config –-global user.email  “sanjeev@gmail.com” <br>
<br>Git config –list <br>
<br>
<br><h1>Remote vs Local</h1>
<br>remote means code on github<br>
<br>local means code on our machine<br>
<br>
<br>clone - Cloning a repository on our local machine<br>
<br>
<br>git clone <- some link-><br>
<br>status - displays the state of our code<br>
<br>git status 
<br>
<br>git commit  -m "Sanjeev first time update"
<br>git add .
<br>git push origin main
<br>
<br>
<br>Remote setup
<br>
<br>Git init
<br>Git remote add origin < link >
<br>Git remote -v (to verify remote)
<br>Git branch  (to check branch)
<br>Git branch -M Main (to rename br
<br>Git push origin main
<br>Git push -u origin Main ( next time we can write only git push , It will work )
<br>
<br>
<br>Branch commands
<br>Git branch
<br>Git branch -M main (make main branch after the master branch)
<br>Git checkout < branch name >
<br>Git checkout -b <new branch name > to create new branch
<br>Git branch -d < branch name > to delete any branch (If u are in the branch and want to delete the same branch then first you have to move in another branch then only you will be able to delete that branch)
<br>
<br>Undoing changes
<br>
<br>Staged changes
<br>
<br>Git reset <file name>
<br>Git reset
<br>
<br>
<br>Git reset HEAD~1 (for one commit)
<br>
<br>Commit changes for many commits
<br>
<br>Git reset < commit hash >
<br>Git reset –hard < commit hash >
<br>