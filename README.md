# 場所の予約申請ウィジェット

## このプラグインについて
このプラグインは、場所の予約申請をするためのプラグインです。
このプラグインは、地図上に任意の位置に円の描画・3D モデルの配置・ラベルを追加や、画面に表示された地図のスクリーンキャプチャを取ったりすることができます。
また、既存の申請フォームを埋め込むことが可能なので、上記でスクリーンキャプチャした画像を用いて、そのまま申請フォームへ回答することが可能です。

（※申請フォームを設定しないで使用することも可能です）


## 使用方法
### ウィジェット編集画面で設定可能な項目

- title: ヘッダーに表示するタイトルを入力します。
- Iframe URL: ウィジェットに埋め込むフォームの URL を指定します。未入力の場合、フォームタブは非表示になります
- 3Dmodel: クリック時に配置する 3D モデルを指定します。指定しない場合は、上記画像の 3D モデルが配置されます
- 3Dmodel scale: 配置する 3D モデルの大きさのスケーリングファクターを指定します。デフォルトは 1 です
- Theme color: ウィジェットボタンの色を指定します。設定しない場合は#00BEBE となります
- Area color: Add Area で配置するエリアのカラーを指定します。未設定の場合、#00FF3880 になります


### 各機能について

1. エリアを追加する：  
描画ツールタブ内「エリアを追加する」ボタンで、**地図上の任意の場所に円を描画し指定**
2. 3Dモデルを追加する：  
描画ツールタブ内「3D モデルを追加する」ボタンで、**地図上の任意の場所に 3D モデルを追加**
3. テキストを追加する：  
描画ツールタブ内「テキストを追加する」ボタンで、**地図上の任意の場所にテキストを追加**
4. 地図画面のダウンロード：  
描画ツールタブ内「地図画面のダウンロード」ボタンで、**画面キャプチャを取りダウンロード**
5. フォームの表示：  
申し込みフォームタブで、既存のフォームの表示（※編集画面で Iframe URL を設定した場合）

![](https://eukarya-inc.github.io/reearth-plugin-location-reservation/src/img1.png)

### 各機能の利用方法

#### 1. エリアを追加する

a. 「エリアを追加する」ボタンをクリック  
b. 地図上の任意の位置をクリック

##### ※指定エリアのサイズ変更

- 円追加時に左サイドバーに出てきたアイテムの、スライダーを調整する

##### ※指定エリアの削除

- 追加したエリアを削除する場合はゴミ箱アイコンをクリック

![](https://eukarya-inc.github.io/reearth-plugin-location-reservation/src/img2.png)

#### 2. 3Dモデルを追加する

a. 「3D モデルを追加する」ボタンをクリック  
b. 地図上の任意の位置をクリック  

![](https://eukarya-inc.github.io/reearth-plugin-location-reservation/src/img3.png)

#### 3. テキストを追加する

a. 「テキストを追加する」ボタンをクリック  
b. 地図上の任意の位置をクリック  
c. テキスト追加時にに左サイドバーに出てきたアイテムの、入力フォームに任意のテキストを入力する

![](https://eukarya-inc.github.io/reearth-plugin-location-reservation/src/img4.png)

#### 4. 地図画面のダウンロード

a. 画面キャプチャを取りたい任意の位置に移動  
b. 「地図画面のダウンロード」をクリック。使用端末のダウンロードフォルダに画面キャプチャがダウンロードされます  
   （※「地図画面のダウンロードボタン」で保存される画像には、インフォボックスやウィジェットの内容は含まれません）
   
![](https://eukarya-inc.github.io/reearth-plugin-location-reservation/src/img5.png)

#### 5.フォームの表示

a. 必須項目を設定した申請フォームを用意する。(このプラグインを有効に使うには、画像項目が必要です）  
b. 右パネルのウィジェット編集画面からフォームのリンク先をプラグインの Iframe URL プロパティに設定

![](https://eukarya-inc.github.io/reearth-plugin-location-reservation/src/img6.png)


### 留意点

- このプラグインを有効に活用していただくには、申込フォームを設定をお勧めします
- 申し込みフォームを埋め込む場合は、あらかじめフォームを作成しておく必要があります。(Google フォーム、Forms by Microsoft など)
- 編集ページにおいて右パネルで設定を変更を行なった場合は、一度ページをリフレッシュしないと変更が反映されません。右パネルで設定を変更した場合は一度ページを更新してください。

## 備考

このプラグインは、以下のOS,ブラウザで動作確認をしています。

- OS
  - Mac OS

- ブラウザ
  - Chrome: 107.0.5304.110
  - Safari: 16.0 (17614.1.25.9.10, 17614)
  - FireFox: 107.0
  - Edge: 107.0.1418.56

## 開発者欄

このプラグインは、Re:Earth公式プラグインです。

 ![](https://eukarya-inc.github.io/reearth-plugin-shinsuiNavi/src/logo-3.png)

ソースコードはこちら(https://github.com/eukarya-inc/reearth-plugin-location-reservation)

- コミュニティ

  - このプラグインを利用したプロジェクトをユーザーコミュニティでシェアしましょう。

  - このプラグインについての不明点がある場合にもここからRe:Earthチームや他の開発者に質問することができます。

  - Discordへのリンクはこちら(https://discord.gg/BXcQhvwqqM)

*****


# Location Reservation plugin

## About this
This is the plugin to register location.
This plugin has two features:
One is a drawing tool： Drawing a circle at any location, placing 3D model on the map, adding a label and taking a screen capture of the map shown on the screen.
Two is application form：to embed the existing application form.

## How to use
### What you can do on the Editor page

- Title: Enter the title to be displayed in the header.
- Iframe URL: Specify the URL of the form to be embedded in the widget. If not entered, the form tab will be hidden.
- 3D model： Specify the 3D model to be placed on click. If not specified, a model on the image above will be placed.
- 3D model scale： Specify the scaling factor of the size of the 3D model to be placed. The default is 1.
- Theme color: Specify the color of the widget buttons. If not set, it will be #00BEBE.
- Area Color: Specify the color of the area to be placed by Add Area. If not set, it will be #00FF3880.
  

### About each function

1. Draw area
2. Draw 3D model
3. Draw Text
4. Download image
5. form (when you have entered the Iframe URL on Editor page)

![](https://eukarya-inc.github.io/reearth-plugin-location-reservation/src/img1.png)





## Caution

- If you want to embed the apply form, you need to make an application form first with some tools. (eg, Google form, Forms by Microsoft, etc.)
- If you change settings in the right panel on the edit page, you must refresh the page once for the changes to take effect. Please refresh the page once when you change the settings in the right panel.
- The image saved by the "Download button on the map screen" does not include the contents of infoboxes and widgets. 
