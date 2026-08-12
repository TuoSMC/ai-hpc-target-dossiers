# Database Mart LLC（GPU Mart） — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國）· 專員 US8664 Tuo Cheng · **日期：** 2026-08-11
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有持股，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之 GPU 型錄與定價、UCC 歸檔、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 德州 League City — Texas Area = **T1**｜T3。一組可直接註冊。
**CRM 狀態：** 2026-08-11 於 salesleads Search（Type = All）實查為乾淨 — 無 lead、無 account、無 do-not-call。一組可註冊。

---

## 1. 結論摘要

Database Mart LLC 是一家成立 21 年、由所有權人自行經營的德州主機代管公司，對外以 **GPU Mart**（[gpu-mart.com](https://www.gpu-mart.com/)）為主要品牌，另有 VPS Mart、Server Mart、RDP-Servers、WinPC-Mart 與 Cloud Clusters。該公司於 **2005-01-13** 在德州取得設立許可（SOS 檔案號 0800439627、納稅編號 32107118534，[Texas Comptroller 課稅實體紀錄](https://data.texas.gov/resource/9cir-efmm.json)），登記地址為 **257 Westwood Dr, League City, TX 77573**——而不動產紀錄顯示該址是一棟**單戶住宅，不是辦公室**（[HAR 房屋資料](https://www.har.com/homedetail/257-westwood-dr-league-city-tx-77573/8020666)）。所有運算資源都放在兩座租用的第三方資料中心：達拉斯位於 **Psychz Networks** 於 1515 Round Table Dr 的空間內，北堪薩斯城位於 1530 Swift St，網路掛在 **Wholesale Internet, Inc.（AS32097）** 之後（[官方資料中心頁](https://www.databasemart.com/data-center)；[ARIN RDAP 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28)）。

商業上，這是一個**具有明確時間窗的平台轉換（platform conversion）標的，不是既有客戶防守案。** 這裡沒有任何原廠可供取代：直接以 grep 檢查兩個網站首頁以及 `/gpu-specs`、`/about/`、`/about-us`，逐一比對 Supermicro、Dell、Gigabyte、ASUS、Tyan、Inspur、Lenovo、HPE 八個字串，**每一個字串的命中數都是零**。他們是在二手市場主機上自行整合。本檔最重要的單一事實就寫在他們自己的旗艦產品頁上：**H100 80GB HBM2e PCIe 機種月租 $2,099.00，主機平台卻是「36-Core Dual E5-2697v4」**（[gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting)，2026-08-11 讀取）——那是 2016 年的 Broadwell-EP 平台，其 root complex **只有 PCIe 3.0**，而同一頁卻把該卡標示為 PCIe Gen5。他們公開的 26 個專用 GPU SKU，每一個主機都是 Xeon E5 v3/v4、Gold 6148 或 Platinum 8160——**2014-2017 年的主機，型錄裡完全沒有任何當世代平台。**

而這個落差，正被他們自己的採購動作放大。**2025-11-08 至 2026-04-19** 之間，他們新增了六個 Blackwell SKU——RTX PRO 6000 96GB、RTX PRO 5000 48GB、RTX PRO 4000 24GB、RTX PRO 2000 16GB、RTX 5090 與 RTX 5060——並整併到一個專屬入口頁。一張 600W 級、PCIe Gen5、96GB GDDR7 的卡，是他們整份型錄裡最難在 Broadwell 主機板上正確運作的零件；他們甚至還把它切成 32 核／84GB 的多租戶 VPS，月租 $479。與此同時，他們在 **2026-01-21 登記了 38.247.128.0/18——16,384 個 IPv4 位址——而且從未對外宣告過**（326 個 RIS peer 中 0 個看得到，[RIPEstat](https://stat.ripe.net/data/routing-status/data.json?resource=38.247.128.0/18)），並在 2026-07-28 讓 5,120 個租用的 RIPE 位址上線。**沒有人會為一個不打算填滿的 /18 付錢。**

可能讓這筆生意破局的因素有兩個，兩個都已知、也都可管理：**他們的單機經濟模型**（以租金推導，每台機器在 24 個月回收期下的硬體天花板約 $19K–$28K，而一張全新 H100 卡本身就要 $25K–$31K——因此同規格換新平台的訴求在算術上必輸，不得嘗試），以及**通路**（全網未具名任何原廠、主機清一色為二手矽晶、上一代顯卡掛著 20–55% 的常態折扣——所有訊號都指向經銷、中盤或二手市場，因此依 Rule 8，在註冊任何東西之前必須先確立採購路徑）。

---

## 2. 公司速覽

| 欄位 | 內容 | 證據／日期 |
|---|---|---|
| **法人名稱** | **DATABASE MART LLC** — 德州本土 LLC，組織型態代碼 **CL**。無 SEC 申報（私有持股）。**未查得任何德拉瓦州登記**——見第 15 節 | [Texas Comptroller 課稅實體紀錄，經 data.texas.gov Socrata 資源 9cir-efmm](https://data.texas.gov/resource/9cir-efmm.json?$where=upper(taxpayer_name)%20like%20'%25DATABASE%20MART%25')：taxpayer_number **32107118534**；SOS／COA 檔案號 **0800439627**；`sos_status_code` **A**（有效）；`right_to_transact_business_code` **A**（有效）。2026-08-11 取件 |
| **登記之 NAICS 產業代碼** | 州檔案中記載為 **541410**——請注意 541410 是 **Interior Design Services（室內設計服務）**，對一家主機代管公司而言幾乎確定是陳舊或誤植的分類。**逐字照錄，不予更正** | [Texas Comptroller 紀錄](https://data.texas.gov/resource/9cir-efmm.json) |
| **創立日期** | **2005-01-13**（德州 SOS 設立許可日） | [Comptroller 紀錄](https://data.texas.gov/resource/9cir-efmm.json) 中設立日與 `sos_status_date` 皆為 2005-01-13。公司自家 [About 頁](https://www.databasemart.com/about/)（「Founded: January 13, 2005」）與 databasemart.com 網域建立日 **2004-11-16** 互相佐證——網域早設立兩個月，符合創辦人先註冊網域再設立公司的常態 |
| **登記地址／總部** | **257 Westwood Dr, League City, TX 77573**（Galveston 郡，郡代碼 84）。**該址為單戶住宅，不是商辦，也不是資料中心** | 同一地址逐字出現於 (a) 德州 SOS／Comptroller 登記地址、(b) ARIN Org DML-132 地址、(c) 兩個 ARIN POC 地址、(d) 網域 WHOIS 註冊人街道、(e) 公開聯絡地址（[contact-us](https://www.databasemart.com/contact-us)）。不動產紀錄記載為 **5 房／3.5 衛、約 4,300 平方英尺單戶住宅，2014 年興建，最近一次成交 2018-01-25，Zestimate 約 $482,700，目前非待售**（[HAR](https://www.har.com/homedetail/257-westwood-dr-league-city-tx-77573/8020666)；[Zillow](https://www.zillow.com/homedetails/257-Westwood-Dr-League-City-TX-77573/83100153_zpid/)）。**公開紀錄中，該公司沒有任何可單獨辨識的公司辦公室** |
| **營運品牌** | GPU Mart（[gpu-mart.com](https://www.gpu-mart.com/)）、VPS Mart、Server Mart、RDP-Servers、WinPC-Mart、Cloud Clusters | 公司 [About 頁](https://www.databasemart.com/about/) 里程碑：2014 vps-mart · 2016 Linux VPS · 2017 Cloud Clusters 合作 · 2021 gpu-mart.com · 2023 自建控制台 ＋ rdp-servers ＋ server-mart · 2024 40 萬客戶里程碑 · 2025-26 Blackwell ＋ winpc-mart。**以萬用字元查詢德州登記資料庫之 CLOUD CLUSTERS、VPS MART、SERVER MART、GPU MART、WINPC，每一個都回傳「（無紀錄）」——這些是營業品牌，不是獨立的德州法人** |
| **所有權** | 外觀為所有權人自營；**受益所有權、成員與股權比例＝GAP** | 無 SEC 申報。Texas Comptroller 公開資料紀錄**完全沒有幹部、董事、經理人、成員、註冊代理人或簽署人欄位**。[Crunchbase](https://www.crunchbase.com/organization/database-mart) **無任何募資輪、無營收數字**。「所有權人自營、自籌資金」屬推論，非有據事實 |
| **員工數** | **「80+ professionals across six departments: Billing, Marketing, Sales, Support (24/7), Operations, and R&D」——自報** | 公司自家 [About 頁](https://www.databasemart.com/about/)。第三方佐證：[ZoomInfo](https://www.zoominfo.com/c/database-mart-llc/35457795) 記為 **51–200 人**，兩者一致。請注意組成：六個部門中 Support、Billing、Marketing 就佔三個，**真正會評估機殼的技術人力屬少數** |
| **營收** | **GAP — 未揭露。下列區間為模型化 ESTIMATE，不得作為事實登錄 CRM** | 無 SEC 申報（私有 LLC，本就不會有）。[Crunchbase](https://www.crunchbase.com/organization/database-mart) 無營收數字、無募資輪。**ESTIMATE：** 以 80+ 人於低價通用主機業計，人均營收通常落在 $125,000–$300,000 → 全產品線年營收約 **$10M–$25M**。另一方向的合理性檢核：200–600 台 GPU 節點、每台約 $400–500/月、約 80% 使用率 → **GPU 單一產品線約 $0.8M–$3.5M/年**。**CRM $100M 門檻判定：公開資料完全不支持 $100M+ 的描述** |
| **ASN** | **AS401479** — ARIN 代號 AS401479，網路名稱 **「DBM-ASN-KC」**，**2024-11-07** 登記給 Database Mart LLC | [ARIN Whois-RWS org DML-132 asns](https://whois.arin.net/rest/org/DML-132/asns.json)；[RIPEstat as-overview](https://stat.ripe.net/data/as-overview/data.json?resource=AS401479)。**僅 21 個月大**——他們在取得自有 ASN 之前，已用堪薩斯城那個 /22 營運了約四年 |
| **IPv4 資產** | **三個位址池共 22,528 個位址，其中 16,384 個處於休眠狀態** | 自有（ARIN）：**163.123.180.0/22**（1,024 個，網路名 DBM-NET-01，2020-08-03 登記）與 **38.247.128.0/18**（16,384 個，網路名 DATABASEMART-CGNT-NET-1，2026-01-21 登記，**未對外宣告**）。租用（RIPE，經 IPXO）：**93.127.128.0/20**（4,096 個）與 **77.93.152.0/22**（1,024 個），兩者皆於 2026-07-28 首次宣告。[ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json)；[RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) |
| **PeeringDB** | **完全沒有紀錄** — API 對 asn=401479 回傳 `{"data": [], "meta": {"error": "Entity not found"}}` | [peeringdb.com/api/net?asn=401479](https://www.peeringdb.com/api/net?asn=401479)。對一個自有 ASN、握有 22,528 個位址的網路而言，在 PeeringDB 完全缺席是很明顯的成熟度訊號 |
| **CRM 狀態** | **實查為乾淨** — 無 lead、無 account、無 do-not-call | salesleads Search（Type = All），2026-08-11 實查 |
| **轄區／團隊** | League City, TX → Texas Area = **T1｜T3** → 一組自有轄區，可逕行註冊 | Territory Map-Jan.2026 (Rev.1)，Sales Territory Assign 分頁 |

---

## 3. 原始名單更正表

判定尺度：**confirmed（確認）**＝一手具名揭露，或多方獨立佐證｜**partly-confirmed（部分確認）**＝核心屬實，但表述方式須修正｜**contradicted（遭反證）**＝證據與原始名單相反｜**unverified（未經查證）**＝無法由公開來源確立，不得對客戶陳述。

| # | 原始名單說法 | 判定 | 證據 | 來源 |
|---|---|---|---|---|
| 1 | **創辦人全名為「Morris Liu」**——此一說法在本次研究過程中，反覆且高度肯定地出現在一般網路搜尋摘要中，並被帶入本檔前一版 | **UNVERIFIED — 極可能是搜尋引擎的杜撰。請勿刊載、亦請勿口頭使用此姓氏** | 姓氏「Liu」在三組不同的搜尋結果摘要中被斷言，但逐一檢視後，**那三組結果集底下沒有任何一個原始來源真的寫出這個字。** 公司自家 About 頁——也就是創辦人敘事的源頭——只稱他為 **「Morris」**，此外沒有任何資訊。存檔的 **2006-01-27** About.aspx 頁面完全沒有提到任何個人。ARIN、RIPE、四個公司網域的 WHOIS、Texas Comptroller 紀錄、USPTO 所有權人紀錄與 CourtListener，**全都不存在本公司任何自然人姓名。** 搜尋中出現一個 LinkedIn 檔案「Morris W.」（[linkedin.com/in/morrislw](https://www.linkedin.com/in/morrislw)），但其職稱為 GaaS Cloud / Senwill 的 Co-Founder/CEO，與 Database Mart 無任何證據上的連結，且其名首字母甚至與被斷言的姓氏不符——**已明確排除為同一人。** 若把它當成已確認的姓名，等於把 AI 摘要傳播出來的杜撰事實當成紀錄 | [Database Mart About 頁](https://www.databasemart.com/about/) |
| 2 | **公司 FAQ：「Our data centers are located in Dallas, Texas (Southern US) and Kansas City, Missouri (Central US)」**——此措辭把設施呈現為公司自有 | **PARTLY-CONFIRMED**——地點屬實，但「our data centers」誇大了關係。Database Mart 是**機房承租戶，不是設施所有人** | 其堪薩斯城據點位於第三方的建物內：RIPE 對其自有 **93.127.128.0/20** 的 remarks 定位在密蘇里州 Kansas City、Jackson County、**ZIP 64116**——正是 **WholeSale Internet, Inc.（AS32097）**（201 East 16th Ave, North Kansas City, MO）的同一個郵遞區號。RIPEstat asn-neighbours 顯示 AS32097 是 AS401479 的**唯一**BGP 鄰居。Database Mart 自家資料中心頁面亦將 Wholesale Internet 列為頻寬供應商之一。歷史上同一模式即已存在：2006 年存檔 About 頁寫明「All our servers hosted in SAVVIS Data Center at Dallas, TX USA」——明白就是第三方設施。另一項獨立的硬體所有權主張（「We own all hardware infrastructure instead of reselling from other vendors」）**未被任何查得資料反證**；站不住腳的是**設施與網路**的所有權暗示 | [FAQ — general questions](https://www.databasemart.com/faq/general-questions) · [RIPEstat asn-neighbours AS401479](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) |
| 3 | **持有 AS401479 就代表 Database Mart 自行發布並營運自己的生產網路**——業界看到「這家主機商有 ASN」時的標準推論 | **CONTRADICTED，由 BGP 資料反證。** 它自己的 ASN **完全沒有**發布它真正的位址空間 | AS401479 只宣告 **10 個 prefix，全部落在 77.93.152.0/22 與 93.127.128.0/20 之內**——也就是那兩塊歐洲 RIPE 區位址。與此同時，其 ARIN Direct Allocation **163.123.180.0/22**（NetName DBM-NET-01）由 **AS32097 WholeSale Internet** 發布，而其大塊 Cogent 位址 **38.247.128.0/18**（NetName DATABASEMART-CGNT-NET-1、NetType「Reallocated」、Parent COGENT-A）則由 **AS174 Cogent Communications 本身**發布。兩者皆以 RIPEstat prefix-overview 查證。換言之，公司的 ASN 只承載租來的歐洲位址，真正的美國生產位址則由兩家第三方電信業者宣告。雪上加霜的是：它**在 PeeringDB 完全沒有紀錄**——net、org、名稱三種查詢皆空——因此沒有公開 peering 政策、沒有 NOC 聯絡人、沒有 IX 據點。**這同時更正本檔前一版（第 5 節）的一項推論「設施所有者不會單線掛在別人的 ASN 之下」：事實上這家業者確實只單線掛在唯一一個上游之下** | [RIPEstat announced-prefixes AS401479](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) |
| 4 | **AS401479 所宣告的歐洲 IP 空間是 Database Mart 的位址空間** | **CONTRADICTED**——77.93.152.0/22 是向 **IPXO** 市集租來的庫存，根本沒有登記在該公司名下 | RIPE whois 對 77.93.152.0/22 顯示 netname **「IPXO」**、org **ORG-PC480-RIPE**、org-name **「Private Customer」**、org-type OTHER、地址字面上就是 **「Private Residence」**、狀態 SUB-ALLOCATED PA、geofeed 為 geofeed.ipxo.com/geofeed.txt、由 **netutils-mnt** 與 **IPXO-MNT** 維護、abuse-mailbox 為 **report@abuseradar.com**（第三方濫用處理服務）。該 inetnum 中**完全沒有出現「Database Mart」**。唯一把它連上這家公司的，只有 route 物件（`route: 77.93.152.0/22, origin: AS401479`，建立於 **2024-11-13**）。相鄰的 **93.127.128.0/20 確實**登記在 Database Mart 名下（ORG-DML16-RIPE），但帶有同一份 IPXO geofeed 與同一個 netutils-mnt 維護者，顯示兩者來自同一條 IP 租賃通路 | [RIPE whois 77.93.152.0/22](https://apps.db.ripe.net/db-web-ui/query?searchtext=77.93.152.0/22) |
| 5 | **前一版的既定假設：ARIN 聯絡人最終會交出具名技術人員**——這也是把 ASN 紀錄查到底的前提 | **CONTRADICTED**——ASN 紀錄已被徹底查過，其中**因為刻意的登記選擇而完全沒有任何具名自然人** | AS401479 與兩個 ARIN 網段的每一項 ARIN 職能，全部指向**同一個**代號 **ADMIN7533-ARIN**，其名稱字面上就是「Admin」——**同時擔任 OrgAdmin、OrgTech、OrgNOC、OrgDNS 與 OrgRouting 五種角色**——另加一個名為「Abuse」的 **ABUSE8080-ARIN**。兩者的 RDAP vCard 都帶有明確屬性 `["kind", {}, "text", "group"]`，這是**機器可讀的宣告：該代號背後沒有任何個人。** RIPE 完全複製同一模式：**DML72-RIPE** 與 **PC19188-RIPE** 都是 `role:` 物件，**整個 RIPE 資料庫中都不存在對應的 `person:` 物件。** 這不是疏漏——兩個 ARIN POC 的狀態都是 **「validated」**，且分別更新於 **2025-11-03** 與 **2026-01-20**。這家公司是**系統性地拒絕在號碼登錄紀錄中揭露具名員工** | [ARIN RDAP ADMIN7533-ARIN](https://rdap.arin.net/registry/entity/ADMIN7533-ARIN) |
| 6 | **存檔頁面 databasemart.com/Management.aspx（以及 /management）是會列出高階主管的「經營團隊」頁**——從網址看是很自然、也很吸引人的解讀 | **CONTRADICTED**——它是**付費「伺服器代管服務」的產品頁**，完全沒有任何人事資訊 | **2011-10-07** 與 **2019-08-20** 兩個 Wayback 存檔都已完整取回並讀完。兩者都是「Basic Management Plan」／「Full Management Plan」（後期為「Hyper-V Management Plan」／「Dedicated Server Management Plan」）的價目表，列出 24x7x365 支援、Windows 安全性修補、主動監控、Cisco ASA 5505 防火牆加購等功能。**兩份存檔都沒有具名任何人。** 明確記錄下來，讓這條線索就此結案，未來不必重查 | [Wayback 2011-10-07 /Management.aspx](https://web.archive.org/web/20111007123343/http://databasemart.com/Management.aspx) |
| 7 | **公司登記地址一直都是 257 Westwood Dr., League City, TX**——所有現行紀錄上的地址 | **PARTLY-CONFIRMED**——今天正確，但 gpu-mart.com 的 WHOIS 紀錄裡**至今仍留著另一個先前的地址**，而且兩個都是住宅 | 2011-10-07 存檔網站頁尾寫著 **「7017 Weis Dr., Galveston, TX 77551 409-877-4238」**。gpu-mart.com 的註冊人紀錄——**並未**完全遮蔽——至今仍顯示 Registrant Street **「7017 Weis Dr.」**、Galveston, Texas 77551、Registrant Phone **+1.4098774238**，儘管該網域創建於 2021 年，早已是搬遷之後多年。同一支電話 **409-877-4238** 從 2011 年 Galveston 頁尾一路不間斷延續到今天的 ARIN POC 紀錄，把兩個地址綁在同一個持續營運的主體上。**兩個都是住宅地址**，與 About 頁自述創辦人「started Database Mart from his home in Texas」相互印證。這是一個先前未被記錄的第二地址，也是一條可用的不動產紀錄線索（第 4.4 節） | [Wayback 2011-10-07 網站頁尾](https://web.archive.org/web/20111007123343/http://databasemart.com/Management.aspx) |
| 8 | **databasemart.com 與 GPU Mart 品牌就是這家公司的完整公開足跡** | **PARTLY-CONFIRMED**——同一家 LLC 之下至少有四個兄弟品牌，其中一個**與旗艦網域一樣老** | **sqlservermart.com 創建於 2004-11-16T15:55:47Z——比 databasemart.com（2004-11-16T15:55:39Z）晚了八秒**，也就是同一次坐下來一起註冊的，時間在 2005-01-13 設立登記的兩個月前。它的 WHOIS 只被部分遮蔽，顯示 Registrant Street「257 Westwood Dr.」、League City, Texas 77573、Registrant Email **domain@databasemart.com**、Admin Organization **「Database Mart LLC」**——這是兩個品牌之間直接、未遮蔽的登記層連結。一則 LowEndTalk 討論標題也獨立指認出這個品牌家族為「databasemart.com (aka gpu-mart, vps-mart, hyper-v-mart)」。所查的公司網域全部指向同一組 Cloudflare 名稱伺服器（THADDEUS/VIVIENNE.NS.CLOUDFLARE.COM）與同一家註冊商 **NetEarth One Inc.** | [LowEndTalk 品牌家族討論串](https://lowendtalk.com/discussion/183355/is-databasemart-com-aka-gpu-mart-vps-mart-hyper-v-mart-legit) |
| 9 | **LinkedIn 公司頁載明員工數 51–200；About 頁宣稱「80+ Professionals across six departments」** | **UNVERIFIED**——兩個數字彼此並不矛盾，但**兩者都沒有獨立佐證**，而唯一一個硬數據遠低於兩者 | 「80+」落在 LinkedIn 的 51–200 區間內，內部沒有矛盾。但 LinkedIn 的規模區間是**由頁面擁有者自行選填**，不構成證據。唯一查到、與人數相關的獨立數據是：LinkedIn 公司頁只顯示 **16 位關聯成員**——相對於宣稱的 80+ 人是偏低的比例，儘管遠距與非 LinkedIn 使用者的員工可以合理解釋部分落差，而 FAQ 也確實載明「some employees work remotely from other countries and regions」。未找到任何職缺、具名主管、薪資或申報證據可以檢驗這個數字。因此標記為 **unverified**，而非遭反證 | [LinkedIn 公司頁](https://www.linkedin.com/company/database-mart) |
| 10 | **這種規模與年資的公司，應該會有可檢索的訴訟、UCC-1 或聯邦法院足跡，並在其中具名幹部** | **CONTRADICTED**——聯邦案卷紀錄**完全是空的** | 已以 CourtListener API v4 針對 RECAP 聯邦案卷語料（`type=r`）與判決語料（`type=o`）查詢完全相符片語 `"Database Mart"`，**兩者皆回傳 count: 0。** 沒有任何聯邦案件、沒有案卷、沒有判決。這條「從法院案卷取得幹部姓名」的路線就此關閉。UCC-1 申報位於德州州務卿 UCC 系統，與 SOSDirect 同一道付費登入障礙，本次未能觸及——記為第 4.5 節的**缺口**，不是負面查證結果 | [CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search/?q=%22Database%20Mart%22&type=r) |

---

## 4. 領導層與所有權

本節證據等級：**primary-record（一手紀錄）**＝網路號碼登錄機構、州登記檔案、聯邦商標申報、法院案卷、競選財務申報，或公司自家已發布頁面｜**corroborated（多方佐證）**＝兩個以上獨立次級來源互相印證｜**single-source（單一來源）**＝僅一個次級來源，無其他佐證｜**GAP**＝已具名搜尋但查無。

進入表格前有三項前提。

**第一，創辦人的姓氏是一個 GAP，前一版「Morris Liu」的判讀就此撤回。** 公司自家 About 頁**只以名字**稱呼創辦人——「Morris」，並描述其擁有「Ph.D. in Computer Science · Medical Systems & Infrastructure Expert」，且「started Database Mart from his home in Texas, volunteering server expertise to local churches and nonprofits」。該頁任何位置都沒有姓氏，而且**所有已觸及的一手紀錄——Texas Comptroller、ARIN、RIPE、USPTO、四個網域的 WHOIS、CourtListener——都不含本公司任何個人姓名。** 一般網路搜尋摘要反覆斷言姓氏為「Liu」，但沒有任何一組結果集底下的原始來源真的寫出這個字。因此視為未經查證，並**刻意不予記載**（第 3 節第 1 列）。存檔的 **2006-01-27** About.aspx 頁面**完全沒有具名任何個人**，可見這段創辦人敘事是近期新增的行銷文案，不是長期存在的揭露。

**第二，本公司在任何政府申報文件中唯一取得的具名自然人，是外部商標律師。** USPTO TSDR 對 Serial No. 99157317 具名 **Allison Shiozawa Miles** 為 Attorney of Record 與 Correspondent。她是位於猶他州 Lehi 的外部律師——**不是員工、不是幹部、不是負責人**——列入此處是因為本次需求要求把登錄文件上的具名人員以獨立列呈現，**不是**因為她是進入這個客戶的路徑。

**第三，也是決定這個案子該怎麼跑的關鍵：每一個 ARIN 與 RIPE 聯絡人都是職務帳號，而且是刻意登記成這樣的。** 兩個 ARIN POC 的 RDAP vCard 都帶有屬性 `["kind", {}, "text", "group"]`——這是機器可讀的宣告：該代號背後沒有任何個人；而兩個 RIPE 聯絡人都是 `role:` 物件，整個 RIPE 資料庫中不存在對應的 `person:` 物件。兩個 ARIN POC 的狀態皆為 **「validated」**，且分別在 2025-11-03 與 2026-01-20 更新過，可見這是刻意維護的結果，不是疏於管理。**一位連 ARIN tech-c 代號都不肯下放給具名工程師的所有權人，也不會下放資本硬體採購單。**

### 4.1 具名人員

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC 紀錄 | 來源 |
|---|---|---|---|---|---|---|
| **Morris** — **姓氏為 GAP。** 所有已觸及的一手紀錄皆未揭露，廣為流傳的「Liu」判定為未經查證而予以排除（第 3 節第 1 列） | **創辦人暨執行長（Founder and Chief Executive Officer）**，自述持有 **Ph.D. in Computer Science · Medical Systems & Infrastructure Expert** | **高階主管／所有權人**（自述；**未獲任何登記機關佐證**） | **single-source** — 公司自行發布之行銷內容，**零登記機關佐證** | **GAP — 不存在任何個人信箱。** 公開的只有職務信箱：**sales@**、**support@**、**billing@**、**marketing@**、**admin@**、**abuse@**、**domain@databasemart.com**。公司／ARIN 電話 **+1-409-877-4238**。**LinkedIn：GAP** — Database Mart LLC 公司頁顯示 16 位關聯成員，但未登入即無法具名任一位；搜尋中出現的「Morris W.」（[linkedin.com/in/morrislw](https://www.linkedin.com/in/morrislw)）職稱為 GaaS Cloud / Senwill 的 Co-Founder/CEO，**與 Database Mart 無任何證據上的連結，已明確排除** | **查無紀錄，但僅限雇主端。** OpenFEC Schedule A 以雇主「Database Mart」「DatabaseMart」「Database Mart LLC」「GPU Mart」查詢，**皆回傳 0 列**。**個人姓名查詢受阻**，因為 FEC 索引以「LASTNAME, FIRSTNAME」為鍵，而姓氏未知。一旦德州 SOSDirect 交出治理人員的完整法定姓名，即可解鎖 | [Database Mart About 頁](https://www.databasemart.com/about/) — 名字「Morris」最早經查證的出現位置就是現行 About 頁，取件日 **2026-08-11**；公司設立日 **2005-01-13** |
| **Allison Shiozawa Miles** | **Attorney of Record 暨 Correspondent of record**，美國商標 **Reg. No. 8076154 / Serial No. 99157317（「DATABASE MART」）** — **外部律師，非公司員工或幹部** | **登記文件具名人員**（聯邦申報文件上的具名簽署／通訊代理人；外部律師）——已標示 | **primary-record** | **Law.AllisonMiles@gmail.com** 與 **allfa6969mi@outlook.com**（TSDR 均列為經授權之通訊 e-mail）· 電話 **1-(801) 989-3452** · 3051 West Maple Loop Drive Suite 222, Lehi, UT 84043。**LinkedIn：GAP** — 未查至確認檔案；她是外部律師，不是公司負責人 | **查無紀錄。** OpenFEC Schedule A 以 `contributor_name` 查詢「MILES, ALLISON」「SHIOZAWA MILES, ALLISON」「MILES, ALLISON SHIOZAWA」，**各回傳 0 列。** 她是外部律師，因此這屬於完整性查核，而非負責人查核 | [USPTO TSDR Serial No. 99157317](https://tsdr.uspto.gov/statusview/sn99157317) — 自申請日 **2025-04-27** 起為登記在案之代理律師 |
| **「Admin」** — ARIN POC 代號 **ADMIN7533-ARIN**。**不是人名；這是一個職務帳號的字面登記名稱** | AS401479 與 Database Mart 全部 ARIN 資源的 **OrgAdmin、OrgTech、OrgNOC、OrgDNS、OrgRouting**——**一個代號包辦五種角色** | **技術聯絡人——職務／群組帳號。** ARIN RDAP vCard 明確設定 `kind = "group"`，確認其非個人 | **primary-record**（就「這是職務帳號、背後無具名自然人」此一事實而言） | **admin@databasemart.com** · **+1-409-877-4238**（Office）。地址 257 Westwood Dr., League City, TX 77573。登記日 **2020-07-31**——比 Org 紀錄 DML-132 於 2020-08-03 建立早三天——更新日 **2025-11-03**，狀態 **「validated」** | **不適用——非自然人** | [ARIN RDAP entity ADMIN7533-ARIN](https://rdap.arin.net/registry/entity/ADMIN7533-ARIN)（經 whois.arin.net 與 rdap.arin.net 直接查詢） |
| **「Abuse」** — ARIN POC 代號 **ABUSE8080-ARIN**。**不是人名；職務帳號的字面登記名稱** | AS401479 與 Database Mart 全部 ARIN 資源的 **OrgAbuse** | **技術聯絡人——職務／群組帳號**（RDAP vCard `kind = "group"`） | **primary-record**（就「這是職務帳號、背後無具名自然人」此一事實而言） | **abuse@databasemart.com** · +1-409-877-4238。同為 257 Westwood Dr. 地址。登記日 **2021-01-27**、更新日 **2026-01-20**——**恰好在 Cogent /18 重新配發登錄日 2026-01-21 的前一天**，與新配額所要求的濫用聯絡人更新相符。狀態「validated」。**僅列為完整性；非銷售管道，請勿使用** | **不適用——非自然人** | [ARIN RDAP entity ABUSE8080-ARIN](https://rdap.arin.net/registry/entity/ABUSE8080-ARIN) |
| **「Database Mart LLC」**（RIPE NIC 代號 **DML72-RIPE**）與 **「Private Customer」**（RIPE NIC 代號 **PC19188-RIPE**）。**不是人名；兩者皆為 RIPE role 物件** | AS401479 所發布之兩塊歐洲 prefix 的 **admin-c、tech-c、abuse-c**——分別對應 **93.127.128.0/20** 與 **77.93.152.0/22** | **技術聯絡人——RIPE `role:` 物件。兩者皆不存在 `person:` 物件** | **primary-record**（就「這是 role 物件、無具名自然人」此一事實而言） | **report@abuseradar.com**——這是**第三方濫用處理服務，不是 Database Mart 的信箱。** 兩個物件皆由 **netutils-mnt／IPXO-MNT** 維護，也就是由 IP 租賃平台維護，而非由 Database Mart 維護。**RIPE 資料庫中，這家業者不存在任何具名自然人** | **不適用——非自然人** | [RIPE whois 93.127.128.0/20](https://apps.db.ripe.net/db-web-ui/query?searchtext=93.127.128.0/20) — inetnum 建立日分別為 **2024-03-21**（77.93.152.0/22）與 **2025-02-25**（93.127.128.0/20） |
| **PeeringDB 聯絡人** | — | **網路聯絡人（PeeringDB）——根本不存在任何紀錄（GAP），而這個缺席本身就是一項發現** | **primary-record**（就「該紀錄缺席」此一事實而言） | **不適用。** `/api/net?asn=401479` 回傳 `{"data": [], "meta": {"error": "Entity not found"}}`；`/api/org?name__contains=Database%20Mart` 回傳空陣列；`/api/net?name__contains=Mart` 只回傳 iomart 等無關業者。**沒有 net 紀錄、沒有 org 紀錄，因此沒有公開的政策／技術／NOC 聯絡人、沒有 IX 據點、沒有 peering 政策。** 對一個持有自有 ASN 的業者而言，這種缺席具有診斷意義：它與「不做 peering、也不自行發布生產流量」的實體相符 | **不適用** | [peeringdb.com/api/net?asn=401479](https://www.peeringdb.com/api/net?asn=401479) |
| **WholeSale Internet, Inc.（AS32097）** — **唯一 BGP 上游。第三方業者，不是 Database Mart 的聯絡人** | ARIN OrgId **WHOLE-125**、ASName WII、201 East 16th Ave, North Kansas City, MO | **上游傳輸供應商兼實質房東——不是 Database Mart 員工** | **primary-record** | **請勿以此作為進入 Database Mart 的路徑。** RIPEstat asn-neighbours 對 AS401479 **恰好回傳一個鄰居：AS32097，type「left」（上游），power 373。** 其郵遞區號 **64116** 正是 RIPE 對 Database Mart 自有 93.127.128.0/20 remarks 中所載的同一個郵遞區號——堪薩斯城據點**就位於 WholeSale Internet 的設施內，單線掛在它的網路之下** | **不適用——非自然人** | [RIPEstat asn-neighbours AS401479](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) |
| **姓名未公開 — GAP** | **Head of Operations（營運部門主管）**（該部門存在，依公司自家 About 頁） | 技術決策者／基礎設施負責人——對機殼選型握有**實質否決權** | **該職能存在：高度確定；身分：完全未知——不得猜測姓名** | **admin@databasemart.com** 是 ARIN 登記之 routing／tech／NOC／DNS／admin 職務信箱，最有可能觸及此職能 | **不適用——人員未辨識** | [About 頁](https://www.databasemart.com/about/)：「80+ Professionals across six departments: Billing, Marketing, Sales, Support (24/7), Operations, and R&D」。**所有已觸及的來源中，營運部門沒有任何一位個人被具名** |
| **姓名未公開 — GAP** | **Head of R&D（研發部門主管）**（部門存在，依 About 頁） | 技術影響者——在採用平台前驗證 **GPU／驅動／hypervisor 相容性** | **該職能存在：高度確定；身分：完全未知** | **GAP** — 未公布任何對應職能信箱 | **不適用——人員未辨識** | [About 頁](https://www.databasemart.com/about/)。公開的 GPU Mart 型錄涵蓋 A100、RTX A6000、V100 與 RTX PRO 6000 等級的卡，代表確實存在一個真正的驗證職能 |
| **姓名未公開 — GAP** | **Head of Sales（業務主管）**、**Head of Marketing（行銷主管）**、**Head of Support（客服主管）**（三個部門皆由 About 頁確認存在） | 商務對口——僅具路徑意義，並非硬體採購決策者 | **該等職能存在：高度確定；身分：完全未知** | **sales@databasemart.com** · **marketing@databasemart.com** · **support@databasemart.com** | **不適用——人員未辨識** | [聯絡頁](https://www.databasemart.com/contact-us) 公布 sales@databasemart.com 為售前窗口，明載可洽「custom server configurations beyond standard offerings」 |

### 4.2 登錄紀錄（Registry record）

須先界定範圍：公司登記機關這條軌道**幾乎全是負面結果**，而唯一有產出的政府申報文件是一份商標，不是公司登記文件。

| 名稱 | 身分／權限 | 申報文件 | 日期 | 來源 |
|---|---|---|---|---|
| **未取得任何幹部、董事、經理人、成員、註冊代理人或簽署人姓名 — GAP** | 已嘗試之全部身分：**經理人（manager）、成員（member）、治理人員（governing person）、註冊代理人、年度／定期報告簽署人，以及申報歷程中的歷任幹部** | **德州州務卿實體檔案號 0800439627／Texas Comptroller 特許稅紀錄**，納稅編號 **32107118534**、taxpayer_name「DATABASE MART LLC」、`taxpayer_organizational_type` **CL**（LLC）、`sos_status_code` **A**（有效）、`right_to_transact_business_code` **A**、地址 257 WESTWOOD DR, LEAGUE CITY, TX 77573、**郡代碼 84（Galveston）**、NAICS 541410。Comptroller 公開資料端點對本實體**完全沒有幹部、董事、經理人、成員或註冊代理人欄位**。德州不在公開資料中揭露 LLC 成員／經理人；而會顯示登記在案之註冊代理人與每一份年度／定期報告簽署人的 **SOSDirect 申報歷程**，位於**付費訂戶登入**之後，本次未能觸及。**已查核德拉瓦州是否有平行或母公司登記，結果為無**——本實體僅依德州法設立，並由 USPTO TSDR「State or Country Where Organized: TEXAS」獨立佐證 | **2005-01-13**（`sos_charter_date` 與 `responsibility_beginning_date`，皆為 2005-01-13T00:00:00.000） | [data.texas.gov Comptroller 紀錄](https://data.texas.gov/resource/9cir-efmm.json?$q=DATABASE%20MART) |
| **Database Mart LLC**（法人，**非自然人**）——列為 USPTO 所有權人 | **商標所有權人，美國商標 Reg. No. 8076154（Serial 99157317）。** 實際代表 LLC 簽署申請書的宣誓書簽署人**會具名一位治理人員**，但 TSDR 文件包（casedocs API）回傳 **HTTP 404**，且文件檢視器需要互動式 JavaScript 工作階段——**簽署人未取得** | USPTO 商標申請案 **Serial No. 99157317**，商標 **「DATABASE MART」**，服務標章，主要註冊簿（Principal Register），標準字樣主張，「DATABASE」聲明不專用，**第 042 類**（雲端主機供應商服務；資料中心架構、公有／私有雲之技術顧問）。主張 **First Use 與 Use in Commerce 均為 2005-01-14**——比 2005-01-13 的德州設立日晚一天 | 申請 **2025-04-27**；公告異議 **2025-11-04**；**核准註冊 2025-12-23** | [USPTO TSDR Serial No. 99157317](https://tsdr.uspto.gov/statusview/sn99157317) |
| **Allison Shiozawa Miles** | 同一申報案的 **Attorney of Record 暨 Correspondent of record**——外部律師，猶他州 Lehi。**本公司在任何政府申報文件中唯一取得的具名自然人** | TSDR Serial 99157317 之 Attorney/Correspondence Information 區塊：「Attorney Name: Allison Shiozawa Miles」、「Attorney Primary Email Address: Law.AllisonMiles@gmail.com」、「Attorney Email Authorized: Yes」，通訊地址 3051 West Maple Loop Drive Suite 222, Lehi, UTAH 84043，電話 1-(801) 989-3452 | 自 **2025-04-27** 起為登記在案之代理律師 | [USPTO TSDR Serial No. 99157317](https://tsdr.uspto.gov/statusview/sn99157317) |
| **「Admin」（ADMIN7533-ARIN）** 與 **「Abuse」（ABUSE8080-ARIN）** — **職務帳號，RDAP `kind = "group"`** | ADMIN7533 為 OrgAdmin＋OrgTech＋OrgNOC＋OrgDNS＋OrgRouting，ABUSE8080 為 OrgAbuse，適用於 **AS401479**、**163.123.180.0/22** 與 **38.247.128.0/18** | ARIN **Org DML-132**（Database Mart LLC，257 Westwood Dr., League City, TX 77573），登記日 **2020-08-03**、更新日 **2024-11-25**。AS401479，ASName **DBM-ASN-KC**，登記日 **2024-11-07** | POC 登記日 **2020-07-31** 與 **2021-01-27**；更新日 **2025-11-03** 與 **2026-01-20** | [ARIN RDAP ADMIN7533-ARIN](https://rdap.arin.net/registry/entity/ADMIN7533-ARIN) · [ARIN RDAP ABUSE8080-ARIN](https://rdap.arin.net/registry/entity/ABUSE8080-ARIN) |
| **DML72-RIPE（「Database Mart LLC」）** 與 **PC19188-RIPE（「Private Customer」）** — **RIPE `role:` 物件，不存在 `person:` 物件** | **93.127.128.0 – 93.127.143.255**（netname Database_Mart_LLC，狀態 ASSIGNED PA）與 **77.93.152.0 – 77.93.155.255**（netname IPXO，狀態 SUB-ALLOCATED PA，org ORG-PC480-RIPE，地址字面上為「Private Residence」）的 admin-c、tech-c、abuse-c | RIPE org **ORG-DML16-RIPE**，org-name Database Mart LLC，地址 **257 Westwood Dr, 77573, League City, US**——與德州及 ARIN 地址完全一致——org-type OTHER。RIPE remarks 將該 /20 定位於 **密蘇里州 Kansas City、Jackson County、ZIP 64116**，座標 39.147840／-94.568880，Usage Type「(DCH) Data Center/Web Hosting/Transit」。兩者皆由 **netutils-mnt** 維護，abuse-mailbox 為 **report@abuseradar.com** | ORG-DML16-RIPE 建立日 **2025-02-25**；ORG-PC480-RIPE 建立日 **2024-04-29**；route 物件 `77.93.152.0/22 origin AS401479` 建立於 **2024-11-13**，即 AS401479 本身登記後第六天 | [RIPE whois 93.127.128.0/20](https://apps.db.ripe.net/db-web-ui/query?searchtext=93.127.128.0/20) · [RIPE whois 77.93.152.0/22](https://apps.db.ripe.net/db-web-ui/query?searchtext=77.93.152.0/22) |

### 4.3 採購決策圈（Buying committee）

Database Mart 是一家**所有權人自營、無揭露董事會、任何紀錄上都沒有成員或經理人、任何來源都未具名 CFO、六個部門全部由未具名者主管，且每一個 ARIN 與 RIPE 聯絡人都登記為職務帳號**的 LLC。**實質上沒有採購層級，也沒有委員會**——只有一個簽名，以及一項這家公司自己也推翻不了的外部限制。

| 對象 | 為何對伺服器採購具關鍵性 | 接觸方式 |
|---|---|---|
| **Morris**（姓氏為 GAP）— 創辦人暨執行長 | **這家公司唯一存在的具名決策者，也是唯一能簽字的人。** 所有結構性事實都指向單一簽名：一家德州 LLC，沒有揭露董事會、任何紀錄上都沒有成員或經理人、任何地方都沒有具名 CFO、六個部門（Billing、Marketing、Sales、Support、Operations、R&D）全部由未具名者主管，而且——最具決定性的——**每一個 ARIN 與 RIPE 聯絡人都登記為職務／群組帳號，而不是下放給具名工程師。** 一位連 ARIN tech-c 代號都不肯下放的所有權人，也不會下放資本硬體採購單。他自述持有**電腦科學博士**學位，並宣稱親手打造與營運了最早的那批伺服器，因此他同時是**技術評估者，而不只是核准者** | **對技術同儕銷售，不要對採購職能銷售——這裡根本沒有採購職能。** 用密度、散熱、每機櫃功耗與 $/GPU-hour 經濟性開場；他看得懂、也會去看規格表。進入路徑為 **admin@databasemart.com** 或 **sales@databasemart.com**（不存在任何個人信箱），或 ARIN 電話 **+1-409-877-4238**。**紀錄中看得到兩個切入時機，而且兩個都是真的：**（1）**2026-01-21 登錄的 Cogent /18 重新配發**（38.247.128.0/18，16,384 個位址）是一次真實的擴容事件，也是目前時機最好的接觸由頭；（2）該公司**單線掛在唯一一個上游之下，且完全沒有 PeeringDB 據點**——這是一個可信、不像推銷的韌性對話。**請勿提案代管服務或融資包裝：** FAQ 明白寫著「We own all hardware infrastructure instead of reselling from other vendors, reducing operational costs」，硬體自有是一項**身分認同宣示**，任何稀釋它的提案都會在原則上被拒絕 |
| **未具名的營運主管 — GAP** | About 頁確認六大部門中有 Operations 部門，但**未揭露任何個人。** 這個人負責上架、供電與散熱，因此對**任何不符合現有機房佈局的機殼握有實質否決權。** 而這個佈局是硬性限制，**而且不是他們能改變的**：堪薩斯城據點位於 WholeSale Internet 的設施內，機櫃電力與散熱額度由房東決定，不是由 Database Mart 決定 | **無法直接接觸**——沒有姓名、沒有職稱、沒有信箱、沒有 LinkedIn 檔案。只能經由執行長或 **support@** 職務信箱。**在提出任何高密度 SKU 之前，先確認 WholeSale Internet 據點的機房電力／散熱上限**，因為擋住案子的很可能是這個上限，而不是預算 |
| **未具名的研發主管 — GAP** | About 頁確認有 R&D 部門。以 GPU Mart 產品線來看——公開型錄涵蓋 A100、RTX A6000、V100 與 RTX PRO 6000 等級的卡——研發端必然有人在採用平台前驗證 **GPU／驅動／hypervisor 相容性**。**這個職能一句技術上的「不行」，會在執行長看到報價之前就悄悄把案子做掉** | 沒有姓名、沒有聯絡路徑。**採取「先化解」而非「先攻略」：** 在首次接觸時就**主動附上**驅動堆疊、hypervisor passthrough 與驗證文件，讓技術異議在內部被提出之前就已經被回答掉 |
| **WholeSale Internet, Inc.（AS32097）** — 外部房東兼唯一上游；一個**這家公司自己也推翻不了的影響者** | 它不屬於 Database Mart，但對任何硬體採購構成**真實的關卡。** 堪薩斯城的部署位於 WholeSale Internet 的設施內（201 East 16th Ave／Oak Tower 一帶，North Kansas City MO 64116），且**單線掛在 AS32097 之下**——RIPEstat 顯示恰好只有一個 BGP 鄰居。因此機櫃密度、供電、散熱與 cross-connect 全都受制於第三方的設施上限。**一台超出房東每機櫃電力額度的 GPU 機殼，不管誰簽採購單都無法部署** | **請勿把它當成進入 Database Mart 的路徑**——那會打錯對象，而且很可能招致反感。**僅作為資格確認用途：** 在做提案規模之前，先確立部署據點及其每機櫃電力與散熱上限。若目標是高密度平台，誠實的說法是這可能需要**更換設施**，那是一個遠大於硬體採購的決策，會顯著拉長週期 |

### 4.4 未能具名之職位——每一項皆為 GAP

**GAP — 創辦人／執行長姓氏：** 本檔價值最高的單一缺口。公司自家 About 頁只有名字「Morris」。它同時擋住 FEC 個人查詢、州級競選財務查詢、LinkedIn 比對與不動產紀錄比對。**只要調閱一次德州 SOSDirect 申報歷程即可解鎖。** · **GAP — 登記在案之註冊代理人：** 德州不在公開資料中揭露；SOSDirect 需付費。 · **GAP — LLC 成員、經理人與治理人員：** 德州不在公開資料中揭露 LLC 成員身分，Comptroller 紀錄亦無幹部／董事欄位。 · **GAP — 年度／定期報告簽署人（現任與歷任）：** 位於 SOSDirect 付費登入之後。 · **GAP — 2005–2026 申報歷程中的歷任幹部：** 同一道付費牆。 · **GAP — Serial 99157317 的 USPTO 宣誓書簽署人：** 會具名一位有權拘束該 LLC 的治理人員；TSDR casedocs API 回傳 **HTTP 404**，文件檢視器需要互動式 JS 工作階段。**這是 SOSDirect 之外，取得執行長姓氏成本最低的路徑。** · **GAP — CTO／工程副總／任何具名工程師：** About 頁確認 R&D 部門存在；任何來源都未具名任何個人，且 ARIN tech-c 是刻意登記的職務帳號。 · **GAP — CFO／財務副總／財務長／應付帳款負責人：** 任何來源都沒有這個姓名；Billing 只以部門名稱與職務信箱存在。 · **GAP — 營運主管：** 部門已確認，無姓名；對機殼選型握有實質否決權。 · **GAP — 業務主管、行銷主管、客服主管：** 三個部門都由 About 頁確認存在，**一個都沒有具名。** · **GAP — 具名 NOC 或網路工程師：** 每一個 ARIN 與 RIPE 角色都指向 group 型職務帳號，而 PeeringDB 根本沒有紀錄，因此該來源也不存在政策／技術／NOC 聯絡人。 · **GAP — 具名招募主管、獵才顧問，或任何「向誰匯報」的關係：** 沒有徵才頁面（**databasemart.com/careers 回傳 HTTP 404**），也找不到任何職缺。 · **GAP — 隱私遮蔽前的歷史 WHOIS 註冊人姓名：** whoisrequest.com 位於 Cloudflare JS 攔截頁之後；whoxy 與 securitytrails 需付費 API key。**請注意，目前部分遮蔽的紀錄顯示 Registrant Name 為「Domain Registration」，本身就是一個角色佔位字串——因此即使取得未遮蔽的歷史紀錄，也可能仍然沒有自然人。** · **GAP — 研討會講者或與會者身分**（HostingCon、Cloudfest、DataCenter World、NANOG、GTC、SC）：公司或創辦人皆查無簡介、議程或與會名單。 · **GAP — LowEndTalk 與 WebHostingTalk 公司帳號背後的實際員工身分：** 發文一律以公司人格、用「we」書寫，未附任何真實姓名，且 LowEndTalk 討論串直接抓取回傳 HTTP 403。 · **GAP — 媒體專訪、Podcast、YouTube 機房導覽或募資報導：** 公司與任何個人皆查無。 · **GAP — 257 Westwood Dr., League City TX 77573 與 7017 Weis Dr., Galveston TX 77551 的郡估價機關登記所有人**（兩者皆已確認位於 Galveston 郡、郡代碼 84）：TrueAutomation／PropAccess 入口需要互動式工作階段。**這兩個地址都是公司自己對外公布的營業地址，因此都是正當的企業盡職調查標的，而且任一個都能獨立交出所有人的完整法定姓名。這是取得姓氏最強的一條非付費路徑。** · **GAP — UCC-1 之 secured party 與 debtor 簽署人：** 德州州務卿 UCC 系統與 SOSDirect 共用同一道付費牆。 · **已結案，非缺口——德拉瓦州登記：** 已查核，無任何紀錄；本實體僅依德州法設立，並由 USPTO TSDR「State or Country Where Organized: TEXAS」獨立佐證。

### 4.5 已實際查詢之來源——含「查無」者

**有產出者。** **[USPTO TSDR statusview Serial 99157317](https://tsdr.uspto.gov/statusview/sn99157317)** — 產出最高的單一來源：任何政府申報文件中唯一的具名自然人（Allison Shiozawa Miles，含 email、電話與 Lehi UT 地址），另有 Reg. No. 8076154、2025-12-23 核准註冊、所有權人 Database Mart LLC、設立於 TEXAS、first use 2005-01-14。 · **[ARIN Whois（whois.arin.net）](https://rdap.arin.net/registry/entity/ADMIN7533-ARIN)** — 直接以 port-43 查詢 `a AS401479`、`o ! DML-132`、`n ! NET-163-123-180-0-1`、`n ! NET-38-247-128-0-1`、`p ! ADMIN7533-ARIN`、`p ! ABUSE8080-ARIN`：**取得完整紀錄，零個具名自然人。** · **ARIN RDAP**（`rdap.arin.net/registry/entity/DML-132`）— 交出決定性細節：兩個 POC 的 vCard 都帶有 `kind = "group"`。 · **ARIN Whois-RWS REST** `/rest/org/DML-132/nets` — 完整網段清單：163.123.180.0/22（DBM-NET-01，Direct Allocation，登記日 2020-10-12）與 **38.247.128.0/18**（DATABASEMART-CGNT-NET-1，自 COGENT-A 重新配發，登記日 **2026-01-21**——一次規模大且非常近期的擴容事件）。 · **[RIPE NCC whois](https://apps.db.ripe.net/db-web-ui/query?searchtext=93.127.128.0/20)** 查詢兩塊歐洲 prefix — 兩個 org 物件、兩個 role 物件、**零個 person 物件**，並查出 77.93.152.0/22 是登記在「Private Customer／Private Residence」名下的 IPXO 租賃庫存。 · **[RIPEstat](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479)** — announced-prefixes（10 個，全在歐洲區）、prefix-overview（163.123.180.0/22 由 AS32097 發布；38.247.128.0/18 由 AS174 Cogent 發布）、asn-neighbours（恰好一個：AS32097），以及 AS32097 的 whois（WholeSale Internet，OrgId WHOLE-125，ZIP 64116）。 · **[Texas Comptroller 公開資料 resource 9cir-efmm](https://data.texas.gov/resource/9cir-efmm.json?$q=DATABASE%20MART)** — 實體資料：納稅編號 32107118534、SOS 檔案號 0800439627、設立 2005-01-13、狀態有效、郡代碼 84、NAICS 541410；**完全沒有任何幹部欄位。** · **sqlservermart.com 註冊商層級 WHOIS** — 品牌之間未遮蔽的登記層連結（比 databasemart.com 晚八秒建立；Registrant Street 257 Westwood Dr.；Registrant Email domain@databasemart.com；Admin Organization「Database Mart LLC」）。 · **gpu-mart.com 註冊商層級 WHOIS** — 一個**先前未被記錄的地址**：Registrant Street「7017 Weis Dr.」、Galveston TX 77551、電話 +1.4098774238；Registrant Name 為「Domain Registration」，屬角色佔位字串。 · **[Wayback Machine CDX](https://web.archive.org/web/20111007123343/http://databasemart.com/Management.aspx)** — 60 餘個存檔，篩選 about／contact／team／management／company／staff／press／news；2011-10-07 與 2019-08-20 的 /Management.aspx 及 2006-01-27 的 /About.aspx 皆完整讀畢。 · **[Database Mart About 頁](https://www.databasemart.com/about/)** 與 **[FAQ](https://www.databasemart.com/faq/general-questions)** — 創辦人名字、博士學位主張、六個部門名稱、「80+ Professionals」、創立日期、四個職務信箱，以及第 3 節所引用的資料中心與硬體所有權主張。

**已觸及但在人員面查無。** **[PeeringDB](https://www.peeringdb.com/api/net?asn=401479)** — 以三種方式查詢（`/api/net?asn=401479`、`/api/org?name__contains=Database Mart`、`/api/net?name__contains=Mart`）：**沒有 net 紀錄、沒有 org 紀錄、沒有聯絡人、沒有 IX 據點。** · **[CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search/?q=%22Database%20Mart%22&type=r)** — RECAP 案卷（`type=r`）與判決（`type=o`），完全相符片語「Database Mart」：**兩者皆 count 0。** · **[OpenFEC Schedule A](https://api.open.fec.gov/v1/schedules/schedule_a/?api_key=DEMO_KEY&contributor_employer=Database+Mart)** — 四種雇主寫法，**全部 0 列**；三種律師姓名寫法，**全部 0 列。** · **[OpenFEC /v1/committees/](https://api.open.fec.gov/v1/committees/?api_key=DEMO_KEY&q=database+mart)** — **0 個委員會；不存在公司 PAC。** · **[美國參議院 LDA API](https://lda.senate.gov/api/v1/filings/?client_name=Database%20Mart)** — client_name「Database Mart」與「GPU Mart」，**兩者皆 count 0。** · **Socrata catalog API** 於 data.texas.gov 搜尋幹部／董事資料集 — **德州 LLC 不存在此類公開資料集。** · **德拉瓦州** — 查核有無平行或母公司登記，**無**；本實體僅依德州法設立。 · **USPTO tmsearch 與 assignment-api** — 分別回傳 MethodNotAllowed 與空回應。 · **「GPU MART」商標** — 已搜尋，**查無任何此類商標存在的證據**；僅 DATABASE MART 一件已註冊。 · **[databasemart.com/careers](https://www.databasemart.com/careers)** — **HTTP 404，不存在徵才頁面。** · **求職平台**（ZipRecruiter、BuiltIn、talent.com）— 查無任何可歸屬於本公司的內容；ZipRecruiter 上的「Database Mart Jobs」列表是對無關雇主之「data mart」職缺的一般關鍵字比對。 · **[LinkedIn 公司頁](https://www.linkedin.com/company/database-mart)** — 總部 257 Westwood Dr、規模區間 51–200、創立 2005、四項專長、**16 位關聯成員，未登入即無法看到任何個人姓名**；另注意該頁所列網站是一組聯盟行銷追蹤連結（clients.databasemart.com/aff.php?aff=421）。 · **LinkedIn 創辦人搜尋** — 最接近的「Morris W.」已排除為非同一人。 · **LowEndTalk 與 WebHostingTalk** — 已確認品牌家族，但發文一律以公司人格用「we」書寫，**未取得任何真實員工姓名**，且介紹討論串回傳 HTTP 403。 · **Reddit、Hacker News、研討會來源**（HostingCon、Cloudfest、DataCenter World、NANOG、GTC、SC）、**媒體、專訪、Podcast、YouTube 機房導覽與募資報導** — **全部查無**，與一家自籌資金、所有權人自營的 LLC 相符。

**受阻或未觸及，以及原因。** **德州 SOSDirect（sos.state.tx.us）** — **未觸及。** 登記在案之註冊代理人、經理人／成員與所有年度報告簽署人皆位於**付費訂戶登入**之後。這是整個人員章節唯一的阻斷性付費牆。 · **USPTO TSDR casedocs／casestatus JSON API**（`/ts/cd/casedocs/sn99157317/docs.json`）— **HTTP 404**；會具名治理人員的宣誓書簽署人未取得。 · **OpenCorporates** — v0.4 API 回傳「Invalid Api Token」；實體頁 `us_tx/0800439627` 回傳 **HTTP 403**。 · **Bizapedia** — 遭「Performing a quick security check」攔截頁阻擋。 · **OpenGovUS**（`opengovus.com/texas-business/32107118534`）— 「File not found」。 · **trademarks.justia.com** 所有權人頁 — **HTTP 403**。 · **whoisrequest.com** 歷史 WHOIS — Cloudflare JS 攔截頁；**whoxy** 與 **securitytrails** 需付費 API key。 · **德州公職倫理委員會（Texas Ethics Commission）** 州級競選財務 — 需互動式工作階段，且個人查詢無論如何都受阻於未知姓氏（第 12 節）。 · **Galveston 郡估價機關** propaccess.trueautomation.com — 僅回傳一般入口外殼，不動產查詢需互動式工作階段，因此**257 Westwood Dr. 與 7017 Weis Dr. 的登記所有人皆未取得。**

**在不驚動公司的前提下，補上幹部缺口的最佳下一步：** 透過訂戶帳號或商業登記資料廠商，對檔案號 **0800439627** 執行一次**德州 SOSDirect 申報歷程調閱**。單這一份文件集就能交出設立證書、註冊代理人，以及每一份年度／定期報告的簽署人——而這又會解開目前因為**沒有姓氏可查**而完全無法進行的 FEC 與德州公職倫理委員會個人查詢（第 12 節）。**次佳且免費的做法：** 對任一個已公布的營業地址，向 Galveston 郡估價機關查詢登記所有人。

---

## 5. 據點與機房

| 據點 | 設施營運者 | 自有 vs 租用 | 規模／電力（僅列已公布者） | 證據 |
|---|---|---|---|---|
| **德州達拉斯** — 公司行銷用語為 **「South US」** — **1515 Round Table Dr, Dallas, TX 75247**。公司公布之測速 IP **108.181.95.28** | **Psychz Networks**（ARIN Org **PS-184**，AS40676），20687-2 Amar Rd #312, Walnut, CA 91789。該空間的 ARIN abuse POC **TEXAS1-ARIN** 登記於 **「Profuse Solutions INC」、「Texas - NOC」，1515 Round Table Drive, Dallas, TX 75247**——即該建物內的實際營運實體。**Database Mart 是客戶／承租戶** | **租用——高信心。** Database Mart 在此**並未**持有 IP 空間：108.181.0.0/16 登記於 Psychz Networks 名下，而非 Database Mart LLC，且 Database Mart 自己的 ARIN 機構（DML-132）在此範圍內**不持有任何資源**。若是自有設施的承租戶，會持有自己的位址空間與自己的 abuse 聯絡人 | **以下為 Database Mart 公布之設施層級規格。這些描述的是「建築物」，不是 Database Mart 在其中的佔用範圍，不得引用為 Database Mart 的容量：** 2 台 2MW Cummins 發電機；3 台 600kVA Liebert UPS，**2N+1** 配置；12 台 30 噸 Liebert 氣冷機組，合計 **360 噸、N+2**；上鎖籠架、影像監控、周界圍籬；24/7 現場技術人員。**Database Mart 自身的籠架面積、機櫃數與簽約 kW：GAP — 任何地方都未揭露** | [官方資料中心頁](https://www.databasemart.com/data-center) 公布街道地址、測速 IP 與設施規格。[ARIN RDAP 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28) 回傳 Psychz Networks 為登記人，abuse 聯絡地址即 1515 Round Table Drive。**兩個獨立來源對同一棟建物互相印證** |
| **密蘇里州北堪薩斯城** — 行銷用語為 **「Central US」** — **1530 Swift St, North Kansas City, MO 64116**。公司公布之測速 IP **163.123.183.33** | **設施營運者未經任何已觸及之公開紀錄具名確認 — GAP。** 已確認的是：此據點的 IP 空間（**163.123.180.0/22**，ARIN 網路代號 NET-163-123-180-0-1，網路名稱 **「DBM-NET-01」**）**直接登記於 Database Mart LLC**（Org DML-132）名下，而對外宣告者是密蘇里州 Kansas City 的 **AS32097, Wholesale Internet, Inc.**——因此是傳輸供應商，也很可能是設施合作方 | **空間為租用，位址為自有。** 這是兩個據點中較成熟的一個：Database Mart 在此持有自己的 ARIN 配額（達拉斯沒有），並以此地為名把自有 ASN 取名 **「DBM-ASN-KC」**。但該建物是電信中立的多租戶設施，並以第三方公用事業關係描述，且 Database Mart 的路由完全依賴 Wholesale Internet 的 AS32097——**設施擁有者不會單歸屬（single-homed）在另一家業者的 ASN 之後** | **以下同樣是 Database Mart 公布之設施層級規格（再次強調：是建築物，不是他們的佔用範圍）：** N+1 天然氣發電機；**「Evergy Ttier 1 customer」** 資格 *[逐字照錄，含原文錯字]*；A/B/C/D 冗餘供電配置；N+1 空調搭配高架地板冷熱通道；「100% 4K UHD cameras」雙角度覆蓋。網路：連接 **AMS-IX、DE-CIX、SIX**；供應商列出 **KCFiber、Zayo、AT&T、Hurricane Electric**。**Database Mart 自身籠架／機櫃／kW：GAP** | [官方資料中心頁](https://www.databasemart.com/data-center) 提供地址、測速 IP 與規格。[ARIN RDAP 163.123.183.33](https://rdap.arin.net/registry/ip/163.123.183.33) 回傳 Database Mart LLC 為 DBM-NET-01 登記人。[RIPEstat routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=163.123.180.0/22) 對 163.123.180.0/22 回傳單一來源 AS **AS32097**，**326 個 RIS peer 全數可見**，首見 **2021-01-30**，2026-08-11 仍在宣告——五年半的穩定生產據點。**2023 年 7 月** 一則公司新聞「Network and Power Issue in Kansas Data Center」獨立佐證該地確有線上生產容量（[portal.databasemart.com/news/](https://portal.databasemart.com/news/)） |
| **257 Westwood Dr, League City, TX 77573** — 登記總部 | Database Mart LLC（住宅） | **不是資料中心。此處特別標註，以免被誤認** | 5 房／3.5 衛、約 4,300 平方英尺單戶住宅，**2014** 年興建，最近成交 **2018-01-25**。**依其型錄規模推算，不可能有任何運算資源放在此處** | 該地址同時逐字出現於 SOS／Comptroller 登記地址、ARIN Org 與兩個 ARIN POC 地址、網域 WHOIS 註冊人街道，以及公開聯絡地址——**而不動產紀錄顯示這是住宅**（[HAR](https://www.har.com/homedetail/257-westwood-dr-league-city-tx-77573/8020666)；[contact-us](https://www.databasemart.com/contact-us)）。**寄送實體郵件或臨門拜訪並不恰當** |
| **第三據點／歐洲存在 — 未解訊號** | 未知 | 未知 | 未知 | **自 2026-07-28 起**，AS401479 開始宣告兩組 RIPE 區域前綴：**93.127.128.0/20**（RIPE 物件名稱「Database_Mart_LLC」，ASSIGNED PA，機構 **ORG-DML16-RIPE**，維護者 **netutils-mnt**）與 **77.93.152.0/22**（RIPE 物件名稱 **「IPXO」**，SUB-ALLOCATED PA，登記人「Private Customer」）。`netutils-mnt` 維護者與「IPXO」物件名稱顯示這是**透過 IPXO 市集租來的位址空間**，不是他們自有的 RIPE 會員資格；兩個物件的國別碼都是 **US**。這是**近兩週內投入生產的額外 5,120 個 IPv4 位址**。它本身**並不**證明存在歐洲設施——租用的 RIPE 空間從美國據點宣告是常態——但與那個休眠 /18 併看，這是活躍的擴張訊號，應列為**平台問題之後的第二個資格問題**。[RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) · [RIPE RDAP 93.127.128.0](https://rdap.db.ripe.net/ip/93.127.128.0) · [RIPE RDAP 77.93.152.0](https://rdap.db.ripe.net/ip/77.93.152.0) |

**據點解讀：** 兩個生產據點，皆為租用，其中一個他們連位址都不持有。**沒有自有設施、沒有自有建物、沒有自營機房。** 這在商業上只有一個具體意義：**他們的每一項硬體決策，都受制於別人的每機櫃 kW 上限與別人的氣流設計**——這也正是第 14 節那個「先問電力額度、再談機殼」的問題之所以是對的問題。

---

## 6. 硬體機隊

本節證據等級：**CONFIRMED（確認）**＝第一手具名揭露或多方獨立佐證｜**CIRCUMSTANTIAL（情況證據）**＝行為指向強烈但從未具名廠商｜**INFERRED（推論）**＝僅由 CPU 腳位、平台世代或機殼形式推導｜**GAP**＝查無。

| 廠商／類別 | 證據等級 | 證據實際說了什麼 |
|---|---|---|
| **所有公開來源中，未具名任何伺服器原廠** | **GAP — 而且這是一次直接的負面測試，不是沒去查** | 已 grep [www.gpu-mart.com](https://www.gpu-mart.com/) 與 [www.databasemart.com](https://www.databasemart.com/) 的線上首頁，加上 `/gpu-specs`、`/about/`、`/about-us`，逐一比對 **Supermicro、Dell、Gigabyte、ASUS、Tyan、Inspur、Lenovo、HPE** 八個字串。**每一個字串的計數都是零。** 另以網路搜尋將兩個網域與這些廠商名稱配對，亦無任何提及這兩個網域的結果。他們的行銷文案用 NVIDIA 型號描述 GPU、用 Intel Xeon SKU 描述主機，**從不具名系統整合廠。本案不得將任何硬體廠商陳述為事實** |
| **Supermicro（或同世代 X10／X11 雙路 GPU 機殼製造商）** | **INFERRED — 明確地「未經確認」，絕不得向客戶表述為已知事實** | 推論鏈，攤開以供反駁：**(1)** 他們 26 個 SKU 的型錄中，每一個專用機種都跑在 Xeon E5 v3/v4、Gold 6148 或 Platinum 8160——2014-2017 年矽晶，已由其[定價頁](https://www.gpu-mart.com/gpu-dedicated-server)逐字轉錄驗證。**(2)** 旗艦機種明載 **「Dual E5-2697v4」** 搭一張雙寬 350W H100，另有 4× A100 與 4× RTX A6000 機種掛在 44 核雙路 E5 主機上。**(3)** 在那個世代，能在 4U 內承載三到四張雙寬 GPU 的雙路 E5-2600 v3/v4 主機板，**壓倒性地是 4028GR 系列機殼裡的 Supermicro X10DRG 級主機板**——該平台在二手市場上正是這種組態的主流。**(4)** 因此他們部分舊機隊由 Supermicro 打造的機率很高。**但是：**(a) 沒有任何來源這樣說；(b) 同樣的組態 Gigabyte、Tyan、ASUS 與白牌整合商都做得出來；(c) 二手市場買家會依價格機會主義地混搭機殼，因此**這批機隊很可能是異質的，而非單一廠牌**。**視為待在對話中檢驗的假說，絕不可當成主張** |
| **以二手／整新市場為採購通路**（相對於任何具名原廠） | **CIRCUMSTANTIAL — 強、多來源，但仍屬推論** | 四條互相獨立的線索收斂：**(1) 平台年齡** — 每一個公布的主機 CPU 都是 2014-2017 矽晶，**型錄裡完全沒有任何當世代主機**；會買新原廠整機的公司至少會有部分近期主機。**(2) 價格與硬體的算術** — 見第 10 節；以他們公布的 $2,099/月，一台全新卡片＋全新平台的 H100 機器無法在 24 個月內回收，因此經濟模型只有在「二手市場顯卡＋近乎零成本的舊主機」上才成立。**(3) 折扣深度集中在舊世代** — P100 **55% off**、A100 40GB **50% off**、RTX A4000 與 A5000 **50% off**、2× RTX 4090 **50% off**、RTX A6000 **40% off**——低價取得、積極出清。**(4) Gen5 卡插在 Gen3 平台上**，是「卡與主機分別從不同市場買來」而非「買一台經驗證整機」的典型跡象。**為求公允而記下的反證：** 他們**很早就進 Blackwell**（RTX PRO 6000 於 2025-11-08 上線，距上市僅數週），純靠二手市場很難做到，代表**在當世代顯卡上至少握有部分新品通路** |
| **NVIDIA** | **CONFIRMED（就機隊中的矽晶而言）；UNKNOWN（就商業關係而言）** | 公布型錄中的每一張 GPU 都是 NVIDIA 產品，從 Pascal P1000／P100 到 Blackwell RTX PRO 6000——已由其定價頁逐字轉錄確認。**未知的是：** 他們是透過 NVIDIA 合作夥伴通路、經銷、系統整合商，還是公開／二手市場採購。**其網站上看不到任何 NVIDIA Partner Network 資格、NVIDIA 品牌合作標章或經銷關係 — GAP** |
| **Psychz Networks（AS40676）與 Wholesale Internet, Inc.（AS32097）** | **CONFIRMED 為基礎設施供應商——但這些是主機代管／傳輸廠商，不是硬體廠商** | 列此僅為防止類別錯誤。[ARIN RDAP](https://rdap.arin.net/registry/ip/108.181.95.28) 確認 Psychz 持有 1515 Round Table Drive 的達拉斯 IP 空間。[RIPEstat](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) 確認 AS32097 是 AS401479 唯一的 BGP 鄰居，也是自 2021-01-30 起 Database Mart 自有 /22 的來源 AS。**兩者都不供應伺服器。兩者都不是這個客戶** |

### 6.1 最重要的單一技術發現

他們的旗艦產品頁（[gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting)，2026-08-11 讀取）逐字公布：一張 **NVIDIA H100 80GB HBM2e PCIe** 卡，掛在 **「36-Core Dual E5-2697v4」** 主機上，256GB RAM、240GB SSD ＋ 2TB NVMe ＋ 8TB SATA、**100Mbps 不限流量**、1 個專屬 IPv4，**月租 $2,099.00，24 個月約期**，狀態 **Available**。

依其自身證據，這裡有兩件事不對：

1. **PCIe 世代不匹配。** E5-2697v4 是 **2016 年推出的 Broadwell-EP** 產品，其平台（Intel C610／X10 世代雙路）**只提供 PCIe 3.0**。他們把一張 PCIe Gen5 的 H100 掛在 Gen3 root complex 上——該卡會降速協商到 **Gen3 x16，約為其設計主機頻寬的四分之一**。而該產品頁**同時在卡片規格欄標示「PCIe Gen5」，卻列出一顆做不到的 CPU 世代。**
2. **匯入頻寬。** 在一台 $2,099/月的 AI 機種上給 **100Mbps 不限流量**，對訓練或資料集備置而言是極細的管線。

兩點都能從他們自己公布的頁面驗證，因此是**安全、不會冒犯人的開場**——你是在引用他們自己的資料，不是在指控他們。

### 6.2 觀察到的 CPU 世代，以及對機隊年齡的意涵

直接讀自其公開販售的平台組合（屬**由公布組態推導的 INFERRED 平台世代證據**，非廠商揭露）：

- **26 個專用機種的全部主機 CPU：** Intel Xeon **E5 v3/v4**（2014–2016 Haswell／Broadwell）、Xeon **Gold 6148**（2017 Skylake-SP）、Xeon **Platinum 8160**（2017 Skylake-SP）。**清單到此為止。**
- **零個當世代主機平台**——型錄中任何位置都沒有 Ice Lake、Sapphire Rapids、Emerald Rapids、Granite Rapids，也沒有任何世代的 EPYC。
- **涵蓋的 GPU 世代：** Pascal（Quadro P1000、Tesla P100）、Turing（GTX 1650／1660、RTX 2060）、Ampere（RTX 3060 Ti、RTX A4000／A5000／A6000、A40、A100 40／80GB）、Ada（RTX 4060、RTX 4090）、Hopper（H100 80GB）、Blackwell（RTX 5060、RTX 5090、RTX PRO 2000／4000／5000／6000）。
- **推得之機殼形式：** 4U 級多 GPU 機殼（4× A100 40GB、4× RTX A6000、3× V100、3× RTX A5000、2× RTX 5090）與單 GPU 的 2U／4U 主機。

**這代表什麼：** 這批機隊在世代上**攔腰切開——新卡配老主機。** 他們積極換 GPU，卻**從不**換底下的平台。這是「BOM 中 90–95% 是 GPU、主機幾乎免費」（第 10 節）這種營運者的典型特徵，也代表 Supermicro 的實際切入點是**專門針對 Blackwell 層的當世代 PCIe Gen5 GPU 平台**——而不是全機隊更換，那在他們的數字上無法成立。

---

## 7. GPU 型錄與 AI 佈局

**已確認、規模可觀、且正積極經營。** Database Mart 以獨立品牌 gpu-mart.com 銷售 GPU 主機，共三個產品族：**專用 GPU 伺服器（26 個公開 SKU）**、**GPU VPS（8 個層級）**，以及旗艦零件的**型號專屬到達頁**。以下所有 SKU 皆於 **2026-08-11** 自線上型錄逐字轉錄。

### 7.1 專用 GPU 伺服器——全部 26 個 SKU，每一個都附價格

| SKU（GPU · 主機平台） | 月租 | 狀態 | 來源 |
|---|---|---|---|
| **NVIDIA H100 80GB HBM2e PCIe** — 36-Core Dual E5-2697v4、256GB RAM、240GB SSD ＋ 2TB NVMe ＋ 8TB SATA、100Mbps 不限流量、1 個專屬 IPv4 · **24 個月約期** | **$2,099.00** | Available | [/h100-hosting](https://www.gpu-mart.com/h100-hosting) |
| **4× NVIDIA A100 40GB** — 44-Core Dual E5、512GB RAM | **$1,899.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA A100 80GB HBM2e** — 36-Core Dual E5、256GB RAM | **$1,559.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **4× NVIDIA RTX A6000 48GB** — 44-Core Dual E5、512GB RAM | **$1,199.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **3× NVIDIA RTX A6000 48GB** — 36-Core Dual E5、256GB RAM | **$899.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **2× NVIDIA RTX 5090 32GB GDDR7** — 44-Core Dual E5、256GB RAM | **$859.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **3× NVIDIA RTX A5000 24GB** — 36-Core Dual E5、256GB RAM | **$539.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 5090 32GB GDDR7** — 36-Core Dual E5、256GB RAM | **$479.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **3× NVIDIA V100 16GB HBM2** — 36-Core Dual E5、256GB RAM | **$469.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **2× NVIDIA RTX 4090 24GB GDDR6X** — 36-Core Dual E5、256GB RAM · **50% OFF**（推得原價 $899.00） | **$449.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA A40 48GB GDDR6** — 36-Core Dual E5、256GB RAM | **$439.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 4090 24GB GDDR6X** — 36-Core Dual E5、256GB RAM | **$409.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA A100 40GB HBM2** — 36-Core Dual E5、256GB RAM · **50% OFF**（推得原價 $799.00） | **$399.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX A6000 48GB GDDR6** — 36-Core Dual E5、256GB RAM · **40% OFF**（推得原價 $549.00） | **$329.40** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA V100 16GB HBM2** — 24-Core Dual E5、128GB RAM | **$229.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 3060 Ti 8GB GDDR6** — 24-Core Dual E5、128GB RAM | **$179.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 2060 6GB GDDR6** — 40-Core Dual Gold、128GB RAM | **$179.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX A5000 24GB GDDR6** — 24-Core Dual E5、128GB RAM · **50% OFF**（推得原價 $349.00） | **$174.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 2060 6GB GDDR6**（Professional 層） — 16-Core Dual E5、128GB RAM · **20% OFF** | **$159.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 5060 8GB GDDR7** — 24-Core Platinum 8160、64GB RAM | **$159.00** | Available | [/nvidia-blackwell-gpu-server](https://www.gpu-mart.com/nvidia-blackwell-gpu-server) |
| **NVIDIA RTX 4060 8GB GDDR6** — 8-Core Xeon、64GB RAM | **$149.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX A4000 16GB GDDR6** — 24-Core Dual E5、128GB RAM · **50% OFF**（推得原價 $279.00） | **$139.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA GTX 1660 6GB GDDR5** — 16-Core Dual E5、64GB RAM | **$139.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA GTX 1650 4GB GDDR5** — 8-Core Xeon、64GB RAM | **$99.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA Tesla P100 16GB HBM2** — 16-Core Dual E5、128GB RAM · **55% OFF**（推得原價 $199.00）— **全型錄最深折扣** | **$89.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA Quadro P1000 4GB GDDR5** — 8-Core Xeon、32GB RAM — **最便宜的專用 GPU 機種** | **$64.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |

### 7.2 GPU VPS 層級——全部 8 個，每一個都附價格

| 層級 | 月租 | 來源 |
|---|---|---|
| **NVIDIA RTX PRO 6000 96GB GDDR7（ECC）** — Enterprise GPU VPS，32 核、84GB RAM、400GB SSD、1000Mbps 不限流量 | **$479.00** | [/rtx-pro-6000-hosting](https://www.gpu-mart.com/rtx-pro-6000-hosting) · [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX 5090 32GB GDDR7** — Advanced GPU VPS，32 核、84GB RAM、400GB SSD · **35% OFF** | **$291.85** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX PRO 5000 48GB GDDR7（ECC）** — Advanced GPU VPS，24 核、56GB RAM、320GB SSD | **$269.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX PRO 4000 24GB GDDR7（ECC）** — Advanced GPU VPS，24 核、56GB RAM、320GB SSD | **$159.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX A4000 16GB** — Professional GPU VPS，24 核、28GB RAM、320GB SSD | **$119.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX PRO 2000 16GB GDDR7** — Professional GPU VPS，16 核、28GB RAM、240GB SSD | **$99.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX 5060 8GB GDDR7** — Basic GPU VPS，16 核、28GB RAM、240GB SSD | **$85.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA GT730 / P600 / K620 2GB DDR3** — Express GPU VPS，8 核、16GB RAM、120GB SSD · **50% OFF**（推得原價 $29.00）— **他們販售的最便宜 GPU 產品** | **$14.50** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |

### 7.3 AI 佈局解讀

**這就是目前活躍的採購戰線。** 六個 Blackwell SKU 在 **2025 年 11 月至 2026 年 4 月**之間，從完全不存在變成完整上架。其中 RTX PRO 6000 是一張 **600W 級、PCIe Gen5、96GB GDDR7** 的卡——是他們整份型錄中最難在 2016 年份雙路 E5 平台上正確運作的零件，**供電與主機頻寬兩方面都是。**

**請注意那張卡的價格軌跡。** 專用機種的 RTX PRO 6000 頁面在 **2025-11-08 的月租是 $729.00**（[Wayback 存檔](https://web.archive.org/web/20251108102809/https://www.gpu-mart.com/rtx-pro-6000-hosting)）；到 2026-08-11，**96GB 的 VPS 層級是 $479.00/月**——約九個月內下降約 34%。**毛利正在被壓縮，而他們還在買。** 這會改變他們在乎的東西：**每機櫃 U 數與每 kW 的效率，開始壓過機殼資本支出。**

**折扣深度作為機隊年齡指標。** 折扣最深的 SKU 恰好都是 Pascal／Turing／Ampere 世代——P100 55% off、A100 40GB 50% off、RTX A4000 與 A5000 50% off、2× RTX 4090 50% off、RTX A6000 40% off。A100 40GB 機種掛著 50% 常態折扣，是一個強烈訊號：**這個世代在他們帳上正快速折舊，舊庫存正在出清。**

**他們自家產品線的缺口，值得在電話前先知道：** 他們**沒有 H200**、**沒有 L40S**、**沒有資料中心級 Blackwell（B200／GB200）**、**沒有 AMD Instinct**。兩個明顯的剩餘缺口是資料中心級 Blackwell 與 H200——任何一個都會是新平台採購，不是換卡而已。

---

## 8. 採購時鐘

Database Mart 實際多久買一次，以其自家公開型錄、自家帶日期的新聞稿，以及登錄機構／BGP 時間戳重建。

### 8.1 事件時間軸（依日期）

| 日期 | 事件 | 類型 | 來源 |
|---|---|---|---|
| **2004-11-16** | **databasemart.com 註冊**（RDAP 建立日）——比德州設立早兩個月 | 起源 | [Verisign RDAP](https://rdap.verisign.com/com/v1/domain/databasemart.com) |
| **2005-01-13** | **德州 SOS 設立** — DATABASE MART LLC，檔案號 0800439627 | 起源 | [Texas Comptroller](https://data.texas.gov/resource/9cir-efmm.json) |
| **2020-06** | 公司新聞稿 **「Database Mart LLC Launches Dedicated GPU Server Hosting」**——**首次擁有 GPU 容量** | **採購事件** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| **2020-07-31** | ARIN POC **ADMIN7533-ARIN** 登記 | 容量 | [ARIN](https://whois.arin.net/rest/poc/ADMIN7533-ARIN.json) |
| **2020-08-03** | ARIN 將 **163.123.180.0/22**（1,024 個位址，DBM-NET-01）登記給 Database Mart LLC | **容量事件** | [ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json) |
| **2021-01-30** | **163.123.180.0/22 首次由 AS32097 對外宣告**——堪薩斯城生產環境上線 | 容量 | [RIPEstat routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=163.123.180.0/22) |
| **2021-11-15** | **gpu-mart.com 註冊**（RDAP 建立日）——GPU 品牌分拆 | 品牌 | [Verisign RDAP](https://rdap.verisign.com/com/v1/domain/gpu-mart.com) |
| **2023-01** | 新聞稿 **「Expands GPU Hosting Offerings」**——「4 new dedicated GPU server offerings and 1 GPU VPS offering」（GTX 1650、GTX 1660、RTX 2060、RTX 3060 Ti） | **採購事件** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| **2023-02-08** | **/rtx-a6000-hosting** 首次 Wayback 存檔 | **採購事件**（定年錨點） | [web.archive.org](https://web.archive.org/web/20230208000000*/gpu-mart.com/rtx-a6000-hosting) |
| **2023-06-04** | 型錄快照顯示 **12 個 GPU 型號**：A100、A40、V100、P1000、A6000、A5000、A4000、4090、3060、2060、1660、1650 | 基準 | Wayback 型錄快照 |
| **2023-07** | 公司新聞 **「Network and Power Issue in Kansas Data Center」**——獨立佐證堪薩斯城有線上生產環境 | 營運 | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| **2023-11-13** | 型錄快照中首次出現 **RTX 4060**（2023-06-04 尚無） | **採購事件** | Wayback 型錄快照 |
| **2024-03-05** | **/nvidia-a100-rental** 首次 Wayback 存檔 | 定年錨點 | Wayback CDX |
| **2024-05-22** | 型錄快照中首次出現 **Tesla P100**（2023-12-07 尚無） | **採購事件** | Wayback 型錄快照 |
| **2024-11-07** | ARIN 將 **AS401479「DBM-ASN-KC」** 登記給 Database Mart LLC | **容量事件** | [ARIN asns](https://whois.arin.net/rest/org/DML-132/asns.json) |
| **2024-12-22** | **/rtx-5090-hosting** 首次 Wayback 存檔——頁面在 RTX 5090 上市時點或稍早建立 | **採購事件** | Wayback CDX |
| **2025-02-13** | **/h100-hosting** 首次 Wayback 存檔 | **採購事件** | Wayback CDX |
| **2025-06-16** | 型錄快照已帶有 **H100、RTX 5090、RTX 5060**（2024-05-22 三者皆無） | 確認 | Wayback 型錄快照 |
| **2025-11-08** | **/rtx-pro-6000-hosting 上線，月租 $729.00**，帶「Order Now」按鈕——**Blackwell 工作站級進入機隊** | **採購事件——本波段起點** | [Wayback 2025-11-08](https://web.archive.org/web/20251108102809/https://www.gpu-mart.com/rtx-pro-6000-hosting) |
| **2026-01-12** | **/rtx-pro-4000-blackwell** 與 **/rtx-pro-5000-blackwell** 首次存檔 | **雙採購事件** | Wayback CDX |
| **2026-01-16** | **/rtx-pro-2000-blackwell** 首次存檔 | **採購事件** | Wayback CDX |
| **2026-01-21** | **ARIN 將 38.247.128.0/18——16,384 個位址——登記給 Database Mart LLC**（Cogent 38.0.0.0/8 之下的 ALLOCATION，網路名 DATABASEMART-CGNT-NET-1） | **重大容量承諾——而且至今未路由** | [ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json) · [RIPEstat routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=38.247.128.0/18) 顯示 **326 個 RIS peer 中 0 個可見**、無來源 AS、無首見日期 |
| **2026-04-19** | **/nvidia-blackwell-gpu-server 入口頁首次存檔**；型錄快照顯示 RTX PRO 6000 與 H100 並列 | **最後一次確認的硬體／型錄事件** | Wayback CDX |
| **2026-07-28** | AS401479 開始宣告租用的 RIPE 前綴 **93.127.128.0/20** 與 **77.93.152.0/22**——**5,120 個位址上線** | **容量事件——本檔完成前兩週** | [RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) |

### 8.2 採購節奏

**兩種明顯不同的節奏。**

**(1) 穩態——2023–2025 年間，每約 4–6 個月一次的漸進式 SKU 增補：**

| 從 → 到 | 間隔 |
|---|---|
| RTX 4060（2023-11）→ P100（2024-05 前） | 約 6 個月 |
| P100（2024-05）→ RTX 5090 頁（2024-12） | 約 7 個月 |
| RTX 5090 頁（2024-12）→ H100 頁（2025-02） | 約 2 個月 |
| H100 頁（2025-02）→ 型錄中出現 RTX 5060 ＋ H100（2025-06 前） | 約 4 個月 |

**(2) 世代換代衝刺期——明顯更快：**

| 從 → 到 | 間隔 |
|---|---|
| RTX PRO 6000（2025-11-08）→ RTX PRO 4000 ＋ 5000（2026-01-12） | **2.2 個月** |
| RTX PRO 4000／5000（2026-01-12）→ RTX PRO 2000（2026-01-16） | **0.1 個月** |
| RTX PRO 2000（2026-01-16）→ Blackwell 入口頁（2026-04-19） | **3.1 個月** |

**約五個月內推出四個 Blackwell SKU——世代轉換期的節奏是約 2–3 個月，相對於穩態的約 5 個月。Blackwell 轉換大致讓他們的採購節拍加倍，而且還在進行中。**

### 8.3 最後事件與下一個窗口

**最後一次確認的硬體／型錄事件：2026-04-19** — `/nvidia-blackwell-gpu-server` 入口頁首次 Wayback 存檔，整併 RTX PRO 2000／4000／5000／6000 與 RTX 5090／5060 產品線。

**最後一次任何類型的容量事件：2026-07-28** — AS401479 開始宣告 5,120 個租用 IPv4 位址。

**尚未消化的存量：** **2026-01-21 登記、至今仍未對外宣告的 16,384 個位址 /18**（326 個 RIS peer 中 0 個可見）。

> ### 下一個窗口推估：**2026 年 9–12 月，機率最高落在 2026 年 10–11 月**

**推理。** 最後一次型錄事件是 2026 年 4 月，而觀察到的穩態間隔為 4–6 個月，光憑這點就指向 8–10 月。三項因素把推估往後推，而且讓它**更確定而不是更早**：

1. **2026-07-28 的 IP 啟用代表網路容量剛剛備妥**，而這家公司的位址備置一貫略早於節點部署。
2. **16,384 個已購但未路由的位址，是已經付過錢的容量承諾，必須被填滿才能回本。**
3. **Blackwell 轉換仍在半途**，而他們產品線上兩個明顯的剩餘缺口是資料中心級 Blackwell 與 H200，兩者目前都沒賣。

**在 2026 年 8 月底／9 月初做第一次接觸，會落在該窗口之前而不是之中——那正是你要的位置。**

### 8.4 方法——如實說明，含其限制

**主要技巧：** 對 gpu-mart.com 的 URL 執行 Wayback Machine **CDX 窮舉**，以 GPU 型號字串（`h100`、`5090`、`6000`、`a100`、`blackwell`、`l40`）過濾，取每個型號專屬到達頁的**最早存檔時間戳**作為定年錨點。輔以抓取 `/gpu-dedicated-server` 在 2023-06 至 2026-04 之間的 **18 份原始（`id_`）快照**，對去標籤後的文字以 **26 組 GPU 型號正規表示式**比對，建立每個日期的存在／缺席狀態。並與公司自家帶日期的新聞稿（[portal.databasemart.com/news/](https://portal.databasemart.com/news/)）以及 ARIN／RIPE 登記與 BGP 宣告時間戳交叉查核。

**三項重要限制：**

1. **Wayback 首次存檔日是「最晚可能日」，不是真正的上線日。** 爬取覆蓋稀疏且不規則，因此真實的頁面發布日**等於或早於**所示時間戳，有時早數週。
2. **頁面發布本身又是採購決策的落後代理指標。** 硬體要先訂購、交貨、上架、燒機，產品頁才會上線，因此**實際採購單通常比定年錨點早約一到三個月**。兩項偏誤方向相同，代表**真實採購日比上表更早，推導出的節奏若有偏差也是偏保守。**
3. **18 份型錄快照中有 7 份回傳零命中**（2024-01-18、2024-09-15、2024-11-27、2024-12-22、2025-11-26、2026-01-11、2026-02-08），原因是存檔回應是 JS 外殼或壓縮／亂碼的擷取。**那些日期屬於「缺乏證據」，不是「證據顯示不存在」**；已用型號專屬到達頁錨點橋接，但採購節奏承擔該不確定性。

**信心度：** **Medium-high** — 2025-11 至 2026-04 的 Blackwell 衝刺（四個獨立到達頁錨點、間隔緊密、且由包含全部六個 SKU 的線上型錄佐證）。**Medium** — 2023–2025 的穩態節奏（存檔覆蓋較薄、數個缺口靠橋接）。**Medium** — 前瞻窗口，其依據是「先備位址、再部署」的模式，該模式已成立兩次，但不是定律。

---

## 9. UCC 融資紀錄

**本軌研究範圍：** DATABASE MART LLC — 德州本土 LLC，SOS 檔案號 **0800439627**、納稅編號 **32107118534**、登記地址 257 Westwood Dr, League City, TX 77573。**就 UCC-1 而言，設立州為德州**（Comptroller 組織型態代碼 **CL** ＝德州本土 LLC），因此**德州州務卿是正確且唯一的中央申報機關——德拉瓦州不適用。** 不存在兄弟 debtor 實體：登記資料庫對 CLOUD CLUSTERS、VPS MART、SERVER MART、GPU MART、WINPC 的萬用字元搜尋皆回傳「（無紀錄）」。

### 9.1 判定

> ### UNVERIFIED — portal blocked

**請完全照字面理解。** **未取得任何 UCC 申報紀錄，且從未有任何 debtor 名稱查詢真正送進德州任何一套 UCC 系統**——每一次嘗試都在到達搜尋欄位之前，就卡在驗證層或路由層。§9.2 的空白代表**什麼都沒看到**，**不代表** Database Mart 沒有擔保債務。**此結果不得對客戶陳述、不得引用給徵信單位、也不得以「查無留置權」寫入 CRM。** 此處的阻擋是**程序性的，不是資產負債表乾淨的證據**。

### 9.2 已在案之申報——每筆完整列出

**取得之申報筆數：0。**

以下沒有任何申報區塊，因為**沒有任何一個查詢面回傳過任何申報**。此處沒有壓縮、簡寫或省略任何內容——登記簿根本未曾被觸及。因此，徵信或通路決策所需的每一個申報欄位，都是明確的 GAP：

| 每筆申報所需欄位 | `DATABASE MART LLC` |
|---|---|
| 申報號碼（filing number） | **GAP — 登記簿未曾觸及** |
| 申報日期（filing date） | **GAP — 登記簿未曾觸及** |
| 失效日／續期狀態（lapse／continuation） | **GAP — 登記簿未曾觸及** |
| Secured party 名稱與地址 | **GAP — 登記簿未曾觸及** |
| Debtor 申報名稱與地址 | **GAP — 登記簿未曾觸及** |
| 擔保品描述（逐字原文） | **GAP — 登記簿未曾觸及** |
| 修正／讓與／終止（amendments／assignments／terminations） | **GAP — 登記簿未曾觸及** |
| 紀錄連結 | **GAP — 登記簿未曾觸及** |

**上述欄位只能靠德州州務卿的 UCC-11 debtor 查詢取得**，須經 SOSDirect 訂戶帳號或商業留置權查詢廠商辦理。查詢精確字串 **`DATABASE MART LLC`**，並以未加後綴的 **`DATABASE MART`** 做第二輪，以捕捉變體登記。

### 9.3 查詢紀錄——四次嘗試，一次一列，不合併

| 入口／URL | 使用的查詢字串 | 逐字回應 | 受阻時的替代路徑 |
|---|---|---|---|
| **[Q1] Texas SOS — UCC 專區首頁** · [sos.state.tx.us/ucc/index.shtml](https://www.sos.state.tx.us/ucc/index.shtml) | 無（勘查——尋找搜尋介面） | **HTTP 200。** 回傳頁面文字：*「…for under the Uniform Commercial Code and certain other lien notice statutes. All accepted documents are processed, recorded, filed, and made available to the public upon request through SOS Portal.」* 另帶常駐公告：*「Technical Notice: Various applications including SOSDirect and SOSUpload are experiencing intermittent issues and are actively being addressed.」* **此頁未提供任何搜尋介面。** | 依該頁自身指引前往「SOS Portal」（於 Q4 嘗試）或 SOSDirect（Q3）。 |
| **[Q2] Texas SOS — 直接探測 UCC debtor 搜尋端點** · [direct.sos.state.tx.us/ucc/ucc-search.asp](https://direct.sos.state.tx.us/ucc/ucc-search.asp) | 直接嘗試 UCC debtor 名稱搜尋端點 | **HTTP 404**，最終 URL 未變。內容：*「404 - File or directory not found. Server Error 404 - File or directory not found. The resource you are looking for might have been removed, had its name changed, or is temporarily unavailable.」* | 此路徑不存在匿名 UCC 搜尋。轉往驗證閘門（Q3）。 |
| **[Q3] Texas SOSDirect — UCC 索引前方的閘門** · [direct.sos.state.tx.us/acct/acct-login.asp](https://direct.sos.state.tx.us/acct/acct-login.asp) | 無（此為登入閘門；預定送出的 debtor 字串 `DATABASE MART LLC` 從未被送出） | **HTTP 200。** 內容原文：*「DIRECT ACCESS SUBSCRIBER LOGIN — TEXAS SECRETARY of STATE — ROBERT S. HOWDEN — UCC | Business Organizations | Trademarks | Notary — Account | Help/Fees | Briefcase | Login — SOSDirect Account Login … reenter your SOSDirect USER ID and PASSWORD and click Submit to begin.」* **這是需付費、需建立帳號與憑證的訂戶系統。未建立任何帳號、未輸入任何憑證——代客戶建立帳號與輸入憑證，不在可執行範圍內。** | **由業務專員或徵信單位以 SOSDirect 訂戶帳號操作**，或委由商業留置權查詢廠商。這是進入德州 UCC 索引的唯一途徑。 |
| **[Q4] 德州「SOS Portal」後繼主機名** · [sosportal.sos.texas.gov](https://sosportal.sos.texas.gov/) 與 [businessfilings.sos.texas.gov](https://businessfilings.sos.texas.gov/) | 嘗試 Q1 文字中所指、作為新公開存取路徑的「SOS Portal」 | **curl 以 HTTP 000 結束（未連上任何德州 SOS 伺服器）。** 沙箱網路路徑回傳的內容是一個不相關的第三方 404 頁（*「Not Found | Hydra Host For AI Platforms … © 2026 Hydra Host, Inc.」*），亦即**這些主機名在本環境中根本未解析到任何德州 SOS 端點。** 另外 [sos.state.tx.us/ucc/forms/index.shtml](https://www.sos.state.tx.us/ucc/forms/index.shtml) 回傳 **HTTP 403**，內容為 *「Sorry, but the requested file was not found」*。 | 由真人以一般網路環境的瀏覽器重試；否則退回 SOSDirect（Q3）或商業廠商。 |

**淨結果：德州 UCC 索引只能經 SOSDirect 付費訂戶登入抵達，而該登入未被突破。** 要結案，請對精確字串 `DATABASE MART LLC`，並以未加後綴的 `DATABASE MART` 做第二輪，執行德州州務卿 **UCC-11 debtor 查詢**。

### 9.4 這個受阻結果允許與不允許推論的事

**它不允許就其融資做任何推論。** 我不能說他們沒有負債，也不能說他們有負債。但周邊證據支持一個相當有力、**應由 UCC 查詢去「檢驗」而不是被其取代的獨立假說**：這看起來像一家**以現金與營運現金流支應、而非以設備融資支應**的公司。

| 觀察 | 意涵 | 信心度 | 對銷售的後果 |
|---|---|---|---|
| **連續營運 21 年，無任何在案外部募資** — [Crunchbase](https://www.crunchbase.com/organization/database-mart) 完全沒有募資資料 | 自籌成長；沒有投資人治理層；看不到放款人加諸的財務約定 | **中** — Crunchbase 沒有紀錄本身是弱證據，但與其他一切一致 | 若獲確認，**不需放款人同意、沒有債權人間協議摩擦**——直接付款條件變得單純 |
| **所有權人自營的 LLC，以創辦人住宅為登記地址** — 典型的「再投資而非舉債」型企業樣態 | 強化自籌資金的讀法 | **中** — 由結構推論，非申報所證 | 買方花的是自己的錢，這正是第 10 節成本天花板算術具有拘束力、而非參考性的原因 |
| **機隊組成** — 以 2014-2017 年主機平台為主，搭配折扣極深的上一代 GPU。**買二手、並把設備用過其可融資年限，正是付現金的公司會做的事**，因為放款人一般不會對那種年份的二手市場硬體放款 | 就舊機隊而言，指向「非設備融資」 | **中高** — 平台年齡證據直接轉錄自其自家型錄 | 不要圍繞舊機層設計租賃／原廠融資訴求，不會有共鳴 |
| **成本天花板算術（第 10 節）** 顯示他們公布的租金**無法支應新硬體的新設備融資** | 要嘛買便宜付現金，要嘛以遠長於 24 個月的期間攤提 | **中高** — 由其自家公布價格推導的算術 | 槓桿在價格與組態，而不在融資結構——**除非**查詢揭露近期有放款人 |
| **反向證據，也是這次查詢仍然重要的原因：** **2025 年 11 月至 2026 年 4 月的 Blackwell 衝刺**，加上 **2026 年 1 月買下的 16,384 位址 /18**，代表真金白銀正在快速流出——而 **RTX PRO 6000 96GB 機隊，正是放款人「會」融資的那種當世代、高殘值資產** | 若存在 UCC-1，最可能是**近期的（2025-2026）** | **中** — 商業推理，非已目視之申報 | **secured party 的身分會極具資訊價值。** 若是銀行或設備融資租賃商，代表他們**有信用額度、也有能吸收更大平台訂單的採購流程**。若是 GPU 中盤或整合商就特定顯卡設定**購買價金擔保權益**，代表他們**受原廠／通路融資綁定、實質為通路俘虜**，整個接觸策略都要改 |

**上述任何一點都不得對客戶表述為事實。**

---

## 10. 成本天花板

每台機器對 Database Mart 能值多少錢，以及同一台機器今天要花多少錢造出來。

### 10.1 假設——請先讀這一段；這些是假設，不是查證發現

**本節每一個數字都由「一個公開價格 ＋ 明列假設」推導而來，任何面向客戶的使用都必須如此標示。**

- **錨點（查證所得，非假設）：** 旗艦 H100 80GB 機種標價 **$2,099.00/月，24 個月約期**（[gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting)，2026-08-11 讀取）。
- **假設 1 — 實收營收為標價的 75–85%**，反映其自家型錄中可見的促銷折扣（八個 SKU 掛著 20–55% 常態折扣）與不完美的使用率 → **實收 $1,574–$1,784/月**。*由其自家公布折扣的深度與廣度推得；並非公司提供。*
- **假設 2 — 營運成本佔實收營收的 35–50%**，涵蓋租用機房空間與電力、IP 傳輸、IPv4、作業系統／控制台授權、24/7 支援人力、金流手續費與流失 → 剩下 **每月 $787–$1,160 的貢獻**可用於支應硬體。*一般主機業界的工作假設；**並非**公司提供，也**未經**查證。他們實際的機房、電力與傳輸成本未知 — GAP。*
- **假設 3 — 回收期取 12／18／24 個月**，依原始需求設定。*他們實際的門檻報酬率、折舊年限與持有期未知 — GAP。請注意 H100 SKU 的 24 個月約期，以及 2016 年份主機至今仍在產生營收，兩者都暗示他們以**更長**的期間攤提，那會**拉高**天花板。*
- **已確認、非假設：** 旗艦機種為單卡——讀自其公布規格。
- **刻意寬鬆：** 100% 的貢獻全數用於硬體回收，**不提列任何管銷、稅負或利潤**。這使天花板成為**上界**；務實的天花板會更低。
- **未納入模型：** 忽略多 GPU 機種——在那些機種上固定主機成本會分攤到 3–4 張卡，單卡經濟性顯著改善。**他們的 4× A100（$1,899/月）與 4× RTX A6000（$1,199/月）正是「更好的機殼最快回本」的 SKU**——這是可以帶進對話的有用論據。

### 10.2 由租金推導之硬體預算天花板——旗艦 H100 機種

| 回收期 | 每台機器硬體預算天花板 |
|---|---|
| **12 個月** | **$9,400 – $13,900** |
| **18 個月** | **$14,200 – $20,900** |
| **24 個月** | **$18,900 – $27,800** |

**區間紀律：** 以 **24 個月回收期下的 $19K–$28K／台**作為整機硬體支出的外緣，並假設 **GPU 佔掉其中 90–95%**。

### 10.3 商業上具決定性的一點

**單一張全新 H100 PCIe 卡，在 2026 年美國街頭價就要 $25,000–$30,970**（見下方 BOM），這還不含任何主機、記憶體、儲存、機殼或滑軌。

**因此，一台全新卡片＋全新平台的 H100 機器，在他們自己公布的租金下無法在 24 個月內回收，在 12 或 18 個月更是差得遠。** 把同樣的檢驗套在 $479/月 VPS 定價的 RTX PRO 6000 96GB 上，只會更緊。

**結論（推論，並如此標示）：他們的單機經濟只有在「二手市場或深度折扣顯卡 ＋ 近乎零成本的舊主機」上才成立——而這正是他們公布的 Dual E5-2697v4 規格所顯示的做法。任何 Supermicro 提案都必須先撐過這個限制。**

### 10.4 旗艦機種的 BOM 重建

**依公布內容的「Enterprise Dedicated GPU Server, H100」：** 1× H100 80GB HBM2e PCIe ＋ Dual Xeon E5-2697v4（合計 36 核）＋ 256GB RAM ＋ 240GB SSD ＋ 2TB NVMe ＋ 8TB SATA。

| # | 項目 | 說明 | 價格 | 狀態 |
|---|---|---|---|---|
| **1** | **H100 80GB PCIe** | **已取得來源。** 截至 **2026 年 3 月**，美國全新街頭價 $25,000–$30,970，部分供應商在缺貨時報 $30,000–$38,000。整新品 **$21,000–$34,000**；非整新二手 **$15,000–$28,000** | **$25,000 – $30,970（全新）** | **已取得來源** |
| **2** | Dual E5-2697v4 CPU 一對 | Broadwell-EP，2016 年推出，早已 EOL，**僅二手市場** | **未獨立取價** | **GAP** |
| **3** | 256GB DDR4 ECC RDIMM | 二手市場 | **未獨立取價** | **GAP** |
| **4** | 4U 雙路 E5 GPU 機殼含電源與滑軌 | X10DRG 級，二手市場 | **未獨立取價** | **GAP** |
| **5** | 240GB SSD ＋ 2TB NVMe ＋ 8TB SATA ＋ 網卡 | 二手市場 | **未獨立取價** | **GAP** |

**即使有這些缺口仍然成立的結構性結論：** 項目 2–5 全是**早已 EOL 的二手市場零件，其合計成本相對項目 1 微不足道**。**GPU 約佔整機 BOM 的 90–95%，主機平台實質上是免費的。**

**Supermicro 對照。** 一台**全新**的同等 Supermicro 系統——**SYS-421GE／AS-4125GS** 家族的當世代 4U／5U PCIe GPU 平台，搭配當世代雙路 Xeon 或 EPYC、256GB 與一張 H100 PCIe——**GPU 成本完全相同**，但會把一台近乎免費的舊主機換成當世代、PCIe Gen5、散熱設計正確的平台。

**此處不報 Supermicro 牌價。** 本次未取得任何 Supermicro 組態器或代理商報價，憑空編一個數字比留白更糟。**GAP — 在任何客戶對話之前，請先拉一份實際組態報價。**

### 10.5 誠實的判讀

**在同規格取代他們現有 H100 機種這件事上，Supermicro 在價格上會輸，而且贏不了純資本支出比較，因為在位主機的成本只有幾百美元。**

**這場比較只有在 Blackwell 機種上才會變得可勝——那裡的舊平台在物理上無法提供 PCIe Gen5，也無法承受 600W 級的散熱與供電範圍。** 見第 14 節。

### 10.6 依層級的 Supermicro 平台對照

| 他們的層級 | 他們目前在跑的（推論） | 建議提出的當代 Supermicro 對應 | 商業判定 |
|---|---|---|---|
| **Blackwell RTX PRO 6000／5000／4000／2000、RTX 5090** | 2016 年雙路 E5、PCIe Gen3、散熱設計未知 | **Blackwell 世代 PCIe GPU 平台——能承載多張 600W 雙寬卡、每插槽 PCIe Gen5 x16 的 4U／5U 工作站暨伺服器 GPU 系統** | **這就是商業上真正要緊的對照。** 以下各項都只是防守 |
| **H100 80GB 單卡** | 等同 Supermicro 4028GR-TR／X10DRG-Q 級 4U（EOL，二手市場） | SYS-421GE／AS-4125GS 家族 4U／5U PCIe GPU 系統，或密度取向的 2U SYS-221GE 級 | **今天在資本支出上會輸。** 只有與 Blackwell 對話綁在一起才有機會 |
| **4× A100 40GB／4× RTX A6000／3× A6000／3× A5000／2× RTX 5090** | 舊雙路 E5 機殼上的約 2kW 節點——在租用籠內是實實在在的電力與氣流問題 | Supermicro 4U 8–10 張 PCIe GPU 平台（SYS-420GP-TNR 家族與後繼）或 AS-4125GS 產品線 | **攤提故事最好的一層。** 固定主機成本分攤到 3–4 張卡；專用機殼在這裡最快回本 |
| **A100 40GB、RTX A6000、A40、V100、RTX 4090 及以下** | 舊世代、深度折扣、快速折舊 | **此處沒有 Supermicro 新機生意** | 僅作為換代壓力的證據 |

---

## 11. 客戶與網路

### 11.1 已具名客戶

**沒有。零具名客戶、零客戶標誌牆、零案例研究、零指名客戶的新聞稿。** 這是**刻意記錄的負面發現**，不是研究疏漏。

| 關係 | 等級 | 來源實際說了什麼 |
|---|---|---|
| **未辨識到任何具名客戶** | **硬性 GAP——但屬於結構上預期之內** | [databasemart.com](https://www.databasemart.com/)、[gpu-mart.com](https://www.gpu-mart.com/) 與 [portal.databasemart.com/news/](https://portal.databasemart.com/news/) 上皆無標誌牆、無案例研究、無具名參考頁、無指名客戶的新聞稿。搜尋案例研究與論壇提及，只回傳評論聚合網站。**這與其商業模式完全一致：** 一家自助式、刷卡、即時開通、月費從 **$14.50 到 $2,099** 賣給個人開發者與中小企業的主機商，本來就不會有具名企業參考客戶。**不必期待找到**，也不要去挖個別評論者的姓名——那些是私人 |
| **客戶規模——自報彙總數字** | **自報、未經稽核** | 公司自家 [About 頁](https://www.databasemart.com/about/) 宣稱 **「500,000+ global customers」** 與 **「650,000+ services delivered」**，並有 **「2024: 400K+ customer milestone」**。此處的「客戶」幾乎確定是**累計歷史註冊數，而非活躍付費帳號**——2024 年里程碑的 40 萬與現在的 50 萬之間跳幅之大，足以支持這種讀法。**僅可作為量級指標**：這是一門高量、低單價、長尾的生意 |
| **客戶輪廓與口碑——第三方評論證據** | **第三方聚合平台；平台自身已標註徵集偏誤** | [Trustpilot](https://www.trustpilot.com/review/databasemart.com) 對 databasemart.com 有 **246 則評論**，對 gpu-mart.com 有 **13 則**。整體情緒在**價格、支援回應速度與快速開通**上偏正面（「RDP/VPS setup ready to connect within 5 minutes」），少數則回報**伺服器不穩、當機、效能低於承諾、GPU 伺服器不退款**；有一則 gpu-mart 評論指控頻寬不足與「bait-and-switch」。**Trustpilot 自身標註該公司「may be asking for reviews in a way that compromises reliability」**——請對正面偏斜保持保留。**商業上相關的解讀：** 反覆出現的抱怨主題是**穩定性與實際交付效能**——正是「不匹配的主機平台 ＋ $2,099 AI 機種上的 100Mbps 管線」會產生的結果。**這把客戶痛點直接接上了平台論述** |
| **Cloud Clusters — 關聯品牌，不是客戶** | **公司自行揭露之關聯** | 公司自家里程碑列出 **「2017: Cloud Clusters partnership」**。其達拉斯測速檔案放在 `speedtest-c002.cloudclusters.io`、堪薩斯城的放在 `speedtest-kansas.cloudclusters.io`，因此 **cloudclusters.io 在營運上屬於他們自己或高度關聯的品牌，不是保持距離的客戶**。該名稱下不存在獨立德州法人（登記資料庫萬用字元搜尋無紀錄）。**記為關聯品牌，不是客戶**（[About 頁](https://www.databasemart.com/about/) · [資料中心頁](https://www.databasemart.com/data-center)） |

### 11.2 規模——可以與不可以界定的部分

**伺服器與 GPU 數量：未揭露。** 任何已觸及的來源都沒有伺服器數、GPU 數、機櫃數或簽約 kW。

**可由證據界定的部分：** 他們公布 **26 個專用 GPU SKU 加 8 個 GPU VPS 層級**，全部標示 Available，涵蓋從 Pascal P1000 到 Blackwell RTX PRO 6000 的 **20 個以上不同 GPU 型號**。要維持這麼多型號的線上庫存，代表**每個 SKU 至少數台——也就是數百台等級的 GPU 節點，而不是數十台。**

**由位址推得的上界：** 他們自有路由空間在堪薩斯城僅一個 **/22（1,024 個位址）**，而每台專用伺服器附 1 個專屬 IPv4。即使計入 Psychz 空間內另行編址的達拉斯據點與新租的 5,120 個 RIPE 位址，整個位址資產所能支撐的是**橫跨所有產品線（Windows／Linux VPS、RDP、裸機與 GPU）的數千台等級伺服器**，而 GPU 只是其中一部分。

> **ESTIMATE：GPU 節點約在 200–600 台這個量級。這是模型化數字，不是查證所得，不得作為事實登錄 CRM。**

### 11.3 網路 — AS401479

- **ASN：** **AS401479**，ARIN 代號 AS401479，網路名稱 **「DBM-ASN-KC」**，**2024-11-07** 登記給 Database Mart LLC（Org **DML-132**），備註「https://www.databasemart.com/」。[RIPEstat as-overview](https://stat.ripe.net/data/as-overview/data.json?resource=AS401479) 確認持有者為「DBM-ASN-KC - Database Mart LLC」，`announced = true`，位於 ARIN 配發的 32-bit 區塊 401309–402332 內。**「KC」後綴明確把 ASN 綁到堪薩斯城據點。** 請注意年齡：**僅 21 個月**——在取得自有 ASN 前，他們已用堪薩斯城的 /22 營運約四年。
- **IPv4 資產——三個位址池共 22,528 個位址，其中 16,384 個休眠：**
  - **自有（ARIN Org DML-132）：** **163.123.180.0/22**，網路代號 NET-163-123-180-0-1，名稱「DBM-NET-01」，1,024 個位址，**2020-08-03** 登記，自 **2021-01-30** 起持續宣告，2026-08-11 為 **326 個 RIS peer 全數可見**。
  - **自有但未點亮：** **38.247.128.0/18**，網路代號 NET-38-247-128-0-1，名稱「DATABASEMART-CGNT-NET-1」，**16,384 個位址**，型態為 Cogent 母體 NET-38-0-0-0-1 之下的 ALLOCATION，**2026-01-21** 登記——且**未對外宣告**：[routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=38.247.128.0/18) 回傳 **326 個 RIS peer 中 0 個可見**、無來源 AS、無首見日期。
  - **租用（RIPE，經 IPXO 市集，維護者 `netutils-mnt`）：** **93.127.128.0/20**，RIPE 物件名稱「Database_Mart_LLC」，ASSIGNED PA，機構 ORG-DML16-RIPE，4,096 個位址；以及 **77.93.152.0/22**，RIPE 物件名稱「IPXO」，SUB-ALLOCATED PA，登記人「Private Customer」，1,024 個位址。**兩者皆於 2026-07-28 首次出現在 AS401479 的宣告中。**
- **頻寬：** 未揭露。其產品頁在 H100 專用機種上賣 **100Mbps 不限流量**，在 RTX PRO 6000 VPS 層賣 **1000Mbps 不限流量**——這些是**每客戶配額，不是站點容量。站點容量為 GAP。**
- **Peering：未列於 PeeringDB。** API 對 asn=401479 回傳 `{"data": [], "meta": {"error": "Entity not found"}}`，以「Database」做名稱搜尋亦無結果。**他們在 PeeringDB 完全沒有存在感**——對一個自有 ASN、握有 22,528 個位址的網路而言，是明顯的成熟度訊號。
- **BGP 拓撲相對單薄。** [RIPEstat asn-neighbours](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) 對 AS401479 恰好回傳 **一個鄰居**——**AS32097, Wholesale Internet, Inc.**（密蘇里州 Kansas City），type「left」、power 371、3,320 個 v4 peer。**AS401479 為單歸屬（single-homed）。**
- **他們自有的 /22 甚至不是由自己的 ASN 發出的。** routing-status 顯示唯一來源為 **AS32097**，帶 ARIN route object。
- **上游背景：** AS32097 **有**列於 PeeringDB，開放 peering 政策，`ix_count` 10、`fac_count` 9，自報流量 **1–5 Tbps**。達拉斯據點完全位於 **Psychz Networks 的 AS40676** 空間內（108.181.0.0/16 登記於 Psychz，Org PS-184）。

> **淨解讀：Database Mart 擁有位址與 ASN，但實質上並不營運一個獨立網路——傳輸、路由發布與 peering 全都是別人的。** 再加上 16,384 個自有卻未點亮的位址，整體圖像是**一家買容量的速度快過建網路的業者。** 未路由的位址空間，就是等待硬體到位的前置容量。

來源：[ARIN asns](https://whois.arin.net/rest/org/DML-132/asns.json) · [ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json) · [RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) · [RIPEstat asn-neighbours](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) · [PeeringDB](https://www.peeringdb.com/api/net?asn=401479) · [RIPE RDAP 93.127.128.0](https://rdap.db.ripe.net/ip/93.127.128.0) · [ARIN RDAP 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28)

---

## 12. 政治與公開紀錄

僅限公開紀錄。每一列都已標籤。**請仔細看標籤：「公開紀錄（已查證之空結果）」代表查詢已執行完成且回傳為空——那本身就是一項發現；「gap」代表查詢根本無法執行。兩者不是同一回事。**

本節最關鍵的事實是一條依賴關係：**創辦人的姓氏未知（第 4.1 節），而 FEC 個人捐款索引是以「LASTNAME, FIRSTNAME」為鍵。** 那個不受姓氏影響、能把他一併撈出來的雇主端查詢**確實**執行完成，且**確實**回傳空結果，因此有積極證據顯示：不存在以任何 Database Mart 雇主字串申報的捐款。但若捐款是以其他雇主、「self-employed」或「retired」申報，就不會被撈到。這個殘餘缺口，會在德州 SOSDirect 交出治理人員完整法定姓名的那一刻關閉。

| 對象 | 發現 | 金額＋日期 | 受贈對象 | 標籤 | 來源 |
|---|---|---|---|---|---|
| **Database Mart LLC**（以**雇主**查詢，全部名稱寫法） | **查無紀錄。** 已以 `contributor_employer` 對 OpenFEC Schedule A（個人捐款）查詢四種寫法——**「Database Mart」「DatabaseMart」「Database Mart LLC」「GPU Mart」**——**每一種都回傳 0 筆。** **在任何一種雇主名稱拼法之下，本公司都沒有任何員工或負責人出現在 FEC 個人捐款資料中。** 這是**來自聯邦一手來源、已查證的空結果，不是未查詢的缺口** | **不適用——回傳 0 列** | **不適用——不存在受贈委員會**，因此下方的受贈機構表必然為空 | **公開紀錄 · 來自 FEC 官方 API 的已查證空結果** | [OpenFEC Schedule A（依雇主）](https://api.open.fec.gov/v1/schedules/schedule_a/?api_key=DEMO_KEY&contributor_employer=Database+Mart) |
| **Database Mart LLC**（以**委員會設立人**查詢） | **不存在公司 PAC。** 以 `q='database mart'` 查詢 OpenFEC `/v1/committees/`，回傳 **0 個委員會。** **不存在任何獨立分離基金（separate segregated fund）、任何關聯組織，也不存在任何形式的公司 PAC。** | **不適用——0 個委員會** | **不適用** | **公開紀錄 · 已查證之空結果** | [OpenFEC 委員會查詢](https://api.open.fec.gov/v1/committees/?api_key=DEMO_KEY&q=database+mart) |
| **Morris** — 創辦人暨執行長，**姓氏未知** | **無法以姓名查詢。** FEC 個人捐款索引以「LASTNAME, FIRSTNAME」為鍵，而**所有已觸及的一手紀錄都未揭露此人的姓氏**（第 4.1 節）。那個不受姓氏影響、能把他一併撈出來的雇主端查詢回傳 0 列（上方第 1 列），因此**確實**有積極證據顯示不存在以 Database Mart 雇主字串申報的捐款——**但若以其他雇主、「self-employed」或「retired」申報，則不會被撈到。** 這個缺口會在德州 SOSDirect 交出治理人員完整法定姓名時關閉 | **GAP — 無姓氏即無法查詢** | **GAP** | **gap — 受阻於上游的登記付費牆，不是空結果** | [Database Mart About 頁](https://www.databasemart.com/about/) — 名字的唯一來源 |
| **Allison Shiozawa Miles** — 外部商標律師。**僅為完整性查核；她不是公司負責人** | **查無紀錄。** 已以 `contributor_name` 對 OpenFEC Schedule A 查詢 **「MILES, ALLISON」**、**「SHIOZAWA MILES, ALLISON」**、**「MILES, ALLISON SHIOZAWA」**——**各回傳 0 列。** | **不適用——回傳 0 列** | **不適用** | **公開紀錄 · 已查證之空結果** | [OpenFEC Schedule A（依姓名）](https://api.open.fec.gov/v1/schedules/schedule_a/?api_key=DEMO_KEY&contributor_name=MILES%2C+ALLISON) |
| **Database Mart LLC 及其負責人** — **德州州級**競選財務（總部所在州） | **未查詢完成 — GAP。** 對一家德州設立的實體而言，德州公職倫理委員會（Texas Ethics Commission）是正確的州級來源，但 TEC 查詢介面需要**互動式工作階段**；更根本的是，州級個人查詢**受阻於與 FEC 個人查詢相同的未知姓氏。** 從法人名稱切入的角度另有其弱點：**德州不允許公司直接捐款給候選人**，因此即使負責人在政治上活躍，以公司名稱查詢預期也會查無。**如實記為缺口，而非空結果** | **GAP** | **GAP** | **gap — 需互動式工作階段，且姓氏依賴未解** | [德州公職倫理委員會競選財務查詢](https://www.ethics.state.tx.us/search/cf/) |

#### 受贈機構 — 沿革、政治傾向與負責人

| 機構 | 類型 | 沿革 | 政治傾向（＋證據） | 負責人 | 負責人姓氏語源（onomastic） | 來源 |
|---|---|---|---|---|---|---|
| **查無任何受贈委員會** — 本表為空，是上表已查證空結果的**直接後果**，不是查證不足 | **不適用** | **未辨識到任何受贈委員會，因為根本沒有查到任何形式的捐款紀錄。** FEC Schedule A 對所測試的每一種雇主寫法都回傳 0 列，且沒有任何委員會與公司名稱關聯。因此**下游無事可查**——沒有委員會可側寫、沒有成立日期、沒有資金脈絡 | **不適用——未查到委員會，因此無從評估任何政治傾向。** 在此處**完全不記載任何傾向**才是正確輸出；若從其他訊號推測本公司或其創辦人的政治取向，即屬杜撰 | **不適用——沒有委員會，因此沒有主席、會長、財務長或執行長可辨識** | **不適用——未執行任何姓名語源研究。** 沒有委員會負責人可供研究。姓氏語源這個步驟依設計**僅適用於已辨識之受贈委員會負責人**，且須取自公開姓名學參考資料；本次**刻意未**將其套用於本公司創辦人或其律師：該步驟純屬姓名語源考據，依本次需求僅附著於受贈委員會負責人，且絕不得被呈現為對任何個人族裔的陳述 | [OpenFEC Schedule A（依雇主）](https://api.open.fec.gov/v1/schedules/schedule_a/?api_key=DEMO_KEY&contributor_employer=Database+Mart) · [OpenFEC 委員會查詢](https://api.open.fec.gov/v1/committees/?api_key=DEMO_KEY&q=database+mart) |

#### 遊說（Lobbying）

**GAP — 查無任何紀錄；而在聯邦這一層，這是已查證的空結果，不是未查詢的缺口。** 已對 [美國參議院遊說揭露法（LDA）API](https://lda.senate.gov/api/v1/filings/?client_name=Database%20Mart) 以 `client_name='Database Mart'` 與 `client_name='GPU Mart'` 查詢申報紀錄；**兩者皆回傳 `count: 0`。** 本公司**沒有任何聯邦遊說登記、沒有申報議題、沒有登記遊說人、也沒有任何受規範官員**，**申報支出為 $0——因為根本不存在申報。** 這與其樣貌完全相符：一家約 80 人、所有權人自營、無外部投資人、無 PAC、看不到聯邦採購足跡的德州 LLC，本來就沒有理由出現在 LDA 資料中。兩點必須說清楚的但書：**LDA 零申報只代表沒有應申報的聯邦遊說行為——並不排除產業公會會費，那在會員層級並不單獨揭露**；以及 **Database Mart LLC 或 GPU Mart 不可能存在 [OpenSecrets](https://www.opensecrets.org/orgs/) 機構檔案**，因為 OpenSecrets 的機構檔案是由 FEC 捐款資料與 LDA 申報建構而成，而這兩個上游來源都回傳零——此處記為**已具名上游來源的推導性空結果**，不是直接抓取該頁的結果。

**訴訟紀錄，僅供完整性：** [CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search/?q=%22Database%20Mart%22&type=r) 以 `"Database Mart"` 查詢，在 RECAP 案卷（`type=r`）與判決（`type=o`）**兩者皆回傳 count 0**。**此僅涵蓋聯邦 RECAP 範圍。** 德州**州法院**紀錄——Galveston 郡地方法院與郡法院、Harris 郡——**未查詢**，且 CourtListener 的聯邦案卷覆蓋本身也不完整。

**未發現本公司或其負責人任何形式的法案或政策立場。** 直說：**在政治與公共政策這條軸線上，本公司在聯邦層級完全沒有足跡——而且與本檔前一版不同，聯邦這一側現在是一次「已完成的負面查證」，不是一次沒跑完的查詢。** FEC 雇主查詢、FEC 委員會查詢與參議院 LDA 查詢三者都執行完成，三者都回傳空。**「查無 FEC 紀錄」本身就是一項發現，並已如此記載。** 仍未結的部分範圍明確且已具名：**個人姓名**的 FEC 查詢，以及**德州州級**競選財務查詢，兩者都受阻於未知的姓氏。這裡沒有可用的切入點，也沒有任何構成風險的事項。

*姓氏語源僅為公開姓名學資料之語源考據，並非對任何個人族裔或血統之查證陳述。政治獻金為公開紀錄，不等於政黨登記。*

---

## 13. 公開聯絡管道

僅限公開來源。**此處不列任何個人手機或私人住宅聯絡方式作為接觸路徑，亦未尋求。** 請注意登記地址是私人住宅——以下記載為登記事實，**不是**可拜訪或可寄件的地點。

| 管道 | 內容 | 來源 |
|---|---|---|
| **售前 email — 建議之首次接觸主要路徑** | **sales@databasemart.com** — 聯絡頁明確邀請透過售前團隊洽詢 **「custom server configurations beyond standard offerings」**，這對硬體供應商而言是正當且切題的來信理由 | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) |
| **辦公室電話 — 官網未公布；由 ARIN 取得** | **+1-409-877-4238** — 登記為 Database Mart LLC **兩個** ARIN POC 紀錄（ADMIN7533-ARIN 與 ABUSE8080-ARIN）的 Office 電話。**409 區碼**涵蓋 Galveston／League City，與登記地址相符。**由於此號碼完全未出現在公開網站上（聯絡頁一支電話都沒列），不太可能被導進被過濾的行銷來電佇列** | [whois.arin.net/rest/poc/ADMIN7533-ARIN.json](https://whois.arin.net/rest/poc/ADMIN7533-ARIN.json) |
| **基礎設施／NOC email — 通往技術決策者的最佳路徑** | **admin@databasemart.com** — ARIN 登記中**同時**負責 Routing、Tech、NOC、DNS、Admin 五項職能的聯絡信箱。讀這個信箱的人掌管網路與節點 | [whois.arin.net/rest/poc/ADMIN7533-ARIN.json](https://whois.arin.net/rest/poc/ADMIN7533-ARIN.json) |
| 一般支援 | **support@databasemart.com** · 工單系統 [console.databasemart.com/ticket](https://console.databasemart.com/ticket) · 網站線上客服 · 宣稱 24/7 | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) |
| 行銷 | **marketing@databasemart.com** | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) |
| 濫用／合規 | **abuse@databasemart.com**（ARIN abuse POC ABUSE8080-ARIN）— **僅列為完整性；非銷售管道，請勿使用** | [whois.arin.net/rest/poc/ABUSE8080-ARIN.json](https://whois.arin.net/rest/poc/ABUSE8080-ARIN.json) |
| 登記／通訊地址 | **Database Mart LLC, 257 Westwood Dr, League City, TX 77573, United States** — 在德州 SOS／Comptroller 紀錄、ARIN Org DML-132、兩個 ARIN POC、網域 WHOIS 註冊人街道與公開聯絡頁上完全一致。**請注意這是私人住宅；寄送實體郵件或臨門拜訪並不恰當** | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) · [ARIN RDAP 163.123.183.33](https://rdap.arin.net/registry/ip/163.123.183.33) |
| 企業社群 | LinkedIn 公司頁 [linkedin.com/company/database-mart](https://www.linkedin.com/company/database-mart) · **由公司操作**的個人格式檔案 [linkedin.com/in/database-mart-788a35111/](https://www.linkedin.com/in/database-mart-788a35111/) · Facebook [facebook.com/databasemart](https://www.facebook.com/databasemart/)。**未查得 Morris Liu 的個人 LinkedIn 檔案 — GAP** | [LinkedIn](https://www.linkedin.com/company/database-mart) |
| **新聞／公告訊息源 — 用來抓下次接觸時機** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) — 公司自家帶日期的公告訊息源；歷來 GPU 上市都先在此宣布。**值得持續監看 2026 年 9–12 月的採購窗口（§8.3）** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| 任何具名個人的直撥電話 | **GAP — 未公布任何一支。** Morris Liu 或任何其他人皆無個人 email、無直線 | — |

---

## 14. Supermicro 銷售切入點

### 分類：**二手市場主機上的自組整合商 → 借 Blackwell 換代做平台轉換**

**這不是既有客戶防守，也不是取代競爭原廠。** 這裡沒有原廠可取代。Database Mart 自行整合：他們公布的 26 個專用 SKU，每一個都跑在 Xeon E5 v3/v4、Gold 6148 或 Platinum 8160 主機上——2014-2017 年矽晶，型錄中沒有任何當世代平台。**競爭對手不是 Dell 或 Gigabyte，而是一台 $700 的二手 4U 機殼。** 接受這一點，策略就清楚了。

### 誠實面對我們會輸的地方

**在同規格的 H100 機種上，我們會輸，也不該去試。** 他們的旗艦是單張 H100 掛在 Dual E5-2697v4 主機上，**GPU 佔 BOM 的 90–95%，主機實質免費。** 沒有任何新的 Supermicro 平台能在資本支出上贏過「免費」，而成本天花板模型也說明了他們為什麼這樣造：以 **$2,099/月**標價、35–50% 營運成本與 75–85% 實收率計算，整機硬體預算即使在寬鬆的 24 個月回收期下也只有 **$18,900–$27,800——比一張全新 H100 卡還少。** **對著那個 SKU 開場就報新平台價，只會讓電話被掛掉。**

### 我們會贏的地方——楔子

> **RTX PRO 6000 96GB 與整條 Blackwell 產品線，在物理上把舊平台弄壞了。**

**2025-11-08 至 2026-04-19** 之間，他們新增了六個 Blackwell SKU——RTX PRO 6000（2025-11-08 上線，$729/月）、RTX PRO 5000 與 4000（2026-01-12）、RTX PRO 2000（2026-01-16），加上 RTX 5090 與 5060——並整併到一個 Blackwell 入口頁。**那些是 PCIe Gen5、600W 級的零件。他們公布的主機服務不了它們：** E5-2697v4 是 Broadwell-EP，掛在 PCIe 3.0 的 root complex 上。

**他們自家的 [H100 頁面](https://www.gpu-mart.com/h100-hosting) 證明他們知道規格重要、但還沒把它對齊**——該頁在卡片規格欄標示「PCIe Gen5」，卻列出一個上限只到 Gen3 的 CPU 世代。**這不是拿來當面戳人的把柄，而是一個可以共同討論的工程問題；一位電腦科學博士創辦人會願意接這個話題。**

三項互相強化的壓力，讓時機是對的：

1. **他們把一張 96GB 的 RTX PRO 6000 當成切分後的 32 核 VPS 在賣**，因此需要一個在多租戶切分下能乾淨驗證的平台，而不是撿來的主機板。
2. **那張卡的價格在九個月內已從 $729 掉到 $479**，代表**毛利在壓縮而採購還在繼續**——每機櫃 U 數與每 kW 的效率，開始比機殼資本支出更重要。
3. **Trustpilot 上反覆出現的抱怨主題是不穩定與效能低於承諾**，那正是不匹配的主機會造成的結果——**平台論述同時也是客戶流失論述。**

**值得帶著的次要、較安靜的訊號：** 他們在 **2026-01-21 登記了 38.247.128.0/18——16,384 個位址——而且至今完全未路由**（326 個 RIS peer 中 0 個可見）。**沒有人會為一個不打算填滿的 /18 付錢。** 再加上 2026-07-28 上線的 5,120 個租用位址，那就是**等待硬體到位的前置容量。**

### 首次接觸的唯一資格問題

> **「你們十一月上線的那批 RTX PRO 6000 96GB 節點，是進到跟 H100 那條線同一個 Dual E5-2697v4 平台，還是為它們換了新機殼？我會這樣問，是因為 Gen5 x16 以及 600W 級的供電與散熱範圍，我想知道你們現在真正在管的限制是主機板，還是資料中心籠內的每機櫃 kW 上限。」**

**問完就閉嘴。** 這個問題具體、可以用他們自己公布的規格回答、不是陷阱，而且答案會立刻把機會分類：

- **「同一個平台」** → 一個我們能解決的真實技術問題。
- **「換了新機殼」** → 追問是誰的，以及是新品還是二手。
- **「kW 上限」** → 對話主題是**密度與效率，不是資本支出**，那對我們是好得多的對話。

**保留備用的第二個資格問題：** 2026-07-28 上線的那些 RIPE 區域前綴，是真的歐洲設施、規劃中的設施，還是從堪薩斯城宣告的位址套利？答案會決定前瞻機會的規模。

### Rule 8 — 經銷通路注意事項（撥號前必讀）

> **註冊任何東西之前，先確立採購路徑。不要假設這是直接客戶。**

證據中的每一個訊號——**清一色 2014-2017 主機矽晶、集中在上一代顯卡的 20–55% 常態折扣、以近乎免費主機承載的 GPU 主導型 BOM，以及從 Pascal 混到 Blackwell 的機隊**——都指向透過**經銷、中盤、整合商或二手市場**採購，而非向原廠直接採購。**所有公開來源中都未具名任何硬體廠商**（兩個網域對八個原廠名稱的 grep **全部零命中**），因此**通路真的是未知的。**

**送件之前：**

- **(a)** 在資格通話中確認**他們今天怎麼取得機殼與顯卡。**
- **(b)** 若答案是經銷商、代理商或整合商，請將 **Database Mart LLC 註冊為終端使用者**，**絕不註冊經銷商**——經銷商不是這個客戶。
- **(c)** 查核**是否已有經銷商註冊涵蓋這個終端使用者**，因為對一筆由經銷履約的案子重複做直接註冊，正是 Rule 8 存在要防範的通路衝突。
- **(d)** **誠實估算規模**——一個 200–600 台節點、換代其中 Blackwell 一部分的機隊，是真實但規模有限的機會，**遠低於 $100M CRM 門檻**，應據此分級，不得為了正當化直接註冊例外而灌水。

**轄區已確定：** 德州 League City 為 **T1**（同時列 T3），**一組可直接註冊**，且 CRM 已於 **2026-08-11** 實查為乾淨——無 lead、無 account、無 do-not-call。

**順序——不得調換：** ① 確立採購路徑並釐清通路歸屬（Rule 8）→ ② 以終端使用者身分註冊 Database Mart LLC（T1、一組、直接）→ ③ 經 sales@databasemart.com 或 +1-409-877-4238 接觸，只問上面那個資格問題。

---

## 15. 查證附錄

### 15.1 單一來源支撐的說法（引用前須再驗證）

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| **執行長姓氏「Liu」** | 僅 [TheOrg](https://theorg.com/org/database-mart-llc/org-chart/morris-liu) | **單一第三方聚合商，非一手登記文件。** 公司自家網站只用名字「Morris」，而德州登記完全沒有具名他。**在書面使用全名之前，請先於首次接觸口頭確認** |
| **舊機隊中的 Supermicro 存在** | **無來源——純由平台世代推論** | **等級為 INFERRED。絕不得對客戶表述為已知事實。** 這是本案業務最可能犯的單一錯誤 |
| **「80+ professionals across six departments」** | 公司 [About 頁](https://www.databasemart.com/about/)，自報；ZoomInfo 51–200 區間為寬鬆佐證 | 自報的行銷文字。**不得改述為經稽核的員工數** |
| **「500,000+ global customers」／「650,000+ services delivered」** | 僅公司 [About 頁](https://www.databasemart.com/about/) | **自報、未經稽核，且幾乎確定是累計歷史註冊而非活躍帳號。** 不得改述為客戶數 |
| **兩個資料中心據點的電力／散熱規格** | 僅公司 [資料中心頁](https://www.databasemart.com/data-center) | **這些描述的是「建築物」，不是 Database Mart 在其中的佔用範圍。** 把「2 台 2MW 發電機」或「360 噸散熱」引用為 Database Mart 的容量會是錯的。另請注意該頁還含逐字錯字 **「Evergy Ttier 1 customer」** |
| **堪薩斯城設施營運者** | **任何來源皆未具名**——只確立了傳輸供應商（Wholesale Internet, AS32097） | 1530 Swift St 的建物營運者屬 **GAP**。不得假設 Wholesale Internet 擁有該建物 |
| **Trustpilot 口碑主題** | [databasemart.com](https://www.trustpilot.com/review/databasemart.com)（246 則）與 [gpu-mart.com](https://www.trustpilot.com/review/gpu-mart.com)（13 則）之搜尋結果摘要 | **Trustpilot 自身標註可能存在評論徵集偏誤。** 個別評論者刻意**未**彙整——他們是私人 |
| **H100 街頭價 $25,000–$30,970** | 對 compute.exchange、cloudzero、northflank、intuitionlabs、gmicloud 等的網路搜尋，**時點為 2026 年 3 月** | 多來源，但相對本檔**已陳舊五個月**，且部分供應商在缺貨時報 $30,000–$38,000。**報價前請當日重新查核** |
| **營收區間 $10M–$25M** 與 **200–600 台 GPU 節點** | **兩者皆無來源，皆為模型化 ESTIMATE** | 分別由「員工數 × 人均營收」與「SKU 廣度 × IPv4 資產」推得。**不得作為事實登錄 CRM** |

### 15.2 矛盾或異常紀錄——呈現，不擇一

**登記之 NAICS 產業代碼**

| 來源 | 值 |
|---|---|
| Texas Comptroller 課稅實體紀錄 | **541410 — Interior Design Services（室內設計服務）** |
| 實際業務 | 網站／GPU 主機代管 |

**未和解，且逐字照錄不予更正。** 幾乎確定是自 2005 年沿用至今的陳舊或誤植分類。本身無害，但代表**以 NAICS 篩選不會把這家公司當成主機業找出來。**

**創立日期 vs 網域註冊日**

| 來源 | 日期 |
|---|---|
| 德州 SOS 設立許可 · 公司 About 頁 | **2005-01-13** |
| databasemart.com 網域建立日（RDAP） | **2004-11-16** |

**這不是衝突，是順序。** 創辦人先註冊網域，兩個月後才設立公司。列此因為它是佐證而非矛盾。

**員工數**

| 來源 | 數字 |
|---|---|
| 公司 About 頁（自報） | **80+** |
| ZoomInfo | **51–200** |

**一致，非衝突。** 任何引用請標示為「自報，第三方區間一致」。

**登記地址**

| 來源 | 性質 |
|---|---|
| 德州 SOS／Comptroller · ARIN Org DML-132 · 兩個 ARIN POC · 網域 WHOIS · 公司聯絡頁 | **公司登記地址** |
| HAR、Zillow、Redfin 不動產紀錄 | **5 房／3.5 衛、約 4,300 平方英尺單戶住宅，2014 年興建** |

**兩者都是真的。** 該公司的登記地址是一棟私人住宅。**這是正確的描述，並且必須帶進任何 CRM 紀錄**，以免有人嘗試現場拜訪或寄送貨物到該址。

### 15.3 未結 GAP

1. **UCC-1 融資聲明——最大的單一缺口。** 取得申報 0 筆；判定為 **「UNVERIFIED — portal blocked」**，不是「無申報」。德州 UCC 紀錄位於 SOSDirect 付費訂戶登入之後，未予突破。**無法回報任何申報號碼、日期、失效／續期、secured party、debtor 地址、擔保品描述或修正／讓與／終止。** **動作：** 透過 SOSDirect 帳號或商業留置權廠商，對 `DATABASE MART LLC` 與未加後綴的 `DATABASE MART` 執行 UCC-11 debtor 查詢。
2. **幹部、經理人、成員與註冊代理人——完全未知。** Texas Comptroller 公開資料紀錄無幹部／代理人欄位，而 Comptroller 帳戶狀態明細頁是 JS 單頁應用，三種查詢方法都只回傳空表單外殼。持有設立證書、申報歷程與年度報告簽署人的 SOSDirect 位於同一個付費登入之後。**Morris Liu 是本檔唯一的名字，且出自單一第三方聚合商，非一手申報。**
3. **FEC 政治捐款——從未查詢完成。** 五次 OpenFEC 查詢在三次嘗試中全部回傳 HTTP 429（公用 DEMO_KEY）。記為 **UNVERIFIED，明確不是「查無紀錄」**。請以 api.data.gov 註冊金鑰重跑。
4. **USPTO 商標——未取得任何紀錄，未辨識任何宣誓書簽署人或通訊代理人。** 四條 API 路徑全部失敗：`tmsearch.uspto.gov/api-v1-0-0/tmsearch` GET 回 **HTTP 404（NoSuchKey）**、POST 回 **HTTP 405**；`developer.uspto.gov` 端點回 **HTTP 301**；TMDN／TMview POST 回 **HTTP 000**；`trademarks.justia.com` 回 **HTTP 403**。以「Database Mart」／「GPU Mart」做一般商標搜尋只回傳通用說明文章。**他們完全有可能沒有註冊商標，但這一點並未被確立——搜尋根本沒跑起來。**
5. **歷史 WHOIS** — whoisrequest.com 回傳 **HTTP 403**；whoxy 與 securitytrails 未觸及。僅取得**現行** WHOIS／RDAP（databasemart.com 建立 2004-11-16、到期 2026-11-16、更新 2025-11-02；gpu-mart.com 建立 2021-11-15、到期 2026-11-15；兩者皆在 **NetEarth One Inc. d/b/a NetEarth**，使用 **Cloudflare** 名稱伺服器 THADDEUS／VIVIENNE 與 clientTransferProhibited；註冊人組織 **REDACTED FOR PRIVACY**，但註冊人街道「257 Westwood Dr.」外露；databasemart.com 帶 DNSSEC signedDelegation）。**無歷史註冊人姓名、無遮蔽前紀錄、無註冊商或名稱伺服器變更時間軸。**
6. **BOM 對照所需之 Supermicro 報價** — 未拉取任何 Supermicro 組態器或代理商報價，因此**未列出同等新系統的任何牌價**。**在任何客戶對話之前必須以實際報價補上**；BOM 對照在結構上完整，但在數字上是單邊的。
7. **二手市場零組件價格** — Dual E5-2697v4 一對、256GB DDR4 ECC RDIMM、4U 雙路 E5 GPU 機殼，以及儲存／網卡等項目**未獨立取價**。僅 H100 卡取得來源。**因此「GPU 佔整機成本 90–95%」是推理所得，不是完整計價所得。**
8. **硬體廠商——機隊任何部分都未辨識出伺服器原廠。** 對兩個網站首頁加上 `/gpu-specs`、`/about/`、`/about-us` grep Supermicro、Dell、Gigabyte、ASUS、Tyan、Inspur、Lenovo、HPE，**每一個字串都零命中**。**第 6 節的 Supermicro 歸屬等級為 INFERRED，絕不得表述為事實。**
9. **主機代管合約條款** — Database Mart 在 **1515 Round Table Dr（達拉斯）** 與 **1530 Swift St（北堪薩斯城）** 兩地的籠架面積、機櫃數、簽約 kW 與合約到期日皆未知。只取得建物層級設施規格，而那是**營運者的，不是承租戶的**。**堪薩斯城設施的營運者名稱同樣未在任何公開紀錄中確認。**
10. **伺服器與 GPU 數量** — 任何地方都未揭露。**200–600 台 GPU 節點為模型化 ESTIMATE**，由 SKU 廣度與 IPv4 資產界定，不是查證所得數字。
11. **營收** — 未揭露。無 SEC 申報（本就不會有）、無 Crunchbase 營收數字、無在案募資輪。**$10M–$25M 區間為模型化 ESTIMATE**，由員工數與人均營收推得，並以型錄租金反向檢核。
12. **郡不動產／估價紀錄** — **未直接調閱** 257 Westwood Dr 的 Galveston CAD 地籍紀錄；不動產特徵來自房產列表聚合商（HAR、Zillow、Redfin），能確立該址為住宅，但**未提供課稅估值、登記所有權人姓名或所有權移轉歷程**。兩個資料中心地址亦未申調估價紀錄，因為兩者都是第三方設施，承租戶並非所有權人。
13. **法院案卷** — CourtListener 以 `"Database Mart"` 查詢案卷（`type=r`）與判決（`type=o`）皆回傳 **count 0**。**此僅涵蓋聯邦 RECAP 範圍。** 德州**州法院**紀錄——Galveston 郡地方法院與郡法院、Harris 郡——**未查詢**，且 CourtListener 的聯邦案卷覆蓋本身也不完整。
14. **徵才啟事與具名人員** — **未找到徵才頁面，任何求職平台上都查不到 Database Mart 的職缺。** 亦未辨識任何研討會簡介、Podcast 出席、社群論壇官方帳號或部落格作者署名。因此**除執行長外，沒有招募主管、沒有任何技術人員姓名。** §4.1 中三位未具名部門主管，是由公司自家部門清單推得，不是來自任何個人來源。
15. **PEERINGDB** — Database Mart **完全沒有 PeeringDB 紀錄**（API 對 asn=401479 回傳 `Entity not found`），因此該來源**沒有設施清單、沒有 IX 據點、沒有流量自報、沒有 peering 聯絡人**。其網路拓撲必須**完全由 RIPEstat BGP 資料重建**。
16. **歐洲／第三據點** — AS401479 自 **2026-07-28** 起宣告的兩組 RIPE 區域前綴（93.127.128.0/20 與 77.93.152.0/22，共 **5,120 個位址**）是 IPXO 租用空間，且國別碼為 **US**。**這是否對應到真實的歐洲設施、規劃中的設施，或僅是從堪薩斯城宣告的位址套利，尚未解決。**
17. **德拉瓦州登記** — eCorp 實體搜尋無法以程式驅動（GET 回 HTTP 200，回傳含 CAPTCHA 的 ASP.NET 表單；POST 回 HTTP 411）。**很可能是死路**，因為 Comptroller 將該實體編碼為組織型態 **CL（德州本土 LLC）**，代表設立州是德州——**但這一點並未被積極確認。**
18. **具名客戶——公開來源中不存在**，而這對自助式中小企業主機商而言**是預期之內**。記為**結構性缺口，而非研究失敗**。個別 Trustpilot 評論者刻意**未**彙整——他們是私人。
19. **WAYBACK 覆蓋缺口** — 18 份型錄快照中有 **7 份**（2024-01-18、2024-09-15、2024-11-27、2024-12-22、2025-11-26、2026-01-11、2026-02-08）回傳零型號命中，因為存檔回應是 JS 外殼或 gzip 亂碼擷取。**那些日期屬於「缺乏證據」，不是「證據顯示不存在」**；已用型號專屬到達頁錨點橋接，但**採購時鐘的節奏承擔該不確定性。** 另有一次針對 2025-08 至 2026-05 區間的 CDX 呼叫回傳 **HTTP 504 Gateway Time-out**。`/rtx-5090-hosting`（2024-12-22）與 `/nvidia-a100-rental`（2024-03-05）的個別到達頁快照回傳**二進位亂碼，未取得任何內容**。
20. **GPU-MART.COM 站點層級缺口** — `/gpu-specs`、`/about-us` 與 `/gpu-vps-hosting` 回傳**空白或 HTTP 404**。因此部分型錄細節——**各 SKU 的庫存水位、確切折扣到期日，以及 3／12／24 個月之外的約期定價階梯**——未能擷取。
21. **重跑時的工具備註** — ZoomInfo MCP 連接器（以及 carta、figma、atlassian、spglobal、adobe 連接器）需要 OAuth 授權，在本次非互動式工作階段中無法使用。**授權 ZoomInfo 連接器很可能會在重跑時補上營收估計與具名人員兩項缺口。**

### 15.4 已實際查詢之來源——含「查無」者

**HIT — 本次最有價值的來源：**

- **[ARIN RDAP 163.123.183.33](https://rdap.arin.net/registry/ip/163.123.183.33)** — 單一價值最高的來源。回傳 Org **DML-132**「Database Mart LLC」、網路 NET-163-123-180-0-1 名稱 **「DBM-NET-01」**（163.123.180.0/22）、2020-08-03 登記、地址 257 Westwood Dr，以及 POC 代號 **ADMIN7533-ARIN** 與 **ABUSE8080-ARIN**，含辦公室電話 **+1-409-877-4238**——一個完全沒有出現在公司網站上的號碼。
- **[ARIN RDAP 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28)** — 回傳 **Psychz Networks**（Org PS-184、AS40676、加州 Walnut）為達拉斯空間登記人，abuse POC **TEXAS1-ARIN** 登記於「Profuse Solutions INC」，地址 1515 Round Table Drive, Dallas TX 75247。**這就是證明達拉斯據點為租用而非自有的關鍵。**
- **ARIN Whois-RWS** — [org DML-132 nets](https://whois.arin.net/rest/org/DML-132/nets.json)、[asns](https://whois.arin.net/rest/org/DML-132/asns.json)、[pocs](https://whois.arin.net/rest/org/DML-132/pocs.json)，以及 `/rest/poc/{ADMIN7533,ABUSE8080}-ARIN.json` 與 `/rest/asn/AS401479.json`。完整盤點 ARIN 資產：ASN AS401479「DBM-ASN-KC」（2024-11-07 登記）與兩個網路，包含此前未知的 **38.247.128.0/18**「DATABASEMART-CGNT-NET-1」（2026-01-21 登記）。同時確認**兩個 POC 皆為 `isRoleAccount=Y`，無任何個人姓名。**
- **ARIN 機構名稱搜尋** — `whois.arin.net/rest/orgs;name=Database%20Mart*` 恰好回傳一個機構（DML-132），確認**無兄弟 ARIN 登記**。
- **RIPE RDAP** — [93.127.128.0](https://rdap.db.ripe.net/ip/93.127.128.0) 與 [77.93.152.0](https://rdap.db.ripe.net/ip/77.93.152.0)。辨識出租用的歐洲登記區位址空間，並確立這些是 **IPXO 市集租約，不是自有空間**。
- **[RIPEstat](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479)** — announced-prefixes、as-overview、asn-neighbours、routing-status 各項資料呼叫。確立 **AS401479 單歸屬於 AS32097 之後**、該 /22 自 2021-01-30 起由 AS32097（而非 Database Mart 自有 ASN）持續發布、租用 RIPE 前綴於 2026-07-28 上線，以及關鍵的 **16,384 位址 /18 並未被宣告（326 個 RIS peer 中 0 個）**。
- **[Texas 開放資料（Socrata）](https://data.texas.gov/resource/9cir-efmm.json)** — 特許稅許可名冊，以 SoQL `$where` 對 `upper(taxpayer_name)` 查詢。**破解實體問題的來源。** 回傳 taxpayer_number 32107118534、SOS 檔案號 0800439627、設立日 2005-01-13、狀態 A/A、組織型態 CL、地址 257 Westwood Dr。第二次以 `%MART%` 限縮 LEAGUE CITY 的萬用字元查詢確認 **DATABASE MART LLC 是唯一一家**；再查 CLOUD CLUSTERS、VPS MART、SERVER MART、GPU MART、WINPC 皆回傳**「（無紀錄）」**，證明兄弟品牌是營業名稱。
- **[Wayback CDX API](https://web.archive.org/cdx/search/cdx)** — 採購時鐘的骨幹。產出各頁首次存檔日：`/rtx-a6000-hosting`（2023-02-08）、`/nvidia-a100-rental`（2024-03-05）、`/rtx-5090-hosting`（2024-12-22）、`/h100-hosting`（2025-02-13）、`/rtx-pro-6000-hosting`（2025-11-08）、`/rtx-pro-4000-blackwell` 與 `/rtx-pro-5000-blackwell`（2026-01-12）、`/rtx-pro-2000-blackwell`（2026-01-16）、`/nvidia-blackwell-gpu-server`（2026-04-19）。
- **Wayback 原始快照抓取（`id_` URL）** — `/gpu-dedicated-server` 自 2023-06-04 至 2026-04-19 共 18 份擷取，以 26 組 GPU 型號正規表示式比對。**11 份解析成功**，定出 RTX 4060（2023-11-13 前）、P100（2024-05-22 前）與 H100／RTX 5090／RTX 5060（2025-06-16 前）的到貨時點。**7 份零命中**（JS 外殼或 gzip 亂碼）。[2025-11-08 的 /rtx-pro-6000-hosting 擷取](https://web.archive.org/web/20251108102809/https://www.gpu-mart.com/rtx-pro-6000-hosting) 取得價格「$ 729.00」與「order now」按鈕。
- **[gpu-mart.com/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server)** — 完整轉錄 26 個專用 GPU SKU 之價格、規格、折扣百分比與供應狀態。**每一個主機 CPU 都是 Xeon E5 v3/v4、Gold 6148 或 Platinum 8160。**
- **[gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting)** — **決定性技術發現的來源。** 確認旗艦為「Nvidia H100 80GB HBM2e PCIe」掛在「36-Core Dual E5-2697v4」主機上，256GB RAM、240GB SSD ＋ 2TB NVMe ＋ 8TB SATA、100Mbps 不限流量、$2,099.00/月、24 個月約期、狀態 Available——**一張 PCIe Gen5 卡插在 PCIe Gen3 平台上。**
- **[gpu-mart.com/gpu-vps](https://www.gpu-mart.com/gpu-vps)**、**[/rtx-pro-6000-hosting](https://www.gpu-mart.com/rtx-pro-6000-hosting)**、**[/nvidia-blackwell-gpu-server](https://www.gpu-mart.com/nvidia-blackwell-gpu-server)** — 八個 GPU VPS 層級與現行 Blackwell 產品線。
- **[databasemart.com/about/](https://www.databasemart.com/about/)** — 創立日 2005-01-13、創辦人「Morris」（電腦科學博士）、完整里程碑時間軸、500,000+ 客戶、650,000+ 服務、「80+ professionals across six departments」。
- **[databasemart.com/contact-us](https://www.databasemart.com/contact-us)** — 地址、support@／marketing@／sales@ 信箱、工單系統、24/7 支援，以及**明確未公布任何電話號碼**（這讓 ARIN 取得的 +1-409-877-4238 更有價值）。
- **[databasemart.com/data-center](https://www.databasemart.com/data-center)** — 兩個資料中心地址、測速 IP 108.181.95.28 與 163.123.183.33，以及完整設施電力／散熱／電信規格，含逐字錯字「Evergy Ttier 1 customer」。
- **[portal.databasemart.com/news/](https://portal.databasemart.com/news/)** — 帶日期的新聞稿：GPU 主機上線 **2020 年 6 月**；「Expands GPU Hosting Offerings」**2023 年 1 月**，含 4 個新專用 GPU SKU；「Network and Power Issue in Kansas Data Center」**2023 年 7 月**。
- **[TheOrg](https://theorg.com/org/database-mart-llc/org-chart/morris-liu)** — 唯一一個人名的來源：「Morris Liu — CEO」，無直屬部屬。
- **databasemart.com 與 gpu-mart.com 的網域 WHOIS 與 Verisign RDAP** — 建立／到期日、NetEarth One 註冊商、Cloudflare 名稱伺服器、REDACTED 的註冊人組織與外露的註冊人街道。
- **經 HAR.com、Zillow、Redfin 取得的 257 Westwood Dr 不動產紀錄** — 5 房／3.5 衛、約 4,300 平方英尺單戶住宅、2014 年興建、2018-01-25 最近成交、Zestimate 約 $482,700 — **確立登記總部為住宅。**
- **H100 街頭價研究** — 跨 compute.exchange、cloudzero、northflank、intuitionlabs、gmicloud 等：截至 2026 年 3 月，美國全新街頭價 $25,000–$30,970（缺貨時部分報 $30,000–$38,000）；整新品 $21,000–$34,000；非整新二手 $15,000–$28,000。
- **[peeringdb.com/api/net?asn=32097](https://www.peeringdb.com/api/net?asn=32097)** — 回傳 Wholesale Internet, Inc.，開放政策、ix_count 10、fac_count 9、流量 1–5 Tbps。

**查無：**

- **[PeeringDB 對 asn=401479](https://www.peeringdb.com/api/net?asn=401479)** — `{"data": [], "meta": {"error": "Entity not found"}}`。以「Database」做名稱搜尋亦回傳空陣列。**Database Mart 在 PeeringDB 完全沒有存在感。**
- **[對兩個網站首頁 grep 硬體廠商](https://www.gpu-mart.com/)** — curl 兩個首頁，統計 Supermicro、Dell、Gigabyte、ASUS、Tyan、Inspur、Lenovo、HPE：**兩站對每一個字串的出現次數皆為零。** 輔以網路搜尋亦無任何提及這兩個網域的結果。
- **[CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search/?q=%22Database+Mart%22)** — `type=r` 與 `type=o` 皆 count 0、document_count 0。
- **求職平台與招募研究** — Indeed、ZipRecruiter、CareerBuilder、FlexJobs、Joblist：無徵才頁、無職缺、無招募主管、無具名技術人員。
- **[gpu-mart.com/gpu-specs](https://www.gpu-mart.com/gpu-specs)**、`/about-us`、`/gpu-vps-hosting` — 空白或 HTTP 404。

**受阻，以及原因：**

- **[Texas SOSDirect](https://direct.sos.state.tx.us/acct/acct-login.asp)** — HTTP 200，回傳**付費訂戶登入**。未建立帳號、未輸入憑證。**這是 UCC 判定與幹部／註冊代理人缺口共同的唯一阻擋點。**
- **[Texas SOS UCC 專區](https://www.sos.state.tx.us/ucc/index.shtml)**（HTTP 200，僅資訊性，無搜尋介面）· `direct.sos.state.tx.us/ucc/ucc-search.asp`（**HTTP 404**）· [sos.state.tx.us/ucc/forms/index.shtml](https://www.sos.state.tx.us/ucc/forms/index.shtml)（**HTTP 403**）。**全部受阻——未執行任何 UCC 查詢。**
- **德州「SOS Portal」後繼主機名** — `sosportal.sos.texas.gov` 與 `businessfilings.sos.texas.gov` **未解析**到任何德州 SOS 端點（curl HTTP 000；沙箱網路路徑回傳一個不相關的第三方 404 頁）。
- **[Texas Comptroller Franchise Tax Account Status 查詢](https://comptroller.texas.gov/taxes/franchise/account-status/search)** — 已觸及但**未回傳任何紀錄**；三種方法都只回傳同一份 130,041 bytes 的空表單外殼。該頁是 JS 單頁應用。
- **[Texas Comptroller 公開 API 說明文件](https://api-doc.comptroller.texas.gov/public-data/)** — 內容**被截斷，且無任何端點規格**。
- **[德拉瓦州 eCorp](https://icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx)** — GET 回 HTTP 200（含 CAPTCHA 的 ASP.NET 表單），**POST 回 HTTP 411**。無法以程式搜尋；**不解 CAPTCHA。**
- **[FEC OpenFEC](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=Morris%20Liu)** — 三次嘗試共五次呼叫，**每一次都 HTTP 429**（公用 DEMO_KEY）。**從未取回任何結果。**
- **USPTO** — 四條路徑全部失敗：`tmsearch.uspto.gov/api-v1-0-0/tmsearch`（GET HTTP 404 NoSuchKey、POST HTTP 405）、`developer.uspto.gov` ibd-api 與 ds-api（HTTP 301）、`tmdn.org/tmview/api/search/results`（HTTP 000）、`trademarks.justia.com`（HTTP 403）。
- **whoisrequest.com/history/databasemart.com** — **HTTP 403。** 未取得歷史 WHOIS；whoxy 與 securitytrails 未嘗試。
- **ZoomInfo、Crunchbase、LinkedIn、Trustpilot** — 僅經**搜尋結果摘要**觸及，未直接抓取。ZoomInfo：51–200 人，無營收數字。Crunchbase：無募資輪、無營收。LinkedIn：確認公司頁存在，未查得 Morris Liu 個人檔案，未取得員工名單。Trustpilot：僅取得評論數與口碑主題。
