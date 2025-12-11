# Mark Otwane - Portfolio Website

A modern, responsive portfolio website showcasing my skills as a Software Engineer specializing in Python, Angular, and NestJS.

## 🚀 Features

-    **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
-    **Dark/Light Theme**: Toggle between themes with smooth transitions
-    **Modern Animations**: Powered by GSAP for smooth, professional animations
-    **Clean Code**: Well-structured HTML, CSS, and JavaScript
-    **Performance Optimized**: Fast loading times and smooth scrolling

## 🛠 Tech Stack

-    **Frontend**: HTML5, CSS3, JavaScript
-    **Animations**: GSAP (GreenSock)
-    **Icons**: Font Awesome
-    **Fonts**: Space Grotesk, Inter (Google Fonts)
-    **Deployment**: Vercel

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── mark.png            # Profile image
├── MARK OTWANE-1.pdf   # Resume/CV
├── public/             # Static assets
│   └── icons/          # SVG icons
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
└── README.md           # This file
```

## 🚀 Deployment on Vercel

### Method 1: Direct Upload

1. **Create a new project on Vercel**

     - Go to [vercel.com](https://vercel.com)
     - Sign in with your GitHub account
     - Click "New Project"

2. **Upload your files**

     - Drag and drop the entire project folder
     - Vercel will automatically detect it's a static site

3. **Configure (if needed)**

     - The `vercel.json` file handles the configuration automatically
     - No build command needed for this static site

4. **Deploy**
     - Click "Deploy"
     - Your site will be live in seconds!

### Method 2: GitHub Integration (Recommended)

1. **Push to GitHub**

     ```bash
     git init
     git add .
     git commit -m "Initial portfolio commit"
     git remote add origin YOUR_GITHUB_REPO_URL
     git push -u origin main
     ```

2. **Connect on Vercel**
     - Import your GitHub repository on Vercel
     - Vercel will automatically deploy on every push

## 🔧 Local Development

1. **Clone the repository**

     ```bash
     git clone YOUR_REPO_URL
     cd portfolio-website
     ```

2. **Open in browser**

     - Simply open `index.html` in your browser
     - Or use a local server:

     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js (if you have it)
     npx serve .
     ```

3. **View locally**
     - Open `http://localhost:8000` in your browser

## 🎨 Customization

### Updating Content

1. **Personal Information**: Edit `index.html` to update:

     - Name and title
     - About section
     - Skills and services
     - Contact information
     - Social media links

2. **Styling**: Modify `style.css` to change:

     - Colors (CSS custom properties at the top)
     - Fonts
     - Layout
     - Animations

3. **Profile Image**: Replace `mark.png` with your own image
4. **Resume**: Replace `MARK OTWANE-1.pdf` with your CV

### Color Scheme

The website uses CSS custom properties for easy theming:

```css
:root {
	--color-primary: #1560bd; /* Main brand color */
	--color-accent: #06b6d4; /* Accent color */
	/* ... more colors */
}
```

## 📱 Browser Support

-    ✅ Chrome (latest)
-    ✅ Firefox (latest)
-    ✅ Safari (latest)
-    ✅ Edge (latest)
-    ✅ Mobile browsers

## 🚨 Troubleshooting

### 404 Error on Vercel

-    Ensure `vercel.json` is in the root directory
-    Check that all file paths are relative (not absolute)
-    Verify all assets (images, CSS, JS) are properly linked

### Images not loading

-    Check file paths in HTML (use `./` for relative paths)
-    Ensure image files are in the correct locations
-    Verify image file names match exactly (case-sensitive)

### Styling issues

-    Clear browser cache
-    Check browser console for CSS errors
-    Ensure `style.css` is properly linked in HTML

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

-    **Email**: otwanemark003@gmail.com
-    **LinkedIn**: [Mark Otwane](https://www.linkedin.com/in/mark-otwane-800871349)
-    **GitHub**: [@MarkOtwane](https://github.com/MarkOtwane)

---

Built with ❤️ by Mark Otwane
