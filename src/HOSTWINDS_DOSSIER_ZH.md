# Hostwinds LLC — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國）　暨　銷售七組 · 專員 US8664 Tuo Cheng · **日期：** 2026-08-03
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

- **HostPapa, Inc.＝母公司／收購方，2026-04-29 起生效。** 新聞稿標題為「HostPapa Acquires Hostwinds to Expand Global Hosting Infrastructure」，**交易條件未揭露**。稿中具名 HostPapa 創辦人暨 CEO **Jamie Opalchuk** 與 Hostwinds 創辦人暨 CEO **Peter Holden**，並稱此案在 Seattle、Dallas、Amsterdam 增加「incremental Pacific Northwest and European infrastructure」。**獨立佐證：**[ARIN 對 autnum 54290 的 RDAP](https://rdap.arin.net/registry/autnum/54290) 現回傳組織「HostPapa」、代碼 HOSTP-7、地址 325 Delaware Avenue Suite 300, Buffalo NY 14202、最後異動 2026-05-12——ASN 已於交易後改登記。（[新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)）
- **Peter Holden＝創辦人、CEO，併購前為唯一所有人／成員。**[公司簡介頁](https://www.hostwinds.com/company/overview) 將 2010 年創立歸功於 CEO Peter；[BBB](https://www.bbb.org/us/wa/tukwila/profile/internet-providers/hostwinds-llc-1296-1000075407) 列「Mr. Peter Holden, Owner/Member」為負責人；bgp.he.net 列他為 AS54290 的 RADB 主要聯絡人。多個第三方檔案（LinkedIn、RocketReach、Wiza）列他為 CEO。有報導稱公司自成立以來「has been owned and maintained by CEO Peter Holden」——**查無外部投資人或募資輪**；Crunchbase 檔案顯示無募資（該頁本身對抓取回 HTTP 403）。**併購後的留任承諾＝GAP。**
- **Jamie Opalchuk＝HostPapa 創辦人暨 CEO（現為最終所有人）。** 於併購新聞稿中具名。併購後他是基礎設施資本支出最可能的最終決策者。（[新聞稿](https://www.hostpapa.com/about-hostpapa/pressroom/2026-04-29-hostpapa-acquires-hostwinds-to-expand-global-hosting-infrastructure/)）
- **WeLoveServers＝Hostwinds 曾收購的資產（歷史、社群來源、未證實）。**（[WHT 討論串](https://www.webhostingtalk.com/showthread.php?t=1536147)；原文回 HTTP 403，日期與條件皆未確立）
- **CEO 以外的主管群＝GAP。** 公開資料中查無任何 CTO、VP Infrastructure 或 Director of Data Center Operations，**因此本案沒有已辨識的技術買方或硬體評估者。**

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
