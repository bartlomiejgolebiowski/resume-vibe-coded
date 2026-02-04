# Vibe Coded Resume 🚀

This is a single-page HTML resume built with Tailwind CSS. It is designed to be hosted on GitHub Pages.

## 📂 Project Structure

```
.
├── index.html          # The main resume file
├── assets/
│   └── images/         # Folder for project screenshots
└── README.md           # This file
```

## 🖼️ Adding Project Images

To make the portfolio section shine, add screenshots of your projects to the `assets/images/` folder.
Ensure they are named exactly as follows (or update the filenames in `index.html`):

0.  **Profile**: `me.png` (Square, recommended 400x400px)
1.  **SAM**: `sam.png` (approx 600x400px recommended)
2.  **Synapse**: `synapse.png`
3.  **Arcoore**: `arcoore.png`
4.  **Omega Buildings**: `omega.png`
5.  **Hostky.app**: `hostky.png`

## 🚀 How to Publish on GitHub

1.  **Initialize Git**:
    ```bash
    git init
    git add .
    git commit -m "Initial commit: Vibe Coded Resume"
    ```

2.  **Create a Repo on GitHub**:
    - Go to GitHub -> New Repository.
    - Name it (e.g., `resume` or `cv`).
    - **Important**: Make it **Public** (required for free GitHub Pages).

3.  **Push Code**:
    ```bash
    git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    git branch -M main
    git push -u origin main
    ```

4.  **Enable GitHub Pages**:
    - Go to Repo **Settings** -> **Pages**.
    - under **Source**, select `main` branch and `/ (root)` folder.
    - Click **Save**.
    - Your resume will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## 🛠️ Editing

Just open `index.html` in any code editor (like VS Code or Cursor).
The styling uses Tailwind CSS via CDN, so you don't need to install `npm` or run a build process. Just edit and refresh!
