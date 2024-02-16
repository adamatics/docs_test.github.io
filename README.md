# docs_test.github.io
Test GitHub Pages

## Steps to generate and deploy

1. Generate documentation with `mkdocs` as explained in the repo.
2. Create a GitHub repo following the instructions for setting up Pages.
3. ...
4. Edit `mkdocs.yml`, `index.md`, etc. as needed until happy with the result.
5. Commit and push the changes.
6. Trigger a deployment with `mike deploy --push <package_version>`:
   1. If updating/deploying the latest version, add `--update-aliases <latest_alias>`.
   2. If unconventional title, add `--title=<version_title>`.
