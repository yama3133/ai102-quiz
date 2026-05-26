# AI-102 Quiz

AI-102（Microsoft Azure AI Engineer Associate）認定資格試験対策の包括的な問題集アプリケーションです。200問以上の実務的な問題で、Azure AIエンジニアリングの知識を習得できます。

## 機能

- **200問以上の問題**: AI-102試験を網羅した充実した問題プール
- **複数の学習モード**:
  - 順番に回答: 体系的に段階的に学習
  - ランダム出題: ランダムな順序で問題演習
  - カテゴリー別: 特定のAzureサービスに絞った学習
  - 本番形式: 試験と同じ60問・時間制限での実践演習

- **カテゴリー別学習**: AI-102試験の主要なAzureサービスをカバー
- **詳細な解説**: 各問題に実務的な解説を付属
- **複数選択問題対応**: 複数の正解を選ぶ問題にも対応
- **進捗追跡**: スコア、正答率、進捗状況の管理
- **レスポンシブデザイン**: PC、タブレット、スマートフォンで利用可能

## 対象資格

**AI-102: Microsoft Azure AI Engineer Associate**

Azure AIを用いた実務的なエンジニアリングスキルの認定。以下の領域をカバーします：

- Azure Cognitive Services
- Azure Machine Learning
- Azure Form Recognizer
- Azure Bot Service
- Azure Search
- Vision API
- Language Services
- Speech Services

## 技術スタック

- **フレームワーク**: React 19.2.5
- **ビルドツール**: Vite 8.0.10
- **言語**: JavaScript (JSX)
- **スタイル**: CSS
- **開発**: ESLint対応

## インストール

```bash
npm install
```

## 開発環境の起動

```bash
npm run dev
```

ブラウザで http://localhost:5173 にアクセスしてください。

## ビルド

```bash
npm run build
```

## プレビュー

```bash
npm run preview
```

## コード品質チェック

```bash
npm run lint
```

## ファイル構成

```
src/
├── App.jsx              # メインアプリケーション
├── main.jsx             # React初期化
├── questions.js         # AI-102問題データベース（200+問）
├── App.css              # スタイル
└── assets/              # 画像・アイコン
public/
└── assets/              # 公開アセット
```

## カバーされるトピック

### Azure AI Services
- **Vision**: Computer Vision、Custom Vision、Face API
- **Language**: Text Analytics、Language Understanding、QnA Maker
- **Speech**: Speech-to-Text、Text-to-Speech
- **Decision**: Anomaly Detector、Content Moderator

### Azure Machine Learning
- ML Pipelines
- データ準備と前処理
- モデルの訓練と評価
- デプロイとモニタリング

### Azure Bot Service
- Bot Framework
- QnA Maker統合
- LUIS統合
- チャネル管理

### Azure Cognitive Search
- インデックス設計
- クエリ構文
- フィルターと facets
- アナライザーとトークナイザー

## 使い方

### 1. 学習開始
```
アプリを起動 → モードを選択 → 学習開始
```

### 2. モード別学習方法

#### 順番モード
体系的に基礎から応用へ。AIサービスの全体像を把握したい時に最適。

#### ランダムモード
本当の実力測定に。毎回異なる問題順で、安定した知識を確認。

#### カテゴリー別モード
特定分野の集中学習。Vision、Language、Speechなどのサービス別に深掘り可能。

#### 本番形式
試験と同条件で、60問・120分（または指定時間）での実練習。
正答率、スコアを確認して合格の可能性を判定。

## 学習のコツ

### 効率的な学習進め方
1. **初回**: 順番モードで全ドメインを確認
2. **弱点把握**: ランダムモードで苦手分野を特定
3. **重点学習**: カテゴリー別モードで弱点集中攻略
4. **最終確認**: 本番形式で総合力を測定

### 実務知識の習得
- **Azure公式ドキュメント参照**: 解説だけでなく、公式Docsで補足学習
- **実験**: Azureの無料枠を使った実践
- **試験テクニック**: 複数選択肢の消去法を意識

## AI-102試験について

### 試験フォーマット
- **出題数**: 40～60問
- **出題形式**: 単一選択、複数選択、ホットエリア
- **試験時間**: 120分
- **合格ライン**: 700点/1000点

### 受験対象者
- Azure AI Engineerを目指す者
- 機械学習・AI実装の経験者
- Azure Cognitive Services/ML経験者

## トラブルシューティング

### ローカルで実行できない場合
```bash
# Node.jsのキャッシュをクリア
rm -rf node_modules package-lock.json
npm install
npm run dev
```

### ブラウザでエラーが出る場合
- ブラウザのコンソール（F12）でエラーを確認
- キャッシュをクリア（Ctrl+Shift+Delete）
- 別のブラウザで試す

## ライセンス

MIT

## 作成者

[@yama3133](https://github.com/yama3133)

## 参考資料

- [Microsoft Learn: Azure AI Services](https://learn.microsoft.com/en-us/azure/ai-services/)
- [Microsoft Azure AI Engineer Associate 認定](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/)
- [Exam AI-102: Study Guide](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/)

## 最終更新

2026年5月
