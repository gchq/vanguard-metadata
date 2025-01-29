# Contributor guidelines

We strongly encourage contributions to Vanguard. Please follow the guidelines
[there](https://github.com/gchq/Vanguard/blob/main/CONTRIBUTING.md). Issues should be
reported to the main Vanguard [issues board](https://github.com/gchq/Vanguard/issues).

## Workflows

This repo runs pre-commit checks. Please run `pre-commit install` before making any
commits. The GitHub workflows check these for pull requests, but not on push to `main`
in order to avoid an excessive number of automatic runs due to automated commits.

Any contributor may push directly to `main`. However, they should create a pull request
instead to enable CI checks.

Since manual commits to this repo are likely to be infrequent, pre-commit hooks are not
updated automatically. Instead, they should be updated manually by running
`pre-commit autoupdate` and committed to the repo before any other changes if updates
have not been checked in the past fortnight.
