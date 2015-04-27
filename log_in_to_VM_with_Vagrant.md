# 起動した仮想環境へのログイン方法

![](./images/log_in_to_VM_with_Vagrant/WS000000.JPG)

VMが起動した状態で、「Vagrantfile」が配置されているディレクトリにて、    
「vagrant ssh」と入力する。

![](./images/log_in_to_VM_with_Vagrant/WS000001.JPG)

しばらく待つと、VM内にSSH接続された状態となる。    
この状態での入力は、VM上のシェルに対する命令となる。

![](./images/log_in_to_VM_with_Vagrant/WS000002.JPG)

試しに「pwd」を入力した状態。    
確かにVM上の現在位置が表示される。
