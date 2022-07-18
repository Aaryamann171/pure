# Pure

> Pretty, minimal and fast ZSH prompt

## Fork of the infamous prompt, tweaked a little for my liking.
[original repo](https://github.com/sindresorhus/pure)


### Installation

1. Clone this repo to `$HOME/.zsh/pure`.

```sh
mkdir -p "$HOME/.zsh"
git clone https://github.com/Aaryamann171/pure.git "$HOME/.zsh/pure"
```

2. Add the path of the cloned repo to `$fpath` in `$HOME/.zshrc`.
```sh
# .zshrc
fpath+=($HOME/.zsh/pure)
```

## Init

Initialize the prompt system (if not so already) and choose `pure`:

```sh
# .zshrc
autoload -U promptinit; promptinit
prompt pure
```

