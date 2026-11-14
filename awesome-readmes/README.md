# Awesome README collection (archive)

Local mirror of project READMEs listed in
[matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme).

## Layout

```
awesome-readmes/
├── README.md           # this file
├── _source-index.md    # original curated index
├── _repos.txt          # owner/repo entries extracted from the index
├── _usernames.txt      # unique owners
├── _entries.json       # structured entries (including architecture file paths)
├── _success.txt        # successfully downloaded
├── _failed.txt         # failures (if any)
└── <username>/
    └── <repo>/
        └── README.md   # or ARCHITECTURE.md / other listed doc filename
```

## Notes

- Organized by GitHub username (owner), then repository name.
- Includes Examples, Architecture Examples (GitHub-hosted), and Tools entries.
- Non-GitHub links (articles, GitLab, GIF tools, etc.) are not mirrored; see `_source-index.md`.
- Wiki-only architecture links (e.g. VS Code, Oh My Zsh) fall back to the repo’s default README.
