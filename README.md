# Meng Wei Personal Website

Static GitHub Pages site structured like an academic profile.

## Local files

- `index.html` - site content
- `styles.css` - visual styling
- `assets/Meng_Wei_CV.pdf` - downloadable CV

## Publish on GitHub Pages

1. Create a new GitHub repository.
   - Recommended repository name for a personal GitHub Pages site: `<your-github-username>.github.io`
   - Example: `mengwei.github.io`

2. Open a terminal in this folder:

   ```bash
   cd /home/mengwei/meng-wei.github.io
   ```

3. Initialize Git and make the first commit:

   ```bash
   git init
   git add .
   git commit -m "Create personal website"
   ```

4. Connect the local folder to the GitHub repo:

   ```bash
   git branch -M main
   git remote add origin git@github.com:<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```

5. Enable GitHub Pages if it is not enabled automatically.
   - Go to the repository on GitHub.
   - Open `Settings` -> `Pages`.
   - Under `Build and deployment`, choose `Deploy from a branch`.
   - Branch: `main`
   - Folder: `/root`
   - Save.

6. Visit:

   ```text
   https://<your-github-username>.github.io
   ```

GitHub Pages can take a few minutes to publish after the first push.
