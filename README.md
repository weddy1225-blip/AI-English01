# 🍳 瘋狂早餐大冒險 (Crazy Breakfast Adventure)

這是一個專為國小四年級學生設計的 **AI 英語口說練習網頁**。透過與 AI 媽媽的互動，學生可以練習點餐英文，並由 Gemini AI 根據選擇生成專屬的大結局！

## ✨ 特色功能
- **語音辨識 (STT)**：使用 Web Speech API，即時糾正學生的發音。
- **語音合成 (TTS)**：自動朗讀英文句子，提供標準發音參考。
- **AI 動態結局**：串接 **Google Gemini API**，根據玩家選的食物與飲料組合出無限種結局。
- **完全免費**：利用 Google Apps Script 作為後端，無需支付伺服器費用。

## 🚀 如何使用 (快速開始)
如果你想直接體驗，請訪問：`[你的 GitHub Pages 網址]`

## 🛠️ 如何部署自己的版本 (給開發者)
如果你想修改程式碼或使用自己的 Gemini API 額度：

1. **取得 Gemini API Key**：到 [Google AI Studio](https://aistudio.google.com/) 申請免費 Key。
2. **設定後端 (GAS)**：
   - 開啟 [Google Apps Script](https://script.google.com/)，建立新專案。
   - 貼入後端代碼，並填入你的 API Key。
   - 點擊「部署」->「網頁應用程式」，將存取權設為「所有人」。
3. **設定前端 (HTML)**：
   - 下載本專案的 `index.html`。
   - 找到 `const GAS_WEB_APP_URL`，換成你部署得到的網址。
4. **上傳至 GitHub Pages** 即可運作！

## 📜 授權協議
本專案採用 **MIT License** 開源授權，歡迎自由修改與分享。
