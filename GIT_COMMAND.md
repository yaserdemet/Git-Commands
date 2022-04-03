# Usefull Git Commands
![](https://www.hostinger.web.tr/rehberler/wp-content/uploads/sites/6/2017/05/github-kullanimi-basit-git-komutlari-1-768x478.png)
### _To check whether git is uploaded or not and introduce yourself to global_
1. `git --version`

 + `git config --global user.name "user name"`
 + `git config --global user.email "your email"`
 + `git config --global core.editor "your editor"`
 + `git config -list`

2. `git init`
 +  It will initialize the project folder into a git repository

3. `git status`
  * It will demonstrate situation of folders and files
4. `git add .`
  * It will add all your files to staging area. If you are to add only a file , you can just write file name instead of "."
5. `git commit -m "your commit message"`
  * It will save your changes in local repository. And make a point which can be backed in case of wanting

6. `git push`
  * This command will sent all changes which happen in your local repository to your Github account.
7. `git pull`
  * This command bring  all changes from Github repository to local repo.
8. `git log`
  * It will list all your commits history which have made until now.
9. `git log -n5`
  * If you want to check just last three commits use this usefull command.
10. `git log --oneline`
  * This command will show all commits in just a line.
11. `git branch "name"`
  * This command is used to create new branch in your local repository.
12. `git checkout branchname`
  * With this command you can move around your commits
  * You can make branch and checkout your new branch in same time via "git checkout -b feature" command
13. `git branch -D name`
  *  Delete branch
14. `git stash`
  * It is used to temporarily remove changes that you have made on working tree.
15. `git stash  pop`
  * This command is used to list your stashes that you have made.
16. `git diff ID1.ID2`
  * This command shows diffrences between two commits.
17. `git commit --amend -m`
 * If you want to change your commit message you can use this command 
 
:round_pushpin: [If you need more information about git commands, click here](https://git-scm.com/book/en/v2)
