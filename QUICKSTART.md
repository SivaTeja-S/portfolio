# Quick Start Guide

## Getting Started in 5 Minutes

### 1. Install Dependencies
```bash
cd portfolio-website
npm install
```

### 2. Customize Your Information
Open [`src/data/portfolioData.js`](src/data/portfolioData.js) and update:

```javascript
export const personalInfo = {
  name: "Your Name",              // Change this
  title: "Full Stack Developer",  // Your title
  email: "your.email@example.com", // Your email
  phone: "+1 (555) 123-4567",     // Your phone
  location: "San Francisco, CA",   // Your location
  social: {
    github: "https://github.com/yourusername",
    linkedin: "https://linkedin.com/in/yourusername",
    twitter: "https://twitter.com/yourusername",
  }
};
```

### 3. Add Your Projects
In the same file, update the `projects` array:

```javascript
export const projects = [
  {
    id: 1,
    title: "Your Project Name",
    description: "Short description",
    longDescription: "Detailed description",
    image: "https://your-image-url.com",
    tags: ["React", "Node.js"],
    category: "Full Stack",
    github: "https://github.com/...",
    demo: "https://your-demo.com",
    featured: true
  },
  // Add more projects...
];
```

### 4. Update Your Skills
Modify the `skills` object:

```javascript
export const skills = {
  "Frontend": [
    "React", "Vue.js", "Your Skills..."
  ],
  "Backend": [
    "Node.js", "Python", "Your Skills..."
  ],
  // Add more categories...
};
```

### 5. Run the Development Server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser!

## Customizing Colors

Edit [`src/styles/index.css`](src/styles/index.css):

```css
:root {
  --primary-color: #6366f1;    /* Main brand color */
  --secondary-color: #8b5cf6;  /* Secondary accent */
  --accent-color: #ec4899;     /* Highlights */
}
```

## Building for Production

```bash
npm run build
```

The production-ready files will be in the `dist` folder.

## Deploy to Vercel (Free & Fast)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "Import Project"
4. Select your repository
5. Click "Deploy"

Done! Your portfolio is live! 🎉

## Next Steps

- Replace placeholder images with your own
- Set up EmailJS for the contact form ([Guide](https://www.emailjs.com/docs/))
- Add your resume PDF to the `public` folder
- Customize the theme colors
- Add more projects as you complete them

## Need Help?

Check the full [README.md](README.md) for detailed documentation.
