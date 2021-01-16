# Git useful commands
1. git init  # Initialize repo in cd (note appearance of hidden .git folder)
2. git add .  # Register all changes since last git commit or git init and prepare them for commit. It's like taking
   the files up to a stage before taking a pic
3. git reset .  # Revert all changes added. It's like asking the files to come down the stage because they aren't ready for the pic
4. git commit  # Commit the changes. Take the pic
5. git checkout -- .  # Reconstruct committed files to the previous commit
6. git log  # Get list of past commits
7. git commit --amend  # Fix last commit comment
8. git checkout -b <branchname>  # Create new branch from last commit
9. git branch  # Show current branch from branches
10. git checkout <branchname>  # Go to specified branch
11. gir merge <branchname>  # Merge specified branch with master
11. git branch -d <branchname>  # Delete specified branch

# Flags
--all: include all new, modified or deleted files, including subdirectories. -A: shorthand for the same command
 .(space dot): all files in the current directory BUT NOT any subdirectories
-b: branch
-m: message