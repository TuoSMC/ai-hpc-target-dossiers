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

**構成切入點的反差：** 公司在首頁掛出「GPU AI Dedicated Servers」服務線、把 **EPYC 4545P 定位為「AI inferencing」**，並發布 AI 視覺客戶案例（Little Planes Farm，見第 8 節）——**但支撐這整套訊息的實際加速器機隊，只有一款 A10 加一張入門級 Quadro 加購卡。** 他們有需求訊號，卻沒有可承接的高密度 GPU 平台。這是 Supermicro GPU 系統乾淨的切入點，且必須依其體質裁切：4U／5U GPU 最佳化準系統，或 2U 4 卡 L40S／RTX PRO 級節點，對應的是 1–2 個機櫃、以單路為主的營運型態，**而不是**他們既無電力也賣不動的 HGX／SXM 規模化提案（[GPU AI 專用伺服器頁](https://www.reliablesite.net/dedicated-servers/gpu-ai-dedicated-servers/)）。

---

## 8. 客戶與網路

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

## 9. 政治與公開紀錄

本節僅涵蓋具名負責人，且每一項均附明確標記。

- **Rodion R. Davydov／「Radic Davydov」（CEO、創辦人）**——**［gap｜unverified／未證實］**
  查無任何聯邦層級的個人政治獻金。以姓名「Davydov」搭配雇主「ReliableSite」進行 FEC 個人捐獻查詢與 OpenSecrets 捐款人查詢，皆無回傳結果。**但兩者皆為 JavaScript 驅動的結果介面，本次研究無法以程式查詢，因此這是「未能證明的負面結果」，不是已驗證的「沒有捐獻」。** 必須人工至 [fec.gov/data/receipts/individual-contributions](https://www.fec.gov/data/receipts/individual-contributions/) 以捐款人姓名「Davydov」、雇主「ReliableSite」手動查詢方能結案。**另請注意 $200 以下的捐獻本來就永遠不會進入公開紀錄。不得寫成「無政治獻金」，只能寫成「未結案，須人工查詢」。**

- **RELIABLESITE.NET LLC（法人）**——**［public-record｜查無］**
  查無企業 PAC、查無遊說登記、查無聯邦承包或補助活動。作為私人 LLC 無 SEC 申報。查無公會理事席次、查無政府事務人員、查無公共政策立場。**唯一近似公民參與的紀錄，是該公司贊助 Let's Encrypt 憑證機構——屬技術／非營利性質，非政治**（[Let's Encrypt 贊助](https://www.reliablesite.net/hosting-news/lets-encrypt-sponsor/)）。

- **監理／聲譽註記（非政治，列入客戶規劃）**——**［public-record］**
  Better Business Bureau 對 RELIABLESITE.NET LLC 的評等為 **「F」**、**未取得 BBB 認證**，理由為 **「Failure to respond to 5 complaint(s) filed against business」**，檔案開立日 **2018-02-26**。**這是客服聲譽訊號，不是法律或監理處分**——查無任何訴訟、執法或制裁紀錄（[BBB 檔案](https://www.bbb.org/us/fl/miami/profile/web-hosting/reliablesitenet-llc-0633-90409819)）。

---

## 10. 公開聯絡管道

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

## 11. Supermicro 銷售切入點

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

## 12. 查證附錄

### 12.1 單一來源支撐的說法——引用前須再驗證

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| ReliableSite 使用 **Supermicro**（三條證據中的其中一條） | Web Hosting Talk 客戶評述 | **社群來源，且兩條 WHT 證據其一為 Atom D510 舊世代。惟 CEO 自己的 LowEndBox 專訪獨立佐證了 Supermicro MicroCloud，故整體判定為「已確認」——單一來源的是這一條個別證據**（[WHT 討論串](https://www.webhostingtalk.com/showthread.php?t=1640888)） |
| **員工 11–50 人** | LinkedIn 公司頁自報 | **單一來源，完全沒有任何交叉佐證。自填區間且範圍很寬** |
| **「From tray to rack... we keep our inventory on site」**（AMD EPYC 4545P） | ReliableSite Facebook 貼文 | **標題經搜尋索引擷取；頁面內文無法直接抓取。視為次級擷取** |
| 特定 SSD／RAM 零件 **「800% cost increase」**、交期 3 個月以上 | CEO 之 Host Rep 帳號「MrRadic」在 LowEndTalk 的單一貼文 | **屬營運者第一手陳述、可信度高——但這是一則論壇貼文、針對特定零件，並非一般性的採購揭露**（[LowEndTalk](https://lowendtalk.com/discussion/218739/us-eu-dedicated-servers-epyc-4545p-ryzen-5800x-intel-core-i9-9900k-more-new-metal-benefits)） |
| **2006 年成立** | 公司 About 頁＋LinkedIn（皆為自述），並由 LowEndBox 專訪以敘事佐證 | **各州登記皆查無 2014 年以前的任何法人。敘事佐證不等於登記佐證** |
| **Querétaro 區域** | ReliableSite 自家機房頁與網路頁 | **僅有公司自行公布；設施營運商未具名，亦無法獨立識別**（[Querétaro 頁](https://www.reliablesite.net/data-center/queretaro-mexico.aspx)） |
| **三則具名客戶案例** | ReliableSite 自行發布之案例研究 | **業者自行發布，未經獨立查證。Scirra 的規格年代顯示為舊案例** |

### 12.2 第三方估計互相矛盾之處——並列呈現，刻意不擇一

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

### 12.3 未結 GAP

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

### 12.4 影響本檔完整度的工具與取得限制

- **JavaScript 驅動介面無法以程式查詢：** fec.gov 個人捐獻查詢與 OpenSecrets 捐款人查詢。**因此 Rodion Davydov 的 FEC 結果屬「未取得資料」，不得寫成「沒有政治獻金」。**
- **本次研究遭遇的 HTTP 阻擋來源：** Web Hosting Talk（403）、datacentermap（429）、datacenters.com（403）、ZoomInfo（403）、Crunchbase（403）。凡依賴上述來源之發現，本檔皆已標記為社群來源、次級擷取或第三方估計。
- **ReliableSite 的 Facebook 頁面內文無法直接抓取**；「from tray to rack」的標題僅由搜尋索引取得。
- **政治紀錄一致原則：** 本檔所有政治資料僅取自公開紀錄，且逐條標記為 `public-record`、`no-findings`、`gap` 或 `unverified`。不作推論、不以姓氏單獨歸屬、不以相近姓名替代。
