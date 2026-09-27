# GitHub Contribution Snake — siddharth-ss

This repository generates the GitHub contribution Snake used in the
`siddharth-ss` profile README.

## Files

- `.github/workflows/snake.yml` — GitHub Actions workflow
- `output` branch — generated SVG files

## Generated files

- `github-snake.svg` — light theme
- `github-snake-dark.svg` — dark theme

The workflow runs daily at 00:00 UTC and can also be started manually
from the GitHub Actions tab.

## Profile README

Add this to the `siddharth-ss` profile README:

```html
<h2 align="center">📊 Contribution Activity</h2>

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/siddharth-ss/github-snake/output/github-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/siddharth-ss/github-snake/output/github-snake.svg"
    />
    <img
      src="https://raw.githubusercontent.com/siddharth-ss/github-snake/output/github-snake.svg"
      alt="GitHub Contribution Snake"
      width="100%"
    />
  </picture>
</p>
```
