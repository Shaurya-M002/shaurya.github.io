# Shaurya's Personal Website

A simple, modern one-page portfolio website built for GitHub Pages.

## 🚀 Quick Start

### Local Development
Simply open `index.html` in your browser to view the site locally.

### Deploy to GitHub Pages

1. **Create a new repository** on GitHub (e.g., `username.github.io` or any repo name)

2. **Initialize git and push** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** section
   - Under **Source**, select `main` branch and `/ (root)` folder
   - Click **Save**
   - Your site will be live at `https://yourusername.github.io/your-repo-name/`

## 📝 Customization

### Update Your Information

1. **Edit `index.html`**:
   - Replace "Shaurya Madukuri" with your name
   - Update the tagline and description
   - Customize project cards with your own projects
   - Update social media links (GitHub, LinkedIn, Email)

2. **Modify Colors** (in `styles.css`):
   ```css
   :root {
       --primary-color: #2563eb;  /* Change to your preferred color */
       --secondary-color: #1e40af;
   }
   ```

3. **Add/Remove Projects**:
   Just copy the `.project-card` div in the HTML and modify the content.

## 🎨 Features

- ✨ Modern, gradient design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎭 Smooth animations and transitions
- 🎯 Clean, professional layout
- ⚡ Fast loading (no heavy dependencies)
- 🔗 Social media integration

## 📁 File Structure

```
shaurya_website/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # Interactive features
└── README.md       # This file
```

## 🛠️ Tech Stack

- Pure HTML5
- CSS3 (with custom properties and animations)
- Vanilla JavaScript
- Google Fonts (Inter)

## 📄 License

Feel free to use this template for your own portfolio!

---

Made with ❤️ by Shaurya

