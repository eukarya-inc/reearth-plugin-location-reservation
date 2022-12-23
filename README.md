# 場所の予約申請ウィジェット

このプラグインは、場所の予約申請をするためのプラグインです。
このプラグインは 2 つの機能を持っています：
1 つは、描画ツール：地図上に任意の位置に円の描画・3D モデルの配置・ラベルを追加や、画面に表示された地図のスクリーンキャプチャを取ったりすることができます。
2 つ目は、申請フォーム：既存の申請フォームを埋め込むことができます。

## 利用の流れ

### 編集者

1. 必須項目を設定した申請フォームを用意する。(このプラグインを有効に使うには、画像項目が必要です。）
2. フォームのリンク先をプラグインの Iframe URL プロパティに設定する。(設定可能なプロパティは以下の通りです。）

### ユーザー

1. 描画ツールタブで、地図上の使用したい場所に円を描画する。
2. 同じタブ内の「地図のダウンロード」ボタンで、画面キャプチャを取る。
3. 上記でダウンロードした画像を使ってフォームに申請する。

## 設定可能な項目

- title: ヘッダーに表示するタイトルを入力します。
- Iframe URL: ウィジェットに埋め込むフォームの URL を指定します。未入力の場合、フォームタブは非表示になります。
- 3Dmodel: クリック時に配置する 3D モデルを指定します。指定しない場合は、上記画像の 3D モデルが配置されます。
- 3Dmodel scale: 配置する 3D モデルの大きさのスケーリングファクターを指定します。デフォルトは 1 です。
- Theme color: ウィジェットボタンの色を指定します。設定しない場合は#00BEBE となります。
- Area color: Add Area で配置するエリアのカラーを指定します。未設定の場合、#00FF3880 になります。

## 注意

- あらかじめ申し込みフォームを作成しておく必要があります。(Google フォーム、Forms by Microsoft など)

# Location Reservation plugin

This is the plugin to register location.
This plugin has two features:
One is a drawing tool： Drawing a circle at any location, placing 3D model on the map, adding a label and taking a screen capture of the map shown on the screen.
Two is application form：to embed the existing application form.

## Use flow:

### Editor

1. Prepare to apply a form that is set the required item. (make this plugin useful, an image item is required)
2. Set the form link to the plugin Iframe URL property. (More settable properties are below)

### User

1. Draw the circle on a map where the user wants to use with the drawing tool tab.
2. Take a screen capture with the "Download map" button on the same tab.
3. User applies to a form using the image downloaded above.

## Configurable items

- Title: Enter the title to be displayed in the header.
- Iframe URL: Specify the URL of the form to be embedded in the widget. If not entered, the form tab will be hidden.
- 3D model： Specify the 3D model to be placed on click. If not specified, a model on the image above will be placed.
- 3D model scale： Specify the scaling factor of the size of the 3D model to be placed. The default is 1.
- Theme color: Specify the color of the widget buttons. If not set, it will be #00BEBE.
- Area Color: Specify the color of the area to be placed by Add Area. If not set, it will be #00FF3880.

## Caution

- You need to make an application form first with some tools. (eg, Google form, Forms by Microsoft, etc.)
