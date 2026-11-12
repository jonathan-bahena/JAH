# AE Launch Plan

One self-contained `index.html`. No build step, no dependencies, no outside requests. Fonts are embedded.

## Put it on GitHub Pages

1. Create a new repository on GitHub. On a free account it has to be public for Pages to work.
2. Add file, Upload files, drop in `index.html`, Commit.
3. Settings, Pages, Source: Deploy from a branch. Branch: `main`, folder: `/ (root)`. Save.
4. About a minute later it is live at `https://<your-username>.github.io/<repo-name>/`.

From a terminal instead:

```bash
git init
git add index.html
git commit -m "AE launch plan"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then do step 3.

## Read this before you publish it

A GitHub Pages site is public to anyone with the link, even when the repository is private. This page names your current employer and describes a job search, and the address will include your GitHub username.

- The page asks search engines not to index it, but that is a request and not a lock.
- Use a repository name that says nothing about the search.
- What you type into the page (applications, notes, numbers) never leaves your browser. Only the built-in text is public.
- If you would rather keep all of it private, use the private Claude link instead of GitHub Pages.

## Where your progress is saved

- On GitHub Pages: in that browser only. Use Backup in the top corner to copy your progress to another device.
- On the private Claude link: to your Claude account, so it follows you between phone and laptop. The label in the top corner tells you which one is active.

## Changing the content

Everything is plain JavaScript data near the bottom of `index.html`: `SESSIONS` (the schedule), `QS` (interview questions), `LINKEDIN`, `RESUME`, `MSGS` (message scripts) and `SEEDS` (starter roles). Edit the text and push again. Your saved progress stays put.
