# ドローンデモ会 参加アンケート サンプルページ
本レポジトリはG’s Academy8回目講義の提出のために作られたものである．


## 課題内容
- 前回の課題で作ったページを流用し，SQLの機能を実装した．
- 元がcsvでデータの受け渡しをしていたが，SQLでできた．

## DEMO
https://gsacademy-ki.sakura.ne.jp/lec_08_php/write.php (アンケート記入ページ)

https://gsacademy-ki.sakura.ne.jp/lec_08_php/read.php (アンケート結果閲覧ページ)

## 難しかった点・次回トライしたいこと(又は機能)
- データの列が多いと$stmtにbindValueする際の文も増えるので，何か簡便化する方法を探りたい．
- アンケート項目を変更する際にSQL文も一緒に変更しないといけないのでそこ含めて自動化できる方法ないか探りたい．
