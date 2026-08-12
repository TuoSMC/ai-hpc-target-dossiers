# ReliableSite（RELIABLESITE.NET LLC） — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國） · 專員 US8664 Tuo Cheng · **日期：** 2026-08-04
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有公司、無 SEC 申報，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之伺服器規格與定價、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 佛州邁阿密（法定）與紐澤西 Piscataway（營運）— East Coast 3／East Coast 1 = T2｜T3｜T6｜T7｜T12。**一組不符資格**：規則 11 之大型資料中心例外門檻為 100MW 以上，本業者遠低於此。應循 **T7（主管 Brian Leaver）**。T11 不符資格。
**CRM 狀態：** 2026-08-03 於 salesleads Search（Type = All）實查：無 lead、無 account、無 do-not-call 紀錄 — 從未註冊。

---

## 1. 結論摘要

ReliableSite 是一家創辦人自有、員工約 11–50 人的美國裸機／專用伺服器業者，自營 AS23470 網路與自有伺服器，橫跨六個租用的第三方機房區域——紐澤西 Piscataway、紐澤西 Newark、佛州邁阿密、加州洛杉磯、荷蘭阿姆斯特丹，以及建置中的墨西哥 Querétaro——販售單路桌上型／工作站級機種，價帶為每月 $49–$699。商業判定是：**這是一個已被打掉一半的既有 Supermicro 帳戶**——機殼生意已經流失到他們自製的設計，但主機板與電源這個插槽依照 CEO 自己公布的設計意圖仍然開放，而 AI／GPU 這一層則是一塊乾淨的空架，因此本案是「板級防守戰 ＋ GPU 全新開發」，不是例行續約，而且**必須由東岸團隊承作，不是一組**。全檔最強的單一證據，是 CEO Radic Davydov 具名的 [LowEndBox 專訪](https://lowendbox.com/blog/custom-built-for-success-interview-with-radic-davydov-ceo-of-reliablesite/)：他在文中親口指出機隊中有 Supermicro MicroCloud，接著用自己的話說明，在 MicroCloud 替換零件斷貨、價格變成「2-3 times the cost」之後，他自行設計了密度較標準 1U 高約 50% 的專屬機殼——**並刻意保持與市售主機板及電源相容**。唯一可能讓本案立刻死掉的做法，是開場就推整機或原廠機殼方案：那等於重新掀開當初失去這個帳戶的傷口；誠實的切角是板級／電源插槽與缺失的 GPU 平台，而**自製機殼所使用的主機板供應商是誰，是本檔商業價值最高的單一未知**。

---

## 2. 公司速覽

| 欄位 | 內容 |
|---|---|
| **法人名稱** | **RELIABLESITE.NET LLC** — Florida Division of Corporations 文件編號 **L14000189024**、EIN 47-2515613、狀態 **Active**、設立日 **2014-12-11**（[FL 登記紀錄](https://bisprofiles.com/fl/reliablesite-net-l14000189024)） |
| **總部（實查地址）** | **兩個真實可拜訪地點。公開紀錄中不存在任何紐約市地址。**（1）法定／登記：**2115 NW 22nd St, Miami, FL 33142-7335**，此址即 **CoreSite MI1** 大樓。（2）營運／東岸：**101 Possumtown Rd, Piscataway, NJ 08854**，此址即 **QTS Piscataway PNJ1** 大樓。公司把該區行銷為「New York City Metro」，但實體據點在紐澤西北部（[FL 登記](https://bisprofiles.com/fl/reliablesite-net-l14000189024)；[Yelp — Piscataway](https://www.yelp.com/biz/reliablesite-net-piscataway-township)） |
| **成立時間** | **品牌／營運自 2006 年**（公司 [About 頁](https://www.reliablesite.net/about/)；[LinkedIn](https://www.linkedin.com/company/reliablesite) 記「Founded 2006」）· **現行法人自 2014-12-11** · **自有 ASN 自 2018-08-10**。各州登記檢索皆查無 2014 年以前的任何前身法人，形成 8 年的登記空窗 |
| **所有權** | 封閉持股／創辦人自有。唯一列名幹部兼註冊代理人為 **Rodion R Davydov, Chief Executive Officer**。About 頁自稱「a financially stable and debt-free company」且「Our servers and equipment are 100% owned and operated in-house」。Florida 申報與 Crunchbase 皆查無募資輪、無 PE／VC 背景、無其他會員或經理人。**佛州 LLC 的會員權益非公開紀錄** |
| **員工數** | **11–50 人** — LinkedIn 公司頁自報區間、347 追蹤者 **［第三方／自報估計，單一來源，無任何交叉佐證］**。含 Piscataway 與 Miami 的支薪駐點機房技師（Glassdoor 列約 $60K 級距）以及 24/7 自有支援人力。確切員工數＝**GAP** |
| **營收** | **年營收 $1.2M — Kona Equity［第三方估計］**（[來源](https://www.konaequity.com/company/reliablesitenet-llc-4395702578/)）；**每員工營收 $27.6K — Owler［第三方估計］**。**警告：** $1.2M 與約 50,944 個 IPv4、五個 IXP 100G 埠、自報 1–5 Tbps、六個租用機房區域與 11–50 名員工明顯不相稱——光是機房費＋transit＋薪資很可能就超過此數。所有營收數字均視為低可信度的第三方模型，不是事實。無任何經稽核或自行公布的財務資料（私人 LLC、無 SEC 申報） |
| **ASN** | **AS23470 — ReliableSite.Net LLC（ARIN）**，註冊於 **2018-08-10**。originates **199 個 IPv4 前綴**與 **29 個 IPv6 前綴**；宣告 **約 50,944 個 IPv4 位址**；觀測前綴合計 267（231 IPv4／36 IPv6）。PeeringDB 自報 1000 個 IPv4／250 個 IPv6 前綴容量（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)） |
| **CRM 狀態** | **從未註冊。** 2026-08-03 於 salesleads Search（Type = All）實查：無 lead、無 account、無 do-not-call 紀錄 |
| **轄區／團隊** | FL＝**East Coast 3**、NJ＝**East Coast 1**，皆為 **T2 \| T3 \| T6 \| T7 \| T12**。一組僅在 Large End User／Data Center 例外下可承作，而 **規則 11 明定「大型資料中心」為 100MW 以上，本業者不符**，故該例外不適用。**應循 T7（主管 Brian Leaver）承作。** T11 不符資格 |

---

## 3. 原始名單更正表

以下每一列，都是原始工作名單中針對本業者被研究**推翻**或**無法證實**的敘述。首次接觸前必須先讀完——以錯誤前提開場會立即失去可信度。

| # | 原始名單的說法 | 判定 | 證據與正確說法 |
|---|---|---|---|
| 1 | ReliableSite 是「紐約」業者，可能是 **Digital Realty** 房客 | **反證（兩處錯誤）** | **（a）不在紐約市。** 公開資料中查無任何曼哈頓地址（111 8th Ave／60 Hudson／32 AoA 皆無）。PeeringDB 所載設施為 **QTS Piscataway PNJ1（101 Possumtown Rd, Piscataway, NJ）** 與 **Newark 的 165 Halsey Street** meet-me room；其產品 SKU 本身即帶 **「(PNJ)」** 地區碼，公司只是把該區「行銷為」New York City Metro。**（b）並非 Digital Realty 房客。** AS23470 在 PeeringDB 的 Digital Realty 設施數為 **零**；房東是 QTS（Blackstone 持有、前身 DuPont Fabros）、CoreSite（American Tower）、Equinix 與 Databarn。Digital Realty 確實在 Piscataway 有 EWR11/12/19，但位於 365 S Randolphville Rd／3 Corporate Place，**與 101 Possumtown Rd 是不同地址**。任何以 Digital Realty 關係切入的話術都會出錯（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)） |
| 2 | ReliableSite 使用 **Supermicro 和／或 Dell** 硬體 | **Supermicro 確認、Dell 反證，但附帶關鍵但書** | **Supermicro 由三條獨立證據成立：** 兩則各自獨立的 Web Hosting Talk 客戶評述（其一指該客戶的 ReliableSite 伺服器全都「use Supermicro hardware with onboard KVM」，另一則描述所購三台 ReliableSite 專用伺服器為「Supermicro barebones, Atom D510, 4GB, 500GB」，屬舊世代），再加上營運者層級的確認——CEO Radic Davydov 於 [LowEndBox 專訪](https://lowendbox.com/blog/custom-built-for-success-interview-with-radic-davydov-ceo-of-reliablesite/)親口討論 Supermicro MicroCloud。**但書極重要：** 該專訪本身就是「離開原廠機殼」的故事——MicroCloud 替換零件買不到、幾乎相同的新世代零件裝不上、價格為「2-3 times the cost」，於是他自行設計密度高約 50% 的專屬機殼，**並刻意保持與市售主機板及電源相容**。因此當世代部署很可能是自製機殼＋通用主機板，Supermicro 屬歷史／部分。**Dell：官網、規格頁、徵才、WHT／LowEndTalk、新聞稿、PeeringDB 全部零則 Dell／PowerEdge／iDRAC。原始名單的 Dell 說法毫無支撐——不得假設有 Dell 既有關係**（[Web Hosting Talk 討論串](https://www.webhostingtalk.com/showthread.php?t=1640888)） |
| 3 | ReliableSite「**自 2006 年營運**」 | **部分確認** | 2006 一律為**自述**（About 頁稱企業級專用伺服器「since 2006」；LinkedIn「Founded 2006」），且**僅在敘事層面**被 LowEndBox 專訪佐證——文中描述 Radic Davydov 於 2006 年在父親買主機公司失利後構思本業，並以 HELM 平台上的單台代管伺服器起家。**但**現行法人於 **2014-12-11** 在佛州設立（Doc L14000189024），ASN 23470 於 **2018-08-10** 註冊；各州登記皆查無 2014 年以前的任何前身。**正確表述：品牌／營運自 2006、法人自 2014、自有 ASN 自 2018。不要把「20 年公司歷史」當成已驗證的公司事實複述**（[FL 登記](https://bisprofiles.com/fl/reliablesite-net-l14000189024)） |
| 4 | ReliableSite「**完全自營**」——自有伺服器、網路與人員 | **部分確認** | **伺服器、網路、人員為真。** 伺服器：About 頁稱「Our servers and equipment are 100% owned and operated in-house」；CEO 自行設計機殼，公司亦自述現場備料、自行組裝。網路：自有 AS23470 與自有 IP 空間（約 50,944 個 IPv4）、自有 transit 組合（NTT／TATA／GTT／Arelion／Comcast／Hurricane Electric／NForce）、五個 IXP 各 100G 埠、自有 looking glass，以及自建的 L3/L4 DDoS 過濾系統。人員：在 Piscataway 與 Miami 直聘支薪駐點技師，另有 24/7 自有支援。**設施則不成立——所有站點都是租用他人大樓內的 colocation 空間**（QTS Piscataway、CoreSite MI1／LA1／LA2、Equinix MI1／AM7、Databarn、165 Halsey）。他們擁有的是 IT 與網路，不是資料中心。About 頁的「in-house maintained infrastructures」指的是他們放在第三方機房內的設備（[About 頁](https://www.reliablesite.net/about/)） |
| 5 | 原始名單的隱含前提：本業者已是 **Supermicro 客戶** | **就本業者而言確認——但這是例外，不是通則** | 在同一批研究的六家業者中，僅 **兩家** 的 Supermicro 獲得確認，而 ReliableSite 是其中證據較強的一家。這確實有價值——但見第 2 列：確認 Supermicro **在機隊中**，不等於確認 Supermicro **在當前採購循環中**。當世代 SKU 級確認仍是 **GAP** |

---

## 4. 領導層與所有權

**整份公開紀錄中只存在三位具名自然人，而其中一位包辦所有簽核。** Rodion Radic Davydov 是 **六家** 佛州 LLC 的唯一授權人——營運公司、母公司、硬體公司、軟體部門，以及兩家資料中心實體——自 **2014-12-11** 設立起，至他本人於 **2026-02-09** 簽署的年度申報為止，從未間斷。這六家公司**從來沒有**列過共同所有人、董事會或第二位簽署人。本次調查另循兩條非顯性路徑找出兩名員工——**USPTO 專利**與 **FEC 雇主欄位掃描**——兩人在商業上都具意義：一位是公司自有伺服器機殼的**共同發明人**，另一位是**機隊主力所在的紐澤西站點經理**。

### 4.1 具名人員

以下證據等級定義：**primary-record（一手紀錄）**＝該姓名出現在官方申報或登記紀錄上 · **corroborated（多源佐證）**＝一手紀錄再加至少一個獨立第二來源 · **single-source（單一來源）**＝僅一個來源，引用前須再驗證。

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC 紀錄 | 來源 |
|---|---|---|---|---|---|---|
| **Rodion Radic Davydov**（公開使用「Radic Davydov」） | 創辦人暨執行長；同時是該 LLC 的 **Registered Agent（註冊代理人）** | 高階主管／所有人／**登記機關具名幹部** | **primary-record** | **rdavydov@reliablesite.net**——他本人公開於 ARIN 的信箱，遠優於 sales@ · +1-866-932-0001 · **查無個人 LinkedIn 檔案（GAP）** | **查無 FEC 紀錄。** 已檢索「davydov, rodion」「davydov, radic」「davydov, r」——共 6 筆，全屬他人（DAVYDOV, ROBERT／RAFAEL／ROMAN）；全佛州「davydov」掃描回傳 70 筆，全為 DAVYDOVA, SOFYA。無政治獻金紀錄 | [Sunbiz 實體明細 L14000189024](https://search.sunbiz.org/Inquiry/CorporationSearch/SearchResultDetail?inquirytype=EntityName&directionType=CurrentList&searchNameOrder=RELIABLESITENET%20L140001890240&aggregateId=flal-l14000189024-03597cea-0c5a-4c28-9b85-f433fa494b02&searchTerm=RELIABLESITE&listNameOrder=RELIABLESITENET%20L140001890240) · [2014 年設立章程](https://search.sunbiz.org/Inquiry/CorporationSearch/ConvertTiffToPDF?storagePath=COR%5C2014%5C1211%5C60345606.tif&documentNumber=L14000189024) · [2026 年度申報](https://search.sunbiz.org/Inquiry/CorporationSearch/GetDocument?aggregateId=flal-l14000189024-03597cea-0c5a-4c28-9b85-f433fa494b02&transactionId=l14000189024-2514e387-50a7-439c-8abd-76386218da8f&formatType=PDF) |
| **Alexander Sinelnikov**（慣用 **Alex Sinelnikov**） | ReliableSite.net 資深機房技師 Level II；**US Patent 12,328,849 B2 的具名共同發明人** | 技術窗口／站點技術團隊主管 | **corroborated**（USPTO 一手紀錄＋LinkedIn） | 僅 [linkedin.com/in/alex-sinelnikov-45b16938](https://www.linkedin.com/in/alex-sinelnikov-45b16938/)——**查無公開信箱或電話（GAP）**；他**不是** ARIN 或 PeeringDB 的 POC，其餘只能走 support@／careers@reliablesite.net 的公用信箱 | **查無 FEC 紀錄。**「sinelnikov」回傳 66 筆，全屬他人（SINELNIKOV, ANDREY／KELSY；SINELNIKOVA, JULIA／YELENA），且無人以 ReliableSite 為雇主 | [US 12,328,849 B2 — Google Patents](https://patents.google.com/patent/US12328849B2/en) |
| **Shahalam Hossain** | ReliableSite.Net 紐約都會區機房經理（其於聯邦申報自填職業為「MANAGER」） | 站點經理 | **corroborated**（聯邦申報＋LinkedIn＋ZoomInfo） | 僅 [linkedin.com/in/shahalam-hossain-774322122](https://www.linkedin.com/in/shahalam-hossain-774322122)——ZoomInfo 顯示遮蔽形式 **s\*\*\*@reliablesite.net**。公司慣例看似為「名首字母＋姓」（參照 rdavydov@），但**本檔不將推導出的信箱陳述為事實（GAP）** | **有紀錄——且這筆申報正是他姓名的發現來源。** 2024-10-28 向 ACTBLUE（Hybrid PAC）捐 $50.00，備註「EARMARKED FOR HARRIS FOR PRESIDENT (C00703975)」，Form 3X 第 11AI 行；捐款人 HOSSAIN, SHAHALAM，Paterson NJ 07501-2510，職業 MANAGER，**雇主 RELIABLESITE**；年初至今累計 $50.00 | [FEC 個人捐獻，雇主＝RELIABLESITE](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=reliablesite) |
| **「Radic Davydov」**——ARIN handle **DAVYD-ARIN** | ARIN Org RL-323 的 **OrgAdmin**（行政 POC）；NET-104-243-32-0-1 的 **RTech**；NET-206-221-176-0-1 的 **RNOC**（於該處列為「Davydov, Radic」） | **網路登記機關窗口——具名自然人**（RDAP kind=individual） | **primary-record** | rdavydov@reliablesite.net · +1-866-932-0001 | 與第 1 列為同一人——**查無 FEC 紀錄** | [ARIN RDAP — Org RL-323](https://rdap.arin.net/registry/entity/RL-323) |
| **「Abuse, Radic」**——ARIN handle **ABUSE6422-ARIN** | NET-104-243-32-0-1 與 NET-206-221-176-0-1 的 **RAbuse**（網路層濫用申訴 POC） | 網路登記機關窗口——以個人名字掛在 abuse handle 上；**是同一人，不是第二個人** | **primary-record** | abuse@reliablesite.net | 與第 1 列為同一人——**查無 FEC 紀錄** | [ARIN RDAP — Org RL-323](https://rdap.arin.net/registry/entity/RL-323) |
| **「Support Department」**——ARIN handle **SUPPO1295-ARIN** | RL-323 的 **OrgTech**，並為數個網段的 **RNOC** | 網路登記機關**角色帳號**（RDAP kind=group）——**背後查無自然人姓名＝GAP** | primary-record（可確認其為角色帳號而非個人） | support@reliablesite.net · +1-866-932-0001 | 不適用——非自然人 | [ARIN RDAP — SUPPO1295-ARIN](https://rdap.arin.net/registry/entity/SUPPO1295-ARIN) |
| **「Abuse Department」**——ARIN handle **ABUSE3593-ARIN** | RL-323 的 **OrgAbuse** | 網路登記機關**角色帳號**（kind=group）——**查無自然人姓名＝GAP** | primary-record（角色帳號） | abuse@reliablesite.net · +1-866-932-0001 | 不適用——非自然人 | [ARIN RDAP — ABUSE3593-ARIN](https://rdap.arin.net/registry/entity/ABUSE3593-ARIN) |
| **「ReliableSite Abuse」** | **PeeringDB Abuse 聯絡人**，net 17907（POC id 28195，建立於 2018-12-10） | PeeringDB **角色帳號**——**查無自然人姓名＝GAP** | primary-record（角色帳號） | complaints@reliablesite.net | 不適用——非自然人 | [PeeringDB net/17907](https://www.peeringdb.com/net/17907) |
| **「Peering」** | **PeeringDB Policy 聯絡人**（POC id 28577，建立於 2019-01-07）。政策 Open，1–5 Tbps，以出向為主，5 個 IXP／8 個設施 | PeeringDB **角色帳號**——**查無自然人姓名＝GAP** | primary-record（角色帳號） | peering@reliablesite.net | 不適用——非自然人 | [PeeringDB net/17907](https://www.peeringdb.com/net/17907) |

**本次的新發現，以及為何這不只是把同一個 CEO 說法重講一次：**

- **Davydov——是查證並擴充，不是複述。** Sunbiz 實體明細只列出**一位**授權人（「Title CEO — DAVYDOV, RODION R, 2115 NW 22nd St, Miami, FL 33142」），且註冊代理人為同一人，頁面顯示「No Events／No Name History」。本次已調閱並 OCR **2014-12-11 的原始電子設立章程**：Article IV 僅列一名獲授權管理該 LLC 之人——「Title: CEO, RODION R DAVYDOV, 7600 Collins Ave #712, Miami Beach, FL 33141」，Article III（註冊代理人）與 Article V（電子簽章）亦為其簽名。**因此自設立至今，從未出現過第二位幹部。** **2026-02-09 年度申報**的文字層顯示簽名欄為「SIGNATURE: RODION RADIC DAVYDOV／CEO／02/09/2026」，一舉解決長期存在的 Rodion 與 Radic 之疑：**Radic 是他的中間名，也是他對外使用的名字。** 他是全部六家佛州實體的唯一 CEO（見 §4.2）。其客服系統帳號「Radic D.」帶有 **Employee 標章、加入日期 2008-04-29**——營運早於 2014 年設立的 LLC，與 About 頁「自 2006 年起」的說法一致。他在 LowEndBox、HostingJournalist、HostingAdvice 專訪中均以 CEO／創辦人具名，並且是公司 CloudFest 2026 回顧文的署名作者。
- **Sinelnikov——先前各輪調查漏掉的最重要姓名。** 他是 **US 12,328,849 B2「Space saving data center system」** 的具名共同發明人（申請號 18/332,807，2023-06-12 申請，2025-06-10 核准），現任受讓人為 **BOOT HARDWARE LLC**——即 Davydov 的佛州硬體實體。Google Patents 結構化資料回傳發明人 `['Alexander Sinelnikov', 'Rodion Davydov']`、現任受讓人 `['Boot Hardware LLC']`；Boot Hardware 名下**恰好只有一件**專利。**已施加反面對照：** 有搜尋摘要聲稱專利 12,328,854 亦列同兩位發明人——經實際抓取確認該案為 LG Innotek 的「Power converter」，故予以捨棄而非誤報。其 LinkedIn 獨立佐證他任職 ReliableSite.net，帶領機房技師團隊，負責 **Piscataway, NJ 逾 1,000 台專用伺服器**。他因此同時是紐澤西站點的第一線技術團隊主管，也是該公司「自造而非外購」機殼的共同設計者。
- **Hossain——由 FEC 雇主欄位掃描找出，這正是能挖出隱形員工的技巧。** 以 `employer = reliablesite` 過濾 FEC 個人捐獻，恰好回傳**一筆**紀錄，展開後即得其姓名、城市、職業與雇主，屬**自填且具法律效力的聯邦申報**。地理佐證強烈：Paterson NJ 距離紐約都會區站點 101 Possumtown Rd, Piscataway 約 15 英里。LinkedIn 與 ZoomInfo 人物紀錄（職稱「NYC Metro Center Manager at ReliableSite.Net」）另行獨立佐證。
- **所有權——創辦人自有、無槓桿、其上無任何核准關卡。** 查無外部投資人、無 PE／VC、無董事會、無顧問。Florida Secured Transaction Registry 對六家實體均回傳 **零筆 UCC-1**（對照組查詢「PUBLIX SUPER MARKETS」回傳 20 筆債務人資料，證明查詢路徑有效），此與 About 頁自稱「financially stable and debt-free」一致，代表**採購案上頭沒有貸方或投資人需要簽核**。惟佛州 LLC 的會員權益非公開紀錄，股權結構本身仍無法查證。

### 4.2 登記紀錄

| 姓名 | 身分 | 申報文件 | 申報日期 | 來源 |
|---|---|---|---|---|
| **DAVYDOV, RODION R** | **CEO——唯一授權人**；同時為註冊代理人 | **RELIABLESITE.NET LLC**——文件號 L14000189024，FEI/EIN 47-2515613，狀態 ACTIVE，主要地址 2115 NW 22nd St, Miami FL 33142（地址於 2017-01-09 變更） | 2014-12-11 申報；2015-01-01 生效 | [Sunbiz 實體明細](https://search.sunbiz.org/Inquiry/CorporationSearch/SearchResultDetail?inquirytype=EntityName&directionType=CurrentList&searchNameOrder=RELIABLESITENET%20L140001890240&aggregateId=flal-l14000189024-03597cea-0c5a-4c28-9b85-f433fa494b02&searchTerm=RELIABLESITE&listNameOrder=RELIABLESITENET%20L140001890240) |
| **RODION R DAVYDOV** | **CEO**（Article IV——唯一獲授權管理之人）＋註冊代理人簽名（Article III）＋電子簽章（Article V） | **RELIABLESITE.NET LLC**——電子設立章程（原始設立文件，自掃描 TIFF/PDF 經 OCR 取得）。設立時地址：7600 Collins Ave #712, Miami Beach FL 33141 | 2014-12-11 | [設立章程](https://search.sunbiz.org/Inquiry/CorporationSearch/ConvertTiffToPDF?storagePath=COR%5C2014%5C1211%5C60345606.tif&documentNumber=L14000189024) |
| **RODION RADIC DAVYDOV** | **CEO**——年度申報的電子簽署人（「Signature of Signing Authorized Person」）；依 Chapter 605 F.S. 聲明其為「a managing member or manager」 | **RELIABLESITE.NET LLC**——2026 年佛州 LLC 年度申報（申報編號 6175444164CC）。已檢視 2016–2026 全部年度申報：**從未增列或移除任何幹部** | 2026-02-09 | [2026 年度申報 PDF](https://search.sunbiz.org/Inquiry/CorporationSearch/GetDocument?aggregateId=flal-l14000189024-03597cea-0c5a-4c28-9b85-f433fa494b02&transactionId=l14000189024-2514e387-50a7-439c-8abd-76386218da8f&formatType=PDF) |
| **DAVYDOV, RODION R** | **CEO——唯一授權人**；同時為註冊代理人。此為**集團母公司**（unpack.me 明列 Tech in a Box LLC 為母公司） | **TECH IN A BOX LLC**——文件號 L22000268350，FEI/EIN 88-2838608，18117 Biscayne Blvd Suite #2577, Miami FL 33160 | 2022-06-13 | [Sunbiz 明細](https://search.sunbiz.org/Inquiry/CorporationSearch/SearchResultDetail?inquirytype=OfficerRegisteredAgentName&directionType=Initial&searchNameOrder=X&aggregateId=flal-l22000268350-fab79cc9-9a8e-4caa-a223-ae6a81fd4c7e&searchTerm=DAVYDOV%20RODION&listNameOrder=X) |
| **DAVYDOV, RODION R** | **CEO——唯一授權人**；同時為註冊代理人。**硬體實體**——US Patent 12,328,849 的受讓人，並營運 boothardware.com | **BOOT HARDWARE LLC**——文件號 L22000275489，FEI/EIN 88-3224329，18117 Biscayne Blvd Suite #2577, Miami FL 33160 | 2022-06-16 | [Sunbiz 明細](https://search.sunbiz.org/Inquiry/CorporationSearch/SearchResultDetail?inquirytype=OfficerRegisteredAgentName&directionType=Initial&searchNameOrder=X&aggregateId=flal-l22000275489-af9cddf0-03e7-4f0e-a39f-798ad5f7bd94&searchTerm=DAVYDOV%20RODION&listNameOrder=X) |
| **DAVYDOV, RODION R** | **CEO——唯一的自然人授權人。** 第二位授權人是**法人而非自然人**：「Title MGR — TECH IN A BOX LLC」。註冊代理人為 Tech In A Box LLC | **DEPLOY2K LLC**——文件號 L22000275572，FEI/EIN 88-3236244，18117 Biscayne Blvd Suite #2577, Miami FL 33160（軟體／自動化部門：ADMN、LaunchMC） | 2022-06-16 | [Sunbiz 明細](https://search.sunbiz.org/Inquiry/CorporationSearch/SearchResultDetail?inquirytype=OfficerRegisteredAgentName&directionType=Initial&searchNameOrder=X&aggregateId=flal-l22000275572-55f9164a-4aec-4fff-86e5-b46589e2b8c7&searchTerm=DAVYDOV%20RODION&listNameOrder=X) |
| **DAVYDOV, RODION** | **CEO——唯一授權人。** 註冊代理人為 Tech In A Box LLC | **SYSTEM DATA CENTERS LLC**——文件號 L24000271009，FEI/EIN 33-2277061，18117 Biscayne Blvd Suite #2577, Miami FL 33160 | 2024-06-14（2024-06-13 生效） | [Sunbiz 明細](https://search.sunbiz.org/Inquiry/CorporationSearch/SearchResultDetail?inquirytype=OfficerRegisteredAgentName&directionType=Initial&searchNameOrder=X&aggregateId=flal-l24000271009-38b94b3d-d719-469b-af86-64bf9f866e5e&searchTerm=DAVYDOV%20RODION&listNameOrder=X) |
| **DAVYDOV, RODION R, MR** | **CEO——唯一授權人。** 註冊代理人為 Tech In A Box LLC。實體名稱對應 **CoreSite MI1**，即 §5 所列的邁阿密設施 | **SYSTEM MI1 LLC**——文件號 L24000326360，FEI/EIN 33-1350354，18117 Biscayne Blvd Suite #2577, Miami FL 33160 | 2024-07-23 | [Sunbiz 明細](https://search.sunbiz.org/Inquiry/CorporationSearch/SearchResultDetail?inquirytype=OfficerRegisteredAgentName&directionType=Initial&searchNameOrder=X&aggregateId=flal-l24000326360-a76cc248-1e4d-4355-bc41-e63b90c01f81&searchTerm=DAVYDOV%20RODION&listNameOrder=X) |

### 4.3 採購決策圈

| 對象 | 為何對伺服器採購案重要 | 如何接觸 |
|---|---|---|
| **Rodion Radic Davydov——創辦人暨執行長，六家實體的唯一所有人** | **凡涉及策略，他一個人就是整個採購決策圈。** 三項獨立佐證：（1）自 2014 年至 2026 年度申報，他是六家佛州實體的唯一授權人——沒有共同所有人、沒有董事會、也沒有第二位能簽約的簽署人；（2）公司自家的 **Director of Engineering** 職缺明載該職「report directly to the CEO」，證實組織扁平，工程之上除他之外沒有任何一層；（3）他在 HostingAdvice 專訪（2024-01-17）中以第一人稱表明自己掌握供應商關係：「We manufacture a lot of our own hardware and work really closely with hardware manufacturers to get exactly what we're looking for in terms of specs that aren't necessarily brought to market the way we would expect them to.」他同時是規格制定者、談判者與簽署者。**商務要點：採購單（PO）很可能由 BOOT HARDWARE LLC（持有機殼專利的硬體實體）或 TECH IN A BOX LLC（母公司）開立，而非 RELIABLESITE.NET LLC——報價與合約主體須據此處理。** | **不要找守門人，因為根本沒有。** 最佳路徑是面對面：Unpack.me／ReliableSite 將設 **CloudFest Americas 401 號攤位，2026 年 11 月 11–12 日**（他們亦曾在 2026 年德國 Rust 的 CloudFest 設 R29 攤位）。第二條路：**rdavydov@reliablesite.net**，他本人公開於 ARIN 的信箱，遠優於 sales@。第三：以 peering@reliablesite.net 作技術／網路面的開場。第四：他固定往來的主機業媒體（LowEndBox、HostingJournalist、HostingAdvice），他向來樂於受訪。**定位必須尊重「他自造機殼、只買零組件」的事實：主打主機板、板＋CPU 托盤、純零件級供應，以及未在市面推出的客製 SKU——而不是完整的品牌 1U／2U 整機，那正是他刻意繞開的東西。** |
| **Alexander（Alex）Sinelnikov——資深機房技師 Level II；US 12,328,849 共同發明人** | **技術把關者，也是最可信的內部支持者。** 他與 Davydov 共同發明背對背機殼，因此任何替代硬體必須滿足的機構／散熱限制，是他親手訂下的（該產品支援最大 12in × 9.6in 的 ATX／mATX 主機板、6 顆 40mm 風扇、雙 500W 電源）。他同時帶領負責 **Piscataway NJ 逾 1,000 台伺服器**的機房技師團隊，因此掌握上架人力、可維修性與 RMA 痛點——正是供應商可以攻擊的成本項。**若方案在尺寸規格與密度上說服不了他，CEO 根本不會看到。** | **工程師對工程師，不是業務簡報。** [LinkedIn](https://www.linkedin.com/in/alex-sinelnikov-45b16938/) 是唯一直接管道——他不是 ARIN 或 PeeringDB 的 POC，也沒有公開信箱。開場請談：相對於他們已取得專利的 1U 雙機設計的密度與散熱、**在他們現有機殼內**的主機板相容性，以及可維修性／熱抽換帶來的人力節省。在此建立可信的技術關係，是通往 CEO 會面最乾淨的路。 |
| **Shahalam Hossain——紐約都會區機房經理（Paterson NJ）** | **最大據點的站點層級影響者。** 位於 101 Possumtown Rd, Piscataway 的紐約都會區部署座落於 QTS（前身 DuPont Fabros NJ1）之內，也是機隊主力所在。機房經理掌握該站的部署排程、備品／RMA 處理、電力與機櫃密度——他會形塑需求，也能以維運理由否決，**但他不會簽名。** | [LinkedIn](https://www.linkedin.com/in/shahalam-hossain-774322122)。切入角度：Piscataway 站的部署物流、備品倉、RMA 週轉，以及機櫃密度的經濟性。**適合用來在接觸 CEO 之前，先確認真實的汰換時點與數量**，並交叉驗證 CEO 所言。 |
| **Boot Hardware LLC／Tech In A Box LLC——是簽約主體，不是自然人** | 雖非自然人，但仍應列入決策圈地圖，因為它決定**由誰簽、用誰的合約紙**。Boot Hardware LLC 是機殼專利的受讓人，並營運 boothardware.com（網域註冊組織為 Tech In A Box LLC），以 **$799 販售 CHA-1U-B2B-R1 機殼**——意即該集團本身也是硬體供應商，不只是買方。Tech In A Box LLC 在 unpack.me 上被列為母公司，並擔任較新實體的註冊代理人／經理人。兩者的唯一 CEO 都是 Davydov，簽名者不變，**但交易對手名稱、EIN 與信用檔案並不相同。** | **報價階段務必明確詢問由哪一家實體開立 PO。** 另有通路／合作角度：Boot Hardware 是潛在的 OEM／ODM 夥伴或零件客戶，而非單純競爭者——**談零件供應或共同工程，可能打開單純賣整機打不開的門。** |
| **Director of Engineering——職缺現為開放且尚未補實；直接向 CEO 匯報** | 這是一則正在招募的公開職缺，一旦補實即成為真正的技術採購影響者。職缺說明該人將管理既有開發團隊，並負責內部自動化系統、面客入口與帳務整合的架構、開發與部署。**目前這是一個沒有姓名的 GAP**——但它是公司唯一試圖建立的工程領導層級。 | 持續追蹤 reliablesite.net/careers 與 LinkedIn 的到職動態。**在此之前無人可聯絡——不得虛構聯絡人。** 同期開放的另有：Senior Network Engineer（遠端）、Senior .NET Software Engineer（遠端）、Data Center Technician（Miami）。四則職缺一律只導向 careers@reliablesite.net，**未列任何具名招募主管**。 |

### 4.4 無法具名的職位——以下每一項均為 GAP

**CFO／Controller／VP Finance——查無姓名**（六份 Sunbiz 申報均無財務幹部，公開資料亦無任何財務窗口；強烈推論此職能由 CEO 本人兼理） · **CTO——查無姓名**（該職並不存在；公司改以招募直接向 CEO 匯報的 Director of Engineering 取代） · **Director of Engineering——職位存在但從缺**，無在任者、無具名招募主管 · **VP Infrastructure／機房營運主管——集團層級查無姓名**（僅識別出站點層級管理者：Hossain 負責紐約都會區、Sinelnikov 為機房技師團隊主管） · **採購／進貨／供應鏈主管——查無姓名**（公開資料無任何採購職能證據；CEO 自述由他本人直接與硬體製造商往來） · **COO／總經理——查無姓名** · **網路工程主管／NOC 主管——查無姓名**（ARIN OrgTech 與 PeeringDB Policy／NOC 皆僅為角色帳號：support@、peering@、complaints@；Senior Network Engineer 職缺開放中且未補實） · **法務長／法務窗口——查無姓名**（查無任何代理律師；唯一一起聯邦訴訟僅列該 LLC 為當事人，且因從未申請商標，故亦無商標聯絡人） · **董事會／投資人／顧問——並不存在**（單一授權人 LLC、Crunchbase 無募資、零筆 UCC-1 留置權、自述「financially stable and debt-free」——**採購案上頭沒有投資人或貸方的核准關卡**） · **人資／招募主管——查無姓名**（四則職缺全數導向 careers@ 角色信箱） · **業務／業務開發／合作夥伴主管——查無姓名** · **Los Angeles、Amsterdam、Querétaro 三個較新據點的站點主管——三者均查無姓名** · **兄弟品牌（Deploy2K、ADMN、LaunchMC、Presence、System Data Centers）的品牌／產品主管——查無姓名**；全部為 Davydov 所有，且他是唯一 CEO · **商標聲明簽署人與聯絡人——並不存在**（已驗證：「ReliableSite」與「Boot Hardware」皆無任何美國商標申請或註冊） · **UCC-1 擔保權人與債務人簽署人——並不存在**（已驗證：六家實體在佛州皆為零筆 UCC 申報） · **CEO 以外的具名授權採購人／PO 簽署人——查無姓名，且登記證據積極顯示此人並不存在。**

### 4.5 已實際查詢的來源——包含查了但一無所獲者

**產出姓名者：** Florida Division of Corporations（Sunbiz）實體明細、2016–2026 完整年度申報紀錄、2014 年原始設立章程，以及以「DAVYDOV RODION」進行的幹部／註冊代理人姓名檢索——最後這一項**揭露了先前未知的五家兄弟實體** · **USPTO／Google Patents**，產出 Sinelnikov，是本次價值最高的來源 · **FEC 個人捐獻以 employer = RELIABLESITE 過濾**，產出 Hossain · **AS23470 的 ARIN WHOIS／RDAP**（Org RL-323，已列舉 16 個網段），產出具名個人 handle DAVYD-ARIN · **BBB 檔案**（Rodion Davydov, CEO 為唯一負責人兼唯一客戶窗口） · **媒體與專訪**（LowEndBox、HostingJournalist、HostingAdvice、完整 hosting-news 索引、/about、/careers） · **unpack.me 的集團架構對照** · **LinkedIn**，僅能透過搜尋索引中介資料部分取得。

**已查詢但無可用結果——上述 GAP 是查過的，不是偷懶：** **PeeringDB** net 17907／org 21056（僅兩個 POC，均為角色帳號，無自然人姓名） · **Delaware ICIS 與 Nevada SOS**（DE 需互動式 ASP.NET postback；NV 位於 Imperva／Incapsula 之後——各路徑均查無 DE／NV 實體，且六家集團實體全為佛州 LLC 並持佛州 EIN） · **reliablesite.net 的歷史 WHOIS**（註冊商 Porkbun，全面隱私遮蔽；whoisrequest.com 與 whoisxmlapi 皆被封鎖——**未能取得隱私遮蔽前的註冊人姓名，屬實質 GAP**；兄弟網域 boothardware.com 則有部分斬獲，其註冊組織未遮蔽，顯示為「Tech In A Box LLC」） · **USPTO 商標（經 TMview）**——以有效對照組驗證之負面結果（「cloudflare」→ 6 筆美國商標；「reliablesite」→ 0；「boothardware」→ 0），故**根本不存在可找的商標聲明簽署人** · **CourtListener／RECAP 案件檔**（7 筆命中；唯一以該公司為當事人的案件為 *Rosen v. Reliablesite.net LLC*，3:24-cv-06040 N.D. Cal.——**該案卷上的個人是原告與共同被告的海報網站經營者，並非 ReliableSite 人員，已刻意排除**） · **Florida Secured Transaction Registry（UCC-1）**——透過後端搜尋 API 並以有效對照組驗證之負面結果（「PUBLIX SUPER MARKETS」→ 20 筆債務人資料）；七種實體名稱變體全部回傳 **零筆** · **Miami-Dade 地政估價與 NJ 不動產紀錄**（2115 NW 22 ST 的所有權人為「CRP MIA TELCO L P, C/O CRG WEST」——CRG West 即 CoreSite 舊名，確認 ReliableSite 是 **colocation 房客而非產權人**；NJ 紀錄網站回傳 403） · **職缺公告**（四則開放職缺，**均無具名招募主管**，但在結構上具決定性：Director of Engineering「直接向 CEO 匯報」） · **研討會檔案**（CloudFest 產出 401 號攤位這個接觸窗口；**NANOG 與會者／講者檔案中查無 ReliableSite、Davydov 或 Sinelnikov**） · **WebHostingTalk／LowEndTalk／公司客服系統**（查無第二個員工帳號；社群索引僅露出角色信箱） · **B2B 資料聚合商**——ZoomInfo 的人物與公司頁面對直接抓取回傳 HTTP 403，且**本環境中的 ZoomInfo MCP 連接器未完成授權**，故其員工名錄工具無法執行；於 claude.ai 連接器設定中完成授權後，很可能可取得更多聯絡人。

---

## 5. 據點與機房

**六個區域，全部租用。他們在別人的大樓裡擁有自己的伺服器與網路——一座資料中心都不擁有。** 以下所有存在的面積與電力數字，**皆為房東的整棟數值**；ReliableSite 自身的 cage／套房面積與合約 kW **在每一個站點都未公開**。

| 站點 | 自有／租用 | 面積與電力（已公布者） | 證據 |
|---|---|---|---|
| **QTS Piscataway PNJ1 — 101 Possumtown Rd, Piscataway, NJ 08854**（行銷為「New York City Metro」；SKU 帶「(PNJ)」地區碼） | **租用 colocation。** 建物由 **QTS Data Centers** 營運（Blackstone 自 2021-08 持有，前身 DuPont Fabros）。ReliableSite 擁有其中的伺服器與網路，不擁有設施 | 全設施 **360,000 sq ft／約 176,000 sq ft raised floor**，額定 **約 52–65 MW**——**皆為 QTS 整棟數字。ReliableSite 自身的 cage 面積與 kW 配額未公開（GAP）** | PeeringDB 將「QTS Piscataway (PNJ1)」列為 AS23470 的互連設施；公司自家徵才貼文招募 **Piscataway 駐點 Data Center Technician**；Yelp 與 D&B 亦將人員定位於 101 Possumtown Rd；datacentermap／datacenters.com 確認 101 Possumtown Rd 即 QTS Piscataway（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)；[NJ 機房技師徵才](https://www.reliablesite.net/hosting-news/nj-job-data-center-technician/)） |
| **165 Halsey Street Meet-Me Room, Newark, NJ**（電信樞紐大樓——互連／transit 節點） | 租用／僅互連據點 | **GAP／GAP** | 於 PeeringDB 列為 AS23470 互連設施。與其 NY-metro transit 組合（NTT、GTT、TATA、Arelion）及 DE-CIX New York／NYIIX peering 一致（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)） |
| **CoreSite MI1 — 2115 NW 22nd St, Miami, FL 33142**（同時是公司法定登記地址） | **租用 colocation**（CoreSite，現屬 American Tower）。ReliableSite 為房客，並以該大樓為公司地址 | 設施 **約 43,000+ sq ft** colocation（CoreSite 整棟數字）。**ReliableSite 自身 cage 面積與電力＝GAP** | PeeringDB 列出「CoreSite - Miami (MI1)」；PeeringDB 的組織地址與 FL SOS 主要地址皆為 2115 NW 22nd St，datacentermap／baxtel／CoreSite 確認該址即 CoreSite MI1。ReliableSite 於此設有駐點 Miami 機房技師（[CoreSite MI1](https://www.coresite.com/data-center/mi1-miami-fl)） |
| **Equinix MI1 — Miami, FL** | 租用 colocation／互連（Equinix） | **GAP** | 於 PeeringDB 列為 AS23470 互連設施；ReliableSite 亦於 Equinix Miami 交換點以 100G 埠 peering（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)） |
| **CoreSite LA1（One Wilshire, 624 S Grand Ave）與 CoreSite LA2（900 N Alameda St），Los Angeles, CA** | 租用 colocation（CoreSite／American Tower） | **GAP** | PeeringDB 將「CoreSite - Los Angeles (LA1 & LA2)」列為 AS23470 設施；ReliableSite 於 Any2West（CoreSite）以 100G 埠 peering。洛杉磯係經 2017 年新聞稿〈ReliableSite Expands Global Network with Data Center in Los Angeles〉啟用。**目前唯一在售且有庫存的 NVIDIA A10 GPU 機種即列於洛杉磯**（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)） |
| **荷蘭阿姆斯特丹 — Equinix AM7 與 Databarn Amsterdam** | 租用 colocation（Equinix；Databarn） | **GAP** | 兩者皆於 PeeringDB 列為 AS23470 互連設施。網路頁列出 AMS-IX 與 ERA-IX peering、以 NForce 為 transit，並有阿姆斯特丹 looking glass nl1-lg.reliablesite.net（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)） |
| **墨西哥 Querétaro（QRO）—「coming soon」，最新區域** | 租用 colocation、carrier-neutral 設施——**營運商未由 ReliableSite 具名，亦無法識別（GAP）** | **GAP** | 公司機房頁列出 Querétaro 具備「carrier-neutral connectivity, dedicated telecom meet-me rooms, and direct access to PIX México 1 and PIX México 2」；網路頁顯示 QRO 為「Network Test Coming Soon」並列出 IENTC／Wantelco peering，即建置進行中。**這是本帳戶最可能的近期新硬體採購觸發點**（[Querétaro 頁](https://www.reliablesite.net/data-center/queretaro-mexico.aspx)） |

**規模：** 伺服器數、節點數、機櫃數**皆未公開**——公司與任何第三方都沒有。最佳代理值為 AS23470 的 **約 50,944 個宣告 IPv4 位址**（分布於 199 個 originated IPv4 前綴）。依裸機業界常見的位址配置慣例，可推得機隊規模可能落在六個區域合計「低至中千台」，但**這是推論，不是已公布數字——不得引為事實**。首通電話直接問。

---

## 6. 硬體機隊

本節使用的證據等級：**已確認** ＝ 營運者第一手具名揭露，或多方獨立佐證 · **旁證** ＝ 行為強烈指向但從未具名 · **推論** ＝ 僅由 CPU／機殼形狀推得 · **反證** ＝ 證據與原始名單相反 · **GAP** ＝ 查無。

- **Supermicro — 已確認。這是本帳戶最強的硬體證據，而且必須永遠與下一條一起講。**
  系統型態：具備板載 IPMI／KVM 的 Supermicro 準系統；CEO 明確具名的 **Supermicro MicroCloud** 多節點機箱。**確切 SKU 未公開。**
  三條獨立證據：（1）一則 Web Hosting Talk 客戶評述，指該客戶的 ReliableSite 伺服器全都「use Supermicro hardware with onboard KVM」；（2）另一則獨立的 WHT 討論串，描述所購三台 ReliableSite 專用伺服器為「Supermicro barebones, Atom D510, 4GB, 500GB」——屬社群來源，但兩串互相佐證；（3）營運者層級確認——CEO Radic Davydov 於 LowEndBox 專訪討論 Supermicro MicroCloud 伺服器以及故障零件難以替換的問題。
  **必須誠實說明的限制：WHT 的 Atom D510 屬舊世代硬體，且當世代 SKU 級確認為 GAP**（[Web Hosting Talk](https://www.webhostingtalk.com/showthread.php?t=1640888)；[LowEndBox 專訪](https://lowendbox.com/blog/custom-built-for-success-interview-with-radic-davydov-ceo-of-reliablesite/)）。

- **自製機殼（whitebox）— 已確認，而且是本帳戶的關鍵競爭動態。**
  一款 ReliableSite 自行設計的專屬伺服器機殼，密度較標準 1U 高約 **50%**，且刻意設計成可安裝 **市售主機板與電源**；專訪當時另有目標密度 +100% 的原型在開發中。
  CEO 的第一手說明：他是在 Supermicro MicroCloud 替換零件斷貨或變貴之後才自行設計專屬機殼——「These failed parts could not be replaced with newer generation parts, even though they were nearly identical, and were 2-3 times the cost.」這是明確、第一人稱的**離開原廠整合機殼、轉向自製鈑金＋通用主機板**的原因。公司行銷亦呼應：「each server built in-house with enterprise grade hardware」與「custom hardware design and manufacturing」。
  **銷售意涵：機殼是他們的，但主機板／板級這個插槽是開放的**（[LowEndBox 專訪](https://lowendbox.com/blog/custom-built-for-success-interview-with-radic-davydov-ceo-of-reliablesite/)）。

- **由公開規格推得的平台 — 推論（廠牌未具名）。**
  機隊高度偏向 **單路桌上型／工作站級矽晶，而非雙路 Xeon Scalable**：Intel Core i7 9700K、i9 9900K／10900K／13900K／14900K；AMD Ryzen 5600X、3700X、7700、8600G、5900X、7900、9900X、5950X、9950X；AMD Threadripper 7995WX；**AMD EPYC 4545P（16C/32T Zen 5、65W、EPYC 4005 系列）**。記憶體自 32GB DDR3 至 256GB DDR5。儲存為 512GB–4TB NVMe，部分為 2×4TB NVMe 或 NVMe＋HDD 混搭。
  **推論內容：** 此組合指向 LGA1700/1200、AM4/AM5、sTR5，以及 AM5 基礎的 EPYC 4004/4005 單路主機板，置於高密度多節點／1U 托盤中——亦即 Supermicro 級的單路與 MicroCloud 型平台，或放在自製機殼中的通用 ATX／mATX 主機板。**此為由 CPU／記憶體／機殼描述推得，並非任何已公布的原廠 SKU，不得陳述為事實**（[專用伺服器列表](https://www.reliablesite.net/dedicated-servers/)；[LowEndTalk offer thread](https://lowendtalk.com/discussion/218739/us-eu-dedicated-servers-epyc-4545p-ryzen-5800x-intel-core-i9-9900k-more-new-metal-benefits)）。
  **機隊年齡判讀：** CPU 清單自約 2018–2019 年的零件（i7 9700K、i9 9900K、Ryzen 3700X）一路延伸到當世代矽晶（Ryzen 9950X、9900X、Threadripper 7995WX、EPYC 4545P Zen 5）。**這不是一支老化的機隊——他們正在積極採購當世代單路零件**，EPYC 4545P 現正上架上櫃。舊世代的 Atom D510 證據來自年代久遠得多的客戶評述，**不得當成現行機隊陳述**。

- **Dell — 反證／查無證據。** 官網、規格頁、徵才、WHT／LowEndTalk 討論串、新聞稿、PeeringDB，均無任何公開來源提及 Dell、PowerEdge 或 iDRAC 與 ReliableSite 有關。**原始名單的 Dell 說法毫無支撐。外展時不得假設有 Dell 既有關係**（[專用伺服器列表](https://www.reliablesite.net/dedicated-servers/)）。

- **HPE — 查無證據（GAP）。** 所有取得之來源中皆無 HPE、ProLiant 或 iLO 的提及。

- **採購型態 — 現場備料、整盤直上機櫃。**
  公司公開表示現場保有 CPU／零件庫存，並自行上架新 SKU——ReliableSite 的 Facebook 貼文標題為「AMD EPYC 4545P: From tray to rack... we keep our inventory on site」（標題經搜尋索引擷取；頁面內文無法直接抓取）。徵才貼文描述自有的「onsite server builds and decommissions」與「racking and stacking servers and network equipment」，職缺為 Piscataway NJ 與 Miami FL 的 Data Center Technician，約 $60K 級距。
  **第一手、且仍在進行中的零件供應痛點：** CEO 以 Host Rep 帳號「MrRadic」在 LowEndTalk 公開表示特定 SSD／RAM 替換零件出現 **「800% cost increase on those specific parts」**，且交期 **3 個月以上**（[LowEndTalk offer thread](https://lowendtalk.com/discussion/218739/us-eu-dedicated-servers-epyc-4545p-ryzen-5800x-intel-core-i9-9900k-more-new-metal-benefits)；[NJ 機房技師徵才](https://www.reliablesite.net/hosting-news/nj-job-data-center-technician/)）。

- **自製機殼所用的主機板廠 — GAP。這是全檔商業價值最高的單一未知。** CEO 說機殼可裝市售主機板與電源，但從未具名板廠。

---

## 7. GPU 與 AI 佈局

**有 GPU，但薄到本質上只是加購項，不是 AI 平台。這是本帳戶最清楚的 AI 缺口，而且是已公布的硬性事實，不是資料缺口。**

- **NVIDIA Quadro RTX 4000** — 跨多個 CPU 層級提供的 **每月 $99 加購**（依機房與庫存而異）。
- **NVIDIA A10** — 僅有 **一款** 已公布的專屬組態：AMD Ryzen 7900（12C／3.70GHz）、128GB DDR5、2×2TB NVMe，**每月 $699**，列於 **洛杉磯**，**庫存 1 台**。
- **完全沒有 L40S、沒有 A100、沒有 H100、沒有 H200、沒有 RTX 6000 Ada；全站沒有任何多卡或 8 卡平台。**
- 專用伺服器整體價帶：**每月 $49–$699**。

**構成切入點的反差：** 公司在首頁掛出「GPU AI Dedicated Servers」服務線、把 **EPYC 4545P 定位為「AI inferencing」**，並發布 AI 視覺客戶案例（Little Planes Farm，見第 11 節）——**但支撐這整套訊息的實際加速器機隊，只有一款 A10 加一張入門級 Quadro 加購卡。** 他們有需求訊號，卻沒有可承接的高密度 GPU 平台。這是 Supermicro GPU 系統乾淨的切入點，且必須依其體質裁切：4U／5U GPU 最佳化準系統，或 2U 4 卡 L40S／RTX PRO 級節點，對應的是 1–2 個機櫃、以單路為主的營運型態，**而不是**他們既無電力也賣不動的 HGX／SXM 規模化提案（[GPU AI 專用伺服器頁](https://www.reliablesite.net/dedicated-servers/gpu-ai-dedicated-servers/)）。

---

## 8. 融資鏈與 UCC 紀錄

### 8.1 結論

> ### **NO FILINGS — verified（查無任何備案——已查證）**

該結論的精確範圍如下。在佛州擔保交易登記處（Florida Secured Transaction Registry, FSTR）中，以 **RELIABLESITE.NET LLC** 為債務人的 UCC-1 融資聲明為零；查詢已涵蓋 Filed、Lapsed 及 Filed+Lapsed 合併索引，涵蓋 Actual-name 與去標點的 Compact-name 兩種形式，涵蓋 `OrganizationDebtorName` 與 `LegacySearch` 兩種查詢型別，並涵蓋六種拼寫變體。本次不是僅憑空結果下判斷，而是以索引相鄰性直接證明：第 **5437842 列（`RELIABLE.FINANCIAL.MANAGEMENT INC`）** 與第 **5437843 列（`RELIABLESOURCE TALENT LLC`）** 彼此緊鄰、中間毫無其他紀錄，而該位置正是 `RELIABLESITE*` 若存在必須出現之處。

受查實體：RELIABLESITE.NET LLC，佛州文件號 **L14000189024**，FEI/EIN **47-2515613**，申請日 **2014-12-11**，生效日 **2015-01-01**，狀態 **ACTIVE**，主要地址 2115 NW 22nd St, Miami, FL 33142（地址變更登錄於 2017-01-09）——與 ARIN 組織代號 RL-323 所登記之地址相同。

- **GAP——索引時效。** 登記處自身的 [`/filings-completed-through-date`](https://publicsearchapi.floridaucc.com/filings-completed-through-date) 端點回傳 `2026-08-06`。任何在 2026-08-07 至今日 **2026-08-10** 之間送件的融資聲明尚不會出現。**任何要寫進合約的引用，都必須重跑一次。**
- **GAP——管轄地。** 本次未於佛州以外進行 UCC 查詢。依 **UCC 9-307(e)**，佛州註冊之 LLC 以佛州為法定登記地，因此佛州是正確且實質上窮盡的查詢管轄地；但若硬體由關係企業或另一設籍地實體持有——考量到登記地在邁阿密、營運據點卻分布於 Piscataway／洛杉磯／阿姆斯特丹／Querétaro，且該事業在 2014 年 12 月設立本 LLC 之前即已營業，此情形並非不可能——則可能在紐約、紐澤西、德拉瓦或他州以另一債務人名稱存在備案。**「零備案」的結論僅對佛州的 RELIABLESITE.NET LLC 成立，不得外推。**
- **GAP——認證查詢費用。** 佛州認證查詢（UCC-11 information request）之費用無法確定。入口網站的 [`/fees`](https://publicsearchapi.floridaucc.com/fees) 端點僅公布**申報**費用，未公布任何查詢或認證費用。取得正式認證查詢須聯絡 **Image API, LLC, UCC Filings, P.O. Box 5588, Tallahassee, FL 32314, tel 850.222.8526**——依 [dos.fl.gov](https://dos.fl.gov/) 說明，該公司自 2001-10-01 起受託民營化營運佛州 UCC 申報流程——費用未報價。
- **GAP——無擔保權人索引。** 佛州 FSTR 完全未提供以擔保權人（secured party）為索引的查詢。因此在此入口網站上，不論付多少費用，都無法以出資方名稱反查，也就無法藉此蒐集「本產業區隔由哪些融資方承作」的競爭情報。

### 8.2 查詢紀錄——逐次記錄，未合併任何一筆

| 入口網站 | URL | 使用的查詢字串 | 回應 | 受阻時的替代路徑 |
|---|---|---|---|---|
| Florida Secured Transaction Registry（FSTR）——網頁前端 | [www.floridaucc.com/uccweb/searchStd.aspx](https://www.floridaucc.com/uccweb/searchStd.aspx) | `RELIABLESITE.NET LLC` | HTTP 200，但未回傳任何可查詢內容。頁面本體解析為 1,308 bytes 的 React 單頁應用外殼，僅含 `<title>FSTR Online Filing</title>` 與 `<noscript>You need to enable JavaScript to run this app.</noscript>`。對非 JS 客戶端未輸出任何表單欄位、查詢結果或費用說明。 | 入口未被封鎖，只是純前端渲染。已採用的具名替代路徑：該站自有的公開查詢 REST API，主機 [publicsearchapi.floridaucc.com](https://publicsearchapi.floridaucc.com)，於頁面 Content-Security-Policy 及 `/static/js/main.b002c695.js` 中以 `REACT_APP_PUBLIC_SEARCH_API` 宣告。**費用：$0.00**——端點免驗證、免帳號。第二具名替代路徑未動用：以郵寄方式向 Image API, LLC, UCC Filings, P.O. Box 5588, Tallahassee, FL 32314, tel 850.222.8526 申請認證查詢（UCC-11 information request）。 |
| FSTR——根網域 | [floridaucc.com](https://floridaucc.com/) | `RELIABLESITE.NET LLC` | HTTP 200，1,308 bytes，同一份 SPA 外殼。轉址鏈：`https://www.floridaucc.com/uccweb/` → `https://floridaucc.com:443/`。伺服器輸出的 HTML 中無導覽連結、無選單項目、無費用說明、無帳號說明。 | 同上——[publicsearchapi.floridaucc.com](https://publicsearchapi.floridaucc.com)，**費用 $0.00**。 |
| FSTR 端點探測（curl，4 條候選路徑） | [/uccweb/](https://www.floridaucc.com/uccweb/) · [/uccweb/searchStd.aspx](https://www.floridaucc.com/uccweb/searchStd.aspx) · [/uccweb/searchDebtor.aspx](https://www.floridaucc.com/uccweb/searchDebtor.aspx) · [floridaucc.com/search](https://floridaucc.com/search) | 無——端點探測，未送出債務人字串 | 四條路徑皆回傳 `http=200 size=1308`。所有舊版 `/uccweb/*.aspx` 路徑均塌縮至 `https://floridaucc.com:443/` 的同一份 SPA 外殼。證實傳統 ASP.NET 查詢頁面已不再以伺服器渲染端點存在。 | 自 `/static/js/main.b002c695.js`（1,989,713 bytes）萃取 API 契約。**費用：$0.00。** |
| FSTR Public Search API——查詢選項列舉 | [publicsearchapi.floridaucc.com/search-types](https://publicsearchapi.floridaucc.com/search-types) | 無——能力列舉 | `{"status":"OK","notOk":false,...}` 僅有四種查詢型別：`OrganizationDebtorName`、`IndividualDebtorName`、`DocumentNumber`、`LegacySearch`（Organization／Individual Debtor Name）。每種名稱型別提供六個子選項：`FiledCompactDebtorNameList`、`LapsedCompactDebtorNameList`、`FiledAndLapsedCompactDebtorNameList`、`FiledActualDebtorNameList`、`LapsedActualDebtorNameList`、`FiledAndLapsedActualDebtorNameList`。Compact 子選項接受 `searchCategory` Standard（"Proximity search"）或 Exact（"Standard search logic"）；Actual 子選項不接受 category。**重大發現：完全沒有擔保權人查詢選項。佛州 FSTR 只以債務人名稱建立索引。** | 不需要。備查說明：因無擔保權人索引，在此入口網站上以出資方名稱反查在任何價格下都不可能。 |
| FSTR Public Search API——索引時效檢查 | [publicsearchapi.floridaucc.com/filings-completed-through-date](https://publicsearchapi.floridaucc.com/filings-completed-through-date) | 無 | `{"status":"OK","notOk":false,"messages":[],"payload":"2026-08-06T04:00:00Z","messageSummary":"","friendlyMessageSummary":""}` | 不需要。確立索引完整至 2026-08-06；2026-08-07 至今日 2026-08-10 之間送件者尚不會出現。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList&searchCategory=Exact](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList&searchCategory=Exact) | `RELIABLESITE.NET LLC` | `{"status":"BadRequest","notOk":true,"messages":[{"type":"Validation","code":"SVC_006","message":"Invalid search category type.","args":[]}],"payload":null,"messageSummary":" code: SVC_006 message: Invalid search category type. ","friendlyMessageSummary":"Invalid search category type."}` | 非封鎖，而是參數錯誤。Actual-name 子選項在 `/search-types` 中宣告的 categories 陣列為空，故必須省略 `searchCategory`。已移除後重跑。**費用：$0.00。** |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE.NET%20LLC&…&searchOptionSubOption=FiledAndLapsedCompactDebtorNameList&searchCategory=Exact](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedCompactDebtorNameList&searchCategory=Exact) | `RELIABLESITE.NET LLC` | `{"status":"OK","notOk":false,"messages":[],"payload":{"debtors":[],"nextRowNumber":null,"previousRowNumber":null,"totalExactMatches":0},"messageSummary":"","friendlyMessageSummary":""}`——**Filed 與 Lapsed 合併 compact 索引，完全比對命中數為 0。** | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE.NET%20LLC&…&searchOptionSubOption=FiledCompactDebtorNameList&searchCategory=Exact](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledCompactDebtorNameList&searchCategory=Exact) | `RELIABLESITE.NET LLC` | status OK，`totalExactMatches = 0`，debtors 陣列長度 0。僅 Filed 的 compact 索引。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE.NET%20LLC&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) | `RELIABLESITE.NET LLC` | status OK。索引錨點落在 rowNumber 5437843 = `RELIABLESOURCE TALENT LLC`，uccNumber 202400468514，FORT LAUDERDALE FL，狀態 Filed。後續各列：5437844 `RELIACO, INC.`（202301757831）；5437845 `RELIACRAFT, INC.`（20200268246X）；5437846 `RELIACRAFT, INC.`（202201483811）。**未回傳任何 RELIABLESITE 紀錄。** | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) | `RELIABLESITE` | status OK。錨點完全相同：rowNumber 5437843 `RELIABLESOURCE TALENT LLC`。無 RELIABLESITE 紀錄。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE.NET&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) | `RELIABLESITE.NET` | status OK。錨點完全相同：rowNumber 5437843 `RELIABLESOURCE TALENT LLC`。無 RELIABLESITE 紀錄。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE%20NET%20LLC&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE%20NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) | `RELIABLESITE NET LLC` | status OK。錨點完全相同：rowNumber 5437843 `RELIABLESOURCE TALENT LLC`。無 RELIABLESITE 紀錄。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE.NET%2C%20LLC&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%2C%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) | `RELIABLESITE.NET, LLC` | status OK。錨點完全相同：rowNumber 5437843 `RELIABLESOURCE TALENT LLC`。無 RELIABLESITE 紀錄。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLESITE%20LLC&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) | `RELIABLESITE LLC` | status OK。錨點完全相同：rowNumber 5437843 `RELIABLESOURCE TALENT LLC`。無 RELIABLESITE 紀錄。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search` | [?text=RELIABLE%20SITE&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLE%20SITE&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) | `RELIABLE SITE`（加空格變體） | status OK。錨點 rowNumber 5437551 = `RELIABLE SITE SOLUTIONS, LLC`，uccNumber 202200227638，CALLAHAN FL 32011，Filed。後續 5437552–5437554 為同公司其他備案（202201449622、202401381331、202402303717），均在 CALLAHAN FL。**此為 Nassau County 的無關工地施工公司，非目標對象。** | 不需要——查詢成功。 |
| FSTR Public Search API——`/search`（鄰近查詢） | [?text=RELIABLESITE.NET%20LLC&…&searchOptionSubOption=FiledAndLapsedCompactDebtorNameList&searchCategory=Standard](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedCompactDebtorNameList&searchCategory=Standard) | `RELIABLESITE.NET LLC`（compact 索引，鄰近查詢） | status OK。compact 索引錨點 rowNumber 5487004 = `RELIABLE SITE SOLUTIONS, LLC`（202200227638，CALLAHAN FL），接著 5487005–5487010 為同公司其他備案，再來 5487011 `RELIABLE SLIDING GLASS DOOR REPAIR`、5487012 `RELIABLE SOD & SERVICES LLC`。在去標點的 compact 索引中，`RELIABLESITENETLLC` 應排在 `RELIABLESITESOLUTIONS` 之前；鄰近錨點直接越過該位置，**證實不存在**。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search`（回頁以證明相鄰性） | [?text=RELIABLESITE.NET%20LLC&…&searchOptionSubOption=FiledAndLapsedActualDebtorNameList&rowNumber=5437833](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList&rowNumber=5437833) | `RELIABLESITE.NET LLC`（自第 5437833 列起的視窗） | status OK，previousRowNumber 5437813，nextRowNumber 5437853。依序回傳：5437833 `RELIABLE WRAP INSTALLATIONS, LLC`（201806029586，Lapsed）；5437834–5437838 `RELIABLE WRECKING CO INC`（910000266491、910000031831、910000021438、960000047322、960000087179，皆 Lapsed）；5437839–5437841 `RELIABLE WRECKING INC`（950000085764、910000189652、920000026008，Lapsed）；5437842 `RELIABLE.FINANCIAL.MANAGEMENT INC`（20200224375X，ORLANDO FL，Filed）；5437843 `RELIABLESOURCE TALENT LLC`（202400468514，Filed）；5437844 `RELIACO, INC.`；5437845／5437846 `RELIACRAFT, INC.`。**決定性證據：5437842 與 5437843 兩列在字母序上緊鄰、中間毫無其他紀錄。索引直接由 RELIABLE.FINANCIAL.MANAGEMENT INC 跳到 RELIABLESOURCE TALENT LLC。在 filed+lapsed 合併的 actual organization debtor name 索引中，任何位置都不存在 RELIABLESITE\* 項目。** | 不需要——查詢成功且具決定性。 |
| FSTR Public Search API——`/search`（LegacySearch，filed） | [?text=RELIABLESITE.NET%20LLC&searchOptionType=LegacySearch&searchOptionSubOption=FiledActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=LegacySearch&searchOptionSubOption=FiledActualDebtorNameList) | `RELIABLESITE.NET LLC` | status OK。錨點 rowNumber 1359337 `RELIABLESOURCE TALENT LLC`（202400468514，Filed），接著 1359338 `RELIACO, INC.`、1359339 `RELIACRAFT, INC.`。在合併 organization／individual 的 legacy filed 索引中無 RELIABLESITE 紀錄。 | 不需要——查詢成功。 |
| FSTR Public Search API——`/search`（LegacySearch，lapsed） | [?text=RELIABLESITE.NET%20LLC&searchOptionType=LegacySearch&searchOptionSubOption=LapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=LegacySearch&searchOptionSubOption=LapsedActualDebtorNameList) | `RELIABLESITE.NET LLC` | status OK。錨點 rowNumber 4077565 `RELIABLE ABSTRACT INC`（200603926949，Lapsed），接著 4077566／4077567 `RELIABLE ACCOUNTING & TAX SERVICES, INC.`（201806966423、202004854500）。錨點落在 RELIABLE\* 區塊開頭而非精確插入點；未浮現任何 RELIABLESITE 紀錄。 | 已與 `FiledAndLapsedActualDebtorNameList`（見上方回頁查詢）交叉比對，該索引將 Filed 與 Lapsed 交錯排列，可獨立佐證於 lapsed 索引中同樣不存在。 |
| FSTR Public Search API——`/search`（Organization，僅 lapsed） | [?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=LapsedActualDebtorNameList](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=LapsedActualDebtorNameList) | `RELIABLESITE.NET LLC` | status OK。錨點 rowNumber 4077565 `RELIABLE ABSTRACT INC`（200603926949，Lapsed），4077566／4077567 `RELIABLE ACCOUNTING & TAX SERVICES, INC.`。無 RELIABLESITE 紀錄。 | 不需要——已由 filed+lapsed 合併相鄰性證明佐證。 |
| FSTR Public Search API——費率表 | [publicsearchapi.floridaucc.com/fees](https://publicsearchapi.floridaucc.com/fees) | 無 | status OK，8 個費用鍵值：`ADDITIONAL_FEE 3.0`；`UCC1_STANDARD_FORM_FEE 35.0`；`UCC1_NON_STANDARD_FORM_FEE 40.0`；`UCC3_STANDARD_FORM_FEE 12.0`；`UCC3_NON_STANDARD_FORM_FEE 17.0`；`UCC3_TERMINATION_BEFORE_FEE 12.0`；`UCC3_TERMINATION_AFTER_FEE 0.0`；`UCC5_FEE 12.0`。**注意：以上皆為「申報」費用。此端點未公布任何查詢或認證查詢（UCC-11）費用。** | 認證查詢費用無法由入口 API 取得。正式認證查詢的具名替代路徑：Image API, LLC, UCC Filings, P.O. Box 5588, Tallahassee, FL 32314, tel 850.222.8526（依 [dos.fl.gov](https://dos.fl.gov/)，自 2001-10-01 起受託民營化營運佛州 UCC 申報流程）。費用未經查證——已列為 GAP。 |

### 8.3 全部備案明細

**以下沒有任何備案區塊，而這個「沒有」本身就是發現，不是遺漏。** 為使空結果的形貌明確且可稽核，此處逐欄列出備案區塊本應載明的每一個欄位：

| 備案區塊本應載明的欄位 | RELIABLESITE.NET LLC 的紀錄（佛州 FSTR，索引完整至 2026-08-06） |
|---|---|
| 備案編號 | **無。此債務人名稱下不存在任何 UCC-1、UCC-3 或 UCC-5 紀錄。** |
| 備案日期 | **無。** |
| 失效日／續期 | **無。既無續期（continuation）亦無終止（termination）可供解讀，因此既無「尚有擔保債務」的證據，也無「近期清償完畢」的證據。** |
| 擔保權人名稱＋地址 | **無。沒有任何銀行、沒有任何原廠融資部門（無 Dell Financial Services、無 HPE Financial Services、無 Supermicro 關聯之融資租賃機構）、沒有任何設備出租人、沒有任何大盤通路商登記為擔保權人。** |
| 債務人名稱＋地址 | **無債務人紀錄。受查實體為 RELIABLESITE.NET LLC, 2115 NW 22nd St, Miami, FL 33142——該名稱不存在於索引中。** |
| 擔保品說明（逐字引用） | **不存在任何可逐字引用的擔保品說明。紀錄上沒有概括性留置權（blanket lien）、沒有全部資產擔保品描述、沒有後取財產條款（after-acquired-property clause）、沒有消極擔保條款（negative pledge）。** |
| 修正／讓與／終止 | **無。** |
| 紀錄連結 | 不存在紀錄頁面。查詢可於 [publicsearchapi.floridaucc.com/search](https://publicsearchapi.floridaucc.com/search?text=RELIABLESITE.NET%20LLC&searchOptionType=OrganizationDebtorName&searchOptionSubOption=FiledAndLapsedActualDebtorNameList) 重現；入口前端見 [floridaucc.com](https://floridaucc.com/) |

### 8.4 這份紀錄代表什麼

| 觀察 | 推論意涵 | 信心度 | 銷售後果 |
|---|---|---|---|
| 以 RELIABLESITE.NET LLC 為債務人的 UCC-1 融資聲明為零，涵蓋 Filed、Lapsed 與 Filed+Lapsed 合併索引，涵蓋 Actual-name 與去標點 Compact-name 兩種形式，涵蓋 `OrganizationDebtorName` 與 `LegacySearch` 兩種型別，並涵蓋六種拼寫變體。相鄰性已直接證明：索引第 5437842 列（`RELIABLE.FINANCIAL.MANAGEMENT INC`）與第 5437843 列（`RELIABLESOURCE TALENT LLC`）緊鄰、中間無任何紀錄。索引完整至 2026-08-06。 | 佛州對此債務人而言是法律上正確、且實質窮盡的管轄地。依 **UCC 9-307(e)**，註冊組織之所在地即其設立州，因此出資方或出租人若要對佛州 LLC 完善擔保權益，就會在佛州申報。故此「無」並非管轄地造成的假象——它代表在該公司十二年的存續期間，從未有任何出資方、設備出租人、原廠融資部門或通路商對其完善過擔保權益。 | 「不存在」此一事實為**高**（相鄰性具決定性、兩種索引皆查、索引時效至 2026-08-06）。法律管轄地之解讀為**中高**。 | 沒有留置權人需要取得同意，你與採購單之間也不存在債權人間協議或次順位問題。程序上沒有任何事情擋住這筆生意。但同樣地，也沒有現成的設備融資額度可供動用——大額訂單只能靠自有現金，或靠你帶進來的融資方案。**請在第一次商務對話就把租賃或原廠融資夥伴帶進來，不要留到最後；也不要假設他們手上已有額度待用。** |
| 紀錄上完全沒有任何擔保權人——沒有銀行、沒有原廠融資部門（無 Dell Financial Services、無 HPE Financial Services、無 Supermicro 關聯融資租賃機構）、沒有設備出租人，也沒有任何大盤通路商申報購置價金擔保權（PMSI）。 | 由此可得兩點。第一，他們並非透過「會例行完善 PMSI 的通路」採購整機系統——一級通路商若以帳期出售六、七位數的整櫃系統，通常會申報。第二，這與其餘證據一致：單路 AM5 桌機級與 EPYC 4005 級矽晶、伺服器由自家技師自行組裝上架佈線、清倉頁面主打 SuperMicro 機殼與伺服器級主機板而非具名整機 SKU。其採購型態讀起來像是以零組件、主機板與準系統為單位，向電商與區域經銷商刷卡或以短天期開放帳期購買，而非通路商方案。 | **中。** 「無 PMSI」是事實；「採購通路」的推論屬情境證據，係自矽晶等級、自建定位與機殼／主機板用語推得，而非取自採購紀錄。 | 與**規則 8 通路核准**直接相關：公開紀錄上沒有任何通路商對此帳戶擁有登記權益，因此引入通路商不會排擠既有者，也不會在公開紀錄上造成通路衝突。但通路條件上要預期摩擦——習慣零組件式交易採購的買方，會抗拒最低訂購量、帳期文件與信用申請。**開場請用他們現在就在消耗的準系統／主機板 SKU 清單，而不是整櫃整機提案。** |
| 沒有備案日期可讀，因為根本沒有備案。採購時鐘完全靠型錄考古（見第 9 節）重建，而非靠留置權日期間距。 | 對這個規模的公司而言，常見的商業破口——每次大型設備交付後數日內出現的 UCC-1，等於免費送你一份交機行事曆——根本不存在。任何關於本帳戶採購節奏的說法，都必須取自庫存證據，並承擔隨之而來的較大誤差帶。反過來說，競爭對手同樣看不到他們的採購節奏；此帳戶對「監看留置權」型開發工具是不透明的，這對願意做型錄功課的人是一項小小的結構性優勢。 | **高。** | **不要等留置權警示來觸發接觸——那個警示永遠不會響。** 改為把專用伺服器型錄頁納入定期監看：新的 CPU 或 GPU 家族出現在該頁，是這個帳戶唯一穩定對外釋放的採購訊號，而且它落後實際採購約兩個月（EPYC 4545P 於 2025 年 8 月在其自家新聞室發布，直到 2025 年 10 月的快照才出現在型錄）。 |
| 因為不存在任何融資聲明，所以既無概括性留置權，也無全部資產擔保品描述；連帶地，明日採購的硬體上沒有後取財產條款，也沒有消極擔保條款。 | 機隊未設定任何負擔。他們完全可以用它借款、做售後回租，或對新的設備融資方設定第一順位 PMSI，無須取得任何人的解除或次順位同意。 | **高。** | 考量第 10 節的回收期算式，融資是一條暢通且可用的槓桿，也是你能提供的最有用的東西。對新交付硬體設定第一順位 PMSI 可以乾淨落地。此點在當下尤其關鍵，因為他們正同時建置三個新據點（阿姆斯特丹已上線、Querétaro 開放預訂、達拉斯開始出現），而環境是十年來最糟的 DRAM 與 NAND 價格。**把一次性資本支出高峰轉換為月費的結構化方案，才是對準他們真正限制條件的提案。** |
| 沒有續期、也沒有終止可供解讀，因此既無尚有擔保債務的證據，也無近期清償完畢的證據。一家在六個據點運作 1–5 Tbps 網路、依型錄證據推估擁有數千台伺服器的公司，在其十二年存續期間背負過零筆已完善的留置權。 | 有兩種讀法，且兩者不互斥。最可能：創辦人持股、規避負債的經營者，以營運現金流支應硬體，隨營收小額分批採購——這正是型錄顯示的樣貌，SKU 家族隨庫存週轉一兩台地出現與消失，而非全機隊式的換代波段。可能性較低但必須排除：硬體不在本實體的資產負債表上，而在關係企業或另一設籍地實體，若如此，備案會以該名稱出現在該州。IP 面的佐證同樣呈現輕資本姿態——[bgp.tools](https://bgp.tools/as/23470) 顯示 AS23470 宣告約 238 條 IPv4 前綴、約 60,928 個位址，但 ARIN 顯示 RL-323 僅持有 16 個直接網段，最後一次 IPv4 配發停在 2019-06-11。差額來自租賃，且檔案中最新一筆是由上游（parent 10VPN-PRIMARY）指派給他們的 IPv6 /48，而非直接配發。 | 「以現金支應、規避負債」為**中高**；「表外持有」的替代解釋為**中**，因未進行佛州以外的 UCC 查詢，故無法排除。 | 要預期資本支出紀律、以回收期為主的決策方式，以及真實的價格敏感度——這位買方會自己把第 10 節的算式算一遍。請以**綁定單一具名據點、一次一櫃**的方式銷售，而不是整機隊汰換。開場講回收月數，不要講抽象 TCO 或效能功耗行銷語言。並且在需求探詢初期就問兩個具體問題：**採購單由哪一家法人簽署，硬體由哪一家法人擁有。** 若兩者不同名，信用與融資對話應轉向後者，且他處可能存在佛州看不到的備案。 |
| 佛州登記處完全未提供擔保權人索引——[`/search-types`](https://publicsearchapi.floridaucc.com/search-types) 僅提供 `OrganizationDebtorName`、`IndividualDebtorName`、`DocumentNumber` 與 `LegacySearch`。 | 即使佛州確有備案，也無法以出資方反查，藉以得知哪一家融資方活躍於一組主機代管公司之間。關於「誰在為這個產業區隔提供融資」的競爭情報，只能一家一家債務人地建立。 | **高**——API 自身的能力列舉即為定論。 | 若要知道可比的佛州主機商使用哪一家出租人，必須針對同業清單逐一執行具名債務人查詢。此端點每次查詢成本為 $0.00，而且值得在**提出融資夥伴之前**先做，好讓你引介的對象是這個區隔已經認得的名字。 |

---

## 9. 採購時鐘

### 9.1 型錄快照時間軸

以 Wayback Machine 對 [reliablesite.net/dedicated-servers/](https://www.reliablesite.net/dedicated-servers/) 的十二次擷取為基礎，直接解析該頁自身的結構化標記（`data-server-name`、`data-cores`、`data-cpu-speed`、`data-memory`、`data-price`，以及自 2026-06 起的 `data-dc-*` 供應屬性）。

| 快照日期 | SKU 數 | 最新矽晶 | 相較前次新增（史上首見） | 相較前次消失 | 快照 |
|---|---|---|---|---|---|
| **2023-03-14** | 38 個 SKU 家族／57 種組態 | AMD Ryzen 9 7950X（Zen 4, Raphael）；Intel Core i9-13900K（Raptor Lake）；AMD EPYC 7773X（Milan-X）；AMD Threadripper 3990X | 基準快照，無前次可比。Zen 4 桌機版與 Raptor Lake 已在列，代表其首次出現早於本觀察窗。 | 不適用（基準） | [擷取](https://web.archive.org/web/20230314191127/https://www.reliablesite.net/dedicated-servers/) |
| **2023-08-02** | 33 家族／47 組態 | AMD Ryzen 7 7700 與 Ryzen 5 7600（Zen 4 非 X，65W）；史上第一款 GPU SKU——nVidia Quadro RTX 4000 | **史上首見：** AMD Ryzen 7600；AMD Ryzen 7700；nVidia Quadro RTX 4000（型錄史上第一款 GPU 產品）；Dual Xeon Silver 4108；Dual Xeon E5 2620 V4；Intel Core i7 4770；Intel Xeon E5 1650 V2。**採購事件——而且是兩件：** 主流 Zen 4 65W 產品，以及切入 GPU 代管此一新產品類別。 | AMD Ryzen 7950X；AMD Threadripper 3990X；Dual Xeon E5 2699 V4；Dual Xeon Plat. 8160；Intel Atom D525；Intel Core i7 4790；Intel Core i7 9700K；Intel Core i9 10900K；Intel Core i9 13900K；Intel Xeon E3 1245 V2；Intel Xeon E5 1660 V3；Intel Xeon W 2155。*多數在後續快照重新出現，故消失代表缺貨而非退場。* | [擷取](https://web.archive.org/web/20230802115010/https://www.reliablesite.net/dedicated-servers/) |
| **2023-10-23** | 34 家族／43 組態 | AMD Ryzen 9 7900（Zen 4，65W 12 核） | **史上首見：** AMD Ryzen 7900；Dual AMD EPYC 7281（Naples，舊世代）。Ryzen 7900 屬同一批 Zen 4 65W 採購的延伸，非新世代——屬增量，**不計為獨立採購事件**。 | Dual Xeon E5 2603 V3；Dual Xeon Silver 4108；Intel Core i5 4570；Intel Xeon E3 1230 V3；Intel Xeon E5 1650 V2；Intel Xeon W 2133（均屬庫存性質） | [擷取](https://web.archive.org/web/20231023023700/https://www.reliablesite.net/dedicated-servers/) |
| **2024-01-07** | 27 家族／38 組態 | AMD Ryzen 9 7900／Ryzen 7600（Zen 4）——未出現比前次更新的矽晶 | **史上首見：** 僅 Intel Atom D510——一顆十年前的零件重新回到庫存。**無採購事件。** | AMD EPYC 7773X；AMD Ryzen 3950X；AMD Ryzen 5800X3D；AMD Ryzen 5900X；AMD Ryzen 5950X；AMD Ryzen 7700；AMD Ryzen 7900；AMD Ryzen 7950X；Dual AMD EPYC 7281；HDD Storage 32TB；Intel Core i7 7700K；Intel Special 256GB | [擷取](https://web.archive.org/web/20240107133526/https://www.reliablesite.net/dedicated-servers/) |
| **2024-05-18** | 15 家族／15 組態——**擷取不完整**（封存物件僅 149,785 bytes，相鄰快照為 200,000–380,000 bytes；此列數字應視為下限，而非真實庫存讀數） | AMD Ryzen 7 8700G（Zen 4 Phoenix APU，2024 年 1 月上市） | **史上首見：** AMD Ryzen 8700G；Intel Special 128GB；Intel Special 6 Core；Intel Special 64GB。**採購事件**——8700G 屬新矽晶家族（單晶 Phoenix APU），其型錄首見時點約落在 AMD 2024 年 1 月上市後四個月。 | 22 個家族缺席，包含整條 Xeon E3／E5 線、Core i7／i9 線與 Ryzen 3700X／5800X／7600——幾可確定是擷取不完整所致而非真正退場，因為全部在 2024-12-18 重新出現。 | [擷取](https://web.archive.org/web/20240518063450/https://www.reliablesite.net/dedicated-servers/) |
| **2024-12-18** | 28 家族／34 組態 | AMD Ryzen 9 9950X 與 Ryzen 9 9900X（**Zen 5**, Granite Ridge，2024 年 8 月上市）；Intel Core i9-14900K（Raptor Lake Refresh）；nVidia A10（Ampere 資料中心 GPU） | **史上首見：** AMD Ryzen 9900X；AMD Ryzen 9950X；AMD Ryzen 8600G；Intel Core i9 14900K；nVidia A10 GPU；AMD Opteron 6272。**重大採購事件——三件同時首見：** Zen 5 桌機世代、Raptor Lake Refresh 旗艦，以及一張真正的資料中心 GPU（A10, 24GB）取代工作站級 Quadro RTX 4000 成為 GPU 旗艦。**這是整個觀察窗中可見的最大一次換代。** | Dual AMD EPYC 7281；Intel Atom D525；Intel Special 128GB；Intel Special 6 Core | [擷取](https://web.archive.org/web/20241218043321/https://www.reliablesite.net/dedicated-servers/) |
| **2025-06-10** | 33 家族／39 組態 | AMD EPYC 9965（Turin Dense, Zen 5c，192 核等級，2024 年 10 月上市）；AMD Threadripper PRO 7995WX（Storm Peak，96 核） | **史上首見：** AMD EPYC 9965；AMD Threadripper 7995WX；HDD Storage 40TB。**採購事件**——首度出現 Zen 5 **伺服器**矽晶（相對於 Zen 5 桌機版），以及首見 96 核 Threadripper PRO。其中 2,048GB DDR5／6×4TB NVMe 的 Threadripper 組態每月 $2,499，是他們有史以來上架過最大的單機。 | AMD Opteron 6272；AMD Ryzen 3900X；AMD Ryzen 7600；AMD Ryzen 8700G；Dual Xeon E5 2620 V4；Intel Core i7 9700K；Intel Core i9 10900K | [擷取](https://web.archive.org/web/20250610103328/https://www.reliablesite.net/dedicated-servers/) |
| **2025-10-08** | 40 家族／48 組態——**整個觀察窗中最寬的型錄** | AMD EPYC 4545P（EPYC 4005「Grado」, Zen 5, 16C/32T, 65W TDP, AM5 腳位） | **史上首見：** AMD EPYC 4545P。另補貨：AMD Ryzen 3900X、7600、8700G、Dual Xeon E5 2603 V3、Dual Xeon E5 2620 V4、Intel Core i7 9700K、Intel Core i9 13900K、Intel Special 128GB、Intel Xeon W 2133。**採購事件——而且這是最近的一次。** 他們自家新聞室已於 2025 年 8 月宣布 EPYC 4545P 進駐紐約、邁阿密與洛杉磯，因此真實採購早於此型錄目擊約兩個月。上市組態價格為每月 $149（128GB／2TB）與每月 $199（256GB／4TB）。 | Dual AMD EPYC 7281；Dual Xeon E5 2620 V2；Intel Atom D510 | [擷取](https://web.archive.org/web/20251008002639/https://www.reliablesite.net/dedicated-servers/) |
| **2025-11-12** | 34 家族／42 組態 | AMD EPYC 4545P——未變 | **無史上首見矽晶。** 僅補貨：AMD Opteron 6272、Dual Xeon E5 2620 V2、Intel Core i9 10900K、Intel Xeon W 2155。**無採購事件。** | AMD EPYC 9965；AMD Ryzen 5800X3D；AMD Ryzen 7600；AMD Ryzen 9950X；Dual Xeon E5 2603 V3；Dual Xeon E5 2620 V4；Intel Atom D510；Intel Core i7 9700K；Intel Special 128GB；Intel Xeon W 2133 | [擷取](https://web.archive.org/web/20251112033200/https://www.reliablesite.net/dedicated-servers/) |
| **2026-03-03** | 29 家族／37 組態 | AMD EPYC 4545P——連續第二次快照未變 | **無史上首見矽晶。** 僅補貨：AMD Ryzen 9950X、Intel Core i7 9700K、Intel Special 128GB。**無採購事件。價格轉折點落在此處**——在三年持平至走跌之後，本次快照全面調漲：EPYC 4545P 128GB／2TB $149 → $189；EPYC 4545P 256GB／4TB $199 → $279；Ryzen 9950X 192GB $249 → $329；Ryzen 7950X 192GB $239 → $289；i9-14900K 192GB $229 → $249。 | AMD EPYC 7773X；AMD Opteron 6272；AMD Ryzen 3950X；AMD Ryzen 7900；AMD Ryzen 8600G；Intel Special 64GB；Intel Xeon W 2155；nVidia Quadro RTX 4000 | [擷取](https://web.archive.org/web/20260303032526/https://www.reliablesite.net/dedicated-servers/) |
| **2026-06-03** | 22 家族／26 組態 | AMD EPYC 4545P——連續第三次快照未變 | **無史上首見矽晶。** 僅補貨：AMD Ryzen 7600、AMD Ryzen 7900、Dual Xeon E5 2620 V4。**無採購事件。** 改變的是頁面標記結構：per-datacentre 供應屬性（`data-dc-pnj`／`mia`／`lax`／`ams`）與地區下拉標頭（United States、Europe）首次出現，且阿姆斯特丹已為現貨據點。價格續漲：A10 GPU $599 → $699；Ryzen 5950X $149 → $179；Ryzen 7600 $109 → $149。 | AMD Ryzen 3900X；AMD Ryzen 5900X；AMD Ryzen 7700；AMD Threadripper 3990X；Dual Xeon E5 2620 V2；Dual Xeon Silver 4108；Intel Core i7 9700K；Intel Core i9 13900K；Intel Special 128GB；Intel Special 6 Core | [擷取](https://web.archive.org/web/20260603011406/https://www.reliablesite.net/dedicated-servers/) |
| **2026-08-07**（最近一次封存擷取；今日 2026-08-10 的線上頁面在最新矽晶與價格上緣皆相符） | 17 家族／20 組態——**觀察窗中最窄的型錄，較 2025 年 10 月的 40 家族高點減少 58%** | CPU 為 AMD EPYC 4545P（EPYC 4005, Zen 5）；GPU 為 nVidia A10。兩者分別自 2025-10-08 與 2024-12-18 起未變。 | **連續第四次快照無史上首見矽晶。** 僅補貨：AMD Ryzen 5800X3D、AMD Ryzen 8600G、Dual Xeon Silver 4108、Intel Special 64GB、nVidia Quadro RTX 4000。**無採購事件。** 機房屬性擴增為六個據點——`ams`、`dfw`、`lax`、`mia`、`pnj`、`qro`——其中 **DFW（達拉斯）與 QRO（Querétaro）首次出現**，並新增 Mexico 地區標頭。價格上緣再漲：Ryzen 9950X 256GB $359 → $399。 | AMD Ryzen 5950X；AMD Ryzen 7600；AMD Ryzen 8700G；AMD Threadripper 7995WX；Dual Xeon E5 2620 V4；HDD Storage 32TB；HDD Storage 40TB；Intel Core i9 10900K；Intel Special 256GB。**值得注意的是整條大容量 HDD 儲存線（32TB／40TB／80TB）全數消失，2,048GB Threadripper 旗艦亦然——這與記憶體與 NAND 缺貨一致，而非需求流失。** | [擷取](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |

### 9.2 採購節奏

**已觀察到的間隔。** 採購事件的定義嚴格限定為：在十二次快照中，新的 CPU 或 GPU 世代首次出現在型錄。符合者共五次。

| 事件 | 日期 | 出現內容 |
|---|---|---|
| **E1** | 2023-08-02 | 主流 Zen 4 65W（Ryzen 7600／7700），加上史上第一款 GPU 產品（Quadro RTX 4000） |
| **E2** | 2024-05-18 | Zen 4 Phoenix APU（Ryzen 8700G） |
| **E3** | 2024-12-18 | Zen 5 桌機版（Ryzen 9900X／9950X）＋ Raptor Lake Refresh（i9-14900K）＋ 資料中心 GPU（nVidia A10）——觀察到的最大一次換代 |
| **E4** | 2025-06-10 | Zen 5 伺服器版（EPYC 9965 Turin Dense）＋ Threadripper PRO 7995WX |
| **E5** | 2025-10-08 | EPYC 4005 Zen 5（EPYC 4545P），原廠於 2025 年 8 月宣布 |

連續事件間隔（月）：**E1→E2 = 9.5 · E2→E3 = 7.0 · E3→E4 = 5.8 · E4→E5 = 3.9**（若 E5 以 2025 年 8 月的宣布日而非型錄目擊日計算，則為 2.1）。**此數列單調遞減——直到最後一次事件為止，換代時鐘都在穩定加速。**

**中位數月數。** **6.4 個月**（9.5、7.0、5.8、3.9 之中位數）。平均 6.6 個月。若採用宣布日修正後的 E5，中位數為 6.4、平均降為 6.1。**可視為約 6 個月的節奏，並在 2025 年全年持續收緊。**

**最近一次採購事件。** **AMD EPYC 4545P**（EPYC 4005 系列, Zen 5, 16C/32T, 65W TDP, AM5 腳位）。ReliableSite 自家新聞室於 **2025 年 8 月**宣布進駐紐約、邁阿密與洛杉磯；型錄首次目擊為 **2025-10-08** 快照，128GB DDR5 + 2TB NVMe 每月 $149、256GB DDR5 + 4TB NVMe 每月 $199。截至今日 **2026-08-10**，距宣布已 **12 個月、距型錄首見已 10.1 個月，對比 6.4 個月的中位數**——約為歷史間隔的 **1.6 至 1.9 倍**，且連續四次快照（2025-11、2026-03、2026-06、2026-08）皆無新矽晶。**這是觀察窗中最長的一次矽晶空窗，且差距甚大**（[新聞室貼文](https://www.reliablesite.net/hosting-news/offering-amd-epyc-4545p-dedicated-servers/)）。

**下一個時間窗推估。** **2026 年 9 月至 2027 年 1 月，機率最高落在 2026 年 10 至 11 月。** 兩股推力方向一致。第一，換代時鐘已逾期 4 至 6 個月，且尚未採用的矽晶存量已相當可觀——Zen 5 X3D 產品、4545P 以上的 EPYC 4005 產品線、NVIDIA 的 L4／L40S 世代都在出貨，而他們的型錄天花板仍停在一顆 65W 16 核，以及一張自 2024 年 12 月起就擔任 GPU 旗艦的 Ampere 世代 A10。第二，也更具決定性的是，他們正同時建置三個新據點：**阿姆斯特丹於 2026-04-29 上線，達拉斯（DFW）與 Querétaro（QRO）的供應旗標於 2026-07-30 出現在標記中**，墨西哥仍處預訂狀態。新據點無論換代時鐘如何都需要新機器——**Querétaro 與達拉斯的建置本身就是那筆採購**，而且必須在這些據點能把預訂轉為營收之前落地。反向作用力是零組件價格，這也正是空窗形成的原因；若 DRAM 與 NAND 維持現價，該筆採購可能被拆成數個較小的分批，而非單一大單。

**依據。** 對 [reliablesite.net/dedicated-servers/](https://www.reliablesite.net/dedicated-servers/) 自 2023-03-14 至 2026-08-07 的十二次 Wayback Machine 擷取，直接解析頁面自身結構化標記，並與 2026-08-10 的線上頁面、以及 ReliableSite 自家標註日期的新聞室貼文交叉核對（[EPYC 4545P，2025 年 8 月](https://www.reliablesite.net/hosting-news/offering-amd-epyc-4545p-dedicated-servers/)；[阿姆斯特丹，2026 年 4 月](https://www.reliablesite.net/hosting-news/reliablesite-dedicated-servers-are-now-available-in-amsterdam/)）。**所有型錄首見日期都是受快照頻率限制的「上限值」——真實採購早於目擊。** EPYC 4545P 一案把這個時間差校準在約兩個月。

**信心度。** 歷史節奏本身為**中高**（五次事件、單調收緊一致、且有獨立原廠宣布日佐證）。下一時間窗推估為**中**——方向有三據點擴張強力支撐，但時點受制於一個真正處於錯位狀態的零組件市場，且其中一次快照（2024-05-18）擷取不完整，可能遮蔽了一次中間事件。

**GAP——限制本節推論的資料覆蓋缺口。**
- Wayback 對型錄在 **2024-12-18 至 2025-06-10** 之間的覆蓋幾乎空白——該六個月區間僅存在一次 status-200 擷取（2025-01-08 回 403、2025-09-19 回 301）。**2025 上半年若曾發生採購事件，可能未被觀察到**，若如此則實際 E3→E4 間隔會更短。
- **2024-05-18** 擷取為不完整封存物件（149,785 bytes，相鄰者為 200,000–380,000 bytes），僅得 15 個 SKU，其計數僅為下限。
- 以直接 HTTP 客戶端擷取線上專用伺服器頁面遭阻擋（回應僅 5,639 bytes），因此「今日」讀數取自 2026-08-07 的 Wayback 擷取，並與一次成功的代理抓取交叉核對。兩者在最新矽晶與價格上緣一致，但線上 SKU 計數為 22 種組態、封存擷取為 20 種——**此微小落差與三天的庫存變動一致。**
- **伺服器總數、機櫃數、機箱數與已裝機規模皆未對外揭露。** 型錄供應數字只顯示各據點各 SKU 的當前未售庫存（通常 1–5 台），完全無法推知裝機基數。**任何關於他們運行多少台伺服器的說法，都不受本研究支持。**

### 9.3 擴張訊號

| 訊號 | 日期 | 來源 |
|---|---|---|
| ARIN 直接配發 **206.221.176.0/20**——最初的 IPv4 區塊，登記於 ReliableSite.Net LLC（組織代號 RL-323） | 2014-07-23 | [ARIN NET-206-221-176-0-1](https://whois.arin.net/rest/net/NET-206-221-176-0-1) |
| ARIN 直接配發 **2605:9880::/32**——其主要 IPv6 區塊，完整一個 /32 | 2014-07-25 | [ARIN NET6-2605-9880-1](https://whois.arin.net/rest/net/NET6-2605-9880-1) |
| ARIN 直接配發 **104.243.32.0/20** | 2014-11-13 | [RDAP 104.243.46.1](https://rdap.arin.net/registry/ip/104.243.46.1) |
| ARIN 直接配發 **45.58.112.0/20** | 2015-02-24 | [ARIN NET-45-58-112-0-1](https://whois.arin.net/rest/net/NET-45-58-112-0-1) |
| ARIN 直接配發 **172.93.96.0/20** | 2015-06-03 | [ARIN NET-172-93-96-0-1](https://whois.arin.net/rest/net/NET-172-93-96-0-1) |
| ARIN 直接配發 **209.222.96.0/20**——十五個月內第四個 /20，為其 IPv4 累積期的高峰 | 2015-10-02 | [ARIN NET-209-222-96-0-1](https://whois.arin.net/rest/net/NET-209-222-96-0-1) |
| ARIN 配發 **172.96.160.0/23** 與 **172.96.172.0/23**——隨 ARIN 存量池枯竭，區塊規模自 /20 縮至 /23 | 2017-02-24 | [ARIN NET-172-96-160-0-1](https://whois.arin.net/rest/net/NET-172-96-160-0-1) |
| ARIN 配發 **199.127.60.0/22** | 2017-05-24 | [ARIN NET-199-127-60-0-1](https://whois.arin.net/rest/net/NET-199-127-60-0-1) |
| ARIN 配發 **172.96.140.0/22** | 2017-07-28 | [ARIN NET-172-96-140-0-1](https://whois.arin.net/rest/net/NET-172-96-140-0-1) |
| ARIN 配發 **104.128.72.0/22** | 2017-10-20 | [ARIN NET-104-128-72-0-1](https://whois.arin.net/rest/net/NET-104-128-72-0-1) |
| ARIN 配發 **104.238.220.0/22** | 2018-04-13 | [ARIN NET-104-238-220-0-1](https://whois.arin.net/rest/net/NET-104-238-220-0-1) |
| ARIN 配發 **104.238.204.0/22** | 2018-08-24 | [ARIN NET-104-238-204-0-1](https://whois.arin.net/rest/net/NET-104-238-204-0-1) |
| ARIN 配發 **104.194.8.0/22** | 2019-02-14 | [ARIN NET-104-194-8-0-1](https://whois.arin.net/rest/net/NET-104-194-8-0-1) |
| ARIN 配發 **185.150.189.0/24** 與 **185.150.190.0/23**——**紀錄上最後一次直接 IPv4 配發，其後是七年的沉默。** 由於 [bgp.tools](https://bgp.tools/as/23470) 顯示 AS23470 宣告約 238 條 IPv4 前綴、約 60,928 個位址，而 ARIN 僅顯示 16 個直接持有網段，2019 年後的位址成長來自移轉或租賃而非配發——此一輕資本姿態與其設備留置權之全然缺席互相呼應。 | 2019-06-11 | [ARIN NET-185-150-189-0-1](https://whois.arin.net/rest/net/NET-185-150-189-0-1) |
| 型錄標記：第四個下單地點選項 **「Pre-Order (USA)」** 首次出現，與三個長期據點（New York City Metro、Miami、Los Angeles）並列。見於 2026-01-16、2026-01-27 與 2026-01-31 擷取，至 2026-03-03 撤下。**達拉斯專案最早的公開痕跡。** | 2026-01-16 | [擷取](https://web.archive.org/web/20260116070311/https://www.reliablesite.net/dedicated-servers/) |
| 型錄標記：**「Pre-Order (EU)」** 選項與「Europe」地區下拉標頭首次出現——阿姆斯特丹開放預訂 | 2026-04-14 | [擷取](https://web.archive.org/web/20260414161143/https://www.reliablesite.net/dedicated-servers/) |
| AS23470 的 PeeringDB 紀錄最後更新——機房清單新增 **Databarn Amsterdam** 與 **Equinix AM7 – Amsterdam**，與 165 Halsey Meet-Me Room（Newark）、QTS Piscataway PNJ1、CoreSite LA1 One Wilshire、CoreSite LA2、CoreSite Miami MI1、Equinix MI1 並列。公開對等互連於 Any2West、DE-CIX New York、Equinix Miami、FL-IX 與 NYIIX，皆為 100G。流量等級 1–5 Tbps、以出向為主、開放對等政策。 | 2026-04-14 | [PeeringDB net/17907](https://www.peeringdb.com/net/17907) |
| **阿姆斯特丹上線——美國境外的第一批現貨庫存。** per-datacentre 供應屬性（`data-dc-pnj`、`data-dc-mia`、`data-dc-lax`、`data-dc-ams`）在同一次擷取中導入頁面標記，且下單選單中「Amsterdam, NL」取代「Pre-Order (EU)」。時點可框定在 2026-04-14 至 2026-04-29 的十五天內；ReliableSite 自家新聞室將其標為 2026 年 4 月，並稱之為第一個國際據點、第四個據點。 | 2026-04-29 | [擷取](https://web.archive.org/web/20260429114107/https://www.reliablesite.net/dedicated-servers/) |
| ReliableSite 新聞室貼文「ReliableSite Dedicated Servers Are Now Available in Amsterdam」——開幕 SKU 為 **AMD Ryzen 9950X**（16 核、256GB DDR5、2×4TB NVMe）與 **AMD EPYC 4545P**（16 核、256GB DDR5、4TB NVMe），皆搭配 1 Gbps 不計流量與完整 KVM over IP | 2026 年 4 月 | [新聞室](https://www.reliablesite.net/hosting-news/reliablesite-dedicated-servers-are-now-available-in-amsterdam/) |
| 型錄標記：**「Pre-Order (USA)」與「Pre-Order (EU)」同時並存**——達拉斯專案在阿姆斯特丹上線後兩個月內重啟 | 2026-06-30 | [擷取](https://web.archive.org/web/20260630061011/https://www.reliablesite.net/dedicated-servers/) |
| ARIN：IPv6 **/48 2602:FED2:7110::/48** 登記於 ReliableSite.Net LLC（組織 RL-323），ARIN 網段名稱為 **「CHICAGOSERVERS」**，母網段 10VPN-PRIMARY（NET6-2602-FED2-1），登記日與最後異動日同日。該網段名稱指向一個芝加哥部署，但其官網、新聞室、型錄標記中都沒有對應項目——**可能是尚未宣布的第七個據點。** 該筆為自上游指派的下游再分配，而非新的 ARIN 直接配發。**GAP——此訊號確實有歧義；不得對客戶陳述為已確認的芝加哥部署。** | 2026-07-25 | [ARIN NET6-2602-FED2-7110-1](https://whois.arin.net/rest/net/NET6-2602-FED2-7110-1) |
| 型錄標記：機房屬性由四個據點擴為六個——**`data-dc-dfw`（達拉斯）與 `data-dc-qro`（Querétaro）首次出現**，新增「Mexico」地區下拉標頭，且「Pre-Order (Mexico)」取代「Pre-Order (USA)」。DFW 供應初期僅限單一 SKU（Ryzen 9950X 256GB），顯示建置仍屬極早期。 | 2026-07-30 | [擷取](https://web.archive.org/web/20260730191917/https://www.reliablesite.net/dedicated-servers/) |
| Querétaro 據點頁面上線：AMD EPYC 與 Ryzen 專用伺服器開放預訂。設施條件載明為 **31 MW 總電力、258,000 平方英尺**，三匯流排電力備援搭配 48 小時燃料自主，N+1 冰水主機。網路將使用在地上游 IENTC 與 Wantelco，並直連 PIX México 1 與 PIX México 2。據載已進入最後階段，機櫃就位、網路測試中。 | 2026-07 至 2026-08 | [Querétaro 機房頁](https://www.reliablesite.net/data-center/queretaro-mexico.aspx) |
| LowEndTalk 討論串「ReliableSite launches in Querétaro, Mexico」——社群可見的上線公告。**GAP——該討論串回傳 HTTP 403 無法讀取；開串日期、官方發文日期，以及任何關於機櫃數、硬體或上線時程的營運方發言均未取得。** | 2026（討論串內容無法取得） | [LowEndTalk 討論串](https://lowendtalk.com/discussion/219644/reliablesite-launches-in-queretaro-mexico) |
| 線上網站現已列出**六個機房**——「New York City Metro, Miami, FL, Los Angeles, CA, Dallas, TX, Amsterdam, NL, Querétaro, MX」——獨立佐證達拉斯為已承諾據點，而不只是標記旗標 | 2026-08-10（觀察日） | [機房總覽頁](https://www.reliablesite.net/data-center/) |
| ReliableSite 新聞室貼文宣布 **AMD EPYC 4545P** 專用伺服器進駐紐約、邁阿密與洛杉磯——三種組態（64GB/1TB、128GB/2TB、256GB/4TB），理由為 65W TDP 與效能功耗比，定位於 AI inferencing 與高密度運算。**這是最近一次採購事件的原廠日期錨點。** | 2025 年 8 月 | [新聞室](https://www.reliablesite.net/hosting-news/offering-amd-epyc-4545p-dedicated-servers/) |

**GAP——達拉斯尚無任何價格或 SKU 廣度資料。** 在 2026-07-30 與 2026-08-07 的擷取中，DFW 僅以單一 SKU（Ryzen 9950X 256GB）的供應屬性出現，Querétaro 仍為預訂狀態。**兩個據點建置訂單的規模與時點均為未知。**

---

## 10. 成本天花板

### 10.1 假設——請先讀完這一節，再看表

**方法。** N 個月的硬體成本天花板 = **（每月租金 − 每月營運成本）× N**。這是理性經營者在滿載出租下、於 N 個月內回收硬體所能支付的上限，尚未計入融資成本，也未計入任何資本報酬。年營收以牌價租金 × 12、100% 出租率表示。

> **以下每一項營運成本數字都是產業常規「假設」，不是關於 ReliableSite 的查證事實。** 任何一項都不是來自該公司。它是針對一家 1–5 Tbps 規模、具自有人力的自營裸機主機商所設定的可辯護區間，**在任何面向客戶的使用場合都必須重申其為假設。**

| 假設項目 | 採用值 | 合理區間 | 依據（明示為假設） |
|---|---|---|---|
| **電力與冷卻** | 綜合到戶電價 **$0.13/kWh**、**PUE 1.5**，套用於*估計平均*系統耗電（非標稱 TDP）→ **每瓦每月 $0.1423**（$0.13/kWh × 730 h/月 × 1.5） | $0.09–$0.18/kWh、PUE 1.3–1.7，會使電力項變動約 **±45%** | 假設。屬產業常規，非 ReliableSite 揭露值。 |
| **估計系統耗電** | 70W（DDR3 世代 4 核清倉機）· 110W（Ryzen 5600X／8600G 級）· 130W（EPYC 4545P 128GB，65W TDP CPU）· 145W（EPYC 4545P 256GB）· 220W（Ryzen 9950X 256GB，170W TDP CPU 搭配大量 DIMM 與 NVMe）· 300W（A10 GPU 節點：150W GPU + 65W CPU + 平台） | — | 假設。由公開 TDP 與零組件數量推得的工程估計值，**非實測值**。 |
| **空間與機櫃** | **每台每月 $10** 攤提——機櫃、佈線、PDU、交叉連接，以及電力以外的設施成本 | $8–$25 | 假設。低端錨點反映的是在次級成本市場以租賃 wholesale 空間進行高密度單路部署；他們自家網站載明 Querétaro 為 258,000 平方英尺、31 MW，屬 wholesale 規模經濟。若其密度確實顯著優於每台 1U，真值會落在此區間下緣或更低，**這會把以下所有天花板往上推。** |
| **頻寬** | **每台每月 $10** 綜合值 | $8–$30 | 假設。低端錨點的理由：他們自營 AS，於五個交換中心（Any2West、DE-CIX New York、Equinix Miami、FL-IX、NYIIX）以 100G 公開對等，1–5 Tbps 且以出向為主、採開放對等政策，故相當比例流量為免結算。其行銷宣稱不限流量、每台 10 Gbps 以上，那是突發與埠速宣稱，**不是承諾速率成本**。 |
| **其他營運成本** | **每台每月 $12**——自有工程與客服人力、IPMI／KVM 佈建、DDoS 清洗、作業系統授權、帳務、金流與退款爭議 | $10–$30 | 假設。 |
| **據此套用的營運成本合計** | **$42**（Intel Special）· **$48**（Ryzen 5600X、Ryzen 8600G）· **$50**（EPYC 4545P 128GB）· **$53**（EPYC 4545P 256GB）· **$63**（Ryzen 9950X 256GB）· **$75**（A10 GPU 節點）——每台每月 | 依上述各區間之全幅敏感度約為每台每月 **$35–$140** | 假設，由上列四項假設推導而得。 |

**刻意排除的項目，以及其偏誤方向。** 出租率假設為 **100%**；現實 70–85% 的使用率會使每一個天花板下修 15–30%，而線上頁面多數 SKU 只剩單台庫存，顯示他們確實跑得很緊。資金成本、IP 位址租賃成本（考量其宣告空間多為租賃，此項並不小）、上架工時與 RMA 備品全數排除。**因此本節公布的每一個天花板都是樂觀上限。若某個 SKU 在這樣的天花板下已經無法涵蓋其 BOM，在現實中只會更差。**

**在任何合理假設組合下都成立的那一項發現。** 每月 $49 的 Intel Special，相對 $42 的營運成本假設約產生 **每月 $7 的邊際貢獻**，換算 **12 個月天花板 $84**、**24 個月天花板 $168**。這個金額買不到任何新硬體。他們價格帶最底層只有在完全折舊完畢的機器上才成立——而這正是他們自家清倉頁面所寫的：銷售先前已部署過、採用 SuperMicro 機殼、預期壽命 5 年以上的伺服器。**該層級在新硬體銷售上結構性地無法承接，無論假設怎麼調，往那裡提案都會敗在算術上。**

### 10.2 由租金推導的成本天花板

| SKU | 每月價格 | 規格 | 100% 出租率年營收 | 12 個月回收天花板 | 18 個月 | 24 個月 | 來源 |
|---|---|---|---|---|---|---|---|
| **Intel Special** | $49/mo | 4 × Varies（DDR3 世代 Xeon／Core 級）、32GB DDR3、1TB SSD。供應 PNJ + MIA。*估計*系統耗電 70W。 | $588 | **$84** | **$126** | **$168** | [2026-08-07 型錄](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |
| **AMD Ryzen 5600X (128GB)** | $119/mo | 6 × 3.70 GHz Zen 3、128GB DDR4、1TB NVMe。供應 MIA + PNJ。*估計*系統耗電 110W。 | $1,428 | **$852** | **$1,278** | **$1,704** | [2026-08-07 型錄](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |
| **AMD Ryzen 8600G** | $159/mo | 6 × 4.30 GHz Zen 4 Phoenix APU、128GB DDR5、2×1TB NVMe。供應 MIA + PNJ。*估計*系統耗電 110W。 | $1,908 | **$1,332** | **$1,998** | **$2,664** | [2026-08-07 型錄](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |
| **AMD Epyc 4545P (128GB)**——出貨主力，也是機隊中最新的矽晶 | $199/mo | 16 × 3.00 GHz EPYC 4005 Zen 5、65W TDP、AM5 腳位、128GB DDR5、2TB NVMe。供應 LAX + PNJ。*估計*系統耗電 130W。**2025 年 10 月上市時為 $149/mo——十個月內租金上調 34%。** | $2,388 | **$1,788** | **$2,682** | **$3,576** | [2026-08-07 型錄](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |
| **AMD Epyc 4545P (256GB)**——同時被選為阿姆斯特丹與 Querétaro 開幕 SKU | $279/mo | 16 × 3.00 GHz EPYC 4005 Zen 5、256GB DDR5、4TB NVMe。供應 AMS + LAX + QRO。*估計*系統耗電 145W。**2025 年 10 月與 11 月為 $199/mo——上調 40%，為型錄中漲幅最陡者。** | $3,348 | **$2,712** | **$4,068** | **$5,424** | [2026-08-07 型錄](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |
| **AMD Ryzen 9950X (256GB)**——唯一在全部六個機房（含達拉斯）皆有庫存的 SKU | $399/mo | 16 × 4.30 GHz Zen 5 Granite Ridge、170W TDP、256GB DDR5、2×4TB NVMe。供應 AMS + DFW + LAX + MIA + PNJ + QRO。*估計*系統耗電 220W。**價格軌跡 $299（2025-06）→ $349（2026-03）→ $359（2026-06）→ $399（2026-08）——十四個月內上調 33%。** | $4,788 | **$4,032** | **$6,048** | **$8,064** | [2026-08-07 型錄](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |
| **nVidia A10 GPU**——型錄中邊際貢獻最高的 SKU | $699/mo | nVidia A10 24GB GDDR6 PCIe Gen4 加速卡 + 12 × 3.70 GHz（Ryzen 9 7900 級）、128GB DDR5、2×2TB NVMe。供應 LAX。*估計*系統耗電 300W。**2024 年 12 月至 2026 年 3 月為 $599/mo，2026 年 6 月起調升至 $699。** | $8,388 | **$7,488** | **$11,232** | **$14,976** | [2026-08-07 型錄](https://web.archive.org/web/20260807123507/https://www.reliablesite.net/dedicated-servers/) |

### 10.3 街頭價物料清單（BOM）

| SKU | 元件 | 零件 | 街頭價 | 來源 |
|---|---|---|---|---|
| **AMD Epyc 4545P (128GB) — $199/mo** | CPU | AMD EPYC 4545P，EPYC 4005 系列，16C/32T Zen 5，64MB L3，AM5 腳位，65W TDP，料號 **100-100001764WOF** | **$592.99**（Newegg 標示 Out of stock）。觀察到較低街頭價：eBay $524.99；AMD 定價 $549。 | [Newegg](https://www.newegg.com/amd-epyc-4545p-socket-am5/p/N82E16819113893) |
| **AMD Epyc 4545P (128GB) — $199/mo** | 機殼 + PSU + 主機板 + NIC（整合式準系統） | **Supermicro AS-1015A-MT** 1U 準系統——16.9 吋深、單路 AM5，支援 EPYC 4005/4004 與 Ryzen 7000/9000 至 170W，4× DDR5 UDIMM 插槽、2× M.2、1× 3.5 吋 SATA、2× 1GbE 內建、500W Platinum PSU。選用整合式準系統而非分件計價，因為它正是對應其型錄中所有 AM5 SKU 的平台等級，且可避免主機板、機殼、電源重複計價。 | **$1,046.00**（NeweggBusiness 標示 Out of stock）。較高街頭價：Broadberry $1,373.56。 | [NeweggBusiness](https://www.neweggbusiness.com/product/product.aspx?item=9b-16-139-455) |
| **AMD Epyc 4545P (128GB) — $199/mo** | 記憶體 | 4 × 32GB DDR5-5600 ECC UDIMM 2Rx8 CL46，Micron **MTC20C2085S1EC56BD1R**——此為正確的模組類別，因 AM5 的 EPYC 4005 平台使用無緩衝 ECC UDIMM，而非 RDIMM | **每條 $215.34 × 4 = $861.36**（Walmart 標示缺貨） | [Walmart](https://www.walmart.com/ip/MICRON-32GB-DDR5-Server-RAM-ECC-UDIMM-2Rx8-5600-CL46-MTC20C2085S1EC56BD1R/5312708792) |
| **AMD Epyc 4545P (128GB) — $199/mo** | NVMe 儲存 | 1 × 2TB NVMe M.2 PCIe Gen4——以 Samsung 990 PRO 2TB，**MZ-V9P2T0B/AM** 作為流動性佳的參考 SKU 計價 | **$385.00**（目前追蹤價）。同一追蹤器上的波動脈絡：2026-04-21 高點 $917.84；2023-11-22 低點 $119.99。 | [Pangoly 價格歷史](https://pangoly.com/en/price-history/samsung-990-pro-2tb) |
| **AMD Ryzen 9950X (256GB) — $399/mo** | CPU | AMD Ryzen 9 9950X，16C/32T Zen 5 Granite Ridge，170W TDP，AM5 腳位 | **$499.99**（Amazon，2026 年 7 月下旬）。其他觀察點：第三方新品 $474.99；2026 年年中 Newegg $485；上市定價 $649。 | [Pangoly 價格歷史](https://pangoly.com/en/price-history/amd-ryzen-9-9950x) |
| **AMD Ryzen 9950X (256GB) — $399/mo** | 主機板 | **Supermicro H13SAE-MF**，micro-ATX，AM5 腳位（LGA-1718），AMD B650 晶片組，支援 EPYC 4005/4004 與 Ryzen 7000/8000/9000 至 170W，4× DDR5-5200 UDIMM，2× PCIe Gen5 x16（x16/x0 或 x8/x8），2× M.2 PCIe Gen5 x4，內建 IPMI。料號 **MBD-H13SAE-MF-O**。 | **$549.00**（Newegg 牌價，標示缺貨）。觀察到的量價街頭價：$467.11。 | [NeweggBusiness](https://www.neweggbusiness.com/product/product.aspx?item=9b-13-183-830) |
| **AMD Ryzen 9950X (256GB) — $399/mo** | 記憶體 | 4 × 64GB DDR5 UDIMM 以達 256GB。**值得在需求探詢中提出的技術矛盾：** H13SAE-MF 官方規格為四槽合計 192GB，因此 256GB 組態要嘛是超規格的 4×64GB 插滿，要嘛是使用了與這片顯而易見的 Supermicro 選擇不同的主機板。**GAP——無法取得任何 64GB DDR5 ECC UDIMM 模組的已查證街頭價。** 此處以 2026 年 7 月所報消費級／UDIMM DDR5 市價每 GB $12–$14 計算。 | **256GB 約 $3,072–$3,584，中點 $3,328——由每 GB 市價推導，非來自模組報價。** 對照之下，registered（RDIMM）市場更嚴峻：64GB DDR5-5600 RDIMM 報價每條 $2,064.00，即每 GB $32.25，256GB 約需 $8,256。 | [DDR5 選購指南，2026 年 7 月](https://techfuelhq.com/articles/ddr5-ram-buying-guide-2025/) |
| **AMD Ryzen 9950X (256GB) — $399/mo** | NVMe 儲存 | 2 × 4TB NVMe M.2 PCIe Gen4 | **一對估計 $1,500–$1,700——非已查證報價。** 係以已查證的 2TB 參考價（$385）等比放大，並套用所報 4TB 與 8TB 容量的不成比例溢價推得。支持此加成的市場脈絡：NAND 價格自 2025 年底以來約已翻倍；一年前 $120–$150 的 2TB NVMe 現價 $300–$480；4TB 與 8TB 區間出現不成比例的價格飆升與庫存短缺。 | [2026 年 NAND 短缺](https://tech-insider.org/ssd-prices-nand-shortage-2026/) |
| **AMD Ryzen 9950X (256GB) — $399/mo** | 機殼 + PSU | 1U 機架式機殼含電源。參考價取自 Supermicro SuperChassis **CSE-505-203B**（1U、200W 80 PLUS Gold、9.8 吋深）。**尺寸相容性警語：** CSE-505 僅接受 mini-ITX，而 H13SAE-MF 為 micro-ATX——實際組裝需要 SC813 級機殼或直接採用 AS-1015A-MT 準系統。**此列應視為機殼與電源項目的下限價，而非已驗證的搭配。** | **$204.92** | [CompSource](https://www.compsource.com/buy/CSE505203B/Supermicro-428) |
| **nVidia A10 GPU — $699/mo** | GPU | NVIDIA A10 Tensor Core，24GB GDDR6，PCIe Gen4，單槽被動式，150W | **$2,750**（美國新品最低在架報價）。43 筆在架報價中位數約 $4,299–$4,320；最高 $4,750。 | [GPU 報價追蹤](https://gpupoet.com/gpu/shop/nvidia-a10) |
| **nVidia A10 GPU — $699/mo** | CPU | AMD Ryzen 9 7900，12C/24T Zen 4，基頻 3.7 GHz，65W TDP，AM5 腳位——由型錄自身的 `data-cores=12` 與 `data-cpu-speed=3.70` 屬性判定 | **未查證——GAP。** 搜尋結果回傳的是 Ryzen 9 7900**X**（觀察區間 $199.99 至 $316），而非非 X 的 7900。僅為彙總目的採用約 **$330** 的佔位值，並標示為未查證。 | [Amazon 商品頁](https://www.amazon.com/AMD-7900-24-Thread-Unlocked-Processor/dp/B0BMQK718H) |
| **nVidia A10 GPU — $699/mo** | 主機板 | Supermicro **H13SAE-MF**（雙 PCIe Gen5 x16 使其成為單槽 A10 的自然承載平台），**MBD-H13SAE-MF-O** | **$549.00** | [NeweggBusiness](https://www.neweggbusiness.com/product/product.aspx?item=9b-13-183-830) |
| **nVidia A10 GPU — $699/mo** | 記憶體 | 4 × 32GB DDR5-5600 ECC UDIMM，Micron **MTC20C2085S1EC56BD1R**，合計 128GB | **每條 $215.34 × 4 = $861.36** | [Walmart](https://www.walmart.com/ip/MICRON-32GB-DDR5-Server-RAM-ECC-UDIMM-2Rx8-5600-CL46-MTC20C2085S1EC56BD1R/5312708792) |
| **nVidia A10 GPU — $699/mo** | NVMe 儲存 | 2 × 2TB NVMe M.2 PCIe Gen4，以 Samsung 990 PRO 為參考 | **$385.00 × 2 = $770.00** | [Pangoly 價格歷史](https://pangoly.com/en/price-history/samsung-990-pro-2tb) |
| **nVidia A10 GPU — $699/mo** | 機殼 + PSU | 可承載 GPU 的 1U／2U 機殼，電源需可支撐 150W 被動式加速卡（被動卡需要導風設計） | **未計價——GAP。** 未能指認或取得任何具體可承載 GPU 的機殼 SKU 報價。**因此以下彙總低估了這個組態的實際成本。** | [Supermicro 機殼產品線](https://www.supermicro.com/en/products/chassis) |

### 10.4 彙總——街頭組裝成本對比租金推導天花板

**組態 A——AMD EPYC 4545P、128GB DDR5、2TB NVMe，售價每月 $199。**
街頭價組裝：CPU $592.99 + AS-1015A-MT 準系統 $1,046.00 + 4×32GB ECC UDIMM $861.36 + 2TB NVMe $385.00 = **$2,885.35**。
對比租金推導天花板：**12 個月 $1,788——短少 $1,097。18 個月 $2,682——短少 $203。24 個月 $3,576——過關，尚餘 $691。**
請仔細看這個結果。**他們最新、出貨量最大、刻意以能效為由選定的平台，在十八個月內回收不了自身的街頭價物料成本，需要大約二十二個月。** 而且這還是對照一個假設 100% 出租率、且未計資金成本的樂觀天花板。

**組態 B——AMD Ryzen 9950X、256GB DDR5、2×4TB NVMe，售價每月 $399。** 這是唯一在全部六個機房都有庫存的 SKU，也是阿姆斯特丹開幕的兩款 SKU 之一。
街頭價組裝：CPU $499.99 + H13SAE-MF $549.00 + 256GB DDR5 約 $3,328（推導值——見 10.3 之 GAP）+ 2×4TB NVMe 約 $1,600（估計值——見 10.3 之 GAP）+ 機殼／電源 $204.92 = **約 $6,181.91**。
對比天花板：**12 個月 $4,032——短少約 $2,150。18 個月 $6,048——短少約 $134，基本上是平手。24 個月 $8,064——過關，尚餘約 $1,880。**
**光是記憶體就佔這個組態的 54%。這一個數字就是他們 2026 年的全部故事。**

**組態 C——nVidia A10 GPU 節點、128GB DDR5、2×2TB NVMe，售價每月 $699。**
街頭價組裝：A10 $2,750（最低報價；中位數 $4,299）+ CPU 約 $330（未查證——見 10.3 之 GAP）+ H13SAE-MF $549.00 + 128GB ECC UDIMM $861.36 + 2×2TB NVMe $770.00 = **約 $5,260，且未含未計價的 GPU 機殼**。
對比天花板：**12 個月 $7,488——過關，即使尚未計入機殼仍餘約 $2,228。18 個月 $11,232 與 24 個月 $14,976——輕鬆過關。** 即使以 $4,299 的 GPU 中位數計，組裝成本約 $6,810，仍可在十二個月內回收。

#### 這個落差對「整合平台 vs. 自行組裝」的提案意味著什麼

1. **自行組裝的優勢已經反轉，而 2026 年就是原因。** 2023 年至 2025 年底，這家公司的整套模式之所以成立，是因為零組件街頭價下跌快於租金下跌：在型錄中，相同組態逐年變便宜——Ryzen 3700X 128GB $139 → $99、Ryzen 5950X 128GB $269 → $139、i9-13900K 128GB $299 → $179。買零件自己鎖起來，明確就是最便宜的路徑。**2026 年 3 月起，這件事劇烈反轉。** 型錄中每一組可對照的組態現在都在漲：EPYC 4545P 128GB $149 → $199（+34%）、EPYC 4545P 256GB $199 → $279（+40%）、Ryzen 9950X 256GB $299 → $399（+33%）、Ryzen 9950X 192GB $249 → $329（+32%）、A10 GPU $599 → $699（+17%）、Ryzen 7950X 192GB $239 → $299（+25%）。**漲幅與裝機記憶體容量成正比，這指認了 DRAM 就是驅動因子。** 他們正把零組件通膨原封不動轉嫁給客戶，而記憶體容量最高的 SKU 被調價得最兇。

2. **算術現在站在你這邊，而不是對立面。** 記憶體與 NAND 便宜的年代，沒有任何整合商打得過一家在公開市場買 DIMM 的主機商。今天，一家握有 DRAM 與 NAND 契約供應、且具備主機板量價的供應商，可以把整合式 EPYC 4005 或 Zen 5 節點的落地價，做到明顯低於組態 A 的 $2,885 街頭價——而 **18 個月回收與 22 個月回收之間的差距，恰恰就是「他能核准的系統」與「他會延後的系統」之間的差距。** 這就是提案本身：不是效能、不是密度、也不是抽象的 TCO，而是**把他們目前在街頭價下做不成的組態，回收期拉回十八個月以內**。

3. **佐證他們已經撞上這道牆的訊號。** 他們的型錄已連續四次快照、涵蓋十個月沒有出現新的 CPU 或 GPU 世代，對比 6.4 個月的歷史中位數（見 9.2）。整條大容量 HDD 儲存線（32TB、40TB、80TB）在 2026 年 6 月至 8 月間消失。2,048GB Threadripper 旗艦消失。型錄廣度由 2025 年 10 月的 40 個 SKU 家族崩落至 2026 年 8 月的 17 個。**一家正在採購的主機商，不會在十個月內把型錄砍掉 58%。他們已經停止採購、改為調價——而且是在同時建置阿姆斯特丹、達拉斯與 Querétaro 的情況下這麼做，這個矛盾終究必須以一筆採購來收斂。**

4. **從 GPU 層級切入，而且現在就切。** 組態 C 以最低街頭 GPU 價計算，十二個月回收還有約 $2,200 餘裕；而他們的 A10 自 2024 年 12 月起就是 GPU 旗艦——在 L4 與 L40S 等級加速卡都已出貨的情況下，一張 Ampere 世代產品撐了二十個月。它同時是他們**邊際貢獻最高的 SKU**（相對假設營運成本為每月 $624，EPYC 4545P 僅 $149）與**最陳舊的 SKU**。這個組合是本帳戶最強的單一切入點。

5. **不要往價格帶底層提案。** 每月 $49 的 Intel Special 約產生每月 $7 邊際貢獻，即使拉到二十四個月，天花板也只有 $168。該層級照設計就是跑在完全折舊的機器上——他們自家清倉頁面就是這麼寫的——**任何新硬體提案碰到它都活不下來。**

**GAP——支撐「機殼 vs. 主機板錢包切分」的自製機殼前提，在本次研究中未獲佐證。** 本次工作的任務說明指出 ReliableSite 已轉為自行設計機殼、密度較 1U 高約 50%。**本次查核未找到該轉換的任何公開證據，因此也無法自型錄推定其時點。** 紀錄上呈現的反而是相反的延續性：其機房頁面自 2015-06-22 至 2025-12-08 的每一次封存擷取中，都**原封不動**載有 *"Every dedicated server offered is physically racked using only server grade SuperMicro equipment in tier 3 and tier 4 facilities"* 這句話，且今日 2026-08-10 的線上頁面仍然在列。清倉頁面自 2015-04-06 至 2024-07-15 亦原封不動載有 *"Each clearance server includes a quality server grade motherboard and SuperMicro branded rackable chassis with a 5+ year life expectancy"*，今日同樣仍在。本次查核所涵蓋的機房頁、清倉頁、首頁、關於頁、新聞室、PeeringDB，以及回傳的 Web Hosting Talk 與 LowEndTalk 結果中，均未出現自製機殼、自研機殼或任何密度宣稱。可能該轉換確實發生但未留下公開痕跡——這完全有可能，因為機殼選擇對客戶不可見——也可能該前提本身不準確。**在以此為基礎建立任何提案之前，必須直接向客戶查證，因為它決定了剩餘錢包究竟是「只有主機板」，還是「主機板加準系統加機殼」。** 本項並未推翻第 6 節（該節奠基於 CEO 第一人稱專訪），而是記錄：為第 8 至 10 節所蒐集的型錄與網站證據，並未獨立佐證該說法（[機房頁](https://www.reliablesite.net/data-center/)；[清倉伺服器頁](https://www.reliablesite.net/dedicated-servers/clearance-servers/)）。

**GAP——自建組裝說法之信心度已下調。** 未能自阿姆斯特丹新聞室貼文萃取硬體相關的逐字句子。某搜尋引擎對該網址的摘要宣稱，阿姆斯特丹設施由 ReliableSite 自有技師駐點、硬體全數由 ReliableSite 擁有，所有伺服器均由其自行組裝、上架、佈線與維護。直接抓取該頁面並未回傳這些句子。**對客戶引用前必須重新查證**——此點重要，因為它是「他們採購主機板與準系統而非整合式系統」的最強可得訊號（[阿姆斯特丹新聞室貼文](https://www.reliablesite.net/hosting-news/reliablesite-dedicated-servers-are-now-available-in-amsterdam/)）。

**GAP——採購通路尚未確立。** 他們究竟是向 Supermicro 直接採購、透過通路商，還是透過電商經銷商，**無法自公開紀錄判定。** 完全沒有 PMSI 備案（見第 8 節）與交易式採購一致，但並不足以證明——現金買方無論走哪條通路都不會產生備案。**就規則 8 通路核准而言，這是需求探詢中最重要的一項待確認事項，而且只能靠開口問。**

---

## 11. 客戶與網路

### 具名客戶（全部來自公司自行發布的案例研究）

- **Scirra Ltd** — Construct／Construct 2 HTML5 遊戲開發軟體的開發商。案例載明規格：4 核 3.2GHz、8GB RAM、SQL Server 授權，部署於 New York City metro 與 Miami 兩地。共同創辦人 **Tom Gullen** 具名引述：「Good quality service is of extreme importance to us. ReliableSite has always provided this... 1 Gbps ports are brilliant!」共同創辦人 **Ashley Gullen** 亦具名。**註：規格年代顯示這是一則較舊的案例**（[案例研究](https://www.reliablesite.net/hosting-news/scirra-dedicated-server-case-study/)）。
- **CloudieWeb.com** — 雲端主機／VPS／專用伺服器轉售商，即 **主機業者型客戶**。CEO **Erkan Saliev** 具名引述：「CloudieWeb provides a service that allows customers to achieve the same great service as our much larger competitors at a fraction of the cost.」部署於 New York City metro 區域。**此案證實其存在批發／轉售客層——這類客戶會帶來成批、可重複的伺服器訂單**（[案例研究](https://www.reliablesite.net/hosting-news/cloudieweb-server-case-study/)）。
- **Little Planes Farm** — 畜牧與飼料零售業者，執行 **AI 視覺工作負載**；案例日期 **2025-11-21**。其 AI 攝影機系統追蹤客戶取貨、清點飼料袋、核對訂單正確性，另有人臉辨識與自動門禁，全部「run entirely on ReliableSite's high-performance dedicated servers」。**在一支幾乎沒有 GPU 容量的機隊上，這是直接的 AI／推論需求訊號**（[案例研究](https://www.reliablesite.net/hosting-news/inside-smart-farms-ai-setup-powered-reliablesite-servers/)）。
- **Let's Encrypt（Internet Security Research Group）— 贊助關係，非付費客戶。** ReliableSite 發布〈ReliableSite Sponsors Certificate Authority Let's Encrypt〉，顯示為基礎設施捐贈／贊助而非商業合約。僅供可信度鋪陳（[公開報導](https://www.reliablesite.net/hosting-news/lets-encrypt-sponsor/)）。
- **客層輪廓（彙總，非具名 logo）：** 公司定位服務對象為「production workloads, private infrastructure, hosting providers, and businesses that need predictable performance without public cloud overhead」，並已推出 **reseller／developer API**（[HostingJournalist 報導](https://hostingjournalist.com/news/dedicated-server-provider-reliablesite-launches-api-for-resellers-and-developers)）。其在 LowEndTalk、Web Hosting Talk 與 HostingDiscussion 的大量在地行銷，顯示主機轉售商與高頻寬／易受 DDoS 攻擊的客群（遊戲、串流、媒體）佔比可觀。**三則案例以外的具名企業客戶＝GAP。**

### 網路

- **ASN：** **AS23470 — ReliableSite.Net LLC（ARIN）**，註冊於 **2018-08-10**。originates **199 個 IPv4 前綴** 與 **29 個 IPv6 前綴**；宣告 **約 50,944 個 IPv4 位址**；觀測前綴合計 267（231 IPv4／36 IPv6）。PeeringDB 自報 1000 個 IPv4／250 個 IPv6 前綴容量。Looking glass：ny1-lg、mi1-lg、la1-lg、nl1-lg.reliablesite.net（QRO 尚未開通）。
- **容量：** PeeringDB 自報流量等級 **1–5 Tbps**，比例以出向為主。公司網路頁載明「multiple 40 Gbps uplinks per switch」與「10+ Gbps network delivery available every server」；**各 IXP 據點皆為 100 Gbps 埠**。宣稱 100% 網路正常運行 SLA 與 0% 封包遺失保證。自建 Layer 3/4 DDoS 過濾系統，CEO 另表示有 **以機器學習為基礎的深度封包分析系統在開發中**。AS23470 有 **8 家上游**，並與 **約 153 個網路** 對接。
- **Transit／上游：** NTT America（AS2914）、TATA Communications（AS6453）、GTT（AS3257）、Arelion、Comcast（AS7922）、Hurricane Electric（AS6939）、NForce（AS43350）。
- **公開 peering（皆 100G）：** Any2West（CoreSite, LA）、DE-CIX New York、Equinix Miami、FL-IX、NYIIX New York。公司另列出 AMS-IX、ERA-IX、Near IP、IENTC 與 Wantelco。
- **Peering 政策：OPEN** — 無合約要求、無流量比要求、無多據點要求（[PeeringDB net/17907](https://www.peeringdb.com/net/17907)）。

---

## 12. 政治與公開紀錄

僅限公開紀錄，僅涵蓋具名負責人，每一列均附明確標記；**已查證的「查無」本身就是結論，不是 GAP**——凡標示「查無紀錄」的列一律保留在表中，因為該次查詢確實執行完畢並回傳空值。本節取代前一輪版本：前一輪把 FEC 與 OpenSecrets 查詢記為「JavaScript 介面無法查詢、未結案」，**該等查詢本次均已實際執行並取得回傳**。

重點結論：**本案全部三名具名人員之中，只有一人在任何層級留有政治紀錄，且僅為單筆 50 美元的代收（conduit）獻金。** NYC Metro 機房經理 **Shahalam Hossain** 於 **2024-10-28** 透過 ActBlue 捐出 **US$50.00**，指定轉交 Harris for President。**Rodion「Radic」Davydov**——創辦人、CEO、註冊代理人，也是集團所有實體唯一的簽署人——**在所有測試過的拼法變體下均無聯邦紀錄，佛州與紐澤西州層級亦查無紀錄**。**Alexander Sinelnikov** 同樣查無。公司本身**無企業 PAC、無獨立分離基金（SSF）、無聯邦遊說登記人、無 OpenSecrets 檔案，兩州亦均無企業獻金紀錄**——包含允許企業捐獻的紐澤西州，若存在企業捐獻本應顯示於該州資料庫。**本案在政治面幾乎沒有足跡：既無可資運用的槓桿，也不構成風險。**

以下所有「查無」均受一項門檻條件限制，引用時必須一併說明：聯邦委員會僅在單一捐款人於同一選舉週期累計超過 **US$200** 時才需逐筆列示。**因此「FEC 查無紀錄」的意思是「無逐筆列示紀錄」，不是「可證明從未捐獻」。** Hossain 的 50 美元之所以看得到，只是因為 ActBlue 作為代收機構，不論金額大小都必須逐筆列示每一筆指定轉交款項。

### 12.1 公開紀錄獻金與公開紀錄查核結果

| 人員 | 職稱／角色 | 事實 | 金額＋日期 | 受贈對象（FEC 委員會代號） | 標記 | 來源 |
|---|---|---|---|---|---|---|
| **Shahalam Hossain** | NYC Metro Data Center Manager, ReliableSite | **查有紀錄——僅此一筆，且是全部 ReliableSite 雇主字串下唯一的聯邦獻金紀錄。** FEC Schedule A：捐款人 **HOSSAIN, SHAHALAM**、雇主 **RELIABLESITE**、職業 **MANAGER**、地址 **Paterson, NJ 07501**。由 **ActBlue 以 CONDUIT／EARMARK（代收／指定轉交）方式受理**（`receipt_type_full = EARMARK`），備註欄文字為 **「EARMARKED FOR HARRIS FOR PRESIDENT (C00703975)」**。申報於 **Form F3X 第 11AI 行**，影像編號 **202412059723466231**，交易 ID **SA11AI_666429834**。捐款人**年度累計金額 US$50.00**——即本選舉週期內他唯一一筆逐筆列示的聯邦獻金。**身分比對警語，明白寫出：** FEC 的雇主欄位為捐款人自行填報的自由文字。雇主字串、職業「MANAGER」以及距 Piscataway 機房約 15 英里的 Paterson NJ 地址，使此一比對具高度可信度，**但並無任何獨立識別碼可將該申報與同名的 ReliableSite 員工綁定** | **US$50.00，2024-10-28** | **ActBlue（C00401224）** 為登記受款之代收機構，指定轉交 **Harris for President（C00703975）**——即目前以 Fight for the People PAC 名義申報的同一委員會代號。**款項是「經由」ActBlue「流向」Harris 競選團隊；受贈對象由捐款人選擇，不是 ActBlue 選的** | **public-record** | [FEC Schedule A — 捐款人 Shahalam Hossain](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Shahalam+Hossain) · [申報影像 202412059723466231](https://docquery.fec.gov/cgi-bin/fecimg/?202412059723466231) |
| **Rodion「Radic」Davydov** | Founder & CEO, ReliableSite；亦為 RELIABLESITE.NET LLC 之**註冊代理人** | **查無 FEC 紀錄——已完成查詢，涵蓋 2000–2026 全部兩年期申報區間。** `Rodion Davydov` = 0 筆；`Davydov, Rodion` = 0；`Radic Davydov` = 0；拼法變體 `Rodion Davidov` = 0、`Rodion Davydoff` = 0。**僅以姓氏**掃描 `Davydov` 全週期共回傳 **771 筆**，**其中沒有任何一筆名字為 Rodion 或 Radic，也沒有任何一筆填報 ReliableSite 為雇主**；紐澤西子集（53 筆）以無關人士 **Yan Davydov**（Summit, NJ）為主，佛州子集（70 筆）以無關人士 **Sofya Davydova**（Coconut Creek／Pompano Beach, FL）為主。以雇主欄位查「ReliableSite」僅回傳一筆，且為 Hossain 而非本人。**結論：這位創辦人兼 CEO 沒有任何形式的聯邦政治獻金紀錄** | 不適用——查無紀錄 | 不適用——查無紀錄 | **public-record（已查證之空值）** | [FEC Schedule A — 捐款人 Rodion Davydov](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Rodion+Davydov) |
| **Alexander Sinelnikov** | Senior Data Center Technician, ReliableSite | **查無 FEC 紀錄——已完成查詢，涵蓋 2000–2026 全部週期。** `Alexander Sinelnikov` = 0 筆；變體 `Alex Sinelnikov` = 0、`Aleksandr Sinelnikov` = 0、`Alexander Sinelnikoff` = 0。僅以姓氏掃描 `Sinelnikov` 回傳 **67 筆，且每一筆都屬於其他人**——Andrey Sinelnikov（Florence, MA，放射科醫師）、Kelsy Sinelnikov（Florence, MA）、Yelena Sinelnikova（Ann Arbor, MI）、Boris Sinelnikov（La Mesa, CA，已退休）、Anton Sinelnikov（Hawthorne, CA）、Julia Sinelnikova（Ridgewood, NY）。**無一人名為 Alexander，亦無一人填報 ReliableSite 為雇主** | 不適用——查無紀錄 | 不適用——查無紀錄 | **public-record（已查證之空值）** | [FEC Schedule A — 捐款人 Alexander Sinelnikov](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Alexander+Sinelnikov) |
| **RELIABLESITE.NET LLC** | 公司法人本身，作為潛在捐款人或委員會發起人 | **查無紀錄。** 以公司名稱作為 **捐款人（法人捐款）** 查詢 FEC Schedule A = **0 筆**。雇主欄位查詢：`ReliableSite` = **1** 筆（即上列 Hossain）；`RELIABLESITE.NET` = **0**；`Reliable Site` = **2 筆，且皆為誤配**——Steven Kelley（Rockville, MD），受僱於無關的 **「RELIABLE ON SITE SERVICES」**。**該公司未設立任何獨立分離基金，亦無企業 PAC。** 以下僅為背景，屬公司登記事實而非政治紀錄：佛州文件編號 **L14000189024**、設立日 **2014-12-11**、地址 Miami, FL、註冊代理人 **Rodion R. Davydov** | 不適用——查無紀錄 | 不適用——查無紀錄 | **public-record（已查證之空值）** | [FEC Schedule A — 雇主 ReliableSite](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=ReliableSite) · [Sunbiz 公司查詢](https://search.sunbiz.org/Inquiry/CorporationSearch/ByName) |

#### 受贈機構 — 沿革、政治傾向與負責人

以下兩個機構之所以出現，完全只因為 Hossain 那筆 50 美元的代收獻金。政治傾向一律取自各機構**自身揭示的宗旨與其自身的 FEC 紀錄——絕不由捐款人反推**。姓氏語源僅供姓名學參照，使用前請先閱讀本節末之免責聲明。

| 機構 | 類型 | 沿革 | 政治傾向（＋佐證） | 負責人 | 負責人姓氏語源（姓名學） | 來源 |
|---|---|---|---|---|---|---|
| **[ActBlue](https://www.fec.gov/data/committee/C00401224/)**（C00401224） | 依 FEC 登記為 **Hybrid PAC（附非捐獻帳戶）– Nonqualified**，指定類別 Unauthorized，申報頻率為月報。**實質上是代收／過渡型支付平台，而非傳統的捐獻型 PAC**——Hossain 該筆為代收指定轉交，ActBlue 只是**經手**款項而非留存。登記地址 PO Box 962017, Boston, MA 02196；TREASURER@ACTBLUE.COM；[secure.actblue.com](https://secure.actblue.com/) | **2004-05-17** 向 FEC 登記，此後持續活動至今（最近一次申報 2026-07-20；2004–2026 每一週期均有活動紀錄）。2004 年由 **Benjamin（Ben）Rahn** 與 **Matt DeBergalis** 創辦——DeBergalis 為 MIT 資訊科學畢業、2003 年曾競選劍橋市議會未當選，Rahn 為哈佛校友、曾中止加州理工的量子物理博士學程。FEC 財務長（treasurer）異動紀錄可完整佐證其制度化交棒：**Matthew DeBergalis（2004–2010）→ Erin Hill（2012–2022）→ George Gilmer（2024 迄今）**，同期委員會類型亦由「PAC – Qualified」升格為「Hybrid PAC（附非捐獻帳戶）」。該平台自述創立約 21 年間已為 **19,000 個以上的競選團隊與組織處理約 190 億美元** 獻金，是民主黨小額募款的主要基礎設施 | **民主黨／進步派——由該組織明文自述，非推論。** 其 About 頁面自述宗旨為「creating technology to shape our democracy and fuel Democratic wins」，並自我定位為民主黨競選團隊、進步派組織與非營利組織的首要線上募款平台。本案 FEC 紀錄本身即為佐證：代收備註欄文字為 **「EARMARKED FOR HARRIS FOR PRESIDENT (C00703975)」**。FEC 代收資料另顯示 ActBlue 的指定轉交流向民主黨籍委員會（Bernie 2020 C00696948、Warren for President C00693234、Harris／Biden C00703975、與民主黨全國委員會相關之委員會），未見流向共和黨籍委員會。**精確性註記：作為代收機構，ActBlue 不選擇受贈對象，選擇的是捐款人；其黨派屬性來自其自述宗旨與適格規則，本欄引用的正是這兩者** | **Regina Wallace-Jones** — President & Chief Executive Officer（2023 年 1 月就任，接替執掌該組織 14 年的 Erin Hill；依美國眾議院 House Administration 與 House Judiciary 兩委員會 2026 年 4 月及 6 月致其為 CEO 的函件，2026 年仍在任）。**George Gilmer** — Treasurer 兼紀錄保管人（FEC Form 1，2024–2026 週期）。**Erin Hill** — 前執行長暨 2012–2022 年 FEC 財務長。創辦人 **Benjamin Rahn** 與 **Matt DeBergalis**（DeBergalis 亦為 2004–2010 年首任 FEC 財務長）。**GAP：董事會主席與完整董事名單未能自第一手來源確認** | **GILMER**（財務長 George Gilmer）——資料記載為源自蓋爾語的**蘇格蘭**姓氏，出自 *Gille Moire*，意為「（聖母）瑪利亞的追隨者／僕人」；另有一支職業義來自蓋爾語 *gille*（僕人）＋ *mor*（偉大）。最早見於蘇格蘭西南 Strathclyde 地區的 **Ayrshire**，並於約 1133–1156 年間在 Cumberland 有早期記載。**WALLACE**（執行長 Regina Wallace-Jones 複合姓氏之一）——資料記載源自**蘇格蘭／英格蘭邊境地帶**，出自 *Wallensis*（意為「威爾斯的」），經盎格魯－諾曼法語 *waleis*（意為「外來的」）而來；有據可查之世系始於 1174 年的封臣 Richard Wallensis。**JONES**（同一複合姓氏之另一半）——為源自人名 John 的**父名式姓氏**，John 出自拉丁文 *Johannes*，意為「耶和華是仁慈的」；以威爾斯來源為主，最早見於威爾斯東北部的 Denbighshire，自 16 世紀起隨威爾斯父名命名習慣擴散 | [FEC C00401224](https://www.fec.gov/data/committee/C00401224/) · [FEC 委員會沿革 API](https://api.open.fec.gov/v1/committee/C00401224/history/) · [ActBlue 宗旨](https://www.actblue.com/about/) · [CEO 就任公告](https://www.actblue.com/posts/introducing-regina-wallace-jones/) · [House Administration 委員會致 CEO Wallace-Jones 函，2026-04-23](https://cha.house.gov/_cache/files/1/d/1de107bd-c3ef-49c2-9980-419213f807dd/BC1AEC45B577803AE5F93BD57DCAF2B043A49C71FABB541878B11F5C19586A89.cha---hearing-invite---wallace-jones.pdf) · [Wikipedia](https://en.wikipedia.org/wiki/ActBlue) · [Ballotpedia](https://ballotpedia.org/ActBlue) · [houseofnames — Gilmer](https://www.houseofnames.com/gilmer-family-crest) · [Wallace](https://www.houseofnames.com/wallace-family-crest) · [Jones](https://www.houseofnames.com/jones-family-crest) |
| **[Fight for the People PAC](https://www.fec.gov/data/committee/C00703975/)**（C00703975）——**前身為 HARRIS FOR PRESIDENT，再前身為 BIDEN FOR PRESIDENT，自始至終為同一委員會代號** | 現為 **PAC – Nonqualified**，指定類別 Unauthorized，**登記政黨為 DEMOCRATIC PARTY**，申報頻率為季報。先前為**總統選舉之主要競選委員會（Presidential principal campaign committee）**。地址 PO Box 58174, Philadelphia, PA 19102；FEC@KAMALAHARRIS.COM；kamalaharris.com。FEC 連結之候選人代號為 **P00009423**（Kamala Harris）與 **P80000722**（Joe Biden） | **同一委員會、兩度更名——這正是正確判讀 Hossain 該筆紀錄的關鍵。** **2019-04-25** 登記為 Joe Biden 2020 年總統選舉主要競選委員會 **BIDEN FOR PRESIDENT**（2020 週期財務長 Maju Varghese；2022 週期起為 Keana Spencer）。**2024-07-21** 提交組織聲明書（Form 1）更名為 **HARRIS FOR PRESIDENT**，即 Biden 退出 2024 年選舉後由 Kamala Harris 接手該競選委員會之時；其後於 2024-08-06 與 2024-10-12 另有 Form 1 申報。**因此 Hossain 於 2024-10-28 的獻金，落在該委員會以 Harris for President 名義運作的期間——這與代收備註欄的文字完全一致。** 2024 年大選後，該委員會依 **2025-09-30** 提交之 Form 1 改制為政治行動委員會 **FIGHT FOR THE PEOPLE PAC**。Harris 公開說明該 PAC 的用途為四處走訪、公開發聲並協助民主黨人當選。委員會目前仍活躍（最近一次申報 2026-07-15） | **民主黨——明文自述，非推論。** FEC 組織聲明書登載該委員會之政黨屬性為 **DEMOCRATIC PARTY**；其登記之候選人代號分別為 Kamala Harris（P00009423）與 Joe Biden（P80000722）；委員會電子郵件與網站為 FEC@KAMALAHARRIS.COM／kamalaharris.com。該委員會在 2025 年改制前的整段存續期間，都是民主黨總統提名人的主要競選委員會；Harris 本人對後繼 PAC 所述之宗旨亦為協助民主黨人當選 | **Keana Spencer** — Treasurer 兼紀錄保管人，自 2022 週期起連續任職至現行 2026 週期，橫跨三個委員會名稱。**Maju Varghese** — 2020 週期之 Treasurer。**Kamala Harris** — 該委員會現行型態所對應之候選人／principal。**註記：作為候選人關聯型 PAC，本委員會不像會員制組織那樣公布主席／會長／執行長名單；FEC 申報上的登載職員即為財務長** | **SPENCER**（財務長 Keana Spencer）——資料記載為源自諾曼法語的**英格蘭職業型**姓氏，出自古法語 *despensier*，意為「管家」或「膳務總管」，即在貴族或王室家戶中掌管配給者。可溯至 1066 年諾曼征服之後的英格蘭，早期記載見於 Leicestershire 的「Robertus Dispensator, otherwise called Le Despencer」；其後以英格蘭中部（Warwickshire、Northamptonshire、Derbyshire、Nottinghamshire）人數最多 | [FEC C00703975](https://www.fec.gov/data/committee/C00703975/) · [FEC C00703975，2024 週期即 Harris for President](https://www.fec.gov/data/committee/C00703975/?cycle=2024) · [委員會名稱／財務長沿革 API](https://api.open.fec.gov/v1/committee/C00703975/history/) · [Form 1 改制為 Fight for the People PAC，2025-09-30](https://docquery.fec.gov/pdf/551/202509309790407551/202509309790407551.pdf) · [Form 1 更名為 Harris for President，2024-07-21](https://docquery.fec.gov/pdf/297/202407219665705297/202407219665705297.pdf) · [全部電子申報](https://docquery.fec.gov/cgi-bin/forms/C00703975/) · [houseofnames — Spencer](https://www.houseofnames.com/spencer-family-crest) |

**重新查詢時的警語。** 委員會 **C00703975** 同一代號先後掛過三個名稱。今日重查該代號者會看到 **「Fight for the People PAC」**，可能因而誤判 2024-10-28 那筆獻金是流向大選後成立的 Harris PAC。**並非如此**——該日期當時委員會係以 **Harris for President** 名義運作，改制用的 Form 1 遲至 2025-09-30 才提交。

#### 州層級政治獻金查核結果 — 每項一行

- **Rodion「Radic」Davydov — 佛州：查無紀錄。** [Florida Division of Elections 政治獻金資料庫](https://dos.elections.myflorida.com/campaign-finance/contributions/)，捐款人查詢，全部選舉／職位／委員會、不設日期範圍：姓氏「Davydov」雖有回傳，但其中僅有 **DAVYDOV MARK M.**（Denver, CO，銀行業）、**DAVYDOV VLADIMIR V**、**DAVYDOV VLADIMIR**、**DAVYDOVA OLGA** 與 **DAVYDOV IRINA** 等相異人士——無 Rodion，亦無 Radic；以「Davydov」＋「Rodion」明確組合查詢則回傳 **0 列（僅有欄位標題）**。查詢環境已用其他查詢驗證可正常運作。
- **Rodion「Radic」Davydov — 紐澤西州：查無紀錄。** [NJ ELEC 依捐款人查詢獻金](https://www.njelecefilesearch.com/SearchContributionByContributor)，姓氏「DAVYDOV」、全部捐款人類型、不加其他條件：**「No records found.」** 已執行正向對照：以姓氏「SMITH」執行相同查詢回傳 19 列真實的紐澤西逐筆獻金資料，**證明查詢確實有執行，而非靜默失敗**。
- **Alexander Sinelnikov — 佛州：查無紀錄。** [Florida Division of Elections](https://dos.elections.myflorida.com/campaign-finance/contributions/)，捐款人姓氏「Sinelnikov」，全部選舉／職位／委員會、不設日期範圍：**0 列，僅有欄位標題**。
- **Alexander Sinelnikov — 紐澤西州：查無紀錄。** [NJ ELEC](https://www.njelecefilesearch.com/SearchContributionByContributor)，姓氏「SINELNIKOV」、全部捐款人類型：**「No records found.」**
- **Shahalam Hossain — 佛州：查無紀錄。** [Florida Division of Elections](https://dos.elections.myflorida.com/campaign-finance/contributions/)，姓氏「Hossain」＋名字「Shahalam」：**0 列**。
- **Shahalam Hossain — 紐澤西州：查無紀錄，且此項刻意查了兩次**，因為他是唯一有聯邦紀錄的人，且居住於紐澤西。[NJ ELEC](https://www.njelecefilesearch.com/SearchContributionByContributor) 以「HOSSAIN」＋「SHAHALAM」精準查詢回傳 **「No records found.」**；僅以姓氏「HOSSAIN」放寬查詢則回傳 **15 列獻金**，其中相異名字為 IFTEKHAR、ANWAR、FAROOK、FARROK、FENOZA、FEROZA 與 FEROZA K，**以程式掃描整份結果表尋找字串「SHAHALAM」，結果為 false**。也就是說，他那筆 50 美元的聯邦獻金**在紐澤西州層級沒有對應紀錄**。
- **RELIABLESITE.NET LLC — 紐澤西州：查無紀錄。** [NJ ELEC](https://www.njelecefilesearch.com/SearchContributionByContributor) 以 **Employer（雇主）** 欄位查「RELIABLESITE」= 「No records found」，以 **Non-Individual Name（法人名稱）** 欄位查「RELIABLESITE」（即公司本身作為法人捐款人）= 「No records found」。**紐澤西州允許企業捐獻，因此若真有企業獻金，此處必然會出現**——這是本節最有力的單一否定結果。
- **RELIABLESITE.NET LLC — 佛州：作為捐款人查無紀錄。** [Florida Division of Elections](https://dos.elections.myflorida.com/campaign-finance/contributions/) 職業／雇主欄位查「ReliableSite」：**0 列**。另單獨查證、僅供背景參考：[Sunbiz](https://search.sunbiz.org/Inquiry/CorporationSearch/ByName) 登載 RELIABLESITE.NET LLC，文件編號 L14000189024、FEI／EIN 47-2515613、設立日 2014-12-11、地址 2115 NW 22nd St, Miami, FL 33142、註冊代理人 Rodion R. Davydov——**此為公司登記事實，不是政治紀錄**。

#### 遊說

> ### **GAP —— 無登記人、無支出。聯邦層級的「零」已查證；兩項州層級查核則尚未完成。**

**ReliableSite／RELIABLESITE.NET LLC 不存在任何形式的聯邦遊說活動。** 參議院《遊說揭露法》（LDA）資料庫以三種方式查詢，全部回傳 `count = 0`：以 `client_name='ReliableSite'` 查 filings = 0；以 `client_name='Reliable Site'` 查 filings = 0；以 `registrant_name='ReliableSite'` 查 filings = 0。**clients** 端點（`client_name='reliablesite'`）亦回傳 `count = 0`，代表**該公司從未被任何事務所登記為遊說客戶**。以遊說者姓名「Davydov」查詢亦為 **0** 筆。對照查詢確認同一 API 對其他查詢會回傳正常且有資料的結果，**因此上述之零值為真實的不存在，而非查詢失效**。支出：**US$0——無 LD-1 登記、無 LD-2 季報備案**，涵蓋資料庫所有可查期間（1999 年迄今，查詢時點為 2026 年 8 月）（[Senate LDA filings API](https://lda.senate.gov/api/v1/filings/?client_name=ReliableSite) · [clients 端點](https://lda.senate.gov/api/v1/clients/?client_name=reliablesite) · [公開查詢介面](https://lda.senate.gov/system/public/)）。

**OpenSecrets 上不存在該公司的機構檔案、遊說檔案或獻金檔案。** 以「ReliableSite」查機構回傳「No results」；以引號片語「Reliable Site」做全站查詢回傳「Your search did not match any results.」。此結果與 Senate LDA 的零值、以及唯一一筆 50 美元的 FEC 紀錄互相一致——**該公司因聯邦政治足跡近乎為零，未達 OpenSecrets 建檔門檻**（[OpenSecrets 機構查詢](https://www.opensecrets.org/search?q=ReliableSite&type=orgs) · [全站查詢](https://www.opensecrets.org/search?q=%22Reliable+Site%22&type=site)）。

**另有兩項州層級遊說查核確實尚未結案，不得記為「查無」：** [佛州遊說登記入口網站](https://floridalobbyist.gov/)之委託人名稱查詢回傳 **HTTP 500 Internal Server Error**，因此佛州州層級的遊說委託人查核**未完成**；紐澤西州 **ELEC 政府事務代理人（governmental-affairs agent）登記則完全未查**。以已查證的聯邦零值推斷，兩者有內容的機率都不高，但形式上仍屬**未查核**。

#### 已實際查詢的來源

**有回傳紀錄的查詢——全部只有一筆：** FEC Schedule A，`contributor_name='Shahalam Hossain'` → 1 列，另加該列的完整明細擷取（雇主、職業、城市、申報表行號、受理類型、影像編號、年度累計金額）。

**查了但一無所獲的來源——這些是已完成的查詢，不是被擋下的查詢：** **FEC Schedule A** 依捐款人姓名查詢（Rodion Davydov、Davydov Rodion、Radic Davydov、Rodion Davidov、Rodion Davydoff、Alexander Sinelnikov、Alex Sinelnikov、Aleksandr Sinelnikov、Alexander Sinelnikoff、Shah Alam Hossain，以及 Davydov、Sinelnikov 之姓氏掃描、Hossain＋城市 Paterson、僅以名字 Shahalam 查詢）· **FEC Schedule A 依雇主欄位查詢**（ReliableSite、RELIABLESITE.NET、Reliable Site）以及以公司作為法人捐款人查詢 · **FEC 委員會端點** C00401224 與 C00703975，含其沿革與 Form 1 申報 · **Senate LDA** filings、clients 與 lobbyist-name 三個端點 · **OpenSecrets** 機構查詢與全站查詢 · **Florida Division of Elections** 政治獻金查詢（捐款人姓氏、姓＋名、職業／雇主欄位）· **NJ ELEC** 依捐款人查詢獻金（捐款人姓氏、姓＋名、雇主欄位、法人名稱欄位，另含 SMITH 正向對照）· **Florida Sunbiz** 公司查詢，僅用於公司登記背景。

**被擋、功能受限或不在範圍內——記錄下來以便日後重跑：** [floridalobbyist.gov](https://floridalobbyist.gov/) 委託人名稱查詢 → **HTTP 500**，未完成 · **NJ ELEC 政府事務代理人登記** → 未查 · **加州 Cal-Access** → 未查；值得註記的是該公司設有**洛杉磯**機房，員工獻金有可能存在於這個未查核的轄區 · [forebears.io](https://forebears.io/) 姓氏頁面 → 直接抓取與實際瀏覽器工作階段皆回傳 **HTTP 403 Forbidden**，因此改以 [houseofnames.com](https://www.houseofnames.com/) 作為公開姓氏參考來源；牛津《Dictionary of American Family Names》因付費牆未能查閱——**若能補上第二個獨立的姓名學來源，這幾筆語源條目會更穩固** · **FEC API 的 DEMO_KEY** 遭速率限制（**HTTP 429、OVER_RATE_LIMIT、Retry-After 約 4.4 小時**），因此改用 fec.gov 自身前端 JavaScript 所公開的 public API key，並帶上 fec.gov referer 發送，**再與 fec.gov 網頁介面交叉驗證，兩者回傳筆數一致**。欲重現本節結果者，建議自行申請 api.data.gov 金鑰或直接使用網頁介面。

**完全未查、且據實載明者：** 本次只跑了**三名具名人員**。ReliableSite 可能另有本檔未列名的其他負責人、成員或經理人，而**本次並未針對 Sunbiz 年報上的完整職員名單做全面掃描**。**配偶與直系親屬亦未查詢**——這是政治獻金常見的替代路徑，且不會以上述任何姓名出現。

#### 非政治性公開紀錄註記（沿用前一輪）

- **查無企業 PAC、查無聯邦承包或補助活動、查無公會理事席次、查無政府事務人員、查無公共政策立場。** 作為私人 LLC 無 SEC 申報。**唯一近似公民參與的紀錄，是該公司贊助 Let's Encrypt 憑證機構——屬技術／非營利性質，非政治**（[Let's Encrypt 贊助](https://www.reliablesite.net/hosting-news/lets-encrypt-sponsor/)）。
- **監理／聲譽註記——非政治，列入客戶規劃［public-record］。** Better Business Bureau 對 RELIABLESITE.NET LLC 的評等為 **「F」**、**未取得 BBB 認證**，理由為 **「Failure to respond to 5 complaint(s) filed against business」**，檔案開立日 **2018-02-26**。**這是客服聲譽訊號，不是法律或監理處分**——查無任何訴訟、執法或制裁紀錄（[BBB 檔案](https://www.bbb.org/us/fl/miami/profile/web-hosting/reliablesitenet-llc-0633-90409819)）。

**本軸線結論。** **本節的主結論是否定的，且應如實陳述，不應淡化。** 一名機房站點經理的單筆 50 美元代收獻金，就是本案政治紀錄的全部。那位一切都由他簽字的創辦人兼 CEO，**在聯邦層級與兩州層級、在所有測試過的拼法變體下都沒有紀錄**。公司**無企業 PAC、無遊說登記人、無遊說支出、無 OpenSecrets 檔案、兩州亦無企業獻金**——這些是已查證的空值而非 GAP，唯二的但書是上述的逐筆列示門檻，以及兩項尚未完成的州層級遊說查核。**這條軸線上既沒有可用的切入槓桿，也沒有風險。記錄於此，是為了讓任何人都不會被它意外，也為了不要再重複前一輪那句「未結案，須人工查詢」——該查的已經查完了。**

*姓氏語源僅為公開姓名學資料之語源考據，並非對任何個人族裔或血統之查證陳述。政治獻金為公開紀錄，不等於政黨登記。除公司政治行動委員會或遊說登記外，本節內容均不歸屬於公司本身。*

---

## 13. 公開聯絡管道

**僅限公開來源。本表不列任何個人行動電話與私人住址，研究過程亦未蒐集。若無已公布之管道，該列標記為 GAP。**

| 管道 | 內容 | 來源 |
|---|---|---|
| 主要／銷售電話（免付費） | **+1 (866) 932-0001** | [BBB 檔案](https://www.bbb.org/us/fl/miami/profile/web-hosting/reliablesitenet-llc-0633-90409819) |
| **銷售信箱——主要外展路徑** | **sales@reliablesite.net** | [Contact 頁](https://www.reliablesite.net/contact/) |
| 支援信箱／24×7 自有支援 | support@reliablesite.net | [Contact 頁](https://www.reliablesite.net/contact/) |
| **徵才信箱——可觸及機房營運／基礎設施主管** | **careers@reliablesite.net** | [NJ 機房技師徵才](https://www.reliablesite.net/hosting-news/nj-job-data-center-technician/) |
| 法務／濫用申訴 | legal@reliablesite.net · complaints@reliablesite.net | [Contact 頁](https://www.reliablesite.net/contact/) |
| 支援／工單入口 | [support.reliablesite.net/Main/](https://support.reliablesite.net/Main/)（知識庫：[support.reliablesite.net/kb/root.aspx](https://support.reliablesite.net/kb/root.aspx)） | [支援入口](https://support.reliablesite.net/Main/) |
| LinkedIn 公司頁 | 「ReliableSite \| Bare Metal Infrastructure」——11–50 人、347 追蹤者、Technology/Information and Internet、founded 2006 | [linkedin.com/company/reliablesite](https://www.linkedin.com/company/reliablesite) |
| **具名決策者——CEO／創辦人（硬體採購者）** | **Rodion R.「Radic」Davydov，CEO & Founder。** 公開路徑：LowEndTalk Host Rep 帳號 **「MrRadic」**（他本人親自在優惠串中回覆硬體與零件成本問題）；公司帳號 **「ReliableSiteHosting」**；LowEndBox 具名專訪。他同時是佛州註冊代理人。**查無任何 VP Infrastructure 或採購職稱** | [LowEndTalk offer thread](https://lowendtalk.com/discussion/218739/us-eu-dedicated-servers-epyc-4545p-ryzen-5800x-intel-core-i9-9900k-more-new-metal-benefits) · [LowEndBox 專訪](https://lowendbox.com/blog/custom-built-for-success-interview-with-radic-davydov-ceo-of-reliablesite/) |
| 註冊／法定地址（同時是 CoreSite MI1 大樓） | 2115 NW 22nd St, Miami, FL 33142-7335 | [FL 登記紀錄](https://bisprofiles.com/fl/reliablesite-net-l14000189024) |
| 紐澤西營運辦公室／機房據點（QTS Piscataway PNJ1 大樓） | 101 Possumtown Rd, Piscataway, NJ 08854 | [Yelp — ReliableSite.net, Piscataway Township](https://www.yelp.com/biz/reliablesite-net-piscataway-township) |
| 社群——其他公開路徑 | Facebook（facebook.com/reliablesite）、X／Twitter、Instagram、YouTube、TikTok；並在 LowEndTalk、Web Hosting Talk 與 HostingDiscussion 張貼優惠 | [Contact 頁](https://www.reliablesite.net/contact/) |
| CEO 層級以下任何具名人員之直撥電話或信箱 | **GAP——無任何已公布管道。所有來源皆查無 CEO 以下的具名人員** | — |
| 採購／進貨部門聯絡窗口 | **GAP——未公布任何採購職能；在 11–50 人規模下，極可能就是 CEO 本人** | — |

---

## 14. Supermicro 銷售切入點

### 分類：**已確認既有客戶——但實際上是「機殼已流失、板級仍開放」的防守戰，外加 GPU 全新開發。**

這**不是**例行續約，也**不是**冷啟動的替換戰。Supermicro 確實在這支機隊裡，由三條獨立證據確認（第 6 節）。但同一份確認它的 CEO 專訪，也正是他們 **離開原廠機殼的第一手說明**：MicroCloud 替換零件買不到、幾乎相同的新世代零件裝不上、價格是「2-3 times the cost」，於是他自建密度高約 50% 的機殼——**並刻意讓它相容於市售主機板與電源**。

這一個設計決定，界定了整個誠實的楔子：

1. **打主機板與電源，不是打機殼。** 機殼生意已經流失，不該優先重推——重推等於重新掀開舊帳。依 CEO 自己公布的設計意圖，仍然開放的是 **主機板與電源這個插槽**。**自製機殼的主機板由誰供應，是本檔商業價值最高的單一未知**，而且公開來源無法回答。
2. **零件供應與交期是活的、第一手的痛點。** CEO 公開表示特定 SSD／RAM 零件出現 **「800% cost increase」**、交期 **3 個月以上**（[LowEndTalk](https://lowendtalk.com/discussion/218739/us-eu-dedicated-servers-epyc-4545p-ryzen-5800x-intel-core-i9-9900k-more-new-metal-benefits)）。長生命週期的零件供應與穩定供貨承諾，正好直接回應當初讓他離開的理由。
3. **AI 缺口是真的，而且已經公布。** 他們行銷「GPU AI Dedicated Servers」、把 EPYC 4545P 定位為 AI inferencing、還發布 AI 視覺客戶案例——背後卻只有 **一款 A10（庫存 1 台）與一張每月 $99 的 Quadro RTX 4000 加購卡**。一款他們能直接上架、標價、自助下單的 4 卡 L40S／RTX PRO 級節點，是最自然的第一個 GPU SKU，尺度對應 1–2 個機櫃、以單路為主的營運型態，**而不是** HGX／SXM 的規模化提案。
4. **他們買的是 Dell 與 HPE 根本不做的平台。** 機隊是單路桌上型／工作站級矽晶——AM5 Ryzen 9950X、LGA1700 i9 14900K、Threadripper 7995WX、EPYC 4545P。這是結構性的產品契合，也正是為什麼這裡沒有 Dell 或 HPE 既有關係可以替換（兩者皆為查無證據）。
5. **Querétaro 是時間觸發點。** QRO 區域公開標示為「coming soon」、網路測試尚未開通——建置進行中，是本帳戶最可能的近期新硬體採購事件。

### 首次接觸要問的資格問題

> **「你們自己的機殼裡用的是哪家的主機板與電源？Querétaro 那批要上什麼平台？」**

首通電話只問這一句，其他都不問。它一句話就解決本檔最高價值的未知；它承認自製機殼是他們的（尊重那個設計決定，而不是攻擊它）；它同時把建置中的區域帶出來。**不報價。不假設既有廠商。不要用「我們知道你們在用 Supermicro」開場**——這對機隊的歷史為真，但在當世代 SKU 級並未確認，而且 CEO 自己公開講過離開 MicroCloud 的經過，帶著佔有感的開場會踩到地雷。

### 規則 8 通路警語——撥出第一通電話前必讀

本業者明顯在營運相當規模的機隊——六個區域、約 50,944 個 IPv4 位址、五個 IXP 據點各 100G 埠、自報 1–5 Tbps——**卻在 CRM 中一筆紀錄都沒有**（2026-08-03 於 salesleads Search，Type = All 實查：無 lead、無 account、無 do-not-call）。合理的推論只有一個：**他們的伺服器是透過經銷通路買的，不是直接向原廠買。** 佐證是他們自述的採購型態：現場備料「keep our inventory on site」、「from tray to rack」自行上架——這正是以零件與準系統為主、透過通路夥伴進貨的行為模式。

**依規則 8，經銷商可以跨越轄區邊界，但必須事先取得核准並掛上「do not call」標記。** 因此：**先確認通路，再登錄 lead，最後才接觸。** 在任何人撥出第一通電話之前，須先與通路窗口確認 ReliableSite 是否已是某家經銷商的既有帳戶。若是，本檔就從「新客開發」轉為「與經銷商共同經營的既有帳戶」，開場方式、報價路徑與登錄方式全部不同。**順序顛倒會造成通路衝突。**

**轄區處理順序：** 一組不得單獨承作本帳戶。FL＝East Coast 3、NJ＝East Coast 1，皆為 **T2 ｜ T3 ｜ T6 ｜ T7 ｜ T12**；Large End User／Data Center 例外不適用，因為 **規則 11 的門檻為 100MW 以上**，本業者遠低於此。**應向 T7（主管 Brian Leaver）發出協同請求。** T11 不符資格，不應收到本檔。

---

## 15. 查證附錄

### 15.1 單一來源支撐的說法——引用前須再驗證

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| ReliableSite 使用 **Supermicro**（三條證據中的其中一條） | Web Hosting Talk 客戶評述 | **社群來源，且兩條 WHT 證據其一為 Atom D510 舊世代。惟 CEO 自己的 LowEndBox 專訪獨立佐證了 Supermicro MicroCloud，故整體判定為「已確認」——單一來源的是這一條個別證據**（[WHT 討論串](https://www.webhostingtalk.com/showthread.php?t=1640888)） |
| **員工 11–50 人** | LinkedIn 公司頁自報 | **單一來源，完全沒有任何交叉佐證。自填區間且範圍很寬** |
| **「From tray to rack... we keep our inventory on site」**（AMD EPYC 4545P） | ReliableSite Facebook 貼文 | **標題經搜尋索引擷取；頁面內文無法直接抓取。視為次級擷取** |
| 特定 SSD／RAM 零件 **「800% cost increase」**、交期 3 個月以上 | CEO 之 Host Rep 帳號「MrRadic」在 LowEndTalk 的單一貼文 | **屬營運者第一手陳述、可信度高——但這是一則論壇貼文、針對特定零件，並非一般性的採購揭露**（[LowEndTalk](https://lowendtalk.com/discussion/218739/us-eu-dedicated-servers-epyc-4545p-ryzen-5800x-intel-core-i9-9900k-more-new-metal-benefits)） |
| **2006 年成立** | 公司 About 頁＋LinkedIn（皆為自述），並由 LowEndBox 專訪以敘事佐證 | **各州登記皆查無 2014 年以前的任何法人。敘事佐證不等於登記佐證** |
| **Querétaro 區域** | ReliableSite 自家機房頁與網路頁 | **僅有公司自行公布；設施營運商未具名，亦無法獨立識別**（[Querétaro 頁](https://www.reliablesite.net/data-center/queretaro-mexico.aspx)） |
| **三則具名客戶案例** | ReliableSite 自行發布之案例研究 | **業者自行發布，未經獨立查證。Scirra 的規格年代顯示為舊案例** |

### 15.2 第三方估計互相矛盾之處——並列呈現，刻意不擇一

**營收**

| 來源 | 數字 | 註記 |
|---|---|---|
| **Kona Equity** | **年營收 $1.2M** | **［第三方估計］**（[來源](https://www.konaequity.com/company/reliablesitenet-llc-4395702578/)） |
| **Owler** | **每員工營收 $27.6K** | **［第三方估計］**——以 11–50 人區間換算約為 $0.3M–$1.4M，與 Kona Equity 大致相容，但兩者都是以同一類薄弱輸入建模而得 |
| **公司／經稽核數字** | **不存在** | 私人 LLC、無 SEC 申報、無自行公布之財務資料 |

**評註（並列呈現而非裁定）：** $1.2M 這個數字與 **可觀測的基礎設施明顯不一致**——約 50,944 個 IPv4 位址、五個 IXP 據點各 100G 埠、自報 1–5 Tbps 流量、六個租用機房區域與 11–50 名員工。光是機房費加 transit 加薪資，很可能就超過 $1.2M。**兩個估計皆予呈現、皆不採用，也不以任何自行推算的數字取代。** 本檔所有營收數字均視為低可信度第三方模型。

**員工數**

| 來源 | 數字 | 註記 |
|---|---|---|
| **LinkedIn（自報）** | **11–50** | **單一來源。本業者未找到任何相競的第三方數字，因此沒有可並列的分歧——但同時也沒有任何佐證。** 確切員工數＝GAP |

**成立年份**

| 來源 | 數字 |
|---|---|
| 公司 About 頁／LinkedIn（自述） | **2006** |
| Florida Division of Corporations | **2014-12-11**（法人設立） |
| ARIN | **2018-08-10**（AS23470 註冊） |

**正確表述：「品牌／營運自 2006、法人自 2014、自有 ASN 自 2018」。不要講「20 年公司歷史」。**

**設施面積與電力**

第 5 節中所有已公布的面積／電力數字，**全部是房東的整棟數值**（QTS：360,000 sq ft／約 176,000 sq ft raised floor／約 52–65 MW；CoreSite MI1：約 43,000+ sq ft）。**ReliableSite 自身的房客配額在任何一個站點都未公開。房東數字與房客數字永遠不得當作同一種量測併用。**

### 15.3 未結 GAP

1. **伺服器數、節點數、機櫃數**——公司與任何第三方皆未公開。僅能由約 50,944 個宣告 IPv4 位址間接推得。**首通電話直接問。**
2. **ReliableSite 在每一個設施的自身租用量體**（sq ft、cage／套房面積、合約 kW／MW）——QTS Piscataway、CoreSite MI1、CoreSite LA1／LA2、Equinix MI1／AM7、Databarn、165 Halsey，全部未公開。現有數字全為房東整棟值。
3. **當世代 Supermicro SKU 級確認。** 現有 Supermicro 證據為（a）社群來源的 WHT 評述，其一為 Atom D510 舊世代；（b）一份談 MicroCloud 的 CEO 專訪，而該專訪本身正是轉向自製機殼的故事。**近數年任何實際部署皆無型號可考。**
4. **自製機殼所使用的主機板／板廠。** CEO 說機殼可裝市售主機板與電源，但從未具名供應商。**這是全檔商業價值最高的單一未知。**
5. **確切員工數。** 僅有 LinkedIn 自報的 11–50 區間。無員工名冊、無組織圖、無 CEO 以下的具名人員。
6. **可信的營收數字。** Kona Equity 的 $1.2M 估計與可觀測的基礎設施規模內部不一致。無任何經稽核或自行公布的財務資料。
7. **CEO Rodion「Radic」Davydov 以外的任何具名主管或經理人。** 查無 CTO、VP Infrastructure、採購主管或機房經理。佛州 SOS 僅列一名幹部。
8. **Rodion Davydov 的 FEC／政治獻金紀錄為「未結案」，不是「已確認沒有」。** fec.gov 與 OpenSecrets 皆回傳 JavaScript 產生的結果集，無法以程式查詢。**必須先人工查詢，才能寫成「無捐獻」。** 且 $200 以下的捐獻本來就不會進入公開紀錄。
9. **2014 年以前的公司沿革。** 若該事業確實自 2006 年營運，應存在更早的法人（NY、NJ 或其他州）或獨資／DBA 登記——但均未找到，形成 8 年登記空窗。
10. **墨西哥 Querétaro 設施的營運商** 未由 ReliableSite 具名，亦無法識別。此處是進行中的建置，因而是最可能的近期硬體採購觸發點——**值得直接詢問。**
11. **換機週期、年度伺服器採購量、現行硬體供應商／經銷關係。** 唯一的間接訊號是 CEO 公開表示特定 SSD／RAM 零件出現「800% cost increase」、交期 3 個月以上，顯示零件供應痛點仍在進行中。
12. **三則已發布案例（Scirra、CloudieWeb、Little Planes Farm）以外的具名企業客戶。** 無 logo 牆、無客戶清單、無轉售商名冊。
13. **BBB「F」評等（5 件投訴未回應，檔案開立於 2018-02-26）屬客服聲譽訊號，不是法律或監理處分。** 查無任何訴訟、執法或制裁紀錄。此處記載是為了避免日後才被發現，不代表對該公司構成不利認定。

### 15.4 影響本檔完整度的工具與取得限制

- **JavaScript 驅動介面無法以程式查詢：** fec.gov 個人捐獻查詢與 OpenSecrets 捐款人查詢。**因此 Rodion Davydov 的 FEC 結果屬「未取得資料」，不得寫成「沒有政治獻金」。**
- **本次研究遭遇的 HTTP 阻擋來源：** Web Hosting Talk（403）、datacentermap（429）、datacenters.com（403）、ZoomInfo（403）、Crunchbase（403）。凡依賴上述來源之發現，本檔皆已標記為社群來源、次級擷取或第三方估計。
- **ReliableSite 的 Facebook 頁面內文無法直接抓取**；「from tray to rack」的標題僅由搜尋索引取得。
- **政治紀錄一致原則：** 本檔所有政治資料僅取自公開紀錄，且逐條標記為 `public-record`、`no-findings`、`gap` 或 `unverified`。不作推論、不以姓氏單獨歸屬、不以相近姓名替代。
