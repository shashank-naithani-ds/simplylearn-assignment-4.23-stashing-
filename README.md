# 4.23 Assingment Stashing
<br>
Stashing is like leaving you current work and saving that state, so that you can come later to work on it. <br> <br>

<b>Problem</b>
create a banch and edit a file that you inherited from master branch. Make a commit in that branch before you commit a second time, stash it away. <br>

Switch to master branch and craete a new branch and apply the stash in that newly created branch. then <br>
return to the first branch and apply the stash again, and the delete that stash entry. <br>

<b>Solution</b> <br> <br>

- create a repo with initial files <br>
- now edit changes in file. <br>
- add to stagging area #git add . <br>
- commit files $ git commit -m "message" <br>
- now create a branch $ git branch [name] or git checkout -b [name] <br>
- now do some changes and commit the file <br>
- now edit some changes and stash the state by $ git stash <br>
- go to the main branch and apply stash to the same file $ git stash apply <br>
- clear stash by $ git stash clear
