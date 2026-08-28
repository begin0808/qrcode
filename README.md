# Studio0808 QR Code 萬用工具箱 (All-in-One QR Code Toolkit)

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-emerald?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20Tablet-indigo?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Offline-100%25%20Client--Side-green?style=for-the-badge" alt="Offline Ready">
</p>

<p align="center">
  <b>現代化、全功能、極致美學的 QR Code 產生、美化、短網址、圖片轉換、解碼與批次處理工作台。</b><br>
  <i>A modern, aesthetic, all-in-one QR Code workstation for generation, styling, URL shortening, image hosting, decoding, and batch processing.</i>
</p>

<p align="center">
  🌐 <b>線上體驗 (Live Demo)</b>：<a href="https://begin0808.github.io/qrcode/">https://begin0808.github.io/qrcode/</a>
</p>

---

## 📖 目錄 / Table of Contents
- [繁體中文說明 (Traditional Chinese)](#-繁體中文說明)
  - [✨ 核心特色](#-核心特色)
  - [🚀 功能亮點](#-功能亮點)
  - [🔒 隱私與安全性](#-隱私與安全性)
  - [🛠️ 使用技術](#️-使用技術)
  - [📦 快速開始與部署](#-快速開始與部署)
- [English Documentation](#-english-documentation)
  - [✨ Features](#-features)
  - [🔒 Privacy & Offline Execution](#-privacy--offline-execution)
  - [🛠️ Tech Stack](#️-tech-stack)
  - [📦 Quick Start & Deployment](#-quick-start--deployment)
- [作者與版權 / Author & License](#-作者與版權--author--license)

---

## 🇹🇼 繁體中文說明

### ✨ 核心特色

**Studio0808 QR Code 萬用工具箱** 專為個人創作者、商家、行銷人員與開發者打造，提供免安裝、即開即用的全方位 QR Code 應用環境：

1. **🎨 頂級視覺美化與客製化**：
   - 支援 6 種點陣顆粒造型（經典方形、圓點、圓角、優雅古典、平滑圓弧、水滴超圓角）。
   - 3 種定位點邊框與內核造型。
   - 支援單色、線性漸層、徑向漸層與自訂漸層旋轉角度。
   - 獨立角落定位點調色。
   - 內建熱門社群 Logo（LINE、Facebook、Instagram、YouTube、GitHub）及支援自訂上傳 Logo 圖示。
   - 8 款預設高質感風格範本（經典黑白、翡翠科技、星幻炫紫、日落暮光、極光冰藍、奢華金箔、賽博螢光、甜心粉彩）一鍵套用。

2. **⚡ 8 大內容格式支援 & 智慧短網址**：
   - 支援：**網址 (URL)**、**純文字**、**Wi-Fi 連線分享**、**電子名片 (vCard)**、**Email 預設信件**、**電話/簡訊**、**社群個人頁面**、**Google 地圖導航**。
   - 整合**智慧短網址服務**，一鍵將落落長網址轉為超短連結，使 QR Code 點陣更稀疏、掃碼辨識更靈敏迅速。

3. **🖼️ 圖片一鍵轉 QR Code（免登入雲端圖片空間）**：
   - 拖曳或上傳海報、菜單、作品照片（支援 PNG, JPG, WebP, GIF），自動取得直連網址並轉換成專屬 QR Code。
   - 內建雙重高速圖片空間自動備援機制。

4. **📷 相機即時掃描與圖片/截圖解碼**：
   - 調用筆電視訊鏡頭或手機前後鏡頭進行即時動態掃描。
   - 支援本機上傳圖片解碼，更支援直接按下 <kbd>Ctrl + V</kbd> 貼上剪貼簿截圖秒速解碼。

5. **📦 批次大量產生與 ZIP 打包下載**：
   - 貼上多行文字或網址清單，一鍵瞬間批次產生數十至數百張 QR Code。
   - 支援自訂檔名前綴與一鍵打包為 ZIP 壓縮檔下載。

6. **🕒 本機歷史紀錄管理**：
   - 自動記錄操作歷史，隨時可一鍵複製或重新載入編輯，100% 存放於瀏覽器 LocalStorage，隱私不外洩。

7. **📱 完整響應式 (RWD) 與清新溫柔風主題**：
   - 手機、平板與電腦皆享有流暢操作體驗。
   - 預設「清新溫柔風」淺色模式，並支援一鍵切換「質感深色模式」。

---

### 🔒 隱私與安全性

* **100% 純前端本地端計算**：
  * QR Code 產生、美化渲染、解碼掃描、批次 ZIP 打包與歷史紀錄均在您個人的瀏覽器內部以 JavaScript 與 Canvas 運算完成。
  * 任何資料（包含 Wi-Fi 密碼、名片聯絡電話、文字備忘）絕不會上傳至任何後端資料庫，保障個人與企業隱私。

---

### 🛠️ 使用技術

* **HTML5 / CSS3 / Vanilla JavaScript**（無龐大框架負擔，極致秒開速度）
* **Tailwind CSS**（現代化 UI 元件與柔和毛玻璃主題設計）
* **QRCodeStyling.js**（高自由度漸層與幾何形狀 QR Code 渲染引擎）
* **ZXing-JS / Library**（多格式條碼與 QR Code 機器視覺解碼庫）
* **JSZip**（前端本地端無伺服器 ZIP 壓縮打包引擎）

---

### 📦 快速開始與部署

本專案為**零依賴純靜態單頁應用 (SPA)**：

1. **直接開啟**：
   - 下載專案後，直接使用任何瀏覽器（Chrome, Edge, Safari, Firefox）雙擊開啟 `index.html` 即可使用。
2. **部署至 GitHub Pages**：
   - 前往 GitHub 專案儲存庫的 **Settings ➔ Pages**。
   - 在 **Build and deployment / Branch** 選擇 `main` 分支與 `/ (root)` 目錄，點擊 **Save** 即可發布！

---

## 🇺🇸 English Documentation

### ✨ Features

**Studio0808 QR Code Toolkit** is an ultra-fast, aesthetic, and feature-packed web application for all your QR Code creation, styling, and scanning needs:

* **🎨 Advanced Styling & Customization**:
  * 6 Dot styles (Square, Dots, Rounded, Classy, Classy Rounded, Extra Rounded).
  * 3 Corner frame & dot options.
  * Solid colors, linear & radial gradients with customizable rotation angles.
  * Independent corner finder color customization.
  * Embedded popular brand icons (LINE, Facebook, Instagram, YouTube, GitHub) + custom logo upload with size and margin controls.
  * 8 Curated one-click style presets.
* **⚡ 8 Content Types & Smart URL Shortening**:
  * Supports URL, Plain Text, Wi-Fi Setup, vCard (Contact), Email, Phone/SMS, Social Links, and Google Maps location.
  * Built-in one-click URL shortener to reduce QR density for faster scanning.
* **🖼️ Image-to-QR Cloud Hosting**:
  * Upload posters, menus, or photos to get instant direct links and auto-generate QR codes.
* **📷 Real-time Camera Scanner & Clipboard Decoder**:
  * Live camera stream QR scanning with front/rear camera switching.
  * Image file decoding & instant clipboard (<kbd>Ctrl + V</kbd>) screenshot decoding powered by ZXing.
* **📦 Batch Generator & ZIP Exporter**:
  * Generate dozens of QR codes at once from multi-line text input.
  * Download all items bundled into a single ZIP archive.
* **🕒 Local History Management**:
  * Automatically saves recent generations with easy copy & reload actions.
* **📱 Fully Responsive Design & Fresh Gentle Light/Dark Mode**:
  * Optimized for mobile phones, tablets, and desktop workstations.

---

### 🔒 Privacy & Offline Execution

* **100% Client-Side Architecture**:
  * All QR generations, gradient rendering, decoding, and ZIP archiving are calculated locally within the user's browser.
  * Zero tracking, zero telemetry, and zero data sent to external servers for core operations.

---

### 🛠️ Tech Stack

* **Core**: HTML5, Vanilla JavaScript (ES6+)
* **Styling**: Tailwind CSS & Glassmorphism design tokens
* **QR Engine**: QRCodeStyling.js
* **Decoder**: @zxing/library
* **Archiver**: JSZip

---

### 📦 Quick Start & Deployment

1. **Local Usage**: Clone this repository and open `index.html` directly in any web browser.
2. **GitHub Pages**: Go to **Repository Settings ➔ Pages**, select the `main` branch with `/ (root)`, and click **Save**.

---

## 👨‍💻 作者與版權 / Author & License

* **Developer**: [Studio0808 智造實驗室](https://begin0808.github.io/studio0808/)
* **Contact & Feedback**: [✉ 寫信給我 (Email)](https://mail.google.com/mail/?view=cm&fs=1&to=begin0808@gmail.com&su=Studio0808%20QR%20Code%E8%90%AC%E7%94%A8%E5%B7%A5%E5%85%B7%E7%AE%B1%20%E2%80%94%20%E6%84%8F%E8%A6%8B%E5%9B%9E%E5%A0%B1)
* **License**: Released under the [MIT License](LICENSE).

© 2026 Studio0808 智造實驗室. All rights reserved.
