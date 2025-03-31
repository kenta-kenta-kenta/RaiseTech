# lecture03

## アプリケーションの起動画面

![app_start](images/lecture03/1_app_start.png)  
![app_start2](images/lecture03/2_app_start2.png)

## 1. APサーバーについて調べる

- 名前：Puma / バージョン：6.4.2  
![ap_name_ver](images/lecture03/3_application_server_name_and_version.png)

- APサーバーを終了させた場合、引き続きアクセスできるか？  
⇒できない。  
![ap_access](images/lecture03/4_accessibility_when_application_server_is_stopped.png)  
![ap_access2](images/lecture03/5_accessibility_when_application_server_is_stopped_2.png)

## 2. DBサーバーについて調べる

- 名前：MySQL / バージョン：8.4.4  
![DB_name_ver](images/lecture03/6_database_server_name_and_version.png)

- DBサーバーを終了させた場合、引き続きアクセスできるか？  
⇒できない。  
![db_access](images/lecture03/7_accessibility_when_database_server_is_stopped.png)

- Railsの構成管理ツールの名前は？  
⇒ Bundler  
![rails_configuration](images/lecture03/8_rails_configuration_management_tool.png)

## 本課題をとおして学んだこと

Cloud9/EC2インスタンスの仕様やできることの違い、ローカルPCから相対パスでの画像のアップロード⇒Markdownファイルへの埋め込みなど、つまづくポイントは多々あった。  
だいぶ時間を費やしてしまったものの、作業導線をしっかりと身につけることができた。
