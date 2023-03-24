# rpgmz-game-template

自分用のツクール MZ ゲームテンプレート

- ツクール 2000 風仕様
- デフォルト戦闘を使用しない前提
- 探索ゲームを作るのに必要最低限のデータベース構成
- 2000 + 2003 + MV + MZ の戦闘アニメ同梱
- EasyRPG 製 RTP 素材同梱
  - https://github.com/EasyRPG/RTP
- 画面描画プラグイン搭載
- 仮想ゲームパッドプラグイン搭載
- ZZFX 搭載
- アセットサーバー機能搭載

## 使い方

1. ZIP で落とす
2. GitHub で新たにリポジトリ作成

### アセットサーバーがある場合

3. AssetServer プラグインでサーバー URL を設定
4. アセットサーバーから素材をローカルに落として開発
   （またはローカルの素材をアセットサーバーにコピー）
5. GitHub Pages でゲームを公開
   （リポジトリに素材を置かなくても動く）

## 制作上の注意

- コモンイベントは SuperCommonEvent を使用する
- 変数は OneVariable を使用する
- 画面描画処理は customChalk に書く

## リリース時の作業

- リントエラーが出てないか確認
- 使っていないタイルセットをデータベースから削除
- サーバー RTP で使用する場合、音声素材・画像素材を削除

## ゆくゆくは欲しい機能

- iframe ゲームプレイヤー（ src/index.html に飛ばすだけじゃカッコがつかないし ）
- したらば掲示板と連携して感想や攻略情報をゲームプレイヤーから読めるように
- アフィリエイトプラグイン
