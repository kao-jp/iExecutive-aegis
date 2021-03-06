# aegis @ iExecutive

改ざん防止文書管理システム

## Project

| 項目 | 明細 | 備考 |
| --- | --- | --- |
| 開始日| 2018/4/xx | |
| ステータス| 準備中 | 第二回ソーシャルハックデイに向けて鋭意作業中 |
| |  | |

## GOAL

- ドキュメントの更新・承認履歴をブロックチェーン上で管理
- 公開ドキュメントにハッシュと同様にブロックチェーン上のトランザクションを紐付け、ドキュメントに権威づけする。
- 管理ブロックチェーンの見える化

## subsystems

aegisは以下のサブシステムから構成される。ただし、全て新規に作るのではなく、既存のOSSなどで要件に合致
するものがあれば最大限活用する。

- history ledger : 更新・承認履歴台帳
- workflow : ドキュメント処理
- document repository : 文書保管
- document manager : 見える化

## sub projects

1. [文書管理システム](https://www.dev.iexecutive.org/)(ここ)
1. [Ethereumを用いてブロックチェーンの機能・実装方法の検証](https://github.com/i-executive/inspect-ethereum)

## TODO

- [x] 開発者向けサイト作成 GitHub Pages
- [x] DNS設定 www.dev.iexecutive.org を　”A” レコードで登録する
- [ ] aegisの基本アーキテクチャの作成
- [ ] ブロックチェーンの試作  
  * ブロックチェーンのデータ構造とaegisのデータ構造のマッピングドラフトを作成
- [ ] private blockchainの動作環境の構築  
  * azure VMに構築
   
## 検証環境
[検証環境](environments.md)

aesisの評価用のネットワークを構築している。VPNで接続して利用する。

## メンバー

  [メンバー一覧](members.html)
