# vismiroglou.github.io

Personal portfolio site built with [Hugo](https://gohugo.io/) and the [Blowfish](https://blowfish.page/) theme, deployed to GitHub Pages via GitHub Actions.

## Development

```sh
hugo server -D
```

Visit http://localhost:1313.

## Adding a project

Add a new page bundle under `content/projects/`:

```sh
hugo new content projects/my-project/index.md
```

## Deployment

Pushing to `main` triggers `.github/workflows/hugo.yml`, which builds the site and publishes it to GitHub Pages. In the repo settings, set **Pages > Build and deployment > Source** to **GitHub Actions**.
