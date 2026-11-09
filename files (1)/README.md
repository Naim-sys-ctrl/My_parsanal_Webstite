# Nizam Uddin Naime - Portfolio Website

A responsive personal portfolio built with HTML5, CSS3 and JavaScript. It has dark and light mode, smooth scrolling and a contact form.

## Files

```
portfolio/
  index.html   page content
  style.css    design and layout
  script.js    interactions (theme, menu, typing text, form)
  README.md    this guide
  assets/      images and icons (profile.jpg, favicon.svg)
```

## Things to edit before publishing

1. **Projects:** edit the four sample project cards in the Projects section with your own work and GitHub links.
2. **Social links:** the links use the username `Naim`. If your real GitHub, LinkedIn or Facebook username is different, search for `/Naim` in `index.html` and fix it.
3. **Education years:** you can add your study years in the Education section.
4. **Skill bars:** change the `data-level` numbers (0 to 100) in the Skills section.

## Run on your PC

1. Download and unzip the project folder.
2. Double-click `index.html`. It opens in your browser.
3. (Optional) Install VS Code and the "Live Server" extension, then right-click `index.html` and choose "Open with Live Server".

## Upload to GitHub

1. Create an account at https://github.com.
2. Click **+** > **New repository**. Name it `portfolio`, keep it **Public**, click **Create repository**.
3. Install Git from https://git-scm.com/downloads.
4. Open a terminal inside the project folder and run (replace `YOUR-USERNAME`):

```
git init
git add .
git commit -m "My portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git push -u origin main
```

No Git? On the repository page click **Add file** > **Upload files**, drag in all files and the `assets` folder, then click **Commit changes**.

## Get a live link

### Option A: GitHub Pages (free)
1. Open your repository > **Settings** > **Pages**.
2. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
3. Wait 1 to 2 minutes. Your link is `https://YOUR-USERNAME.github.io/portfolio/`.

### Option B: Netlify (free)
1. Sign up at https://www.netlify.com (you can use your GitHub account).
2. Click **Add new site** > **Deploy manually**, then drag the whole project folder onto the page. Or choose **Import from Git** and pick your repository.
3. Netlify gives you a link such as `https://random-name.netlify.app`. Change it in **Site configuration** > **Change site name**.

## Updating the site later

Edit the files, then run `git add .`, `git commit -m "Update"` and `git push`. The live site updates in a minute.
