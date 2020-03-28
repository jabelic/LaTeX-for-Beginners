# LaTeX テキスト for Freashman

##### Auther (*編集者は記述しておくこと. 貢献順ではありません.*)

Meiji Univ. IMS/MS B3 Jabelic

---
## What is LaTeX
>TeX は Donald Ervin Knuth によって開発された，フリーの「組版システム」です。 すなわち，活版印刷のような「文字や図版などの要素を紙面に配置する」という作業をコンピュータで行います。(LaTeX入門 - TeX Wiki)


#### 使用用途
- レポート作成
- 論文執筆
- 本やテキストの執筆
- ハガキの宛名(やろうと思えば)

---
## How to install

明治大学総合数理学部現象数理学科では基本的には一律で同じMacbookAirを買うことになっていて、その中にはきちんとLaTeXが入っていると思います。アプリケーションの`TeXShop`を開けばすぐに使えます。


現象数理学科で何かの都合でご自身で別のMacbookを使っている場合や, __現象数理学科以外の学生__ は最初からLaTeXが実行できる環境は整っていないと思われますので、その方々向けに説明を書いておきます。


#### macOS(MacBookAir, MacBookPro, iMac等)

1. XcodeをApp Storeから`install`する
2. `Xcode Command Line Tools`を`install`する
```bash=
$ xcode-select --install
```

3. `Homebrew`を`install`する
```bash=
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```


4.  ミラーサイト等からpkgファイルをダウンロードしてくる(3時間ほどかかる)
    
    [ミラーサイト一覧](https://texwiki.texjp.org/?MacTeX#mirror)

5. `tlmgr`でTeXLiveレポジトリを最新版にアップデート

```bash=
$ sudo tlmgr update --self --all
```


6. `Homebrew`で`macTeX`を`install`

```bash=
$ brew cask install mactex
$ sudo tlmgr update --self --all
$ sudo tlmgr paper a4 
```


7. 日本語を使えるようにしておく

    [TeXShopで日本語を使う方法](https://medemanabu.net/latex/mactex-texshop-ptex-platex/)



---
## How to use







---
## 参考文献

[MacTeX 2018 のインストール＆日本語環境構築法](https://doratex.hatenablog.jp/entry/20180501/1525144736)
