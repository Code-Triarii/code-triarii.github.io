<h1 align="center">📖 Code Triarii GH Pages Guide</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-GitHub%20Pages-green?style=for-the-badge&logo=github" alt="Platform - GitHub Pages">
  <img src="https://img.shields.io/badge/Engine-Hugo-blue?style=for-the-badge&logo=hugo" alt="Engine - Hugo">
  <img src="https://img.shields.io/badge/Deployment-GitHub%20Actions-yellowgreen?style=for-the-badge&logo=github-actions" alt="Deployment - GitHub Actions">
</p>

---

## 🚀 Getting Started

### 1️⃣ Install Hugo and Clone the Repository

Make sure you have `Hugo` package installed. Check `https://gohugo.io/installation/linux/`. For Debian distributions:

```bash
sudo apt install hugo
```

If you rather have it all dockerized pull the hugo image and work from there:

```bash
docker pull klakegg/hugo
```
To start, you need to clone the repository to your local machine.

```bash
git clone https://github.com/code-triarii/code-triarii.github.io.git
```

### 2️⃣ Modify the Content

Navigate to the `/content` folder and make your desired changes.

```bash
cd code-triarii.github.io/content
```

⚠️ Please, do not modify `/themes/terminal` folder if you are unsure of what you are doing.

### 3️⃣ Test it Locally
Before deploying, you should always test your changes. Run the Hugo server using the following command:


```bash
hugo serve
```

Visit `localhost:1313` in your browser to see the live changes.

### 4️⃣ Build the Site
Build your site and make sure the docs folder gets updated.

```bash
hugo
```
Check if the docs folder has been changed using:

```bash
git status
```

### 5️⃣ Commit & Push Changes

Once you're satisfied with your changes:

```bash
git add .
git commit -m "Describe your changes here"
git push origin master
```
Wait for GitHub Actions to deploy the page.

### 6️⃣ Visit the Site
Your changes should now be live (it needs a little bit of time to get everything running correctly). Visit `code-triarii.github.io` to see them.
