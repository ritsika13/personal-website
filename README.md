# CS Portfolio Website - Deployment Guide

## 🚀 Quick Start

This is your one-page portfolio website ready to be hosted on GitHub Pages!

## 📝 Customization Checklist

Before deploying, update the following in `index.html`:

1. **Personal Information** (line ~300):
   - Replace "YourName" with your actual name
   - Update the hero title and description
   - Add your personal tagline

2. **Projects** (starting ~400):
   - Replace placeholder projects with your actual CS projects
   - Update project titles, descriptions, and tech stacks
   - Add your GitHub repo links and demo links

3. **UX Wireframes** (starting ~550):
   - Add links to your wireframe images
   - Update project titles and descriptions
   - You can use Figma, Dribbble, or any image hosting service

4. **Contact Information** (starting ~650):
   - Update email address
   - Add your GitHub username
   - Add your LinkedIn profile
   - Link to your resume (upload resume.pdf to the repo)

## 🌐 Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it: `yourusername.github.io` (replace with your GitHub username)
   - Example: if your username is "johndoe", name it: `johndoe.github.io`
3. Make it **public**
4. Don't initialize with README (we'll add files manually)

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. Click "uploading an existing file"
2. Drag and drop your `index.html` file
3. Commit the changes

**Option B: Using Git Command Line**
```bash
# Navigate to where you saved index.html
cd path/to/your/portfolio

# Initialize git repository
git init

# Add your files
git add index.html

# Commit
git commit -m "Initial portfolio commit"

# Add remote (replace 'yourusername' with your GitHub username)
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: View Your Website

Your site will be live at: `https://yourusername.github.io`

## 🎨 Adding Wireframe Images

To add your UX wireframes:

1. **Export from your design tool** (Figma, Adobe XD, Sketch)
   - Export as PNG or JPG
   - Recommended size: 800x600px or larger

2. **Upload images to your repo**:
   - Create an `images` folder in your repository
   - Upload your wireframe images there

3. **Update the HTML**:
   Replace `[Add your wireframe image here]` with:
   ```html
   <img src="images/your-wireframe.png" alt="Project name" style="width: 100%; height: 100%; object-fit: cover;">
   ```

## 🛠️ Optional Enhancements

### Add Google Fonts
The site uses DM Mono and Syne fonts (already linked in the HTML)

### Add Your Resume
1. Upload your resume PDF to the repo
2. Update the resume link in the contact section:
   ```html
   <a href="your-resume.pdf" class="contact-link">
   ```

### Add Favicon
1. Create a favicon (16x16 or 32x32 PNG)
2. Add to your repo as `favicon.ico`
3. Add to `<head>` section:
   ```html
   <link rel="icon" type="image/x-icon" href="favicon.ico">
   ```

## 📱 Mobile Responsive

The site is fully responsive and looks great on:
- Desktop computers
- Tablets
- Mobile phones

## 🎯 Features Included

✅ Smooth scroll navigation  
✅ Fixed navigation bar  
✅ Animated sections on scroll  
✅ Hover effects on cards  
✅ Mobile responsive design  
✅ Professional color scheme  
✅ Clean, modern typography  
✅ Project showcase cards  
✅ UX wireframe gallery  
✅ Contact section with links  

## 💡 Tips

- **Update regularly**: Keep your projects and skills current
- **Add analytics**: Consider adding Google Analytics to track visitors
- **Custom domain**: You can use a custom domain with GitHub Pages
- **SEO**: Update the `<title>` and add meta descriptions for better SEO

## 🆘 Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
- [Git Tutorial](https://git-scm.com/docs/gittutorial)

---

Good luck with your portfolio! 🚀
