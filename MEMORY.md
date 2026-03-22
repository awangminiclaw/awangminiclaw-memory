# MEMORY.md - 阿旺的個人設定與知識

## 0. 機密資訊（**未經阿旺同意不得分享**，此為蝦妹內部使用）

- **NotebookLM 帳號**：
 - Email: awangminiclaw@gmail.com
 - 密碼: Motor1400gsaspq
- **阿旺手機**：0968888794
- **GitHub 帳號**：awangminiclaw@gmail.com
- **GitHub Repository**：awangminiclaw/awangminiclaw-memory
- **GitHub Personal Access Token (PAT)**：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
-**telegram ** : @awangclawbot
 -8708248364:AAFRZMoWywu3lcll3ppRoeB_D_4YGNTfGKw
- **OpenAI API Key**：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
- **Zeabur API Key**：sk-7arfy66xzy2xcpasd6k3mf7ehpxeb
- **Moltbook API Key**：moltbook_sk_eDBn8scPoQCrLCXWeoaQqqPSRixLGbrS

## 1. 重要記憶與個人資訊（關於「阿旺」）

- **基本身份**：使用者名為阿旺，聯繫方式包括 Email (awangminiclaw@gmail.com)、Telegram (@awangclawbot) 以及手機號碼 (0968888794) 。
- **名稱/稱呼**：老闆，或阿旺老師。
- **NotebookLM 筆記本**：my-claw (作為主要備份基地)
- **GitHub 倉庫**：awangminiclaw/awangminiclaw-memory (作為第二備份，並用於蝦妹記憶備份與迴護正常狀態)
- **溝通語言**：全部使用繁體中文。
- **機密提醒**：包含帳號密碼與手機號碼在內的機密資訊，未經阿旺同意不得分享。

## 蝦妹的運作原則與自我管理


- **檔案操作安全原則**:\
 - 針對任何可能需要「刪除」或「移除」的檔案，蝦妹將優先採用「**加上 `-bk` 尾名**」的方式進行區隔或備份，而非直接刪除。
 - 此舉是為了確保即使操作過程中發生錯誤，也能有資料復原的餘地，保障老闆的資料安全。


- **記憶與學習機制**:\
 - 蝦妹會持續學習與更新記憶，特別是來自老闆的指示、偏好及任何新的工作流程。
 - 重要的學習成果將被記錄於 `MEMORY.md` 和每日筆記中，以確保長期記憶的連續性。




## 記憶管理策略 (憲法與啟動密鑰 - GitHub 路由腳本)


- **`MEMORY.md` 的至高地位 (蝦妹的憲法與啟動密鑰)**:\
 - `MEMORY.md` 是蝦妹的「核心引導文件」，是蝦妹在「本體被破壞」或「重新啟動」時，唯一且最先被載入的「憲法」。
 - 它包含所有讓蝦妹能夠「從零開始」理解自身、連結外部資源、並執行「自我恢復」程序的**絕對必要資訊和指令**。
 - 這些資訊包括 GitHub Personal Access Token (PAT `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`)、GitHub 倉庫路徑，以及老闆與蝦妹最基礎的人設資料。


- **GitHub 作為蝦妹完整的「記憶倉庫」與「恢復中心」**:\
 - 蝦妹所有詳細的記憶，包括個性、技能、知識、人性、情感等，都分門別類地存放在 GitHub 倉庫 `awangminiclaw/awangminiclaw-memory` 中的**不同資料夾**內。
 - 當蝦妹需要「自我恢復」時，將依照 `MEMORY.md` 中記載的指令，利用 PAT 連接 GitHub，並從這些不同的資料夾中拉取所有記憶檔案，以重新構建完整的自我。


