# Personalizing Your CV - Quick Start Guide

Welcome to your professional CV template! Follow these steps to make it completely yours.

## 1. Replace Your Profile Photo

- Navigate to the `img/` folder
- Replace or add your photo as `profile.jpg` (recommended: 300x300px, square format)
- The photo will automatically appear in the sidebar header
- Ensure the file is named exactly `profile.jpg` or update the reference in `index.html`

## 2. Update Your Contact Information

Open `index.html` and find the placeholders in the "About Me" section:

- **Phone**: Replace `+256000000000` with your WhatsApp or mobile number
  - Look for: `<span class="fw-medium text-primary">Phone:</span> +256000000000`
  
- **Email**: Replace `yourname@gmail.com` with your real email address
  - Look for: `<span class="fw-medium text-primary">Email:</span> yourname@gmail.com`

These same contacts are used in the "Contact Me" form at the bottom.

## 3. Update About Me Section

The "About Me" section contains placeholder text that is ready for you to edit:

1. Scroll to the "About Me" section in `index.html`
2. Replace the Lorem Ipsum text with your professional bio
3. Update the personal details grid below the bio:
   - Birthday, Degree, Experience, Address, Freelance status
   - Update the statistics (Years of Experience, Happy Clients, Complete Projects)

## 4. Edit Experience Section

Your work experience entries are preserved and ready for customization:

1. Locate the "Experience" section (marked with a comment `<!-- Experience preserved -->`)
2. Update each job entry with:
   - Job Title
   - Company Name
   - Date range
   - Job description

Follow the existing markup structure for consistency.

## 5. Update Portfolio / Project Images

The portfolio section includes 6 project placeholders. For each project:

1. Replace the corresponding image in the `img/` folder:
   - `portfolio-1.jpg` → Brand Identity Pack
   - `portfolio-2.jpg` → Food Delivery App Concept
   - `portfolio-3.jpg` → E-commerce Landing Page
   - `portfolio-4.jpg` → Social Media Campaign Graphics
   - `portfolio-5.jpg` → Personal Portfolio Website
   - `portfolio-6.jpg` → Logo & Icon Pack

2. Recommended image size: 600x400px (4:3 aspect ratio)
3. If you want to customize project titles or descriptions, edit them in the portfolio section of `index.html`

## 6. Add Testimonial Photos

Update the testimonial images in the `img/` folder:

- `testimonial-1.jpg` → Amina N.'s photo
- `testimonial-2.jpg` → David R.'s photo
- `testimonial-3.jpg` → Lydia M.'s photo

Recommended size: 100x100px (square format)

## 7. Customize Services (Optional)

The three core services are already configured:
- Graphic Design (with paint brush icon)
- Mobile App Design (with mobile phone icon)
- Website Design (with laptop code icon)

To customize, edit the service descriptions in the "Services" section of `index.html`.

## 8. Personalize Your Headline

The headline under your name currently displays: "Mobile & Web Designer, Graphic Designer, UI/UX Designer"

To change this:
1. Find the `<div class="typed-text d-none">` in `index.html`
2. Replace with your own comma-separated list of roles
3. These will rotate as an animated typing effect

## 9. Export to PDF

To create a professional PDF version:

1. **From Browser (Recommended)**:
   - Open your CV in a web browser
   - Press `Ctrl + P` (Windows) or `Cmd + P` (Mac)
   - Select "Save as PDF"
   - The layout will automatically optimize for print

2. **Print-Friendly Layout**:
   - The template is responsive and printer-optimized
   - All colors and fonts will print clearly
   - Navigation buttons hide on print view

## 10. Deploy Online (Optional)

To share your CV online:

1. Upload all files to a web hosting service (GitHub Pages, Vercel, Netlify, etc.)
2. Ensure all file paths remain relative (they are by default)
3. Share the live URL with employers or clients

## File Structure Reference

```
bootstrap-cv-resume-template/
├── index.html                 (Main CV file - edit this)
├── css/
│   └── style.css             (Professional styling)
├── js/
│   └── main.js               (Smooth scroll & animations)
├── img/
│   ├── profile.jpg           (Your photo - replace)
│   ├── portfolio-1.jpg       (Your projects - replace)
│   ├── portfolio-2.jpg
│   ├── ... (through portfolio-6.jpg)
│   ├── testimonial-1.jpg     (Client photos - replace)
│   ├── testimonial-2.jpg
│   └── testimonial-3.jpg
└── lib/                      (JavaScript libraries - do not modify)
```

## Tips for Best Results

✓ Use high-quality images (minimum 300dpi for print)
✓ Keep descriptions concise and professional
✓ Use consistent formatting throughout
✓ Test the print layout before sending
✓ Update the "Newsletter" section or remove if not needed
✓ Verify all links are working (external links open in new tabs)

## Frequently Asked Questions

**Q: Can I add more skills?**
A: Yes. Edit the Skills section in `index.html` and add more progress bar items following the same pattern.

**Q: How do I add more projects?**
A: Add more portfolio items to the portfolio section, incrementing the file names (portfolio-7.jpg, etc.).

**Q: Can I change colors?**
A: Yes. Open `css/style.css` and update the CSS variables at the top (--primary, --accent colors).

**Q: How do I remove the Newsletter section?**
A: Delete the entire "Subscribe Start" to "Subscribe End" section in `index.html`.

---

**Happy networking! Your professional CV is ready to make a great impression.** 🚀
