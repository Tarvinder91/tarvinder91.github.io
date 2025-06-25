# 🚀 My Portfolio – Powered by Hugo Resume Theme

This is my personal portfolio website, built using [Hugo](https://gohugo.io/) and the [hugo-resume](https://themes.gohugo.io/themes/hugo-resume) theme. It showcases my experience in cloud infrastructure, DevOps leadership, and AI-driven cloud solutions.

> 🌐 Live Site: [https://tarvinder91.github.io](https://tarvinder91.github.io)

---

## ✨ Features

- Clean, resume-style layout
- Responsive design
- Projects, experience, education, and contact details
- Easily editable `config.toml` and markdown content
- Deployable via GitHub Pages

---

## 🚧 Setup Instructions

### 1. Install Hugo (if not installed)

```bash
brew install hugo           # macOS/Linux
# OR
sudo apt install hugo       # Debian/Ubuntu
```

### 2: Create a New Hugo Site

```bash
hugo new site my-portfolio
cd my-portfolio
```
### 3. Clone the Hugo theme as submodule

```bash
git init
git submodule add https://github.com/gurusabarish/hugo-profile.git themes/hugo-profile
```

Update your config.toml

```bash
baseURL = 'https://<your-github-username>.github.io/'
languageCode = 'en-us'
title = 'Your Name | Portfolio'
theme = 'hugo-profile'
```

### 4: Add Sample Content

Create your content by copying files from theme\hugo-theme\exampleSite folder to the folders in your repository

> Example: File content\Index.md is the homepage

### 5. Run Locally

```bash
hugo server -D
```

Visit: [http://localhost:1313](http://localhost:1313)

---

## 🚀 Deploy to GitHub Pages. Create your own repository <username>.github.io

### Deploy to `<username>.github.io`

```bash
hugo                      # builds site into ./public. Run this everytime before you push the changes to the repo
cd public                 # the code in this folder would actually  actually committed to your repo
git init
git remote add origin https://github.com/your-github-username/your-github-username.github.io.git
git add .
git commit -m "Initial portfolio"
git push -u origin master
```

---

## 🧠 Credits

- Built with [Hugo](https://gohugo.io/)
- Theme: [hugo-resume](https://github.com/eddiewebb/hugo-resume.git)

---

## 📫 Contact

- 🌐 [LinkedIn](https://linkedin.com/in/tarvinder91)
- 💻 [GitHub](https://github.com/tarvinder91)
