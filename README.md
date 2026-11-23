# Antharas Classic site

Live site: https://antharas-game.github.io/

## Publish a patch

Edit `site/index.html` in a separate branch, then merge its pull request into `main`. The workflow `.github/workflows/deploy.yml` deploys changes in `site/` automatically through GitHub Pages. You can also run the workflow manually from **Actions → Deploy Antharas site → Run workflow**.

The Telegram and MAX buttons currently open placeholder dialogs. When the real channel URLs exist, set `LINKS.telegram` and `LINKS.max` near the end of `site/index.html`.
