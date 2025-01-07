# Initialize a new Git repository
git init

# Clone an existing repository
git clone <repository_url>

# Check the status of your repository
git status

# Add files to the staging area
- for single file : <br>
git add <file_name> 
- for multiple files :<br> 
git add . 

# Commit changes to the repository
git commit -m "Commit message"

# Push changes to a remote repository
git push origin <branch_name>

# Pull changes from a remote repository
git pull origin <branch_name>

# Create a new branch
git branch <branch_name>

# Switch to a different branch
git checkout <branch_name>

# Merge a branch into the current branch
git merge <branch_name>

# View commit history
git log

# View a specific commit
git show <commit_hash>

# Remove a file from the staging area
git reset <file_name>

# Revert changes in a file
git checkout -- <file_name>