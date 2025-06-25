# 🚀 My Portfolio – Powered by Hugo Resume Theme

This is my personal portfolio website, built using [Hugo](https://gohugo.io/) and the [hugo-resume](https://themes.gohugo.io/themes/hugo-resume) theme. It showcases my experience in cloud infrastructure, DevOps leadership, and AI-driven cloud solutions.

> 🌐 Live Site: [https://your-github-username.github.io](https://your-github-username.github.io)

---

## ✨ Features

- Clean, resume-style layout
- Responsive design
- Projects, experience, education, and contact details
- Easily editable `config.toml` and markdown content
- Deployable via GitHub Pages

---

## 🚧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-github-username/your-github-username.github.io.git
cd your-github-username.github.io
```

### 2. Install Hugo (if not installed)

```bash
brew install hugo           # macOS/Linux
# OR
sudo apt install hugo       # Debian/Ubuntu
```

### 3. Initialize Hugo Theme

```bash
git submodule add https://github.com/resume/resume-theme.git themes/hugo-resume
```

> If using this template, the theme is already included as a submodule.

### 4. Run Locally

```bash
hugo server -D
```

Visit: [http://localhost:1313](http://localhost:1313)

---

## 🚀 Deploy to GitHub Pages

### Option A: Deploy to `<username>.github.io`

```bash
hugo                      # builds site into ./public
cd public
git init
git remote add origin https://github.com/your-github-username/your-github-username.github.io.git
git add .
git commit -m "Initial portfolio"
git push -u origin master
```

### Option B: Deploy via `/docs` folder

If using a custom repo:

```bash
hugo -d docs
```

Then in GitHub > Settings > Pages:
- Source: `main` branch
- Folder: `/docs`

---

## 🧠 Credits

- Built with [Hugo](https://gohugo.io/)
- Theme: [hugo-resume](https://github.com/resume/resume-theme)

---

## 📫 Contact

- 🌐 [LinkedIn](https://linkedin.com/in/yourprofile)
- 💻 [GitHub](https://github.com/yourusername)
- 📧 your.email@example.com
