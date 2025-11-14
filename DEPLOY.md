# GitHub Pages Deployment Guide

## Steps to Deploy to GitHub Pages

### 1. Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `metro-design-history` (or your preferred name)
3. Description: "A website documenting the history and evolution of Microsoft's Metro/Fluent Design Language"
4. Set to **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

### 2. Push to GitHub

After creating the repository on GitHub, run these commands:

```bash
# Add the remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/metro-design-history.git

# Rename branch to main (GitHub's default)
git branch -M main

# Push to GitHub
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** section (left sidebar)
4. Under "Source", select **main** branch
5. Select **/ (root)** folder
6. Click **Save**
7. Wait 1-2 minutes for deployment

### 4. Your Site Will Be Live At:

```
https://YOUR_USERNAME.github.io/metro-design-history/
```

## Quick Commands (Copy & Paste)

After creating the repository on GitHub, replace `YOUR_USERNAME` and run:

```powershell
cd "c:\Users\joshu\Documents\Design Style"
git remote add origin https://github.com/YOUR_USERNAME/metro-design-history.git
git branch -M main
git push -u origin main
```

## Making Updates

After the initial push, to update the site:

```powershell
cd "c:\Users\joshu\Documents\Design Style"
git add .
git commit -m "Description of your changes"
git push
```

GitHub Pages will automatically redeploy within 1-2 minutes.

## Troubleshooting

### If you get "remote origin already exists":
```powershell
git remote remove origin
git remote add origin https://github.com/YOUR_USERNAME/metro-design-history.git
```

### If you need to set git credentials:
```powershell
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### If push asks for authentication:
- Use a Personal Access Token (PAT) instead of password
- Generate at: https://github.com/settings/tokens
- Or use GitHub CLI: `gh auth login`

---

**Status**: ✅ Local repository created and committed  
**Next Step**: Create GitHub repository and push
