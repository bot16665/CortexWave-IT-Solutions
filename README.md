# ITCore Solutions - Website

Complete website for ITCore Solutions - an IT setup and support services company.

## 📁 Project Structure

```
d:/nigga you ass hole/
├── index.html           # Homepage
├── services.html        # Services page with detailed descriptions
├── pricing.html         # Pricing & packages
├── contact.html         # Contact form & information
├── css/
│   └── style.css        # Main stylesheet with all styling
├── js/
│   └── script.js        # Interactive functionality (FAQ, form validation, etc.)
└── assets/              # For images, logos, etc.
```

## 🚀 Quick Start

1. **Open the website:**
   - Open `index.html` in your web browser
   - Or use a local server for better performance

2. **Navigate between pages:**
   - Use the navigation menu in the header
   - All links are fully functional

3. **Interactive features:**
   - FAQ accordion (click to expand/collapse)
   - Contact form with validation
   - Smooth scrolling
   - Animated statistics

## 📄 Pages Included

### 1. **Homepage (index.html)**
   - Hero section with call-to-action
   - Services overview grid
   - Computer Lab setup section
   - Features/Why Choose Us section
   - FAQ section
   - Statistics with animated counters

### 2. **Services (services.html)**
   - Detailed service descriptions:
     - PC Assembly
     - OS Installation
     - Software Setup
     - Hardware Repair
     - Networking
     - College Lab Contracts
   - Full-width layouts with descriptions

### 3. **Pricing (pricing.html)**
   - Three pricing tiers:
     - Individuals & Small Offices
     - Engineering Colleges & Institutes
     - AMC Annual Maintenance
   - Service comparison table
   - FAQ section

### 4. **Contact (contact.html)**
   - Contact form with validation
   - Multiple contact methods
   - Service area information
   - FAQ section
   - Quick contact buttons

## 🎨 Design Features

- **Dark Theme:** Professional dark background (#1a1410) with orange accents
- **Responsive:** Mobile-friendly design that works on all devices
- **Color Scheme:**
  - Primary: Orange (#ff8c00)
  - Background: Dark Brown (#1a1410)
  - Cards: Dark Gray (#2a2218)
  - Text: Light Gray (#e0e0e0)

## 💻 JavaScript Features

- **FAQ Accordion:** Click questions to expand/collapse answers
- **Form Validation:** Contact form validates all required fields
- **Counter Animation:** Animated statistics on homepage
- **Smooth Scrolling:** Click internal links for smooth scroll effect
- **Active Navigation:** Highlights current page in menu

## 📝 How to Customize

### Change Company Information
Edit the following in each HTML file:
- Logo text: Replace "⬚" icon in the `.logo` element
- Contact details: Update phone, email, WhatsApp numbers
- Service area: Modify "Maharashtra" references
- Footer information

### Update Colors
Edit `:root` variables in `css/style.css`:
```css
--primary-color: #ff8c00;
--dark-bg: #1a1410;
--text-light: #e0e0e0;
```

### Add Images
Place images in the `assets/` folder and update image paths:
```html
<img src="assets/your-image.png" alt="Description">
```

## 🔧 Form Integration

The contact form currently logs data to the browser console. To make it functional:

1. **Using PHP (server-side):**
   - Create a PHP handler file
   - Update form action attribute
   - Process and store submissions

2. **Using JavaScript services:**
   - Integrate with EmailJS, Formspree, or similar
   - Update the form submission in `js/script.js`

## 📱 Responsive Breakpoints

- **Desktop:** 1200px and above
- **Tablet:** 768px - 1199px
- **Mobile:** Below 768px
- **Small Mobile:** Below 480px

## ✨ Features

✅ Fully responsive design
✅ Dark theme with modern styling
✅ Interactive FAQ accordion
✅ Contact form with validation
✅ Animated statistics
✅ Multiple service pages
✅ Pricing comparison
✅ Professional layout
✅ Mobile-friendly navigation
✅ Quick contact options

## 🎯 SEO Considerations

- Proper meta tags in each page
- Semantic HTML structure
- Descriptive page titles
- Alt text for images
- Internal linking structure

## 🚀 Performance Tips

1. **Optimize images:** Compress before uploading
2. **Use CDN:** For faster image delivery
3. **Minimize CSS/JS:** For production deployment
4. **Enable caching:** Set proper cache headers

## 📞 Contact Section

Current contact information can be customized:
- Phone: 9768742926
- WhatsApp: 9768742926
- Email: singhayush6565@gmail.com
- Service Area: Maharashtra

## 🔐 Security Notes

- The contact form is a front-end form only
- Implement server-side validation
- Use HTTPS in production
- Protect email addresses from bots

## 📧 Next Steps

1. Replace placeholder phone/email with actual contact information
2. Add real company logo in assets folder
3. Upload high-quality images for services
4. Set up form submission backend
5. Deploy to web hosting
6. Set up Google Analytics
7. Optimize for SEO

---

**Created:** 2024
**Version:** 1.0
**License:** Commercial Use
