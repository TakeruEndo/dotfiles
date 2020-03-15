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

