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

<div style="width: 100%; height: 300px; overflow: hidden; border: 1px solid #ddd; box-shadow: 2px 2px 5px rgba(0,0,0,0.1); border-radius: 8px; position: relative; margin: 20px 0;">

    <iframe 
        src="./行程規劃A.html" 
        style="
            width: 100%;
            height: 100%;
            border: none; 
            transform: scale(1); /* 不縮小 */
            transform-origin: 0 0;  /* 從左上角開始縮放 */
            pointer-events: none;   /* 禁止滑鼠直接操作 iframe 內部的捲軸或按鈕，讓點擊事件穿透到下方的連結 */
        ">
    </iframe>

    <a href="./行程規劃A.html" style="
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: 10; /* 確保連結在最上層 */
        cursor: pointer;
    " title="點擊前往：行程規劃">
    </a>
    
    <div style="position: absolute; bottom: 0; width: 100%; background: rgba(0,0,0,0.6); color: white; text-align: center; font-size: 12px; padding: 5px 0; pointer-events: none;">
        行程規劃 預覽
    </div>

</div>

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
</style>
