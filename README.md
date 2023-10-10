# Free Time Navigator

### [画面遷移図](https://www.figma.com/file/n0ZRoCEkUWNxR26it2SO1l/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?type=design&node-id=0%3A1&mode=design&t=S7d836lFTDsDbiy3-1)

### [ER図](https://drive.google.com/file/d/1sL5jKD6LwQu95wq17XnB2Fd7OVhyeP75/view?usp=sharing)

## サービス概要
空き時間に応じた行ける場所を提案することで、 <br>
外出時に何ができるかを考える手助けをする　<br>
スポット検索サービスです。

## 想定されるユーザー層
- 外出好きの人
- 性別・年齢問わず
- 空いた時間に何するかを決めるのが苦手な人

## サービスコンセプト
外出した際、予定の前後で空いた時間に「何をするか」を決めるのに苦労した経験があるため考案しました。 <br>
私自身外出が好きなのですが、
- 予定より早く目的地に着いた
- 予定を終えたがすぐに帰宅する必要はない
- 知人を待たなければならない

といった、時間はあるけど予定はないという状況になることが多くあります。 <br>
その際に周辺施設の情報を検索するにしても、「〇〇駅　カフェ」といったように目的を決めないと検索できなかったりします。 <br>
結果、毎回カフェでスマートフォンをいじるといったような過ごし方になってしまい勿体無いと感じます。 <br>

上記の経験から、指定した時間内に移動および利用ができる施設・スポットを表示することで、行動の選択肢を可視化することができ、空き時間を有効に利用できるのではないかと考えました。 <br>

差別化ポイントとして、 <br>
- 施設・スポット検索系サービスは、場所を指定 → 時間を表示する構成に対して、このアプリは時間を指定 → 場所を表示となっている点
- 「やりたいことリスト」を登録・通知する機能によってリマインダーとしての機能も有する点

上記2点が、差別化・推しポイントとなっています。

## 実装を予定している機能
### MVP
- スポット検索機能
- 絞り込み検索機能
    - 施設タグの指定
- スポット一覧表示機能
- スポット詳細表示機能（ルート表示）
- 位置情報取得機能

### その後の機能
- ユーザー登録機能
- ログイン/ログアウト機能
- 時間リマインド機能（ライン通知）
- やりたいことリスト登録
- スポットお気に入り機能
- スポットシェア機能（外部SNS）
