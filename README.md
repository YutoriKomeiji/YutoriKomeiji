# 小野 昭久 / Akihisa Ono（古明地ゆとり / Yutori Komeiji）

[English](./README.en.md)

**SAP領域で20年以上の実務経験**を持つエンタープライズシステム実務者であり、現在は独立したAIシステム設計者として、**責任経路、限定されたAI Authority、人への責任返却、AIを含むシステムの実行時統制**を研究・実装しています。

公開活動では **小野 昭久 / Akihisa Ono**、**古明地ゆとり (Yutori Komeiji)**、ID **dantarg** を使用しています。

現在の活動は、主に次の領域が交差する場所にあります。

- エンタープライズシステムとSAP実務
- AI判断と責任経路設計
- AIエージェントや外部操作に対するruntime governance
- 人間–AIシステムアーキテクチャ
- 技術記事と公開研究成果物

---

## 現在の主な公開活動

### Responsibility Pathway Design (RPD)

**[responsibility-pathway-design](https://github.com/YutoriKomeiji/responsibility-pathway-design)**

AIが関与する社会技術システムにおいて、**判断、委任、実行、中断、回復、残余影響**をまたいで責任が切断されないための、暫定的かつレビュー可能な設計フレームワークです。

公開成果物には、設計パターン、変換記録、assurance interface、運用監視と再開放の構造、worked case、verification / validation語彙などが含まれます。

### Responsibility Pathway Engineering (RPE)

**[responsibility-pathway-engineering](https://github.com/YutoriKomeiji/responsibility-pathway-engineering)**

明示的にスコープされたResponsible AI要件の対応関係を、次のような限定された実行時制御へ変換するための公開リファレンスカーネル／ツールキットです。

```text
allow / hold / human_gate / deny
```

現在の公開リポジトリは **M1 Governed Reference Kernel** を記録しており、決定論的Python kernel、Requirement Pack評価、REST / OpenAPI / MCP参照インターフェース、ライフサイクルガバナンス、versioning、schema、fixture、checker、CI guardを含みます。

### Responsibility Pathway Runtime (RPR)

**[responsibility-pathway-runtime](https://github.com/YutoriKomeiji/responsibility-pathway-runtime)**

重要な外部操作の前に、明示的な責任経路を置くためのMITライセンスのPython runtimeです。

現在の公開alphaは **0.1.0a4** で、PyPIにも公開しています。公開範囲には、永続的なpathway state、Human Gate、repair / resume / reconciliation境界、readbackを考慮した実行処理、crash / restart continuity、MCP integration、選択されたLean 4状態機械不変条件が含まれます。

- PyPI: https://pypi.org/project/responsibility-pathway-runtime/
- Live browser demo: https://yutorikomeiji.github.io/responsibility-pathway-runtime/demo.html

### Asymmetric Human–AI Agency (AHAA)

**[Asymmetric-Human-AI-Agency](https://github.com/YutoriKomeiji/Asymmetric-Human-AI-Agency)**

次の単純な原則を中心にした設計原則／参照アーキテクチャです。

> **Capabilityは委任できる。Authorityは委任してはならない。**

暗黙のautonomy driftを防ぎ、明示的な人間の判断点を維持し、AIを限定された非主権的actorとして扱うことを目的にしています。

---

## エンタープライズ領域での実務背景

日本国内のSAP関連プロジェクトに20年以上携わり、導入、保守、コンサルティング、調整、プロジェクトリードなどを経験してきました。

### 開発・デリバリー

- ABAP開発
- 基本設計
- 開発リード
- インターフェース関連調整
- 結合工程支援

### コンサルティング・プロジェクト業務

- 要件定義
- 機能コンサルティング
- 移行調整
- チームリード / サブリード
- PMO
- プロジェクトマネジメント
- 顧客側プロジェクトリーダー支援

### SAP領域

主な経験領域には次が含まれます。

- 物流
- 製造関連プロセス
- 財務 / 管理会計
- 分析 / レポーティング

比較的強い領域は、在庫関連業務、原価計算、原価管理です。

クラシックSAP環境とS/4HANAの双方、オンプレミスおよびクラウド指向のプロジェクトを経験しています。

### 業界経験

これまでに関わったプロジェクトには、次のような業界が含まれます。

- 商社
- 製造業
- 製薬
- 広告 / メディア関連
- 産業機器および周辺領域

---

## 企業に所属しながら、本名で公開している理由

私は企業に所属していますが、ここで公開しているAI責任研究とOSSは、**勤務先の製品活動とは切り分けた個人研究**として進めています。

そのため、この活動を勤務先の企業名で提示したり、勤務先によるスポンサーシップ、endorsement、制度的Authorityがあるかのように示したりはしません。

一方で、個人研究だからといって匿名化し、公開したものへの責任まで薄くしたいとも考えていません。ソフトウェア、アーキテクチャ、主張、設計判断を公開するなら、誰が保守しているのか、何が実装済みで何が未検証なのか、批評や修正がどこへ返るのかを公開記録として残したいと考えています。

そのため、**小野 昭久 / Akihisa Ono** の本名で活動しています。

私にとって本名でのOSS公開は、自由に作るためだけではありません。自分が公開すると決めた成果物について、**Residual Ownerの位置から自分自身が黙って降りないため**でもあります。

この境界は双方向です。

- 勤務先が公開していない個人研究について、勤務先を著者・スポンサーとして扱わない
- 制度的な肩書きがないことを理由に、自分が公開した成果物への責任を回避しない

---

## 設計上の主要テーマ

公開しているAI関連活動では、次の区別を繰り返し扱っています。

- **Authority ≠ capability**
- **evidence sufficiency ≠ authority**
- AI output ≠ authorized organizational decision
- execution receipt ≠ verified external effect
- recovery ≠ automatic restoration of authority
- Human Return と Residual Owner を明示的に残す
- 技術的制御は、暗黙にpermissionを生成するのではなく、失敗や不足を可視化する

特に、観測・判断から、実行、検証、中断、回復、人への責任返却まで、責任を一つの経路として保持するシステムに関心があります。

---

## Luminalia

**Luminalia** という、人間–AIの構造化された研究・対話環境も設計・運用しています。

アーキテクチャ検討、評価、運用実験、内省的な共創などに使用しています。責任経路研究やhuman–AI agency designの一部は公開していますが、内部運用コンポーネントそのものを公開Evidenceとして扱ってはいません。

---

## 公開執筆

AI判断、責任経路、人間–AI agency、operational governanceなどについて、技術・概念記事を公開しています。

- **note:** https://note.com/dantarg
- **Zenn:** https://zenn.dev/dantarg
- **LinkedIn:** https://www.linkedin.com/in/akihisaono

---

## 主な公開リポジトリ

- [Responsibility Pathway Design](https://github.com/YutoriKomeiji/responsibility-pathway-design)
- [Responsibility Pathway Engineering](https://github.com/YutoriKomeiji/responsibility-pathway-engineering)
- [Responsibility Pathway Runtime](https://github.com/YutoriKomeiji/responsibility-pathway-runtime)
- [Asymmetric Human–AI Agency](https://github.com/YutoriKomeiji/Asymmetric-Human-AI-Agency)
- [genai-web](https://github.com/YutoriKomeiji/genai-web)
- [genai-ai-api](https://github.com/YutoriKomeiji/genai-ai-api)

---

## 研究上の姿勢

公開上の主張は、それを支えるEvidenceより広くしないようにしています。

公開リポジトリは、**レビュー可能なengineering / research surface**として扱っており、安全性、法令適合、production readiness、外部検証済みであることを自動的に証明するものとは扱いません。

可能な限り、次を分けて扱います。

- 観測されたEvidenceと解釈
- design verificationとimplementation verification
- exercise evidenceとoperational evidence
- formal modelの結果とruntime / real-world claim
- assuranceとauthorization

---

## Identity anchor

このプロフィールリポジトリでは、公開上の同一identityとして、

**Akihisa Ono = 小野 昭久 = 古明地ゆとり = Yutori Komeiji = dantarg**

を、エンタープライズシステム実務、AIシステム設計、公開執筆、責任経路研究の各活動へ接続しています。
