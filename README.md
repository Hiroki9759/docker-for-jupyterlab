# dockerfileの使い方

## ダウンロード
公式サイトからdockerをダウンロードしてください
手順は公式に従ってください

## dockerfileの起動
git colneしたdockerfileをimage化します
docker build -t imagename:tag .

## dockerfileの起動
docker run -p ポート -it コンテナ名 シェル
