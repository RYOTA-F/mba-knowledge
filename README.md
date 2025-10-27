# MBA Knowledge Base

## 概要

このリポジトリは、MBA で学ぶ主要なフレームワークや概念を体系的にまとめた知識ベースです。ビジネス戦略、マーケティング、ファイナンス、オペレーション、リーダーシップなど、MBA コアカリキュラムで扱われる重要なトピックを、実務で活用できる形で整理しています。

## 目的

- **学習の効率化**: MBA 学習内容を一元管理し、復習や参照を容易にする
- **知識の体系化**: 個別の概念を構造的に整理し、相互の関連性を理解する
- **実務への応用**: フレームワークの実践的な活用方法を明確にする
- **チーム内での共有**: 組織内での MBA 知識の共通言語化を促進する

## リポジトリ構造

```
mba-knowledge/
├── docs/
│   └── courses/
│       └── [コースID]/           # コース別ディレクトリ（例: 18_TVB）
│           └── framework.md      # フレームワークドキュメント
├── images/                       # 図表・画像ファイル（ルートレベル）
│   └── frameworkname.png
├── CLAUDE.md                     # Claude Code用の開発ガイド
└── README.md                     # このファイル
```

**実際の構造例:**
```
mba-knowledge/
├── docs/
│   └── courses/
│       └── 18_TVB/               # Thought-Value-Behaviorコース
│           └── business_model_canvas.md
├── images/
│   └── businessmodelcanvas.png
├── CLAUDE.md
└── README.md
```

### ディレクトリ構成

