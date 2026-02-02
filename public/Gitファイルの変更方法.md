---
title: ファイルの頭文字の小文字から大文字に変更したファイルをGit操作でGit及びGitHubに反映させる方法
tags:
  - 'Git''GitHub'
private: false
updated_at: ''
id: null
organization_url_name: null
slide: false
ignorePublish: false
---
# ファイルの頭文字の小文字から大文字に変更したファイルをGit操作でGit及びGitHubに反映させる方法
Gitでファイル名の頭文字小文字から大文字に変更するには、下記のコマンドが必要みたいです。
```diff_*git
 - git mv apiContactController.php ApiContactController.php
 + git mv app/Http/Controllers/apiContactController.php app/Http/Controllers/ApiContactController.php
```
つまり、何が言いたいかと言うと、git mv 旧ファイル名 新ファイル名ではあるのですが、新旧ともにパスを書くと言うことです。
これで、自分はGit操作でファイル名の変更を反映させました。
この記事がお役に立てれば嬉しいです。
