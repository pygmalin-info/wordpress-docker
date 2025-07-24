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

## 管理者画面

<img width="800" alt="image" src="https://github.com/user-attachments/assets/1a9ef23b-6b8b-4a00-ba53-3d818a84b3d3" />

### 記事を新規投稿

<img width="500" alt="image" src="https://github.com/user-attachments/assets/3e3842ab-8c45-4bcf-8ac7-c00db72394fe" />

### 記事作成&公開

<img width="800" alt="image" src="https://github.com/user-attachments/assets/b8a85632-201b-4a6c-a340-b45dbc6dc3c6" />

## ユーザー画面

左上のリンクから移動

<img width="800" alt="image" src="https://github.com/user-attachments/assets/57292d92-a836-4e25-a9a9-696eace24a32" />

先ほど登録した記事が表示されている

<img width="800" alt="image" src="https://github.com/user-attachments/assets/1ec7ab8b-e7bf-4cbc-a2bc-56f20df65172" />
