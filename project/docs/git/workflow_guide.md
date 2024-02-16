# 專案名稱

此專案旨在簡化版本控制流程，提高團隊的開發效率和程式碼品質。

## 流程概述

在本專案中，我們採用了簡化版的 GitLab Flow，以便更好地適應團隊的需求和專案的特性。

### GitLab Flow（簡化版）

我們所採用的方式包括以下幾個主要分支：

- **上線分支 (main)**:
   - 作為穩定的上線版本，用於生產環境部署。

- **版本分支 (vx.x.x)**:
   - 遵循語意化版本控制（Semantic Versioning）制定版本號。
   - 根據版本號規劃各階段的主要功能。

- **開發分支 (developer_name)**:
   - 依照開發者名字建立的開發分支。
   - 在每一個版本分支下單獨運作，確保程式碼的隔離和版本控制。

## 版本控制

### 語意化版本控制（Semantic Versioning）

版本號由三個部分組成：主版本號、次版本號和修訂號。 具體意義如下：

- **主版本號 (Major)**:
   - 改版，可能導致與先前版本不相容的重大變更。

- **次版本號 (Minor)**:
   - 功能，定期推出新功能。

- **修訂號 (Patch)**:
   - 補丁，修復一些小錯誤。

## Git Flow vs GitHub Flow vs GitLab Flow

- **Git Flow**
   - Git Flow 包含兩個主要分支和三個輔助分支，複雜度較高，適用於大型專案。

- **GitHub Flow**
   - GitHub Flow 主要整合在主要分支，適用於快速迭代和持續部署的小型專案。

- **GitLab Flow**
   - GitLab Flow 採用多個環境的測試方式，並根據上游優先不斷部署到下游環境中，適用於中等規模的專案。

- **GitLab Flow（簡化版）**
   - 相較於 Git Flow 和 GitHub Flow，我們採用了更簡化的 GitLab Flow，保留了主要分支和版本分支，以解決固定上線的審核拖延問題。

## 使用指南

以下是使用本項目的簡單指南：

1. 克隆倉庫到本地環境。
2. 在開發分支上進行開發工作。
3. 在提交程式碼之前，請確保程式碼通過了本地測試。
4. 合併開發分支到版本分支，並解決衝突（如果有）。
5. 在版本分支上進行測試，並確保功能完整。
6. 合併版本分支到上線分支，準備部署到生產環境。

## 貢獻

如果您對該專案有任何建議或意見，請隨時提出 issue 或提交 pull request，我們非常歡迎您的貢獻。

## 許可證

本項目採用 [AGPL 3.0 許可證](https://github.com/Yippine/fairy-tale-factory?tab=AGPL-3.0-1-ov-file#readme) 進行許可。

## 聯絡我們

如果您有任何疑問或需求，可以透過以下方式聯絡我們：

- 信箱：Olange.stone@gmail.com