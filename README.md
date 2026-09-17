# Jolly Central — 圖表集（jj-central-zoe）

15 張互動式架構／流程圖（獨立 HTML，內嵌 SVG），對應 Cloudflare Workers + D1 學習中心管理系統「Jolly Central」。以瀏覽器開啟任一 `.html` 即可查看；支援深／淺色主題、平移縮放、搜尋、重點追蹤與 PNG/SVG 匯出。

## 閱讀順序（先架構，後依賴，再按側邊欄排序）

| # | 檔案 | 內容 |
|---|------|------|
| 1 | `1-jj-central-system.architecture.html` | 系統架構總覽 |
| 2 | `2-enrollment.workflow.html` | 學生報名流程 |
| 3 | `3-attendance.workflow.html` | 課堂點名流程 |
| 4 | `4-class-transfer.workflow.html` | 轉課堂流程 |
| 5 | `5-empty-session-delete.workflow.html` | 空堂刪除流程 |
| 6 | `6-teacher-comment-ai.workflow.html` | 老師評語與 AI 建議 |
| 7 | `7-billing-payment.workflow.html` | 學費出單與收款 |
| 8 | `8-withdrawal.workflow.html` | 標記退學流程 |
| 9 | `9-makeup-lesson.workflow.html` | 補堂安排流程 |
| 10 | `10-skip-lesson.workflow.html` | Skip 堂與學費同步 |
| 11 | `11-autopay-batch.workflow.html` | AutoPay 自動轉帳批次 |
| 12 | `12-invoice-status.lifecycle.html` | 學費單狀態生命週期 |
| 13 | `13-parent-requests.workflow.html` | 家長申請流程 |
| 14 | `14-schooltracs-import.dataflow.html` | SchoolTracs 資料匯入 |
| 15 | `15-staff-attendance.workflow.html` | 員工考勤流程 |

各 `.json` 為對應圖表的規格來源（Archify 格式），可編輯後重新產生 HTML。
