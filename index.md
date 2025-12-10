<meta name="viewport" content="width=device-width, initial-scale=1">
# 2026-January-Trip

- [2026-January-Trip](#2026-january-trip)
  - [1.行程規劃](#1行程規劃)
  - [2.相關資料](#2相關資料)
    - [2.1 機票資料](#21-機票資料)
    - [2.2 九州JR鐵路時刻表](#22-九州jr鐵路時刻表)
    - [2.3 其他資料](#23-其他資料)

---

## 1.行程規劃

- 行程規劃

<div style="width: 100%; height: 300px; overflow: hidden; border: 1px solid #ddd; box-shadow: 2px 2px 5px rgba(0,0,0,0.1); border-radius: 8px; position: relative; margin: 20px 0;">

    <iframe 
        src="./行程規劃A.html" 
        style="
            width: 100%;            /* 寬度設為 100%，不需補償，保持原始寬度 */
            height: 200%;           /* 高度設為 200%，讓它渲染出兩倍長的內容 */
            border: none; 
            transform: scale(1, 0.5); /* 關鍵：X軸(寬)保持 1，Y軸(高) 縮小為 0.5 */
            transform-origin: 0 0;  /* 從左上角開始縮放 */
            pointer-events: none; 
        ">
    </iframe>

    <a href="./行程規劃A.html" style="
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: 10;
        cursor: pointer;
    " title="點擊前往：行程規劃">
    </a>
    
    <div style="position: absolute; bottom: 0; width: 100%; background: rgba(0,0,0,0.6); color: white; text-align: center; font-size: 12px; padding: 5px 0; pointer-events: none;">
        行程規劃 預覽 點擊前往閱讀
    </div>

</div>

---

- <a href="https://chictrip-share.app.link/CRLecHqSYYb" target="_blank">去趣行程規劃 (To-Do)</a>
- [WORD版本](./2026-Japan-trip.docx)

[回到頁首](#2026-january-trip)

---

## 2.相關資料

### 2.1 機票資料

| 班機日期       | 起飛機場                 | 抵達機場                | 航空公司       | 起飛時間 | 抵達時間 |
| ------------- | ---------------------- | ---------------------- | ------------- | ------- | ------ |
| 01月18日 星期日 | 台北 桃園機場 [第一航站]  | 福岡 福岡國際機場 [I航站] | 星宇航空 JX840  | 14:45   | 18:00  |
| 01月23日 星期五 | 福岡 福岡國際機場 [I航站] | 台北 桃園機場 [第一航站]  | 星宇航空 JX 841 | 19:10   | 20:50  |

- 亮萱
<object data="./機票訂單-亮萱.pdf" type="application/pdf" width="100%" height="600px" style="border: 1px solid #ccc;">

    <div style="width: 100%; height: 600px; position: relative;">
        
        <iframe 
            src="https://docs.google.com/viewer?url=shuming-yang.github.io/2026-January-Trip/機票訂單-亮萱.pdf&embedded=true" 
            width="100%" 
            height="100%" 
            style="border: none;">
        </iframe>

        <div style="position: absolute; bottom: 10px; right: 10px; background: rgba(255,255,255,0.9); padding: 5px; border-radius: 4px;">
             <a href="./機票訂單-亮萱.pdf" target="_blank" style="text-decoration: none; font-weight: bold; color: #007bff;">
                📥 下載原始檔案
             </a>
        </div>

    </div>

</object>

- 威漢
  [To-Do](#31-機票資料)

[回到頁首](#2026-january-trip)

---

### 2.2 九州JR鐵路時刻表

<object data="./JR九州鐵路火車時刻表.pdf" type="application/pdf" width="100%" height="600px" style="border: 1px solid #ccc;">

    <div style="width: 100%; height: 600px; position: relative;">
        
        <iframe 
            src="https://docs.google.com/viewer?url=shuming-yang.github.io/2026-January-Trip/JR九州鐵路火車時刻表.pdf&embedded=true" 
            width="100%" 
            height="100%" 
            style="border: none;">
        </iframe>

        <div style="position: absolute; bottom: 10px; right: 10px; background: rgba(255,255,255,0.9); padding: 5px; border-radius: 4px;">
             <a href="./JR九州鐵路火車時刻表.pdf" target="_blank" style="text-decoration: none; font-weight: bold; color: #007bff;">
                📥 下載原始檔案
             </a>
        </div>

    </div>

</object>

### 2.3 其他資料

  [其他資料](./相關資料.md)


[回到頁首](#2026-january-trip)

---

<style>
/* 覆蓋主題預設的最大寬度，讓內容寬一點 */
.main-content {
    max-width: 1000px !important; /* 原本通常是 64rem，稍微加寬適合放地圖 */
    padding: 2rem 1rem;
}

/* 確保 iframe (Google Maps) 在手機上會自動縮放 */
iframe {
    width: 100% !important; /* 強制寬度填滿 */
    height: 400px; /* 統一高度 */
    max-width: 100%;
}

/* 手機版面優化 */
@media screen and (max-width: 768px) {
    /* 調整主題預設的字體大小 */
    body, .main-content {
        font-size: 18px !important;
    }
    
    /* 讓 Mermaid 圖表可左右滑動 */
    .mermaid {
        overflow-x: auto;
        display: block;
        padding-bottom: 20px; /* 預留捲軸空間 */
    }
}

/* 針對大多數 GitHub Theme (Cayman, Slate, Minimal 等) 的容器 */
.main-content, .wrapper, .markdown-body, .container {
    max-width: 95% !important; /* 強制寬度擴展到 95% */
    width: 95% !important;     /* 確保寬度生效 */
    padding-left: 20px !important;  /* 稍微縮減左右留白 */
    padding-right: 20px !important;
    margin: 0 auto !important; /* 確保內容置中 */
}

/* 如果是電腦螢幕超大，可以設個上限以免一行字太長很難讀 */
@media screen and (min-width: 1600px) {
    .main-content, .wrapper, .markdown-body {
        max-width: 1400px !important; /* 超大螢幕限制在 1400px */
    }
}

/* 針對 header (標題區) 也同步加寬，不然會發生標題窄、內容寬的奇怪狀況 */
.page-header {
    max-width: 100% !important;
    width: 100% !important;
    padding-left: 40px !important; /* 標題區通常留多一點白比較好看 */
    padding-right: 40px !important;
}
</style>
