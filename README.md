# Junior Game Designer ePortfolio
## Sandaru Nanayakkara

A complete, professional ePortfolio website showcasing game design projects, skills, and experience.

---

## 🎨 COLOR PALETTE

- **Background**: `#0D1117` (Dark grey-blue)
- **Text**: `#E6E6E6` (Light grey)
- **Accent Primary**: `#00ADB5` (Teal/Cyan)
- **Accent Secondary**: `#393E46` (Grey)
- **Highlight**: `#FFD369` (Golden yellow)

---

## 📁 WEBSITE STRUCTURE

```
Website/
├── index.html          → Home page (About + Vision)
├── projects.html       → Projects showcase (10 projects)
├── cv.html            → CV/Resume page
├── pitch.html         → Video pitch page
├── contact.html       → Contact information & form
└── assets/
    ├── css/
    │   └── styles.css → Main stylesheet
    ├── images/        → Project images (add your screenshots here)
    └── Sandaru_Nanayakkara_Junior_Game_Designer_CV.pdf → Your CV file
```

---

## ✅ NEXT STEPS TO COMPLETE YOUR PORTFOLIO

### 1. **Add Your CV PDF**
- Create a PDF version of your CV
- Save it as `Sandaru_Nanayakkara_Junior_Game_Designer_CV.pdf`
- Place it in the `assets/` folder
- The download button on `cv.html` is already linked to this file

### 2. **Add Project Images**
- Add screenshots/images of your projects to `assets/images/`
- Recommended filenames:
  - `tower-defense.jpg`
  - `pixel-adventure.jpg`
  - `space-shooter.jpg`
  - `robot-3d.jpg`
  - `environment-3d.jpg`
  - `educational-website.jpg`
  - `safety-website.jpg`
  - `military-sim.jpg`
  - `vr-app.jpg`
  - `mobile-app.jpg`
- Images will automatically display when files exist
- If no image exists, emoji placeholders will show instead

### 3. **Add Your Profile Photo (Optional)**
- Add a professional headshot as `assets/images/profile.jpg`
- The site currently shows an "SN" logo placeholder
- Your photo will automatically appear when the file exists

### 4. **Embed Your Panopto Video**
- Record your 5-minute video pitch on Panopto
- Set video visibility to "Public" or "Unlisted"
- Get the embed code or share URL from Panopto
- Open `pitch.html` and find the video section (around line 53)
- Replace the placeholder with your iframe embed code

**Example:**
```html
<div class="video-wrapper">
    <iframe src="https://ecu.ap.panopto.com/Panopto/Pages/Embed.aspx?id=YOUR-VIDEO-ID"
            width="100%" 
            height="100%" 
            allowfullscreen>
    </iframe>
</div>
```

### 5. **Update Social Media Links**
- Open `contact.html`
- Update the LinkedIn, GitHub, and ArtStation URLs (around line 83-97)
- Replace placeholder URLs with your actual profile links
- If you don't have these profiles, create them or remove the links

### 6. **Customize Content (Optional)**
- Feel free to edit any text in the HTML files
- Update project descriptions in `projects.html`
- Add more personal details to `index.html`
- Modify the CV content in `cv.html`

---

## 🚀 HOW TO VIEW YOUR WEBSITE

### Option 1: Open Directly in Browser
1. Navigate to your Website folder
2. Double-click `index.html`
3. Your default browser will open the site

### Option 2: Use VS Code Live Server
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Website will open with auto-refresh on save

### Option 3: Host Online
- **GitHub Pages**: Push to GitHub and enable Pages
- **Netlify**: Drag and drop the Website folder
- **Vercel**: Connect your repository
- **PebblePad/Wix**: Import the HTML and CSS files

---

## 📋 PAGE BREAKDOWN

### 🏠 **index.html** - Home Page
- Hero section with name and tagline
- About Me section with profile
- Vision statement
- Navigation to all other pages

### 🎮 **projects.html** - Projects Showcase
- 10 project cards in responsive grid
- Each card includes: image, title, date, tools, role, description
- Call-to-action buttons to CV and Contact

