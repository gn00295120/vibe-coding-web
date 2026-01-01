# Changelog / 更新日誌

All notable changes to VibeCoding Scrum will be documented in this file.

所有 VibeCoding Scrum 的重要變更都會記錄在此檔案中。

The format is based on [Keep a Changelog](https://keepachangelog.com/).

---

## [Unreleased] / 開發中

### Coming Soon / 即將推出
- Performance optimizations / 效能優化
- Enhanced search functionality / 增強搜尋功能

---

## [1.0.0] - 2025-01-01

### Added / 新增
- **Popularity Pool** / **人氣池**
  - Free task submission from public GitHub repositories / 免費提交公開 GitHub 儲存庫任務
  - Community voting via likes / 社群點讚投票
  - Task sorting by popularity / 依人氣排序任務
  - Search and filtering capabilities / 搜尋與篩選功能

- **Scrum Board** / **Scrum 看板**
  - Three-column Kanban: Waiting → In Progress → Completed / 三欄式看板
  - Drag-and-drop task management / 拖放式任務管理
  - Task status tracking / 任務狀態追蹤

- **Showcase System** / **成果展示系統**
  - Display completed tasks with PR and demo links / 展示已完成任務的 PR 和 Demo 連結
  - Maintainer notes and limitations / 維護者筆記與限制說明
  - Task completion celebration / 任務完成慶祝

- **Monetization** / **付費功能**
  - Promote ($24.99) - Move task to Scrum Board / 推進 - 將任務移至看板
  - Sponsor ($24.99+) - Support tasks on the board / 贊助 - 支持看板上的任務
  - Like ($4.99) - Thank maintainers / 喜歡 - 感謝維護者
  - Stripe payment integration / Stripe 付款整合

- **User Features** / **使用者功能**
  - Google OAuth authentication / Google OAuth 認證
  - My Tasks dashboard / 我的任務儀表板
  - Repository ownership verification / 儲存庫所有權驗證
  - Multi-language support (English/繁體中文) / 多語言支援

- **Maintainer Panel** / **維護者面板**
  - Claimable tasks view / 可認領任務視圖
  - Task claiming and management / 任務認領與管理
  - Showcase creation and editing / 成果建立與編輯
  - Admin comments / 管理員評論

- **Transparency** / **透明度**
  - 60-day experiment countdown / 60天實驗倒數
  - Real-time statistics / 即時統計數據
  - Public showcase of all results / 公開展示所有結果

- **SEO & Accessibility** / **SEO 與無障礙**
  - Schema.org structured data / 結構化資料
  - Sitemap with lastmod dates / 含更新日期的 Sitemap
  - Responsive design / 響應式設計
  - Dark mode support / 深色模式支援

### Technical / 技術
- React 18 + TypeScript frontend / React 18 + TypeScript 前端
- Vite build system / Vite 建構系統
- TailwindCSS + shadcn/ui styling / TailwindCSS + shadcn/ui 樣式
- TanStack Query for server state / TanStack Query 伺服器狀態管理
- Supabase backend (PostgreSQL + Auth) / Supabase 後端
- Stripe payment processing / Stripe 付款處理

---

## How to Read This Changelog / 如何閱讀更新日誌

- **Added** / **新增**: New features / 新功能
- **Changed** / **變更**: Changes in existing functionality / 現有功能的變更
- **Deprecated** / **棄用**: Features that will be removed / 即將移除的功能
- **Removed** / **移除**: Features that have been removed / 已移除的功能
- **Fixed** / **修復**: Bug fixes / 錯誤修復
- **Security** / **安全性**: Security-related changes / 安全性相關變更

---

[Unreleased]: https://github.com/gn00295120/vibe-coding-web/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/gn00295120/vibe-coding-web/releases/tag/v1.0.0
