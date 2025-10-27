# 🌐 [Malta.dp.ua](https://malta.dp.ua)

This is a static website built using [Nanoc](https://nanoc.app/), a flexible static site generator written in Ruby. The site is compiled into the `docs/` folder and automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch.

## 🚀 Features

- ⚙️ Built with Nanoc for fast and customizable static site generation
- 📁 Compiles output to `docs/` directory
- 🚀 Automatic deployment to GitHub Pages on push to `main` branch
- 🧹 Smart pruning of outdated files
- 🌍 UTF-8 encoding support
- 📝 Rich support for textual formats (Markdown, HTML, CSS, JS, etc.)

## 🛠️ Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/malta-dp-ua/malta.git
cd malta
```

### 2. Install Dependencies

```
gem install nanoc
```

## 🌍 Deployment to GitHub Pages

This project is configured to deploy automatically via GitHub Pages:

- The compiled site lives in the docs/ folder
- GitHub Pages is set to serve from the docs/ folder on the main branch
- Every git push to `main` branch triggers a redeploy

### ✅ To deploy:

```
nanoc
git add .
git commit -m "Update site"
git push origin main
```

Your changes will be live shortly!
