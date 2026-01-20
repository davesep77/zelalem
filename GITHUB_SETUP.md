# GitHub Repository Setup Instructions

## Repository Details
- **Username:** davesep77
- **Repository Name:** efi_portfolio
- **Description:** Professional portfolio for Senior Pavement & Materials Engineer

## Steps to Create and Push to GitHub:

### Option 1: Using GitHub Website (Recommended)

1. **Go to GitHub:**
   - Visit: https://github.com/new
   - Login with username: davesep77

2. **Create Repository:**
   - Repository name: `efi_portfolio`
   - Description: `Professional portfolio and CV for Senior Pavement & Materials Engineer`
   - Set to: **Public** (or Private if you prefer)
   - **DO NOT** initialize with README (we already have one)
   - Click "Create repository"

3. **Push Your Code:**
   Open PowerShell in this folder and run:
   ```powershell
   git remote add origin https://github.com/davesep77/efi_portfolio.git
   git branch -M main
   git push -u origin main
   ```

### Option 2: Using Git Commands (If you have GitHub CLI)

```powershell
gh repo create davesep77/efi_portfolio --public --source=. --remote=origin --push
```

## After Pushing:

Your portfolio will be available at:
- **Repository:** https://github.com/davesep77/efi_portfolio
- **Live Site (GitHub Pages):** https://davesep77.github.io/efi_portfolio/portfolio.html

## Enable GitHub Pages (Optional):

1. Go to repository Settings
2. Click "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be live at: https://davesep77.github.io/efi_portfolio/

## Files Ready to Push:
✅ portfolio.html - Modern portfolio website
✅ INDEX.HTML - Professional CV with translations
✅ README.md - Repository documentation
✅ profile.png - Profile photo
✅ engineer-photo-1.jpg - Engineering photo 1
✅ engineer-photo-2.jpg - Engineering photo 2
✅ .gitignore - Git ignore file

## Git Status:
All files are committed and ready to push!

---
Need help? Contact: ephwz2000@gmail.com
