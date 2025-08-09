# web-media-tools
專業多媒體工具集 - 支援錄影、截圖、螢幕錄製和影片編輯
# 🎬 Web Media Tools Collection

一套專業的網頁端多媒體處理工具集合，完全基於瀏覽器技術實現，無需安裝任何軟體。

## ✨ 工具列表

### 📹 [攝像頭計時錄影器](./camera-timer-recorder/)
- **功能**：智慧計時錄影，支援預備倒數和延長錄製
- **特色**：可在錄影中顯示倒數時間、多格式輸出（MP4/WebM）
- **適用場景**：自拍錄影、教學錄製、運動記錄

### 🖥️ [螢幕錄影工具](./screen-recorder/)
- **功能**：專業螢幕錄製，支援全螢幕、視窗、分頁錄製
- **特色**：高品質錄製、即時時間顯示、多格式支援
- **適用場景**：教學錄製、軟體演示、會議記錄

### 📸 [螢幕截圖工具](./screenshot-tool/)
- **功能**：螢幕截圖與圖片裁剪編輯
- **特色**：即時預覽、拖拽選區、一鍵下載
- **適用場景**：快速截圖、圖片裁剪、內容分享

### ✂️ [影片裁切工具](./video-crop-tool/)
- **功能**：專業影片裁切，支援多種比例預設
- **特色**：即時預覽、拖拽調整、高品質輸出
- **適用場景**：影片剪輯、比例調整、內容重製

## 🚀 快速開始

### 線上體驗
每個工具都可以直接在瀏覽器中使用：

- [攝像頭計時錄影器 Demo](https://your-username.github.io/web-media-tools/camera-timer-recorder/)
- [螢幕錄影工具 Demo](https://your-username.github.io/web-media-tools/screen-recorder/)
- [螢幕截圖工具 Demo](https://your-username.github.io/web-media-tools/screenshot-tool/)
- [影片裁切工具 Demo](https://your-username.github.io/web-media-tools/video-crop-tool/)

### 本地運行
```bash
# 克隆倉庫
git clone https://github.com/your-username/web-media-tools.git

# 進入目錄
cd web-media-tools

# 使用任何 HTTP 伺服器運行，例如：
# Python 3
python -m http.server 8000

# Node.js
npx serve .

# 然後在瀏覽器中訪問 http://localhost:8000
```

## 🔧 技術特點

- **🌐 純前端實現**：無需後端服務，完全基於現代瀏覽器 API
- **📱 響應式設計**：支援桌面端和行動端使用
- **🎨 現代化介面**：採用漸層設計和流暢動畫
- **⚡ 高效能**：使用 Canvas、MediaRecorder 等原生 API
- **🔒 隱私保護**：所有處理均在本地完成，無資料上傳

## 🌟 主要技術

- **WebRTC API** - 攝像頭和螢幕擷取
- **MediaRecorder API** - 媒體錄製
- **Canvas API** - 圖像處理和影片渲染
- **File API** - 檔案處理
- **Modern CSS** - 響應式佈局和動畫效果

## 📋 瀏覽器支援

| 功能 | Chrome | Firefox | Safari | Edge |
|------|--------|---------|--------|------|
| 攝像頭錄影 | ✅ | ✅ | ✅ | ✅ |
| 螢幕錄製 | ✅ | ✅ | ⚠️ | ✅ |
| 截圖工具 | ✅ | ✅ | ⚠️ | ✅ |
| 影片裁切 | ✅ | ✅ | ⚠️ | ✅ |

> ⚠️ Safari 對某些 API 支援有限，建議使用 Chrome 或 Firefox 以獲得最佳體驗

## 🤝 貢獻指南

歡迎提交 Issues 和 Pull Requests！

1. Fork 此倉庫
2. 創建您的功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 開啟一個 Pull Request

## 📄 授權條款

本專案採用 MIT 授權條款 - 查看 [LICENSE](LICENSE) 檔案了解詳情

## 🙏 致謝

- 感謝所有貢獻者的付出
- 靈感來源於現代 Web 技術的強大能力
- 特別感謝開源社群的支持

## 📞 聯絡方式

如有任何問題或建議，歡迎：
- 開啟 [Issue](https://github.com/ZhengXueTech/web-media-tools/issues)
- 發送郵件至：vvv9509@gmail.com
- 關注我的 GitHub：[ZhengXueTech](https://github.com/ZhengXueTech)

---

⭐ 如果這個專案對您有幫助，請給它一個星星！
