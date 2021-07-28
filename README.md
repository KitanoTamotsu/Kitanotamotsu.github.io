# Welcome to My GitHub Pages
<br>Alfredワークフローのサンプルを公開しています、というか、遊んでいます
<br>私がAlfredやシェルスクリプト初心者なので、皆さんの参考になれば幸いです
<br>各サンプルのreadmeに開発メモを記載しているのでご参考まで
<br>
<br> テーブルレイアウトに変更中です
<br>

## Alfred Workflow Examples

|2021/02/14| [Lesson1.初めてのワークフロー](https://kitanotamotsu.github.io/googlesuggest)   |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126853221-7f6cee62-c8b2-487e-b77f-14cd7857ac9e.png"><img width="150"  src="https://user-images.githubusercontent.com/40127279/126853221-7f6cee62-c8b2-487e-b77f-14cd7857ac9e.png"></a>|ソースコードレス・ワークフロー。練習作です。Githubの練習も兼ねて作ってみました。サンプルワークフローのGoogle SuggestをHOTKEYで起動します|

|2021/02/14| [Lesson2.入力パラメータを利用してURLを組み立てる](https://kitanotamotsu.github.io/googletimeline)  |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126853536-aaa978e7-db52-446e-9942-73c0781e7ef7.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126853536-aaa978e7-db52-446e-9942-73c0781e7ef7.png"></a>|<font color=red>Google Timeline</font>を日付指定で開きます。Alfredとしてパラメータを受け取り、URLを生成します。URLのパラメータを設定する最もプリミティブなワークフローの例キーワードが英語でも日本語でも”発火”します。勝手にバイリンガル起動と呼んでいます|

|2021/02/19| [Lesson3.選択中のテキストを{query}にする](https://kitanotamotsu.github.io/tripadvisor) |
|<a target="wf" href="https://user-images.githubusercontent.com/40127279/126853884-380f4324-51d5-4dc3-908d-4c647407b38c.png"><img width="150" src="https://user-images.githubusercontent.com/40127279/126853884-380f4324-51d5-4dc3-908d-4c647407b38c.png"></a>|{query}というのはAlfred workflowの受け渡しです。シェルスクリプトを扱う方には受け渡しというより標準出力という方が通じるかな。選択中の文字列を受け渡すことで、ソースコードレスとなります。その受け渡したキーワードで<font color=red>Tripadvisor</font>を検索します|

|2021/02/20| [Lesson4.シェルスクリプトでURLエンコードする](https://kitanotamotsu.github.io/kakaku.comKeywordSearch) |
| |<font color=red>価格コム</font>をキーワード検索します。nkfコマンドによる％エンコードを実装しています |

|2021/02/20| [Lesson5.複数のパラメータを利する](https://kitanotamotsu.github.io/norikae) |
| |<font color=red>ジョルダンの乗り換え案内</font>を検索します。出発駅、到着駅、到着時間という複数のパラメータに対応しています |

|2021/02/20| [Lesson6.Alfredの出力フォーマットを試してみる](https://kitanotamotsu.github.io/testjson) |
| |Tips3でgoogle suggestを解析したら、Alfredの出力xmlを使っていることがわかりました。Alfredのサンプルを見て真似してみました。JSON出力フォーマットを利用しています |

|2021/02/27| [Lesson7.MXLをパースする](https://kitanotamotsu.github.io/yahoo) |
| |<font color=red>Yahoo!みんなの意見</font>のRSS表示ワークフローです。AlfredのJSON出力フォーマット出力の利用やRSSファイル（XML)のパースと要素の抽出などを実装しています |

|2021/03/02| [Lesson8.RSSニュースを検索する](https://kitanotamotsu.github.io/searchnews) |
| |<font color=red>Googleニュース</font>RSSのキーワード検索です。Lesson7の変形です|

|2021/03/07| [Lesson9.ブラウザからURLを取得する](https://kitanotamotsu.github.io/translate) |
| |ブラウザで開いているページを翻訳します。コアは<font color=red>google translate</font>です。ブラウザから情報を取得するためシェルスクリプトからappleスクリプトを実行しています。もとはconditionalユーティリティとクリップボードを扱うサンプルとして作ったものです|

|2021/03/13| [Lesson10.TVのリモコン](https://kitanotamotsu.github.io/natureremo) |
| |Alfredの入力でTVを操作します。コアは<font color=red>NatureRemo</font>のAPIです。エキスポート禁止の変数の使い方のサンプルとなります。『TV ++』でテレビのボリュームが2メモリ上げれるので、なかなか面白いかも。もちろんスクリプトを改造すれば、TV以外のリモコンにもなりますよ|

|2021/03/13| [Lesson11.ローカルファイルを利用する](https://kitanotamotsu.github.io/avatar) |
| |<font color=red>Joe Schmoe</font>のAPIを利用してアバターを作成します。リターンされるアバター画像からhtmlを生成してローカルに保存します |

|2021/03/14| [Lesson12.randomユーティリティを使用する](https://kitanotamotsu.github.io/wikipedia) |
| |<font color=red>ウィキペディア</font>のおまかせ表示が興味のない記事ばかりという方におすすめ。カテゴリー内の記事をランダムに表示させることができます。randomユーティリティを利用したコードレスワークフローです|

|2021/03/20| [Lesson13.randomユーティリティの選択肢を動的に設定する](https://kitanotamotsu.github.io/favo) |
| |お気に入りのURLを保存しておき、好きな時にランダムに表示させるお<font color=red>遊びワークフロー</font>です。randomユーティリティのワードリストを外部ファイルから動的に作成しています。またNotificationに渡すメッセージをArg and Varsでセットしています|

|2021/03/20| [Lesson14.RSSやHTMLをパースする/出力する一覧をコントロールする](https://kitanotamotsu.github.io/rssmania) |
| |多数のRSSをAlfredに出力するおもちゃ、その名も<font color=red>RSSマニア</font>です。パラメータの文字数で記事一覧のページ替えをコントロールしています。Alfredのインクリメンタルサーチと紐づいて、いろいろと応用が効く使い方だと思います |

|2021/03/21| [Lesson15.Arg and Varsオブジェクトの変数を動的にセットする](https://kitanotamotsu.github.io/sourceviewer) |
| |RSSやHTMLのソースを表示させるツール<font color=red>『ソースビュー』</font>です。ソースはテキストファイルとして保管します。その際、ファイル名に使う日時をArg and Varsオブジェクトで設定しています|

|2021/03/21| [Lesson16.出力フォーマットへランダムにセットする](https://kitanotamotsu.github.io/trivia) |
| |伝説の雑学番組<font color=red>トリビアの泉</font>の雑学をランダムに表示します。ツールではインターネットアクセスしていませんが、元ネタはこちらhttps://www.noncky.net/trivia/ |


|2021/03/28| [Lesson17.Alfred環境変数を使ってカスタマイズ設定を可能とする](https://kitanotamotsu.github.io/nazonazo) |
| |なぞなぞを出題するお遊びワークフローです。1度に出題する問題数や、出題したなぞなぞを保存する場所をカスタマイズできます。なぞなぞサイト<font color=red>『なぞQ.com』</font>からの出題です|

|2021/04/04| [Lesson18.別のワークフローを呼び出す](https://kitanotamotsu.github.io/tv) |
| |Lesson10で<font color=red>NatureRemo</font>のAPを使ってTVを操作するワークフローを作成しましたが。今回はその入口にTV番組表を追加しました |

|2021/04/11| [Lesson19.ホットキーツールを作成する／後続フローを二股にする](https://kitanotamotsu.github.io/quickterminal) |
| |選択しているテキストによってURLをOPENしたり、。TERMINALで実行したり、ブラウザで検索したりします。勝手に<font color=red>『クイックターミナル』</font>と名付けました。Hotkey起動時の選択テキストの連携や、Colditionalオブジェクトのgrep判定の機能をつかいます。ターミナルでの実行とクリップボードへのコピーは後続フローを二股にして非同期に処理しています |

|2021/04/17| [Lesson20.テキストファイルを行ごとに配列に読み込む](https://kitanotamotsu.github.io/meigen) |
| |ネットサーフィンなどでみつけた名言を保存するツール<font color=red>『自分で集める名言集』</font>です。Alfredの機能ではないですが、テキストファイルの読み書きの小技を使っています。1行目に書き出したり、行単位に配列に読み込んだりしています |

|2021/04/24| [Lesson21.『アレクサ、うんちく教えて』をワークフローにする](https://kitanotamotsu.github.io/unchiku) |
| |お遊びで、<font color=red>アレクサ</font>の真似をしてみました。『うんちく教えて』でも、『雑学教えて』でも、『豆知識教えて』でも起動するマルチキーワード構造です |

|2021/05/01| [Lesson22.スクリプトフィルターとキーワードをハイブリッドにする](https://kitanotamotsu.github.io/aircon) |
| |<font color=red>NatureRemo</font>のAPIを利用してエアコンを操作します。Lesson10と18でテレビを操作しましたが、今回はエアコンです。室温や湿度を確認できます|

|2021/05/08| [Lesson23.スクリプトフィルターをワークフローの途中で使う](https://kitanotamotsu.github.io/ameba) |
| |ランダムに<font color=red>amebaブログ</font>のRSSを読み込んで記事一覧を表示させます。Lesson14のRSSマニア等の変形です。スクリプトフィルターがワークフローの途中でも利用できることがわかったのでまた用途が広がりますね|

|2021/05/16| [Lesson24.Alfredの出力を10件以上に設定する／濁音・半濁音検索に対応する](https://kitanotamotsu.github.io/recipe) |
| |NHKレシピサイト<font color=red>『きょうのみんなの料理』</font>の検索結果を表示させています。また、作成中に判明した、濁音・半濁音を含む検索にも対応しています |

|2021/05/22| [Lesson25.スニペット起動を使ってみる](https://kitanotamotsu.github.io/now) |
| |ワークフローのトリガーにスニペットがあったので気になって使ってみました。スクリプトフィルターとあわせて引数を受け取る機能を実装しています。スニペットのキーワード『.now』で<font color=red>整形した日時のバリエーション</font>を表示します|

|2021/05/29| [Lesson26.四字熟語であそんでみる](https://kitanotamotsu.github.io/4ji) |
| |今回はレッスンとして目新しいものはないです。。。難読四字熟語をランダムに表示します。元ネタは、<font color=red>『Yattoke! - 小･中学生の学習サイト』の難読四字熟語一覧</font>です。暇つぶしにどうぞ|

|2021/06/06| [Lesson27.ワークフローを放置する](https://kitanotamotsu.github.io/sourcecutter) |
| |conditionalユーティリティで条件を設定するものの一部の条件には後続を描かずに放置する例です。こんな使い方もできるのかなというノリで見てください。題材としては、<font color=red>テキストのn文字目やn行目を検索するツール</font>を作成しています |

|2021/06/12| [Lesson28.ワークフローをの分岐を統合する](https://kitanotamotsu.github.io/plant) |
| |ワークフローで分岐した2つの流れを、ひとつのオブジェクトで受け取ります。Alfredワークフローの柔軟性というか自由度の高さのサンプルです。日本植物生理学会のHP<font color=red>『みんなのひろば』の植物Q&A</font>を検索もしくはランダム表示します |

|2021/06/19| [Lesson29.Alfredのファイルアクションを使ってみる](https://kitanotamotsu.github.io/fileaction) |
| |タイトルの通りAlfredのファイルアクションのワークフローです。Alfredはファイルオペレーションをサポートしていてワークフローなしでも便利に使えます。機能としては、画像ファイルを<font color=red>LuminarAI</font>で開くという単純なものです|

|2021/06/27| [Lesson30.GitHubのHPを作ってみる](https://kitanotamotsu.github.io/waza) |
| |Alfredのレッスンとして目新しいものはないです。。。題材は、裏技サイトをパースして、3アイテムをランダムに表示させています。トップページ以外もGitHubで作ってみました。サイトデザインをテーマから選んでmdファイルを置くだけでできそうですね。ダウンロードをリリースとして管理する方が良さそうです。以前のレッスンも徐々に修正していきます。|

|2021/07/04| [Lesson31.NatureRemoでダイソン空気清浄機を使う](https://kitanotamotsu.github.io/dyson) |
| |Alfredのレッスンとして目新しいものはないです。。。NatureRemoとの連携の第3作目となります。今回はダイソン空気清浄機。ダイソン謹製のスマホアプリもあるのですが、キーボード操作ができるAlfredで実装してみました|

|2021/07/11| [Lesson32.ListFilterを使ってみる](https://kitanotamotsu.github.io/noet) |
| |ListFilterのサンプルです。ScriptFilterと組み合わせて使っています。よろず投稿サイトの<font color=red>Note.com</font>をキーワード検索したり。人気タグやカテゴリーからアクセスしたりしています |
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
