- Here is several git tricks learning from Linkedin Courses
- `git stash` save changes locally but not commit now, usually using `git stash save "message"` to make easy to search
- `git stash pop` restore changes before and delete from list
- `git stash apply` apply most recent stash but not delete it from list
- `git stash list` check stash history

- `git add -p` check every file when adding file to stage before commit, useful than just `git add .`
- `git push <origin> <branch>` always do so to make sure push to the right remote respository and right branch

- `git reset --soft HEAD~1` restore the stage to before commit

- `git log --oneline` check log in brief
- `git log --graph --oneline` check log in visualized way

- `git commit --amend` overwritting commit by amend something

- using `.` to enter dev stage in github, useful!!! (must login)