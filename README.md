Create New Repository from Command Line
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git.github.com:aileenbastos/projectname.git
git push -u origin main


Steps to Commit and Push
git add . (adds everything in the current project folder)
git commit -m "message" (commits and adds message about what you're committing)
git push (pushes changes to the repo)

Change Repo name in GitBash
$ git remote set-url origin git@github.com:aileenbastos/new_name.git
