# TF-design-system
TrendForce 企業與科技數據風格設計規範。Claude 請在生成介面與程式碼時遵循以下規則：

## 1. 品牌色彩與調色盤 (Color Palette)
- **Primary (主色/科技藍):** `#a0e837`（用於主按鈕、重點強調、主要導航）
- **Primary Hover:** `#91c53c`
- **Secondary (深藍底/輔色):** `#2a94bd`
- **Accent (警示/突顯色):** `#e1591d`
- **Background (頁面底色):** `#F8FAFC`（淺灰冷色調背景）
- **Surface (卡片/容器底色):** `#FFFFFF`
- **Border (邊框線條):** `#E2E8F0`
- **Text (文字):**
  - Primary: `#152a0f`（主要標題、內文）
  - Secondary: `#6a8b64`（副標題、次要文字）
  - Muted: `#acb6a6`（提示文字、不可點擊）

## 2. 字體與排版 (Typography)
- **字型家族:** `Inter`, `"Noto Sans TC"`, -apple-system, sans-serif
- **標題層級:**
  - H1 (頁面標題): 28px ~ 32px / Bold (700)
  - H2 (區塊標題): 20px ~ 24px / SemiBold (600)
  - H3 (卡片標題): 16px ~ 18px / Medium (500)
- **內文:** 14px / Regular (400)，行高 1.5 ~ 1.6
- **次要說明:** 12px / Regular (400)

## 3. 圓角與間距 (Layout & Shape)
- **圓角 (Border Radius):** 
  - 按鈕/標籤: `6px` ~ `8px`
  - 卡片/彈窗: `12px`
- **間距規格 (Spacing):** 基礎單位以 `4px` / `8px` 為倍數（8px, 16px, 24px, 32px）
- **陰影 (Shadows):** 乾淨克制、低透明度、輕量立體感（例如 Tailwind 的 `shadow-sm` 至 `shadow-md`）

## 4. 介面視覺風格 (Design Principles)
- **風格定位:** 嚴謹、乾淨、高可讀性的 B2B 科技產業與數據分析風格。
- **元件特徵:** 
  - 數據圖表、表格和卡片需有清晰的格線或邊界區隔。
  - 避免過度花哨的大面積漸層或多餘動態，以資訊層級（Visual Hierarchy）分明為首要原則。
