# Welcome to My GitHub Pages

Alfredワークフローのサンプルを公開。私がAlfred初心者なので、皆さんの参考になれば幸いです
- 基本的に言語はシェルスクリプト（bin/bash）で作成
- 1リポジトリに1ワークフローを投稿
- それぞれのフォルダーのreadme.txtに、ポイントとなる開発メモを記載
- トップページ以外はGithubリポジトリでの公開（手抜きです）


## Alfred Workflow Examples

[Lesson1.初めてのワークフロー](https://github.com/KitanoTamotsu/googlesuggest)
<font size=1>ソースコードレス・ワークフロー。練習作です。Githubの練習もかねて作ってみました。
<br>Google SuggestをHOTKEYで起動します。</font>




[Lesson2.入力パラメータを利用してURLを組み立てる](https://github.com/KitanoTamotsu/googletimeline)
<br>Google Timelineを日付指定で開きます。
<br>Alfredとしてはパラメータを受け取り、URLを生成します。
<br>URLのパラメータを設定する最もプリミティブなワークフローの例。
<br>キーワードが英語でも日本語でも”発火”します。勝手にバイリンガル起動と呼んでいます。



[Lesson3.選択中のテキストとHOTKEYで起動させる](https://github.com/KitanoTamotsu/tripadvisor)
<br>ソースコードレス・ワークフロー。
<br>選択中の文字列を取得して、Tripadvisorを検索します。



[Lesson4.シェルスクリプトでURLエンコードする](https://github.com/KitanoTamotsu/kakaku.comKeywordSearch)
<br>価格コムをキーワード検索します。
<br>nkfコマンドによる％エンコードを実装しています。




[Lesson5.複数のパラメータを利用する](https://github.com/KitanoTamotsu/norikae)
<br>ジョルダンの乗り換え案内を検索します。
<br>出発駅、到着駅、到着時間という複数のパラメータに対応しています。



[Lesson6.Alfredの出力フォーマットを試してみる](https://github.com/KitanoTamotsu/testjson)
<br>Tips3でgoogle suggestを解析したら、Alfredの出力xmlを使っていることがわかりました。
<br>Alfredのサンプルを見て真似してみました。JSON出力フォーマットを利用しています。



[Lesson7.MXLをパースする](https://github.com/KitanoTamotsu/yahoo)
<br>JSON出力フォーマットの利用を考えていたらRSSに辿り着きました。
<br>AlfredのJSON出力フォーマット出力の利用や
<br>RSSファイル（XML)のパースと要素の抽出などを実装しています。
<br>Yahoo!みんなの意見のRSS表示ツールです。



## Tips
ワークフロー作成時のもろもろです
<br>[Tips1.alfredworkflowファイルの作成方法](https://github.com/KitanoTamotsu/tips1/)
<br>[Tips2.ワークフロー用透過アイコンの作成方法](https://github.com/KitanoTamotsu/tips2/)
<br>[Tips3.Google suggest ワークフローを解析してみる](https://github.com/KitanoTamotsu/tips3/)




## 環境
2021年2月〜　Macbook Air (M1,2020)　OSX 11.1 (BigSur)　Alfred4 & Powerpack
