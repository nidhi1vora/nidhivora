# Personal Portfolio Website Template v2

A modern, dark-themed portfolio template for CS students with a sidebar navigation layout.

## Features

- 🌙 Dark theme with modern design
- 📱 Fully responsive (mobile-friendly)
- 🎨 Sidebar navigation layout
- ⚡ Smooth animations and transitions
- 🚀 Easy to customize
- 📄 Resume download section
- 🔗 Integrated social links

## Design Differences from v1

This version features:
- **Sidebar navigation** instead of top navbar
- **Dark theme** with purple/indigo accent colors
- **Card-based layout** for projects and sections
- **Skills section** integrated into About
- **Different visual hierarchy** and typography
- **Hover animations** and scroll effects

## Setup Instructions

### 1. Fork or Clone This Repository

If you're using this as a template:
- Fork this repository to your GitHub account
- Or clone it locally and push to your own repository

### 2. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be available at `https://yourusername.github.io/repository-name/`

### 3. Customize Your Portfolio

#### Update `index.html`:

1. **Replace "Your Name"** with your actual name
2. **Update profile avatar initials** - change "YN" in the profile-avatar div
3. **Update the About section** with your own information
4. **Customize skills** - modify the skill tags in the skills section
5. **Add your projects** - update project titles, descriptions, and tech badges
6. **Update resume link** - replace `jakes-resume.pdf` with your resume filename
7. **Update contact information**:
   - Replace email address
   - Update GitHub and LinkedIn URLs

#### Update `styles.css` (Optional):

- Change color scheme by modifying CSS variables in `:root`:
  ```css
  --primary: #6366f1;        /* Main accent color */
  --primary-dark: #4f46e5;   /* Darker shade */
  --accent: #8b5cf6;         /* Secondary accent */
  --bg-dark: #0f172a;        /* Background color */
  ```

#### Add Your Resume:

- Place your resume PDF in the portfolio-2 folder
- Update the filename in `index.html` if different from `jakes-resume.pdf`

### 4. Commit and Push

```bash
git add .
git commit -m "Customize portfolio"
git push
```

Your changes will be live on GitHub Pages within a few minutes!

## File Structure

```
portfolio-2/
├── index.html      # Main HTML file
├── styles.css      # Styling
├── script.js       # JavaScript for interactivity
├── README.md       # This file
└── your-resume.pdf # Your resume (add this)
```

## Customization Ideas

- Change the profile avatar to an actual image
- Add project screenshots or images
- Customize the color scheme to match your brand
- Add more sections (Education, Experience, Blog)
- Integrate a contact form
- Add a light/dark mode toggle
- Add more animations or micro-interactions
- Include a blog or writing section

## Tips

- Keep your projects section updated with your latest work
- Use consistent tech badges across projects
- Test your site on mobile devices (sidebar collapses on mobile)
- Keep the design clean and professional
- Update your resume regularly
- Customize the skills section to match your expertise

## Color Scheme

The default color scheme uses:
- **Primary**: Indigo (#6366f1)
- **Accent**: Purple (#8b5cf6)
- **Background**: Dark slate (#0f172a)
- **Cards**: Slate (#1e293b)

Feel free to customize these to match your preferences!

## License

Feel free to use this template for your personal portfolio!

## Support

If you have questions or need help customizing, feel free to:
- Check GitHub Pages documentation
- Look at other portfolio examples
- Ask for help in CS communities

---

**Happy coding! 🚀**

