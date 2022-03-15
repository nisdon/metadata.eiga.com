# 映画データベース  Scraper for Kodi

## 概要
Kodi映画データベースへ映画情報を追加するめのScraperです。

## 特徴
 - 日本語対応のみ。
 - 映画.comの情報をScraping。
 - ポスター、ジャンル情報はTMDBから取得。
 - 原題でTMDB情報を検索可能。

## 取得項目
 - タイトル
 - 原題
 - 上映時間
 - 製作年
 - あらすじ
 - 監督
 - 俳優
 - 評価
 - ジャンル
 - 製作国
 - ポスター

## 依存ライブラリ
 - metadata.common.themoviedb.org version 3.2.6

## その他
### ジャンルの取得
 - TMDBから取得できない場合は「ドラマ」に設定。

### ポスターの取得
 - TMDBから取得できない場合は、映画.comより取得。

### Tips
 - TMDB情報取得に失敗する場合、マニュアルで原題の入力を試して下さい。
