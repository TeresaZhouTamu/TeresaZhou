# Yingtong (Teresa) Zhou — Academic Website

A classic, responsive academic homepage built with plain HTML/CSS for GitHub Pages.

## Deploy to your EXISTING repository

Repository: https://github.com/TeresaZhouTamu/TeresaZhou

1. Download and unzip `teresa-academic-site.zip`.
2. Open a terminal in the extracted `teresa-academic-site` folder.
3. Run:

   ```bash
   git clone https://github.com/TeresaZhouTamu/TeresaZhou.git
   cp -R index.html style.css assets .nojekyll TeresaZhou/
   cp README.md TeresaZhou/README.md
   cd TeresaZhou
   git add .
   git commit -m "Add academic personal website"
   git push origin main
   ```

   If the empty repository has no `main` yet, create the first commit using GitHub's *Add file* option, or use `git init` and push (see the detailed instructions below).

4. Go to **Settings → Pages** in your repository.
5. Under **Build and deployment**, select **Deploy from a branch** → `main` → `/ (root)` → **Save**.
6. Your project site should appear at **https://teresazhoutamu.github.io/TeresaZhou/**.

## Most reliable first-push commands (for an EMPTY repo)

Run these commands in the extracted website directory, **not** inside a cloned folder:

```bash
git init
git branch -M main
git remote add origin https://github.com/TeresaZhouTamu/TeresaZhou.git
git add .
git commit -m "Launch academic website"
git push -u origin main
```

If the repository already has files or commits, clone it and copy the website files into that clone instead of using these first-push commands.

## Customize

- `index.html` — all academic content, links, and sections.
- `style.css` — typography, spacing, responsiveness, and colors.
- `assets/profile-placeholder.svg` — replace with your headshot, then update the `img src` in `index.html` to `assets/profile.jpg` (or whichever filename you use). Also update `alt` and remove the placeholder caption.
- `assets/Yingtong_Zhou_CV.pdf` — public version of your CV with phone number excluded. Replace with an updated CV as needed.
- Add verified Google Scholar/paper/code links when you have them. Do not assume that a manuscript under review is accepted.

**Privacy:** A published GitHub Pages site and linked CV are public. Review the PDF and any added personal details before pushing.

## Optional shorter web address

To use `https://teresazhoutamu.github.io/` without `/TeresaZhou/`, rename the repository to `TeresaZhouTamu.github.io` under **Settings → General → Repository name**, then update the Git remote URL and Pages settings as needed.
