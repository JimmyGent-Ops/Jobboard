# Jimmy Ops Board

Team jobs live here. Static status board for Jimmy's property management + listings workflow.

## Local development

- `index.html` (root) is what GitHub Pages serves at <https://jimmygent-ops.github.io/Jobboard/>.
- `jobboard/index.html` is the working copy we edit; after changes, copy or move it over the root file (or edit both if you prefer).
- No build tooling—open either file directly in a browser, update the `sections` array + timestamp, commit.

## Deployment workflow

1. Commit changes on `main`.
2. Push to GitHub.
3. GitHub Pages (branch = `main`, folder = `/`) publishes automatically.

If Pages isn’t enabled yet: Settings → Pages → “Deploy from branch,” select `main` and `/ (root)`.
