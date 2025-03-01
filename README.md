# git_command_list

1. cloning project from github
git clone https://github.com/....

2. update project
git add .  
git commit  -m "first update"
git push origin main   

3. create branch
git branch first_branch
git checkout first_branch  (switch to first_branch)

4. update branch
git add .  
git commit  -m "update branch"
git push origin first_branch

5. merge branch
git checkout main 
git pull
git checkout first_branch
git pull
git checkout main
git merge first_branch

- resolve conflict in code editor
git commit -m "resolve conflict"
git push origin main

