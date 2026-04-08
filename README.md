# slidev-theme-astro

The Astro theme for Slidev.

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

```yaml
---
theme: astro
---
```

Learn more about [how to use a theme](https://sli.dev/guide/theme-addon#use-theme).

## Features

### `text-gradient` class

Use the `text-gradient` to have a nice looking gradient:

```md
# Something <span class="text-gradient font-normal">big</span>
```

You can customize the gradient colors in `slides.md`:

```yaml
---
theme: astro
themeConfig:
    gradient-from: red
    gradient-to: blue
---
```

## Licensing

[MIT Licensed](./LICENSE). Made with ❤️ by [Florian Lefebvre](https://github.com/florian-lefebvre).

This theme is forked from `@slidev/theme-apple-basic`.
