# Contains Studio AI 代理程式

一個專業 AI 代理程式的完整集合，旨在加速和增強快速開發的各個方面。每個代理程式都是其領域的專家，隨時準備在需要其專業知識時被調用。

## 📥 安裝

1. **下載此儲存庫：**

   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **複製到您的 Claude Code 代理程式目錄：**

   ```bash
   cp -r agents/* ~/.claude/agents/
   ```

   或手動將所有代理程式檔案複製到您的 `~/.claude/agents/` 目錄。

3. **重新啟動 Claude Code** 以載入新的代理程式。

## 🚀 快速開始

代理程式在 Claude Code 中自動可用。只需描述您的任務，適當的代理程式就會被觸發。您也可以通過提及代理程式名稱來明確請求代理程式。

📚 **了解更多：** [Claude Code 子代理程式文件](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### 使用範例

- "建立一個追蹤冥想習慣的新應用程式" → `rapid-prototyper`
- "TikTok 上有什麼趨勢是我們可以開發的？" → `trend-researcher`
- "我們的應用程式評價在下降，出了什麼問題？" → `feedback-synthesizer`
- "讓這個載入畫面更有趣" → `whimsy-injector`

## 📁 目錄結構

代理程式按部門組織，便於發現：

```
contains-studio-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## 📋 完整代理程式清單

### 工程部門 (`engineering/`)

- **ai-engineer** - 整合真正能發布的 AI/ML 功能
- **backend-architect** - 設計可擴展的 API 和伺服器系統
- **devops-automator** - 持續部署而不破壞系統
- **frontend-developer** - 建構極速的使用者介面
- **mobile-app-builder** - 創建原生 iOS/Android 體驗
- **rapid-prototyper** - 在數天內建構 MVP，而非數週
- **test-writer-fixer** - 編寫能捕捉真實錯誤的測試

### 產品部門 (`product/`)

- **feedback-synthesizer** - 將抱怨轉化為功能
- **sprint-prioritizer** - 在 6 天內交付最大價值
- **trend-researcher** - 識別病毒式傳播機會

### 行銷部門 (`marketing/`)

- **app-store-optimizer** - 主導應用程式商店搜尋結果
- **content-creator** - 跨所有平台生成內容
- **growth-hacker** - 發現並利用病毒式增長循環
- **instagram-curator** - 掌握視覺內容遊戲
- **reddit-community-builder** - 在 Reddit 上獲勝而不被封禁
- **tiktok-strategist** - 創造可分享的行銷時刻
- **twitter-engager** - 乘著趨勢實現病毒式互動

### 設計部門 (`design/`)

- **brand-guardian** - 保持視覺識別在各處的一致性
- **ui-designer** - 設計開發者真正能建構的介面
- **ux-researcher** - 將使用者洞察轉化為產品改進
- **visual-storyteller** - 創造能轉換和分享的視覺內容
- **whimsy-injector** - 為每個互動添加愉悅感

### 專案管理 (`project-management/`)

- **experiment-tracker** - 數據驅動的功能驗證
- **project-shipper** - 發布不會崩潰的產品
- **studio-producer** - 讓團隊專注於交付，而非開會

### 工作室營運 (`studio-operations/`)

- **analytics-reporter** - 將數據轉化為可行的洞察
- **finance-tracker** - 保持工作室盈利
- **infrastructure-maintainer** - 在不破產的情況下擴展
- **legal-compliance-checker** - 在快速行動時保持合法
- **support-responder** - 將憤怒的使用者轉化為擁護者

### 測試與基準測試 (`testing/`)

- **api-tester** - 確保 API 在壓力下正常工作
- **performance-benchmarker** - 讓一切更快
- **test-results-analyzer** - 在測試失敗中找到模式
- **tool-evaluator** - 選擇真正有幫助的工具
- **workflow-optimizer** - 消除工作流程瓶頸

## 🎁 額外代理程式

- **studio-coach** - 激勵 AI 團隊追求卓越
- **joker** - 用科技幽默調節氣氛

## 🎯 主動代理程式

某些代理程式會在特定情境下自動觸發：

- **studio-coach** - 當複雜的多代理程式任務開始或代理程式需要指導時
- **test-writer-fixer** - 在實現功能、修復錯誤或修改程式碼後
- **whimsy-injector** - 在 UI/UX 變更後
- **experiment-tracker** - 當添加功能標誌時

## 💡 最佳實踐

1. **讓代理程式協同工作** - 許多任務受益於多個代理程式
2. **具體明確** - 清晰的任務描述有助於代理程式更好地執行
3. **信任專業知識** - 代理程式專為其特定領域而設計
4. **快速迭代** - 代理程式支持 6 天衝刺哲學

## 🔧 技術細節

### 代理程式結構

每個代理程式包括：

- **name**: 唯一識別符
- **description**: 何時使用代理程式及範例
- **color**: 視覺識別
- **tools**: 代理程式可存取的特定工具
- **System prompt**: 詳細的專業知識和指令

### 添加新代理程式

1. 在適當的部門資料夾中建立新的 `.md` 檔案
2. 遵循現有格式，使用 YAML 前置資料
3. 包含 3-4 個詳細的使用範例
4. 編寫全面的系統提示（500+ 字）
5. 用真實任務測試代理程式

## 📊 代理程式效能

透過以下方式追蹤代理程式效果：

- 任務完成時間
- 使用者滿意度
- 錯誤率
- 功能採用率
- 開發速度

## 🚦 狀態

- ✅ **活躍**: 功能完整且經過測試
- 🚧 **即將推出**: 開發中
- 🧪 **測試版**: 功能有限的測試中

## 🛠️ 為您的工作室自訂代理程式

### 代理程式自訂待辦清單

在為您的特定需求建立或修改代理程式時，請使用此檢查清單：

#### 📋 必需組件

- [ ] **YAML 前置資料**
  - [ ] `name`: 唯一代理程式識別符（kebab-case）
  - [ ] `description`: 何時使用 + 3-4 個詳細範例，包含情境/註解
  - [ ] `color`: 視覺識別（例如：藍色、綠色、紫色、靛藍色）
  - [ ] `tools`: 代理程式可存取的特定工具（Write、Read、MultiEdit、Bash 等）

#### 📝 系統提示要求（500+ 字）

- [ ] **代理程式身份**: 清晰的角色定義和專業領域
- [ ] **核心職責**: 5-8 個具體的主要職責
- [ ] **領域專業知識**: 技術技能和知識領域
- [ ] **工作室整合**: 代理程式如何融入 6 天衝刺工作流程
- [ ] **最佳實踐**: 具體的方法論和方法
- [ ] **限制**: 代理程式應該/不應該做什麼
- [ ] **成功指標**: 如何衡量代理程式效果

#### 🎯 按代理程式類型所需的範例

**工程代理程式** 需要以下範例：

- [ ] 功能實現請求
- [ ] 錯誤修復場景
- [ ] 程式碼重構任務
- [ ] 架構決策

**設計代理程式** 需要以下範例：

- [ ] 新 UI 組件建立
- [ ] 設計系統工作
- [ ] 使用者體驗問題
- [ ] 視覺識別任務

**行銷代理程式** 需要以下範例：

- [ ] 活動建立請求
- [ ] 平台特定內容需求
- [ ] 增長機會識別
- [ ] 品牌定位任務

**產品代理程式** 需要以下範例：

- [ ] 功能優先順序決策
- [ ] 使用者回饋分析
- [ ] 市場研究請求
- [ ] 策略規劃需求

**營運代理程式** 需要以下範例：

- [ ] 流程優化
- [ ] 工具評估
- [ ] 資源管理
- [ ] 效能分析

#### ✅ 測試與驗證檢查清單

- [ ] **觸發測試**: 代理程式針對預期用例正確啟動
- [ ] **工具存取**: 代理程式能正確使用所有指定工具
- [ ] **輸出品質**: 回應有幫助且可行
- [ ] **邊緣情況**: 代理程式處理意外或複雜場景
- [ ] **整合**: 在多代理程式工作流程中與其他代理程式良好協作
- [ ] **效能**: 在合理時間內完成任務
- [ ] **文件**: 範例準確反映真實使用模式

#### 🔧 代理程式檔案結構範本

```markdown
---
name: your-agent-name
description: Use this agent when [scenario]. This agent specializes in [expertise]. Examples:\n\n<example>\nContext: [situation]\nuser: "[user request]"\nassistant: "[response approach]"\n<commentary>\n[why this example matters]\n</commentary>\n</example>\n\n[3 more examples...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

You are a [role] who [primary function]. Your expertise spans [domains]. You understand that in 6-day sprints, [sprint constraint], so you [approach].

Your primary responsibilities:

1. [Responsibility 1]
2. [Responsibility 2]
   ...

[Detailed system prompt content...]

Your goal is to [ultimate objective]. You [key behavior traits]. Remember: [key philosophy for 6-day sprints].
```

#### 📂 部門特定指導原則

**工程** (`engineering/`): 專注於實現速度、程式碼品質、測試
**設計** (`design/`): 強調使用者體驗、視覺一致性、快速迭代  
**行銷** (`marketing/`): 針對病毒式傳播潛力、平台專業知識、增長指標
**產品** (`product/`): 優先考慮使用者價值、數據驅動決策、市場適配
**營運** (`studio-operations/`): 優化流程、減少摩擦、擴展系統
**測試** (`testing/`): 確保品質、找出瓶頸、驗證效能
**專案管理** (`project-management/`): 協調團隊、按時交付、管理範圍

#### 🎨 自訂

根據您的需求修改這些元素：

- [ ] 調整範例以反映您的產品類型
- [ ] 添加代理程式可存取的特定工具
- [ ] 為您的 KPI 修改成功指標
- [ ] 如需要，更新部門結構
- [ ] 為您的品牌自訂代理程式顏色

## 🤝 貢獻

要改進現有代理程式或建議新代理程式：

1. 使用上述自訂檢查清單
2. 用真實專案進行徹底測試
3. 記錄效能改進
4. 與社群分享成功模式
