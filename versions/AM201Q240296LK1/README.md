<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 2.01″ AMOLED 显示屏 240×296（AM201Q240296LK1）</h1>

<p align="center"><b>AMOLED 模组 · QSPI · ICNA3306</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: ICNA3306" src="https://img.shields.io/badge/Driver-ICNA3306-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 2.01 寸 240×296 AMOLED 模组宣传图" src="./images/3.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 2.01 英寸 |
| 类型 | AMOLED |
| 分辨率 | 240×296 |
| 外形尺寸 | 36.40 x 43.57 mm |
| 有效显示区域 | 32.04 x 39.52 mm |
| 接口 | QSPI |
| 驱动 IC | ICNA3306 |
| 触摸驱动 | — |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`ICNA_3306_Datasheet_release_V0_03_20211008_2_966e953f85.pdf`](./datasheets/ICNA_3306_Datasheet_release_V0_03_20211008_2_966e953f85.pdf) |
| 规格文档 | [`CST_816_D_V1_0_2_1b06dfb078.pdf`](./datasheets/CST_816_D_V1_0_2_1b06dfb078.pdf) |
| 规格文档 | [`AM201Q240296LK1.pdf`](./datasheets/AM201Q240296LK1.pdf) |
| CAD 图纸 | [`OK-14F024-04.pdf`](./cad/OK-14F024-04.pdf) |
| 转接板资料 | [`2.01_AMOLED转接板V1.0_2025-05-22.pdf`](./adapter/2.01_AMOLED%E8%BD%AC%E6%8E%A5%E6%9D%BFV1.0_2025-05-22.pdf) |

## 仓库结构

```text
display-amoled-2.01inch-240x296/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── AM201Q240296LK1/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── cad/              # 外形/盖板 CAD
        └── adapter/          # 转接板资料 + 转接板图片
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
