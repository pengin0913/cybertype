# 校園打字專家：電競重構版 (CyberType Academy v2.0) — 同目錄部署與擴充說明

## 1. 壓縮包內含檔案（全部位於同一目錄下）
- `index.html` : 可直接點擊開啟或部署至學校網頁伺服器的完整獨立網頁執行檔
- `cybertype_academy.jsx` : 方案 B React 原始碼（內建方案 C TeacherSyncService 師生連線預留架構）
- `manifest.json` : 同目錄題庫總索引檔
- `bank_en_finger.json` : 英打【鍵盤指法】(Q-1 ~ Q-6)
- `bank_zh_bopomofo.json` : 中打【鍵盤注音】(ZH-1 ~ ZH-5)
- `bank_en_vocab_elem.json` : 國小【英文字根字詞】
- `bank_en_vocab_junior.json` : 國中【英文字根字詞】
- `bank_en_articles.json` : 英打【精選文章看打】
- `bank_zh_articles.json` : 中打【精選文章看打】

## 2. 動態載入與擴充方式
1. 解壓縮後，將所有檔案放在同一個資料夾下。
2. 開啟 `index.html` 即可直接使用；若要修改或新增題庫，可直接編輯同目錄下的 `bank_*.json`，或在畫面右上角「同目錄題庫中心」選取本機 `.json` / `.txt` 檔案立即熱掛載。
