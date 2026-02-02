# Marcel Kojo Gyan - Personal Website

A minimal, clean personal portfolio website showcasing work as an artist, designer, developer, and engineer.

## Quick Deploy to GitHub Pages

1. **Create a new repository** on GitHub named `username.github.io` (replace `username` with your GitHub username) or any other name

2. **Push this code** to your repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Personal website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select the `main` branch and `/ (root)` folder
   - Click Save

4. Your site will be live at `https://YOUR_USERNAME.github.io/` (or `https://YOUR_USERNAME.github.io/YOUR_REPO/` if not using `username.github.io`)

## Custom Domain (Optional)

To use a custom domain like `marcelstudios.co`:

1. Add a file named `CNAME` to the root with your domain:
   ```
   www.yourdomain.com
   ```

2. Configure your domain's DNS:
   - Add an A record pointing to `185.199.108.153`
   - Add an A record pointing to `185.199.109.153`
   - Add an A record pointing to `185.199.110.153`
   - Add an A record pointing to `185.199.111.153`
   - Or add a CNAME record pointing to `YOUR_USERNAME.github.io`

## Structure

```
website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Art portfolio images
│   ├── nebula.jpg
│   ├── namemeking.jpg
│   ├── nhyipoleon.png
│   └── dogheaven.png
└── blog/               # Future blog posts
```

## Customization

- **Colors**: Edit CSS variables in `css/style.css` `:root` section
- **Content**: Update text directly in `index.html`
- **Images**: Replace images in the `images/` folder

## Tech Stack

- HTML5
- CSS3 (Custom properties, Grid, Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter, Playfair Display)

---

#WITH♥MARCEL
