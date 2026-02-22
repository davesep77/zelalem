# Firebase Deployment Guide - Zelalem Tsegaye CV

## Prerequisites
✅ Firebase CLI installed
✅ Google account ready

## Deployment Steps

### 1. Login to Firebase
```powershell
firebase login
```
This will open your browser to authenticate with Google.

### 2. Initialize Firebase Project
```powershell
firebase init hosting
```

When prompted:
- **Use an existing project or create a new one?** → Use existing project (or create new)
- **Project name:** `zelalem-cv` (or your preferred name)
- **What do you want to use as your public directory?** → `.` (current directory)
- **Configure as a single-page app?** → No
- **Set up automatic builds?** → No
- **File index.html already exists. Overwrite?** → No

### 3. Deploy to Firebase
```powershell
firebase deploy
```

## After Deployment

Your portfolio will be live at:
- **Firebase URL:** `https://zelalem-cv.web.app`
- **Custom domain:** Can be configured in Firebase Console

## Quick Deploy Command
```powershell
# One-line deploy (after initial setup)
firebase deploy --only hosting
```

## Files Ready for Deployment
✅ portfolio.html - Main portfolio website
✅ INDEX.HTML - Professional CV (alternate)
✅ cv.html - Professional CV with print support
✅ Z PIC.jpg - Professional photo
✅ pp.png - Profile photo
✅ profile.png - Profile photo (alternate)
✅ firebase.json - Configuration

---
**Note:** Make sure you're logged into the correct Google account before deploying!
**Portfolio Owner:** Zelalem Tsegaye | Senior Surveyor | Addis Ababa, Ethiopia
