# Antharas Classic site

Live site: https://antharas-game.github.io/

## Publish a patch

Edit `site/index.html` in a separate branch, then merge its pull request into `main`. The workflow `.github/workflows/deploy.yml` deploys changes in `site/` automatically through GitHub Pages. You can also run the workflow manually from **Actions → Deploy Antharas site → Run workflow**.

The Telegram button currently opens a placeholder dialog. When the real channel URL exists, set `LINKS.telegram` near the end of `site/index.html`.
