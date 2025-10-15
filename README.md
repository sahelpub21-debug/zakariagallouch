# Zakaria Gallouch – Strategic Communications Portfolio

A responsive single-page HTML portfolio showcasing strategic communications case studies across multiple industries — aviation, fintech, hospitality, and technology.
The portfolio is designed for **clarity, visual impact, and case-based storytelling**, with a simple structure (HTML, CSS, JS) and no external dependencies.

---

## 📁 Project Structure

```
/portfolio/
│
├── index.html           # Main portfolio file (self-contained)
├── /images/             # Folder for images (portraits, campaign visuals, etc.)
└── README.md            # This documentation file
```

> 💡 All images are referenced through placeholders in `index.html`.
> Replace `[Placeholder Text]` with `<img src="images/filename.jpg" alt="description">`.

---

## 🧠 Overview

**Author:** Zakaria Gallouch
**Role:** Senior Strategic Communications Consultant
**Experience:** 10+ years
**Industries:** Aviation, Finance, Tech, Hospitality, Retail

### Core Sections

| Section          | Description                                                 |
| ---------------- | ----------------------------------------------------------- |
| **Hero**         | Personal intro, positioning statement, and call to action   |
| **Case Studies** | Grid of major projects (ABL, IKEA, FAN4ALL, Glovo, ATDA)    |
| **Case Pages**   | Each case has detailed challenge–approach–results breakdown |
| **Stats**        | Global metrics summarizing portfolio impact                 |
| **Footer**       | Quick navigation + expertise list                           |

---

## ⚙️ How to Use / Edit

### 🖼 Replace Images

1. Add your images in the `/images/` folder.
2. In `index.html`, find the placeholders like:

   ```html
   <div class="case-image">[IKEA Campaign Visual]</div>
   ```
3. Replace with your image tag:

   ```html
   <div class="case-image">
     <img src="images/ikea-morocco.jpg" alt="IKEA Morocco Campaign" style="width:100%;border-radius:15px;">
   </div>
   ```

---

### ✏️ Customize Text Content

You can directly edit text blocks inside `index.html`.
Search for project titles or case IDs (e.g. `#abl-page`, `#glovo-page`) to update details.

---

## 🌐 Hosting Options (Free)

### **1. Netlify Drop (no domain required)**

Fastest method — drag your folder to [https://app.netlify.com/drop](https://app.netlify.com/drop)
✅ Instant live link like: `https://portfolio-zakaria.netlify.app`

### **2. GitHub Pages**

Push your folder to a GitHub repo → Settings → Pages → *Deploy from main branch*
✅ Link: `https://yourusername.github.io/portfolio/`

### **3. Neocities**

Upload manually to [https://neocities.org](https://neocities.org)
✅ Link: `https://yourname.neocities.org`

---

## 🧩 Optional Enhancements

| Feature                          | How to Add                                         |
| -------------------------------- | -------------------------------------------------- |
| Replace placeholders dynamically | Integrate Netlify CMS or Google Sheets JSON feed   |
| Analytics tracking               | Insert Google Analytics script before `</body>`    |
| Custom domain                    | Add CNAME or connect via Netlify’s domain settings |

---

## 🧰 Technical Notes

* No external JS libraries required
* Pure HTML + CSS + Vanilla JS
* Fully responsive down to 400px width
* Animations use `IntersectionObserver` and CSS keyframes
* No server required — works offline

---

## 🧑‍💻 Credits

**Designed & Coded by:** Zakaria Gallouch
**Specialization:** Strategic Communications, Crisis Management, and B2B Thought Leadership
**Contact:** [Add your email or LinkedIn]

---

## 📄 License

This project is open for personal and professional portfolio use.
Commercial reuse or template redistribution requires permission from the author.
