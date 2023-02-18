multihoming-sample
---

# 概要

複数のネットワークインターフェースが存在するときに通信プロトコルによって使用するネットワークインターフェースを切り替えるサンプル環境。

# 依存

- vagrant
- virtualbox

# 手順

## 仮想マシン構築

```
git clone https://github.com/n-hachi/multihoming-sample.git
cd multihoming-sample
vagrant up
```
vagrant up実行中にネットワークインターフェースをブリッジネットワークとして使うか聞かれる可能性がある。
その場合はホスト側のデフォルトゲートウェイに設定されているネットワークインターフェースを選択する。

## 仮想マシン接続
```
vagrant ssh
```
