新しいアカウントでTeamNishitaniに参加。

gitHubに公開鍵が設定されていなかったので、このブログを移動できなかったので公開鍵を設定。

公開鍵は隠しファイルの.sshの中に保存されているのでpbcopyを用いてコピー。

pbcopy < /.ssh/id_rsa.pubを使う。

gitHub内でsettings/ssh/Add SSH keyと進んでいき、titleに公開鍵名、keyに公開鍵の中身を登録。

ssh -T git@github.com で接続を確認。

確認後、jekyllのブログの中身を移動すると、無事動かすことができた。