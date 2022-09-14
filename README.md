# GitHub Actions CI/CD

## AWS CloudFormation
- テンプレート
  ```
  aws cloudformation validate-template --template-body file://./cloudformation/network.yml
  ```

- スタック作成
  ```
  aws cloudformation create-stack --stack-name phoo-stack --template-body file://./cloudformation/network.yml
  ```

- スタック削除
  ```
  aws cloudformation delete-stack --stack-name phoo-stack
  ```
