# CLAUDE.md — Personal Website

## Local preview

Jekyll is installed via Homebrew Ruby. After adding Homebrew Ruby to PATH (done in ~/.zshrc), run from the repo root:

```bash
jekyll serve
```

Preview at **http://127.0.0.1:4000**. Stop with Ctrl+C.

## Repository structure

| Path | Purpose |
|------|---------|
| `index.md` | About/home page |
| `research.md` | Publications list |
| `news.md` | Invited talks and updates |
| `cv.md` | Embeds CV PDF via Google Docs viewer |
| `_data/menu.yml` | Navigation order and items |
| `_sass/_page.scss` | Page-level styles (news dl layout lives here) |
| `css/main.scss` | Color variables and global settings |
| `cv/Peng_Huang_CV.pdf` | CV PDF binary |
| `images/` | Paper figures and diagrams |

## Conventions

**New page:** create `name.md` with front matter `layout: page`, `permalink: /name/`, `title: Name`, then add an entry to `_data/menu.yml`.

**Navigation:** order in `menu.yml` controls display order. Commented-out items (`#`) are hidden but preserved.

**Research entries** (`research.md`): use raw HTML `.paper` divs with `<a target="_blank" rel="noopener noreferrer">` for links.

**News entries** (`news.md`): use kramdown definition list syntax. The `dl` grid layout in `_page.scss` handles alignment automatically.

```markdown
**Mon YYYY**
: One-sentence description with optional [linked institute](URL){:target="_blank" rel="noopener noreferrer"}.
```

**External links:** always add `{:target="_blank" rel="noopener noreferrer"}` in markdown files, or `target="_blank" rel="noopener noreferrer"` in raw HTML.

## Git

- Work on a feature branch; never commit directly to `master`.
- Push to GitHub only when ready to publish — some commits may intentionally be held back on local `master`.
