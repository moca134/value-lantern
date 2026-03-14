# value-lantern プロジェクト設定

## デプロイ
- GitHub Pages で公開中（スマホからアクセスされている）
- URL: https://moca134.github.io/value-lantern/
- **ファイルを変更したら必ず `git push` すること。ローカル変更だけではスマホに反映されない。**

## 構成
- `index.html` 1ファイルのみ（フレームワーク不使用）
- Canvas で壁紙画像を生成する（`drawLantern` 関数）
- ユーザーが見る成果物 = 最後に生成されるキャンバス画像

## 注意
- UI のスタイル変更とキャンバス画像の変更は別物。ユーザーが「画像」と言ったら `drawLantern` 関数を変更する。
