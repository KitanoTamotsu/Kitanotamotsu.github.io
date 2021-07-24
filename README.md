# Welcome to My GitHub Pages
<br>Alfredワークフローのサンプルを公開しています、というか、遊んでいます
<br>私がAlfredやシェルスクリプト初心者なので、皆さんの参考になれば幸いです
<br>各サンプルのreadmeに開発メモを記載しているのでご参考まで
<br>

## テーブルレイアウト実験中

| | |
|:--|:--|
| 2021-02-14 | [Lesson1.初めてのワークフロー](https://kitanotamotsu.github.io/googlesuggest)   |
|<a href="https://user-images.githubusercontent.com/40127279/126853221-7f6cee62-c8b2-487e-b77f-14cd7857ac9e.png"><img width="200"  src="https://user-images.githubusercontent.com/40127279/126853221-7f6cee62-c8b2-487e-b77f-14cd7857ac9e.png"></a>　|<font size=1>ソースコードレス・ワークフロー。練習作です。Githubの練習も兼ねて作ってみました。サンプルワークフローのGoogle SuggestをHOTKEYで起動します|

<br>
## Alfred Workflow Examples
<br>2021-02-14<br>
[Lesson1.初めてのワークフロー](https://kitanotamotsu.github.io/googlesuggest) 
<br>ソースコードレス・ワークフロー。練習作です。Githubの練習も兼ねて作ってみました
<br>サンプルワークフローのGoogle SuggestをHOTKEYで起動します
<br>
<br>
<br>2021-02-14<br>
[Lesson2.入力パラメータを利用してURLを組み立てる](https://kitanotamotsu.github.io/googletimeline) 
<br><font color=red>Google Timeline</font>を日付指定で開きます。
<br>Alfredとしてはパラメータを受け取り、URLを生成します。
<br>URLのパラメータを設定する最もプリミティブなワークフローの例
<br>キーワードが英語でも日本語でも”発火”します。勝手にバイリンガル起動と呼んでいます
<br>
<br>
<br>
<br>2021-02-19<br>
[Lesson3.選択中のテキストを{query}にする](https://kitanotamotsu.github.io/tripadvisor) 
<br>{query}というのはAlfred workflowの受け渡しです
<br>シェルスクリプトを扱う方には受け渡しというより標準出力という方が通じるかな
<br>選択中の文字列を受け渡すことで、ソースコードレスとなります
<br>その受け渡したキーワードで<font color=red>Tripadvisor</font>を検索します
<br>
<br>
<br>
<br>2021-02-20<br>
[Lesson4.シェルスクリプトでURLエンコードする](https://kitanotamotsu.github.io/kakaku.comKeywordSearch) 
<br><font color=red>価格コム</font>をキーワード検索します
<br>nkfコマンドによる％エンコードを実装しています
<br>
<br>
<br>
<br>2021-02-20<br>
[Lesson5.複数のパラメータを利する](https://kitanotamotsu.github.io/norikae) 
<br><font color=red>ジョルダンの乗り換え案内</font>を検索します
<br>出発駅、到着駅、到着時間という複数のパラメータに対応しています
<br>
<br>
<br>
<br>2021-02-20<br>
[Lesson6.Alfredの出力フォーマットを試してみる](https://kitanotamotsu.github.io/testjson) 
<br>Tips3でgoogle suggestを解析したら、Alfredの出力xmlを使っていることがわかりました
<br>Alfredのサンプルを見て真似してみました。JSON出力フォーマットを利用しています
<br>
<br>
<br>
<br>2021-02-27<br>
[Lesson7.MXLをパースする](https://kitanotamotsu.github.io/yahoo) 
<br><font color=red>Yahoo!みんなの意見</font>のRSS表示ワークフローです
<br>AlfredのJSON出力フォーマット出力の利用や
<br>RSSファイル（XML)のパースと要素の抽出などを実装しています
<br>
<br>
<br>
<br>2021-03-02<br>
[Lesson8.RSSニュースを検索する](https://kitanotamotsu.github.io/searchnews) 
<br><font color=red>Googleニュース</font>RSSのキーワード検索です
<br>Lesson7の変形です
<br>
<br>
<br>
<br>2021-03-07<br>
[Lesson9.ブラウザからURLを取得する](https://kitanotamotsu.github.io/translate) 
<br>ブラウザで開いているページを翻訳します
<br>コアは<font color=red>google translate</font>です
<br>ブラウザから情報を取得するためシェルスクリプトからappleスクリプトを実行しています
<br>もとはconditionalユーティリティとクリップボードを扱うサンプルとして作ったものです
<br>
<br>
<br>
<br>2021-03-13<br>
[Lesson10.TVのリモコン](https://kitanotamotsu.github.io/natureremo) 
<br>Alfredの入力でTVを操作します。コアは<font color=red>NatureRemo</font>のAPIです
<br>エキスポート禁止の変数の使い方のサンプルとなります
<br>『TV ++』でテレビのボリュームが2メモリ上げれるので、なかなか面白いかも
<br>もちろんスクリプトを改造すれば、TV以外のリモコンにもなりますよ
<br>
<br>
<br>
<br>2021-03-13<br>
[Lesson11.ローカルファイルを利用する](https://kitanotamotsu.github.io/avatar) 
<br><font color=red>Joe Schmoe</font>のAPIを利用してアバターを作成します
<br>リターンされるアバター画像からhtmlを生成してローカルに保存します
<br>
<br>
<br>
<br>2021-03-14<br>
[Lesson12.randomユーティリティを使用する](https://kitanotamotsu.github.io/wikipedia) 
<br><font color=red>ウィキペディア</font>のおまかせ表示が興味のない記事ばかりという方におすすめ
<br>カテゴリー内の記事をランダムに表示させることができます
<br>randomユーティリティを利用したコードレスワークフローです
<br>
<br>
<br>
<br>2021-03-20<br>
[Lesson13.randomユーティリティの選択肢を動的に設定する](https://kitanotamotsu.github.io/favo) 
<br>お気に入りのURLを保存しておき、好きな時にランダムに表示させるお<font color=red>遊びワークフロー</font>です
<br>randomユーティリティのワードリストを外部ファイルから動的に作成しています
<br>またNotificationに渡すメッセージをArg and Varsでセットしています
<br>
<br>
<br>
<br>2021-03-20<br>
[Lesson14.RSSやHTMLをパースする/出力する一覧をコントロールする](https://kitanotamotsu.github.io/rssmania) 
<br>多数のRSSをAlfredに出力するおもちゃ、その名も<font color=red>RSSマニア</font>です
<br>パラメータの文字数で記事一覧のページ替えをコントロールしています
<br>Alfredのインクリメンタルサーチと紐づいて、いろいろと応用が効く使い方だと思います
<br>
<br>
<br>
<br>2021-03-21<br>
[Lesson15.Arg and Varsオブジェクトの変数を動的にセットする](https://kitanotamotsu.github.io/sourceviewer) 
<br>RSSやHTMLのソースを表示させるツール<font color=red>『ソースビュー』</font>です
<br>ソースはテキストファイルとして保管します
<br>その際、ファイル名に使う日時をArg and Varsオブジェクトで設定しています
<br>
<br>
<br>
<br>2021-03-21<br>
[Lesson16.出力フォーマットへランダムにセットする](https://kitanotamotsu.github.io/trivia) 
<br>伝説の雑学番組<font color=red>トリビアの泉</font>の雑学をランダムに表示します
<br>ツールではインターネットアクセスしていませんが、元ネタはこちらです
<br>https://www.noncky.net/trivia/
<br>
<br>
<br>
<br>2021-03-28<br>
[Lesson17.Alfred環境変数を使ってカスタマイズ設定を可能とする](https://kitanotamotsu.github.io/nazonazo) 
<br>なぞなぞを出題するお遊びワークフローです
<br>1度に出題する問題数や、出題したなぞなぞを保存する場所をカスタマイズできます
<br>なぞなぞサイト<font color=red>『なぞQ.com』</font>からの出題です
<br>
<br>
<br>
<br>2021-04-04<br>
[Lesson18.別のワークフローを呼び出す](https://kitanotamotsu.github.io/tv) 
<br>Lesson10で<font color=red>NatureRemo</font>のAPを使ってTVを操作するワークフローを作成しましたが
<br>今回はその入口にTV番組表を追加しました
<br>
<br>
<br>
<br>2021-04-11<br>
[Lesson19.ホットキーツールを作成する／後続フローを二股にする](https://kitanotamotsu.github.io/quickterminal) 
<br>選択しているテキストによってURLをOPENしたり、
<br>TERMINALで実行したり、ブラウザで検索したりします
<br>勝手に<font color=red>『クイックターミナル』</font>と名付けました
<br>Hotkey起動時の選択テキストの連携や、
<br>Colditionalオブジェクトのgrep判定の機能をつかいます
<br>ターミナルでの実行とクリップボードへのコピーは後続フローを二股にして非同期に処理しています
<br>
<br>
<br>
<br>2021-04-17<br>
[Lesson20.テキストファイルを行ごとに配列に読み込む](https://kitanotamotsu.github.io/meigen) 
<br>ネットサーフィンなどでみつけた名言を保存するツール<font color=red>『自分で集める名言集』</font>です
<br>Alfredの機能ではないですが、テキストファイルの読み書きの小技を使っています
<br>1行目に書き出したり、行単位に配列に読み込んだりしています
<br>
<br>
<br>2021-04-24<br>
[Lesson21.『アレクサ、うんちく教えて』をワークフローにする](https://kitanotamotsu.github.io/unchiku) 
<br>お遊びで、<font color=red>アレクサ</font>の真似をしてみました
<br>『うんちく教えて』でも、『雑学教えて』でも、『豆知識教えて』でも起動するマルチキーワード構造です
<br>
<br>
<br>
<br>2021-05-01<br>
[Lesson22.スクリプトフィルターとキーワードインプットをハイブリッドにする](https://kitanotamotsu.github.io/aircon) 
<br><font color=red>NatureRemo</font>のAPIを利用してエアコンを操作します
<br>Lesson10と18でテレビを操作しましたが、今回はエアコンです
<br>室温や湿度を確認できます
<br>
<br>
<br>
<br>2021-05-08<br>
[Lesson23.スクリプトフィルターをワークフローの途中で使う](https://kitanotamotsu.github.io/ameba) 
<br>ランダムに<font color=red>amebaブログ</font>のRSSを読み込んで記事一覧を表示させます
<br>Lesson14のRSSマニア等の変形です
<br>スクリプトフィルターがワークフローの途中でも利用できることがわかったので
<br>また用途が広がりますね
<br>
<br>
<br>
<br>2021-05-16<br>
[Lesson24.Alfredの出力を10件以上に設定する／濁音・半濁音検索に対応する](https://kitanotamotsu.github.io/recipe) 
<br>NHKレシピサイト<font color=red>『きょうのみんなの料理』</font>の検索結果を表示させています
<br>また、作成中に判明した、濁音・半濁音を含む検索にも対応しています
<br>
<br>
<br>
<br>2021-05-22<br>
[Lesson25.スニペット起動を使ってみる](https://kitanotamotsu.github.io/now) 
<br>ワークフローのトリガーにスニペットがあったので気になって使ってみました
<br>スクリプトフィルターとあわせて引数を受け取る機能を実装しています
<br>スニペットのキーワード『.now』で<font color=red>整形した日時のバリエーション</font>を表示します
<br>
<br>
<br>
<br>2021-05-29<br>
[Lesson26.四字熟語であそんでみる](https://kitanotamotsu.github.io/4ji) 
<br>今回はレッスンとして目新しいものはないです。。。
<br>難読四字熟語をランダムに表示します
<br>元ネタは、<font color=red>『Yattoke! - 小･中学生の学習サイト』の難読四字熟語一覧</font>です
<br>暇つぶしにどうぞ
<br>
<br>
<br>
<br>2021-06-06<br>
[Lesson27.ワークフローを放置する](https://kitanotamotsu.github.io/sourcecutter) 
<br>conditionalユーティリティで条件を設定するものの
<br>一部の条件には後続を描かずに放置する例です
<br>こんな使い方もできるのかなというノリで見てください
<br>題材としては、<font color=red>テキストのn文字目やn行目を検索するツール</font>を作成しています
<br>
<br>
<br>
<br>2021-06-12<br>
[Lesson28.ワークフローをの分岐を統合する](https://kitanotamotsu.github.io/plant) 
<br>ワークフローで分岐した2つの流れを、ひとつのオブジェクトで受け取ります
<br>Alfredワークフローの柔軟性というか自由度の高さのサンプルです
<br>日本植物生理学会のHP<font color=red>『みんなのひろば』の植物Q&A</font>を検索もしくはランダム表示します
<br>
<br>
<br>
<br>2021-06-19<br>
[Lesson29.Alfredのファイルアクションを使ってみる](https://kitanotamotsu.github.io/fileaction) 
<br>タイトルの通りAlfredのファイルアクションのワークフローです
<br>Alfredはファイルオペレーションをサポートしていてワークフローなしでも便利に使えます
<br>機能としては、画像ファイルを<font color=red>LuminarAI</font>で開くという単純なものです
<br>
<br>
<br>
<br>2021-06-27<br>
[Lesson30.GitHubのHPを作ってみる](https://kitanotamotsu.github.io/waza) 
<br>Alfredのレッスンとして目新しいものはないです。。。
<br>題材は、裏技サイトをパースして、3アイテムをランダムに表示させています。
<br>トップページ以外もGitHubで作ってみました。
<br>サイトデザインをテーマから選んでmdファイルを置くだけでできそうですね。
<br>ダウンロードをリリースとして管理する方が良さそうです。
<br>以前のレッスンも徐々に修正していきます。
<br>
<br>
<br>
<br>2021-07-04<br>
[Lesson31.NatureRemoでダイソン空気清浄機を使う](https://kitanotamotsu.github.io/dyson) 
<br>Alfredのレッスンとして目新しいものはないです。。。
<br>NatureRemoとの連携の第3作目となります。今回はダイソン空気清浄機
<br>ダイソン謹製のスマホアプリもあるのですが、キーボード操作ができるAlfredで実装してみました
<br>
<br>
<br>
<br>2021-07-11<br>
[Lesson32.ListFilterを使ってみる](https://kitanotamotsu.github.io/noet) 
<br>ListFilterのサンプルです。ScriptFilterと組み合わせて使っています
<br>よろず投稿サイトの<font color=red>Note.com</font>をキーワード検索したり
<br>人気タグやカテゴリーからアクセスしたりしています
<br>
<br>
<br>
## Tips
ワークフロー作成時のもろもろです
<br>2021-02-14 [Tips1.alfredworkflowファイルの作成方法](https://github.com/KitanoTamotsu/tips1/) 
<br>2021-02-14 [Tips2.ワークフロー用透過アイコンの作成方法](https://github.com/KitanoTamotsu/tips2/) 
<br>2021-02-20 [Tips3.Google suggest ワークフローを解析してみる](https://github.com/KitanoTamotsu/tips3/) 
<br>2021-03-13 [Tips4.<font color=red>Mighty Optical Illusion</font> のおまかせページを翻訳する](https://github.com/KitanoTamotsu/tips4/) 
<br>2021-04-04 [Tips5.デスクトップ操作を録画する方法](https://github.com/KitanoTamotsu/tips5/)
<br>2021-04-04 [Tips6.シェルスクリプトをbashからzshに変更する](https://github.com/KitanoTamotsu/tips6/)
<br>
## 環境
2021年2月〜　Macbook Air (M1,2020)　OSX 11.1 (BigSur)　Alfred4 & Powerpack
<br>
<br>
<br>
