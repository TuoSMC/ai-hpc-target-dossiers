# Hot Aisle Inc. — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國）· 專員 US8664 Tuo Cheng · **日期：** 2026-08-11
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有持股，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之 GPU 型錄與定價、UCC 歸檔、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 密西根州 — Chicago Area = **T1**｜T2｜T11。一組可直接註冊。
**CRM 狀態：** 2026-08-11 於 salesleads Search（Type = All）實查為乾淨 — 無 lead、無 account、無 do-not-call。一組可註冊。

---

## 1. 結論摘要

Hot Aisle Inc. 是一家**兩人編制、AMD 獨家的裸機 GPU 雲端業者**，以主機代管租戶身分，在密西根州 Grand Rapids／Caledonia 的 Switch「The Pyramid」園區內營運約 **16 台 Dell PowerEdge XE9680／約 128 顆 AMD Instinct MI300X**，使用 **AS21566**；公司沒有任何辦公室，登記地址是懷俄明州 Cheyenne 的一個郵件代收信箱（[hotaisle.xyz/datacenter](https://hotaisle.xyz/datacenter)；[ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)，2026-08-11 讀取）。商業上，這是一個**針對下一世代的全新切入（greenfield displacement）——不是既有客戶防守，更絕對不是要對方換掉現有機隊的提案。** Dell 擁有既有機隊，而且擁有得理所當然：Hot Aisle 曾公開表示，Dell 為了一顆螺絲鬆脫的 GPU 派了兩名工程師到場，並稱該支援水準「breathtaking」（[Hot Aisle 部落格，2024-09-13](https://hotaisle.xyz/blog/cruising-to-the-finish-line/)）。這支機隊搶不到，也不該去搶。

真正開放的是**尚未採購、也尚未取得資金的 MI355X 建置案**。所有採購前置條件都已由公司自己公開陳述：**產能 100% 滿載且有客戶排隊等待**、**2026-07-14 已將 MI300X 價格自每 GPU 每小時 $1.99 調升至 $2.99**、宣稱有 **「超過 5,000 萬美元的 MI355X 產能需求」**，並正在**募集 $50–100M，資金來源明列「equity、strategic investment 與 asset finance」**，用途是「purchase AMD MI355X systems and fund the networking, rack integration, and site deployment」（[pricing](https://hotaisle.xyz/pricing)；[Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)；[investors](https://hotaisle.xyz/investors)）。他們自己的話：**「The constraint is access to hardware, not demand for the platform.」**

有兩件事讓這案子是可打的，而不是一廂情願。第一，**資金不足時他們會跳過世代** —— MI325X 在 2024 年 11 月被預告過，卻從未部署；此為負面查證結果，依據是 `hotaisle.xyz/mi325x` 在整個 Wayback 典藏中 CDX 回傳空集合。因此 MI355X 的平台決策是**真正未定案**，而不是既有機隊的例行汰換。第二，**他們自己的 MI355X 頁面載明每顆加速器 1,400 W，且採用直接液冷（direct liquid cooling）的機櫃設計**，但他們是**租戶**，並不掌握散熱系統（[hotaisle.xyz/mi355x](https://hotaisle.xyz/mi355x)）。Supermicro 的**氣冷式 10U 8× MI355X** 平台，等於把一項「房東相依性」從一家資金吃緊、且公開宣稱唯一瓶頸是硬體取得的公司的關鍵路徑上移除。**這是能力論述，不是折扣論述**，也是本檔案中最有力的一點。

有三件事會讓案子破局。**（1）Advizex** —— 這家 Dell Titanium 整合商跑了四個月的每週規劃會議、在自家辦公室預置硬體，且已被白紙黑字寫明是下一座叢集的合作方（[Advizex 案例](https://www.advizex.com/case-studies/advizex-and-hot-aisle)）；**要換掉的是機殼，絕不是整合商。** **（2）牌價** —— MI300X 世代的 Supermicro 對應機種標價 $275,863.87，對照其自家公開租金，只有在 24 個月回收期、且營運成本假設落在最省的一端時才勉強過關，12 個月與 18 個月都差得很遠（§10）。**（3）通路與轄區** —— 資料中心在密西根（T1），但登記法人在懷俄明，兩位決策者看來分別位於新罕布夏州與華盛頓州；因此註冊當下必須以密西根的生產據點作為 T1 主張的依據並留存紀錄，且在談任何價格之前，須依 Rule 8 先釐清經銷商歸屬（§14）。

---

## 2. 公司速覽

| 欄位 | 內容 | 證據／日期 |
|---|---|---|
| **法人名稱** | **Hot Aisle Inc.** — 網站頁尾寫作「Hot Aisle, Inc.」，ARIN POC 的 org 欄位寫作「Hot Aisle Inc」。私有持股，無 SEC 申報 | 網站頁尾「© 2026 Hot Aisle, Inc.」；[ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)。**GAP：任何一州皆未取得一手公司登記文件** — 見 §4.4 與 §15 |
| **設立州別** | **未經查證 — 研判為懷俄明州，屬推論而非確認** | 登記地址為 1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne, WY 82001 —— 這是商業註冊代理人的 PMB 私人信箱 —— 見 [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)（2024-01-15 登記，2026-07-14 最後異動）與 [D&B 商業名錄](https://www.dnb.com/business-directory/company-profiles.hot_aisle_inc.6343b38590429aa36d4f33b58a5ecdf9.html)（同樣以 Cheyenne 收錄）。**德拉瓦州與密西根州皆已嘗試、皆失敗**（§9.2）。懷俄明州 SOS 有圖形 CAPTCHA。**不得將設立州別陳述為事實** |
| **創立時間** | **2023 年 10 月** | 公司自家 [About 頁](https://hotaisle.xyz/about/) 及多份第三方檔案。並由網域建立時間獨立佐證：hotaisle.xyz 建立於 **2023-10-18T06:14:34Z**、hotaisle.ai 建立於 **2023-10-18T06:14:37Z** —— **相隔三秒**，同一註冊商 Spaceship, Inc.（[RDAP](https://rdap.centralnic.com/xyz/domain/hotaisle.xyz)） |
| **總部（其實沒有）** | **公司從未在任何地方公布街道總部 —— 這是刻意的。** 存在三個彼此不同的地址，絕不可混為一談：**（1）法人／登記地址** 1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne WY 82001 —— 郵件代收信箱，不是辦公室；**（2）生產據點** Switch「The Pyramid」園區，密西根州 Grand Rapids／Caledonia —— 唯一真實的實體足跡，且是**租用**；**（3）人** —— 兩位負責人看來皆為遠距，且**不在密西根** | [hotaisle.xyz/datacenter](https://hotaisle.xyz/datacenter) 逐字寫「Switch Pyramid • Grand Rapids, MI」；Switch 的園區地址為 6100 East Paris Avenue SE, Caledonia, MI（[switch.com/grand-rapids](https://www.switch.com/grand-rapids/)）；FEC 將 Clint Armstrong 定位於新罕布夏州 Grantham，並將一位任職 W3BCloud 的 Jon Stevens 定位於華盛頓州 Entiat（[FEC](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=Hot+Aisle)）。聯絡方式僅有電子郵件：hello@hotaisle.ai（[contact](https://hotaisle.xyz/contact)） |
| **所有權／投資方** | 外觀為創辦人主導；**Mesh.xyz／MeshWeb3（Joseph Lubin）具名為投資方。** **GAP：無輪次金額、日期、持股比例、董事會組成或股權結構表** | [gen.xyz 專訪](https://gen.xyz/blog/hotaisle-xyz)。Crunchbase 回 HTTP 403 |
| **員工數** | **1–10 區間；實質為 2 位全職負責人，加上外包與合作夥伴的人力支援（第三方估計＋佐證訊號，非公司陳述）** | D&B 與 LinkedIn 均顯示 1-10 區間；[About 頁](https://hotaisle.xyz/about/) 僅列兩人；[GitHub 組織](https://github.com/hotaisle) 顯示「no public members」，且只有兩個 hotaisle 網域的 committer；ARIN 將六種 POC 角色全部收斂到同一個信箱；Advizex 明載提供「personnel and staff augmentation」；**全網查無任何徵才啟事**。他們自己的說法：「With experienced operators directing it, AI gives a small team unusual leverage」（[investors](https://hotaisle.xyz/investors)） |
| **營收** | **未揭露 —— 僅為推導估計。區間 $2.2M–$3.8M 年化，2026 年價格轉換期間最可能落在 $2.5M–$3.2M** | 僅以公開價格所做的「價格 × 產能 × 使用率」模型：128 GPU × 8,760 小時，$1.99 得 $2.23M；$2.99 得 $3.35M；$3.39 得 $3.80M。**該公司從未公布營收、ARR、毛利或成本資料。** 另須注意，「超過 $50M 的 MI355X 需求」是**前瞻性需求管線，不是營收**，絕不可當作營收引用。**CRM $100M 門檻判定：公開資料完全不支持 $100M+ 的定性** |
| **ASN** | **AS21566，ARIN 代號「HOTAISLE」**，狀態 Active，**2024-02-14** 登記於 Org HA-716。IPv4 **23.183.40.0/24**（NET-23-183-40-0-1，「HA-4-10」）；IPv6 **2602:f955::/36**（NET6-2602-F955-1，「HA-SOPH」） | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)。單一 /24 與單站點的中小型足跡相符；/36 的 IPv6 則偏大且具前瞻性 |
| **PeeringDB** | **查無任何紀錄。未進駐任何 IX、無 peering 政策、無設施列表、無 peering 聯絡人姓名** | [PeeringDB API](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle) 回傳空的 data 陣列。連線是**採購**而來的 transit —— Switch Connect 與 Megaport（[networking](https://hotaisle.xyz/networking)） |
| **認證** | **SOC 2 Type 1（2025-07-01）、SOC 2 Type 2（2025-09-18）、HIPAA** | [gen.xyz 專訪](https://gen.xyz/blog/hotaisle-xyz) |
| **訴訟** | **查無。** CourtListener 以「Hot Aisle Inc」為當事人做精確片語查詢，回傳 0 筆 | [CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search)。僅涵蓋聯邦層級；較寬鬆查詢回傳 32 筆與本案無關的資料中心專利訴訟，僅因通用術語命中 |
| **商標** | **無 —— 這是真實的負面結果，不是查詢失敗。** USPTO 對「hot aisle」與「hotaisle」兩種拼法、於 Live／Registered／Pending／Dead／Cancelled／Abandoned 全狀態、全類別均回傳「No results found」 | [tmsearch.uspto.gov](https://tmsearch.uspto.gov)。因此不存在 TSDR 紀錄、登錄律師或聲明簽署人可供擷取。「hot aisle」是業界通用術語，這很可能就是未申請的原因 |
| **CRM 狀態** | **從未登錄** —— 無 lead、無 account、無 do-not-call | salesleads Search（Type = All），2026-08-11 實查 |
| **轄區／團隊** | Grand Rapids, MI → Chicago Area = **T1｜T2｜T11** → 一組可直接註冊。**注意：法人在 WY，負責人看來在 NH 與 WA —— 註冊時須以密西根生產據點作為 T1 主張依據並留存紀錄** | Territory Map-Jan.2026 (Rev.1)，Sales Territory Assign 分頁 |

---

## 3. 原始名單更正表

僅列與 Hot Aisle Inc. 有關者。判定尺度：**已確認**＝第一手具名揭露，或多個獨立來源互相佐證｜**部分確認**＝核心為真，但表述方式必須修正｜**已否定**＝證據與原始名單相反｜**未經查證**＝無法由公開來源建立，**不得對客戶陳述**。

| # | 原始名單說法 | 判定 | 證據與正確表述 | 來源 |
|---|---|---|---|---|
| 1 | **Hot Aisle 是密西根州公司，其公司幹部可自密西根 LARA 調閱** | **就公司地址而言已否定 · 就設立州別而言未經查證** | 密西根是**算力所在地**，不是公司登記地址所在地。`/datacenter` 頁把基礎設施放在密西根州 Grand Rapids 的 Switch「Pyramid」園區（Tier 5 Platinum）。而每一筆可取得的公司地址紀錄都指向**懷俄明州 Cheyenne**：ARIN Org HA-716 為「1603 CAPITOL AVE, STE 415, PMB 41293, Cheyenne, WY 82001」，LinkedIn 公司頁為「1603 Capitol Ave, Suite 415, Cheyenne, WY 82001」。**設立州別在任何地方都未揭露** —— 服務條款沒有、隱私政策沒有、sitemap 的 45 個 URL（非部落格者全數檢查）也沒有。密西根 LARA、德拉瓦 ICIS 與懷俄明 SOS 查詢皆位於機器人防護之後且未被破解，因此**任何一州都無法取得幹部、董事、經理人、股東、註冊代理人或年報簽署人。** 設立州別確實未知，「密西根」沒有任何查得資料支持 | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716) · [LinkedIn 公司頁](https://www.linkedin.com/company/hotaisle) · [hotaisle.xyz/datacenter](https://hotaisle.xyz/datacenter) |
| 2 | **1603 Capitol Ave, Suite 415, Cheyenne WY 是 Hot Aisle 的總部或辦公室** | **已否定** | ARIN 紀錄本身即載明 **「PMB 41293」** —— Private Mail Box 私人信箱代號，亦即郵件轉寄／註冊代理人地址，不是營業處所。獨立佐證其為共用商業收件地址：**WinRed 自己的 FEC Form 1 所填委員會地址為「1603 CAPITOL AVENUE, CHEYENNE, WY 82001」**，與 Hot Aisle 登記紀錄同一條街道地址。**必須明講：該地址相同不代表 Hot Aisle 與 WinRed 之間有任何關係。** 這正是粗心讀者最容易過度解讀的巧合，特此標示以免誤讀。LinkedIn 列該公司為 2–10 人；公司沒有對外宣稱的辦公室，人員分散各地 —— Armstrong 的 FEC 申報把他放在新罕布夏州 Grantham | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716) · [FEC 委員會 C00694323](https://api.open.fec.gov/v1/committee/C00694323/) |
| 3 | **Hot Aisle 目前供應 AMD Instinct MI355X 產能**（若干第三方 GPU 比價網站如此列示） | **已否定 —— 這是本檔在商業上最重要的一項更正** | 其自家 MI355X 頁面寫道：**「We are still raising the capital required to buy and deploy the hardware.」** 頁面說他們正在「in active conversations」，且「the right introduction could make a real difference」，並把買家導向「available now」的 MI300X。investors 頁確認所募資金的用途正是「to purchase AMD MI355X systems」。**任何在今天把他們列為 MI355X 供應商的比價網站都是錯的** | [hotaisle.xyz/mi355x](https://hotaisle.xyz/mi355x) · [hotaisle.xyz/investors](https://hotaisle.xyz/investors) · [getdeploying.com](https://getdeploying.com/gpus/amd-mi355x)（錯誤列示者） |
| 4 | **Hot Aisle 是已完成募資、由 Consensys Mesh／Joseph Lubin 投資的新創** | **部分確認** | 投資關係為真，且雙方都有陳述 —— `hotaisle.xyz/about` 具名 **Joseph Lubin** 為早期投資人，**mesh.xyz 亦將 Hot Aisle 列於其投資組合**（AI／Enterprise／Infrastructure 分類）。但**輪次金額、日期、階段、估值、領投人與董事席次，在任何可觸及之處皆未揭露**；Mesh 投資組合頁只有分類標籤、沒有任何投資細節，Crunchbase 回 HTTP 403。同時其 investors 頁顯示他們**正在募集**「$50–100 million across equity, strategic investment, and asset finance」——這不是剛完成一輪募資的公司會有的姿態。**「資金充裕」一說並無依據** | [hotaisle.xyz/investors](https://hotaisle.xyz/investors) · [mesh.xyz/portfolio/hot-aisle](https://www.mesh.xyz/portfolio/hot-aisle) · [hotaisle.xyz/about](https://hotaisle.xyz/about/) |
| 5 | **Hot Aisle 的 MI300X 是每 GPU 每小時 $1.99**（廣被引用的數字，包含其 CEO 自己 2026 年 4 月的 Hacker News 貼文） | **部分確認／已過時** | 其貼文〈Why We Raised Our MI300X Price〉載明：**新配置的 MI300X 虛擬機由 $1.99 調升至 $2.99／GPU-hr**，既有客戶配額**沿用 $1.99**，**裸機維持 $3.39 不變**。同一篇文章說他們產能全滿、服務**超過 700 位客戶**，並批評 DigitalOcean 把 MI300X（$1.99）與 NVIDIA H100（$3.39）訂在同一價位。**任何把 $1.99 當成現行新客戶價的引用，都是引用已被取代的數字** | [Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price) |
| 6 | **有自營 AS 的 neocloud，必然可透過 ARIN 與 PeeringDB 找到具名的網路工程師** | **已否定** | **ARIN 完全沒有產出任何人名。** 四個號碼資源物件 —— Org HA-716、AS21566、23.183.40.0/24 與 2602:F955::/36 —— 全部指向同一個 POC **NETOP393-ARIN**，其 vCard 為 `kind="group"`、`fn="NetOps"`，同時承擔六種角色（admin、tech、NOC、abuse、DNS、routing）。**PeeringDB 則完全沒有紀錄：** API 對 `asn=21566` 回傳 `{"data": [], "meta": {"error": "Entity not found"}}`，以組織名稱查詢亦為空集合。bgp.he.net 顯示**僅一個觀測到的對接對象 AS49915 Megaport UK Limited**，平均 AS path 長度 4.872，IPv6 /36 已配發但**未宣告**。另注意公布的 NOC 電話 **+1-646-389-2009 是紐約區碼**，既不符懷俄明郵寄地址、也不符密西根機房 | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716) · [PeeringDB API](https://www.peeringdb.com/api/net?asn=21566) · [bgp.he.net/AS21566](https://bgp.he.net/AS21566) |
| 7 | **創辦人極為公開 —— 部落格、X、podcast、社群 benchmark —— 因此深挖必能查出可觀的具名員工名冊** | **已否定** | 公開度確實高，**但那是兩個人的公開度。** 在完整處理公司登記機關、ARIN、PeeringDB、BGP、四個 TLD 的 WHOIS、GitHub（組織、9 個程式庫、全部 commit 作者）、Hugging Face、Hacker News（226 筆命中）、完整 45 個 URL 的 sitemap、夥伴案例、AMD 部落格、研討會／theCUBE 報導與 LinkedIn 之後，**Hot Aisle 的具名員工總數恰好為二：Jon Stevens 與 Clint Armstrong。** LinkedIn 公司頁以「2-10 employees」獨立佐證。其餘浮現的姓名一律是夥伴端（Dell 的 Saurabh Kapoor；theCUBE 主持人 Savannah Peterson 與 Dave Vellante；benchmark 作者 Dr. Moritz Lehmann），或是無法辨識身分的 GitHub 帳號。**請以兩人公司規劃此帳戶，不要當成有部門建制的新創** | [LinkedIn 公司頁](https://www.linkedin.com/company/hotaisle) · [GitHub 組織 API](https://api.github.com/orgs/hotaisle) · [hotaisle.xyz/about](https://hotaisle.xyz/about/) |
| 8 | **Hot Aisle 持有註冊之「HOT AISLE」商標** | **本輪未能查證** —— 請注意與 §2 的張力 | 本輪**既無法確認、也無法否認**：tmsearch.uspto.gov 的查詢後端對所有嘗試過的既載 API 路徑回傳 405／404，assignment API 無法連線，可替代之第三方鏡站（trademarks.justia.com、uspto.report）皆回 HTTP 403。一般網路搜尋亦未浮現任何「HOT AISLE」註冊紀錄。**因此無法取得任何商標序號、聲明簽署人或代理人。** 本帳戶先前一輪曾成功觸及 tmsearch，並記錄到全狀態、全類別的「No results found」乾淨負面結果（§2）——**該負面結果維持為工作立場，但本輪未再驗證。** 另注意「hot aisle」是資料中心通用術語，純文字商標本就難以註冊 —— 但那是推理，不是證據，故不作為查證發現呈現 | [tmsearch.uspto.gov](https://tmsearch.uspto.gov/) |
| 9 | **這種樣態的公司會有聯邦遊說支出或企業 PAC** | **已否定 —— 兩者皆為對權威登記庫查得的確認負面結果** | **參議院 LDA：** 以 `client_name` 與 `registrant_name` 對「hot aisle」、「hot%20aisle」、「hotaisle」、「Hot Aisle Inc」四種寫法共八次查詢，全部回傳 `{"count":0,"results":[]}` —— 無 LD-1、無 LD-2、無任何申報支出。**FEC 委員會登記庫：** `q="hot aisle"` 回傳 count 0 —— 從未登記任何 connected PAC、SSF、super PAC 或 hybrid PAC。**該公司在案的政治足跡總量，就是共同創辦人的一筆 $50 個人捐款** | [參議院 LDA API](https://lda.senate.gov/api/v1/filings/?client_name=hot+aisle) · [FEC 委員會查詢](https://api.open.fec.gov/v1/committees/?q=hot+aisle) |
| 10 | **取得 SOC 2 Type 2 認證，代表必有具名的資安／法遵主管** | **未經查證** | 部落格公告了 SOC 2 Type 1 與 Type 2 的取得，而 Type 1 該篇明謝 **Sprinto 與 ATOM** 的協助 —— 亦即法遵是外包給工具與稽核方，而非內部編制。**站上任何地方都沒有具名的 CISO、資安主管、法遵主管或 DPO；** 隱私政策把所有資料保護聯絡導向通用信箱 hello@hotaisle.ai。值得一提的是他們也發過一篇〈SOC2 Is Broken — And The Entire Industry Knows It〉，可用來理解他們如何看待法遵宣稱 | [SOC 2 Type 1 貼文](https://hotaisle.xyz/blog/hot-aisle-secures-initial-compliance-milestone-soc-2-type-1-completed) · [隱私政策](https://hotaisle.xyz/policies/privacy-policy) |

---

## 4. 領導層與所有權

本節證據等級：**primary-record（一手紀錄）**＝網路號碼登錄機構、聯邦競選財務申報、法院案卷、主管機關檔案、公司自有程式碼庫之 commit 紀錄，或公司自家已發布頁面｜**corroborated（多方佐證）**＝兩個以上獨立次級來源互相印證｜**single-source（單一來源）**＝僅一個次級來源｜**circumstantial（旁證）**＝行為已確認但關係未確認｜**GAP**＝已具名搜尋但查無。

進入表格前有三項前提。第一，**本檔案中每一個幹部姓名，都是公司自行宣稱、由公司自有程式碼庫 commit 佐證，或由 FEC 申報佐證 —— 沒有任何一個經過公司登記機關驗證。** 任何一州皆未取得公司登記文件，因為在研判與備選的設立州別中，每一個入口網站都拒絕自動化存取（§4.4、§9.2）。「自行宣稱之幹部」與「登記在案之幹部」的區別，在本檔中以獨立且標示清楚的列保留，以免下游誤讀。第二，**登錄機構與 ARIN／PeeringDB 聯絡人以獨立列呈現並明確標示** —— 只要登錄資料具名，那就是真實的具名自然人，而對這種規模的公司而言，ARIN POC 往往是唯一存在的已驗證聯絡面；此處的結果則是反向而且格外有訊息量：**ARIN 完全沒有具名任何個人**，六種角色全部收斂到單一群組信箱，這本身就是兩人編制的證據。第三，**本公司具名員工總數恰好為二** —— 這是橫跨登記機關、程式碼、社群論壇與媒體查證後的結果，不是查得不夠（§3 第 7 列）。

### 4.1 具名人員

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC | 來源 |
|---|---|---|---|---|---|---|
| **Jon Stevens** | **Founder & Chief Executive Officer（創辦人暨執行長）。** 網站用語：「Platform, customer, and infrastructure」，站上呈現為「Founder / CEO」；其 GitHub 個人簡介自述「CEO of Hot Aisle Inc.」。*（部分第三方檔案將其創始職稱記為 CTO —— 本檔採公司自家用語）* | **經營者／所有人。** 資本、硬體供應商選擇、定價與 AMD 獨家路線的最終決策者；同時是公司的公開發聲者 —— 部落格作者、研討會講者、podcast 來賓 | **primary-record** —— 公司自家 `/about`、`/contact`、`/partners`、`/datacenter`、`/investors` 與 `/policies/privacy-policy` 六個路徑；**hotaisle GitHub 組織全部 9 個公開程式庫中的主要 commit 作者，署名 jon@hotaisle.xyz**；**huggingface.co/hotaisle 組織的唯一成員**；以「Jon Stevens, CEO of Hot Aisle」受訪於 AMD TechTalk podcast（主持人 Jim Greene，AMD EPYC 產品行銷總監，2025-04-22）；於 Advizex 案例與 SC24 theCUBE 均以 CEO／Founder 出現。前一段創業經歷：**GearLaunch**（舊金山）共同創辦人；更早參與 Apache Software Foundation；背景被描述為大規模 Bitcoin／Ethereum 挖礦 | **jon@hotaisle.xyz** —— 公開於 hotaisle-cli、hotaisle-website、homebrew-tap 與 apt-repo 的 git commit 作者欄位 · **hello@hotaisle.ai**（全站銷售＋支援信箱，建議優先管道）· **Hacker News 帳號 `latchkey`**（karma 17,167，帳號建立於 2009 —— 最佳的入站管道；他在討論串中自述「(CEO Hot Aisle)」2026-06-03、「i'm the ceo」2026-04-05）· **X／Twitter @HotAisle** · [LinkedIn](https://www.linkedin.com/in/jon-s-stevens/) | **以雇主「Hot Aisle」查詢查無紀錄** —— 全公司以雇主過濾恰好回傳一筆，且該筆是 Clint Armstrong。**以前東家查得相符紀錄，但附身分認定但書：** 四筆 2016 年逐筆申報為 STEVENS, JON · 加州舊金山 · 雇主 **GEARLAUNCH** · 職業 CO-FOUNDER／MR · 經 ActBlue 指定捐給 **BERNIE 2016** · 2016-02-10 $50、2016-03-06 $50 與 $50、2016-03-09 $50。Hot Aisle 的 Jon Stevens 有獨立佐證確為 **GearLaunch 共同創辦人**，且其於 Hacker News 列出的個人網域 ridecontrol.xyz 之登記人州別為加州 —— **依據強，但建立在姓名＋城市＋雇主＋職稱之上，而非建立在載有 Hot Aisle 的申報上。** 另有兩筆 2020 年舊金山紀錄（雇主 SELF、職業 FABRICATOR，$50＋$5 經 ActBlue 指定 BERNIE 2020）一併記錄，但**職業不符，視為未經查證。** 前一輪另保留一筆**可能**的 2020 年紀錄：雇主 **W3BCLOUD**、華盛頓州 Entiat、ActBlue $25（§12） | [About](https://hotaisle.xyz/about/) · [GitHub jon-hotaisle](https://api.github.com/users/jon-hotaisle) · [Hugging Face 組織成員](https://huggingface.co/api/organizations/hotaisle/members) · [AMD TechTalk podcast](https://rss.com/podcasts/amdtechtalk/1997579/) · [Hacker News](https://news.ycombinator.com/item?id=48378058) · [FEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=STEVENS%2C+JON&contributor_state=CA&contributor_city=SAN+FRANCISCO) |
| **Clint Armstrong** | **Co-Founder；Head of Engineering（共同創辦人／工程負責人）。** 網站用語：「Operations, systems, and reliability」；LinkedIn 標題為「Co-Founder / Engineer - Hot Aisle Inc.」 | **經營者／所有人。** 技術決策者與架構／維運守門人 —— **他就是決定「非 Dell 機殼是否可被接受」的人** | **primary-record** —— 公司自家 `/about`、`/contact`、`/partners`、`/datacenter`、`/investors` 與 `/policies/privacy-policy`；**hotaisle/hotaisle-cli 與 hotaisle/cloud-init-templates 的 commit 作者，署名 clint@hotaisle.xyz**（GitHub 帳號 `clint-hotaisle`，2024-02-21 建立）；**另有一份聯邦申報獨立載明其雇主為 HOT AISLE。** 公司新聞素材指出兩位創辦人共事已逾五年，並曾在九座資料中心部署大規模運算 | **clint@hotaisle.xyz** —— 公開於 hotaisle-cli 與 cloud-init-templates 的 git commit 作者欄位 · **hello@hotaisle.ai** · [LinkedIn](https://www.linkedin.com/in/clint-armstrong/)（所在地 Grantham，自述「uses open source software to build reliable networks and business infrastructure」，與其 FEC 申報的 Grantham, NH 地址一致） | **查有紀錄 —— 而且是全 FEC 個人捐款資料庫中唯一一筆雇主為「HOT AISLE」的紀錄。** ARMSTRONG, CLINT · 職業 **ENGINEER** · 新罕布夏州 Grantham · **2024-06-22 · $50.00** · 受款委員會 **WINRED（C00694323）** · 收款類型「EARMARKED FOR LILY4CONGRESS COMMITTEE（C00800458）」· Form F3X、2024 年第 2 季、交易編號 AA27C49AC2D984DBBBB1、影像 202407159656410321。**以姓名＋州查詢回傳 count=1，故這就是他完整的個人捐款史** | [About](https://hotaisle.xyz/about/) · [hotaisle-cli commits](https://api.github.com/repos/hotaisle/hotaisle-cli/commits) · [LinkedIn](https://www.linkedin.com/in/clint-armstrong/) · [FEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_employer=HOT+AISLE) |
| **「NetOps」—— ARIN POC 代號 NETOP393-ARIN** *（登錄機構聯絡人列）* | **Hot Aisle Inc.（ARIN Org HA-716）之 Administrative、Technical、NOC、Abuse、DNS 與 Routing 在案聯絡人。** 狀態 **validated**，2024-01-15 登記，2026-01-14 最後異動 | **技術聯絡人（登錄機構）—— 職務／群組帳號，未具名任何個人。** 就「具名自然人」而言這是明確的 GAP：**ARIN 在整棵 Hot Aisle 樹中未回傳任何個人姓名** | 就登錄物件本身而言為 **primary-record**；其背後的自然人屬**推論，登錄資料從未具名** | **netops@hotaisle.xyz** · **+1-646-389-2009** —— 兩者皆公開於 ARIN POC vCard。646 為紐約區碼，**既不符**懷俄明郵寄地址、**也不符**密西根機房，研判為 VoIP／轉接。**這是維運信箱，不得在此做陌生開發** | 不適用 —— 職務帳號，非自然人 | [ARIN entity HA-716](https://rdap.arin.net/registry/entity/HA-716) · [autnum 21566](https://rdap.arin.net/registry/autnum/21566) · [23.183.40.0/24](https://rdap.arin.net/registry/ip/23.183.40.0) · [2602:f955::/36](https://rdap.arin.net/registry/ip/2602:f955::) |
| **不存在獨立具名的 OrgAdmin／OrgTech／OrgAbuse／NOC** | — | **登錄機構聯絡人 ——「不存在」本身就是發現** | **primary-record**（就「六種角色收斂為單一群組代號」此一事實而言） | 多數業者會把 OrgAdmin、OrgTech、OrgAbuse 與 NOC 分派給不同具名個人。Hot Aisle 把六種角色全部收斂到單一已驗證的**群組**信箱，vCard 為 `kind="group"`、`fn="NetOps"`、`org="Hot Aisle Inc"`。**ARIN 中沒有其他可擷取的具名網路人員。** 再加上 GitHub 組織「no public members」與 LinkedIn 的 2–10 區間，可佐證這確實是兩人的工程團隊 | 不適用 | [ARIN entity HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **PeeringDB 聯絡人** | — | **網路聯絡人（PeeringDB）—— 完全沒有紀錄（GAP）** | **primary-record**（就「集合為空」此一事實而言） | `net?asn=21566` 回傳 `{"data": [], "meta": {"error": "Entity not found"}}`；以組織名稱含「Hot Aisle」查詢亦為空集合。**沒有 policy、technical 或 NOC 聯絡人可擷取，這個帳戶也沒有 peering 社群的切入路徑** | 不適用 | [PeeringDB API](https://www.peeringdb.com/api/net?asn=21566) |
| **AS21566 網路足跡** *（登錄列，無自然人）* | 已宣告前綴 **23.183.40.0/24**（256 個 IPv4 位址），IRR 與 ROA 皆有效；IPv6 **2602:F955::/36 已配發但未宣告** | **網路紀錄 —— 無具名聯絡人可掛接** | **primary-record** | bgp.he.net 顯示**僅一個觀測到的對接／上游：AS49915 Megaport UK Limited**。平均 AS path 長度 4.872，資料時點 2026-08-11。未顯示任何 IRR maintainer 姓名 | 不適用 | [bgp.he.net/AS21566](https://bgp.he.net/AS21566) |
| **Joseph Lubin** | **早期投資人** —— 由 Hot Aisle 具名為「Founder of ConsenSys and co-founder of Ethereum」。**未有任何幹部、董事或員工身分之證據** | **投資方／資金端 —— 明確**未**被證實為在案之幹部、董事或所有權人** | **single-source**（投資關係僅見於公司自家頁面，並由 Mesh 投資組合列示呼應）；**所有量化細節皆為 GAP** | **GAP** —— Hot Aisle 端未公布任何可聯絡到他的管道 | **本輪未查詢 —— 記為 GAP，而非「查無紀錄」。** 他是公司具名的投資人，不是 Hot Aisle 的主事者，查詢他已逾越本公司幹部的研究範圍 | [hotaisle.xyz/about](https://hotaisle.xyz/about/) · [mesh.xyz/portfolio/hot-aisle](https://www.mesh.xyz/portfolio/hot-aisle) · [gen.xyz](https://gen.xyz/blog/hotaisle-xyz) |
| **Saurabh Kapoor** | **Dell Technologies 產品管理總監（Director, Product Management）** —— 這段關係在 Dell 端的可見面孔。**非 Hot Aisle 員工** | **鄰接法人（既有 OEM）—— 夥伴端聯合行銷對口** | **corroborated** —— 於 SC24 theCUBE 與 Stevens 同台；Stevens 亦在 SC24 Dell Technologies 攤位演講 | 僅限 Dell 端。**不得把他當成切入 Hot Aisle 的路徑** —— 他是聯合行銷對口，不是 Hot Aisle 的決策者 | 未查詢 —— 非 Hot Aisle 主事者 | SC24 theCUBE 報導 · [Advizex 案例](https://www.advizex.com/case-studies/advizex-and-hot-aisle) |
| **Advizex 客戶團隊** *（整合商端具名人員列）* | **無法具名任何個人 —— GAP，且是剩餘研究項目中價值最高的一項** | **外部 —— 既有整合商／通路** | **GAP** —— 聯合案例未具名任何 Advizex 人員，LinkedIn 端亦未浮現姓名 | **GAP。** Advizex 於 `/partners` 被列為「Deployment and lifecycle services」，並執行了四個月的基礎設施規劃期，提供解決方案架構、交付與導入、人力支援與供應鏈整合，並與 Dell、AMD、Broadcom、Panduit 協同。**在只有兩名員工的情況下，Hot Aisle 把整合職能外包出去** —— 因此整合商是真實的影響者，競爭的 OEM 要嘛透過 Advizex，要嘛得自行取代該項能力 | 不適用 —— 未辨識出任何個人 | [Advizex 案例](https://www.advizex.com/case-studies/advizex-and-hot-aisle) · [partners](https://hotaisle.xyz/partners) |
| **Andrey Cheptsov**（GitHub `peterschmidt85`） | **dstack 創辦人 —— 外部編排（orchestration）夥伴，非 Hot Aisle 員工** | **影響者／技術背書者／可信的溫暖引介路徑** | 帳號對應真人的部分為 **circumstantial**（公開上已廣為人知，但非 Hot Aisle 所述）；**dstack 為 Hot Aisle 具名夥伴則為確認** | 經 [dstack.ai](https://dstack.ai/blog/h100-mi300x-inference-benchmark/) —— 非 Hot Aisle 信箱 | 未查詢 —— 非 Hot Aisle 主事者 | 於 [hotaisle-website](https://api.github.com/repos/hotaisle/hotaisle-website/contributors) 有 3 筆 commit · dstack 列於 [partners](https://hotaisle.xyz/partners) · 共同貼文 [Orchestrating AMD GPUs with dstack](https://hotaisle.xyz/blog/gpu-orchestration-with-dstack) |
| **Gabriel Alfonzo**（GitHub `NarukeAlpha`） | **僅為 hotaisle-website 的網站／前端貢獻者** | **邊緣人物 —— 網站外包，非採購決策圈成員。** 列出僅為把「還有誰碰過這家公司」這個問題收尾 | **circumstantial** —— 程式碼貢獻已確認，雇傭關係未確認 | 公開 git commit metadata 中出現其個人信箱。**不得進行陌生接觸：** 那是附帶曝光的個人地址，他沒有 hotaisle.xyz 信箱，也未列於 About 頁；本檔刻意不轉載該地址 | 未查詢 —— 邊緣貢獻者 | [hotaisle-website 貢獻者](https://api.github.com/repos/hotaisle/hotaisle-website/contributors) |
| **`dhogaivannan`（GitHub）—— 未公開真實姓名** | **hotaisle/hotaisle-cli** 的第三位貢獻者 —— 2026-06-23 commit「feat(release): publish signed RPM repository」 | **未解線索 —— 記為線索，不是已辨識之人員** | 身分為 **GAP**。個人檔案顯示名稱「Dhogaivannan」、所在地 New York、帳號建立於 2013。**無法確認其為員工或外部貢獻者；** 未公開真實姓名、信箱或 LinkedIn | **GAP** —— 不得接觸 | 無法查詢 —— 無真實姓名 | [api.github.com/users/dhogaivannan](https://api.github.com/users/dhogaivannan) |
| **`gtnotacoder`（gt@netg.co）· `vmiss33`** | 僅為 **hotaisle-website** 的貢獻者 —— 亦即部落格／來賓內容，不是平台程式碼 | **外部／夥伴貢獻者 —— 未有其為員工之證據** | 雇傭關係為 **GAP**。**把他們列為員工會是臆測** | **GAP** —— 不得接觸 | 未查詢 | [hotaisle-website 貢獻者](https://api.github.com/repos/hotaisle/hotaisle-website/contributors) |

**刻意排除，並在此載明。** GitHub commit 紀錄**不是員工名冊**。整個組織的七個不同貢獻者帳號中，恰好只有兩個使用 hotaisle.xyz 的 commit 信箱（jon@、clint@），其餘僅限網站、屬夥伴關聯，或無法辨識身分。上表將其一併列出，是為了避免後續讀者把 commit 紀錄當成員工名冊來挖。同理，**benchmark 引用索引與夥伴 logo 列也不是員工來源** —— Dr. Moritz Lehmann 是獨立研究者，Savannah Peterson 與 Dave Vellante 是 theCUBE 主持人，皆非 Hot Aisle 人員。

### 4.2 登錄紀錄（Registry record）

須先界定範圍，而這也是本檔案最大的證據弱點：以下是**網路號碼登錄紀錄、聯邦競選財務紀錄，加上公司自行陳述。這裡沒有任何一筆公司登記機關紀錄，因為根本取不到**（§9.2 逐字記錄每一次嘗試）。

| 姓名 | 身分／權限 | 申報文件 | 申報日期 | 來源 |
|---|---|---|---|---|
| **未取得任何公司幹部資料** | **無法取得。** 任何一州皆無法取得幹部、董事、經理人、股東、設立人、註冊／登記代理人姓名或年報簽署人 | **未取得任何文件。** 密西根 LARA 前置 Cloudflare，直接中斷 TLS 交握；德拉瓦 ICIS 回傳頁內錯誤；懷俄明 SOS 位於 F5／Shape 機器人防護（`window["bobcmn"]`）之後，且無可用之 ASP.NET `__VIEWSTATE` 可供提交；OpenCorporates（HTTP 403）、Bizapedia（HTTP 404）與 CorporationWiki（HTTP 403）皆受阻。**設立州別本身仍屬未知** | 不適用 | [Michigan LARA](https://cofs.lara.state.mi.us/CorpWeb/CorpSearch/CorpSearch.aspx)（受阻）· [Delaware ICIS](https://icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx)（錯誤）· [Wyoming SOS](https://wyobiz.wyo.gov/Business/FilingSearch.aspx)（機器人防護） |
| **「NetOps」—— ARIN POC 代號 NETOP393-ARIN**（群組／職務帳號；org 欄位為「Hot Aisle Inc」） | **ARIN Org HA-716、AS21566（名稱 HOTAISLE）、23.183.40.0/24 與 2602:F955::/36 之 Administrative POC、Technical POC、NOC POC、Abuse POC、DNS POC 與 Routing POC。** 登記組織地址：**1603 CAPITOL AVE, STE 415, PMB 41293, Cheyenne, WY 82001** | **ARIN 號碼資源登錄：** Org 紀錄 HA-716 ＋ POC 紀錄 NETOP393-ARIN，狀態 **validated**。AS21566 的登記備註指向 https://hotaisle.xyz/ | POC 登記 **2024-01-15**；Org HA-716 登記 **2024-01-15**；AS21566 登記 **2024-02-14**；Org 最後異動 **2026-07-14** | [rdap.arin.net/registry/entity/HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **「Hot Aisle Inc.」** *（組織列）* | **ARIN Org 代號 HA-716。** ARIN 要求組織就法定名稱與地址作出聲明，因此在缺乏登記文件的情況下，**這是現有最佳的法人存在佐證** | ARIN Org 紀錄；AS21566「HOTAISLE」；NET-23-183-40-0-1（「HA-4-10」，2024-06-26 直接配發）；NET6-2602-F955-1（「HA-SOPH」，2024-03-04） | Org 登記 **2024-01-15T14:49:58-05:00**；最後異動 **2026-07-14** —— 與公開調價同一天 | [rdap.arin.net/registry/entity/HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **Jon Stevens** | **僅由公司自行宣稱並由程式碼 commit 佐證之幹部，非登記在案。** Founder／Chief Executive Officer | **並非申報文件。** 屬公司網站六個路徑之陳述、以 jon@hotaisle.xyz 署名之組織程式庫 commit、Hugging Face 組織唯一成員身分，以及第三方報導（AMD、Advizex、theCUBE） | About 頁截至 2026-08-11 為現行；GitHub 組織建立於 2023-10-18；AMD TechTalk 2025-04-22 | [hotaisle.xyz/about](https://hotaisle.xyz/about/) · [GitHub jon-hotaisle](https://api.github.com/users/jon-hotaisle) |
| **Clint Armstrong** | **僅由公司自行宣稱並由程式碼 commit 佐證之幹部，非登記在案。** Co-Founder／Head of Engineering | 就公司職務而言**並非申報文件** —— 但**確有一份聯邦申報佐證其雇傭關係**：他在 FEC Schedule A 中填列雇主 HOT AISLE、職業 ENGINEER。這佐證的是**雇傭，不是公司職務** | GitHub 帳號建立於 2024-02-21；FEC 收款日 **2024-06-22** | [hotaisle.xyz/about](https://hotaisle.xyz/about/) · [FEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_employer=HOT+AISLE) |
| **網域登記人** | **已遮蔽 —— 無法取得任何登記人姓名** | hotaisle.xyz WHOIS／RDAP：建立於 **2023-10-18T06:14:34Z**，到期 2026-10-18，最後異動 2025-11-05，註冊商 **Spaceship Inc.**（IANA 3862），registry ID D404089308-CNIC，名稱伺服器 mario／sara.ns.cloudflare.com。hotaisle.ai、.com、.io 與 .net 同樣遮蔽 | 網域建立於 2023-10-18 | [rdap.centralnic.com/xyz/domain/hotaisle.xyz](https://rdap.centralnic.com/xyz/domain/hotaisle.xyz) |

### 4.3 採購決策圈（Buying committee）

Hot Aisle 是一家**兩人公司，沒有採購職能、沒有 CFO、也沒有 IT 主管可以繞** —— 創辦人自己簽核。但「路徑最短」不等於「路徑完整」：**資金、整合商、加速器廠商與房東各自握有真實的否決權，而其中三者比創辦人更可能讓案子死掉。**

| 對象 | 為何對伺服器採購具關鍵性 | 接觸方式 |
|---|---|---|
| **Jon Stevens** —— Founder & CEO | **在一家 LinkedIn 列為 2–10 人、且僅有兩位有據可查主事者的公司，商業上他本人就是整個採購決策圈。** 依公司自家 `/about` 的分工，平台、客戶、夥伴關係與社群都歸他；`/investors` 的具名聯絡人是他；**定價由他親自訂定並公開辯護** —— 把 MI300X 虛擬機價格自 $1.99 調升至 $2.99／GPU-hr 的那篇文章就是他寫的。**任何 MI355X 規模的硬體採購單，都是由他簽核。** AMD 獨家路線也由他決定，而他把這件事講成**理念問題** —— 去中心化、與 NVIDIA 競爭 —— 不只是商業問題 | **不要對他跑企業銷售流程。** `/contact` 頁明白拒絕「traditional sales chains」，公司以「no contracts, no sales calls」的方式銷售。他在公開技術場域**回應極快** —— Hacker News 帳號 **`latchkey`**、X 帳號 **@HotAisle** —— 也可直接寄信（**jon@hotaisle.xyz**、**hello@hotaisle.ai**）。**以工程實質與單位經濟開場**，公開或以簡短私訊皆可。**任何對話要成真，先過兩道硬關卡：**（1）平台**設計上就只用 AMD Instinct**，非 AMD 的 SKU 直接出局；（2）**他目前沒有資本。** 可行的開場是**一份帶融資結構的 AMD MI355X 系統提案，不是一張報價單** |
| **Clint Armstrong** —— Co-Founder / Head of Engineering | 掌管「operations, systems, and reliability」與「the engineering and automation work behind the platform」。**他就是技術否決權：** 裸機可管理性、cloud-init／provisioning 範本、2×400G Broadcom 網路、機櫃整合、Switch Grand Rapids 廠內的電力與散熱，以及 60 秒內完成佈建的承諾，全都在他這一側。他也是**唯一另一位擁有公開公司信箱與 commit 權限的人** | **工程師對工程師，以書面、談具體數字。** 他的公開足跡是開源基礎設施自動化（他自己的說法：以開源軟體打造可靠的網路與商業基礎設施）。可寄 **clint@hotaisle.xyz**。**能打動他的是：** 帶外管理與韌體方案、cloud-init／裸機重佈建行為、對照 Switch 設計的機櫃電力與散熱包絡，以及可維修性。**行銷簡報不會有效** |
| **資金提供方／未結案的 $50–100M 募資** —— **真正的關卡** | **對任何要賣硬體給他們的人而言，這是最重要的一條。** `/investors` 頁載明正在募集 **「$50–100 million across equity, strategic investment, and asset finance」**，且「The capital will purchase AMD MI355X systems and fund the networking, rack integration, and site deployment required to bring each regional unit online.」`/mi355x` 頁直白寫著：**「We are still raising the capital required to buy and deploy the hardware.」** 他們宣稱 MI355X 產能的**客戶需求已超過 5,000 萬美元**，並說**「The constraint is access to hardware, not demand for the platform.」** 定價那篇文章補充「More capital groups and strategic operators are taking an interest.」**輪次金額、日期、階段與領投人從未公開揭露** —— Consensys Mesh 把他們列在投資組合，公司具名 Joseph Lubin 為早期投資人，但沒有任何量化細節 | **賣的是融資，不是機器。** 可行的工具是**供應商／資產融資或租賃結構** —— 「asset finance」本來就是他們自己列出的三條資本路徑之一。一份**把硬體與租賃或遞延付款結構綁在一起**的提案，或把自有融資單位／第三方出租方帶到桌上的提案，命中的是真正的瓶頸，也是唯一可能**趕在募資交割之前**推進的做法。他們也說過，接上對的資金來源「could make a real difference」——**在這個帳戶上，引介本身就是正當的敲門磚。** 請把募資公告視為採購觸發訊號 |
| **Advizex** —— 既有整合商／通路 · **無具名個人（GAP）** | 於 `/partners` 被列為「Deployment and lifecycle services」，並且是聯合案例的主角。Advizex 執行了**四個月的基礎設施規劃期**，為 Dell XE9680 ＋ MI300X 建置提供解決方案架構、交付與導入、人力支援與供應鏈整合，並與 Dell、AMD、Broadcom、Panduit 協同。Stevens 的引述是：「Advizex has helped us with all aspects of the deployment」與「Everything Advizex has said they would do, they have done above and beyond expectations.」**在只有兩名員工的情況下，Hot Aisle 把整合職能外包出去** —— 因此整合商是真實的影響者，競爭的 OEM 要嘛透過 Advizex，要嘛得自行取代該項能力 | **在直接接觸之前或同時，先把負責 Hot Aisle 的 Advizex 客戶團隊摸清楚並接觸。** **本輪無法由公開來源具名任何 Advizex 個人 —— 這是未結的 GAP，也是價值最高的下一步研究項目。** 案例中沒有任何 Advizex 人名，LinkedIn 端亦未浮現。**要換掉的是機殼，絕不是整合商** |
| **Dell Technologies** —— 既有 OEM · **Saurabh Kapoor（Director, Product Management）是 Dell 端的可見面孔** | Dell 於 `/partners` 被列為「Hardware systems and support」，而**既有機隊全部是 Dell PowerEdge XE9680。** Kapoor 在 SC24 與 Stevens 同台 theCUBE，Stevens 也在 SC24 Dell 攤位演講 —— **這是活躍的聯合行銷關係，不只是交易型供貨關係。** 這就是任何競爭 OEM 必須跨過的轉換成本，而且 **Dell 一定會守住 MI355X 這次改朝換代** | **把 Dell 當成要被取代的既有者，並假設 Dell 已經知道 MI355X 計畫。** 差異化必須落在 Dell 沒有給的東西：**融資條件、MI355X 交期、對應其分散小型站點模式的密度／功耗，或可維修性。** **Kapoor 是公開的聯合行銷對口，不是 Hot Aisle 的決策者 —— 不要把他當成切入路徑** |
| **AMD** —— 平台守門人 | 於 `/partners` 被列為「Accelerator platform」。Hot Aisle 是 **AMD 獨家的 neocloud**，曾被 AMD 自家部落格以 NeoCloud 專文報導，Stevens 也上過 AMD TechTalk podcast。**AMD 對 MI355X 供給的配額本身，就是與資本並列的關卡。** AMD 同樣有讓 MI355X 產能落地的動機 | **任何提案都必須以 AMD Instinct MI355X 為基礎。** AMD 的 neocloud／夥伴團隊是**正當的並行路徑** —— 鑑於他把公司身分與 AMD 綁得如此公開，經由 AMD 轉介的溫暖引介，份量遠高於供應商的陌生開發 |
| **Switch**（Grand Rapids「Pyramid」園區）—— **場域限制，不是買家** | 算力位於 Switch 的密西根州 Grand Rapids 廠（Tier 5 Platinum、武裝警衛、生物辨識門禁、100% 再生能源）。**機櫃、電力與散熱包絡以及進場物流由 Switch 決定**，而 Hot Aisle 自述的 MI355X 計畫是採分散式的「smaller inference-focused sites」，而非單一大型部署。任何硬體提案都必須符合 Switch 式主機代管限制與多站點推展 | **不是銷售對象 —— 不要代替 Hot Aisle 直接接觸 Switch。** 請當成**資格確認輸入**：提出符合多站點主機代管部署的 SKU 與機櫃設計，並且要能談 Switch 的散熱設計。把散熱問題做成**對 Hot Aisle 的資格確認問題**（§14） |

### 4.4 未能具名之職位 —— 每一項皆為 GAP

**GAP — CFO／財務負責人／財務主辦：** 任何地方皆無具名財務職；依 `/investors`，**$50–100M 的募資由 Stevens 親自處理。** · **GAP — 業務主管／CRO／業務副總／任何業務代表：** 而且**依其設計本來就可能真的不存在** —— `/contact` 明白拒絕「traditional sales chains」，產品以自助方式銷售，標榜「no contracts, no sales calls」。 · **GAP — 採購／採購經理：** 無此職稱；硬體採購看來是 **Stevens → Advizex → Dell** 的路徑。 · **GAP — 具名的 Advizex 客戶團隊成員**（客戶經理、解決方案架構師、交付主管）：Advizex 是具名的部署與生命週期服務夥伴，並執行了四個月規劃期，但聯合案例**未**具名任何 Advizex 個人，其他地方也未浮現。**對任何要把硬體賣進這個帳戶的人而言，這是價值最高的剩餘研究目標。** · **GAP — CISO／資安主管／SOC 2 法遵負責人／DPO：** 已宣稱取得 SOC 2 Type 1 與 Type 2；Type 1 該篇明謝 **Sprinto 與 ATOM**（外部），隱私政策把資料保護聯絡導向通用信箱 hello@hotaisle.ai。 · **GAP — 法務長／法務聯絡人／服務條款簽署人：** 服務條款與隱私政策上沒有法務聯絡人、沒有法人州別、也沒有幹部簽名欄。 · **GAP — 行銷／公關負責人：** 部落格貼文無署名；Stevens 的 `/about` 職責描述明確含「socials」。 · **GAP — 客戶成功／支援主管：** `/contact` 描述有「Customer Support」路徑，由未具名的「operations staff」負責；唯一地址是 hello@hotaisle.ai。 · **GAP — 具名網路工程師／NOC 人員：** ARIN 只回傳群組職務帳號 NETOP393-ARIN，**PeeringDB 完全沒有紀錄。** · **GAP — 董事會、觀察員、投資方董事：** Joseph Lubin 僅被具名為早期投資人；**沒有任何董事席次、觀察權或董事之證據。** · **GAP — 公司登記之幹部：** 設立人、董事、幹部、經理人、股東、註冊／登記代理人、年報簽署人與歷史幹部沿革 —— **密西根 LARA、德拉瓦與懷俄明皆然。** 三個登記機關都在機器人防護之後且未被破解。**設立州別本身仍屬未知。** · **GAP — UCC-1 擔保權人與債務人簽署人：** 懷俄明與密西根的 UCC 查詢位於同樣受阻的州務卿入口網站之後。鑑於該公司以融資方式取得 GPU 硬體，並明列「asset finance」為資本路徑之一，**UCC-1 查詢很可能有產出，應自未受阻環境重試 —— 它可能同時揭露既有的貸方與一位幹部簽名。** · **GAP — 法院案卷之當事人與簽署人：** CourtListener API 拒絕匿名存取（HTTP 403），其網頁查詢亦回 403；本輪未完成任何聯邦或州層級案卷查詢。 · **GAP — 商標聲明簽署人與代理人：** 無可用之 USPTO 查詢路徑（§3 第 8 列）。 · **GAP — 隱私遮蔽前之歷史 WHOIS 登記人：** hotaisle.xyz 自 2023-10-18 建立起即在 Spaceship 遮蔽；whoisrequest.com 位於 Cloudflare 挑戰之後，whoxy.com 的歷史查詢以 CAPTCHA 收費牆封鎖，本檔未嘗試繞過。 · **GAP —— 屬刻意排除而非查詢失敗：機房所在郡之產權／估價紀錄。** Hot Aisle 是 Switch Grand Rapids Pyramid 園區（密西根州 Kent County）的**主機代管租戶**；地號的所有權人會是 **Switch** 而不是 Hot Aisle，因此 Kent County 估價查詢只會查到 Switch 的幹部。基於此原因未予進行。 · **GAP — 具名招募主管、匯報鏈、招募顧問或任何職缺：** 而且**這些職位看來根本不存在** —— 45 個 URL 的 sitemap 沒有 `/careers` 或 `/jobs` 頁，任何求職平台上都查不到 Hot Aisle 職缺，LinkedIn 也把公司列為 2–10 人。 · **GAP — GitHub 貢獻者 `dhogaivannan` 的真實姓名**（New York；2026-06-23 對 hotaisle-cli 提交簽章 RPM 發行工具）：無法確認其為員工或外部貢獻者。 · **GAP — WebHostingTalk、LowEndTalk 或 Reddit 上經查證的員工帳號：** 僅 Hacker News（`latchkey` = Jon Stevens，於討論串中自述為 CEO）獲得確認。 · **GAP — 投資細節：** Mesh.xyz／Joseph Lubin 具名為投資方，但**無輪次金額、日期、持股比例、董事席次或股權結構表**，且**現行 $50–100M 募資案查無任何公告。**

### 4.5 已實際查詢之來源 —— 含「查無」者

**網路號碼登錄機構。** **[ARIN RDAP](https://rdap.arin.net/registry/entity/HA-716)** —— **對法人高產出，對具名人員零產出。** 以 `fn=Hot Aisle*` 查詢實體，回傳 Org 代號 **HA-716**、1603 CAPITOL AVE STE 415 PMB 41293, Cheyenne WY 82001、2024-01-15 登記、2026-07-14 最後異動。完整 Org 紀錄回傳 **AS21566「HOTAISLE」**（2024-02-14 登記）、IPv4 **23.183.40.0/24**（NET-23-183-40-0-1，「HA-4-10」，2024-06-26 直接配發）與 IPv6 **2602:F955::/36**（NET6-2602-F955-1，「HA-SOPH」，2024-03-04）。四個物件共用**同一個** POC：NETOP393-ARIN，`kind=group`、`fn="NetOps"`，同時承擔 administrative ＋ technical ＋ noc ＋ abuse ＋ dns ＋ routing，信箱 netops@hotaisle.xyz，電話 +1-646-389-2009。**沒有任何 OrgAdmin、OrgTech、OrgAbuse 或 NOC 條目具名個人。** *（第一次以代號「HOTAI」查詢回傳的是無關組織 ——「HotAir」，維吉尼亞州 Arlington —— 已記錄以免重蹈。）* · **[PeeringDB API](https://www.peeringdb.com/api/net?asn=21566)** —— **查無。** `net?asn=21566` → `{"data":[],"meta":{"error":"Entity not found"}}`；`org?name__contains=Hot Aisle` → 空集合。 · **[bgp.he.net AS21566](https://bgp.he.net/AS21566)** —— 產出有限且**無聯絡人**：確認 AS 名稱、一條已宣告的 IPv4 前綴（IRR 與 ROA 皆有效）、無 IPv6 宣告、平均 AS path 4.872、單一觀測對接對象 **AS49915 Megaport UK Limited**，資料時點 2026-08-11。

**公司登記機關 —— 全數受阻，零資料。** **密西根 LARA**（`cofs.lara.state.mi.us`、`mibusinessregistry.lara.state.mi.us`）—— cofs 主機完全無法連線（三個端點包含 `SearchApi/Search/Search` JSON 路由，GET 與 POST 皆 curl exit 000）；mibusinessregistry 回 **HTTP 403 並帶 `cf-mitigated: challenge`**。 · **[Delaware ICIS](https://icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx)** —— 主機可解析（75.2.72.47），但實體查詢需互動式工作階段／CAPTCHA；**未取得任何資料。** · **[Wyoming SOS](https://wyobiz.wyo.gov/Business/FilingSearch.aspx)** —— 頁面可載入，但受 **F5／Shape 機器人防護腳本**（`window["bobcmn"]` 挑戰負載）保護，且無可用之 ASP.NET `__VIEWSTATE` 可供提交；**未破解。** · **OpenCorporates** —— HTTP 403。 · **Bizapedia** —— 查詢端點 HTTP 404。 · **CorporationWiki** —— HTTP 403。 · **OpenGovUS** —— 查詢頁可載入，但該站**沒有懷俄明州的商業實體資料集**（其州別清單由 Alabama 到 West Virginia，沒有 Wyoming），故無法替代。

**競選財務與遊說。** **[FEC openFEC API](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_employer=HOT+AISLE)** —— **高產出。** 執行之查詢：以 `contributor_employer` 對六種 Hot Aisle 寫法查 `schedule_a`；以 `contributor_name` 查 ARMSTRONG, CLINT（NH）與 STEVENS, JON／JONATHAN（CA、WY、San Francisco）；以雇主 GEARLAUNCH 查詢；以雇主含「AISLE」做萬用字元掃描（**1,250 筆，全部屬無關公司** —— Aisle 518 Strategies、AisleLogic、Aisle Rocket、Across the Aisle）；以及 C00694323、C00800458、C00401224、C00577130、C00696948 的委員會查詢與 C00800458 的候選人連結。**委員會登記庫查詢 `q="hot aisle"` → count 0。** *（存取註記：api.data.gov 的 DEMO_KEY 遭速率限制 HTTP 429，因此改用 FEC 自行公布於 fec.gov/data 公開資料瀏覽頁原始碼中的公開 API key —— 那是供瀏覽公開競選財務資料之用的公開金鑰。）* · **[參議院 LDA API](https://lda.senate.gov/api/v1/filings/?client_name=hot+aisle)** —— **確認負面結果。** 八次查詢：以 `client_name` 與 `registrant_name` 分別查「hot aisle」、「hot%20aisle」、「hotaisle」、「Hot Aisle Inc」，全部回傳 `{"count":0,"next":null,"previous":null,"results":[]}`。 · **懷俄明州競選財務**（[wycampaignfinance.gov](https://www.wycampaignfinance.gov/WYCFWebApplication/GSF_SystemConfiguration/SearchContributions.aspx)）—— **可觸及但無法查詢**：HTTP 200，但捐款查詢是 ASP.NET postback 表單。 · **密西根州競選財務**（`cfs.sos.state.mi.us`）—— **無法連線**（curl exit 000）。 · **新罕布夏州競選財務** —— 本輪未觸及。

**程式碼、社群與身分。** **[GitHub](https://api.github.com/orgs/hotaisle)** —— **高產出。** 組織 `hotaisle`，id 148374139，已驗證，建立於 2023-10-18T17:01:52Z，信箱 hello@hotaisle.ai，twitter hotaisle。**`public_members` 回傳 `[]`** —— 零公開成員。橫跨 hotaisle-cli、hotaisle-website、cloud-init-templates、homebrew-tap、apt-repo、rpm-repo 與 .github 的 commit 作者列舉，**恰好得到兩位持有公司信箱的真實員工身分。** · **[Hugging Face 組織 API](https://huggingface.co/api/organizations/hotaisle/members)** —— **佐證性**：成員恰好一位，Jon Stevens；未發布任何模型。 · **[Hacker News](https://news.ycombinator.com/user?id=latchkey)**（Firebase ＋ Algolia API）—— **高產出**：「hotaisle」226 筆命中；帳號 `latchkey`（2009 年建立，karma 17,167）即 Jon Stevens，並於討論串中自述（「(CEO Hot Aisle)」2026-06-03，item 48378058；「i'm the ceo」2026-04-05，item 47651686；「I'm CEO of an AMD neocloud」2026-05-03，item 47999209）。**這是通往 CEO 最佳的入站管道。** · **Reddit、WebHostingTalk、LowEndTalk** —— **查無**；搜尋結果被無關的「hot aisle containment」機房設施討論淹沒。 · **Glassdoor** —— 僅間接佐證（2023 年 10 月由 Jon Stevens 與 Clint Armstrong 創立，總部懷俄明州 Cheyenne）；頁面未直接抓取。

**公司與夥伴來源。** **hotaisle.xyz** —— 完整 45 個 URL 的 sitemap 逐頁處理：`/about`、`/contact`、`/investors`、`/partners`、`/datacenter`、`/mi355x`、`/pricing`、`/policies/privacy-policy`、`/policies/terms-of-service`、`/lighthouse`、`/blog` 與部落格索引。**全站具名人員：僅 Jon Stevens 與 Clint Armstrong，加上被具名為早期投資人的 Joseph Lubin。** 唯一公布的聯絡管道：hello@hotaisle.ai。**沒有地址、沒有電話、沒有徵才頁、沒有設立州別、沒有幹部簽名欄。** *（注意頁尾連結的 `/supercomputer` 回 404。）* · **[/investors](https://hotaisle.xyz/investors)** 與 **[/mi355x](https://hotaisle.xyz/mi355x)** —— 關鍵商業發現（募資，以及「still raising the capital」）。 · **[Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)** —— $1.99 → $2.99 的調整、700+ 客戶、產能全滿、「More capital groups and strategic operators are taking an interest.」 · **[Wayback Machine CDX API](http://web.archive.org/cdx/search/cdx?url=hotaisle.xyz/mi325x&matchType=prefix)** —— 列舉 20 份定價快照、抓取並解析其中 12 份；產出 §8 的完整採購時鐘與「跳過世代」的發現。**WebFetch 對 web.archive.org 為硬性阻擋，只有 Bash/curl 可行。** · **[Advizex 案例](https://www.advizex.com/case-studies/advizex-and-hot-aisle)** —— 關係細節，**內文完全沒有任何 Advizex 人名**。 · **theCUBE／SC24 報導** —— 僅得夥伴端姓名（Dell 的 Saurabh Kapoor；主持人 Savannah Peterson 與 Dave Vellante）。 · **[AMD TechTalk podcast](https://rss.com/podcasts/amdtechtalk/1997579/)**（2025-04-22）—— 職稱／角色確認，訪談者 Jim Greene。 · **[AMD NeoCloud 部落格](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html)** —— 本輪抓取逾時 60 秒；已索引並確認存在，未讀取。 · **[LinkedIn 公司頁](https://www.linkedin.com/company/hotaisle)** —— 2–10 人；總部 Cheyenne WY；創立 2023；IT Services and IT Consulting；夥伴 Dell、AMD、Broadcom、Advizex；聯絡 hello@hotaisle.ai。*（個人檔案 `/in/jon-s-stevens/` 抓取回 HTTP 999 反爬蟲；Armstrong 的標題與 Grantham 所在地僅由搜尋結果摘要取得。）* · **Crunchbase** —— HTTP 403。PitchBook 有檔案（id 600969-16）但無法存取。 · **[Consensys Mesh 投資組合](https://www.mesh.xyz/portfolio/hot-aisle)** —— **幾乎沒有產出**：只有分類標籤，沒有階段、日期、金額、創辦人或 Mesh 合夥人。 · **[D&B](https://www.dnb.com/business-directory/company-profiles.hot_aisle_inc.6343b38590429aa36d4f33b58a5ecdf9.html)** —— 僅由搜尋摘要取得片段（Cheyenne WY、1-10 區間）；**未取得**營收、SIC／NAICS 與主要負責人欄位。 · **[Supermicro eStore](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html)** 與 [MI355X 方案頁](https://learn-more.supermicro.com/mi355x) —— BOM 錨點與氣冷楔子。 · **[Switch](https://www.switch.com/grand-rapids/)** 及 DataCenterFrontier／datacenters.com／Baxtel 之園區背景。

**智財、訴訟與不動產。** **USPTO**（tmsearch、TSDR、assignment API）—— **本輪未取得資料**：POST 回 HTTP 405，三個既載 GET 路徑回 404（NoSuchKey），assignment-api 無法連線，trademarks.justia.com 回 403，uspto.report 回 403。 · **CourtListener／RECAP** —— **本輪受阻**：API v3 回傳 `{"detail":"Anonymous users don't have permission to access the API."}`（HTTP 403），網頁查詢亦回 403。 · **UCC-1（懷俄明與密西根）** —— **未查詢**，兩者皆位於受阻的州務卿入口網站之後；鑑於其明列 asset finance 路徑，標記為高價值項目。 · **郡產權／估價紀錄** —— **屬刻意排除而非受阻**（租戶而非所有權人：任何 Kent County 地號紀錄的所有權人都會是 Switch）。已找出正確查詢管道（Kent County Property Search；Caledonia Township Assessing，8196 Broadmoor Ave SE，(616) 891-0070），但未調閱任何地號。

**網域紀錄。** **hotaisle.xyz 的 WHOIS／RDAP** —— 取得日期與註冊商，**未取得登記人姓名**：建立於 2023-10-18T06:14:34Z，到期 2026-10-18，最後異動 2025-11-05，註冊商 Spaceship Inc.（IANA 3862），狀態 clientTransferProhibited，登記人完全遮蔽。hotaisle.ai、.com、.io 與 .net 同樣遮蔽。**歷史 WHOIS**（whoisrequest.com、whoxy.com、viewdns.info）—— **三者皆查無**：分別為 HTTP 403 Cloudflare 挑戰、CAPTCHA 收費牆、HTTP 404。*（附帶說明：**ridecontrol.xyz** 是 Stevens 由其 Hacker News 個人檔案連出的個人專案，公開 WHOIS 中登記人州別為 **CA**、國別 US。此資訊**僅**用於為 FEC 姓名查詢設定地理範圍 —— 隨後即命中舊金山／GearLaunch。該紀錄中的登記人電話為個人號碼，本檔刻意不予轉載。）*

**徵才啟事 —— 查無，而這本身就是發現。** 45 個 URL 的 sitemap 中沒有 `/careers` 或 `/jobs` 頁；LinkedIn Jobs、Indeed 或任何彙整平台上都沒有 Hot Aisle 職缺；搜尋結果只浮現無關的「hot aisle containment」機房設施職缺。**未取得任何具名招募主管、匯報鏈或招募顧問。** 由 LinkedIn 的 2–10 區間佐證 —— **這些職位很可能根本不存在。**

---

## 5. 據點與機房

| 站點 | 機房營運商 | 自有／租用 | 面積與電力 | 證據 |
|---|---|---|---|---|
| **Switch「The Pyramid」園區 —— 密西根州 Grand Rapids／Caledonia（Kent County）。** 前身為 Steelcase Pyramid；Switch 的園區地址為 6100 East Paris Avenue SE, Caledonia, MI。**這是 Hot Aisle 唯一的生產據點** | **Switch, Inc.** —— 機房營運商／房東。Hot Aisle 是運算租戶 | **租用 —— 主機代管租戶關係。** 伺服器、網路設備與 IP 位址由 Hot Aisle 擁有；建物、電力與散熱由 Switch 擁有並營運。佐證：Hot Aisle 自家頁面的租戶措辭（「Located at the Switch Pyramid data center」）、Switch 代其核發年度再生能源憑證並退役 REC，以及 Partners 頁把 Switch 列在「Data center operations」。**對產權研究的意涵：Kent County 不會有以 Hot Aisle 為名的地號或估價紀錄 —— 地號屬於 Switch** | **機房：** Switch 稱 Pyramid 園區為 **Tier 5 Platinum、已建 660,000 平方英尺、規劃可達 180 萬平方英尺與滿載 110 MW。** **Hot Aisle 自身的用量未揭露 —— 但可由其公布的 REC 退役量推導。** 2024 年退役 267 張、2025 年退役 781 張。以 1 REC = 1 MWh 計：2025 年 781 MWh ÷ 8,760 小時 ≈ **平均 89 kW**；2024 年 267 MWh 分攤於約四個實際運轉月（叢集約 2024 年 9 月上線）≈ **91 kW**。**兩個獨立年度收斂到約 90 kW 的平均總負載** —— 這是一個緊密且自洽的估計。以 Switch 宣稱的低 PUE 推算，IT 負載約 **70–80 kW**，即個位數到十幾個機櫃的規模。**此為本檔推導之估計值，非公司揭露** | 逐字取自 [hotaisle.xyz/datacenter](https://hotaisle.xyz/datacenter)：「Switch Pyramid • Grand Rapids, MI」「Tier 5 Platinum Infrastructure」「Located at the Switch Pyramid data center in Grand Rapids, Michigan. A facility our partners can brag about.」「Armed guards, multiple layers of physical and biometric access controls」「100% renewable energy, low PUE (patented T-SCIF design)」，以及「Fiscal — Tax optimization allows us to pass significant capital cost savings onto our partners」*（研判所指為密西根州資料中心銷售／使用稅減免）*。REC 數字逐字取自 [2024](https://hotaisle.xyz/blog/hot-aisle-goes-100-green-with-switch-sustainability-certification-2024/) 與 [2025](https://hotaisle.xyz/blog/hot-aisle-goes-100-green-with-switch-sustainability-certification-2025/) 兩篇認證貼文。園區數據：[switch.com/grand-rapids](https://www.switch.com/grand-rapids/) |
| **未來／規劃中 —— 多個小型區域推論站點**（地點尚未具名） | **不明** —— 尚未選定或未揭露 | 依其自述模式，將為租用之主機代管空間 | 未揭露。描述為「Compact, repeatable inference deployments in more data centers, placed near the teams and jurisdictions that need them」 | 逐字取自 [investors](https://hotaisle.xyz/investors)：「We are not pursuing one giant deployment and hoping demand follows. We will grow through smaller inference-focused sites, each able to serve a regional market with the same platform and operating discipline.」以及「Existing automation brings networking, PXE boot, operating systems, ROCm, and KVM isolation online without rebuilding the process at every site.」**這是可重複單元的採購模式 —— 贏下一個節點設計，等於贏下一套範本，而不是一筆一次性生意** |
| **歷史能力宣稱 —— 與「Tier 3-5 data centers in the US」的關係** | 各家，未具名 | 不適用 —— 屬顧問／仲介宣稱，非其自身據點 | 不適用 | 取自 2024 年存檔的 Cluster 頁：「Bring your own DC or use ours: We've developed relationships with a number of Tier 3-5 data centers in the US. We can help negotiate your DC, Insurance and Internet contracts for you」（[Wayback 2024-11-14](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)）。保留此列，是因為它顯示了**第二條、不明顯的業務線 —— 叢集設計顧問**，硬體供應商可以附掛其上 |
| **登記地址 —— 郵件代收信箱** —— 1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne, WY 82001 | 商業註冊代理人（與 Registered Agents Inc. 相符） | 不適用 —— 私人信箱 | 不適用 | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716)；[D&B](https://www.dnb.com/business-directory/company-profiles.hot_aisle_inc.6343b38590429aa36d4f33b58a5ecdf9.html)。**不得前往拜訪，也不得寄送貨物。** Hot Aisle 在任何地方都沒有可拜訪的辦公室；唯一的實體存在是 Switch Pyramid 園區內的租用機櫃空間，需 Switch 陪同、武裝警衛核可與生物辨識通行 |

**租戶關係備註（這是 §5 中最具商業決定性的事實，不是註腳）：** 因為 Hot Aisle 是承租而非自營，**它並不掌握自己的散熱系統。** 其 MI355X 規劃明列每顆加速器 1,400 W、採用直接液冷。Switch 能否在 Hot Aisle 的特定足跡內供應 DLC、密度多少、成本多少、時程多久 —— **完全未知，而這是整份檔案中價值最高的未解問題**，見 §14 與 §15。

---

## 6. 硬體機隊

本節證據等級：**已確認**＝第一手具名揭露或多方獨立佐證｜**旁證**＝行為或第三方指向，但標的自身從未具名｜**GAP**＝查無｜**反證**＝證據與說法相反。

### 6.1 供應商證據等級

| 供應商／類別 | 證據等級 | 證據實際內容 |
|---|---|---|
| **Dell Technologies** | **已確認** | 證據壓倒性且多方。（1）[MI300X 頁](https://hotaisle.xyz/mi300x)：「Eight MI300X accelerators are available in each Dell PowerEdge XE9680.」（2）[pricing](https://hotaisle.xyz/pricing) 將「Dell XE9680 chassis」列為預設含括。（3）[networking](https://hotaisle.xyz/networking) 具名 Dell PowerSwitch Z9864F、Z9664F 與 Z9432F，並寫明「Dell ProSupport Next Business Day covers every switch.」（4）[partners](https://hotaisle.xyz/partners) 將 Dell Technologies 列於「Hardware systems and support」。（5）[Advizex 案例](https://www.advizex.com/case-studies/advizex-and-hot-aisle)：「Advizex deployed Dell PowerEdge XE9680 servers equipped with AMD MI300x GPUs.」（6）Jon Stevens 於 2024 年 11 月 SC24 在 Dell Technologies 攤位與 Dell 的 Saurabh Kapoor 同台。（7）其自家 [2024-09-13 現場札記](https://hotaisle.xyz/blog/cruising-to-the-finish-line/)：「one of the AMD MI300x GPUs went crazy and had a few loose screws. Dell immediately sent two technicians out to diagnose and fix it. **The level of support they are giving us is breathtaking.**」**最後這一項才是關鍵 —— 這份既有關係不只是合約，還帶著情感** |
| **AMD** | **已確認** | 唯一的加速器供應商，實質上也是品牌夥伴。每一頁的頁尾都寫著 **「AMD Exclusive AI Cloud」**。AMD 發表過專屬的 [NeoCloud 部落格](https://www.amd.com/en/blogs/2025/neocloud-hot-aisle-brings-the-heat.html)，並架設 [Hot Aisle 評估申請頁](https://www.amd.com/en/products/accelerators/instinct/eval-request/hot-aisle.html)。AMD 的 Jim Greene 於 2025 年 4 月在 AMD TechTalk podcast 訪問 Jon Stevens。[partners](https://hotaisle.xyz/partners) 將 AMD 列於「Accelerator platform」。兩個產品頁均為 AMD 專屬 |
| **Advizex**（Dell Titanium Solution Provider Partner）—— 整合商／通路 | **已確認** | Advizex 自家 [案例](https://www.advizex.com/case-studies/advizex-and-hot-aisle) 描述了與 Hot Aisle、Dell、Broadcom、Panduit 等進行的四個月每週規劃會議；解決方案架構、交付與導入服務、人員與人力支援、供應鏈整合；安全設備運送；以及動用 Advizex 當地辦公空間存放硬體元件。Hot Aisle 亦在 [partners](https://hotaisle.xyz/partners) 以「Deployment and lifecycle services」及首頁夥伴標誌列回應 |
| **Broadcom** | **已確認** | 列於 [partners](https://hotaisle.xyz/partners)「Networking and connectivity」與首頁標誌列，並在 [networking](https://hotaisle.xyz/networking) **以料號具名**：Broadcom 57608 dual-port 200G Q112 介面卡（每機殼八張）、Broadcom 57504 quad-port 10/25GbE、Broadcom 5720 dual-port 1GbE。亦被 Advizex 列為四個月規劃會議的參與者 |
| **Panduit**（機櫃、佈線、實體基礎設施） | **旁證 —— 不得陳述為事實** | **由 Advizex** 具名為四個月每週基礎設施規劃會議的參與者，與 Hot Aisle、Dell、Broadcom 並列。**Panduit 未列於 Hot Aisle 自家 Partners 頁，Hot Aisle 也未在任何地方具名任何 Panduit 料件。** 其在實際部署中的角色因此**可能為真但未確立**（[Advizex](https://www.advizex.com/case-studies/advizex-and-hot-aisle)） |
| **Switch, Inc.** | **已確認 —— 但身分是房東，不是硬體供應商** | 列於 [partners](https://hotaisle.xyz/partners)「Data center operations」；整個 [/datacenter](https://hotaisle.xyz/datacenter) 頁都在講 Switch Pyramid；Switch 代其核發年度再生能源憑證並退役 REC。**列於此處，是為了避免被誤算成硬體供應商** |
| **Supermicro** | **GAP —— 查無任何既有關係，正面或負面皆無** | **查無任何證據顯示 Hot Aisle 曾購買、評估、測試或公開提及 Supermicro。** Supermicro 未出現在其 Partners 頁、部落格、benchmark 參考索引、Advizex 案例，或 AMD 關於他們的 NeoCloud 貼文中。以「Hot Aisle」＋ Supermicro 的定向檢索只回傳無關的 Supermicro MI355X 產品頁。**這是真正的全新關係 —— 沒有既有陣地要守，也沒有過去的失單要克服。** 另須分別記錄，且**不得當成 Hot Aisle 的事實陳述**：AMD 自家內容在 AMD Instinct Coder 整合方案中提及 Supermicro AI 伺服器，可證 AMD–Supermicro 共同銷售確實存在 —— 這對「AMD 主導的聯合切入」是有用的背景，僅此而已 |
| **GigaIO** | **反證／無關係** | GigaIO 之所以在關鍵字檢索中浮現，只是因為一則無關的 [2024 年 11 月 GigaIO 產品公告](https://gigaio.com/2024/11/next-generation-edge-to-core-products-for-scale-up-ai-and-hpc-infrastructure/)。**Hot Aisle 任何地方都未提及 GigaIO，GigaIO 也未提及 Hot Aisle。** 明白記錄於此，是為了避免一則雜訊命中日後被誤當訊號 |
| **NVIDIA** | **反證 —— 刻意且完全的排除** | Hot Aisle 的整個品牌定位就是「AMD Exclusive AI Cloud」（每頁頁尾）。其 [2024 年貼文](https://hotaisle.xyz/blog/amd-groundbreaking-myths/) 為 AMD 辯護以對抗既有龍頭；其 [benchmark 索引](https://hotaisle.xyz/benchmarks-and-analysis/) 將 MI300X 對比 H100／H200。**機隊中沒有任何 NVIDIA 硬體，就證據看也沒有加入的意圖。任何以 NVIDIA 平台開場的提案，光是在品牌認同層面就會被拒絕** |

### 6.2 機隊清單與 Supermicro 對應

| 項目 | 內容 | 依據 | Supermicro 對應 |
|---|---|---|---|
| **GPU 運算節點 —— Dell PowerEdge XE9680，每機殼 8× AMD Instinct MI300X 192 GB HBM3 OAM** | **約 16 台機殼／約 128 顆 GPU。** 公司用語為「Our flagship 128 GPU MI300x bare metal cluster」；MI300X 頁寫「Eight MI300X accelerators are available in each Dell PowerEdge XE9680」。128 ÷ 8 = 16 台。每顆 GPU：192 GB HBM3、5.3 TB/s 頻寬、304 個運算單元、CDNA 3、256 MB Infinity Cache | 第一手（[現行](https://hotaisle.xyz/mi300x) 與 [2024 存檔](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)），並由 [Advizex 案例](https://www.advizex.com/case-studies/advizex-and-hot-aisle) 及 AMD NeoCloud 貼文佐證。**節點數是由公司自己的兩個數字相除得出，不是公司陳述** | **直接對應機種：[Supermicro AS-8125GS-TNMR2](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html)** —— 8U GPU A+ Server、8× AMD Instinct MI300X OAM、雙路 AMD EPYC 9005/9004（最高 400 W TDP）、24 條 DDR5 DIMM 最高 6 TB @ 6000 MT/s、前置 12 個熱插拔 2.5" NVMe（可擴至 16）另加 2 個 SATA 與 M.2 開機碟。**Supermicro eStore 標價 $275,863.87，現貨，3-5 個工作天出貨。** 注意可得性的對比：Supermicro 現貨 3-5 個工作天，對比 Dell XE9680 MI300X 組態在通路端為報價制、預估交期約 4 週。**對一家自述瓶頸是「取得產能的速度」的客戶而言，交期是活的差異化條件** |
| **每節點主機 CPU／記憶體／本地 NVMe** | **存在兩種不同的節點組態** —— 容易被忽略但很重要。裸機層宣傳「64 or 102 CPU Cores」、單 GPU VM 層「8 or 13 CPU Cores」、2/4 GPU 層「26 or 52 CPU Cores」。**每一層都出現「X or Y」的一致模式，代表機隊中存在兩種不同的主機 CPU SKU。** 每台裸機節點：2 TB 系統記憶體、122 TB NVMe。VM 層提供 224／448／896 GB RAM 與 12 TB NVMe | 第一手 [pricing 頁](https://hotaisle.xyz/pricing)，2026-08-11 現行。**「兩種組態」是由雙值模式推得的推論，非公司陳述** —— 但支撐力很強 | AS-8125GS-TNMR2 採雙路 EPYC 9004/9005，可涵蓋其兩種核心數，且可擴至 6 TB DDR5（現行為 2 TB），為更大的 KVM 承載留下餘裕。前置 16 個 NVMe 槽位可支撐其 122 TB 本地 NVMe 配置。**若他們確實在跑兩個主機世代，這就是可以明講的標準化痛點：** 下一批建置採用單一 Supermicro 平台 SKU，可把兩套備品池與兩條自動化路徑收斂成一套 |
| **運算網路網卡 —— Broadcom 57608 dual-port 200G，每台 XE9680 八張** | **每節點 8 張、3.2 Tbps、RoCEv2。** pricing 頁行銷用語為「8x400G networking — RoCEv2 for ultra-low latency clusters」 | 第一手，逐字取自 [networking](https://hotaisle.xyz/networking)：「Dell XE9680 chassis with eight Broadcom 57608 dual-port 200G Q112 adapters and Dell PowerSwitch Z9864F switching」 | Broadcom Thor2（57608）400G 等級介面卡在 Supermicro 的 OAM GPU 平台上均獲支援 —— **網卡選擇並非鎖定點，也不必更換。以此開場：他們在網路架構與 RoCEv2 調校上的投資可以完整沿用。** Broadcom 已經是 Hot Aisle 具名夥伴，因此「Supermicro ＋ Broadcom」的敘事對通路而言是一致的，而非破壞性的 |
| **乙太網路交換 —— Dell PowerSwitch Z9864F（運算）、Z9664F（叢集／儲存）、Z9432F（頻外管理），全部執行 SONiC** | 三個交換平面。運算網路走 Z9864F。東西向／儲存走 Z9664F，搭配 Broadcom 57504 quad-port 10/25GbE、100 Gbps。頻外管理走 Z9432F，搭配 Broadcom 5720 dual-port 1GbE、1 Gbps。可維修性：「Dell ProSupport Next Business Day covers every switch. The Z9864F has additional four-hour mission-critical coverage, backed by on-site replacement parts.」 | 第一手，逐字取自 [networking](https://hotaisle.xyz/networking) | **這是 Dell 陣地中黏著度最高的一塊，不應率先攻擊。** 他們在 Dell 硬體上跑 SONiC（開放 NOS），代表 NOS 可攜，即使機器不可攜。任何 Supermicro 交換器的討論，都必須追平或超越「每台交換器 NBD、脊層四小時關鍵任務、Grand Rapids 現場備品」—— **若做不到，第一筆生意就只談運算節點，不要碰交換器。在無法對等服務承諾的情況下攻擊交換層，正是輸掉這個案子的方式** |
| **下一世代目標平台 —— AMD Instinct MI355X，每系統 8 顆** | **尚未採購。** 每顆 288 GB HBM3E、8 TB/s 記憶體頻寬、**每顆 1,400 W**、八 GPU 組態合計 2.3 TB 記憶體、八顆 OAM 加速器以 AMD Infinity Fabric 網狀互連，採用**直接液冷**的「a deployable rack design」。逐字：「We are still raising the capital required to buy and deploy the hardware.」先前的登記實驗只收集到意向 | 第一手 [MI355X 頁](https://hotaisle.xyz/mi355x) 與 [investors](https://hotaisle.xyz/investors)。1,400 W 與 DLC 需求皆為其自行公布之數字 | **這才是真正的商機。** Supermicro 提供[氣冷式 10U 8× MI355X 系統](https://www.supermicro.com/en/pressreleases/supermicro-expands-its-portfolio-performance-and-efficiency-driven-air-cooled-ai)（2.3 TB HBM3E、第 5 代 EPYC、最高 72 核心）以及液冷版本，並設有具名的 [AMD MI355X JumpStart 方案](https://learn-more.supermicro.com/mi355x)。**若 Hot Aisle 租用的 Switch 足跡無法順利支援 DLC —— 或無法在其時程內支援 —— 氣冷式 8× MI355X 平台就能把一項機房相依性從其關鍵路徑上移除。** 這是能力論述而非折扣論述，也是現有最強的楔子 |
| **MI325X —— 刻意跳過（負面發現，訊號強）** | **零。** 從未部署或上架。其 2024 年 11 月存檔的 Cluster 頁寫過「AMD's MI300x (soon MI325x)」—— 但對 `hotaisle.xyz/mi325x*` 的 Wayback CDX 查詢**在整個典藏中回傳空集合**，且自 2024 年 6 月至 2026 年 7 月的任何一份定價快照中都未出現 MI325X | [Wayback CDX API](http://web.archive.org/cdx/search/cdx?url=hotaisle.xyz/mi325x&matchType=prefix)，負面結果，並與十二份定價快照交叉比對；[存檔之 cluster 頁](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/) | **策略上很重要：資金不到位時他們會跳過世代。他們的採購節奏由「資金」而非 AMD 的產品節奏決定。** 不要用 AMD 的產品路線圖日期做預測，要用他們的募資進度。同樣地，這也代表 MI355X 是一個**真正開放、未承諾的平台決策**，而不是既有 MI325X 陣地的汰換 |
| **軟體／維運堆疊**（非硬體，但對轉換成本具決定性） | NetBox 作為 DCIM 單一真實來源並有客製整合；自動化 SONiC 網路；PXE boot；自動化主機建置與作業系統；當前 ROCm 驅動；具 GPU 直通的 NUMA 平衡 KVM 虛擬機；Stripe 用量計費；終端 UI、API 與開源 Go CLI（[hotaisle-cli](https://github.com/hotaisle)）；一份 SkyPilot fork；dstack 作為 GPU 原生編排 | 第一手 [首頁](https://hotaisle.xyz/) 與 [networking](https://hotaisle.xyz/networking)，並由其公開 [GitHub 程式庫](https://github.com/hotaisle) 佐證 | **他們的自動化在設計上就是廠商中立的**（SONiC、PXE、cloud-init、KVM、NetBox）—— 這**實質降低了更換機殼供應商的成本**，也是「Supermicro 節點不是打掉重練」這個論點最好的依據。**要對 Clint Armstrong 明確量化這一點：會變的是 BMC／Redfish 端點與 NetBox 的硬體庫存範本，而不是整條供裝管線** |

---

## 7. GPU 型錄與 AI 佈局

**AMD 專屬、自助開通、無合約、以分鐘計費，且目前已售罄。** Hot Aisle 把每一個價格都公布在同一頁。截至 2026-08-11 的完整已查證型錄（[hotaisle.xyz/pricing](https://hotaisle.xyz/pricing)）：

| SKU | 價格 | 可得性 |
|---|---|---|
| **VM Small —— 1× AMD Instinct MI300X**（192 GB HBM3、8 或 13 CPU 核心、224 GB 系統記憶體、12 TB NVMe） | **每 GPU 每小時 $2.99**，以分鐘計費、隨用隨付、無合約 | 現可自助開通。**但公司自述產能 100% 滿載且有客戶排隊，實務上的可得性受限** |
| **VM Medium —— 2× 與 4× AMD Instinct MI300X**（384 GB 或 768 GB HBM3、26 或 52 CPU 核心、448 GB 或 896 GB RAM、12 TB NVMe） | **每 GPU 每小時 $2.99**，以分鐘計費 | 現可自助開通。同樣受 100% 滿載限制 |
| **Bare Metal Large —— 8× AMD Instinct MI300X 整台節點**（1.5 TB HBM3、64 或 102 CPU 核心、2 TB RAM、122 TB NVMe、Dell XE9680 機殼、完整 root／SSH／BMC／iDRAC 存取、8×400G RoCEv2、私有隔離網路、公有 IPv4＋IPv6） | **每 GPU 每小時 $3.39 ＝ 每節點每小時 $27.12。** **最短承諾一個月 —— 這是其整份型錄中唯一的承諾條款** | 現可經「Reserve Bare Metal」預約 —— 屬預約流程而非即時自助 |
| **既有客戶沿用的舊費率（grandfathered）** | **每 GPU 每小時 $1.99** —— 對仍有運算在跑的既有客戶無限期保留 | **自 2026-07-14 起對新客戶關閉**（[Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)） |
| **AMD Instinct MI355X —— 每系統 8 顆**（每顆 288 GB HBM3E、8 TB/s、每顆 1,400 W、每 8 GPU 系統合計 2.3 TB、直接液冷） | **未公布價格** | **無法取得 —— 尚未採購。** 逐字：「We are still raising the capital required to buy and deploy the hardware.」先前的登記實驗只收集到意向。第三方比價網站仍將 Hot Aisle 列為 MI355X 供應商（[getdeploying.com](https://getdeploying.com/gpus/amd-mi355x)）—— **研判該列表反映的是意向／候補而非已部署產能，應視為不可靠** |
| **AMD Instinct MI325X** | **從未提供** | **從未部署 —— 整個世代被跳過。** 2024 年 11 月的 cluster 頁預告過「soon MI325x」，但任何一份存檔快照中都未曾出現 MI325X 頁面或價格（[CDX 空集合](http://web.archive.org/cdx/search/cdx?url=hotaisle.xyz/mi325x&matchType=prefix)） |
| **Cluster Design & Deploy 顧問服務**（非 GPU 收入線） | **報價制，未公布** | 提供中 —— 以工作負載為起點的叢集設計，涵蓋運算、儲存、管理與公網路徑；歷史上亦包含機房／保險／網路合約的協商（[cluster](https://hotaisle.xyz/cluster/)；[2024 存檔](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)） |

**未提供：任何 NVIDIA SKU，任何價格，從來沒有。**

**判讀。** 從這份型錄可以讀出三件事。**（1）他們是賣光了而不是降價** —— 2026-07-14 的 $1.99 → $2.99 明確以「We are at 100% capacity」與「a queue of customers waiting for MI300X capacity」為理由。這與小型 neocloud 常見的搶使用率行為正好相反，也代表**其營收是被實體產能上限鎖死，而不是被需求鎖死。** **（2）裸機的一個月最短期是他們對任何人提出的唯一承諾要求** —— 一家連自己客戶都不願綁約的公司，對於被供應商綁住會極度過敏。**（3）MI355X 那一列就是整個商機的濃縮：** 一個規格完整、正在對外行銷、卻沒有價格、並附帶「仍在募資」聲明的產品。**那座建置案的平台還沒選定，而且他們已經公告全世界了。**

---

## 8. 採購時鐘

Hot Aisle 實際多久買一次硬體 —— 由存檔快照比對、登錄機構時戳與有日期的第一手貼文重建。

### 8.1 時間軸

| 日期 | 事件 | 來源 |
|---|---|---|
| **2023-10-18** | hotaisle.xyz 與 hotaisle.ai **相隔三秒**註冊（06:14:34Z 與 06:14:37Z），註冊商 Spaceship, Inc.。公司創立於 2023 年 10 月 | [RDAP](https://rdap.centralnic.com/xyz/domain/hotaisle.xyz) · [About](https://hotaisle.xyz/about/) |
| **2024-01-15** | **ARIN Org HA-716 登記** | [ARIN](https://rdap.arin.net/registry/entity/HA-716) |
| **2024-02-14** | **AS21566「HOTAISLE」核配**，並取得 23.183.40.0/24 與 2602:f955::/36。**網路先於硬體建置** | [ARIN](https://rdap.arin.net/registry/entity/HA-716) |
| **約 2024 Q2–Q3** | 與 Advizex、Dell、Broadcom、Panduit 進行**四個月的每週基礎設施規劃會議** | [Advizex](https://www.advizex.com/case-studies/advizex-and-hot-aisle) |
| **2024 年 9 月初** | **採購／部署事件 #1 —— 迄今唯一的一次機隊採購。** 約 16 台 Dell PowerEdge XE9680、約 128 顆 MI300X。日期依據 2024-09-13 的現場札記：「After a bit more than a week, we have fully deployed our own high-performance super computing cluster」—— 因此上架約始於 **2024-09-04** | [Cruising to the finish line](https://hotaisle.xyz/blog/cruising-to-the-finish-line/) |
| **2024-06-17 → 2024-11-14** | 價格持平於**每 GPU 每小時 $4.50**，單一 SKU | Wayback 定價快照 |
| **2024-12-14** | `/mi300x` 產品頁首度被存檔 | Wayback CDX |
| **2025-03-24** | 出現分層定價（**$2.00–$3.00**）並附「coming soon」 | Wayback 定價快照 |
| **2025-05-12** | 分層下探至 **$1.50** | Wayback 定價快照 |
| **2025-07-01／2025-09-18** | **SOC 2 Type 1**，隨後 **SOC 2 Type 2** | [gen.xyz](https://gen.xyz/blog/hotaisle-xyz) |
| **2025-07-25** | 定價收斂為單一 **$1.99／GPU／小時**。**這是十個月內 56% 的降價** —— 典型的「在已完全付清的自有機隊上追使用率」 | Wayback 定價快照 |
| **2025-09-30** | **`/mi355x` 頁首度被存檔** —— 下一世代目標公開宣示，**距首次建置十二個月** | Wayback CDX |
| **2026-05-18** | **$3.39 裸機層出現** | Wayback 定價快照 |
| **2026-07-14** | **轉折點。** 對新客戶**調價，自 $1.99 升至 $2.99**；**ARIN org 紀錄同日更新**；理由明載「We are at 100% capacity」與「a queue of customers waiting for MI300X capacity」 | [Why We Raised Our MI300X Price](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price) · [ARIN](https://rdap.arin.net/registry/entity/HA-716) |
| **2026-08（現況）** | **Investors 頁上線：明確為採購 MI355X 而募集 $50–100M** | [investors](https://hotaisle.xyz/investors) |

### 8.2 採購節奏

**三年內只有一次機隊採購 —— 而這就是全部的發現。**

這**不是週期性汰換型買家。** 節奏既非年度、也不跟 AMD 的產品節奏、更與折舊無關。證明就是被跳過的 MI325X 世代：2024 年 11 月預告，從未購入。**決定性變數是資金可得性**，而可觀察的觸發序列一致且可重複：

> **持續 100% 使用率 → 調漲價格 → 公開募資 → 採購**

這個序列在 2024 年跑過一次，通往 2024 年 9 月的建置。**現在它正在重跑，而且處在史上最後段的階段。**

**最近一次硬體採購：** 2024 年 9 月初（約 16 台 Dell XE9680／約 128 顆 MI300X，約一週內部署完成，由 Advizex 整合）。
**最近一次商業事件，也是最要緊的一件：** **2026-07-14**，以 100% 滿載與客戶排隊為由，把價格從 $1.99 調到 $2.99。
**最近一次策略事件：** Investors 頁上線、為 MI355X 募集 $50–100M —— 這就是本帳戶今天（2026-08-11）所處的位置。

### 8.3 下一個窗口

**現在就是開的，且只卡在一件事：$50–100M 募資案的交割。**

所有採購前置條件都已滿足且已由公司公開陳述 —— 100% 使用率、排隊中的客戶、超過 $50M 的 MI355X 需求、已完成的調價、三年生產實績、SOC 2 Type 2 與 HIPAA，以及明白宣示可採用股權、策略性投資**或 asset finance**。他們自己的話：**「The constraint is access to hardware, not demand for the platform.」**

**預估採購窗口：2026 下半年至 2027 上半年，觸發條件是募資交割，而非任何日曆日期。**

**應每週監看的領先指標：**
1. **[hotaisle.xyz/mi355x](https://hotaisle.xyz/mi355x) 上「We are still raising the capital required to buy and deploy the hardware」這句話消失，或該頁出現價格 —— 這是價值最高的單一警報線。**
2. AS21566 名下出現新的 ARIN 網段核配，或出現 PeeringDB 紀錄，代表第二個站點。
3. [hotaisle.xyz/datacenter](https://hotaisle.xyz/datacenter) 出現 Switch Pyramid 以外的機房名稱。
4. **Advizex 或 Dell 發布 MI355X 叢集相關訊息 —— 那代表窗口已對我方關閉。**
5. 出現提及 Mesh.xyz 或新策略投資人的募資公告。

**因為他們一次買整座叢集、而且會跳過世代，這是一個二元、高價值、只有一發的窗口 —— 錯過這次，下一次可能是兩年後。現在就要接觸，趕在募資交割之前**，因為平台決策是在為投資人建模型的當下做出的，不是在錢到位之後。

### 8.4 方法

以 [Wayback Machine CDX API](http://web.archive.org/cdx/search/cdx?url=hotaisle.xyz/mi325x&matchType=prefix) 依 URL 前綴查詢 `hotaisle.xyz/pricing`、`/mi300x`、`/mi355x` 與 `/mi325x`；接著以 `id_` 原始修飾詞逐份抓取快照、gzip 解壓，並以正規表示式掃描 GPU SKU 字串與金額。**在列舉出的 20 份中，12 份定價快照**產出乾淨的價格與 SKU 序列；各 GPU 產品頁的首次出現日期則界定每個世代的公開登場時點；**`/mi325x` 的空 CDX 結果就是「跳過世代」的立論基礎。** 並與有日期的第一手部落格貼文、ARIN RDAP 的登記與最後異動時戳、網域 RDAP 建立時間交叉驗證。**所有日期都帶有存檔或登錄機構的時戳；沒有任何一個是從文字敘述推測而來。**

**信心水準：** 對「僅一次採購」與 2026-07-14 轉折點為**高**（兩者皆有存檔與登錄機構時戳，來自兩個獨立面）。對 MI325X 跳過為**高**（整個典藏的空 CDX 結果是強力負面證據）。對前瞻窗口為**中**，因為它取決於一次由公司自行宣布、無法事前觀測的募資交割。

---

## 9. UCC 融資紀錄

**本軌研究範圍：** Hot Aisle Inc. —— 研判設立於懷俄明州（依 ARIN 與 D&B 之法人地址），擔保品所在地為密西根州（伺服器位於 Grand Rapids 的 Switch Pyramid）。

### 9.1 判定

> ### UNVERIFIED — portal blocked

**請完全照字面理解。** **未取得任何 UCC-1、修正、讓與、續期或終止文件，因此本檔不報告任何一筆。** 沒有申報編號、申報日期、失效日期、擔保權人姓名與地址、債務人姓名與地址，也沒有擔保品描述，**因為在任何一個候選設立州別中，都沒有任何一套 UCC 索引能被觸及。** §9.3 的空白代表**什麼都沒看到**，**不代表** Hot Aisle 沒有擔保債務。此結果不得對客戶陳述、不得引用給徵信單位、也不得以「查無留置權」寫入 CRM。**此處的阻擋是程序性的，不是資產負債表乾淨的證據。**

### 9.2 查詢紀錄 —— 一次嘗試一列，不合併

| 入口／索引 | URL | 預定或實際送出的查詢字串 | 逐字回應 |
|---|---|---|---|
| **懷俄明州 SOS — UCC Search**（依 ARIN 與 D&B 的 Cheyenne 地址，為研判之設立州別） | [wyobiz.wyo.gov/UCC/UCCSearch.aspx](https://wyobiz.wyo.gov/UCC/UCCSearch.aspx) | 債務人精確比對 `HOT AISLE INC` 與前綴比對 `HOT AISLE`。**從未執行 —— 搜尋表單始終無法抵達** | **以 curl 取得 HTTP 200，但回應主體是 F5／Shape 的機器人防禦 JavaScript 挑戰，不是搜尋表單。** 改以真實瀏覽器重試：頁面呈現變形圖形 CAPTCHA，逐字為 *「This question is for testing whether you are a human visitor and to prevent automated spam submission. What code is in the image? submit. Your support ID is: 11385417910158787977.」* **本檔未嘗試破解該 CAPTCHA** |
| **懷俄明州 SOS — Business Filing Search**（法人查詢入口） | [wyobiz.wyo.gov/Business/FilingSearch.aspx](https://wyobiz.wyo.gov/Business/FilingSearch.aspx) | 法人名稱 `HOT AISLE`。**從未執行** | **完全相同的 CAPTCHA 挑戰，support ID 11385417910158757353** |
| **懷俄明州 — 備用主機**（作為備援探測五個） | `uccsearch.wyo.gov` · `sosbiz.wyo.gov` · `uccfiling.wy.gov` · `ucc.wyo.gov` · [sos.wyo.gov/Business/UCC.aspx](https://sos.wyo.gov/Business/UCC.aspx) | 同上債務人字串。**皆未執行** | `uccsearch.wyo.gov` → **連線失敗（curl exit code 000）** · `sosbiz.wyo.gov` → **000** · `uccfiling.wy.gov` → **000** · `ucc.wyo.gov` → **HTTP 302 轉址回受 CAPTCHA 保護的 wyobiz 主機** · `sos.wyo.gov/Business/UCC.aspx` → **HTTP 404** |
| **密西根州 LARA**（實體擔保品所在州 —— 伺服器位於 Grand Rapids 的 Switch Pyramid） | [cofs.lara.state.mi.us](https://cofs.lara.state.mi.us/CorpWeb/CorpSearch/CorpSearch.aspx) 與 `cofs.lara.state.mi.us/UCC/UCCSearch.aspx` | `HOT AISLE`。**從未執行** | **連線始終未完成。** curl verbose 逐字：*「Connected to cofs.lara.state.mi.us (172.64.144.107) port 443 / TLS handshake, Client hello (1) / LibreSSL/3.3.6: error:1404B410:SSL routines:ST_CONNECT:sslv3 alert handshake failure / Closing connection」*。DNS 解析為 `cofs.lara.state.mi.us.cdn.cloudflare.net`（104.18.43.149、172.64.144.107），**因此這是 Cloudflare 邊緣的機器人防護在拒絕該 TLS 指紋。** 改以 `--tlsv1.2 --tls-max 1.2` 重試 → **HTTP 000**；以 `-k`（略過驗證）重試 → **HTTP 000**；`ucc.lara.state.mi.us` → **000**；`/SearchApi/Search/Search` 端點以 GET 與 POST（JSON body）嘗試 → **回傳空** |
| **德拉瓦州 Division of Corporations — ICIS 法人查詢** | [icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx](https://icis.corp.delaware.gov/ecorp/entitysearch/NameSearch.aspx) | **已執行一次。** 於欄位 `ctl00$ContentPlaceHolder1$frmEntityName` 輸入 `HOT AISLE` 並送出一次 | **頁面載入成功（HTTP 200，48,338 bytes）。逐字回應：在輸入框旁以黃底反白顯示 *「An error occurred while processing the request」*，FILE NUMBER／ENTITY NAME 結果表為空。** 同一頁載有告示 *「The Division of Corporations strictly prohibits mining data… Use of automated tools in any form may result in the suspension of your access to utilize this service」*，**因此僅執行一次查詢，未重試** |
| **德拉瓦州 UCC** | [services.sos.delaware.gov](https://services.sos.delaware.gov/) | 債務人 `HOT AISLE INC`。**從未執行** | **本環境取得 HTTP 000。** 另需獨立說明：**德拉瓦州根本不提供免費公開的線上 UCC 債務人名稱索引** —— 該州 UCC 查詢採訂購制 —— **因此即使連線未受阻，也不會產生自助式的德拉瓦 UCC 結果** |
| **OpenCorporates**（聚合站備援） | [opencorporates.com/companies?q="Hot Aisle"](https://opencorporates.com/companies?q=%22Hot+Aisle%22) | `"Hot Aisle"`。**從未執行** | **HAProxy CAPTCHA 挑戰頁，抓取與瀏覽器皆是** |
| **Bizapedia**（聚合站備援） | [bizapedia.com/search.aspx?q=hot+aisle](https://www.bizapedia.com/search.aspx?q=hot+aisle) | `hot aisle`。**從未執行** | **拖曳式人機驗證挑戰** |
| **CorporationWiki**（聚合站備援） | [corporationwiki.com/search/results?term=Hot Aisle](https://www.corporationwiki.com/search/results?term=Hot%20Aisle) | `Hot Aisle`。**從未執行** | **HTTP 403** |
| **OpenGovUS**（聚合站備援，兩州） | `opengovus.com/wyoming-business?q=Hot+Aisle` 與 `.../michigan-business` | `Hot Aisle`。**從未執行** | **HTTP 404 ——「File not found.」** |

### 9.3 已在案之申報 —— 每筆完整列出

**取得之申報筆數：0。**

下方沒有申報區塊，因為**沒有任何一個查詢面回傳過任何一筆申報。** 沒有任何內容被壓縮、簡寫或摘要省略 —— 登記簿根本沒被觸及。因此，做徵信或通路決策所需的每一個逐筆欄位，都是明確的 GAP：

| 所需之逐筆欄位 | `HOT AISLE INC`（WY，研判之設立州） | `HOT AISLE INC`（MI，擔保品所在州） |
|---|---|---|
| 申報編號 | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |
| 申報日期 | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |
| 失效日期／續期狀態 | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |
| 擔保權人姓名＋地址 | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |
| 債務人姓名＋申報地址 | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |
| 擔保品描述（逐字） | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |
| 修正／讓與／終止 | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |
| 紀錄連結 | **GAP —— 登記簿從未觸及** | **GAP —— 登記簿從未觸及** |

**補齊此缺口的行動：** 委託人工辦理 **UCC-11 債務人查詢，債務人為 `HOT AISLE INC`**，範圍涵蓋**懷俄明州**（研判之設立州）**與密西根州**（擔保品所在地），可透過公司資料查詢商或直接向懷俄明州務卿申請；並調閱**懷俄明州 certificate of good standing**，以確定設立州別、法人編號與註冊代理人。務必編列別名表單預算 —— `HOT AISLE INC`、`HOT AISLE, INC.`、`HOT AISLE` —— 因為精確比對式索引會讓單一表單的查詢變成一個等著發生的偽陰性。

### 9.4 推論

**請將此視為「附帶強烈先驗判斷的證據缺口」，並把該先驗當成通話時要去驗證的假設 —— 絕不可當成查證結果。**

**公司自己對資金來源的說法屬直接證據，不依賴任何 UCC 索引。** [investors 頁](https://hotaisle.xyz/investors) 載明正在募集 $50–100M，來源為「equity、strategic investment，**and asset finance**」，且「The capital will purchase AMD MI355X systems and fund the networking, rack integration, and site deployment.」**把 ASSET FINANCE 與股權並列為獨立的第三條路徑，是本次研究中所能取得最具證明力的資金訊號**，指向他們正在考慮擔保式硬體融資 —— 而該融資若實際執行，將產生一筆以伺服器為擔保品的 UCC-1。

**至於 2024 年的建置，存在一個同樣合理的競爭解釋。** 他們自創立起即由 Mesh.xyz（Joseph Lubin 的孵化器）支持；兩位創辦人來自 W3BCloud，在該公司運行過 150,000 顆 AMD GPU；2024 年的 cluster 頁還誇稱「Our deep relationships with vendors will ensure you get the best pricing」與「you can harness supercomputer-grade resources without the hefty CapEx」（[2024-11-14 存檔](https://web.archive.org/web/20241114101217/https://hotaisle.xyz/cluster/)）。這與股權出資購買、透過 Dell Financial Services 的原廠融資，或由 Advizex 安排的供應鏈結構皆相容 —— **而上述任一種都可能產生、也可能不產生申報紀錄。**

**商業上的意涵，也就是真正要緊的部分。** 因為下一座叢集的資金機制確實尚未確定，而客戶又公開表示 asset finance 在考慮之列，**融資結構就是一個開放的槓桿，而不是既定的限制。請把 Supermicro 的租賃／融資選項帶進第一次對話。** 同時同樣重要：**不得斷言、暗示或影射他們是舉債經營或已設定擔保** —— 那並未經證實，把它當事實陳述既錯誤又具殺傷力。

---

## 10. 成本天花板

一台 Hot Aisle GPU 節點對他們值多少，以及同等機器今天要花多少錢。**本節只回答一個問題：硬體成本要低到多少，一台 8 GPU 節點才划得回來？**

### 10.1 假設 —— 請先讀這一段；這些是假設，不是查證發現

**這是一個明確以假設驅動的模型，不是查證所得的事實。** 只有公布的價格是有來源的；營運成本佔比與回收期都是假設，並以區間呈現。

**有來源，非假設：** 三個公布價格點（裸機 $3.39、新客戶 VM $2.99、既有客戶 $1.99 —— [pricing](https://hotaisle.xyz/pricing)，2026-08-11 讀取）；8 GPU 節點組態；裸機最短一個月；100% 滿載的陳述；以及由 2025 年退役 781 張 REC 推得的約 90 kW 平均機房負載（781 MWh ÷ 8,760 小時），並以 2024 年 267 張 REC 分攤約四個實際運轉月交叉檢核。

**是假設，無來源：**（1）**營運成本佔營收 35–55%** —— 涵蓋 Switch 主機代管的電力與空間、Switch Connect 與 Megaport 的傳輸、Dell ProSupport、Stripe 金流手續費、工程與支援人力、管銷，以及他們沒有業務團隊這一點 —— 因此有 45–65% 的營收可用於支應硬體；**公司完全未揭露任何成本資料。**（2）**回收期 12／18／24 個月。**（3）以牌價維持 100% 滿載，無折扣、無免費額度、無故障節點 —— **這個假設偏寬鬆，而他們歷史上確實提供過免費運算方案。**（4）每月 730 小時、每年 8,760 小時。（5）不計入叢集設計顧問業務的收入。（6）回收期末不計殘值。（7）**融資成本以零計，若他們採用 asset finance，這會低估真實天花板。**

### 10.2 由租金推導之每 8 GPU 節點天花板

滿載下的每節點毛收入：

| 費率 | 每節點每小時 | 每節點每月（730 小時） | 每節點每年（8,760 小時） |
|---|---|---|---|
| **裸機 $3.39／GPU／小時** | **$27.12** | **$19,798** | **$237,571** |
| **新客戶 VM $2.99／GPU／小時** | **$23.92** | **$17,462** | **$209,539** |
| **既有客戶 $1.99／GPU／小時** | **$15.92** | **$11,622** | **$139,459** |

在 35–55% 營運成本區間下，每 8 GPU 節點的硬體成本天花板：

| 回收期 | 以裸機費率計 | 以新客戶 VM 費率計 | **混合工作區間（每節點）** | **每 GPU** |
|---|---|---|---|---|
| **12 個月** | $107k – $154k | $94k – $136k | **約 $95k – $155k** | **$12k – $19k** |
| **18 個月** | $160k – $232k | $141k – $204k | **約 $140k – $230k** | **$18k – $29k** |
| **24 個月** | $214k – $309k | $189k – $272k | **約 $190k – $310k** | **$24k – $39k** |

**敏感度警告。** 一旦使用率跌破 100%，上述數字會迅速崩解；而**他們自己的歷史就是十個月內降價 56%（$4.50 → $1.99）來追使用率，且是在需求跟上之前**（§8）。**對這個客戶而言，24 個月回收期的假設偏激進；以 12–18 個月為框架來談判比較安全。** 以上全部是模型輸出，不是公司揭露。

### 10.3 BOM 重建 —— 雙向對照

**（a）DELL —— 既有路線。無任何公開的市場價格。** Dell PowerEdge XE9680 搭 8× AMD Instinct MI300X 為**報價制**。最接近的公開對照是 Uvation Marketplace，其刊登了該組態（兩顆第 4 代 Intel Xeon Scalable，各最高 56 核心；32 條 64 GB DDR5 4800 MT/s；8× MI300X 以 Infinity Fabric 互連；最高 8 個 2.5" NVMe 至 122.88 TB），標示 **「Estimated Delivery 4 Weeks」但不顯示價格**，並要求聯絡業務以 PO 方式取得報價。**本檔因此不報告任何 Dell 價格，而不是自行估一個。**

**（b）SUPERMICRO —— 對應機種，而且有公開價格。**

| 項目 | 內容 | 價格 | 來源 |
|---|---|---|---|
| **Supermicro AS-8125GS-TNMR2** | 8U GPU A+ Server、8× AMD Instinct MI300X OAM、雙路 AMD EPYC 9005/9004 最高 400 W TDP、24 條 DDR5 DIMM 最高 6 TB @ 6000 MT/s、前置 12 個熱插拔 2.5" NVMe（可擴至 16）另加 2 個 SATA 與 M.2 開機碟。**現貨，3-5 個工作天出貨** | **$275,863.87** | [Supermicro eStore](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html) |
| 通路交叉檢核 | Dihuni 就同一平台標示 **$281,548.48**，可佐證量級。**但該頁在直接抓取時回傳 HTTP 307 轉址迴圈，因此此數字僅為搜尋浮現，未於原頁查證** | *$281,548.48（未於原頁查證）* | 僅搜尋浮現 |

**可比性警語：** $275,863.87 是**起始價**。Hot Aisle 的實際規格 —— 2 TB RAM、122 TB NVMe、八張 Broadcom 57608 200G 介面卡 —— 會定在**高於**基本款的價位。

### 10.4 對照結論，以及這對報價的意義

**$275,864／節點 ＝ 每 GPU $34,483。** 對照 §10.2 的租金推導區間：

- **12 個月回收（$95k–$155k）：** **差距極大，不成立。**
- **18 個月回收（$140k–$230k）：** **不成立。**
- **24 個月回收（$190k–$310k）：** **只有在營運成本假設最省的一端才勉強過關。**

**報價結論：牌價在任何合理的回收期下都無法成交。** 能成交的是**（i）** 大幅折讓後的**交付到位總價**，約需壓到**每節點 $230k 以下**才能達到 18 個月回收；以及／或**（ii）** **把問題從「回收期」轉成「每月現金支出」的融資方案** —— 這正是他們自己點名 asset finance 之所以重要的原因（§9.4）。

**把交期對比帶進會議室。** 現貨 3-5 個工作天，對比 Dell 通路端約 4 週的報價交期 —— 而這個客戶自述的唯一限制就是取得產能的速度。**對這位買家而言，交期就是價格：** 一台 8 GPU 節點每閒置一週，以 $3.39／GPU／小時計，就是**約 $4,550 的未計費產能**（8 × $3.39 × 168 小時 ＝ $4,556）。

**最後，也很重要：2026–27 年真正的決策標的是 MI355X 而不是 MI300X，而兩家廠商都查無任何公開的每節點 MI355X 市場價格。** 上述 BOM 對照是錨定在前一世代。**這仍是一個未解缺口**（§15）。

---

## 11. 客戶與網路

### 11.1 客戶

| 關係 | 等級 | 來源實際內容 |
|---|---|---|
| **700+ 客戶（總量，未具名）** | **已確認為公司陳述 —— 未經審計** | 公司陳述兩次：[首頁](https://hotaisle.xyz/) 的「700+ customers served」與 [investors](https://hotaisle.xyz/investors) 的「more than 700 customers … Customers around the world have used the platform for compute without procurement drag」。自助、刷卡、無合約的模式，因此客群是**長尾的開發者與新創，而不是少數大型客戶。網站上任何地方都沒有具名的客戶標誌牆 —— 這是刻意的** |
| **dstack**（GPU 編排廠商） | **已確認 —— 最強的具名關係** | 列於 [partners](https://hotaisle.xyz/partners)「GPU-native orchestration」。共同貼文 [Orchestrating AMD GPUs with dstack](https://hotaisle.xyz/blog/gpu-orchestration-with-dstack)（2026-03-02）。dstack 在 Hot Aisle 提供的硬體上發表了「Exploring inference memory saturation effect: H100 vs MI300x」與「Llama 3.1 405B on 8x MI300X」（[dstack.ai](https://dstack.ai/blog/h100-mi300x-inference-benchmark/)）。dstack 創辦人在 hotaisle-website 程式庫中亦有 commit。**同時扮演夥伴、背書者與通路三種角色** |
| **Red Hat（Neural Magic）** | **已確認** | 共同貼文 [Computing for All: Hot Aisle + Red Hat (Neural Magic) + AMD](https://hotaisle.xyz/blog/hot-aisle-red-hat-neural-magic-amd-open-ai-inference-mi300x)（2025-05-15），主題為 MI300X 上的開放 AI 推論。**顯示有企業級推論驗證工作跑在其機隊上** |
| **Dr. Moritz Lehmann —— FluidX3D CFD** | **已確認** | Hot Aisle [貼文](https://hotaisle.xyz/blog/dr-moritz-lehmann-linkedin-hot-aisle-8x-amd-mi300x-fastest-fluidx3d-cfd)（2025-03-03），引述 205 GLUPs/s 與 23 TB/s VRAM 頻寬。**獨立研究者在其硬體上跑真實工作負載** |
| **SemiAnalysis** | **須加註 —— 屬分析／測評關係，不是商業客戶** | [SemiAnalysis 的 MI300X vs H100 vs H200 研究](https://newsletter.semianalysis.com/p/mi300x-vs-h100-vs-h200-benchmark-part-1-training) 在支援開源 MI300X 測評的業者中提到 Hot Aisle（與 TensorWave、Nebius、Lambda、Sustainable Metal Cloud 並列），Hot Aisle 也在自家參考索引中列出 SemiAnalysis |
| **警告 —— benchmark 參考索引不是客戶名單** | **明確記為警語** | Hot Aisle 的 [benchmarks-and-analysis 頁](https://hotaisle.xyz/benchmarks-and-analysis/) 收錄約 20 個第三方來源，包含 Oracle Cloud、Nscale、RunPod、Fireworks.ai、Chips and Cheese、Anthracite 的 Magnum 72B、AMD Community 的 MLPerf 貼文與若干 Reddit 討論串。**這些是關於 MI300X 的外部策展參考，不是 Hot Aisle 的客戶。** 明白記錄於此，是為了避免這份清單日後被當成標誌牆來挖。**只有 dstack、Red Hat／Neural Magic 與 Moritz Lehmann 有證據顯示確實在 Hot Aisle 自家硬體上運行** |

### 11.2 網路 —— AS21566

- **登錄：** **AS21566**，ARIN 代號 **HOTAISLE**，ASN 範圍 21566-21566，狀態 **Active**，於 **2024-02-14T11:05:57-05:00** 登記於 Org HA-716。**IP 資源：** IPv4 **23.183.40.0/24**（NET-23-183-40-0-1，「HA-4-10」，Active）；IPv6 **2602:f955::/36**（NET6-2602-F955-1，「HA-SOPH」，Active）。**Org 紀錄最後異動 2026-07-14 —— 與公開調價同一天。** 注意其不對稱：**單一 /24（256 個位址）與單站點的中小型足跡相符，而 /36 的 IPv6 則偏大且具前瞻性**，與其宣稱的 IPv6 優先設計與多站點企圖一致（[ARIN](https://rdap.arin.net/registry/entity/HA-716)）。
- **三個實體分離的平面**，全部以料號具名（[networking](https://hotaisle.xyz/networking)）：
  - **運算網路：** RoCEv2，**每節點 3.2 Tbps**，經每台 Dell XE9680 上的八張 Broadcom 57608 dual-port 200G Q112 介面卡，交換於 Dell PowerSwitch **Z9864F**（pricing 頁行銷為「8x400G networking」）。
  - **叢集服務／東西向／儲存：** **100 Gbps**，經 Broadcom 57504 quad-port 10/25GbE，交換於 Dell PowerSwitch **Z9664F**。
  - **管理平面：** **1 Gbps 頻外管理**，經 Broadcom 5720 dual-port 1GbE，交換於 Dell PowerSwitch **Z9432F**。
- **對外網路：** 經 **Switch Connect** 與 **Megaport** 的 **100G** 連線；每台裸機伺服器與 VM 均含公有 IPv4 與 IPv6。
- **設計：** IPv6 優先定址、VRF 隔離、全網自動化 SONiC。
- **可維修性：** **每一台**交換器皆有 Dell ProSupport Next Business Day，Z9864F 另有**四小時關鍵任務等級，並由現場備品支援。**
- **Peering：無。** [PeeringDB API 查詢](https://www.peeringdb.com/api/net?name__contains=Hot%20Aisle) 回傳空的 data 陣列。他們**未進駐任何網際網路交換中心**、未公布 peering 政策，除單一 ARIN 職務帳號外也未列出任何 NOC 或 peering 聯絡人。**連線是採購而來，不是對等互連** —— 這與「做推論服務的主機代管租戶」而非「網路業者」的定位完全一致。**意涵：這個帳戶沒有 peering 社群的切入路徑；唯一的網路聯絡窗口是 netops@hotaisle.xyz。**

---

## 12. 政治與公開紀錄

僅限公開紀錄。每一列均加註標籤。只列具名主事者。**查無者即明白寫出：經確認的「FEC 查無紀錄」是一項查證發現，不是遺漏 —— 並且全篇與「未能取得」（屬 GAP）嚴格區分。**

### 12.1 公開紀錄之政治獻金

| 對象 | 查得內容 | 金額＋日期 | 受款方 | 標籤 | 來源 |
|---|---|---|---|---|---|
| **Clint Armstrong** —— Co-Founder／Head of Engineering | **以雇主「HOT AISLE」、職業「ENGINEER」申報之個人捐款**，捐款人城市／州為**新罕布夏州 Grantham**。以 WinRed 為在案受款委員會，指定捐給特定眾議院選舉。**這是全 FEC 個人捐款資料庫中唯一一筆以「Hot Aisle」為雇主的紀錄**，也是**他在任何雇主名下唯一一筆在案捐款**（姓名＋州查詢回傳 count=1，精確）。由此衍生的兩項次要事實，在操作上比政治傾向本身更有用：**它獨立佐證了他在 Hot Aisle 的雇傭關係，並把他定位在新罕布夏州，而不是密西根州** | **2024-06-22 · $50.00。** Form F3X，2024 年第 2 季報告；交易編號 AA27C49AC2D984DBBBB1；影像 202407159656410321；檔號 1800865；捐款人年初至今累計 $50.00 | **WINRED（C00694323）** 為在案受款委員會；收款類型 **「EARMARKED FOR LILY4CONGRESS COMMITTEE（C00800458）」** —— 亦即最終受益者是 **Lily Tang Williams** 於**新罕布夏州第 2 選區**的眾議員選舉 | **公開紀錄** | [FEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_employer=HOT+AISLE) · [FEC 影像 202407159656410321](https://docquery.fec.gov/cgi-bin/fecimg/?202407159656410321) |
| **Jon Stevens** —— Founder & CEO · **經前東家比對之身分歸屬，見但書** | 四筆 **2016 年**逐筆申報為 STEVENS, JON —— **加州舊金山** —— 雇主 **GEARLAUNCH** —— 其中三筆職業填「MR」、一筆填 **「CO-FOUNDER」**，全部經 ActBlue 指定捐給 Bernie Sanders 2016 總統選舉。**身分認定但書：申報文件中並未出現 Hot Aisle。** 比對依據為（a）姓名、（b）舊金山、（c）雇主 **GearLaunch**（Hot Aisle 的 Jon Stevens 有獨立佐證確為其共同創辦人）、（d）職業 CO-FOUNDER。其於 Hacker News 列出的個人網域 ridecontrol.xyz 之登記人州別為加州，與舊金山一致。**依據強，但非確定；他名下不存在任何載有 Hot Aisle 的申報** | **2016-02-10 $50.00**（影像 201603209010551932）；**2016-03-06 $50.00 與 $50.00**（影像 201702069043313679）；**2016-03-09 $50.00**（導管影像 201702069043313679；同一筆 $50 亦出現在 Bernie 2016 自家報表影像 201606149017659439，其職業於該處填為 CO-FOUNDER）。**合計約 $200** | **ACTBLUE（C00401224）** 為在案導管委員會；備註文字 **「EARMARKED FOR BERNIE 2016（C00577130）」** —— 最終受益者為 **BERNIE 2016**，即 Bernard Sanders 的主要競選委員會 | **公開紀錄**（申報文件本身為公開紀錄並逐字引用）；**歸屬於 Hot Aisle 之 Jon Stevens 一節屬「有佐證但不確定」** | [FEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=STEVENS%2C+JON&contributor_state=CA&contributor_city=SAN+FRANCISCO) |
| **「STEVENS, JON」，加州舊金山** —— **可能但無法確認為同一人** | 兩筆 **2020 年**紀錄：STEVENS, JON —— 加州舊金山 —— 雇主 **SELF** —— 職業 **FABRICATOR**，經 ActBlue 指定捐給 Bernie Sanders 2020 選舉。**職業「FABRICATOR」與科技創業者不符**，且與 GearLaunch 或 Hot Aisle 無雇主關聯。予以記錄而非隱去，但**明確不歸屬於 Hot Aisle 的 CEO** | **$50.00 加上 $5.00 的 ActBlue 小費，皆為 2020-03-10**（影像 202004219230161073） | **ACTBLUE（C00401224）**；備註「EARMARKED FOR BERNIE 2020（C00696948）」 | **未經查證** | [FEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=STEVENS%2C+JON&contributor_state=CA&contributor_city=SAN+FRANCISCO) |
| **「STEVENS, JON」，華盛頓州 Entiat** —— **由前一輪保留；僅為可能歸屬** | 一筆 2020 年紀錄：STEVENS, JON · 華盛頓州 Entiat 98822 · 職業 **DIRECTOR OF IT** · 雇主 **W3BCLOUD** —— 其有據可查的前東家。**歸屬依據為雇主相符，並因自陳職業「Director of IT」與 Founder/CEO 不符而減弱。** **排除項，特此載明以免日後被誤當命中：** 僅以姓名於密西根州查詢回傳 27 筆，經核為**另一人**（Farmington, MI 的 Jon Stevens，職業與雇主皆為「NOT EMPLOYED」）；僅以姓名於華盛頓州查詢回傳 **2,091 筆**，絕大多數是一位高頻小額捐款人 Jonathan Stevens，無法與他連結。**上述皆不歸屬於他** | **2020-09-19 · $25.00** | **ACTBLUE（C00401224）**；備註「EARMARKED FOR MCGRATH FOR US SENATE（C00711549）」 | **公開紀錄 · 僅為可能歸屬 · 不得歸屬密西根或華盛頓的大量結果** | [FEC W3BCLOUD 查詢](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Stevens%2C+Jon&contributor_employer=W3BCLOUD) |
| **Jon Stevens —— 以 Hot Aisle 雇主查詢** | **查無紀錄。這是一項查證發現，不是遺漏。** FEC `schedule_a` 以 `contributor_employer` 查「HOT AISLE」（1 筆，僅 Armstrong）、「HOT AISLE INC」（0）、「HOT AISLE INC.」（0）、「HOTAISLE」（0）、「HOTAISLE.XYZ」（0）、「SELF - HOT AISLE」（0）；並以 `contributor_name`「STEVENS, JON」／「STEVENS, JONATHAN」交叉雇主 HOT AISLE 過濾（0）。以雇主含「AISLE」做寬鬆萬用字元查詢回傳 1,250 筆，**全部屬無關公司**（Aisle 518 Strategies、AisleLogic、Aisle Rocket、Across the Aisle） | 不適用 | 不適用 | **gap** | [FEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_employer=HOT+AISLE) |
| **Hot Aisle Inc.** —— 企業 PAC／獨立分離基金（SSF） | **查無紀錄。** FEC 委員會查詢 `q="hot aisle"` 回傳 **count 0**。Hot Aisle Inc. **從未向 FEC 登記任何 connected PAC、SSF、hybrid PAC、super PAC 或其他委員會** | 不適用 | 不適用 | **公開紀錄（經確認之負面結果 —— 委員會登記庫完整且具權威性）** | [FEC 委員會查詢](https://api.open.fec.gov/v1/committees/?q=hot+aisle) |
| **懷俄明州競選財務**（登記地址所在州） | **未能取得。** 懷俄明競選財務入口網站有回應，但其捐款查詢是**ASP.NET postback 表單**，無法自本環境以程式查詢；懷俄明州務卿的商業／申報入口則位於 **F5／Shape 機器人防護**之後，未予破解。**應據以調整期待的背景說明：** 懷俄明僅是**私人信箱地址（PMB 41293）**，兩位有據可查的主事者都不住在該州 —— Armstrong 的 FEC 申報把他放在新罕布夏州 Grantham，Stevens 的線索指向加州舊金山 —— 因此這兩人出現懷俄明州層級捐款的可能性，表面上就很低。**記為 gap，而非「查無紀錄」** | 不適用 | 不適用 | **gap** | [wycampaignfinance.gov](https://www.wycampaignfinance.gov/WYCFWebApplication/GSF_SystemConfiguration/SearchContributions.aspx) |
| **密西根州競選財務**（機房所在州）**與新罕布夏州**（Armstrong 居住州） | **未能取得。** 密西根競選財務系統（`cfs.sos.state.mi.us`）自本環境無法解析／連線，密西根 LARA 商業入口位於 Cloudflare 挑戰之後。**新罕布夏州競選財務本輪未觸及。** 記為 gap | 不適用 | 不適用 | **gap** | [cfs.sos.state.mi.us](https://cfs.sos.state.mi.us/) |

#### 受贈機構 —— 沿革、政治傾向與負責人

| 機構 | 類型 | 沿革 | 政治傾向（＋證據） | 負責人 | 負責人姓氏語源（onomastic） | 來源 |
|---|---|---|---|---|---|---|
| **[WINRED](https://api.open.fec.gov/v1/committee/C00694323/)**（FEC 委員會 C00694323） | **Hybrid PAC，附非捐款帳戶（Nonqualified）**，designation 為 Unauthorized。實務上運作為**共和黨官方線上捐款處理導管** —— 與 ActBlue 對應的共和黨版本。FEC 地址 1603 Capitol Avenue, Cheyenne, WY 82001；法遵信箱 COMPLIANCE@CROSBYOTT.COM；網站 win.red。**注意：該街道地址與 Hot Aisle 登記之 PMB 地址相同，而此一巧合不代表兩者之間有任何關係 —— 見 §3 第 2 列** | 首次 FEC 申報 **2019-01-18**；2019 年公開上線，作為共和黨官方支付平台，由 **Revv**（2014 年 12 月成立的共和黨支付處理公司）與該黨的 **DataTrust** 選民資料庫合併而成。創辦人暨負責人為 **Gerrit Lansing**，先前任共和黨全國委員會（RNC）數位長，更早於 2012 年在 RNC 數位部門，再更早曾任眾議院預算委員會新聞秘書與 Rep. Peter Roskam（IL）的新媒體主任。活躍於 2020、2022、2024 與 2026 週期；最近一次 Form 1 申報於 2026-04-10 | **共和黨／保守派。** 明確設立為共和黨官方支付平台，並獲 RNC 背書；**經由其流出的每一筆指定捐款都流向共和黨候選人與委員會。** 在本檔案中，Armstrong 該筆捐款的 FEC 收款類型寫作「EARMARKED FOR LILY4CONGRESS COMMITTEE」，而 FEC 將該委員會編碼為 `party_full = REPUBLICAN PARTY`。Ballotpedia、Wikipedia 與 InfluenceWatch 皆將其描述為共和黨的募款平台 | **Gerrit Lansing** —— 創辦人暨總裁。**Benjamin Ottenhoff** —— 依現行 FEC Form 1 為財務長暨紀錄保管人（在案姓名「OTTENHOFF, BENJAMIN」） | **LANSING：** Forebears 引《Dictionary of American Family Names》（1956，Elsdon Coles Smith）—— 英格蘭語源，「One who came from Lancing (people of Wlenca), in Sussex」；另一說引《An Etymological Dictionary of Family and Christian Names》（1857，William Arthur），為荷蘭地形語源，指低平沖積地，「ing」意為草地。今日以美國分布最多。**OTTENHOFF：** Forebears **未收錄**任何語源釋義（「The meaning of this surname is not listed」）。就分布而言以**荷蘭**最多（383 人，約 1/44,092），全球 75% 的持有者位於西歐／日耳曼語區，21% 在美國；全球總數約 521 人 | [FEC C00694323](https://api.open.fec.gov/v1/committee/C00694323/) · [Wikipedia](https://en.wikipedia.org/wiki/WinRed) · [Ballotpedia](https://ballotpedia.org/WinRed) · [InfluenceWatch](https://www.influencewatch.org/for-profit/winred/) · [Forebears: Lansing](https://forebears.io/surnames/lansing) · [Forebears: Ottenhoff](https://forebears.io/surnames/ottenhoff) |
| **[LILY4CONGRESS COMMITTEE](https://api.open.fec.gov/v1/committee/C00800458/)**（FEC 委員會 C00800458） | **主要競選委員會，眾議院。** 在案政黨：**REPUBLICAN PARTY**。地址 PO Box 406, Weare, NH 03281；網站 lilytangwilliams.com；信箱 LILY4CONGRESS@LILYTANGWILLIAMS.COM 與 TREASURER@LILYTANGWILLIAMS.COM | 首次 FEC 申報 **2022-01-11**。為候選人 **Lily Tang Williams**（FEC 候選人代號 H2NH02260）之授權主要競選委員會，共和黨籍，參選**新罕布夏州第 2 選區**，在案選舉年為 2022、2024 與 2026。**Armstrong 2024 年 6 月的捐款落在其 2024 年週期** | **共和黨／保守派。** FEC 將該委員會編碼為 `party_full = REPUBLICAN PARTY`，候選人 WILLIAMS, LILY TANG 編碼為 REPUBLICAN PARTY、眾議院、NH 第 02 選區。其資金經由**共和黨專屬導管 WinRed** 進入。**捐款人地理位置一致：Grantham, NH 就在 NH-02 選區內** | **Lily Tang Williams** —— 候選人（FEC 候選人代號 H2NH02260）。**John Charles Williams** —— 依 FEC Form 1 為財務長暨紀錄保管人（在案姓名「WILLIAMS, JOHN CHARLES」）。此類主要競選委員會的 FEC 紀錄中未另列主席或執行長 | **WILLIAMS：** 由名字 William 衍生的父名式姓氏；最早可溯至中世紀英格蘭，但**該姓氏的主要來源是威爾斯**，當地多數姓氏約在 1500 至 1800 年間定型，取代了「Owain ap William」（William 之子 Owain）這類父名形式。今日以美國最多。**TANG：** Forebears 記載此姓以**中國**的分布多於其他任何國家或地區，並列為**全球第 37 常見**的姓氏；Forebears 上的釋義條目屬使用者提交而非學術引註，**本檔不予採信** | [FEC C00800458](https://api.open.fec.gov/v1/committee/C00800458/) · [FEC 候選人連結](https://api.open.fec.gov/v1/committee/C00800458/candidates/) · [Forebears: Williams](https://forebears.io/surnames/williams) · [Forebears: Tang](https://forebears.io/surnames/tang) |
| **[ACTBLUE](https://api.open.fec.gov/v1/committee/C00401224/)**（FEC 委員會 C00401224） | **Hybrid PAC，附非捐款帳戶（Nonqualified）**，designation 為 Unauthorized；實際運作為**導管／指定捐款平台**。地址 PO Box 962017, Boston, MA 02196；網站 secure.actblue.com；信箱 TREASURER@ACTBLUE.COM | 首次 FEC 申報 **2004-05-17**；2004 年由 **Benjamin Rahn** 與 **Matt DeBergalis** 創立，作為民主黨候選人與委員會的線上捐款處理導管。經營沿革：**Erin Hill** 領導該組織約十四年；**Regina Wallace-Jones** 於 **2023 年 1 月**接任，為 ActBlue 史上第四位負責人。2023–2024 週期申報處理金額達 **38 億美元**。2026 年該組織與其執行長成為**眾議院行政委員會（House Committee on House Administration）**調查與往來函件的對象（函件日期 2026-04-14 與 2026-04-23），該執行長並於 2026-06-10 於《華盛頓郵報》投書表示將於國會行使第五修正案權利 | **民主黨／進步派。** ActBlue **僅**為民主黨候選人、委員會與進步派組織處理捐款。本檔自身的 FEC 查詢即直接佐證：經 C00401224 流向 **BERNIE 2016**（C00577130）、**BERNIE 2020**（C00696948）、HARRIS FOR PRESIDENT（C00703975）、HARRIS VICTORY FUND（C00744946）、DEMOCRATIC NATIONAL COMMITTEE（C00010603）、ALEXANDRIA OCASIO-CORTEZ FOR CONGRESS（C00639591）、JON OSSOFF FOR SENATE、WARNOCK FOR GEORGIA 與 SLOTKIN FOR CONGRESS 的指定捐款 | **Regina Wallace-Jones** —— 總裁暨執行長（2023 年 1 月上任；2026 年 4 月與 6 月的國會往來函件與媒體報導中仍以執行長身分出現）。**George Gilmer** —— 依現行 FEC Form 1 為財務長暨紀錄保管人（在案姓名「GILMER, GEORGE」）。**創辦人：Benjamin Rahn 與 Matt DeBergalis（2004）** | **WALLACE：** Forebears 記載此姓一向被認為表示其原始持有者來自威爾斯；蘇格蘭最早的持有者據稱是隨 Stewart 家族自威爾斯邊界附近的 Shropshire 而來的追隨者。今日以美國最多。**JONES：** 父名式姓氏，意為 John、Johan 或 Jone 之子；13 至 14 世紀「Johan」男女通用，其後分化為 John／Jon 與 Joan／Jone。全球第 **208** 常見；以美國最多。**GILMER：** 源自蓋爾語 *Gille Moire*，意為「（聖母）瑪利亞的僕人」；Forebears 記載一位 Gilander 之子 Gilmor，於 1133 至 1156 年間在 Cumberland 郡 Walton 教區創建 Treverman（今 Trierman）小教區。今日以美國最多。**2004 年兩位創辦人的姓氏 Rahn 與 DeBergalis 本輪未查 —— GAP** | [FEC C00401224](https://api.open.fec.gov/v1/committee/C00401224/) · [ActBlue 公告](https://www.actblue.com/posts/introducing-regina-wallace-jones/) · [Wikipedia](https://en.wikipedia.org/wiki/ActBlue) · [Forebears: Wallace](https://forebears.io/surnames/wallace) · [Forebears: Jones](https://forebears.io/surnames/jones) · [Forebears: Gilmer](https://forebears.io/surnames/gilmer) |
| **[BERNIE 2016](https://api.open.fec.gov/v1/committee/C00577130/)**（FEC 委員會 C00577130） | **主要競選委員會，總統選舉。** 在案政黨：**DEMOCRATIC PARTY**。地址 PO Box 391, Burlington, VT 05402；網站 berniesanders.com；信箱 COMPLIANCE@BERNIESANDERS.COM | 首次 FEC 申報 **2015-04-30**，即 Bernard Sanders 投入 2016 年民主黨總統初選之時。候選人代號 **P60007168**。**這是上文歸屬於 Jon Stevens 的四筆 2016 年 ActBlue 指定捐款的最終受益者** | **民主黨／進步派（位於民主黨中間線之左）。** FEC 將該委員會編碼為 `party_full = DEMOCRATIC PARTY`、designation 為「Principal campaign committee」，候選人 P60007168 Bernard Sanders 於 2016 年以明確的民主社會主義政綱競逐民主黨總統提名。其資金經由**民主黨專屬導管 ActBlue** 進入 | **Bernard Sanders** —— 候選人（FEC 候選人代號 P60007168）。**Susan Jackson** —— 依 FEC Form 1 為財務長暨紀錄保管人（在案姓名「JACKSON, SUSAN」） | **SANDERS：** 父名式姓氏，意為「Alexander 之子」，源自中世紀暱稱 Saunder；Forebears 引 13 世紀 Hundred Rolls 之例，如 Alisandre／Sandre de Leycestre（倫敦，1273）與 Thomas fil. Saundre（Northamptonshire）。全球第 1,539 常見，82% 的持有者在美洲。**JACKSON：** 由祖先名字衍生，意為「John 之子」，源自流行暱稱 Jake 或 Jack；Forebears 引 Robert fil. Jake（Cambridgeshire，1273，Hundred Rolls）與 Johannes Jakson（1379 年約克郡人頭稅冊）。全球第 383 常見；以美國最多 | [FEC C00577130](https://api.open.fec.gov/v1/committee/C00577130/) · [Forebears: Sanders](https://forebears.io/surnames/sanders) · [Forebears: Jackson](https://forebears.io/surnames/jackson) |
| **[BERNIE 2020](https://api.open.fec.gov/v1/committee/C00696948/)**（FEC 委員會 C00696948） | **主要競選委員會，總統選舉。** 在案政黨：**DEMOCRATIC PARTY**。地址 P.O. Box 391, Burlington, VT 05402；網站 www.berniesanders.com；信箱 COMPLIANCE@BERNIESANDERS.COM | 首次 FEC 申報 **2019-02-19**，即 Bernard Sanders 投入 2020 年民主黨總統初選之時；**候選人代號與 2016 年委員會同為 P60007168**。**列入本表僅因它是上文兩筆 2020 年舊金山紀錄（標籤為「未經查證」）的最終受益者 —— 該兩筆並未歸屬於 Hot Aisle 的 CEO** | **民主黨／進步派（位於民主黨中間線之左）。** FEC 編碼為 `party_full = DEMOCRATIC PARTY`、designation 為「Principal campaign committee」，候選人 P60007168 Bernard Sanders，總統選舉。資金經由 ActBlue 進入 | **Bernard Sanders** —— 候選人（P60007168）。**Lora Haggard** —— 依 FEC Form 1 為財務長暨紀錄保管人（在案姓名「HAGGARD, LORA」） | **HAGGARD：** Forebears 引《The Surnames of Scotland》（1946，George Fraser Black），記載 1723 年於 Stitchill 對 Isobel Hagger 提出之求償，並指出該姓於 13 世紀的 Suffolk 以 Hacgard 形式出現；另一說給出盎格魯－法語／條頓語意「lean; wild」（源自法語 *hagard*，或經中古高地德語）。全球第 42,207 常見，87% 的持有者在美洲，以美國人數最多。**SANDERS：** 見上方 Bernie 2016 條目 | [FEC C00696948](https://api.open.fec.gov/v1/committee/C00696948/) · [Forebears: Haggard](https://forebears.io/surnames/haggard) · [Forebears: Sanders](https://forebears.io/surnames/sanders) |
| **MCGRATH FOR US SENATE**（C00711549）—— 保留之 W3BCloud 紀錄的最終受益者 | **主要競選委員會，參議院** | **本輪未做機構側寫 —— GAP。** 指向它的那一列本身僅屬「可能歸屬」，因此未依上述五個委員會的標準研究該受贈機構 | **GAP —— 本輪未研究** | **GAP** | **GAP —— 因未辨識出負責人，故未進行任何姓名學考據** | [FEC W3BCLOUD 查詢](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Stevens%2C+Jon&contributor_employer=W3BCLOUD) |

#### 遊說（Lobbying）

**查無紀錄 —— 而且這是對權威登記庫查得的確認負面結果，不是 GAP。** **Hot Aisle Inc. 沒有任何形式的聯邦《遊說揭露法》（LDA）登記，無論是作為登記人或作為客戶。** 已就 `client_name` = 「hot aisle」、「hot%20aisle」、「hotaisle」、「Hot Aisle Inc」，以及 `registrant_name` 同樣四種寫法，查詢參議院公開紀錄辦公室的 LDA API。**八次查詢全部回傳 `{"count":0,"results":[]}`。** LDA 資料庫是完整的聯邦登記庫，因此這是真實的負面結果：**沒有 LD-1 登記、沒有 LD-2 季度活動報告，因此任何期間的申報支出皆為 $0**（[參議院 LDA API](https://lda.senate.gov/api/v1/filings/?client_name=hot+aisle)）。**OpenSecrets 上也不存在該公司的組織頁面** —— 這與前述結果一致而非矛盾，因為 OpenSecrets 的組織遊說檔案是由 LDA 申報衍生而來，零申報的公司自然不會有檔案（[LDA clients 端點](https://lda.senate.gov/api/v1/clients/?client_name=hot+aisle)）。**懷俄明、密西根與新罕布夏三州的州層級遊說登記本輪未查詢 —— 該子問題為 GAP。**

*姓氏語源僅為公開姓名學資料之語源考據，並非對任何個人族裔或血統之查證陳述。政治獻金為公開紀錄，不等於政黨登記。*

**給銷售專員的操作結論。** 兩位主事者在案的捐款**方向相反** —— Armstrong 是單筆、載明雇主的 $50，經 WinRed 捐給共和黨眾議院選舉；Stevens 則（很可能）是 2016 年間合計約 $200，經 ActBlue 捐給民主黨總統初選 —— 且**兩者金額都小到顯示雙方都談不上政治投入。** 就公司本身而言，以任何權威指標衡量都是**政治上完全不活躍**：沒有 PAC、沒有任何形式的委員會、沒有聯邦遊說、沒有任何申報支出。**這裡沒有可用來建立共鳴的共同政治框架，反而有在一家兩人公司內部踩到斷層線的實質風險。這個帳戶上不要談政治，任何方向、任何時點都不要。**

**查無任何法案或政策立場** —— 無論是公司或其主事者。在政治與公共政策這條軸線上，Hot Aisle 幾乎沒有公開足跡：沒有可用的切入點，也沒有風險 —— **前提是根本不要提起這個話題。**

---

## 13. 公開聯絡管道

僅限公開來源。**本節不列任何個人手機號碼與私人住址，亦未進行相關蒐集。** 無公開管道者標示為 GAP。

| 管道 | 內容 | 來源 |
|---|---|---|
| **公司主要信箱 —— 他們明確邀請的正門** | **hello@hotaisle.ai** —— 注意是 **.ai** 網域，不是 .xyz。其 contact 頁寫明「A person on the Hot Aisle team will reply directly. No AI bot, and no spam.」，並依主題分流為 *Compute and deployment*、*Customer support*、*Partnerships and growth*。**對硬體供應商而言，正確的窗口是「Partnerships and growth — Discuss infrastructure partnerships, deployment opportunities, or the next location for sovereign inference capacity」** | [hotaisle.xyz/contact](https://hotaisle.xyz/contact) |
| CEO 直接信箱（公開於 git commit metadata） | **jon@hotaisle.xyz** —— 出現在 hotaisle-cli 的 commit 作者欄位。**合法且公開，但屬開發者導向；請先用 hello@hotaisle.ai，若無回應再以此跟進** | [hotaisle-cli commits](https://api.github.com/repos/hotaisle/hotaisle-cli/commits) |
| 網路維運（ARIN 已驗證） | **netops@hotaisle.xyz** · **+1-646-389-2009** —— ARIN POC NETOP393-ARIN，承擔 Admin、Tech、NOC、Abuse、DNS 與 Routing。646 為紐約區碼，既不符懷俄明登記地址、也不符任一創辦人已知所在州，**研判為 VoIP／轉接。這是維運信箱；不得在此陌生開發** | [ARIN Org HA-716](https://rdap.arin.net/registry/entity/HA-716) |
| **投資人／募資窗口 —— 目前意向強度最高的入站路徑** | Investors 頁設有「Discuss the raise」與「Discuss the opportunity」的行動呼籲，並以「A conversation, not a campaign. Let's build a verifiably secure sovereign inference cloud.」作結。**鑑於他們正在股權之外尋求 asset finance，供應商融資的對話正是這條路徑的正當且受歡迎的用途** | [hotaisle.xyz/investors](https://hotaisle.xyz/investors) |
| LinkedIn —— 公司與兩位主事者 | 公司：[linkedin.com/company/hotaisle](https://www.linkedin.com/company/hotaisle) · Jon Stevens：[linkedin.com/in/jon-s-stevens](https://www.linkedin.com/in/jon-s-stevens/) · Clint Armstrong：[linkedin.com/in/clint-armstrong](https://www.linkedin.com/in/clint-armstrong/)。**Stevens 發文活躍，是回應性較高的公開存在** | [About](https://hotaisle.xyz/about/) |
| X／Twitter | **@hotaisle**（公司）。Jon Stevens 的 GitHub 個人檔案也列出 `twitter_username: hotaisle`，因此該公司帳號實質上就是他本人 | [GitHub jon-hotaisle](https://api.github.com/users/jon-hotaisle) · [gen.xyz](https://gen.xyz/blog/hotaisle-xyz) |
| **GitHub —— 本帳戶技術可信度最好的管道** | [github.com/hotaisle](https://github.com/hotaisle) —— 9 個公開程式庫，含 hotaisle-cli（Go）、hotaisle-website（TypeScript）、cloud-init-templates、SkyPilot fork，以及 apt／rpm／homebrew 套件庫。帳號為 **jon-hotaisle** 與 **clint-hotaisle**。**在這裡做實質互動（提出有用的 issue 或 PR，不是行銷），對 Clint Armstrong 的效果會勝過任何一封信** | [github.com/hotaisle](https://github.com/hotaisle) |
| **溫暖引介路徑（依優先順序）** | **1）AMD Instinct／neocloud 現場團隊** —— Hot Aisle 自稱「AMD Exclusive AI Cloud」，AMD 也架設了 [Hot Aisle 評估申請頁](https://www.amd.com/en/products/accelerators/instinct/eval-request/hot-aisle.html)；**由 AMD 主導的聯合切入是最強的開場。** **2）Advizex** —— 既有整合商；**應以潛在合作對象而非取代目標的姿態接觸。** **3）dstack** —— 具名夥伴，且有網站程式庫的 commit 權限，是可信的同儕聲音。**4）Broadcom** —— 已是 Hot Aisle 具名夥伴且為共同元件供應商，因此「Supermicro ＋ Broadcom」的敘事對通路是一致的 | [partners](https://hotaisle.xyz/partners) |
| 登記地址 —— **郵件代收信箱，不得前往或寄送** | 1603 Capitol Ave, Ste 415, PMB 41293, Cheyenne, WY 82001。**這是註冊代理人的私人信箱，不是辦公室。** Hot Aisle 在任何地方都沒有可拜訪的辦公室；唯一的實體存在是密西根州 Grand Rapids、Switch Pyramid 園區內的租用機櫃空間，需 Switch 陪同、武裝警衛核可與生物辨識通行 | [ARIN](https://rdap.arin.net/registry/entity/HA-716) · [datacenter](https://hotaisle.xyz/datacenter) |
| 業務直撥電話 | **GAP —— 未公布，而且是刻意的。** 公司明白標榜「no sales calls」 | — |

---

## 14. Supermicro 銷售切入點

### 分類：**針對下一世代的全新切入（GREENFIELD DISPLACEMENT）**

**不是既有客戶防守 —— 我們沒有既有陣地。也不是平台轉換 —— 不要叫他們拆掉一座正在運作的 128 GPU MI300X 叢集。**

誠實的判讀：**Dell 擁有既有機隊，而且擁有得理所當然。** Hot Aisle 公開讚揚 Dell 為了一顆螺絲鬆脫的 GPU 派出兩名工程師，並稱其支援「breathtaking」（[2024-09-13](https://hotaisle.xyz/blog/cruising-to-the-finish-line/)）。這支機隊搶不到，也不該去搶。**真正開放的是下一座叢集** —— MI355X 建置案：未採購、未取得資金，而且關鍵在於**那是一個他們從未部署過的世代**，因此沒有 MI325X 陣地造成的標準化慣性。他們已經因為資金因素跳過一個世代，這證明**平台決策在每個週期都會重新打開。**

### 讓這個案子可打的五項事實

1. **產能 100% 滿載、有客戶排隊，而且因此剛把價格從 $1.99 調到 $2.99** —— 瓶頸不是需求（[pricing](https://hotaisle.xyz/pricing)；[調價貼文](https://hotaisle.xyz/blog/why-we-raised-our-mi300x-price)）。
2. **他們宣稱有「超過 5,000 萬美元的 MI355X 產能需求」**，並說「**The constraint is access to hardware, not demand for the platform**」（[investors](https://hotaisle.xyz/investors)）。
3. **他們正明確為了「purchase AMD MI355X systems and fund the networking, rack integration, and site deployment」募集 $50–100M，並把 ASSET FINANCE 列為三條路徑之一** —— 融資是開放槓桿，不是既定限制。
4. **他們的 MI355X 頁面直白寫著「We are still raising the capital required to buy and deploy the hardware」** —— 平台尚未鎖定，即使 Advizex 的案例寫著他們會與 Advizex 一起建 MI355X 叢集。**整合商的承諾 ≠ 機殼的承諾。**
5. **他們的自動化在架構上就是廠商中立的** —— SONiC、PXE、cloud-init、NUMA 平衡 KVM、NetBox 單一真實來源 —— 因此轉換成本是 **BMC／Redfish 端點與 NetBox 範本，不是打掉重寫。這一點要直接對 Clint Armstrong 講明：那是他會提出的疑慮，也是我們真的答得出來的那一個。**

### 技術楔子 —— 比任何折扣都強

他們自己的 MI355X 頁面載明**每顆加速器 1,400 W**，採**直接液冷**的「a deployable rack design」。**他們是 Switch Pyramid 的主機代管租戶 —— 並不掌握散熱系統。** 若 DLC 在其租用足跡內無法取得、容量受限或供裝緩慢，**他們整個 MI355X 計畫的關鍵路徑上就掛著一個機房相依性。**

Supermicro 在液冷版本之外，另有**氣冷式 10U 8× MI355X 系統**（2.3 TB HBM3E、第 5 代 EPYC、最高 72 核心，[新聞稿](https://www.supermicro.com/en/pressreleases/supermicro-expands-its-portfolio-performance-and-efficiency-driven-air-cooled-ai)）。**對一家資金吃緊、且公開表示硬體取得是唯一瓶頸的公司來說，把一項房東相依性從關鍵路徑上移除，是能力論述而不是價格論述 —— 這也是他們願意接受這場會議的最好理由。**

### 第二個楔子 —— 對這位買家而言，交期就是價格

Supermicro 的 8× MI300X 平台顯示為**現貨、3-5 個工作天出貨**（[eStore](https://store.supermicro.com/us_en/8u-gpu-superserver-as-8125gs-tnmr2.html)）；Dell XE9680 MI300X 路線是**報價制，通路端預估交期約四週**，**而且他們第一次建置還先跑了四個月的規劃會議。** 對一家營收被實體產能鎖死、客戶還在排隊的公司來說，幾週的交期直接換算成流失的營收。**用他們自己公布的價格量化：一台 8 GPU 節點每閒置一週，以 $3.39／GPU／小時計，就是約 $4,550 的未計費產能。**

### 第三個楔子 —— 可重複的單位經濟

他們自述的擴張模式是「smaller inference-focused sites」「compact, repeatable inference deployments」，並以「existing automation」讓每個站點上線而「without rebuilding the process at every site」（[investors](https://hotaisle.xyz/investors)）。**他們買的不是一座叢集，而是一套打算在各區域複製的範本。贏下一次參考設計，就贏下標準。第一個節點的價格與結構要照這個邏輯來設計。**

### 首次接觸的唯一資格問題

> **「就 MI355X 這個建置案，Switch 是否已經確認你們 Pyramid 足跡內的直接液冷容量與供裝時程？如果 DLC 延後、或無法達到你們需要的密度，氣冷式 8× MI355X 平台能否讓部署維持在時程上？」**

就問這一句。這是真實的維運問題、一句話就能回答、尊重他們「不談銷售」的文化、**能立刻揭露機房是否為瓶頸**，並把 Supermicro 定位在能力面而非價格面。

**若第一題有進展，才追加的第二題：** *「在這輪募資的模型裡，你們對 MI355X 節點假設的交付到位單價與回收期是多少？」* —— 這會直接讓成本天花板浮上檯面，而不是靠猜（§10）。

### 怎麼開場，以及絕對不要怎麼做

**要做：** 盡可能**走 AMD Instinct／neocloud 現場團隊** —— 他們自稱「AMD Exclusive AI Cloud」，AMD 已為其發布 NeoCloud 貼文與評估申請頁，而**GPU 配額是我們單靠自己無法供給的稀缺投入。** 把 **Supermicro AMD MI355X JumpStart 方案**當成第一個具體步驟：以評估為先、自主推進，正好對應一家公開發布社群 benchmark 且拒絕銷售通話的公司。以**工程師對工程師的口吻、用純文字**書寫。

**不要做：** 以 benchmark 主張開場 —— **他們的 MI300X 數據比我們好**，且公開策展了二十個第三方測評來源。 · 要求他們汰換正在運作的 MI300X 叢集。 · 在第一筆生意中提議更換 Dell PowerSwitch／SONiC 網路 —— **Dell ProSupport NBD 覆蓋每一台交換器，Z9864F 另有四小時關鍵任務等級與現場備品，我們無法輕率超越。第一筆生意就限縮在運算節點，不要碰交換器。** · 貶低 Dell 或 Advizex —— **那份關係真實、溫暖且有公開紀錄，攻擊它只會顯得不了解他們的歷史。** · 送出裸機報價：**任何報價都必須含 L11/L12 機櫃整合、預置、Grand Rapids 物流與現場備品，因為 Advizex 交付的是一座上好架、能運作的叢集；一台裸機在完整度上必輸，不論單價多低。**

### Rule 8 —— 經銷通路注意事項（接觸前必讀）

**這個帳戶必須透過授權通路推進，而且在這個案子上這不是形式問題，而是具體風險。** 在談任何價格之前：

**（a）** 對 Hot Aisle Inc. 執行**夥伴／商機註冊查核**，確認沒有既存的有效註冊。**CRM 已於 2026-08-11 實查為乾淨**（salesleads Search，Type = All：無 lead、無 account、無 do-not-call）—— **但 CRM 乾淨不等於通路乾淨。**
**（b）** **在首次實質接觸之前就選定並註冊授權經銷商／整合商**，因為這位客戶買的是整合交付的叢集而不是機殼；未經註冊的直接接觸，最終一定會與必須負責交付的那個夥伴撞在一起。
**（c）** **不得在經銷商報價旁邊或之下提出直接報價**，也不得讓 AMD 主導的聯合切入變成繞過已註冊夥伴的後門。
**（d）** **對 Advizex 要特別謹慎處理** —— 他們是 Dell Titanium Solution Provider，也是既有的整合商。若打法是把他們拉到 Supermicro 平台上，**那必須透過正式通路流程設計，不能在客戶對話中臨場即興。**
**（e）** **註冊前先確認轄區。** **資料中心在密西根州（Chicago Area = T1，一組可直接註冊）**，但法人登記地在**懷俄明州 Cheyenne**，兩位決策者看來分別位於**新罕布夏州與華盛頓州**。**僅以密西根機房地址註冊，日後可能因法人所在地而被挑戰** —— 因此**註冊當下就要把密西根生產據點作為 T1 主張的依據記錄下來，並主動把 WY／NH／WA 的分歧告知通路營運單位，不要等它在案子上線後才變成爭議。**

**順序 —— 不得調換：** ① 釐清通路／經銷商歸屬並完成夥伴註冊（Rule 8）→ ② 以密西根生產據點註冊此 lead（T1）→ ③ 經 AMD 或 hello@hotaisle.ai 接觸，只問上述那一個資格問題。

---

## 15. 查證附錄

### 15.1 單一來源或模型推導之說法（引用前須再驗證）

| 說法 | 唯一來源／依據 | 風險 |
|---|---|---|
| **約 16 台節點／128 顆 GPU** | 公司自述「128 GPU cluster」÷ 每台 XE9680 八顆 GPU | **這個除法是本檔做的，不是公司說的。** 已由約 90 kW 的電力推導獨立佐證，因此在電力上說得通 —— 但**他們可能自 2024 年 9 月以後又增購而未對外宣布**，而定價層中可見的兩種主機 CPU 組態正暗示了這一點 |
| **平均總負載約 90 kW；IT 負載約 70–80 kW** | 由公布的 REC 退役量（2025 年 781 張、2024 年 267 張）以 1 REC = 1 MWh 推導 | **本檔的計算，非公司揭露。** 兩個獨立年度收斂，這點令人安心，但從總負載換算到 IT 負載的 PUE 步驟，用的是 Switch「low PUE」的行銷說法，並無公布數值 |
| **營收年化 $2.2M–$3.8M** | 僅以公開牌價所做的「價格 × 產能 × 使用率」模型 | **模型輸出。該公司從未公布過營收、ARR、毛利或成本資料。** 且假設以牌價 100% 滿載、無折扣與免費額度 |
| **成本天花板區間與「每節點 $230k 可達 18 個月回收」** | §10 模型 | **建立在假設的 35–55% 營運成本佔比與假設的回收期上。兩者都不是查證所得的事實** |
| **兩種不同的主機 CPU 組態** | 每一定價層都出現的「X or Y」核心數模式 | **由模式推得的推論，不是公司陳述** —— 雖然支撐力不弱 |
| **Panduit 出現在實際部署中** | 僅由 Advizex 具名，且身分是規劃會議參與者 | **旁證。Panduit 不在 Hot Aisle 的 Partners 頁上，Hot Aisle 也未具名任何 Panduit 料件。不得陳述為事實** |
| **Jon Stevens 的 FEC 紀錄（W3BCloud、ActBlue、$25）** | FEC 姓名＋雇主比對 | **僅為可能歸屬。** 職業「Director of IT」與 Co-Founder/CTO 不符。**在任何情況下都不得把密西根或華盛頓的大量結果歸屬於他** |
| **Andrey Cheptsov ＝ GitHub `peterschmidt85`** | 公開上已廣為人知的帳號對應 | **並非 Hot Aisle 所述。** 身分對應屬旁證；dstack 的夥伴關係本身則已確認 |
| **Dihuni 的 Supermicro 價格 $281,548.48** | 僅由搜尋浮現 —— **該頁直接抓取時回傳 HTTP 307 轉址迴圈** | 僅可佐證量級；**未於原頁查證** |
| **比價網站將 Hot Aisle 列為 MI355X 供應商** | [getdeploying.com](https://getdeploying.com/gpus/amd-mi355x) | **不可靠 —— 研判反映的是候補意向而非已部署產能。公司自己說硬體還沒買** |
| **懷俄明為設立州別** | ARIN 地址 ＋ D&B 收錄，兩者都指向註冊代理人的 PMB | **推論。未取得任何登記文件。不得將設立州別陳述為事實** |

### 15.2 第三方資料的分歧與未解之處

**員工數**

| 來源 | 數字 |
|---|---|
| D&B 商業名錄 | **1–10** |
| LinkedIn | **1–10** |
| 公司自家 About 頁 | **恰好 2 位具名人員** |
| GitHub 組織 | **「no public members」；2 個 hotaisle 網域 committer** |

**評估而非結論：** 各來源一致，但全部是自報或自行推導的區間。**任何引用都須標註為「第三方估計」。** 真正的佐證是結構性的 —— 六種角色共用一個 ARIN 信箱、查無職缺、Advizex 明載提供「personnel and staff augmentation」。

**法人名稱寫法**

| 來源 | 寫法 |
|---|---|
| 網站頁尾 | **「Hot Aisle, Inc.」** |
| ARIN POC org 欄位 | **「Hot Aisle Inc」** |
| ARIN Org 紀錄 | **「Hot Aisle Inc.」** |

**未解，且對銷售本身不重要，但對 UCC 或登記查詢很重要** —— 精確比對式索引意味著三種字串都應查。

**Jon Stevens 的創始職稱**

| 來源 | 職稱 |
|---|---|
| 公司 About 頁、AMD、Advizex | **Co-Founder & CEO** |
| 部分第三方檔案 | **CTO** |

**本檔採 Co-Founder & CEO** —— 那是公司自家現行用語，且有 AMD 與 Advizex 佐證。

### 15.3 未結 GAP

1. **設立州別未確認。** 任何一州皆未取得公司登記文件。懷俄明僅由 ARIN Org 地址與 D&B 收錄推得，兩者都指向 Cheyenne 的註冊代理人 PMB。密西根 LARA 在 TLS 層被 Cloudflare 阻擋、德拉瓦 ICIS 回傳頁內處理錯誤、懷俄明 SOS 有 CAPTCHA。**補齊方式：** 申請懷俄明州 certificate of good standing／法人明細，或委由公司資料查詢商人工查詢。
2. **無登記在案之幹部、董事、經理人、股東、設立人、註冊代理人姓名或年報簽署人。** 本檔每一個幹部姓名都是公司自行宣稱或由 FEC 佐證，沒有一個經登記機關驗證。**在兩位具名創辦人之外可能還有其他幹部、董事或股東，而從現有資料完全看不到。**
3. **無申報歷史。** 設立文件、修正、更名、前身名稱、外州登記資格 —— 特別是**Hot Aisle 是否已在密西根州辦理外州法人登記**（其主機代管足跡可能需要）—— 全部無法取得。
4. **UCC-1 融資聲明完全未經查證。** 零筆取得、零個入口可觸及。本報告中不存在任何申報編號、日期、失效／續期狀態、擔保權人、債務人地址、擔保品描述或修正／讓與／終止歷史。**這是最大的證據缺口，且直接影響硬體過去與未來的融資方式。補齊方式：** 以 `HOT AISLE INC` 為債務人，在懷俄明州（研判之設立州）與密西根州（擔保品所在地）辦理 UCC-11 查詢。
5. **歷史 WHOIS 無法取得。** whoisrequest.com 回 HTTP 403；whoxy.com 需付費登入；securitytrails 需 API key。僅取得現行 WHOIS（建立 2023-10-18、註冊商 Spaceship Inc.、Cloudflare 名稱伺服器、登記人遮蔽於「Withheld for Privacy ehf」（冰島）之後）。**任何 2023–2024 年隱私遮蔽前的登記人姓名、組織或信箱皆未還原** —— 那有可能揭露原始設立法人或早期地址。
6. **無商標，因此無聲明簽署人與代理人。** USPTO 對「hot aisle」與「hotaisle」於全狀態、全類別均回傳「No results found」。**記為真實的負面結果，不是查詢失敗。**（注意通用名詞問題：「hot aisle」是業界術語，這很可能就是未申請的原因。）
7. **現行機隊確切規模未揭露。** 16 節點／128 GPU 是推導所得的算術，並以電力推導交叉檢核。**他們可能自 2024 年 9 月以後又增購而未宣布** —— 兩種主機 CPU 組態正暗示了這一點，但第二批的規模與日期不明。
8. **完全沒有任何財務揭露。** 無營收、ARR、毛利、EBITDA、電力成本、主機代管費率、傳輸成本或硬體取得成本。**營收區間與整套由租金推導的成本天花板，都是建立在公開牌價加上假設營運成本佔比的模型 —— 它們不是查證所得的事實，絕不可如此呈現。**
9. **兩家廠商的 MI355X 每節點市場價格皆不明。** 本檔找到了 MI300X 世代 Supermicro AS-8125GS-TNMR2 真實、當前、有現貨的價格（$275,863.87），但**Supermicro 與 Dell 的任何 8× MI355X 系統都查無公開市場價格**，Dell XE9680 MI300X 更是完全無價（報價制）。**因此 BOM 對照錨定在前一世代。而真正的決策標的是 MI355X。**
10. **Switch Pyramid 的散熱條件未經查證 —— 而這是商業上最重要的缺口。** Hot Aisle 的租用足跡能否支援每顆加速器 1,400 W 的直接液冷、密度多少、成本多少、時程多久 —— **完全未知。整個主要銷售楔子取決於這個答案，這正是它被設計成資格問題而不是被斷言的原因。**
11. **Hot Aisle 在 Switch 的簽約電力、機櫃數與樓地板面積未揭露。** 公開的只有 Switch 的全園區數字（已建 660,000 平方英尺、規劃可達 180 萬平方英尺與 110 MW）。Hot Aisle 自身的配額僅能由 REC 資料推得。
12. **如預期，郡府產權或估價紀錄中沒有以 Hot Aisle 為名的資料。** 他們是主機代管租戶，Kent County 的地號屬於 Switch。本檔**未**調閱 Switch 的地號紀錄，因為那描述的是房東而非本標的 —— **屬刻意的範圍決策，不是疏漏。**
13. **查無法院案卷 —— 很可能是真實的負面結果，但非窮盡。** CourtListener 以「Hot Aisle Inc」為當事人的精確片語查詢回傳 0 筆；較寬鬆查詢回傳 32 筆與本案無關的資料中心專利訴訟，僅因通用術語命中。**僅涵蓋聯邦層級** —— 未進行密西根、懷俄明、新罕布夏或華盛頓的州法院查詢，且 RECAP 的涵蓋率本質上不完整。
14. **查無任何徵才啟事**，因此沒有招募主管姓名、沒有團隊成長訊號、也沒有組織擴編證據。這與「兩人公司使用夥伴人力支援」相符，**但沒有職缺是弱證據，不是證明。**
15. **貢獻者身分未釐清。** GitHub 帳號 **vmiss33**（5 筆 commit）、**dhogaivannan**（New York NY）與 **gtnotacoder**（gt@netg.co）出現在 Hot Aisle 的程式碼庫中，但無法確認其為員工、外包或外部貢獻者。**未接觸，亦不計入人員。**
16. **無任何收入端的客戶姓名。** 「700+ 客戶」是公司總量；只有 dstack、Red Hat／Neural Magic 與 Dr. Moritz Lehmann 有證據顯示確實在 Hot Aisle 硬體上運行。**沒有任何具名企業標誌、沒有具名客戶的案例研究，也沒有任何合約金額證據。**
17. **投資方細節稀薄。** Mesh.xyz／MeshWeb3（Joseph Lubin）具名為投資方，但**查無輪次金額、日期、持股比例、董事會組成或股權結構，且現行 $50–100M 募資案查無任何公告。**
18. **PeeringDB 完全沒有紀錄**，因此無流量揭露、無 IX 進駐、無設施列表、無 peering 聯絡人姓名。其唯一的網路聯絡窗口是單一共用的 ARIN 職務信箱。
19. **OpenCorporates、Bizapedia、CorporationWiki 與 OpenGovUS 全數受阻**（分別為 CAPTCHA、HTTP 403 與 HTTP 404），**登記資料的所有聚合站備援路徑因此全部斷絕。**
20. **$50–100M 募資案除了公司自家 Investors 頁之外未經任何查證。** 無申報、無新聞稿、無第三方確認其目標金額、階段或任何承諾。**「超過 $50M 的 MI355X 產能需求」同樣是公司陳述且未經審計，且屬前瞻性需求管線而非營收。**
21. **重跑時的工具註記。** ZoomInfo MCP 連接器（以及 carta、figma、atlassian、spglobal、adobe 連接器）需要 OAuth 授權，在本次非互動式工作階段中無法使用。透過 claude.ai 連接器設定完成 ZoomInfo 授權，重跑時很可能可以補上部分員工數與具名人員缺口。另請注意：**WebFetch 對 web.archive.org 為硬性阻擋** —— §8 的整套採購時鐘都必須以 Bash/curl 搭配 gzip 處理才能取得。
