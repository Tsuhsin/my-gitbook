#  設定主題
### 修改 `.zshrc`
1. 切資料夾至Home `cd ~`
2. 列出所有資料(包含隱藏檔) `ls -la` 會看到名稱為 `.zshrc` 的檔案
3. 修改此檔案 `vim .zshrc`
4. 進到vim之後會看到`ZSH_THEME="bira"` 這句，代表現在套用的主題為`bira`，修改引號內的內容即可更換主題

### 有哪些主題
`cd ~/.oh-my-zsh/themes`可以看有哪些主題，[這裡](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes)可以看主題長什麼樣子

### agnoster主題
如果換了agnoster主題會需要[下載字型](https://github.com/powerline/fonts)，否則會有亂碼出現，如下圖
![](https://i.imgur.com/KMAEGPC.png)

#### 下載字型
將字型clone至Home
```
git clone https://github.com/powerline/fonts.git
sudo ./fonts/install.sh
```
#### 設定字型
以 iTerm2 為例：

iTerm2 > Preference > Profiles > Text > Change Font <br>
將字型改成 `Meslo LG M DZ for Powerline`
![](https://i.imgur.com/kk87Aue.png)
![](https://i.imgur.com/sTJ70cr.png)

### 修改完成
(左: `bira` ; 右: `agnoster` )
![](https://i.imgur.com/CbvB96R.png)
