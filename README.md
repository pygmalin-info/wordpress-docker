# Wordpress + docker

参考サイト：<br>
[クィックスタート: Compose と WordPress](https://docs.docker.jp/compose/wordpress.html)

## 環境構築

### gitクローン

```bash
git clone git@github.com:pygmalin-info/wordpress-docker.git
```

ディレクトリ移動

```bash
cd wordpress-docker
```

### コンテナ作成&起動

```bash
docker compose up -d
```

### ブラウザ上でWordPressへアクセス

管理者画面：http://localhost:8000/wp-admin/

ユーザー画面：http://localhost:8000

#### 初期設定画面

言語選択

<img width="500" alt="image" src="https://github.com/user-attachments/assets/55278fb5-8a69-464e-8781-31a553d31dbd" />

サイト設定

<img width="500" alt="image" src="https://github.com/user-attachments/assets/e4089152-ea39-4d6a-be10-d2a5896552e5" />

### コンテナ停止&削除

```bash
docker compose down
```
