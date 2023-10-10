# My terminal environment

## Tabby (Terminal app)

[Download tabby](https://tabby.sh/).

### Tabby config

Copy paste the `tabby.conf` content in Tabby > Configuration > Configuration file.

## Install zsh

```bash
sudo apt install zsh && zsh --version
```

### Oh-my-zsh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### powerlevel10k

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

#### p10k config
```bash
cp ./config-files/.p10k.zsh ~/.p10k.zsh
```

### zsh config
Copy paste the `.zshrc` in `~/.zshrc`.

```bash
cp ./config-files/.zshrc ~/.zshrc
```