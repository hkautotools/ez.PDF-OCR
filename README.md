📄 OCR Smart Renamer (OCR 智能命名工具)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

🌐 Live Demo / 在線體驗

#English | #繁體中文

#English

A privacy-focused, browser-based PDF renaming tool. It uses OCR technology to extract specific text from PDF documents (such as Invoice Numbers, Dates, or Client Names) and renames them in batches according to your rules.

✨ Key Features
>Privacy First: 100% Client-side processing. Your documents never leave your browser.

>Visual Calibration: Draw recognition zones directly on the PDF canvas with your mouse.

>Regex Filtering: Use Regular Expressions to extract specific patterns (e.g., RO#:[A-Z0-9]+).

>Smart Suffixes: Support for dynamic tags like {date}, {time}, and {n} (index).

>Template System: Save and load settings for different document layouts.

>Batch Export: Process and download hundreds of files with customized filenames in one click.

🚀 How to Use
1.Launch: Visit hkautotools.github.io.

2.Upload: Drag and drop PDF files into the workspace.

3.Select Zone: Drag your mouse over the PDF area containing the target text.

4.Configure: Set your Regex patterns and filename suffixes.

5.Sync: Click "Apply to All" to update OCR results for the entire list.

6.Export: Review the new filenames and click "Start Batch Processing".


#繁體中文

這是一個純前端的 PDF 智能命名工具，專為解決辦公室重複性改名工作而設計。透過強大的 OCR（光學字元辨識）技術，您可以精確框選 PDF 中的資訊（如單號、日期、客戶名稱），並依據自定義規則批量重新命名檔案。

✨ 核心功能
>隱私安全：100% 瀏覽器端處理，檔案不會上傳到任何伺服器。

>精準框選：支援滑鼠直覺式拖曳，精確定位 PDF 上的辨識區域。

>正則過濾 (Regex)：自動過濾雜訊，提取符合格式的編號（如：RO#:ABC12345）。

>自動後綴：支援 {date}, {time}, {n} 等變數，自動產生流水號與時間標記。

>範本管理：儲存常用的座標與規則，下次使用一鍵套用。

>批量導出：支援同時處理數百份檔案，自動完成改名與下載。

🚀 使用流程
1.開啟網站：訪問 hkautotools.github.io。

2.匯入檔案：將多份 PDF 檔案拖放至上傳區。

3.座標校準：在畫布上框選欲辨識的欄位（如單據編號位置）。

4.設定規則：輸入 Regex 規則（例如：RO#:[A-Z]{3}\d{8}）與檔案後綴。

5.同步全案：點擊「套用至全部檔案」，系統將自動處理清單中的所有 PDF。

6.批量下載：確認預覽名稱正確後，點擊「開始批量改名下載」。


🛠 技術棧 / Tech Stack
PDF Core: pdf.js (High-fidelity rendering)

OCR Engine: Tesseract.js (Multi-language support)

Interface: Vanilla HTML5 / CSS3 / JavaScript

