# 🚀 GitHub Profile Deployment Guide

## Prerequisites
- GitHub account (obviously 😄)
- Your username must match the repository name (De-adlock)

## Step 1: Create the Profile Repository
1. Go to GitHub and create a new repository
2. Name it **exactly** as your username: `De-adlock`
3. Make sure it's **PUBLIC** (very important!)
4. Initialize with the README.md we created

## Step 2: Customize Your Profile

### Update Personal Information
Edit the README.md and replace:
- Email address in the email badge
- Discord server link
- Twitter username
- Any project links you want to showcase

### Update Stats Cards
The stats cards will automatically pull your GitHub data, but you can customize:
- Colors (change `title_color`, `icon_color`, etc.)
- Themes (check available themes at github-readme-stats repo)
- Layout options

### Daily.dev Card (Optional)
1. Sign up at https://app.daily.dev
2. Generate your dev card
3. Replace `YOUR_DEVCARD_ID` with your actual ID

## Step 3: Enable GitHub Actions for Snake Animation
1. Go to repository Settings
2. Navigate to Actions → General
3. Enable "Allow all actions and reusable workflows"
4. The snake will generate automatically after first push

## Step 4: Push to GitHub

```bash
cd /mnt/d/IsaQ/De-adlock
git add .
git commit -m "🎨 Initial awesome profile setup"
git branch -M main
git remote add origin https://github.com/De-adlock/De-adlock.git
git push -u origin main
```

## Step 5: Verify Your Profile
1. Visit https://github.com/De-adlock
2. Your new profile README should be visible!
3. The snake animation will appear after the first workflow run

## 🎨 Customization Tips

### Gradient Colors
The header uses custom gradient colors. You can change them:
- `customColorList=12` - Change the number for different gradients
- Available: 0-30

### Typing Animation
Modify the lines in the typing animation to showcase your skills:
```
lines=Your+First+Line;Your+Second+Line;Your+Third+Line
```

### Tech Stack Badges
Add more badges from: https://github.com/Ileriayo/markdown-badges
Just copy the badge code and add to the appropriate section.

### Color Themes
- Current theme: Black/Green (Matrix style)
- Can be changed to any color scheme you prefer
- Main colors used: `#00ff41` (green), `#0d1117` (dark background)

## 📊 Tracking Profile Views
The profile view counter will start from 0 and increment with each unique visitor.

## 🔄 Updating Your Profile
Simply edit the README.md and push changes:
```bash
git add README.md
git commit -m "Update profile"
git push
```

## ⚡ Pro Tips
1. Keep the README under 10MB for best performance
2. Update regularly to show you're active
3. Pin your best repositories (up to 6)
4. Use GitHub's new profile features (status, pronouns, etc.)
5. Consider adding a blog feed using GitHub Actions

## 🎯 Checklist
- [ ] Repository named exactly as username
- [ ] Repository is public
- [ ] README.md is in root directory
- [ ] Personal links updated
- [ ] GitHub Actions enabled
- [ ] First push completed
- [ ] Profile visible at github.com/username

## 🆘 Troubleshooting
- **Profile not showing?** Make sure repo is public and named correctly
- **Stats not loading?** Check if github-readme-stats is not down
- **Snake not generating?** Wait for the workflow to run (every 12 hours)
- **Images broken?** Verify all URLs are correct and services are online

## 🌟 Extra Features to Add Later
- Blog posts auto-fetch
- YouTube latest videos
- Spotify currently playing
- Wakatime coding stats
- LeetCode stats
- Custom animations
- 3D contribution calendar

---

**Ready to impress everyone with your GitHub profile! 🚀**