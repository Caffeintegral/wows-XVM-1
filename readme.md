## 必要なもの
- リプレイを残すようにする設定
- Nodejs
- JavaScript有効のWebブラウザ

## 動作環境
node jsのバージョン13で作ったので, 13以上だと動きそうです.

## はじめに
.envファイルに必要情報を書いておいてください.
- APIKEY：WGのアプリケーションなんちゃらから取得するやつ
- APIURL：ASIAサーバなら変えなくてヨシ
- WOWSPATH：ゲームがあるPC上のディレクトリのパス

## 起動
run-xvm.batを開いたら起動します. ポートは10080.

## 強調表示の仕様
とくに断りのないものは太字もしくは太字+下線による強調表示.
- トータル戦闘数
    - そのときのrekisiの戦闘数（この値を1rekisiとする）以上のとき
- 主砲命中率
    - 戦艦
        - 32.5%以上のとき
    - 巡洋艦
        - 40.0%以上のとき
    - 駆逐艦
        - 51.0%以上のとき
- 生存率
    - 12.5%以下のとき. ただし, 16戦以上プレイしているときのみ
- ソロ戦闘割合
    - 100%のとき
    - 30%以下のとき