# GitHub Pages Deployment Guide - NICE Platform

## Step-by-Step Instructions

---

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to **https://github.com**
2. Click **"Sign up"**
3. Follow the registration process
4. Verify your email address

---

## Step 2: Create a New Repository

1. Log in to GitHub
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name:** `nice-platform` (or any name you prefer)
   - **Description:** `Lufthansa Technik NICE Platform - In-flight Entertainment Solutions`
   - **Visibility:** Choose **Public** (required for free GitHub Pages)
   - ✅ Check **"Add a README file"**
5. Click **"Create repository"**

---

## Step 3: Upload Your Files

### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop these files:
   - `index.html` (the main file I created for you)
   - `README.md` (optional, for documentation)
3. In the "Commit changes" section:
   - Add a message like: `Initial commit - NICE Platform`
4. Click **"Commit changes"**

### Option B: Using Git Command Line (Advanced)

```bash
# Clone your repository
git clone https://github.com/YOUR_USERNAME/nice-platform.git

# Navigate to the folder
cd nice-platform

# Copy the index.html file here
# (copy the file I provided into this folder)

# Add the files
git add .

# Commit
git commit -m "Initial commit - NICE Platform"

# Push to GitHub
git push origin main
```

---

## Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (tab at the top)
3. In the left sidebar, click **"Pages"**
4. Under **"Source"**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Click **"Save"**

---

## Step 5: Access Your Live Site

1. Wait 1-2 minutes for GitHub to build your site
2. Refresh the Settings → Pages section
3. You'll see a green box with your URL:
   ```
   Your site is live at https://YOUR_USERNAME.github.io/nice-platform/
   ```
4. Click the link to view your live platform!

---

## Troubleshooting

### Site not loading?
- Make sure the file is named exactly `index.html` (lowercase)
- Wait a few minutes - GitHub Pages can take up to 10 minutes to deploy
- Check if GitHub Pages is enabled in Settings → Pages

### 404 Error?
- Ensure you selected the correct branch (`main`) in Pages settings
- Verify the `index.html` file is in the root of the repository, not in a subfolder

### Site looks broken?
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Try opening in an incognito/private window

---

## Updating Your Site

To update your site in the future:

1. Go to your repository
2. Click on `index.html`
3. Click the **pencil icon** (Edit this file)
4. Make your changes or replace the content
5. Click **"Commit changes"**
6. Wait 1-2 minutes for the site to update

---

## Custom Domain (Optional)

If you want a custom domain like `nice.yourdomain.com`:

1. In Settings → Pages, enter your custom domain
2. Add a CNAME record in your domain's DNS settings pointing to `YOUR_USERNAME.github.io`
3. Wait for DNS propagation (can take up to 24 hours)

---

## Summary

| Step | Action |
|------|--------|
| 1 | Create GitHub account |
| 2 | Create new repository |
| 3 | Upload `index.html` |
| 4 | Enable GitHub Pages in Settings |
| 5 | Visit `https://YOUR_USERNAME.github.io/nice-platform/` |

Your NICE Platform will be live and accessible from anywhere in the world!

---

## Questions?

If you encounter any issues, check:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Status](https://www.githubstatus.com/)
