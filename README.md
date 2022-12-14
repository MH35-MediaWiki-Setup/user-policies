# user-policies
MediaWikiで使うIAMユーザ用のポリシー

## 使い方

1. `aws cloudformation deploy --template-file formation.yml --stack-name [your stack name] --capabilities CAPABILITY_IAM --parameter-overrides BucketName=[upload bucket name] SendIdentity=[sender identity ARN]`する
2. デプロイ完了まで待つ
