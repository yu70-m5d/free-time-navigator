# [Free Time Navigator](https://www.free-time-navigator.com)
### https://www.free-time-navigator.com

<br>

## サービス概要
周辺施設を、空き時間やジャンルで検索しルートを表示するサービスです。

<img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/e8e165cf-0977-4061-8b38-c499a766d780"
    width="320px"
/>

<br>

## ターゲットユーザー
- 外出好きの人
- 性別・年齢問わず
- 空いた時間に何するかを決めるのが苦手な人
### ユーザーが抱える課題
- 予定の前後で余った時間を活用したい
- マップアプリは目的地が決まっていないと検索しづらい
### 解決方法
- 空き時間やジャンルから施設を検索できる
- 「やりたいこと」をメモしておくことができる

<br>

## 制作背景
私自身、外出したとき、予定の前後で生まれた空き時間に何をするか悩む機会が多くあります。  
こういった場合、そもそも目的が決まっていないためマップアプリ等も利用しにくい状況です。  
そこで、入力した空き時間から利用できる周辺施設を一覧で表示することで、選択肢を可視化し  
空き時間の活用をサポートするサービスを制作しようと考えました。  
予定のコントロールがし易いよう、おおよその利用時間の表示や、LINE通知による時間リマインド、    
外出先での利用を想定しているため、スマートフォンからの操作がし易いUIにするといった工夫をしました。

<br>

## 機能の紹介

| スポット一覧表示 | タグ絞り込み |
| - | - |
| <img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/f9135ad1-4c58-48ff-8efa-6edf27b1dde8" width="200px" /> | <img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/409c7de5-bbfc-4ee8-916d-59372242ea51" width="200px" /> |

|スポット詳細表示 | ルート表示 | LINEリマインド |
| - | - | - |
| <img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/e1d5ff17-11a5-4ef3-ac99-8758ec1132a6" width="200px" /> | <img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/8ed3e312-e2ff-4759-afe6-66fc4fd3354b" width="200px" /> | <img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/0cdfd374-4b2c-406f-b279-26cf93e64da1" width="200px" /> |

| タスク一覧・作成・詳細・編集 |
| - |
|<img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/1e77ee79-4b06-48db-a243-2bef391cc52e" width="200px" /><img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/77d92678-d21c-4d4f-a04f-1630e35f58d0" width="200px" /><img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/130cbdf9-fff1-49a5-b207-a348856c10b1" width="200px" /><img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/d49dce61-96f2-4b21-ba66-5764e6148b86" width="200px" /> |

| ユーザーページ |
| - |
| <img src="https://github.com/yu70-m5d/free-time-navigator/assets/124274307/6b829d1b-25f8-4de5-ba7d-44463738cfdd" width="200px" /> |
 
<br>

## その他の機能
- お問い合わせ機能
- ユーザー登録
- メールログイン・LINEログイン
- 施設お気に入り登録
- X（旧Twitter)シェア

<br>

## 画面遷移図
### [Figma](https://www.figma.com/file/n0ZRoCEkUWNxR26it2SO1l/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?type=design&node-id=0%3A1&mode=design&t=S7d836lFTDsDbiy3-1)

<br>

## ER図
![ER図_FreeTimeNavigator drawio](https://github.com/yu70-m5d/free-time-navigator/assets/124274307/221fda1b-36e3-4ddd-a755-41ee68e8ffa4)

<br>

## 使用技術
### バックエンド
- Ruby 3.2.2
- Ruby on Rails(APIモード) 7.0.8

### フロントエンド
- Next.js 14.0.1

### インフラ
- Render.com
- Vercel
- Neon (PostgreSQL)

### その他
- GoogleMapsAPI
- GoogleDirectionsAPI
- GooglePlacesAPI

<br>

## 対応エリア（随時追加）
```
新宿駅（東京都）
渋谷駅（東京都）
池袋駅（東京都）
北千住駅（東京都）
東京駅（東京都）
町田駅（東京都）
上野駅（東京都）
中目黒駅（東京都）
新御茶ノ水駅（東京都）
横浜駅（神奈川県）
武蔵小杉駅（神奈川県）
大宮駅（埼玉県）
西船橋駅（千葉県）
名古屋駅（愛知県）
梅田駅（大阪府）
京都駅（京都府）
```
