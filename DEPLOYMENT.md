# 🚀 Deploy to Render - Step by Step Guide

This guide will walk you through deploying your portfolio website to Render.com.

## Prerequisites

- Your portfolio files ready (index.html, styles.css, script.js, photo.jpeg)
- A Render account (free)

## Step 1: Create Render Account

1. Go to [render.com](https://render.com)
2. Click "Get Started" or "Sign Up"
3. You can sign up with:
   - GitHub account (recommended)
   - Google account
   - Email address

## Step 2: Create New Static Site

1. **From Dashboard**:
   - Click the "New +" button
   - Select "Static Site"

2. **Connect Repository** (if using Git):
   - Choose "Connect a repository"
   - Select your GitHub repository
   - Or choose "Upload files" if you don't have a Git repository

## Step 3: Configure Your Site

### If Using Git Repository:
- **Name**: `jasmita-portfolio` (or your preferred name)
- **Branch**: `main` (or your default branch)
- **Build Command**: Leave empty (not needed for static sites)
- **Publish Directory**: Leave empty (root directory)

### If Uploading Files:
- **Name**: `jasmita-portfolio`
- Upload all your files:
  - `index.html`
  - `styles.css`
  - `script.js`
  - `photo.jpeg`
  - `README.md`

## Step 4: Deploy

1. Click "Create Static Site"
2. Render will automatically:
   - Upload your files
   - Build your site
   - Deploy to a live URL

## Step 5: Access Your Site

- Your site will be available at: `https://your-site-name.onrender.com`
- The URL will be shown in your Render dashboard
- You can customize the URL in settings

## Step 6: Custom Domain (Optional)

1. **In Render Dashboard**:
   - Go to your site settings
   - Click "Custom Domains"
   - Add your domain

2. **Update DNS**:
   - Add CNAME record pointing to your Render URL
   - Wait for DNS propagation (up to 48 hours)

## Troubleshooting

### Common Issues:

1. **Site not loading**:
   - Check if `index.html` is in the root directory
   - Verify all file paths are correct

2. **Images not showing**:
   - Ensure image files are uploaded
   - Check file paths in HTML

3. **Styling issues**:
   - Verify `styles.css` is uploaded
   - Check CSS file path in HTML

4. **JavaScript not working**:
   - Ensure `script.js` is uploaded
   - Check console for errors

### File Structure Check:
```
your-site/
├── index.html
├── styles.css
├── script.js
├── photo.jpeg
└── README.md
```

## Render Features

### Free Tier Includes:
- ✅ Static site hosting
- ✅ Custom domains
- ✅ Automatic deployments
- ✅ SSL certificates
- ✅ Global CDN

### Automatic Deployments:
- When you push to your Git repository, Render automatically redeploys
- No manual intervention needed

## Performance Tips

1. **Optimize Images**:
   - Compress images before uploading
   - Use WebP format when possible

2. **Minimize Files**:
   - Remove unused CSS/JS
   - Compress files for faster loading

3. **Use CDN**:
   - Render automatically serves files via CDN
   - Global distribution for faster loading

## Monitoring

- **Render Dashboard**: Monitor site performance
- **Analytics**: Add Google Analytics for visitor tracking
- **Uptime**: Render provides 99.9% uptime guarantee

## Support

- **Render Documentation**: [docs.render.com](https://docs.render.com)
- **Community**: [Render Community](https://community.render.com)
- **Email Support**: Available for all users

---

**Your portfolio is now live! 🎉**

Share your Render URL with potential employers and on your resume.
