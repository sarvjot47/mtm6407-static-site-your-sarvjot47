# mtm6407-static-site-your-sarvjot47-

Name: Sarvjot Singh Student No:- 41122802

Great idea, Sarvjot! Here's a clean and simple **README.md** section you can copy-paste or tweak as needed to explain the basic steps you followed using Hugo to build your hobby site:

---

## 📄 Project Overview

This website is a static hobby site built for **Sarvjot Singh** using the **Hugo static site generator**. The project fulfills all the course requirements, including the use of real content, multiple templates, responsive design, and deployment to Netlify.

---

## 🚀 Steps to Build This Site Using Hugo

### 1. Install Hugo (Extended Version)
- Downloaded and extracted `hugo_extended_0.146.1_windows-amd64.zip`.
- Added the `hugo.exe` to system PATH for easy use in terminal.

### 2. Create New Hugo Site
```bash
hugo new site sarvjot-hobby-site
```

### 3. Add a Theme
- Cloned the **Ananke** theme:
```bash
git clone https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
```
- Configured the theme in `config.toml`.

### 4. Add Content
- Created **5+ pages** with real content using:
```bash
hugo new about.md
```
- Edited Markdown files inside the `content/` folder.

### 5. Use Multiple Templates
- Used default Ananke template.
- Created a custom layout/template for a few pages under `layouts/`.

### 6. Add Site-Wide Navigation
- Added a navigation menu in `config.toml`.

### 7. Style and Make It Responsive
- Used built-in theme CSS (Ananke is responsive).
- Optionally added Bootstrap for custom styling.

### 8. Build the Site Locally
```bash
hugo serve
```

### 9. Push to GitHub
- Initialized Git, committed files, and pushed to a GitHub repo.

### 10. Deploy to Netlify
- Connected GitHub repo to Netlify.
- Added a `netlify.toml` file to specify Hugo version.
- Deployed successfully using Netlify’s build system.
- Site deployed at: https://sarvjot-static-site.netlify.app/


