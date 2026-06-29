# Learning in Public — Bootstrap Migration

A small personal "learning in public" notebook site, migrated from
CSS to **Bootstrap 5**.

## Live site

```html
https://github.com/MartimLou95/bootstrap-website
```

## Pages

| File            | Purpose                                                             |
| --------------- | ------------------------------------------------------------------- |
| `index.html`    | Home — intro and "Start Here" / "Why Bother" / "Learning Now" cards |
| `learning.html` | Journal index, grouped into topic cards                             |
| `contact.html`  | Contact form                                                        |
| `entry.html`    | Full article: notes on _Atomic Habits_                              |
| `images/`       | Article images                                                      |

## What changed in the migration

- **No custom CSS.**&#x20;
  All styling now comes from Bootstrap utility classes and components.
- **Components used:** responsive Navbar (collapses to a hamburger), Cards,
  List groups, Form controls, Badges, Buttons.
- **Grid system** — the old two-column flex layout is now `container → row →
col-md-3 / col-md-9`, which stacks automatically on small screens.
- **Responsive** — verified with no horizontal overflow from desktop down to
  narrow mobile widths.
- **Modern styling** — sticky shadowed navbar, hero headers, borderless
  soft-shadow cards with subtle colored Bootstrap Icons headers, pill badges,
  and a sticky footer — all using Bootstrap utilities and Bootstrap Icons, no
  custom CSS.
