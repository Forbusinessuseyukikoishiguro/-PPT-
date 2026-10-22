# うさうさ研修工房 Skillセット（環境構築PPT改修・作成）

| フォルダ | 役割 |
|---|---|
| usausa-dev-env-ppt-redesign | 新卒初心者が一人で開発環境を構築できるPPTに、新規作成・分析・提案・修正・格納するSkill（SKILL.md、PROMPTS.md） |
| usausa-brand-stamp-kit | ブランドとPC環境に合わせて、スタンプ・アイコン・図形・補足文をYAMLで定義・生成するSkill（SKILL.md、assets/brand-kit.yaml、scripts/build_kit.py、sample_kit_preview.pptx） |

## 使い方
1. 2つのフォルダを、Skillの置き場所（例：`/mnt/skills/plugins/`）に入れる
2. `usausa-brand-stamp-kit/assets/brand-kit.yaml` の色・フォント・PC環境を実値に置き換える（現在は仮値）
3. 既存PPTとブランド素材を渡して、`usausa-dev-env-ppt-redesign/PROMPTS.md` のプロンプトで依頼する

## 注意
- brand-kit.yaml の色・企業名は仮値。Mac・旧Office等は実機未確認
