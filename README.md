# My Git Doc 👇🏻🔥🔥

## 0- What is git ❓
* Git is a version control system which allows us to protect and save our code on a server (local or external with github)

## 1- Git configuration 👇🏻
```bash 
# To add name and email👇🏻
git config --global user.name "Issa WebDev"
git config --global user.email "Issa WebDev"

# To config editor (code ==> vs code and --wait)👇🏻
git config --global core.ediator "code --wait"

# To open all config in vs code👇🏻
git config --global -e

# To display all config in cmd👇🏻
git config --glabal --list
git config --list
```

## 2- Git init and basic command line 👇🏻
```bash
# To initilize a new git repository (.git file)
git init

# To display (.git file)
ls -a

# To remove (.git file)
rm -rf .git

# To display the state of the repository
git status

# To add in staging area
git add text.txt
git add text.txt textall.txt
git add *.txt
git add .
git add --all

# To record
git commit
git commit -m "my first commit"
git commit -am "stage and commit at the same time"
``` 




