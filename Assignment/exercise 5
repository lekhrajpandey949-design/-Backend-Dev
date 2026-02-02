mkdir advanced-workflow
cd advanced-workflow
git init

# Create some files
echo "File 1 content" > file1.txt
echo "File 2 content" > file2.txt

git add .
git commit -m "Initial commit with multiple files"

echo "node_modules/" > .gitignore
echo "*.log" >> .gitignore

git add .gitignore
git commit -m "Add .gitignore"

# Make some changes
echo "Some temporary changes" >> file1.txt

# Save changes without committing
git stash

# Check stashes
git stash list

# Apply the stash later
git stash apply

# Make changes and commit
echo "Release version 1.0 content" >> file2.txt
git add file2.txt
git commit -m "Prepare release v1.0"

# Create a tag
git tag -a v1.0 -m "Release version 1.0"

# List tags
git tag

# Add remote
git remote add origin https://github.com/your-username/advanced-workflow.git

# Push commits
git push origin main

# Push tags
git push origin --tags
