# citostyle.github.io

Personal page of Jürgen Cito: one `index.html`, styled as a terminal. No build step; GitHub Pages serves this branch as-is.

## Editing

All content lives in the block marked `Content: edit here` at the top of the script in `index.html`:

- `LINKS`: entries for `ls -l links/` and `open <name>`
- `MAIL`, `ABOUT`, `PLAN` (`cat .plan`)
- `COMMITS`: the career shown by `git log`, newest first. Each has a 7-character `sha` (also its `#link`), a `subject`, a `text` and optional `papers` as `[title, venue, url]`. `old: true` commits only show with `git log --all`.

Commands and easter eggs are in `CMDS` right below.

## Preview locally

```bash
python3 -m http.server 8000
```

Fonts are self-hosted IBM Plex Mono (SIL Open Font License, see `fonts/`), so the page makes no third-party requests.
