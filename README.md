# Math for HTML5 Game Builders: sample games

The 29 playable games for the book, as a static site.

## Deploy to GitHub Pages (gh-pages branch)

```bash
unzip gh-pages-bundle.zip -d math-for-html5-game-builders
cd math-for-html5-game-builders
git init
git checkout -b gh-pages
git add -A
git commit -m "Publish sample games"
git remote add origin https://github.com/YOUR-USERNAME/math-for-html5-game-builders.git
git push -u origin gh-pages
```

Then on GitHub: **Settings -> Pages -> Build and deployment -> Source: Deploy from a branch -> Branch: gh-pages, folder: / (root)**.
The games appear at `https://YOUR-USERNAME.github.io/math-for-html5-game-builders/` after about a minute.
`.nojekyll` is included so GitHub serves every file as is.
