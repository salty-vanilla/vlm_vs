# VLM_VS: Vision Language Models for Visial Inspection

## How to develop
基本的に以下のコマンドでshellに入った上で以下の作業をする
```
poetry shell
```
### 初めて動かすとき
```
poetry install
```
### python packageを追加するとき
```
poetry add <package_name>
```

## Scriptについて
### 学習
```
python scripts/train.py --config <config_path>
```
### 評価
```
python scripts/evaluate.py --config <config_path>
```
### ファインチューニング
```
python scripts/finetune.py --config <config_path>
```

