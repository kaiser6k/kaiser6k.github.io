# Kyle A. Behrman - Cybersecurity & IT Support Professional

A professional, responsive portfolio website showcasing your web development experience, projects, and skills as a technical professional and Army Veteran.

## Features

✓ **Responsive Design** - Works beautifully on desktop, tablet, and mobile devices
✓ **Modern Styling** - Clean, professional aesthetic with smooth animations
✓ **Easy to Customize** - Simple HTML/CSS/JavaScript structure
✓ **SEO Ready** - Semantic HTML markup
✓ **Fast Loading** - No external dependencies, pure HTML/CSS/JavaScript
✓ **Multiple Sections**:
  - Hero/Landing section
  - About Me
  - Featured Projects
  - Skills & Expertise
  - Professional Experience Timeline
  - Education & Certifications
  - Contact Information

## File Structure

```
.
├── index.html      # Main portfolio page
├── styles.css      # All styling
├── script.js       # Interactive elements
└── README.md       # This file
```

## How to Use Locally

### Quick Start
1. Open `index.html` directly in your web browser
2. Or run a local server:

**Python 3:**
```bash
python3 -m http.server 8000
```
Then navigate to `http://localhost:8000`

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Node.js (if installed):**
```bash
npx http-server
```

## Deployment Options

### Option 1: GitHub Pages (Recommended)
1. Create a GitHub account at github.com (if you don't have one)
2. Create a new repository named `username.github.io` (replace "username" with your GitHub username)
3. Upload these files (index.html, styles.css, script.js) to the repository
4. Your portfolio will be live at `https://username.github.io`

### Option 2: Netlify (Free)
1. Go to https://netlify.com
2. Sign up with GitHub or email
3. Drag and drop this folder into Netlify
4. Your site is live instantly with a Netlify URL
5. Connect a custom domain if you have one

### Option 3: Vercel (Free)
1. Go to https://vercel.com
2. Sign up and import your GitHub repository
3. Deploy with one click
4. Live at your custom domain

### Option 4: Traditional Hosting
1. Use any web hosting provider (GoDaddy, Bluehost, etc.)
2. Upload files via FTP or file manager
3. Make sure files are in the root directory or a designated public folder

### Option 5: Your Own Domain
1. Register a domain (GoDaddy, Namecheap, etc.)
2. Point it to GitHub Pages, Netlify, or your hosting provider
3. Upload the files to your hosting

## Customization

### Edit Your Information
Open `index.html` and update:
- Contact information (email, phone)
- Social links
- Project descriptions
- Skills list
- Experience timeline
- Education details

### Change Colors
Edit `styles.css` - look for the `:root` section at the top:
```css
:root {
    --primary-color: #2c3e50;        /* Dark blue */
    --accent-color: #3498db;          /* Light blue */
    --accent-dark: #2980b9;           /* Darker blue */
    --text-color: #333;
    --light-bg: #f8f9fa;
    --border-color: #e0e0e0;
    --success-color: #27ae60;
}
```

### Add More Projects
Copy a project card in the projects section and modify:
```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <p class="project-date">Your Date</p>
    </div>
    <p class="project-description">Your description here...</p>
    <div class="project-features">
        <h4>Key Accomplishments:</h4>
        <ul>
            <li>Feature 1</li>
            <li>Feature 2</li>
        </ul>
    </div>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
</div>
```

## Mobile Responsiveness

The portfolio automatically adapts to:
- **Desktop** (1200px and above) - Full layout
- **Tablet** (768px - 1199px) - Adjusted grid and spacing
- **Mobile** (below 768px) - Single column layout, hamburger menu

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Tips for Success

1. **Add a Profile Photo** (Optional)
   - Add to the About section
   - Keep it professional (headshot or professional photo)

2. **Add GitHub Links**
   - Modify the project cards to include links to your GitHub repositories
   - Add social media links in the footer

3. **SEO Optimization**
   - Update the `<title>` tag in index.html
   - Update meta descriptions
   - Keep content relevant and well-formatted

4. **Performance**
   - The site is already very fast
   - Consider adding Google Analytics if desired
   - Optimize any images you add (keep under 500KB)

5. **Regular Updates**
   - Keep your projects and experience current
   - Update skills as you learn new technologies
   - Share your portfolio link on:
     - LinkedIn
     - GitHub
     - Your resume/CV
     - Email signature

## Need Help?

- **Netlify Docs**: https://docs.netlify.com
- **GitHub Pages Guide**: https://pages.github.com
- **HTML/CSS Reference**: https://developer.mozilla.org/en-US/docs/Web
- **CSS Customization**: Feel free to modify styles.css

## License

This portfolio is yours to use, modify, and deploy freely.

---

Happy sharing your work! Your portfolio is now ready to impress potential employers and clients.
