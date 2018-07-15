# これはなに？

個人学習のため下記記事のチュートリアルを写経する  

- Tutorial: Django REST with React (Django 2.0 and a sprinkle of testing)  
https://www.valentinog.com/blog/tutorial-api-django-rest-react/  


## 参考

本チュートリアルを行う上で下記の記事を参考にさせて頂きました。  

### pipenvの使い方  

- Pipenv: 人間のためのPython開発ワークフロー  
https://pipenv-ja.readthedocs.io/ja/translate-ja/

### git/GitHubの使い方  

- 初めてGitHubリポジトリにpushしたらrejectedエラーになったときの対応メモ  
https://qiita.com/takanatsu/items/fc89de9bd11148da1438  


## コメント  
- pipenv便利ですね  
- 久しぶりにgitをコマンドで使うと色々忘れていて困ります  


## トラブル事例  
- Cloud9(AWS)でpython manage.py runserver 0.0.0.0:8080でWebサーバを起動してブラウザからアクセスするとDisallowedHostになる  

settings.pyのALLOWED_HOSTSに下記のようにAWS側のホスト名を設定したら解決した。
```python
ALLOWED_HOSTS = [
    '…s.cloud9.ap-southeast-1.amazonaws.com'
]
```
DEBUG = Trueだとセキュリティの制限がかかるみたい。

