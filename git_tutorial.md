# JSM MASTERY COURSE


```bash
git config user.name 'Maryanne'
git config user.email 'maryanneinyang@gmail.com'
```

# initialize a new repo and change branch name to main
```bash
git init
git config --global init.defaultBranch main
```

# how to check for files that aren't being tracked
```bash
git status 
```
# to track files you made changes to

```bash
git add <filename> or
git add . (for all untracked files)
```


# now to commit(like creatiing a whole new copy of your project, this is what is creating the actual new versions/checkpoints of your project)

- the -m flag is for message 
  
```bash
git commit -m 'initial commit'
```

# to see the history of all commits created
```bash
git log
```

# how to restore your project to a previous project
```bash
git checkout <commit-hash gotten from git log command>
```
# to delete changes made in the detached head state (when you rolled back to a previous commit)

-f flag means force
```bash
git checkout -f main
```

# remote repository is basically your repo on the internet and to link it you have to create an empty repo on github and then push your local repo up there

origin is basically an alias for your remote repo's link, like a variable for it

```bash
git remote add orgin <https link or ssh link>
```
# now to pussh your code to github you use
now were using orgin instead of the repo link to push to main 
```bash
git push -u origin main
```

# Branching
this allows you to make different copies of your project without affecting the original project, so that everyone can work independently without affecting the orginal code and you can merge it with the original when you're done 

Now to create a new branch and enter it 
```bash
git branch js_feature
git checkout js_feature
```
now a shortcut to create and enter your new branch automatically is 

```bash
git checkout -b js_feature1
```

when you create a new branch it will be based on the branch you're currently on, so if youre in a bug branch and you create a new branch your new beanch will be based on that bug branch instead of your main project branch. So in that case you can just do so that your new b
```bash
git branch <new-branch> <source-branch>
```
## im adding this for js_feature branch
```bash```
```bash```
```bash```
```bash```
```bash```
```bash```
