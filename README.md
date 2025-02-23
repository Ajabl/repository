GIT notes:

 1184  git status
 1185  git add *
 1186  git commit -m "Add file"
 1187  git status
 1188  git log
 1189  git status
 1190  git diff file01.py
 1191  git add -A
 1192  git status
 1193  git commit -m "Add/Modify files"
 1194  git status
 1195  git add file01.py file02.py file03.py
 1196  git status
 1197  git add *
 1198  git status
 1199  git commit -m "Add/Modify/Delete"
 1200  git log
 git branch
git branch feature/git-commit-workflow
git branch
git checkout feature/git-commit-workflow
git status
git add git-commands.md
got commit -m "Dodano polecenia: status,add,commit"
git commit -m "Dodano polecenia: status,add,commit"
git status
git log
git status
git add git-cheat-sheet-education.pdf
git commit -m "Dodano cheatsheet z githuba"
git checkout main
git branch feature/git-log-and-config
git status
git branch
git checkout feature/git-log-and-config
git status
git add git-commands.md
git commit -m "Dodano polecenia; config,log"
git checkout feature/git-commit-workflow
git checkout feature/git-log-and-config
git branch
git checkout main
git branch release/v1.3-rc1
git checkout release/v1.3-rc1
git branch
git merge feature/git-commit-workflow
git log
git branch
git merge feature/git-log-and-config
git status
git commit -m "Conflict resolved"
git log
git checkout main
git merge release/v1.3-rc1
git branch
git branch -d
git branch -d feature/git-log-and-config feature/git-commit-workflow
git branch -d release/v1.3-rc1

1. Stwórz branch na podstawie main o nazwie: release/rc1
2. "Zmerguj" do niego zmiany z feature/A oraz feature/B. Rozwiąż konflikty, jeżeli się pojawią.
3. "Zmerguj" release/rc1 do main. Rozwiąż konflikty, jeżeli się pojawią.
4. Usuń niepotrzebne branche po pomyślnym merge do main.
git log
git checkout -b feature/branch-test
git add main.py
git commit -m "Chaned main.py"
git log
git reset --hard 1d2d78ebdbaa04fbf23919a16ab9bdef726b71a4
git status
git add main.py
git commit -m "Add function"
git add main.py
git commit --amend -m "Added missing add_values"
git log
