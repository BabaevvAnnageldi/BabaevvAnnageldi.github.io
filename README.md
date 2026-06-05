# Annageldi Babayev - Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- Dark theme with teal accent colors
- Fully responsive design (mobile & desktop)
- Smooth scroll navigation
- Fade-in animations on page load
- Interactive hover effects
- Mobile-friendly hamburger menu

## Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right corner
3. Select **New repository**
4. Name your repository `BabaevvAnnageldi.github.io`
   - **Important**: For a personal site, the repo name must match `<username>.github.io`
5. Keep it **Public**
6. Click **Create repository**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click **Add file** > **Upload files**
2. Drag and drop `index.html` and `README.md`
3. Click **Commit changes**

**Option B: Using Git Command Line**

```bash
# Navigate to your home folder
cd ~

# Initialize git repository
git init

# Add your files
git add index.html README.md

# Commit the files
git commit -m "Initial portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/BabaevvAnnageldi/BabaevvAnnageldi.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (gear icon)
3. Click **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Website

Your portfolio will be live at:

```
https://BabaevvAnnageldi.github.io
```

It may take 1-2 minutes for the site to become available.

## Customization

### Update Colors

Edit the CSS variables in `index.html`:

```css
:root {
    --accent: #00d4aa;  /* Change accent color */
}
```

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript
- Google Fonts (Poppins)

---

Built by Annageldi Babayev
