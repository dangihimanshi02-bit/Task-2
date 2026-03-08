# Configure Git
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list

# Initialize repository
git init

# Clone repository
git clone https://github.com/username/repository-name.git

# Check status
git status

# Add files
git add filename
git add .

# Commit changes
git commit -m "Initial commit"

# View commit history
git log
git log --oneline

# Branch commands
git branch
git branch new-branch
git checkout new-branch
git checkout -b another-branch

# Merge branch
git merge branch-name

# Connect to remote repository
git remote add origin https://github.com/username/repository-name.git
git remote -v

# Push to GitHub
git push -u origin main
git push origin main

# Pull latest changes
git pull origin main

# Fetch updates
git fetch

# Remove file
git rm filename

# Undo changes
git checkout -- filename
git reset filename

# Delete branch
git branch -d branch-name

