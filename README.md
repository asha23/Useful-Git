# Useful-Git

### General git setup

```
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://username:mypassword@github.com/asha23/repo.git
git push -u origin master
```

### Set up the username and password

```
git remote rm origin 
git remote add origin https://username:mypassword@github.com/asha23/repo.git
```
