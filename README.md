# fun

A collection of little web toys. The landing page ([`index.html`](index.html))
is a hub that links to each quiz.

## The Trolley Test

An interactive philosophy toy: 30 trolley-problem dilemmas that map your
choices across seven ethical dials and hand you a moral archetype. Lives in
[`trolley.html`](trolley.html).

## The Holiday Quiz

A travel toy: 20 questions about how you like to travel that map your choices
across six travel dials — pace, setting, budget, planning, sociability, and
curiosity — and reveal your holiday archetype (Beach Lounger, City & Culture
Explorer, Adrenaline Adventurer, and more), plus where you'd thrive. Lives in
[`holiday.html`](holiday.html).

### GitHub Pages

The site deploys automatically via the workflow in
[`.github/workflows/pages.yml`](.github/workflows/pages.yml). To enable it,
go to **Settings → Pages** and set the **Source** to **GitHub Actions**. Once
`main` is updated, the site publishes at:

```
https://clementtay.github.io/fun/
```

Each toy is a self-contained HTML file, so it's also reachable directly — e.g.
`https://clementtay.github.io/fun/holiday.html`.
