# vimrcの管理

シンボリックリンクの作成
```
ln -s ~/dotfiles/_vimrc ~/.vimrc
ln -s ~/dotfiles/_gvimrc ~/.gvimrc
```

# vim-plugの導入
ダウンロード
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
プラグインの追加
```
call plug#begin()
Plug 'tpope/vim-sensible'
call plug#end()
```
プラグインのインストール
```
# vimrc上で
:PlugInstall
```

# NERDTree
vimフォルダのツリー表示
### よく使うコマンド
```
ツリー表示
:NERDTree
ツリーを閉じる
:q
コマンド確認
?
```

# vim
## 一括処理
```
Ctrl + v :visulaモード
shift + i: 挿入モード
文字入力
Escで戻る

# 一括コメントアウト(plugin導入ずみ)
範囲選択
Ctrl + - を２回入力
```


# zshrc
以下の設定を参考にした
https://gist.github.com/mollifier/4979906

## zplug
必要になったらzplugかzinitを入れる
https://qiita.com/Jung0/items/300f8b83520e56766f22

### 参照
#### もっとも参考にした
[脱初心者を目指すVimmerにオススメしたいVimプラグインや.vimrcの設定](https://qiita.com/jnchito/items/5141b3b01bced9f7f48f)
#### その他
- http://holypp.hatenablog.com/entry/20110515/1305443997
- https://qiita.com/jnchito/items/5141b3b01bced9f7f48f
- [何も考えずにvimcにこれを書くんだ](https://qiita.com/morikooooo/items/9fd41bcd8d1ce9170301)
#### NerdTreeのリポジトリ
- https://github.com/preservim/nerdtree
#### vimPlugのリポジトリ
- https://github.com/junegunn/vim-plug
#### zsh設定関係
- https://qiita.com/ktr_type23/items/3eb782f98c7a5f4c60b0
- https://qiita.com/hiroyuki827/items/4e87ce517a4894f092e8
