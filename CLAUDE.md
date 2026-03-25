# CLAUDE.md — 專案指南與偏好

## 專案概述

行為面試題庫（Behavioral Interview Question Bank），包含 7 大類別、15 題標準行為面試問題，搭配 1-5 分評分量表與 STAR 方法論。目前範例回答以**專案管理（PM/TPM）**角度撰寫，未來可擴展至 SWE、EM 等角色。

## 內容原則

### 語言與格式
- 全部使用**繁體中文**
- 所有內容以 **Markdown** 撰寫，評分用 Markdown 表格呈現
- 每個檔案都要有**跨頁導覽連結**（回首頁、評分指南、其他類別）

### 範例回答撰寫規範

1. **回答不是越長越好** — 精簡為上，保留核心 STAR 骨幹與量化數據，刪除冗餘鋪陳
   - 2 分回答：~80-100 字
   - 4 分回答：~150-200 字
   - 5 分回答：~200-250 字

2. **排版必須有換行** — blockquote 內每個 STAR 段落之間要有空行（`>`），不能擠成一面牆

3. **STAR 標籤標註**
   - 4 分和 5 分回答：使用 `**【S — 情境】**`、`**【T — 任務】**`、`**【A — 行動】**`、`**【R — 結果】**`、`**【反思】**` 標籤分段
   - 2 分回答：**刻意不標 STAR 標籤**，用自然段落呈現，讓面試官自己發現缺漏（這是教學設計）
   - 5 分回答比 4 分多一段 `**【反思】**`，展現方法論提煉

4. **選擇 2/4/5 三個等級**做範例（跳過 1 和 3），展現清楚的品質差異

## 評分系統

- **4 個評分維度：** STAR 完整度、相關性與影響力、個人貢獻度、自我覺察與成長
- 每個維度 1-5 分，每題有**題目專屬**的評分描述（非通用模板）
- 差異比較表的 STAR 完整度欄位要**具體指出缺漏**（如「缺 T 和 A」），不能只寫模糊描述

## 檔案結構

```
README.md                          # 首頁入口
SCORING_GUIDE.md                   # 評分系統指南
categories/01-leadership.md        # 領導力（2 題）
categories/02-teamwork.md          # 團隊合作（2 題）
categories/03-problem-solving.md   # 問題解決（3 題）
categories/04-conflict-resolution.md # 衝突處理（2 題）
categories/05-adaptability.md      # 適應力（2 題）
categories/06-communication.md     # 溝通能力（2 題）
categories/07-drive-and-ownership.md # 驅動力與當責（2 題）
templates/question-template.md     # 新增題目模板
templates/role-extension-template.md # 角色擴展指南
```

## Git 資訊

- Remote: `https://github.com/RayChenCode/behavioral-interview-question-bank.git`
- Branch: `main`
