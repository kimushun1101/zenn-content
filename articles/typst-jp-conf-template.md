---
title: "Typst で日本語論文のテンプレートを作成しました"
emoji: "🇯🇵"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["Typst"]
published: true
---

【テスト記事】
https://github.com/kimushun1101/typst-jp-conf-template
からののコピペです．

# typst-jp-conf-template

Typst で日本語論文を書くときのテンプレートです．
Typst の概要について知りたい方は，https://github.com/kimushun1101/How-to-use-typst-for-paper-jp をご覧ください．


[vscode-typst.webm](https://github.com/kimushun1101/typst-jp-conf-template/assets/13430937/f227b85b-0266-417b-a24a-54f28f9a71b8)


| ファイル  | 意味                    |
| -------- | ----------------------- |
| main.typ | 原稿の Typst ソースコード |
| refs.*　 | 参考文献ファイル          |


| ディレクトリ | 含まれるファイルの種類          |
| ------------- | --------------------------- |
| figs　　      | 論文に使用する画像ファイル    |
| libs　　      | 体裁を整えるライブラリファイル |


雰囲気を掴みたい場合には [こちらの Typst Web Application](https://typst.app/project/wXmeFlJ5bhx1awSRuJRiUf) をお試しください．  
コンパイル済みの資料を確認したいだけでしたら [こちらの GitHub Pages](https://kimushun1101.github.io/typst-jp-conf-template/typst-jp-conf.pdf) からお読みできます．

## 使用方法
GitHub に慣れていない方は，GitHub ページの `<>Code▼` から `Download ZIP` して展開してください．  
慣れている方は，`git clone` したり `use this template` したり，適宜扱ってください．

### VS Code を使用する場合
1. [VS Code](https://code.visualstudio.com/) をインストール．
2. VS Code で `File`→`Open Folder` でこのフォルダーを開く．  
3. 推奨拡張機能をインストール．  
  Extensions (`Ctrl` + `Shift` + `X`) の `Search Extensions in Marketplace` のテキストボックスに `@recommended` と入力すると表示される，以下の拡張機能をinstall をクリック．  
    - [Tinymist Typst](https://marketplace.visualstudio.com/items?itemName=myriad-dreamin.tinymist)
4. Explorer (`Ctrl` + `Shift` + `E`) から `main.typ` を開いた状態で，画面右上にある Typst Preview の方の ![view-icon](https://github.com/kimushun1101/typst-jp-conf-template/assets/13430937/a44c52cb-d23a-4fdb-ac9f-dc2b47deb40a) アイコンをクリック (
 `Ctrl` + `K` のあと `V`) でプレビューを表示．[トップにある動画](#typst-jp-conf-template) の操作です．
5. `Ctrl` + `S` で PDF を生成．

### 他のエディターで執筆する場合

筆者は試せていませんが，他のエディターでも同様の拡張機能はありそうです．  
また，Typst のインストールおよびコンパイルはコマンドラインでも行えます．  
お使いの OS によってインストール方法が異なるため，詳細は[別ページ](docs/native-install.md)にまとめました．

## 参考元
- (unofficial) IFAC Conference Template for Typst : https://github.com/typst/packages/tree/main/packages/preview/abiding-ifacconf/0.1.0
- charged-ieee : https://github.com/typst/packages/tree/main/packages/preview/charged-ieee/0.1.0
- IEEE style as per the 2021 guidelines, V 01.29.2021. : https://editor.citationstyles.org/styleInfo/?styleId=http%3A%2F%2Fwww.zotero.org%2Fstyles%2Fieee
- GitHub Pages へのデプロイ : https://github.com/yukukotani/typst-coins-thesis

## ライセンス
参考元にならってライセンスを付与しています．  
Typst ファイル : MIT No Attribution  
CSL ファイル : Creative Commons Attribution-ShareAlike 3.0 License  