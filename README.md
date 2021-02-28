# Welcome to My GitHub Pages

Alfredワークフローのサンプルを公開。私がAlfred初心者なので、皆さんの参考になれば幸いです
- 基本的に言語はシェルスクリプト（bin/bash）で作成
- 1リポジトリに1ワークフローを投稿
- それぞれのフォルダーのreadme.txtに、ポイントとなる開発メモを記載
- トップページ以外はGithubリポジトリでの公開（手抜きです）


## Alfred Workflow Examples

<font color='green'>Lesson1.初めてのワークフロー</font>　[Google Suggest](https://github.com/KitanoTamotsu/googlesuggest)
<br>ソースコードレス・ワークフロー。
<br>練習作です。Githubの練習もかねて作ってみました。


<font color='green'>Lesson2.入力パラメータを利用してURLを組み立てる</font>　
[Google Timeline](https://github.com/KitanoTamotsu/googletimeline)
<br>キーワードとパラメータを受け取り、URLを開きます。
<br>URLのパラメータを設定する最もプリミティブなワークフローの例です。
<br>また、Alfredの機能で実現してますが、キーワードが英語でも日本語でも”発火”します。
<br>勝手にバイリンガル起動と呼んでいます。




<font color='green'>Lesson3.選択中のテキストとHOTKEYで起動させる</font>　
[Tripadvisor](https://github.com/KitanoTamotsu/tripadvisor)
<br>ソースコードレス・ワークフロー。
<br>選択中の文字列をAlfredのパラメータとして利用します。




<font color='green'>Lesson4.シェルスクリプトでURLエンコードする</font>　
[価格コム検索](https://github.com/KitanoTamotsu/kakaku.comKeywordSearch)
<br>価格コムをキーワード検索します。
<br>nkfコマンドによる％エンコードを実装しています。




<font color='green'>Lesson5.複数のパラメータを利用する</font>　
[電車ルート検索](https://github.com/KitanoTamotsu/norikae)
<br>ジョルダンの乗り換え案内を検索します。
<br>出発駅、到着駅、到着時間という複数のパラメータに対応しています。




<font color='green'>Lesson6.Alfredの出力フォーマットを試してみる</font>　
[JSONのテスト](https://github.com/KitanoTamotsu/testjson)
<br>Tips3でgoogle suggestを解析したら、Alfredの出力xmlを使っていることがわかりました。
<br>Alfredのサンプルを見て真似してみました。JSON出力フォーマットを利用しています。




<font color='green'>Lesson7.MXLをパースする</font>　
[Yahoo!みんなの意見RSS](https://github.com/KitanoTamotsu/yahoo)
<br>JSON出力フォーマットの利用を考えていたらRSSに辿り着きました。
<br>AlfredのJSON出力フォーマット出力の利用や
<br>RSSファイル（XML)のパースと要素の抽出などを実装しています。




## Tips
ワークフロー作成時のもろもろです
1.[alfredworkflowファイルの作成方法](https://github.com/KitanoTamotsu/tips1/)
2.[ワークフロー用透過アイコンの作成方法](https://github.com/KitanoTamotsu/tips2/)
3.[Google suggest ワークフローを解析してみる](https://github.com/KitanoTamotsu/tips3/)




## 環境
2021年2月〜　Macbook Air (M1,2020)　OSX 11.1 (BigSur)　Alfred4 & Powerpack
