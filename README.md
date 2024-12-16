# zsh-ahoy

The Zsh completion plugin for [Ahoy](https://github.com/ahoy-cli/ahoy).

## Installation

### Oh-My-Zsh

1. Clone this repository into the `$ZSH_CUSTOM/plugins` directory (by default `~/.oh-my-zsh/custom/plugins`).

```bash
git clone https://github.com/ahoy-cli/zsh-ahoy.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/ahoy
```

2. Add the ahoy zsh plugin to the list of plugins for [Oh My Zsh](https://ohmyz.sh/) to load, inside `~/.zshrc`:

```
plugins=(
    # Other plugins above...
    ahoy
)
```

3. Start a new terminal session.

### Manual

1. Clone this repository somewhere on your machine. This guide will assume `~/.config/zsh-ahoy`

```bash
git clone https://github.com/ahoy-cli/zsh-ahoy.git ~/.config/zsh-ahoy
```

2. Append `source ~/.config/zsh-ahoy/zsh-ahoy.zsh` to your `.zshrc`:

```bash
echo "source ~/.config/zsh-ahoy/zsh-ahoy.zsh" >> ~/.zshrc
```

3. Start a new terminal session.

## Further information about Zsh completions

See the [`zsh-completions`](https://github.com/zsh-users/zsh-completions) project for more examples, further information about Zsh completions, or to write your own and be inspired to help out with this project!
