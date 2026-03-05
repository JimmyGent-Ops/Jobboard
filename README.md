# Jimmy Ops Board

Team jobs live here. Static status board for Jimmy's property management + listings workflow.

## Live URLs

- Main board (all projects): <https://jimmygent-ops.github.io/Jobboard/>
- Field board (Melissa + Jon spotlight): <https://jimmygent-ops.github.io/Jobboard/field.html>

## Local development

- `index.html` (root) is the main board GitHub Pages serves by default.
- `jobboard/index.html` is the structured source for the main board; keep it in sync with `index.html`.
- `field.html` renders the Melissa/Jon-only board. Update the `fieldTasks` array there when their workload changes.
- No build tooling—open files directly in a browser, tweak timestamps/arrays, then commit.

## Deployment workflow

1. Commit changes on `main`.
2. Push to GitHub.
3. GitHub Pages (branch = `main`, folder = `/`) publishes automatically.

If Pages isn’t enabled yet: Settings → Pages → “Deploy from branch,” select `main` and `/ (root)`.
