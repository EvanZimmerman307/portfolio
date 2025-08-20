
# Evan Zimmerman — Portfolio (Hugo + PaperMod)

This is a Hugo static site using the **PaperMod** theme via Hugo Modules. Content is pre-filled from my CV.

## Local preview
1. Install [Hugo Extended](https://gohugo.io/installation/).
2. Run:
```bash
hugo mod get
hugo server -D
```
## Deploy (GitHub Pages)
- This repo includes a GitHub Actions workflow that builds and deploys on push to `main`.
- After pushing, enable GitHub Pages in your repo settings if not already auto-enabled.
