# 海風伺服器插件

[![mc-seawind-cc](https://img.shields.io/badge/海風伺服器-SeaWind.cc-578aff?style=flat-square)](https://www.seawind.cc)

海風伺服器自製 Minecraft 插件集中倉庫。

## 📦 插件清單

👉 **[完整插件清單（108 個）](PLUGINS.md)** — 含分類、功能說明

### 自訂插件

| 插件 | 說明 | 狀態 |
|---|---|---|
| MinecartSpeedPlus | 礦車速度 | 非公開 |

## 🛠️ 開發環境

- **API**: Paper / Spigot 1.21.x
- **語言**: Java 21+
- **建構工具**: Maven / Gradle（依插件而定）

## 📁 專案結構

```
plugins/
├── plugin-name/          # 各插件獨立資料夾
│   ├── src/
│   ├── pom.xml / build.gradle
│   └── README.md
└── README.md             # 本文件
```

## 📋 規範

- 每個插件放在獨立資料夾，附帶自己的 `README.md`
- 使用 [設計規範](https://www.seawind.cc/設計規範) 作為遊戲數值設計參考
- Commit 訊息請使用清楚的描述

## 📄 License

各插件依其自身 LICENSE 為準。
