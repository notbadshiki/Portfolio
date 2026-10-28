# Portfolio Website

A clean, modern portfolio website built with Tailwind CSS, inspired by minimalist design principles.

## Features

- 📱 Fully responsive design
- 🎨 Clean and modern UI using Tailwind CSS
- 📄 Multiple sections: Hero, About, Work, Resume, Contact
- 🔗 Smooth scrolling navigation
- 📱 Mobile-friendly navigation menu
- ⚡ Fast loading (uses Tailwind CDN)

## Sections

1. **Hero** - Introduction and overview
2. **About** - Detailed background and interests
3. **Work** - Project portfolio with descriptions
4. **Resume** - Complete professional resume
5. **Contact** - Contact information and social links

## How to Customize

### 1. Personal Information
Replace placeholder text with your information:
- Your name (appears in navigation and hero section)
- Your title/profession
- Location
- Email and phone number

### 2. Hero Section
- Update the main heading with your name
- Add your current role and years of experience
- Write a compelling introduction paragraph
- Update "Currently studying" section

### 3. About Section
- Write 2-3 paragraphs about your background
- Update the three key areas: Studying, Interested in, Also exploring

### 4. Work/Projects Section
- Add your projects (currently has 3 placeholders)
- For each project, include:
  - Project type and time period
  - Project name
  - Description
  - Technologies used (tags)
  - Optional: Add project icons/images

### 5. Resume Section
- Update your objective statement
- List your skills and qualifications
- Add your projects with descriptions
- Fill in educational background
- List achievements
- Add character references with contact info

### 6. Contact Section
- Update email address
- Update phone number
- Add social media links (GitHub, LinkedIn, etc.)

### 7. Colors (Optional)
You can customize the color scheme by modifying Tailwind classes:
- Primary color: Currently uses default gray scale
- To change, replace classes like `bg-gray-50`, `text-gray-600`, etc.
- Or add custom colors in the `<style>` section

## Running the Site

### Option 1: Open Directly
Simply double-click `index.html` to open in your browser.

### Option 2: Use a Local Server
For better development experience:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

You can deploy this site to any static hosting service:

- **Vercel**: Perfect for quick deployment
  1. Push to GitHub
  2. Import project in Vercel
  3. Deploy!

- **Netlify**: Drag and drop deployment
  1. Go to netlify.com
  2. Drag the project folder
  3. Done!

- **GitHub Pages**: Free hosting
  1. Push to GitHub repository
  2. Enable GitHub Pages in settings
  3. Your site will be at `username.github.io/repo-name`

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript (for mobile menu and smooth scrolling)
- Google Fonts (Inter)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Tips for Customization

1. **Add Images**: Replace the gray placeholder boxes with actual project images
2. **Custom Font**: Change the Google Fonts import to use your preferred font
3. **Icons**: Add more icon links in the contact section
4. **Animations**: Add Tailwind animation classes for subtle effects
5. **Dark Mode**: Add dark mode support using Tailwind's dark mode feature

## License

Feel free to use this template for your own portfolio!
