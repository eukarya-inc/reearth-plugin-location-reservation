# 場所の予約申請ウィジェット

このプラグインは、場所の予約申請をするためのプラグインです。
このプラグインは 2 つの機能を持っています：
1 つは、描画ツール：地図上に任意の位置に円の描画・3D モデルの配置・ラベルを追加や、画面に表示された地図のスクリーンキャプチャを取ったりすることができます。
2 つ目は、申請フォーム：既存の申請フォームを埋め込むことができます。

### 編集ページでできること

1. 必須項目を設定した申請フォームを用意する。(このプラグインを有効に使うには、画像項目が必要です。）
2. フォームのリンク先をプラグインの Iframe URL プロパティに設定する。(設定可能なプロパティは以下の通りです。）

### 公開ページでできること

1. 描画ツールタブで、地図上の使用したい場所に円を描画する。
2. 同じタブ内の「地図のダウンロード」ボタンで、画面キャプチャを取る。
3. 上記でダウンロードした画像を使ってフォームに申請する。

<!-- #### 各機能の利用方法
円の描画方法
2. 「エリアの追加」ボタンをクリック
3. 地図上の任意の位置をクリック

円のサイズ変更方法
1. 円追加時に
2. 半径のスライドバーを操作するとエリアの大きさを変更することができます。
3. 追加したエリアを削除する場合はゴミ箱アイコンをクリックしてください。 -->

## 設定可能な項目

- title: ヘッダーに表示するタイトルを入力します。
- Iframe URL: ウィジェットに埋め込むフォームの URL を指定します。未入力の場合、フォームタブは非表示になります。
- 3Dmodel: クリック時に配置する 3D モデルを指定します。指定しない場合は、上記画像の 3D モデルが配置されます。
- 3Dmodel scale: 配置する 3D モデルの大きさのスケーリングファクターを指定します。デフォルトは 1 です。
- Theme color: ウィジェットボタンの色を指定します。設定しない場合は#00BEBE となります。
- Area color: Add Area で配置するエリアのカラーを指定します。未設定の場合、#00FF3880 になります。

## 注意

- 申し込みフォームを埋め込みたい場合は、あらかじめフォームを作成しておく必要があります。(Google フォーム、Forms by Microsoft など)
- 編集ページにおいて右パネルで設定を変更を行なった場合は、一度ページをリフレッシュしないと変更が反映されません。右パネルで設定を変更した場合は一度ページを更新してください。
- 「地図画面のダウンロードボタン」で保存される画像には、インフォボックスやウィジェットの内容は含まれません。

# Location Reservation plugin

This is the plugin to register location.
This plugin has two features:
One is a drawing tool： Drawing a circle at any location, placing 3D model on the map, adding a label and taking a screen capture of the map shown on the screen.
Two is application form：to embed the existing application form.

## Use flow:

### What you can do on the edit page

1. Prepare to apply a form that is set the required item. (make this plugin useful, an image item is required)
2. Set the form link to the plugin Iframe URL property. (More settable properties are below)

### User

1. Draw the circle on a map where the user wants to use with the drawing tool tab.
2. Take a screen capture with the "Download map" button on the same tab.
3. User applies to a form using the image downloaded above.

## What you can do on the public page

- Title: Enter the title to be displayed in the header.
- Iframe URL: Specify the URL of the form to be embedded in the widget. If not entered, the form tab will be hidden.
- 3D model： Specify the 3D model to be placed on click. If not specified, a model on the image above will be placed.
- 3D model scale： Specify the scaling factor of the size of the 3D model to be placed. The default is 1.
- Theme color: Specify the color of the widget buttons. If not set, it will be #00BEBE.
- Area Color: Specify the color of the area to be placed by Add Area. If not set, it will be #00FF3880.

## Caution

- If you want to embed the apply form, you need to make an application form first with some tools. (eg, Google form, Forms by Microsoft, etc.)
- If you change settings in the right panel on the edit page, you must refresh the page once for the changes to take effect. Please refresh the page once when you change the settings in the right panel.
- The image saved by the "Download button on the map screen" does not include the contents of infoboxes and widgets.
