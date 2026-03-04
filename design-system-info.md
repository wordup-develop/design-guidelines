# Design System 資訊

## Figma 檔案連結
讀取來源（Design System 主檔）
Claude 啟動時從這個檔案讀取所有 component 和 token：
https://www.figma.com/design/cM4wqQ8BuMgp6WU1i09EGO/-Lab--Design-System?m=auto&t=liBBcrYGCPqcl7ay-6

| 用途 | 網址 |
|------|------|
| App | https://www.figma.com/design/4NDOlkfLNmLkJ0WCG7I28z/-New--App?node-id=234-4850&t=pGfa3fzHPMmyUlUa-1 |
| Shop | https://www.figma.com/design/gpeCbBQIZ4y4wRWFxfo4DI/-New--Shop?node-id=644-4123&t=g1i6vqSasGuHnQu6-1 |

---

## Library 名稱

- Design System Library：`-Lab- Design System (v2)`

---

## 操作方式

- 開啟 Chrome，前往 Design System 主檔讀取 component 和 token
- 生成的畫面放到對應產品的 UI Screens 檔案：
| 生成畫面 | 存放網址 |
|------|------|
| App UI Screens | [https://www.figma.com/design/4NDOlkfLNmLkJ0WCG7I28z/-New--App?node-id=234-4850&t=pGfa3fzHPMmyUlUa-1] |
| Shop UI Screens | [https://www.figma.com/design/gpeCbBQIZ4y4wRWFxfo4DI/-New--Shop?node-id=644-4123&t=g1i6vqSasGuHnQu6-1] |
- 確認目標檔案已開啟 Design System Library（Assets → Libraries）

---

## Design System 結構

| Page 名稱 | 內容 |
|-----------|------|
| Foundation | Color tokens、Typography、Spacing、Border radius |
| Components | 所有 UI component |

---

## 注意事項

- 所有顏色必須使用 Semantic token，不可使用 primitive color（例如用 `background/primary` 而非 `color/grey/50`）
- Component 命名格式：`[Component 名稱] / [Variant]`
- 如果目標檔案沒有 link library，請提醒使用者先在 Figma 開啟 library 再繼續
