<br>Alfredワークフローのサンプルを公開しています、というか、遊んでいます
<br>私がAlfredやシェルスクリプト初心者なので、皆さんの参考になれば幸いです
<br>各レッスン(?)の開発メモを残していますので、青字のリンクから飛んでみてください
<br>また、表のワークフロー画像をクリックで拡大できます
<br>特に予定していたわけではないですが、一通りのレッスンは完結とします
<br>気が向いたら更新はつづけますけど・・  2021.07.11

## Alfred Workflow Examples

|2021/02/14| [Lesson1.初めてのワークフロー](https://kitanotamotsu.github.io/googlesuggest)   |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126853221-7f6cee62-c8b2-487e-b77f-14cd7857ac9e.png"><img width="150"  src="https://user-images.githubusercontent.com/40127279/126853221-7f6cee62-c8b2-487e-b77f-14cd7857ac9e.png"></a>|ソースコードレス・ワークフロー。練習作です。Githubの練習も兼ねて作ってみました。サンプルワークフローのGoogle SuggestをHOTKEYで起動します|
|2021/02/14| [Lesson2.入力パラメータを利用してURLを組み立てる](https://kitanotamotsu.github.io/googletimeline)  |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126853536-aaa978e7-db52-446e-9942-73c0781e7ef7.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126853536-aaa978e7-db52-446e-9942-73c0781e7ef7.png"></a>|<font color=red>Google Timeline</font>を日付指定で開きます。Alfredとしてパラメータを受け取り、URLを生成します。URLのパラメータを設定する最もプリミティブなワークフローの例。キーワードが英語でも日本語でも”発火”します。勝手にバイリンガル起動と呼んでいます|
|2021/02/19| [Lesson3.選択中のテキストを{query}にする](https://kitanotamotsu.github.io/tripadvisor) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126853884-380f4324-51d5-4dc3-908d-4c647407b38c.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126853884-380f4324-51d5-4dc3-908d-4c647407b38c.png"></a>|{query}というのはAlfred workflowの受け渡しです。シェルスクリプトを扱う方には受け渡しというより標準出力という方が通じるかな。選択中の文字列を受け渡すことで、ソースコードレスとなります。その受け渡したキーワードで<font color=red>Tripadvisor</font>を検索します|
|2021/02/20| [Lesson4.シェルスクリプトでURLエンコードする](https://kitanotamotsu.github.io/kakaku.comKeywordSearch) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126853658-61b24681-679d-44c6-9026-a83834ad9570.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126853658-61b24681-679d-44c6-9026-a83834ad9570.png"></a>|<font color=red>価格コム</font>をキーワード検索します。nkfコマンドによる％エンコードを実装しています |
|2021/02/20| [Lesson5.複数のパラメータを利する](https://kitanotamotsu.github.io/norikae) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126855661-db2256c7-bfd3-4c8c-bc3d-3bb1d03bb9df.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126855661-db2256c7-bfd3-4c8c-bc3d-3bb1d03bb9df.png"></a>|<font color=red>ジョルダンの乗り換え案内</font>を検索します。出発駅、到着駅、到着時間という複数のパラメータに対応しています |
|2021/02/20| [Lesson6.Alfredの出力フォーマットを試してみる](https://kitanotamotsu.github.io/testjson) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126855770-e0e7f392-8559-4e29-be92-1673beb72369.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126855770-e0e7f392-8559-4e29-be92-1673beb72369.png"></a>|Tips3でgoogle suggestを解析したら、Alfredの出力xmlを使っていることがわかりました。Alfredのサンプルを見て真似してみました。JSON出力フォーマットを利用しています |
|2021/02/27| [Lesson7.MXLをパースする](https://kitanotamotsu.github.io/yahoo) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126856670-b705deb1-6ce7-4633-8eff-345b743c9567.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126856670-b705deb1-6ce7-4633-8eff-345b743c9567.png"></a>|<font color=red>Yahoo!みんなの意見</font>のRSS表示ワークフローです。AlfredのJSON出力フォーマット出力の利用やRSSファイル（XML)のパースと要素の抽出などを実装しています |
|2021/03/02| [Lesson8.RSSニュースを検索する](https://kitanotamotsu.github.io/searchnews) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126856776-7d1f59d4-c968-4cd9-b55d-142ce88fcbb4.png"><img width="150"  src="https://user-images.githubusercontent.com/40127279/126856776-7d1f59d4-c968-4cd9-b55d-142ce88fcbb4.png"></a>|<font color=red>Googleニュース</font>RSSのキーワード検索です。Lesson7の変形です|
|2021/03/07| [Lesson9.ブラウザからURLを取得する](https://kitanotamotsu.github.io/translate) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126857141-8dfc15db-5f1c-41a6-8c2a-5abdaa204d69.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126857141-8dfc15db-5f1c-41a6-8c2a-5abdaa204d69.png"></a>|ブラウザで開いているページを翻訳します。コアは<font color=red>google translate</font>です。ブラウザから情報を取得するためシェルスクリプトからappleスクリプトを実行しています。もとはconditionalユーティリティとクリップボードを扱うサンプルとして作ったものです|
|2021/03/13| [Lesson10.TVのリモコン](https://kitanotamotsu.github.io/natureremo) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126858838-6207222c-1d9c-45d6-85e1-86e0303f80a9.png"><img width="150"  src="https://user-images.githubusercontent.com/40127279/126858838-6207222c-1d9c-45d6-85e1-86e0303f80a9.png"></a>|<font color=green><b>　★おすすめ★　</b></font>AlfredでTVを操作します。コアは<font color=red>NatureRemo</font>のAPIです。エキスポート禁止の変数の使い方のサンプルとなります。『TV ++』という入力でテレビのボリュームを2つ上げることができます。なかなか面白いかも。もちろんスクリプトを改造すれば、TV以外のリモコンにもなりますよ|
|2021/03/13| [Lesson11.ローカルファイルを利用する](https://kitanotamotsu.github.io/avatar) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126859618-eabe4143-8516-4786-a969-543967259814.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126859618-eabe4143-8516-4786-a969-543967259814.png"></a>|<font color=red>Joe Schmoe</font>のAPIを利用してアバターを作成します。リターンされるアバター画像からhtmlを生成してローカルに保存します |
|2021/03/14| [Lesson12.randomユーティリティを使用する](https://kitanotamotsu.github.io/wikipedia) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126860198-1e1e98b5-af42-42ea-b3b7-4ca9d06ae5a4.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126860198-1e1e98b5-af42-42ea-b3b7-4ca9d06ae5a4.png"></a>|<font color=green><b>　★おすすめ★　</b></font><font color=red>ウィキペディア</font>のおまかせ表示が興味のない記事ばかりという方におすすめ。カテゴリー内の記事をランダムに表示させることができます。つまり自分の興味のあるカテゴリを指定すれば、関心のある記事のランダム表示が可能になるのです。randomユーティリティを利用したコードレスワークフローです|
|2021/03/20| [Lesson13.randomユーティリティの選択肢を動的に設定する](https://kitanotamotsu.github.io/favo) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126867726-a3dc3141-44b1-476e-924a-a9eb8b971833.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126867726-a3dc3141-44b1-476e-924a-a9eb8b971833.png"></a>|お気に入りのURLを保存しておき、好きな時にランダムに表示させる<font color=red>お遊びワークフロー</font>です。randomユーティリティのワードリストを外部ファイルから動的に作成しています。またNotificationに渡すメッセージをArg and Varsでセットしています|
|2021/03/20| [Lesson14.RSSやHTMLをパースする/出力する一覧をコントロールする](https://kitanotamotsu.github.io/rssmania) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756010-7b080e13-334b-4881-bdda-f7d2129ca5b8.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756010-7b080e13-334b-4881-bdda-f7d2129ca5b8.png"></a>|<font color=green><b>　★おすすめ★　</b></font>多数のRSSをAlfredに出力するおもちゃ、その名も<font color=red>RSSマニア</font>です。パラメータの文字数で記事一覧のページ替えをコントロールしています。Alfredのインクリメンタルサーチと紐づいて、いろいろと応用が効く使い方だと思います |
|2021/03/21| [Lesson15.Arg and Varsオブジェクトの変数を動的にセットする](https://kitanotamotsu.github.io/sourceviewer) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756168-8158e17f-0cc9-4864-a9b5-d46e695866aa.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756168-8158e17f-0cc9-4864-a9b5-d46e695866aa.png"></a>|RSSやHTMLのソースを表示させるツール<font color=red>『ソースビュー』</font>です。ソースはテキストファイルとして保管します。その際、ファイル名に使う日時をArg and Varsオブジェクトで設定しています|
|2021/03/21| [Lesson16.出力フォーマットへランダムにセットする](https://kitanotamotsu.github.io/trivia) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127758662-62ca56a0-81c1-4eef-9c09-0cc66922957d.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127758662-62ca56a0-81c1-4eef-9c09-0cc66922957d.png"></a>|伝説の雑学番組<font color=red>トリビアの泉</font>の雑学をランダムに表示します。ツールではインターネットアクセスしていませんが、元ネタはこちらhttps://www.noncky.net/trivia/ |
|2021/03/28| [Lesson17.Alfred環境変数を使ってカスタマイズ設定を可能とする](https://kitanotamotsu.github.io/nazonazo) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756311-07b24635-6885-44ee-a2e1-6015f9a60058.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756311-07b24635-6885-44ee-a2e1-6015f9a60058.png"></a>|なぞなぞを出題するお遊びワークフローです。1度に出題する問題数や、出題したなぞなぞを保存する場所をカスタマイズできます。なぞなぞサイト<font color=red>『なぞQ.com』</font>からの出題です|
|2021/04/04| [Lesson18.別のワークフローを呼び出す](https://kitanotamotsu.github.io/tv) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126859172-605ef5f8-5826-44a4-a1ce-50f9db25e380.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126859172-605ef5f8-5826-44a4-a1ce-50f9db25e380.png"></a>|<font color=green><b>　★おすすめ★　</b></font>Lesson10で<font color=red>NatureRemo</font>のAPを使ってTVを操作するワークフローを作成しましたが。今回はその入口にTV番組表を追加しました |
|2021/04/11| [Lesson19.ホットキーツールを作成する／後続フローを二股にする](https://kitanotamotsu.github.io/quickterminal) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756499-9981be1f-809f-4a91-a3e9-c5545eaaa0da.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756499-9981be1f-809f-4a91-a3e9-c5545eaaa0da.png"></a>|選択しているテキストによってURLをOPENしたり、TERMINALで実行したり、ブラウザで検索したりします。勝手に<font color=red>『クイックターミナル』</font>と名付けました。Hotkey起動時の選択テキストの連携や、Colditionalオブジェクトのgrep判定の機能をつかいます。ターミナルでの実行とクリップボードへのコピーは後続フローを二股にして非同期に処理しています |
|2021/04/17| [Lesson20.テキストファイルを行ごとに配列に読み込む](https://kitanotamotsu.github.io/meigen) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756559-c55c4092-a02f-4505-b4ba-6aa495be6b12.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756559-c55c4092-a02f-4505-b4ba-6aa495be6b12.png"></a>|ネットサーフィンなどでみつけた名言を保存するツール<font color=red>『自分で集める名言集』</font>です。Alfredの機能ではないですが、テキストファイルの読み書きの小技を使っています。1行目に書き出したり、行単位に配列に読み込んだりしています |
|2021/04/24| [Lesson21.『アレクサ、うんちく教えて』をワークフローにする](https://kitanotamotsu.github.io/unchiku) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756657-844234f8-22e1-4109-9f9b-44d84bb8a50f.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756657-844234f8-22e1-4109-9f9b-44d84bb8a50f.png"></a>|お遊びで、<font color=red>アレクサ</font>の真似をしてみました。『うんちく教えて』でも、『雑学教えて』でも、『豆知識教えて』でも起動するマルチキーワード構造です |
|2021/05/01| [Lesson22.スクリプトフィルターとキーワードをハイブリッドにする](https://kitanotamotsu.github.io/aircon) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756738-3b43bea3-7326-4bd3-854b-d02487b4e58b.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756738-3b43bea3-7326-4bd3-854b-d02487b4e58b.png"></a>|<font color=red>NatureRemo</font>のAPIを利用してエアコンを操作します。Lesson10と18でテレビを操作しましたが、今回はエアコンです。室温や湿度を確認できます|
|2021/05/08| [Lesson23.スクリプトフィルターをワークフローの途中で使う](https://kitanotamotsu.github.io/ameba) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127756932-1f627195-1442-46ef-bf3d-27d4a9bbcf2b.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127756932-1f627195-1442-46ef-bf3d-27d4a9bbcf2b.png"></a>|ランダムに<font color=red>amebaブログ</font>のRSSを読み込んで記事一覧を表示させます。Lesson14のRSSマニア等の変形です。スクリプトフィルターがワークフローの途中でも利用できることがわかったのでまた用途が広がりますね|
|2021/05/16| [Lesson24.Alfredの出力を10件以上に設定する／濁音・半濁音検索に対応する](https://kitanotamotsu.github.io/recipe) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127757111-9c75bb4a-e944-4dfc-b251-c661a00f7122.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127757111-9c75bb4a-e944-4dfc-b251-c661a00f7122.png"></a>|NHKレシピサイト<font color=red>『きょうのみんなの料理』</font>の検索結果を表示させています。また、作成中に判明した、濁音・半濁音を含む検索にも対応しています |
|2021/05/22| [Lesson25.スニペット起動を使ってみる](https://kitanotamotsu.github.io/now) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127757168-373aefbc-774f-45c8-ad0c-876a60a02db5.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127757168-373aefbc-774f-45c8-ad0c-876a60a02db5.png"></a>|ワークフローのトリガーにスニペットがあったので気になって使ってみました。スクリプトフィルターとあわせて引数を受け取る機能を実装しています。スニペットのキーワード『.now』で<font color=red>整形した日時のバリエーション</font>を表示します|
|2021/05/29| [Lesson26.四字熟語であそんでみる](https://kitanotamotsu.github.io/4ji) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127757593-1d2e5973-0fa3-461a-a40c-50384ba07e9d.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127757593-1d2e5973-0fa3-461a-a40c-50384ba07e9d.png"></a>|今回はレッスンとして目新しいものはないです。。。難読四字熟語をランダムに表示します。元ネタは、<font color=red>『Yattoke! - 小･中学生の学習サイト』の難読四字熟語一覧</font>です。暇つぶしにどうぞ|
|2021/06/06| [Lesson27.ワークフローを放置する](https://kitanotamotsu.github.io/sourcecutter) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127757659-6d253032-6f97-4433-801e-2773f3ef7e72.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127757659-6d253032-6f97-4433-801e-2773f3ef7e72.png"></a>|conditionalユーティリティで条件を設定するものの一部の条件には後続を描かずに放置する例です。こんな使い方もできるのかなというノリで見てください。題材としては、<font color=red>テキストのn文字目やn行目を検索するツール</font>を作成しています |
|2021/06/12| [Lesson28.ワークフローをの分岐を統合する](https://kitanotamotsu.github.io/plant) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127758761-7c94eb45-9f6a-4b46-b184-761e03dab45a.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127758761-7c94eb45-9f6a-4b46-b184-761e03dab45a.png"></a>|ワークフローで分岐した2つの流れを、ひとつのオブジェクトで受け取ります。Alfredワークフローの柔軟性というか自由度の高さのサンプルです。日本植物生理学会のHP<font color=red>『みんなのひろば』の植物Q&A</font>を検索もしくはランダム表示します |
|2021/06/19| [Lesson29.Alfredのファイルアクションを使ってみる](https://kitanotamotsu.github.io/fileaction) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127757814-605572a6-cac6-4383-9583-11c8171a071f.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127757814-605572a6-cac6-4383-9583-11c8171a071f.png"></a>|タイトルの通りAlfredのファイルアクションのワークフローです。Alfredはファイルオペレーションをサポートしていてワークフローなしでも便利に使えます。機能としては、画像ファイルを<font color=red>LuminarAI</font>で開くという単純なものです|
|2021/06/27| [Lesson30.GitHubのHPを作ってみる](https://kitanotamotsu.github.io/waza) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127757986-ab910290-6835-4ddf-bc12-3cbb324bb8d3.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127757986-ab910290-6835-4ddf-bc12-3cbb324bb8d3.png"></a>|Alfredのレッスンとして目新しいものはないです。。。題材は、裏技サイトをパースして、3アイテムをランダムに表示させています。トップページ以外もGitHubで作ってみましたので作り方をレッスンとします|
|2021/07/04| [Lesson31.NatureRemoでダイソン空気清浄機を使う](https://kitanotamotsu.github.io/dyson) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127758072-3f8e398d-e1a1-4c53-b16f-320183d1dfc6.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127758072-3f8e398d-e1a1-4c53-b16f-320183d1dfc6.png"></a>|Alfredのレッスンとして目新しいものはないです。。。NatureRemoとの連携の第3作目となります。今回はダイソン空気清浄機。ダイソン謹製のスマホアプリもあるのですが、キーボード操作ができるAlfredで実装してみました|
|2021/07/11| [Lesson32.ListFilterを使ってみる](https://kitanotamotsu.github.io/note) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/127758117-5a334898-0378-4357-a226-352759adbde7.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/127758117-5a334898-0378-4357-a226-352759adbde7.png"></a>|ListFilterのサンプルです。ScriptFilterと組み合わせて使っています。よろず投稿サイトの<font color=red>Note.com</font>をキーワード検索したり、人気タグやカテゴリーからアクセスしたりしています |
|2021/09/25| [Lesson33.スクリプトフィルターを2段階で使う](https://kitanotamotsu.github.io/gakusha) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/134764365-86db183b-0c8f-4144-857e-fafa97bc6b25.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/134764365-86db183b-0c8f-4144-857e-fafa97bc6b25.png"></a>|ScriptFilterを2段構えで使っています。雑学サイトの<font color=red>Gaku-Sha.com</font>をランダムに表示させます |
|2022/02/13| [Lesson34.グーグルサジェストを使う](https://kitanotamotsu.github.io/googlesuggest2) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/153736515-857e3014-bac3-4641-8646-afc05e532dcc.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/153736515-857e3014-bac3-4641-8646-afc05e532dcc.png"></a>|ふたたびのグーグルサジェスト登場です。コア部分をシェルスクリプトで作成しました |
|2022/02/23| [Lesson35.今日のクイズを出題する](https://kitanotamotsu.github.io/dailyquiz) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/155270515-f47ca8b1-00d8-4dbc-ab5f-a86f7c28be6c.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/155270515-f47ca8b1-00d8-4dbc-ab5f-a86f7c28be6c.png"></a>|その日にちなんだクイズを出すサイト<font color=red>今日のクイズ</font>からランダムに出題します |

<br>
<br>
<br>
## Tips
ワークフロー作成時のもろもろです
<br>2021-02-14 [Tips1.alfredworkflowファイルの作成方法](https://kitanotamotsu.github.io/tips1/) 
<br>2021-02-14 [Tips2.ワークフロー用透過アイコンの作成方法](https://kitanotamotsu.github.io/Tips2/) 
<br>2021-02-20 [Tips3.Google suggest ワークフローを解析してみる](https://kitanotamotsu.github.io/tips3/) 
<br>2021-03-13 [Tips4.<font color=red>Mighty Optical Illusion</font> のおまかせページを翻訳する](https://kitanotamotsu.github.io/tips4/) 
<br>2021-04-04 [Tips5.デスクトップ操作を録画する方法](https://kitanotamotsu.github.io/tips5/)
<br>2021-04-04 [Tips6.シェルスクリプトをbashからzshに変更する](https://kitanotamotsu.github.io/tips6/)
<br>
## 環境
2021年2月〜　Macbook Air (M1,2020)　OSX 11.1 (BigSur)　Alfred4 & Powerpack
<br>2022年2月〜　Macbook Air (M1,2020)　OSX 12.1 (Monterey)　Alfred4 & Powerpack
<br>
<br>
<br>
