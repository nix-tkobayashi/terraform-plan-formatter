# Terraform Plan Formatter

このリポジトリは、Terraform Planの出力を見やすく整形するWebツールです。

## このツールについて

- HCP Terraform（Terraform Cloud）を使っていなくても、あれに近い見やすいフォーマットでplan結果を確認したい方に最適です。
- HTML＋CSS＋JavaScriptのみで動作するため、ローカル環境でも安全・手軽にご利用いただけます。

## ファイル構成
- `index.html` : メインのHTMLアプリケーション（CSS・JSも内包）
- `README.md` : この説明ファイル

## 使い方
1. Terraform Planの出力のうち、
   ```
   Terraform will perform the following actions:
   ```
   から
   ```
   Plan: ... to add, ... to change, ... to destroy.
   ```
   までの範囲をコピーして、左側のテキストエリアに貼り付けてください。
2. 「Format Plan」ボタンを押すと、右側に整形された内容が表示されます。

---

- ご自由にご利用・カスタマイズください。
- Pages に公開してますので自由にご利用ください。

## 公開ページ
https://nix-tkobayashi.github.io/terraform-plan-formatter/

## 作者

- [\_\_\_nix___ on X (旧Twitter)](https://x.com/___nix___)
