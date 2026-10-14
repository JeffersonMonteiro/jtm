# Jefferson Monteiro — Professional Portfolio Website

Modern, responsive personal portfolio website for **Jefferson Monteiro**, Senior Java Backend Developer & Solutions Architect based in Adelaide, Australia.

- **Live URL**: [https://jeffersontadeumonteiro.github.io/](https://jeffersontadeumonteiro.github.io/)
- **LinkedIn**: [linkedin.com/in/jefferson-monteiro-58503b61/](https://www.linkedin.com/in/jefferson-monteiro-58503b61/)
- **Email**: jeffermonteiro@gmail.com
- **Phone**: +61 478 610 401

---

## 🚀 Tech Stack

- **HTML5**: Semantic markup, accessible attributes (`aria-*`), SEO & OpenGraph meta tags.
- **CSS3**: Custom CSS variables, dark navy theme with electric cyan and sapphire accents, responsive grid & flexbox, glassmorphism, print stylesheet.
- **Vanilla JavaScript (ES6+)**: Zero external dependencies. Active scroll-spy, responsive mobile menu drawer, skill category filtering, project category filtering, one-click copy-to-clipboard with toast notifications, and interactive contact handler.

---

## 📂 Project Structure

```text
jeffersontadeumonteiro.github.io/
├── index.html                 # Main single-page portfolio document
├── README.md                  # Project overview and publishing guide
├── css/
│   └── style.css              # Custom styling, dark navy theme, and responsive design
├── js/
│   └── main.js                # Interactive logic (filters, navigation, clipboard, toast)
└── assets/
    └── icons/
        └── favicon.svg        # Custom monogram vector favicon (<JM/>)
```

---

## 💻 Running the Website Locally

You can preview the website locally using any standard HTTP server:

### Option 1: Using Python
If Python is installed on your machine:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your web browser.

### Option 2: Using Node.js (npx)
If Node.js is installed:
```bash
npx serve .
# or
npx http-server . -p 8080
```
Then open the displayed local URL in your browser.

### Option 3: Direct File Opening
Double-click `index.html` to open it directly in Google Chrome, Microsoft Edge, Firefox, or Safari.

---

## 🌐 Publishing to GitHub Pages

Because this repository is named `jeffersontadeumonteiro.github.io` on GitHub under your account, GitHub Pages serves the `main` branch directly at root level.

### Step 1: Stage and Commit the Files
Open your terminal in `C:\Users\jeffe\jeffersontadeumonteiro.github.io`:
```bash
git add .
git commit -m "feat: build modern senior java backend developer portfolio"
```

### Step 2: Push to GitHub
```bash
git push origin main
```

### Step 3: Verify GitHub Pages Settings
1. Open your repository on GitHub: `https://github.com/JeffersonMonteiro/jeffersontadeumonteiro.github.io`
2. Go to **Settings** &rarr; **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)`
4. Click **Save** (if not already enabled).
5. Within 1–2 minutes, your website will be live at:
   👉 **`https://jeffersontadeumonteiro.github.io/`**

---

## 📄 Sections Included

1. **Hero**: Professional title, location indicator (Adelaide, SA), core summary, quick skill badges, and interactive profile terminal.
2. **About Me**: International software engineering experience spanning Australia (Credit Union SA), Europe (BMW / Critical TechWorks, Inetum), and Brazil (Mastercard, Bradesco, HSBC).
3. **Technical Skills**: Java SE/EE, Spring Boot, Spring Batch, Microservices, REST & SOAP APIs, AWS, Azure, Docker, Kafka, Oracle PL/SQL, JUnit, and test automation.
4. **Featured Projects**: Published Google Play Store apps (*Australian Home Budget*, *Golden Connect AU*), BMW Assembly Line MAPP System, Mastercard Anti-Fraud Platform, and Credit Union SA integration suite.
5. **Professional Experience**: Chronological history detailing 15+ years of production roles and achievements.
6. **Education & Certifications**: AWS Certified Solutions Architect – Associate, Microsoft Azure Fundamentals, WES Verification, UTFPR Java specialization, PUC-PR Bachelor's in Systems Analysis.
7. **Contact**: Quick copy-to-clipboard for email/phone, LinkedIn and GitHub links, and interactive contact message form.