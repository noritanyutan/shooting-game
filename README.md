# shooting-game

# アプリ名
宇宙戦争

# 概要
スペースキーで弾を発射でき、矢印キーでそれに応じた動きを自機がします
敵が弾を撃ってきて、当たると赤くなるエフェクトが発生します。敵に自機が当たった場合も同様です。
![](https://i.gyazo.com/f3463eb89ffee0cde1eb8ea5e0e3f185.png)

# 本番環境(デプロイ先 テストアカウント＆ID)
https://noritanyutan.github.io/shooting-game/

# 制作背景(意図)
私は子供の頃ゲームが好きであり、まだまだ初心者の状態だったので、まずはプログラミングの勉強と思ってjavascriptの勉強も兼ねて、jsを用いたゲームを作ろうと思ったからです。

# DEMO
![](https://gyazo.com/f04ce94304b52b5db5094f57203ed81e.gif)

# 工夫したポイント
7日間という限られた時間のなかで、素人同然の私がどうすればゲームを作れるかを考え、まずはエラー起きてもいいやくらいの気持ちで手を動かしたこと
敵の動きが単調にならないように三角関数でもって動きをつけた事、敵の弾も同様です。
アニメーションのような動きをつけるため画像をたくさん引っ張ってきて、それに伴う動きをつけるように工夫しました


# 使用技術(開発環境)
javascript、HTML

# 課題や今後実装したい機能
今後実装したい機能は自機に敵の弾や敵そのものに３回当たったら、ゲームオーバー画面に遷移するようにしたいです
課題は私は釣りも好きなので釣りに応じた実装をすること、また効果音をどのようにしてつけるかが課題です。

# DB設計
今回はDB設計は特に行っていません。
