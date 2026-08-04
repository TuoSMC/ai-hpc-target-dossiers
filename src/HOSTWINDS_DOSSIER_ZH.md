# Hostwinds LLC — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國） · 專員 US8664 Tuo Cheng · **日期：** 2026-08-04
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有公司、無 SEC 申報，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之伺服器規格與定價、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 華盛頓州 Tukwila — West Coast North = T4｜T31。**一組不符資格**，T7 與 T11 亦均不涵蓋此區。應循 **T4（主管 Kambiez Tahvilian）** 或 T31。
**CRM 狀態：** 2026-08-03 於 salesleads Search（Type = All）實查：無 lead、無 account、無 do-not-call 紀錄 — 從未註冊。

---

## 1. 結論摘要

Hostwinds LLC 是一家私人持股、位於華盛頓州 Tukwila（西雅圖都會區）的裸機、VPS、雲端與轉售型主機業者，創立於奧克拉荷馬州 Tulsa，持有自有 ASN（AS54290，303,360 個 IPv4 位址），營運三個租用的 colocation 站點——Seattle／Tukwila、Dallas 與 Amsterdam——另在其他七個市場轉售 colocation 容量。商業判定為**帶著採購權問號的全新開發（greenfield）AI 標的**：完全沒有任何 GPU 產品，目前可下單的專用伺服器機隊約 8 至 19 年舊、機隊中沒有任何一顆 Xeon Scalable、也沒有 EPYC，但公司已於 2026-04-29 被 HostPapa, Inc. 併購，資本支出決策權很可能在任何換機對話開始之前就已經北移。最強的單一證據是即時公開訂購表單 [clients.hostwinds.com/cart.php?gid=12](https://clients.hostwinds.com/cart.php?gid=12)：20 個 CPU-only SKU 涵蓋 Xeon 5300 Clovertown（2007）到 E3-1270 v6 Kaby Lake（2017），機架裡還有一顆桌上型 i7-3930K，卻沒有任何一顆 Xeon Scalable 或 EPYC——這是一個完全標價、可驗證的世代落差。最可能讓案子直接死掉的一件事就是這樁併購本身：[HostPapa 2026-04-29 新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/) 未揭露交易條件、未說明創辦人 Peter Holden 的留任承諾、也未公布資本支出計畫，而 [ARIN 對 AS54290 的 RDAP](https://rdap.arin.net/registry/autnum/54290) 已於 2026-05-12 改登記為 HostPapa（Buffalo, NY）——若 Hostwinds 已不再自行採購硬體，所有與 Tukwila 進行的規格討論都是白費。

---

## 2. 公司速覽

| 欄位 | 內容 | 證據 |
|---|---|---|
| **法人名稱** | Hostwinds LLC | BBB 檔案載明法定名稱與負責人「Mr. Peter Holden, Owner/Member」（[BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407)）。Washington Secretary of State 的 UBI 編號＝**GAP**——WA CCFS 為 JavaScript 應用，無法以抓取方式取得，Bizapedia／OpenCorporates 亦無紀錄 |
| **總部（實查地址）** | 12101 Tukwila International Blvd, Suite 320, 3rd Floor, Tukwila, WA 98168-2398——位於 Sabey Data Center Properties「Intergate.Seattle-West」園區。公司自行行銷為「Seattle, WA 98168」，BBB 則歸檔於 Tukwila | [BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407)；[公司簡介頁](https://www.hostwinds.com/company/overview) |
| **創立年份** | **矛盾未解。** 公司自述 2010 年創立於 Oklahoma 州 Tulsa；BBB 記載「Date of Business Started: March 14, 2016」（應為 WA 登記／BBB 建檔日，非原始設立日） | [公司簡介頁](https://www.hostwinds.com/company/overview)；[BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407) |
| **所有權** | **2026-04-29 起由 HostPapa, Inc. 併購持有。** 併購前：創辦人暨 CEO Peter Holden 為唯一所有人／成員；查無外部投資人或募資輪 | [HostPapa 新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)；由 [ARIN RDAP AS54290](https://rdap.arin.net/registry/autnum/54290)（最後異動 2026-05-12）獨立佐證 |
| **員工數** | **僅有第三方估計、彼此相差 40 倍、公司未揭露：** LinkedIn 自報 **51–200**・Growjo **30**・LeadIQ 約 **17**（2026-06）・RocketReach **16**・Craft.co **5** | [LinkedIn](https://www.linkedin.com/company/hostwinds)；[Growjo](https://growjo.com/company/Hostwinds)——**全部為第三方估計** |
| **營收** | **全部為第三方估計、從未經公司確認：** Growjo **$3.5M**・RocketReach **$3M**（2026）・ZoomInfo **<$5M**。公司自稱曾入選 Inc. 5000（未指明年份），暗示歷史成長高於此——**區間應視為軟性** | [Growjo](https://growjo.com/company/Hostwinds)——**第三方估計**，不得以事實形式寫入 CRM 或預測 |
| **ASN** | **AS54290**——RADB 代碼 HOSTWINDS-1（最後修改 2023-11-13），RADB 主要聯絡人 Peter Holden。ARIN 現回傳組織「HostPapa」、代碼 HOSTP-7、註冊 2011-12-05、最後異動 2026-05-12、地址 325 Delaware Avenue Suite 300, Buffalo NY 14202。75 個 IPv4 前綴 ＋ 4 個 IPv6 前綴；303,360 個 IPv4 位址 | [PeeringDB net/9308](https://www.peeringdb.com/net/9308)；[ARIN RDAP](https://rdap.arin.net/registry/autnum/54290) |
| **CRM 狀態** | **從未註冊**——2026-08-03 於 salesleads Search（Type = All）實查：無 lead、無 account、無 do-not-call 紀錄 | 內部 CRM 實查，2026-08-03 |
| **轄區／團隊** | Tukwila, WA → West Coast North（WA, OR, ID, MT, WY, AK, HI）＝ **T4｜T31**。**一組不符資格**；T7 與 T11 亦均不涵蓋此區。應循 **T4（主管 Kambiez Tahvilian）** 或 T31。母公司 HostPapa 位於 Burlington ON／Buffalo NY，若採購權確已北移，實際承作團隊可能還要再變更 | Territory Map-Jan.2026 (Rev.1)，Sales Territory Assign 分頁 |

---

## 3. 原始名單更正表

以下每一列都是原始工作名單中被本研究**推翻**或**無法證實**的敘述。首次接觸前必須先讀完本表，避免以錯誤前提開場。

| # | 原始名單的說法 | 判定 | 證據與正確說法 |
|---|---|---|---|
| 1 | Hostwinds 使用 Supermicro 和／或 Dell 硬體 | **未證實** | **完全查無：無任何公開來源具名 Supermicro／Dell／HPE 或任何 OEM。** 已檢索 hostwinds.com 產品頁、[/company/datacenters](https://www.hostwinds.com/company/datacenters)、[/colocation](https://www.hostwinds.com/colocation)、/product-docs、/guide、部落格，以及 WebHostingTalk、LowEndTalk、徵才啟事、PeeringDB 與新聞稿。公司只確認自有硬體——「Our hardware is directly owned and sold by us… no middlemen」（[公司簡介頁](https://www.hostwinds.com/company/overview)）——但從不揭露供應商。唯一旁證是其文件全篇使用泛稱 IPMI 詞彙：「full IPMI access」「BMC Cold Reset」「BMC Warm Reset」「Get Console Link」，且**全網域零則 iDRAC（Dell）或 iLO（HPE）**（[管理文件](https://www.hostwinds.com/guide/dedicated-server-management-controls/)）。**這是命名慣例的推論，不是證明。不得對客戶陳述，亦不得寫入 CRM。** |
| 2 | Hostwinds 總部在 Seattle | **部分確認** | 西雅圖都會區正確，但實際城市是 **Tukwila** 而非 Seattle。Hostwinds 自己把地址寫成「12101 Tukwila International Blvd #320, Seattle, WA 98168」，並自述位於「in the Pacific Northwest, just outside Seattle」；[BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407) 則將同一地址歸檔為 Tukwila, WA 98168-2398。郵遞區號 98168 是 Seattle 位址但涵蓋 Tukwila。該建物位於 Sabey Intergate.Seattle-West 資料中心園區。公司創立於 Oklahoma 州 Tulsa，且保有 Tulsa 據點（另有獨立的 BBB 檔案）。 |
| 3 | Hostwinds 銷售可自訂組態的專用伺服器 | **確認** | 公司自家產品頁逐字寫明：「Customize your server based on the amount of RAM and type of CPU(s) you need. You can also specify the size and amount of disks and even the RAID configuration」，以及「Every configuration is available to select based on the number of disks deployed, RAID 0 through RAID 60」（[專用伺服器頁](https://www.hostwinds.com/dedicated/servers)）。即時購物車銷售 20 個不同的基礎 CPU 平台，可逐單客製，並附 IPMI／KVM、電源控制與 ISO 掛載。**話術但書：** 這裡的「客製」指的是在一份老舊的固定 CPU 平台清單（X5355 至 E3-1270 v6）上由客戶自選 RAM／硬碟／RAID，**不是現代的 build-to-order**。 |
| 4 | 隱含前提：Hostwinds 是既有 Supermicro 客戶 | **反證（作為前提不成立）** | 在整份原始名單中，僅有兩家業者的 Supermicro 屬已確認；Hostwinds 僅是**推論訊號**等級，唯一依據是泛稱 IPMI 命名。以「我們知道你們在用 Supermicro」開場會立即失去可信度。**要用問的，不要用斷言的。** |
| 5 | **原始名單完全未提及——重大新事實** | **確認** | **Hostwinds 已於 2026-04-29 被 HostPapa, Inc. 併購**（[HostPapa 新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)），且 [ARIN 對 AS54290 的 RDAP](https://rdap.arin.net/registry/autnum/54290) 已於 2026-05-12 改登記為 HostPapa（325 Delaware Avenue Suite 300, Buffalo NY 14202）；bgp.tools 亦已將 AS54290 標為 HostPapa。**採購決策權很可能已移轉。** Tukwila 站點現為子公司據點，非集團總部。 |
| 6 | Hostwinds 曾收購 WeLoveServers | **未證實（社群來源）** | Web Hosting Talk 討論串「WeLoveServers bought by HostWinds?」指出 Hostwinds 取得 WeLoveServers 資產並續為既有客戶服務（[WHT 討論串](https://www.webhostingtalk.com/showthread.php?t=1536147)）。**原文對直接抓取回 HTTP 403，僅取得搜尋摘要；日期與條件均未確立。** |
| 7 | Tukwila 的資料中心技師職缺屬於 Hostwinds | **反證** | 檢索到的 Tukwila 機房技師職缺屬於 **Wowrack**，是位於 **12201** Tukwila International Blvd 的另一家公司（18,000 sq ft raised floor、3.0 MW）。Hostwinds 位於 **12101**。**不得誤植於 Hostwinds，兩處設施亦不可混為一談。** |

---

## 4. 領導層與所有權

**所有權現況。** Hostwinds LLC 自 2010 年起由創辦人自有、自籌資金經營，直至 **HostPapa, Inc. 於 2026-04-29 完成收購**（[HostPapa 新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)，交易條件未揭露）。網路資產的控制權移轉已由登記機構證實：[ARIN 對 AS54290 的 RDAP](https://rdap.arin.net/registry/autnum/54290) 仍載明 `ASName: HOSTWINDS`，但所屬組織已變更為 `OrgName: HostPapa, OrgId: HOSTP-7`，地址 325 Delaware Avenue Suite 300, Buffalo NY 14202，紀錄更新日 2026-05-12。就硬體採購而言更關鍵的是，[ColoCrossing 自身的併購說明](https://www.colocrossing.com/company/) 明載 Hostwinds 的 **基礎設施將移轉至 ColoCrossing**（即 HostPapa 的 Infrastructure Business Unit）——**這使採購決策點離開 Tukwila。** Hostwinds 在任何階段均查無董事會、機構投資人或外部股東。

### 4.1 具名人物一覽——Hostwinds、收購方、登記機構與網路聯絡人

證據等級定義：**primary-record**＝公司自行發布、登記機構或政府檔案 · **corroborated**＝兩個以上獨立來源互相印證 · **single-source**＝僅單一來源（多為資料聚合商），使用前須重新查證。

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC 紀錄 | 來源 |
|---|---|---|---|---|---|---|
| **Peter Holden** | Founder & CEO, Hostwinds LLC（交割前）。交割後角色**無法確定**——查無任何來源說明他在 2026-04-30 後是否續任 | 高階主管／所有人（創辦人） | **primary-record**——四項獨立原始紀錄：未遮蔽的 hostwinds.com WHOIS 同時列他為 Registrant、Admin 與 Tech；RADB AS54290 的 admin-c／tech-c；HostPapa 自身新聞稿稱他為「Founder」；hostwinds.com/company/overview 載明他為 2010 年創辦人 | peter@hostwinds.com（AS54290 IRR admin-c／tech-c） · domains@hostwinds.net 與 +1.206.886.0665（網域 WHOIS） · [linkedin.com/in/holdenpeter](https://www.linkedin.com/in/holdenpeter/) | **查無 FEC 紀錄。** 以雇主「hostwinds」查詢 fec.gov 個人政治獻金共得 11 筆、5 人，**無一筆為 Holden** | [HostPapa 新聞稿 2026-04-29](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/) · [RADB AS54290](https://bgp.he.net/AS54290#_whois) |
| **Peter Holden**（同一人——**登記機構人員**列） | hostwinds.com 的 Registrant、Administrative 與 Technical 聯絡人 | 登記機構人員（網域） | **primary-record**——ICANN 註冊商 WHOIS，無隱私代理遮蔽，組織欄為「Hostwinds」，地址 12101 Tukwila Intl Blvd #320, Seattle WA 98168 | domains@hostwinds.net · +1.206.886.0665 | 同上——查無紀錄 | [whois.namecheap.com](https://www.namecheap.com) |
| **Peter Holden**（同一人——**網路聯絡人**列） | AS54290（as-name HOSTWINDS-1）的 admin-c 與 tech-c | 網路聯絡人（IRR／RADB） | **primary-record**——**全 ASN 唯一一位具名的自然人網路聯絡人** | peter@hostwinds.com | 同上——查無紀錄 | [bgp.he.net/AS54290](https://bgp.he.net/AS54290#_whois) |
| **Dustin Waggoner** | Director of Operations, Hostwinds（2021-01 起）；此前 2018-09 至 2021-01 任 Datacenter Manager；2017-11 起任 Frontline Support Engineer | 高階主管／經理（維運） | **corroborated**——theorg.com 組織圖、RocketReach 管理層圖、LinkedIn 互相印證。個人檔案明載專長為「data center operations, and effective deployment and maintenance of hardware」。所在地 Kirkland, WA | [linkedin.com/in/dustinwaggoner](https://www.linkedin.com/in/dustinwaggoner/) · 直接信箱與電話＝**GAP** | **查無 FEC 紀錄**——不在雇主「hostwinds」的 11 筆紀錄中 | [theorg.com](https://theorg.com/org/hostwinds/org-chart/dustin-waggoner) |
| **Matthew Anderson** | Director of Backend Development, Hostwinds（2019-01 起）；此前為 Full Stack Developer（PHP、WHMCS 模組開發）；更早任職 Nintendo | 高階主管／經理（工程） | **corroborated**——theorg.com 組織圖，並經 RocketReach 印證（載明 Hostwinds 的 IT 部門共 11 人、由他領導）。所在地 Kirkland, WA | [linkedin.com/in/matthew-anderson-196822149](https://www.linkedin.com/in/matthew-anderson-196822149/) · 直接信箱與電話＝**GAP** | **查無 FEC 紀錄**——不在雇主「hostwinds」的 11 筆紀錄中 | [theorg.com](https://theorg.com/org/hostwinds/org-chart/matthew-anderson) |
| **Jamie Opalchuk** | Founder & CEO, HostPapa, Inc.（收購方；自 2006 年創辦 HostPapa） | 高階主管（收購方——最終決策者） | **primary-record**——HostPapa 自身 2026-04-29 併購新聞稿具名並列出職稱；Crunchbase、ZoomInfo、RocketReach 佐證 | press@hostpapa.com（企業媒體窗口） · LinkedIn 網址＝**GAP**，未能確認 | **查無 FEC 紀錄**——不在雇主「hostwinds」結果集中。其人在加拿大，依常理不會有美國聯邦個人政治獻金紀錄 | [HostPapa 新聞稿 2026-04-29](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/) |
| **Jon Biloh** | GM, Infrastructure Business Unit, HostPapa／General Manager, ColoCrossing。歷史上為 ColoCrossing／Velocity Servers Inc. 創辦人暨 CEO（2003 年創立） | 高階主管（收購方——基礎設施損益負責人） | **corroborated**——Send2Press 通稿（ColoCrossing 洛杉磯機房，1200 W 7th St，2025 年 1 月）具名引述其職稱為「General Manager, ColoCrossing (HostPapa Inc.)」；其 LinkedIn 標題為「GM, Infrastructure Business Unit at HostPapa」 | sales@colocrossing.com 與 1-800-518-9716（ColoCrossing 組織層級公開管道，非其專線） · [linkedin.com/in/jon-biloh](https://www.linkedin.com/in/jon-biloh/) | **GAP——未個別查核。** OpenFEC API 全程回 OVER_RATE_LIMIT，且 fec.gov 介面查詢僅以雇主「hostwinds」為範圍，無法涵蓋 HostPapa／ColoCrossing 雇主紀錄 | [Send2Press——ColoCrossing 洛杉磯機房](https://www.send2press.com/wire/colocrossing-expands-global-reach-with-new-los-angeles-datacenter/) |
| **Michael Carr** | COO, HostPapa, Inc. | 高階主管（收購方——營運） | **single-source**——RocketReach 管理層圖；可對應 LeadIQ 所公布的 HostPapa COO 遮蔽首字母「M. C.」，兩家聚合商在職務上一致，但**無任何 HostPapa 官方頁面可證實** | **GAP** | **GAP——未個別查核**，OpenFEC 遭速率限制 | [RocketReach](https://rocketreach.co/hostpapa-management_b5e12855f42e6a59) |
| **Corey Hammond** | Chief Marketing Officer, HostPapa, Inc.；同時是 Hostwinds 併購案的具名媒體窗口 | 高階主管（收購方——行銷） | **corroborated**——姓名為公司自行發布（2026-04-29 新聞稿的媒體聯絡人）；職稱來自 RocketReach | press@hostpapa.com（刊載於併購新聞稿） | **GAP——未個別查核**，OpenFEC 遭速率限制 | [HostPapa 新聞稿 2026-04-29](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/) |
| **Jorge Carvalho** | President, HostPapa, Inc. | 高階主管（收購方） | **single-source**——僅來自聚合式高管搜尋結果。不在所取得的 RocketReach 圖表中，且 hostpapa.com/about-hostpapa/leadership/ 回 HTTP 404，無官方名單可比對。**為 HostPapa 名單中最弱的一項，使用前必須重新查證** | **GAP** | **GAP——未個別查核**，OpenFEC 遭速率限制 | [RocketReach](https://rocketreach.co/hostpapa-management_b5e12855f42e6a59) |
| **David Woolford** | General Counsel, HostPapa, Inc. | 高階主管（收購方——法務） | **single-source**——聚合式高管搜尋。相關性在於：即使由業務負責人簽 PO，總法律顧問辦公室通常仍須會簽主採購／供應合約 | **GAP** | **GAP——未個別查核**，OpenFEC 遭速率限制 | [RocketReach](https://rocketreach.co/hostpapa-management_b5e12855f42e6a59) |
| **Ariel Antonelli** | Deputy General Counsel — CLO, CCO and CPO, HostPapa, Inc. | 高階主管（收購方——法務／法遵／隱私） | **single-source**——RocketReach 管理層圖，複合職稱如實照錄 | **GAP** | **GAP——未個別查核**，OpenFEC 遭速率限制 | [RocketReach](https://rocketreach.co/hostpapa-management_b5e12855f42e6a59) |
| **Danesh Waheed** | Director of Finance, HostPapa, Inc. | 高階主管（收購方——財務） | **single-source**——RocketReach 管理層圖。值得注意的是，**所有已觸及來源中 HostPapa 均查無具名 CFO**，代表資本支出核決很可能自此職位直接上呈 COO／CEO | **GAP** | **GAP——未個別查核**，OpenFEC 遭速率限制 | [RocketReach](https://rocketreach.co/hostpapa-management_b5e12855f42e6a59) |
| **Josey Devereaux** | Controller, HostPapa, Inc. | 經理（收購方——財務／會計） | **single-source**——聚合式高管搜尋。與應付帳款／PO 作業相關 | **GAP** | **GAP——未個別查核**，OpenFEC 遭速率限制 | [RocketReach](https://rocketreach.co/hostpapa-management_b5e12855f42e6a59) |
| **Ernie Q.**——姓氏**未公開**，來源端以首字母遮蔽，且在其他任何來源皆無法還原。**不得臆測補齊** | Vice President of Sales, Infrastructure BU (ColoCrossing), HostPapa | 高階主管（收購方——基礎設施 BU 商務） | **single-source（僅部分姓名）**——RocketReach 管理層圖。其職稱正好位於承接 Hostwinds 基礎設施的業務單位內 | **GAP** | **無法查核**——全名未知 | [RocketReach](https://rocketreach.co/hostpapa-management_b5e12855f42e6a59) |
| **Vince S.**——姓氏**未公開**，LeadIQ 僅公布首字母「V. S.」，後續搜尋僅還原出名字。**不得臆測補齊** | Chief Technology Officer, HostPapa, Inc. | 高階主管（收購方——技術） | **single-source（僅部分姓名）**——無 HostPapa 官方領導層頁可比對（該網址 404）。相關性在於：即使由 BU GM 簽核，集團 CTO 通常仍主導平台／硬體標準 | **GAP** | **無法查核**——全名未知 | [LeadIQ](https://leadiq.com/c/hostpapa/5a1d9b6e23000054008ad566) |
| **Michael George** | Frontend Web Developer, Hostwinds（職稱依 Datanyze；FEC 申報書載雇主「HOSTWINDS」、州別 WA） | 一般員工（個人貢獻者）——無採購權限 | **primary-record（FEC 申報）**；職稱為 single-source 佐證。Datanyze 獨立將其列於 12101 Tukwila International Blvd Fl 3 Ste 320，正是本案目標地址，可與同名的西雅圖市議員參選人明確區隔 | **GAP** | **查得紀錄**——GEORGE, MICHAEL，ActBlue，WA，雇主 HOSTWINDS，2024-08-02，$50.00。為 FEC 可證的最新一位 Hostwinds 員工，故併購當時很可能仍在職 | [FEC 個人政治獻金，雇主「hostwinds」](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=hostwinds) |
| **Benjamin Bream** | Hostwinds——**確切職稱為 GAP**；LinkedIn 可證任職關係，FEC 申報書載雇主「HOSTWINDS, L.L.C.」、州別 WA | 一般員工 | **primary-record（FEC 申報）**；LinkedIn 個人檔案（學歷 Tacoma Community College）佐證任職事實 | [linkedin.com/in/benjaminbream](https://www.linkedin.com/in/benjaminbream/) | **查得紀錄**——BREAM, BENJAMIN，ActBlue，WA，雇主 HOSTWINDS, L.L.C.，2020-02-18，$25.00。注意該申報使用完整法人格式「L.L.C.」 | [FEC 個人政治獻金，雇主「hostwinds」](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=hostwinds) |
| **Nathan Powers** | Software Developer, Hostwinds（職業欄為 FEC 申報自填）；Tulsa OK 74136 | 前員工（個人貢獻者） | **primary-record**——已取得完整 FEC 明細面板。Tulsa 所在地與 Hostwinds 遷往西雅圖前的沿革一致 | **GAP** | **查得紀錄**——POWERS, NATHAN，Tulsa OK 74136，職業 SOFTWARE DEVELOPER，雇主 HOSTWINDS，2016-04-30 兩筆 ActBlue 獻金 $20.00 與 $5.00 | [FEC 個人政治獻金，雇主「hostwinds」](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=hostwinds) |
| **Paul Johnson** | Tech Support Engineer, Hostwinds（職業欄為 FEC 申報自填）；Tulsa OK 74116 | 前員工（個人貢獻者） | **primary-record**——已取得完整 FEC 明細面板。為所查得年代最早的 Hostwinds 員工 | **GAP** | **查得紀錄**——JOHNSON, PAUL，Tulsa OK 74116，職業 TECH SUPPORT ENGINEER，雇主 HOSTWINDS，ActBlue，2015-09-18，$10.00 | [FEC 個人政治獻金，雇主「hostwinds」](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=hostwinds) |
| **Guy Hopkins** | Hostwinds LLC——**確切職稱未公開**；FEC 申報書載雇主「HOSTWINDS LLC」、州別 PA。公司當時位於 Tulsa／Seattle 而其人在 PA，顯示可能為遠端工作者 | 前員工——職能未確認 | **primary-record（FEC 申報）**；角色與職稱未經證實，查無可佐證的個人檔案 | **GAP** | **查得多筆紀錄**——HOPKINS, GUY，ActBlue，PA，雇主 HOSTWINDS LLC，2016-02-10 至 2018-04-06 共六筆（2016-02-10 兩筆 $6.66、2016-03-14 $6.66、2016-03-31 $9.99、2016-09-30 $1.00、2018-04-06 $5.00）。職業欄無法取得 | [FEC 個人政治獻金，雇主「hostwinds」](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=hostwinds) |
| **Patrick Ringland** | Principal and Managing Director, CLA Meridian Capital——Hostwinds 的賣方 M&A 顧問 | 外部顧問（交易） | **primary-record**——顧問公司自行發布的新聞稿具名。為賣方團隊資深銀行家；可證此案為投行主導的競標流程，而非雙邊私下成交 | 僅有 meridianib.com 公司層級聯絡管道 | **未查核**——非目標公司；雇主別 FEC 查詢範圍限於「hostwinds」 | [CLA Meridian Capital 新聞稿](https://meridianib.com/press-releases/cla-meridian-capital-advises-hostwinds-on-acquisition-by-hostpapa/) |
| **Tim Johnson** | Vice President, CLA Meridian Capital——賣方 M&A 顧問 | 外部顧問（交易） | **primary-record**——顧問公司新聞稿具名 | 僅公司層級聯絡管道 | **未查核**——非目標公司 | [CLA Meridian Capital 新聞稿](https://meridianib.com/press-releases/cla-meridian-capital-advises-hostwinds-on-acquisition-by-hostpapa/) |
| **Andrew Cardillo** | Marketing Director, CLA Meridian Capital | 外部顧問（交易——溝通） | **primary-record**——顧問公司新聞稿具名 | 僅公司層級聯絡管道 | **未查核**——非目標公司 | [CLA Meridian Capital 新聞稿](https://meridianib.com/press-releases/cla-meridian-capital-advises-hostwinds-on-acquisition-by-hostpapa/) |
| **NETOPS**——ARIN 代碼 NETOP351-ARIN。**角色帳號，未公開任何自然人姓名** | 現持有 AS54290 之組織的 OrgAdmin（HostPapa, Inc.，5063 North Service Rd Suite 102, Burlington ON L7L 5H6） | 網路聯絡人（ARIN POC） | **primary-record**——登記機構紀錄。ARIN 此處登記的是角色帳號而非具名個人，故此來源不產出人名 | net-ops@hostpapa.com · +1-905-315-3455 | 不適用——角色帳號 | [ARIN RDAP NETOP351-ARIN](https://rdap.arin.net/registry/entity/NETOP351-ARIN) |
| **NETTECH**——ARIN 代碼 NETTE9-ARIN。**角色帳號，未公開任何自然人姓名** | 現持有 AS54290 之組織的 OrgTech（HostPapa, Inc.，325 Delaware Avenue Suite 300, Buffalo NY 14202） | 網路聯絡人（ARIN POC） | **primary-record**——登記機構紀錄。**更新日 2026-05-01，即交割後第二天**，可佐證控制權移轉 | net-tech-global@hostpapa.com · +1-905-315-3455 | 不適用——角色帳號 | [ARIN RDAP NETTE9-ARIN](https://rdap.arin.net/registry/entity/NETTE9-ARIN) |
| **NETABUSE**——ARIN 代碼 NETAB23-ARIN。**角色帳號，未公開任何自然人姓名** | 現持有 AS54290 之組織的 OrgAbuse | 網路聯絡人（ARIN POC） | **primary-record**——登記機構紀錄 | net-abuse-global@hostpapa.com · +1-905-315-3455 | 不適用——角色帳號 | [ARIN RDAP NETAB23-ARIN](https://rdap.arin.net/registry/entity/NETAB23-ARIN) |
| **查無具名聯絡人——PeeringDB 回傳空的聯絡人集合** | PeeringDB net id 9308／org id 13221 確實存在（Content、20-50 Gbps、Selective 政策、Global、ix_count 1、地址 12101 Tukwila International Blvd #320），但 `/api/poc?net_id=9308` 回傳空的 data 陣列 | 網路聯絡人（PeeringDB）——**GAP** | **primary-record（確認為零回傳）**——該組織**完全未公開**任何政策、技術或 NOC 聯絡人。poc_updated 停留在 2020-07-27、紀錄最後異動 2022-07-27，亦即併購後未更新 | 無公開管道 | 不適用 | [PeeringDB API net asn=54290](https://www.peeringdb.com/api/net?asn=54290) |
| **查無具名 DMCA 代理人** | Hostwinds 服務條款提及「designated DMCA Agent」，卻**從未具名**；唯一公開管道為濫用檢舉信箱 | 公開濫用檢舉管道——**人名為 GAP** | **primary-record（確認為零回傳）**——於美國著作權局 DMCA 指定代理人名錄以「Hostwinds」查詢亦無任何結果 | abuse@hostwinds.com | 不適用 | [Hostwinds 服務條款](https://www.hostwinds.com/legal/terms) |

### 4.2 登記機構紀錄

| 姓名 | 身分／職權 | 檔案內容 | 檔案日期 | 來源 |
|---|---|---|---|---|
| **未取得任何主管姓名——Washington Secretary of State CCFS 無法連通** | 原可提供 Hostwinds LLC 的 governors／members／managers、註冊代理人、年報簽署人，以及歷任登記主管的申報沿革 | WA SOS Corporations & Charities Filing System 商業搜尋——**遭封鎖**。公開 API（ccfs-api.prod.sos.wa.gov/api/BusinessSearch/GetBusinessSearchList）在所有嘗試中均回 HTTP 400，內容為「System verification in progress, please wait.」：包括直接 curl、附完整瀏覽器標頭／Referer／Origin 的 curl，以及在已通過 Cloudflare Turnstile 的真實 Chrome 工作階段中發出的同源 fetch。Angular 介面本身可載入，但深層連結僅顯示空白結果頁。替代來源同樣失敗——OpenCorporates（HAProxy CAPTCHA）、Bizapedia（安全驗證頁），data.wa.gov 上兩組資料集（f9jk-mm39、4wur-kfnr）皆註冊為非表格式的連結型資產。**此為真正未解的 GAP，而非查無資料——UBI、註冊代理人與主管名單仍屬未知** | 嘗試日 2026-08-04 | [ccfs.sos.wa.gov](https://ccfs.sos.wa.gov/#/BusinessSearch) |
| **Peter Holden** | AS54290 的 admin-c 與 tech-c（行政與技術聯絡人） | RADB／IRR aut-num 物件：`aut-num: AS54290 / as-name: HOSTWINDS-1 / descr: Hostwinds / admin-c: Peter Holden / tech-c: Peter Holden`，電子郵件 peter@hostwinds.com | 最後異動 2023-11-13 | [bgp.he.net/AS54290](https://bgp.he.net/AS54290#_whois) |
| **Peter Holden** | hostwinds.com 網域的 Registrant、Administrative 與 Technical 聯絡人（組織「Hostwinds」，地址 12101 Tukwila Intl Blvd #320, Seattle WA 98168） | whois.namecheap.com 的 ICANN 註冊商 WHOIS——**未遮蔽、無隱私代理**。Registry Domain ID 1605411348_DOMAIN_COM-VRSN。聯絡信箱 domains@hostwinds.net，電話 +1.2068860665 | 網域建立 2010-07-07；WHOIS 紀錄最後更新 2023-07-26；到期 2033-07-07 | [whois.namecheap.com](https://www.namecheap.com) |
| **無自然人姓名——僅角色帳號** | 現持有 AS54290 之組織的 OrgAdmin | ARIN POC 代碼 NETOP351-ARIN，名稱「NETOPS」，公司「Hostpapa, Inc」，5063 North Service Rd Suite 102, Burlington ON L7L 5H6, Canada；電話 +1-905-315-3455；信箱 net-ops@hostpapa.com | POC 登記 2020-11-17；更新 2025-12-12 | [ARIN RDAP NETOP351-ARIN](https://rdap.arin.net/registry/entity/NETOP351-ARIN) |
| **無自然人姓名——僅角色帳號** | 現持有 AS54290 之組織的 OrgTech | ARIN POC 代碼 NETTE9-ARIN，名稱「NETTECH」，公司「HostPapa, Inc」，325 Delaware Avenue Suite 300, Buffalo NY 14202；電話 +1-905-315-3455；信箱 net-tech-global@hostpapa.com。**請注意更新日期——在併購交割後第二天即被異動，佐證控制權移轉** | POC 登記 2020-11-17；更新 2026-05-01 | [ARIN RDAP NETTE9-ARIN](https://rdap.arin.net/registry/entity/NETTE9-ARIN) |
| **無自然人姓名——僅角色帳號** | 現持有 AS54290 之組織的 OrgAbuse | ARIN POC 代碼 NETAB23-ARIN，名稱「NETABUSE」，電話 +1-905-315-3455，信箱 net-abuse-global@hostpapa.com | 取得日 2026-08-04 | [ARIN RDAP NETAB23-ARIN](https://rdap.arin.net/registry/entity/NETAB23-ARIN) |
| **組織層級紀錄——控制權移轉證據，無自然人姓名** | AS54290（即 Hostwinds ASN）的登記持有人 | ARIN whois：`ASName: HOSTWINDS, ASHandle: AS54290, RegDate: 2011-12-05, Updated: 2026-05-12`，但 `OrgName: HostPapa, OrgId: HOSTP-7`，地址 325 Delaware Avenue Suite 300, Buffalo NY 14202。**ASN 名稱仍為 Hostwinds，所屬組織卻已是 HostPapa——這是網路資產控制權移轉的登記機構硬證據，時點約在交割後兩週** | ASN 登記 2011-12-05；紀錄更新 2026-05-12；HOSTP-7 組織紀錄更新 2025-10-05 | [ARIN RDAP autnum 54290](https://rdap.arin.net/registry/autnum/54290) |
| **未取得簽署人姓名——USPTO 商標** | 原可提供 HOSTWINDS 商標的聲明書簽署人姓名／職稱，以及登記在案的通訊代表人 | HOSTWINDS 文字商標，序號 87125319，註冊號 5160503，國際分類 038（VPN 服務、網站代管、為他人代管網站、網域註冊、電腦安全），所有人欄位為「Hostwinds」。**簽署人與通訊代表人無法取得**——TSDR JSON API 現已要求註冊 API key，Justia 鏡像頁回 HTTP 403 | 申請 2016-08-03；註冊 2017-03-14 | [Justia——HOSTWINDS 87125319](https://trademarks.justia.com/871/25/hostwinds-87125319.html) |

### 4.3 採購決策圈（buying committee）

| 姓名 | 對伺服器採購為何重要 | 接觸方式 |
|---|---|---|
| **Jon Biloh**——GM, Infrastructure Business Unit, HostPapa／GM, ColoCrossing | **本名單中最關鍵的單一人物，應視為經濟決策買方。** ColoCrossing 自身的併購說明明載 Hostwinds 的基礎設施「will be transitioned to ColoCrossing」，而該業務單位由他為 HostPapa 執掌。他自 2003 年創辦並經營 ColoCrossing／Velocity Servers，在今日橫跨美國／都柏林／多倫多共 10 座機房的版圖上，擁有二十年親自採購與上架伺服器的經驗，並公開具名推動產能擴張（2025 年 1 月洛杉磯機房）。交割後 Hostwinds 的機隊更新幾乎必然是他損益表內的 ColoCrossing 產能決策，而非 Tukwila 的在地決策 | **不要把 Hostwinds 當成獨立客戶來提案**——應鎖定 ColoCrossing／HostPapa Infrastructure BU 的整體機隊，並以兩樁剛完成的併購（Hostwinds 2026-04-29 與 Tailor Made Servers 2026-04-17，相隔 12 天）作為整併與標準化的觸發點切入。經由公開的 ColoCrossing 業務窗口（sales@colocrossing.com、1-800-518-9716）明確指名要找 Infrastructure BU GM，同時併行 [linkedin.com/in/jon-biloh](https://www.linkedin.com/in/jon-biloh/)。切入角度：把三個新併入的機隊（Seattle、Dallas、Amsterdam）收斂到同一組硬體 SKU。他公開表述的關注點是延遲、市場覆蓋與擴張速度——**訴求應圍繞機櫃密度與部署時程，而非單價** |
| **Jamie Opalchuk**——Founder & CEO, HostPapa, Inc. | 收購方的創辦人兼 CEO，在 Hostwinds 新聞稿中親自具名受訪，並主導一連串積極併購（Jumpline、ColoCrossing、CloudBlue、Deluxe web hosting、Tailor Made Servers、Hostwinds）。在一家由創辦人主導、**且所有來源皆查無具名 CFO** 的私人公司中，重大資本支出幾乎必然需要他核准。凡屬全機隊級（而非例行汰換）的案子，最終簽核在他 | 屬高層對高層層級，非交易性接觸。最佳暖線是併購與整併敘事——HostPapa 已公開承諾在 shared、cloud VPS、dedicated 與 reseller 上建立「full-stack infrastructure capabilities」，本質上就是硬體標準化的題目。初期可經 press@hostpapa.com／Corey Hammond（CMO），或透過執行賣方流程的 CLA Meridian Capital 銀行團。**切勿以規格表開場，應以整併後機隊的總持有成本開場** |
| **Dustin Waggoner**——Director of Operations, Hostwinds | **技術擁護者，也是唯一實際碰觸 Tukwila 硬體的人。** 升任前於 2018-09 至 2021-01 擔任 Datacenter Manager，公開檔案明確載明專長為「data center operations and effective deployment and maintenance of hardware」。併購後他不會簽 PO，但他撰寫或驗證規格、負責安裝與實際上架，**他一反對，案子就死**。他也最清楚西雅圖機隊目前哪些設備正在故障或老化 | 工程師對工程師，**不要用採購框架**。經 [linkedin.com/in/dustinwaggoner](https://www.linkedin.com/in/dustinwaggoner/) 接觸，所在地 Kirkland WA。最好的切入點正是這場整併：他即將把 HostPapa／ColoCrossing 的硬體標準套用到自己一手建起的機隊上，而這正是規格影響力可被爭取的時刻。先讓他定出參考組態，再由他往上帶到 Biloh。查無公開直接信箱——僅能走 LinkedIn 或維運窗口 |
| **Michael Carr**——COO, HostPapa, Inc. | 收購方的集團營運主管。在一家有 Director of Finance 與 Controller、**卻沒有具名 CFO** 的公司裡，COO 最可能是介於 BU GM 與 CEO 之間掌握營運與資本支出預算的人，也最可能是橫跨 Seattle、Dallas、Amsterdam 三站併購後整併計畫的負責人 | 作為 Biloh 之外的次要／併行路線，用途是由上而下製造拉力。應在 BU 層級的技術案成形之後才接觸，否則會被解讀為越過 GM。**其職稱僅來自聚合商，在任何對外訊息具名前必須重新查證** |
| **Danesh Waheed**——Director of Finance, HostPapa, Inc. | 看來是 HostPapa 財務體系中最資深的具名職位——所有已觸及來源皆未出現 CFO。核發與核准 PO 文件與付款條件的人，若非此人便在其之下。與融資架構、租賃或購置取捨、以及多站分批交付條件相關，屬**商務決策確定之後**的議題 | **不要從這裡開場。** 待 Biloh 或 Carr 在技術上點頭後再引入，用以就三個新併入站點安排條件。另需注意 HostPapa 正處於併購整合期，可能偏好分階段資本支出 |
| **Peter Holden**——Hostwinds LLC 創辦人、交割前 CEO 兼所有人 | 他自 2010 年創辦公司，依多方來源為唯一所有人，並在成交前一直是網域與 AS54290 的 registrant、admin 與技術聯絡人。交割前他毫無疑問就是簽核人。**交割後其職權未經證實**——查無任何來源說明他是否續任，且在代管業整併案中，賣方創辦人常於 12 個月內離開。就理解既有機隊、既有供應商與汰換週期而言，他仍是價值最高的關係人 | **先視為情報與轉介來源，僅在能確認他保有營運職務時才視為簽核人。** 可循公開登記聯絡管道直接接觸：peter@hostwinds.com（AS54290 IRR admin-c／tech-c）與 domains@hostwinds.net／+1.206.886.0665（網域 WHOIS）。開場應詢問 HostPapa 併購後由誰掌握基礎設施決策，而非直接提案——由他暖轉介到 Biloh 或 Waggoner，價值遠高於對任一人冷開發 |
| **Ernie Q.**（姓氏未公開）——VP of Sales, Infrastructure BU (ColoCrossing), HostPapa | 位於承接 Hostwinds 的同一業務單位內。身為業務主管，他不是伺服器的買方，但他負責這批產能所要服務的營收計畫，而且是通往 Infrastructure BU 最容易接觸的公開入口。**屬影響者與內部導引者，非決策者** | 用作組織地圖訪談而非提案：以夥伴／供應商身分談 ColoCrossing 的 dedicated server 與 colocation 藍圖，通常就能問出誰定規格、誰簽核硬體。**務必先還原其姓氏——來源僅公開遮蔽首字母，任何對外訊息都不得填入臆測的姓名** |
| **Matthew Anderson**——Director of Backend Development, Hostwinds | 領導 Hostwinds 約 11 人的 IT／工程團隊，掌管控制平面與佈建堆疊（WHMCS／PHP 背景）。可影響形塑硬體選型的工作負載與平台需求，**但無採購權限**。為具名決策圈中優先度最低者 | 僅在提案涉及佈建、自動化或雲端控制平面時才具相關性。管道為 [linkedin.com/in/matthew-anderson-196822149](https://www.linkedin.com/in/matthew-anderson-196822149/)，所在地 Kirkland WA。用於佐證 Waggoner 的規格，而非作為獨立切入點 |

### 4.4 未能補齊的角色

**以下每一項均為 GAP——皆為實際查找後未取得，而非單純未列出：** Hostwinds LLC 登記在案的 governors／members／managers——GAP（WA SOS CCFS 於 API 與 UI 兩端皆遭機器人防護阻擋） · Hostwinds LLC 註冊代理人姓名與地址——GAP（同一阻礙） · Hostwinds LLC 的 UBI 號碼、設立日期與申報沿革（含歷任登記主管）——GAP（同一阻礙） · Hostwinds LLC 年報簽署人——GAP（同一阻礙） · Delaware／Nevada 平行實體查核——GAP（所有來源均將營運實體記為「Hostwinds LLC」並搭配華盛頓州地址，服務條款逐字確認，且查無 DE／NV 控股公司證據；惟兩州登記處均未直接搜尋，故無法排除控股架構） · Hostwinds 的 CFO 或任何財務主管——GAP · Hostwinds 的 CTO——GAP（LeadIQ 僅顯示遮蔽首字母「T. M.」，任何來源皆無法還原全名） · HostPapa CTO 全名——部分／GAP（僅公開為「V. S.」／名字「Vince」，姓氏從未出現，**未予臆測**） · HostPapa Infrastructure BU 業務副總全名——部分／GAP（僅公開為「Ernie Q.」，姓氏從未出現，**未予臆測**） · HostPapa 的 CFO——GAP（所有已觸及來源皆無具名 CFO，僅出現 Director of Finance 與 Controller，且 hostpapa.com/about-hostpapa/leadership/ 回 HTTP 404，並無官方高管名單可比對） · Hostwinds、ColoCrossing 或 HostPapa 的專職採購／供應鏈主管——三家皆 GAP · Hostwinds 的 VP Infrastructure 或 VP Engineering——GAP（該組織在 CEO 之下似乎最高僅到 Director 層級） · AS54290 的具名 NOC 或網路工程師——GAP（ARIN 僅公開角色帳號，PeeringDB 完全未公開聯絡人；唯一具名的自然人網路聯絡人是 IRR 物件上的 Peter Holden） · 具名的 DMCA 指定代理人——GAP（服務條款提及卻從未具名，且美國著作權局名錄以「Hostwinds」查詢無結果） · Dallas 與 Amsterdam 站點的場站主管——GAP（新聞報導可確認站點存在，卻未具名任何人） · 併購後 Hostwinds 品牌的日常負責人／總經理——GAP（查無任何來源說明品牌日常由誰負責，亦無來源說明 Peter Holden 在 2026-04-30 後是否保有職務） · Hostwinds LLC 的董事會與投資人——GAP（所有來源均描述其自 2010 年起為創辦人自有、自籌資金；查無董事會、機構投資人或外部股東，交易條件亦未揭露） · Benjamin Bream 與 Guy Hopkins 的確切職稱——GAP（兩人皆由原始 FEC 申報證實為 Hostwinds 員工，但職業欄無法取得） · HOSTWINDS 商標的聲明書簽署人與登記通訊代表人——GAP（TSDR 現需註冊 API key，Justia 鏡像回 HTTP 403） · UCC-1 擔保權人與債務人簽署人——GAP（華盛頓州 UCC 紀錄由 Dept of Licensing 保管，須以互動式或付費方式查詢）。

### 4.5 已實際查詢的來源

**產出人名或登記機構硬證據者：** ARIN Whois／RDAP（AS54290 與其三個 POC；確認組織已移轉至 HostPapa，三個 POC 均為角色帳號、無自然人姓名） · 經 bgp.he.net 取得的 RADB／IRR（具名 Peter Holden 為 admin-c 與 tech-c，並取得 peter@hostwinds.com） · whois.namecheap.com 的 hostwinds.com 註冊商 WHOIS（未遮蔽，具名 Peter Holden 為 Registrant／Admin／Tech） · HostPapa 自身 2026-04-29 併購新聞稿（Holden、Opalchuk、Hammond） · ColoCrossing 企業部落格（「infrastructure will be transitioned to ColoCrossing」此一使採購決策點外移的關鍵發現） · CLA Meridian Capital 新聞稿（Ringland、Johnson、Cardillo；法律顧問 Davis Wright Tremaine LLP 僅具事務所名稱） · Send2Press 通稿（ColoCrossing 洛杉磯機房，三度引述 Jon Biloh 之 GM 職稱） · 以雇主「hostwinds」查詢 FEC 個人政治獻金（11 筆、5 人，全數捐予 ActBlue） · theorg.com Hostwinds 組織圖（恰好三位具名領導人） · RocketReach 的 Hostwinds、HostPapa 與 ColoCrossing 管理層圖 · LeadIQ／ZoomInfo／Datanyze／Clodura／Visual Visitor／Growjo／Wiza／ContactOut（員工數與地址；Datanyze 於完全相同的目標地址佐證了 Michael George 的 FEC 命中）。

**已查詢但查無結果或遭封鎖者——上述缺口是查過的結果，不是偷懶：** Washington Secretary of State CCFS（以 curl、附瀏覽器標頭的 curl、已通過 Cloudflare Turnstile 之真實 Chrome 工作階段的同源 fetch、直接開啟 API 網址、以及 Angular 介面共六種不同方式嘗試，每次皆回 HTTP 400「System verification in progress, please wait.」；**完全未取得任何主管、governor、註冊代理人、UBI 或申報沿革資料——本節最大的單一缺口**） · data.wa.gov 上的 SOS／DOR 鏡像資料集（已定位 f9jk-mm39 與 4wur-kfnr，但兩者皆註冊為非表格式的連結型資產） · OpenCorporates（HAProxy CAPTCHA） · Bizapedia（安全驗證頁） · Delaware 與 Nevada 登記處（未搜尋——列為已知缺口，而非查無資料） · OpenFEC API（共用 DEMO_KEY 每次皆回 OVER_RATE_LIMIT，這正是 Michael George、Benjamin Bream 與 Guy Hopkins 職業欄缺漏、以及無法對 HostPapa／ColoCrossing 名單進行雇主別 FEC 查核的原因） · CourtListener／RECAP（14 個案號、60 份文件，全部是 Hostwinds 以第三方代管業者或傳票受送達人身分出現的案件；**其中無任何主管、成員或經理人以當事人或具結人身分具名**；判決意見搜尋回 0 筆） · 美國著作權局 DMCA 指定代理人名錄（「Hostwinds」無紀錄） · USPTO TSDR（現需 API key）與 Justia 鏡像（HTTP 403） · PeeringDB POC 端點（空的 data 陣列——完全未公開任何聯絡人） · King County／Tukwila 不動產紀錄（地號 092304-9309，登記所有人「INTERNATIONAL GATEWAY WEST」，出租窗口為 Sabey Corporation——Hostwinds 為承租戶，故稅籍紀錄不會揭露任何主管） · 華盛頓州 Dept of Licensing 的 UCC-1 申報（僅限互動式或付費查詢，無法以程式執行） · 求職平台 ZipRecruiter、Indeed、Glassdoor、Built In Seattle（任何職缺皆未揭露具名的招募主管、招募人員或「reports to」職稱） · NANOG、HostingCon、WHD.global、DataCenter World 與 CloudFest 的講者簡介（查無任何 Hostwinds 人員的講席或名單） · WebHostingTalk 與 LowEndTalk（相關討論串存在，但無任何員工帳號可對應到真實姓名） · HostPapa 官方領導層頁（HTTP 404——並無公司自行發布的高管名單，這正是多數 HostPapa 名字僅列為 single-source 的原因） · HostingAdvice 與 HostAdvice 的創辦人專訪（兩者皆 HTTP 403，內文無法擷取） · whoisrequest.com 的歷史 WHOIS（HTTP 403；影響輕微，現行 WHOIS 本已未遮蔽） · ZoomInfo MCP 連接器（**無法使用——該連接器需 OAuth 授權，而本次為非互動式工作階段，故無法使用其採購決策圈與聯絡資料補全工具；若於 claude.ai 連接器設定或以互動式工作階段執行 `claude mcp`／/mcp 完成授權，可補上上述數項被遮蔽的姓氏與缺漏的直接信箱**）。

---

## 5. 據點與機房

Hostwinds 只聲稱擁有**三個**自有資料中心，卻在**十個**市場銷售 colocation。公司明說自有*硬體*——「Our hardware is directly owned and sold by us」——但從未聲稱擁有任何建物，並自述使用「SAS Type II, audited, Tier 3+ Data centers」，**這是第三方設施的用語。所有站點均為租用／colocation。**

| 站點 | 設施／營運商 | 自有或租用 | 面積 | 電力 | 證據 |
|---|---|---|---|---|---|
| **Seattle／Tukwila, WA**——12101 Tukwila International Blvd（與總部辦公室同址） | Sabey Data Center Properties，Intergate.Seattle-West 園區（Sabey 為園區房東） | **租用／colocation** | **GAP**——Hostwinds 未公布任何 cage／機櫃／sq ft 數字。僅有園區層級數字：Intergate.Seattle-West 約 173,000 sq ft，服務多家 colocation 業者 | **自身足跡＝GAP。** 公司宣稱 2N 備援、雙獨立電源、N+1 發電機備援、備援電源供應器與獨立饋線 | [機房頁](https://www.hostwinds.com/company/datacenters)；總部地址見 [公司簡介頁](https://www.hostwinds.com/company/overview) 與 [BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407)。**注意：隔壁 12201 Tukwila International Blvd 是 Wowrack 的資料中心（18,000 sq ft raised floor、3.0 MW），不同地址、不同公司，不可混為一談** |
| **Dallas, TX**——Infomart Data Center, 1950 N Stemmons Fwy, Dallas, TX 75207 | Infomart carrier hotel | **租用／colocation**——Hostwinds 擁有伺服器，不擁有設施 | **僅有公司公布的歷史數字：** 約 40 台伺服器、跨 3 個機箱，該機箱可擴充至 60 台，出自約 2012–2013 年的 Hostwinds 新聞部落格。**十餘年前的陳舊數字，幾可確定遠低於現況，只能當地板值。現況＝GAP。** 原網址（hostwinds.com/blog/news/37/）現回 HTTP 404，數字由搜尋索引片段取得——**標記為公司公布之歷史值、未於原始頁面驗證** | **GAP**——未公布任何 kW／機櫃數字 | Dallas Infomart 之名稱與街道地址見 Hostwinds 機房／速度測試資料（[速度測試文件](https://www.hostwinds.com/tutorials/how-to-test-speed-to-hostwinds-data-centers)），並由 [HostPapa 併購新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/) 佐證。他處描述為災難備援／地理分散站點 |
| **Amsterdam, Netherlands**——Global Switch Amsterdam West, Johan Huizingalaan 759, 1066 VH Amsterdam | Global Switch | **租用／colocation** | **GAP** | **GAP** | [速度測試文件](https://www.hostwinds.com/tutorials/how-to-test-speed-to-hostwinds-data-centers)；Amsterdam 於 [HostPapa 新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/) 中確認為三個機房之一，並被稱為此案帶來的「European infrastructure」 |
| **Colocation 轉售市場（10 個）**——Buffalo、Dallas、Atlanta、Chicago、Seattle、San Jose、Los Angeles、New York City、Dublin、Toronto | **該頁完全未揭露設施名稱、營運商、地址、面積或電信夥伴** | **幾可確定是夥伴／轉售空間，非 Hostwinds 自營**——公司只曾聲稱三個自有機房，卻在十個市場賣 colo，另外七個是轉售。**注意 Buffalo NY 與 Toronto 正好對應 HostPapa 自身版圖**（HostPapa 的 ARIN 地址即在 Buffalo NY），此清單可能已反映併購後的合併容量 | 公開規格僅四級：1U 單機・半櫃 20U・整櫃 42U・cage 2 × 42U | 各 SKU 公開電力：單機 1A/120V・半櫃 **1.92 kW**・整櫃 **3.84 kW**・cage **7.68 kW**。**密度很低——整櫃 3.84 kW／42U 在未升級電力與冷卻之前，無法承載現代 GPU 或高核心數節點** | [colocation 頁](https://www.hostwinds.com/colocation) 逐字列出十個市場與四個機櫃／電力級距 |

**規模。** 現行伺服器與機櫃數**未公開＝GAP**。唯一硬數字是上述 Dallas 的陳舊數字。最佳現況代理是 IP 空間：AS54290 originates **75 個 IPv4 前綴 ＋ 4 個 IPv6 前綴，合計 303,360 個 IPv4 位址**——約 4.6 個 /16，屬有意義的 VPS／主機代管足跡，與「低至數千台實體主機」相符。**IP 數不是伺服器數，絕不得如此呈現。**

---

## 6. 硬體機隊

本節證據等級：**已確認**＝業者第一手具名揭露或多方獨立佐證・**旁證**＝業者行為強烈指向但從未具名・**推論**＝僅由 CPU／機殼形狀推得・**反證**＝證據與原始名單相反・**GAP**＝查無。

| 供應商／項目 | 證據等級 | 證據實際說了什麼 |
|---|---|---|
| **任何伺服器 OEM（Supermicro、Dell、HPE 或其他）** | **GAP——完全未公開** | Hostwinds 的官網、文件、部落格、徵才啟事、論壇足跡與新聞報導，**沒有任何公開來源具名任何伺服器 OEM**。**這是真實的證據缺口，不是檢索不足**——對 hostwinds.com 的站內限定檢索，以及 WebHostingTalk 與 LowEndTalk 的論壇檢索，均未取得任何具名供應商。公司最強的說法也只是泛稱：「Enterprise Hardware」「state-of-the-art infrastructure」，以及自有硬體聲明「Our hardware is directly owned and sold by us… we own our work」與「no middlemen」——**這確認了他們直接買、直接持有機器（對原廠提案有利），但完全沒有具名供應商**（[公司簡介頁](https://www.hostwinds.com/company/overview)） |
| **Supermicro／whitebox（由 BMC 命名慣例推得）** | **旁證——僅為推論，不得當作事實陳述** | Hostwinds 自家文件把專用伺服器控制台描述為提供「full IPMI access to VNC KVM controls, power controls, and ISO mounting」，按鈕為「BMC Cold Reset」「BMC Warm Reset」「Get Console Link」；產品頁寫「Nearly all of our Dedicated Servers have full IPMI access.」。**有品牌 BMC 的原廠通常以品牌名行銷——Dell 講 iDRAC、HPE 講 iLO。泛稱 IPMI／BMC cold and warm reset／Java 或 HTML5 KVM 主控台，是 Supermicro 與其他 whitebox／ODM BMC 的標準用語，且全網域零則 iDRAC 或 iLO。** **這是命名慣例訊號，不是證明；混合機隊完全可能**（[管理文件](https://www.hostwinds.com/guide/dedicated-server-management-controls/)） |
| **CPU 機隊——Intel Xeon 與 AMD Opteron，全部早於 Xeon Scalable 世代** | **已確認（即時公開訂購表單）——本案最強的硬體證據** | 目前可下單的全部機種與月租，取自 [clients.hostwinds.com/cart.php?gid=12](https://clients.hostwinds.com/cart.php?gid=12)：雙 Opteron 6272 $253・雙 E5-2620 v2 $214・雙 E5-2620 v3 $264・雙 E5-2670 v2 $303・雙 E5645 $176・雙 L5630 $171・雙 L5640 $147・雙 X5355 $91・單 Opteron 6272 $122・E3-1240 v2 $103.50・E3-1270 v2 $98・E3-1270 v3 $98・E3-1270 v5 $151・E3-1270 v6 $167・E3-1271 v3 $113・E5-1620 v2 $168・E5-2620 v2 $183・i7-3930K $154・L5320 $98・Dual E5-2620 v3 $99。其中一項規格為 12 × 3.2 GHz、最高 96 GB RAM、4 個硬碟槽 |
| **機隊年齡意涵** | **已確認（為上表之解讀）** | 上述清單涵蓋 **Xeon 5300 Clovertown（2007）／5500-5600 Westmere／E5 v2 Ivy Bridge／E5 v3 Haswell 至 E3-1270 v6 Kaby Lake（2017）**。**沒有任何一顆 Xeon Scalable（Skylake-SP 以後）、沒有 EPYC、Haswell 之後沒有任何 DDR4 世代的雙路機種**，機架裡還有一顆**桌上型 i7-3930K**。**機隊年齡約 8 至 19 年。** 4 槽、最高 96 GB、1 Gbps 埠的節點是典型 1U/2U Supermicro 級 whitebox 組態——**此為由節點形狀推得的推論，非確認** |
| **客戶可自選組態** | **已確認** | 產品頁確認客戶可自選 RAM、CPU 數、硬碟容量與數量、RAID 0 至 RAID 60，並附 IPMI 與「full access to the 1 Gbps network link」——**是 1 GbE，不是 10/25 GbE**（[專用伺服器頁](https://www.hostwinds.com/dedicated/servers)） |
| **雲端／VPS 機隊的供應商與 CPU 世代** | **GAP** | 雲端伺服器以 1–16 vCPU、1–96 GB RAM 分級銷售，「Solid State Drives」（未區分 SSD 或 NVMe），1 Gbps 埠，時計 $0.006931/hr 至 $0.456931/hr。**頁面未具名 CPU 廠、亦未具名 hypervisor**（第三方評測提及 KVM 與 OpenVZ）。歷史部落格描述早期 VPS 主節點為 4 核／16 GB、共享節點為 8 核／8 GB——2012–13 年代，非現況（[雲端伺服器頁](https://www.hostwinds.com/cloud/cloud-servers)） |

**銷售解讀。** 供應商問題是本帳戶最重要的未解項目，**只能靠訪談、現場，或在試用機上查看 IPMI／BMC 橫幅來確認。**

---

## 7. GPU 與 AI 佈局

**硬性否定：完全沒有任何 GPU 產品。這是全新開發（greenfield）的 AI／加速運算機會，不是競爭替換。**

- **GPU 型號：GAP——零。** 全站未提供、亦未提及任何 NVIDIA、AMD Instinct 或 Intel GPU 型號。對 hostwinds.com 的站內限定檢索（GPU／NVIDIA／顯示卡相關詞）僅回傳 /dedicated/servers、/cloud/cloud-servers、/vps/linux 等一般頁面，皆無 GPU 內容。專用伺服器訂購表單**無任何 GPU 加購選項**；雲端伺服器頁**無任何 GPU 級距**。
- **價格：GAP**——沒有 GPU SKU，因此沒有價格，**也沒有任何 GPU 價格點可供比較**。
- **已執行兩項獨立查核：**（i）對 hostwinds.com 的網域限定 GPU／NVIDIA 詞彙檢索；（ii）即時專用伺服器購物車（[gid=12](https://clients.hostwinds.com/cart.php?gid=12)）列出 20 個 CPU-only SKU，無任何加速器選項。
- **佐證性負面訊號——密度限制。** 公開的 colocation 電力上限為**整櫃 42U 3.84 kW、雙櫃 cage 7.68 kW**（[colocation 頁](https://www.hostwinds.com/colocation)）。**此密度在未進行設施電力與冷卻升級之前，無法支撐 H100／L40S 級部署。**
- **網路條件亦強化此判斷。** 客戶埠在專用、雲端與 colocation 產品一律為 **1 Gbps——沒有 10/25 GbE 客戶埠選項**，對 AI／HPC 工作負載是明顯限制。
- **銷售意涵。** 在此提 AI／GPU，**必須同時帶電力與冷卻的密度方案**，而且**必須對 HostPapa 這個新的資本決策方談**。另需注意 greenfield 說法的另一面：正因為完全沒有 GPU 產品，**本帳戶也沒有任何 AI 需求或 AI 資本支出意圖的證據**——這件事要在電話上建立，不能預設。

---

## 8. 客戶與網路

### 客戶

- **無任何具名終端客戶。GAP。** Hostwinds 未公布任何客戶 logo、案例或推薦名單，只以泛稱描述客層：「a diversified client base that ranges from small bloggers with a single website to Fortune 500 companies」（此措辭出現在**供應商代管的案例文字**，並非 Hostwinds 自家網站）與「a diverse global customer base」（HostPapa 新聞稿）。**「Fortune 500」在任何地方都無實證——視為行銷語、未證實。**（[MailChannels 案例](https://www.mailchannels.com/customer/hostwinds/)）
- **白標轉售商／小型主機業者（通路客層，未具名）。** Hostwinds 經營白標轉售方案，讓客戶「set up their very own hosting company, powered by Hostwinds」，可完全移除 Hostwinds 品牌，涵蓋 VPS（KVM、OpenVZ、Windows）、雲端、共享、轉售、負載平衡與 Minecraft／VPN 伺服器（[白標頁](https://www.hostwinds.com/hosting/whitelabel)，另有 /hosting/reseller）。**代表相當比例的需求是間接的——這對估算硬體換機量有影響，因為轉售商流動率直接驅動節點使用率。**
- **MailChannels——供應商／夥伴，不是客戶。** MailChannels 發布 Hostwinds 案例，描述 Hostwinds 在將 email 行銷業者移出網路、重新聚焦核心基礎設施與企業網站代管後，導入其反垃圾郵件過濾。**關係方向：Hostwinds 是買方。** 列於此僅因這是查得的唯一一則具名公司關係。（[MailChannels](https://www.mailchannels.com/customer/hostwinds/)）
- **WeLoveServers 客戶群——曾收購，社群來源、未證實。**（[WHT 討論串](https://www.webhostingtalk.com/showthread.php?t=1536147)；原文回 HTTP 403，日期與條件皆未確立）

### 網路

- **ASN：AS54290**，RADB 代碼 HOSTWINDS-1（最後修改 2023-11-13），RADB 主要聯絡人 Peter Holden。**[ARIN RDAP](https://rdap.arin.net/registry/autnum/54290) 現回傳組織「HostPapa」、代碼 HOSTP-7、註冊 2011-12-05、最後異動 2026-05-12、地址 325 Delaware Avenue Suite 300, Buffalo NY 14202**——併購後改登記。bgp.tools 亦已將 AS54290 標為 HostPapa。
- **資源：** 75 個 IPv4 前綴 ＋ 4 個 IPv6 前綴（合計 79 個）；**originates 303,360 個 IPv4 位址**。
- **衛生弱點兩則：目前無有效 RPKI ROA**，且**該 ASN 曾被觀測宣告 bogon**。兩者皆值得記錄。
- **容量：**[PeeringDB](https://www.peeringdb.com/net/9308) 自報流量等級 **20–50 Gbps**；網路類型「Content」；範圍 Global；單播 IPv4 與 IPv6，無多播。**客戶埠在專用、雲端與 colocation 一律 1 Gbps——沒有 10/25 GbE 客戶埠。** Colocation 級距標示 1 Gbps 埠、100 Mbps 承諾流量與 /29 IP 配發。
- **Peering：** 政策 **Selective**；無流量比或合約要求。**公開 IX 僅 SIX Seattle（Seattle Internet Exchange）**，兩個 10G 埠——IPv4 206.81.81.79 與 206.81.81.82，另有 IPv6；不支援 route server 或 BFD。**PeeringDB 完全未列任何私有互連設施（「no filter matches」）**——Hostwinds 完全不公布設施據點，這相當罕見，既限制夥伴探索，也使設施層無法獨立佐證。
- **觀測到的上游／對接**（bgp.he.net）：NTT America AS2914、Cogent AS174、Zayo AS6461、Hurricane Electric AS6939、GSL Networks AS137409、RETN AS9002。**共觀測到 39 個 BGP peer**（34 個 IPv4、31 個 IPv6），平均 AS path 長度 3.958。
- **Hostwinds 自行具名的電信商：** 四家 Tier 1——**Zayo、Cogent、NTT Communications 與 GTT**，並稱有自動路徑改道、備援交換器與備援核心路由器（[機房頁](https://www.hostwinds.com/company/datacenters)）。

---

## 9. 政治與公開紀錄

僅取公開紀錄，逐條標記 `public-record`｜`unverified`｜`gap`。

- **Peter Holden（Hostwinds LLC 創辦人暨 CEO）——`gap`。** 無法取得或確認任何 FEC 個人捐獻紀錄。[FEC 個人捐獻查詢](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Peter+Holden&contributor_employer=Hostwinds) 為客戶端 JavaScript 應用；帶入 contributor_name=Peter+Holden 與 contributor_employer=Hostwinds 的預篩網址只回傳空白查詢介面、無任何結果列，因此**捐獻的有無皆未確立。這是取得失敗，不是「查無捐獻」——不得寫成「沒有政治獻金」。** 另「Peter Holden」為常見姓名，任何命中都須以雇主與城市交叉佐證才能歸屬。查無遊說登記、PAC 活動、政府合約或公開政治發言。
- **Jamie Opalchuk（HostPapa Inc. 創辦人暨 CEO，新母公司）——`gap`。** 查無美國政治獻金、遊說或政府事務紀錄。**HostPapa 總部在加拿大**（ARIN 紀錄的技術與濫用聯絡人使用 +1-905 安大略區碼），故美國 FEC 個人捐獻紀錄通常不適用於非美國人；**外國人依法不得捐獻美國聯邦競選。** 本次檢索無法確認任何政治活動。（[新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)）
- **Hostwinds LLC（法人）——`public-record｜查無政治活動`。** **明白陳述：查無企業 PAC、查無聯邦遊說登記、查無政府或公部門得標、查無公共政策立場。** 唯一近似監理的公開足跡與濫用／內容管理有關：一則 Web Hosting Talk 批評其濫用處理的討論串，以及公開的濫用聯絡管道與 [phish.report 條目](https://phish.report/contacts/HOSTWINDS-US)。公司亦曾為整頓 IP 信譽而將 email 行銷業者移出其網路。**上述皆非政治活動。**

---

## 10. 公開聯絡管道

**僅限公開來源。本表不列任何個人行動電話與私人住址。** 若業者未公布該管道，該列標示 GAP。

| 管道 | 內容 | 來源 |
|---|---|---|
| 銷售 email | **sales@hostwinds.com**——銷售時段 週一至週五 08:00–16:00 PST | [Hostwinds 支援層級文件](https://www.hostwinds.com/product-docs/support/hostwinds-tiers-of-support) |
| 主要／銷售電話（免付費） | **+1 (888) 404-1279**——公布於官網頁尾與 BBB 檔案 | [hostwinds.com](https://www.hostwinds.com/) |
| 支援 email | **support@hostwinds.com**——24/7/365 工單與線上客服；公司宣稱 5 分鐘工單回應目標 | [支援層級文件](https://www.hostwinds.com/product-docs/support/hostwinds-tiers-of-support) |
| 濫用聯絡 | **abuse@hostwinds.com**；濫用電話 **+1-206-886-0665**。**併購後 ARIN 登記之濫用 POC 已改為 net-abuse-global@hostpapa.com、+1-905-315-3455** | [ARIN RDAP AS54290](https://rdap.arin.net/registry/autnum/54290) |
| 網路／技術聯絡（併購後 ARIN 登記） | **net-tech-global@hostpapa.com、+1-905-315-3455**——這是 AS54290 的登記技術路徑，也是**併購後最可靠、通往網路與基礎設施決策者的路徑** | [ARIN RDAP AS54290](https://rdap.arin.net/registry/autnum/54290) |
| 法務／隱私 email | **legal@hostwinds.com**（著作權／DMCA）；**privacy@hostwinds.com**（隱私查詢） | [產品文件／支援](https://www.hostwinds.com/product-docs/support/) |
| 總部地址 | **12101 Tukwila International Blvd, Suite 320, 3rd Floor, Tukwila（行銷寫成 Seattle）, WA 98168-2398** | [BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407) |
| LinkedIn 公司頁 | [linkedin.com/company/hostwinds](https://www.linkedin.com/company/hostwinds)——自報 51–200 名員工、IT & Services、創立 2010、Seattle WA | [LinkedIn](https://www.linkedin.com/company/hostwinds) |
| 具名主管——**Peter Holden，創辦人暨 CEO** | [linkedin.com/in/holdenpeter](https://www.linkedin.com/in/holdenpeter/)——併購前的主要具名決策者，亦為 AS54290 的 RADB 技術聯絡人。公開路徑為 LinkedIn 與公司銷售／主管專線。**公司未公布其直接 email。**（RocketReach、ContactOut、Wiza 等聲稱持有其直接 email／電話——**屬付費資料商紀錄而非公開紀錄**，本次未取得亦未驗證） | [LinkedIn](https://www.linkedin.com/in/holdenpeter/) |
| 具名主管——**Jamie Opalchuk，HostPapa 創辦人暨 CEO**（新母公司／可能的資本支出決策方） | 於 2026-04-29 併購新聞稿中具名；經 HostPapa 企業管道可聯繫。**併購後，Seattle／Dallas／Amsterdam 合併足跡的基礎設施採購最可能改由 HostPapa 而非 Hostwinds 主導——鎖定對象前務必先確認** | [HostPapa 新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/) |
| 徵才／招募（通往基礎設施人員的路徑） | Hostwinds 在 Tukwila 的職缺散見 ZipRecruiter、Indeed、LinkedIn、Glassdoor 與 Built In Seattle（某聚合站稱有 9 個職缺）。**未能取得任何含硬體細節的 Hostwinds 資料中心技師 JD**——檢索到的 Tukwila 機房技師職缺屬於 12201 號的 **Wowrack**，是不同公司。**不得誤植於 Hostwinds** | [Indeed — Hostwinds, Tukwila WA](https://www.indeed.com/cmp/Hostwinds/locations/WA/Tukwila) |
| 任何主管的直接 email | **GAP**——Hostwinds 所有公開資產上皆未公布任何主管個人 email | — |
| 具名技術買方（CTO／VP Infrastructure／機房營運主管） | **GAP**——公開資料中查無任何此類具名人員 | — |

---

## 11. Supermicro 銷售切入點

**分類：全新開發（greenfield）AI——附帶條件，且採購權可能已移轉。** 這**不是**既有客戶防守案（無任何已確認 OEM），**不是**替換案（無任何具名競爭廠商），也**不是** WebNX 那種平台轉換案。這是新客開發，並卡在兩件事上。

**誠實的楔子。** Hostwinds **完全沒有 GPU 產品**，可下單的機隊**約 8 至 19 年舊**（最新僅到 2017 年的 E3-1270 v6，**沒有任何 Xeon Scalable、沒有 EPYC**），且**客戶埠一律 1 Gbps**。這是很大的 greenfield 面積。但這是一個**帶條件**的機會，原因有兩個具體事實：

1. **密度。** 公開的 colocation 電力上限為**整櫃 42U 3.84 kW、雙櫃 cage 7.68 kW**。**在電力與冷卻升級之前，H100／L40S 級部署實體上就放不進去。** 任何 AI 提案在此都必須連同密度方案一起賣，不能只是報一張伺服器單。
2. **決策權。** **Hostwinds 已於 2026-04-29 被 HostPapa 併購，ARIN 亦已於 2026-05-12 將 AS54290 改登記為 HostPapa（Buffalo NY）。** 資本支出權責很可能已移轉。**在討論任何一項規格之前，先確認採購權在誰手上。**

另需注意框架風險：正因為完全沒有 GPU 產品，本帳戶也**沒有任何 AI 需求或 AI 資本支出意圖的證據**。此處的 greenfield 意思是「未經證實」，不只是「尚無競爭者」。

**不得以「我們知道你們在用 Supermicro」開場。** 本案硬體的研究等級是**未證實**；唯一訊號是泛稱 IPMI／BMC 命名加上全網域零則 iDRAC／iLO，那是推論。**要把它變成問句。**

**首次接觸的唯一資格問題——只問這一句，其他都不用問：**

> **「併購之後，Seattle／Dallas／Amsterdam 的伺服器採購決策是留在 Hostwinds，還是已經歸到 HostPapa？」**

在這句話有答案之前，其他都不重要。不報價、不預設既有供應商、不談規格。

**Rule 8 經銷商注意事項——開打前必讀。** Hostwinds 明顯在營運相當規模的機隊（303,360 個 IPv4 位址、三個資料中心、十個 colocation 市場），**但在 CRM 中一筆紀錄都沒有**——2026-08-03 於 salesleads Search（Type = All）實查：無 lead、無 account、無 do-not-call 紀錄。合理推論與整個裸機層一致：**他們的伺服器是透過經銷通路買的，不是直接向原廠買。** Hostwinds 自述的「no middlemen」指的是自有硬體、直接持有，並未具名任何供應商。**依 Rule 8，經銷商可以跨越轄區邊界，但必須事先取得核准並掛上「do not call」標記。** 在撥出第一通電話之前，須先與通路窗口確認 Hostwinds 是否已是某家經銷商的既有帳戶。若是，本案就從「新客開發」轉為**與經銷商共同經營的既有帳戶**，開場、報價路徑與登錄方式都不同。**順序：先確認通路，再登錄 lead，最後才接觸——顛倒順序會造成通路衝突。**

**轄區執行。** Tukwila 屬 West Coast North ＝ **T4｜T31**。**一組不符資格、不得單獨承作；T7 與 T11 亦均不涵蓋此區**（T11 涵蓋 Chicago Area 與 Canada East，與本案不相干——不要送件）。協同請求應送 **T4（主管 Kambiez Tahvilian）** 或 T31。**額外複雜度：** 母公司 HostPapa 位於 Burlington ON／Buffalo NY，若採購權確已北移，實際承作團隊可能還要再變更——這正是第一通電話必須先問決策權問題的原因。

---

## 12. 查證附錄

### 12.1 單一來源支撐的說法（引用前須再驗證）

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| Dallas「約 40 台伺服器／3 機箱、可擴至 60 台」 | 約 2012–2013 年的 Hostwinds 新聞部落格 | **原網址（hostwinds.com/blog/news/37/）現回 HTTP 404，數字僅由搜尋索引片段取得。十餘年前資料——只能當地板值，絕不可當現況規模** |
| Hostwinds 曾收購 **WeLoveServers** | 單一則 [Web Hosting Talk 討論串](https://www.webhostingtalk.com/showthread.php?t=1536147) | **原文對直接抓取回 HTTP 403，日期與條件皆未確立。社群來源、未證實** |
| 客層包含「Fortune 500 companies」 | 單一份供應商代管的案例（[MailChannels](https://www.mailchannels.com/customer/hostwinds/)）——**並非 Hostwinds 自行發布的陳述** | **任何地方皆無實證。視為行銷語；不得對客戶複述，亦不得寫入 CRM** |
| 歷史 VPS 節點規格（主節點 4 核／16 GB、共享節點 8 核／8 GB） | Hostwinds 新聞部落格 2012–13 年代的索引片段 | **原始頁面對直接抓取回 404。非現況** |
| Supermicro 級 whitebox 機隊 | 僅為命名慣例推論（泛稱 IPMI／「BMC Cold Reset」／「BMC Warm Reset」／「Get Console Link」，全網域零則 iDRAC 或 iLO）（[管理文件](https://www.hostwinds.com/guide/dedicated-server-management-controls/)） | **是推論，不是證據。混合機隊完全可能。不得對客戶陳述為事實，亦不得寫入 CRM** |
| Sabey Intergate.Seattle-West 園區身分與約 173,000 sq ft | 園區層級的登錄資料（datacentermap／Seattle 相關列表） | **這是園區數字，不是 Hostwinds 的足跡數字。Hostwinds 自身的 cage／機櫃／sq ft ＝ GAP** |

### 12.2 第三方估計互相矛盾之處（**呈現分歧，不擇一**）

**員工數（公司未揭露；約 40 倍落差；無任何權威來源）**

| 來源 | 數字 | 備註 |
|---|---|---|
| LinkedIn（公司自報） | **51–200** | 公司自填，區間最寬 |
| Growjo | **30** | 第三方估計 |
| LeadIQ | 約 **17**（2026-06） | 第三方估計 |
| RocketReach | **16** | 第三方估計 |
| Craft.co | **5** | 第三方估計 |

以一家營收約 $3–5M 的公司而言，資料商聚攏的約 16–30 人可能比 LinkedIn 區間更接近實況，**但沒有任何來源具權威性，本檔不擇一。**

**營收（全部為第三方估計；從未經公司確認；無 SEC 申報；HostPapa 未揭露交易條件）**

| 來源 | 數字 | 備註 |
|---|---|---|
| Growjo | **$3.5M** | 第三方估計（[Growjo](https://growjo.com/company/Hostwinds)） |
| RocketReach | **$3M**（2026） | 第三方估計 |
| ZoomInfo | **<$5M** | 第三方估計 |

三家聚攏在 **$3M–$5M**，但公司自稱曾入選 **Inc. 5000**（未指明年份），暗示歷史成長明顯高於這些估計——**故此區間應視為軟性。任何一項皆不得以事實形式寫入 CRM 紀錄或預測。**

**創立年份**

| 來源 | 數字 |
|---|---|
| 公司（hostwinds.com/company/overview、HostPapa 新聞稿） | **2010**，創立於 Oklahoma 州 Tulsa |
| BBB 檔案 | **「Date of Business Started: March 14, 2016」**——應為 WA 登記／BBB 建檔日，非原始設立日 |

**未解。兩個日期均予保留，不擇一捨棄。**

### 12.3 未結 GAP

1. **伺服器 OEM 完全未公開**——任何公開來源皆無 Supermicro／Dell／HPE／whitebox 的確認。**這是本案最重要的未解問題**，只能靠訪談、現場，或在試用機上查看 IPMI／BMC 橫幅來確認。
2. **現行伺服器與機櫃數未公開。** 唯一公司公布的數字（Dallas 約 40 台／3 機箱、可擴至 60 台）出自約 2012–2013 年的部落格，網址現已 404，且僅由搜尋片段取得。
3. **未取得 Washington Secretary of State 的 UBI 編號與正式設立日**——WA CCFS 為 JavaScript 應用無法抓取，Bizapedia／OpenCorporates 亦無紀錄。創立年份亦矛盾（2010 vs 2016-03-14）。
4. **併購條件未揭露**——HostPapa 未公布交易價格、員工移轉、Peter Holden 的留任承諾，亦無任何基礎設施／資本支出計畫。**Hostwinds 併購後是否保有獨立硬體採購權，未知，且是本帳戶的關鍵資格問題。**
5. **三個站點的自身足跡全部未公開**——無面積、無 cage／機櫃數、無合約 kW，亦未明確說明租或買（由「Tier 3+, SAS Type II audited data centers」用語強烈指向租用／colo，但從未明說）。
6. **PeeringDB 完全未列 AS54290 的任何私有互連設施**，因此設施層據點無法獨立於 Hostwinds 自家行銷之外取得佐證。以此規模的網路而言相當罕見。
7. **無具名終端客戶、無案例、無 logo 牆。**「Fortune 500 companies」僅出現在第三方供應商案例中，無實證。
8. **不存在任何 GPU 或加速器產品**，因此無競品足跡、無價格、無安裝基礎可分析——是 greenfield，但同時也**沒有任何 AI 需求或 AI 資本支出意圖的證據**。
9. **Peter Holden 的 FEC 政治獻金資料無法查詢**——fec.gov 查詢為客戶端 JavaScript，只回傳空白介面。**查無結果是取得失敗，不是「沒有捐獻」的證據。**
10. **hypervisor、儲存架構（SSD vs NVMe）與任何 10/25 GbE 能力皆未揭露**；所有已公布的客戶埠均為 1 Gbps。
11. **Peter Holden 以外的主管群未建檔**——公開資料中無任何 CTO、VP Infrastructure 或機房營運主管，因此**沒有已辨識的技術買方或硬體評估者**。
12. **員工數無法由公開資料解決**——估計自 5（Craft.co）至 51–200（LinkedIn 自報），落差 40 倍，無任何權威來源。
13. **未能取得任何含硬體或基礎設施細節的 Hostwinds 職缺。** 檢索到的 Tukwila 資料中心技師職缺屬於隔壁 12201 號的 **Wowrack**，**不得誤植於 Hostwinds**。
14. **七個非自營 colocation 市場**（Buffalo、Atlanta、Chicago、San Jose、Los Angeles、New York City、Dublin、Toronto）**的設施與營運商全未揭露**——無任何設施名稱或營運商。

### 12.4 工具與取得限制（影響本檔完整度）

- **本次遭遇的 HTTP 阻擋來源：** WebHostingTalk（403）、Crunchbase（403）、ZoomInfo（403）。凡依賴上述來源之發現，均已於本檔標記為社群來源、次級擷取或第三方估計。
- **無法以程式查詢的 JavaScript 介面：** fec.gov 個人捐獻查詢，以及 Washington 的 CCFS 商業登記。**因此 Peter Holden 的 FEC 結果屬「無資料」，絕不可寫成「沒有政治獻金」**；WA 的 UBI 編號亦因同一原因為 GAP。
- **政治紀錄一致原則：** 本檔所有政治資料僅取自公開紀錄，並逐條標記為 `public-record`、`unverified` 或 `gap`。
