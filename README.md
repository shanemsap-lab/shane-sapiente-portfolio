# E-Portfolio Site - Deployment Instructions

## Site Location
`/Users/shane.sapiente/Documents/Capstone Assignment/e-portfolio-site/`

## Files Included
```
e-portfolio-site/
├── index.html        (Home page)
├── about.html        (About Me)
├── coursework.html   (Course artifacts)
├── reflections.html  (Course reflections)
├── resume.html       (Resume/CV)
├── contact.html      (Contact info)
├── css/
│   └── style.css     (All styling)
├── assets/           (Put PDFs here)
└── README.md         (This file)
```

## Preview Locally
1. Open Finder
2. Navigate to this folder
3. Double-click `index.html` to open in browser

## Deploy to GitHub Pages (FREE)

### Step 1: Create GitHub Repository
1. Go to github.com and log in (or create account)
2. Click the **+** icon → **New repository**
3. Name it: `portfolio` (or any name you like)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Files
1. On the repo page, click **uploading an existing file**
2. Drag ALL files from this folder into the upload area
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to **Settings** tab in your repo
2. Click **Pages** in the left sidebar
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 minutes

### Step 4: Access Your Site
Your site will be live at:
`https://YOUR-USERNAME.github.io/portfolio/`

## Customization Needed

Before deploying, update these placeholders:

### contact.html
- [ ] Your email address
- [ ] Your LinkedIn URL
- [ ] Your city/location

### resume.html
- [ ] Your job title at Yale
- [ ] Your job dates
- [ ] Your responsibilities/achievements
- [ ] Any certifications

### To Add Paper PDFs
1. Put PDF files in the `assets/` folder
2. Uncomment the download links in `coursework.html`

## Alternative: Netlify (Even Easier)

1. Go to netlify.com
2. Sign up (free)
3. Drag and drop this entire folder onto the page
4. Done! You get a URL like `random-name.netlify.app`
5. You can customize the URL in settings

## Color Customization

Edit `css/style.css` and change the colors at the top:
```css
:root {
  --primary: #1a365d;      /* Dark blue - headers, nav */
  --primary-light: #2c5282; /* Medium blue */
  --accent: #3182ce;       /* Bright blue - links, buttons */
}
```

---
*Created: December 6, 2025*
