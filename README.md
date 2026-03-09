# 📦 My-Assets-Hub (個人資產集散中心)

這是一個公開的資產託管倉庫，專門存放個人各項開發計畫所需的圖片、影片及多媒體素材。透過 GitHub 的 CDN 加速，確保素材能穩定地供應給 Notion、README 文件或個人網站使用。

---

## 📂 目錄結構說明

倉庫採用專案分類制，請依循以下路徑存取資源：

* **projects/**: 所有計畫的根目錄
    * **project-A/**:
        * `images/`: 存放 UI 截圖、插圖、硬體架構圖。
        * `videos/`: 存放動畫 (MP4) 與操作示範影片。
    * **SHARED/**: 跨專案通用的 Logo、Icons。
---

## 🛠️ 使用指南 (手機使用者建議)

### 1. 如何取得永久 Raw 連結？
1. 進入目標檔案頁面。
2. 長按 **Download** 按鈕並選擇「拷貝連結網址」。
3. 確保網址格式為：
   `https://raw.githubusercontent.com/SuperRockManZero/My-Assets-Hub/main/projects/您的專案名稱/images/您的檔案.jpg`

### 2. 嵌入至 Notion
* 在 Notion 中使用 `/image` 命令，並選擇 **Embed link** 貼上上述連結。

### 3. 在 Markdown (README) 顯示影片
由於 GitHub README 無法直接播放 MP4，建議使用以下 HTML 格式：
```html
<p align="center">
  <video src="您的MP4連結" width="100%" controls></video>
</p>
