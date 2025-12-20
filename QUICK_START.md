# Quick Reference Guide

## 🚀 Get Started Quickly

### Open Portfolio in 30 Seconds

**Option 1 - Simplest:**
```
Double-click index.html
```

**Option 2 - Best (with Python):**
```bash
cd "C:\Users\priyanshu\Desktop\ALL Files\MY PROJECTS\fullstackdeveloper"
python -m http.server 8000
```
Then open: `http://localhost:8000`

**Option 3 - VS Code:**
- Right-click `index.html` → "Open with Live Server"

---

## 🎨 Quick Customization

### Change Main Color
Edit `css/style.css`:
```css
:root {
    --primary-color: #006064;  /* ← Change this hex color */
}
```

### Update Your Name
Edit `index.html`:
```html
<span class="logo-text">Your Name Here</span>
```

### Update Email
```html
<a href="mailto:youremail@gmail.com">youremail@gmail.com</a>
```

### Update Phone
```html
<p>+91 1234567890</p>
```

### Add/Edit Project
Find in `index.html`:
```html
<div class="project-card">
    <div class="project-image"></div>
    <h3>Project Name</h3>
    <!-- Edit details here -->
</div>
```

---

## 📝 File Locations

| File | Purpose | Edit For |
|------|---------|----------|
| `index.html` | Content | Text, links, structure |
| `css/style.css` | Design | Colors, fonts, layouts |
| `js/script.js` | Interactions | Animations, form handling |

---

## 🎯 Common Tasks

### Add a New Skill
Find Skills section in `index.html`:
```html
<span class="skill-tag">Your Skill</span>
```

### Add a New Social Link
Find social-links section:
```html
<a href="https://your-link" target="_blank" class="social-icon">
    <i class="fab fa-icon-name"></i>
</a>
```

### Change Particle Count
Edit `js/script.js`:
```javascript
this.particleCount = 50;  // Change 50 to any number
```

### Speed Up Animations
Edit `css/style.css`:
```css
animation: slideInLeft 0.8s ease-out;  /* Change 0.8s to faster time */
```

### Change Font
Edit `css/style.css`:
```css
body {
    font-family: 'Your Font Name', sans-serif;
}
```

---

## 🌓 Theme Colors Reference

### Light Mode
- Primary: #006064 (Teal)
- Secondary: #ff6b6b (Red)
- Background: #ffffff (White)
- Text: #1a1a1a (Dark)

### Dark Mode
- Primary: #00a9b5 (Lighter Teal)
- Background: #1a1a1a (Dark)
- Text: #e0e0e0 (Light)

---

## 📱 Breakpoints

```css
/* Tablet and below */
@media (max-width: 768px)

/* Mobile and below */
@media (max-width: 480px)
```

---

## 🔥 CSS Classes Reference

```html
<!-- Buttons -->
<a class="btn btn-primary">Primary Button</a>
<a class="btn btn-secondary">Secondary Button</a>

<!-- Cards -->
<div class="project-card">Project Card</div>
<div class="info-card">Info Card</div>
<div class="skill-category">Skill Card</div>

<!-- Text Styling -->
<h1 class="section-title">Section Title</h1>
<p class="hero-subtitle">Subtitle</p>
<p class="tech-stack">Tech Stack</p>
```

---

## 🎬 Animation Classes

```css
fadeInUp      /* Fade in while moving up */
slideInLeft   /* Slide in from left */
slideInRight  /* Slide in from right */
slideInUp     /* Slide up */
scaleIn       /* Scale from small to normal */
float         /* Floating up and down */
bounce        /* Bouncing animation */
pulse         /* Pulsing size change */
rotate        /* Continuous rotation */
```

---

## 📞 Contact Section Variables

Edit in `index.html`:
```html
<!-- Phone -->
<p>+91 9071048836</p>

<!-- Email -->
<a href="mailto:showlittlemercy@gmail.com">showlittlemercy@gmail.com</a>

<!-- Location -->
<p>Bangalore, India</p>
```

---

## 🔗 Important Links to Update

