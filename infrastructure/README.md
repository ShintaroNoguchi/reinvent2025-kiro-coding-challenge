# Infrastructure

AWS CDK を使用したインフラストラクチャコード

## セットアップ

```bash
cd infrastructure
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## デプロイ

```bash
cdk bootstrap  # 初回のみ
cdk deploy
```

## その他のコマンド

```bash
cdk synth      # CloudFormation テンプレートを生成
cdk diff       # 変更内容を確認
cdk destroy    # スタックを削除
```
