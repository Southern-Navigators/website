# Push to GitHub — run these after creating the repo

The project is already a **Git repo**. The canonical repository is **https://github.com/Southern-Navigators/website** (Southern Navigators organization).

## 1. Repo location

- **Org repo:** `Southern-Navigators/website`
- If you're setting up a new clone or the remote isn't set yet, use the remote URL below.

## 2. Add the remote and push

In a terminal, from the project folder (e.g. `c:\Users\Dad\git\Southern-Navigators\website`), run:

```bash
git remote add origin https://github.com/Southern-Navigators/website.git
git push -u origin main
```

If you use SSH:

```bash
git remote add origin git@github.com:Southern-Navigators/website.git
git push -u origin main
```

## 3. Deploy on Netlify

Then follow **DEPLOY.md**: Netlify → Import from GitHub → build `npm run build`, publish `dist` → enable Identity + Git Gateway → invite committee.

---

**Summary:** Point your local repo at `Southern-Navigators/website` with the `git remote` commands above, then push.
