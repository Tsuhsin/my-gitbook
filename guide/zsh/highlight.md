# Syntax Highlighting 設定

### 下載 zsh-syntax-highlighting
```
brew install zsh-syntax-highlighting
```
### 設定
進vim修改`.zshrc`，加上以下內容：
```
typeset -gA ZSH_HIGHLIGHT_STYLES
# 防止開新視窗style失效(可能跟globle array有相關)
ZSH_HIGHLIGHT_STYLES[alias]=fg=050,bold
ZSH_HIGHLIGHT_STYLES[builtin]=fg=050,bold
ZSH_HIGHLIGHT_STYLES[function]=fg=050,bold
ZSH_HIGHLIGHT_STYLES[command]=fg=050,bold
```
其中`fg=050`這個數字是256色碼，更改可以換顏色
> [色碼表](https://upload.wikimedia.org/wikipedia/commons/1/15/Xterm_256color_chart.svg)

### 套用
```
source .zshrc
```
