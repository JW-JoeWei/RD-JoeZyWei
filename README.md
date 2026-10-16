# RD-JoeZyWei · 市場研究報告

Joe.zy.wei 的 Report Dashboard（GitHub Pages，由 `main` 分支根目錄發佈；原名 `Research_Reports_AI-Gen`，2026-10-16 改名）。

**公開網址：https://jw-joewei.github.io/RD-JoeZyWei/**

全部內容由 AI 生成，僅供參考！

## 分類

**Server industry**／**Job opportunity**／**Industry events**（報告的 `cat` 欄位之後補上）。

## 結構

- 入口頁 `index.html` 的 `REPORTS` 陣列列出所有報告。
- `reports.json` 是給 All-RD（Daddy Joe 的五合一 Report Dashboard）讀取的清單，新增報告時與 `REPORTS` 一起更新。
- 報告放在 `reports/<YYYY-MM-DD>_<slug>/index.html`；日期格式固定 `YYYY-MM-DD`，同一主題重新抓取時新增新日期的項目。
