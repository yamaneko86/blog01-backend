# blog01-backend

- 仮想環境の作成

```
  $ python3 -m venv myvenv
```

- 仮想環境の有効化

```
  $ source myvenv/bin/activate
```

- 仮想環境の無効化

```
  $ deactivate
```

- 管理者サイト作成(Django コマンド)

```
  $ django-admin startproject mysite .
```

- プロジェクト作成(.で直下に作成)

```
  $ python3 manage.py startproject myproject .
```

- アプリケーション作成

```
  $ python3 manage.py startapp myapp
```

- テスト用簡易サーバを起動

```
  $ python3 manage.py runserver
```

- 管理者サイトのためのスーパーユーザー作成

```
  $ python3 manage.py createsuperuser
```

- models.py を探索してデータベースのマイグレーションファイルを作成

```
  $ python3 manage.py makemigrations
```

- マイグレーションファイルをデータベースに反映

```
  $ python3 manage.py migrage
```
