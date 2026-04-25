# 笑顔メーター

カメラでリアルタイム笑顔判定 (0〜100点)。

- MediaPipe Face Landmarker で顔検出＋blendshapes取得
- 笑顔成分: 口角上がり / 頬の収縮 / 目の細さ から合算スコア
- 90点以上で「パーフェクト笑顔！」、ランクメッセージ6段階
- 顔の口元ライン描画
- スコアキャプチャでXシェア / PNG保存
- インカメラ ⇔ 外カメラ切替
- 完全クライアント完結（カメラ画像はサーバー送信なし）

GitHub Pages: <https://maxtakaharu34-cmd.github.io/smile-jp/>
