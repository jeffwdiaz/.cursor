# Git Commands Reference

## New Project Setup

```bash
# Clone OR Initialize
git clone <repository-url>
git init

# Add all files to staging
git add .

# Create initial commit
git commit -m "Initial commit"

# Add remote origin
git remote add origin <repository-url>

# Push to remote and set upstream
git push -u origin main
```

## 2. Commits and Pushing

```bash
# Check status
git status

# Add specific file
git add <filename>

# Add all files
git add .

# Create commit
git commit -m "Your commit message"

# Push to remote
git push

# Push to branch
git push origin <branch-name>

# Pull from remote
git pull

# Create new branch
git checkout -b <new-branch-name>

# Switch branch
git checkout <branch-name>

# Unstage file
git reset HEAD <filename>

# DELETES and unstages
git rm <filename>

# Unstage but keep file
git rm --cached <filename>
```

## 3. Submodules

```bash
# Add submodule
git submodule add <repository-url> <path>

# Initialize submodules
git submodule init

# Update submodules
git submodule update

# Update all submodules
git submodule update --init --recursive

# Force update submodules
git submodule update --init --recursive --force

# Check submodule status
git submodule status

# Remove submodule
git submodule deinit <path>
git rm <path>
```
