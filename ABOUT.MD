# ABOUT ME - mace

> I WANNA GRADUATE BY 2027 OR 2028
>> I WANNA GO HOOOOOOOOOOOME ;-;

**STEPS**
1. Make the project as local reposition / storage
```bash
git init
git config --global user.name "Aijix"
git config --global user.email "mariaclarice.madrid@lorma.edu"
```
--
## Prepare changes to be saved locally in the remote repository
```bash
git add .
```
---
## Finalize or Commit/make last changes to make a save point
```bash
git commit -m "Description"
```
--
## Rename branch `master` to `main`
```bash
git branch -M main
```
--
2. Create a remote repo in Github
// open github
    > click from left side > create new repository 


3. Connect both repo so they
## Link local repo to remote repo
```bash
git remote add origin <gitHubLink> 
// https://github.com/Aijix/dev-mace.git
```

## Delete currently logged in accs
```bash
> to check who is currenty logged in on ur acc:
git credential-manager github list      
// git credential-cache exit
```

# Push or upload our changers
```bash
git push -u origin main
```

