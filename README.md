# Dotfiles

## Lunarvim

Hard link `config.lua` to `~/.config/lvim/config.lua`.

```bash
ln ~/.dotfiles/lvim/config.lua ~/.config/lvim/config.lua
```

Delete if it already exists on destiny.

### Python

Install `pylint`, `black`, and `pyright` via Mason.
`:Mason`

### q

Since directories can't be hard linked, copy paste `indent` and `syntax` into `.config/lvim`
