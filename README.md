# vue-todo-output
アウトプットとして、Vueを使ったtodoリストを作成。

Trello風。

vuexを利用した状態管理。

urlはこちら
https://github.com/massu-159/vue-todo-output


## 目次
1. 環境構築
2. アプリケーションの仕様

## 1. 環境構築

### 1-1. ライブラリ インストール

```
npm install

または

yarn
```

### 1-2. アプリケーション実行

```
npm run dev

または

yarn dev
```

## 2. アプリケーションの仕様

### 2-1. 仕様
- リスト
  - リスト一覧表示
  - リスト作成処理
  - リスト削除処理
  - リスト移動処理(ドラッグ&ドロップ)
- Todoカード(リスト内に作成)
  - Todoカード一覧表示
  - Todoカード作成処理
  - Todoカード削除処理
  - Todoカード移動処理(ドラッグ&ドロップ)


### 2-2. 構成技術
- vue : "2.6.11"
vuedraggable : "^2.24.3",
vuex : "^3.4.0"
- eslint : "^6.7.2"

