# Browndust2 Wiki I18n / Browndust2 Wiki 多語言翻譯

歡迎來到 **Browndust2 Wiki I18n** 專案。
這個倉庫負責管理 **Browndust2 Wiki** 的國際化 (`i18n`) 翻譯檔案，目標是讓玩家能夠以自己的語言更輕鬆地瀏覽與編輯 Wiki。

Welcome to the **Browndust2 Wiki I18n** project.
This repository manages the internationalization (`i18n`) translation files for **Browndust2 Wiki**, aiming to make it easier for players to browse and edit the Wiki in their preferred language.

📌 **BD2 Wiki**：[Browndust2 Wiki](https://browndust2-wiki.pages.dev/)
📌 **BD2 Wiki Discord**：[加入我們 / Join us!](https://discord.gg/PzBNacyXQW)

---

## 🌍 支援的語言 / Supported Languages
我們目前計畫支援以下語言：
We currently plan to support the following languages:

- 🇹🇼 **繁體中文** (`zh-TW`) ✅ **（基礎翻譯 / Base Translation）**
- 🇺🇸 **英文** (`en`) ✅ **（基礎翻譯 / Base Translation）**
- 🇨🇳 **簡體中文** (`zh-CN`) 🛠 **（可從繁體複製 / Clone from `zh-TW`）**
- 🇯🇵 **日文** (`ja`) 🛠 **（可從英文複製 / Clone from `en`）**
- 🇰🇷 **韓文** (`ko`) 🛠 **（可從英文複製 / Clone from `en`）**

---

## 📖 目錄結構 / Directory Structure
```plaintext
/
├── en/       # English (Base Translation)
│   ├── bd2/
│   │   ├── _bd2_commons.ts
│   │   ├── ... Common words in the game
│   ├── layout/
│   │   ├── _commons.ts
│   │   ├── _navs.ts
│   │   ├── ... Common words on the website
│   ├── views/
│   │   ├── characters.ts
│   │   ├── costumes.ts
│   │   ├── home.ts
│   │   ├── weapons.ts
│   │   ├── ... Each page's translation
│
├── zh-TW/    # 繁體中文 (Base Translation)
│   ├── bd2/
│   │   ├── _bd2_commons.ts
│   │   ├── ... 遊戲內常用詞彙
│   ├── layout/
│   │   ├── _commons.ts
│   │   ├── _navs.ts
│   │   ├── ... 網站通用詞彙
│   ├── views/
│   │   ├── characters.ts
│   │   ├── costumes.ts
│   │   ├── home.ts
│   │   ├── weapons.ts
│   │   ├── ...各個頁面的翻譯
│
├── zh-CN/    # 简体中文 (Clone from zh-TW)
├── ja/       # 日本語 (Clone from en)
├── ko/       # 한국어 (Clone from en)
```

---

## 🛠 如何貢獻翻譯？/ How to Contribute Translations?

我們歡迎所有人幫助改善翻譯！請按照以下步驟貢獻：
We welcome everyone to help improve translations! Please follow these steps:

1️⃣ **Fork 本倉庫 / Fork this repository**
2️⃣ **選擇 `en/` 或 `zh-TW/` 作為基礎，複製至新語言資料夾**
    - 📝 **簡體中文** → 請從 `zh-TW` 複製
    - 📝 **日文 / 韓文** → 請從 `en` 複製
3️⃣ **修改內容後提交 PR（Pull Request） / Edit translations and submit a PR**
4️⃣ **等待審核與合併 / Wait for review and merge** 🎉

如果你不熟悉 Git，也可以在 **Discord** 內提供翻譯建議！
If you are not familiar with Git, you can also suggest translations in our **Discord**!

---

感謝你的參與！ / Thank you for your contribution!
作者：曹齊白 / Author: Souseihaku
