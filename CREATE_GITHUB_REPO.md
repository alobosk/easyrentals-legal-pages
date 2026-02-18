# Create GitHub Repository - Quick Steps

## Step 1: Create Repository on GitHub

1. Go to: https://github.com/new
2. Repository name: `easyrentals-legal-pages`
3. Description: `Legal documents for EasyRentals Inc QuickBooks integration`
4. **Make it PUBLIC** (required for public URLs)
5. **DO NOT** initialize with README, .gitignore, or license (we already have files)
6. Click **"Create repository"**

## Step 2: Add Remote and Push

After creating the repo, GitHub will show you commands. Use these:

```bash
cd "/Users/alobos/Documents/EasyRentals Inc/easyrentals-legal-pages"
git remote add origin git@github.com:alobosk/easyrentals-legal-pages.git
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to: https://github.com/alobosk/easyrentals-legal-pages/settings/pages
2. Source: `main` branch
3. Folder: `/ (root)`
4. Click **Save**

## Step 4: Get Your URLs

After Pages is enabled (takes ~1 minute), your URLs will be:

- **EULA:** `https://alobosk.github.io/easyrentals-legal-pages/eula.html`
- **Privacy:** `https://alobosk.github.io/easyrentals-legal-pages/privacy.html`

## Step 5: Add to Intuit Developer Portal

1. Go to: https://developer.intuit.com/
2. Open your app
3. **Settings** → **App URLs**
4. Paste the GitHub Pages URLs
5. **Save**

---

**Everything is ready - just create the repo on GitHub and push!**
