# Quick Deployment Guide

## Option 1: GitHub Pages (Recommended - Free & Easy)

### Steps:
1. **Create a GitHub repository:**
   - Go to https://github.com/new
   - Name it: `baum-quiz` or any name you like
   - Click "Create repository"

2. **Push your code:**
   ```bash
   cd /Users/philipknoll/Downloads/Quiz
   git remote add origin https://github.com/YOUR-USERNAME/baum-quiz.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click "Settings" → "Pages"
   - Under "Source", select "main" branch
   - Click "Save"

4. **Access your quiz:**
   - URL will be: `https://YOUR-USERNAME.github.io/baum-quiz/index_mit_bildern.html`
   - Or customize by renaming `index_mit_bildern.html` to `index.html`

### Quick Command:
```bash
# Run these commands (replace YOUR-USERNAME with your actual GitHub username):
git remote add origin https://github.com/YOUR-USERNAME/baum-quiz.git
git branch -M main
git push -u origin main
```

---

## Option 2: Netlify (Simplest - Free)

### Steps:
1. Go to https://www.netlify.com
2. Sign up (free)
3. Drag and drop the entire Quiz folder onto the Netlify dashboard
4. Done! You'll get a URL like: `https://random-name-123.netlify.app`

---

## Option 3: Vercel (Also Simple - Free)

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel` in the Quiz folder
3. Follow the prompts
4. Done!

---

## Option 4: Local Testing

Just open the file in your browser:
```bash
open index_mit_bildern.html
```

Or share via local network in your classroom.

---

## Need Help?

Choose an option above and I'll help you execute it!

