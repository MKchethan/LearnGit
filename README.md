To create virtaul environment 
```bash
pip install virtualenv 
python -m virtualenv rolex 
cd rolex
cd scripts
activate 
```

To download all the requirements
```bash
pip install -r requirements.txt
```


**Learn Git**

For initialising git
```bash
git init
```

For Configuration 
```bash
git config --global user.name "MKchethan"
git config --global email.name "chethanmudbasallar@gmail.com"
```

To check the status --> Tells whether we have a new file or not anything modified there
```bash
git status
```

To add our files and commit to our repository
```bash
git add README.md
git commit -m "The first commit"
```

To know the braches in the repo and to change name from master to main
```bash
git branch
git branch -M main
```

To add to our origin file
```bash
git remote add origin https://github.com/MKchethan/LearnGit.git
git push origin main
```

To restore the file, not to do changes from the previous commit 
```bash
git restore README.md
```

To add the files in the directory all at one time
```bash
git add .
git commit -m "The second commit"
git push origin main
```

To get clone from the repo to our local 
```bash
cd d:\cmk\gitForClone
d:
d:\gitForClone>git clone https://github.com/MKchethan/LearnGit.git
```

To restore
```bash
git restore --staged "New File.txt"
--- or
git reset "New File.txt"
```

To know difference of what is changed but not staged
```bash
git diff
```

To know difference of what is staged but not commited
```bash
git diff --staged
```

To create new branch with name developer in our local repository
```bash
git branch developer 
```

To get switched to new branch
```bash
git checkout developer
```

To merge the specified branch history into the main branch 
```bash
git checkout main
git merge developer
git push origin main
```

To see all the commits and the last three commits 
```bash
git log
git log -p -3
```




