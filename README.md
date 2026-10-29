# Express.js presentations

Run these commands from the project root with `pnpm` and `presenterm` installed.
The first argument is a config name from `md/config/` (currently `d` or `w`), and the second is a Markdown presentation.

## Present a deck

```sh
pnpm run present d md/01-git.md
```

This opens the deck using `md/config/d.yaml`.

## Export a PDF

```sh
pnpm run pdf d md/01-git.md
```

This exports the deck to `pdf/d/01-git-d.pdf`. The output directory is created automatically.
