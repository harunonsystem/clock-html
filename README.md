# clock

Notion 埋め込み用のストップウォッチ / タイマー。

- `index.html` … 本体（単一ファイル・依存なし）
- `vercel.json` … 更新が即座に反映されるようキャッシュを無効化

## 使い方

Vercel にデプロイして発行された URL を、Notion のページで `/embed` に貼る。
枠の高さは 480〜560px 程度が収まりやすい。

## 更新

`index.html` を編集して push すると自動で再デプロイされる。
