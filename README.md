# OpenChain
Japanese Translation of LF OpenChain docs using OmegaT

本READMEは、三浦広志氏のDjangoドキュメントの翻訳プロジェクトのものを参考にしています。
<<本READMEは、現状、レビュー前の書きかけの状況です。>>

本プロジェクトは、The Linux Foundation（LF)が主催するオープンソース コンプライアンス推進プロジェクトOpenChainの主要英文資料を、The Linux Foundation Japan（LFJ)参加企業の貢献者が協調しながら日本語訳を作成することによって、日本のあらゆる企業・組織におけるオープンソース コンプライアンス普及を目指しています。

1. プロジェクトへの参加

  ・　The Linux Foundation Japanに参加を申請、メーリングリスト<lfj-trans@lists.linuxfoundation.org>に登録してもらう。
  ・　GitHubのユーザーIDを確保する。
  ・　Javaで記述されたコンピュータ翻訳支援ツール、OmegaTの最新版をインストールする。 http://omegat.org/
  ・　日本語スタイルガイドを一読する。https://www.jtf.jp/jp/style_guide/pdf/jtf_style_guide.pdf
      各企業のスタイルガイドとはちょっと違っているかもしれません。15分で一読できます。「感じ」をつかんでください。    

２．　翻訳作業の開始

  ・　OmegaTでチーム設定を行います。 Omega-Tを起動し、「設定」－「チーム．．．」を選択して、あなたの名前をいれてください。 この名前は、コミットメッセージに自動的に使用されますので、今後残ることに注意してください。

作業の始め方

Omega-Tのファイルメニューから、「チームプロジェクトのダウンロード」を選択し、GithubのOpenChainリポジトリURL；

https://github.com/t-kunai/OpenChain

と、新規ローカルディレクトリを指定します。 ローカルディレクトリは、MyDocuments/Github等を指定するといいでしょう。 ID、パスワードを聞かれますので、GithubのID/パスワードを入力します。 「暗号化しないで保存」オプションをチェックすることで、再度の入力をせずにすみます。 Omega-Tは、sshによるアクセスに十分に対応できないようなので、httpsによるURLを使いましょう。

2回目以降は、ダウンロードしたフォルダを開くと、自動的にgithubから最新をPullしてきます。

翻訳の実施とコミット

ダウンロードすると、原文一覧が表示されます。 担当する原文を選択して、作業をおこなってください。チームプロジェクトとしては、翻訳メモリ（/omegat/project_save.tmx)が、作業結果となります。 

Omega-Tで保存を選択すると、翻訳メモリ(/omegat/project_save.tmx)を保存し、自動コミットします。

Omega-Tに訳文の生成を指示するとローカルディレクトリのtargetフォルダーに、原文ファイルと同形式の訳文が生成されますので、確認やレビューに使って下さい。ただし、「保存」を行ってもリモートリポジトリの訳文は変更されません。

Omega-Tは、django-level1.tmx、 django-level2.tmx、django-omegat.tmxファイルを同時に生成します。 これらは、他のツールでの利用のために、自動生成されるものです。

ディレクトリの構造

ディレクトリ構造は、Omega-Tの既定にあわせてあります。

ファイル形式

原文は、MS Office形式で準備します。 MS OfficeやOpenOfficeでアクセスできますが、OpenOfficeでPowerPointデータをアクセスすると、表示が乱れます。

原文のタブは、訳文に残します。頻繁にt0, t1などのタブが入っていますが、英文字のスペース調整のようなので、タブはそのままにして、スペース文字を削除するのがいいでしょう。

翻訳メモリは、XML形式のTMX形式を利用します。

Known Issues

複数名で並行作業した場合に、用語集や翻訳メモリのコンフリクトが発生した場合の方法 について、確立したしくみがありません。

ライセンス

This README　material is licensed by 3-clauses BSD style.


