# Welcome to My GitHub Pages

Alfredワークフローのサンプルを公開しています、というか、遊んでいます
<br>私がAlfred初心者なので、皆さんの参考になれば幸いです
<br>各サンプルのreadmeに開発メモを記載しているのでご参考まで
<br>
<br>
<br>
## Alfred Workflow Examples

[Lesson1.初めてのワークフロー](https://github.com/KitanoTamotsu/googlesuggest)
<br>ソースコードレス・ワークフロー。練習作です。Githubの練習も兼ねて作ってみました
<br>サンプルワークフローのGoogle SuggestをHOTKEYで起動します
<br>
<br>
<br>
[Lesson2.入力パラメータを利用してURLを組み立てる](https://github.com/KitanoTamotsu/googletimeline)
<br><font color=red>Google Timeline</font>を日付指定で開きます。
<br>Alfredとしてはパラメータを受け取り、URLを生成します。
<br>URLのパラメータを設定する最もプリミティブなワークフローの例
<br>キーワードが英語でも日本語でも”発火”します。勝手にバイリンガル起動と呼んでいます
<br>
<br>
<br>
[Lesson3.選択中のテキストを{query}にする](https://github.com/KitanoTamotsu/tripadvisor)
<br>{query}というのはAlfred workflowの受け渡しです
<br>選択中の文字列を受け渡すことで、ソースコードレスとなります
<br>その受け渡したキーワードで<font color=red>Tripadvisor</font>を検索します
<br>
<br>
<br>
[Lesson4.シェルスクリプトでURLエンコードする](https://github.com/KitanoTamotsu/kakaku.comKeywordSearch)
<br><font color=red>価格コム</font>をキーワード検索します
<br>nkfコマンドによる％エンコードを実装しています
<br>
<br>
<br>
[Lesson5.複数のパラメータを利用する](https://github.com/KitanoTamotsu/norikae)
<br><font color=red>ジョルダンの乗り換え案内</font>を検索します
<br>出発駅、到着駅、到着時間という複数のパラメータに対応しています
<br>
<br>
<br>
[Lesson6.Alfredの出力フォーマットを試してみる](https://github.com/KitanoTamotsu/testjson)
<br>Tips3でgoogle suggestを解析したら、Alfredの出力xmlを使っていることがわかりました
<br>Alfredのサンプルを見て真似してみました。JSON出力フォーマットを利用しています
<br>
<br>
<br>
[Lesson7.MXLをパースする](https://github.com/KitanoTamotsu/yahoo)
<br><font color=red>Yahoo!みんなの意見</font>のRSS表示ツールです
<br>AlfredのJSON出力フォーマット出力の利用や
<br>RSSファイル（XML)のパースと要素の抽出などを実装しています
<br>
<br>
<br>
[Lesson8.RSSニュースを検索する](https://github.com/KitanoTamotsu/searchnews)
<br><font color=red>Googleニュース</font>RSSのキーワード検索です
<br>Lesson7の変形です
<br>
<br>
<br>
[Lesson9.ブラウザからURLを取得する](https://github.com/KitanoTamotsu/translate)
<br>ブラウザで開いているページを翻訳します
<br>コアは<font color=red>google translate</font>です
<br>ブラウザから情報を取得するためシェルスクリプトからappleスクリプトを実行しています
<br>もとはconditionalユーティリティとクリップボードを扱うサンプルとして作ったものです
<br>
<br>
<br>
[Lesson10.TVのリモコン](https://github.com/KitanoTamotsu/natureremo)
<br>Alfredの入力でTVを操作します。コアは<font color=red>NatureRemo</font>のAPIです
<br>エキスポート禁止の変数の使い方のサンプルとなります
<br>『TV ++』でテレビのボリュームが2メモリ上げれるので、なかなか面白いかも
<br>もちろんスクリプトを改造すれば、TV以外のリモコンにもなりますよ
<br>
<br>
<br>
[Lesson11.ローカルファイルを利用する](https://github.com/KitanoTamotsu/avatar)
<br><font color=red>Joe Schmoe</font>のAPIを利用してアバターを作成します
<br>リターンされるアバター画像からhtmlを生成してローカルに保存します
<br>
<br>
<br>
[Lesson12.randomユーティリティを使用する](https://github.com/KitanoTamotsu/wikipedia)
<br><font color=red>ウィキペディア</font>のおまかせ表示が興味のない記事ばかりという方におすすめ
<br>カテゴリー内の記事をランダムに表示させることができます
<br>randomユーティリティを利用したコードレスワークフローです
<br>
<br>
<br>
## Tips
ワークフロー作成時のもろもろです
<br>[Tips1.alfredworkflowファイルの作成方法](https://github.com/KitanoTamotsu/tips1/)
<br>[Tips2.ワークフロー用透過アイコンの作成方法](https://github.com/KitanoTamotsu/tips2/)
<br>[Tips3.Google suggest ワークフローを解析してみる](https://github.com/KitanoTamotsu/tips3/)
<br>[Tips4.<font color=red>Mighty Optical Illusion</font> のおまかせページを翻訳する](https://github.com/KitanoTamotsu/tips4/)
<br>
<br>
<br>
## 環境
2021年2月〜　Macbook Air (M1,2020)　OSX 11.1 (BigSur)　Alfred4 & Powerpack
<br>
<br>
<br>
