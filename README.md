# ec2-instance-managed-by-ssm-with-projen

- SSM で管理するプライベートネットワークのインスタンスを作成する

## Init project with `projen`

```bash
npx projen new awscdk-app-ts
```

## 事前準備

```sh
export AWS_ACCESS_KEY_ID=
export AWS_SECRET_ACCESS_KEY=
export AWS_DEFAULT_REGION=
```

## ビルド

```sh
npx projen build
```

- アプリケーションのビルド
- CloudFormation テンプレートの生成
- テストとリンターの実行

## インフラストラクチャの作成

```sh
npx projen deploy
```

### インフラストラクチャの削除

```sh
npx projen destroy
```
