# The HUB — Bad Ideas Works

Live at **https://badsadcode.github.io/**

A single `index.html` that lists every repo with GitHub Pages enabled.
It asks the GitHub API on each visit, so **new pages show up automatically**:
turn on Pages in any repo and it appears here.

## Tweaking

Everything lives in the `CONFIG` block at the bottom of `index.html`:

- `EXTRA`: give a repo a nicer title or description, a custom URL, or `hide: true`.
- `HIDDEN`: repos that never show up.
- `FALLBACK`: the list shown if the GitHub API can't be reached (60 requests/hour per visitor limit).

Repos without Pages are listed in the collapsible **Workshop** section, linking to their source.
