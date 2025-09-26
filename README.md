# Quarto starter (blog + pages)

## Quickstart
1. Install Quarto (see https://quarto.org/docs/get-started/).
2. (Optional) Create and activate a Python env, then `pip install jupyter ipykernel numpy`.
3. In this folder, run:
   ```bash
   quarto preview
   ```
4. Edit files and posts under `posts/`.
5. Publish to GitHub Pages:
   ```bash
   git init && git add . && git commit -m "init"
   git branch -M main
   git remote add origin https://github.com/<yourname>/<yourrepo>.git
   git push -u origin main
   quarto publish gh-pages
   ```

## Giscus comments
- Make your GitHub repo public, enable Discussions, install the giscus app for the repo, and copy the values (`repo-id`, `category-id`) from giscus setup into `_quarto.yml` under `website: comments:`.