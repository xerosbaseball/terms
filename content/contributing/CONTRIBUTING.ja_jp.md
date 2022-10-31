---
title: "CONTRIBUTING"
draft: false
weight: 5
chapter: false
---

## 修正の出し方

1. Issueに課題について記載する
2. Issueにコメントを皆で書いて解決すべき課題はなにか明らかにする
   1. 目の前におきた現象をそのまま解決すべき課題と信じ込んでしまうことが多く見られます、また課題と改善の議論が同時に行われ解決に直接関係ない改善を実施しようとすることもありました。まずは、目の前に発生した現象が実際に自分たちにどのような悪影響が出ているのか明らかにします。その後、具体的な悪影響が出ていることがわかった時点で初めてこの現象は解決すべき課題であり、具体的な改善策について話し合います。
3. 修正する
   1. contentディレクトリの下にあるファイルがこのページを含むコンテンツです。これらのファイルを修正します。なお、.mdの拡張子がついているファイルは[マークダウン記法](https://backlog.com/ja/blog/how-to-write-markdown/)で記載しています。
4. プルリクエストを作成する
   1. 修正が終わったら編集の取り込みを依頼しますこれをプルリクエストといいます。詳細は[プルリクエストとは](https://backlog.com/ja/git-tutorial/pull-request/01/)とGitHubの公式ドキュメントも合わせて参照してください[pull request の作成](<https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request>)
5. 修正が取り込まれる
   1. プルリクエストに対してコメントが付いた場合は修正してください。
   2. [textlint](https://github.com/textlint/textlint)も使用していますので、textlintから指摘を受けた場合はこちらもすべて修正します。他にも[textlint](https://ics.media/entry/220404/)も参考になります。textlintについてあなたが疑問に思ったことはほぼすべてネットに書いてあるのでGoogle等の検索エンジンを使うと解決できます。
   3. レビュアによって修正が承認されると、修正が取り込まれます。修正が取り込まれると自動でサイトは更新される仕組みになっていますのでしばらくお待ち下さい。GitHubのActionsタブから更新状況を確認できます。
   4. 修正が取り込まれたらIssueに当該プルリクエストのリンクをコメントで追加してクローズします。
