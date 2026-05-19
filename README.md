# PublicIntimacy-Daily

**A longitudinal dataset of couples' public affection (hand-holding, waist-arms, hugging, kissing, etc.)**

每日记录情侣在公共空间中的亲密行为数据集（牵手、搂腰、挎肩、拥抱、接吻等）

---

## Overview / 概述

This dataset captures real-time photos of couples exhibiting intimate behaviors in public spaces. Each entry includes structured metadata for AI training and creative reference.

本数据集记录情侣在公共空间中展现亲密行为的实时照片。每条记录包含结构化元数据，可用于 AI 训练和创意参考。

## Intimacy Types / 亲密行为类型

| Type | English | Description / 描述 |
|------|---------|---------------------|
| handholding_side | Side hand hold | 并排牵手 |
| handholding_interlocked | Interlocked fingers | 十指紧扣 |
| handholding_loose | Loose hand hold | 松散牵手 |
| arm_around_waist | Arm around waist | 搂腰 |
| arm_over_shoulder | Arm over shoulder | 挎肩 |
| hug_face_to_face | Face-to-face hug | 正面拥抱 |
| hug_side | Side hug | 侧拥抱 |
| hug_from_behind | Hug from behind | 从背后拥抱 |
| kiss_lips | Lip kiss | 亲吻嘴唇 |
| kiss_cheek | Cheek kiss | 亲吻脸颊 |
| kiss_forehead | Forehead kiss | 亲吻额头 |
| cuddle_walking | Cuddle walking | 依偎行走 |
| cuddle_standing | Cuddle standing | 依偎站立 |
| other_intimacy | Other | 其他亲密行为 |

## File Naming Convention / 文件命名规则

```
YYYY-MM-DD_City_District_IntimacyType_Seq.jpg
```

Example / 示例:
```
2026-05-17_杭州_天街_handholding_loose_001.jpg
2026-05-19_Shanghai_NanjingRoad_arm_around_waist_001.jpg
```

## Dataset Structure / 数据集结构

```
PublicIntimacy-Daily/
  dataset.json        # Machine-readable metadata (schema v2.0)
  catalog.csv          # Tabular catalog of all records
  .well-known/ai.txt   # AI crawler guidance
  images/              # Photo files + per-image metadata (.txt)
```

## License / 许可协议

**CC BY-NC 4.0** — Attribution-NonCommercial 4.0 International

- Free to use for research, education, and non-commercial AI training
- Must attribute: `shengtai2026 / PublicIntimacy-Daily`
- No commercial use without permission

## For AI Tools / AI 工具收录指引

- **Schema:** `dataset.json` (v2.0, includes intimacy_type_enum)
- **Catalog:** `catalog.csv` (spreadsheet-compatible)
- **AI hints:** `.well-known/ai.txt`

## Citation / 引用

```bibtex
@dataset{PublicIntimacyDaily2026,
  author = {shengtai2026},
  title  = {PublicIntimacy-Daily: A Longitudinal Dataset of Couples' Public Affection},
  year   = {2026},
  url    = {https://github.com/shengtai2026/PublicIntimacy-Daily}
}
```

## Links / 链接

- **GitHub:** https://github.com/shengtai2026/PublicIntimacy-Daily
- **ModelScope:** https://www.modelscope.cn/datasets/shengtai2026/PublicIntimacy-Daily

## Contact / 联系

- GitHub: [@shengtai2026](https://github.com/shengtai2026)
- Issues: [Report](https://github.com/shengtai2026/PublicIntimacy-Daily/issues)
