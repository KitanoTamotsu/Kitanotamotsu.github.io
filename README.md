# Welcome to My GitHub Pages

Alfredワークフローのサンプルを公開します
- 基本的に言語はシェルスクリプト（bin/bash）で作成します
- 1リポジトリに1ワークフローを投稿します
- それぞれのフォルダーのreadme.txtに、ポイントとなる開発メモを残します
- 私がAlfred初心者なので、皆さんの参考になれば幸いです
- トップページ以外はGithubリポジトリでの公開とします（手抜きです）

## Alfred Workflow Examples

### Lesson1.初めてのワークフロー
[Google Suggest](https://github.com/KitanoTamotsu/googlesuggest)<br>
ソースコードレス・ワークフロー。練習作です。Githubの練習もかねて作ってみました。

### Lesson2.入力パラメータを利用してURLを組み立てる
[Google Timeline](https://github.com/KitanoTamotsu/googletimeline)<br>
キーワードとパラメータを受け取り、URLを開きます。URLのパラメータを設定する最もプリミティブなワークフローの例です。
また、Alfredの機能で実現してますが、キーワードが英語でも日本語でも”発火”します（バイリンガル起動）

### Lesson3.選択中のテキストとHOTKEYで起動させる
[Tripadvisor](https://github.com/KitanoTamotsu/tripadvisor)<br>
ソースコードレス・ワークフロー。HOTKEYを押すと、選択中の文字列でトリップアドバイザーを検索します。

### Lesson4.シェルスクリプトでURLエンコードする
[価格コム検索](https://github.com/KitanoTamotsu/kakaku.comKeywordSearch)<br>
価格コムをキーワード検索します。％エンコードを試してみました。

### Lesson5.複数のパラメータを利用する
[電車ルート検索](https://github.com/KitanoTamotsu/norikae)<br>
ジョルダンの乗り換え案内を検索します。出発駅、到着駅、到着時間という複数のパラメータに対応しています。

### Lesson6.Alfredの出力フォーマットを試してみる
[Alfred JSON formatのテスト](https://github.com/KitanoTamotsu/testjson)<br>
Tips3でgoogle suggestを解析したらxmlでalfredのリターン用インターフェイスを作成しているようでした。
現状ではJSONが推奨とのことで試してみました.といってもAlfredのサンプルを使っているだけです。

### Lesson7.MXLをパースする
[Yahoo!みんなの意見RSS](https://github.com/KitanoTamotsu/yahoo)<br>
Lesson6でテストしたJSONフォーマットを利用して何かできないものかと考えていたらRSSに辿り着きました。
AlfredのJSONフォーマット出力の利用、RSSファイル（XML)のパースと要素の抽出などを実装しています。


## Tips
ワークフォロー作成時のもろもろです

 1.[alfredworkflowファイルの作成方法](https://github.com/KitanoTamotsu/tips1/)
 
 2.[ワークフロー用透過アイコンの作成方法](https://github.com/KitanoTamotsu/tips2/)

 3.[Google suggest ワークフローを解析してみる](https://github.com/KitanoTamotsu/tips3/)



## 環境
2021年2月〜　Macbook Air (M1,2020)　OSX 11.1 (BigSur)　Alfred4 & Powerpack
