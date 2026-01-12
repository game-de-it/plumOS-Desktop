# plumOS-Desktop
<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc05.jpeg" width="320"> <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc06.jpeg" width="320">   
<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc07.jpeg" width="320"> <img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc08.jpeg" width="320">   




plumOS-DesktopはdArkOSをベースに作られたCFWであり、Powkiddy RGB30専用に作られています。  
dArkOSはDebian Trixieをベースに作られたハンドヘルド用のOSです。  
[dArkOSについてはこちらを参照してください](https://github.com/christianhaitian/dArkOS)


## 注意事項
- このCFWを操作するには基本的なLinux知識が必要になりますので、ご自身で勉強したり調査したりして問題を解決してください
- 品質の高いSDカードを利用してください
- 速度の遅いSDカードを利用すると、OSの動作が不安定になる可能性があります
- デスクトップとEmulationstationの切り替え時にOSが不安定になることがあります
- 操作ができない状態になったらRGB30本体のリセットボタンを押すか、電源を長押しして強制的に電源OFFしてください
- 要望やそのほか不具合があるかも知れませんが基本的にはサポートはありませんので、ご自身で調べて解決してください
- このCFWについてdArkOSの作者に問い合わせをしないでください
- OTA機能を利用するとOS環境が破壊される可能性がありますので注意してください


## 特徴
- lightdmとLXQtで構成されたデスクトップ環境が利用できます
- ブラウザでyoutubeを視聴したり、音楽ファイルを再生できたりします
- マウス操作はRGB30のコントローラーを利用して操作できます
- USBマウス、USBキーボードに対応しています
  - OTGポートにUSB-HUBを接続すると便利です
- Emulationstationが利用できるためdArkOSがサポートするエミュレーターでゲームをプレイ可能です


## 操作方法
| Key operation | Explanation |
|:-----------|------------:|
| 左アナログスティック | マウスカーソル操作 |
| 右アナログスティックの上下 | 画面の上下スクロール|
| D-pad | 上下左右の画面スクロール、項目の移動など |
| R1ボタン | 左クリック |
| L1ボタン | 右クリック |
| L2+X | ソフトウェアキーボードの起動 |
| Aボタン | Enterキー |


## ログインユーザー情報
- ユーザ名は`ark`
- パスワードは`ark`
  - SSH接続などでこのユーザーが利用可能です


## Wifiの接続方法について
1. 画面上部のネットワークアイコンをクリックして`Available Networks`からSSIDを検索するか、`Create New Wi-Fi Network`からSSIDを手動で入力します
<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc04.jpeg" width="320">

2. コントローラーのL2+Xボタンを押すと上部パネルに`Onboard`アイコンが起動しますので、再度L2+Xボタンを押すとソフトウェアキーボードが起動します
<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc02.jpeg" width="320">
<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc03.jpeg" width="320">

3. SSIDやパスワードの入力が完了すると自動的に接続されますが、接続されない場合はOSを再起動してみてください


## Emulationstationへの切り替えとデスクトップ画面への切り替え方法
1. 画面上部の`ES`アイコンをクリックすることでESに切り替えが可能です(アイコンを連続でクリックしないでください)
<img src="https://github.com/game-de-it/plumOS-Desktop/blob/main/asset/sc01.jpeg" width="320">

2. Emulationstationからデスクトップ画面に切り替える場合は`Ports`セクションにある`Start_LXQt`を実行してください


## Dungeon Antiqua 2の起動方法について
1. SDカードの`roms/pyxel`ディレクトリに`dungeon-antiqua2.pyxapp`ファイルをコピーしてください
2. デスクトップ画面にある`dungeon-antiqua2.sh`をダブルクリックして`Execute`をクリックしてください
3. Emulationstationから起動する場合は、`Ports`セクションにある`dungeon-antiqua2`を実行してください


## その他の情報について
[詳しくはdArkOSのwikiを参照してください](https://github.com/christianhaitian/arkos/wiki/Frequently-Asked-Questions---RGB30)


















