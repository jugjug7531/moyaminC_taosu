# moyaminCを倒すゲーム
ボス”moyaminC”を倒すだけのシューティングゲームです(身内向け).

[遊ぶ！(クリックすると実際に遊べます)](https://jugjug7531.github.io/moyaminC_taosu/)

# 操作方法
- ショット：Xキー
- 移動：十字キー
- ポーズ画面：Pキー（BGMと効果音の音量調整ができます）

# ゲームURL
https://jugjug7531.github.io/moyaminC_taosu/

# 使用画像およびBGM等
- [シューティングゲーム用ドット絵フリー素材｜RECLUSE](http://mfstg.web.fc2.com/material/index.html)
- [ポケットサウンド/効果音素材](http://pocket-se.info/)
- [Music-Note.jp](http://www.music-note.jp)

moyminCの画像は自作です.

# 更新履歴
- 2016/12/31
  - ver. 1.0

- 2017/1/1
  - ver. 1.1
    - メモリ増加を軽減するためにmain.jsを修正
      - core.replaceSceneを修正
      - 重複していたscene.addEventListenerを削除
    - タイトル画面に現在のバージョンを表示
- 2017/1/2
  - ver. 1.2
    - ステージ２, ステージ３を追加
    - 「全ステージクリア画面」を追加.
    - ゲームオーバー画面に「リトライボタン」と「タイトルに戻るボタン」を追加
    - ステージクリア画面に「次のステージに進むボタン」と「タイトルに戻るボタン」を追加
    - BGMおよび効果音を追加
    - プレイ中の「ポーズ画面」を追加
- 2017/1/3
  - ver. 1.3
    - BGM&効果音の音量調節機能を追加(ポーズ画面から調整可能)
    - 全ステージクリア後にプレイヤーランクを表示
    - 全ステージクリア後にTwitterでつぶやくことができるボタンを追加
- 2017/1/4
  - ver. 1.3.1
    - ポーズ画面からタイトル画面に戻ったときに, ゲームオーバー合計回数とダメージを受けた合計回数がリセットされない不具合を修正
    - ポーズ画面からタイトル画面に戻った後, 初めからやり直して再びその戻ったステージにきたとき, ステージのBGMが途中から再生される不具合を修正
    - ゲームページ内にTwitter共有ボタンを追加
  - ver 1.3.2
    - ゲーム内容の修正
      - すべてのステージのいずれかでゲームオーバーになるたびに, ステージ３開始時のボスの体力が少し減った状態からスタートするようにしました. (ただし, ゲームオーバー11回目以降は減りません.)
    - 画面右上に制限時間を追加
