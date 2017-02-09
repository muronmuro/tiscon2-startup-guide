# Windowsマシンの開発TIPS

## コマンドプロンプトの起動方法

コマンドプロンプトとは、いわゆる「黒い画面」です。

環境構築手順において、時々コマンドプロンプトからコマンドを実行する必要があります。
コマンドプロンプトは、以下の手順で起動できます。

`スタート` > `すべてのプログラム` > `アクセサリ` > `コマンドプロンプト`を選択

環境変数の編集時などは、コマンドプロンプトを再起動しないと設定が反映されません。
コマンドの実行結果が想定通りでない場合、一度コマンドプロンプトを再起動してみてください。

## 環境変数「Path」の編集

**環境変数の「Path」を編集する場合、もともと記載されている設定は消さないでください！**

消すとPCが動かなくなる場合がありますので、必要な設定の**追記**のみ行ってください。
問題が発生した時に作業前の状態に戻せるよう、環境変数を編集する際は、**編集前の値をテキストファイル等にバックアップ**しておいてください。
設定を追記する際は、既存の値と新しく設定する値の間を`;`で区切ってください。