# compornent（共通部品）

## イメージ画像
- chrome
 <img width="388" alt="image" src="https://user-images.githubusercontent.com/99580997/166088880-8855aebc-0d6e-4668-b6ca-d83ca113f8dc.png">
 <img width="780" alt="image" src="https://user-images.githubusercontent.com/99580997/166088890-b60bc682-888f-4f24-ab0c-f820724c2c0c.png">
 <img width="1165" alt="image" src="https://user-images.githubusercontent.com/99580997/166088904-7e0ce72c-ceca-4d82-9e1a-23a4a54d1ce4.png">
- safari
 <img width="597" alt="image" src="https://user-images.githubusercontent.com/99580997/166088984-d479f399-5bd2-41b9-bd0a-d54359b5b4c0.png">


## 概要

- 同じページ内で swiper を複数存在させる
- https://www.notion.so/000_web-component-index-c4b399010bf342e9b4e2ed516cf9c730

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- html -> `<div class="swiper mySwiper1">` `mySwiper1`クラスを追加する。
- swiper css -> デフォルトでは`swiper`にサイズを設定してたが、`.mySwiper1`クラス名を変更してサイズを設定する。
- `.swiper-slide`などは触らない。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> xxx をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/

## portfolio url:

- https://c-0062.wtb.cfbx.jp/

## 参考にしたサイト

- xxx

## 更新履歴

- 2022/4/30 特に問題なく同一ページに swiper を複数存在できた。

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
