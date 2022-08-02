# トーナメント自動作成アプリ ATCA(Automatic Tournament Creation App) 

## 概要 Overview
これはトーナメントを自動で作成するWindowsフォームアプリケーションです．
選手リストを登録して，あとはボタンを押すだけで自動でシード権の分配からトーナメントの作成まで行います．

This is a Windows forms application that automatically creates tournaments.
Simply register the list of players and press a button to automatically distribute seeding rights and create the tournament.

## 使い方 Usage
### ダウンロード＆インストール Download&Install
本ページ右上の緑色のボタン「Code」をクリックしたあと，「Download ZIP」をクリックします．<br>
ZIPを解凍したあとは，Tournamentフォルダ下に日本語版（Japannese）と英語版（English）があるので，言語に応じて適切なフォルダを開いてください．<br>
「setup.exe」をクリックするとインストーラーが起動するので，指示に従ってインストールを完了させてください．

Click the green button "Code" in the upper right corner of this page, then click "Download ZIP".<br>
After unzipping the ZIP, open the appropriate folder for the language you are using, as there are "Japanese" and "English" folders under the Tournament folder.<br>
Click "setup.exe" to start the installer and follow the instructions to complete the installation.

### 選手リストの登録，対戦形式の選択
登録したい選手名，レベル，ランキングを入力します．レベル，ランクの入力が必要無い場合は「0」を入力してください．(何も入力しないとエラーが発生します)<br>
対戦形式は「完全ランダム」，「レベルを考慮する」，「ランキングを考慮する」の3種類あります．それぞれの対戦形式の詳細は以下の通りです．
- 完全ランダム
  - レベルやランキングを考慮せず，対戦相手がランダムなトーナメントを作成します．
  - この項目の上限人数はありません．

- レベルを考慮する
  - プレイヤーのレベルを降順で並べたあと，レベルが高い人が有利になるようにトーナメントを作成します．
  - この項目の上限人数は32人です．

- ランキングを考慮する
  - プレイヤーのランキングを昇順で並べたあと，ランキングが高い人が有利になるようにトーナメントを作成します．
  - この項目の上限人数は32人です．
