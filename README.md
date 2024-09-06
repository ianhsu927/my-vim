# 我的 vim

## 安装

```bash
# 这里是用 NeoVim
brew install neovim
# 使用 homebrew 安装无法在 root 用户下使用
```

## 插件管理

```bash
# 安装 vim-plug
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
# :PlugInstall 安装依赖
```

