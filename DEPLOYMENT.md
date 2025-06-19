# GitHub Pages Deployment Guide

## Quick Setup (5 minutes)

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and create a new repository
2. Name it something like `your-website` or `bennees-blog`
3. **Don't** initialize with README (we already have files)
4. Copy the repository URL (e.g., `https://github.com/yourusername/your-website.git`)

### 2. Connect Your Local Files to GitHub
Run these commands in your terminal (replace with your actual repository URL):

```bash
git remote add origin https://github.com/yourusername/your-website.git
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### 4. Access Your Live Website
- Your site will be available at: `https://yourusername.github.io/your-website`
- It may take a few minutes to go live initially

## Making Updates

### Adding New Blog Posts

1. **Edit the HTML files directly** in VS Code
2. **Commit and push changes**:
   ```bash
   git add .
   git commit -m "Add new blog post about [topic]"
   git push
   ```
3. **Changes go live automatically** within a few minutes

### Easy Content Updates

For cooking posts, edit `cooking.html`:
- Add new `<article class="post">` sections
- Follow the existing format with title, date, and content

For random thoughts, edit `random.html`:
- Same format as cooking posts

## Pro Tips

- **Edit files locally** in VS Code for the best experience
- **Preview changes** by opening the HTML files in your browser before pushing
- **Use consistent dates** in the format "June 18, 2025"
- **Keep the minimalist style** - focus on content over flashy design

## Custom Domain (Optional)
If you want a custom domain like `yourblog.com`:
1. Add a `CNAME` file to your repository with your domain
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use your custom domain
