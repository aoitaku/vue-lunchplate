# vue-lunchplate
[English](README.md) / 日本語

> Vue 2.0 で TypeScriptとクラススタイルの Vue コンポーネントと Element UI を使ってさっとプロトタイプを作るための Webpack と `vue-loader` のテンプレートです。

> このテンプレートは Vue 2.0 向けです。

### 使い方

これは [vue-cli](https://github.com/vuejs/vue-cli) のプロジェクトテンプレートです。

``` bash
$ npm install -g vue-cli
$ vue init aoitaku/vue-lunchplate my-project
$ cd my-project
$ npm install
$ npm run dev
```

### 内容物

- `npm run dev`: Webpack + `vue-loader` を起動します。source map と hot-reload が設定されています。

- `npm run build`: HTML/CSS/JS を最小化してビルドします。

詳細は [docs for vue-loader](http://vuejs.github.io/vue-loader) を見てください。[breaking changes in vue-loader@9.0.0](https://github.com/vuejs/vue-loader/releases/tag/v9.0.0) も参照のこと。

### フォークして私家版を作る

このリポジトリをフォークして私家版を作って、 `vue-cli` で使うことができます:

``` bash
vue init username/repo my-project
```
