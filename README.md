echo "#project" >>README.md
git init
git add README.md
git branch -m main
git commit -m "first commit"
git remote add origin https://github.com/gptcs/project.git
git push -u origin master
