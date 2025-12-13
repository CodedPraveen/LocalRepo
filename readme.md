# 1. for git version chack

```
git --version
```

# 2. from Github repository to local computer

https code link

```
git clone https://github.com/CodedPraveen/Project.git
```

# 3. Use your Folder Direct / Terminal

here to ways First

```
code -r .\Project
```

and second enter

```
cd .\Project\ // "
```

to return use

```
"cd ..
```

<h4>before terminal
<br>
<h3> C:\Folder <br>
 <h4>after terminal<br>
<h3> C:\Folder\Project

# 4. Check Hidden File in Terminal

Mac

```
ls -a
```

Window

```
ls -Force
```

Git bash

```
dir -Force
```

# 5. Git Status

to see file update or modify

```
git status
```

# 6. add a File into Github repository

```
git add .\index.html
```

and also we use

```
git add .
```

and than

```
git commit -m "Add Index Files"
```

# 7. To see your code and Folder in Github repository

```
git push origin main
```

than link your VS Code to Github

# If You want Add New Folder using Terminal

```
mkdir New Folder
```

<br>
<br>
<br>
<h1>You Enter a Intermediate level
<h1>
Next how to your local folder add in Github repository

# 1. Git init

in your new folder terminal

```
git init
```

# 2. Make a New repository in Github Than in VS Code Terminal

like my Folder name Localrepository

```
 git remote add origin https://github.com/CodedPraveen/Localrepository.git
```

# 3. To verify Remote

Remote = github repository location link

```
git remote -v
```

# 4. Git Branch

```
git branch
```

rename branch

```
git branch -M main
```

To update repository

```
git push -u origin main
```

<h3> -u // chill (iski tension mat le)

<h2> You did it

# 5. If You Do Changes Than

```
git add .
```

```
git commit -m "I Do Changes in Index.html"
```

And see in Github repository to

```
git push
```

<h1> Finnaly How Workflow Looks

I. Github repository<br>
II. Clone in VS Code<br>
III. Make Changes<br>
IV. Git add .<br>
V. Commit<br>
Vi. push to see in repository

Another Topic

# 1 Git Branch

Default branch is main and See Branch

```
git branch
```

# 2. Create and Switch Branch

```
git checkout -b branch1
```

# 3. Switch

```
git checkout main
```

# 4. Delete Branch

```
git branch -d branch1
```

# 5. To See Branch in Github Follow Step

make changes in any file file

```
git add .
```

```
git commit -m "What Changes"
```

```
git push origin branch1
```

# 6. See Changes

```
git diff main
```

# 7. Merging Code

If You Went To Merge
Way 1

```
git merge branch1
```

Way 2 <br>
Create a new Pull Request in Github and merge <br>
How to create pull request first repeat # 5 and Go to Github and see compare & pull request and Done it. <br>
So in VS Code main branch you see not code update than we do :-

```
git pull origin main
```

# 8. Resolving Merge Conflicts

First merge code <br>
if not branch change so first change it

```
git merge branch1
```

VS Code suggest what kind of change you keep than select what type of you went and than repeat # 5 <br>
refresh your github repository

<h4>chack out both branch and push request <br>

```
git checkout branch1
```

```
git push
```

<h1>
You are Going to Master Level

# 1 Undoing changes

Case 1: Staged Changes
<br>
if we delete code and add it and only remain to commit

```
git reset branch1
```

Case 2 : Commit Changes ( for one commit )

```
git reset HEAD~1
```

Case 3 : Commit Changes ( for many commit )<br>
commit hash = in the ( git log ) commit number 
```
git reset <-commit hash->
```
for pure delete
```
git reset --hard <-commit hash->
```

Check commit history and find commit number

```
git log
```


# 2. Fork (Rough Copy)
Go to Github and search what we want to copy and when you go on search repository than click on fork and you make it. copy !
```
Bye Bye
```