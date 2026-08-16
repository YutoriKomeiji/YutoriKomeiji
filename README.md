# 小野 昭久 / Akihisa Ono（古明地ゆとり / Yutori Komeiji）

[English](./README.en.md)

SAPを中心としたエンタープライズシステムの仕事に20年以上携わっています。現在もSAP関連業務を本職としつつ、個人活動としてAIの責任設計、AIエージェントの実行制御、人間とAIの役割分担について研究・実装しています。

公開活動では **小野 昭久 / Akihisa Ono**、**古明地ゆとり (Yutori Komeiji)**、ID **dantarg** を使用しています。

---

## 経歴概要

### SAP / エンタープライズシステム

日本国内のSAP関連プロジェクトで、導入、保守、開発、コンサルティング、調整、プロジェクト支援などを経験してきました。

主な経験は以下のとおりです。

- ABAP開発
- 基本設計
- 開発リード
- 要件定義
- 機能コンサルティング
- 移行・インターフェース関連の調整
- チームリード / サブリード
- PMO
- プロジェクトマネジメント
- 顧客側プロジェクトリーダー支援

経験領域は、物流、製造、財務・管理会計、分析・レポーティングなどです。中でも在庫関連業務、原価計算、原価管理には比較的長く関わっています。

クラシックSAPとS/4HANAの双方、オンプレミスおよびクラウドを含む案件を経験しています。

これまでに、商社、製造業、製薬、広告・メディア、産業機器などの業界案件に関わってきました。

---

## 個人研究・OSS活動

本業とは別に、AIが判断や実行に関わるシステムで、責任や権限が曖昧にならないための設計を研究しています。

特に関心があるのは、次のようなテーマです。

- AIにどこまで任せ、どこで人間に戻すか
- 「できること」と「許可されていること」を分けること
- AIの出力を、そのまま組織の正式判断にしないこと
- 外部操作が本当に反映されたかを確認すること
- 停止後の再試行、再開、再承認を区別すること
- 最後に誰が責任を引き受けるのかを明確にすること

### Responsibility Pathway Design (RPD)

**[responsibility-pathway-design](https://github.com/YutoriKomeiji/responsibility-pathway-design)**

AIが関与する業務やシステムで、判断、委任、実行、中断、回復までの責任の流れを設計するためのフレームワークです。

### Responsibility Pathway Engineering (RPE)

**[responsibility-pathway-engineering](https://github.com/YutoriKomeiji/responsibility-pathway-engineering)**

人が定めた要件を、AIや自動化システムの実行時チェックへ落とし込むための公開リファレンス実装です。

現在の公開版では、Pythonによる判定カーネル、Requirement Pack、REST / OpenAPI / MCPの参照インターフェース、ライフサイクル管理、スキーマ、テストなどを公開しています。

### Responsibility Pathway Runtime (RPR)

**[responsibility-pathway-runtime](https://github.com/YutoriKomeiji/responsibility-pathway-runtime)**

AIエージェントや自動化が外部操作を行う際に、権限、実行結果、停止、修復、再開、人への判断返却を記録・管理するためのPythonランタイムです。

現在の公開alphaは **0.1.0a4** で、PyPIにも公開しています。

- PyPI: https://pypi.org/project/responsibility-pathway-runtime/
- Live browser demo: https://yutorikomeiji.github.io/responsibility-pathway-runtime/demo.html

### Asymmetric Human–AI Agency (AHAA)

**[Asymmetric-Human-AI-Agency](https://github.com/YutoriKomeiji/Asymmetric-Human-AI-Agency)**

2026年1月にまとめた初期の設計原則です。

> **Capability may be delegated. Authority must not be.**

現在は、後続のResponsibility Pathway研究につながる基礎的・歴史的な位置づけとして整理しています。

---

## 企業に所属しながら、本名で公開している理由

私は企業に所属していますが、ここで公開しているAI研究やOSSは、勤務先の製品活動とは分けた個人活動です。

そのため、勤務先の企業名や肩書きを、この研究の権威づけとして使うことはしていません。

一方で、個人活動だからといって匿名で責任を曖昧にしたくもありません。

公開する以上、誰が作っているのか、どこまで実装できているのか、何がまだ未検証なのか、問題があったときに誰が直すのかを明確にしておきたいと考えています。

そのため、**小野 昭久 / Akihisa Ono** の本名で活動しています。

---

## Luminalia

**Luminalia** という、人間とAIの共同作業・研究のための環境も設計・運用しています。

AIとの長期的な対話、設計検討、評価、運用実験などに使っており、その中で生まれた考えの一部がResponsibility Pathway関連の公開研究にもつながっています。

---

## 執筆

AI、責任設計、人間とAIの役割分担、AIガバナンスなどについて記事を書いています。

- **note:** https://note.com/dantarg
- **Zenn:** https://zenn.dev/dantarg
- **Qiita:** https://qiita.com/dantarg
- **LinkedIn:** https://www.linkedin.com/in/akihisaono

---

## 主な公開リポジトリ

- [Responsibility Pathway Design](https://github.com/YutoriKomeiji/responsibility-pathway-design)
- [Responsibility Pathway Engineering](https://github.com/YutoriKomeiji/responsibility-pathway-engineering)
- [Responsibility Pathway Runtime](https://github.com/YutoriKomeiji/responsibility-pathway-runtime)
- [Asymmetric Human–AI Agency](https://github.com/YutoriKomeiji/Asymmetric-Human-AI-Agency)

---

## 公開時の考え方

自分の設計や実装には自信を持って取り組んでいますが、開発者自身の評価と第三者評価は分けて考えています。

公開したこと、テストが通ったこと、形式的に確認できたことだけで、現実の安全性や法令適合、実運用での有効性まで証明されたとは考えません。

できるだけ、実装できていること、確認できていること、まだ分からないことを分けて記録するようにしています。

---

## 公開名義

**Akihisa Ono = 小野 昭久 = 古明地ゆとり = Yutori Komeiji = dantarg**
