# AWS利用の際、読むもの・やること

* [AWS クラウドサービス活用資料集](https://aws.amazon.com/jp/aws-jp-introduction/)

## 参考文献
* [[AWS] AWS IAM ベストプラクティスのご紹介 – AWSアカウントの不正利用を防ぐために](https://aws.amazon.com/jp/blogs/news/aws-iam-best-practice/)
* [[AWS] IAM のベストプラクティス](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/best-practices.html)
* [[Qiita] AWSアカウントを取得したら速攻でやっておくべき初期設定まとめ](https://qiita.com/tmknom/items/303db2d1d928db720888)

* https://www.youtube.com/watch?v=_wiGpBQGCjU
  * https://www.slideshare.net/AmazonWebServices/sec302-iam-best-practices-to-live-by
* https://www.youtube.com/watch?v=suBsFAEJUIc
  * https://www.slideshare.net/AmazonWebServices/gpstec310iam-best-practices-and-becoming-an-iam-ninja
* https://www.youtube.com/watch?v=SGntDzEn30s
  * https://www.slideshare.net/AmazonWebServices/aws-reinvent-2016-iam-best-practices-to-live-by-sac317



## やること

### Git Secretsを利用する

```bash
# https://github.com/awslabs/git-secrets
$ brew install git-secrets
# Set git hook
$ git secrets --install
# Adds common AWS patterns
$ git secrets --register-aws
```

## ルートユーザーを利用しない(アクセスキーをロックする)
### MFA有効化

## IAMユーザー作成

### MFA有効化

## IAMグループを作成する（管理者、開発者など)
便利だから。

## パスワードポリシーを強力にする
https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/id_credentials_passwords_account-policy.html

## EC2インスタンスにIAMロールつける

## AWS アカウントのアクティビティの監視
CloudTrailなど
