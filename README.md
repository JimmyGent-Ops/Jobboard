# Jimmy Ops Board

Team jobs live here. Static status board for Jimmy's property management + listings workflow.

## Local development

Open `jobboard/index.html` directly in a browser (no build tooling required). Update the `tasks` array in the inline script, adjust the header timestamp, and commit.

## Deployment workflow

1. Commit changes on `main`.
2. Push to GitHub.
3. GitHub Pages serves `/jobboard/index.html` at `https://jimmygent-ops.github.io/Jobboard/`.

If Pages isn’t enabled yet: Settings → Pages → “Deploy from branch,” select `main` and `/ (root)`.
