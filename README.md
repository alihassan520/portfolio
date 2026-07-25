# Ali Hassan - Portfolio Website

A clean, professional, and responsive one-page portfolio website built with HTML, CSS, Bootstrap 5, and JavaScript.

## 📋 Features

- **Responsive Design** – Works perfectly on mobile, tablet, and desktop screens
- **Modern Layout** – Clean and professional design using Bootstrap 5
- **One-Page Navigation** – Smooth scrolling between sections
- **Professional Sections** – About, Services, Portfolio, and Contact
- **Simple Profile Image** – SVG avatar included (easily replaceable)
- **Beginner-Friendly** – Well-structured code with comments for learning

## 🛠 Technologies Used

- **HTML5** – Page structure and semantics
- **CSS3** – Custom styling and animations
- **Bootstrap 5** – Responsive grid and component system
- **JavaScript** – Simple interactive functionality
- **Google Fonts** – Modern typography (Poppins font)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main website file
├── styles.css          # Custom CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/
    └── avatar.svg      # Profile image (SVG format)
```

## 🚀 How to View

### Option 1: Using Python (Recommended for Beginners)
1. Open a terminal in the portfolio folder
2. Run: `python -m http.server 8000`
3. Open your browser and go to: `http://127.0.0.1:8000`

### Option 2: Publish on GitHub Pages
1. Create a GitHub repository for this project
2. Push all files to GitHub
3. In GitHub, go to **Settings > Pages**
4. Under **Source**, choose **GitHub Actions**
5. The workflow in `.github/workflows/deploy.yml` will publish your site automatically
6. After deployment finishes, your site will be available at:
   `https://your-username.github.io/your-repository-name/`

> Important: If your repository name is `portfolio`, your site URL will be `https://your-username.github.io/portfolio/`

### Option 2: Direct File
Simply double-click `index.html` to open it in your default browser.

### Option 3: Using Live Server (VS Code Extension)
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"

## 🎨 Customization Guide

### Change Your Name
Edit `index.html` and replace "Ali Hassan" with your name:
```html
<title>Your Name | Web Developer</title>
<a class="navbar-brand fw-bold" href="#home">Your Name</a>
<h1 class="display-4 fw-bold mb-3">Hello, I'm Your Name</h1>
```

### Change Profile Image
Replace the SVG avatar with your own image:
1. Save your image as `assets/profile.jpg` (or .png)
2. Update `index.html` line with the image:
```html
<img src="assets/profile.jpg" alt="Your Name profile" class="profile-image mb-3" />
```

### Update Your Skills
Edit the skills section in `index.html`:
```html
<li class="mb-2">• Your Skill 1</li>
<li class="mb-2">• Your Skill 2</li>
<li class="mb-2">• Your Skill 3</li>
<li>• Your Skill 4</li>
```

### Add Your Projects
In the Portfolio section, update the project cards:
```html
<h4 class="fw-bold">Your Project Name</h4>
<p class="text-muted">Your project description here.</p>
```

### Update Contact Information
Edit the contact section with your real email:
```html
<p class="mb-0">your-email@example.com</p>
```

### Change Colors
Edit `styles.css` and modify the color variables:
```css
:root {
  --primary-color: #2563eb;      /* Change to your brand color */
  --secondary-color: #0f172a;    /* Dark color */
  --accent-color: #38bdf8;       /* Highlight color */
  --text-color: #334155;         /* Text color */
}
```

## 💡 Next Steps to Improve

1. **Add Real Content**
   - Replace placeholder text with your actual information
   - Add your real projects and descriptions
   - Update contact details

2. **Add a Profile Photo**
   - Replace the SVG avatar with your actual photo
   - Use JPG, PNG, or keep the SVG format

3. **Add Hover Effects** (in `script.js`)
   - Make buttons glow on hover
   - Add smooth transitions

4. **Add More Interactivity**
   - Create a contact form that works
   - Add a smooth scroll effect
   - Add animations when sections come into view

5. **Deploy Online**
   - Use GitHub Pages (free hosting)
   - Use Netlify or Vercel
   - Use traditional web hosting

## 📚 Learning Resources

- **Bootstrap Docs**: https://getbootstrap.com/docs/5.3/
- **CSS Tutorial**: https://www.w3schools.com/css/
- **JavaScript Basics**: https://www.w3schools.com/js/
- **HTML Guide**: https://www.w3schools.com/html/

## 🔧 File Breakdown

### index.html
- Contains all the HTML structure
- Includes links to CSS, Bootstrap, and JavaScript
- Divided into sections: Hero, About, Services, Portfolio, Contact

### styles.css
- Custom colors and typography
- Responsive breakpoints
- Button and card styling
- Profile image styling

### script.js
- Sets the current year in the footer automatically
- Can be expanded for more interactivity

### assets/avatar.svg
- Simple SVG profile image
- Can be replaced with your own photo

## 📝 Notes for Beginners

- **HTML** is the structure (what content goes on the page)
- **CSS** is the styling (how it looks)
- **Bootstrap** makes responsive design easier
- **JavaScript** adds interactivity (things that respond to clicks, scrolling, etc.)

Change things one at a time and refresh the browser to see the changes!

## 📄 License

This project is open source and free to use and modify.

---

Happy coding! 🚀 Keep improving step by step.
