# Jay Prakash Lohar - Portfolio Website

A modern, responsive portfolio website built with React, TypeScript, Tailwind CSS, and Framer Motion. Features a data-driven architecture with glassmorphism design and premium animations.

## 🚀 Quick Start

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation & Development

```bash
# Clone the repository
git clone <YOUR_GIT_URL>
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── Hero.tsx        # Landing section with animated background
│   ├── Navbar.tsx      # Navigation with smooth scrolling
│   ├── About.tsx       # About section with timeline
│   ├── Skills.tsx      # Interactive skills grid with progress rings
│   ├── Projects.tsx    # Project showcase with modal details
│   ├── Contact.tsx     # Contact form and information
│   ├── Footer.tsx      # Footer with social links
│   └── AnimatedBackground.tsx # Particle animation canvas
├── data/               # JSON data files
│   ├── profile.json    # Personal information and experience
│   ├── projects.json   # Project details and case studies
│   └── skills.json     # Technical skills and proficiencies
├── Portfolio.tsx       # Main portfolio component
├── App.tsx            # App wrapper with routing
├── main.tsx          # React entry point
└── index.css         # Global styles and design system

public/
├── screenshots/       # Project screenshots
├── resume.pdf        # Downloadable resume
└── robots.txt       # SEO robots file
```

## 🎨 Design System

The portfolio uses a custom design system with:

- **Colors**: Electric Indigo (#6C63FF) and Teal (#00C2A8)
- **Typography**: Inter (body) and Poppins (headings)
- **Theme**: Dark glassmorphism with neon accents
- **Animations**: Framer Motion with accessibility considerations

## 📝 Content Management

### Updating Personal Information

Edit `src/data/profile.json`:

```json
{
  "name": "Your Name",
  "headline": "Your tagline",
  "role": "Your role and specialization",
  "experience_years": 2,
  "education": "Your education",
  "contact": {
    "email": "your.email@example.com",
    "phone": "+91-XXXXXXXXXX",
    "linkedin": "https://linkedin.com/in/yourprofile",
    "github": "https://github.com/yourusername"
  }
}
```

### Adding/Updating Projects

Edit `src/data/projects.json`:

```json
{
  "featured": [
    {
      "id": "unique-project-id",
      "title": "Project Name",
      "summary": "Brief description",
      "role": "Your role",
      "stack": ["React", "Node.js", "MongoDB"],
      "impact": "Key achievement or metric",
      "period": "2024-01 - 2024-05",
      "images": ["/screenshots/project-1.jpg"],
      "repo": "https://github.com/username/repo",
      "live": "https://project-demo.com"
    }
  ]
}
```

### Updating Skills

Edit `src/data/skills.json`:

```json
{
  "categories": {
    "Frontend": {
      "skills": [
        {
          "name": "React.js",
          "proficiency": 90,
          "tools": ["Hooks", "Context API", "Redux"]
        }
      ]
    }
  }
}
```

### Replacing Resume

1. Replace `public/resume.pdf` with your resume file
2. Update the `resume_path` in `src/data/profile.json` if needed

### Adding Project Screenshots

1. Add images to `public/screenshots/`
2. Update image paths in `src/data/projects.json`
3. Use descriptive filenames (e.g., `project-name-dashboard.jpg`)

## 🎯 Customization Checklist

- [ ] Update `src/data/profile.json` with your information
- [ ] Update `src/data/projects.json` with your projects
- [ ] Update `src/data/skills.json` with your skills
- [ ] Replace `public/resume.pdf` with your resume
- [ ] Add project screenshots to `public/screenshots/`
- [ ] Update social media links in profile.json
- [ ] Customize colors in `src/index.css` if desired
- [ ] Update meta tags in `index.html` for SEO

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌟 Features

- **Responsive Design**: Mobile-first approach with smooth animations
- **Performance Optimized**: Lazy loading, optimized images, and efficient animations
- **SEO Ready**: Meta tags, structured data, and semantic HTML
- **Accessibility**: ARIA labels, keyboard navigation, and reduced motion support
- **Modern Tech Stack**: React 18, TypeScript, Tailwind CSS, Framer Motion
- **Data-Driven**: Easy content updates through JSON files

## 🚢 Deployment

### Using Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with default settings

### Using Netlify

1. Build the project: `npm run build`
2. Deploy the `dist` folder to Netlify

### Manual Deployment

1. Run `npm run build`
2. Upload the `dist` folder to your hosting provider

## 📧 Support

For questions or issues, please contact:

- Email: loharjayprakash4@gmail.com
- LinkedIn: [linkedin.com/in/jay-prakash-lohar-571823236](https://linkedin.com/in/jay-prakash-lohar-571823236)
- GitHub: [github.com/jayprakashlohar](https://github.com/jayprakashlohar)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ using React, TypeScript, and Framer Motion
