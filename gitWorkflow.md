Git Workflow:<br />
Git Add<br /> 
Git commit -m<br />
Git pull --rebase upstream DEV<br />
Git push origin master (or DEV depending what branch your on in YOUR fork)<br />

How to initially create upstream:<br />
git remote add upstream https://github.com/GreenFieldofDreams/GreenFieldOfDreams.git<br />


To Pull Down Changes:
Git stash  (this stashes your local changes so you can reapply them)
Git pull upstream --rebase dev  (or whatever the branch name you want)