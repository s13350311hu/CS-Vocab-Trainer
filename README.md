# CS Vocab Trainer

一個以瀏覽器直接使用的英文學習平台，整合 **高中 7000 單字、國中會考文法、高中文法、TOEIC、資工英文、閃卡、克漏字、測驗、錯題與學習進度**。

> English learning platform for High School English, TOEIC, Computer Science English, grammar practice, flashcards, quizzes, and review.

## ✨ Features

### 📚 Vocabulary

- 資工研究所英文核心單字
- 高中 7000 單字
- TOEIC 常見單字
- 學術高頻英文
- 分類瀏覽與搜尋
- 中文反查英文
- 英文拼字錯誤的相似單字建議
- 單字發音與例句朗讀

### 📖 Grammar

- 國中會考常見文法
- 高中文法
- 文法關鍵字搜尋
- 基礎到進階句型
- 時態、被動、假設、關係詞、分詞、不定詞、動名詞、倒裝等主題

### 🃏 Flashcards

所有已載入單字都可以進入閃卡，包括資工、高中 7000 與 TOEIC 詞庫。

支援：

- 上一張／下一張
- 洗牌
- 單字朗讀
- 例句朗讀
- 太簡單
- 需複習
- 完全掌握

### ✏️ Practice & Quizzes

- 克漏字
- 單字測驗
- 文法測驗
- TOEIC／綜合練習
- 考試模式
- 計時測驗
- 成績與正確率

### ❌ Wrong Answer Review

答錯內容可以進入錯題與弱點中心，依錯誤次數排序，方便集中複習。

### 📊 Learning Progress

- 每日學習目標
- 今日學習量
- 連續學習天數
- 單字掌握度
- 測驗正確率
- 學習統計

### 🔊 Pronunciation

使用瀏覽器的 Web Speech API 朗讀英文。實際聲音會依作業系統與瀏覽器提供的英文語音而有所不同。

### 💾 Local Storage

主要學習資料保存在使用者自己的瀏覽器 `localStorage`，因此不需要另外建立後端資料庫。

---

## 🚀 Live Demo

GitHub Pages 開啟後可以放在這裡：

`https://你的GitHub帳號.github.io/CS-Vocab-Trainer/`

---

## 🖥️ Run Locally

最簡單的方法：直接雙擊 `index.html`。

也可以使用任何靜態網站伺服器，例如 VS Code Live Server。

---

## 🌐 Deploy with GitHub Pages

本專案是純 HTML/CSS/JavaScript 靜態網站，可以直接使用 GitHub Pages。

1. 建立 GitHub repository。
2. 將本專案檔案上傳到 repository 的 `main` branch。
3. 進入 **Settings → Pages**。
4. 在 **Build and deployment** 的 **Source** 選擇 **Deploy from a branch**。
5. Branch 選擇 `main`，資料夾選擇 `/(root)`。
6. 按 **Save**。
7. 等待部署完成後，按 **Visit site**。

---

## 📁 Project Structure

```text
CS-Vocab-Trainer/
├── index.html
├── README.md
├── LICENSE
├── DATA_NOTICE.md
├── GITHUB_FIRST_TIME.md
├── ABOUT.txt
├── .gitignore
└── screenshots/
```

目前核心網站刻意維持單一 `index.html`，方便第一次使用 GitHub Pages 的使用者直接部署。

---

## ⚠️ Data & Third-party Notice

本專案內含詞彙資料與線上字典功能。不同資料來源可能具有不同的著作權、授權與使用條款。

在公開 GitHub repository 前，請確認你使用的詞庫內容可以依其原始授權條件公開與再散布。

線上字典功能可能透過公開 Dictionary API 查詢資料；使用時請遵守該服務當時的使用條款。

本專案的程式碼授權與第三方資料授權應分開看待，請參考 `LICENSE` 與 `DATA_NOTICE.md`。

---

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- Web Speech API
- Browser localStorage
- Dictionary API

---

## 🎯 Target Users

- 國中學生
- 高中學生
- 學測／分科測驗準備者
- TOEIC 準備者
- 大學生
- 資工相關學生
- 自主學習英文者

---

## 🗺️ Roadmap

未來可以持續加入：

- 更完整的大考題庫
- TOEIC 題型化練習
- 聽力題庫
- 英文拼字測驗
- 易混淆字比較
- 同義字／反義字
- 常見搭配詞
- 更完整的間隔重複演算法
- 學習曲線與每週／每月報告
- 行動裝置最佳化

---

## 👨‍💻 Author

Personal English learning project.

---

## 📄 License

程式碼採 MIT License；第三方詞庫、服務與資料仍依各自授權條款處理。詳見 `LICENSE` 與 `DATA_NOTICE.md`。
