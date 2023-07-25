# Website for Juggling Convention in Herxheim

We use [Hugo](https://gohugo.io/) as a static site generator in combination with
the [hugo-scroll](https://github.com/zjedi/hugo-scroll) theme.

## How to run it locally

Once you have [Hugo](https://gohugo.io/installation/) and [Git](https://github.com/git-guides/install-git) installed, run:

```sh
git submodule update --init --recursive
```

which will download the `hugo-scroll` theme.

Afterwards run

```sh
hugo server
```

and visit http://localhost:1313.

## Deployment

Each commit on the `main` branch triggers a build automatically and deploys the
rendered static site to [GitHub Pages](https://pages.github.com/), see
[deploy.yaml](.github/workflows/deploy.yaml).
