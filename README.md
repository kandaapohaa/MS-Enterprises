# M.M. Enterprises — Company Profile Website

A modern, static single-page company profile for **M.M. Enterprises**, Pune.  
Built with pure HTML + CSS — no JavaScript, no frameworks, no dependencies.

## 🗂 Project Structure

```
mm-enterprises-profile/
├── index.html          # Main website (single file)
├── images/             # All images go here
│   ├── logo.png        # MME company logo
│   ├── projects/       # Project photos
│   │   ├── column-jacketing.jpg
│   │   ├── terrace-waterproofing.jpg
│   │   ├── rebar-reinforcement.jpg
│   │   ├── epoxy-flooring.jpg
│   │   ├── steel-truss.jpg
│   │   └── industrial-flooring.jpg
│   ├── brands/         # Brand partner logos
│   │   ├── fosroc.png
│   │   ├── sika.png
│   │   ├── basf.png
│   │   └── ... (one per brand)
│   └── clients/        # Client logos
│       ├── kolte-patil.png
│       ├── paranjape.png
│       └── ... (one per client)
└── README.md           # This file
```

## 🚀 How to Use

1. **Clone the repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/mm-enterprises-profile.git
   ```

2. **Add images**  
   Drop your image files into the `images/` folder following the structure above.

3. **Open locally**  
   Just open `index.html` in any browser. That's it — no build step needed.

4. **Host on Vercel / GitHub Pages / Netlify**  
   Push to GitHub and connect to any static hosting platform.

## 🖼 Adding Images

1. Upload images to the correct subfolder inside `images/`
2. In `index.html`, replace placeholder gallery cards with:
   ```html
   <div class="gal-card" style="background:url('./images/projects/column-jacketing.jpg') center/cover;">
   ```
3. For brand logos, replace text chips with:
   ```html
   <img src="./images/brands/fosroc.png" alt="Fosroc" style="height:40px;">
   ```

## 📄 Converting to PDF

**Option 1 — Chrome Print**
- Open `index.html` in Chrome
- Press `Ctrl + P` (or `Cmd + P` on Mac)
- Set destination to "Save as PDF"
- Print

**Option 2 — Online Tools**
- Use [PDFCrowd](https://pdfcrowd.com) or [WeasyPrint](https://weasyprint.org)

## 📝 Tech Stack

- HTML5 + CSS3 only
- Google Fonts (Inter + Oswald)
- Zero JavaScript
- Print-ready CSS included

## 📞 Contact

**M.M. Enterprises**  
Pune, Maharashtra, India  
+91 98817 14050 | +91 77679 82996  
sales@mmepune.com | www.mmenterpriseindia.com
