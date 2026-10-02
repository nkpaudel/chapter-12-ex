create a new repository on the command line
echo "# chapter-12-ex" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nkpaudel/chapter-12-ex.git
git push -u origin main

push an existing repository from the command line
git remote add origin https://github.com/nkpaudel/chapter-12-ex.git
git branch -M main
git push -u origin main

it remote -v
origin  https://github.com/nkpaudel/chapter-12-ex.git (fetch)
origin  https://github.com/nkpaudel/chapter-12-ex.git (push)


git branch -r 

detach head: git checkout main <Reverse to Root/main/head>

working with colaboration:
Refresh from master (Fatching/pulling)
