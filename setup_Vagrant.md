# Vagrantのセットアップ手順

## セットアッププログラムのダウンロード

[Vagrant公式サイト](https://www.vagrantup.com/)より、最新版のVagrantセットアッププログラムをダウンロードする。

## セットアッププログラムの起動

ダウンロードしたセットアッププログラムを起動する。

![](./images/setup_Vagrant/WS000000.JPG)

「Next」をクリック。

![](./images/setup_Vagrant/WS000001.JPG)

「I accept the term in the License Agreement」にチェックを入れ、  
「Next」をクリック。

![](./images/setup_Vagrant/WS000002.JPG)

インストール先を指定し、「Next」をクリック。  
インストール先はデフォルトのままでも良いが、ここでは後続の説明上  
「C:\Vagrant」を指定したとする。

![](./images/setup_Vagrant/WS000003.JPG)

「Install」をクリック。

![](./images/setup_Vagrant/WS000004.JPG)

インストールが完了するまで待つ。

![](./images/setup_Vagrant/WS000005.JPG)

「Finish」をクリック。

![](./images/setup_Vagrant/WS000006.JPG)

再起動を促されるため、都合の良いタイミングで再起動を実施する。

## プラグインのインストール

### vagrant-omnibus

```bash
vagrant plugin install vagrant-omnibus
```

上記コマンドにて、プラグインをインストールする。

```bash
vagrant plugin list
```

インストールされたか／されているかは上記コマンドにて確認できる。
