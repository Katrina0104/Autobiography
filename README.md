# Katrina Lin 作品集網站

這是林姿穎（Katrina）的個人作品集靜態網站原始碼，內容涵蓋 VR 低溫治療訓練模擬、VQA-Project 等專案介紹。

## 檔案結構

```
index.html      主頁面（單一 HTML 檔，含內嵌 CSS）
images/         頁面使用的照片與作品截圖
```

## 放到 GitHub 上公開（GitHub Pages）

1. 在 GitHub 新增一個 repository，例如 `portfolio` 或 `katrina0104.github.io`
2. 把這個資料夾裡的 `index.html` 和 `images/` 上傳到 repo（可用 GitHub Desktop 或網頁介面拖曳上傳）
3. 到 repo 的 **Settings → Pages**
4. 在 **Branch** 選擇 `main`（或你 push 的分支）、資料夾選 `/ (root)`，按 **Save**
5. 等待一兩分鐘，GitHub 會給你一個網址，格式通常是：
   - `https://<你的帳號>.github.io/<repo名稱>/`
   - 如果 repo 名稱就叫 `<你的帳號>.github.io`，網址會是 `https://<你的帳號>.github.io/`

## 之後想修改內容

`index.html` 是純 HTML + CSS，直接用文字編輯器打開修改文字、連結或顏色即可，不需要額外安裝任何工具或打包步驟。
