# Git Command Line Guidelines

**ALWAYS PULL BEFORE STARTING WORK ON A REPO. If you aren't up to date with the repo and make changes and then try to push them up to GitHub you're going to have a bad time. AKA merge conflicts**

**_Here's how you pull down everything from the repo_**
```
git pull origin master
```

After completing what you're working on, run these 3 commands to push your work up to the repo. _(You must be in the root folder of the project you're working on in order to run these commands.)_

1. `git add .` This will add all the files you worked on to then run the next command
2. `git commit -m 'YOUR COMMIT MESSAGE'` Write whatever you want the commit message to be inside the quotes
3. `git push origin master` This is the command that will push everything you've worked on up to GitHub so that others can then pull down what you've done to their local environment.
