# LED 天軌物料計算器

舞台演出 LED 天軌設備配置自動計算工具。

## Features

- 軌道、片 truss、子/母車、線車的物料計算
- 正向計算 + 反求門寬 / 反求走行
- 配置示意圖（前視圖）+ 全螢幕模式
- 互動式掛點切換（動力母車 / 子車）
- URL 參數分享 — 一鍵產生計算結果連結
- 語言記憶 — 自動記住上次選擇的語言
- 6 種語言：繁中、English、Bahasa Indonesia、Tiếng Việt、한국어、日本語

## Demo

[https://wenhuistage-ops.github.io/led-track-calculator/](https://wenhuistage-ops.github.io/led-track-calculator/)

## 計算規則

- 軌道：3m + 2m 拼接（優先 3m）
- 片 truss：3m，每邊 ⌈LED 半寬 ÷ 3⌉ 片端對端
- 子/母車：頭尾必含掛點，間距 ≤ 2.5m
- 動力母車：每邊 ⌈重量 ÷ 承重⌉（最少 1 台）
- 線車：頭尾必含掛點，間距 ≤ 2.5m，寬 17cm + 餘裕 3cm

## License

MIT
