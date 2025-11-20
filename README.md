# Poetry Design - "Didn't Sappho Say"

An interactive web-based poetry visualization project.

## GitHub Pages Setup

To view this repository on GitHub Pages, follow these steps:

### 1. Add Your Image Files
- Upload all required image files to the `images/` directory
- See `images/README.md` for the complete list of required images

### 2. Enable GitHub Pages
1. Go to your repository on GitHub: https://github.com/ziohere/ASSIGNMENT-1
2. Click on **Settings** (at the top of the repository page)
3. Scroll down to the **Pages** section in the left sidebar
4. Under **Source**, select the branch you want to deploy (e.g., `main` or `master`)
5. Select the root folder `/` as the source directory
6. Click **Save**

### 3. Wait for Deployment
- GitHub will automatically build and deploy your site
- You'll see a message with your site URL (usually: `https://ziohere.github.io/ASSIGNMENT-1/`)
- The deployment may take a few minutes

### 4. Access Your Live Site
Once deployed, your site will be available at:
```
https://ziohere.github.io/ASSIGNMENT-1/
```

## Troubleshooting

### Site Not Showing Up
- **Check if Pages is enabled**: Go to Settings → Pages and verify the source is set correctly
- **Verify branch**: Make sure you're deploying from the correct branch that contains `index.html`
- **Check deployment status**: Go to the **Actions** tab to see if the deployment succeeded
- **Wait for DNS**: Sometimes it takes a few minutes for the site to become available

### Images Not Loading
- Make sure all image files are uploaded to the `images/` directory
- Verify image filenames match exactly (including spaces and capitalization)
- Check browser console for 404 errors on missing images

### Recent Fixes Applied
✅ Fixed image paths from `../images/` to `images/`
✅ Created proper images directory structure
✅ Added documentation for GitHub Pages setup

## Project Structure
```
ASSIGNMENT-1/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── images/             # Image assets directory
│   ├── README.md       # List of required images
│   └── .gitkeep        # Keeps directory in git
└── README.md           # This file
```

## Local Development
To test locally, you can use any static web server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server

# Then open http://localhost:8000 in your browser
```

## Notes
- This project uses Google Fonts (Vesper Libre, UnifrakturMaguntia, UnifrakturCook)
- The design is optimized for desktop viewing
- All image paths have been corrected to work with GitHub Pages
