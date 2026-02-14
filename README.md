# Sync

Stage 1:
# 1. Create the project directory
mkdir ml-project

# 2. Navigate into the directory
cd ml-project

# 3. Initialize the Git repository
git init

# 4. Create the required files (empty)
touch train.py predict.py utils.py README.md

# 5. Check the status of the repository
git status

Stage 2:
# Step 1: Stage specific files
git add train.py utils.py

# Step 2: Commit changes
git commit -m "Add training script and utilities"

# Step 3: Rename branch to main (Standard practice)
git branch -M main

# Step 4: Link our local repository to GitHub
git remote add origin https://github.com/yourusername/ml-project.git

# Step 5: Push our commits to the main branch
git push -u origin main


Stage 3:
1. Sync Remote ChangBeforeore committing, pull our teammate's updates to predict.py and README.md.
git pull origin main

2. Commit Local Work
Stage our modified utils.py and the new config.py.
git add utils.py config.py
git commit -m "Update utils and add config file"

3. Push to GitHub
Upload our combined history to the shared repository.
git push origin main)
