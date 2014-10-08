github-training
===============

# 2014/10/08 Git, GitHub勉強会内容

## Git

スライド: [いつやるの？Git入門](http://www.slideshare.net/matsukaz/git-17499005)

* Gitの簡単な説明
* init, add, commitまで

## GitHub

（スライドなし）

* SADP Organizationにgithub-trainingレポジトリを作成
* 各自 `git clone git@github.com:sadp-andante2014/github-training.git`
* ブラウザ上でREADME.mdを変更&コミット
* 各自 `git pull`
* 各自 `git branch <自分の名前> && git checkout <自分の名前>` で自分のブランチを作成
* 各自 自分の名前.md ファイルを作成 && add && commit
* 各自 `git push origin <自分の名前>`
* ブラウザ上で各自の名前ブランチからmasterブランチへpull-request
* 全てのプルリクエストをマージ
* yubessyがREADME.mdを破壊的に変更してorigin/masterにpush
* e-monが（yubessyによるpushを知らずに）README.mdを破壊的に変更してorigin/masterにpush→ERROR
* e-monがpull && merge && push
