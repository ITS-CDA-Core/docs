# [Winのみ]コマンドライン版ssh・rsync（MinGW）のセットアップ手順

![](./images/setup_MinGW_ssh_and_rsync/WS000000.JPG)

「[www.mingw.org](http://www.mingw.org)」にアクセスし、右上の「Download Installer」ボタンをクリック。

![](./images/setup_MinGW_ssh_and_rsync/WS000001.JPG)

自動でダウンロードが開始されるファイルを保存する。

![](./images/setup_MinGW_ssh_and_rsync/WS000002.JPG)

保存したインストーラを起動し、初期画面にて「Install」をクリック。

![](./images/setup_MinGW_ssh_and_rsync/WS000003.JPG)

インストール先を指定し、「Continue」ボタンをクリック。
以下では、インストール先として「C:\MinGW」を指定したと仮定する。

![](./images/setup_MinGW_ssh_and_rsync/WS000004.JPG)

しばらく待つ。

![](./images/setup_MinGW_ssh_and_rsync/WS000005.JPG)

「Continue」ボタンがクリック可能になったらクリックする。

![](./images/setup_MinGW_ssh_and_rsync/WS000006.JPG)

左メニューの「All Packages->MSYS->MinGW Developer Toolkit」を選択し、
右上のリストから
・msys-openssh
・msys-rsync
のbin/doc/licを選択する。

![](./images/setup_MinGW_ssh_and_rsync/WS000007.JPG)

ウィンドウメニューの「Installation->Apply Changes」を選択する。

![](./images/setup_MinGW_ssh_and_rsync/WS000008.JPG)

表示されるダイアログにて、「Apply」ボタンをクリック。

![](./images/setup_MinGW_ssh_and_rsync/WS000009.JPG)

ダウンロード＆インストールが終了し、「Colse」ボタンがクリック可能になったらクリックする。

![](./images/setup_MinGW_ssh_and_rsync/WS000010.JPG)

システムのコントロールパネルを表示し、左メニューの「システムの詳細設定」をクリック。

![](./images/setup_MinGW_ssh_and_rsync/WS000011.JPG)

「環境変数」ボタンをクリック。

![](./images/setup_MinGW_ssh_and_rsync/WS000012.JPG)

システム環境変数「Path」を選択し「編集」ボタンをクリック。

![](./images/setup_MinGW_ssh_and_rsync/WS000013.JPG)

変数値の末尾に、「;」＋「MinGWのインストール先パス」＋「\bin」を追記する。
（「C:\MinGW」にインストールした場合、「;C:\MinGW\bin」を追記）

「OK」をクリックしていき、コントロールパネルを閉じて終了。
