---
title: SublimeText3で保存時に自動で空白を削除しないようにする方法
date: 2014-10-18 00:13:10
---

SublimeText3でMarkdown書いてると改行（半角2つ）が出来ないことに気付いた。  
保存時に文末の空白が消えてしまうようだ。

大変不便なので調べたら、「Preferences > Settings - User」で設定ファイルを開き、  
`trim_trailing_white_space_on_save`という設定項目を`true`から`false`にすればOK。

これでSublimeText3でMarkdownに書けるようになった。