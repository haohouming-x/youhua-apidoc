# Easily devlop the apidoc server

```js
npm install

// 读该项目下的apidoc.json
npm start

// 读后端项目下的apidoc.json
npm run start:remote

// 打包项目，生成静态页面
npm run build
npm run build:remote
```

选一个使用

- `npm start` 读本地apidoc文件，需要项目经常pull才可以看到最新api文档
- `npm run start:remote` 读远程后端项目的apidoc文件，可及时看到最新api文档
- `npm run build`或`npm run build:remote`打包出静态页面然后打开，可不需要每次跑server。（规则同`start`）

## [demo](https://haohouming.github.io/youhua-apidoc/index)
