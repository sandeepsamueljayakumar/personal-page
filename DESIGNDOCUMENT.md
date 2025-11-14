# Personal Website Design Document

**Project:** Personal Portfolio Website  
**Author:** Sandeep Samuel Jayakumar  
**Repository:** https://github.com/sandeepsamueljayakumar/personal-page  
**Date:** November 2025

---

## 1. Project Overview

**Purpose:** Professional portfolio website showcasing technical skills, projects, and achievements for career advancement and networking.

**Target Audience:**
- Tech recruiters and employers
- Academic peers and professors  
- Potential clients and collaborators

**Key Objectives:**
- Showcase programming projects
- Highlight education and experience
- Enable professional networking
- Demonstrate web development skills

## 2. Technical Stack

| Component | Technology |
|-----------|-----------|
| **Hosting** | GitHub Pages |
| **Frontend** | HTML5, CSS3, JavaScript ES6+ |
| **Framework** | Bootstrap 5 |
| **Version Control** | Git/GitHub |
| **Analytics** | Google Analytics 4 |
| **Build Tool** | Jekyll (optional) |

## 3. Site Architecture

```
personal-page/
├── index.html         # Homepage
├── about.html         # Bio/Skills
├── portfolio.html     # Projects
├── resume.html        # Experience
├── contact.html       # Contact form
├── assets/
│   ├── css/          # Stylesheets
│   ├── js/           # Scripts
│   ├── images/       # Media files
│   └── documents/    # Resume PDF
├── CNAME             # Custom domain
└── README.md         # Documentation
```

## 4. Design Specifications

### Color Scheme
- **Primary:** #1a1a2e (Dark Navy)
- **Accent:** #e94560 (Vibrant Red)
- **Background:** #ffffff (White)
- **Text:** #333333 (Dark Gray)

### Typography
- **Headings:** Montserrat, sans-serif
- **Body:** Open Sans, sans-serif
- **Code:** Fira Code, monospace

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 991px
- Desktop: ≥ 992px

## 5. Page Components

### Homepage
- Hero section with name and title
- Brief introduction
- Featured projects (3-4)
- Call-to-action buttons

### About Page
- Professional summary
- Education (Northeastern University)
- Skills with proficiency levels
- Interests (soccer, travel, gaming)

### Portfolio Page
- Project cards with:
  - Title and description
  - Technologies used
  - GitHub/Demo links
  - Screenshot thumbnails
- Featured projects:
  - JobTracker (MERN)
  - StyleSmart Wardrobe
  - Calendar Application

### Resume Page
- Experience timeline
- Education details
- Certifications
- Downloadable PDF

### Contact Page
- Contact form (name, email, message)
- Social media links
- Professional email

## 6. Key Features

### Performance
- Page load < 3 seconds
- Optimized images (WebP/JPEG)
- Minified CSS/JS
- Lazy loading

### SEO
- Meta tags and descriptions
- XML sitemap
- Structured data
- Clean URLs

### Accessibility
- WCAG 2.1 AA compliant
- Semantic HTML
- Keyboard navigation
- Alt text for images

## 7. Content Guidelines

### Project Descriptions
- **Format:** Title (3-5 words)
- **Description:** 50-75 words
- **Tech stack:** Badge format
- **Links:** GitHub and live demo

### Professional Bio
- **Length:** 150-200 words
- **Include:** Current role, education, expertise, goals
- **Tone:** Professional yet personable

## 8. Deployment

### GitHub Pages Setup
```bash
# Push to repository
git add .
git commit -m "Deploy site"
git push origin main

# Enable in Settings > Pages
# Source: Deploy from branch (main)
```

### Custom Domain (Optional)
Create `CNAME` file:
```
www.sandeepsamuel.com
```

## 9. Testing Checklist

- [ ] Mobile responsiveness
- [ ] Cross-browser compatibility (Chrome, Firefox, Safari, Edge)
- [ ] Form validation
- [ ] Broken links
- [ ] Loading speed (< 3s)
- [ ] SEO meta tags
- [ ] Accessibility standards

## 10. Maintenance

| Task | Frequency |
|------|-----------|
| Content updates | Weekly |
| Portfolio additions | As needed |
| Performance audit | Monthly |
| Dependency updates | Quarterly |
| Design refresh | Annually |

## 11. Future Enhancements

**Phase 1 (Immediate)**
- Deploy basic site
- Add 5-6 projects
- Implement contact form

**Phase 2 (3 months)**
- Blog section
- Dark mode toggle
- Animations

**Phase 3 (6 months)**
- PWA features
- Newsletter integration
- Advanced portfolio filters

---

## Quick Start

1. **Clone repository:**
   ```bash
   git clone https://github.com/sandeepsamueljayakumar/personal-page.git
   ```

2. **Customize content:**
   - Update `index.html` with your information
   - Add project images to `assets/images/`
   - Modify CSS in `assets/css/style.css`

3. **Deploy:**
   - Push changes to GitHub
   - Enable GitHub Pages in repository settings

4. **Verify:**
   - Visit: `https://sandeepsamueljayakumar.github.io/personal-page`

---

**Success Metrics:**
- Lighthouse score > 90
- Mobile-friendly test: Pass
- Load time < 3 seconds
- Zero hosting cost