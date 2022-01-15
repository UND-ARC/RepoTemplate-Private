# New Repository Setup To-Do

## Repository Settings

- [ ] Add author name and email to `/docs/_config.yml`
- [ ] Configure access control (read/write/admin) to the repository as needed
  - [ ] Ensure the visibility is set to **Private**

## Metadata

- [ ] Add basic information to `/docs/index.md` about what the repo is for
- [ ] Add basic information to this file `/.github/README.md` about what the repo is for (should be similar to `/docs/index.md`)
  - [ ] The README file should include a note on when/if the repository can be made public, and who its contents can be shared with.
- [ ] If applicable, edit the basic bug report template: `/.github/ISSUE_TEMPLATE/bug.md`
- [ ] If applicable, edit the basic pull request template: `/.github/PULL_REQUEST_TEMPLATE.md`
- [ ] If applicable, edit the contributing guidelines: `/.github/contributing.md`

## Repo Structure

Most code repositories should have at minimum the following structure:

```
root directory
+- .github
| +- ISSUE_TEMPLATE
| | +- bug.md
| | CODE_OF_CONDUCT.md
| | contributing.md
| | PULL_REQUEST_TEMPLATE.md
| | README.md
+- docs
| | index.md
+- src
+- tests
| LICENSE
| .gitignore
```

Frequently, the `tests` directory may be better located under `src`.  Most of the
time, however, it'll be its own directory.  The directory structure of `tests`
should mirror exactly that of `src`, however, the code in the file(s) will
not be program code, but instead be comprised of unit tests.
