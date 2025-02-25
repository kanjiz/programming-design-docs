# Java実装ガイドライン

このディレクトリにはJavaプログラミング実習における実装の標準パターンやベストプラクティスをまとめています。

## ガイドライン一覧

### 入出力処理

- [コンソール入出力の実装](./console-io-guide.md)
  - 標準入力からの読み取り
  - プラットフォーム非依存の文字セット処理
  - try-with-resourcesパターン

### 言語機能

- [拡張for文の実装](./enhanced-for-loop-guide.md)
  - 従来のfor文との比較
  - 適切な使用場面
  - 実践的なコード例
  - Stream APIによる発展的な使用法

### 文字列処理

- [String.formatted()の実装](./string-formatted-guide.md)
  - 文字列フォーマットの新しい方法
  - 数値や日付のフォーマット
  - 位置揃えと桁区切り
  - エラー処理とベストプラクティス

- [文字列検証の実装](./string-validation-guide.md)
  - null値と空文字列の検証
  - 拡張for文による検証処理
  - Stream APIを使用した検証
  - 実践的な検証パターン

### 今後追加予定

- ファイル入出力の実装
- ネットワーク入出力の実装
- データベース接続の実装

## 使用方法

1. 各ガイドラインはスタンドアロンの文書として機能
2. コード例は完全な形で提供（インポート文含む）
3. 実装時のベストプラクティスとして参照

## 注意事項

- これらのガイドラインは実装の参考としてください
- より良い実装方法がある場合は適宜アップデートされます
- 特定の課題向けではなく、一般的な実装パターンとして提供
- 各ガイドラインには必要なバージョン要件が記載されています
