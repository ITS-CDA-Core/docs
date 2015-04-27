# 開発リソース内のVagrantスクリプトの起動方法

![](./images/setup_VM_with_Vagrant/WS000000.JPG)

「Vagrantfile」が含まれるディレクトリ位置を確認する。    
ここでは仮に、「C:\Sync\GitHub\workshop_FY15」に配置されているケースを想定する。

![](./images/setup_VM_with_Vagrant/WS000001.JPG)

コマンドプロンプト（ターミナル）を起動し、    
「Vagrantfile」が含まれるディレクトリまで移動する。

![](./images/setup_VM_with_Vagrant/WS000002.JPG)

「vagrant up」と入力する。

![](./images/setup_VM_with_Vagrant/WS000003.JPG)

初回は、OSイメージのダウンロードが実行されるため時間がかかる。（初回のみ）    
根気よく待つ。

![](./images/setup_VM_with_Vagrant/WS000004.JPG)

「Report handlers complete」と表示されれば、起動完了。

![](./images/setup_VM_with_Vagrant/WS000005.JPG)

念のため、VMが起動しているか確認するには、「vagrant status」と入力する。    
「running」と表示されれば起動中である。
