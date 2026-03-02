# GitHub Setup Instructions for Your Freelance Profile

Your freelance profile is ready to be hosted on GitHub Pages! Follow these steps:

## Files Ready

✅ `index.html` - Your freelance profile (main file)
✅ `README.md` - Repository description
✅ `.gitignore` - Standard Git configuration

## Step-by-Step Setup

### 1. Create a GitHub Account
- Go to https://github.com
- Click "Sign up"
- Complete registration and verify your email

### 2. Create a New Repository
- Log in to GitHub
- Click the **+** icon (top right) → **New repository**
- **Repository name:** `freelance-profile`
- **Description:** `Sustainability Technology & Market Research Consultant Portfolio`
- Select **Public** (not private)
- ✅ Check "Add a README file"
- Click **Create repository**

### 3. Upload Files to GitHub

**Option A: Using GitHub Web Interface (Easiest)**

1. Go to your new repository on GitHub
2. Click **Add file** → **Upload files**
3. Download these files from your computer:
   - `index.html` (your profile)
   - `README.md`
   - `.gitignore`
4. Drag & drop them into GitHub or click "choose your files"
5. Click **Commit changes** at the bottom

**Option B: Using Git Command Line (Advanced)**

```bash
# Navigate to your freelance-profile folder
cd freelance-profile

# Initialize git repository
git init

# Add files
git add .

# Create initial commit
git commit -m "Initial commit: Freelance profile"

# Add GitHub as remote
git remote add origin https://github.com/YOUR-USERNAME/freelance-profile.git

# Push to GitHub (replace main if your default branch is different)
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages

1. In your repository, go to **Settings** (gear icon)
2. In left sidebar, click **Pages**
3. Under "Build and deployment" → "Source", select **Deploy from a branch**
4. Select **main** branch
5. Keep folder as **/ (root)**
6. Click **Save**
7. Wait 1-2 minutes for GitHub to build your site

### 5. Find Your Public URL

After GitHub finishes deploying:

1. Go back to **Settings** → **Pages**
2. Look for the green message: **"Your site is published at: https://YOUR-USERNAME.github.io/freelance-profile/"**
3. Copy this URL

## Your Live Profile URL
```
https://YOUR-USERNAME.github.io/freelance-profile/
```

(Replace `YOUR-USERNAME` with your actual GitHub username)

## Add to LinkedIn

Once your site is live:

1. Go to your LinkedIn profile
2. Click **Edit public profile**
3. In **About** section or add a **Website** link
4. Add your GitHub Pages URL: `https://YOUR-USERNAME.github.io/freelance-profile/`
5. Save changes

## Updating Your Profile

To make changes in the future:

1. Go to your GitHub repository
2. Click on `index.html`
3. Click the pencil icon (✏️ Edit this file)
4. Make your changes
5. Scroll down and click **Commit changes**
6. GitHub will automatically update your live site within minutes

## Troubleshooting

**Site not showing?**
- Wait 2-3 minutes after enabling Pages
- Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
- Check that file is named `index.html` (not `freelance_profile.html`)

**HTTPS not working?**
- Go to Settings → Pages
- Wait a few minutes, HTTPS should be auto-enabled
- Refresh the page

**Need help?**
- GitHub Pages docs: https://docs.github.com/en/pages
- Contact GitHub support at https://github.com/support

---

## Next Steps

1. ✅ Create GitHub account
2. ✅ Create repository
3. ✅ Upload files
4. ✅ Enable GitHub Pages
5. ✅ Get your URL
6. ✅ Add to LinkedIn
7. ✅ Start sharing on freelance platforms!

Your profile will be live and automatically updated whenever you make changes!
