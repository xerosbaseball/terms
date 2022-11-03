---
title: "CONTRIBUTING"
draft: false
weight: 5
chapter: false
---

## 事前準備

1. GitHubのアカウントをつくり、サインインする
2. チーム規約のファイル群[xerosbaseball/terms](https://github.com/xerosbaseball/terms)を、自分のアカウントにフォーク(コピー)する
   1. [xerosbaseball/terms](https://github.com/xerosbaseball/terms)にアクセスする
   2. Forkボタンを押す
      ![Fork](../images/fork.png)
   3. 名前が[自分のアカウント名]/termsであることを確認して、Create forkボタンを押す
      ![Create fork](../images/create_fork.png)

## 修正の出し方

1. Issueに課題について記載する
   1. [xerosbaseball/terms](https://github.com/xerosbaseball/terms)にアクセスする
   2. Issuesボタンを押す
      ![Fork](../images/issues.png)
   3. New issueボタンを押す
      ![Fork](../images/new_issue.png)
   4. Get startedボタンを押す
      ![Fork](../images/get_start.png)
   5. テンプレートが開くので、タイトルと内容を編集してSubmit new issueボタンを押す
      ![Fork](../images/template.png)
   6. Issueにコメントを皆で書いて解決すべき課題はなにか明らかにする
      目の前におきた現象をそのまま解決すべき課題と信じ込んでしまうことが多く見られます。
      また、課題と改善の議論が同時に行われ解決に直接関係ない改善を実施しようとすることもありました。まずは、目の前に発生した現象が実際に自分たちにどのような悪影響が出ているのか明らかにします。その後、具体的な悪影響が出ていることがわかった時点で初めてこの現象は解決すべき課題であり、具体的な改善策について話し合います。意見を記入したらCommentボタンを押します。
      ![Fork](../images/comment.png)
2. 修正する
   1. contentディレクトリの下にあるファイルがこのページを含むコンテンツです。これらのファイルを修正します。なお、.mdの拡張子がついているファイルは[マークダウン記法](https://backlog.com/ja/blog/how-to-write-markdown/)で記載しています。
   2. 対象ファイルのページで編集ボタン(ペンのアイコン)を押し、内容編集する
      ![Fork](../images/edit.png)
   3. 編集したらPropose changeを押す
      ![Fork](../images/propose_change.png)
3. プルリクエストを作成する
   1. 修正が終わったら編集の取り込みを依頼しますこれをプルリクエストといいます。Create pull requestを押します。詳細は[プルリクエストとは](https://backlog.com/ja/git-tutorial/pull-request/01/)とGitHubの公式ドキュメントも合わせて参照してください[pull request の作成](<https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request>)
      ![Fork](../images/pull_request.png)
4. 修正が取り込まれる
   1. プルリクエストに対してコメントが付いた場合は修正してください。
   2. [textlint](https://github.com/textlint/textlint)も使用していますので、textlintから指摘を受けた場合はこちらもすべて修正します。他にも[textlint](https://ics.media/entry/220404/)も参考になります。textlintについてあなたが疑問に思ったことはほぼすべてネットに書いてあるのでGoogle等の検索エンジンを使うと解決できます。
   3. レビュアによって修正が承認されると、修正が取り込まれます。修正が取り込まれると自動でサイトは更新される仕組みになっていますのでしばらくお待ち下さい。GitHubのActionsタブから更新状況を確認できます。
   4. 修正が取り込まれたらIssueに当該プルリクエストのリンクをコメントで追加してクローズします。

## プルリクエストの修正

レビューの指摘やtextlintの指摘を受けてプルリクエストの修正する場合は、プルリクエストを提出したブランチに対して修正を加えます。
コマンドラインが使用できる場合は[レビューとマージ](https://backlog.com/ja/git-tutorial/pull-request/07/)を参考にします。
また、ブラウザしか使用できない場合は[ファイルを編集する](https://docs.github.com/ja/repositories/working-with-files/managing-files/editing-files)
を参考に修正します。
スマートフォンを修正対象のファイルを開きブランチを指定してから修正します。
![edit_from_browser width="320" height="640"](../images/edit_from_browser.png)
