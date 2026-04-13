# dotfiles

## Claude

Config lives in `claude/`. To wire it up on a new machine:

```sh
git clone git@github.com:marioweid/dotfiles.git ~/Sources/dotfiles

for f in CLAUDE.md settings.json commands statusline.sh; do
  ln -sf ~/Sources/dotfiles/claude/$f ~/.claude/$f
done
```

## Caveman
https://github.com/juliusbrussee/caveman

## RTK
https://github.com/rtk-ai/rtk
