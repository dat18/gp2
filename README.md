# 2019年度 ゲームプログラミング2

## 講義の進め方
- [Qiita](https://qiita.com/)、あるいは、[はてなブログ](https://hatenablog.com/)などにブログを開設して、そこに毎週記事を投稿する
  - サービスは何を使ってもよい
  - 講義で見れれば限定公開でも構わない(就活を考えれば公開ブログの方がよい)
  - 公開する場合は検索されやすい方がよいので、上記サービスを利用した方がお得
- デスクトップの動画を共有して、ブログや開発したプログラムを実行して見せながら、10分程度発表をする
- 卒業制作では作品の**進捗報告**。この講義では、**技術の説明や実装手順**など
- [発表用YouTubeURLの作成](https://docs.google.com/document/d/11rh1ojJnCJInI33XEk9xX3T_bHfKfoI_BH0foDVSGtM/)

# 7回目(6/6)
## 予定
- Unity2019とVisual Studio2019のインストール

## 手順
### 準備
1. 担当PCの割り振り
  - 一度にすべてをやるとネットで遅くなるので、半分をインストールしつつ、残りのPCでは作業を進められるようにしておく
1. PCをStudentで起動

### Unity2019のインストール
1. Unity Hubを起動
1. Unity Hubを更新
  - パスワードを求められたら呼んでください
1. 右上のインストールをクリック
1. Unity2019.1の最新版を選んで次へをクリック
1. 以下のモジュールを追加
  - WebGL Build Support
  - Windows Build Support(IL2CPP)
  - 上記以外にチェックがあったら外す
1. 実行をクリック

インストールが完了したら、Visual Studioのインストールへ進む。

### Visual Studio 2019のインストール
[こちら](https://ameblo.jp/minato58-work/entry-12451856226.html)を参照。

ついでに、Visual C#の.NETプロジェクトもインストールする。

### Unityのセットアップ
1. Unityを起動
1. Visual Studio 2019をエディターに選択
1. Unityで新規プロジェクトを作成
1. スクリプトを作成して、ダブルクリックして、Visual Studioが正常に起動するか確認する

### アンインストール
1. Unity Hubから操作が可能であれば、Unity2017をアンインストールする
1. Visual Studio 2017をアンインストールする

以上のアンインストールを開始したら、待機していたPCでのインストールを始める。

### アンインストールが完了したら
- 教員を呼んでください。Unityのインストールフォルダーの権限を変更します


## 作業完了後
- ブログのテーマを決めて、執筆を開始


# 6回目(5/30)
- 仕上げ
- ゲーム動画の撮影
  - 準備
    - スタートメニューから歯車アイコンをクリックして、ゲームをクリック
    - 一番上の設定をオンにする
    - 設定ウィンドウを閉じる
  - 録画
    - 録画する画面を表示したら、[Win]+[Alt]+[R]キーを押す
    - 「ゲーム機能は利用できません」というウィンドウが出たら、チェックの場所をクリックする
    - ゲーム画面をクリックする
    - 録画中は画面に操作バーが表示されている(これは録画されない)。停止したい場合は停止ボタンを押す
  - 録画を確認する
    - [Win]+[G]キーを押す
    - 「全キャプチャを表示」をクリック
    - 「ファイルの場所を開く」をクリックしたら、動画ファイルの保存先フォルダーを確認できる
    

# 5回目(5/23)
- 全員の作業を統合してmasterバージョンを作る
- 明日、できあがっているグラフィックをすべて統合して、ステージが作れる準備をしておく

# 4回目(5/16)
- 開発

# 3回目(5/9)
## 予定
- 合同講義。教室はA601。細谷先生にゲーム画面の評価を受ける
- 評価を持ち帰って、開発項目、手順を確認
- 開発

## 話題
- [日本ゲーム大賞のツイート](https://twitter.com/tokyo_game_show/status/1121681424455622658)

## ブログ発表
- [ブログURL一覧](https://trello.com/c/wEek2G17/4-%E3%83%96%E3%83%AD%E3%82%B0url)

# 2回目(4/25)
## 内容
- チーム制作で担当する技術の調査と発表(1)
- 正式な企画決定は明日なので、今日は先週に続いて使いそうな技術の下準備と、ブログ作成
- ヒアリングと作業
- 最後にブログを画面に出すので簡単に報告

# 1回目(4/18)
## 内容
- [シラバス](syllabus.md)の確認
- ブログを選んで開設（元々あれば不要）
  - [例](http://am1tanaka.hatenablog.com/)
- ブログを開設したら、[Trello](https://trello.com/)にログインして、以下を実施
  - [ゲームプログラミング２のリスト](https://trello.com/b/Z6HEkj2N/1%E3%82%B2%E3%83%BC%E3%83%A0%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B02)の今日の日付のカードにコメントで以下を書く
  - ブログのURL
- 卒業制作について以下を検討して、ブログにまとめる
  - 解像度
  - 企画が決まるまでにできる作業のリストアップ
  - リストアップした作業の担当者と期限を決める
  - 使えそうなアセットを探して、箇条書きでURLをまとめる
- 時間が余ったら、Unityのプロジェクトを作成して、GitHubのPrivateリポジトリーにプッシュする

## ブログの書き方
- 週1なので短くてよい
  - 参考：[コガネブログ](http://baba-s.hatenablog.com/)
- 書く内容
  - ブログの概要を1～数行でざっくりと。スクリーンショットがあるとよい
  - 目次
  - 前提条件として、Unityのバージョンや、アセットを使っていたらそのバージョン
  - 本文
    - 簡潔に書く。省略して意味が変わらない表現があれば、短い方を採用する
    - スクリーンショット多めがよい
    - 技術ブログはくだけた表現が許されるが、企業に見せても構わないようにすること(就活で使えなければ意味がないので)
  - まとめで、ブログの内容について簡単におさらい
  - 最後に利用したアセットや、参考にしたブログ、動画などのURLを**参考URL**などでまとめておく
    - なるべく多い方がよい
    - 関連する公式ページのURLなど

## ブログの試し書き
- 概要として、「卒業制作で開発予定の企画について、ゲームの解像度や、作業リスト、使えそうなアセットについてまとめます。」などと書いておく
- 目次を作成(作り方があると思うので調べる)
- タイトルをつけながら、以下を書いていく
  - ゲームの解像度
  - 企画が決まる前にできることのリスト
    - 箇条書きの書式を利用
    - 話し合いながら考えられる作業をリストアップして、担当者と期限も書く
  - 作品に使えそうなアセットやライブラリのURLリスト
    - [アセットストア](https://assetstore.unity.com/)
    - [Unity AssetStoreまとめ](http://www.asset-sale.net/)
    - [コガネブログ](http://baba-s.hatenablog.com/)
    - etc...