- **docs/courses/**: コース別に MBA フレームワークを整理
  - 各コースディレクトリ内に、トピック別のマークダウンファイルを配置
- **images/**: ドキュメントで使用する図表やビジュアル素材
  - フレームワークの構造図、プロセスフロー、概念図など

## 収録コンテンツ

### 18_TVB（Thought-Value-Behavior）

> **コース識別子**: 18_TVB | **ドキュメント数**: 18

テクノベート時代のビジネスモデル設計を学ぶコース。価値提案、マーケティング、価値提供の仕組み、利益モデルの4要素を軸に、価値共創、エコシステム、自己強化ループといったテクノベート特有の概念を組み込んだビジネスモデルの構築方法を体系的に学習します。

📖 **[コース詳細を見る](docs/courses/18_TVB/README.md)**

#### 📊 ビジネスモデルのフレームワーク（4）

| トピック | 概要 | ファイル |
|---------|------|---------|
| ビジネスモデルキャンバス | 9つのブロックでBM全体を可視化する標準的フレームワーク | [business_model_canvas.md](docs/courses/18_TVB/business_model_canvas.md) |
| BCG流ビジネスモデル | バリュープロポジションとオペレーション・モデルの2軸で整理 | [bcg_business_model.md](docs/courses/18_TVB/bcg_business_model.md) |
| 4つの箱モデル | 競合比較やBM変革の検討に適したシンプルなフレームワーク | [four_boxes_model.md](docs/courses/18_TVB/four_boxes_model.md) |
| 新たな課金対象の見つけ方 | 費用負担者・課金対象・価格・タイミングの4変数によるマネタイズ革新 | [monetization_strategies.md](docs/courses/18_TVB/monetization_strategies.md) |

#### 🔄 テクノベート特有の概念（4）

| トピック | 概要 | ファイル |
|---------|------|---------|
| サービス・ドミナント・ロジック | GDロジックからSDロジックへ、価値共創パラダイムの理解 | [service_dominant_logic.md](docs/courses/18_TVB/service_dominant_logic.md) |
| ビジネスエコシステム | 多様なアクターとの協業による価値創造の仕組み | [business_ecosystem.md](docs/courses/18_TVB/business_ecosystem.md) |
| 自己強化のメカニズム | ネットワーク効果とデータフライホイールによる競争優位の構築 | [self_reinforcing_mechanism.md](docs/courses/18_TVB/self_reinforcing_mechanism.md) |
| プラットフォームのユニットエコノミクス | 媒介型PFにおけるPMFとUE健全化のタイムラグと対策 | [platform_unit_economics.md](docs/courses/18_TVB/platform_unit_economics.md) |

#### 👥 顧客理解とマーケティング（6）

| トピック | 概要 | ファイル |
|---------|------|---------|
| 顧客理解 | ジョブ理論、ペルソナ、カスタマージャーニーによる深い顧客理解 | [customer_understanding.md](docs/courses/18_TVB/customer_understanding.md) |
| 顧客循環型の態度変容モデル | AISAS、AISCEAS、コトラー5Aモデルの比較と活用 | [customer_behavior_models.md](docs/courses/18_TVB/customer_behavior_models.md) |
| 市場ポテンシャル | TAM、SAM、SOMによる市場規模の3段階評価手法 | [market_potential.md](docs/courses/18_TVB/market_potential.md) |
| リテンション・マーケティング | 継続率×顧客単価による優先順位付けの数学的根拠とCRM戦略 | [retention_marketing.md](docs/courses/18_TVB/retention_marketing.md) |
| リテンション戦略と顧客セグメントのバランス | ヘビーユーザー偏重のリスクとバランスの取れたポートフォリオ戦略 | [retention_strategy.md](docs/courses/18_TVB/retention_strategy.md) |
| 国内モバイルゲーム市場 | 日本のモバイルゲーム市場の特徴と競争環境の分析 | [mobile_game_market.md](docs/courses/18_TVB/mobile_game_market.md) |

#### 🎯 事業機会の探索と評価（3）

| トピック | 概要 | ファイル |
|---------|------|---------|
| 課題の選択基準 | 取り組むべき課題の妥当性を評価する7つの基準と優先順位付け | [problem_selection_criteria.md](docs/courses/18_TVB/problem_selection_criteria.md) |
| 初期段階のビジネスモデル開発 | MVPとアジャイル開発による仮説検証型BM構築プロセス | [early_stage_bm_development.md](docs/courses/18_TVB/early_stage_bm_development.md) |
| プレモーテム | 失敗シナリオを事前想定し、リスクを特定・対策する手法 | [premortem.md](docs/courses/18_TVB/premortem.md) |

#### 📚 学習のまとめ（1）

| トピック | 概要 | ファイル |
|---------|------|---------|
| Day2 Key Takeaway | 価値共創、マネタイズ、ユニット・エコノミクスの要点整理 | [day2_key_takeaway.md](docs/courses/18_TVB/day2_key_takeaway.md) |

## ドキュメント形式

各フレームワークのドキュメントは、以下の構成で記述されています：

1. **タイトル**: フレームワーク名（日本語）
2. **図表**: フレームワーク全体像を示す画像（`../../../images/`から参照）
3. **概要セクション**: フレームワークの定義、提唱者、出典、目的
4. **構成要素**: フレームワークを構成する各要素の詳細説明
   - 英語の原語表記を併記（例: `顧客セグメント (CS: Customer Segments)`）
5. **活用方法**: 実務での適用シーン（該当する場合）

## 使い方

### ドキュメントの閲覧

1. `docs/courses/` 以下のディレクトリから、目的のコースを選択
2. 各マークダウンファイルを開いて内容を確認
3. 画像はマークダウンビューアーで自動表示されます

### 新しいフレームワークの追加（既存コース内）

1. 適切なコースディレクトリに移動：`docs/courses/[コースID]/`
2. 新しいマークダウンファイルを作成
   - ファイル名は内容を表す英語名を使用（小文字、アンダースコア区切り）
   - 例: `swot_analysis.md`, `value_chain.md`
3. 以下のテンプレートに従ってドキュメントを作成：

```markdown
# [フレームワーク名（日本語）]

![フレームワーク名](../../../images/filename.png)

## 概要

[フレームワークの説明、提唱者、発表年など]

## [主要な要素やセクション]

[詳細な説明]
```

4. 必要な図表はルートの `images/` ディレクトリに配置
5. このREADME.mdの「収録コンテンツ」セクションに追加したフレームワークを記載

### 新しいコースの追加

1. `docs/courses/` 配下に新しいコースディレクトリを作成
   - 命名規則: `[番号]_[略称]/` （例: `19_SM/` for Strategic Management）
2. コースディレクトリ内にフレームワークのマークダウンファイルを追加
3. このREADME.mdに新しいコースセクションを追加（収録コンテンツ内）

### 画像の追加

1. PNG 形式を推奨（図表やスクリーンショット）
2. ファイル名は内容を表す小文字英語名（例: `businessmodelcanvas.png`, `swotanalysis.png`）
3. ルートレベルの `images/` ディレクトリに配置
4. マークダウンから相対パスで参照：`![説明](../../../images/filename.png)`
   - `../../../` はコースディレクトリ（`docs/courses/[コースID]/`）からルートへのパス

## 貢献方法

このナレッジベースへの貢献を歓迎します：

1. **新しいフレームワークの追加**: 学習した内容を文書化して追加
2. **既存ドキュメントの改善**: 説明の明確化、図表の追加、誤字修正
3. **実務事例の追加**: フレームワークの実践的な活用例を共有

## ライセンス

このリポジトリは教育目的で作成されています。記載されているフレームワークは、各提唱者・著者の知的財産であることをご留意ください。