In `index.html`, search for and update:
```
LinkedIn: https://www.linkedin.com/in/your-profile/
GitHub: https://github.com/your-username
Instagram: https://www.instagram.com/your-profile/
Portfolio: https://your-portfolio-link.com
```

---

## ✅ Testing Checklist

Before sharing your portfolio:
- [ ] Open in Chrome
- [ ] Open in Firefox
- [ ] Open on mobile phone
- [ ] Test theme toggle (dark/light)
- [ ] Click all buttons
- [ ] Scroll through all sections
- [ ] Test download resume button
- [ ] Test contact form
- [ ] Check all links work
- [ ] Verify all images load

---

## 🐛 If Something Breaks

1. **Check console for errors**: F12 → Console tab
2. **Verify file paths**: All imports should be correct
3. **Clear browser cache**: Ctrl+Shift+Del
4. **Try different browser**: Chrome, Firefox, Safari
5. **Use local server**: Don't open HTML directly

---

## 🎨 Color Palette Suggestions

**Modern Teal** (Current):
- Primary: #006064
- Secondary: #ff6b6b

**Deep Blue**:
- Primary: #003f87
- Secondary: #ff6b9d

**Forest Green**:
- Primary: #1b4332
- Secondary: #ffd60a

**Purple Gradient**:
- Primary: #7209b7
- Secondary: #f72585

**Professional Navy**:
- Primary: #0a3161
- Secondary: #ff6b35

---

## 📱 Mobile Testing

### In Chrome:
1. Press F12 (DevTools)
2. Press Ctrl+Shift+M (Toggle device mode)
3. Choose device size
4. Test interaction

### In Firefox:
1. Press F12
2. Click responsive design mode icon
3. Choose mobile size

---

## 🚀 Before Deploying

### 1. Verify All Links:
- Check all project links
- Verify social media links
- Test contact form
- Test resume download

### 2. Performance:
- Check page load time (should be < 2 seconds)
- Test on 3G connection
- Check on slow phone

### 3. Accessibility:
- Test keyboard navigation (Tab key)
- Check contrast (text readable)
- Test with screen reader

### 4. Responsiveness:
- Test on mobile
- Test on tablet
- Test on desktop
- Test landscape orientation

---

## 📚 HTML Section IDs

Navigate to sections programmatically:
```
#home          → Hero section
#about         → About section
#experience    → Experience section
#projects      → Projects section
#skills        → Skills section
#certifications → Certifications
#publications  → Publications
#contact       → Contact section
```

---

## 🔐 Form Validation

Contact form validates:
- ✅ Name (required)
- ✅ Email (valid format)
- ✅ Subject (required)
- ✅ Message (required)

Currently shows toast notifications but doesn't email. To enable emails:
1. Use Formspree
2. Use EmailJS
3. Set up backend server

---

## 🎯 Next Steps

1. **Customize content** - Update all personal information
2. **Add project images** - Replace gradient backgrounds
3. **Set up email** - Enable contact form
4. **Test thoroughly** - All devices and browsers
5. **Deploy** - Choose hosting platform
6. **Share** - Send to employers/clients
7. **Maintain** - Keep content updated

---

## 💻 Text Editor Shortcuts

### VS Code:
- Find: Ctrl+F
- Replace: Ctrl+H
- Format: Alt+Shift+F
- Save: Ctrl+S

---

## 🎓 Learning Path

After this portfolio, explore:
1. JavaScript frameworks (React, Vue)
2. Backend development (Node.js, Python)
3. Database design (PostgreSQL, MongoDB)
4. Deployment & DevOps
5. Advanced CSS frameworks

---

## 📞 Quick Support

**Issue**: Text looking wrong
→ Check font loading in CSS

**Issue**: Colors different than expected
→ Check CSS variables (root section)

**Issue**: Animations not smooth
→ Use local server instead of direct file

**Issue**: Mobile layout broken
→ Check viewport meta tag in HTML

**Issue**: Form not working
→ Check console (F12) for JavaScript errors

---

**Remember**: When in doubt, use browser DevTools (F12) to inspect and debug!

Made with ❤️ for Easy Customization | December 2025
