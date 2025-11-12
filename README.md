# 1. Initialize repo (if not already)
git init
git add .
git commit -m "Initial commit - Fresh Tide Laundry site"

# 2. Create repo on GitHub (replace USER/REPO)
# Either create it on github.com via UI, or use gh CLI:
#   gh repo create fresh-tide-laundry --public --source=. --remote=origin --push
# If not using gh CLI, add remote:
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/REPO_NAME.git

# 3. Push to GitHub (main branch)
git branch -M main
git push -u origin main
