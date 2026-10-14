# Portfolio site

A one-page portfolio in plain HTML and CSS. No build step, no dependencies, free to host on GitHub Pages.

## Before you publish: replace these placeholders

Search each file for the text on the left and swap in your own.

| Find | Replace with | File |
| --- | --- | --- |
| `your.email@example.com` | your email | `index.html` (2 places) |
| `linkedin.com/in/your-profile` | your LinkedIn URL | `index.html` (2 places) |
| `github.com/your-username` | your GitHub profile URL | `index.html` (2 places, plus the repository link below) |
| `github.com/your-username/job-search-tracker` | your tracker repository | `index.html` |
| `your-app.streamlit.app` | your live demo link, or delete that whole `<a>` line | `index.html` |
| `assets/Palak_Shah_Resume.pdf` | save your resume PDF at this path | `assets/` folder |

Search for `TODO` in `index.html` to find each spot.

## Publish on GitHub Pages

1. On GitHub, create a new public repository. Name it `your-username.github.io` to get the address `https://your-username.github.io`. Any other name also works, and the site will live at `https://your-username.github.io/repo-name`.
2. Upload everything in this folder: `index.html`, `style.css`, `.nojekyll` and the `assets` folder. On the repository page, choose **Add file**, then **Upload files**, drag the files in, and commit.
3. Open **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, and save.
4. Wait a minute or two. The address appears at the top of the Pages screen.
5. Open the address on your phone and your computer and click every link.

Prefer the command line?

```bash
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```

## Keep it current

- **Add a project:** copy one `<details class="project">` block in `index.html` and edit the text.
- **Add screenshots:** save images in `assets/` and add `<img src="assets/name.png" alt="Describe what the image shows">` inside a project's `p-detail` block.
- **Change colors:** edit the values at the top of `style.css`. The dark theme follows the visitor's device setting.
- **Add numbers where you have them:** a figure such as hours saved per week or number of users makes a project row stronger. Only add numbers you can back up.

## Where to link it

Put the site address in three places: under your name on your resume, in the Website field on your LinkedIn profile, and in the profile README of your GitHub account.

## Notes

- Fonts load from Google Fonts. If they fail to load, the page falls back to system fonts and still works.
- Do not publish client names, internal screenshots or real company data. The site is public.
