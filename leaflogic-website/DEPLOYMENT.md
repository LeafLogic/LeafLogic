# 🚀 Deployment Guide - LeafLogic Website

This guide will walk you through the exact steps to upload your LeafLogic website to GitHub and make it live.

## 📋 Prerequisites

- A GitHub account (free)
- Git installed on your computer (optional, but recommended)
- All website files ready in the `leaflogic-website` folder

## 🎯 Method 1: Using GitHub Web Interface (Easiest)

### Step 1: Create a New Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name**: `leaflogic-website` (or any name you prefer)
   - **Description**: `LeafLogic AI-Powered Plant Care Robot Website`
   - **Visibility**: Choose Public or Private
   - **DO NOT** check "Add a README file" (we already have one)
5. Click **"Create repository"**

### Step 2: Upload Your Files
1. In your new repository, click **"uploading an existing file"**
2. Drag and drop the **entire contents** of your `leaflogic-website` folder
3. Make sure you see these files:
   - `index.html`
   - `css/styles.css`
   - `js/main.js`
   - `README.md`
   - `images/` folder (if you have images)
4. Add a commit message: `Initial website upload`
5. Click **"Commit changes"**

### Step 3: Enable GitHub Pages
1. Go to your repository's **Settings** tab
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"Deploy from a branch"**
4. Choose **"main"** branch and **"/ (root)"** folder
5. Click **"Save"**
6. Wait a few minutes for deployment

### Step 4: Access Your Website
Your website will be available at:
`https://yourusername.github.io/leaflogic-website`

## 🎯 Method 2: Using Git Command Line (Advanced)

### Step 1: Install Git
If you don't have Git installed:
- **Windows**: Download from [git-scm.com](https://git-scm.com)
- **Mac**: Install via Homebrew: `brew install git`
- **Linux**: `sudo apt-get install git`

### Step 2: Configure Git
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 3: Create Repository and Upload
```bash
# Navigate to your website folder
cd path/to/leaflogic-website

# Initialize Git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial website upload"

# Add GitHub repository as remote
git remote add origin https://github.com/yourusername/leaflogic-website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
Follow the same steps as Method 1, Step 3.

## 🔧 Custom Domain (Optional)

If you want to use your own domain (e.g., `leaflogic.ai`):

1. **Purchase a domain** from a registrar (GoDaddy, Namecheap, etc.)
2. **In GitHub repository Settings > Pages**:
   - Enter your custom domain
   - Check "Enforce HTTPS"
3. **Configure DNS** with your domain provider:
   - Add a CNAME record pointing to `yourusername.github.io`
   - Or add A records pointing to GitHub's IP addresses

## 📱 Testing Your Website

### Before Deployment
1. Open `index.html` in your browser
2. Test all links and buttons
3. Check mobile responsiveness
4. Verify all images load correctly

### After Deployment
1. Visit your GitHub Pages URL
2. Test on different devices
3. Check browser console for errors
4. Verify all functionality works

## 🐛 Common Issues & Solutions

### Issue: Website shows 404 error
**Solution**: 
- Make sure `index.html` is in the root directory
- Check that GitHub Pages is enabled
- Wait 5-10 minutes for deployment

### Issue: Images not loading
**Solution**:
- Check image file paths in HTML
- Ensure images are uploaded to GitHub
- Use relative paths (e.g., `images/logo.png`)

### Issue: Styles not applying
**Solution**:
- Check CSS file path in HTML
- Clear browser cache
- Verify CSS file is uploaded

### Issue: JavaScript not working
**Solution**:
- Check browser console for errors
- Verify JavaScript file is uploaded
- Check for syntax errors in code

## 🔄 Updating Your Website

### Using GitHub Web Interface
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon to edit
4. Make your changes
5. Commit the changes

### Using Git Command Line
```bash
# Make your changes to files locally
# Then push to GitHub:
git add .
git commit -m "Update website content"
git push
```

## 📊 Analytics Setup

To add Google Analytics:

1. **Create Google Analytics account**
2. **Get your tracking ID** (starts with "G-")
3. **Add tracking code** to `index.html` in the `<head>` section:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## 🔒 Security Best Practices

1. **Use HTTPS**: GitHub Pages automatically provides this
2. **Keep dependencies updated**: Regularly check for updates
3. **Validate forms**: Add client-side and server-side validation
4. **Sanitize user input**: If you add forms later

## 📈 Performance Optimization

1. **Optimize images**: Use WebP format when possible
2. **Minify CSS/JS**: Use online tools to compress files
3. **Enable compression**: GitHub Pages handles this automatically
4. **Use CDN**: Consider using a CDN for better performance

## 🎉 Congratulations!

Your LeafLogic website is now live! Share the URL with your team and customers.

## 📞 Need Help?

- **GitHub Support**: [help.github.com](https://help.github.com)
- **GitHub Pages Documentation**: [pages.github.com](https://pages.github.com)
- **Contact**: hello@leaflogic.ai

---

**Your website URL**: `https://yourusername.github.io/leaflogic-website`

*Remember to replace "yourusername" with your actual GitHub username!* 