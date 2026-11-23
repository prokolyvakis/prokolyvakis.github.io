# prokolyvakis.github.io

Source of [my personal website](https://prokolyvakis.github.io/): who I am, what I work on, and selected publications.

Built with [Hugo](https://gohugo.io/) and the [Bear Cub](https://github.com/clente/hugo-bearcub) theme, deployed to GitHub Pages by the workflow in `.github/workflows/hugo.yaml` on every push to `main`.

## Run locally

```sh
git clone --recurse-submodules git@github.com:prokolyvakis/prokolyvakis.github.io.git
cd prokolyvakis.github.io
hugo server
```

Then open http://localhost:1313/. If you already cloned without the theme, run `git submodule update --init`.

## Layout

- `content/` pages and blog posts
- `assets/custom.css` site styles on top of the theme
- `layouts/partials/` small overrides of the theme (header, nav, social icons, head tags)
- `themes/hugo-bearcub/` the theme, as a git submodule

## License

[CC BY 4.0](LICENSE).
