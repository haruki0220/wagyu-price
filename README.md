# Git Lesson



## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
リモートリポジトリとは、分散バージョン管理システムで、ネットワーク上のサーバーで運用され、プロジェクトの大本のファイル群を保管、管理するリポジトリ。
ローカルリポジトリとは、分散バージョン管理システムで、利用者の手元のコンピュータに作成・複製されたリポジトリ。利用者が直にファイルの編集などを行う事ができる。



## プッシュとマージの違いは何でしょうか？
プッシュはローカルリポジトリの変更をリモートリポジトリに反映させること。
マージは他のユーザーが行った変更と、自分の変更を併合させること。



## コミットとプッシュの違い
コミットはVSコードなどで変更した内容をローカルリポジトリに反映させる事。
プッシュはローカルリポジトリの変更をリモートリポジトリに反映させる事。



## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
どこをどのように変更したのかが一目見て分かりやすいように書くのが最適。



## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
ローカルでマージはgithubでマージする前に変更をテストおよび検証できるもの。
プルリクエストでマージはgithubでリポジトリに対してプッシュアクセスを持つユーザなら誰でもマージを実行できるもの。



## コンフリクトを起こしてしまった場合、どう対処すべきですか？
誰かがリポジトリのブランチからプルリクエストを送信した場合、ローカルでマージして、マージコンフリクトを解決する。






