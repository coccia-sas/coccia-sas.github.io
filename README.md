# Michael Coccia — Academic Website

Personal job-market website for Michael Coccia, PhD candidate in Finance at the
University of Mississippi. Plain static HTML/CSS, hosted on GitHub Pages.

## Structure

```
index.html        # the whole site (single page, anchored sections)
style.css         # styles + light/dark theme; accent color set in :root
assets/
  cv.pdf          # curriculum vitae
  crumbs.pdf      # "Crumbs on the Tape" working paper
  algo-events.pdf # "Algorithmic Trading and Information Dynamics" working paper
  jmp.pdf         # job market paper (add when ready)
  headshot.jpg    # headshot
```

## Editing

Everything is in `index.html`. Remaining `TODO` comments mark the one open item
(the job market paper PDF). To change the accent color, edit `--accent` in
`style.css`.

## Deploy

Pushing to the `main` branch of a repo named `coccia-sas.github.io` publishes to
`https://coccia-sas.github.io/`. See repo settings → Pages.
