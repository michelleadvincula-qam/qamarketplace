# QA Marketplace Website

Modern, efficient website for QA Marketplace - connecting fast-paced teams with pre-vetted QA professionals.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it: `qamarketplace` (or any name you prefer)
3. Set it to **Public**
4. Don't initialize with README (we already have files)

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Commit the files

**Option B: Using Git Command Line**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/qamarketplace.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings**
2. Scroll to **Pages** section (left sidebar)
3. Under "Source", select **main** branch
4. Select **/ (root)** folder
5. Click **Save**
6. Wait 2-3 minutes for deployment

Your site will be live at: `https://YOUR-USERNAME.github.io/qamarketplace/`

### Step 4: Connect Custom Domain (qamarketplace.org)

1. In GitHub Pages settings, add your custom domain: `qamarketplace.org`
2. In your domain registrar (where you bought qamarketplace.org):
   - Add an **A Record** pointing to GitHub's IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - Add a **CNAME Record** for `www` pointing to: `YOUR-USERNAME.github.io`

3. Wait 24-48 hours for DNS propagation (usually faster, 1-2 hours)
4. Check "Enforce HTTPS" in GitHub Pages settings once DNS is set up

## 📁 Files Structure

```
qamarketplace/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # Interactive features
└── README.md       # This file
```

## 🎨 Design Features

- **Modern, Efficient Design**: Reflects the speed and effectiveness of your service
- **Brand Colors**: 
  - Primary: #3366cc (Blue)
  - Secondary: #434343 (Dark Gray)
  - Accent: #ff0000 (Red)
- **Responsive**: Works perfectly on mobile, tablet, and desktop
- **Fast Loading**: Optimized for performance
- **Smooth Animations**: Professional micro-interactions

## 🛠️ Customization

### Update Content
Edit `index.html` to change:
- Text content
- Links
- Images (if you add any)

### Change Colors
Edit `styles.css` at the top (CSS variables):
```css
:root {
    --primary: #3366cc;
    --secondary: #434343;
    --accent: #ff0000;
}
```

### Update Links
Current links in the site:
- Book a Call: `https://calendar.app.google/yaRZvBUFFkmBwv4XA`
- Join QA Pool: `https://forms.gle/VXkkEmyNVeXyKo9y9`
- Contact Form: `https://forms.gle/83Hm1gxzYUG7BrBU6`
- LinkedIn: `https://www.linkedin.com/company/110906548/`

## 📱 Mobile Responsive

The site automatically adapts to:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Technical Stack

- Pure HTML5
- CSS3 (with CSS Variables and Grid/Flexbox)
- Vanilla JavaScript (no frameworks needed)
- Google Fonts: Archivo & JetBrains Mono

## 📊 Performance

- No external dependencies (except fonts)
- Lightweight (total size < 100KB)
- Fast load times
- SEO optimized

## 🆘 Troubleshooting

**Site not showing up?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check that index.html is in the root folder
- Verify branch is set to "main" in settings

**Custom domain not working?**
- DNS can take up to 48 hours to propagate
- Verify A and CNAME records are correct
- Check GitHub Pages settings show green checkmark

**Mobile menu not working?**
- Make sure script.js is uploaded
- Check browser console for errors

## 📞 Support

For issues with the website code, check:
1. Browser console for JavaScript errors
2. GitHub Pages deployment status
3. DNS propagation status (use: https://dnschecker.org)

## 📄 License

© 2025 QA Marketplace. All rights reserved.
