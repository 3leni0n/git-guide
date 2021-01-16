# Commands
* **git init**  
  Initialize repo in cd (note appearance of hidden .git folder)  
* **git add .**  
  Register all changes since last git commit or git init and prepare them for commit. It's like taking  the 
  files up to a stage before taking a pic  
* **git reset .**  
  Revert all changes added. It's like asking the files to come down the stage because they aren't ready for the pic  
* **git commit -m "<<message>message>"**  
  Commit the changes. Take the pic
* **git checkout -- .**  
  Reconstruct committed files to the previous commit  
* **git log**  
  Get list of past commits  
* **git commit --amend**  
  Fix last commit comment  
* **git checkout -b <<branch>branch>**  
  Create new branch from last commit  
* **git branch**  
  Show current branch from branches  
* **git checkout <<branch>branch>**  
  Go to specified branch  
* **gir merge <<branch>branch>**  
  Merge specified branch with master/main  
* **git branch -d <<branch>branch>**  
  Delete specified branch  
* **git branch -M main**  
  Create/change name (not sure)? to main branch  
* **git remote add origin https://github.com/user/repo.git**  
  Add remote via HTTPS or  
**git remote add origin git@github.com:user/repo.git**  
  Add remote via SSH  
* **git push -u origin <<branch>branch>**  
  Send changes to specified branch in remote repo

# Flags
--all: include all new, modified or deleted files, including subdirectories. -A: shorthand for the same command  
space dot ( .): all files in the current directory BUT NOT any subdirectories  
-b: branch  
-d: delete  
-m: message  
-u: --set upstream

# …or create a new repository on the command line
echo "# guitguide" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/user/repo.git or git remote add origin git@github.com:user/repo.git  
git push -u origin main

# …or push an existing repository from the command line
git remote add origin git@github.com:user/repo.git or git remote add origin git@github.com:user/repo.git  
git branch -M main
git push -u origin main