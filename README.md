# Jack Tang - Personal Webpage

一個現代化、高度互動的個人網頁，展示時尚的視覺設計和實時功能。

## ✨ 功能特性

### 🕐 實時時鐘
- 每秒自動更新
- 24小時制顯示（HH:MM:SS）
- 使用等寬字體確保對齐

### 📅 動態日期
- 顯示完整日期（星期、月份、日期、年份）
- 自動本地化格式

### 🎨 設計亮點

#### 玻璃態效果 (Glassmorphism)
- 半透明卡片背景 (rgba 0.1 透明度)
- Backdrop blur 效果 (10px)
- 微妙的邊框與光暈陰影
- 現代化的視覺風格

#### 漸變動畫背景
- 深紫色到靛藍色的流暢漸變
- 15秒循環動畫
- 營造沉浸式視覺體驗

#### 浮動球體
- 三個帶有高斯模糊的彩色球體
- 不同的浮動動畫延遲
- 增加視覺深度和動感

### 💫 入場動畫
- 平滑淡入效果
- 錯階向上滑動 (Staggered fade-up)
- 每個元素有不同的動畫延遲

#### 名字特效
- 紫色漸變文字效果
- 持續閃爍動畫
- 高度可見的視覺焦點

## 📁 檔案結構

```
L1/
└── index.html        # 主要網頁文件（包含 HTML、CSS、JavaScript）
└── README.md         # 說明文檔（本文件）
```

## 🚀 使用方法

### 快速開始
1. 下載或複製 `index.html` 文件到本地
2. 使用任何現代網頁瀏覽器打開 `index.html`
3. 網頁會自動開始運行，時鐘實時更新

### 支援的瀏覽器
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- 任何支援 ES6 的現代瀏覽器

## 🛠️ 技術細節

### 使用的技術
- **HTML5** - 語意化標記
- **CSS3** - 動畫、漸變、Backdrop Filter
- **Vanilla JavaScript** - 無依賴的時鐘更新邏輯

### 關鍵 CSS 特性
- `backdrop-filter` - 玻璃態效果
- `background-clip: text` - 文字漸變
- `animation` - 多種動畫效果
- CSS 變數友好的設計

### JavaScript 功能
```javascript
// 每秒更新時鐘和日期
setInterval(updateTime, 1000);

// 支援多語言日期格式
toLocaleDateString('en-US', options);
```

## 🎯 設計靈感

本設計採用現代 UI 趨勢：
- **Glassmorphism** - 透明玻璃效果
- **Neumorphism 元素** - 柔和的陰影
- **微交互** - 流暢的動畫過渡
- **色彩心理學** - 紫色象徵創意與優雅

## 📱 響應式設計

網頁在不同設備上都能正常顯示：
- 桌面電腦
- 平板裝置
- 行動裝置（Viewport Meta Tag）

## 🔧 自訂指南

### 修改姓名
編輯 `index.html` 中的第 192 行：
```html
<div class="name">Jack Tang</div>
```

### 修改顏色方案
調整 CSS 中的漸變色值：
```css
background: linear-gradient(135deg, #1a0033 0%, #2d0052 25%, ...);
```

### 調整動畫速度
修改 `animation` 屬性的時間值（單位：秒）

## 📄 授權

自由使用、修改和分發

---

**製作日期**: 2026年3月2日  
**版本**: 1.0