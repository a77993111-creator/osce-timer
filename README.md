# OSCE 考站計時器

OSCE 考官用的手機計時器，單一 HTML 檔，瀏覽器打開即可使用，不需安裝。

## 功能
- 指針錶面倒數（預設 8 分鐘），剩 1 分鐘轉橘並提示音，時間到轉紅、響鈴、震動
- 開始／暫停／重設，一鍵切換學員並自動記錄每位用時（存在本機瀏覽器）
- 考站設定：站別、考題、考試時間、提醒時間、學員名單
- 畫面風格：清爽／童話；原創角色「咕咕醫師」可拖曳、點擊給 OSCE 小提醒
- 分享面板：QR code、宣傳文字；可加入手機主畫面（PWA）

## 檔案
| 檔案 | 用途 |
|---|---|
| `index.html` | 計時器本體（HTML + CSS + JS 全部在內） |
| `manifest.webmanifest`、`icon.svg` | 加入主畫面用的 App 資訊與圖示 |
| `sw.js` | 通知用的 service worker |

## 使用的外部資源
- Google Fonts：Lexend、Fredoka（SIL Open Font License）
- qrcode-generator 1.4.4（Kazuhiko Arase，MIT License），經 cdnjs 載入
- 無中國來源的 AI 模型、套件或元件

## 版本
- v2.0（2026-10-29）：指針錶面、咕咕醫師、童話風格、分享與通知

## 版權
© 2026 羅翊賓醫師 版權所有。未經授權不得重製、散布或修改。
角色「咕咕醫師」與所有圖示為本專案原創。
