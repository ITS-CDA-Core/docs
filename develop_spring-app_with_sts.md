# STS(Spring Tool Suite)を利用したSpringBootアプリの開発

## STSのダウンロード

[STS公式サイト](https://spring.io/tools)より、最新のZipファイルをダウンロードする。

## STSの解凍・セットアップ

ダウンロードしたZipファイルを任意の場所に解凍。

(解凍先)\sts-bundle\sts-x.x.x.RELEASE\STS.exe
を実行。

![](./images/develop_spring-app_with_sts/WS000000.JPG)

workspaceは好きな場所またはデフォルトで良い。

![](./images/develop_spring-app_with_sts/WS000001.JPG)

(初期画面)

## SpringBootアプリのImport

![](./images/develop_spring-app_with_sts/WS000002.JPG)

「File」メニューから「Import」を選択。

![](./images/develop_spring-app_with_sts/WS000003.JPG)

「Maven->Existing Maven Projects」を選択し、「Next」をクリック。

![](./images/develop_spring-app_with_sts/WS000004.JPG)

「Root Directory」に、対象プロジェクトの「pom.xml」が含まれるフォルダを指定し、「Finish」をクリック。

![](./images/develop_spring-app_with_sts/WS000005.JPG)

「Package Explorer」に、Importしたプロジェクトが追加される。
初回Import時は、依存ライブラリのダウンロードが実行され、それが完了するまで正しく表示されない事がある。

## STSによるSpringBootアプリの起動

![](./images/develop_spring-app_with_sts/WS000006.JPG)

「Package Explorer」上のSpringBootアプリプロジェクトを右クリックし、
「Run As->Spring Boot App」を選択。

![](./images/develop_spring-app_with_sts/WS000007.JPG)

組み込みTomcatにアプリ配備の上起動される。
「Console」に「Started App in XXX seconds...」と表示されるまで待つ。

![](./images/develop_spring-app_with_sts/WS000008.JPG)

以上にてアプリが起動し、
ブラウザから[http://localhost:8080/](http://localhost:8080/)
にアクセスすることで、アプリを利用することができるようになる。
