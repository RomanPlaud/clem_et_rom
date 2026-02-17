# Deploying Your Wedding Website to GitHub Pages

Here is the step-by-step guide to putting your website online for free using GitHub Pages.

## 1. Create a GitHub Repository
1.  Go to [github.com/new](https://github.com/new).
2.  **Repository name**: e.g., `mariage-clemence-roman` (or anything you like).
3.  **Public/Private**: Choose **Public** (required for free GitHub Pages unless you have Pro).
4.  Click **Create repository**.

## 2. Push Your Code
Run these commands in your terminal (I can run the first few for you):

```bash
cd /home/infres/rplaud/wed_site
git init
git add .
git commit -m "Initial commit - Wedding Website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
git push -u origin main
```
*(Replace `YOUR_USERNAME` and `REPOSITORY_NAME` with your actual info)*

## 3. Activate GitHub Pages
1.  Go to your repository on GitHub.
2.  Click **Settings** (top tabs).
3.  Click **Pages** (left sidebar).
4.  Under **Build and deployment** > **Branch**, select **main** and click **Save**.

**That's it!**
After a minute, GitHub will give you a link (e.g., `https://your-username.github.io/mariage-clemence-roman/`). You can share this link with your guests!
