# 美國裸機／專用主機層 — 銷售情報檔案
**六家目標：** ReliableSite · QuadraNet · WebNX · Sharktech · Hostwinds · Psychz
**編製對象：** Supermicro 銷售一組（美國）　暨　銷售七組 · 專員 US8664 Tuo Cheng · **日期：** 2026-08-03
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及各公司與其客戶之關係為研究軸線。此六家均為私有公司、無 SEC 申報，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之伺服器規格與定價、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。

---

## 1. 結論摘要（Bottom line）

這六家都是美國中小型裸機／專用主機（bare metal）業者，全部為私人持股、無 SEC 申報，規模落在員工 11–50 人、自有 ASN、租用第三方資料中心機櫃、以元件級或準系統級自行組裝伺服器的同一種商業型態。CRM 於 2026-08-03 以 salesleads Search（Type=All）逐家實查，六家全部回傳「No similar record found」——沒有 lead、沒有 account、也沒有 DNC，代表這一整層從未被登錄過。依「Territory Map-Jan.2026 (Rev.1)」的 Sales Territory Assign 分頁，其中四家坐落在銷售一組自有轄區內：WebNX（Ogden, UT）與 Sharktech（Las Vegas, NV）屬 West Coast South excl. CA（T1 | T31），QuadraNet 與 Psychz（皆 Los Angeles, CA）屬 West Coast South California（T1 | T2）；Hostwinds（Tukwila, WA）落在 West Coast North，須與 T4（Kambiez Tahvilian）協同，ReliableSite 的實體據點在 NJ 與 FL，屬東岸轄區。本次調查最重要的商業事實是：**WebNX 已經在買、並已公開標價出售當世代 AI 平台——雙路 AMD EPYC 9575F（128C/256T）、1.5TB DDR5、4 張 NVIDIA RTX PRO 6000 96GB，月租 $7,999**（[WebNX Ogden GPU & AI 商店](https://clients.webnx.com/index.php?rp=/store/ogden-gpu-and-ai-servers)），同一份型錄裡卻同時掛著 2017 年的 V100 與 2020 年的消費級 RTX 3090，且完全沒有 H100／H200／L40S——這是本層唯一一個有標價、可驗證、規格明確的當世代改朝換代缺口。

---

## 2. 六家對照表（Comparison matrix）

硬體欄位刻意分級：**已確認**＝業者第一手具名揭露或多方獨立佐證；**旁證**＝業者行為強烈指向但從未具名；**推論**＝僅由 CPU／機殼形狀推得；**反證**＝證據與原始名單相反；**GAP**＝查無。

| 業者 | 總部（實查地址） | 轄區／團隊 | 已確認硬體供應商 | GPU 產品線（型號） | 規模訊號 | CRM 狀態 |
|---|---|---|---|---|---|---|
| **WebNX, Inc.** | 119 North 600 West, Bldg 3B, Ogden, UT 84404（[BBB](https://www.bbb.org/us/ut/ogden/profile/internet-service/webnx-inc-1166-90026506)）；datacenters.com／ZoomInfo 誤植為加州，未採信 | West Coast South excl. CA = **T1 \| T31** → 一組自有 | **無任何已確認的伺服器品牌。** WebNX 全站、職缺、PeeringDB 均未具名機殼或主機板廠。唯一具名者為 **NVIDIA DGX Spark 整機（已確認）**。Dell／HPE = GAP。Supermicro = **未證實**（僅有同址、同創辦人之獨立法人 GorillaServers 的第三方評測文字提及，不得視為 WebNX 事實）（[Indeed 職缺](https://www.indeed.com/viewjob?jk=9329bfea43788efd)） | **實有且在賣**：RTX A5000／RTX A6000 48GB／RTX 5090／4×RTX 3090／4×V100 16GB 及 32GB／2×A100 80GB／4×RTX PRO 6000 96GB（Blackwell）／DGX Spark 單機與雙機／Intel Arc Pro B70／AMD Radeon AI PRO R9700。**無 H100、H200、L40S、GB200** | 自述「thousands of high-end servers globally」；Equinix LA3 逾 150 機櫃；Ogden 逾 100,000 sq ft（LinkedIn 稱近 150,000，衝突）；AS18450 約 100,096 個 IPv4；員工 11–50（自報）；營收 = **GAP** | **未登錄**（2026-08-03 實查：No similar record found） |
| **Psychz Networks**（Profuse Solutions, Inc.） | 辦公：611 Wilshire Blvd, Suite 300, Los Angeles, CA 90017；機房：700 Wilshire Blvd #100/#200；法定登記：20687-2 Amar Rd #312, Walnut, CA 91789（[CA 登記鏡像](https://www.bizprofile.net/ca/walnut/profuse-solutions-inc)） | West Coast South California = **T1 \| T2** → 一組自有（T2 亦可承作） | **Supermicro = 旁證，非確認。** 依據：Psychz 在自家知識庫撰寫並託管 Supermicro 專屬 BMC 文件（[Access Supermicro IPMI Remote Console](https://www.psychz.net/client/question/en/access-supermicro-ipmi-remote-console.html)），且站內查無任何 Dell iDRAC／HPE iLO 對應文件；庫存中出現 Core i7-7700K 機種，Dell／HPE 不生產此類機架伺服器。**未見任何機殼或主機板型號**。網路層 Juniper MX960／MX240 為第三方案例（次級擷取） | **有，但全部報價制、無公開價**：H100（80GB SXM／94GB NVL）、H200 141GB、B200、B300；另於 Q&A 提及 A100、V100、T4、RTX 3090、RTX 4090。單卡至 8 卡系統（[ai-llm 頁](https://www.psychz.net/ai-llm.html)） | LA 自營 15,000 sq ft；PeeringDB 16 個互連設施（自稱 17）；AS40676 約 188,928–283,904 個 IPv4（來源不一）；自稱 6 Tbps+；Inc. 5000 四度上榜（2018/2019/2020/2025，2025 名次 #2372、三年成長 179%）；員工數三方衝突 8～200 | **未登錄** |
| **ReliableSite**（RELIABLESITE.NET LLC） | 法定：2115 NW 22nd St, Miami, FL 33142（即 CoreSite MI1 大樓）；營運：101 Possumtown Rd, Piscataway, NJ 08854（即 QTS PNJ1）（[FL 登記](https://bisprofiles.com/fl/reliablesite-net-l14000189024)）。**無任何紐約市地址** | FL＝East Coast 3、NJ＝East Coast 1，皆為 **T2\|T3\|T6\|T7\|T12**；T1 僅在 Large End User／Data Center 例外下可承作，惟 **Rule 11 定義「大型資料中心」為 100MW 以上，本案不符**，故 T1 例外不適用 → **須東岸協同（七組 Brian Leaver 為本檔對口）** | **Supermicro = 已確認**（本層證據最強）：兩則獨立 Web Hosting Talk 客戶評述指其伺服器為 Supermicro barebones／onboard KVM，加上 CEO Radic Davydov 於 [LowEndBox 專訪](https://lowendbox.com/blog/custom-built-for-success-interview-with-radic-davydov-ceo-of-reliablesite/) 親口討論 Supermicro MicroCloud。**同一專訪也是他們轉向自製機殼的原因說明**。Dell = **反證／查無**（全網零則） | **極薄**：NVIDIA Quadro RTX 4000 作為 $99/月加購；NVIDIA A10 單一機種 $699/月（Los Angeles，庫存 1 台）。**無 L40S、A100、H100、H200、RTX 6000 Ada，無多卡平台**（[GPU AI 頁](https://www.reliablesite.net/dedicated-servers/gpu-ai-dedicated-servers/)） | AS23470 originates 199 個 IPv4 前綴、約 50,944 個 IPv4；PeeringDB 自報 1–5 Tbps；六個區域；員工 11–50（自報）；Kona Equity 估 $1.2M 營收（**與可觀測基礎設施明顯不符，低可信度**） | **未登錄** |
| **Sharktech, Inc.** | 8560 S. Eastern Ave., Suite 210, Las Vegas, NV 89123（[contact 頁](https://sharktech.net/contact/)）。此為辦公室，非機房；拉斯維加斯運算位於 Flexential 機房。NV 為外國公司登記，**本籍為 Montana** | West Coast South excl. CA = **T1 \| T31** → 一組自有 | **Lenovo = 已確認，且是他們唯一一次公開具名的伺服器品牌。** 客戶入口公告 #221（2025-01-16）AMD EPYC 7702P 產品線規格逐字寫著「System: Lenovo」（[公告](https://portal.sharktech.net/index.php/announcements/221/Now-Available-AMD-EPYC-7702P-with-NVMe-U.2.html)）。**Supermicro = 全站零則**（已逐頁比對 servers.json 全 51 個 SKU、25 則公告、PeeringDB、ARIN）。其餘約 50 個 SKU 的平台廠 = GAP | **象徵性**：51 個 SKU 中僅 1 個 GPU 機種，只在 Las Vegas，且目前 `inStock:false`。基礎款 NVIDIA RTX A4000 16GB，升級選項 雙／三 A4000、V100 32GB 及雙／三 V100。**無 L40S、L4、A100、H100、H200、RTX 6000 Ada、Blackwell；無 SXM／HGX、無 4 卡或 8 卡節點**（[servers.json](https://sharktech.net/servers.json)） | AS46844 originates 413 個 IPv4 前綴、124,416 個 IPv4；五個站點；全 51 SKU 標配 10Gbps／300TB；2026-06-25 完成 400GE 骨幹升級；客戶數 1,000+（73 國，官網另稱 10,000，內部矛盾）；LeadIQ 估 $10M–$25M（第三方估計） | **未登錄** |
| **Hostwinds LLC** | 12101 Tukwila International Blvd, Suite 320, 3F, Tukwila, WA 98168（位於 Sabey Intergate.Seattle-West 園區）（[BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407)）。**2026-04-29 已被 HostPapa, Inc. 併購**，AS54290 之 ARIN 登記機構已於 2026-05-12 改為 HostPapa（Buffalo, NY） | West Coast North (WA,OR,ID,MT,WY,AK,HI) = **T4 \| T31** → **須 T4 協同（T4 主管 Kambiez Tahvilian）**。母公司 HostPapa 位於 Burlington ON／Buffalo NY，採購權可能已北移 | **全部未證實。** 官網、文件、部落格、職缺、論壇、新聞稿皆未具名任何伺服器品牌。唯一線索為文件中一律使用泛稱 IPMI／「BMC Cold Reset」「BMC Warm Reset」，全網零則 iDRAC／iLO——此為**推論訊號，不得當作事實陳述**（[管理文件](https://www.hostwinds.com/guide/dedicated-server-management-controls/)） | **完全沒有 GPU。** 站內 GPU／NVIDIA 關鍵字查無產品；購物車（gid=12）20 個 SKU 全為 CPU-only、無加速器選項。且 colocation 電力上限為整櫃 3.84 kW／雙櫃籠 7.68 kW，**現行電力密度無法承載 H100／L40S 級部署**（[購物車](https://clients.hostwinds.com/cart.php?gid=12)） | AS54290 originates 75 個 IPv4 前綴、303,360 個 IPv4；PeeringDB 自報 20–50 Gbps；客戶埠一律 1 Gbps；線上 20 個 CPU 平台自 Xeon 5300 Clovertown（2007）至 E3-1270 v6（2017），**無任何 Xeon Scalable、無 EPYC**；員工數第三方估計 5～200（40 倍差距）；營收第三方估 $3M–$5M | **未登錄** |
| **QuadraNet**（QuadraNet Enterprises, LLC） | 530 W 6th Street, Penthouse, Los Angeles, CA 90014（Telecom Center 大樓，緊鄰 One Wilshire）（[Yelp](https://www.yelp.com/biz/quadranet-los-angeles)） | West Coast South California = **T1 \| T2** → 一組自有轄區，**但標的本身已崩解** | **Supermicro = 已確認（第一手逐字）**：自家促銷規格書逐字寫「1U Supermicro Server – 4x Hot-Swap Bays」，特賣頁列「Supermicro CSE」機殼與「Supermicro IPMI」（[LowEndBox 專屬優惠](https://lowendbox.com/blog/quadranet-exclusive-black-friday-dedi-offers-in-los-angeles/)）。**Dell = 部分**：僅由帶外管理選項寫「Dell Enterprises iDRAC」推得，無任何 PowerEdge 型號。HPE = 查無。RAID 卡 Adaptec 2405（第一手） | **完全沒有 GPU，且是硬性否定而非資料缺口。** 所有可考組態均為 Intel Xeon CPU-only，最新僅到 Broadwell／Coffee Lake | **已瓦解**：2024-04-08 由 VSS Capital Partners 售予 Edge Centres；澳洲母公司 Edge Centres Pty Ltd 於 2025-06-16 遭法院指派清算人；2025 年初逾 200,000 個 IPv4 售予 HostPapa（自約 300,000 降至約 6,656）；2025-01 LA／Chicago／Dallas 多日斷線；2025-02 LA colocation 客戶被要求一週內撤離。2026-08-03 實測：quadranet.com 僅剩 logo，/dedicated-servers、/specials_baremetal、/atlanta-dedicated-servers 皆 404，blog.quadranet.com NXDOMAIN，AS8100 幾乎不再宣告 IPv4 | **未登錄** |

---

## 3. 原始名單更正表（Corrections to the working list）

以下每一列都是原始工作名單中被研究**推翻**或**無法證實**的敘述。銷售人員在首次接觸前必須先讀完本表，避免以錯誤前提開場。

| # | 原始名單的說法 | 判定 | 證據與正確說法 |
|---|---|---|---|
| 1 | ReliableSite 是「紐約」業者，可能是 Digital Realty 房客 | **反證（兩處錯誤）** | （a）**不在紐約市**。公開資料中查無任何曼哈頓地址（111 8th Ave／60 Hudson／32 AoA 皆無）。PeeringDB 所載設施為 **QTS Piscataway PNJ1（101 Possumtown Rd, Piscataway, NJ）** 與 **Newark 的 165 Halsey Street** meet-me room；其產品 SKU 本身即帶「(PNJ)」地區碼，公司只是把該區「行銷為」New York City Metro。（b）**並非 Digital Realty 房客**。AS23470 在 PeeringDB 的 Digital Realty 設施數為零；房東是 QTS（Blackstone 持有）、CoreSite（American Tower）、Equinix、Databarn。Digital Realty 確實在 Piscataway 有 EWR11/12/19，但位於 365 S Randolphville Rd／3 Corporate Place，**與 101 Possumtown Rd 是不同地址**。任何以 Digital Realty 關係切入的話術都會出錯。（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)） |
| 2 | Sharktech 使用 Supermicro 硬體 | **反證** | Sharktech 唯一一次公開具名伺服器品牌，指的是 **Lenovo**：客戶入口公告 #221（2025-01-16）EPYC 7702P 產品線規格逐字為「System: Lenovo」（[公告 #221](https://portal.sharktech.net/index.php/announcements/221/Now-Available-AMD-EPYC-7702P-with-NVMe-U.2.html)）。「Supermicro」一詞在下列全部來源出現 **0 次**：sharktech.net 專用伺服器／colocation／DDoS／五個機房頁、[servers.json 全 51 個 SKU](https://sharktech.net/servers.json)、[入口公告全 25 則](https://portal.sharktech.net/index.php/announcements)、PeeringDB、ARIN RDAP、LinkedIn、LowEndTalk 評論串。硬碟槽位階梯（24×3.5"／12×3.5"／10×U.2／2×M.2）與全機隊泛稱 IPMI 確實**相容於** Supermicro 級準系統，但同樣相容於 Lenovo ThinkSystem，**單憑形狀無法識別廠牌**。正確定位：這是 **Lenovo 替換／第二供應商**機會，不是續約。 |
| 3 | WebNX 使用 Supermicro 和／或 Dell 硬體 | **無法證實（不得對客戶陳述）** | 經 16 次以上檢索並直接抓取 WebNX 的 Ogden custom／GPU-AI／storage／Intel／colocation 商店頁、Utah 機房頁、LinkedIn 與兩則線上 Indeed 職缺，**WebNX 從未具名任何系統廠、機殼型號或主機板品牌**；其 WHMCS 知識庫為空（[knowledgebase](https://clients.webnx.com/index.php?rp=/knowledgebase)），連帶外管理品牌（IPMI／iDRAC／iLO）這條慣用線索也斷了。已確立的是：WebNX 是**元件級自組整合商**，職缺明載「assembling & disassembling servers, testing hardware」「repair or replace faulty hardware components」與用棧板車搬運整棧伺服器零件，並自稱每年測試「hundreds of server configurations and parts」（[Indeed](https://www.indeed.com/viewjob?jk=9329bfea43788efd)）。唯一出現 Dell／SuperMicro／HP 字樣的文字，描述的是 **GorillaServers**——同一位創辦人 Daniel Pautz、同一棟 Ogden 廠房、但**法人不同**，且該敘述來自第三方評測而非官方揭露。**不得以此推定 WebNX 的機隊。** |
| 4 | QuadraNet 位於 One Wilshire | **部分確認，但框架需修正** | PeeringDB 確實把「CoreSite - Los Angeles (LA1) One Wilshire」列為 AS8100 的私有互連設施——**One Wilshire 內確有網路／peering 據點**。但其旗艦自營機房**不在** One Wilshire 內，而在**隔壁的 530 W 6th Street（Telecom Center）**，QuadraNet 自 2004 年進駐、據稱是最大房客、跨 6 個樓層。正確說法：One Wilshire 內是互連據點，真正的機房量體在隔壁棟。（[PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)）另須注意這整段footprint 已是歷史：2025-02 LA colocation 客戶被通知約一週內撤離。 |
| 5 | QuadraNet 站點：LA、Dallas、Miami、Atlanta、**NYC** | **部分確認（NYC 為誤）** | LA、Dallas（TierPoint Dallas）、Miami（South Reach Networks）、Atlanta（CoreSite AT1）皆由 PeeringDB 確認。**紐約市查無任何設施**——所謂紐約都會據點實際位於 **Secaucus, New Jersey**（H5 Data Centers Secaucus 與 InterServer Teb2），QuadraNet 自己也是以「New Jersey」行銷。同時原始名單**低估**了範圍：漏列 Chicago（Equinix CH3）、Seattle／Tukwila（WowRack）、荷蘭 Woerden（HostSlim）。（[PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)） |
| 6 | Psychz 自有（owns）約 15,000 sq ft 資料中心 | **部分確認——面積對，「自有」錯** | 15,000 sq ft 由業者自家 LA 機房頁確認（「15000 sq ft of gross space」）（[LA 機房頁](https://www.psychz.net/los-angeles-data-center.html)）。但**「擁有」不成立**：該設施位於 700 Wilshire Blvd 的 #100、#200 **編號套房**，是第三方多租戶大樓；Psychz 另在 624 South Grand Avenue（One Wilshire，業主為 GI Partners／TechCore，meet-me room 由 CoreSite 營運）有空間，並且是 CoreSite Marketplace 在 LA／Chicago／北維吉尼亞／DC／Atlanta 的掛牌租戶（[CoreSite Marketplace](https://www.coresite.com/marketplace/psychz-networks)）。查無任何地契或產權紀錄。可支持的是**營運自主**（自 2014 年起自營、自有 UPS／發電機／燃料儲存、自售機櫃與 remote hands）。**正確話術：「約 15,000 平方英尺的自營機房」，不是「他們擁有的資料中心」。** 另注意 DataCenterJournal 所列 19,440 sq ft 是**建物量體**，兩者不可混用。 |
| 7 | ReliableSite 使用 Supermicro 和／或 Dell | **Supermicro 確認、Dell 反證，但需附帶重要但書** | Supermicro 由三條獨立證據成立：兩則 Web Hosting Talk 客戶評述（其一為 Atom D510 舊世代）、加上 CEO 於 LowEndBox 專訪親口討論 Supermicro MicroCloud。**但書極重要**：該專訪本身是「離開原廠機殼」的故事——CEO 表示 MicroCloud 替換零件買不到、且價格為原來的「2-3 times」，因此他自行設計密度高約 50% 的專屬機殼，並刻意保持**相容於市售主機板與電源**。因此當世代部署很可能是自製機殼＋通用主機板，Supermicro 屬歷史／部分。**Dell：官網、規格頁、職缺、WHT／LowEndTalk、新聞稿、PeeringDB 全部零則 Dell／PowerEdge／iDRAC，原始名單的 Dell 說法無任何支撐。** |
| 8 | Psychz 使用 Supermicro | **部分確認（強旁證，非揭露）** | 支持：（i）Psychz 在自家支援網域撰寫並託管 **Supermicro 專屬** BMC 文件（Access Supermicro IPMI Remote Console；Supermicro IPMI 預設密碼 ADMIN/ADMIN），並在通用文中寫「At Psychz, every server comes with... IPMI」；（ii）站內限定檢索**查無** Dell iDRAC 或 HPE iLO 對應文件——Supermicro 是他們唯一具名的伺服器廠；（iii）線上庫存含 **Core i7-7700K** 機種，Dell 與 HPE 均不生產此類機架伺服器。缺什麼：無機殼或主機板型號、無機櫃照片、無機房導覽、無提及 Supermicro 的職缺、無員工發言；而且直接抓取那兩篇 IPMI 文件，內文並未寫「Psychz 的伺服器是 Supermicro」。**定位為首通電話要確認的高信心假設，不是已驗證事實。** |
| 9 | QuadraNet 使用 Supermicro 和／或 Dell | **確認（Supermicro）／部分（Dell）** | Supermicro 為**第一手逐字**：四款 LA 專用伺服器 SKU（X3450、E3-1241v3、雙 E5620、E-2124G）的規格行皆逐字寫「1U Supermicro Server – 4x Hot-Swap Bays」；自家 specials_baremetal 頁列「Supermicro CSE」機殼與「Supermicro IPMI」（該網址於 2026-08-03 實測回 404，內容由搜尋索引擷取）。Dell **僅為推得**：唯一依據是帶外管理選項寫成「Dell Enterprises iDRAC」或「Supermicro IPMI」二擇一，iDRAC 為 Dell 專屬，故機隊中應有部分 PowerEdge——**但型號、世代、佔比全部 GAP，不得聲稱已知**。另注意整個可考機隊自 Nehalem 到 Broadwell／Coffee Lake，**在公司崩解前就已落後當世代 5–10 年**。 |
| 10 | Hostwinds 使用 Supermicro 和／或 Dell；總部在 Seattle | **未證實（硬體）／部分確認（總部）** | **硬體：完全查無。** 已檢索 hostwinds.com 產品頁、/company/datacenters、/colocation、/product-docs、/guide、部落格，以及 WebHostingTalk、LowEndTalk、職缺、PeeringDB 與新聞稿，**無任何來源具名 Supermicro／Dell／HPE 或任何 OEM**。公司只確認「Our hardware is directly owned and sold by us... no middlemen」（自有硬體、無中間商），但不揭露供應商。唯一旁證是文件全篇使用泛稱 IPMI 與「BMC Cold/Warm Reset」，全網零則 iDRAC／iLO——**這是命名慣例訊號，屬推論，禁止寫入 CRM 或對客戶陳述**。**總部：實際城市是 Tukwila 而非 Seattle**（郵遞區號 98168 為 Seattle 位址但涵蓋 Tukwila），公司自寫成「Seattle」。且**最關鍵的更正**：Hostwinds 已於 **2026-04-29 被 HostPapa, Inc. 併購**（[HostPapa 新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)），ARIN AS54290 已於 2026-05-12 改登記為 HostPapa（325 Delaware Avenue Suite 300, Buffalo NY），採購決策權很可能已移轉。 |
| 11 | WebNX 提供 GPU 伺服器 | **確認（唯一完全成立的硬體相關原始說法）** | Ogden 一地即有 14 個 GPU SKU 公開標價，自 $299/月（雙 Xeon Gold 6148 配 GT 1030）到 $7,999/月（雙 AMD EPYC 9575F、1.5TB DDR5、2×15TB Gen5 NVMe、4×RTX PRO 6000 96GB）；另在 Los Angeles 與 Dallas 設有獨立 GPU & AI 商店分類。（[Ogden GPU & AI 商店](https://clients.webnx.com/index.php?rp=/store/ogden-gpu-and-ai-servers)） |
| 12 | ReliableSite「自 2006 年營運」、「完全自營」 | **各為部分確認** | **2006**：僅為公司自述（About 頁、LinkedIn），現行法人 RELIABLESITE.NET LLC 於 **2014-12-11** 在 Florida 設立（Doc L14000189024），ASN 23470 於 **2018-08-10** 註冊，各州登記查無 2014 年之前的前身。正確表述：**品牌／營運自 2006、法人自 2014、自有 ASN 自 2018**；不要複述「20 年公司歷史」。**自營**：伺服器、網路、人員為真（自有 IP、自有 transit 組合、五個 IXP 各 100G、自建 L3/L4 DDoS 過濾、在 Piscataway 與 Miami 直聘駐點技師）；**設施為假**——所有站點都是租用他人機房內的空間。 |
| 13 | 六家皆為 Supermicro 客戶（原始名單的隱含前提） | **反證** | 逐家實查後：**已確認 Supermicro 者僅 2 家**（ReliableSite、QuadraNet，且後者已崩解）；**強旁證 1 家**（Psychz）；**推論訊號 1 家**（Hostwinds，僅 IPMI 命名）；**完全未證實 1 家**（WebNX）；**確認為 Lenovo 1 家**（Sharktech）。把六家一律當成既有 Supermicro 客戶開場，在其中四家會立即失去可信度。 |

---

## 4. 各業者專章（依商業價值由高至低）

排序原則：**有真實 GPU 機隊 ＋ 已確認或高機率 Supermicro ＋ 位於一組自有轄區** 者優先。

---

### 4.1 WebNX, Inc. — 一組自有轄區內，唯一已在買當世代 Blackwell 平台的業者

**法人與所有權**
法人名稱 **WebNX, Inc.**，無 SEC 申報。BBB 檔案載明法定名稱與地址 119 N 600 W, 3B, Ogden, UT 84404、電話 (800) 840-5996、檔案開立於 2020-06-03、評等 A+、**未取得 BBB 認證**；BBB 同時記錄兩個日期：業務開始 1999-04-04、「locally incorporated 2018-09-14」（後者應為 Utah 登記事件，非創立日）（[BBB](https://www.bbb.org/us/ut/ogden/profile/internet-service/webnx-inc-1166-90026506)）。另有 USDOT #3244340「WEBNX INC」公開紀錄，與其自營車輛處理硬體物流一致。
- **Daniel Pautz — 創辦人暨 CEO**。LinkedIn 標題為「Founder & CEO of WebNX, Inc.」，位於 Ogden, Utah（[LinkedIn](https://www.linkedin.com/in/daniel-pautz-0b11597/)）；BBB 主要聯絡人獨立列出同一人。搜尋結果亦將他與 **GorillaServers** 的創立連結——該公司為**法律上獨立**、但在**同一棟 Ogden 廠房**營運。
- **Dario Perovich — 營運長（COO）**，來源為 BBB 主要聯絡人欄位（未取得直接 email 或 LinkedIn，**GAP**）。
- **受益所有權／股權比例＝GAP**：無 SEC 申報、未取得州登記幹部名單、Crunchbase／PitchBook 無揭露之募資輪。外觀為創辦人自有、自力成長，但**無任何可查證文件佐證**。
- **Utah Division of Corporations 之實體編號、狀態、設立日、註冊代理人＝GAP**：businessregistration.utah.gov 為 JS 互動式入口，無法以抓取方式取得紀錄。

**總部與各資料中心（自有 vs 租用）**
| 站點 | 自有／租用 | 面積與電力 | 證據 |
|---|---|---|---|
| **Ogden, UT — 119 North 600 West, Bldg 3B**（旗艦兼總部） | **自營**（證據強，但非產權查核）。公司行銷「100% self-operated data centers」，Indeed 職缺寫明 WebNX「operates self-managed data centers across Utah, California, and New York」。**GAP：查無郡府產權或租約文件可證明是持有 3B 棟產權或長期租賃** | **面積數字互相衝突**：官網與 datacenters.com 稱「over 100,000 sq ft」，LinkedIn 稱「nearly 150,000 square-foot」。**以 100,000+ sq ft 為可辯護下限**。電力：N+1 拓撲，雙市電饋線、N+1 UPS、多台柴油發電機；**無 MW／kW 臨界 IT 負載、無每櫃 kW 密度、無 PUE**（皆 GAP） | [Utah 機房頁](https://webnx.com/datacenter-locations-and-networks/utah)。公開 colocation 價目：1U-2U $75/月、4U $129/月、半櫃 $699/月、整櫃 $1,199/月（1Gbps 不限流量、可升 10G；/29 IPv4、整櫃 /28）。**整櫃方案未公布安培配額**——這點在談 AI 密度時必問 |
| **Los Angeles, CA — Equinix LA3**（另於 CoreSite One Wilshire 與 Equinix LA1 有互連據點） | 租用第三方 carrier hotel | **「more than 150 racks within Equinix LA3」（LinkedIn）——本檔取得最有用的單一規模數據**。電力 = GAP | [LinkedIn 公司頁](https://www.linkedin.com/company/webnx-inc-)；[PeeringDB net/4729](https://www.peeringdb.com/net/4729) |
| **New York, NY — NYI NY1（100 William Street）**；LinkedIn 另稱擴展至 60 Hudson Street | 租用 | GAP。商店以「NY1 (Manhattan)」與「NY2 (Staten Island)」兩個 PoP 販售 Ryzen／EPYC／Threadripper | [PeeringDB net/4729](https://www.peeringdb.com/net/4729) |
| **Salt Lake City, UT — DataBank、Flexential Downtown、Level(3)** | 租用／互連空間 | GAP（研判為網路 PoP 而非運算機房） | 同上；另於 SLIX 以 40G peering |
| **Dallas, TX — 「DA1 (Dallas)」** | **未定，幾可確定為租用（GAP）** | GAP | 商店販售 DA1 Instant Ryzen 與 DA1 Instant GPU & AI；**但官方機房行銷頁未列 Dallas**，研判為較新或較小的部署（[商店](https://clients.webnx.com/index.php?rp=/store)） |

**硬體機隊與證據等級**
- **系統品牌＝未確認（本案對銷售最關鍵的未知）。** 所有 WebNX 產品描述只列 CPU／RAM／NVMe／GPU／網路，從不列機殼或系統廠。
- **自組整合＝已確認，且是最貼切的描述。** 職缺（Ogden，時薪 $15–17）列明組裝與拆解伺服器、測試硬體、更換故障零件、以棧板車搬運整棧伺服器零件，並自述每年測試「hundreds of server configurations and parts」（[Indeed](https://www.indeed.com/viewjob?jk=9329bfea43788efd)）。一則 7 年期 WebHostingTalk 客戶評述描述僅需提出組態即可在數日內取得報價並更換硬體 4–5 次——這是**持有零件庫存的自組商**行為，不是 OEM 訂單週期買家。
- **實際銷售的矽晶組合（可據以反推平台）**：AMD Ryzen 9950X／9950X3D（AM5）、Threadripper、EPYC 7443P（單路 Milan 24C/48T，橫跨多個 GPU SKU）、雙路 EPYC 9575F（128C/256T Turin，1.5TB DDR5）、Intel Core Ultra 9 285K／Ultra 7 265K／Ultra 5 250K（LGA1851）、雙路 Xeon Gold 6148 與 6152、雙路 Xeon E5-2690v4（12 槽儲存節點）。機殼型態推得：12 槽 3.5" 儲存機殼（12×26TB／12×28TB HDD ＋ 480GB SSD，HW RAID 或 JBOD）與 4U 級 4 卡 GPU 機殼。
- **NVIDIA 整機＝已確認**：NVIDIA DGX Spark（Blackwell，20 核 ARM、128GB 統一 VRAM、4TB Gen4 NVMe）單機 $459/月，雙機版「2X NVIDIA Spark DGX + 2 x 200Gbps Direct Connect」$1,099/月——代表 AI 機隊**至少有一部分是買成品整機**，且已在組小型多節點 AI 叢集。
- **Cisco ASR 9000 × 多台 ＋ Noction IRP**：**注意歸屬**，此清單出自 GorillaServers 的 LowEndTalk 行銷貼文描述**共用的 Ogden 廠房**，非 WebNX 自述文件；WebNX 僅自行行銷「BGP route-optimized network」。屬**設施相鄰、社群來源**。
- **Dell／HPE＝GAP**：針對 WebNX ＋ PowerEdge／ProLiant／iDRAC／iLO 的定向檢索無 WebNX 專屬結果。其 WHMCS 知識庫為空，**連帶外管理品牌這條最可靠的辨識線索也不可用**。

**GPU 產品線與確切價格（全部為公開月租、無合約）**
| SKU | 月租 |
|---|---|
| RTX A5000 + Ryzen 9950X／96GB／3.84TB | $389 |
| Intel Arc Pro B70 + Ryzen 9950X／128GB | $399 |
| AMD Radeon AI PRO R9700 + Ryzen 9950X／128GB | $429 |
| NVIDIA DGX Spark（單機） | $459 |
| RTX 5090 + Ryzen 9950X／96GB | $479 |
| RTX A6000 48GB + EPYC 7443P／256GB | $599 |
| 4 × RTX 3090 + EPYC 7443P／128GB | $699 |
| 4 × V100 16GB + EPYC 7443P／128GB | $799 |
| 4 × V100 32GB + EPYC 7443P／128GB | $799 |
| 4 × V100 + EPYC 7443P／256GB／7.6TB | $899 |
| 雙 Xeon Gold 6148／512GB／4×3.8TB + GT 1030 | $299 |
| 2 × A100 80GB + EPYC 7443P／512GB／2×3.84TB | $1,499 |
| DGX Spark 雙機 + 2×200Gbps Direct Connect | $1,099 |
| **雙 AMD EPYC 9575F（128C/256T）／1.5TB DDR5／2×15TB Gen5 NVMe／4×RTX PRO 6000 96GB** | **$7,999** |

**未提供：H100、H200、L40S、GB200。** 這正是切入點——他們已證明買得起也賣得動當世代 Turin ＋ Blackwell 平台，同時卻壓著一批 2017 年 V100 與 2020 年消費級 RTX 3090。

**規模**：自述「thousands of high-end servers globally」（行銷語，非稽核數字）；Equinix LA3 逾 150 機櫃；Ogden 100,000+ sq ft（LinkedIn 稱近 150,000，衝突未解）；AS18450 宣告 159 個 IPv4 前綴 ＋ 8 個 IPv6 前綴，約 100,096 個 IPv4，PeeringDB 登記 300 個 IPv4／20 個 IPv6 前綴；IPinfo 顯示 AS18450 上約 31,446 個網域分布於 1,707 個 IP。**員工 11–50（LinkedIn 自報區間，第三方估計）**，目前 Ogden 仍在招募 Computer Tech - Data Center（$15.00–$17.00/hr，雇主全額負擔醫療／牙科／視力，401k 提撥 4%）。**營收＝GAP，未做任何估計**：ZoomInfo 與 datacenters.com 皆回 HTTP 403，Crunchbase 無揭露募資。**針對 CRM $100M 門檻的判定：公開資料完全不支持 WebNX 達到 $100M+**。

**已具名客戶**：**無**。無 logo 牆、無案例研究、無指名客戶的新聞稿。社群來源提及 GorillaServers「sometimes purchases equipment from WebNX」與 QuickPacket 同在 Equinix LA3（僅為同址，非商業關係）——兩者皆**社群來源且在原文中即有爭議**。客群只能由 SKU 組合與約 31,446 個網域推得：主機轉售商、CDN／串流、備份／儲存、AI/ML 新創與個人開發者。

**網路**：AS18450（WebNX, Inc.），註冊於 2007-07-27，IRR 為 RADB::AS-WEBNX；RPKI 衛生良好——167 個前綴中 161 個有有效 ROA、零 invalid。PeeringDB 自報流量 200–300Gbps、以出向為主。公開 IX 埠：Any2West（CoreSite）100G、Equinix Los Angeles 100G、NYIIX New York 100G、SLIX Salt Lake City 40G。客戶埠：專用與 GPU 伺服器標配 10Gbps、新款 Core Ultra 為 25Gbps、DGX Spark 配對機間 200Gbps。開放 peering，bgp.he.net 觀測 78 個 BGP peer、跨 6 個 IX；上游包含 Cogent、Hurricane Electric、NTT America、Zayo、GTT、Arelion（Telia）；官方機房頁另稱直連 Level3、NTT、Zayo、Telia、China Unicom。NOC：noc@webnx.com。（[PeeringDB net/4729](https://www.peeringdb.com/net/4729)）

**政治紀錄（僅公開紀錄，並附標記）**
- **Daniel Pautz（創辦人暨 CEO）＝查無聯邦政治獻金紀錄**［公開紀錄｜負面結果］。以 FEC Open Data schedule_a API 查詢「Daniel Pautz」，全國僅回傳 1 筆，且**是不同人**：「PAUTZ, DANIEL J.」，紐約州 Syracuse，雇主 Bond Schoeneck & King，職業律師，2022-06-30 捐 $175.00 予 STEVE WELLS FOR CONGRESS。該筆與 WebNX 或 Utah 無關，**嚴禁張冠李戴**。（[FEC API](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=Daniel+Pautz)）
- **Dario Perovich（COO）＝GAP**，未單獨查詢。
- **WebNX（法人）＝GAP**：查無企業 PAC、Utah 州級遊說登記、經濟發展獎勵、稅務減免或市政公用事業協議。相關但非政治之公開紀錄：2021 年 4 月 Ogden 全市停電期間備援發電機起火，導致 WebNX／GorillaServers 中斷，獲 The Register、TechRadar、HostAdvice 報導，**查無任何主管機關裁處**（[The Register](https://www.theregister.com/2021/04/06/webnx_data_fire/)）。此事可作為韌性議題的談資，也可能是發電機／電力設備更新支出的驅動因素。

**公開聯絡管道**：總機（銷售與支援，宣稱 24/7）1-800-840-5996；支援 support@webNX.com；**NOC noc@webnx.com（最佳技術路徑，來自 PeeringDB）**；收貨與到訪地址 119 North 600 West, Building 3B, Ogden, UT 84404；LinkedIn 公司頁（[hyphen 版描述較完整](https://www.linkedin.com/company/webnx-inc-)）；資本支出決策者 Daniel Pautz（[LinkedIn](https://www.linkedin.com/in/daniel-pautz-0b11597/)）；營運／採購路徑 Dario Perovich（僅有姓名職稱）；即時價格與庫存 [客戶入口商店](https://clients.webnx.com/index.php?rp=/store)（可用來追蹤哪些 GPU SKU 售罄）；論壇銷售據點 [WebHostingTalk thread 1933969](https://www.webhostingtalk.com/showthread.php?t=1933969)；徵才 [Indeed Ogden](https://www.indeed.com/q-webnx-l-ogden,-ut-jobs.html)。

**GAP 清單（WebNX）**：系統廠確認（最高優先）／Utah 州登記實體編號與狀態／營收（無任何可辯護數字）／各站電力 MW·kW 與每櫃密度與 PUE／Ogden 面積 100,000 vs 150,000 衝突／Ogden 建物是持有或長租／總部州別衝突（BBB 與職缺指 Ogden，datacenters.com 與 ZoomInfo 稱加州）／確切伺服器與機櫃數／具名客戶（零）／CEO 與 COO 以外的具名人員／Dallas DA1 的設施名稱、營運商、規模、租期／WebHostingTalk（403）與 datacentermap（429）擋抓取，部分佐證僅由搜尋摘要取得。

---

### 4.2 Psychz Networks（Profuse Solutions, Inc.）— 一組自有轄區，已在行銷 Blackwell 級容量卻沒有標準平台供應鏈

**法人與所有權**
營運品牌 **Psychz Networks**，法人為 **Profuse Solutions, Inc.**（California，實體編號 **3470432**）。CoreSite 描述 Psychz 為「a wholly-owned subsidiary of Profuse Solutions, Inc.」，psychz.net About 頁頁尾亦寫「Psychz Networks, A Profuse Solutions Inc Company」。同一母公司下的兄弟品牌：PhotoVPS、YardVPS、GigePipe。
加州登記（經 bizprofile.net 鏡像，資料日期 2025-07-15）：實體 #3470432、設立 **2012-04-23**、狀態 Active，主要與通訊地址 20687-2 Amar Rd #312, Walnut, CA 91789；幹部 **William H Lu（CEO）**、**Renjielyn Gazzingan（Secretary）**、**William Lu（CFO 兼 Director）**；註冊代理人亦為 William H Lu、同一地址。**注意：bizfileonline.sos.ca.gov 對自動抓取回 HTTP 403，故此為登記鏡像而非 SOS 第一手頁面，簽約前應重新自 CA SOS 拉取。**（[登記鏡像](https://www.bizprofile.net/ca/walnut/profuse-solutions-inc)）
- **William H. Lu**（公開場合作「William Lu」「William L」）＝**控制人**。一人同時兼任 CEO、CFO、Director 與註冊代理人，是**獨資／極度封閉持股**的強烈指標。Juniper（現 HPE Juniper Networking）案例研究 PDF 引用「William Lu, CEO, Psychz Networks」。**幹部身分已確認；持股比例非公開（GAP）。**
- 其餘公開幹部（公司僅公布「名＋姓氏首字母」）：**Jimmy L（Vice President）**、**Deepak K（General Manager）**、**Ron K（VP of Product）**——**Ron K 是硬體供應商最可能的技術購買委員會對口**（[About Us](https://www.psychz.net/about-us.html)）。
- **外部投資人＝查無**。Crunchbase 與 PitchBook 皆有 profile 但無揭露募資。Profuse Solutions 四度入選 Inc. 5000（2018 #3413、2019 #3869、2020 #3499/#3501、2025 #2372 且三年成長 179%），與獨立、非 sponsor 支持的私人公司相符（[Inc. profile](https://www.inc.com/profile/profuse-solutions)）。
- **創立年份衝突未解**：品牌自稱 2001（About 頁標題「25 Years And Counting」）、LinkedIn 與聚合站稱 1999、加州法人為 2012-04-23、自營機房自 2014 起。

**總部與各資料中心**
- **營運總部**：611 Wilshire Blvd, Suite 300, Los Angeles, CA 90017（公司標示為「Office/Fiber」），電話 (626) 549-2801。**法定登記地址不同**：20687-2 Amar Rd #312, Walnut, CA 91789。**機房收貨地址**：700 Wilshire Blvd #100 與 #200, Los Angeles, CA 90017。
- **LAX1（旗艦）— 700 Wilshire Blvd Suites #100/#200**：**自營，但幾可確定為租用套房**，非自有不動產（見更正表第 6 列）。面積 **15,000 sq ft gross**（公司自述）；DataCenterJournal 另列建物 19,440 sq ft（**建物量體，非 Psychz 白空間**）。電力：IT 負載走現場電池 UPS，機械系統走備援發電機並備現場儲油與 24×7×365 加油合約；colocation 機櫃售 **1.92 kW 至 4.99 kW** 授權電路（20A/120V 至 30A/208V），聲稱單櫃可支援至 **10kW**，並針對**單卡 GPU 部署**提供 per-kW 選項。**全設施總 MW＝GAP**。進駐電信商：Comcast、GTT、Hurricane Electric、Cogent、China Unicom、China Telecom、PCCW、Any2 IX 與 CN2 Premium；DataCenterJournal 另補 Zayo 暗光纖（[LA 機房頁](https://www.psychz.net/los-angeles-data-center.html)）。
- **One Wilshire — 624 South Grand Avenue**：互連／光纖據點，租用或授權空間。One Wilshire 業主為 GI Partners 的 TechCore（CalPERS 支持），meet-me room 由 CoreSite 營運（LA1，約 187,533 sq ft、35 個套房）。**Psychz 的佔用面積＝GAP**。
- **CoreSite 各市場**：LA、Chicago、北維吉尼亞／華府、Atlanta（CoreSite AT1，55 Marietta Street）——皆為租用，Psychz 是 CoreSite Marketplace 掛牌服務商（[CoreSite Marketplace](https://www.coresite.com/marketplace/psychz-networks)）。
- **Dallas, TX 與 Ashburn, VA**：租用。社群來源（LowEndTalk，**未證實**）指 Dallas 站為「Prime Data Center」。Colocation 價目：Ashburn 20U 半櫃 1.92 kW $599/月；42U 整櫃 1.92–4.99 kW $907–$2,332/月（設定費 $2,250）；帶鎖整櫃 1.92 kW $608/月、4.99 kW $1,058/月（[colocation 頁](https://www.psychz.net/colocation.html)）。
- **國際**：London、Amsterdam、Barcelona、Moscow、Johannesburg、Mumbai、Singapore、Taipei、Tokyo、Seoul、Sydney、São Paulo，皆為租用／夥伴設施。**設施數三方衝突**：PeeringDB 列 16、官網 network 頁稱 17、colocation 頁一度出現 **66**——**66 幾可確定是夥伴／轉售足跡，不得引述為 Psychz 自營站點數**。

**硬體機隊與證據等級**
- **Supermicro＝強旁證，非廠商聲明**（完整論證見更正表第 8 列）。**無任何機殼或主機板型號公開。**
- **由線上訂購頁觀測到的 CPU 組合（推論平台族系用）**：Xeon E3-1230 v2／E3-1230 v5／E3-1270 v5／E3-1270 v6、**Core i7-7700K**、Xeon E5-1650 v3、雙 E5-2620 v2/v3/v4、雙 Xeon Silver 4214（24c）／4216（32c）、雙 Xeon Platinum 8270（52c）；RAM 16GB–256GB；單路至 4 顆硬碟、雙路至 8 顆；上行 100 Mbps 至 40 Gbps。**這是由公開組態推得的平台族系推論，不是廠商揭露。**
- **Intel（其自家參考架構明載）**：「5th, 4th, and 3rd Gen Intel Xeon Scalable processors, Intel Xeon processor, Intel Atom processors」、Intel Data Center GPU Flex Series、Intel Arc Series GPU、NVMe SSD 與企業級 HDD，並註明「BIOS information can be provided upon request」。**代表 Ice Lake／Sapphire Rapids／Emerald Rapids 的換機週期正在進行中**，但同一份文件**未具名任何機殼廠、RAID 卡、網卡或交換器**（[參考架構](https://www.psychz.net/client/kb/en/reference-architecture--dedicated-server-deployment.html)）。
- **AMD**：EPYC 僅列為 GPU／AI 系統的 CPU 主機選項，**標準裸機庫存中無任何 EPYC SKU**，研判為報價制／AI 專屬層。
- **Juniper Networks（網路層，非伺服器）**：MX960 與 MX240 全球部署。**標記：次級擷取**——Juniper HTML 頁已 301 轉址至 hpe.com，PDF 內文為子集字型編碼無法完整抽取，型號與客戶名單來自搜尋引擎對該頁的擷取（[Juniper PDF](https://www.juniper.net/content/dam/www/assets/case-studies/us/en/3520727-en.pdf)）。
- **Dell／HPE／Lenovo 作為伺服器供應商＝查無證據，視為開放的競爭槽位**。
- **「Rack n' Stack」＝未證實**，僅出現在對 Juniper 案例的搜尋摘要中，無法對照原始頁面，**不得用於任何對客資料**。

**GPU 產品線與價格**
**有，且正在行銷，但全部報價制、零公開價**——這是最強的近期切入點：他們在賣 Blackwell 級容量，卻**沒有設定器、沒有公開 SKU、沒有具名平台廠**，符合「逐案採購 GPU 節點」而非「有常設供應協議」的樣態。
- 明列型號：**H100（80GB SXM 與 94GB NVL）、H200 141GB HBM3e、B200（Blackwell，每卡約 180GB HBM3e）、B300（Blackwell Ultra，每卡 288GB HBM3e）**；部署選項為單卡、2–4 卡、至 8 卡企業系統，月租與客製期間皆可。GPU 主機問答另提及 A100、V100、T4、RTX 3090、RTX 4090。主機 CPU：AMD EPYC 或 Intel Xeon（[ai-llm 頁](https://www.psychz.net/ai-llm.html)）。
- **定價＝GAP**。AI/LLM 頁只有含預算下拉（$0-$100 至 $1000+）的聯絡表單，Q&A 明寫請提供完整規格向團隊索取報價。**對比之下其 CPU 庫存完全標價且可自助下單（$9.60/月 E3-1230 v2 至 $1,159/月 雙 Platinum 8270）——這個不對稱本身就是訊號：GPU 是刻意設下的報價閘門，不是疏漏。**
- **ai-llm 頁未提及任何機殼製造商**（無 Supermicro、無 Dell、無 NVIDIA DGX/HGX 字樣）。

**規模**：伺服器數、機櫃數、機箱數**全部未公開（GAP）**。可用代理值：LA 15,000 sq ft、16–17 個設施、機櫃售 1.92–4.99 kW（可支援至 10 kW）、AS40676 宣告 **188,928–283,904 個 IPv4（來源不一）**。**由 IP 數推得「數千台實體伺服器」純屬推論，不得當作事實引用。** 線上庫存多個 SKU 顯示缺貨並開候補；社群回報曾因「out of hard drives」導致 3 週交機延遲（**社群來源、未證實**）——兩者都是對硬體供應商有利的供給緊縮訊號。
**員工數三方互相矛盾（皆為第三方估計）**：LinkedIn 11–50；LeadIQ 約 11（2025-08）與約 8（2026-04）；Inc.com 51–200。社群指支援外包至印度（未證實），可解釋美國本地人數偏低。
**絕對營收＝GAP**，Crunchbase、PitchBook、ZoomInfo、Owler、D&B 皆無金額。成長證據僅來自上述 Inc. 5000 名次［第三方估計／公開榜單］。

**已具名客戶**：**Verizon、Baidu、XO**，以及「25,000 customers」——**全部出自單一 Juniper 案例研究，且為次級擷取（HTML 已轉址、PDF 內文無法抽取）**，**放進任何對客資料前必須先行驗證**。註：XO 已於 2017 年被 Verizon 併購，該引用應早於案例的 2020 年發布日。公司 About 頁另稱 2006 年共享主機時期有 100,000 客戶——**不同年代、不同產品線，不可與 25,000 相互調和**。方向相反的兩個關係：**Noction**（Psychz 是**買方**，部署 IRP 改善亞洲連線，[Noction 客戶頁](https://www.noction.com/clients/psychz_networks)）；**CoreSite／American Tower**（Psychz 是**房客**）。行銷客群：主機商／轉售商、遊戲伺服器、CDN／媒體遞送、AI/LLM GPU 租戶。

**網路**：AS40676，ARIN 註冊，約 18 年 BGP 網路。前綴數依來源而異：bgp.he.net 為 482 個 IPv4 前綴／188,928 個 IPv4／117 個 IPv6 前綴／247 個 BGP peer／14 個 IX；BGPView 為 517 個 IPv4 與 124 個 IPv6 範圍、合計 283,904 個 IPv4、跨 23 國、241 個 peer、8 個上游。RPKI：426 個有效 ROA、17 個 invalid。**官網稱「6 Tbps+ Network Connectivity」，PeeringDB 自報實際流量落在 1–5 Tbps 區間——請注意容量與實際流量是兩種量測，不可混用。** 開放 peering。交換點：Any2（LA）、Equinix Chicago、LINX、MSK-IX 與 DATA-IX（Moscow）、NAPAfrica、JPIX／JPNAP／BBIX（Tokyo）、TPIX（Taipei）、DE-CIX Mumbai、IX.br（São Paulo，30G）、CATNIX，多數為 10G 埠。核心路由 Juniper MX960／MX240。LA looking glass：lg.lax.psychz.net。（[PeeringDB net/6747](https://www.peeringdb.com/net/6747)）

**政治紀錄（僅公開紀錄，並附標記）**
- **Yangjian Wu**［公開紀錄｜**員工層級，非業主**｜重要性低］：FEC 個人捐獻紀錄，雇主「PSYCHZ」、職業 Engineer、San Diego CA，多筆 **$1.00** 經 WINRED（C00694323）轉捐，指定 Save America 與 Trump 競選。金額僅象徵性，符合名單簽署／請願式捐輸而非實質政治活動。
- **Boyu Wu**［公開紀錄｜員工層級｜重要性低］：雇主「Psychz Network」、職業 Manager、Los Angeles CA，經 ActBlue（C00401224）捐 **$2.70** 指定 Bernie 2020。
- **William H. Lu（CEO／業主）**［**GAP｜未證實——僅為查無，不等於沒有**］：以雇主「Psychz」與「Profuse Solutions」查詢 FEC 皆無紀錄。**刻意未以「Lu, William」做純姓名檢索**，因該姓名在加州過於常見，無雇主對應時貿然歸屬會有錯認風險。（[FEC API 查詢](https://api.open.fec.gov/v1/schedules/schedule_a/?api_key=DEMO_KEY&contributor_employer=Profuse+Solutions)）
- **Profuse Solutions, Inc.／Psychz Networks（法人）**［公開紀錄｜得標紀錄未證實｜GAP］：查無企業 PAC、聯邦遊說登記、州級政治活動。但**存在聯邦供應商登記**：GovTribe 有「Profuse Solutions Inc. / Psychz Networks」廠商檔案，顯示已在 SAM.gov 註冊——**可作為公部門通路的線索，惟本次未確認任何得標紀錄**（[GovTribe](https://govtribe.com/vendors/profuse-solutions-inc-dot-psychz-networks-7vvq0)）。

**公開聯絡管道**：銷售 **sales@psychz.net**（GPU/AI 頁與 GPU Q&A 皆導向此信箱，另有 psychz.net/dedicated-hosting.html#Quote 報價表單）；美加免付費 **800-933-1517**；國際暨 LA 總部 **+1 626-549-2801**；NOC **noc@psychz.net**（PeeringDB 技術聯絡人）；濫用 abuse@psychz.net；會面地址 611 Wilshire Blvd, Suite 300, Los Angeles, CA 90017；[LinkedIn showcase 頁](https://www.linkedin.com/showcase/psychz-networks/)（**注意這是 showcase 子頁而非獨立公司頁**）；母公司 [profusesolutions.com](https://www.profusesolutions.com/)。**因公司僅公布名＋姓氏首字母，主管個人 email 皆非公開，須經 sales@ 或 LinkedIn 轉介。**

**GAP 清單（Psychz）**：GPU 全線無公開價／伺服器與機櫃數／各站電力總量／LA 機房不動產產權（「擁有」無法佐證）／Supermicro 的直接確認（無機殼型號、無照片、無導覽、無職缺、無員工發言）／絕對營收／員工數三方矛盾且查無徵才頁／主管全名／股權比例／客戶名單僅單一來源且為次級擷取／「Rack n' Stack」無法驗證／設施數 16 vs 17 vs 66 衝突／創立年份 1999 vs 2001 vs 2012 vs 2014 衝突／業主政治紀錄僅為查無／CA SOS 第一手頁面 403 需重拉／無狀態頁、無 SLA 賠償表（colocation 僅有 4 小時硬體更換 SLA 窗口）、無擴充路線圖。

---

### 4.3 ReliableSite（RELIABLESITE.NET LLC）— Supermicro 證據最強，但轄區不在一組，且已自行走向自製機殼

**法人與所有權**
**RELIABLESITE.NET LLC**，Florida Division of Corporations 文件編號 **L14000189024**，EIN 47-2515613，狀態 Active，設立 **2014-12-11**；主要地址 2115 NW 22nd St, Miami, FL 33142；註冊代理人與唯一列名幹部皆為 **Rodion R Davydov（Chief Executive Officer）**。BBB 獨立列出相同地址與「Rodion Davydov, CEO」。**注意：2014 年的 FL 法人晚於品牌自稱的 2006 年起點，公開檢索查無 2014 年以前的任何州登記前身。**（[FL 登記](https://bisprofiles.com/fl/reliablesite-net-l14000189024)）
- **Rodion R. Davydov（公開使用「Radic Davydov」）＝創辦人暨 CEO，兼註冊代理人**。LowEndBox 專訪描述他原為軟體工程師，2006 年在父親買主機公司失利後構思本業；他在 LowEndTalk 以 Host Rep 帳號「MrRadic」發言（[LowEndBox 專訪](https://lowendbox.com/blog/custom-built-for-success-interview-with-radic-davydov-ceo-of-reliablesite/)）。
- **無外部投資人／無機構持股**：About 頁自稱「a financially stable and debt-free company」且「Our servers and equipment are 100% owned and operated in-house」；FL 申報僅一名幹部，Crunchbase 亦無募資輪。視為創辦人自有；**FL 的會員權益非公開紀錄**。

**總部與各資料中心**
**兩個真實可拜訪地點：Piscataway NJ ＋ Miami FL。無紐約市地址。**
| 站點 | 自有／租用 | 面積與電力 | 說明 |
|---|---|---|---|
| **QTS Piscataway PNJ1 — 101 Possumtown Rd, Piscataway, NJ 08854**（其行銷之「New York City Metro」，SKU 帶「PNJ」碼） | **租用 colocation**；建物由 QTS 營運（Blackstone 自 2021-08 持有，前身 DuPont Fabros）。ReliableSite 擁有內部伺服器與網路，不擁有設施 | 全設施 360,000 sq ft／約 176,000 sq ft raised floor、額定約 52–65 MW——**皆為 QTS 整棟數字，ReliableSite 自身的 cage 面積與 kW 配額未公開（GAP）** | 其自家徵才貼文招募 Piscataway 駐點 Data Center Technician，Yelp／D&B 亦將人員定位於此址 |
| **165 Halsey Street Meet-Me Room, Newark, NJ** | 租用／僅互連 | GAP／GAP | AS23470 互連設施，與 NY-metro transit 組合（NTT、GTT、TATA、Arelion）及 DE-CIX New York／NYIIX peering 一致 |
| **CoreSite MI1 — 2115 NW 22nd St, Miami, FL 33142**（同時是法定登記地址） | 租用 colocation（CoreSite，現屬 American Tower） | 設施約 43,000+ sq ft（CoreSite 整棟數字）；**ReliableSite 自身 cage 面積與電力＝GAP** | 於此設有駐點 Miami 機房技師（[CoreSite MI1](https://www.coresite.com/data-center/mi1-miami-fl)） |
| **Equinix MI1 — Miami, FL** | 租用／互連 | GAP | 亦於 Equinix Miami 交換點以 100G peering |
| **CoreSite LA1（One Wilshire, 624 S Grand Ave）與 LA2（900 N Alameda St）, Los Angeles** | 租用（CoreSite／American Tower） | GAP | 2017 年新聞稿宣布進入 LA；於 Any2West 以 100G peering。**目前唯一在售的 NVIDIA A10 GPU 機種即列在 Los Angeles** |
| **Amsterdam — Equinix AM7 與 Databarn** | 租用 | GAP | AMS-IX 與 ERA-IX peering，transit 供應商 NForce，looking glass 為 nl1-lg.reliablesite.net |
| **Querétaro, Mexico（QRO）— 「coming soon」** | 租用、carrier-neutral（**營運商未具名，GAP**） | GAP | 官方頁列出直連 PIX México 1 與 2；network 頁顯示 QRO「Network Test Coming Soon」並列出 IENTC／Wantelco peering——**建置中，是最可能的近期硬體採購觸發點**（[Querétaro 頁](https://www.reliablesite.net/data-center/queretaro-mexico.aspx)） |

**硬體機隊與證據等級**
- **Supermicro＝已確認（本檔最強）**，但**必須連同下一條一起講**。證據三條：兩則獨立 WHT 客戶評述（其一為 Atom D510 舊世代 barebones）＋ CEO 於 LowEndBox 專訪親口討論 Supermicro MicroCloud。**當世代 SKU 級確認＝GAP。**
- **自製機殼（whitebox）＝已確認，且是本案的關鍵競爭動態**：CEO 自述在 MicroCloud 替換零件斷貨、且價格為「2-3 times the cost」之後，自行設計密度較標準 1U 高約 50% 的專屬機殼，**並刻意讓它相容於市售主機板與電源**；訪談時另有目標密度 +100% 的原型在開發中。公司行銷亦呼應「each server built in-house with enterprise grade hardware」與「custom hardware design and manufacturing」。**銷售意涵：機殼是他們的，但主機板／板級這個插槽是開放的。**
- **由公開規格推得的平台（廠牌未具名，屬推論）**：機隊高度偏向**單路桌上型／工作站級矽晶**而非雙路 Xeon Scalable——Intel Core i7 9700K、i9 9900K／10900K／13900K／14900K；AMD Ryzen 5600X、3700X、7700、8600G、5900X、7900、9900X、5950X、9950X；Threadripper 7995WX；**AMD EPYC 4545P（16C/32T Zen 5，65W，EPYC 4005 系列）**。RAM 32GB DDR3 至 256GB DDR5，儲存 512GB–4TB NVMe。**推得**：LGA1700/1200、AM4/AM5、sTR5 與 AM5 基礎的 EPYC 4004/4005 單路板，置於高密度多節點／1U 托盤中。**此為由 CPU/RAM/機殼描述推得，非公開的廠商 SKU。**
- **Dell＝查無證據**；**HPE＝查無證據**（全網無 PowerEdge／iDRAC／ProLiant／iLO）。**不得假設有 Dell 既有關係。**
- **採購型態＝現場備料、整盤直上機櫃**：Facebook 貼文標題「AMD EPYC 4545P: From tray to rack... we keep our inventory on site」；徵才描述「onsite server builds and decommissions」與「racking and stacking servers and network equipment」。**現行零件供應痛點（第一手）**：CEO 以「MrRadic」在 LowEndTalk 公開表示特定 SSD／RAM 零件出現「800% cost increase」且交期 3 個月以上（[LowEndTalk offer thread](https://lowendtalk.com/discussion/218739/us-eu-dedicated-servers-epyc-4545p-ryzen-5800x-intel-core-i9-9900k-more-new-metal-benefits)）。

**GPU 產品線與價格**
**有，但極薄，本質是加購項而非 AI 平台——這是本案最清楚的 AI 缺口。**
- **NVIDIA Quadro RTX 4000**：跨多個 CPU 層級的 **$99/月**加購（依機房與庫存而異）。
- **NVIDIA A10**：唯一一款專屬組態（AMD Ryzen 7900 12C/3.70GHz、128GB DDR5、2×2TB NVMe），**$699/月**，列於 Los Angeles，**庫存 1 台**。
- **完全沒有 L40S、A100、H100、H200、RTX 6000 Ada，也沒有任何多卡或 8 卡平台。**
- 整體專用伺服器價帶 $49–$699/月。**反差點**：他們行銷「GPU AI Dedicated Servers」、把 EPYC 4545P 定位為 AI inferencing，甚至有 AI 視覺客戶案例，**但支撐這套訊息的實際加速器機隊只有一款 A10 加一張入門加購卡**（[GPU AI 頁](https://www.reliablesite.net/dedicated-servers/gpu-ai-dedicated-servers/)）。

**規模**：伺服器數、節點數、機櫃數**皆未公開（GAP）**。最佳代理：AS23470 originates 199 個 IPv4 前綴、約 **50,944 個 IPv4**，另 29 個 IPv6 前綴；PeeringDB 自報 1000 個 IPv4／250 個 IPv6 前綴容量。**由此推「低至中千台」屬推論，不得引為事實。** 員工 **11–50（LinkedIn 自報，347 追蹤者）**，含 Piscataway 與 Miami 的支薪駐點技師（Glassdoor 約 $60K 級距）與 24/7 自有支援。**營收：Kona Equity 估 $1.2M［第三方估計］、Owler 估每員工 $27.6K［第三方估計］——警告：$1.2M 與約 51K 個 IPv4、5 個 IXP 100G 埠、1–5 Tbps、六個租用機房區域與 11–50 名員工明顯不相稱，光是機房費＋transit＋薪資很可能就超過此數。全部視為低可信度第三方模型，不是事實。**（[Kona Equity](https://www.konaequity.com/company/reliablesitenet-llc-4395702578/)）

**已具名客戶（皆為公司自行發布之案例）**
- **Scirra Ltd**（Construct／Construct 2 HTML5 遊戲開發軟體）：規格 4 核 3.2GHz／8GB RAM／SQL Server 授權，部署於 NY metro 與 Miami；共同創辦人 Tom Gullen 具名引述，Ashley Gullen 亦具名。**規格年代顯示為舊案例。**（[案例](https://www.reliablesite.net/hosting-news/scirra-dedicated-server-case-study/)）
- **CloudieWeb.com**（雲端主機／VPS／專用伺服器轉售商）：CEO Erkan Saliev 具名引述，部署於 NY metro——**證實其存在批發／轉售客層，這類客戶帶來成批、可重複的伺服器訂單**（[案例](https://www.reliablesite.net/hosting-news/cloudieweb-server-case-study/)）。
- **Little Planes Farm**（畜牧與飼料零售，跑 AI 視覺工作負載），案例日期 2025-11-21：AI 攝影機系統追蹤客戶取貨、清點飼料袋、核對訂單正確性，加上人臉辨識與自動門禁，「run entirely on ReliableSite's high-performance dedicated servers」——**在一個幾乎沒有 GPU 容量的機隊上，這是直接的 AI 推論需求訊號**（[案例](https://www.reliablesite.net/hosting-news/inside-smart-farms-ai-setup-powered-reliablesite-servers/)）。
- **Let's Encrypt（ISRG）＝贊助關係，非付費客戶**，僅供可信度鋪陳。
- 另已推出 **reseller/developer API**（HostingJournalist 報導），並在 LowEndTalk／WHT／HostingDiscussion 大量做在地行銷，顯示主機轉售商與高頻寬／易受 DDoS 客群（遊戲、串流、媒體）佔比可觀。**三則案例以外的具名企業客戶＝GAP。**

**網路**：AS23470（ReliableSite.Net LLC，ARIN），ASN 註冊於 2018-08-10；originates 199 個 IPv4 與 29 個 IPv6 前綴、約 50,944 個 IPv4（觀測前綴合計 267：231 IPv4／36 IPv6）。Looking glass：ny1-lg、mi1-lg、la1-lg、nl1-lg.reliablesite.net（QRO 尚未開通）。PeeringDB 自報流量 **1–5 Tbps**、以出向為主；官網稱「multiple 40 Gbps uplinks per switch」與每台伺服器可達 10+ Gbps；**各 IXP 皆為 100 Gbps 埠**；宣稱 100% 網路正常運行 SLA 與 0% 封包遺失保證；自建 L3/L4 DDoS 過濾系統，CEO 另表示有以機器學習為基礎的深度封包分析系統在開發中。上游 8 家、對接約 153 個網路。Transit：NTT America（AS2914）、TATA（AS6453）、GTT（AS3257）、Arelion、Comcast（AS7922）、Hurricane Electric（AS6939）、NForce（AS43350）。公開 peering（皆 100G）：Any2West、DE-CIX New York、Equinix Miami、FL-IX、NYIIX；另列 AMS-IX、ERA-IX、Near IP、IENTC、Wantelco。**Peering 政策：OPEN**（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)）。

**政治紀錄（僅公開紀錄，並附標記）**
- **Rodion R. Davydov／「Radic Davydov」**［**GAP｜未證實**］：FEC 個人捐獻查詢與 OpenSecrets 捐款人查詢，以姓名「Davydov」搭配雇主「ReliableSite」皆無回傳結果。**但兩者皆為 JavaScript 驅動介面、無法以程式查詢，因此這是「未能證明的負面結果」，不是已驗證的「沒有捐獻」**；須人工至 fec.gov/data/receipts/individual-contributions 手動查詢方能結案。另請注意 **$200 以下的捐獻本來就不會進入公開紀錄**。
- **RELIABLESITE.NET LLC（法人）**［公開紀錄｜查無］：查無企業 PAC、遊說登記、聯邦承包或補助；私人 LLC 故無 SEC 申報；查無公會理事席次、政府事務人員或公共政策立場。唯一近似公民參與的紀錄是**贊助 Let's Encrypt 憑證機構**（技術／非營利，非政治）。
- **監理／聲譽註記（非政治，但列入客戶規劃）**［公開紀錄］：**BBB 對 RELIABLESITE.NET LLC 評等為「F」、未取得認證，理由為「Failure to respond to 5 complaint(s) filed against business」**，檔案開立於 2018-02-26。**這是客服聲譽訊號，不是法律或監理處分**；查無任何訴訟、執法或制裁紀錄（[BBB](https://www.bbb.org/us/fl/miami/profile/web-hosting/reliablesitenet-llc-0633-90409819)）。

**公開聯絡管道**：免付費 **+1 (866) 932-0001**；**銷售 sales@reliablesite.net（主要外展路徑）**；支援 support@reliablesite.net；**徵才 careers@reliablesite.net（可觸及機房營運／基礎設施主管）**；法務 legal@reliablesite.net、申訴 complaints@reliablesite.net；[支援入口](https://support.reliablesite.net/Main/)；[LinkedIn 公司頁](https://www.linkedin.com/company/reliablesite)（11–50 人、347 追蹤者、founded 2006）。**具名決策者＝CEO Rodion R.「Radic」Davydov**——公開路徑包括 LowEndTalk Host Rep 帳號「MrRadic」（他本人親自回覆硬體與零件成本問題）、公司帳號「ReliableSiteHosting」、以及 LowEndBox 具名專訪。**在 11–50 人規模且他具工程背景的情況下，他極可能就是硬體採購的直接決策者；查無任何 VP Infrastructure 或採購職稱。**

**GAP 清單（ReliableSite）**：伺服器／節點／機櫃數／各設施自身的 sq ft、cage 面積與合約 kW（現有數字全為房東整棟值）／當世代 Supermicro SKU 級確認／**自製機殼所用的主機板廠——本檔商業價值最高的單一未知**／確切員工數／可信營收數字／CEO 以外任何具名主管／FEC 紀錄未結案（需人工查詢）／2014 年之前的公司沿革（8 年登記空窗）／Querétaro 設施營運商未具名／換機週期、年度採購量與現行硬體供應商／三則案例以外的具名客戶。

---

### 4.4 Sharktech, Inc. — 一組自有轄區，Lenovo 為既有廠商的替換／第二供應商標的，並有明確時間窗

**法人與所有權**
**SHARKTECH, INC.**（BBB 別名「Sharktech Internet Services」）。Nevada 登記：實體編號 **E0295442013-6**、商業編號 NV20131360657、類型 **FOREIGN CORPORATION**、狀態 Active、於 2013-06-14 在 Nevada 登記，**本籍為 Montana**。註冊代理人 **TIM TIMRAWI**，2681 E Hacienda Avenue, Las Vegas, NV 89120，登記為 Noncommercial Registered Agent。**銷售須知：Nevada 這份是外國公司資格登記，原始章程在 Montana——Montana SOS 紀錄本次未取得（GAP）**；esos.nv.gov 與 Bizapedia 皆為 CAPTCHA／Incapsula 阻擋，未予繞過（[NV 登記](https://www.nevada-register.com/1182880-sharktech-inc)）。
創立年份：公司自稱 2003（sharktech.net/about）；BBB 記載「Business Started: 8/19/2003」與「Business Started Locally: 4/14/2014」；ARIN AS46844 註冊於 2009-03-31，ARIN 組織代碼 SHARK-7 註冊於 2012-01-20。**2003 為公司主張，非登記事實。**
- **Tim Timrawi（Tim M. Timrawi）＝創辦人暨 CEO；登記之 President、Treasurer、Director，兼註冊代理人**。他親自具名發布客戶公告（如 2026-04-07 Denver 遷移通知：「Hi, it's Tim Timrawi, the Founder and CEO of Sharktech」）。**ARIN 行政 POC 即為 TMT-ARIN / TIM M TIMRAWI / timt@sharktech.net / +1-702-425-9980。**
- **Erin Timrawi＝Corporate Secretary（NV 登記）**，BBB 列為「Managing Member」。**外觀為家族封閉持股。**
- **外部投資人＝GAP**，查無募資、機構投資人、PE 持股或併購。**採購決策幾可確定直接經由 Tim Timrawi。**

**總部與各資料中心**
公司總部與郵寄：**8560 S. Eastern Ave., Suite 210, Las Vegas, NV 89123**——**這是辦公套房、不是機房**。另有兩個地址出現在紀錄中：幹部／註冊代理人地址 2681 E Hacienda Avenue, Las Vegas, NV 89120，以及 BBB 所列 3315 E Russell Rd STE A4 PMB 112, Las Vegas, NV 89120-3477（[contact 頁](https://sharktech.net/contact/)）。

| 站點 | 自有／租用 | 面積與電力 | 重點 |
|---|---|---|---|
| **Las Vegas, NV — Flexential Las Vegas** | 租用／colocation（房客，非設施擁有者） | Sharktech 自身 cage／機櫃／sq ft **＝GAP**。設施層第三方數字：Flexential Las Vegas - North 111,240 sq ft、9.00 MW［第三方估計，描述整棟而非 Sharktech 佔用］ | 唯一與總部同城的站點，**也是其唯一 GPU SKU 所在地**。進駐電信商 Comcast、GTT、TATA、Cogent，「Up to 400 Gbps connectivity」，PCI DSS／HITRUST CSF／FISMA／ISO／SOC／ITAR 合規（**均為機房營運商持有的合規，非 Sharktech**）（[LV 機房頁](https://sharktech.net/data-centers/las-vegas/)） |
| **Los Angeles, CA — One Wilshire** | 租用／colocation | GAP；頁面僅稱 UPS/PDU/RPP 具 N、N+1、2N 冗餘與「Six 9s 歷史組合正常運行率」（**營運商聲明**） | 自稱「Over 1Tbps of Internet Connectivity」與亞太連線優勢，電信商含 Comcast、GTT、TATA、China M[obile]。LA 與 Amsterdam 售價最高 |
| **Denver, CO — 正在遷移：H5 Data Centers → US Signal COO1** | 租用／colocation | Sharktech 佔用＝GAP。H5 Denver 園區 300,000 sq ft（設施層，2016 新聞稿） | **本檔發現的最高價值銷售觸發事件。** CEO 於 2026-04-07 公告：「Sharktech will move our Denver point of presence from H5 Data Centers to US Signal COO1... the migration will start on May 1, 2026, and is scheduled to be fully complete by May 31, 2026.」裸機客戶收到一週搬遷通知，colocation 客戶須於 2026-05-29 前遷離設備。**實體機房搬遷是典型的硬體更新窗口。**（[Denver 遷移公告](https://portal.sharktech.net/index.php/announcements/236/Denver-migration.html)） |
| **Chicago, IL — 365 Data Centers** | 租用／colocation | GAP；頁面稱 N+1 或 2N+1 UPS 冗餘、Level 3 ID Security、10+ 年 100% 正常運行 | 自稱「Over 1Tbps」，HIPAA／ISO／PCI／SOC 合規 |
| **Amsterdam, NL — Equinix AM11** | 租用／colocation | **設施層（非 Sharktech 佔用）：8,320 m² / 89,555 ft²**，由 Sharktech 自家頁面引述；自身 cage 面積 GAP。電力：發電機 N+1、UPS/PDU/RPP N、N+1、2N | 唯一非美國站點，AMS-IX 100G 為其唯一公開交換點；EPYC 定價最高（$499/$699，對比美國 $459/$659）（[AMS 機房頁](https://sharktech.net/data-centers/amsterdam/)） |

**硬體機隊與證據等級**
- **Lenovo＝直接、已確認，且是他們唯一一次公開具名的伺服器品牌。** 客戶入口公告 #221（2025-01-16）推出 AMD EPYC 7702P 裸機平台（EPYC 7702P 64C/128T、256GB DDR4、2TB NVMe 可擴充至 14 顆 NVMe U.2、10G 共享不限流量可至 40Gbps，於 Los Angeles 與 Las Vegas 供應，$599/月起），**規格行逐字寫「System: Lenovo」**。同一公告另註明「initial quantities are limited, and delivery may take up to 10 days」——**顯示小批量採購、非常備庫存**（[公告 #221](https://portal.sharktech.net/index.php/announcements/221/Now-Available-AMD-EPYC-7702P-with-NVMe-U.2.html)）。
- **未具名的第三方供應商／經銷商＝行為已確認、廠商未具名。** 兩則 2026 年公告證實他們透過經銷通路進貨並自行整合，而非採購成品品牌機：（i）2026-07-13「we received a new batch of EPYC 7702 servers from our supplier, and they're now available in all US locations」；（ii）2026-07-01「we're upgrading our flagship Xeon Gold 6148 server to Dual Xeon Gold 6248 CPUs. **We're currently building 12 of them in Las Vegas.**」——「我們正在組 12 台」正是準系統／元件買家的樣態，**恰好就是 Supermicro barebone／BTO 銷售動作的目標客型**。批量小（12 台）、周轉快（「usually sold out within 48 hours」），代表緊湊、重複、小量的採購節奏。**供應商名稱全網未具名（GAP）。**
- **機隊主體的機殼／平台廠＝僅為推論，未確認。** 由其即時產品資料（servers.json，51 個 SKU）擷取的槽位特徵：24×SATA/SAS 3.5"（5 個 SKU）、12×3.5"（6）、8×3.5"（5）、6×3.5"（5）、6×SATA/SAS 2.5"（10）、3×3.5"（5），NVMe 層 10×U.2（10）、6×U.2（5）、4×U.2（5）、2×M.2（31）。在庫 CPU 平台：雙 Xeon E5-2695v4（21 個 SKU）、雙 Xeon Gold 6248（20）、EPYC 7702P（5）、雙 EPYC 7702（5），RAM 至 1TB。**已逐頁比對後確認「Supermicro／Dell／PowerEdge／HPE／ProLiant／Gigabyte／Tyan／ASRock」在其全部資產中為 0 命中。** 另一個弱訊號：2026 年公告「we are upgrading all IPMI interfaces to HTML5 to eliminate compatibility issues and Java-related errors experienced with older IPMI consoles」——**全機隊泛稱「IPMI」（而非 iDRAC／iLO／XClarity）符合 Supermicro 級板卡的特徵，但這只是待驗證假設，不是發現。**
- **Supermicro＝查無任何證據（明確的負面發現，特此記錄以免銷售帶著錯誤前提進場）。**
- **軟體／虛擬化堆疊（平台適配脈絡）**：OpenStack（公私有雲）、Proxmox（Smart-VPS）、Virtuozzo（具名 PaaS 夥伴）、cPanel、Acronis Cyber Protect、S3 相容物件儲存 $4.9/TB。**相關性：物件儲存 ＋ Proxmox ＋ OpenStack 全都拉向高密度 NVMe 與高槽位儲存機殼——正好對應他們已在賣的 24 槽與 10×U.2 SKU。**（[about 頁](https://sharktech.net/about/)）

**GPU 產品線與價格**
**有，但象徵性——51 個裸機 SKU 中僅 1 個 GPU 機種，只在 Las Vegas，且目前標記 `inStock:false`（缺貨）。這是本案最大的 AI 切入口。**
- 基礎組態：**NVIDIA RTX A4000 16GB（單卡）**。公開升級選項：雙 A4000、三 A4000、**V100 32GB**、雙 V100、三 V100。主機平台：雙 Xeon E5-2695v4（36×3.3GHz）、128GB RAM（可升 256/512/768GB/1TB）、12×SATA/SAS 3.5" 槽、2TB M.2 NVMe、10 Gbps／300TB 月流量。
- **產品線的關鍵缺口：無 L40S、無 L4、無 A100、無 H100、無 H200、無 RTX 6000 Ada、無 Blackwell——最新者不過是 Ampere 工作站卡（A4000，2021）與 Volta（V100，2017）；完全沒有 SXM／HGX 平台，沒有 4 卡或 8 卡節點，主機 CPU 還是 2016 年的 Broadwell E5。**
- 定價：**季繳 $1,140／半年 $2,280／年繳 $4,560**，**GPU SKU 無月繳價**（資料中月繳欄為 null，代表 GPU 為季繳起跳）。舊版價目頁同組態列為 $1,557/QTR。其餘裸機月租 $219–$699，GPU 節點折合約 $380/月，**定價方式就是把它當利基加購而非產品線**（[servers.json](https://sharktech.net/servers.json)）。
- **可用切入語**：Sharktech 自行行銷「upgrade CPU, RAM, GPU, or Disk configuration... Even if the hardware is not immediately available, we can work with our vendors to provide you with exact」——**即他們明說 GPU 硬體是依需求向供應商調貨**，而其唯一 GPU 節點已缺貨、且落後兩到三個世代。**當世代 GPU 平台對他們是全新產品線，而他們已證明會一次買進一整個新平台族系（Lenovo EPYC 7702P 的推出即是先例）。**

**規模**：未公開（GAP）。可用代理：（i）跨 5 站共 51 個可下單裸機 SKU，其中僅 17 個在庫，且批量明確偏小（「We're currently building 12 of them in Las Vegas」）；（ii）AS46844 originates 413 個 IPv4 前綴與 9 個 IPv6 前綴，合計 **124,416 個 IPv4**；（iii）colocation 以 1–6U（200–1200W）與 10–42U 機櫃（1600–5500W）出售，顯示租的是機櫃／cage 而非整個機房。**員工數第三方數字互相衝突（皆為估計）**：LinkedIn 11–50（48 位關聯成員）；公司／新聞素材稱「more than 25 employees」；ZoomInfo 18。**務實工作值：約 25–50 人。** **營收：LeadIQ 估 $10M–$25M［僅第三方估計，不得當作事實陳述］**；型錄佐證（51 個 SKU $219–$699/月、VPS $2.48/月起、雲端 $0.065/hr 起、colo $35/月起、物件儲存 $4.9/TB、宣稱 1,000–10,000 家企業客戶）與八位數美元營收區間相符但無法證實（[LeadIQ](https://leadiq.com/c/sharktech/5a1da70c23000059009a71a0)）。

**已具名客戶**
- **客戶數為公司自我矛盾**：首頁同時出現「Join more than 10,000 businesses on Sharktech」與「Join more than 1,000+ businesses」；LinkedIn 與 Virtuozzo 夥伴頁稱「over 1,000 clients across 73 countries」。**可辯護值：1,000+ 客戶、約 73 國；10,000 視為行銷語。**
- **Wings Technology Co., LTD**、**Kill-Streak Gaming**（描述為中國大陸 IDC 業者）、**ISPHELPER**——**三者皆為媒體／社群來源、未證實**，出自 HostingAdvice 的推薦語報導，該文對直接抓取回 HTTP 403，僅由搜尋片段取得；Sharktech 自家 /case-study/ 頁**未列任何具名客戶**。ISPHELPER 的引述（稱讚其針對特定伺服器需求與 failover 組態的彈性與客製能力）**正是驅動 Sharktech 客製裸機需求的客戶原型**。
- **Virtuozzo＝技術夥伴，非買方客戶**。Sharktech 自家 about 頁具名 Equinix、CoreSite、Flexential、Crown Castle 為設施夥伴，OpenStack 與 Virtuozzo 為虛擬化夥伴。
- **客群（有文件佐證）**：遊戲伺服器代管是明確垂直（Battlefield、ARK、Minecraft、Rust、GTA、CS:GO）；另有 VPN 業者、IDC／主機轉售商（美、歐、中）、SMB 與 MSP。**這是對延遲與頻寬敏感、對價格敏感、流動率高的租戶結構**，正好解釋為何是 10G 標配＋300TB 不限流量，而非高階企業 SLA。

**網路**：AS46844（ARIN AS 名稱「SHARKTECH」，組織代碼 SHARK-7，組織註冊 2012-01-20，ASN 註冊 2009-03-31，最後異動 2022-09-16）。宣告 413 個 IPv4 與 9 個 IPv6 前綴＝124,416 個 IPv4。**RPKI 衛生乾淨：414 個有效 ROA，零 invalid。** IRR 為 AS-46844，looking glass 公開於 sharktech.net/looking-glass/。**骨幹已升級至 400GE**：2026-06-25 公告「we have finished upgrading connectivity to our transit providers to 400GE-based. This is a big increase in the capacity for rapid deployment, and it further improves our ability to handle volumetric DDoS attacks.」各機房頁稱「Over 1Tbps」（Las Vegas 為「Up to 400 Gbps」）。**全部 51 個裸機 SKU 現已標配 10 Gbps／300TB 月流量，並一律提供 40 Gbps 與 100 Gbps 升級。** DDoS 清洗：每 IP 含 60Gbps 緩解，標準保護上限標示為 40Gbps，另售「100G DDoS Protection」以 BGP 將攻擊分散至全部機房。PeeringDB：開放 peering、**要求 ratio**、不需合約、全球範圍；公開 IX 僅 AMS-IX 100G；私有設施為 One Wilshire、H5 Denver、365 Data Centers Chicago、Equinix AM11。上游／對接（bgp.he.net 觀測）：NTT America AS2914、GTT AS3257、Comcast AS7922、Cox AS22773；站點素材另列 TATA、Cogent 與 LA 的 China Mobile。約 193–195 個觀測 BGP peer（[PeeringDB asn/46844](https://www.peeringdb.com/asn/46844)）。

**政治紀錄（僅公開紀錄，並附標記）**
- **Tim Timrawi（創辦人暨 CEO）**，FEC 申報雇主 SHARKTECH、城市 Henderson, NV［公開紀錄］：**217 筆列項個人捐獻，2014–2026 年間合計 $3,544.83**。型態為小額經常性——2025 至 2026 年多數月份 17 日固定出現 $10 與 $1，偶有較大筆（2026-02-19 $200、2026-04-22 $50）。依申報彙整（含家戶）：ACTBLUE（轉捐管道）$2,932.00；BERNIE 2016 $571.83；BERNIE 2020 $465.00；ALEXANDRIA OCASIO-CORTEZ FOR CONGRESS $80.00；HARRIS FOR PRESIDENT $55.00。**一致的進步派民主黨小額捐輸；查無共和黨或企業 PAC 活動。** 注意 FEC 申報城市為 Henderson NV（住所），非 Las Vegas（辦公室）。
- **Erin Timrawi（Corporate Secretary）**，雇主 SHARKTECH，Henderson, NV［公開紀錄］：**48 筆列項捐獻合計 $527.00**，同樣的 ActBlue 小額型態，最近一筆 2026-04-13 $10.00。**佐證了家戶作為申報單位，也印證家族控股的樣貌。**
- **「Chateau Timrawi」（依申報姓名）**，雇主 SHARKTECH［公開紀錄｜未證實］：5 筆合計 $32.00，可能是姓名申報變體或第三位家庭成員，**身分未獨立確認**。
- **Sharktech Inc（法人）**［GAP］：查無企業 PAC、遊說登記、州級捐獻或政府合約得標。**所有可查政治活動皆為創辦家族的個人小額捐輸，12 年合計不到 $4,200——重要性極低，無跡象顯示會影響硬體採購決策。**（[FEC 查詢](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Timrawi)）

**公開聯絡管道**：**銷售 sales@sharktech.net**——Sharktech 在硬體公告中明白把容量需求導向此處（「If you're looking to reserve capacity, please use the links below or reach out to us at sales@sharktech.net」）；銷售免付費 **+1 (844) 763-4816**；總機／NOC **+1 (702) 425-9980**（ARIN 三個 POC 皆登記此號）；**CEO 直接信箱 timt@sharktech.net（ARIN 行政 POC，本案價值最高的路徑）**——在一家創辦人自有、約 25–50 人、無外部投資人的公司，這就是實際的硬體採購決策者（[ARIN RDAP](https://rdap.arin.net/registry/entity/SHARK-7)）；支援／NOC support@sharktech.net；濫用 abuse@sharktech.net；**peering peering@sharktech.net**；[LinkedIn 公司頁](https://www.linkedin.com/company/sharktech)（890 追蹤、48 位關聯成員）；[Tim Timrawi LinkedIn](https://www.linkedin.com/in/tim-timrawi-379717b/)；總部 8560 S. Eastern Ave., Suite 210, Las Vegas, NV 89123；**[客戶入口公告區](https://portal.sharktech.net/index.php/announcements)——25 則公開存檔、中英雙語，是他們唯一一次公開揭露硬體廠商的地方，應持續監看以捕捉更新訊號**；BBB 電話 (844) 706-7383。

**GAP 清單（Sharktech）**：Montana 本籍設立紀錄未取得（原始章程、設立日、其他股東幹部皆在該處）／五個站點的伺服器、機櫃、cage 面積全數未揭露／各站合約電力／**51 個 SKU 中約 50 個的平台廠不明**／**「our supplier」的實際名稱——這是替換戰最有價值的單一未知**／換機節奏、預算與採購流程／查無任何現行職缺（故無招募方名單、無 JD 硬體需求、無人力成長訊號）／CEO 夫婦以外無任何具名機房或基礎設施人員／客戶名單未經查證／營收與員工數僅第三方估計且互相矛盾／客戶數自我矛盾（10,000 vs 1,000+）／GPU 路線圖未公開（無 AI/ML 產品頁，唯一 GPU SKU 缺貨，是否有 L40S/H100 級預算與意圖須於通話中確認）／**Denver 遷移後的實際佔用未知**（原訂 2026-05-31 完成，但其 Denver 機房頁仍在描述 H5 園區，現行機櫃數與硬體是換新或搬遷皆未知）／各站實際承諾 transit 容量（「Over 1Tbps」在四個站點頁逐字重複，讀來像樣板而非量測值）。

---

### 4.5 Hostwinds LLC — 無 GPU 的全新開發標的，但採購權可能已隨併購北移

**法人與所有權**
**Hostwinds LLC**。BBB 檔案載法定名稱、負責人「Mr. Peter Holden, Owner/Member」、地址 12101 Tukwila International Blvd Ste 320 Fl 3, Tukwila, WA 98168-2398，以及「Date of Business Started: March 14, 2016」（**應為 BBB 建檔／WA 登記日，非原始設立日**）。公司自述 2010 年創立於 Oklahoma 州 Tulsa。**Washington SOS 的 UBI 編號、正式設立日＝GAP**（CCFS 為 JavaScript 應用，無法抓取；Bizapedia／OpenCorporates 亦無紀錄）。**創立年份 2010 vs 2016 的矛盾未解。**（[BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407)）
- **HostPapa, Inc.＝母公司／收購方（2026-04-29 起）**。HostPapa 新聞稿「HostPapa Acquires Hostwinds to Expand Global Hosting Infrastructure」，**交易條件未揭露**；稿中具名 HostPapa 創辦人暨 CEO **Jamie Opalchuk** 與 Hostwinds 創辦人暨 CEO **Peter Holden**，並稱此案在 Seattle、Dallas、Amsterdam 增加「incremental Pacific Northwest and European infrastructure」。**獨立佐證：ARIN 對 AS54290 的 RDAP 現回傳組織「HostPapa」、代碼 HOSTP-7、地址 325 Delaware Avenue Suite 300, Buffalo NY 14202、最後異動 2026-05-12——ASN 已於交易後改登記。**（[新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)）
- **Peter Holden＝創辦人、CEO，併購前為唯一所有人／成員**。bgp.he.net 列他為 AS54290 的 RADB 主要聯絡人。查無外部投資人或募資輪。
- **WeLoveServers＝Hostwinds 曾收購的資產（歷史，社群來源）**：WHT 討論串「WeLoveServers bought by HostWinds?」，**原文對直接抓取回 HTTP 403，僅由摘要取得，日期與條件均未確立——標記為社群來源、未證實**。

**總部與各資料中心**
- **Seattle／Tukwila, WA — 12101 Tukwila International Blvd（Sabey Intergate.Seattle-West 園區），與總部辦公室同址**：**租用／colocation**。Hostwinds 明說自有*硬體*（「Our hardware is directly owned and sold by us」）但從未聲稱擁有建物，並自述使用「SAS Type II, audited, Tier 3+ Data centers」——**這是第三方設施的用語**，Sabey 是園區房東。**自身 cage／機櫃／sq ft＝GAP**；園區層級約 173,000 sq ft、服務多家 colocation 業者。**注意：隔壁 12201 Tukwila International Blvd 是 Wowrack 的機房（18,000 sq ft raised floor、3.0 MW），不同地址，不可混為一談。**（[機房頁](https://www.hostwinds.com/company/datacenters)）
- **Dallas, TX — Infomart Data Center, 1950 N Stemmons Fwy, Dallas, TX 75247**：租用 carrier hotel 空間。**歷史、公司自行公布的數字：Dallas 部署約 40 台伺服器、跨 3 個機箱，該機箱可擴充至 60 台**——出自約 2012–2013 年的 Hostwinds 新聞部落格。**這是十餘年前的陳舊數字，幾可確定遠低於現況，只能當地板值；現況＝GAP。**（原文網址現回 404，數字由搜尋索引片段取得，**標記為公司公布之歷史值、未於原始頁面驗證**）
- **Amsterdam, NL — Global Switch Amsterdam West, Johan Huizingalaan 759, 1066 VH Amsterdam**：租用。面積與電力皆 GAP（[速度測試文件](https://www.hostwinds.com/tutorials/how-to-test-speed-to-hostwinds-data-centers)）。
- **Colocation 轉售市場（10 個）**：Buffalo、Dallas、Atlanta、Chicago、Seattle、San Jose、Los Angeles、New York City、Dublin、Toronto。**Hostwinds 只曾聲稱三個自有機房（Seattle／Dallas／Amsterdam），卻在十個市場賣 colo——另外七個幾可確定是夥伴／轉售空間。注意 Buffalo NY 與 Toronto 正好對應 HostPapa 自身版圖（HostPapa 的 ARIN 地址即在 Buffalo NY），此清單可能已反映併購後的合併容量。** 公開規格僅四級：1U 單機、20U 半櫃、42U 整櫃、2×42U cage；**公開電力：單機 1A/120V、半櫃 1.92 kW、整櫃 3.84 kW、cage 7.68 kW——密度很低，3.84 kW/櫃在未升級電力與冷卻前無法承載現代 GPU 或高核心數節點**（[colocation 頁](https://www.hostwinds.com/colocation)）。

**硬體機隊與證據等級**
- **系統廠＝完全未證實（見更正表第 10 列）。這是真實的證據缺口，不是檢索不足。**
- **唯一推論訊號（僅為推論）**：其文件把專用伺服器控制台描述為提供「full IPMI access to VNC KVM controls, power controls, and ISO mounting」，按鈕為「BMC Cold Reset」「BMC Warm Reset」「Get Console Link」。**有品牌 BMC 的原廠通常以品牌名行銷（Dell 講 iDRAC、HPE 講 iLO）；泛稱 IPMI／BMC cold and warm reset／Java 或 HTML5 KVM 主控台，是 Supermicro 與其他 whitebox／ODM BMC 的標準用語。全網零則 iDRAC 或 iLO。——僅為命名慣例訊號，不是證明，且混合機隊完全可能。**
- **由線上訂購表單推得的 CPU 機隊（本案最強的硬體證據）——Intel Xeon 與 AMD Opteron，全部早於 Xeon Scalable 世代**。目前可下單的全部機種與月租（[購物車 gid=12](https://clients.hostwinds.com/cart.php?gid=12)）：雙 Opteron 6272 $253；雙 E5-2620 v2 $214；雙 E5-2620 v3 $264；雙 E5-2670 v2 $303；雙 E5645 $176；雙 L5630 $171；雙 L5640 $147；雙 X5355 $91；單 Opteron 6272 $122；E3-1240 v2 $103.50；E3-1270 v2 $98；E3-1270 v3 $98；E3-1270 v5 $151；E3-1270 v6 $167；E3-1271 v3 $113；E5-1620 v2 $168；E5-2620 v2 $183；i7-3930K $154；L5320 $98；雙 E5-2620 v3 $99。**銷售解讀：涵蓋 Xeon 5300 Clovertown（2007）／5500-5600 Westmere／E5 v2 Ivy Bridge／E5 v3 Haswell 至 E3-1270 v6 Kaby Lake（2017）——沒有任何一顆 Xeon Scalable（Skylake-SP 以後），沒有 EPYC，機架裡還有一顆桌上型 i7-3930K。機隊年齡約 8 至 19 年。4 槽、至 96GB、1 Gbps 埠的節點，是典型 1U/2U Supermicro 級 whitebox 組態。**
- **雲端／VPS 機隊**：1–16 vCPU、1–96GB RAM、「Solid State Drives」（未區分 SSD 或 NVMe）、1 Gbps 埠、時計 $0.006931–$0.456931/hr。**CPU 廠與世代皆未揭露，頁面未具名 hypervisor**（第三方評測提及 KVM 與 OpenVZ）。

**GPU 產品線**
**完全沒有——這是全新開發（greenfield）機會，不是競爭替換。** 兩項獨立查核：（i）站內限定檢索 GPU／NVIDIA／顯示卡相關詞，僅回傳 /dedicated/servers、/cloud/cloud-servers、/vps/linux 等一般頁面，皆無 GPU 內容；（ii）即時購物車（gid=12）列出 20 個 CPU-only SKU，**無任何加速器選項**。**佐證性負面訊號：公開的 colocation 電力上限為整櫃 3.84 kW、雙櫃 cage 7.68 kW——此密度無法支撐 H100/L40S 級部署。銷售意涵：在此提 AI/GPU，必須同時帶電力與冷卻密度的方案，而且要對 HostPapa（新的資本決策方）談。**

**規模**：現況未公開（GAP）。唯一硬數字為前述約 2012–2013 年的「Dallas 約 40 台／3 機箱、可擴至 60 台」。**最佳現況代理：AS54290 originates 75 個 IPv4 前綴 ＋ 4 個 IPv6 前綴，合計 303,360 個 IPv4（約 4.6 個 /16），與「低至數千台實體主機」相符，但 IP 數不是伺服器數，不得如此呈現。** **員工數第三方估計互相衝突且無公司揭露**：LinkedIn 自報 51–200；Growjo 30；LeadIQ 約 17（2026-06）；RocketReach 16；Craft.co 5——**40 倍差距，無任何權威來源**。**營收：全部為第三方估計、從未經公司確認——Growjo $3.5M；RocketReach $3M（2026）；ZoomInfo <$5M。** 註：公司自稱曾入選 Inc. 5000（未指明年份），暗示歷史成長高於上述估計，**故此估計區間應視為軟性**（[Growjo](https://growjo.com/company/Hostwinds)）。

**已具名客戶**：**無**。無 logo 牆、無案例、無推薦名單。公司只以泛稱描述客層：「a diversified client base that ranges from small bloggers with a single website to Fortune 500 companies」（**出現在供應商代管的案例文字**）與「a diverse global customer base」（HostPapa 新聞稿）。**「Fortune 500」在任何地方都無實證，視為行銷語、未證實。** 唯一具名的公司關係方向相反：**MailChannels**（Hostwinds 是**買方**，導入反垃圾郵件過濾，[案例](https://www.mailchannels.com/customer/hostwinds/)）。另有明確的**白標轉售通路**（/hosting/reseller 與 /hosting/whitelabel，可完全移除 Hostwinds 品牌，涵蓋 VPS（KVM、OpenVZ、Windows）、雲端、共享、轉售、負載平衡與 Minecraft／VPN 伺服器）——**代表相當比例的需求是間接的，對估算硬體換機量有影響，因為轉售商流動率直接驅動節點使用率**。

**網路**：AS54290——RADB 登記為 HOSTWINDS-1（最後修改 2023-11-13），主要聯絡人 Peter Holden；**ARIN autnum 54290 現回傳組織「HostPapa」、代碼 HOSTP-7、註冊 2011-12-05、最後異動 2026-05-12、地址 Buffalo NY**；bgp.tools 亦已將 AS54290 標為 HostPapa。資源：75 個 IPv4 ＋ 4 個 IPv6 前綴、303,360 個 IPv4。**衛生弱點兩則：目前無有效 RPKI ROA，且該 ASN 曾被觀測宣告 bogon。** PeeringDB 自報流量 20–50 Gbps、類型「Content」、範圍 Global。**客戶埠一律 1 Gbps（專用、雲端、colocation 皆同）——沒有 10/25 GbE 客戶埠選項，對 AI/HPC 工作負載是明顯限制。** Peering 政策 Selective。公開 IX 僅 SIX Seattle 兩個 10G 埠。**PeeringDB 未列任何私有互連設施（「no filter matches」）——這相當罕見，也讓設施層無法獨立佐證。** 觀測上游／對接：NTT America AS2914、Cogent AS174、Zayo AS6461、Hurricane Electric AS6939、GSL Networks AS137409、RETN AS9002，共 39 個 BGP peer。官方機房頁具名四家 Tier 1：Zayo、Cogent、NTT Communications、GTT（[PeeringDB net/9308](https://www.peeringdb.com/net/9308)）。

**政治紀錄（僅公開紀錄，並附標記）**
- **Peter Holden（創辦人暨 CEO）**［**GAP — FEC 無法以抓取方式查詢；視為無資料，不可視為「沒有捐獻」**］：fec.gov 個人捐獻查詢為客戶端 JavaScript 應用，帶入 contributor_name=Peter+Holden 與 contributor_employer=Hostwinds 的預篩網址只回傳空白查詢介面、無任何結果列，因此**捐獻的有無皆未確立**。另「Peter Holden」為常見姓名，任何命中都須以雇主與城市交叉佐證才能歸屬。查無遊說登記、PAC 活動、政府合約或公開政治發言。
- **Jamie Opalchuk（HostPapa 創辦人暨 CEO，新母公司）**［GAP］：查無美國政治獻金、遊說或政府事務紀錄。**HostPapa 總部在加拿大**（ARIN 紀錄的技術與濫用聯絡人使用 +1-905 安大略區碼），**外國人依法不得捐獻美國聯邦競選**，故美國 FEC 個人捐獻紀錄通常不適用。
- **Hostwinds LLC（法人）**［公開紀錄｜查無政治活動］：查無企業 PAC、聯邦遊說登記、政府／公部門得標與公共政策立場。唯一近似監理的公開足跡與濫用／內容管理有關：一則 WHT 批評其濫用處理的討論串，以及公開的濫用聯絡管道與 phish.report 條目；公司亦曾為整頓 IP 信譽而將 email 行銷業者移出其網路。**上述皆非政治活動。**（[phish.report](https://phish.report/contacts/HOSTWINDS-US)）

**公開聯絡管道**：銷售 **sales@hostwinds.com**（銷售時段 週一至週五 08:00–16:00 PST）；免付費 **+1 (888) 404-1279**；支援 support@hostwinds.com（24/7/365，宣稱 5 分鐘回應目標）；濫用 abuse@hostwinds.com／+1-206-886-0665，**併購後 ARIN 登記之濫用 POC 已改為 net-abuse-global@hostpapa.com／+1-905-315-3455**；**網路技術聯絡（併購後 ARIN 登記）net-tech-global@hostpapa.com／+1-905-315-3455——這是 AS54290 的登記技術路徑，也是併購後最可靠的網路／基礎設施決策路徑**（[ARIN RDAP](https://rdap.arin.net/registry/autnum/54290)）；法務 legal@hostwinds.com、隱私 privacy@hostwinds.com；總部 12101 Tukwila International Blvd, Suite 320, 3F, Tukwila, WA 98168-2398；[LinkedIn 公司頁](https://www.linkedin.com/company/hostwinds)；**具名主管 Peter Holden**（[LinkedIn](https://www.linkedin.com/in/holdenpeter/)，併購前的主要決策者、亦為 AS54290 的 RADB 技術聯絡人；公司未公布其直接 email——RocketReach／ContactOut／Wiza 等付費資料商聲稱持有，**屬付費資料商紀錄而非公開紀錄，本次未取得亦未驗證**）；**Jamie Opalchuk（HostPapa 創辦人暨 CEO，可能的資本支出決策方）**。
**徵才注意**：Hostwinds 在 Tukwila 的職缺散見 ZipRecruiter、Indeed、LinkedIn、Glassdoor、Built In Seattle（某聚合站稱有 9 個職缺），**但未能取得任何含硬體細節的機房技師 JD；檢索到的 Tukwila 機房技師職缺屬於隔壁 12201 號的 Wowrack，是不同公司，不得誤植於 Hostwinds**（[Indeed](https://www.indeed.com/cmp/Hostwinds/locations/WA/Tukwila)）。

**GAP 清單（Hostwinds）**：伺服器 OEM 完全未公開（**本案最重要的未解問題，只能靠訪談、現場或試用機 BMC 橫幅確認**）／現行伺服器與機櫃數（唯一公司數字為十餘年前的 40 台/3 機箱）／WA SOS 的 UBI 與正式設立日、且創立年份 2010 vs 2016 矛盾／**併購條件未揭露——未公布價格、員工移轉、Peter Holden 留任承諾或基礎設施資本支出計畫；Hostwinds 是否保有獨立硬體採購權是本案的關鍵資格問題**／三個站點的面積、cage/機櫃數、合約 kW、租或買皆未公開／PeeringDB 完全未列私有互連設施／無具名客戶且「Fortune 500」無實證／無 GPU 產品故無競品足跡、亦無 AI 需求或 AI 資本支出意圖的證據／Peter Holden 的 FEC 資料無法查詢（**是取得失敗，不是查無捐獻**）／hypervisor、儲存架構（SSD vs NVMe）與 10/25 GbE 能力皆未揭露／CEO 以外無任何具名技術主管或硬體評估者／員工數 5 至 200 的 40 倍落差無法解決／七個非自營 colocation 市場的設施與營運商全未揭露。

---

### 4.6 QuadraNet（QuadraNet Enterprises, LLC）— Supermicro 已確認，但公司已瓦解；此為資產追蹤與後手接管標的，不是新機管線

> **銷售前置警語：這不是活的硬體潛在客戶。** 2024-04 由 VSS Capital Partners 售予 Edge Centres；澳洲母公司 Edge Centres Pty Ltd（ACN 647 483 476）於 **2025-06-16 遭指派清算人**（[ASIC 公告](https://publishednotices.asic.gov.au/browsesearch-notices/notice-details/Edge-Centres-Pty-Ltd-647483476/8f031111-abd0-4700-9a06-56f8b484a5e2)）；2025 年初逾 200,000 個 IPv4 售予 HostPapa（自約 300,000 降至約 6,656）；2025-01-23 起 LA／Chicago／Dallas 多日斷線；2025-02 LA colocation 客戶被通知約一週內撤離。**2026-08-03 直接實測：quadranet.com 僅剩 logo 版面，/dedicated-servers、/specials_baremetal、/atlanta-dedicated-servers 全部 HTTP 404，blog.quadranet.com NXDOMAIN，squiggly.quadranet.com 拒絕連線（ECONNREFUSED 至 198.55.111.55——該位址已屬 HostPapa），AS8100 幾乎不再宣告任何 IPv4。以信用風險／資產回收／後手帳戶處理，不要當成伺服器管線。**

**法人與所有權（部分、登記未證實）**
**QuadraNet Enterprises, LLC（California）**。ARIN 將 AS8100 登記於「QuadraNet Enterprises LLC」（ASName ASN-QUADRANET-GLOBAL，2009-10-22 配發），PeeringDB 亦以此為 QuadraNet LAX 設施的所屬組織。**加州 SOS 的實體編號、設立日、狀態與註冊代理人皆未取得（GAP）**：bizfileonline.sos.ca.gov 僅暴露不透明的影像 API 端點，Bizapedia 顯示安全檢查頁，OpenCorporates 顯示 HAProxy CAPTCHA（未嘗試繞過）。商號「QuadraNet, Inc.」另出現於 D&B 名錄與 FEC 紀錄中，**兩者是否為同一法人或屬 DBA 未能確認**。**創立 2001 年於 Los Angeles，創辦人 Ilan Mishan**（由 HostingAdvice CEO 專訪、Mergr／Preqin 交易紀錄與 cxponent 廠商檔案三方獨立佐證）。
- **Ilan Mishan＝創辦人暨 CEO（2001 年起，PE 進場之前）**。2024 年售出後的現職狀態未確認；RocketReach 將他與「NEO Investment Group, LLC」的 Managing Partner 職稱連結，**未證實**（[HostingAdvice 專訪](https://www.hostingadvice.com/blog/quadranet-hosting-solutions-help-businesses-evolve/)）。
- **VSS Capital Partners（Veronis Suhler Stevenson）＝前 PE 股東／賣方（2024-04 退出）**。MergerLinks 記載「Edge Centres completed the acquisition of QuadraNet from VSS」，日期 2024-04-08；**交易條件未揭露**。
- **Edge Centres LLC／Edge Centres Pty Ltd＝收購方暨現行母公司（2024-04），母公司已進入法院清算**。收購為 Edge Centres 的美國版圖增加 10 個設施，加上其 2023-07 的 Multacom 收購，宣稱在加州擁有 100,000+ sq ft 白空間。**注意：ASIC 公告涵蓋的是澳洲 Pty Ltd 實體；美國「Edge Centres LLC」是否另行有償債能力＝GAP。**
- **Jonathan Eaves＝Edge Centres 創辦人**（2021 年創立於澳洲 Grafton）；**其相對於清算程序的現況＝GAP，社群／第三方來源**。
- **Kiarash Jahangiri＝併購後獲任的 QuadraNet CEO（2024）——報導互相衝突**。DataCenterDynamics 報導 Edge Centres 的 CTO Kiarash Jahangiri 獲任 QuadraNet CEO；**另有搜尋索引摘要把 2024 年 CEO 一職歸給 Tim Caulfield**。DCD 原文對直接抓取回 HTTP 403，**無法裁定，標記為未證實衝突**。
- **HostPapa＝IPv4 位址資產的收購方（2025 年初），非股權所有人**。取得「over 200,000」個 IPv4，QuadraNet 的 ARIN 檔案隨後降至約 6,656 個。**獨立佐證：bgp.he.net 現把 QuadraNet 最後一個 originated 前綴 198.55.111.0/24 歸屬於 HostPapa。這是資產剝離訊號，不是股權移轉。**（[LowEndBox 報導](https://lowendbox.com/blog/hostpapa-acquires-nearly-all-quadranet-ips/)）

**總部與各資料中心**
總部 **530 W 6th Street, Penthouse, Los Angeles, CA 90014**（Telecom Center 大樓，緊鄰 One Wilshire；部分名錄將郵遞區號寫成 90017）。另有 Tarzana, CA 的地址關聯（RocketReach 檔案與 2012 年 Ilan Mishan 的 FEC 紀錄），**但未獲佐證為公司總部，視為未證實**。
| 站點 | 自有／租用 | 面積與電力 | 說明 |
|---|---|---|---|
| **LA 市中心總部 — 530 W 6th Street** | **租用建物、自營機房套房**。公司行銷為「privately-owned and operated datacenter space」，實為大樓房客（自 2004 年進駐、據稱最大房客、跨 6 個樓層）；**房東身分＝GAP** | 公司／市集掛牌稱「over 60,000 square feet」；datacenters.com 同址列整棟 300,000 sq ft、80,000 sq ft raised floor。**數字衝突：60,000 是 QuadraNet 自述的套房面積，較大者為整棟。** 電力＝**GAP**（僅提及冗餘 UPS 與 ATS，無任何數字） | 旗艦站，2025-01-23 起多日斷線；2025-02 通知 LA colocation 客戶約一週內撤離（[datacenterHawk](https://datacenterhawk.com/marketplace/providers/quadranet/530-w-6th-street/141073)） |
| **QuadraNet LAX — 6171 W Century Blvd, Basement, Los Angeles, CA 90045** | 自營設施（PeeringDB 設施紀錄所屬組織為 QuadraNet Enterprises LLC）；底層不動產幾可確定為租用（**產權＝GAP**） | GAP／GAP | PeeringDB 設施 ID 3825，最後更新 2025-09-26；列有 8 個網路進駐，含 QuadraNet AS8100、ServerMania AS55286、Eonix AS62904、24Shells AS55081、HostingInside AS9678、rixCloud AS64271、Navice AS137490、Xlitt AS22298——**顯示 QuadraNet 在此轉售空間給其他主機商**（[PeeringDB fac/3825](https://www.peeringdb.com/fac/3825)） |
| **CoreSite LA1 — One Wilshire** | 租用（第三方 carrier hotel） | GAP | 見更正表第 4 列；另於 Equinix LA1 亦有據點 |
| **Dallas, TX — 3004 Irving Blvd** | 租用（PeeringDB 顯示為 TierPoint Dallas 內的空間） | cloudandcolocation 引 68,000 sq ft（**應為整棟而非 QuadraNet 套房**） | 行銷稱「industry-leading power-to-space ratio」與 80 Gbps 頻寬容量，**無絕對電力數字**；2025-01 亦在斷線名單 |
| **Miami, FL — 2115 NW 22nd St** | 租用（PeeringDB 顯示為 South Reach Networks） | 引 50,000 sq ft（整棟） | 行銷為 Tier III 認證、可抗五級颶風；另於 FL-IX 以 10G peering |
| **Atlanta, GA — CoreSite AT1** | 租用 | GAP | quadranet.com/atlanta-dedicated-servers **現為 404** |
| **Chicago, IL — Equinix CH3, Elk Grove Village** | 租用 | GAP | 2025-01 斷線名單之一 |
| **Secaucus, NJ（紐約都會）— H5 Data Centers Secaucus 與 InterServer Teb2** | 租用（兩個不同營運商） | GAP | **這才是其「New Jersey」／紐約都會行銷的實體所在；任何來源皆無曼哈頓／紐約市設施** |
| **Seattle 一帶 — WowRack, Tukwila, WA** | 租用 | GAP | PeeringDB 私有設施 |
| **Woerden, Netherlands（Amsterdam 都會）— HostSlim** | 租用 | GAP | 唯一非美國站點 |
| **Reston, VA 與 St. Louis, MO** | **GAP，推定為租用、未證實** | GAP | 僅出現在 Preqin／Mergr 併購紀錄的摘要中，**PeeringDB 與任何 QuadraNet 自述頁面皆無，標記未證實** |

**硬體機隊與證據等級**
- **Supermicro＝主要／主導平台（直接、第一手、逐字）**。「1U Supermicro Server – 4x Hot-Swap Bays」是其整個 LA 專用伺服器產品線的逐字規格行，確認組態包括：Intel Xeon X3450 四核 2.66GHz／16GB DDR3 ECC Registered／1TB SATA 7.2k；Xeon E3-1241v3 四核 3.50GHz／16GB／1TB；雙 Xeon E5620 四核 2.40GHz／64GB／1TB；Xeon E-2124G 四核 3.40GHz／32GB DDR4 ECC Reg／1TB——四者皆列「Integrated IPMI, KVM over IP, Remote Power Control」。其自家 specials_baremetal 頁另以 **「Supermicro CSE」** 機殼列出高階裸機：雙 E5-2698 v4／256GB／4×2TB SSD／10Gbps／硬體 RAID／**Supermicro IPMI**，$249/月（原 $299）；雙 E5-2650 v2／128GB／4×2TB SSD／Supermicro IPMI，$139/月（原 $199）。另有「1U Supermicro Servers with 2x HDD Bays」搭 **Adaptec 2405** 控制器做硬體 RAID-1，以及部分 15,000RPM SAS 硬碟走硬體 RAID。**機隊世代嚴重落後：Nehalem/Lyndale（X3450）、Westmere（E5620）、Haswell（E3-1241v3）、Ivy Bridge（E5-2650 v2）、Broadwell（E5-2620v4／E5-2698 v4）、Coffee Lake（E-2124G）——在公司崩解之前，就已落後當世代矽晶 5–10 年。**（[LowEndBox 專屬優惠](https://lowendbox.com/blog/quadranet-exclusive-black-friday-dedi-offers-in-los-angeles/)）
- **Dell＝次要／部分證據，僅由管理控制器名稱推得**：唯一依據是裸機特賣頁把帶外管理列為「Dell Enterprises iDRAC」或「Supermicro IPMI」二擇一。**具體 PowerEdge 型號、世代與佔比全部 GAP，不得聲稱已知。**
- **Adaptec（RAID 卡）＝元件級、直接**：Adaptec 2405 用於 1U 雙槽機的 RAID-1。**證實他們採購獨立 RAID HBA 而非僅用主機板內建 SATA**——若日後對任何承接方推整合式儲存平台，這點有用。
- **AMD＝僅行銷提及、無確認 SKU**：第三方市集檔案稱其裸機「from entry-level Intel Xeon/AMD EPYC builds to high-end multi-processor systems with NVMe storage」，**但所有 QuadraNet 自述組態都是 Intel Xeon，AMD EPYC 的存在未證實**。
- **HPE＝GAP**，所有規格頁、優惠貼文、論壇、職缺、設施清單皆無 HPE／ProLiant／iLO。

**GPU 產品線**：**完全沒有——這是硬性否定，不只是缺頁。** 針對 QuadraNet GPU／NVIDIA 專用伺服器的定向檢索**沒有回傳任何 QuadraNet 結果**（只回傳競品）。其整個產品面（專用伺服器、colocation、InfraCloud KVM 雲、DDoS 緩解）在任何可還原的頁面或優惠中都沒有加速運算產品線；可考的最新 CPU 世代僅到 Broadwell／Coffee Lake。**銷售意涵：此處沒有 AI 上攻鉤——QuadraNet 從未完成向加速運算的轉型，而這本身就是它失去競爭力的一部分原因。這個地址上任何 AI／GPU 機會都屬於後手營運方（Edge Centres 的美國殘餘資產、取得 IP 的 HostPapa、或接手 LA 套房者），不屬於 QuadraNet。**

**規模**：伺服器數、機櫃數、機箱數**從未公布（GAP）**。間接指標：2024-04 併購時 **1,000+ 活躍客戶**；為 Edge Centres 增加 10 個設施；Edge Centres 併入 Multacom 後宣稱加州 100,000+ sq ft 白空間；站點面積約 60,000–80,000 sq ft（LA）、68,000 sq ft（Dallas）、50,000 sq ft（Miami）——**皆為設施總量，非 QuadraNet 佔用**。LowEndBox 分析指出，HostPapa 交易後殘餘的 6,656 個 IPv4 依每客戶 5 個 IP 計，僅能支撐約 1,300 個客戶，**顯示存活機隊已很小**。
**員工數 28 人（RocketReach）＝第三方估計、非公司揭露**；Crunchbase、ZoomInfo、PitchBook、D&B 皆付費牆或 HTTP 403 無法佐證；**清算後的現況＝GAP，很可能遠低於 28**。Enlyft 對其客群的分析顯示 QuadraNet 自己的客戶偏小（82% 未滿 50 人、11% 中型、6% 逾 1,000 人）。
**營收 $8.8M（RocketReach）＝僅第三方估計、年份不明，幾可確定為 2024 年之前，且在 2025 年的資產出售、客戶撤離與母公司清算之後已不具代表性。無任何經稽核或揭露的財務數字；VSS 出售價格從未公開。不得以此為事實陳述。**（[RocketReach](https://rocketreach.co/quadranet-enterprises-llc-profile_b5cd1cf9f42e0ad1)）

**已具名客戶**
- **HostMantis（Livonia, Michigan）——共享／VPS／轉售主機商**：QuadraNet 自行發布之 DDoS 緩解案例主角，案例中引述「QuadraNet was continuously helpful in assisting us block the attacks and keep our servers online and our clients unaffected」，並提及 HostMantis 將兩地設備整併至單一 QuadraNet 機房。**這是唯一一個公司自行發布的具名客戶；注意來源頁 blog.quadranet.com 於 2026-08-03 已無法解析。**
- **ServerMania Inc（AS55286）** 與 **Eonix N.A.（AS62904）、24Shells（AS55081）、HostingInside（AS9678）、rixCloud（AS64271）、Navice Consulting（AS137490）、Xlitt（AS22298）**：皆由 PeeringDB 列為與 AS8100 同在 QuadraNet LAX 設施內的網路。**同設施進駐是批發／colocation 關係的強力證據，但不是合約確認——標記為由設施進駐推得。** 此租戶組合（小型主機轉售商）與 Enlyft 所稱 82% 客戶未滿 50 人一致。
- **Sandler Partners＝主代理／通路夥伴，非終端客戶**（[Sandler Partners 公告](https://sandlerpartners.com/quadranet-enterprises-announces-a-strategic-partnership-with-sandler-partners/)）。
- **總體客群**：2024-04 併購時「more than 1,000 active customers」，垂直定位為媒體、遊戲與金融服務。**具名企業客戶＝GAP，從未公布。**

**網路**：AS8100（ASName ASN-QUADRANET-GLOBAL，ARIN 於 2009-10-22 配發，組織 QuadraNet Enterprises LLC；PeeringDB「aka」欄位記「FKA AS29761」）。IRR AS-SET：AS-SET-QUADRANET。**關鍵：網路實質上已被拆解**——bgp.he.net 顯示 AS8100 僅 originates 1 個 IPv4 前綴（198.55.111.0/24，256 個 IP，標記 IRR Invalid 與 ROA Signed Invalid，且已歸屬 HostPapa）與 1 個 IPv6 前綴（2602:fed2:708d::/48，歸屬 Free Range Cloud Hosting）；ipinfo.io 回報 0 個宣告 IPv4 前綴、0 個代管網域。**歷史規模約 300,000 個 IPv4，2025 年初移轉後降至約 6,656。** PeeringDB 自報流量 100–200Gbps、Balanced、北美範圍；第三方市集稱「over 300Gbps of capacity」**屬行銷、未證實**。公開 peering 規模有限：Any2West、Equinix Los Angeles、FL-IX 各 10G。現行 BGP 關係極少：上游 AS29802（Hivelocity），對接 AS35916（Multacom Corporation——Edge Centres 於 2023-07 收購的 LA 業者，**證實集團內互連**）；下游數已歸零。（[PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)）

**政治紀錄（僅公開紀錄，並附標記）**
- **Ilan Mishan（創辦人暨 CEO）**［公開紀錄］：FEC 個人捐獻紀錄——捐獻人「MISHAN, ILAN」，Tarzana, CA；**雇主欄填「QUADRANET INC」**；職業欄填「SYSTEM ENGINEER」；金額 **$250.00**；收受日 **2012-10-03**；受款委員會 **「ROMNEY FOR PRESIDENT INC.」**。取自 FEC 自家 Schedule A API，**是該姓名唯一浮現的紀錄**。**註記**：自填職業（System Engineer）與其高階職稱不符，這在 FEC 自我申報中很常見，**本身不足以認定為不同人**；身分比對建立在雇主欄與 Tarzana, CA 位置，後者與 RocketReach 檔案中 QuadraNet Enterprises LLC 的 Tarzana 關聯相符（[FEC API](https://api.open.fec.gov/v1/schedules/schedule_a/?api_key=DEMO_KEY&contributor_name=Ilan+Mishan)）。
- **Michael Lowe（CRO）、Ken Lee（CFO）、Kiarash Jahangiri（併購後 CEO）、Jonathan Eaves（Edge Centres 創辦人）**［GAP］：未查詢亦未發現 FEC 個人捐獻紀錄。**QuadraNet Enterprises LLC 或 QuadraNet Inc 作為法人，查無遊說登記、PAC 關聯或政府合約。**

**公開聯絡管道（多數已失效，逐一標註）**：銷售 sales@quadranet.com——**警告：來自 blog.quadranet.com/contact 的搜尋索引片段，該主機名已於 2026-08-03 無法解析（NXDOMAIN），送達性未驗證、很可能已失效**；免付費 (888) 578-2372（Yelp 所列），名錄另見 +1 833-471-7100，**兩者皆未撥測，以公司現況推定可能皆已停用**；總部 530 W 6th Street, Penthouse, Los Angeles, CA 90014；支援——行銷宣稱 24/7/365 與「24x7 NOC Task Force」，狀態頁歷史位於 status.quadranet.com，**未取得任何直接支援信箱或 NOC 電話**；**Ilan Mishan（創辦人暨 CEO）**——公開路徑為 LowEndBox 專訪、HostingAdvice 專文、Equilar ExecAtlas 頁、Crunchbase 個人檔案，**無確認之直接 email 或電話**；**Michael Lowe（CRO）**——身分出自 2024-08 一則 LowEndTalk 帳務爭議討論串，他曾公開回應投訴人後失聯，**社群來源，現職不明**（[討論串](https://lowendtalk.com/discussion/197081/edge-centres-quadranet-owes-us-13-000)）；**Ken Lee（CFO）**——RocketReach 公司檔案所列，**第三方資料商來源、未經公司確認**；母公司 [Edge Centres LinkedIn](https://www.linkedin.com/company/edgecentres)；**QuadraNet 自身的 LinkedIn 公司頁網址＝GAP，未經驗證故不臆測**。

**GAP 清單（QuadraNet）**：加州 SOS 實體編號／設立日／狀態／代理人（三個入口皆被阻擋）／「QuadraNet, Inc.」與「QuadraNet Enterprises, LLC」的關係／**美國實體在母公司崩解後的法律與營運現況（是否進入接管、解散、再轉售或名義上仍在營業），以及清算人姓名與美國資產處置＝GAP**／所有站點的電力容量／伺服器與機櫃數／Dell 機隊細節／AMD EPYC 是否存在／併購後 CEO 身分衝突未解／具名企業客戶／員工數與營收僅第三方估計／QuadraNet 自身 LinkedIn 網址／Reston VA 與 St. Louis MO 未證實／530 W 6th Street 的業主與租約條件與到期日／**LA 套房在 2025-02 客戶撤離與母公司清算之後，實體 Supermicro 資產由誰控制——這是本帳戶唯一實際的商業角度，且無法由公開來源解決**／歷史職缺無法取得（LowEndBox 曾指其徵才頁仍掛 2019 年的職缺作為衰敗訊號）。

---

## 5. Supermicro 銷售切角（Sales angle）

先分類，再談話術。**四種角色需要四種完全不同的開場，用錯會立刻失去可信度。**

| 業者 | 角色分類 | 誠實的楔子 |
|---|---|---|
| **WebNX** | **Whitebox 自組商 → 平台轉換（platform conversion）**（**非**既有客戶：Supermicro 在 WebNX 為未證實） | 他們在元件與準系統層採購、自行組裝與測試，且**已經證明會買當世代頂規 AI 平台**（雙 EPYC 9575F ＋ 4×RTX PRO 6000 96GB，$7,999/月）。同一份型錄裡卻是 2017 年 V100 與 2020 年 RTX 3090，**且完全沒有 H100／H200／L40S**。切角：**以 GPU 最佳化 4U/5U 準系統做 V100 與 3090 的汰換，再加開雙路 Turin 的 4 卡與 8 卡平台**。他們賣的是 AM5 Ryzen 9950X/9950X3D 與 LGA1851 Core Ultra 9 285K 這類桌上型插槽——**Dell 與 HPE 根本不做這種伺服器板，Supermicro 做**，這是天然的產品契合點。**禁止**開場說「我們知道你們在用 Supermicro」——研究等級是未證實。**改成問句。** |
| **Psychz** | **高機率既有／類既有 → 防守 ＋ 換代 ＋ GPU 產品線延伸**（Supermicro 為強旁證） | 他們自己撰寫並託管 **Supermicro 專屬** IPMI 文件、站內查無 iDRAC/iLO、庫存裡有 Dell/HPE 根本不做的 i7-7700K 機種。同時其參考架構已明載 3rd/4th/5th Gen Xeon Scalable——**換代週期正在進行**。最強的一點：**他們在行銷 H100／H200／B200／B300，卻沒有設定器、沒有公開價、沒有具名平台廠，而 CPU 產品線卻是全標價自助下單**。這個不對稱就是缺口——**他們在逐案調貨 GPU 節點，沒有常設供應協議。** 切角：把 8 卡與 4 卡平台變成他們可以標價上架的標準品，並用 colocation 頁已在賣的 per-kW 單卡 GPU 方案往上帶密度。**話術務必說成待確認假設，不是既定事實。** |
| **ReliableSite** | **已確認既有 → 但實際上是「機殼流失、板級仍開放」的防守戰** | Supermicro 在此有三條獨立證據，**但同一份 CEO 專訪就是他們離開原廠機殼的原因說明**：MicroCloud 替換零件斷貨、價格三倍，於是自製高密度機殼，**並刻意保持相容於市售主機板與電源**。這代表**板級與電源這個插槽仍然開放**，而**主機板供應商是誰，是本檔商業價值最高的單一未知**。第二個楔子是零件供應痛點——CEO 本人公開講特定 SSD/RAM 漲價 800%、交期 3 個月以上。第三個楔子是 AI 缺口：他們有 AI 客戶案例（Little Planes Farm 的 AI 視覺）、把 EPYC 4545P 行銷為 AI inferencing，**實際加速器只有一款 A10（庫存 1 台）加一張 $99/月 Quadro 加購**。**但轄區不在一組，見第 6 節。** |
| **Sharktech** | **競爭對手的帳戶 → 替換／第二供應商（displacement）** | **既有廠商是 Lenovo，不是 Supermicro**——這是他們唯一一次公開具名。他們透過未具名的經銷商進貨、在 Las Vegas 自行組裝（「we're currently building 12 of them」），**這正是準系統／BTO 動作的目標客型**。三個具體楔子：（i）**Denver 由 H5 遷至 US Signal COO1**，原訂 2026-05-31 完成——實體搬遷是典型換機窗口；（ii）**唯一的 GPU SKU 缺貨且落後兩三代**（A4000／V100，無 SXM/HGX、無多卡節點），而他們明說會「work with our vendors」依需求調 GPU；（iii）**他們自己承認部分既有機隊沒有 10G 網卡**（「if your server hardware already has a 10G capable network port (most do)」），而 40G/100G 升級路徑是許多 Broadwell 世代 E5-2695v4 節點做不到的。**先問平台，不要先報價。** |
| **Hostwinds** | **無 GPU → 全新開發（greenfield AI），但採購權可能已北移** | 完全沒有 GPU 產品，機隊年齡約 8–19 年（最新僅到 2017 年 E3-1270 v6，**沒有任何 Xeon Scalable、沒有 EPYC**），客戶埠一律 1 Gbps。**但這是一個帶條件的機會**：其公開 colocation 電力上限僅整櫃 3.84 kW、雙櫃 cage 7.68 kW——**在沒有電力與冷卻升級之前，H100/L40S 級部署根本放不進去**。因此 AI 提案必須連同密度方案一起賣。**最關鍵的一點：Hostwinds 已於 2026-04-29 被 HostPapa 併購，AS54290 的 ARIN 登記已改為 HostPapa（Buffalo NY），資本支出權責很可能已移轉——先確認採購權在誰手上，再談任何規格。** |
| **QuadraNet** | **不做前瞻銷售 → 信用風險與資產追蹤** | Supermicro 在此是第一手確認的既有平台，**但公司已瓦解**：母公司清算、IP 資產已賣、客戶被要求撤離、官網僅剩 logo。**沒有 AI 上攻鉤（從未有任何 GPU 產品）。** 唯一實際角度是：**LA 套房中的實體 Supermicro 資產目前由誰控制**，以及承接方（Edge Centres 美國殘餘、取得 IP 的 HostPapa、或接手套房者）是否會成為新帳戶。**在確認美國實體的法律狀態之前，不要投入銷售時數，也不要以任何形式承作信用條件。** |

### 通路問題（開打前必讀）

**這六家明顯都在營運相當規模的機隊——WebNX 自稱數千台伺服器、Equinix LA3 逾 150 機櫃；Psychz 15,000 sq ft 自營機房與 16–17 個設施；ReliableSite 六個區域、約 51K 個 IPv4；Sharktech 五個站點、124K 個 IPv4；Hostwinds 303K 個 IPv4——但六家在 CRM 中一筆紀錄都沒有（2026-08-03 實查，全部 No similar record found，無 lead、無 account、無 DNC）。**

合理推論只有一個：**他們的伺服器是透過經銷通路買的，不是直接向原廠買。** 佐證分散在各家：Sharktech 明說「we received a new batch of EPYC 7702 servers from **our supplier**」（供應商名稱未具名，**這是替換戰最有價值的單一未知**）；WebNX 的職缺描述用棧板車搬運整棧伺服器零件、每年測試數百種組態；ReliableSite 自述「keep our inventory on site」並自 tray 直上機櫃；Hostwinds 自述「no middlemen」但從不具名供應商。

**行動前置條件：依 Rule 8，經銷商可以跨越轄區邊界，但必須事先取得核准並掛上「do not call」標記。在任何人撥出第一通電話之前，須先與通路窗口確認這六家是否已經是某家經銷商的既有帳戶。** 若是，本檔就從「新客開發」轉為「與經銷商共同經營的既有帳戶」，開場、報價與登錄方式都不同。**先確認通路，再登錄 lead，最後才接觸——順序顛倒會造成通路衝突。**

---

## 6. 接觸計畫（Engagement plan）

### 6.1 排序：先登錄誰

依「一組自有轄區 ＋ 機隊訊號最強 ＋ 有明確時間窗」三項排序。

| 順位 | 業者 | 轄區依據 | 為何是這個順位 | 首通電話的**唯一**資格問題 |
|---|---|---|---|---|
| **1** | **WebNX**（Ogden, UT） | West Coast South excl. CA = **T1 \| T31** → **一組自有，可逕行登錄** | 全層唯一已在買、且已公開標價出售當世代 Blackwell 4 卡平台的業者（$7,999/月）；同時壓著一批 V100 與 RTX 3090、零 H100/H200/L40S。**已確認為元件級自組商**，準系統動作直接契合 | 「你們現在的 AM5／LGA1851 機種與 4 卡 GPU 機種，是拿哪家的準系統或主機板在組？」——**這是本案最高優先的未知，一句話就能把 Supermicro 是否在他們供應鏈裡確定下來** |
| **2** | **Psychz**（Los Angeles, CA） | West Coast South California = **T1 \| T2** → **一組自有（T2 亦可承作，登錄前先與 T2 Tony Lai 對齊避免撞單）** | 已在行銷 H100/H200/B200/B300 卻無設定器、無公開價、無具名平台廠；CPU 產品線卻全標價自助——**代表 GPU 是逐案調貨、沒有常設供應協議**。Supermicro 為強旁證（自撰 Supermicro-only IPMI 文件） | 「你們的 H100／H200／B200 節點目前是逐案調貨嗎？如果有一份可以直接上架標價的 4 卡與 8 卡標準平台，你們會想把它變成常設 SKU 嗎？」 |
| **3** | **Sharktech**（Las Vegas, NV） | West Coast South excl. CA = **T1 \| T31** → **一組自有** | Lenovo 替換／第二供應商；**Denver 由 H5 遷至 US Signal COO1（原訂 2026-05-31 完成）**是明確的換機窗口；唯一 GPU SKU 缺貨且落後兩三代 | 「除了那條 Lenovo 的 EPYC 7702P 產品線，其餘 Xeon Gold 6248 與 E5-2695v4 機種是走哪家供應商？Denver 搬完之後，那批設備是換新還是原機搬遷？」 |
| **4** | **ReliableSite**（Piscataway, NJ ＋ Miami, FL） | FL＝East Coast 3、NJ＝East Coast 1，皆 **T2\|T3\|T6\|T7\|T12**；**Rule 11 的 100MW 門檻不符，T1 的大型資料中心例外不適用** → **必須由東岸團隊承作，本檔以七組（Brian Leaver）為對口** | Supermicro 證據最強，但**機殼已流失、板級仍開放**；CEO 就是採購決策者且公開可觸及（LowEndTalk「MrRadic」）；Querétaro 建置中是近期採購觸發點 | 「你們自製機殼用的是哪家的主機板與電源？Querétaro 那批要上什麼平台？」 |
| **5** | **Hostwinds**（Tukwila, WA） | West Coast North = **T4 \| T31** → **必須與 T4 協同（T4 主管 Kambiez Tahvilian）** | 完全無 GPU、機隊 8–19 年、1 Gbps 客戶埠——全新開發機會很大，但**採購權可能已隨 2026-04-29 的 HostPapa 併購移轉**，且機櫃電力上限 3.84 kW 需先解決密度 | 「併購之後，Seattle／Dallas／Amsterdam 的伺服器採購決策是留在 Hostwinds 還是已經歸到 HostPapa？」——**先問這句，其他都不用問** |
| **6** | **QuadraNet**（Los Angeles, CA） | West Coast South California = **T1 \| T2** → 一組自有轄區，**但標的本身已崩解** | 不投入前瞻銷售時數。母公司清算、IP 已賣、官網 404 | 「530 W 6th Street 與 6171 W Century Blvd 的機房套房與其中設備，現在由哪個法人控制？」——**這是對資產承接方問的，不是對 QuadraNet 問的** |

### 6.2 需要協同的兩家，以及協同對象

- **Hostwinds（Tukwila, WA）→ 銷售四組（T4），主管 Kambiez Tahvilian。** West Coast North（WA, OR, ID, MT, WY, AK, HI）＝T4 | T31。一組不得單獨承作，須以 co-op 形式進場。**額外複雜度：母公司 HostPapa 位於 Burlington ON／Buffalo NY，若採購權確已北移，實際承作團隊可能還要再變更——第一通電話先釐清這件事，再決定 co-op 的組合。**
- **ReliableSite（Piscataway NJ ＋ Miami FL）→ 東岸團隊。** East Coast 1（含 NY、NJ、PA）與 East Coast 3（GA、FL、AL、MS、TN）皆為 T2|T3|T6|T7|T12；**T1 僅在 Large End User／Data Center 並經核准時例外**，而 **Rule 11 明定「大型資料中心」為 100MW 以上，本案六家沒有一家符合，故該例外不適用**。本檔的編製對象已含銷售七組，**七組（Brian Leaver）為自然對口**；若需再擴大，T2（Tony Lai）、T3（Mark Parker）、T6（Matt Abreu）、T12（Nancy Lee）亦在該轄區。
- **註記（避免誤派）：T11（Derek Tong）僅涵蓋 Chicago Area 與 Canada East，與這六家皆不相干，不要送件。**

### 6.3 執行順序（不可跳步）

1. **先確認通路（Rule 8）**：查明這六家是否已是某家經銷商的既有帳戶；如是，取得跨區的事先核准並掛上 do-not-call 標記。
2. **再登錄 lead**：一組自有的四家（WebNX、Psychz、Sharktech、QuadraNet）先登；QuadraNet 僅以資產追蹤性質登錄並註明信用風險。
3. **同步發出 co-op 請求**：Hostwinds 致 T4（Kambiez Tahvilian）、ReliableSite 致 T7（Brian Leaver）。
4. **最後才接觸**，且第一通電話只問上表那一個資格問題，**不報價、不假設既有廠商**。

---

## 7. 查證附錄（Verification appendix）

### 7.1 單一來源支撐的說法（引用前須再驗證）

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| Psychz 的客戶包含 **Verizon、Baidu、XO**，以及「~25,000 customers」 | 單一份 [Juniper 案例研究 PDF](https://www.juniper.net/content/dam/www/assets/case-studies/us/en/3520727-en.pdf) | **HTML 頁已 301 轉址至 hpe.com，PDF 內文為子集字型編碼無法本地抽取，字串係由搜尋引擎對該頁的擷取取得（次級擷取）。放入任何對客資料前必須先行驗證。** 另 XO 已於 2017 年被 Verizon 併購，該引用應早於案例的 2020 年發布日 |
| Psychz 的網路夥伴「**Rack n' Stack**」 | 同上 PDF 的搜尋摘要 | **無法對照原始頁面，明確標示為不可引用** |
| Sharktech 的客戶 **Wings Technology Co., LTD／Kill-Streak Gaming／ISPHELPER** | 單一篇 HostingAdvice 報導 | **該文對直接抓取回 HTTP 403，僅取得搜尋片段；Sharktech 自家 /case-study/ 頁未列任何具名客戶** |
| Sharktech 的伺服器廠 **Lenovo** | 單一則客戶入口公告 #221 | **是第一手逐字揭露（「System: Lenovo」），可信度高，但僅涵蓋 EPYC 7702P 一條產品線；其餘約 50 個 SKU 的平台廠仍是 GAP** |
| WebNX 的「Dell、SuperMicro、HP」 | **描述的是 GorillaServers，不是 WebNX** | **不同法人。第三方評測文字。嚴禁作為 WebNX 的硬體事實使用** |
| Hostwinds Dallas「約 40 台伺服器／3 機箱」 | 約 2012–2013 年的公司部落格 | **原網址現回 404，數字由搜尋索引片段取得；十餘年前資料，只能當地板值** |
| QuadraNet 併購後 CEO 為 **Kiarash Jahangiri** | DataCenterDynamics 報導 | **另有搜尋摘要指為 Tim Caulfield；DCD 原文 HTTP 403 無法裁定，衝突未解** |
| QuadraNet 的 **Ken Lee（CFO）** | RocketReach 公司檔案 | **第三方資料商來源，未經公司確認，任期與現況未證實** |
| Hostwinds 收購 **WeLoveServers** | 單一 WHT 討論串 | **原文 HTTP 403，日期與條件皆未確立，社群來源** |
| ReliableSite 的 Supermicro（其中一條） | Web Hosting Talk 客戶評述 | **社群來源，且其中一則為 Atom D510 舊世代；但另有 CEO 專訪的第一手佐證，故整體判定為已確認** |
| QuadraNet 的 **Reston, VA 與 St. Louis, MO** 設施 | Preqin／Mergr 併購紀錄摘要 | **PeeringDB 與所有 QuadraNet 自述頁面皆無，未證實** |

### 7.2 第三方估計互相矛盾之處（**呈現分歧，不擇一**）

**員工數**
| 業者 | 各來源數字 | 分歧幅度 |
|---|---|---|
| **Hostwinds** | LinkedIn 自報 **51–200**／Growjo **30**／LeadIQ 約 **17**（2026-06）／RocketReach **16**／Craft.co **5** | **40 倍**。無任何權威來源。LinkedIn 為公司自填且區間最寬 |
| **Psychz** | LinkedIn **11–50**／LeadIQ 約 **11**（2025-08）與約 **8**（2026-04）／Inc.com **51–200** | 約 25 倍。公司僅公布 4 名主管（名＋姓氏首字母），社群指支援外包印度（未證實）可解釋美國人數偏低 |
| **Sharktech** | LinkedIn **11–50**（48 位關聯成員）／公司素材「**more than 25**」／ZoomInfo **18** | 約 3 倍。務實工作值 25–50 |
| **ReliableSite** | LinkedIn **11–50**（自報） | 單一來源，無交叉佐證 |
| **WebNX** | LinkedIn **11–50**（自報） | 單一來源。以 100k+ sq ft 自營機房、LA 150+ 機櫃、NY/Dallas/SLC PoP 的規模而言，人力密度極低 |
| **QuadraNet** | RocketReach **28** | 單一第三方；**清算後現況幾可確定遠低於此** |

**營收**
| 業者 | 各來源數字 | 分歧與可信度評註 |
|---|---|---|
| **ReliableSite** | Kona Equity **$1.2M**／Owler **每員工 $27.6K** | **內部明顯不一致**：$1.2M 與約 51K 個 IPv4、五個 IXP 100G 埠、1–5 Tbps、六個租用機房區域、11–50 名員工不相稱——**光機房費＋transit＋薪資很可能就超過此數。全部視為低可信度第三方模型。** |
| **Sharktech** | LeadIQ **$10M–$25M** | 單一第三方估計。型錄結構（51 SKU $219–$699/月、VPS $2.48/月起、雲端 $0.065/hr、colo $35/月起、物件儲存 $4.9/TB、1,000+ 客戶）與八位數區間相符但**無法證實** |
| **Hostwinds** | Growjo **$3.5M**／RocketReach **$3M**（2026）／ZoomInfo **<$5M** | 三家聚攏在 $3M–$5M，但公司自稱曾入選 Inc. 5000（未指年份），**暗示歷史成長高於此，區間應視為軟性** |
| **QuadraNet** | RocketReach **$8.8M** | **年份不明，幾可確定為 2024 年之前；在 2025 年資產出售、客戶撤離與母公司清算後已不具代表性** |
| **Psychz** | **無任何來源給出金額** | Crunchbase、PitchBook、ZoomInfo、Owler、D&B 皆無。**僅有 Inc. 5000 名次可佐證是真實且成長中的營收型企業（2025 #2372、三年成長 179%），但本檔不編造沒有來源公布過的數字** |
| **WebNX** | **無任何可辯護數字** | ZoomInfo 與 datacenters.com 皆 HTTP 403、Crunchbase 無募資揭露。**本檔不作任何估計。針對 $100M 門檻：公開資料完全不支持** |

**其他量測衝突**
- **WebNX Ogden 面積**：官網與 datacenters.com「over 100,000 sq ft」 vs LinkedIn「nearly 150,000 square-foot」——**未解，以 100,000+ 為可辯護下限**。
- **WebNX 總部州別**：BBB、職缺、CEO LinkedIn 皆指 Ogden UT vs datacenters.com 與 ZoomInfo 稱加州——**未解，本檔採 Ogden**。
- **Psychz 設施數**：PeeringDB **16** vs 官網 network 頁 **17** vs colocation 頁 **66**——**66 幾可確定是夥伴／轉售足跡，不得引為自營站點數**。
- **Psychz 網路容量**：官網「6 Tbps+」（容量）vs PeeringDB 自報 1–5 Tbps（實際流量）——**兩者是不同量測，不可混用**。
- **Psychz 創立年份**：品牌 2001（「25 Years And Counting」）vs LinkedIn 與聚合站 1999 vs 加州法人 2012-04-23 vs 自營機房 2014——**未解**。
- **Sharktech 客戶數**：官網首頁同時出現「more than 10,000 businesses」與「more than 1,000+ businesses」，LinkedIn 與 Virtuozzo 稱「over 1,000 clients across 73 countries」——**公司自我矛盾；可辯護值為 1,000+／73 國**。
- **ReliableSite 創立年份**：品牌自稱 2006 vs FL 法人 2014-12-11 vs ASN 2018-08-10——**正確表述為「品牌自 2006、法人自 2014、ASN 自 2018」，不要講「20 年公司歷史」**。
- **Hostwinds 創立年份**：公司稱 2010（Tulsa）vs BBB「Date of Business Started: March 14, 2016」——**未解**。
- **WebNX 創立年份**：LinkedIn／Indeed／BBB 皆稱 1999（BBB 為 1999-04-04）vs BBB 另記「locally incorporated 2018-09-14」——**後者未獲解釋，須與 1999 對帳**。
- **QuadraNet LA 面積**：自述套房「over 60,000 sq ft」vs datacenters.com 整棟 300,000 sq ft／80,000 sq ft raised floor——**兩者量測對象不同**。
- **Sharktech 各站「Over 1Tbps」**：同一句話在四個機房頁逐字重複，**讀來像樣板而非量測值**；各站實際承諾 transit 容量未揭露。

### 7.3 各業者未結 GAP 總覽（僅列必須在首次接觸前或接觸中補齊者）

**WebNX**：系統廠確認（最高優先）／Utah 州登記編號與狀態／營收（零可辯護數字）／各站 MW·kW、每櫃密度、PUE（**整櫃 colo 方案未公布安培配額**）／Ogden 面積衝突／Ogden 建物持有或長租／總部州別衝突／確切伺服器與機櫃數／**具名客戶為零**／CEO 與 COO 以外無具名人員（Dario Perovich 無 email 亦無 LinkedIn）／Dallas DA1 設施名稱與營運商／WebHostingTalk 403 與 datacentermap 429 擋抓取。

**Psychz**：GPU 全線無公開價／伺服器與機櫃數／各站電力總量／LA 機房產權（「擁有」不成立）／Supermicro 直接確認（無型號、無照片、無導覽、無職缺、無員工發言）／絕對營收／員工數三方矛盾且**查無任何徵才頁**（故無招募方名單、無 JD 硬體線索、無人力成長訊號）／主管全名（僅 William H. Lu 可考）／股權比例／客戶名單為單一來源次級擷取／設施數 16/17/66 衝突／創立年份四重衝突／業主政治紀錄僅為查無／**CA SOS 第一手頁面 403，簽約前須重拉**／無狀態頁、無 SLA 賠償表、無擴充路線圖。

**ReliableSite**：伺服器／節點／機櫃數／各設施自身 sq ft、cage 與合約 kW（現有全為房東整棟值）／當世代 Supermicro SKU 級確認／**自製機殼的主機板廠——本檔商業價值最高的單一未知**／確切員工數／可信營收／CEO 以外具名主管／**FEC 未結案（fec.gov 與 OpenSecrets 皆為 JS 介面無法程式查詢，屬「未能證明的負面結果」，須人工查詢）**／2014 年前的 8 年登記空窗／Querétaro 設施營運商／換機週期與年度採購量／三則案例以外的具名客戶／**BBB「F」評等（5 件投訴未回應）為客服聲譽訊號，非法律或監理處分**。

**Sharktech**：**Montana 本籍設立紀錄未取得**（原始章程、設立日、其他幹部股東皆在該處；NV SOS 與 Bizapedia 皆 CAPTCHA 阻擋）／五站的伺服器、機櫃、cage 面積全數未揭露／各站合約電力／**51 個 SKU 中約 50 個的平台廠不明**／**「our supplier」的名稱——替換戰最有價值的單一未知**／換機節奏、預算與採購流程／**查無任何現行職缺**／CEO 夫婦以外無具名技術人員／客戶名單未經查證／營收與員工數僅第三方估計且矛盾／客戶數自我矛盾／GPU 路線圖未公開／**Denver 遷移後的實際佔用未知（官網 Denver 頁仍在描述 H5 園區）**／各站實際承諾 transit 容量。

**Hostwinds**：**伺服器 OEM 完全未公開（本案最重要的未解問題，只能靠訪談、現場或試用機 BMC 橫幅確認）**／現行伺服器與機櫃數／WA SOS 的 UBI 與正式設立日／創立年份矛盾／**併購條件未揭露：價格、員工移轉、Peter Holden 留任、資本支出計畫皆無；Hostwinds 是否保有獨立硬體採購權是關鍵資格問題**／三站面積、cage、合約 kW、租或買／**PeeringDB 完全未列私有互連設施（罕見，導致設施層無法獨立佐證）**／無具名客戶且「Fortune 500」無實證／無 GPU 故無 AI 需求或 AI 資本支出意圖證據／**Peter Holden 的 FEC 資料無法查詢（是取得失敗，不是查無捐獻）**／hypervisor、儲存架構、10/25 GbE 能力／CEO 以外無具名技術主管／員工數 40 倍落差／**Tukwila 機房技師職缺屬 Wowrack，不得誤植**／七個非自營 colo 市場的設施與營運商。

**QuadraNet**：加州 SOS 實體編號、設立日、狀態、代理人（三個入口皆被阻擋）／「QuadraNet, Inc.」與「QuadraNet Enterprises, LLC」的關係／**美國實體在母公司清算後的法律與營運現況、清算人姓名、美國資產處置**／所有站點電力／伺服器與機櫃數／Dell 機隊細節（僅由 iDRAC 選項推得）／AMD EPYC 是否存在（僅第三方行銷文字）／併購後 CEO 身分衝突未解／具名企業客戶（僅 HostMantis 一則且來源頁已 NXDOMAIN）／員工數與營收僅第三方估計／QuadraNet 自身 LinkedIn 網址／Reston VA 與 St. Louis MO 未證實／530 W 6th Street 的業主、租約條件與到期日／**LA 套房中的實體 Supermicro 資產由誰控制——本帳戶唯一實際的商業角度，公開來源無法解決**。

### 7.4 工具與取得限制（影響本檔完整度，供下次重跑參考）

- **ZoomInfo、carta、figma、atlassian、spglobal、adobe 等 MCP 連接器需要 OAuth 授權，本次為非互動工作階段無法完成。** 這些連接器（尤其 ZoomInfo）若經由 claude.ai 連接器設定完成授權，重跑時很可能可以補上 WebNX、Psychz、QuadraNet 的營收估計與具名人員缺口。
- **HTTP 阻擋清單**：WebHostingTalk（403）、datacentermap（429）、datacenters.com（403）、ZoomInfo（403）、Crunchbase（403）、HostingAdvice（403）、DataCenterDynamics（403）、bizfileonline.sos.ca.gov（403）、Bizapedia／OpenCorporates（安全檢查／CAPTCHA，未予繞過）、esos.nv.gov（Incapsula）。凡依賴上述來源之發現，皆已在本檔中標記為社群來源、次級擷取或第三方估計。
- **JavaScript 介面無法程式查詢**：fec.gov 個人捐獻查詢、OpenSecrets 捐款人查詢、businessregistration.utah.gov、WA CCFS。因此 **ReliableSite（Rodion Davydov）與 Hostwinds（Peter Holden）的 FEC 結果屬「無資料」，不得寫成「沒有政治獻金」**；Utah 與 Washington 的州登記編號亦因此為 GAP。
- **政治紀錄一致原則**：本檔所有政治資料僅取自公開紀錄（FEC Schedule A API、ASIC 公告、州商業登記、BBB），並逐條標記為 `public-record`、`negative-result`、`gap` 或 `unverified`。**已明確排除的錯誤歸屬：FEC 中唯一的「PAUTZ, DANIEL J.」（Syracuse NY 律師）與 WebNX 創辦人無關，嚴禁張冠李戴。**
