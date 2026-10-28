# ECC_sample

このリポジトリは、楕円曲線暗号（ECC: Elliptic Curve Cryptography）の仕組みや演算、実装サンプルをまとめたプロジェクトです。

## 概要

楕円曲線暗号は、短い鍵長でありながらRSA暗号と同等以上の高い安全性を持つことから、近年の暗号通信（TLSや暗号資産など）で広く利用されている公開鍵暗号方式です。

当リポジトリでは、楕円曲線上の基本的な演算や、安全性を支える数学的背景について理解することを目指しています。特に、暗号の根幹となる **「点のスカラー倍算（Point Doubling & Point Addition / 点の2倍算と加算）」** などの幾何学的・代数的な仕組みに焦点を当てています。

より詳細な数学的解説や理論的な背景については、以下の外部ノートもあわせてご覧ください：
- [暗号についての詳しい解説（doublePoint.md）](https://github.com/yabusan2-dot/technical-essays-notes/blob/main/doublePoint.md)

## 特徴

- **幾何学的・代数的アプローチ:** 楕円曲線上の点がどのように加算・倍算されるのか、直感的なアルゴリズムの流れを整理。
- **シンプルな実装:** ECCの根幹をなす演算の仕組みを把握しやすいコード構成。

## 使い方・ファイル構成

- `README.md`: 本ドキュメント
- 

## ライセンス

This project is open source under the [MIT License](LICENSE).
