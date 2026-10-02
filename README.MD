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

git fetch (fetching allows us to download change from a remote repository, but those change will not be automatically integrated into our working files. It lets you see what others have been working on, without having to merge those change into your local repo)
git fetch origin main

git pull: is use to retrieve changed form a remote repository. unlike fetch, pull actually updates our HEAD branch with whatever changes are retrieved form the remote.

git pull = git fetch + mgit merge
