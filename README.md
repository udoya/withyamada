## 注意事項

React + Vite + TypeScript

インターンで学んだことを友達に教えるために制作したレポジトリです。

## セットアップ

### 前提

ちゃんとバージョンが入ってるかな？
入ってなかったら、検索しながら使えるようにしてみよう
最終的には node, yarn, vite が通ってれば多分大丈夫。

```
node -v
yarn -v
```

こいつも参考にしよう

[yarn をインストールする](https://qiita.com/suisui654/items/1b89446e03991c7c2c3d)

もし Windows で権限がないって言われてしまったら
[PowerShell の実行ポリシー変更 - Qiita](https://qiita.com/earthdiver1/items/b3f529c81f5892972a72)

### 準備完了～ web アプリが立ち上がるまで

```
yarn install
```

これによって yarn に書いておいた色々が install されるはず。今回使う vite もこれで入るはず。

```
yarn dev
```

でポート番号 5173 で動けば 準備完了
`http://localhost:5173/` or `http://127.0.0.1:5173/` になるはず。

なお、

```
yarn dev --host
```

だと同じネットワーク内からアクセスできるようになる。

## ブランチの切り方

以下を参考

[git flow と github flow とは？その違いは？](https://qiita.com/mint__/items/bfc58589b5b1e0a1856a)
