# Visual CV Website

This project is ready to publish with GitHub Pages.

## Publish steps

1. Create a new empty GitHub repository.
2. In this folder, run:

```powershell
git add .
git commit -m "Initial CV website"
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. On GitHub, open your repository:
   - Go to **Settings → Pages**
   - Under **Build and deployment**, set **Source** to **GitHub Actions**

4. Wait for the workflow **Deploy static site to GitHub Pages** to complete.

Your site URL will be:

`https://<your-username>.github.io/<your-repo>/`
