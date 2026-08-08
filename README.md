# Yuhei Takahashi Academic Homepage

This repository is configured for GitHub Pages using the
[Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) Jekyll theme.

## Publish

1. Create or open the repository `yuhei-takahashi.github.io`.
2. Put all files in this folder at the repository root.
3. Commit and push them to the default branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select the default branch and `/ (root)`.
7. Open `https://yuhei-takahashi.github.io/`.

## Optional profile photo

Create:

`assets/images/profile.jpg`

Then edit `_config.yml`:

```yaml
author:
  avatar: "/assets/images/profile.jpg"
```

## Main files

- `_config.yml` — site and author settings
- `_data/navigation.yml` — top navigation
- `index.md` — home page
- `_pages/biography.md`
- `_pages/publications.md`
- `_pages/repositories.md`
- `_pages/news.md`
- `assets/css/main.scss` — custom design
