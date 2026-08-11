# Hot Aisle Inc. — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國）· 專員 US8664 Tuo Cheng · **日期：** 2026-08-11
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有持股，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之 GPU 型錄與定價、UCC 歸檔、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 密西根州 — Chicago Area = **T1**｜T2｜T11。一組可直接註冊。
**CRM 狀態：** 2026-08-11 於 salesleads Search（Type = All）實查為乾淨 — 無 lead、無 account、無 do-not-call。一組可註冊。

---

## 1. 結論摘要

Hot Aisle Inc. 是一家兩人編制、AMD 獨家的裸機 GPU 雲業者，以主機代管租戶身分，在密西根州 Grand Rapids 的 Switch「The Pyramid」園區內營運**單一生產叢集**——約 **16 台 Dell PowerEdge XE9680 機箱、搭載約 128 張 AMD Instinct MI300X**（[hotaisle.xyz/mi300x](https://hotaisle.xyz/mi300x)、[/datacenter](https://hotaisle.xyz/datacenter)，2026-08-11 讀取）。商業上，這是一個**針對下一世代的全新切入（greenfield displacement），不是既有客戶防守案，也不是平台轉換案**——查無任何證據顯示 Hot Aisle 曾經採購、評估或公開提及 Supermicro，同樣地，也沒有任何過往失單需要翻案。Dell 掌握既有機隊，而且掌握得理所當然：Hot Aisle 曾公開稱讚 Dell 為了一張「螺絲鬆掉」的 GPU 直接派兩名技師到場，並形容其支援「breathtaking」（[Cruising to the finish line，2024-09-13](https://hotaisle.xyz/blog/cruising-to-the-finish-line/)）。**不要試圖去搶這支機隊。**

真正打開的是**下一座**叢集。Hot Aisle 於 2026-07-14 把 MI300X 價格自 $1.99 調高到 $2.99／GPU／小時，理由是「at 100% capacity」且「有客戶排隊等候」（[Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)）；公司自述有 **「>$50 million in customer requests for MI355X capacity」**，並明白表示 **「The constraint is access to hardware, not demand for the platform.」**；同時正在募集 **$50–100M，管道為「equity, strategic investment, and asset finance」**，資金用途明載為「purchase AMD MI355X systems and fund the networking, rack integration, and site deployment」（[Investors 頁](https://hotaisle.xyz/investors)）。其自家 MI355X 頁面至今仍逐字寫著 **「We are still raising the capital required to buy and deploy the hardware」**（[/mi355x](https://hotaisle.xyz/mi355x)）——因此**平台尚未鎖定**，即使 Advizex 的案例研究說 MI355X 叢集會「working with Advizex every step of the way」建置（[Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle)）。**系統整合商的承諾，不等於機箱的承諾。**

最強的單一技術切入點是散熱。Hot Aisle 自家 MI355X 頁面載明 **每張加速卡 1,400 W，機櫃設計採直接液冷（direct liquid cooling）**——但他們是 Switch 的*租戶*，不掌握冷卻系統。Supermicro 除液冷版本外，另有出貨 **氣冷 10U 8× MI355X 系統**（[Supermicro 新聞稿](https://www.supermicro.com/en/pressreleases/supermicro-expands-its-portfolio-performance-and-efficiency-driven-air-cooled-ai)），這等於替一家資本受限、且公開表示唯一瓶頸就是「拿不到硬體」的公司，**從關鍵路徑上移除一個房東依賴**。這是能力論述，不是折扣論述。

有兩件事可能讓這筆生意破局。第一是**通路**：Advizex 是 Dell Titanium Solution Provider，曾主持四個月的每週規劃會議、在自家辦公室空間預備硬體，且已被明列為下一次建置的合作夥伴——一份只報機箱的報價，在完整度上必輸，不論單價多低。因此依 Rule 8，必須在第一次實質接觸**之前**先選定並註冊授權經銷／整合商。第二是**價格**：公開標價的 Supermicro 8× MI300X 平台為 **$275,863.87**（[Supermicro eStore](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html)），即**每張 GPU $34,483**，僅在模型中營運成本假設最寬鬆的一端才勉強通過 24 個月回收，18 個月則完全不通過（第 9 節）。**定價牌價無法拿下這個帳戶；能拿下的是融資結構與交期**——而他們自己把「asset finance」寫進募資管道，就是把這兩件事一併帶上桌的邀請函。

---

## 2. 公司速覽

| 欄位 | 內容 | 證據／日期 |
|---|---|---|
| **法人名稱** | **Hot Aisle Inc.** — 網站頁尾寫為「Hot Aisle, Inc.」，ARIN POC 組織欄寫為「Hot Aisle Inc」。**無 SEC 申報（私有持股）。** | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)（組織登記 2024-01-15T14:49:58-05:00，最後異動 2026-07-14T15:29:52-04:00）；網站頁尾「© 2026 Hot Aisle, Inc.」；[D&B 商業名錄](https://www.dnb.com/business-directory/company-profiles.hot_aisle_inc.6343b38590429aa36d4f33b58a5ecdf9.html) |
| **設立州別** | **UNVERIFIED — 研判為懷俄明州，屬推論而非查證。** 登記地址為 1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne, WY 82001 — 一個商業註冊代理人的私人信箱（PMB）。D&B 亦將該公司索引於懷俄明州 Cheyenne。**任何州登記入口皆無法觸及以確認設立州。** 德拉瓦州與密西根州均已嘗試、均告失敗（第 14 節） | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)；[D&B](https://www.dnb.com/business-directory/company-profiles.hot_aisle_inc.6343b38590429aa36d4f33b58a5ecdf9.html)。**GAP：任何州皆未取得一手登記文件** |
| **已取得之登記證據** | **無任何公司登記機關文件。** 現有最佳佐證為：(1) ARIN 組織紀錄——ARIN 要求組織就法定名稱與地址作出聲明；(2) D&B 索引條目；(3) 網站頁尾。**未能取得任何幹部、董事、註冊代理人姓名、年報簽署人或申報歷史** | [rdap.arin.net/registry/entity/HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **創立時間** | **2023 年 10 月** | 公司自家 [About 頁](https://hotaisle.xyz/about/) 與多個第三方檔案。並由網域建立時間獨立佐證：hotaisle.xyz 建立於 **2023-10-18T06:14:34Z**、hotaisle.ai 建立於 **2023-10-18T06:14:37Z** — 相隔三秒，同一註冊商 Spaceship, Inc.（[RDAP](https://rdap.centralnic.com/xyz/domain/hotaisle.xyz)） |
| **總部** | **全網未公布任何街道總部，且研判為刻意為之。** 存在三個彼此不同的地址，**絕不可混為一談**：(1) **公司／登記地址** — 1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne, WY 82001，是註冊代理人的收信信箱，*不是辦公室*；(2) **生產設施** — 密西根州 Grand Rapids／Caledonia 的 Switch「The Pyramid」園區，Hot Aisle 在此為**主機代管租戶**；(3) **人** — 兩位主事者研判皆為遠距，且**不在密西根**（FEC 將 Clint Armstrong 記於 Grantham, NH 03753；一筆 W3BCloud 任職的 Jon Stevens 記於 Entiat, WA 98822）。聯絡方式僅有電子郵件 | [/datacenter](https://hotaisle.xyz/datacenter)；[/contact](https://hotaisle.xyz/contact)；[ARIN HA-716](https://rdap.arin.net/registry/entity/HA-716)；[Switch Grand Rapids](https://www.switch.com/grand-rapids/)；[FEC 雇主檢索](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle) |
| **所有權** | **創辦人主導；受益所有權與股權比例＝GAP。** 據報有 **Mesh.xyz** 支持——由以太坊共同創辦人 **Joseph Lubin** 創立之 web3 孵化／投資機構——但**查無輪次規模、日期、持股比例、董事會組成或股權結構**，且**現行募資未找到任何公告**。Crunchbase 回 HTTP 403 | [gen.xyz 專訪](https://gen.xyz/blog/hotaisle-xyz)；[Investors 頁](https://hotaisle.xyz/investors)。**GAP — 投資人資訊稀薄** |
| **員工數** | **1–10 人——實質為 2 位全職主事者，加上外包與合作夥伴人力支援（第三方估計區間，非公司陳述）** | D&B 與 LinkedIn 均顯示 1–10 區間（[D&B](https://www.dnb.com/business-directory/company-profiles.hot_aisle_inc.6343b38590429aa36d4f33b58a5ecdf9.html)）。佐證：[About 頁](https://hotaisle.xyz/about/) 僅列兩人；[GitHub 組織](https://github.com/hotaisle) 顯示「no public members」，且僅有兩位 hotaisle 網域的提交者；ARIN 將**全部六個** POC 角色收攏到同一個共用信箱；Advizex 明載提供「personnel and staff augmentation」；**全網查無任何徵才啟事**。Investors 頁自述：「With experienced operators directing it, AI gives a small team unusual leverage」 |
| **營收** | **未揭露——僅為推導估計值，不得作為事實登錄。** 以 128 張 GPU × 8,760 小時 × 100% 使用率計：舊約 $1.99 為 **$2.23M／年**、新客 $2.99 為 **$3.35M／年**、裸機 $3.39 為 **$3.80M／年**。合理混合區間為 **$2.2M–$3.8M 年化**，2026 年舊約客戶逐步轉出期間最可能落在 **$2.5M–$3.2M**。**CRM $100M 門檻判定：公開資料完全不支持 $100M+ 之描述。** 注意：**「>$50M MI355X 客戶需求」屬前瞻 pipeline，不是營收**，絕不可當成營收引用 | 模型僅取用 [/pricing](https://hotaisle.xyz/pricing) 公開價格與 [/mi300x](https://hotaisle.xyz/mi300x) 的 128 GPU 數字。公司從未公布營收、ARR、毛利或成本資料 |
| **ASN** | **AS21566**，ARIN 代號 **HOTAISLE**，狀態 Active，登記於 **2024-02-14T11:05:57-05:00**，隸屬 Org HA-716。IPv4 **23.183.40.0/24**（NET-23-183-40-0-1，「HA-4-10」）；IPv6 **2602:f955::/36**（NET6-2602-F955-1，「HA-SOPH」） | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)。注意：**網路建置比硬體早了七個月** |
| **PeeringDB** | **查無紀錄——這是一個有意義的負面發現。** 以名稱含「Hot Aisle」查詢 PeeringDB API 回傳**空的 data 陣列**。無 IX 進駐、無 peering 政策、無設施清單、無流量揭露、無 peering 聯絡人姓名 | [peeringdb.com/api/net?name\_\_contains=Hot Aisle](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle) |
| **認證** | SOC 2 Type 1（2025-07-01）、SOC 2 Type 2（2025-09-18）、HIPAA | [gen.xyz 專訪](https://gen.xyz/blog/hotaisle-xyz)；[Investors 頁](https://hotaisle.xyz/investors) |
| **CRM 狀態** | **2026-08-11 實查為乾淨** — 無 lead、無 account、無 do-not-call | salesleads Search（Type = All），由專員於 2026-08-11 實查。**注意：CRM 乾淨不等於通路乾淨——見第 13 節** |
| **轄區／團隊** | 密西根州 — Chicago Area = **T1｜T2｜T11** → 一組可直接註冊 | Territory Map-Jan.2026 (Rev.1)，Sales Territory Assign 分頁。**警示：資料中心在密西根，但登記法人在懷俄明州 Cheyenne，兩位決策者研判分別位於新罕布夏州與華盛頓州——見第 13 節 Rule 8 說明** |

---

## 3. 領導層與所有權

本節證據等級：**CONFIRMED（已確認）**＝第一手具名揭露或多方獨立佐證｜**CIRCUMSTANTIAL（旁證）**＝證據指向但事實未確立｜**primary-record（一手紀錄）**＝網路號碼登錄機構、聯邦競選財務申報、法院案卷，或公司自家已發布頁面｜**GAP**＝已具名搜尋但查無。

進入表格前有兩項前提。第一，**本檔中每一個幹部姓名都是公司自行宣告，或由 FEC 佐證，沒有任何一個經公司登記機關查證**——任何州皆未取得登記文件，因此**很可能存在兩位創辦人以外的幹部、董事或股東，只是完全看不見**（3.4）。第二，**登錄機構幹部與網路聯絡人以獨立列呈現並明確標示**：ARIN Point of Contact 是公開合法的接觸管道，對一家如此低調的公司而言，這往往是唯一能取得的幹部等級紀錄。

### 3.1 具名人員

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC 紀錄 | 來源 |
|---|---|---|---|---|---|---|
| **Jon Stevens** | **Co-Founder & CEO**（部分第三方檔案將其創業職稱寫為 CTO） | **經濟決策人／最終拍板者**——資本、硬體供應商選擇與定價。同時也是公司的公開發聲者：部落格作者、研討會講者、podcast 來賓 | **CONFIRMED** — 多個彼此獨立的一手與第三方來源，姓名與角色一致 | **jon@hotaisle.xyz**（hotaisle-cli 倉庫公開 git 提交作者信箱）· **hello@hotaisle.ai**（公司聯絡頁）· [LinkedIn](https://www.linkedin.com/in/jon-s-stevens/) | **以雇主「Hot Aisle」查詢查無其紀錄**——該雇主篩選只回傳一筆，且是 Clint Armstrong。有一筆**研判為其本人但不確定**的歷史紀錄：STEVENS, JON · Entiat WA 98822 · 職業 **DIRECTOR OF IT** · 雇主 **W3BCLOUD** · ActBlue · 2020-09-19 · **$25.00** · 指定捐給 McGrath for US Senate（C00711549）。雇主與其已知前東家相符，但自陳職業與 Co-Founder/CTO 不符。**密西根與華盛頓州大量同名筆數不得歸屬於他**——見第 11 節 | [About 頁](https://hotaisle.xyz/about/)（「Platform, customer, and infrastructure — leads customer deployments, partnerships, and operating decisions」）；[AMD NeoCloud 部落格](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html)；[Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle)；[gen.xyz](https://gen.xyz/blog/hotaisle-xyz)；[GitHub jon-hotaisle](https://api.github.com/users/jon-hotaisle) |
| **Clint Armstrong** | **Co-Founder & Head of Engineering**（亦有「Co-Founder / Engineer」寫法） | **技術決策人／架構與維運守門人。** 掌握規格、可維修性要求與開機自動化——**這位就是決定「非 Dell 機箱能不能接受」的人** | **CONFIRMED** — 一手 About 頁 ＋ 獨立第三方檔案 ＋ 程式碼倉庫活動 | **查無個人信箱。** 可經 hello@hotaisle.ai 或 [LinkedIn](https://www.linkedin.com/in/clint-armstrong/) | **查有紀錄。** ARMSTRONG, CLINT · Grantham NH 03753-3433 · 職業 **ENGINEER** · 雇主 **HOT AISLE** · 受款方 **WINRED** · 收款日 **2024-06-22** · **$50.00** · Form 3X 第 11AI 行。這是**全 FEC 資料庫中唯一一筆雇主為「Hot Aisle」的紀錄**，且以姓名＋州別查詢恰好回傳 1 筆——**這就是他完整的個人捐款史** | [About 頁](https://hotaisle.xyz/about/)（「Operations, systems, and reliability — oversees engineering, automation, control plane, and compute provisioning」）；[gen.xyz](https://gen.xyz/blog/hotaisle-xyz)；[GitHub cloud-init-templates 貢獻者](https://api.github.com/repos/hotaisle/cloud-init-templates/contributors)；[FEC](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle) |
| **NetOps**（職務帳號，Hot Aisle Inc）— *登錄聯絡人列* | **ARIN Point of Contact，同時擔任全部六個角色：Administrative、Technical、NOC、Abuse、DNS、Routing。** 代號 **NETOP393-ARIN**，狀態 **Validated** | 營運／技術的入口。由於六個角色全部收攏到同一個共用信箱，**實際上幾乎可以確定是由 Armstrong 和／或 Stevens 兼任**，而非另有團隊 | **CONFIRMED** 為經驗證的 ARIN 紀錄。其背後的自然人為**推論**，登錄資料中未具名 | **netops@hotaisle.xyz** · **+1-646-389-2009**。646（紐約市）區碼既不符懷俄明州登記地址，也不符任何一位創辦人已知所在州——研判為 VoIP／轉接 | 不適用——職務帳號，非個人 | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)。掛載於 Org HA-716、AS21566、NET-23-183-40-0-1 與 NET6-2602-F955-1 |
| **不存在獨立的 OrgAdmin／OrgTech／OrgAbuse 個人** — *登錄聯絡人列* | — | **這個「不存在」本身就是發現。** 多數業者會把 OrgAdmin、OrgTech、OrgAbuse 與 NOC 分派給不同的具名個人；Hot Aisle 把六個角色全部收攏到單一經驗證的職務信箱。**ARIN 端沒有任何額外的具名網路人員可以挖** | **primary-record**（就「僅有單一職務帳號」此一事實而言） | 僅 netops@hotaisle.xyz | 不適用 | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)。與 GitHub 組織「no public members」及 D&B 1–10 人區間相互佐證，指向一個名副其實的雙人工程團隊 |
| **PeeringDB 聯絡人** — *網路聯絡人列* | — | **完全沒有——連 PeeringDB 網路物件本身都不存在（GAP）。** 無 peering 聯絡人姓名、無 IX 進駐、無設施清單、無流量揭露可供挖掘。其連線為**外購 transit／雲端 on-ramp**（Switch Connect 與 Megaport），不是無結算 peering——與「推論服務型租戶」而非「網路營運商」的定位一致 | **primary-record**（就「查詢回傳為空」此一事實而言） | 不適用——PeeringDB 中不存在 | 不適用 | [peeringdb.com/api/net?name\_\_contains=Hot Aisle](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle) 回傳空的 data 陣列 |
| **Gabriel Alfonzo**（GitHub：NarukeAlpha／narukealpha） | **網站前端貢獻者** | **邊緣人物——網站外包。並非採購決策圈成員。** 列於此僅為把「還有誰碰過這家公司」這個問題收乾淨 | **CIRCUMSTANTIAL** — 程式碼貢獻已確認；僱傭關係未確認。**視為外包，不得以員工身分接觸** | 公開 git 提交後設資料中出現 bagaao@live.com — **不得主動聯絡；這是被順帶曝露的私人信箱** | 未查詢——邊緣貢獻者，非主事者 | 對 [hotaisle-website](https://api.github.com/repos/hotaisle/hotaisle-website/commits) 有 15 次提交，作者名同時出現「Gabriel Alfonzo」與「narukealpha」；[GitHub NarukeAlpha](https://api.github.com/users/NarukeAlpha)。**無 hotaisle.xyz 信箱，未列於 About 頁** |
| **Andrey Cheptsov**（GitHub：peterschmidt85） | **dstack 創辦人——外部編排合作夥伴，非 Hot Aisle 員工** | **影響者／技術背書。** 是可信的溫和引介路徑與參考客戶聲音 | 身分對應為 **CIRCUMSTANTIAL**（該帳號對應真人在公開領域已廣為人知，但 Hot Aisle 未曾陳述）；**dstack 為 Hot Aisle 具名夥伴則為 CONFIRMED** | 經 [dstack.ai](https://dstack.ai/blog/h100-mi300x-inference-benchmark/) — **非 Hot Aisle 的信箱** | 未查詢——非 Hot Aisle 主事者 | 對 [hotaisle-website 貢獻者](https://api.github.com/repos/hotaisle/hotaisle-website/contributors) 有 3 次提交；dstack 列於 [/partners](https://hotaisle.xyz/partners) 之「GPU-native orchestration」；合著部落格「Orchestrating AMD GPUs with dstack」（2026-03-02） |

**刻意排除，並在此載明。** GitHub 帳號 **vmiss33**（5 次提交，twitter vmiss33）、**dhogaivannan**（紐約州紐約市）與 **gtnotacoder**（gt@netg.co）出現於 Hot Aisle 的倉庫中，但**無法確認其為員工、外包或外部貢獻者**。**未予聯絡，亦不計入人員編制**（[GitHub 組織](https://github.com/hotaisle)）。

### 3.2 登錄紀錄（Registry record）

須先界定範圍：以下為**網路號碼登錄機構（ARIN）紀錄與聯邦競選財務申報**，**不是公司登記機關紀錄**。**任何州皆未能取得公司幹部或董事申報文件**——詳見 3.4 與第 14 節。

| 姓名 | 身分／權限 | 申報文件 | 申報日期 | 來源 |
|---|---|---|---|---|
| **未取得任何幹部** | **無法取得。** 未能取得任何幹部、董事、經理人、股東、發起人、註冊代理人姓名或年報簽署人，因為**研判設立州與替代州的每一個公司登記入口都拒絕自動化存取** | **未取得任何文件。** 密西根 LARA（cofs.lara.state.mi.us）位於 Cloudflare 之後，直接中斷 TLS 交握；德拉瓦 ICIS 回傳頁內錯誤；懷俄明州務卿位於圖形 CAPTCHA 之後，**本檔未嘗試破解**；OpenCorporates 與 Bizapedia 皆位於 CAPTCHA 挑戰之後 | 不適用 | [密西根 LARA](https://cofs.lara.state.mi.us/CorpWeb/CorpSearch/CorpSearch.aspx)（受阻）· [德拉瓦 ICIS](https://icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx)（錯誤）· [懷俄明州務卿](https://wyobiz.wyo.gov/Business/FilingSearch.aspx)（CAPTCHA） |
| **Jon Stevens** — **僅為公司自行宣告之幹部，非登記機關認定** | Co-Founder／**Chief Executive Officer**。來源為公司自家 About 頁、AMD 部落格與 Advizex 案例研究——**不是州登記文件**。在此明列，是為了讓「自行宣告」與「登記查證」的區別明確化，避免下游流失 | **並非申報文件。** 公司網站與第三方媒體的陳述 | About 頁截至 2026-08-11 為現行；AMD 部落格 2025 年；Advizex 案例研究未載日期 | [hotaisle.xyz/about/](https://hotaisle.xyz/about/) |
| **Clint Armstrong** — **僅為公司自行宣告之幹部，非登記機關認定** | Co-Founder／**Head of Engineering**。同一警語：自行宣告，未取得州登記文件 | **並非申報文件。** 公司網站陳述，**外加一筆聯邦申報，其中他自填雇主為 HOT AISLE、職業為 ENGINEER**——該筆佐證僱傭關係，但不佐證公司職務 | FEC 收款日 **2024-06-22** | [hotaisle.xyz/about/](https://hotaisle.xyz/about/) · [FEC](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle) |
| **NetOps**（職務帳號——未具名個人） | **ARIN OrgAdmin ＋ OrgTech ＋ OrgNOC ＋ OrgAbuse ＋ DNS ＋ Routing**，POC 代號 **NETOP393-ARIN**，netops@hotaisle.xyz，+1-646-389-2009，狀態 **Validated** | ARIN Org 紀錄「Hot Aisle Inc」（Org 代號 **HA-716**），1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne WY 82001 | Org 登記 **2024-01-15T14:49:58-05:00**；最後異動 **2026-07-14T15:29:52-04:00**——與公開調價同一天 | [rdap.arin.net/registry/entity/HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **AS21566「HOTAISLE」** | 自治系統號碼，範圍 21566-21566，狀態 **Active**，持有者 Org HA-716 | ARIN autnum 紀錄 | 登記 **2024-02-14T11:05:57-05:00** | [rdap.arin.net/registry/entity/HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **NET-23-183-40-0-1／NET6-2602-F955-1** | IPv4 **23.183.40.0/24**（網段名「HA-4-10」）與 IPv6 **2602:f955::/36**（網段名「HA-SOPH」），皆為 Active，皆隸屬 Org HA-716 | ARIN 網段紀錄 | 與 AS21566 同期登記，2024-02 | [rdap.arin.net/registry/entity/HA-716](https://rdap.arin.net/registry/entity/HA-716) |

### 3.3 採購決策圈（Buying committee）

Hot Aisle 是一家**兩人、創辦人自有、無 CFO、無採購職能、也沒有 IT 主管可以繞道**的未上市公司。路徑因此極短——**但真正的守門人是既有的系統整合商，不是兩位創辦人。**

| 對象 | 為何對伺服器採購具關鍵性 | 接觸方式 |
|---|---|---|
| **Jon Stevens** — Co-Founder & CEO | **他同時是經濟決策人、募資人，以及親自動手的工程師**——網站倉庫 347 次提交、CLI 倉庫 145 次提交（[GitHub](https://api.github.com/users/jon-hotaisle)）。沒有採購職能、沒有 CFO、沒有 IT 主管；**他就是簽核人。** 他也親自撰文說明公司的定價邏輯與單位經濟學，這代表他會就**每 GPU 小時成本的算式**對話，而不是規格表。關鍵在於，他已公開說出限制條件：**「The constraint is access to hardware, not demand for the platform.」** | **以資本效率與交付確定性開場，不要以效能數據開場**——他手上的 benchmark 資料比我們好。開場就談他自己說的瓶頸：如何把**已表態的 >$50M MI355X 需求**轉換成實際部署產能。引用他自己那篇 [「Why We Raised Our MI300X Price」](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price) 以證明你讀過。寄 **hello@hotaisle.ai** 或 **jon@hotaisle.xyz**；他會親自回覆，[聯絡頁](https://hotaisle.xyz/contact) 明白承諾「A person on the Hot Aisle team will reply directly. No AI bot, and no spam.」**切勿套用制式業務節奏**——整家公司的品牌就是「no contracts, no sales calls」，繁重流程會被解讀為敵意 |
| **Clint Armstrong** — Co-Founder & Head of Engineering | **技術否決權持有者。** 他掌管開機自動化（SONiC 網路、PXE boot、主機設定、ROCm 驅動、NUMA 平衡 KVM）、NetBox 單一真實來源整合，以及可維修性。**換機箱廠商的重新自動化工作是由他承擔**，所以他就是替「離開 Dell 的轉換成本」定價的人。他也會在意：今天 Dell ProSupport NBD 涵蓋每一台交換器，Z9864F 另有 4 小時關鍵任務等級與現場備品（[/networking](https://hotaisle.xyz/networking)） | **工程師對工程師、以書面、講細節：** OAM 基板相容性、ROCm／驅動對等性、供其自動化使用的 BMC／Redfish API 介面、PXE 與 cloud-init 行為，以及**決定性的一項：Grand Rapids 現場備品與回應 SLA**。備妥具體答案，說明 Supermicro 平台如何嵌入既有的 NetBox ＋ SONiC ＋ KVM 堆疊而**不需重寫**。**絕不宣稱效能勝過他已經量測過的數字** |
| **Advizex**（Dell Titanium Solution Provider）— **既有整合商，也是真正的守門人** | **這是本表中最重要的一項，也是「天真打法必敗」的原因。** 依其自家案例研究，Advizex 主持了與 Hot Aisle、Dell、Broadcom、Panduit 的**四個月每週規劃會議**；提供解決方案架構、交付與導入、人力支援與供應鏈整合；並**動用自家辦公室空間預備硬體**。Hot Aisle 於 [/partners](https://hotaisle.xyz/partners) 將 Advizex 列於「Deployment and lifecycle services」。案例研究更明白寫著：**「When AMD releases the MI355x, they will purchase them and build a new cluster, working with Advizex every step of the way.」下一筆採購在紙面上已被通路綁定** | **不要試圖取代 Advizex——要取代的是機箱，不是整合商。** 正確打法是把 Advizex 視為 Supermicro MI355X 機種的 partner-of-record 候選，或找到能提供同等預備／機櫃整合／供應鏈包覆的 Supermicro 授權整合商。**Hot Aisle 買的是一座交付完成、上架完成、能開機運轉的叢集——不是一個箱子。** 任何未包含 L11／L12 機櫃整合、預備、現場備品與 Grand Rapids 物流的報價，**在完整度上必輸給 Advizex，不論單價多低**（[Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle)） |
| **AMD**（Instinct 現場團隊／neocloud 專案團隊） | Hot Aisle 在自家頁尾將自己標榜為 **「AMD Exclusive AI Cloud」**。AMD 已發布專屬的 [NeoCloud 部落格](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html) 與 [Hot Aisle 試用申請頁](https://www.amd.com/en/products/accelerators/instinct/eval-request/hot-aisle.html)。因此 AMD 對「MI355X 配額落到哪個平台夥伴」具有直接影響力，更重要的是對 **GPU 配額本身**——那才是真正稀缺的投入 | **與其單線直攻，不如同時經由 AMD Instinct 夥伴關係並行推進。** AMD ＋ Supermicro 就 MI355X 配額**加上**平台的聯合提案，遠強於 Supermicro 單方報價，因為 Hot Aisle 的瓶頸是資本與 GPU 供給，不是機箱偏好。**Supermicro AMD MI355X JumpStart 專案** 是針對這個客戶最自然、摩擦最低、也最符合其品牌調性的第一次接觸（[learn-more.supermicro.com/mi355x](https://learn-more.supermicro.com/mi355x)） |
| **Switch**（設施營運商，The Pyramid，Grand Rapids MI） | Switch **定義了 Hot Aisle 必須在其中採購的物理框架**：機櫃功率密度、散熱方式，以及其租用空間內是否具備直接液冷。Hot Aisle 自家 MI355X 頁面描述「a deployable rack design using direct liquid cooling」，**每張加速卡 1,400 W**。若其 Switch 據點的 DLC 受限，整個平台決策就會完全改變。Switch 同時核發其再生能源認證（2025 年退役 781 張 REC） | **不得代表 Hot Aisle 直接聯絡 Switch。** 應改為**把散熱問題設計成對 Hot Aisle 的資格確認提問**（第 13 節）。若其空間內無法取得 DLC，或供裝時程太慢，Supermicro 的氣冷 10U 8× MI355X 系統就是那個差異化答案——**這是真正的技術楔子，不是價格爭論** |
| **$50–100M 募資的資金提供者**（含既有支持者 Mesh／Joseph Lubin） | Hot Aisle 於 [Investors 頁](https://hotaisle.xyz/investors) 表明正募集 **$50–100M**，管道為「equity, strategic investment, and **asset finance**」，明載用於「purchase AMD MI355X systems and fund the networking, rack integration, and site deployment」。因為**資產融資被列為三條管道之一**，硬體融資結構就是一個**開放的商業變數——一個供應商可以施力的槓桿** | **把融資／租賃條件當成方案的一部分，不是事後補件。** 明白寫出「asset finance」就是邀請。一個能讓他們**在股權完全到位之前先部署產能**的結構，直接命中他們自陳的瓶頸，價值遠高於百分比折扣。**報價前先與 Supermicro 融資／租賃單位協調** |

### 3.4 未能具名之職位——每一項皆為 GAP

**GAP — 公司登記之幹部、董事、經理人、股東、發起人、註冊代理人與年報簽署人：** 任何州皆未取得。密西根 LARA 在 TLS 層被 Cloudflare 阻擋，德拉瓦 ICIS 回傳頁內處理錯誤，懷俄明州務卿為 CAPTCHA 閘門；**本檔不破解 CAPTCHA。** 很可能存在兩位具名創辦人之外的幹部、董事或股東，而目前**完全無從查看**。 · **GAP — 設立州：** 懷俄明僅由 ARIN 組織地址與 D&B 索引推得，兩者都指向 Cheyenne 的註冊代理人 PMB。德拉瓦與密西根均已嘗試、均告失敗。 · **GAP — 申報歷史：** 設立文件、修正、更名、前用名稱與外州登記——**特別是 Hot Aisle 是否已在密西根辦理外州登記（其主機代管據點可能有此要求）**——全部無法取得。 · **GAP — CFO／財務副總／財務主辦：** 從未有過姓名，也無證據顯示存在此職。 · **GAP — 採購／採購主管／供應商管理：** 全網無此職稱；採購權在 CEO 手上。 · **GAP — 業務副總／業務主管：** 沒有，且屬刻意設計——公司主打「no sales calls」。 · **GAP — 獨立的網路／NOC 人員：** 六個 ARIN 角色全部收攏到同一個共用信箱；**不存在其他可查的具名網路人員。** · **GAP — 全網查無任何徵才啟事**（Indeed、ZipRecruiter、LinkedIn 檢索），因此**無招募主管姓名、無團隊擴編訊號、無組織擴張證據。** 這與「雙人公司＋夥伴人力支援」一致，但**「查無職缺」是弱證據，不是證明。** · **GAP — 無商標，因此無聲明簽署人與代理人：** USPTO 文字商標檢索對「hot aisle」與「hotaisle」在 Live、Registered、Pending、Dead、Cancelled、Abandoned 全狀態與全類別均回傳「No results found」。**這是真正的負面結果，不是查詢失敗**——注意通用詞問題：「hot aisle」本身就是業界術語，這很可能就是沒有申請的原因。 · **GAP — UCC-1 擔保權人與債務人簽署人：** 所有候選入口皆受阻（第 8 節）。 · **GAP — 隱私遮蔽前的歷史 WHOIS 登記人：** whoisrequest.com 回 HTTP 403、whoxy.com 需付費登入、securitytrails 需 API 金鑰；僅取得現行 WHOIS。任何可能揭露原始設立實體的 2023–2024 年登記人姓名、組織或信箱**皆未還原**。 · **GAP — 貢獻者身分：** GitHub 帳號 vmiss33、dhogaivannan 與 gtnotacoder 出現於 Hot Aisle 倉庫，但**無法確認其為員工、外包或外部貢獻者。**

### 3.5 已實際查詢之來源——含「查無」者

**在人員面有產出者：** **[hotaisle.xyz/about/](https://hotaisle.xyz/about/)** — 唯一的一手名冊，恰好列兩人並附明確職責範圍。 · **[ARIN RDAP](https://rdap.arin.net/registry/entity/HA-716)** — 公司身分的突破口：法定名稱、Cheyenne WY 地址、登記與最後異動時戳、AS21566、兩個 IP 區塊，以及唯一一個經驗證的六角色 POC。*（第一次以代號「HOTAI」查詢回傳無關組織——維吉尼亞州 Arlington 的「HotAir」——已載明以免重蹈。）* · **[FEC 個人捐款資料庫](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle)** — 六種不同查詢；全公司範圍僅回傳一筆（Armstrong），外加一筆經 W3BCLOUD 的 Stevens 可能紀錄，並明確排除密西根同名者。*（DEMO_KEY API 觸及 OVER_RATE_LIMIT，改由 fec.gov 前端完成。）* · **[GitHub REST API](https://github.com/hotaisle)** — 真實具名人員與其活動量：jon-hotaisle（Jon Stevens，公司「Hot Aisle Inc.」，jon@hotaisle.xyz，347 ＋ 145 次提交）、clint-hotaisle，以及外部貢獻者。組織顯示 **「no public members」**。 · **[gen.xyz 專訪](https://gen.xyz/blog/hotaisle-xyz)** — 兩位創辦人背景細節：Stevens 為 W3BCLOUD 共同創辦人／CTO，曾在美國七座資料中心管理 150,000+ 張 AMD GPU；Armstrong 為 W3BCLOUD 去中心化儲存總監，建過 20 PB 叢集與 20,000+ 台機器的網路；Mesh.xyz／Joseph Lubin 支持；781 張 REC；SOC 2 Type 2 與 HIPAA。 · **[Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle)** — 具名 Stevens 為 CEO／創辦人，並描述完整的整合商關係。

**已觸及但在人員面查無者：** **[PeeringDB](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle)**（空的 data 陣列——根本沒有網路物件，因此無 peering 聯絡人姓名） · **[USPTO 商標檢索](https://tmsearch.uspto.gov)**（「hot aisle」與「hotaisle」皆 0 Live、0 Dead；assignment-api 為空、tsdrapi 回 HTTP 401、uspto.report 回 HTTP 403、trademarks.justia.com 回 HTTP 403——**不存在任何登錄律師或聲明簽署人可供擷取**） · **[CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search)**（以「Hot Aisle Inc」精確詞當事人查詢回傳 **count 0**；較寬鬆的「Hot Aisle」RECAP 查詢回傳 32 筆無關的資料中心專利訴訟——Valtrus、Key Patent Innovations、Vertiv、Crusoe Energy、Cloud Byte v. Dell——僅因通用術語而命中） · **歷史 WHOIS**（whoisrequest.com 403；whoxy.com 登入牆） · **[Crunchbase](https://www.crunchbase.com/organization/hot-aisle)**（HTTP 403——無募資輪資料） · **[Hugging Face](https://huggingface.co/hotaisle)**（組織存在、創辦人具名，但無公開模型或資料集） · **職缺檢索**（Indeed、ZipRecruiter、LinkedIn 皆查無——無職缺、無招募主管、無招募顧問姓名）。

**受阻及其原因：** **密西根 LARA** — `LibreSSL/3.3.6: error:1404B410:SSL routines:ST_CONNECT:sslv3 alert handshake failure`；DNS 解析至 cofs.lara.state.mi.us.cdn.cloudflare.net，即 **Cloudflare 機器人防護拒絕該 TLS 指紋**。已改以 `--tlsv1.2`、以 `-k`、以 `/SearchApi/Search/Search` 端點的 GET 與 POST，以及 ucc.lara.state.mi.us 重試——全部 HTTP 000。 · **[德拉瓦 ICIS](https://icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx)** — 頁面載入成功（HTTP 200，48,338 bytes）；以實體名稱「HOT AISLE」送出 **一次** 查詢；逐字回應，於輸入框旁以黃色標示：**「An error occurred while processing the request」**，結果表為空。基於該站明載禁止自動化／重複查詢，**僅執行一次，未重試。** · **[懷俄明州務卿](https://wyobiz.wyo.gov/Business/FilingSearch.aspx)** — 圖形 CAPTCHA，support ID 11385417910158757353；**未嘗試破解。** · **資料聚合站全數受阻：** OpenCorporates（HAProxy CAPTCHA，抓取與瀏覽器皆然）、Bizapedia（拖曳式人機驗證）、CorporationWiki（HTTP 403）、OpenGovUS（HTTP 404「File not found.」）。

**在不驚動公司的前提下、補齊幹部名單的最佳中性路徑：** 訂購**懷俄明州的良好存續證明／實體明細**（或委外進行人工公司資料查詢），以確定設立州、實體編號與註冊代理人。同一份文件也會提供第 8 節 UCC 查詢所需的正確 debtor 字串。

---

## 4. 據點與機房

| 站點 | 機房營運商 | 自有／租用 | 面積與電力（僅列已公布者） | 證據 |
|---|---|---|---|---|
| **Switch「The Pyramid」園區 — 密西根州 Grand Rapids／Caledonia（Kent County）** — Hot Aisle **唯一的生產據點** | **Switch, Inc.**（設施營運商／房東）。Hot Aisle 為運算租戶 | **租用——主機代管租戶身分。** Hot Aisle 擁有伺服器、網路設備與 IP 空間；**Switch 擁有並營運建物、電力與冷卻。** 由 Hot Aisle 自家 [/datacenter](https://hotaisle.xyz/datacenter) 的租戶語氣（「Located at the Switch Pyramid data center」）、Switch 代其核發年度再生能源證明並代為退役 REC，以及 [/partners](https://hotaisle.xyz/partners) 將 Switch 列於「Data center operations」三方佐證。**對產權研究的意涵：Kent County 沒有任何以 Hot Aisle 為名的地號或估價紀錄——地號屬於 Switch** | **設施端：** Switch 稱 Pyramid 園區為 **Tier 5 Platinum、已建 660,000 平方英尺、規劃可達 180 萬平方英尺與滿載 110 MW**（[switch.com/grand-rapids](https://www.switch.com/grand-rapids/)）。園區地址 6100 East Paris Avenue SE, Caledonia, MI，即前 Steelcase Pyramid。**Hot Aisle 自身在其中的用量並未揭露，但可由其公布的 REC 退役量推導——見下方推估框** | 逐字取自 [/datacenter](https://hotaisle.xyz/datacenter)：「Switch Pyramid • Grand Rapids, MI」「Tier 5 Platinum Infrastructure」「Located at the Switch Pyramid data center in Grand Rapids, Michigan. A facility our partners can brag about.」「Armed guards, multiple layers of physical and biometric access controls」「100% renewable energy, low PUE (patented T-SCIF design)」，以及「Fiscal — Tax optimization allows us to pass significant capital cost savings onto our partners」（研判所指為密西根資料中心銷售／使用稅減免）。[/pricing](https://hotaisle.xyz/pricing)：「100% green datacenter — Located in our secure Michigan facility」 |
| **未來／規劃中——多個小型區域推論站點**（地點尚未公布） | **不明——尚未選定或未揭露** | 依其模式應為**租用主機代管** | **未揭露。** 明確描述為「Compact, repeatable inference deployments in more data centers, placed near the teams and jurisdictions that need them」 | 逐字取自 [Investors 頁](https://hotaisle.xyz/investors)：「We are not pursuing one giant deployment and hoping demand follows. We will grow through smaller inference-focused sites, each able to serve a regional market with the same platform and operating discipline.」以及「Existing automation brings networking, PXE boot, operating systems, ROCm, and KVM isolation online without rebuilding the process at every site.」**這是可重複單元的採購模式——高度相關，因為贏下一個節點設計，等於贏下一個樣板，而不是一筆單次生意** |
| **歷史能力宣告——「Tier 3-5 data centers in the US」關係** | 多家，未具名 | **不適用**——顧問／仲介宣告，非自有據點 | 不適用 | 取自 2024 年存檔的 Cluster 頁：「Bring your own DC or use ours: We've developed relationships with a number of Tier 3-5 data centers in the US. We can help negotiate your DC, Insurance and Internet contracts for you.」保留此列，是因為**它顯示他們同時銷售叢集設計顧問服務**——這是硬體供應商可以附掛的第二條、不明顯的動線（[Wayback 2024-11-14](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)） |

> **推導之電力估計——本檔自行計算，非公司揭露。** Hot Aisle 公布其 REC 退役量：**2024 年退役 267 張**、**2025 年退役 781 張**（[2024 年認證](https://hotaisle.xyz/blog/hot-aisle-goes-100-green-with-switch-sustainability-certification-2024/)、[2025 年認證](https://hotaisle.xyz/blog/hot-aisle-goes-100-green-with-switch-sustainability-certification-2025/)）。取 **1 REC = 1 MWh**：2025 年為 781 MWh ÷ 8,760 h ≈ **89 kW 平均負載**；2024 年為 267 MWh，攤在約四個月的上線期（叢集約 2024 年 9 月上線）≈ **91 kW 平均**。**兩個彼此獨立的年度收斂到約 90 kW 平均總負載**——這是一個緊密且自洽的估計。以 Switch 宣稱的低 PUE（專利 T-SCIF 設計）換算，隱含約 **70–80 kW 平均 IT 負載**，即個位數到十幾櫃的規模。**推估值，由本檔推導，非公司揭露。**

**GAP — Hot Aisle 在 Switch 的合約電力、機櫃數與樓地板面積均未揭露。** 公開的只有 Switch 的全園區數字，Hot Aisle 自身配額僅由 REC 資料推得。 · **GAP — Switch Pyramid 的散熱框架未經查證，而這是全檔在商業上最重要的缺口。** 其租用空間能否支援 **每張加速卡 1,400 W 的直接液冷**、密度多少、成本多少、時程多久，**全部未知**。第 13 節的主要銷售楔子完全建立在這個答案上——正因如此，它被設計成資格確認提問，而不是被斷言。 · **GAP — 如預期，Kent County 沒有任何以 Hot Aisle 為名的產權或估價紀錄。** 地號屬於 Switch。Switch 自身的地號紀錄（Kent County Property Search／Caledonia Township Assessing）**未予調閱——這是刻意的範圍決定**，因為它描述的是房東，不是標的。

**地址紀律——在寄送任何東西或安排任何拜訪之前先讀這段。** Cheyenne 地址是**註冊代理人的私人信箱，不是辦公室**：不要前往，也不要寄送。**Hot Aisle 在任何地方都沒有可以拜訪的辦公室。** 唯一的實體存在是 Switch Pyramid 園區內的租用機櫃空間，進入需 Switch 陪同、武裝警衛核可與生物辨識通行（[/datacenter](https://hotaisle.xyz/datacenter)）。

---

## 5. 硬體機隊

本節證據等級：**CONFIRMED（已確認）**＝第一手具名揭露或多方獨立佐證｜**CIRCUMSTANTIAL（旁證）**＝行為或第三方指向，但公司從未具名｜**INFERRED（推論）**＝由公開組態推得，非揭露｜**CONTRADICTED（反證）**＝證據方向相反｜**GAP**＝查無。

### 5.1 機隊清單

| 項目 | 內容 | 依據 | Supermicro 對照 |
|---|---|---|---|
| **GPU 運算節點 — Dell PowerEdge XE9680，每箱 8 × AMD Instinct MI300X 192 GB HBM3 OAM** | **約 16 台機箱／約 128 張 GPU。** 公司自述為「Our flagship 128 GPU MI300x bare metal cluster」；MI300X 頁載明「Eight MI300X accelerators are available in each Dell PowerEdge XE9680」。**128 ÷ 8 = 16 個節點。** 每張 GPU：192 GB HBM3、5.3 TB/s 頻寬、304 個運算單元、CDNA 3、256 MB Infinity Cache | 平台為 **CONFIRMED**（一手，現行與 2024 年存檔版本皆有，並由 [Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle) 與 [AMD NeoCloud 部落格](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html) 佐證）。**節點數是由公司自己的兩個數字相除得出，不是公司陳述** | **直接對等機種：Supermicro AS-8125GS-TNMR2** — 8U GPU A+ Server，8 × AMD Instinct MI300X OAM，雙 AMD EPYC 9005／9004（最高 400 W TDP），24 × DDR5 DIMM 至 6 TB／6000 MT/s，前置 12 個熱插拔 2.5" NVMe（可擴至 16），另有 2 個 SATA 與 M.2 開機碟。[Supermicro eStore](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html) 標價 **$275,863.87**，**有現貨、3–5 個工作日出貨**。**注意供貨對比：** Dell XE9680 MI300X 組態為**僅供報價，經銷平台估交期約 4 週**。對一個自陳瓶頸是「產能到位時間」的客戶而言，**交期是活生生的差異化** |
| **每節點的主機 CPU／記憶體／本機 NVMe** | **存在兩種不同的節點組態**——這是一個重要且容易被忽略的訊號。裸機層標示「**64 or 102** CPU Cores」，1-GPU VM 層標示「**8 or 13** CPU Cores」，2／4-GPU 層標示「**26 or 52** CPU Cores」。這種橫跨每一層的「X or Y」一致模式，代表機隊中有**兩種不同的主機 CPU SKU**。每個裸機節點：**2 TB 系統記憶體、122 TB NVMe**。VM 層提供 224 GB／448 GB／896 GB 記憶體與 12 TB NVMe | 一手 [定價頁](https://hotaisle.xyz/pricing)，截至 2026-08-11 為現行。**「兩種組態」的判讀是由一致的雙值模式推得的 INFERRED 推論——不是公司陳述，但依據充分** | AS-8125GS-TNMR2 支援雙路 EPYC 9004／9005，**涵蓋其兩種核心數**，並可擴充到 **6 TB DDR5（相對其現行 2 TB）**——為更大的 KVM 租戶密度預留餘裕。前置 16 個 NVMe 槽位支援其 122 TB 本機快閃配置。**若他們確實在跑兩個主機世代，那是一個值得指出的標準化痛點：** 下一次建置採用單一平台 SKU，可把兩套備品池與兩條自動化路徑收斂為一套 |
| **運算網路卡 — Broadcom 57608 雙埠 200G，每台 XE9680 八張** | **每節點 8 張、3.2 Tbps、RoCEv2。** 定價頁行銷為「8x400G networking — RoCEv2 for ultra-low latency clusters」 | **CONFIRMED** — 逐字取自 [網路頁](https://hotaisle.xyz/networking)：「Dell XE9680 chassis with eight Broadcom 57608 dual-port 200G Q112 adapters and Dell PowerSwitch Z9864F switching」 | Broadcom Thor2（57608）400G 等級網卡在 Supermicro 的 OAM GPU 平台上皆有支援——**因此網卡選擇不是鎖定點，也不必更換。以此開場：** 他們在網路架構與 RoCEv2 調校上的投資可完整沿用。**Broadcom 本來就是 Hot Aisle 的具名夥伴**，因此 Supermicro ＋ Broadcom 的組合在通路上是延續而非破壞 |
| **乙太網路交換 — Dell PowerSwitch Z9864F（運算）、Z9664F（叢集／儲存）、Z9432F（頻外管理），全部跑 SONiC** | **三個交換平面。** 運算網路用 **Z9864F**。東西向／儲存用 **Z9664F**，搭配 Broadcom 57504 四埠 10/25GbE，速率 100 Gbps。頻外管理用 **Z9432F**，搭配 Broadcom 5720 雙埠 1GbE，速率 1 Gbps。**可維修性：「Dell ProSupport Next Business Day covers every switch. The Z9864F has additional four-hour mission-critical coverage, backed by on-site replacement parts.」** | **CONFIRMED** — 逐字取自 [網路頁](https://hotaisle.xyz/networking) | **這是整個 Dell 陣地中最黏的一塊，不應該優先攻擊。** 他們在 Dell 硬體上跑 **SONiC（開放 NOS）**，意味著 NOS 可攜、但盒子不可攜。任何交換器對話都必須**打平或勝過「每台交換器 NBD、骨幹 4 小時關鍵任務、Grand Rapids 現場備品」**——若做不到，**第一筆交易就只鎖定運算節點，交換器不要碰。** 在沒有對等服務包覆的情況下去攻交換器，正是這筆生意輸掉的方式 |
| **下一世代目標平台 — AMD Instinct MI355X，每系統 8 張** | **尚未採購。** 每張加速卡 288 GB HBM3E、8 TB/s 記憶體頻寬、**1,400 W**、八卡組態合計 2.3 TB 記憶體、八張 OAM 加速卡走 AMD Infinity Fabric mesh，採「a deployable rack design」搭配**直接液冷**。Hot Aisle 逐字表示：**「We are still raising the capital required to buy and deploy the hardware.」** 先前的登記實驗**只收到意向承諾** | **CONFIRMED 為「尚未採購的目標」** — 一手 [MI355X 頁](https://hotaisle.xyz/mi355x) 與 [Investors 頁](https://hotaisle.xyz/investors)。1,400 W／卡與 DLC 需求是他們自己公布的數字 | **這才是真正的機會。** Supermicro 除液冷版本外，另出貨 **氣冷 10U 8× MI355X 系統**（2.3 TB HBM3E、第 5 代 EPYC、最高 72 核）（[新聞稿](https://www.supermicro.com/en/pressreleases/supermicro-expands-its-portfolio-performance-and-efficiency-driven-air-cooled-ai)），並設有具名的 **AMD MI355X JumpStart** 評估專案（[learn-more.supermicro.com/mi355x](https://learn-more.supermicro.com/mi355x)）。若 Hot Aisle 租用的 Switch Pyramid 據點無法順利支援 DLC——**或無法在其時程內支援**——氣冷 8× MI355X 平台就能**把一個設施依賴從他們的關鍵路徑上移除。** 這是能力論述，不是折扣論述，也是本帳戶最強的楔子 |
| **MI325X — 刻意跳過（負面發現，訊號強度高）** | **零。** Hot Aisle 從未部署或上架 MI325X。其 2024 年 11 月存檔的 Cluster 頁曾寫「AMD's MI300x (soon MI325x)」——但以 Wayback CDX 查詢 `hotaisle.xyz/mi325x*` **在整個存檔中回傳空結果集**，且從 2024 年 6 月到 2026 年 7 月的任何一份定價快照中，MI325X 從未出現 | Wayback Machine CDX API，**負面結果**，並與十二份定價快照交叉核對（[空的 CDX 查詢](http://web.archive.org/cdx/search/cdx?url=hotaisle.xyz/mi325x&matchType=prefix)；[2024 年 cluster 頁](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)） | **戰略上很重要：資金不到位時，他們會直接跳過一個世代。** 其採購節奏由**資金而非 AMD 產品週期**決定。不要用 AMD 的產品路線圖日期做預測，要用他們的募資進度做預測。同樣地，這也代表 **MI355X 是一個真正開放、未承諾的平台決策**，而不是既有 MI325X 陣地的換代 |
| **軟體／維運堆疊**（非硬體，但對轉換成本具決定性） | **NetBox** 作為 DCIM 單一真實來源並有自建整合；自動化 **SONiC** 網路；**PXE boot**；自動化主機設定與作業系統；當期 **ROCm** 驅動；具直通 GPU 的 **NUMA 平衡 KVM** 虛擬機；**Stripe** 用量計費；終端 UI、API 與開源 **Go CLI**（[github.com/hotaisle/hotaisle-cli](https://github.com/hotaisle)）；**分支版 SkyPilot**；**dstack** GPU 原生編排 | **CONFIRMED** — 一手 [首頁](https://hotaisle.xyz/) 與 [網路頁](https://hotaisle.xyz/networking)；並由其公開 [GitHub 倉庫](https://github.com/hotaisle) 佐證 | **其自動化在設計上就與供應商無關**（SONiC、PXE、cloud-init、KVM、NetBox）——這**實質降低了更換機箱廠商的成本**，也是「Supermicro 節點不是整套翻新」這個論點最好的依據。**對 Clint Armstrong 要把這件事量化說清楚：** 要改的是 **BMC／Redfish 端點與 NetBox 的硬體庫存範本**，不是整條供裝流水線 |

### 5.2 硬體供應商——附明確證據等級

| 供應商 | 等級 | 證據實際內容 |
|---|---|---|
| **Dell Technologies** | **CONFIRMED（已確認）** | 證據壓倒性且多來源。(1) [MI300X 頁](https://hotaisle.xyz/mi300x)：「Eight MI300X accelerators are available in each Dell PowerEdge XE9680.」(2) [定價頁](https://hotaisle.xyz/pricing) 將「Dell XE9680 chassis」列為預設含括。(3) [網路頁](https://hotaisle.xyz/networking) 具名 Dell PowerSwitch Z9864F、Z9664F、Z9432F，並載「Dell ProSupport Next Business Day covers every switch.」(4) [Partners 頁](https://hotaisle.xyz/partners) 將 Dell Technologies 列於「Hardware systems and support」。(5) [Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle)：「Advizex deployed Dell PowerEdge XE9680 servers equipped with AMD MI300x GPUs.」(6) Jon Stevens 於 2024 年 11 月在 **SC24 的 Dell Technologies 攤位**發表，並與 Dell 的 Saurabh Kapoor 一同上 theCUBE。(7) 其自家 [2024-09-13 現場筆記](https://hotaisle.xyz/blog/cruising-to-the-finish-line/)：「one of the AMD MI300x GPUs went crazy and had a few loose screws. Dell immediately sent two technicians out to diagnose and fix it. **The level of support they are giving us is breathtaking.**」**最後這一項才是重點——這個既有關係不只是合約上的，也是情感上的** |
| **AMD** | **CONFIRMED（已確認）** | 唯一的加速器供應商，實質上也是品牌夥伴。每一頁的網站頁尾都寫著 **「AMD Exclusive AI Cloud」**。AMD 為 Hot Aisle 發布了專屬的 [NeoCloud 部落格文章](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html)，並架設 [Hot Aisle 試用申請頁](https://www.amd.com/en/products/accelerators/instinct/eval-request/hot-aisle.html)。AMD 的 Jim Greene 於 2025 年 4 月在 AMD TechTalk podcast 專訪 Jon Stevens。AMD 列於 [/partners](https://hotaisle.xyz/partners) 之「Accelerator platform」。MI300X 與 MI355X 兩頁皆為 AMD 獨占 |
| **Advizex**（Dell Titanium Solution Provider）— 整合商／通路 of record | **CONFIRMED（已確認）** | Advizex 自家 [案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle) 描述與 Hot Aisle、Dell、Broadcom、Panduit 等進行 **四個月每週規劃會議**；提供解決方案架構、交付與導入服務、**人員與人力支援**、供應鏈整合；安全設備運送；以及**動用 Advizex 在地辦公室空間存放硬體零組件**。Hot Aisle 亦於 [/partners](https://hotaisle.xyz/partners)「Deployment and lifecycle services」與首頁夥伴標誌列中對等列出 Advizex。案例研究另載明 MI355X 的前瞻承諾 |
| **Broadcom** | **CONFIRMED（已確認）** | 列於 [/partners](https://hotaisle.xyz/partners)「Networking and connectivity」與首頁夥伴標誌列，並在 [網路頁](https://hotaisle.xyz/networking) **以料號具名**：Broadcom **57608** 雙埠 200G Q112（每箱八張）、Broadcom **57504** 四埠 10/25GbE、Broadcom **5720** 雙埠 1GbE。亦被具名為 Advizex 四個月規劃會議的參與方 |
| **Panduit**（機櫃、佈線、實體基礎設施） | **CIRCUMSTANTIAL（旁證）——不得陳述為事實** | 由 **Advizex** 具名為四個月每週基礎設施規劃會議的參與方，與 Hot Aisle、Dell、Broadcom 並列。**Panduit 並未出現在 Hot Aisle 自家 Partners 頁，Hot Aisle 也未在任何地方列出 Panduit 料號。** 因此其在實際部署中的角色**可能為真，但未確立**（[Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle)） |
| **Switch, Inc.** | **CONFIRMED——但身分是房東，不是硬體供應商** | 列於 [/partners](https://hotaisle.xyz/partners)「Data center operations」；[/datacenter](https://hotaisle.xyz/datacenter) 整頁都在講 Switch Pyramid 設施；Switch 代其核發年度再生能源證明並代為退役 REC（2024 年 267 張、2025 年 781 張）。**在此列出，是為了避免被誤計為硬體供應商** |
| **Supermicro** | **GAP — 查無任何既有關係之證據，正面或負面皆無** | **查無任何證據顯示 Hot Aisle 曾經採購、評估、測試或公開提及 Supermicro。** Supermicro 未出現於其 [Partners 頁](https://hotaisle.xyz/partners)、部落格、benchmark 參考索引、Advizex 案例研究，或 [AMD 的 NeoCloud 文章](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html)。以「Hot Aisle」＋ Supermicro 定向檢索只回傳無關的 Supermicro MI355X 產品頁。**這是一個真正的全新關係——沒有既有陣地要防守，也沒有過往失單要翻案。** 另需分開記錄，且**不得當成 Hot Aisle 的事實陳述**：AMD 自家的內容中，於 AMD Instinct Coder 整包平台裡引用了 Supermicro AI 伺服器，證實 **AMD–Supermicro 聯合銷售確實存在**——這對 AMD 主導的聯合提案是有用的背景色，僅此而已 |
| **GigaIO** | **CONTRADICTED（反證）／無關係** | GigaIO 之所以出現在關鍵字檢索中，**只是因為**一則無關的 [2024 年 11 月 GigaIO 產品公告](https://gigaio.com/2024/11/next-generation-edge-to-core-products-for-scale-up-ai-and-hpc-infrastructure/)。**Hot Aisle 任何地方都未提及 GigaIO，GigaIO 也未提及 Hot Aisle。** 明確載明，以免日後把一則游離的檢索命中誤當訊號 |
| **NVIDIA** | **CONTRADICTED（反證）——刻意且徹底的排除** | Hot Aisle 的整個品牌定位就是 **「AMD Exclusive AI Cloud」**（頁尾，每一頁）。其 2024 年的部落格為 AMD 對既有龍頭辯護；其 [benchmark 索引](https://hotaisle.xyz/benchmarks-and-analysis/) 把 MI300X 對比 H100／H200。**機隊中沒有任何 NVIDIA 硬體，就現有證據看也沒有加入的意圖。任何以 NVIDIA 平台開場的提案，光是在身分認同上就會被否決**（[hotaisle.xyz](https://hotaisle.xyz/)；[AMD myths 文章](https://hotaisle.xyz/blog/amd-groundbreaking-myths)） |

---

## 6. GPU 型錄與 AI 佈局

**已確認、公開標價、無合約銷售。** Hot Aisle 於 [/pricing](https://hotaisle.xyz/pricing) 公布完整價目；以下每一個 SKU 皆為一手資料，截至 2026-08-11 為現行。計費以分鐘為單位、隨用隨付，透過 Stripe。

| SKU | 價格 | 供應狀態 |
|---|---|---|
| **VM Small — 1 × AMD Instinct MI300X**（192 GB HBM3、8 或 13 CPU 核心、224 GB 系統記憶體、12 TB NVMe） | **$2.99／GPU／小時**，以分鐘計費、隨用隨付、無合約 | 現可自助購買。**公司自述機隊已達 100% 產能且有客戶排隊，因此實際可用性受限**（[/pricing](https://hotaisle.xyz/pricing)） |
| **VM Medium — 2 × 與 4 × AMD Instinct MI300X**（384 GB 或 768 GB HBM3、26 或 52 CPU 核心、448 GB 或 896 GB 記憶體、12 TB NVMe） | **$2.99／GPU／小時**，以分鐘計費 | 現可自助購買。同樣受 100% 產能限制（[/pricing](https://hotaisle.xyz/pricing)） |
| **Bare Metal Large — 8 × AMD Instinct MI300X 整節點**（1.5 TB HBM3、64 或 102 CPU 核心、2 TB 記憶體、122 TB NVMe、Dell XE9680 機箱、完整 root／SSH／BMC／iDRAC 權限、8×400G RoCEv2、私有隔離網路、公開 IPv4 ＋ IPv6） | **$3.39／GPU／小時 ＝ $27.12／節點／小時。** **最短承諾一個月——這是其整份型錄中唯一的承諾條款** | 現可預約，「Reserve Bare Metal」為預約流程而非即時自助（[/pricing](https://hotaisle.xyz/pricing)） |
| **舊約沿用之 MI300X 費率** | **$1.99／GPU／小時** — 對持續使用中的既有客戶**無限期保留**。新客戶為 $2.99 | **自 2026-07-14 起不再開放新客戶**（[/pricing](https://hotaisle.xyz/pricing)；[Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)） |
| **AMD Instinct MI355X — 每系統 8 張**（每張 288 GB HBM3E、8 TB/s、1,400 W，八卡系統合計 2.3 TB，直接液冷） | **未公布價格** | **無法供應——尚未採購。** 公司逐字表示：**「We are still raising the capital required to buy and deploy the hardware.」** 先前的登記實驗**只收到意向承諾**。第三方比價站仍把 Hot Aisle 列入 MI355X 供應商，研判反映的是**意向／候補名單而非已部署產能——該類名單應視為不可靠**（[/mi355x](https://hotaisle.xyz/mi355x)；[getdeploying.com](https://getdeploying.com/gpus/amd-mi355x)） |
| **AMD Instinct MI325X** | **從未提供** | **從未部署——整個世代被跳過。** 2024 年 11 月的 cluster 頁曾預告「soon MI325x」，但任何存檔快照中都不曾出現 MI325X 頁面或價格（[空結果集的 CDX 查詢](http://web.archive.org/cdx/search/cdx?url=hotaisle.xyz/mi325x&matchType=prefix)） |
| **Cluster Design & Deploy 顧問服務**（非 GPU 營收線） | **報價制，未公布** | 提供中——以工作負載為起點的叢集設計，涵蓋運算、儲存、管理與公網路徑；歷史上亦包含資料中心／保險／網路合約談判（[/cluster/](https://hotaisle.xyz/cluster/)；[Wayback 2024-11-14](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)） |

**AI 佈局判讀。** 這是一支**單一世代、單一供應商、偏推論用途、產能已封頂且後面有人排隊**的機隊。他們處於 100% 使用率、選擇漲價而非降價、有 **>$50M 未被滿足的 MI355X 需求**，並且為了資金因素**整整跳過一個 AMD 世代**。**沒有 NVIDIA 硬體，也沒有加入的意圖。** 商業上的結論是：**這個帳戶的整場 AI 對話都是關於下一座叢集，不是現有那一座**——而下一座叢集，是一個他們從未部署過的世代上的開放平台決策。

---

## 7. 採購時鐘

Hot Aisle 實際上多久買一次硬體。以 Wayback CDX 對 [hotaisle.xyz/pricing](https://hotaisle.xyz/pricing) 進行快照差分（20 份快照，2024 年 6 月至 2026 年 7 月）、`/mi300x`／`/mi355x`／`/mi325x` 的首次出現日期、ARIN 登記時戳、網域 RDAP，以及有日期的部落格文章重建。

### 7.1 時間軸

| # | 日期 | 事件 | 來源 |
|---|---|---|---|
| 1 | **2023-10-18** | **hotaisle.xyz 與 hotaisle.ai 相隔三秒註冊**，註冊商 Spaceship, Inc.。公司創立於 2023 年 10 月 | [RDAP](https://rdap.centralnic.com/xyz/domain/hotaisle.xyz)；[About 頁](https://hotaisle.xyz/about/) |
| 2 | **2024-01-15** | **ARIN Org HA-716 登記** | [ARIN](https://rdap.arin.net/registry/entity/HA-716) |
| 3 | **2024-02-14** | **AS21566「HOTAISLE」核配**，同時取得 23.183.40.0/24 與 2602:f955::/36。**網路建置比硬體早七個月** | [ARIN](https://rdap.arin.net/registry/entity/HA-716) |
| 4 | **約 2024 Q2–Q3** | 與 Advizex、Dell、Broadcom、Panduit 進行**四個月每週基礎設施規劃會議** | [Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle) |
| 5 | **2024 年 9 月初** | **採購／部署事件 #1——迄今唯一一次機隊採購：** 約 16 台 Dell PowerEdge XE9680、約 128 張 MI300X。由 2024-09-13 的現場筆記定年：「After a bit more than a week, we have fully deployed our own high-performance super computing cluster」——因此**上架約自 2024-09-04 開始** | [Cruising to the finish line，2024-09-13](https://hotaisle.xyz/blog/cruising-to-the-finish-line/) |
| 6 | **2024-06-17 → 2024-11-14** | 價格**固定於 $4.50／GPU／小時，單一 SKU** | Wayback 定價快照 |
| 7 | **2024-12-14** | `/mi300x` 產品頁**首次存檔** | Wayback CDX |
| 8 | **2025-03-24** | **出現分層定價（$2.00–$3.00）**，並標示「coming soon」 | Wayback 定價快照 |
| 9 | **2025-05-12** | 分層下探至 **$1.50** | Wayback 定價快照 |
| 10 | **2025-07-25** | 收斂為**單一價 $1.99／GPU／小時**。**十個月內降價 56%——典型的「以價格追使用率」，且是在一支已付清、完全自有的機隊上** | Wayback 定價快照 |
| 11 | **2025-09-30** | `/mi355x` 頁**首次存檔**——公開宣告下一世代目標，**距第一次建置整整十二個月** | Wayback CDX |
| 12 | **2025-07-01／2025-09-18** | **SOC 2 Type 1**，其後 **SOC 2 Type 2** | [gen.xyz](https://gen.xyz/blog/hotaisle-xyz) |
| 13 | **2026-05-18** | **$3.39 裸機層出現** | Wayback 定價快照 |
| 14 | **2026-07-14** | **轉折點。** 價格對新客戶**自 $1.99 調高至 $2.99**；**ARIN 組織紀錄同日更新**；理由明載為**「We are at 100% capacity」**且**「有客戶排隊等候 MI300X 產能」** | [Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)；[ARIN](https://rdap.arin.net/registry/entity/HA-716) |
| 15 | **2026-08（現在）** | **Investors 頁上線：募集 $50–100M，明載用於購買 MI355X 系統** | [Investors 頁](https://hotaisle.xyz/investors) |

### 7.2 節奏

**三年一次機隊採購——這就是全部的發現。** 這**不是週期性換代的買家。** 節奏不是年度、不與 AMD 產品週期綁定、也不與折舊綁定。**證據：儘管 2024 年 11 月已預告，他們仍整個跳過 MI325X。**

決定性變數是**資金可得性**，而可觀察的觸發序列一致且可重複：

> **持續 100% 使用率 → 調漲價格 → 公開募資 → 採購**

該序列在 2024 年跑過一次，一路推進到 2024 年 9 月的建置，**而現在它正在重跑，且進度比以往任何時候都更接近終點。**

**最近一次硬體採購：** 2024 年 9 月初（約 16 台 Dell XE9680／約 128 張 MI300X，約一週內完成部署，由 Advizex 整合）。
**最近一次商業事件，也是關鍵的那一次：** **2026-07-14**，以 100% 產能與排隊名單為明確理由，將價格自 $1.99 調高到 $2.99。
**最近一次戰略事件：** Investors 頁上線、募集 $50–100M 用於 MI355X——這就是本帳戶今天（**2026-08-11**）所在的位置。

### 7.3 下一個窗口

> ### **現在就是開的——且只卡在一件事：$50–100M 募資的完成。**

**所有採購前提都已滿足，而且都是公開陳述的：** 100% 使用率；客戶排隊；**>$50M 已表態的 MI355X 需求**；已完成的調價；三年的生產運行紀錄；SOC 2 Type 2 與 HIPAA；以及明白宣示願意採用**股權、策略投資或資產融資**。他們直接說了：**「The constraint is access to hardware, not demand for the platform.」**

**預估採購窗口：2026 下半年至 2027 上半年，由募資完成觸發，而非任何日曆日期。**

**每週應監看的領先指標：**

| 優先序 | 觸發線 | 意義 |
|---|---|---|
| **1 — 價值最高** | [hotaisle.xyz/mi355x](https://hotaisle.xyz/mi355x) **移除「We are still raising the capital required to buy and deploy the hardware」這句話，或出現價格** | 平台決策正在做、或已經做完，最乾淨的單一訊號 |
| 2 | **AS21566 名下出現新的 ARIN 網段核配，或出現 PeeringDB 紀錄** | 代表正在建置第二站 |
| 3 | **[/datacenter](https://hotaisle.xyz/datacenter) 出現 Switch Pyramid 以外的設施名稱** | 區域推論站點正式上線 |
| 4 | **Advizex 或 Dell 發布 MI355X 叢集相關新聞** | **代表窗口已對我方關閉** |
| 5 | **出現提及 Mesh.xyz 或新策略投資人的募資公告** | 錢已到位；平台決策很可能已經定案 |

**因為他們是一次買下整座叢集、而且會跳世代，這是一個二元的、高價值的、單發的窗口——錯過這次，下一次可能是兩年後。現在就要進場，趕在募資完成之前，因為平台決策是在替投資人建模型的時候做的，不是在錢落地之後。**

### 7.4 方法

以 Wayback Machine CDX API（`http://web.archive.org/cdx/search/cdx`）依 URL 前綴查詢 `hotaisle.xyz/pricing`、`/mi300x`、`/mi355x` 與 `/mi325x`；每份快照以 `id_` 原始修飾符抓取並解 gzip，再以正規表示式掃描 GPU SKU 字串與金額。**十二份定價快照產出乾淨的價格與 SKU 序列**；各 GPU 產品頁的首次出現日期，替每一個世代的公開登場定年；**`/mi325x` 的空 CDX 結果，正是「跳過一個世代」這項發現的依據。** 全部與有日期的一手部落格文章、ARIN RDAP 登記與最後異動時戳，以及網域 RDAP 建立日期交叉驗證。**所有日期皆有存檔或登錄機構戳記，無一由文字敘述推得。**

**信心水準：** 時間軸本身為**高**（每個日期都有存檔或登錄戳記）。「僅一次採購」此一發現為**高**（MI325X 的負面結果是橫跨整個存檔的乾淨空結果集）。前瞻窗口為**中**——它取決於一次由公司自行斟酌時點公布的募資完成，**事前無法觀測。**

---

## 8. UCC 融資紀錄

**本軌研究範圍：** Hot Aisle Inc.（[hotaisle.xyz](https://hotaisle.xyz/)，AS21566）——研判設立州為**懷俄明州**（未確認，第 2 節）；**擔保物所在地為密西根州**，因為伺服器位於 Grand Rapids 的 Switch Pyramid。

### 8.1 判定

> ### UNVERIFIED — portal blocked

**請完全照字面理解。** **未取得任何 UCC-1、修正、讓與、延續或終止文件，因此本檔不報告任何一筆。** 無 filing number、無 filing date、無 lapse date、無擔保權人姓名或地址、無債務人姓名或地址、無擔保品描述——**因為任何候選設立州的 UCC 索引都無法觸及。**

**本檔明確地不會、也絕不會報告「無融資」。** 唯一誠實且正確的陳述是：**入口被阻擋。** 8.2 的空白代表**什麼都沒看到**。此結果不得對客戶陳述、不得引用給徵信單位、也不得以「查無留置權」寫入 CRM。

### 8.2 已登錄之申報——逐筆全文，不省略

**取得筆數：0。**

以下沒有任何申報區塊，因為**任何介面都不曾回傳過任何一筆**。沒有任何內容被壓縮、簡寫或摘要掉——**登記簿從未被觸及。** 因此，信用或通路決策所需的每一個逐筆欄位，都是明確的 GAP：

| 逐筆必要欄位 | `HOT AISLE INC`（懷俄明——研判設立州） | `HOT AISLE INC`（密西根——擔保物所在地） |
|---|---|---|
| Filing number（申報編號） | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Filing date（申報日期） | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Lapse date／延續狀態 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| 擔保權人姓名＋地址 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| 債務人姓名＋申報地址 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| 擔保品描述（逐字） | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| 修正／讓與／終止 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| 紀錄連結 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |

### 8.3 查詢紀錄——一次嘗試一列，不合併

| 入口／URL | 預定送出之查詢字串 | 逐字回應 | 替代路徑 |
|---|---|---|---|
| **懷俄明 — UCC 查詢**（研判之設立州，依 ARIN 與 D&B 的 Cheyenne 地址）· [wyobiz.wyo.gov/UCC/UCCSearch.aspx](https://wyobiz.wyo.gov/UCC/UCCSearch.aspx) | 債務人精確比對 `HOT AISLE INC`、前綴比對 `HOT AISLE`。**從未執行——搜尋表單自始未能觸及** | 以 curl 取得 **HTTP 200**，但內容是 **F5／Shape 機器人防禦的 JavaScript 挑戰，不是搜尋表單**。改以真實瀏覽器重試：頁面呈現扭曲圖形 CAPTCHA，文字為「This question is for testing whether you are a human visitor and to prevent automated spam submission. What code is in the image? submit. Your support ID is: **11385417910158787977**.」**未嘗試破解該 CAPTCHA** | 由真人操作瀏覽器於同一網址查詢，或委外／向懷俄明州務卿申請 **UCC-11 債務人查詢** |
| **懷俄明 — 商業實體查詢** · [wyobiz.wyo.gov/Business/FilingSearch.aspx](https://wyobiz.wyo.gov/Business/FilingSearch.aspx) | 實體名稱 `HOT AISLE INC`，以確定設立州、實體編號與註冊代理人 | **完全相同的 CAPTCHA**，support ID **11385417910158757353**。未破解 | 同上；另可以**懷俄明良好存續證明**確定設立州 |
| **懷俄明 — 已探測之替代主機** · uccsearch.wyo.gov · sosbiz.wyo.gov · uccfiling.wy.gov · ucc.wyo.gov · sos.wyo.gov/Business/UCC.aspx | 任何免驗證的 UCC 債務人查詢路徑 | `uccsearch.wyo.gov` → **連線失敗（curl exit code 000）**；`sosbiz.wyo.gov` → **000**；`uccfiling.wy.gov` → **000**；`ucc.wyo.gov` → **HTTP 302 轉回受 CAPTCHA 保護的 wyobiz 主機**；`sos.wyo.gov/Business/UCC.aspx` → **HTTP 404** | **這些端點無任何可行路徑。** 僅能人工／委外查詢 |
| **密西根 — LARA 公司與 UCC 入口**（實體擔保物所在州）· [cofs.lara.state.mi.us](https://cofs.lara.state.mi.us/CorpWeb/CorpSearch/CorpSearch.aspx) 與 `/UCC/UCCSearch.aspx` | `HOT AISLE`。**從未執行** | 連線始終未完成。curl verbose 輸出：「Connected to cofs.lara.state.mi.us (172.64.144.107) port 443 / TLS handshake, Client hello (1) / **LibreSSL/3.3.6: error:1404B410:SSL routines:ST_CONNECT:sslv3 alert handshake failure** / Closing connection」。DNS 解析至 **cofs.lara.state.mi.us.cdn.cloudflare.net**（104.18.43.149、172.64.144.107），故為 **Cloudflare 邊緣機器人防護拒絕該 TLS 指紋**。以 `--tlsv1.2 --tls-max 1.2` 重試 → **HTTP 000**；以 `-k`（不驗證）重試 → **HTTP 000**；`ucc.lara.state.mi.us` → **000**；`/SearchApi/Search/Search` 端點以 GET 與 POST（JSON body）嘗試，**回傳為空** | 由真人操作瀏覽器，或委外進行密西根 UCC-11 債務人查詢 |
| **德拉瓦 — Division of Corporations ICIS** · [icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx](https://icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx) | 於欄位 `ctl00$ContentPlaceHolder1$frmEntityName` 輸入 `HOT AISLE`，**僅送出一次** | 頁面載入 **HTTP 200，48,338 bytes**。逐字回應，於輸入框旁以黃色標示：**「An error occurred while processing the request」**，FILE NUMBER／ENTITY NAME 結果表為空。該頁載有公告「The Division of Corporations strictly prohibits mining data… Use of automated tools in any form may result in the suspension of your access to utilize this service」——因此**僅執行一次查詢，未重試** | **另需分開記錄：德拉瓦根本不提供免費的線上 UCC 債務人索引。** 德拉瓦 UCC 查詢採委託訂購制，經 [services.sos.delaware.gov](https://services.sos.delaware.gov/)（已探測，本環境回 **HTTP 000**），因此**即使連線未受阻，也不會產出可自助查詢的德拉瓦 UCC 結果** |
| **資料聚合站——因主要入口全數失敗而作為備援嘗試** · [opencorporates.com](https://opencorporates.com/companies?q=%22Hot+Aisle%22) · [bizapedia.com](https://www.bizapedia.com/search.aspx?q=hot+aisle) · corporationwiki.com · opengovus.com | `"Hot Aisle"`／`Hot Aisle` | OpenCorporates → **HAProxy CAPTCHA 挑戰頁**，抓取與瀏覽器皆然。Bizapedia → **拖曳式人機驗證**。CorporationWiki → **HTTP 403**。OpenGovUS（wyoming-business 與 michigan-business）→ **HTTP 404「File not found.」** | **沒有任何聚合站備援可用。** 全數受阻 |

### 8.4 這份紀錄的意義

以下為推論，非親眼所見的證據。**請把下述先驗當成要在會談中「驗證」的假說，絕不可當成結論。**

**公司自己怎麼說融資——這是直接證據，且不依賴任何 UCC 索引。** [Investors 頁](https://hotaisle.xyz/investors) 表明正募集 **$50–100M，管道為「equity, strategic investment, and asset finance」**，並載「The capital will purchase AMD MI355X systems and fund the networking, rack integration, and site deployment.」**把「資產融資」與股權並列、明白列為第三條獨立管道，是本次研究所能取得最具證明力的融資訊號**，且指向**正在考慮擔保式硬體融資**——若真的執行，就會產生一筆以伺服器為擔保品的 UCC-1。

**至於 2024 年那次建置，另有一個同樣合理的競爭解讀。** 他們自創立起即有 Mesh.xyz（Joseph Lubin 的孵化器）支持；兩位創辦人來自 W3BCloud，在那裡跑過 150,000 張 AMD GPU；而 2024 年的 cluster 頁自誇「Our deep relationships with vendors will ensure you get the best pricing」與「you can harness supercomputer-grade resources without the hefty CapEx」（[Wayback 2024-11-14](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)）。這與**股權出資購買**、**經 Dell Financial Services 的原廠／供應商融資**，或**由 Advizex 安排的供應鏈結構**都相容——而以上任何一種，都可能產生、也可能不產生申報。

**商業結論，這才是重點。** 因為下一座叢集的資金機制**確實未定**，且客戶**已公開表示資產融資在選項之內**，融資結構就是一個**開放的槓桿，而不是既定的限制。將 Supermicro 的租賃／融資方案帶進第一次對話。** 同時：**不得斷言、不得暗示、不得旁敲側擊說他們有債務融資或已設定擔保**——那未經證實，把它當成事實陳述既錯誤又具破壞性。

**補齊此缺口的行動：** 委外或直接向懷俄明州務卿申請，就 **`HOT AISLE INC` 在懷俄明州**（研判設立州）**與密西根州**（擔保物所在地）進行 **UCC-11 債務人查詢**，並調取**懷俄明良好存續證明**以確定設立州、實體編號與註冊代理人。**請在任何信用或通路核准對話之前完成這件事。**

---

## 9. 成本天花板

一個 8-GPU 節點對 Hot Aisle 能值多少錢，以及今天買一台最接近的對等機種要多少錢。**本節只回答一個問題：硬體成本壓到多少，一個 Hot Aisle 節點才還付得回本？**

### 9.1 假設——請先讀這段；這些是假設，不是研究發現

**這是一個以假設驅動的模型，不是研究出來的事實。只有公開價格是有來源的；營運成本佔比與回收期都是假設，並以區間形式呈現。**

**有來源、非假設者：** 三個公開價格（裸機 $3.39、新客 VM $2.99、舊約 $1.99）、8-GPU 節點組態、裸機最短一個月承諾、100% 產能陳述（[/pricing](https://hotaisle.xyz/pricing)；[調價文章](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)），以及由 2025 年退役 781 張 REC（781 MWh ÷ 8,760 h）推得、並以 2024 年 267 張 REC 攤在約四個月上線期交叉核對的 **約 90 kW 平均設施負載**。

**假設、無來源者：**

1. **營運成本佔營收比：35% 至 55%**，即**留下 45% 至 65% 的營收可用於支應硬體**。此範圍涵蓋 Switch 主機代管電力與空間、Switch Connect 與 Megaport 傳輸、Dell ProSupport、Stripe 金流費、工程與支援人力、一般行政——以及**他們沒有業務團隊**這件事。**此區間為本檔主張；公司完全未揭露任何成本資料。**
2. **回收期 12、18 或 24 個月。**
3. **維持 100% 進駐率、以牌價計價**，無折扣、無免費額度、無故障節點——**這是寬鬆假設**，且他們歷史上確實推過免費運算方案。
4. **每月 730 小時、每年 8,760 小時。**
5. **叢集設計顧問收入不計入。**
6. **回收期末不計殘值。**
7. **融資成本視為零**，若他們採用資產融資，這會**低估**真實天花板。

### 9.2 由租金推導之每節點天花板

**滿載時的每節點毛營收**（8 張 GPU × 每月 730 小時、每年 8,760 小時）：

| 費率 | 每節點小時 | 每節點月 | 每節點年 |
|---|---|---|---|
| **裸機 $3.39／GPU／小時** | **$27.12** | **$19,798** | **$237,571** |
| **新客 VM $2.99／GPU／小時** | **$23.92** | **$17,462** | **$209,539** |
| **舊約 $1.99／GPU／小時** | **$15.92** | **$11,622** | **$139,459** |

**推得之每 8-GPU 節點硬體成本天花板**（營收 × 45–65% 可用於硬體）：

| 回收期 | 以裸機費率計 | 以新客 VM 費率計 | **混合工作區間——報價時請用這一欄** |
|---|---|---|---|
| **12 個月** | $107k – $154k | $94k – $136k | **約 $95k – $155k／節點（每 GPU $12k – $19k）** |
| **18 個月** | $160k – $232k | $141k – $204k | **約 $140k – $230k／節點（每 GPU $18k – $29k）** |
| **24 個月** | $214k – $309k | $189k – $272k | **約 $190k – $310k／節點（每 GPU $24k – $39k）** |

> **敏感度警示。** 一旦使用率跌破 100%，這套數字會迅速崩解；而**他們自己的歷史就是十個月內降價 56%（$4.50 → $1.99）以追使用率，等需求追上來**（第 7 節）。**對這個客戶而言，24 個月回收是激進假設；以 12–18 個月為談判基準較為安全。** 所有數字都是模型輸出，不是公司揭露。

### 9.3 BOM 重建——今天買一台對等節點要多少

**雙向比較。**

| 路徑 | 平台 | 市場價 | 供貨 | 來源 |
|---|---|---|---|---|
| **(a) DELL — 既有路徑** | Dell PowerEdge XE9680 搭 8 × AMD Instinct MI300X（兩顆第 4 代 Intel Xeon Scalable，各最高 56 核；32 × 64 GB DDR5 4800 MT/s；8 × MI300X 走 Infinity Fabric；最多 8 × 2.5" NVMe 至 122.88 TB） | **無公開市場價——僅供報價。** 最接近的公開參考（Uvation Marketplace）列出該組態但**未顯示價格**，並導向業務以 PO 方式報價。**本檔選擇不報 Dell 價格，而非自行估算** | **「Estimated Delivery 4 Weeks」** | Uvation Marketplace XE9680 MI300X 商品頁 |
| **(b) SUPERMICRO — 對等機種，且有公開標價** | **Supermicro AS-8125GS-TNMR2**，8U GPU A+ Server，8 × AMD Instinct MI300X OAM，雙 AMD EPYC 9005／9004 最高 400 W TDP，24 個 DDR5 DIMM 槽至 6 TB／6000 MT/s，前置 12 個熱插拔 2.5" NVMe（可擴至 16），另有 2 個 SATA 與 M.2 開機碟 | **$275,863.87** | **有現貨，3–5 個工作日出貨** | [Supermicro eStore](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html) |
| **(b) 交叉核對** | 同一平台，經銷商掛牌 | **$281,548.48**（Dihuni）——量級相符。**該頁直接抓取時回傳 HTTP 307 轉址迴圈，故此數字為檢索浮現而非頁面實查——僅供參考** | — | 檢索浮現；**未經頁面實查** |

**可比性警語：$275,863.87 是起始價。** Hot Aisle 的實際規格（2 TB 記憶體、122 TB NVMe、八張 Broadcom 57608 200G 網卡）會**高於**基本配置。

### 9.4 彙總——這個落差對提案的意義

**結論標題：以牌價計，對等節點無法在任何可信的回收期內回本。能成交的是折扣 ＋ 融資 ＋ 交期，不是規格表。**

**每節點 $275,864 ＝ 每 GPU $34,483。** 對照 9.2 的租金推導區間：

| 回收期 | 每節點天花板 | $275,864 的節點通過嗎？ |
|---|---|---|
| 12 個月 | $95k – $155k | **不通過——差距極大** |
| 18 個月 | $140k – $230k | **不通過** |
| 24 個月 | $190k – $310k | **僅在營運成本假設最寬鬆的一端勉強通過** |

**報價結論：**

1. **牌價無法在任何可信回收期內成交。** 能成交的是 (i) **實質折讓後的交付價落到每節點約 $230k 以下**以達成 18 個月回收，以及／或 (ii) **以融資把問題從「回收期」轉換成「每月現金支出」**——這正是他們自己提到「asset finance」之所以重要的原因（8.4）。
2. **把交期對比帶進會議室：** **有現貨、3–5 個工作日出貨**，對上 **Dell 約 4 週的報價交期**，而客戶自陳唯一的限制就是產能到位時間。**對這位買家而言，交期就是價格。** 用他們自己的公開價格量化：**一個 8-GPU 節點每閒置一週，以 $3.39／GPU／小時計，約等於 $4,550 未計費產能。**
3. **任何報價都必須包含 L11／L12 機櫃整合、預備、Grand Rapids 物流與現場備品**——因為 Advizex 交付的是**上架完成、可運轉的叢集**，一個裸箱在完整度上必輸，不論單價（3.3）。
4. **注意：2026–27 的真實決策是 MI355X，不是 MI300X**，而**兩家供應商的 8× MI355X 每節點市場價都查無公開資料**——這仍是 GAP（第 14 節）。上表的 BOM 比較錨定在**上一個世代**，簡報時必須如實說明。

---

## 10. 客戶與網路

### 10.1 客戶

**全站沒有任何具名客戶標誌牆——研判為刻意。** 只有四個關係有證據顯示曾在 Hot Aisle 自家硬體上執行，而其中一個是 benchmark 關係而非商業關係。

| 關係 | 等級 | 來源實際內容 |
|---|---|---|
| **700+ 客戶（總數，未具名）** | **CONFIRMED 為公司陳述** | 公司陳述兩次——[首頁](https://hotaisle.xyz/)（「700+ customers served」）與 [Investors 頁](https://hotaisle.xyz/investors)（「more than 700 customers … Customers around the world have used the platform for compute without procurement drag」）。自助、刷卡、無合約模式，因此**客戶基礎是長尾的開發者與新創，而不是少數大型客戶** |
| **dstack**（GPU 編排廠商） | **CONFIRMED — 最強的具名關係** | 列於 [/partners](https://hotaisle.xyz/partners)「GPU-native orchestration」。合著部落格 [「Orchestrating AMD GPUs with dstack」](https://hotaisle.xyz/blog/gpu-orchestration-with-dstack)（2026-03-02）。dstack 發表的 benchmark——「Exploring inference memory saturation effect: H100 vs MI300x」與「Llama 3.1 405B on 8x MI300X」——**是在 Hot Aisle 提供的 8 × MI300X 硬體上執行**（[dstack.ai](https://dstack.ai/blog/h100-mi300x-inference-benchmark/)）。dstack 創辦人亦在 hotaisle-website 倉庫中有提交。**同時扮演夥伴、參考案例與通路三種角色** |
| **Red Hat（Neural Magic）** | **CONFIRMED** | 合著部落格 [「Computing for All: Hot Aisle + Red Hat (Neural Magic) + AMD」](https://hotaisle.xyz/blog/hot-aisle-red-hat-neural-magic-amd-open-ai-inference-mi300x)（2025-05-15），主題為 MI300X 上的開放 AI 推論。**顯示其機隊上有企業級推論驗證工作** |
| **Dr. Moritz Lehmann — FluidX3D CFD** | **CONFIRMED** | Hot Aisle 部落格（2025-03-03）引述其在 8 × MI300X 伺服器上的 FluidX3D CFD 成績：**205 GLUPs/s、23 TB/s VRAM 頻寬**。**獨立研究者在其硬體上跑真實工作負載**（[文章](https://hotaisle.xyz/blog/dr-moritz-lehmann-linkedin-hot-aisle-8x-amd-mi300x-fastest-fluidx3d-cfd)） |
| **SemiAnalysis** | **CIRCUMSTANTIAL — 屬 benchmark／分析師關係，不是商業客戶** | SemiAnalysis 的 MI300X vs H100 vs H200 benchmark 研究，將 Hot Aisle 列為支援開源 MI300X benchmark 的業者之一（與 TensorWave、Nebius、Lambda、Sustainable Metal Cloud 並列），Hot Aisle 亦於自家參考索引中列出 SemiAnalysis 的「Faster tokens for fewer dollars」（[SemiAnalysis](https://newsletter.semianalysis.com/p/mi300x-vs-h100-vs-h200-benchmark-part-1-training)；[/benchmarks-and-analysis](https://hotaisle.xyz/benchmarks-and-analysis/)） |
| **警示——benchmark 參考索引不是客戶名單** | **明確載明，以免日後被當成標誌清單開採** | [/benchmarks-and-analysis](https://hotaisle.xyz/benchmarks-and-analysis/) 索引約 20 個第三方來源，包括 Oracle Cloud、Nscale、RunPod、Fireworks.ai、Chips and Cheese、Anthracite 的 Magnum 72B、AMD 社群 MLPerf 文章與多則 Reddit 討論。**這些是關於 MI300X 的外部策展參考，不是 Hot Aisle 的客戶。** 只有 dstack、Red Hat／Neural Magic 與 Moritz Lehmann 有在其硬體上執行的證據 |

**GAP — 無任何營收端具名客戶、無任何具名的客戶案例研究、全網無任何合約金額證據。**

### 10.2 網路 — AS21566

- **登錄：** **AS21566**，ARIN 代號 **HOTAISLE**，ASN 範圍 21566-21566，狀態 **Active**，登記於 **2024-02-14T11:05:57-05:00**，隸屬 Org **HA-716**（Hot Aisle Inc.）。Org 紀錄 **最後異動 2026-07-14**——與公開調價同一天。
- **位址空間：** IPv4 **23.183.40.0/24**（代號 NET-23-183-40-0-1，網段名「HA-4-10」，Active）；IPv6 **2602:f955::/36**（代號 NET6-2602-F955-1，網段名「HA-SOPH」，Active）。**注意形狀：** IPv4 只有**單一 /24（256 個位址）**，與單站小規模據點一致；而 **/36 的 IPv6 很大且具前瞻性**，與其自述的 IPv6 優先設計與多站企圖一致。
- **運算網路：** **RoCEv2、每節點 3.2 Tbps**，經每台 Dell XE9680 八張 **Broadcom 57608** 雙埠 200G Q112 網卡，交換於 **Dell PowerSwitch Z9864F**（定價頁行銷為「8x400G networking」）。
- **叢集服務／東西向／儲存：** **100 Gbps**，經 **Broadcom 57504** 四埠 10/25GbE，交換於 **Dell PowerSwitch Z9664F**。
- **管理平面：** **1 Gbps 頻外**，經 **Broadcom 5720** 雙埠 1GbE，交換於 **Dell PowerSwitch Z9432F**。
- **對外網路：** **經 Switch Connect 與 Megaport 的 100G 連線**；每台裸機伺服器與 VM 均含公開 IPv4 與 IPv6。
- **設計：** IPv6 優先定址、VRF 隔離、全網自動化 **SONiC**。
- **可維修性：** **每台交換器均有 Dell ProSupport Next Business Day**，Z9864F 另有 **4 小時關鍵任務等級，並備有現場替換零件。**
- **Peering：無——而這本身就是發現。** [PeeringDB API 查詢](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle) 回傳**空的 data 陣列**。他們**未進駐任何網際網路交換中心**、**未公布 peering 政策**、**除單一 ARIN 職務帳號外未列任何 NOC 或 peering 聯絡人**。連線是**外購的**——經 Switch Connect（設施營運商自家的網路服務）與 Megaport 的 100G。這與**推論服務型主機代管租戶而非網路營運商**的定位完全一致，也代表**沒有任何 peering 社群路徑可以切入這個帳戶**——唯一的網路聯絡點是 netops@hotaisle.xyz。

來源：[ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716) · [/networking](https://hotaisle.xyz/networking) · [/pricing](https://hotaisle.xyz/pricing) · [PeeringDB（空）](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle)

---

## 11. 政治與公開紀錄

僅列公開紀錄。每一列均加註標籤。僅限具名主事者。

| 對象 | 查得內容 | 標籤 |
|---|---|---|
| **Clint Armstrong** — Co-Founder & Head of Engineering | **查有紀錄——單一筆，且為其完整捐款史。** ARMSTRONG, CLINT · Grantham, NH 03753-3433 · 職業 **ENGINEER** · 雇主 **HOT AISLE** · 受款方 **WINRED** · 收款日 **2024-06-22** · **$50.00** · 申報於 Form 3X 第 11AI 行。以姓名＋州別查詢**恰好回傳一筆**，而以雇主「Hot Aisle」對全 FEC 資料庫查詢則**只回傳這一列，別無其他**。**這份申報另外帶出兩項比政治本身更有操作價值的事實：** 它**獨立佐證了他在 Hot Aisle 的僱傭關係**，而且**把他定位在新罕布夏州，不是密西根州**（[FEC](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle)） | **偏右，金額微不足道（$50）。** WinRed 為共和黨小額捐款處理平台 |
| **Jon Stevens** — Co-Founder & CEO | **以雇主「Hot Aisle」查詢查無紀錄**——該雇主篩選對他回傳**零筆**。有一筆**研判為其本人但不確定**的歷史紀錄：STEVENS, JON · Entiat, WA 98822 · 職業 **DIRECTOR OF IT** · 雇主 **W3BCLOUD** · 受款方 **ACTBLUE** · **2020-09-19** · **$25.00** · 備註「EARMARKED FOR MCGRATH FOR US SENATE (C00922591/C00711549)」。歸屬的依據是雇主與其有據的前東家相符；**弱點在於自陳職業「Director of IT」與 Co-Founder/CTO 不符。** **以下排除項明確載明，以免日後被誤當命中：** 以姓名於**密西根州查詢回傳 27 筆，解析為另一人**（Farmington, MI 的 Jon Stevens，職業與雇主皆為「NOT EMPLOYED」）；以姓名於**華盛頓州查詢回傳 2,091 筆**，絕大多數是一位高頻小額捐款者 Jonathan Stevens，**無法與其連結**。**以上皆不歸屬於他**（[FEC W3BCLOUD 查詢](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Stevens%2C+Jon&contributor_employer=W3BCLOUD)） | **若該筆 W3BCloud 紀錄確為其本人則偏左；否則查無紀錄。** 金額微不足道（$25） |
| **Hot Aisle Inc.**（公司） | **查無公司 PAC、無委員會登記、無任何形式的公司政治活動。** 全 FEC 資料庫中唯一以 Hot Aisle 為雇主的紀錄，就是 Clint Armstrong 那一筆 $50（[FEC](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle)） | **無——組織層面政治零活動** |
| **訴訟／公開裁處** | **查無法院案卷——研判為真負面，但非窮盡。** CourtListener 以「Hot Aisle Inc」精確詞作為當事人查詢回傳 **0 筆**；較寬鬆的「Hot Aisle」RECAP 查詢回傳 32 筆無關的資料中心專利訴訟（Valtrus、Key Patent Innovations、Vertiv 等），僅因通用術語而命中。**僅涵蓋聯邦層級**——未執行密西根、懷俄明、新罕布夏或華盛頓的州法院查詢，且 CourtListener 的 RECAP 覆蓋率本質上並不完整（[CourtListener API](https://www.courtlistener.com/api/rest/v4/search)） | **gap — 負面結果，非窮盡** |
| **給業務專員的操作結論** | **兩位共同創辦人的政治捐款方向相反**——Armstrong 捐 WinRed、Stevens（研判）捐 ActBlue——**且金額都小到顯示他們對政治毫無實質投入。** 這意味著**沒有共同的政治話題可以建立關係**，卻**有實質機率在一家兩人公司內部踩到斷層線** | **本帳戶不得談論政治，任何方向、任何時點皆然** |

**查無本公司或其主事者的任何法案或政策立場。** 在政治與公共政策這條軸線上，Hot Aisle 幾乎沒有公開足跡。這裡沒有可用的切入點，也沒有風險——前提是最後一列的規則被確實遵守。

---

## 12. 公開聯絡管道

僅列公開來源。**本節不列任何個人手機或私人住址，也未曾蒐集。** 無公開管道者標示 GAP。

| 管道 | 內容 | 來源 |
|---|---|---|
| **公司主要信箱——他們明白邀請的正門** | **hello@hotaisle.ai** — 注意是 **.ai** 網域，不是 .xyz。其聯絡頁寫著：「A person on the Hot Aisle team will reply directly. No AI bot, and no spam.」並依主題分流為 **Compute and deployment**、**Customer support**、**Partnerships and growth**。對硬體供應商而言，**正確的分流是「Partnerships and growth — Discuss infrastructure partnerships, deployment opportunities, or the next location for sovereign inference capacity」** | [/contact](https://hotaisle.xyz/contact) |
| **CEO 直接信箱**（公開於 git 提交後設資料） | **jon@hotaisle.xyz** — 出現在 hotaisle-cli 的提交作者欄。**合法且公開，但這是面向開發者的信箱；請先用 hello@hotaisle.ai**，此信箱作為未獲回覆時的後續管道 | [GitHub 提交](https://api.github.com/repos/hotaisle/hotaisle-cli/commits) |
| **網路營運（ARIN 已驗證）** | **netops@hotaisle.xyz** · **+1-646-389-2009** — ARIN POC NETOP393-ARIN，兼任 Admin、Tech、NOC、Abuse、DNS、Routing。646 區碼為紐約，既不符懷俄明登記地址也不符任一創辦人已知所在州，**研判為 VoIP／轉接。這是營運信箱；不得冷推銷** | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **投資／募資管道——目前意向最強的入站路徑** | Investors 頁設有 **「Discuss the raise」** 與 **「Discuss the opportunity」** 行動呼籲，並以「A conversation, not a campaign. Let's build a verifiably secure sovereign inference cloud.」作結。**鑑於他們正在尋求股權以外的資產融資，供應商融資對話走這條路徑是正當且受歡迎的** | [/investors](https://hotaisle.xyz/investors) |
| **LinkedIn——公司與兩位主事者** | 公司：[linkedin.com/company/hotaisle](https://www.linkedin.com/company/hotaisle) · Jon Stevens：[linkedin.com/in/jon-s-stevens/](https://www.linkedin.com/in/jon-s-stevens/) · Clint Armstrong：[linkedin.com/in/clint-armstrong/](https://www.linkedin.com/in/clint-armstrong/)。**Stevens 發文活躍，是回應性較高的公開身影** | [About 頁](https://hotaisle.xyz/about/) |
| **X／Twitter** | **@hotaisle**（公司）。Jon Stevens 的 GitHub 個人檔案也列出 twitter_username「hotaisle」，因此**公司帳號實質上就是他本人** | [GitHub jon-hotaisle](https://api.github.com/users/jon-hotaisle)；[gen.xyz](https://gen.xyz/blog/hotaisle-xyz) |
| **GitHub——本帳戶最佳的技術可信度管道** | [github.com/hotaisle](https://github.com/hotaisle) — 9 個公開倉庫，含 **hotaisle-cli**（Go）、**hotaisle-website**（TypeScript）、**cloud-init-templates**、**SkyPilot 分支**，以及 apt／rpm／homebrew 套件庫。帳號：**jon-hotaisle**、**clint-hotaisle**。**在此做實質互動——一個有用的 issue 或 PR，不是行銷——對 Clint Armstrong 的效果會勝過任何一封信** | [github.com/hotaisle](https://github.com/hotaisle) |
| **溫和引介路徑（依優先序）** | **1)** AMD Instinct／neocloud 現場團隊 — Hot Aisle 自稱「AMD Exclusive AI Cloud」，AMD 也架設了 [Hot Aisle 試用申請頁](https://www.amd.com/en/products/accelerators/instinct/eval-request/hot-aisle.html)；**AMD 主導的聯合接觸是最強的開場。** **2)** **Advizex** — 既有整合商；**以潛在夥伴身分接觸，不是以取代目標身分接觸。** **3)** **dstack** — 具名夥伴，且對其網站倉庫有提交權，是可信的同儕聲音。 **4)** **Broadcom** — 本來就是 Hot Aisle 的具名夥伴與共同零組件供應商，因此 Supermicro ＋ Broadcom 的故事在通路上是延續的 | [/partners](https://hotaisle.xyz/partners) |
| **登記地址——收信信箱，不得前往、不得寄送** | **1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne, WY 82001。** 這是**註冊代理人的私人信箱，不是辦公室。** **Hot Aisle 在任何地方都沒有可以拜訪的辦公室**；唯一的實體存在是密西根 Grand Rapids 的 Switch Pyramid 園區內租用機櫃空間，進入需 **Switch 陪同、武裝警衛核可與生物辨識通行** | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)；[/datacenter](https://hotaisle.xyz/datacenter) |
| **業務直撥電話** | **GAP — 未公布，且屬刻意設計。** 公司主打「no sales calls」。只有 hello@hotaisle.ai、兩位創辦人的個人管道與 netops 專線 | — |
| **徵才／招募** | **GAP — 全網查無任何職缺**（Indeed、ZipRecruiter、LinkedIn 檢索）。無招募主管、無招募顧問姓名 | — |

---

## 13. Supermicro 銷售切入點

### 定位：**針對下一世代的全新切入（greenfield displacement）**

**不是既有客戶防守——我們沒有既有陣地。不是平台轉換——不要要求他們拆掉一座運轉中的 128 GPU MI300X 叢集。**

**誠實的判讀。** Dell 掌握既有機隊，而且掌握得理所當然——Hot Aisle 公開稱讚 Dell 為了一張「螺絲鬆掉」的 GPU 直接派兩名技師到場，並形容其支援 **「breathtaking」**（[2024-09-13 現場筆記](https://hotaisle.xyz/blog/cruising-to-the-finish-line/)）。**你搶不到那支機隊，也不該去搶。** 真正開放的是**下一座叢集**——MI355X 建置案，尚未採購、尚未取得資金，而且關鍵在於**那是一個他們從未部署過的世代**，因此沒有 MI325X 陣地形成的標準化慣性。**他們已經為了資金因素跳過一個世代，這證明平台決策每一輪都會重新打開。**

### 讓這筆生意有機會的五項事實

1. **他們處於 100% 產能且有客戶排隊**，並因此把價格從 $1.99 調到 $2.99 — **需求不是限制**（[調價文章](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)）。
2. 公司自述有 **「>$50 million in customer requests for MI355X capacity」**，並表示 **「The constraint is access to hardware, not demand for the platform.」**
3. 他們正募集 **$50–100M**，明載用於「purchase AMD MI355X systems and fund the networking, rack integration, and site deployment」，且把 **ASSET FINANCE** 列為三條管道之一——**融資是開放的槓桿，不是既定限制**（[Investors](https://hotaisle.xyz/investors)）。
4. 其 [MI355X 頁](https://hotaisle.xyz/mi355x) 直白寫著 **「We are still raising the capital required to buy and deploy the hardware」**，代表**平台尚未鎖定**，即使 Advizex 的案例研究說 MI355X 叢集會與 Advizex 一起建。**整合商承諾 ≠ 機箱承諾。**
5. **其自動化在架構上就與供應商無關**——SONiC、PXE、cloud-init、NUMA 平衡 KVM、NetBox 單一真實來源——因此**轉換成本是 BMC／Redfish 端點與 NetBox 範本，不是整套重寫。對 Clint Armstrong 要把這句話說出口；那是他會提出的異議，也是我們真的答得出來的那一個。**

### 技術楔子——比任何折扣都強

他們自家 MI355X 頁面載明**每張加速卡 1,400 W**，機櫃設計採**直接液冷**。**他們是 Switch Pyramid 的主機代管租戶——不掌握冷卻系統。** 若其租用據點的 DLC 無法取得、容量受限，或供裝時程太慢，**整個 MI355X 計畫就在關鍵路徑上掛著一個設施依賴。**

Supermicro 除液冷版本外，另出貨 **氣冷 10U 8× MI355X 系統**（2.3 TB HBM3E、第 5 代 EPYC、最高 72 核）（[新聞稿](https://www.supermicro.com/en/pressreleases/supermicro-expands-its-portfolio-performance-and-efficiency-driven-air-cooled-ai)）。**替一家資本受限、且公開表示唯一瓶頸是「拿不到硬體」的公司，從關鍵路徑上移除一個房東依賴——這是能力論述，不是價格論述，也是他們願意接這場會的最好理由。**

### 第二楔子——對這位買家而言，交期就是價格

Supermicro 的 8× MI300X 平台顯示**有現貨、3–5 個工作日出貨**（[eStore](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html)）；Dell XE9680 MI300X 路徑則是**僅供報價、經銷層級估交期約 4 週**，**而且這還是在他們第一次建置所需的四個月規劃會議之上。** 對一家營收被實體產能封頂、客戶又在排隊的公司而言，**幾週的交期會直接轉換成流失的營收。用他們自己的公開價格量化：一個 8-GPU 節點每閒置一週，以 $3.39／GPU／小時計，約等於 $4,550 未計費產能。**

### 第三楔子——可重複的單位經濟

他們自述的擴張模式是 **「smaller inference-focused sites」「compact, repeatable inference deployments」**，並且「existing automation」能讓每個站點上線而「without rebuilding the process at every site」（[Investors](https://hotaisle.xyz/investors)）。**他們買的不是一座叢集，是一個打算在各區域複製壓印的樣板。贏下參考設計一次，就贏下標準。第一個節點的定價與結構要照這個邏輯設計。**

### 第一次接觸的資格確認提問

只問一個，而且就問這一個：

> **「For the MI355X build, has Switch confirmed direct-liquid-cooling capacity and a provisioning timeline in your Pyramid footprint — and if DLC slips or isn't available at the density you need, would an air-cooled 8× MI355X platform keep the deployment on schedule?」**

這是一個**真正的營運問題**，一句話就能回答，**尊重他們「不接業務電話」的文化**，**立刻揭露設施是不是瓶頸**，並且**把 Supermicro 定位在能力而非價格上。**

**若第一問命中，接續的資格確認問題：**「What per-node delivered cost and payback horizon does your model assume for the MI355X units in the raise?」——**這會直接讓天花板浮出水面，而不是用猜的**（第 9 節）。

### 該怎麼開場，以及絕對不要怎麼開場

**要做：**
- **盡可能經由 AMD 的 Instinct／neocloud 現場團隊切入** — 他們自稱「AMD Exclusive AI Cloud」，AMD 已為他們發布 NeoCloud 部落格與試用申請頁，而 **GPU 配額是我們單方無法供應的稀缺投入。**
- **以 Supermicro AMD MI355X JumpStart 專案作為第一個具體步驟**（[learn-more.supermicro.com/mi355x](https://learn-more.supermicro.com/mi355x)）——它是評估先行、自助導向，**完全契合一家公開發布社群 benchmark、且拒絕業務電話的公司。**
- **以工程師對工程師的方式、用純文字書寫。**
- **第一次對話就把融資／租賃帶上桌**，因為「asset finance」是他們自己提的。

**不要做：**
- **絕不以 benchmark 主張開場** — 他們手上的 MI300X 資料比我們好，而且公開策展了二十個第三方 benchmark 來源（[/benchmarks-and-analysis](https://hotaisle.xyz/benchmarks-and-analysis/)）。
- **絕不要求他們汰換運轉中的 MI300X 叢集。**
- **第一筆交易絕不提議替換 Dell PowerSwitch／SONiC 網路。** Dell ProSupport NBD 涵蓋每一台交換器、Z9864F 另有 4 小時關鍵任務與現場備品，我們無法輕易勝過——**第一筆交易就只鎖定運算節點，交換器不要碰。**
- **絕不貶低 Dell 或 Advizex。** 這段關係真實、溫暖且有公開紀錄；攻擊它只會顯得對他們的歷史一無所知。
- **絕不談政治**（第 11 節）。
- **絕不報一個裸箱。** 任何報價都必須包含 **L11／L12 機櫃整合、預備、Grand Rapids 物流與現場備品**，因為 Advizex 交付的是上架完成、可運轉的叢集，一個裸機箱在完整度上必輸，不論單價。

### Rule 8 — 經銷通路警示（撥號之前必讀）

**本帳戶必須透過授權經銷通路推進，而且在這一案上這不是形式問題——這就是這筆生意的具體風險。** 在談任何價格之前：

**(a)** 對 Hot Aisle Inc. **執行夥伴／案件註冊查核**，確認沒有既存的有效註冊。**注意：業務專員已於 2026-08-11 實查 CRM 為乾淨**（Search，Type = All：無 lead、無 account、無 do-not-call）——**但 CRM 乾淨不等於通路乾淨。**

**(b)** **在第一次實質接觸之前，就選定並註冊授權經銷／整合商**，因為這個客戶買的是**整合交付的叢集，不是機箱**，未經註冊的直接接觸，最終一定會與實際負責交付的夥伴相撞。

**(c)** **不得在經銷價之外或之下另報直接價**，也**不得讓 AMD 主導的聯合接觸變成繞過已註冊夥伴的側門。**

**(d)** **對 Advizex 尤須審慎** — 他們是 Dell Titanium Solution Provider，也是既有的整合商 of record，因此若打法是把他們拉到 Supermicro 平台上，**必須循正式通路流程處理，不得在客戶對話中臨場即興。**

**(e)** **註冊前先確認轄區。** **資料中心在密西根（T1 — 一組可直接註冊）**，但**登記法人在懷俄明州 Cheyenne**，兩位決策者研判分別位於**新罕布夏州與華盛頓州**。**僅以密西根設施地址註冊，日後可能因法人設籍地被質疑**，因此**在註冊當下就要把密西根生產據點記載為 T1 主張的依據，並主動把 WY／NH／WA 的分散情形通報通路管理單位**，不要讓它在案件成立之後才變成爭議。

**順序——不得調換：** ① 釐清通路／經銷歸屬並選定整合商（Rule 8）→ ② 註冊，並記載密西根生產據點為 T1 依據、同時通報 WY／NH／WA 分散情形 → ③ 經 AMD 或 hello@hotaisle.ai 接觸，只問上述那一個資格確認問題。

---

## 14. 查證附錄

### 14.1 單一來源或模型推導之主張——引用前須重新查證

| 主張 | 唯一來源／依據 | 風險 |
|---|---|---|
| **設立州＝懷俄明** | ARIN 組織地址 ＋ D&B 索引條目，**兩者指向同一個註冊代理人 PMB** | **推論，未經查證。** 任何州皆未取得登記文件。**不得將設立州陳述為事實。** 以懷俄明良好存續證明補齊 |
| **Jon Stevens＝CEO；Clint Armstrong＝Head of Engineering** | 公司自家 About 頁、AMD 部落格、Advizex 案例研究；Armstrong 另有一筆列雇主為 HOT AISLE 的 FEC 申報佐證 | **自行宣告，非登記查證。** 可能存在此二人以外、目前看不見的幹部、董事或股東 |
| **約 16 節點／約 128 張 GPU** | 由公司自述「128 GPU cluster」÷ 每台 XE9680 8 張 GPU 的**算術**，並以 REC 推得的約 90 kW 平均負載**交叉核對** | **推導，非揭露。** 他們可能自 2024 年 9 月後又加購而未公告——**定價層中兩種不同主機 CPU 組態正暗示此事**，但第二批的規模與日期不明 |
| **約 90 kW 平均總負載** | 由 2025 年 781 張與 2024 年 267 張 REC **自行計算** | **推估值。** 取決於 1 REC = 1 MWh，以及 REC 涵蓋 Hot Aisle 全部用電的假設 |
| **機隊中有兩種不同主機 CPU SKU** | 由每一個定價層一致出現的「64 or 102／26 or 52／8 or 13 CPU Cores」模式**推論** | **推論，依據充分但非公司陳述** |
| **營收 $2.2M–$3.8M 年化** | 僅以公開價格建構的**價格 × 產能 × 使用率模型** | **模型輸出，非研究事實。** 公開領域不存在營收、ARR、毛利或成本資料。**絕不可作為事實登錄 CRM** |
| **成本天花板每節點 $95k–$310k** | 以**假設**的 35–55% 營運成本佔比與 12／18／24 個月回收期建構的**模型** | **假設驅動。** 並非由 Hot Aisle 的成本資料推得，該資料不公開 |
| **Panduit 參與實際建置** | 僅 Advizex 案例研究；**未列於 Hot Aisle 的 Partners 頁，Hot Aisle 亦未列出任何 Panduit 料號** | **旁證。不得陳述為 Hot Aisle 的硬體供應商** |
| **Andrey Cheptsov＝GitHub peterschmidt85** | 公開領域廣為人知的帳號對應，**但 Hot Aisle 未曾陳述** | **身分對應為旁證。** dstack 的夥伴關係本身則為已確認 |
| **Jon Stevens 2020 年的 ActBlue 捐款** | FEC 紀錄，雇主為 W3BCLOUD；職業「DIRECTOR OF IT」與其已知職稱不符 | **研判為真但不確定的歸屬。密西根與大量華盛頓州同名筆數，在任何情況下都不得歸屬於他** |
| **Dihuni 交叉核對價 $281,548.48** | 檢索浮現；該頁直接抓取時回傳 **HTTP 307 轉址迴圈** | **未經頁面實查。** 僅佐證量級 |
| **比價站將 Hot Aisle 列為 MI355X 供應商** | [getdeploying.com](https://getdeploying.com/gpus/amd-mi355x) | **研判反映意向／候補名單而非已部署產能。應視為不可靠**——公司自家頁面明載硬體尚未採購 |
| **員工數 1–10／兩位主事者** | D&B 與 LinkedIn 區間，加上 About 頁、GitHub、ARIN | **第三方估計區間**，有結構性訊號佐證，但非公司陳述 |

### 14.2 未解缺口

1. **設立州未確認。** 任何州皆未取得公司登記文件。懷俄明僅由 ARIN 組織地址與 D&B 索引推得，兩者都指向 Cheyenne 的註冊代理人 PMB。密西根 LARA 在 TLS 層被 Cloudflare 阻擋，德拉瓦 ICIS 回傳頁內處理錯誤，懷俄明州務卿為 CAPTCHA 閘門。**補齊方式：** 訂購懷俄明良好存續證明／實體明細，或委外進行人工公司資料查詢。
2. **無任何登記機關之幹部、董事、經理人、股東、發起人、註冊代理人姓名或年報簽署人。** 本檔中每一個幹部姓名都是公司自行宣告或由 FEC 佐證，**從未經登記機關查證。** 很可能存在兩位具名創辦人以外的幹部、董事或股東，而目前無從查看。
3. **無申報歷史。** 設立文件、修正、更名、前用名稱與外州登記——**特別是 Hot Aisle 是否已在密西根辦理外州登記（其主機代管據點可能有此要求）**——全部無法取得。
4. **UCC-1 融資聲明完全未經查證。** 取得筆數為零，可觸及入口為零。本報告中不存在任何 filing number、日期、lapse／延續狀態、擔保權人、債務人地址、擔保品描述或修正／讓與／終止歷史。**這是最大的單一證據缺口，並直接影響硬體過去與未來的融資方式。補齊方式：** 就 `HOT AISLE INC` 在**懷俄明**（研判設立州）與**密西根**（擔保物所在地）委外進行 UCC-11 債務人查詢。
5. **歷史 WHOIS 無法取得。** whoisrequest.com 回 HTTP 403；whoxy.com 需付費登入；securitytrails 需 API 金鑰。僅取得現行 WHOIS（建立於 2023-10-18、註冊商 Spaceship Inc.、Cloudflare 名稱伺服器、登記人遮蔽於冰島「Withheld for Privacy ehf」之後）。**任何 2023–2024 年隱私遮蔽前的登記人姓名、組織或信箱皆未還原**——那本可能揭露原始設立實體或早期地址。
6. **無商標，因此無聲明簽署人與代理人。** USPTO 商標檢索對「hot aisle」與「hotaisle」在 Live、Registered、Pending、Dead、Cancelled、Abandoned 全狀態與全類別均回傳「No results found」。**這是真正的負面結果，不是查詢失敗。**（注意通用詞問題：「hot aisle」本身就是業界術語，這很可能就是沒有申請的原因。）
7. **目前機隊確切規模未揭露。** 16 節點／128 GPU 是推導值。他們可能自 2024 年 9 月後又加購而未公告；兩種不同主機 CPU 組態正暗示此事，但第二批的規模與日期不明。
8. **完全沒有任何財務揭露。** 無營收、ARR、毛利、EBITDA、電力成本、主機代管費率、傳輸成本或硬體取得成本。**營收區間與整套租金推導成本天花板，都是以公開牌價加上假設的營運成本佔比建構的模型——不是研究事實，絕不可以事實呈現。**
9. **兩家供應商的 MI355X 每節點市場價皆未知。** 已取得 **MI300X 世代** AS-8125GS-TNMR2 的真實、現行、有現貨價格（$275,863.87），但**查無 Supermicro 或 Dell 任何 8× MI355X 系統的公開市場價**，且**完全查無 Dell XE9680 MI300X 的價格**（僅供報價）。**因此 BOM 比較錨定在上一個世代。真正的決策是 MI355X。**
10. **Switch Pyramid 散熱框架未經查證——這是商業上最重要的缺口。** 其租用據點能否支援每張加速卡 1,400 W 的直接液冷、密度多少、成本多少、時程多久，**全部未知。主要銷售楔子完全建立在這個答案上，正因如此它被設計成資格確認提問而非斷言。**
11. **Hot Aisle 在 Switch 的合約電力、機櫃數與樓地板面積未揭露。** 公開的只有 Switch 的全園區數字（已建 660,000 平方英尺、規劃可達 180 萬平方英尺與 110 MW）。其自身配額僅由 REC 資料推得。
12. **如預期，Kent County 沒有任何以 Hot Aisle 為名的產權或估價紀錄。** 他們是主機代管租戶，地號屬於 Switch。**Switch 自身的地號紀錄刻意未予調閱**（Kent County Property Search／Caledonia Township Assessing，8196 Broadmoor Ave SE，(616) 891-0070），因為它描述的是房東，不是標的——**這是範圍決定，不是疏漏。**
13. **查無法院案卷——研判為真負面，但非窮盡。** 僅涵蓋聯邦層級；未執行密西根、懷俄明、新罕布夏或華盛頓的州法院查詢，且 CourtListener 的 RECAP 覆蓋率本質上並不完整。
14. **全網查無任何徵才啟事**，因此無招募主管姓名、無團隊擴編訊號、無組織擴張證據。這與「雙人公司＋夥伴人力支援」一致，但**「查無職缺」是弱證據，不是證明。**
15. **貢獻者身分未解。** GitHub 帳號 **vmiss33**（5 次提交）、**dhogaivannan**（紐約州紐約市）與 **gtnotacoder**（gt@netg.co）出現於 Hot Aisle 倉庫，但無法確認其為員工、外包或外部貢獻者。**未予聯絡，不計入人員編制。**
16. **無任何營收端具名客戶。** 700+ 客戶是公司總數；只有 dstack、Red Hat／Neural Magic 與 Dr. Moritz Lehmann 有在 Hot Aisle 硬體上執行的證據。**無任何具名企業標誌、無具名客戶案例研究、全網無合約金額證據。**
17. **投資人資訊稀薄。** Mesh.xyz／MeshWeb3（Joseph Lubin）被列為支持者，但**查無輪次規模、日期、持股比例、董事會組成或股權結構**，且**現行 $50–100M 募資未找到任何公告。**
18. **PeeringDB 完全不存在紀錄**，因此無流量揭露、無 IX 進駐、無設施清單、無 peering 聯絡人姓名。其唯一的網路聯絡點是單一共用的 ARIN 職務信箱。
19. **OpenCorporates、Bizapedia、CorporationWiki 與 OpenGovUS 全數受阻**（分別為 CAPTCHA、HTTP 403 與 HTTP 404），移除了登記資料的所有聚合站備援。
20. **$50–100M 募資除公司自家 Investors 頁外未經任何查證。** 無申報、無新聞稿、無任何第三方對目標金額、階段或承諾的確認。**「>$50M MI355X 客戶需求」同樣是公司自述且未經稽核，且屬前瞻 pipeline 而非營收。**

### 14.3 已實際查詢之來源——含「查無」者

**有產出者：**

- **[hotaisle.xyz](https://hotaisle.xyz/)** — 完整一手網站爬取：`/pricing`、`/datacenter`、`/networking`、`/investors`、`/partners`、`/contact`、`/about`、`/mi300x`、`/mi355x`、`/cluster`、`/benchmarks-and-analysis`、`/blog` 與 6 篇個別文章。**產出：遙遙領先的最豐富單一來源**——Switch Pyramid Grand Rapids MI 設施、Dell XE9680 ＋ 8× MI300X、完整的 Broadcom 網卡與 Dell PowerSwitch 料號、SONiC、AS21566、三個現行價格、$50–100M 募資、700+ 客戶、100% 使用率、W3BCloud 淵源，以及逐字的「still raising the capital」MI355X 陳述。*（註：頁尾連結的 `/supercomputer` 回傳 404。）*
- **[ARIN RDAP](https://rdap.arin.net/registry/entity/HA-716)** — 以 `fn=Hot Aisle*` 實體檢索，再取 Org HA-716 完整紀錄。**產出：公司身分的突破口。** *（第一次以代號「HOTAI」查詢回傳無關組織——維吉尼亞州 Arlington 的「HotAir」——已載明以免重蹈。）*
- **[Wayback Machine CDX API 與快照擷取](https://web.archive.org)** — 列舉 20 份定價快照、抓取並解析 12 份；取得 `/mi300x`、`/mi355x`、`/mi325x`、`/cluster` 的首份快照日期；還原完整 2024 年 cluster 頁。**產出：整條採購時鐘。** 需處理 gzip 與重試退避；**注意 WebFetch 對 web.archive.org 為硬性封鎖，只有 Bash／curl 可行。**
- **[FEC 個人捐款資料庫](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle)** — 六種不同查詢。**產出：全公司範圍恰好一筆紀錄**，加上一筆經 W3BCLOUD 的 Stevens 可能紀錄，以及明確的排除項。
- **[GitHub REST API](https://github.com/hotaisle)** — 組織、四個倉庫的貢獻者與提交作者後設資料，加上六次個人檔案查詢。**產出：真實具名人員與其活動量。**
- **[Advizex 案例研究](https://www.advizex.com/case-studies/advizex-and-hot-aisle)** — **產出：通路全貌與前瞻採購承諾。**
- **[AMD](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html)** — NeoCloud 部落格與 [試用申請頁](https://www.amd.com/en/products/accelerators/instinct/eval-request/hot-aisle.html)。**產出：** Jon Stevens 語錄、$1.99／GPU／小時 的定位、關係深度的確認，以及兩位創辦人曾「successfully deployed large-scale compute in multiple data centers across the US and Southeast Asia」的記述。
- **[Supermicro](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html)**（eStore、[新聞稿](https://www.supermicro.com/en/pressreleases/supermicro-expands-its-portfolio-performance-and-efficiency-driven-air-cooled-ai)、[MI355X JumpStart](https://learn-more.supermicro.com/mi355x)）— **產出：BOM 錨點與技術楔子。**
- **[gen.xyz 專訪](https://gen.xyz/blog/hotaisle-xyz)** — **產出：兩位創辦人背景細節**、Mesh.xyz／Joseph Lubin 支持、781 張 REC、SOC 2 Type 2 與 HIPAA。
- **網域 RDAP 與現行 WHOIS**（[rdap.centralnic.com](https://rdap.centralnic.com/xyz/domain/hotaisle.xyz)）— **產出：** 兩個網域皆建立於 2023-10-18 且相隔三秒、註冊商 Spaceship Inc.（IANA 3862）、Cloudflare 名稱伺服器、clientTransferProhibited、.xyz 到期 2026-10-18、.ai 到期 2027-10-18、登記人遮蔽。
- **[Switch, Inc.](https://www.switch.com/grand-rapids/)** 與次級設施來源 — **產出：設施脈絡：** Pyramid 園區位於 6100 East Paris Avenue SE, Caledonia MI，即前 Steelcase Pyramid，已建 660,000 平方英尺、規劃可達 180 萬平方英尺與 110 MW、Tier 5 Platinum、T-SCIF 冷卻。
- **第三方 benchmark 與比價來源**（[dstack.ai](https://dstack.ai/blog/h100-mi300x-inference-benchmark/)、[SemiAnalysis](https://newsletter.semianalysis.com/p/mi300x-vs-h100-vs-h200-benchmark-part-1-training)、[getdeploying.com](https://getdeploying.com/gpus/amd-mi355x)、spheron.network）— **產出：** 獨立確認其贊助 8× MI300X benchmark 用機、不可靠的 MI355X 供應商掛名，以及市場價格脈絡（專業 neocloud 約 $1.99／GPU-小時，對上超大規模業者的 $6.00–$7.86）。

**已觸及但查無者：**

- **[PeeringDB API](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle)** — **查無。** 空的 data 陣列。無網路物件、無 peering 政策、無 IX 進駐、無設施清單、無 peering 聯絡人。**有意義的負面發現：他們外購 transit，不做 peering。**
- **[USPTO 商標檢索](https://tmsearch.uspto.gov)** — 兩次文字商標查詢，六種狀態篩選全開、全類別。**查無：**「No results found」，兩次皆 0 Live、0 Dead。另探測：assignment-api.uspto.gov（空）、tsdrapi.uspto.gov（HTTP 401）、uspto.report（HTTP 403）、trademarks.justia.com（HTTP 403）。
- **[CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search)** — 以「Hot Aisle Inc」精確詞查詢 **查無**（count 0）。較寬鬆的「Hot Aisle」回傳 32 筆無關的資料中心專利訴訟。
- **歷史 WHOIS 服務** — whoisrequest.com 回 HTTP 403；whoxy.com 登入牆。**查無可用資料。**
- **[Crunchbase](https://www.crunchbase.com/organization/hot-aisle)** — **HTTP 403，查無。** 未取得任何募資輪資料。
- **[Hugging Face](https://huggingface.co/hotaisle)** — 組織存在、創辦人具名、自述興趣為「AMD MI300x on Dell hardware」，**但無公開模型或資料集。**
- **[D&B 商業名錄](https://www.dnb.com/business-directory/company-profiles.hot_aisle_inc.6343b38590429aa36d4f33b58a5ecdf9.html)** — **僅取得部分，且經檢索摘要**（Cheyenne WY、1–10 人區間）。頁面本體抓取時只回傳 meta description 文字，因此**營收、SIC／NAICS 與主要負責人欄位皆未取得。**
- **Dell／經銷價格查核**（Uvation Marketplace XE9680 8× MI300X 頁與一般檢索）— **查無價格：** 僅供報價、「Contact our sales team」、以 PO 方式處理、估交期約 4 週。
- **職缺與招募檢索**（Indeed、ZipRecruiter、LinkedIn 檢索）— **查無。** 無職缺、無招募主管、無招募顧問姓名。

**受阻及其原因：**

- **[密西根 LARA](https://cofs.lara.state.mi.us/CorpWeb/CorpSearch/CorpSearch.aspx)** — Cloudflare 之後的 TLS 交握失敗；所有重試皆 HTTP 000。逐字紀錄見 8.3。
- **[德拉瓦 ICIS](https://icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx)** — 「An error occurred while processing the request」；依該站明載禁止自動化查詢，**僅執行一次。** 德拉瓦另外**根本不提供免費的線上 UCC 債務人索引。**
- **[懷俄明州務卿商業](https://wyobiz.wyo.gov/Business/FilingSearch.aspx)與 [UCC](https://wyobiz.wyo.gov/UCC/UCCSearch.aspx) 入口** — 圖形 CAPTCHA，**未破解。** support ID 11385417910158757353 與 11385417910158787977。另探測五個懷俄明替代主機，全數失敗。
- **公司登記聚合站** — [OpenCorporates](https://opencorporates.com/companies?q=%22Hot+Aisle%22)（HAProxy CAPTCHA）、[Bizapedia](https://www.bizapedia.com/search.aspx?q=hot+aisle)（拖曳式驗證）、CorporationWiki（HTTP 403）、OpenGovUS（HTTP 404）。

**刻意排除於範圍之外，非受阻者：** **Kent County 密西根產權／估價研究。** 已辨識出正確的查詢工具（Kent County Property Search；Caledonia Township Assessing，8196 Broadmoor Ave SE，(616) 891-0070），但**未調閱任何地號**，因為 Hot Aisle 是主機代管租戶，任何地號紀錄描述的都會是 **Switch 這個房東，不是標的。**

### 14.4 重跑時的工具註記

ZoomInfo MCP 連接器（以及 carta、figma、atlassian、spglobal、adobe 連接器）**需要 OAuth 授權，在本次非互動工作階段中無法使用。** 經 claude.ai 連接器設定授權 ZoomInfo，在重跑時可望改善員工數與具名人員的輪廓——**不過對一家名副其實的兩人公司而言，其邊際價值遠低於面對較大型標的時。真正關鍵的兩個缺口——懷俄明登記紀錄與 UCC 查詢——任何連接器都解不了，必須委外進行人工查詢。**
