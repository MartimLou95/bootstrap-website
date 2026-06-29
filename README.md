# Learning in Public — Bootstrap Migration

A small personal "learning in public" notebook site, migrated from hand-written
CSS to **Bootstrap 5**. This was a bootcamp challenge: take an existing static
site and rebuild its styling with the Bootstrap framework.

## Live site

<!-- Replace this with your GitHub Pages URL once deployed -->
https://MartimLou95.github.io/bootstrap-website/

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Home — intro and "Start Here" / "Why Bother" / "Learning Now" cards |
| `learning.html` | Journal index, grouped into topic cards |
| `contact.html` | Contact form |
| `entry.html` | A full article: notes on *Atomic Habits* |
| `images/` | Article images |

## What changed in the migration

- **No custom CSS.** The original `style.css` (~335 lines) was removed entirely;
  all styling now comes from Bootstrap utility classes and components.
- **Bootstrap via CDN** — linked in each page's `<head>`, no build step.
- **Components used:** responsive Navbar (collapses to a hamburger), Cards,
  List groups, Form controls, Badges, Buttons.
- **Grid system** — the old two-column flex layout is now `container → row →
  col-md-3 / col-md-9`, which stacks automatically on small screens.
- **Responsive** — verified with no horizontal overflow from desktop down to
  narrow mobile widths.

## Run it locally

It's plain HTML — just open `index.html` in a browser. Or serve the folder:

```
npx live-server
```

## Tech

HTML5 · Bootstrap 5.3 (CDN) · no JavaScript of its own
