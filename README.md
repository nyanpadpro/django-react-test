# これはなに？

djangoとReactの個人的な学習リポジトリ  


## 動作サンプル  

https://agile-waters-13416.herokuapp.com/

## 参考

### プロジェクトの作り方
- Tutorial: Django REST with React (Django 2.0 and a sprinkle of testing)  
https://www.valentinog.com/blog/tutorial-api-django-rest-react/  

### pipenvの使い方  
- Pipenv: 人間のためのPython開発ワークフロー  
https://pipenv-ja.readthedocs.io/ja/translate-ja/

### git/GitHubの使い方  
- 初めてGitHubリポジトリにpushしたらrejectedエラーになったときの対応メモ  
https://qiita.com/takanatsu/items/fc89de9bd11148da1438  

### Herokuの使用方法  
#### Googleでheroku Django などで検索するとデプロイ方法がたくさん出ます  

#### トラブル：アプリケーションクラッシュ  
サンプルのプロジェクト構成と本リポジトリのディレクトリの構成が異なるためProcfileの書き方に躓いた。  
試行錯誤し、無理やりプロジェクトフォルダに移動後、gunicornを起動するようにしたらうまくWebサーバが立ち上がった  

#### トラブル：500 server error
調査中