### 📄 **cv.html** - CV/Resume
- Complete curriculum vitae with sections:
  - Profile
  - Education
  - Key Projects
  - Technical Skills
  - Professional Skills
  - Contact Information
- Download CV button

### 🎥 **pitch.html** - Video Pitch
- Embedded Panopto video player
- Pitch description and topics covered
- Instructions for embedding your video
- Call-to-action buttons

### 📞 **contact.html** - Contact Page
- Contact information (email, phone, location)
- Social media links (LinkedIn, GitHub, ArtStation)
- Contact form (needs backend setup to work)
- Quick navigation to all pages

---

## 🎯 FEATURES

✅ **Responsive Design** - Works on desktop, tablet, and mobile
✅ **Modern Color Scheme** - Game design aesthetic with dark theme
✅ **Smooth Animations** - Hover effects and transitions
✅ **Mobile Menu** - Hamburger menu for small screens
✅ **Accessible** - Semantic HTML and proper contrast ratios
✅ **Professional** - Clean layout and typography
✅ **Fast Loading** - Optimized CSS with no external dependencies (except Google Fonts)

---

## 🔧 TECHNICAL DETAILS

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox/grid
- **Vanilla JavaScript** - Mobile menu toggle (no frameworks needed)
- **Google Fonts** - Montserrat & Open Sans
- **No Dependencies** - Pure HTML/CSS/JS

---

## 💡 TIPS FOR HIGH MARKS

1. ✅ **Add real project images** - Screenshots make a huge difference
2. ✅ **Record a confident video pitch** - Practice before recording
3. ✅ **Update all placeholder content** - Make it personal and authentic
4. ✅ **Test on multiple devices** - Check mobile, tablet, desktop
5. ✅ **Proofread everything** - Check for typos and grammar
6. ✅ **Update social media links** - LinkedIn is especially important
7. ✅ **Add your CV PDF** - Make sure the download works
8. ✅ **Show your personality** - Let your passion shine through

---

## 📧 CONTACT INFORMATION IN PORTFOLIO

- **Email**: sandaruabisheka01@gmail.com
- **Phone**: 0764035803
- **Location**: Perth, Western Australia
- **University**: Edith Cowan University

---

## 🎨 DESIGN PHILOSOPHY

This portfolio follows modern game designer aesthetic:
- **Dark Mode** - Professional and easy on the eyes
- **Teal Accent** - Stands out without being overwhelming
- **Clean Layout** - Easy navigation and clear hierarchy
- **Hover Effects** - Interactive and engaging
- **Typography** - Clear, readable, and stylish

---

## 🆘 TROUBLESHOOTING

**Q: Images aren't showing?**
A: Make sure image files are in `assets/images/` with correct filenames. The site will show emoji placeholders if images are missing.

**Q: CV download isn't working?**
A: Add your PDF file to the `assets/` folder with the exact filename: `Sandaru_Nanayakkara_Junior_Game_Designer_CV.pdf`

**Q: Contact form isn't sending emails?**
A: The form needs a backend service. Use FormSpree, Netlify Forms, or connect to a PHP mail handler.

**Q: Video isn't showing?**
A: Make sure your Panopto video is set to Public/Unlisted and you've replaced the placeholder with your embed code.

**Q: Menu not working on mobile?**
A: Make sure JavaScript is enabled in your browser. The hamburger menu uses JavaScript for toggle functionality.

---

## 📝 LICENSE

This portfolio template is created for Sandaru Nanayakkara's educational purposes at Edith Cowan University.

---

## 🎓 ACADEMIC CONTEXT

This ePortfolio is created for:
- **Course**: Bachelor of Design (Interactive Media)
- **Institution**: Edith Cowan University
- **Purpose**: Part 2b of ePortfolio assessment
- **Date**: 2025

---

**Good luck with your portfolio! 🚀🎮**

*Remember: Your portfolio represents YOU. Make it personal, professional, and authentic!*
