<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.48″ TFT 172×640（AXS15231B · QSPI）</h1>

<p align="center"><b>条状 TFT · QSPI · AXS15231B · 电容触摸</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Size: 3.48 inch" src="https://img.shields.io/badge/Size-3.48%22-3498DB?style=flat-square" />
  <img alt="Resolution: 172x640" src="https://img.shields.io/badge/Resolution-172%C3%97640-8E44AD?style=flat-square" />
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: AXS15231B" src="https://img.shields.io/badge/Driver-AXS15231B-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 3.48 寸 172×640 TFT QSPI 模组（AXS15231B）宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [产品简介](#产品简介)
- [规格参数](#规格参数)
- [示例工程](#示例工程)
- [仓库结构](#仓库结构)
- [相关资料](#相关资料)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 产品简介

OSPTEK **3.48 寸 172×640 TFT** 是一款 **QSPI** 接口彩色显示模组，驱动芯片为 **AXS15231B**（显示与电容触摸一体）。细长分辨率适合条形 HMI、侧边状态条与紧凑信息面板等场景。

规格标识（仓库名）：`tft-3.48-172x640-qspi-axs15231b`

当前模组版本：**YDP348BT001-V1**。电气与外形细节以 [`docs/YDP348BT001-V1.pdf`](./docs/YDP348BT001-V1.pdf) 为准。

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 3.48 英寸 |
| 类型 | TFT（彩色） |
| 分辨率 | 172×640 |
| 接口 | QSPI |
| 驱动 IC | AXS15231B |
| 触摸驱动 | AXS15231B |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 示例工程

| 说明 | 路径 |
| ---- | ---- |
| ESP32-S3 · AXS15231B QSPI + LVGL8 | [`examples/esp32s3-idf5_axs15231b-qspi_lvgl8/`](./examples/esp32s3-idf5_axs15231b-qspi_lvgl8/) |
| ESP32-S3 · AXS15231B QSPI + LVGL8（另一套引脚，源自 3.48TFT_QSPI） | [`examples/esp32s3-idf5_3.48tft-qspi_lvgl8/`](./examples/esp32s3-idf5_3.48tft-qspi_lvgl8/) |

## 仓库结构

```text
tft-3.48-172x640-qspi-axs15231b/                                # 仓库根（导航见 ../../README.md）
└── versions/
    └── YDP348BT001-V1/                                # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/                  # 示例工程
```

## 相关资料

| 资料 | 链接 |
| ---- | ---- |
| 产品规格书（YDP348BT001-V1） | [`docs/YDP348BT001-V1.pdf`](./docs/YDP348BT001-V1.pdf) |
| 转接板资料（适配 S3 DEMO 底板） | [`docs/3.48寸TFT转接板_适配S3 DEMO底板.pdf`](./docs/3.48%E5%AF%B8TFT%E8%BD%AC%E6%8E%A5%E6%9D%BF_%E9%80%82%E9%85%8DS3%20DEMO%E5%BA%95%E6%9D%BF.pdf) |

### 示例工程

- [ESP32-S3 AXS15231B QSPI + LVGL8](./examples/esp32s3-idf5_axs15231b-qspi_lvgl8/)
- [ESP32-S3 AXS15231B QSPI + LVGL8（另一套引脚）](./examples/esp32s3-idf5_3.48tft-qspi_lvgl8/)

## 购买链接

<p align="center">
  <a href="https://shop110742373.taobao.com/"><img alt="淘宝官方店铺" src="https://img.shields.io/badge/淘宝-官方店铺-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="速卖通官方店铺" src="https://img.shields.io/badge/速卖通-官方店铺-E62E04?style=for-the-badge&logo=aliexpress&logoColor=white" /></a>
</p>

**国内（淘宝）**

- 店铺：[鱼鹰光电工厂店](https://shop110742373.taobao.com/)

**海外（AliExpress）**

- 店铺：[OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

## 技术支持

- 技术支持 / 产品咨询：<luyu@osptek.com>
- QQ 技术交流群：**985881096**
- 公司官网：<https://osptek.com/>
- 有任何问题，都可以在本仓库 Issues 中提问

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
