# SonarQube_GithubActions_test
GithubActionsとSonarQubeを連携を確認するためのレポジトリ

# テストを試したい場合
## PHPUnit をインストールする
$ docker-compose exec php composer update
## テストを実行する
$ docker-compose exec php composer test -- html/tests

### Reference
https://qiita.com/engineerjyef/items/6d54b8edcc636e29c1e2

### Todo
SonarQubeをAWSなどでホスティングしtockenを発酵させた後、レポジトリのsettingにて
githubActionsに必要なtokenのkey, valueを入れる。

