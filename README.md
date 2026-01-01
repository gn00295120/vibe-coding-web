# VibeCoding Scrum

<div align="center">

<img src="https://vibe.lucas-futures.com/og-image.png" alt="VibeCoding Scrum" width="600">

### 一個開放工程的社群實驗 | A Community Experiment in Open Engineering

**No guarantees. No obligations. Just vibes and code.**

[English](#english) | [繁體中文](#繁體中文)

[![Website](https://img.shields.io/badge/Website-vibe.lucas--futures.com-00D4AA?style=for-the-badge&logo=google-chrome&logoColor=white)](https://vibe.lucas-futures.com/)
[![Status](https://img.shields.io/badge/Status-60_Day_Experiment-FF6B6B?style=for-the-badge)](https://vibe.lucas-futures.com/)
[![License](https://img.shields.io/badge/License-Proprietary-6C757D?style=for-the-badge)](#license)

[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Supabase](https://img.shields.io/badge/Supabase-Backend-3FCF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/)

---

[**Visit Website**](https://vibe.lucas-futures.com/) | [**View Showcases**](https://vibe.lucas-futures.com/showcases) | [**Submit Task**](https://vibe.lucas-futures.com/submit) | [**Report Issue**](../../issues/new/choose)

</div>

---

<a id="繁體中文"></a>
## 繁體中文

### 關於專案

**VibeCoding Scrum** 是一個為期 60 天的公開實驗，旨在探索社群驅動的開源專案資助與展示模式。

> 沒有保證、沒有義務——只有氛圍與程式碼。

這是一個讓開發者可以提交他們的 GitHub 開源專案，透過社群投票獲得關注，並可能獲得資助與實作的平台。

### 功能預覽

| 人氣池 Pool | Scrum 看板 | 成果展示 |
|:---:|:---:|:---:|
| 免費提交任務 | 追蹤開發進度 | 展示完成成果 |

### 核心功能

#### 1. 人氣池 (Popularity Pool)
- **免費提交**：連結你的公開 GitHub 儲存庫
- **社群投票**：透過點讚決定什麼值得關注
- **排名機制**：最活躍的任務會上升到頂部

#### 2. Scrum 看板 (Scrum Board)
- **三欄式看板**：等待中 → 進行中 → 已完成
- **任務追蹤**：透明化的開發進度
- **拖放管理**：直覺的任務狀態更新

#### 3. 成果展示 (Showcases)
- **PR 連結**：展示實際的 Pull Request
- **Demo 連結**：線上展示成果
- **維護者筆記**：說明實作細節與限制

### 付費選項

| 類型 | 價格 | 說明 |
|------|------|------|
| **推進 (Promote)** | $24.99 | 將任務從人氣池移至 Scrum 看板 |
| **贊助 (Sponsor)** | $24.99+ | 對任務的純支持，可多次購買 |
| **喜歡 (Like)** | $4.99 | 感謝已完成任務的維護者 |

> ⚠️ **重要提醒**：所有付款均為最終付款且**不退款**。付款是支持的表達，而非購買保證服務。

### 使用教學

#### 提交任務

1. **登入**：使用 Google 帳號登入
2. **填寫資訊**：提供公開 GitHub 儲存庫網址和描述
3. **驗證所有權**：在儲存庫中添加驗證檔案
4. **發布**：任務進入人氣池

#### 推進任務

1. 瀏覽人氣池中的任務
2. 點擊「推進到看板」按鈕
3. 完成 $24.99 付款
4. 任務進入 Scrum 看板的「等待中」狀態

#### 查看成果

1. 前往「成果展」頁面
2. 瀏覽已完成的任務
3. 查看 PR、Demo 連結和維護者筆記

### 核心原則

- **沒有保證**：任務可能永遠不會被處理或完成
- **不退款**：所有付款都是最終的
- **僅限公開**：只支援公開的 GitHub 儲存庫
- **無高成本功能**：避免會產生持續基礎設施成本的功能

### 技術架構

| 類別 | 技術 |
|------|------|
| **前端框架** | React 18 + TypeScript |
| **建構工具** | Vite |
| **樣式** | TailwindCSS + shadcn/ui |
| **狀態管理** | TanStack Query + React Context |
| **後端服務** | Supabase (PostgreSQL + Auth) |
| **付款處理** | Stripe |
| **部署** | 雲端託管 |

### 常見問題

<details>
<summary><strong>有任何保證我的任務會被完成嗎？</strong></summary>

沒有。這是一個為期 60 天的公開實驗，零保證。任務可能永遠不會被認領、可能部分完成，或可能不符合你的期望。
</details>

<details>
<summary><strong>可以退款嗎？</strong></summary>

不可以。所有付款（推進、贊助、喜歡）都是最終的且不退款。
</details>

<details>
<summary><strong>為什麼只支援公開的 GitHub 儲存庫？</strong></summary>

1. 我們不想存取你的私有程式碼
2. 保持實驗的透明度
3. 符合開源原則
</details>

<details>
<summary><strong>如何驗證儲存庫所有權？</strong></summary>

在提交任務時，你需要在儲存庫中添加一個小型 JSON 檔案。這證明你有寫入權限。驗證是一次性的，發布後可以移除該檔案。
</details>

<details>
<summary><strong>60 天實驗結束後會發生什麼？</strong></summary>

我們將發布一份完整的透明報告，包含所有結果、指標和學習心得。平台的未來將根據結果決定。
</details>

### 問題回報

如果你遇到任何問題或有任何建議，歡迎透過以下方式聯繫我們：

- **Bug 回報**：[提交 Bug Report](../../issues/new?template=bug_report.md)
- **功能建議**：[提交 Feature Request](../../issues/new?template=feature_request.md)
- **問題諮詢**：[提交問題](../../issues/new?template=question.md)
- **網站聯絡頁**：[聯絡我們](https://vibe.lucas-futures.com/contact)

---

<a id="english"></a>
## English

### About

**VibeCoding Scrum** is a 60-day public experiment exploring community-driven open source project funding and showcasing.

> No guarantees, no obligations—just vibes and code.

A platform where developers can submit their GitHub open source projects, gain attention through community voting, and potentially receive funding and implementation.

### Feature Preview

| Popularity Pool | Scrum Board | Showcases |
|:---:|:---:|:---:|
| Submit tasks for free | Track development | Display results |

### Core Features

#### 1. Popularity Pool
- **Free Submission**: Link your public GitHub repository
- **Community Voting**: Likes determine what gets attention
- **Ranking System**: Most active tasks rise to the top

#### 2. Scrum Board
- **Three-Column Board**: Waiting → In Progress → Completed
- **Task Tracking**: Transparent development progress
- **Drag & Drop**: Intuitive status updates

#### 3. Showcases
- **PR Links**: Display actual Pull Requests
- **Demo Links**: Live demonstration of results
- **Maintainer Notes**: Implementation details and limitations

### Payment Options

| Type | Price | Description |
|------|-------|-------------|
| **Promote** | $24.99 | Move task from Pool to Scrum Board |
| **Sponsor** | $24.99+ | Pure support for tasks, can be purchased multiple times |
| **Like** | $4.99 | Thank maintainers for completed tasks |

> ⚠️ **Important**: All payments are final and **non-refundable**. Payments are expressions of support, not purchases of guaranteed services.

### How to Use

#### Submit a Task

1. **Login**: Sign in with Google
2. **Fill Details**: Provide public GitHub repository URL and description
3. **Verify Ownership**: Add verification file to your repository
4. **Publish**: Task enters the Popularity Pool

#### Promote a Task

1. Browse tasks in the Popularity Pool
2. Click "Promote to Board" button
3. Complete $24.99 payment
4. Task enters "Waiting" status on Scrum Board

#### View Showcases

1. Go to "Showcases" page
2. Browse completed tasks
3. View PR, Demo links and maintainer notes

### Core Principles

- **No Guarantees**: Tasks may never be processed or completed
- **No Refunds**: All payments are final
- **Public Only**: Only public GitHub repositories are supported
- **No High-Cost Features**: We avoid functionality that creates ongoing infrastructure costs

### Tech Stack

| Category | Technology |
|----------|------------|
| **Frontend** | React 18 + TypeScript |
| **Build Tool** | Vite |
| **Styling** | TailwindCSS + shadcn/ui |
| **State Management** | TanStack Query + React Context |
| **Backend** | Supabase (PostgreSQL + Auth) |
| **Payments** | Stripe |
| **Deployment** | Cloud Hosted |

### FAQ

<details>
<summary><strong>Is there any guarantee my task will be completed?</strong></summary>

No. This is a 60-day public experiment with zero guarantees. Tasks may never be picked up, may be partially completed, or may not meet your expectations.
</details>

<details>
<summary><strong>Can I get a refund?</strong></summary>

No. All payments (Promote, Sponsor, Like) are final and non-refundable.
</details>

<details>
<summary><strong>Why only public GitHub repositories?</strong></summary>

1. We don't want access to your private code
2. Keeps the experiment transparent
3. Aligns with open-source principles
</details>

<details>
<summary><strong>How do I verify repository ownership?</strong></summary>

During task submission, you'll be asked to add a small JSON file to your repo. This proves you have write access. The verification is one-time and the file can be removed after publishing.
</details>

<details>
<summary><strong>What happens after the 60-day experiment?</strong></summary>

We'll publish a full transparency report with all outcomes, metrics, and learnings. The future of the platform will be decided based on results.
</details>

### Report Issues

If you encounter any issues or have suggestions, please reach out through:

- **Bug Reports**: [Submit Bug Report](../../issues/new?template=bug_report.md)
- **Feature Requests**: [Submit Feature Request](../../issues/new?template=feature_request.md)
- **Questions**: [Ask a Question](../../issues/new?template=question.md)
- **Website Contact**: [Contact Us](https://vibe.lucas-futures.com/contact)

---

## License

This repository is for public information and issue tracking only. The source code is proprietary and not included here.

**Operated by**: Lucas Quant Trading LLC

---

<div align="center">

**60-Day Public Experiment • All outcomes are published transparently**

[Visit Website](https://vibe.lucas-futures.com/) | [Report Issue](../../issues/new/choose)

</div>
