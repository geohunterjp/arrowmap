# arrowmap

ArrowMap by GeoHunter

地図やストリートビューのスクリーンショットの上に、矢印やエリアを描き込んでメモを残せるツールです。GeoGuessrなどの位置特定(ジオロケーション)の検討・共有に使いやすいよう作られています。

A tool for drawing arrows and areas on top of a map screenshot and attaching notes to them. Designed to make geolocation research (e.g. for GeoGuessr) easy to work through and share.


🇯🇵 日本語

できること
矢印を描く: Ctrl + クリックでスタート地点、終点をクリックして矢印を作成
矢印を曲げる: Ctrl + 右クリックで矢印に曲げ点を追加
エリア(面)を描く: Shift + クリックで多角形のエリアを作成
矢印・エリアにメモを追加: クリックして開くポップアップにメモを記入
色分け: 矢印・エリアごとに好きな色を設定可能。明るい色を選んだときは番号の文字が自動で黒に切り替わり、見やすさを保ちます
ホバーでメモ表示: 矢印やエリアにマウスを乗せると、書いたメモがポップアップ表示されます
線を細くする: 矢印の編集欄のチェックボックスで、線と矢じり、番号バッジを一回り小さい表示に切り替え可能
双方向矢印: 両端に矢じりを付けられます
メモの並べ替え: 右側のメモ一覧のグリップ(⠿⠿)をつかんでドラッグすると、順番(番号)を入れ替えられます
元に戻す/やり直す: 矢印・エリアの追加や編集はもちろん、背景画像の読み込み・貼り付けもUndo/Redoで取り消し可能
背景画像: 「画像を読み込む」ボタンでのファイル選択、またはクリップボードからの貼り付け(Ctrl+V)に対応
複数ファイル管理: 案件ごとにメモを分けて保存・切り替え可能(ブラウザのlocalStorageに自動保存)
書き出し/読み込み: メモや矢印のデータをJSONファイルとしてエクスポート・インポート可能。別のPCやメンバーへの共有にも使えます
日本語/英語切り替え、ライト/ダークテーマに対応


使い方
上のリンク(公開URL)を開く
「画像を読み込む」から地図のスクリーンショットを読み込む(貼り付けでもOK)
Ctrl + クリックで矢印、Shift + クリックでエリアを描く
描いた矢印/エリアをクリックしてメモや色を設定
必要に応じて「書き出し」でJSONを保存し、他の人と共有


データの保存について
入力したデータはブラウザ内(localStorage)に自動保存されます。ブラウザやパソコンを変えると引き継がれないため、大事なデータは「書き出し(Export)」でJSONファイルとして保存しておくことをおすすめします。
ツール自体をアップデートしても、ブラウザに保存済みのデータが消えることはありません。


フィードバック

不具合や要望があれば、Discordなどでお気軽にどうぞ。


🇬🇧 English

Features

Draw arrows: Ctrl + click to place a start point, then click again for the end point
Bend an arrow: Ctrl + right-click to add a bend point to an arrow
Draw areas: Shift + click to draw a polygon area
Add notes: click an arrow or area to open a popup and write a note
Color coding: pick any color for each arrow/area. When a light color is chosen, the number badge text automatically switches to black for readability
Hover to preview notes: hovering over an arrow or area shows its note in a tooltip
Thin line mode: a checkbox in the arrow editor switches the line, arrowhead, and number badge to a smaller size
Two-way arrows: add arrowheads to both ends
Reorder notes: grab the handle (⠿⠿) on a note in the sidebar list and drag it to reorder — numbers update automatically
Undo/redo: covers arrow/area edits as well as loading or pasting a background image
Background image: load via the "Load image" button, or paste directly from the clipboard (Ctrl+V)
Multiple files: keep separate notes per case/project, auto-saved to the browser's localStorage
Export/Import: save your arrows and notes as a JSON file, and load them back later — handy for sharing with others
Japanese/English toggle and light/dark theme


How to use

Open the published link above
Click "Load image" to add a map screenshot (or paste one from the clipboard)
Ctrl + click to draw arrows, Shift + click to draw areas
Click any arrow/area to add a note or change its color
Use "Export" to save your work as a JSON file to share with others


About data storage

Everything you enter is auto-saved locally in your browser (localStorage). It won't carry over if you switch browsers or computers, so it's a good idea to use "Export" to save important work as a JSON file.
Updating the tool itself will never erase data already saved in your browser.


Feedback

Bug reports and feature requests are always welcome — feel free to share them on Discord or wherever the tool is discussed.
