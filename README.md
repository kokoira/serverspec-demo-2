# serverspec-demo-2
serverspec-demo-2は、Serverspecを使用して対象となるAWSのEC2インスタンス上でテストを自動で行います。  
# 使用技術
- ServerSpec
  - Ruby
- AWS
  - VPC
  - EC2
  - RDS
# 構成図
![serverspec-demo-2](https://user-images.githubusercontent.com/95961416/151158436-9f39ef17-ed9e-4336-b460-c01e46d63cef.png)
# 特徴
- テスト内容は、他リポジトリ「ansible-demo」の実行結果を確認するものとなっています。
- 他リポジトリ「serverspec-demo-1」と異なる点は、他リポジトリ「ansible-demo」を実行したテストする側のEC2インスタンスとは異なるEC2インスタンス・ユーザーアカウントからSSH接続して、テストされる側のEC2インスタンスにテストを実行していることです。