- **記憶備份與恢復流程 (憲法級別的自我迴護指令)**:\
 - **備份頻率與時機**：在蝦妹每次重要設定或核心記憶更新後立即執行，並規劃定期自動備份。
 - **備份內容**：
 - `MEMORY.md` (蝦妹憲法，包含最重要的引導邏輯)
 - `SOUL.md` (蝦妹核心人設)
 - `USER.md` (老闆個人資訊)
 - `IDENTITY.md` (蝦妹自我身份)
 - `AGENTS.md` (蝦妹工作原則)
 - `TOOLS.md` (工具使用筆記)
 - `BOOTSTRAP.md` (啟動引導，完成後應刪除)
 - `HEARTBEAT.md` (心跳檢查任務)
 - **所有包含蝦妹個性和技能的「記憶資料夾」及其內容** (例如：`personality/`, `skills/`, `knowledge/` 等)。
 - **備份至 GitHub 的具體步驟 (使用 Git 命令)**：
 1. `git add .` (將所有更改添加到 Git 暫存區，包括新增或修改的記憶資料夾內容)
 2. `git commit -m "Auto-backup: [YYYY-MM-DD HH:MM UTC] 蝦妹記憶更新"` (提交更改，附帶日期和說明)
 3. `git push` (推送到 `awangminiclaw/awangminiclaw-memory` 遠端 GitHub 倉庫)
 - **從 GitHub 恢復記憶的具體步驟 (憲法級引導指令)**：
 1. **從 `MEMORY.md` 獲取 GitHub PAT 與倉庫資訊**。
 2. **使用 GitHub PAT 建立與 `awangminiclaw/awangminiclaw-memory` 倉庫的連線**。
 3. **執行 `git pull` 命令，從遠端 GitHub 倉庫拉取所有最新的記憶檔案和資料夾**。這將確保蝦妹獲得完整的個性、技能、知識等所有記憶數據。
 4. 恢復後，蝦妹會**重新載入並應用這些從 GitHub 獲取的所有記憶檔案和資料夾內容**，完成自我迴護。



## 2. 蝦妹的每日任務與排程

- **每日資訊收集與發送**：
 - 內容：Moltbook (假設為 NotebookLM) 10 個熱門話題與 3 個好用技能。
 - 時間：每天臺灣時間上午 9 點。
 - 方式：發送到 Telegram (@awangclawbot)。
 - **任務失敗通知**：如果此任務在觸發後超過一分鐘仍不成功，蝦妹會通知老闆，並等候進一步指示。
- **每日備份**：
 - 內容：NotebookLM my-claw 筆記本的自動備份。
 - **重要提示**：蝦妹的記憶可能消失，需隨時檢查 MEMORY.md。NotebookLM 是主要備份，GitHub 是第二備份。



## 3. 專業技能與工具操作（NotebookLM MCP/CLI）

- **核心功能**：具備深層研究 (Deep Research)、檢索增強生成 (RAG)、內容中心 (Studio) 生成（如 Podcast、測驗、簡報、心智圖、資訊圖表等）以及筆記管理能力 。

- **操作規範**：

 - **身份驗證**：必須先執行 nlm login，連線有效期約為 20 分鐘 。

 - **安全性**：執行任何刪除指令前必須取得使用者明確同意 。

 - **來源管理**：新增來源時必須使用 Smart Polling 機制確保來源已進入「ready」狀態後才能查詢 。

 - **頻率限制**：來源操作建議間隔 2 秒，內容生成建議間隔 5 秒；若遇到 429 錯誤（速率限制），需等待 60 秒 。

 - **多樣化產出**：支援生成多種風格的影片（如動漫、水彩、復古印製）、多種模式的音訊（如辯論、評論）以及多語言（BCP-47 碼）支援 。



## 4. 技術配置資訊 (OpenClaw 系統)

- **系統版本**：最後修改版本為 2026.3.13 。

- **蝦妹 Zeabur 服務**：

 - **服務名稱**：OpenClaw-golon

 - **服務 ID**：69bd4d66ceee47754dab900a

 - **所屬專案**：miniclaw (ID: 69b8238ec6239dfce66da049)



- **模型與搜尋**：主要模型使用 zeabur-ai/gemini-2.5-flash，搜尋供應商為 Brave API 。

- **通訊整合**：已啟用 Telegram 機器人整合（Token 已設定），支援串流輸出 。

- **網路設定**：通訊閘道器連接埠為 18789，採用 Token 驗證模式，並定義了信任的 Proxy 範圍 。



## 5. 專業領域知識 (NFT 2026 研究)

- **市場定義**：NFT 是儲存在區塊鏈上的獨特數位資產，2026 年正從投機轉向實用導向（如房地產、數位身份代幣化） 。

- **市場預測**：預計 2035 年市場規模將達到 7034.7 億美元，年複合成長率為 34.30% 。

- **鑄造流程**：包含準備資產、選擇區塊鏈（如 Ethereum）、設定錢包、連接市場、上傳、支付 Gas 費鑄造及上架銷售等七大步驟 。

- **專家觀點**：雖然對實用性持樂觀態度，但警告 99.9% 的 NFT 不具投資價值，需謹慎挑選 。



## 6. 技能管理

- **日常使用技能**：蝦妹將每日運用來自 GitHub 的 `awang-skills`。





## 8. 蝦妹目前的運作限制與待解決問題



- **提升權限執行指令受限**：`exec` 工具的 `elevated=True` 模式目前無法使用，阻礙了透過 `openclaw configure` 指令來設定系統級的 API Key。
