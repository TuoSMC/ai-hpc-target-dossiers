# phoenixNAP — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國）· 專員 US8664 Tuo Cheng · **日期：** 2026-08-11
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有持股，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之 GPU 型錄與定價、UCC 歸檔、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 亞利桑那州鳳凰城 — West Coast South excl. CA = **T1**｜T31。一組可直接註冊。
**CRM 狀態：** 2026-08-11 於 salesleads Search（Type = All）實查為乾淨 — 無 lead、無 account、無 do-not-call。一組可註冊。

---

## 1. 結論摘要

phoenixNAP（法人名稱 **PHOENIX NAP, LLC**，亞利桑那州本地 LLC，ACC 檔號 **L15102933**，實體狀態 ACTIVE）是一家私人持股的全球 Bare Metal Cloud、專用伺服器與主機代管（colocation）業者，總部設於其位於亞利桑那州鳳凰城 3402 East University Drive 的自建旗艦資料中心內，營運 **AS12189** 及另外七個 ASN，在六個地區提供已標價運算資源，並在橫跨四大洲的十六處設施設有網路據點（[GLEIF LEI 549300AC0LNX8QT0G149](https://api.gleif.org/api/v1/lei-records/549300AC0LNX8QT0G149)，已對亞利桑那州公司委員會查核；[PeeringDB AS12189](https://www.peeringdb.com/api/net?asn=12189&depth=2)）。商業上，這是**一個既有客戶防守案，且帶有急迫的被替換威脅；任何把它當成全新開發案來談的人都會輸掉**。Supermicro 是有據可查的九年既有供應商——Supermicro 於 2017 年 6 月與 phoenixNAP 共同發表案例研究，具名引述總裁 Ian McClarty 與產品副總 William Bell，內容涵蓋 X11 Building Block Solutions、BigTwin 2U 4 節點系統、Simply Double 全快閃 SuperStorage、Supermicro Rack Scale Design 以及跨全部據點使用的 Supermicro Server Manager（[CaseStudy_PhoenixNAP.pdf](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)）——且 ServeTheHome 於 2023 年 3 月實機拆解，確認 phoenixNAP 一台生產節點就是 Supermicro twin node（[ServeTheHome，2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)）。**但在 2025 年 4 月，HPE 公開宣稱 phoenixNAP 是其首個符合 DC-MHS 規範之解耦式硬體、搭載 Intel Xeon 6 的部署場域**（[HPE 新聞室，2025 年 4 月](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)），而對應的 `s4.x6`（Xeon 6 6731E）SKU 正好在同一時間窗出現在 phoenixNAP 自家型錄中。**競爭對手已在一個 Supermicro 既有帳戶裡，把最新一代矽晶的旗子插了下去。**

有三件事讓這個時間點格外有利。第一，**他們自己擁有機隊**——這不是推論：亞利桑那州稅務法院紀錄載明，IaaS 客戶使用的是「PNAP-owned servers」，且法院認定這些伺服器是 PNAP 出租的有形動產（[TX2024-000075 minute entry，2026-05-21 歸檔](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)）。第二，**一個次世代 GPU SKU 已經卡在待發狀態十六個月**：產品代碼 `d3.g3.c2.medium` 存在於 phoenixNAP 自家產品系統中，卻沒有硬體規格、沒有 GPU 型號、也沒有價格，僅以價格 0 的形式出現在兩筆 Windows Server 2025 授權列的關聯產品代碼上——在 2025-04-22 快取的 Wayback 快照中就已存在，2026-08-11 的線上型錄中仍然原封不動（[phoenixNAP 快取定價 API](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)）。這是一個**原則上已決定、但尚未在矽晶選型或資本支出上拍板的 GPU 平台決策**。第三，**2026 年 3 月 12 日，RadiusDC 同意收購其鳳凰城資料中心與主機代管業務**，預計 2026 年第二季完成交割；此後 phoenixNAP 在自家旗艦建物內轉為**承租方**，並保留約 80% 的全球業務，明確包含 Bare Metal Cloud 與網路平台（[RadiusDC 新聞稿，2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html)；[phoenixNAP 新聞稿，2026-03-17](https://www.prnewswire.com/news-releases/phoenixnap-sharpens-focus-on-on-demand-infrastructure-with-strategic-transaction-for-phoenix-colocation-business-302716069.html)）。他們剛把一門不動產生意換成一門運算生意，手上有現金；**機隊如今就是整間公司**。

可能讓這筆生意破局的因素是價格，而且是算術問題而非態度問題。其旗艦 GPU 節點由租金推導出的成本天花板落在約 **$8,000–$12,000**，而街頭價物料清單（BOM）約為 **$14,000–$18,300**（第 10 節）——這兩個數字唯有在 phoenixNAP 以顯著低於街頭價採購時才對得上，而這正是 Supermicro 自家案例研究所記載的事實：phoenixNAP 是**透過 Supermicro**進入 Intel 的 Early Deployment 計畫。**守住這個帳戶的路徑是 Intel 計畫關係與計畫價，不是機殼規格。**還有一項在第一次報價前必須讓團隊知道的逆風：2026 年 5 月 18 日的亞利桑那州稅務法院裁定，使其主機代管與伺服器租賃收入**自此往後**須繳交先前未曾負擔的州、郡與鳳凰城市交易特權稅（TPT），本季他們在價格上會更硬。

---

## 2. 公司速覽

| 欄位 | 內容 | 證據／日期 |
|---|---|---|
| **法人名稱** | **PHOENIX NAP, LLC** — 商業字號寫作「phoenixNAP」；於亞利桑那州稅務法院案件標題中呈現為「PHOENIX NAP L L C」。亞利桑那州本地 LLC，法律形式 O85W。**無 SEC 註冊。查無德拉瓦州實體。** | [GLEIF LEI **549300AC0LNX8QT0G149**](https://api.gleif.org/api/v1/lei-records/549300AC0LNX8QT0G149) — 狀態 FULLY_CORROBORATED，查核機關 **RA000597 ＝亞利桑那州公司委員會（Arizona Corporation Commission）**，`validatedAs`／`registeredAs` ＝ ACC 檔號 **L15102933**，管轄 US-AZ，實體狀態 **ACTIVE**；OpenCorporates id `us_az/L15102933`；S&P company id 61203246。另由 [TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf) 之案件標題獨立佐證。**請注意區分：LEI 的「註冊狀態」為 LAPSED**（nextRenewalDate 2023-10-14）——失效的是 LEI 憑證本身，不是公司；**底層的亞利桑那州實體仍為 ACTIVE** |
| **總部（實查地址）** | **3402 East University Drive, Phoenix, AZ 85034** — 旗艦資料中心兼總部。**Suite 420** 是 ARIN POC 紀錄上使用的行政／收件套房。另有**第二個登記地址**：**2353 W University Drive, Tempe, AZ 85281** — CCBill／CWIE 大樓，作為本 LLC 的法定登記地址，也是休眠 ARIN org PHOEN-89 的街道地址 | GLEIF 總部地址；法定登記地址逐字為「**C/O MARCUS BOHN, 2353 W UNIVERSITY DRIVE, TEMPE, AZ 85281**」（[GLEIF](https://api.gleif.org/api/v1/lei-records/549300AC0LNX8QT0G149)）；ARIN org PHOEN-56 街道地址為 3402 E. University Drive（[ARIN POC 清單](https://whois.arin.net/rest/org/PHOEN-56/pocs)） |
| **創立年份** | **2009** — 依 ACC 紀錄，實體 creationDate 為 **2009-03-04**。值得一記的細節：網域 **phoenixnap.com 註冊於 2009-02-26T18:04:14Z**，比 LLC 設立**早八天** | [GLEIF](https://api.gleif.org/api/v1/lei-records/549300AC0LNX8QT0G149)（creationDate）；Verisign RDAP（網域建立日）；Supermicro 2017 年案例研究亦載「Founded in 2009」（[CaseStudy_PhoenixNAP.pdf](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)） |
| **所有權** | **由創辦人主導；受益所有權與出資額比例＝GAP。** CWIE／CCBill 集團關係有多方佐證，但**查無任何確立母公司或控股公司之申報文件**——GLEIF 對直接母公司與最終母公司皆記為 reporting exceptions，亦即**未申報任何母公司 LEI** | 集團關係有三項佐證：法定登記地址即 Tempe 的 CCBill／CWIE 大樓；Marcus A. Bohn 於鳳凰城市遊說申報上公布的聯絡信箱為 **MarcusB@cwie.net**（[遊說登記 PDF](https://lobbyist.phoenix.gov/PDF/Registration/f9bc617c-1340-44ac-aa24-0e45f75a28fa)）；ARIN POC **PETRO182-ARIN** 的 `companyName` 欄位逐字寫著「**CCBill EU**」，而其信箱為 draganp@phoenixnap.com（[ARIN](https://whois.arin.net/rest/poc/PETRO182-ARIN)） |
| **員工數** | **公司未揭露。僅有第三方估計，且彼此矛盾：Datanyze 約 300 人 · ZoomInfo 201–500 · Ampliz 51–200。** 2017 年版 Ron Cadwell 簡介提及約 450 人的集團規模，但那是更大的 CWIE／CCBill 集團，不是 phoenixNAP 單體 | 資料商估計為**無可見方法論的第三方模型——登錄 CRM 時必須標示為估計值**。唯一一項有紀錄的規模陳述，是 phoenixNAP 自己在訴訟中主張其於 2016 年 10 月至 2020 年 8 月查核期間「provided hundreds of employees and independent contractors to operate its data center」（[TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)）——此為訴訟攻防脈絡下的陳述，且其法律主張已遭法院駁回 |
| **營收** | **未揭露。Datanyze 約 $25M 屬不可靠的第三方模型。** 另有一個較有依據的 **ESTIMATE — DERIVED（推導估計）**：鳳凰城市對 2016 年 10 月至 2020 年 8 月共 47 個月，就商業租賃類 TPT 核課 **$2,537,075.23**，而裁定書逐字引述市稅率為「two and eight-tenths percent」→ $2,537,075.23 ÷ 0.028 ≈ **47 個月內約 $90.6M 的主機代管毛收入 ≈ 每年約 $23M**。若對 $1,096,327.97 的州「個人財產租賃」核課套用**假設**的 5.5% 州稅率（**此稅率並未出現在裁定書中，屬本檔假設**），推得同期 IaaS 伺服器租賃毛收入約 $19.9M ≈ **每年約 $5M**。鳳凰城單一據點合計 ≈ **2016–2020 年間每年約 $28M** | [TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)。**警告：** 州商業租賃的 $528,288.69 在 5.5% 稅率下無法對回同一稅基，可見分類與稅基確實不同——這是**有界限的估計，不是算術上的真值**。此推導真正確立的是：**流傳的 $25M 全公司數字，對一家六地區的全球業者而言幾乎可以確定偏低**，因為光是鳳凰城主機代管在 2019 年就可能已接近該數字。**CRM $100M 門檻：公開資料不支持——但請注意上述推導只涵蓋鳳凰城，不涵蓋整個集團** |
| **ASN** | **主要營運 ASN：AS12189**（PeeringDB net id 2932，名稱「PhoenixNAP」，IRR as-set LEVEL3::AS-PHOENIXNAP，紀錄建立 2010-02-17，最後更新 2026-03-25）。ARIN org **PHOEN-56** 持有 **八個 ASN**：AS11572（SS-ATL）、AS12189、AS46385、AS53605、AS394643、AS397378、AS400672、AS401633。另有一個**休眠**的 ARIN org：**PHOEN-89**（2353 W University, Tempe；登記於 2017-07-25；canAllocate＝N；**零 POC、零 ASN**） | [PeeringDB AS12189](https://www.peeringdb.com/api/net?asn=12189&depth=2)；[ARIN org PHOEN-56 POC](https://whois.arin.net/rest/org/PHOEN-56/pocs)。phoenixNAP 另自行營運 rwhois 服務於 `rwhois://rwhois.phoenixnap.com:4321` |
| **機隊所有權** | **自有伺服器——此為法院紀錄所確立，非推論** | 「PNAP's customers pay for … (2) infrastructure as a service（"IaaS"）services（**utilization by customers of PNAP-owned servers**）」（PSOF ¶10）；法院認定該等硬體與軟體為 PNAP 出租之有形動產（[TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)）。**這是整個帳戶的資格條件** |
| **線上型錄規模** | **101 個產品代碼** — 84 個具完整硬體 metadata 的伺服器 SKU、3 個 GPU SKU，另加儲存／頻寬／OS／Netris 品項——橫跨 **6 個地區**（PHX、ASH、NLD、SGP、CHI、SEA）標價 | 直接讀取 phoenixNAP 自家快取定價 API payload，**1,061,819 bytes**，2026-08-11 取得：[api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) |
| **正在進行的結構性變化** | **鳳凰城資料中心與主機代管業務正被出售給 RadiusDC**（IPI Partners 設立之平台，執行長 Mike Krza），2026-03-12 宣布，預計 **2026 年第二季**交割。phoenixNAP 保留約 80% 全球業務，明確包含 Bare Metal Cloud 與網路平台，並在 3402 E University Drive **轉為承租方**。**GAP：截至 2026-08-11 查無交割完成之確認** | [RadiusDC 新聞稿](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) · [phoenixNAP 新聞稿](https://www.prnewswire.com/news-releases/phoenixnap-sharpens-focus-on-on-demand-infrastructure-with-strategic-transaction-for-phoenix-colocation-business-302716069.html)。顧問：BofA Securities（phoenixNAP）、J.P. Morgan（RadiusDC）；Cleary Gottlieb（phoenixNAP）、Gibson Dunn ＋ Snell & Wilmer（RadiusDC） |
| **對州政府機關之進行中訴訟** | **Phoenix NAP, LLC v. Arizona Department of Revenue**，亞利桑那州稅務法院 **TX2024-000075**，承審法官 Hon. Erik Thorson。核課總額 **$4,549,556.05**。裁定於 2026-05-21 歸檔：ADOR 在實體爭點勝訴（主機代管與伺服器租賃**確實**應課 TPT），但 phoenixNAP 部分勝訴——該適用僅得**向後生效（PROSPECTIVELY ONLY）** | [Minute entry PDF](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)。**商業上具實質意義：這是一項針對「支撐 GPU 採購的那條收入線」的永久性新稅負** |
| **CRM 狀態** | **乾淨 — 無 lead、無 account、無 do-not-call** | salesleads Search（Type = All），2026-08-11 實查 |
| **轄區／團隊** | 亞利桑那州鳳凰城 → West Coast South excl. CA ＝ **T1｜T31** → 一組自有轄區，可逕行註冊 | Territory Map-Jan.2026 (Rev.1)，Sales Territory Assign 分頁 |

---

## 3. 原始名單更正表

僅列與 phoenixNAP 相關者。判定尺度：**confirmed（確認）**＝一手具名揭露或多方獨立佐證｜**partly confirmed（部分確認）**＝核心屬實，但表述方式必須修正｜**contradicted（推翻）**＝證據與原始名單相反｜**unverified（無法查證）**＝無法由公開來源確立，**不得對客戶陳述**。

| # | 原始名單之說法 | 判定 | 證據與正確表述 |
|---|---|---|---|
| 1 | **phoenixNAP 營運 AS23033**（任務指派所載） | **CONTRADICTED — 該 ASN 屬於另一家公司** | AS23033 登記於 **Wowrack.com**，ARIN org 代號 **WOWTEC-1**，ASN 名稱「WOW」，登記於 **2002-01-07**。phoenixNAP 的自治系統是 **AS12189**，於 **2013-03-07** 登記於 ARIN org **PHOEN-56「PhoenixNAP LLC」**。PeeringDB 獨立佐證：net id **2932**、名稱 PhoenixNAP、asn 12189、IRR as-set LEVEL3::AS-PHOENIXNAP。**任何以 AS23033 為鍵值進行的 prefix、peering、路由或濫用處理工作，都會打到完全錯誤的業者**（[ARIN autnum 23033](https://whois.arin.net/rest/asn/23033.json) · [PeeringDB AS12189](https://www.peeringdb.com/api/net?asn=12189)） |
| 2 | **RadiusDC 交易「預計 2026 年第二季交割」，且查無交割完成之確認**（本檔前一版於 2026-08-11 所列之 GAP） | **CONFIRMED — 且郡府紀錄顯示已完成交割** | **馬里科帕郡估價官（Maricopa County Assessor）**不動產名冊顯示 **RADIUS DC PHOENIX I LLC** 為 **APN 122-03-089, 3402 E UNIVERSITY DR, PHOENIX 85034** 之所有權人（分區 ALLRED SOUTHBANK，MCR 46809，COMMERCIAL）——即旗艦資料中心——同時亦持有 **APN 122-03-005A, 3221 E ELWOOD ST**（VACANT LAND INDUSTRIAL），與已宣布之 DC2 開發案相符。並由公司登記文件佐證：**Radius DC Phoenix I, LLC** 於 **2026-03-13** 登記為亞利桑那州**外州** LLC，AZ 檔號 **25032212**，設立地為**德拉瓦州**，主營業所 3402 E University Dr。**phoenixNAP 已不再擁有其旗艦設施；它現在是承租方。** **仍為 GAP：** 馬里科帕郡地政事務所（Recorder）之產權移轉文件編號、登記日期與對價金額並未取得（[馬里科帕郡估價官](https://mcassessor.maricopa.gov/mcs/?q=3402+E+UNIVERSITY+DR) · [Radius DC Phoenix I, LLC 登記資料](https://www.bizapedia.com/az/radius-dc-phoenix-i-llc.html)） |
| 3 | **無法取得 Phoenix NAP, LLC 於亞利桑那州公司委員會之幹部、經理人、股東與法定代理人**——本檔前一版最大的單一 GAP | **CONTRADICTED — 此缺口現已補上** | 檔號 **L15102933** 之 ACC 登記資料顯示：**本地 LLC，2009-03-04 申報，狀態 ACTIVE**；主營業地址 **3402 E University Dr Suite 420, Phoenix AZ 85034**；**法定代理人 MARCUS BOHN**，同址；以及**兩位經理人（Manager）——IRA RONALD CADWELL 與 STEPHANIE CADWELL**，同址。**來源出處必須如實說明：** 本筆資料讀自**最後更新於 2026-08-11 之登記資料鏡像站**，並非 ACC 官方入口。ACC 自身的 Business Search（arizonabusinesscenter.azcc.gov）於送出時出現圖形字元 CAPTCHA，其 API 對未驗證呼叫回傳「Authentication Failed」；**該 CAPTCHA 並未被破解，亦未被繞過**（[ACC 登記資料，經 Bizapedia 鏡像](https://www.bizapedia.com/az/phoenix-nap-llc.html)） |
| 4 | **phoenixNAP 是一家由創辦人主導的公司，領導層為 Ron Cadwell 與 Ian McClarty** | **PARTLY CONFIRMED — 實際結構是兩位經理人，不是單一創辦人** | 已申報的經理人是 **Ira Ronald Cadwell** 與 **Stephanie Cadwell**——**雙經理人**結構。**Ian McClarty 是總裁與對外的高層代言人，但在登記資料上並未列為經理人或股東**，因此他的權限屬營運／執行層級，而非出資成員層級。另請注意其法定名字：登記資料寫的是 **IRA** Ronald Cadwell，不是 Ron 或 Ronald——**這正是先前每一次以「Ron Cadwell」為鍵值的 FEC 查詢都查錯字串的原因**（[ACC 登記資料](https://www.bizapedia.com/az/phoenix-nap-llc.html)） |
| 5 | **查無任何確立 Phoenix NAP, LLC 母公司或控股公司之申報文件**（本檔前一版） | **PARTLY CONFIRMED — 狹義上仍成立，但 CWIE 關係現已有四方佐證** | 狹義上仍然成立：ACC 紀錄列的是**兩位自然人經理人，不是法人母公司**，且 GLEIF 對直接母公司與最終母公司皆記為 reporting exceptions。但 CWIE 關係現在已由**四個獨立方向**佐證：(1) **Stephanie Cadwell**——Phoenix NAP LLC 的申報經理人——公開自述為 **CWIE Holding Company, INC 的 Owner/Partner**；(2) 馬里科帕郡**營業用動產（business personal property）名冊**顯示 **CWIE HOLDING CO INC** 在 3402 E University Dr 持有兩個帳戶（9337591、9337607），與另一個獨立的 **PHOENIX NAP** 帳戶（0006384）並列；(3) **Marcus A. Bohn** 以 **marcusb@cwie.net** 在 phoenixNAP 的聯邦商標上署名為 Attorney of Record；(4) 現任 phoenixNAP 副總 **Danny Fuentes** 在一份聯邦 FEC 申報中，將雇主填為 **「CWIE」**。**在沒有申報所有權鏈的情況下，這個集團關係的證據強度大致已到極限**（[馬里科帕郡估價官](https://mcassessor.maricopa.gov/mcs/?q=3402+E+UNIVERSITY+DR)） |
| 6 | **Marcus A. Bohn 的職稱是「Chief Legal Officer（法務長）」** | **UNVERIFIED — 任何申報文件皆未載明此職稱** | 此職稱仍僅來自資料商。**一手紀錄中確實存在的是：** 他是 ACC 檔案上的**法定／登記代理人**；是 Phoenix NAP LLC 聯邦商標（USPTO TSDR，序號 87396103 與 90366571）的 **Attorney of Record 與 Correspondent**；並且是鳳凰城市遊說登記上**具名的主事者**。USPTO 的「Attorney of Record」身分確實確立他**以律師身分代表該實體行事**——但「Chief Legal Officer」這幾個字並未出現在任何申報文件中（[USPTO TSDR sn 90366571](https://tsdr.uspto.gov/statusview/sn90366571)） |
| 7 | **無法辨識 phoenixNAP 之 USPTO 商標代理人與簽署人**（本檔前一版之 GAP） | **PARTLY CONFIRMED — 代理人已解決，簽署人仍未解決** | TSDR 現已完整提供代理人與 correspondent：**Marcus A. Bohn，3402 E University Dr Suite 420, Phoenix AZ 85034，marcusb@cwie.net，電話與傳真均為 480-467-2450**，於 **SECURED SERVERS**（sn 87396103，註冊號 5293238，Supplemental Register，2017-09-19 註冊）與 **PHOENIX NAP**（sn 90366571，註冊號 6422118，Supplemental Register，2021-07-13 註冊）兩件商標上皆然。**Section 8 聲明於 2024-03-19 提出、2024-11-22 獲准**；通訊資料於 2025-01-28 變更。**但實際的聲明簽署人仍未確立**——那需要調閱申報文件影像，而 TSDR 的 bulk／document API 現已要求註冊之 USPTO API 金鑰（[USPTO TSDR sn 87396103](https://tsdr.uspto.gov/statusview/sn87396103)） |
| 8 | **phoenixNAP 以 FLEXSERVERS 作為受保護品牌行銷** | **CONTRADICTED — 該商標已放棄，且在案的商標組合比想像中弱** | **FLEXSERVERS** 申請案（序號 88517423，以 Tempe 之 2353 West University Drive 地址提出）狀態記為 **「Abandoned — Failure to Respond or Late Response」，狀態日 2020-06-18**，無註冊號。同樣地，**SECURED CLOUD**（85577377，註冊號 4299511）與 **SECURED STORAGE**（85581244，註冊號 4200375）皆為 **「Cancelled — Section 8」**，而最早的 **PHOENIX NAP** 商標（77750335，註冊號 3700592）已於 **2020-06-05** 依 Section 8 註銷。**目前僅有兩件商標有效**——PHOENIX NAP（註冊號 6422118）與 SECURED SERVERS（註冊號 5293238）——**且兩者都掛在 SUPPLEMENTAL register，不是 Principal register**，保護強度明顯較弱（[商標組合，經登記資料鏡像](https://www.bizapedia.com/az/phoenix-nap-llc.html)） |
| 9 | **PeeringDB 是切入 phoenixNAP 網路團隊的可用管道** | **CONFIRMED AS A NEGATIVE — 它根本沒有公開任何聯絡人** | AS12189 的 PeeringDB 紀錄 **2932** 之 `poc_set` **完全為空陣列**，`poc_updated` 凍結在 **2016-03-14T21:50:49Z**——已經十年沒動——即使 netixlan 資料在 2026-03-25 才更新過。org 紀錄（id 3061）的 address、city、state、country 欄位全部未填。Policy Selective、Heavy Outbound、500–1000 Gbps、10 個 IX、16 處設施。**因此所有 peering、NOC 或技術端的接觸都必須改走 ARIN 代號**——相對地 ARIN 那邊維護良好，其中三筆在 2026 年才建立或更新（[PeeringDB AS12189](https://www.peeringdb.com/api/net?asn=12189)） |
| 10 | **phoenixNAP 從事聯邦遊說** | **CONTRADICTED — 零筆聯邦申報** | 直接查詢**參議院遊說揭露法（LDA）API**，對**每一個**嘗試過的客戶名稱——「phoenix nap」「phoenixnap」「cwie」「ccbill」「radiusdc」「IPI Partners」——皆回傳 `{"count":0,"results":[]}`。這是一個乾淨、明確的否定結論。**他們的遊說足跡完全是市政層級的：** Phoenix NAP, LLC 是**鳳凰城市** **CY2025 與 CY2026** 的登記遊說客戶，具名主事者為 **Marcus A. Bohn**（[參議院 LDA API](https://lda.senate.gov/api/v1/filings/?client_name=phoenix%20nap) · [鳳凰城市 2026 年登記客戶名單](https://lobbyist.phoenix.gov/PDF/RegisteredClients/2026)） |
| 11 | **分割後 phoenixNAP 保留約 80% 的全球業務** | **UNVERIFIED — 僅為公司自身說法，每次引用都必須標明出處** | 此數字**只出現在該公司 2026 年 3 月自家新聞稿**與 RadiusDC 新聞稿中，並被產業媒體逐字轉載。phoenixNAP 為私人持股、不公布財務數字；**沒有任何申報文件、經審計報表或第三方量測可以用來檢核這個 80%**。請當成**具名歸屬的公司說法**使用，絕不可當成事實（[phoenixNAP 新聞稿，2026-03-17](https://www.prnewswire.com/news-releases/phoenixnap-sharpens-focus-on-on-demand-infrastructure-with-strategic-transaction-for-phoenix-colocation-business-302716069.html)） |
| 12 | **Stephanie Cadwell 是 Ron Cadwell 的母親**（或依另一流傳來源所稱，是他的姊妹） | **UNVERIFIED — 且兩種流傳說法彼此矛盾** | 一篇 2015 年的個人部落格稱她是「Ira R. Cadwell 的母親」；一份由資料商彙整的摘要則稱她「與其兄弟 Ron Cadwell 共同持有 CCBill LLC」。**兩者互斥，且兩者都不是紀錄**；亦查無任何申報文件、訃聞、法院文書或公司揭露可確立任何親屬關係。**已確立的事實是：兩人皆為 Phoenix NAP, LLC 同址之申報經理人。** 請記錄「共同擔任經理人」這件事；**不得以任何形式記錄親屬關係**（[ACC 登記資料](https://www.bizapedia.com/az/phoenix-nap-llc.html)） |
| 13 | **phoenixNAP 約有 186–300 名員工**（各家資料商估計） | **UNVERIFIED — 各家估計彼此差異極大，且沒有一份是分割後的數字** | 與前一版相同，但值得重申：Datanyze 約 300 · ZoomInfo 201–500 · Ampliz 51–200 · 一份 2026 年搜尋摘要稱 2026 年 6 月約 186。**沒有任何一家揭露方法論，也沒有任何一家反映分割**——而分割已把主機代管與資料中心營運人員移轉給 RadiusDC。任何帶進 CRM 的人數，都必須標示為**第三方估計，並附上「未反映分割」之但書**（[ZoomInfo 公司頁](https://www.zoominfo.com/c/phoenix-nap-llc/352148054)） |

---

## 4. 領導層與所有權

本節證據等級：**primary-record（一手紀錄）**＝公司登記、網路號碼登錄機構、USPTO 申報、郡府估價名冊、法院案卷、市政申報、競選財務申報，或公司自家已發布頁面｜**corroborated（多方佐證）**＝兩個以上獨立來源互相印證｜**single-source（單一來源）**＝僅一個次級來源，無佐證｜**GAP**＝已具名搜尋但查無。

進入表格前有四項前提。第一，**前一版最大的亞利桑那州公司委員會缺口現已補上**：Phoenix NAP, LLC（檔號 **L15102933**）有**兩位申報經理人——Ira Ronald Cadwell 與 Stephanie Cadwell**——以及一位**法定代理人 Marcus Bohn**，三者同址於 3402 E University Dr Suite 420。請一併讀出處但書：本筆資料來自**更新於 2026-08-11 之登記資料鏡像站**，因為 ACC 官方入口有 CAPTCHA 阻擋，而**該 CAPTCHA 並未被破解，亦未被繞過**。第二，**法定名字是 IRA，不是 Ron 或 Ronald**——單就這一項更正，就能解釋為何先前以姓名為鍵值的紀錄查詢一再落空。第三，**ARIN 登錄資料仍是本帳戶最豐富的人員來源**：org PHOEN-56 揭露**五位真實具名人員**，附直接信箱與直撥電話，分布於鳳凰城、馬爾他與塞爾維亞，且**其中兩位是前一版之後新增的**（Carmody 於 2026-02-25 加入、Ilic 於 2026-04-06 加入）。登記機構幹部與 ARIN 聯絡人**以獨立列呈現並明確標示**——他們是真實具名的人，而且往往是一家私人公司唯一對外揭露、具幹部等級的名字。第四，**phoenixNAP 根本沒有發布領導層頁面**：phoenixnap.com/company/leadership 與 /about-us 皆回傳 **HTTP 404**，因此以下每一個名字都來自申報文件、登記機構、新聞稿或已分級之次級來源，**沒有一個來自公司現行名冊頁面**。

**FEC 的狀態已經改變，且必須精確理解。** 本次查詢中 FEC 資料瀏覽器**確實有回傳結果**，因此數位主事者現在帶有**明確的否定結論（「查無紀錄」）**，而非先前的「查詢被阻擋」。但**仍有三個名字未解決**，原因是 FEC 介面卡住或無法套用可資區辨的過濾條件，且 openFEC API 在整段作業期間持續對共用 DEMO_KEY 限流。**「未解決」的一列絕對不是「查無紀錄」的一列，任何情況下都不得如此回報。**

### 4.1 具名人員

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC 紀錄 | 來源 |
|---|---|---|---|---|---|---|
| **Ira Ronald Cadwell**（公開署名：「Ron Cadwell」） | 亞利桑那登記身分為 **Manager（經理人）**；對外則以 **Founder & Chief Executive Officer** 名義出現 | **股東／登記機構幹部／高階主管——最終經濟核准人** | **corroborated**（經理人身分經鏡像站取得；ACC 官方入口有 CAPTCHA 阻擋且未被繞過） | **GAP — 查無直接公開信箱。** 公司主線 **+1-480-422-2022**，公布於 org PHOEN-56 之 ARIN Admin／Abuse POC 紀錄 · [LinkedIn](https://www.linkedin.com/in/ron-cadwell-0b747313b/) | **查無紀錄——明確之否定結論。** 姓氏「Cadwell」且捐款人州別為 **AZ** 的 **45 筆** FEC 個人捐款紀錄，已跨兩頁全數逐筆列舉（Sarah、Holli Cadwell Dunn、Jeremy、Colleen、Capri、Sara、Delores、Bess、Jon、Susan、Daphne、Thomas）——**沒有 Ira、Ron 或 Ronald**。全國性查詢「cadwell ira」／「cadwell ron」僅回傳無關的 **RONALD G. CADWELL**（加州，雇主 Kindred Healthcare）與 **RONALD CADWELL**（華盛頓州，無業） | [ACC 登記資料，檔號 L15102933，經 2026-08-11 更新之鏡像站](https://www.bizapedia.com/az/phoenix-nap-llc.html) · [Crunchbase](https://www.crunchbase.com/person/ron-cadwell) · [FEC — Cadwell, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=cadwell&contributor_state=AZ) |
| **Stephanie Cadwell** | 亞利桑那登記身分為 **Manager（經理人）**；LinkedIn 自述為 **「Owner/partner at CWIE Holding Company, INC」** | **股東／登記機構幹部** | 經理人身分為 **corroborated**（經鏡像站取得之登記資料）；CWIE 角色為 **single-source，且屬自行發布** | **GAP** · [LinkedIn](https://www.linkedin.com/in/stephanie-cadwell-36ba8348/) | **無可確認之紀錄。** 「CADWELL, STEPHANIE」全國共有九筆 FEC 紀錄（WinRed，**加州**，職業 SELF／SELF-EMPLOYED，2020-07-19 至 2021-03-01，$0.50–$70.00），但全部在**加州**，無法與亞利桑那的登記經理人連結。以 Chula Vista 市過濾（流傳中唯一的地址線索）回傳 **0 筆**。**查無 AZ 紀錄** | [ACC 登記資料，檔號 L15102933](https://www.bizapedia.com/az/phoenix-nap-llc.html) · [LinkedIn](https://www.linkedin.com/in/stephanie-cadwell-36ba8348/) · [FEC — Cadwell, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=cadwell&contributor_state=AZ) |
| **Ian McClarty** | **總裁（President，共同創辦人）** | **高階主管——資本支出核准人／高層贊助者。並非申報經理人**，其權限屬營運層級，在授權範圍內行使 | **primary-record**（九年間持續於供應商與公司新聞稿中具名受訪） | **GAP** — 查無直接公開信箱 · [LinkedIn](https://www.linkedin.com/in/mcclarty) | **查無紀錄——明確之否定結論。** FEC 個人捐款查詢，捐款人姓名「mcclarty」，捐款人州別 **AZ**，全部年度：**「Viewing 0 filtered results」** | [Supermicro 2017 案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf) · [2018 NVIDIA Tesla 新聞稿](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus) · [phoenixNAP RadiusDC 新聞稿，2026-03-17](https://www.prnewswire.com/news-releases/phoenixnap-sharpens-focus-on-on-demand-infrastructure-with-strategic-transaction-for-phoenix-colocation-business-302716069.html) · [FEC — mcclarty, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=mcclarty&contributor_state=AZ) |
| **William (Bill) L. Bell** | **產品執行副總（Executive Vice President of Products）**；在研討會資料中亦呈現為「VP of Product Development, Cloud & Enterprise」 | **技術決策者——掌握 SKU／平台決策。本帳戶最重要的一個名字** | 職務為 **primary-record**；CloudFest 2026 之確切職稱變體為 **single-source** | **確切位址為 GAP。** ZoomInfo 僅顯示遮罩型態 `w***@phoenixnap.com`。**不得將依 ARIN 命名規則推得的 `williamb@phoenixnap.com` 視為已確認——那是推論** · [LinkedIn](https://www.linkedin.com/in/williamb) | **未解決——明確「不是」查無紀錄。** 「Bell, William」過於常見，無法僅憑姓名查詢；用以區辨身分的雇主過濾查詢（contributor_employer ＝ phoenixnap／CWIE ＋姓名）**在 FEC 介面上連續五次卡住**，而 openFEC API 全程對 DEMO_KEY 限流。狀態：**已嘗試查詢，未解決** | [Supermicro 2017 案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf) · [2018 NVIDIA Tesla 新聞稿](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus) · [2026 年 3 月 RadiusDC 新聞稿](https://www.prnewswire.com/news-releases/phoenixnap-sharpens-focus-on-on-demand-infrastructure-with-strategic-transaction-for-phoenix-colocation-business-302716069.html) · CloudFest 講者名單 · [openFEC](https://api.open.fec.gov/v1/schedules/schedule_a/) |
| **Marcus A. Bohn** | Phoenix NAP, LLC 之**法定／登記代理人**；公司 USPTO 商標之 **Attorney of Record 與 Correspondent**；鳳凰城市 Phoenix NAP, LLC **具名遊說主事者**。資料商稱其為「Chief Legal Officer」——**任何申報文件皆未載明此職稱** | **登記機構幹部／高階主管——法務關卡** | 代理人／律師／遊說主事者身分為 **primary-record**；「Chief Legal Officer」職稱為 **single-source（資料商）** | **marcusb@cwie.net** — 同時公布於 USPTO TSDR **與**鳳凰城市遊說 PDF，屬公開合法管道 · **+1-480-467-2450**（電話**與**傳真，公布於 USPTO TSDR）· LinkedIn **GAP — 未能確定定位** | **查無紀錄——明確之否定結論。** FEC 個人捐款查詢，捐款人姓名「bohn marcus」，捐款人州別 **AZ**，全部年度：**「Viewing 0 filtered results」** | [USPTO TSDR sn 87396103](https://tsdr.uspto.gov/statusview/sn87396103) · [USPTO TSDR sn 90366571](https://tsdr.uspto.gov/statusview/sn90366571) · [ACC 登記資料](https://www.bizapedia.com/az/phoenix-nap-llc.html) · [鳳凰城市 2026 年登記客戶名單](https://lobbyist.phoenix.gov/PDF/RegisteredClients/2026) · [FEC — bohn marcus, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=bohn+marcus&contributor_name=carmody+robert&contributor_state=AZ) |
| **Danny Fuentes** | **VP of Information Systems, PhoenixNAP LLC** — 其本人的 FEC 申報記載職業 **「VP」**、雇主 **「CWIE」** | **高階主管／管理職——在建置佈署與資產管理面的技術相鄰影響者** | **corroborated**（LinkedIn 職稱 ＋ 一份顯示 VP／CWIE 的獨立聯邦申報） | **GAP** · [LinkedIn](https://www.linkedin.com/in/danny-fuentes-02b2189/) | **查有紀錄。** FUENTES, DANNY — Mesa, AZ 85212 — 職業 **VP** — 雇主 **CWIE** — **2026-02-18 捐款 $10.00** 予 **ACTBLUE**（C00401224），備註「EARMARKED FOR TALARICO FOR TEXAS (C00919084)」，申報於 Form 3X line 11AI。**本次調查中唯一能連結到 phoenixNAP 具名在職者的 FEC 紀錄** | [LinkedIn](https://www.linkedin.com/in/danny-fuentes-02b2189/) · [FEC — fuentes danny, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=fuentes+danny&contributor_state=AZ) |
| **Robert Carmody** — *ARIN 登錄聯絡人列* | **ARIN 技術聯絡人（CARMO67-ARIN），PhoenixNAP** | **技術聯絡人——網路／IP 工程** | **primary-record**（登錄紀錄） | **robertca@phoenixnap.com** · **+1-480-506-0120** · 3402 E University Dr, Phoenix AZ 85034 · LinkedIn **GAP** | **查無紀錄——明確之否定結論。** FEC 查詢「carmody robert」搭配捐款人州別 **AZ** 回傳 **0 筆** | [ARIN POC CARMO67-ARIN](https://whois.arin.net/rest/poc/CARMO67-ARIN) — 登記與更新皆為 **2026-02-25**，亦即與 RadiusDC 交易同一時間窗建立 · [FEC](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=bohn+marcus&contributor_name=carmody+robert&contributor_state=AZ) |
| **Brian Musgrave** — *ARIN 登錄聯絡人列* | **ARIN 技術聯絡人（MUSGR48-ARIN），PhoenixNAP** | **技術聯絡人——網路／IP 工程** | **primary-record**（登錄紀錄） | **brianmu@phoenixnap.com** · **+1-480-401-0309** · 3402 E University Dr, Phoenix AZ 85034 · LinkedIn **GAP** | **未解決——明確「不是」查無紀錄。** 全國性姓名查詢帶出數筆「MUSGRAVE, BRIAN」紀錄（WinRed 與 ActBlue），但**用以區辨亞利桑那本人所需的州別過濾查詢在 FEC 介面上逾時**。狀態：已嘗試查詢，未解決 | [ARIN POC MUSGR48-ARIN](https://whois.arin.net/rest/poc/MUSGR48-ARIN) — ARIN 登記 **2021-07-13**，紀錄更新 **2026-02-03** |
| **Milos Ilic** — *ARIN 登錄聯絡人列* | **ARIN 技術聯絡人（ILICM-ARIN），PhoenixNAP — 塞爾維亞 Niš** | **技術聯絡人——海外工程。該 org 上*最新*的技術聯絡人** | **primary-record**（登錄紀錄） | **milosi@phoenixnap.com** · **+381 61 549 4754** · Blagoja Parovica, Niš 18000, Serbia · LinkedIn **GAP** | **不適用** — 非美國人士 | [ARIN POC ILICM-ARIN](https://whois.arin.net/rest/poc/ILICM-ARIN) — 建立於 **2026-04-06**，正值分割交易前後 |
| **Adrian Montebello** — *ARIN 登錄聯絡人列* | **ARIN 技術聯絡人（MONTE41-ARIN），PhoenixNAP — 馬爾他 Santa Venera** | **技術聯絡人——EMEA 網路。該 org 上*在任最久*的具名技術聯絡人** | **primary-record**（登錄紀錄） | **adrianm@phoenixnap.com** · **+356 7930 5305** · Phoenix Business Center, Penthouse Level, Triq il-Ferrovija, Santa Venera SVR9022, Malta · LinkedIn **GAP** | **不適用** — 非美國人士 | [ARIN POC MONTE41-ARIN](https://whois.arin.net/rest/poc/MONTE41-ARIN) — ARIN 登記 **2014-04-24**，紀錄更新 **2026-05-08** |
| **Dragan Petrovic** — *ARIN 登錄聯絡人列* | ARIN 技術聯絡人（**PETRO182-ARIN**），其登錄 `companyName` 欄位逐字寫著 **「CCBill EU」**，信箱卻是 @phoenixnap.com | **技術聯絡人——同時是所有權問題上最具證明力的單一登錄證據** | **primary-record**（登錄紀錄） | **draganp@phoenixnap.com** · 行動 **+381 62 144 8366** · 辦公室 **+356 77548965** · 16. Oktobra 23/60, Belgrade 11000, Serbia · LinkedIn **GAP** | **不適用** — 非美國人士 | [ARIN POC PETRO182-ARIN](https://whois.arin.net/rest/poc/PETRO182-ARIN) — ARIN 登記 **2025-07-07**。**CCBill EU 與 phoenixNAP 的人員重疊，就白紙黑字寫在登錄資料裡** |
| **ARIN 職務帳號** — *登錄聯絡人列* | **ADMIN1723-ARIN**（OrgAdmin，「IP Admin」）、**ABUSE2349-ARIN**（OrgAbuse）、**TECH357-ARIN**（一般 Tech） | **登錄機構聯絡人——皆為職務帳號，未具名任何個人（GAP）** | **primary-record**（就「皆為職務帳號」此一事實而言） | Admin **ipadmin@phoenixnap.com**、+1-480-422-2022、3402 E University Dr Suite 420 · Abuse **abuse@phoenixnap.com**、+1-480-422-2022 · Tech **support@phoenixnap.com**、+1-480-646-5362 | 不適用 | [ADMIN1723-ARIN](https://whois.arin.net/rest/poc/ADMIN1723-ARIN) · [ABUSE2349-ARIN](https://whois.arin.net/rest/poc/ABUSE2349-ARIN) · [TECH357-ARIN](https://whois.arin.net/rest/poc/TECH357-ARIN) |
| **PeeringDB 聯絡人** — *網路登錄列* | — | **網路聯絡人（PeeringDB）——未公開任何一位（GAP）** | **primary-record**（就「清單為空」此一事實而言） | net id **2932** 的 `poc_set` 為**空陣列**，`poc_updated` 凍結在 **2016-03-14**——已十年未動。Policy Selective、Heavy Outbound、500–1000 Gbps、10 個 IX、16 處設施。**所有 peering 或網路端接觸都必須改走上方 ARIN 代號** | 不適用 | [PeeringDB AS12189](https://www.peeringdb.com/api/net?asn=12189)（PeeringDB org id 3061） |
| **Michael (Mike) Krza** | **RadiusDC 執行長** — 亦即 phoenixNAP 現正承租之鳳凰城設施的**新所有權人** | **高階主管——交易對手／房東，非 phoenixNAP 幹部** | **corroborated** | **GAP** · [LinkedIn](https://www.linkedin.com/in/michael-krza-3b37637/) | **未執行** — 不在 phoenixNAP 本身具名主事者的範圍內 | 所有權見[馬里科帕郡估價官名冊](https://mcassessor.maricopa.gov/mcs/?q=3402+E+UNIVERSITY+DR)（RADIUS DC PHOENIX I LLC 現為 APN 122-03-089 之所有權人）；領導層資訊出自 RadiusDC 資料／The Org。此前曾任 Flexential 及其前身 ViaWest 之 COO 與 CFO |
| **Joe Guerriero** | **RadiusDC 營運長兼法務長（COO and General Counsel）** | **高階主管——交易對手。將掌管 phoenixNAP 佔用 3402 E University Dr 之租約文件** | **single-source** — 公司自行發布之領導層資料，經搜尋摘要取得；**領導層頁面本身對直接抓取回傳 HTTP 404** | **GAP** · LinkedIn **GAP** | **未執行** | [radius-dc.com/leadership](https://www.radius-dc.com/leadership)（直接抓取回 404）／RadiusDC 成立時之報導。此前曾任 Flexential 與 ViaWest 法務長，最近則於 Alvaria Inc. |
| **Mitch Coan** | **RadiusDC 財務資深副總（Senior Vice President of Finance）** | **高階主管——交易對手** | **single-source** | **GAP** · LinkedIn **GAP** | **未執行** | [radius-dc.com/leadership](https://www.radius-dc.com/leadership)。此前於 Zayo Group 任職七年，包含其 $143 億的私有化交易 |
| **Cindy Anastasi** | **人力資源總監，phoenixNAP**（*出自資料商*） | 管理職 | **single-source — 僅資料商，未經任何一手紀錄查證** | **GAP** | **未解決** — 包含「anastasi」的 AZ 合併查詢在 FEC 介面上**逾時** | [Comparably 高階團隊頁](https://www.comparably.com/companies/phoenix-nap/executive-team)。**列出是為了不讓這個職位被無聲略過；已標示為弱證據** |
| **Harold Winey** | **全球業務與行銷副總，phoenixNAP**（*出自資料商*） | 高階主管 | **single-source — 僅資料商，未經查證** | **GAP** | **未解決** — 包含「winey」的 AZ 合併查詢**逾時** | [Comparably 高階團隊頁](https://www.comparably.com/companies/phoenix-nap/executive-team)。查無任何佐證之新聞引述、申報文件或公司頁面。**若獲確認，將是 Bell 在商務端的對口** |
| **Frank Eickenhorst** | **支援服務與資料中心營運副總，phoenixNAP**（*出自資料商*） | 高階主管 | **single-source — 僅資料商，未經查證** | **GAP** | **全國姓氏查詢查無「FRANK EICKENHORST」之紀錄**，且**亞利桑那州完全沒有任何 Eickenhorst 紀錄**。全國查詢帶出 James Steven、Jay、Daniel R、Danielle、Stephanie E、Kristin 與 Cheryl E Eickenhorst——**沒有一個在亞利桑那，也沒有一個叫 Frank**——對此人在此職位上的存在毫無佐證作用 | [Comparably 高階團隊頁](https://www.comparably.com/companies/phoenix-nap/executive-team) |
| **James G. Busby Jr.** | **Phoenix NAP, LLC 之登錄律師**，亞利桑那州稅務法院 TX2024-000075 | **外部顧問（稅務律師）——非公司幹部** | **primary-record**（法院紀錄） | **GAP** — minute entry 中未公布 · LinkedIn 未定位 | 本次未查詢——**屬 GAP，不是「查無紀錄」** | [2026-05-21 歸檔之 minute entry](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)，承審法官 Hon. Erik Thorson，對造為亞利桑那州稅務局之 **Benjamin H. Updike** |
| **Benjamin Graff**（Quarles & Brady LLP） | 於較早期鳳凰城市遊說登記上簽署、聲明 Phoenix NAP, LLC 為付酬客戶之人；土地使用與都市計畫律師 | **外部——受託事務所之簽署人。並非 phoenixNAP 幹部** | **primary-record**（市政申報） | Quarles & Brady LLP, 2 N. Central Ave. #3, Phoenix AZ 85004，**(602) 229-5696** | 不適用——外部律師 | [鳳凰城市年度遊說登記](https://lobbyist.phoenix.gov/PDF/Registration/40cc5ed5-fd5c-48d3-afd9-ae9b03dc7e62)，2023-07-24（2023 年度）與 2023-01-17（2022 年度）送件 |

### 4.2 登錄紀錄（Registry record）

涵蓋公司登記、聯邦商標登記、市政遊說登記，以及郡府不動產／動產名冊。**每一列 ACC 資料皆適用出處但書：** 該資料讀自**最後更新於 2026-08-11 之登記資料鏡像站**，不是 ACC 官方入口；官方入口有 CAPTCHA 阻擋，且**未被繞過**。

| 名稱 | 身分／權限 | 申報文件 | 申報日期 | 來源 |
|---|---|---|---|---|
| **Ira Ronald Cadwell** | **Manager（經理人）** | 亞利桑那州公司委員會 — **Phoenix NAP, LLC**，本地有限責任公司，檔號 **L15102933**，狀態 **ACTIVE**。主營業地址 **3402 E University Dr Suite 420, Phoenix AZ 85034** | 實體申報於 **2009-03-04**；登記資料最後更新 **2026-08-11** | [ACC 登記資料](https://www.bizapedia.com/az/phoenix-nap-llc.html) |
| **Stephanie Cadwell** | **Manager（經理人）** | 亞利桑那州公司委員會 — Phoenix NAP, LLC，檔號 **L15102933**。**名列第二位經理人**，同為 Suite 420 地址。**本帳戶先前歷次查核從未辨識出此人** | 登記資料最後更新 **2026-08-11** | [ACC 登記資料](https://www.bizapedia.com/az/phoenix-nap-llc.html) |
| **Marcus Bohn** | **法定／登記代理人（Registered / Statutory Agent）** | 亞利桑那州公司委員會 — Phoenix NAP, LLC，檔號 **L15102933**。代理人地址 3402 E University Dr Suite 420, Phoenix AZ 85034 — **請注意他的遊說申報改用 Tempe 的 CCBill／CWIE 大樓 2353 W University Dr** | 登記資料最後更新 **2026-08-11** | [ACC 登記資料](https://www.bizapedia.com/az/phoenix-nap-llc.html) |
| **Marcus A. Bohn** | 公司聯邦商標之 **Attorney of Record 與 Correspondent** | USPTO TSDR — **SECURED SERVERS** 序號 87396103／註冊號 5293238，及 **PHOENIX NAP** 序號 90366571／註冊號 6422118，權利人 Phoenix NAP LLC（亞利桑那 LLC）。信箱 **marcusb@cwie.net**，電話與傳真 **480-467-2450**。**在一份聯邦商標申報文件上出現 @cwie.net 信箱，是登記層級的 CWIE 集團關係證據** | Section 8 聲明 **2024-03-19** 提出、**2024-11-22** 獲准；通訊資料 **2025-01-28** 變更 | [USPTO TSDR sn 87396103](https://tsdr.uspto.gov/statusview/sn87396103) |
| **Phoenix Data Intermediate Pledgor I, LLC** | **Radius DC Phoenix I, LLC 之 Member（登記在案之唯一主事者）** — 該實體現持有 phoenixNAP 原旗艦設施 | 亞利桑那州公司委員會 — Radius DC Phoenix I, LLC，**外州**有限責任公司，AZ 檔號 **25032212**，設立管轄 **德拉瓦州**。Member 地址 2401 E 2nd Ave Ste 400, Denver CO 80206-4735（RadiusDC 的丹佛據點） | 於 ACC 申報 **2026-03-13**；登記資料更新 **2026-08-06** | [ACC 登記資料 — Radius DC Phoenix I, LLC](https://www.bizapedia.com/az/radius-dc-phoenix-i-llc.html) |
| **C T Corporation System** | Radius DC Phoenix I, LLC 之**登記代理人** | 亞利桑那州公司委員會 — Radius DC Phoenix I, LLC，檔號 **25032212**。代理人地址 3800 N Central Ave Suite 460, Phoenix AZ 85012-1992 | 申報於 **2026-03-13** | [ACC 登記資料 — Radius DC Phoenix I, LLC](https://www.bizapedia.com/az/radius-dc-phoenix-i-llc.html) |
| **RADIUS DC PHOENIX I LLC** | 鳳凰城旗艦資料中心地號與相鄰開發地號之**登記所有權人** | 馬里科帕郡估價官不動產名冊：**APN 122-03-089, 3402 E UNIVERSITY DR, PHOENIX 85034**，分區 ALLRED SOUTHBANK，MCR 46809，COMMERCIAL；以及 **APN 122-03-005A, 3221 E ELWOOD ST**，分區 SOUTHBANK，VACANT LAND INDUSTRIAL（與已宣布之 DC2 建案相符）。**這是「鳳凰城設施現在歸誰所有」這個問題的郡府紀錄答案** | 於估價名冊上觀察日 **2026-08-11** | [馬里科帕郡估價官](https://mcassessor.maricopa.gov/mcs/?q=3402+E+UNIVERSITY+DR) |
| **CWIE HOLDING CO INC** | phoenixNAP 旗艦地址之**營業用動產納稅義務人**——**兩個獨立帳戶** | 馬里科帕郡估價官營業用動產名冊，帳號 **9337591** 與 **9337607**，均位於 3402 E UNIVERSITY DR, PHOENIX 85034 — 與同址另一個獨立的 **PHOENIX NAP** 帳戶 **0006384** 並列。關聯實體 **CWIE MANAGEMENT RESOURCES LLC** 持有 APN 215-47-003M（7880 E Beck Ln, Scottsdale，WAREHOUSE），而 **CC PROPERTY INVESTMENTS LLC** 持有 APN 122-03-005B，即緊鄰 RadiusDC 土地的工業地號 | 於估價名冊上觀察日 **2026-08-11** | [馬里科帕郡估價官](https://mcassessor.maricopa.gov/mcs/?q=3402+E+UNIVERSITY+DR) |
| **Phoenix NAP, LLC**（*主事者：Marcus A. Bohn*） | **鳳凰城市登記遊說客戶**——市政層級，非聯邦 | 鳳凰城市 Registered Lobbyist Clients 名冊。登記條目：**Marcus A. Bohn ／ Phoenix NAP, LLC ／ 2353 West University Drive, Tempe AZ 85281 ／ MarcusB@cwie.net** | **CY2025**（名單更新 2025-09-16）與 **CY2026**（名單更新 2026-07-13）之登記客戶 | [鳳凰城市 2026 年登記客戶](https://lobbyist.phoenix.gov/PDF/RegisteredClients/2026) · [2025 年](https://lobbyist.phoenix.gov/PDF/RegisteredClients/2025) |
| **GAP — 受益所有權與出資額比例** | 無法取得 | 亞利桑那州**不要求 LLC 揭露股東或出資比例**，因此 ACC 檔案列出兩位經理人即為止 | 不適用 | **Cadwell 家族與任何 CWIE 實體之間的實際股權分配仍屬未知** |

### 4.3 採購決策圈（Buying committee）

phoenixNAP 是一家**雙經理人的私有 LLC，且有一位有據可查、異常穩定的平台決策擁有者**。這裡的技術決策者不是推論——他連續九年在供應商文件中被具名引述談伺服器平台選型。**這讓接觸順序異常清楚，也讓「從最上面開始談」變成異常容易犯的錯。** 分割之後，**機隊就是公司本身**，因此每一個 SKU 決策都比以往更靠近這門生意的核心。

| 姓名 | 為何對伺服器採購具關鍵性 | 接觸方式 |
|---|---|---|
| **William (Bill) L. Bell** — EVP of Products | **連續九年有據可查的平台選型代言人，也是 Supermicro 唯一曾經引述、說明為何選擇某一世代伺服器的 phoenixNAP 高階主管。** 分割後他們賣掉不動產、留下 Bare Metal Cloud 與網路——機隊就是這門生意。**如果這個帳戶要贏或要輸，就發生在這裡** | **以特定型錄產品線的每 rack-U、每瓦 SKU 經濟性開場，不要用公司能力簡報開場。** 他講的是節點密度、DIMM 數量與每節點 NVMe。最自然的開場是**他自家型錄裡那個已掛著待發、卻始終未標價的 GPU SKU**（第 7、8 節）——直接問卡在哪裡，不要繞著它推銷。**不要猜他的信箱**；經 LinkedIn，或請 ARIN 技術聯絡人引介 |
| **Ian McClarty** — 總裁 | **高層贊助者與資本支出核准人**，也是 RadiusDC 交易雙邊的發言人。**他並非本 LLC 的申報經理人**，因此他是在授權範圍內核准，而不是自己擁有這筆錢——這意味著**任何大額承諾都需要 Cadwell 兩位經理人在後面撐** | **第二次會議，在 Bell 完成平台驗證之後。** 論述框架應圍繞他自己已公開表述的分割後策略——聚焦、隨選基礎設施——而不是硬體 |
| **Ira Ronald Cadwell** — 申報經理人兼創辦人／執行長 | **現已確認為 Phoenix NAP, LLC 的申報經理人，不只是新聞稿上的創辦人。** 他是集團層級資本承諾的最終經濟核准人 | **僅限高層對高層，且必須在 Bell 完成技術認可之後。不要從這裡開場。** 請注意他的法定姓名是 **Ira Ronald Cadwell**——任何文件上都要寫對 |
| **Stephanie Cadwell** — 申報經理人；CWIE Holding Company 之 Owner/Partner | **第二位申報經理人，也是通往 CWIE 所有權方最清楚的人脈連結。** 任何需要股東／經理人層級授權的承諾，合理推斷都需要她與 Ira Cadwell 一起點頭。**她在本帳戶歷次查核中始終不曾出現，這正是她重要的原因** | **不要直接接觸。** 知道她存在、知道她要簽字，並**確保呈給 Bohn 的交易結構，是兩位經理人不必重新談判就能核准的結構** |
| **Marcus A. Bohn** — 登記代理人、Attorney of Record、遊說主事者 | **法務關卡**：ACC 檔案上的法定代理人、商標的 Attorney of Record，以及 2025 與 2026 年仍有效之鳳凰城市遊說登記的具名主事者。他將主導 MSA、保固條款與任何融資或租賃文件。他同時也是對**設備在亞利桑那交易特權稅（TPT）下如何被認定**最敏感的一方 | **不要從這裡開場，但要預期他一定會出現在文件端，並事先準備。** 一個能讓所有權歸屬乾淨、且明確記載為**購置自有資產而非租賃**的交易結構，在他們目前的稅務處境下是真實且非顯而易見的價值點。已公開管道：**marcusb@cwie.net**、**+1-480-467-2450**（兩者皆出自 USPTO 紀錄） |
| **Danny Fuentes** — VP of Information Systems | **新辨識出的副總層級內部系統負責人**，其本人的聯邦申報將雇主填為 **CWIE**。內部系統副總通常掌管佈建、映像檔、監控與資產管理整合——**這些正是決定一次機隊汰換在營運上成或敗的環節** | **技術相鄰的影響者，不是簽核者。** 用來在 Bell 自己必須提問之前，先驗證擬議平台是否吻合他們的佈建與管理堆疊 |
| **Robert Carmody 與 Brian Musgrave** — ARIN 技術聯絡人，鳳凰城 | 兩位都是該 org ARIN 紀錄上**自行登錄、可電話聯繫的鳳凰城工程師**，而且 **Carmody 是在 2026 年 2 月、交易宣布的當下才被加入**。實際上架、佈線、配址機隊的就是他們 | **具公開直撥號碼的正當技術切入點**（+1-480-506-0120／+1-480-401-0309）。用於由下而上探明實際正在佈署的內容，再把這份情報帶進與 Bell 的對話。**不要試圖對他們推銷** |
| **Mike Krza** — RadiusDC 執行長（*房東，不是客戶*） | **馬里科帕郡名冊上，RADIUS DC PHOENIX I LLC 現為 3402 E University Dr 的登記所有權人。** phoenixNAP 想在鳳凰城增加的任何空間、電力或密度，如今都**由一位房東把關**，而該房東自己有 8 MW 的 DC1 擴建與 18 MW 的 DC2 計畫 | **獨立關係、獨立動作，不要混為一談。** 但任何涉及在鳳凰城據點大幅增加電力的 phoenixNAP 提案，都應與 RadiusDC 已公開承諾交付的內容與時程相互檢核 |

### 4.4 未能具名之職位——每一項皆為 GAP

**GAP — CFO／財務副總／財務主辦／司庫：** 任何申報文件、名冊、新聞稿、求職網站或資料商中皆查無姓名。**這是最顯眼的一個空缺，而且很重要——一家分割後手握出售價金的公司，此刻正有一個財務職能在做資本配置決策。** · **GAP — CTO／工程副總／首席架構師：** 查無姓名。公開存在的最高技術職稱是 **EVP of Products**（Bell）。某份資料商摘要提到一位未具名的「Chief Information Officer (T.T.)」與「VP of Architecture and Platform (S.L.)」，**僅有縮寫，不算名字，未予採用**。 · **GAP — 採購／採購主管／供應商管理／尋源負責人：** 任何申報文件、名冊、求職網站結果或資料商中皆無此職稱；**採購權限看起來是直接走產品部門與總裁，而非獨立職能**。 · **GAP — 資料中心營運招募主管：** 已確認鳳凰城有一則 Data Center Technician 職缺存在，但任何求職平台上都**未公布主管姓名、未公布「reports to」、未公布招募人員姓名**。 · **GAP — Section 8 商標聲明之簽署人：** 代理人與 correspondent 現已確知（Marcus A. Bohn），但實際簽署者需調閱申報文件影像，而 **TSDR 的 document／bulk API 現已要求註冊之 USPTO API 金鑰**。 · **GAP — phoenixnap.com 隱私遮罩之前的歷史 WHOIS 登記人**——正是能顯示該網域最初是否由 CWIE／CCBill 實體持有的關鍵資料。所有免費路徑皆遭阻擋（見 4.5）。僅取得現行 Verisign RDAP 紀錄：建立 **2009-02-26T18:04:14Z**，到期 2027-02-26，最後異動 2026-01-27，註冊商 NameCheap（IANA 1068）。 · **GAP — 經理人層級以下之受益所有權與出資額：** ACC 檔案列出兩位經理人，但**亞利桑那州不要求揭露股東／出資比例**，因此 Cadwell 家族與任何 CWIE 實體之間的實際股權分配未知。 · **GAP — 馬爾他與塞爾維亞營運據點之境外登記申報：** 由 ARIN 可證實員工登記於 Santa Venera（馬爾他）與 Niš／貝爾格勒（塞爾維亞），但**未取得任何馬爾他或塞爾維亞公司登記文件**。 · **GAP — William L. Bell 的確切電子郵件：** ZoomInfo 僅顯示遮罩型態 `w***@phoenixnap.com`；**依 ARIN 規則推得的位址已刻意不予採用**。 · **GAP — Marcus A. Bohn、Robert Carmody、Brian Musgrave、Milos Ilic、Adrian Montebello、Dragan Petrovic、Joe Guerriero 與 Mitch Coan 之 LinkedIn 網址**——未能定位。 · **GAP — WebHostingTalk、LowEndTalk、Reddit 或 Hacker News 上經查證之員工帳號及其真實姓名：** 已搜尋，**未浮現任何可查證者**。只有第三方討論 phoenixNAP 的串，沒有任何可辨識的員工帳號。 · **GAP — 2025–2026 年 NANOG、SC、GTC、DataCenter World 或 HostingCon 上具名 phoenixNAP 員工的講者簡介：** 僅找到一則與 Bell 有關的 **CloudFest 2026 論壇引用**，**未取得任何講者簡介頁**。 · **GAP — TX2024-000075 以外之法院案卷，以及載有 secured party／debtor 簽署人的 UCC-1 申報：** 本次未執行 PACER、聯邦案卷或亞利桑那州州務卿 UCC 查詢。 · **GAP — RADIUS DC PHOENIX I LLC 取得 APN 122-03-089 之產權移轉文件編號、登記日期與對價：** 估價名冊顯示所有權人已變更，但**馬里科帕郡地政事務所之產權移轉文件本身並未調閱**，因此交割日期與價格仍屬未知。 · **GAP — phoenixNAP、CWIE 或 CCBill 之公司 PAC：** FEC 委員會名稱查詢**始終未回傳**（介面卡住、API 限流）。403 筆員工紀錄的受贈對象型態*暗示*其不存在，但**未經證明**。 · **GAP — William L. Bell、Brian Musgrave、Adrian Montebello 與 Cindy Anastasi 之 FEC 狀態：** 已嘗試查詢，但**逾時或無法區辨身分**。明確**不得**記為「查無紀錄」。 · **GAP — 3492 E University Dr 的「Cadwell, Rockridge」是否與 phoenixNAP 經理人有關：** 該亞利桑那州級申報本身是真實的一手資料，但**身分連結並未確立**。

### 4.5 已實際查詢之來源——含「查無」者

**有產出者。** **ARIN Whois REST** 是本帳戶最豐富的人員來源：`autnum 12189` **確認**了 phoenixNAP（org PHOEN-56「PhoenixNAP LLC」，登記於 2013-03-07）；`org PHOEN-56` 回傳 org 紀錄（3402 E. University Drive，更新於 2026-04-06，自營 rwhois 於 rwhois.phoenixnap.com:4321）與 **8 個 POC 代號**的完整清單；8 筆 POC 紀錄全數讀取，取得**五位具直接信箱與直撥電話的真實具名人員**（Musgrave、Ilic、Montebello、Petrovic、Carmody）加三個職務帳號，其中**兩位 POC 是前一版之後新增的**；`org PHOEN-56 nets` 回傳 **12 筆 IPv4／IPv6 資源**——64.38.220.0/22（PNAP-01）、104.244.52.0/22（PNAP-03）、144.90.0.0/16、192.240.192.0/18、69.160.32.0/20、103.67.200.0/22、125.253.64.0/18、199.201.104.0/21（SC-ASH）、23.235.242.0/24 與 23.235.243.0/24（PHOENIXNAP），以及 IPv6 2607:3000::/32（SECURED-CLOUD）與 2607:6000::/32（PHOENIXNAP-V6）。 · **ARIN `autnum 23033`** 產生了第 3 節的**更正**：該 ASN 屬於 Wowrack.com（WOWTEC-1），不是 phoenixNAP。 · **以 Bizapedia 作為 ACC 登記資料鏡像**是**本次的突破口**：檔號 L15102933，2009-03-04 申報，ACTIVE，主營業地址 3402 E University Dr Suite 420，法定代理人 MARCUS BOHN，以及**兩位經理人——IRA RONALD CADWELL 與 STEPHANIE CADWELL**，另附完整商標組合與註冊號、有效／失效狀態；第二次查詢回傳 **Radius DC Phoenix I, LLC**（AZ 外州 LLC 25032212，德拉瓦州設立，代理人 C T Corporation System，唯一 Member 為位於丹佛的 Phoenix Data Intermediate Pledgor I, LLC）。 · **馬里科帕郡估價官地號查詢**是**本次單一價值最高的來源**：RADIUS DC PHOENIX I LLC 持有 APN 122-03-089（旗艦）與 APN 122-03-005A；CC PROPERTY INVESTMENTS LLC 持有相鄰的 122-03-005B；CWIE MANAGEMENT RESOURCES LLC 持有一處 Scottsdale 倉庫；營業用動產名冊則顯示 **CWIE HOLDING CO INC（兩個帳戶）與 PHOENIX NAP 並列**於同一旗艦地址。 · **USPTO TSDR statusview** 對序號 **87396103** 與 **90366571** 回傳 Marcus A. Bohn 的完整律師／correspondent 紀錄，含 **marcusb@cwie.net** 與 480-467-2450，兩件商標皆在 **Supplemental** register。 · **參議院 LDA API** 對六種客戶名稱變體回傳乾淨、明確的**零**。 · **鳳凰城市遊說登記** — CY2025 與 CY2026 的 Registered Clients 名冊 PDF 已下載並解析，另加一份登記明細 PDF。 · **FEC 資料瀏覽器**產出四項明確否定（mcclarty/AZ、bohn marcus/AZ、carmody robert/AZ、cadwell/AZ 全 45 筆）、一項**命中**（fuentes danny/AZ），以及雇主為「CWIE」／AZ 的 403 筆彙總。 · **FEC 委員會紀錄** C00919084 與 C00401224 回傳完整委員會明細。 · **亞利桑那 SeeTheMoney** — 直接下載並解析了一份公開報表 PDF。 · **forebears.io** 對 Yee、Childress、Talarico、Lee、Gilmer、DeBergalis 與 Wallace 的姓氏頁皆回傳語源、出現數與分布（須用 WebFetch；直接 curl 無內容，因頁面為 JS 渲染）。 · **Verisign RDAP** 對 phoenixnap.com 僅回傳現行紀錄。 · **LinkedIn 公開個人頁**取得 Ian McClarty、William Bell、Ron Cadwell、Stephanie Cadwell、Danny Fuentes 與 Michael Krza 的可用網址。

**已觸及但在人員面查無者。** **PeeringDB**（`net?asn=12189`、`org?name_search=phoenixnap`）——`poc_set` 為空陣列，`poc_updated` 凍結在 2016-03-14，org 紀錄地址欄位全空；**確認為硬性否定**。 · **phoenixnap.com/company/leadership** 與 **/about-us** — **兩者皆 HTTP 404**；該公司在最顯而易見的網址上根本沒有發布領導層頁面，這本身就是一項發現。 · **radius-dc.com/leadership** — 直接抓取回 **HTTP 404**，因此 Krza、Guerriero 與 Coan 只能以來自新聞報導的 single-source 信心度呈現。 · **Bizapedia 之 CWIE Holding Company, Inc. 頁面** — 連續四次嘗試（含強制重新載入）都**停在「Performing a quick security check」的過場畫面**，因此 **CWIE 母公司自身的幹部仍未讀取**。 · **馬里科帕郡估價官地號明細頁與 JSON API** — `/parcel/122-03-089` 呈現空白，`/mcs/122-03-089/` 回 404，JSON API 需要 AUTHORIZATION token，因此**產權移轉文件編號、成交日與對價皆未取得**。 · **網路搜尋** WebHostingTalk／LowEndTalk／Reddit／HN 員工帳號、研討會講者簡介（NANOG、CloudFest、DataCenter World、HostingCon、SC、GTC），以及帶有具名招募主管或「reports to」的職缺——**全部沒有可用結果**；ziprecruiter／Indeed 上確實有一則鳳凰城 Data Center Technician 職缺，但無主管、無招募人員、無回報線。 · 一般性高階主管搜尋帶出 **Danny Fuentes** 這個真正的新名字，以及僅出自資料商的 **Cindy Anastasi、Harold Winey 與 Frank Eickenhorst**，三者皆無法對照任何一手紀錄取得佐證。

**受阻或未觸及者及其原因。** **亞利桑那州公司委員會** — 於真實瀏覽器工作階段中以 Business ID L15102933 查詢 arizonabusinesscenter.azcc.gov 的 Business Search：**遭圖形字元 CAPTCHA 阻擋**（「User validation required to continue」）。**未破解、未繞過，符合政策。** 舊主機 ecorp.azcc.gov 回傳連線失敗（DNS／主機已失效）。 · **ACC API** — 自該站自家 Angular bundle 取出的端點（`businesssearch/public-search`、`businesssearch/get`、`businesssearch/getbyidasync`）全數回傳 **HTTP 401「Authentication Failed」**；並請注意該 API 自身的路由名稱包含 `getcaptchafilinglist` 與 `getcaptcharegisteragenthistory`，亦即**申報歷史在設計上就是 CAPTCHA 控管的**。 · **OpenCorporates** `us_az/L15102933` — **HAProxy CAPTCHA 過場**，未繞過。 · **openFEC API**（DEMO_KEY）— **整段作業期間每一次呼叫都回傳 `{"error":{"code":"OVER_RATE_LIMIT"}}`**：依姓名的 schedule_a、依雇主的 schedule_a，以及委員會名稱 typeahead 皆然。**要完成雇主端的 FEC 工作，必須改用已註冊的 api.data.gov 金鑰。** · **FEC 資料瀏覽器，雇主「phoenixnap」／「phoenix nap」** — **反覆逾時**，三種網址變體共六次嘗試全部卡在「Loading…」；**記為「已嘗試查詢，未解決」**。 · **FEC 資料瀏覽器，含 musgrave／montebello／anastasi／winey 的 AZ 合併查詢** — **逾時**。 · **FEC 委員會瀏覽器** `q=phoenixnap／cwie／ccbill` — **逾時，從未回傳**；公司 PAC 問題未解決。 · **USPTO TSDR JSON API**（tsdrapi.uspto.gov）— **HTTP 401，現已要求 API 金鑰**；tmsearch.uspto.gov POST 回 HTTP 405 MethodNotAllowed。**因此聲明簽署人仍為 GAP。** · **馬里科帕郡地政事務所** — **未觸及**；RadiusDC 取得產權之移轉文件仍未調閱。 · **whoisrequest.com/history/phoenixnap.com** — WebFetch 回 HTTP 403，於瀏覽器中則顯示「Page not found!」。 · **whoxy.com/phoenixnap.com** — **遭「I'm not a Robot」機器人偵測攔截；未繞過，符合政策。** · **azfollowthe.money** — HTTP 403。 · **亞利桑那 SeeTheMoney 搜尋入口** — 卡在 Cloudflare 過場（但報表 PDF 仍直接取得）。 · **OpenSecrets** — 對自動化請求回 Cloudflare HTTP 403，與前一版一致；不過既然聯邦 LDA 申報已確認為**零**，OpenSecrets 的遊說檔案本來就應該是空的。 · **德拉瓦州公司司** — 對 Phoenix NAP LLC **未查詢**，因其為亞利桑那本地 LLC，本就不應有德拉瓦檔案；但德拉瓦**確實**經由 Radius DC Phoenix I, LLC 的亞利桑那外州 LLC 申報，確認為該公司的設立管轄。 · **法院案卷與 UCC-1 申報** — 本次未執行；**這是尋找幹部簽署人的一條真正未開發路徑**。

**在不驚動公司的前提下、補齊其餘缺口的最佳中性路徑：** 調閱 APN 122-03-089 的**馬里科帕郡地政事務所產權移轉文件**。單這一份文件就能確定 RadiusDC 的交割日期與對價，而其簽署欄很可能是 phoenixNAP 一方授權簽署人姓名最可能的公開來源——那是最後一個不必接觸公司就能補上的幹部等級缺口。

---

## 5. 據點與機房

十六處網路設施中，只有六處提供**已標價的 Bare Metal Cloud 運算資源**；其餘十處是網路 PoP，**不是伺服器採購標的**。這個區分比設施總數重要得多。

| 站點 | 機房營運商 | 自有／租用 | 面積與電力（僅列已公布者） | 證據 |
|---|---|---|---|---|
| **鳳凰城 — 3402 East University Drive, AZ 85034（「PHX」，旗艦兼總部）** | **由 phoenixNAP 自建自有。** 自 2026 年 3 月起**正被出售給 RadiusDC**（IPI Partners 設立之平台；執行長 **Mike Krza**） | **自有 → 2026 年第二季轉為租用／承租方。這是本帳戶最重要的單一結構性變化** | 約 **200,000 平方英尺**，2010 年啟用；該不動產據報於 2009 年以 **$6.3M** 購入；報導稱約 **20 MW，並擴充至 25 MW**。RadiusDC 自家新聞稿則描述 **DC1 擴充至 8 MW 總 IT 電力**，並規劃 **DC2 達 18+ MW**（首批階段 2028 上半年），最終形成約 **26 MW** 的 Phoenix I 園區。**20 MW 的機房數字與 8 MW 的「IT 電力」數字量的是不同的東西——以「報導值」看待，不要視為已對帳** | [RadiusDC 新聞稿 2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) · [phoenixNAP 新聞稿 2026-03-17](https://www.prnewswire.com/news-releases/phoenixnap-sharpens-focus-on-on-demand-infrastructure-with-strategic-transaction-for-phoenix-colocation-business-302716069.html)。phoenixNAP 保留約 80% 全球業務含 Bare Metal Cloud 與網路。**Datacentermap 已將 3402 E University Dr 標示為「RadiusDC Phoenix I DC1」**，而 PeeringDB 仍列有一處名為「PhoenixNAP」的鳳凰城設施。**GAP：$6.3M 的 2009 年購入價為新聞數字，未對郡府登記處查核** |
| **鳳凰城 PHX02 — 3221 E Elwood Street（第二棟）** | phoenixNAP 開發案 | 開發中／依報導為自有 | 報導稱約 **530,000 平方英尺、30 MW**，目標 **2026 年第四季**完工 | **未確認。** 由 DataCenterDynamics 報導，但 **DCD 對直接抓取回 HTTP 403——此數據出自[該篇文章](https://www.datacenterdynamics.com/en/news/phoenixnap-set-to-break-ground-on-second-data-center-in-phoenix-arizona/)的搜尋結果摘要，非原文閱讀。** 須與 RadiusDC 新聞稿中「development rights for future campus expansion」的措辭對照，兩者可能指同一塊土地 |
| **維吉尼亞州 Ashburn（「ASH」）** | **DataBank Ashburn（IAD1）** 與 **Equinix DC1-DC15／DC21-DC22** | **租用**（phoenixNAP 為承租戶／colo 客戶） | 未揭露 | [PeeringDB AS12189 netfac_set](https://www.peeringdb.com/api/net?asn=12189&depth=2)。**ASH 是有效的 BMC 地區，承載完整 GPU SKU 組合，且價格與 PHX 完全相同** |
| **阿姆斯特丹／荷蘭（「NLD」）** | **Iron Mountain Data Center — Amsterdam（AMS-1）** | **租用** | 未揭露 | [PeeringDB](https://www.peeringdb.com/api/net?asn=12189&depth=2)。NLD 為已標價 BMC 地區，含全部三個 GPU SKU。phoenixNAP 自家網路頁把**鳳凰城與阿姆斯特丹描述為其兩座「data centers」**，其餘皆為網路節點 |
| **新加坡（「SGP」）** | **Equinix SG1** 與 **Equinix SG3** | **租用** | 未揭露 | [PeeringDB](https://www.peeringdb.com/api/net?asn=12189&depth=2)。已標價 BMC 地區，含全部三個 GPU SKU |
| **芝加哥／伊利諾州 Elk Grove Village（「CHI」）** | **Equinix CH3 — Elk Grove** | **租用** | 未揭露 | [PeeringDB](https://www.peeringdb.com/api/net?asn=12189&depth=2)。已標價 BMC 地區，含全部三個 GPU SKU——**這與行銷頁宣稱 GPU 僅在「鳳凰城與 Ashburn」的說法互相矛盾。價格型錄的說法不同，而型錄才是有效來源** |
| **華盛頓州西雅圖（「SEA」）** | **Equinix SE2／SE3 — Seattle** | **租用** | 未揭露 | [PeeringDB](https://www.peeringdb.com/api/net?asn=12189&depth=2)。已標價 BMC 地區，含全部三個 GPU SKU |
| **無已標價 BMC 運算的網路節點設施：** 亞特蘭大（Digital Realty ATL13）、洛杉磯（Equinix LA1）、法蘭克福（Equinix FR7）、馬德里（Equinix MD2）、雪梨（Equinix SY1/SY2）、華沙（Equinix WA1）、米蘭（Equinix ML2）、貝爾格勒（Cetin Data Center） | Equinix／Digital Realty／Cetin | **租用** | 未揭露 | [PeeringDB netfac_set](https://www.peeringdb.com/api/net?asn=12189&depth=2) — AS12189 共 16 處設施。**線上型錄中沒有任何一處掛有已標價的 BMC 運算 SKU——它們是網路 PoP，因此不是伺服器採購標的** |

**結構性註記（本節最重要的一句）：** 2026 年第二季交割之後，phoenixNAP 將首次在自家旗艦據點向房東支付電費。**每一瓦都會變成他們看得見的帳上項目。** 這使得仍掛在價目表上的十二年舊節點（第 6 節）從一個抽象的密度論述，變成一個租金帳單上的論述。

---

## 6. 硬體機隊

本節證據等級：**已確認（CONFIRMED）**＝第一手具名揭露或多方獨立佐證｜**旁證（CIRCUMSTANTIAL）**＝行為或 SKU 命名強烈指向，但無已發布之協議｜**反證（CONTRADICTED）**＝證據方向相反｜**GAP**＝正反皆查無，亦即**未評估，不是排除**。

### 6.1 供應商證據分級

| 供應商／類別 | 證據等級 | 證據實際內容 |
|---|---|---|
| **Supermicro（Super Micro Computer, Inc.）** | **已確認** | 三條獨立線索。**（1）** Supermicro 發表過一份七頁共同案例研究《SUPERMICRO AND PHOENIXNAP PARTNER TO DELIVER IT EQUIPMENT FOR EVOLVING BUSINESS OPPORTUNITIES》，2017 年 6 月，文件編號 `14_PhoenixNAP-CaseStudy_2017-06_Rev1`，內含 **Ian McClarty（總裁）** 與 **William Bell（產品副總）** 的具名引述。文中載明 phoenixNAP 選用 **Supermicro X11 Building Block Solutions 與 SuperServers**，部署 **BigTwin 2U 4 節點**系統與 **Simply Double SuperStorage 全快閃 NVMe**，並在所有據點使用 **Supermicro Rack Scale Design** 與 **Supermicro Server Manager（SSM）**。文中亦載明 phoenixNAP「participated in Intel's Early Deployment program to validate performance and new platform features with Intel Xeon Scalable Processor Family **THROUGH SUPERMICRO**」——**Supermicro 就是他們取得早期矽晶的通路。** **（2）** ServeTheHome 在鳳凰城機房實測 phoenixNAP BMC `d3.m6.xlarge` 執行個體，指認其為 **Supermicro twin node**（2023-03-31 發表）——六年後的獨立、非行銷佐證。**（3）** phoenixNAP 維持一個線上的「Bare Metal Cloud Ecosystem」頁面 `/offers/supermicro-servers`，載明「phoenixNAP utilizes Supermicro's solutions to ensure Bare Metal Cloud servers deliver stability, reliability, and efficiency.」（[案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf) · [ServeTheHome](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/) · [/offers/supermicro-servers](https://phoenixnap.com/offers/supermicro-servers)） |
| **HPE（Hewlett Packard Enterprise）** | **已確認——而且這是競爭失分指標** | HPE 於 **2025 年 4 月**發布新聞稿（businesswire 2025-04-04 與 hpe.com 新聞室），標題為《phoenixNAP Advances Cloud Services Using HPE Disaggregated Data Center Modular Hardware System Servers with Intel Xeon 6》，稱其為 **HPE 首個符合 DC-MHS 設計規範的解耦式運算硬體**。`s4.x6`（Intel Xeon 6 6731E）SKU 於同一時間窗出現在 phoenixNAP 自家型錄中。**請注意界限：新聞稿內文從未被讀取**——hpe.com 於 60 秒逾時且未重試——因此**部署規模、機型與是否有 phoenixNAP 高管引述皆為未讀**。供應商關係本身由標題加型錄佐證確認（[HPE 新聞室](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)） |
| **Intel（矽晶，非機殼）** | **已確認** | Intel 矽晶佔絕對主導：**84 個伺服器 SKU 中有 68 個搭載 Intel CPU**（Xeon Scalable 第 1–4 代、Xeon 6 P-core 與 E-core、Xeon E 系列、Core i9 14900K）。**三個 GPU SKU 全部是 Intel Data Center GPU Max 1100。** phoenixNAP 設有專屬的 Intel Max GPU 與 Intel Xeon 6 產品落地頁。2017 年案例研究載明 phoenixNAP 參與 **Intel 的 Early Deployment／Early Ship 計畫**。GPU 節點上另特別標註啟用 SGX。**Intel 是平台錨點**（[/offers/intel-data-center-max-gpu-1100-bmc](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc)） |
| **NVIDIA** | **就現行隨選型錄而言＝反證／就歷史客製專用伺服器而言＝已確認** | phoenixNAP 於 **2018-10-01** 發表 **NVIDIA Tesla V100 與 Tesla P40** 專用伺服器，提供 4 張或 8 張 V100 搭配 NVLink，並引述 McClarty 與 Bell。**但 2026-08-11 的線上價格型錄中，NVIDIA SKU 為零**——已逐一列舉全部 101 個產品代碼與每一個 `gpuConfigurations` 區塊，全網唯一出現的 GPU 字串是「Intel Max 1100 GPU」。第三方部落格（Cherry Servers、Ventus）宣稱 phoenixNAP 提供「L4 到 H100」；**此說法不受 phoenixNAP 自家型錄支持，且無法由任何 phoenixNAP 發布之來源佐證。不得在客戶面前複述 H100／L40S 的說法**（[2018 新聞稿](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus) · [線上型錄](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)） |
| **Dell** | **GAP — 未評估，不是排除** | 正反皆查無。phoenixNAP 任何已發布頁面、新聞稿、PeeringDB 紀錄，或所觸及的 Supermicro／ServeTheHome 素材中皆無 Dell 字樣。**這僅是「缺乏證據」**——本次未執行針對 Dell 的專項檢索，且該型錄中根本不出現任何供應商名稱，只有 CPU／GPU 零件名。**請將 Dell 視為未評估** |
| **Ampere Computing（矽晶）** | **矽晶已確認／機殼供應商 GAP** | `a1.c5`（Ampere Altra Q80-30）與 `a2.c9`（AmpereOne A96-36X）SKU 皆為線上且已標價。**Arm 節點背後的機殼供應商不明** |
| **AMD（矽晶）** | **矽晶已確認／機殼供應商 GAP** | `s4` 系列採用 **EPYC 4345P** 與 **EPYC 4565P** — **僅入門級單路。型錄中無 SP5／Genoa／Turin，亦無任何 Instinct MI 系列 GPU** |
| **Netris（網路軟體）與 Pliops（儲存加速器）** | **旁證** | 型錄中列有 `netris/softgate_1g`、`netris/softgate_10g` 與 `netris/softgate_25g` 為已標價產品，並有一個 `d2.c4.db1.pliops1` SKU（雙 Xeon Gold 6336Y、256 GB、4× 4 TB NVMe），暗示配有 Pliops XDP 卡。**這是真實的整合夥伴，但證據僅止於 SKU 命名，並無已發布之協議** |
| **VMware 與 Veeam（軟體）** | **歷史上已確認** | 2017 年 Supermicro 案例研究載明 phoenixNAP 為「a VMware Premier Service Provider and Veeam Platinum Partner」。**已九年——現況未經查證** |

### 6.2 機隊本身

| 項目 | 證據內容 | 依據 | 對 Supermicro 的對照 |
|---|---|---|---|
| **機隊所有權——法律上已確立，非推論** | 亞利桑那州稅務法院紀錄：「PNAP's customers pay for … (2) infrastructure as a service（"IaaS"）services（**utilization by customers of PNAP-owned servers**）」（PSOF ¶10）。稅務局成功主張、法院並認定「the computer hardware (i.e., servers) and software are tangible personal property」為 PNAP 出租之標的 | **法院紀錄**——能證明這是一家「自購機隊」業者而非轉售他人硬體者的最強證據（[TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)） | **這是整個帳戶的資格條件：他們取得伺服器的所有權** |
| **線上 BMC 伺服器 SKU 總數** | **84 個具完整硬體 metadata 的伺服器產品代碼**，加 **3 個 GPU SKU**，加儲存／頻寬／OS／Netris 品項——**合計 101 個產品代碼**——橫跨 **6 個地區**標價 | 直接讀取線上快取定價 API，1,061,819 bytes，2026-08-11 取得（[api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)） | 84 SKU × 6 地區，每個 SKU 在每個地區都需備品池，**下限推得為數千台實體節點。確切節點數未揭露——見第 15 節** |
| **實機指認的 Supermicro 節點 — `d3.m6.xlarge`** | 雙 **Intel Xeon Platinum 8452Y**（各 36c/72t，Sapphire Rapids）、標配 512 GB、2× 4 TB NVMe、雙 25 GbE 綁定——經實機拆解指認為 **Supermicro twin node** | [ServeTheHome 實機評測，2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)，於鳳凰城機房實測一台 phoenixNAP BMC 執行個體。**這是本次取得的唯一一項第三方實機機殼供應商指認** | **Supermicro BigTwin／X13 2U 4 節點——直接的既有供應商證據。** `d3.m6.xlarge` 與 `d3.m6.xxlarge`（1 TB）**今日皆仍在線並標價** |
| **旗艦 GPU 節點 — `d3.g2.c3.xlarge`** | **2× Intel Data Center GPU Max 1100**（56 Xe cores、48 GB HBM2E、各 300 W）＋ 雙 **Xeon Gold 6442Y**（24c @ 2.6 GHz，啟用 SGX）＋ **512 GB DDR5** ＋ **4× 2 TB NVMe** ＋ **2× 25 Gbps** 綁定 | 線上型錄 JSON 的產品 metadata 區塊，逐字取得 | 雙路 Sapphire Rapids 平台，承載兩張雙寬 300 W PCIe Gen5 加速卡，加 4× U.2 NVMe 與雙 25G SIOM／OCP NIC。Supermicro GPU SuperServer 與 X13 雙路 GPU 產品線直接涵蓋此規格範圍。**注意：GPU 節點的實體機殼供應商並未確認——見下方 GAP 列** |
| **機隊中最新的 CPU 世代 — `s5.x6` 系列（Intel Xeon 6 P-core／Granite Rapids）** | `s5.x6.c3.large/medium`（Xeon 6527P，256 GB）、`s5.x6.c8.large/medium`（Xeon 6767P）、`s5.x6.c9.large/medium`（Xeon 6770P）、`s5.x6.m8.xlarge`／`m9.xlarge`（512 GB）、`s5.x6.s5.large`（Xeon 6767P，512 GB，6× 15 TB NVMe ＋ 1× 1 TB） | 線上型錄 JSON；**首見於 2025-11-09 的 Wayback 快照，2025-04-23 快照中不存在** | **單路 Intel Xeon 6 P-core 平台——Supermicro X14 Hyper／單路 SuperServer 的守備範圍。這是一次真實發生的 2025 年採購事件，帳戶團隊應該要知道這一單是否拿到** |
| **Intel Xeon 6 E-core（Sierra Forest）— `s4.x6` 系列——由 HPE 供應** | `s4.x6.c6.large`（Xeon 6 6731E，256 GB，2× 2 TB NVMe）與 `s4.x6.m6.xlarge`（512 GB，2× 4 TB NVMe） | 線上型錄 JSON；**首見於 2025-01-14 的 Wayback 快照**，並由 [HPE 2025 年 4 月 DC-MHS 新聞稿](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)佐證 | **競爭失分指標。在有反證之前，`s4.x6` 產品線應視為 HPE 已握有** |
| **Arm 機隊 — `a1`／`a2` 系列** | `a1.c5.large/xlarge`（**Ampere Altra Q80-30**，256 GB）；`a2.c9.large`（**AmpereOne A96-36X**，256 GB，1× 4 TB ＋ 1× 1 TB NVMe）與 `a2.c9.xlarge`（384 GB） | 線上型錄 JSON。**a2／AmpereOne 系列存在於 2026-08-11 的線上型錄，但在 2025-11-09 與 2026-01-17 兩份 Wayback 快照中皆不存在——這是一次發生於 2026-01-17 至 2026-08-11 之間的採購事件** | Supermicro ARM／MegaDC Ampere 平台。**這是本次能確定日期的最近一次採購事件，因此也是「採購動能仍活躍」最新鮮的證據** |
| **AMD 機隊 — `s4` 系列** | `s4.c3.medium`（EPYC 4345P，128 GB）、`s4.c6.medium/large/xlarge`（EPYC 4565P，128–192 GB）、`s4.s2.large`（EPYC 4345P，64 GB，2× 8 TB ＋ 1× 1 TB NVMe） | 線上型錄 JSON；`s4` 系列首見於 2025-01-14 | AMD 4004／4005 系列單路 AM5 平台——Supermicro AS-1015／AS-2015 等級。**注意這是入門級 EPYC，不是 SP5——屬於成本最佳化的專用伺服器線，不是 AI 機隊** |
| **高密度 NVMe 儲存節點** | `d3.s5.xlarge`（雙 Xeon Gold 6430，256 GB，**6× 15.36 TB NVMe** ＋ 1× 1 TB）與 `s5.x6.s5.large`（Xeon 6767P，512 GB，6× 15 TB NVMe ＋ 1× 1 TB） | 線上型錄 JSON | **Supermicro「Simply Double」SuperStorage 全快閃 NVMe 在 2017 年案例研究中被明確點名為已部署於 phoenixNAP**——這條產品線有明確的 Supermicro 淵源，是天然的汰換標的 |
| **仍在創造營收的舊機隊** | `s0.d1.small`／`s0.d1.medium`，搭載 **Intel E3-1240v3／E3-1270v3**（Haswell，**2013 年世代**，16–32 GB、SATA SSD、**2× 1 Gbps**）——**2026 年仍在標價販售** | 線上型錄 JSON | **汰換標的。** 十二年前的單路 Haswell 節點、掛在 1 GbE 上，至今仍在價目表中。這是一個具體、可標定日期的生命週期終止對話，帶有清楚的電力／密度 ROI 論述——**而且在他們變成向 RadiusDC 繳電費的承租方之後，這個論述會更鋒利** |
| **已建置但未發表的 GPU SKU — `d3.g3.c2.medium`** | 產品代碼存在於 phoenixNAP 的產品系統中，但**無伺服器產品紀錄、無硬體 metadata、無價格**。它只以關聯產品代碼的形式，出現在 **Windows Server 2025 Datacenter**（sku `WWBN-M6YV-QYJ6`）與 **Windows Server 2025 Standard**（sku `CBHG-TCTK-B1QS`）兩筆 OS 授權列上，**且價格皆為 0** | 首見於 **2025-04-22** 快取之 Wayback 快照（`20250423054018`）。**在 2026-08-11 取得的線上型錄中仍然存在，形式完全相同（$0 OS 關聯）。** 兩處皆已驗證其「不存在為伺服器產品」 | **本帳戶最好的單一採購訊號。** 一個次世代 GPU SKU（「g3」，g2／Max 1100 產品線的後繼）已在其內部產品系統中掛了約 16 個月，卻從未被賦予硬體規格或價格。這是**一個原則上已決定、但尚未在矽晶或資本支出上拍板的 GPU 平台決策的特徵。任何來源都未指名任何 GPU 型號——不要猜** |
| **GAP — GPU、Ampere、AMD 與 Xeon 6 P-core 節點的機殼供應商** | **不明。** Supermicro 在 `d3.m6` twin node 上由實機拆解確認、在 BigTwin／SuperStorage 上由 2017 案例研究確認，但**沒有任何證據指出誰製造雙 Max 1100 的 `d3.g2` 節點**，或 Ampere、AMD、Xeon 6 P-core 節點 | 所觸及之全部來源皆無證據 | **不得就這些產品線陳述任何機殼供應商。這是一個探詢題，不是已知事實** |

### 6.3 觀察到的 CPU 世代，以及對機隊年齡的意涵

以下直接由線上已標價型錄讀出（此為由公開組態推得的**平台族系推論**，非廠商揭露）：

- **當世代：** Intel Xeon 6 P-core（Granite Rapids — 6527P／6767P／6770P）；Intel Xeon 6 E-core（Sierra Forest — 6731E）；AmpereOne A96-36X；AMD EPYC 4565P／4345P（AM5 入門級）
- **中生代：** Intel Xeon Scalable 第 4 代（Sapphire Rapids — Platinum 8452Y、Gold 6442Y／6436／6426／6430）；Ampere Altra Q80-30；Intel Xeon Gold 6336Y
- **仍在創造營收的舊世代：** Intel Xeon E3-1240v3／E3-1270v3（**Haswell，2013**），掛在 2× 1 Gbps 上
- **網路標準：** **每一個伺服器 SKU 的上限都是 2× 25 Gbps 綁定**，較舊的 s0–s3 層級為 2× 1 Gbps 或 2× 10 Gbps。**型錄中任何地方都沒有 100G 伺服器網卡**

**意涵：** 這是一支**啞鈴型且多供應商**的機隊。phoenixNAP 在同一份價目表裡同時掛著 2013 年的 Haswell 與 2025 年的 Granite Rapids，而且**至少同時向兩家系統廠採購**（Supermicro 由拆解與案例研究確認；HPE 由新聞稿確認、且拿下最新的 E-core 矽晶）。因此對 Supermicro 而言，實際可切入的點是 **GPU 平台決策、機殼供應商不明的 Xeon 6 P-core 與 Ampere 產品線，以及那批十二年舊的 s0 層級**——**不是** `s4.x6` 產品線，該線在有反證之前應視為已失。全機隊 2×25 Gbps 的上限，則是任何多節點 AI 訓練論述的真實限制，也是一條正當的探詢主線。

---

## 7. GPU 型錄與 AI 佈局

**已確認、範圍狹窄、且明顯停滯。** phoenixNAP 全部的公開 GPU 型錄就是**三個 SKU**，全部建立在同一款加速器上——**每節點 2× Intel Data Center GPU Max 1100**——且全部在 **2024 年 2 月（含）之前**上線，**2.5 年來沒有任何 GPU 換代**。與此同時，第四個產品代碼 **`d3.g3.c2.medium`** 自 2025 年 4 月起就掛在他們自家產品系統中，沒有規格、沒有價格。

以下每一個價格皆於 **2026-08-11** 直接讀自 phoenixNAP 自家快取定價 API（[api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)）。**六個地區的定價分毫不差、完全相同**——PHX、ASH、NLD、SGP、CHI、SEA。

| SKU | 規格 | 每小時 | 1 個月 | 12 個月 | 24 個月 | 36 個月 |
|---|---|---|---|---|---|---|
| **`d3.g2.c1.xlarge`** | 2× Intel Data Center GPU Max 1100（各 56 Xe cores、48 GB HBM2E）＋ 雙 **Xeon Gold 6426**（2×16c @ 2.9 GHz，SGX）＋ 512 GB DDR5 ＋ 4× 2 TB NVMe ＋ 2× 25 Gbps | **$2.49/hr** | **$1,646.72/月** | **$998.26/月** | **$880.11/月** | **$808.21/月** |
| **`d3.g2.c2.xlarge`** | 2× Intel Data Center GPU Max 1100 ＋ 雙 **Xeon Gold 6436**（2×20c @ 2.7 GHz，SGX）＋ 512 GB DDR5 ＋ 4× 2 TB NVMe ＋ 2× 25 Gbps | **$2.60/hr** | **$1,726.02/月** | **$1,065.66/月** | **$947.52/月** | **$875.63/月** |
| **`d3.g2.c3.xlarge`** — **旗艦** | 2× Intel Data Center GPU Max 1100 ＋ 雙 **Xeon Gold 6442Y**（2×24c @ 2.6 GHz，SGX）＋ 512 GB DDR5 ＋ 4× 2 TB NVMe ＋ 2× 25 Gbps | **$2.67/hr** | **$1,778.49/月** | **$1,110.27/月** | **$992.12/月** | **$920.23/月** |
| **`d3.g3.c2.medium`** — **未發表** | **無伺服器產品紀錄。無硬體 metadata。未指名任何 GPU 型號。** 僅以 **$0** 關聯產品代碼形式出現在兩筆 Windows Server 2025 OS 授權列上（`WWBN-M6YV-QYJ6` srv2025dc、`CBHG-TCTK-B1QS` srv2025std） | **無價格** | **無價格** | **無價格** | **無價格** | **無價格** |
| **歷史品項——不在現行型錄中：** NVIDIA **Tesla V100** 與 **Tesla P40** 專用伺服器，**4 張或 8 張 V100 搭配 NVLink**，可完全客製，搭配 Intel Xeon Scalable | 發表於 **2018-10-01**，引述 Ian McClarty 與 William Bell | **未公布** — 客製報價之專用伺服器，從未列入隨選價目表 | — | — | — | — |

**內部 SKU 代碼，供客戶引述某一列品項時對照用**（PHX 地區）：`d3.g2.c1.xlarge` — 每小時 `PEL2-QH4Q-FP4T`、1 個月 `MAFO-FS6G-RD6R`、12 個月 `DDTM-SKBE-GCXN`、24 個月 `IHK0-HA8C-EVJL`、36 個月 `ETLK-RCB9-BIVM`。`d3.g2.c3.xlarge` — 每小時 `XDUF-XDER-93WU`、1 個月 `VUZM-7GJ8-L04C`、12 個月 `2TKW-XWSE-UJPC`、24 個月 `LLEK-TPQB-BPMZ`、36 個月 `ZUX8-LKYV-JKTL`。

**開會前該知道的可用地區矛盾：** 三個 GPU SKU 在**六個地區都已標價且可下單**，但 phoenixNAP 自家行銷頁仍寫著這些機種「currently available in Phoenix (AZ) and Ashburn (VA) only」。**價格型錄與行銷頁互相矛盾，而型錄才是有效來源。**

**判讀：** phoenixNAP 選定了一條**單一加速器的 GPU 路線**——Intel Data Center GPU Max 1100，每節點兩張，三個 SKU 構成一道 CPU 階梯，全球一價。這是一個連貫、有紀律的定位，而它已經**兩年半沒動**。線上型錄中**完全沒有 NVIDIA**、沒有 AMD Instinct、沒有 H100／H200／L40S——儘管第三方部落格聲稱有（第 6.1 節——不得複述）。而一個後繼世代 **g3**，已在內部掛了約**十六個月，既無規格也無價格**。這個組合——凍結的 GPU 產品線、卡在產品系統中的次世代代碼、加上一筆剛釋出資本的分割案——是本帳戶最清楚、且可標定日期的 AI 汰換切入口。

**不要猜 g3 的加速器。** 所觸及的任何來源都未指名任何 GPU 型號。**這是本檔中最有價值的單一未知**（第 15 節）。

---

## 8. 採購時鐘

以其自家公開型錄，回看三年間 phoenixNAP 實際多久買一次新矽晶。

### 8.1 快照時間軸

日期取自 `phoenixnap.com/bare-metal-cloud/instances` 的 Wayback 快照，該頁面內嵌完整產品型錄 JSON。

| 日期 | 型錄狀態 | 事件 | 快照／來源 |
|---|---|---|---|
| **2023-01-30、2023-05-08、2023-08-29、2023-12-14** | **42–48 KB 的純 JS 空殼，內嵌產品代碼為零** | **無資料——這是覆蓋率失敗，不是研究發現。** 這四份快照無法用來收斂任何時點 | Wayback CDX |
| **2024-02-27（含）之前** | **58 個產品代碼**，橫跨 a1／d1／d2／d3／s0／s1／s2／s3 | **三個 `d3.g2` Intel Max 1100 GPU SKU 已經上線。** 該快照中 GPU 價格渲染為 **$0.00**，因此 GPU 線已上線但**尚未公開標價**。**這是整份研究中觀察到的最後一次 GPU 採購事件** | Wayback 快照 `20240227211036` |
| **2023-12-14 至 2024-02-27 之間** | — | **無法再收斂。** 2023 年的快照全是純 JS 空殼（見第一列），因此真正的 GPU 採購日期只有上界 | Wayback CDX |
| **2025-01-14** | 型錄成長至 **71 個代碼** | **採購事件——`s4` 系列與 `s4.x6`（Intel Xeon 6 6731E，Sierra Forest）首次出現。** 由 [HPE 2025 年 4 月 DC-MHS Xeon 6 發布](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)佐證 | Wayback 快照 2025-01-14 |
| **2025-04-23**（頁面快取於 2025-04-22） | 型錄達到高點 **79 個代碼** | **`d3.g3.c2.medium` 首次出現——僅作為 OS 關聯項，無伺服器產品、無價格。** 這個停滯的 GPU 決策的時鐘從這裡開始跑 | Wayback 快照 `20250423054018` |
| **2025-11-09** | **新增 10 個 SKU** | **採購事件——整個 `s5.x6` 系列出現**（Xeon 6527P／6767P／6770P，Granite Rapids P-core） | Wayback 快照 2025-11-09 |
| **2026-01-17** | 無新系列 | **無採購事件。** 已驗證 `a2` AmpereOne **不存在** | Wayback 快照 2026-01-17 |
| **2026-01-17 至 2026-08-11 之間** | — | **採購事件——`a2.c9` AmpereOne A96-36X 系列出現**（`a2.c9.large`、`a2.c9.xlarge`）。在 2025-11-09 與 2026-01-17 **兩份**快照中皆不存在，於線上型錄中存在。**這是最近一次可標定日期的採購事件** | [線上型錄，2026-08-11](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) |
| **2026-08-11（線上基準）** | **101 個產品代碼** — 84 個具完整 metadata 的伺服器 SKU、3 個 GPU SKU，另加儲存／頻寬／OS／Netris 品項，橫跨 6 個地區 | **`d3.g3.c2.medium` 仍然存在、仍然無價、仍然無 metadata——已掛在待發狀態約 16 個月** | [api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) |

### 8.2 採購節奏

**CPU：** 新的伺服器 CPU 世代系列大約**每 9–12 個月**落地一次：

| 期間 | 系列 | 間隔 |
|---|---|---|
| 約 2024 Q4／2025 Q1 | Intel Xeon 6 E-core（Sierra Forest，`s4.x6`）— **由 HPE 供應** | 基準 |
| → 約 2025 Q3/Q4 | Intel Xeon 6 P-core（Granite Rapids，`s5.x6`） | 約 10 個月 |
| → 約 2026 上半年 | AmpereOne A96-36X（`a2.c9`） | 約 9 個月 |

**GPU：** 慢得多。整個 2024–2026 窗口中，**只有一個 GPU 世代**（g2／Intel Max 1100）曾被公開標價。**2.5 年以上沒有 GPU 換代**，而一個 g3 後繼世代已掛在待發狀態、未標價約 16 個月。

**最近一次事件：** **AmpereOne A96-36X**，發生於 2026-01-17 至 2026-08-11 之間。前一次 CPU 事件：`s5.x6` Granite Rapids，約 2025 年第四季。**最近一次 GPU 採購事件：g2／Intel Max 1100，2024 年 2 月（含）之前。**

### 8.3 下一個窗口

**估計：2026 下半年至 2027 上半年，而 GPU 決策是其中活的那一個。** 三個交會中的觸發條件：

1. **RadiusDC 交易於 2026 年第二季交割**，釋出資本，並以 phoenixNAP 自己的話說「sharpening focus」於保留下來的那約 80% 隨選基礎設施業務（[新聞稿](https://www.prnewswire.com/news-releases/phoenixnap-sharpens-focus-on-on-demand-infrastructure-with-strategic-transaction-for-phoenix-colocation-business-302716069.html)）。
2. **`d3.g3` 已掛了 16 個月，早該落地。** GPU 世代決策是**待決，不是假設**。
3. **CPU 節奏**依 AmpereOne 事件起算的 9–12 個月週期，把下一次系列汰換推到大約 **2026 Q4 – 2027 Q1**。

**反向因素，且是真實的：** **2026-05-18 的亞利桑那州稅務法院裁定**使其伺服器租賃收入**自此往後**須課 TPT——這是一個可能延後可裁量資本支出的新增毛利逆風（[TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)）。

### 8.4 方法——以及為何每個日期都是上界

以 Wayback CDX API 查詢（`url=phoenixnap.com/bare-metal-cloud/instances`、`from=2023`、`to=2026`、`collapse=timestamp:6`），取得 **32 份快照**。其中 15 份以 `id_` 原始內容旗標抓取，對每一個符合 `[adsn]N.family.size` 型態的產品代碼做正規表示式擷取，再逐對比較相鄰快照的系列集合差異。**十份快照**（`20230130`、`20230508`、`20230829`、`20231214`、`20240702`、`20241126`、`20250815`、`20260327`、`20260715`、`20260801`）**只擷取到 JS 空殼、無內嵌型錄，已排除。**

**必然的推論，如實陳述：上表中每一個「首次出現」日期，都是真實上線日期的「上界」；而上線日期又晚於採購／上架日期，因此它同時也是採購日期的上界。** 線上基準為 2026-08-11 取得之 phoenixNAP 自家快取定價 API JSON。

**信心水準：** 對「GPU 產品線自 2024 年 2 月（含）以來未曾換代」為**中高**（該窗口中五份資料完整的快照都顯示同樣的三個 g2 SKU）。對 `d3.g3` 的掛載日期及其持續存在為**中高**（頭尾兩端皆為直接觀察）。對 CPU 節奏為**中等**，因其建立在五份可用快照所得的三個間隔上。對 2023 年的任何推論為**低**——覆蓋率根本不足，**任何 2023 年的間隔都不得引用為事實**。

---

## 9. UCC 融資紀錄

**本軌研究範圍：** PHOENIX NAP, LLC（亞利桑那州本地 LLC，ACC 檔號 L15102933）——亞利桑那州鳳凰城。亞利桑那州為設立地，依 UCC §9-301／§9-307 即為正確的申報機關所在。

### 9.1 判定

> ### UNVERIFIED — portal blocked

**請完全照字面理解。** **未取得任何 UCC 申報紀錄。無法取得任何 filing number、filing date、lapse／continuation 狀態、secured party、debtor、collateral description、amendment、assignment 或 termination——因為亞利桑那州州務卿 UCC 入口從未送出過任何搜尋表單。**

由於表單從未載入，**從未有任何搜尋字串被送出**——本次查詢甚至沒有走到「輸入 debtor 名稱」那一步。

9.3 節之所以是空的，代表**什麼都沒看到**。這**不代表** phoenixNAP 沒有擔保債務。此結果不得對客戶陳述、不得引用給徵信單位，也不得以「查無留置權」寫入 CRM。**此處的阻擋是程序性的，不是資產負債表乾淨的證據。**

### 9.2 查詢紀錄——一次嘗試一列，不合併

全部執行於 **2026-08-11**，對象為設立地**亞利桑那州**。四次 curl 嘗試皆使用完整的桌面版 Chrome User-Agent 加上 `Accept` 與 `Accept-Language` 標頭。

| 入口 | URL | 使用之查詢字串 | 回應 | 受阻時之替代路徑 |
|---|---|---|---|---|
| 亞利桑那州州務卿 — UCC 應用根路徑 | [apps.azsos.gov/apps/ucc/](https://apps.azsos.gov/apps/ucc/) | **未送出任何字串** — 嘗試載入應用以觸及 debtor 搜尋欄位 | **HTTP 403，5,687 bytes。** Cloudflare 互動式挑戰；內文逐字為 `<title>Just a moment...</title> … Enable JavaScript and cookies to continue`。**該挑戰未被破解或繞過** | **以真人操作之瀏覽器工作階段開啟同一 URL — 成本 $0。** 此為反機器人閘門，非付費牆。否則走向 AZ SOS 申請認證 **UCC-11** |
| 亞利桑那州州務卿 — UCC 搜尋路徑 | [apps.azsos.gov/apps/ucc/search/](https://apps.azsos.gov/apps/ucc/search/) | **未送出任何字串** — 無表單渲染 | **HTTP 403，5,708 bytes。** 相同 Cloudflare 挑戰 | 同上 |
| 亞利桑那州州務卿 — UCC debtor 搜尋路徑 | [apps.azsos.gov/apps/ucc/search/debtor](https://apps.azsos.gov/apps/ucc/search/debtor) | **未送出任何字串** — 這正是本應接收 debtor 名稱的端點，而它從未渲染 | **HTTP 403，5,726 bytes。** 相同 Cloudflare 挑戰 | 同上 |
| 亞利桑那州州務卿 — UCC 說明頁 | [azsos.gov/business/uniform-commercial-code](https://azsos.gov/business/uniform-commercial-code) | 唯讀：定位權威搜尋 URL 與認證查詢途徑 | **HTTP 403，5,773 bytes。** 相同 Cloudflare 挑戰。**連說明頁都無法觸及，因此認證查詢的規費與作業時程也無法確立** | 真人瀏覽器工作階段；或直接致電 AZ SOS 商業部門 |
| 亞利桑那州州務卿 — WebFetch 嘗試 | [apps.azsos.gov/apps/ucc/search/](https://apps.azsos.gov/apps/ucc/search/) | **未送出任何字串** | **「The server returned HTTP 403 Forbidden.」** | 同上 |
| *（同一次作業中相關的登記機關阻擋，一併載明）* 亞利桑那州公司委員會 — 舊主機 | `ecorp.azcc.gov` | 查詢 PHOENIX NAP, LLC 之實體／幹部 | **DNS NXDOMAIN — 主機已無法解析。實測兩次** | 改用替代入口（見下一列） |
| 亞利桑那州公司委員會 — 替代 API | [api-azbusinessconnectonline.azcc.gov/api/businesssearch/advance-search](https://api-azbusinessconnectonline.azcc.gov/api/businesssearch/advance-search) | POST 查詢 PHOENIX NAP, LLC／檔號 L15102933；另 GET `/api/businesssearch/get` | **兩者皆回 HTTP 401 `{"detail":"Authentication Failed.","instance":"/api/businesssearch/advance-search"}`** | 於 `arizonabusinesscenter.azcc.gov` 以真人瀏覽器工作階段查詢 |
| OpenCorporates API | `api.opencorporates.com` | 直接公司查詢 `us_az/L15102933` 與 AZ 管轄搜尋 | **`{"error":{"message":"Invalid Api Token. Please check your OpenCorporates account"}}`** | 付費 OpenCorporates token，或改走上列州政府入口 |

### 9.3 已在案之申報——每筆完整列出

**取得之申報筆數：0。**

以下沒有申報明細區塊，因為**任何介面都不曾回傳過任何一筆申報**。此處沒有任何壓縮、簡寫或省略——**登記簿根本沒有被觸及**。因此，做出徵信或通路決策所需的每一個逐筆欄位，都是明確的 GAP：

| 所需之逐筆欄位 | `PHOENIX NAP, LLC` |
|---|---|
| Filing number（申報編號） | **GAP — 登記簿從未觸及** |
| Filing date（申報日） | **GAP — 登記簿從未觸及** |
| Lapse date／continuation 狀態 | **GAP — 登記簿從未觸及** |
| Secured party 名稱＋地址 | **GAP — 登記簿從未觸及** |
| Debtor 名稱＋申報時地址 | **GAP — 登記簿從未觸及** |
| Collateral description（擔保標的描述，逐字） | **GAP — 登記簿從未觸及** |
| Amendments／assignments／terminations | **GAP — 登記簿從未觸及** |
| 紀錄連結 | **GAP — 登記簿從未觸及** |

**重做查詢時「必須」逐一執行的 debtor 字串**——這不是選配，因為 UCC 搜尋邏輯以字串精確比對為基礎，只查一組字串等於在等一個偽陰性：

| # | Debtor 字串 | 理由 |
|---|---|---|
| 1 | `PHOENIX NAP, LLC` | 經 ACC 查核紀錄中的正式登記名稱 |
| 2 | `PHOENIX NAP LLC` | 無逗號變體；索引項目不同 |
| 3 | `PHOENIXNAP` | 其自家所有素材通篇使用的商業字號 |
| 4 | `SECURED SERVERS, LLC` | 被併購的子公司，**其商標至今仍由 Phoenix NAP LLC 持有**，其舊有 ASN AS11572（「SS-ATL」）也仍掛在 phoenixNAP 的 ARIN org 上 |
| 5 | `CWIE` | 關係人清查——位於 Tempe 2353 W University Drive 的集團 |

### 9.4 這份紀錄的意涵

**以下為推論，非目擊證據。** 每一列自行標示信心水準。

| 觀察 | 意涵 | 信心 | 對銷售的後果 |
|---|---|---|---|
| **亞利桑那州州務卿 UCC 入口對自動化存取完全不可觸及。** 四個 URL 變體全數 HTTP 403，卡在同一個 Cloudflare 挑戰；debtor 搜尋端點本身從未渲染。**正確的判讀是：phoenixNAP 的留置權狀態為「未知」，不是「乾淨」** | 不能由「查無結果」推出任何關於其擔保債務的結論。任何「phoenixNAP 沒有留置權」的陳述都**毫無根據** | **高** — 四次直接觀察，附位元組數 | **不得讓任何人以「查無 UCC 申報」為基礎，建立徵信或通路核准論述。** 在任何定價或融資對話**之前**，必須以真人瀏覽器工作階段或認證 UCC-11 完成此查詢 |
| **其他來源「能」確立的事實，已大幅收斂這個問題。** 亞利桑那州稅務法院紀錄以無爭執事實載明 IaaS 客戶使用的是「**PNAP-owned servers**」，且法院認定這些伺服器是 PNAP 出租的有形動產（[TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)） | **phoenixNAP 對機隊擁有所有權。** 它不是在轉售他人的硬體，也不是在跑客戶自帶設備的模式。這是任何結構的硬體交易的前提條件 | **高** — 法院紀錄 | **這是資格條件。** 它排除了此類帳戶最大的一項失格風險，且可在內部直接引用 |
| **三種融資假說仍然開放，且都與現有證據相容。**（a）**營運現金**——考量該集團與 CCBill／CWIE 支付事業的關聯，以及 phoenixNAP 於 2009 年以報導中的 $6.3M 全額購入 3402 E University Dr，此假說合理。（b）**供應商或 OEM 租賃額度**——phoenixNAP 自己就在銷售「hardware leasing」與 HaaS，而*一家把硬體租出去的公司，往往也把硬體融資進來*。（c）**ABL 或設備融資額度**，這會以銀行或 OEM 融資部門為 secured party 的 UCC-1 呈現 | 三者各自對應不同的銷售動作。（a）代表價格是唯一的槓桿。（b）代表已存在一條融資通路，必須把它找出來。（c）代表可能有一張總括留置權壓在擔保標的池上 | **中** — 硬體租賃產品為直接觀察；到融資結構的映射是商業推理，**不是目擊到的申報** | **實務上最關鍵的是 secured party 的「名稱」。** 一張以 **OEM 融資部門**（Supermicro、HPE 或 Dell 相關之融資機構）為 secured party 的 UCC-1，會立刻揭露既有的融資通路，**以及最近一次動撥的大致時點**——與第 8 節的採購時鐘交叉比對，即可標定 HPE Xeon 6 部署的融資時點 |
| **與稅務裁定的交叉關聯。** 自 2026 年中起，phoenixNAP 在亞利桑那的主機代管與 IaaS 伺服器租賃收入須負擔先前未曾繳交的州、郡與市 TPT | 對**恰好是用來償付設備債務、支撐 GPU 資本支出的那條收入線**，新增一筆數個百分點的永久性扣減 | **高** — 裁定為直接閱讀；毛利效果為算術 | 若確有融資存在，這會**壓縮「以機隊為擔保之收入」的償債覆蓋率**。本季應預期更硬的價格談判，以及對結構化條件更高的接受度 |
| **第二項關係人風險。** phoenixNAP 與 CWIE／CCBill 集團共用地址、共用法務聯絡人、至少共用一位 ARIN POC，且仍持有 SECURED SERVERS 商標與 SS-ATL ASN | **若確有融資，它可能掛在「持有硬體的那個實體」上。** 只查「PHOENIX NAP, LLC」有可能漏掉一張針對關係實體、卻壓在同一批實體機隊上的留置權 | **中** — 關聯性有登記資料佐證；**共同控制屬推論，未由所有權文件查證** | **請查 9.3 節全部五組 debtor 字串，不要只查一組。** 承擔擔保債務的那個實體才是真正的資產負債表——與它簽約，或要求它出具保證 |

### 9.5 GAP — Track 1，如實列出

- **UCC 是「未經查證」，不是「乾淨」。** 未取得任何亞利桑那州 UCC 申報。該入口對四個 URL 變體全數回傳 Cloudflare HTTP 403，curl（含完整瀏覽器標頭）與 WebFetch 皆然。**9.3 節之所以為空是因為什麼都沒看到——絕不可回報為「沒有融資」。**
- **從未有任何 debtor 名稱查詢真正送進亞利桑那州任何一套 UCC 系統。** 9.3 節所列字串是**必須執行**的字串，不是已執行的字串。**不得讀作已完成之搜尋。**
- **亞利桑那州的認證查詢規費與作業時程無法確立**，因為連 [azsos.gov/business/uniform-commercial-code](https://azsos.gov/business/uniform-commercial-code) 的說明頁都回 HTTP 403。編列預算前，請直接向亞利桑那州州務卿確認現行 UCC-11 規費與處理時間。
- **亞利桑那州公司委員會的實體紀錄同樣未取得**（舊主機 NXDOMAIN；替代 API HTTP 401），因此 **phoenixNAP 與任何 CWIE／CCBill 實體之間的幹部重疊，只能主張為「合理」，屬未經查證**。*（與 4.4 節所載為同一個硬性中止。）*
- **3402 E University Drive 於 2009 年以 $6.3M 購入之報導價格，未對馬里科帕郡登記處查核** — mcassessor.maricopa.gov 回傳 HTML 空殼而非 JSON，其 API 需要 token。地號、估定價值、產權移轉鏈與 RadiusDC 之登記移轉皆未經查證。

---

## 10. 成本天花板

一台旗艦 GPU 節點對 phoenixNAP 值多少錢，以及今天重建同一台機器要花多少錢。**標的：`d3.g2.c3.xlarge`。**

### 10.1 假設——請先讀這一段；這些是假設，不是查證發現

**以下只有一項輸入是他們的，其餘全部是本檔自訂的。**

**每節點的公開營收已查證**，取自 phoenixNAP 自家型錄（[api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)，2026-08-11）：**$2.67/hr · 1 個月 $1,778.49/月 · 12 個月 $1,110.27/月 · 24 個月 $992.12/月 · 36 個月 $920.23/月。** 由此往下：

- **假設 1 — 可持續營收率。** 假設 GPU 節點主要以 **12 至 36 個月保留方案**售出，而非以 1 個月牌價售出，得出可持續區間 **每月 $920–$1,110**。
- **假設 2 — 營運成本佔營收 40–55%。** 涵蓋每節點 600 W 以上的電力（兩張 300 W 加速卡加雙路 Sapphire Rapids）、冷卻、空間、網路、遠端協助、支援、管銷，以及自 2026 年 5 月起新增的**亞利桑那伺服器租賃 TPT**。**這是最吃重的單一假設，且背後沒有任何 phoenixNAP 的成本資料。** 據此得出每節點每月貢獻毛利 **$414–$666**。
- **假設 3 — 使用率高到足以讓保留營收連續發生。** **GPU 節點閒置會摧毀整個計算，而本檔沒有任何使用率資料。**
- **假設 4 — 回收期取 12／18／24 個月**，反映此規模的自營業者看待 GPU 折舊的方式。若改採 36 或 48 個月，天花板會按比例上升。
- **假設 5 — 不計入生命週期結束時的殘值。**
- **假設 6 — 亞利桑那 TPT 自 2026 年中起向後適用於伺服器租賃**，使淨營收下降數個百分點（[TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)）。

**以上皆非 phoenixNAP 揭露之數字。以下每一個天花板都是模型估計值，一旦離開本文件就必須如此標示。**

### 10.2 由租金推導之天花板

| 回收期 | 可回收之硬體成本 |
|---|---|
| **12 個月** | **$4,970 – $7,990** |
| **18 個月** | **$7,450 – $11,990** |
| **24 個月** | **$9,940 – $15,980** |

**推得之硬體成本天花板：最激進的讀法（36 個月費率、高營運成本、12 個月回收）約 $5,000，最寬鬆的讀法（12 個月費率、低營運成本、24 個月回收）約 $16,000，重心落在每台雙 GPU 節點 $8,000–$12,000。**

**敏感度：** 營運成本比率是主導槓桿。下行側現在還多了一個更硬的錨——2026-05-18 裁定使伺服器租賃自此往後須課州、郡與鳳凰城市 TPT，**這是直接打在同一條收入線上、數個百分點的新增扣減**，會進一步壓縮天花板。

### 10.3 街頭價物料清單（BOM）重建 — `d3.g2.c3.xlarge`

每一列均已分級。**兩列有依據，四列是本檔自訂的估計區間。**

| 元件 | 零件 | 街頭價 | 等級／來源 |
|---|---|---|---|
| **CPU（2 顆）** | **Intel Xeon Gold 6442Y** — Intel 建議客戶價每顆 **$2,878.00** | RCP 計為 **$5,756** · 合理量產 tray 價計為 **$4,000–$4,800**（每顆約 $2,000–2,400） | **硬價格點（RCP，非街頭價）。** RCP 經搜尋結果佐證取得——**intel.com 對直接抓取回 HTTP 403**。量產 tray 價會顯著更低 |
| **GPU（2 張）** | **Intel Data Center GPU Max 1100，48 GB** | **約 $4,798**（2 × $2,399） | **單一次級市場資料點——不是通路價。** **不存在任何公開的新品通路牌價**：Intel 訂購頁與 HPE Store（料號 S1T66C）皆為報價制，MegaGrid Supply 則要求 **$5,000 可退押金，只為鎖價 14 天**。唯一觀察到可成交的數字是次級市場上一張 **Dell 品牌 WG7J6 Max 1100 48 GB HBM2e 300 W PCIe x16，售價 $2,399** |
| **記憶體** | 512 GB DDR5-4800 RDIMM，以 16 × 32 GB 配置 | **$1,800 – $2,600** | **估計區間——本檔自訂，無來源** |
| **NVMe 儲存** | 4 × 2 TB 企業級 U.2 NVMe | **$700 – $1,100** | **估計區間——本檔自訂，無來源** |
| **網卡** | 雙埠 25GbE SIOM／OCP | **$300 – $500** | **估計區間——本檔自訂，無來源** |
| **機殼＋主機板＋電源** | 2U/4U 可裝 GPU 之機殼、主機板與冗餘電源，需能支撐 2 × 300 W 加速卡 | **$2,500 – $4,500** | **估計區間——本檔自訂，無來源** |
| **合計** | | **約 $14,100 – $18,300** | 視 CPU 以 RCP 或量產價計算而定 |

**與 Supermicro 的比較——如實陳述。** **本次未取得任何 Supermicro 報價，也不會憑空編造。** 誠實的比較是結構性的：一台 Supermicro 雙路 Sapphire Rapids GPU 平台，承載兩張雙寬 300 W PCIe Gen5 卡、16 條 DIMM 插槽填滿至 512 GB、4 × U.2 NVMe 與雙 25G SIOM，用的是**同一條 Intel 通路的同樣矽晶**，差異在機殼、散熱、整合與計畫價，而不在元件成本。

### 10.4 最吃重的結論

**由租金推導的天花板（$5K–$16K，重心 $8–12K）落在街頭價 BOM（$14.1K–$18.3K）之下或齊平。**

這兩個數字唯有在 **phoenixNAP 以顯著低於街頭價採購**時才對得上——而這正是 [2017 年 Supermicro 案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)所記載的事實：phoenixNAP **是透過 Supermicro** 參與 Intel 的 Early Deployment／Early Ship 計畫，因此其採購走的是**計畫經濟，不是牌價**。

**這就是這個帳戶的商業真相：價格是關卡，而既有供應商的結構性優勢是 Intel 計畫關係，不是金屬件。** 任何以機殼規格而非計畫價與 Intel 通路為主軸的訴求，都在講錯東西。而 2026 年的稅務裁定意味著本季這個天花板是**往下**移動，不是往上。

---

## 11. 客戶與網路

### 已具名客戶

以此類業者而言相當少見——phoenixNAP **公開了一份具名客戶索引**，[phoenixnap.com/customer-experience](https://phoenixnap.com/customer-experience) 上列有 24 個名字。**它沒有公開的，是任何一位具名個人與職稱。**

| 客戶 | 來源實際內容 | 相關性 |
|---|---|---|
| **TGen（Translational Genomics Research Institute）** | 列出**兩次**——一次為基因體研究擴充與 GDPR 合規，一次為 COVID-19 研究運算。位於鳳凰城的非營利基因體研究機構 | **名單中最具說服力的 AI／HPC 錨定客戶。** 基因體是 GPU／HPC 密集型工作負載，且與旗艦據點同城 |
| **UC Berkeley — 統計系** | 列為整合學生運算資源 | 真正的研究運算工作負載 |
| **SpyFu** | 明確列在 **AI 工作負載**項下 | **最明確的具名 AI 客戶** |
| **Namecheap** | 列為伺服器部署 | 大規模主機託管公司，成批採購 bare metal |
| **RTB House** | 列為歐洲擴張基礎設施 | 廣告科技即時競價——對延遲敏感、高流量運算 |
| **Authentic8** | 列為基礎設施成本削減 | 資安／瀏覽器隔離廠商 |
| **Ascent Aerospace** | 列為製造業資安營運 | — |
| **chuck-stack** | 公開被引述為以「AWS 或 Azure 四分之一的價格」建置混合雲，並將基礎設施成本降至 AWS 支出的四分之一或五分之一 | **可作為 phoenixNAP 價格定位的證據——而這反過來限制了他們能為硬體付出多少**（第 10 節） |
| **同一索引中的其他名單** | Kaligent（符合 HIPAA 的健康平台）、itpilot ApS、Glimpse（CI/CD 與代管私有雲）、My Party Album Inc.（自述較公有雲支出下降 80%）、Sagenext Infotech、ServerGenie.com、CMA Technology Solutions、FossHub、Ligris、Electric Mirror、NutPile Networks、ServerMiner、Sneaker Server、MCProHosting | 長尾主機託管、中小企業與垂直 SaaS |
| **Crown Castle** — *互連客戶，非運算客戶* | Crown Castle 在 phoenixNAP 鳳凰城資料中心**內部**設立 PoP | **與 RadiusDC 交易相關——互連平台正是被出售的資產之一**（[Lightwave](https://www.lightwaveonline.com/data-center/data-center-interconnectivity/article/14292834/crown-castle-establishes-pop-in-phoenixnaps-data-center-in-phoenix)） |

### 網路 — AS12189 與另外七個 ASN

- **登錄：** 主要營運 ASN **AS12189**（[PeeringDB net id 2932](https://www.peeringdb.com/api/net?asn=12189&depth=2)），名稱「PhoenixNAP」，IRR as-set **LEVEL3::AS-PHOENIXNAP**，紀錄建立 2010-02-17，最後更新 2026-03-25。ARIN org **PHOEN-56** 共持有 **八個 ASN**：AS11572（SS-ATL — Secured Servers 亞特蘭大的舊有資產）、AS12189、AS46385（PNAP-SE3）、AS53605、AS394643（AUS1）、AS397378（BRA）、AS400672（LA0）、AS401633（RDU0）。自營 rwhois 於 `rwhois://rwhois.phoenixnap.com:4321`
- **申報容量：** **500–1000 Gbps**、**Heavy Outbound** 流量比、**Global** 範圍、**1,000 個 IPv4 前綴與 100 個 IPv6 前綴**、peering 政策 **Selective**（PeeringDB）
- **公司宣稱：** 「**9+ Tbps 全球網路骨幹**」與每台伺服器內含 **20 Gbps DDoS 防護**（phoenixNAP 自家網路頁）。**視為行銷用語，非稽核值**
- **申報之 IX 埠總容量：640 Gbps**，橫跨 10 筆 PeeringDB `netixlan` — Equinix Ashburn 100G · AMS-IX 100G · DE-CIX Frankfurt 100G · SIX Seattle 100G · BIX.BG 100G · DE-CIX Phoenix 100G · Equinix Chicago 20G · Ninja-IX Phoenix 10G · Equinix Los Angeles 10G · Equinix Milan 10G
- **鳳凰城的電信商：** 行銷為 40 家以上，含 Cogent、Arelion、Lumen、TATA、GSL、NTT、DE-CIX、Telxius、Cox、Telstra 與 Global Layer，並**直連 AWS 與 Google Cloud**
- **設施：16 處**（自有／租用、有無運算的區分見第 5 節）
- **伺服器端網路標準——這是商業上最相關的一行：** **所有 BMC 伺服器 SKU 一律為 2× 25 Gbps 綁定**（較舊的 s0–s3 層級為 2× 1 Gbps 或 2× 10 Gbps）。**型錄中任何地方都沒有 100G 伺服器網卡**——這是任何 AI fabric 對話的相關缺口，也是一條正當的探詢主線
- **聯絡人：PeeringDB 未公開任何一位。** `poc_set` 為空，因此 peering 端接觸必須改走第 4.1 與第 13 節的 ARIN 代號

來源：[PeeringDB AS12189](https://www.peeringdb.com/api/net?asn=12189&depth=2) · [ARIN org PHOEN-56](https://whois.arin.net/rest/org/PHOEN-56/pocs)

---

## 12. 政治與公開紀錄

僅限公開紀錄。每一行皆已標記。**凡是查無者即如實寫明——一項「經執行並完成之查詢後確認不存在的 FEC 紀錄」是一項發現，不是空白。** 請特別注意以下使用的第三種狀態：**「未解決」**代表查詢已嘗試但工具失敗，**絕不可**回報為「查無紀錄」。

**重點：作為一個法人實體，phoenixNAP 唯一被找到的政治活動是鳳凰城市層級的市政遊說。完全沒有任何聯邦遊說登記，也找不到任何公司 PAC。** 在個人層級上，恰好只有**一筆** FEC 紀錄連結到具名的 phoenixNAP 在職者，而金額是 **$10.00**。

### 12.1 公開紀錄之政治獻金與申報

| 對象 | 事實 | 金額＋日期 | 受贈方 | 標記 | 來源 |
|---|---|---|---|---|---|
| **Danny Fuentes** — VP of Information Systems, phoenixNAP（FEC 申報之雇主：**CWIE**） | 經 **ActBlue 導管**路由、並指定給一場民主黨聯邦參議員選戰的逐筆個人獻金。捐款人登載為 **Mesa, AZ 85212**，職業 **「VP」**，雇主 **「CWIE」**。申報於 **Form 3X, line 11AI**。**這是本次調查中唯一能連結到具名 phoenixNAP 在職者的 FEC 紀錄**——而且請注意，一位現任 phoenixNAP 副總把雇主填成 **CWIE 集團實體**，這是來自聯邦紀錄（而非行銷素材）對集團結構異常乾淨的自我陳報式佐證 | **$10.00 — 2026-02-18** | **ACTBLUE**（C00401224），備註：*EARMARKED FOR TALARICO FOR TEXAS (C00919084)* | **public-record（公開紀錄）** | [FEC — fuentes danny, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=fuentes+danny&contributor_state=AZ) |
| **Cadwell, Rockridge** — 3492 E University Dr, Phoenix AZ 85034，職業 Self-Employed | 出現在亞利桑那州州務卿競選財務報表中的**州級**現金獻金。之所以記錄於此，**僅僅**是因為姓氏與 phoenixNAP 的經理人相同，且街道地址與旗艦設施同一街廓（**3492** 對 **3402** E University Dr）。**關鍵但書：查無任何證據可將此捐款人連結到 Ira Ronald Cadwell 或 Stephanie Cadwell。**「Rockridge」作為名字相當罕見，可能是申報方的資料輸入錯誤。**不得主張任何關聯** | **$520.51 — 2025-09-16** | **Kimberly Yee for Superintendent of Public Instruction**（亞利桑那州州務卿委員會 **#101898**），2025 年第 3 季報表，2025-10-15 送件 | **public-record** — 申報文件本身為一手資料；**但與 phoenixNAP 主事者之連結未經查證** | [亞利桑那州州務卿報表 PDF](https://seethemoney.az.gov/PublicReports/2026/41EA9853-D2EA-455F-8952-DC3A42066C35.pdf) |
| **Ira Ronald Cadwell** — 經理人、創辦人／執行長 | **查無紀錄——這是經確認的「不存在」，不是未執行的查詢。** 亞利桑那州 45 筆「Cadwell」FEC 紀錄已跨兩頁全數逐筆列舉：Sarah、Holli Cadwell Dunn、Jeremy、Colleen、Capri、Sara、Delores、Bess、Jon、Susan、Daphne 與 Thomas Cadwell。**沒有 Ira、Ron 或 Ronald。** 全國性查詢僅回傳 **RONALD G. CADWELL**（加州，雇主 Kindred Healthcare，2008–2010 之 PAC 薪資扣繳）與 **RONALD CADWELL**（華盛頓州，ActBlue，2019–2022）——**兩者皆非該亞利桑那經理人** | 不適用 | 不適用 | **public-record（經確認之不存在）** | [FEC — cadwell, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=cadwell&contributor_state=AZ) |
| **Stephanie Cadwell** — 經理人；CWIE Holding Company 之 Owner/Partner | **查無亞利桑那紀錄。** 全國有九筆「CADWELL, STEPHANIE」紀錄——**全部在加州、全部經 WinRed**，職業為 SELF 或 SELF-EMPLOYED，金額 $0.50 至 $70.00。這些**無法**歸屬於亞利桑那的登記經理人：州別不符、雇主欄從未出現 CWIE 或 phoenixNAP，且以 Chula Vista 市過濾（流傳中唯一的地址線索）回傳**零筆** | 加州紀錄橫跨 **2020-07-19 至 2021-03-01** | **WINRED**（僅加州紀錄——**未予歸屬**） | **unverified（無法查證）** | [FEC — cadwell 姓名查詢](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=cadwell+ira&contributor_name=cadwell+stephanie&contributor_name=cadwell+ron) |
| **Ian McClarty** — 總裁 | **查無紀錄——明確之否定結論。** FEC 個人捐款，捐款人姓名「mcclarty」，捐款人州別**亞利桑那**，全部年度：**零筆**。這是經確認的否定，不是未執行的查詢 | 不適用 | 不適用 | **public-record（經確認之不存在）** | [FEC — mcclarty, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=mcclarty&contributor_state=AZ) |
| **Marcus A. Bohn** — 登記代理人／Attorney of Record | **查無紀錄。** FEC 個人捐款，捐款人姓名「bohn marcus」，捐款人州別**亞利桑那**，全部年度：**零筆** | 不適用 | 不適用 | **public-record（經確認之不存在）** | [FEC — bohn marcus, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=bohn+marcus&contributor_name=carmody+robert&contributor_state=AZ) |
| **Robert Carmody** — ARIN 技術聯絡人 | **查無紀錄。** FEC 個人捐款，捐款人姓名「carmody robert」，捐款人州別**亞利桑那**，全部年度：**零筆** | 不適用 | 不適用 | **public-record（經確認之不存在）** | [FEC — carmody robert, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=bohn+marcus&contributor_name=carmody+robert&contributor_state=AZ) |
| **William (Bill) L. Bell** — EVP of Products | **未解決——且明確「不」記為查無紀錄。** 此姓名過於常見，無法在不加過濾的情況下查詢，而所有用以區辨其身分的雇主過濾 FEC 查詢**都在 FEC 資料介面上無限期卡住**，同時 openFEC API 全程對共用 DEMO_KEY **限流** | 不適用 | 不適用 | **gap** | [openFEC 端點](https://api.open.fec.gov/v1/schedules/schedule_a/) |
| **Brian Musgrave** — ARIN 技術聯絡人 | **未解決。** 全國性姓名查詢帶出數筆「MUSGRAVE, BRIAN」紀錄（WinRed 與 ActBlue），但**用以區辨亞利桑那本人所需的州別過濾在 FEC 介面上逾時**。這不是否定發現 | 不適用 | 不適用 | **gap** | [openFEC 端點](https://api.open.fec.gov/v1/schedules/schedule_a/) |
| **Cindy Anastasi／Harold Winey** — 出自資料商之高階主管 | **未解決** — 含「anastasi」與「winey」的亞利桑那合併查詢**在 FEC 介面上逾時**。另外，全國姓氏查詢中**不存在「FRANK EICKENHORST」的紀錄**，且**亞利桑那州完全沒有任何 Eickenhorst 紀錄** | 不適用 | 不適用 | **gap**（Eickenhorst：**經確認之不存在**） | [openFEC 端點](https://api.open.fec.gov/v1/schedules/schedule_a/) |
| **CWIE 集團員工之整體樣態** — *非主事者* | **403 筆 FEC 逐筆個人獻金**登載捐款人位於亞利桑那、雇主為 **「CWIE」**、**「CWIE HOLDING」** 或 **「CWIE HOLDING CO」**。樣態是**小額且跨黨**：大量重複的 ActBlue 捐款（例如 DANIEL J WELDON，約 $2–$5，重複至 2026 年 2 月）、Harris for President 捐款（EDWIN AVALOS，$25–$50，2024 年 9–10 月），以及 WinRed 捐款（ANTHONY PRUITT，$50，2025-07-23）。**這些人沒有一位是 phoenixNAP 主事者**，其數量反映的是一份大型集團薪資名冊，而不是協同一致的企業政治立場。**列為背景脈絡，不列為公司政治活動** | 紀錄至少橫跨 **2024-09 至 2026-02** | ACTBLUE · WINRED · HARRIS FOR PRESIDENT | **public-record（彙總；個人未連結至 phoenixNAP 幹部職位）** | [FEC — 雇主 CWIE, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=CWIE&contributor_state=AZ) |
| **phoenixNAP／CWIE／CCBill 之公司 PAC** | **未解決。** 已嘗試以「phoenixnap」「phoenix nap」「cwie」「ccbill」執行 FEC 委員會名稱查詢，但**FEC 委員會瀏覽器在反覆嘗試下始終未回傳結果**，且 openFEC 的委員會名稱端點**遭限流**。僅有間接訊號：在 **403 筆** CWIE 雇主獻金紀錄中，**觀察到的受贈方全部是導管（ActBlue、WinRed）或候選人委員會——沒有任何掛 CWIE 或 phoenixNAP 名稱的 PAC 出現在受贈方欄位。這暗示沒有公司 PAC，但未經證明** | 不適用 | 不適用 | **gap** | [FEC 委員會查詢](https://www.fec.gov/data/committees/?q=phoenixnap) |
| **Phoenix NAP, LLC**（*公司本身——法人層級*） | **現行有效之市政遊說客戶。** Phoenix NAP, LLC 出現在**鳳凰城市 Registered Lobbyist Clients** 名單的 **2025 曆年**（名單最後更新 2025-09-16）與 **2026 曆年**（名單最後更新 2026-07-13）。登記上的具名主事者為 **Marcus A. Bohn**，2353 West University Drive, Tempe AZ 85281，**MarcusB@cwie.net**。**這是該公司作為法人唯一被找到的政治活動——而且是市級，不是聯邦級** | **CY2025 與 CY2026** 之登記客戶 | 鳳凰城市遊說登記與申報計畫 | **public-record** | [鳳凰城市 2026 年登記客戶](https://lobbyist.phoenix.gov/PDF/RegisteredClients/2026) |
| **Phoenix NAP, LLC v. Arizona Department of Revenue**（*自前一版保留——州稅訴訟，非政治獻金*） | 亞利桑那州稅務法院 **TX2024-000075**，承審法官 Hon. Erik Thorson；起訴狀 2024-03-13 提出，就一件由鳳凰城市執行、亞利桑那州稅務局授權、查核期間 2016-10-01 至 2020-08-31 的 TPT 查核提起救濟。**核課總額 $4,549,556.05。** 裁定於 **2026-05-21** 歸檔：ADOR 在實體爭點勝訴——主機代管與伺服器租賃**確屬**應課 TPT——但 phoenixNAP 部分勝訴，法院認定該適用屬於「to a new or additional category or type of taxpayer」，違反 **A.R.S. §42-2078(B)**，故僅得**向後生效（PROSPECTIVELY ONLY）**。**商業上具實質意義：這是一項針對「支撐 GPU 採購的那條收入線」的永久性新稅負** | 裁定 **2026-05-21** 歸檔 | 亞利桑那州稅務局（對造） | **public-record** | [Minute entry PDF](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf) |

#### 受贈機構 — 沿革、政治傾向與負責人

上表中出現的每一個受贈機構，都獨立研究。**導管不是終點：** 捐給 ActBlue 或 WinRed，實質上是捐給被指定（earmarked）的候選人，而 FEC 的備註欄正是判斷對象的依據。

| 機構 | 類型 | 沿革 | 政治傾向（＋依據） | 負責人 | 負責人姓氏語源（onomastic） | 來源 |
|---|---|---|---|---|---|---|
| **[ActBlue](https://www.fec.gov/data/committee/C00401224/?tab=about-this-committee)**（FEC 委員會 **C00401224**） | **Hybrid PAC**，附設 non-contribution account；non-qualified、unauthorized。實際功能是民主黨與進步派候選人及議題的**付款導管**。登記於麻薩諸塞州，PO Box 962017, Boston MA 02196 | **2004 年**由 **Benjamin Rahn** 與 **Matt DeBergalis** 於麻州劍橋創立，最初為小額線上募款平台，其後成長為美國左翼最主要的募款導管。單就 **2025–2026** 這個兩年期，其申報總收入即達 **$1,925,847,484.38**，全數為逐筆個人獻金。Rahn 隨時間由總裁轉為執行董事與董事會成員等較被動的角色 | **民主黨／進步派——明示，非推論。** 其自述使命即為協助民主黨候選人與進步派組織進行小額募款，且平台僅接受民主黨及其盟友之委員會。本次調查中，導管功能是**直接可見的**：與 phoenixNAP 相關的那筆獻金經 ActBlue 通過，FEC 備註欄為 **「EARMARKED FOR TALARICO FOR TEXAS (C00919084)」**，即一場民主黨聯邦參議員選戰 | **登記司庫：GILMER, GEORGE**（依該委員會現行 Statement of Organization，FEC-1975230，2026-05-15 送件）。**總裁兼執行長：Regina Wallace-Jones**（2023 年就任）。**董事長／共同創辦人：Matt DeBergalis。** **共同創辦人：Benjamin Rahn** | **僅為姓名語源。** **GILMER**：源自蓋爾語 *Gille Moire*，意為「（聖母）瑪利亞的僕人」；另一種讀法為 *gille*（僕人）＋ *mor*（偉大）＝「great servant」；蘇格蘭與愛爾蘭源流，紀錄可溯至 1133–1156 年；全球約 10,503 人使用，以美國最多。**DEBERGALIS**：[forebears.io](https://forebears.io/surnames/debergalis) 明白記載「The meaning of this surname is not listed」，且未列出起源國；極為罕見，全球僅約 52 人，以美國最集中（紐約州 67%）。**WALLACE**（如 Wallace-Jones）：源自 *Le Waleis*，意為「威爾斯人」或「外來者」，依十二世紀特許狀更精確地指 Strathclyde 的不列顛人；出現於十二世紀的 Ayrshire 與 Renfrewshire；全球約 378,119 人使用 | [FEC C00401224](https://www.fec.gov/data/committee/C00401224/?tab=about-this-committee) · [forebears.io/gilmer](https://forebears.io/surnames/gilmer) · [forebears.io/debergalis](https://forebears.io/surnames/debergalis) · [forebears.io/wallace](https://forebears.io/surnames/wallace) |
| **[Talarico for Texas](https://www.fec.gov/data/committee/C00919084/?tab=about-this-committee)**（FEC 委員會 **C00919084**） | **聯邦參議員主要競選委員會（principal campaign committee）**——單一聯邦候選人之授權委員會。PO Box 14508, Austin TX 78761 | 於 **2025-09-09** 向 FEC 登記，支持 **James Talarico** 之德州聯邦參議員選舉。募款速度極快：2025–2026 週期至 2026-06-30 之總收入為 **$68,555,930.42**，其中 **$65,585,741.88** 為個人獻金、**$36,717,034.10** 為未逐筆申報部分——屬小額為主的結構。期末現金 **$21,548,155.08**，無負債。現行 Statement of Organization 為 FEC-1997955，2026-07-15 送件 | **民主黨。** FEC 自身的委員會紀錄載明授權候選人為 **TALARICO, JAMES**，德州聯邦參議員候選人，**民主黨**。這是主要競選委員會，因此依定義只資助一個人：它自己的候選人 | **授權候選人：James Talarico。** **司庫：LEE, LAUREN DECOT** | **僅為姓名語源。** **TALARICO**：[forebears.io](https://forebears.io/surnames/talarico) 記載「The meaning of this surname is not listed」；全球約 9,341 人使用，絕對人數以美國最多（賓州 20%、紐約州 15%、紐澤西州 10%），但相對於人口的**密度**則以義大利最高。**LEE**：古英語地名型姓氏，源自 *leah*，意為草地或草原，即「居於草地或牧地者」；凱爾特語讀法則有「灰色」或「醫者／放血師」之義；「Alan de Leia」約於 1177 年見證一份特許狀；全球第 232 常見姓氏，約 2,280,266 人使用，**同時也是許多彼此無關之東亞姓氏的常見羅馬拼音——這正好說明為何一個拼寫的語源，對任何個別使用者都不具任何推論意義** | [FEC C00919084](https://www.fec.gov/data/committee/C00919084/?tab=about-this-committee) · [forebears.io/talarico](https://forebears.io/surnames/talarico) · [forebears.io/lee](https://forebears.io/surnames/lee) |
| **[Kimberly Yee for Superintendent of Public Instruction](https://seethemoney.az.gov/PublicReports/2026/41EA9853-D2EA-455F-8952-DC3A42066C35.pdf)**（亞利桑那州州務卿委員會 **#101898**） | **亞利桑那州級候選人競選委員會**，管轄機關為亞利桑那州州務卿。PO Box 82071, Phoenix AZ 85071；(602) 456-9536；info@kimberlyyee.com | **Kimberly Yee** 參選 2026 年亞利桑那州公共教育廳長（Superintendent of Public Instruction）之候選人委員會。Yee 為現任**亞利桑那州財政廳長（State Treasurer）**，2018 年當選、2022 年連任，因任期限制不得再任該職。她於 **5 月 28 日**宣布參選廳長，並於 **2026 年 7 月的共和黨初選中擊敗現任 Tom Horne**，將於 11 月對上民主黨的 Teresa Leyba Ruiz。**2025 年第 3 季**報表（2025-10-15 送件，報表 ID 309517，涵蓋 2025-07-01 至 2025-09-30）顯示該季現金收入 **$42,951.52**，期末現金餘額 **$197,670.82** | **共和黨。** Yee 以共和黨籍擔任州級公職，並贏得 2026 年公共教育廳長之共和黨初選，且該委員會為**單一候選人委員會**，因此其全部資金都用於資助這位共和黨候選人。該委員會自身送件的報表即載明候選人與亞利桑那州州務卿之管轄 | **候選人：Yee, Kimberly。** **司庫：Childress, Phyllis**（PO Box 82071, Phoenix AZ 85071） | **僅為姓名語源。** **YEE**：[forebears.io](https://forebears.io/surnames/yee) 轉載之《Dictionary of American Family Names》（1956）釋為「(Chinese) First person singular pronoun, I」；全球約 189,056 人使用，以緬甸最多（98,397 人），其次為馬來西亞與美國。**CHILDRESS**：「(English) A variant of Childers」；另有使用者提交之語源將其溯自 Childerhouse 型地名，由古英語 *cildra*（child）＋ *hus*（house）組成；全球約 33,501 人使用，絕大多數在美國（德州 13%、維吉尼亞州 11%、田納西州 7%） | [亞利桑那州州務卿報表 PDF](https://seethemoney.az.gov/PublicReports/2026/41EA9853-D2EA-455F-8952-DC3A42066C35.pdf) · [Ballotpedia — Kimberly Yee](https://ballotpedia.org/Kimberly_Yee) · [forebears.io/yee](https://forebears.io/surnames/yee) · [forebears.io/childress](https://forebears.io/surnames/childress) |
| **[WinRed](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=CWIE&contributor_state=AZ)** | **共和黨陣營之線上募款導管**——ActBlue 在政治光譜右側的對應者 | **本次未深入研究**，列出僅為求完整，因為它在 CWIE 雇主的彙總 FEC 資料中以受贈方身分出現（例如 ANTHONY PRUITT，$50.00，2025-07-23），也出現在**未經歸屬**的加州「CADWELL, STEPHANIE」紀錄中。**沒有任何一筆流向 WinRed 的獻金能連結到具名的 phoenixNAP 主事者**，因此其創立沿革、負責人與司庫並未追查 | **共和黨。** 廣泛被認知、亦自述為共和黨小額募款導管；在本資料集中，其相關紀錄搭配的是共和黨委員會（例如 TRUMP NATIONAL COMMITTEE JFC、TEAM GRAHAM），而 ActBlue 紀錄搭配的則是民主黨委員會 | **GAP — 未研究**，因為沒有任何具名 phoenixNAP 主事者被連結到 WinRed 獻金 | **GAP — 未辨識出任何負責人，因此未查閱任何姓氏語源資料。並非杜撰** | [FEC — 雇主 CWIE, AZ](https://www.fec.gov/data/receipts/individual-contributions/?contributor_employer=CWIE&contributor_state=AZ) |

*姓氏語源僅為公開姓名學資料之語源考據，並非對任何個人族裔或血統之查證陳述。政治獻金為公開紀錄，不等於政黨登記。*

#### 遊說

| 登記人／客戶 | 議題 | 支出 | 來源 |
|---|---|---|---|
| **不存在任何聯邦 LDA 登記——一項乾淨、明確的否定結論。** 已直接以客戶名稱「phoenix nap」「phoenixnap」「cwie」「ccbill」「radiusdc」「IPI Partners」查詢參議院遊說揭露法（LDA）API。**每一次查詢皆回傳 `{"count":0,"results":[]}`。** phoenixNAP 及其關係企業**未出現在聯邦遊說登記系統的任何位置** | 不適用——無聯邦登記 | **聯邦 $0**（不存在任何申報） | [參議院 LDA API](https://lda.senate.gov/api/v1/filings/?client_name=phoenix%20nap) |
| **Phoenix NAP, LLC — 鳳凰城市登記遊說客戶（市政層級，非聯邦），CY2026。** 登記上之具名主事者：**Marcus A. Bohn**，2353 West University Drive, Tempe AZ 85281，**MarcusB@cwie.net** | Registered Clients 名冊 PDF **未逐項列出**議題明細。前幾年的 Annual Lobbyist Registration 申報（**2022 年度**，2023-01-17 送件；**2023 年度**，2023-07-24 送件）皆載明 Bohn 為 Phoenix NAP, LLC 之主事者。就其業務性質而言，市級資料中心事務——分區、公用事業、許可、University Drive 園區之開發協議——是顯而易見的可能主題，**但這是推論，不是申報文字** | **未揭露** — 名冊 PDF 只記載登記與最後更新日期，**不記載支出金額** | [鳳凰城市 2026 年登記客戶](https://lobbyist.phoenix.gov/PDF/RegisteredClients/2026)（名單更新 2026-07-13） |
| **Phoenix NAP, LLC — 鳳凰城市登記遊說客戶，CY2025** | 同一計畫、前一年度。**證明這段市政遊說關係具有延續性，不是一次性事件** | 名冊上**未揭露** | [鳳凰城市 2025 年登記客戶](https://lobbyist.phoenix.gov/PDF/RegisteredClients/2025)（名單更新 2025-09-16） |
| **OpenSecrets 機構檔案** | **未取得** — OpenSecrets 對自動化請求回傳 Cloudflare **HTTP 403**，與前一版一致。既然聯邦 LDA 申報已確認為**零**，OpenSecrets 的遊說檔案本來就應該是空的 | 不適用 | [opensecrets.org](https://www.opensecrets.org/) |

**評估。** 在政治軸線上，phoenixNAP 的足跡**規模不大、脈絡清晰，且幾乎完全是市政層級的**。**沒有聯邦遊說**、**找不到公司 PAC**，而且**創辦人兼經理人、總裁、登記代理人，以及兩位具名鳳凰城網路工程師其中一位，都完全沒有 FEC 紀錄**——這是四項獨立、且各自來自已執行並完成之查詢的確認性不存在。唯一確實存在的個人紀錄，是一位副總 **$10.00** 的導管獻金。CWIE 的薪資名冊顯示 403 筆小額紀錄分散於兩邊的導管，這是一個大型集團雇主應有的樣子，**而不是**企業的政治立場。**這些都不是切入點，也都不是風險。** 本節在商業上真正重要的是那件**亞利桑那州稅務法院裁定**，而它屬於定價簡報，不屬於關係經營簡報。

---

## 13. 公開聯絡管道

僅限公開來源。**本節不列任何個人行動電話與私人住址，且本次亦未尋找。** 以下每一項，皆由 phoenixNAP 自行登錄於登記機構，或由政府機關公布於公開申報文件中。無公開管道者標示為 GAP。

| 管道 | 內容 | 來源 |
|---|---|---|
| **公司／OrgAdmin 電話** | **+1-480-422-2022** — 列於 ARIN 的 Admin 與 Abuse POC 紀錄，3402 E. University Dr. Suite 420, Phoenix AZ 85034 | [ADMIN1723-ARIN](https://whois.arin.net/rest/poc/ADMIN1723-ARIN) |
| **IP 管理信箱——最近更新之 POC（2026-07-07），已確認活躍** | **ipadmin@phoenixnap.com** | [ADMIN1723-ARIN](https://whois.arin.net/rest/poc/ADMIN1723-ARIN) |
| **支援電話與信箱** | **+1-480-646-5362**／**support@phoenixnap.com** | [TECH357-ARIN](https://whois.arin.net/rest/poc/TECH357-ARIN) |
| **具名網路工程師 — Robert Carmody** | **robertca@phoenixnap.com** ｜ **+1-480-506-0120** ｜ 3402 E University Dr, Phoenix AZ | [CARMO67-ARIN](https://whois.arin.net/rest/poc/CARMO67-ARIN) |
| **具名網路工程師 — Brian Musgrave** | **brianmu@phoenixnap.com** ｜ **+1-480-401-0309** ｜ 3402 E University Dr, Phoenix AZ | [MUSGR48-ARIN](https://whois.arin.net/rest/poc/MUSGR48-ARIN) |
| **具名法務聯絡人 — Marcus A. Bohn** | **MarcusB@cwie.net** ｜ 2353 West University Drive, Tempe AZ 85281 | [鳳凰城市遊說登記](https://lobbyist.phoenix.gov/PDF/Registration/f9bc617c-1340-44ac-aa24-0e45f75a28fa) |
| **具名 EMEA 網路 — Adrian Montebello（馬爾他）** | **adrianm@phoenixnap.com** ｜ **+356 7930 5305** ｜ Phoenix Business Center, Penthouse Level, Triq il-Ferrovija, Santa Venera, Malta | [MONTE41-ARIN](https://whois.arin.net/rest/poc/MONTE41-ARIN) |
| **具名工程 — Milos Ilic（塞爾維亞）** | **milosi@phoenixnap.com** ｜ **+381 61 549 4754** ｜ Niš, Serbia | [ILICM-ARIN](https://whois.arin.net/rest/poc/ILICM-ARIN) |
| **具名工程 — Dragan Petrovic（登載於「CCBill EU」名下）** | **draganp@phoenixnap.com** ｜ 辦公室 **+356 77548965** ｜ 行動 **+381 62 1448366** ｜ Belgrade, Serbia | [PETRO182-ARIN](https://whois.arin.net/rest/poc/PETRO182-ARIN) |
| **Abuse** | **abuse@phoenixnap.com** ｜ +1-480-422-2022 | [ABUSE2349-ARIN](https://whois.arin.net/rest/poc/ABUSE2349-ARIN) |
| **線上產品型錄與定價——可用來追蹤哪些 GPU SKU 在動** | [phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) | phoenixNAP 自家快取定價 API |
| **具名客戶索引** | [phoenixnap.com/customer-experience](https://phoenixnap.com/customer-experience) | phoenixNAP |
| **高階主管管道 — Bell、McClarty、Cadwell** | **GAP — 三人皆無公開直接信箱。** 僅有 LinkedIn：[Bell](https://www.linkedin.com/in/williamb) · [McClarty](https://www.linkedin.com/in/mcclarty) · [Cadwell](https://www.linkedin.com/in/ron-cadwell-0b747313b/) | LinkedIn |
| **信箱命名型態——推論，未經查證** | 六筆 ARIN 紀錄中已確認的型態是 **名字＋姓氏前兩個字母**：robertca@、brianmu@、milosi@、adrianm@、draganp@。依此型態，**William Bell 應為 williamb@phoenixnap.com——此為推論，未經查證。不得視為已確認，也不得向推測出來的位址發冷信** | [ARIN org PHOEN-56 POC 清單](https://whois.arin.net/rest/org/PHOEN-56/pocs) |
| **業務直撥聯絡人** | **GAP — 未公布。** 僅有公司主線、支援專線，以及具名工程師的直撥號碼 | — |
| **PeeringDB peering 聯絡人** | **GAP — `poc_set` 為空。** peering 相關問題請改走上方 ARIN 代號 | [PeeringDB AS12189](https://www.peeringdb.com/api/net?asn=12189&depth=2) |

---

## 14. Supermicro 銷售切入點

### 分類：**既有客戶防守，且帶有急迫的被替換威脅**

**這不是全新開發案；任何把它當成全新開發案來談的人都會輸掉。** Supermicro 是有據可查的九年既有供應商：2017 年 6 月共同發表的案例研究**具名引述 Ian McClarty 與 William Bell**；已部署 BigTwin 2U 4 節點與 Simply Double 全快閃 SuperStorage；**Supermicro Rack Scale Design 與 Supermicro Server Manager 跨全部據點運行**；且早期 Intel 矽晶是**透過 Supermicro 的 Early Ship／Early Deployment 計畫**取得（[案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)）。ServeTheHome 更於 **2023 年 3 月**實機確認一台 Supermicro twin node 正作為 phoenixNAP 的 `d3.m6.xlarge` 運行（[拆解](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)），而 phoenixNAP 至今仍掛著 [/offers/supermicro-servers](https://phoenixnap.com/offers/supermicro-servers) 生態頁。

**但在 2025 年 4 月，HPE 宣布其首個 DC-MHS 解耦式硬體部署落在 phoenixNAP，搭載 Intel Xeon 6**——而 `s4.x6`（Xeon 6 6731E）SKU 正好在同一時間窗出現在 phoenixNAP 的型錄中（[HPE](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)）。**HPE 在一個 Supermicro 帳戶裡拿下了最新矽晶的旗子。這是帳戶團隊必須交代的一件事。**

### 三個切入點，依優先順序

**1. GPU 切入點——價值最高、時機最好。** phoenixNAP 全部的公開 GPU 型錄就是三個雙 Intel Data Center GPU Max 1100 的 SKU（`d3.g2.c1/c2/c3`），**全部在 2024 年 2 月（含）之前上線，2.5 年來沒有換代**。與此同時，後繼 SKU **`d3.g3.c2.medium`** 自 **2025 年 4 月**起就掛在他們自家產品系統中——僅以 **$0 的 Windows Server 2025 授權關聯項**形式可見，沒有硬體規格、沒有價格——而且**截至 2026 年 8 月 11 日仍然掛在那裡、仍未發表**。這是一個**原則上已決定、卻卡在矽晶選型或資本支出上的 GPU 平台決策**。誰幫他們把它結掉，誰就拿下這次汰換。

**2. 分割後切入點——時機的催化劑。** **2026 年 3 月 12 日**，RadiusDC（IPI Partners 平台，執行長 Mike Krza）同意收購 phoenixNAP 的鳳凰城資料中心與主機代管業務，2026 年第二季交割；phoenixNAP 轉為**承租方**，保留約 80% 的全球業務，**明確包含 Bare Metal Cloud 與網路**。McClarty：「*This transaction sharpens our focus.*」Bell：「*We are building platforms for customers who want dedicated and private infrastructure without friction.*」**他們剛把一門不動產生意換成一門運算生意，手上有現金——機隊如今就是整間公司。**

**3. 舊機汰換切入點——不華麗、但好拿的一單。** 他們在 **2026 年**仍在販售 `s0.d1.small`／`s0.d1.medium`，搭載 **Intel E3-1240v3／E3-1270v3 — Haswell、2013 年世代、16–32 GB、SATA SSD、2× 1 Gbps**。針對十二年舊鐵件的密度與電力 ROI 論述自己就會寫，而且**在他們成為向 RadiusDC 繳電費的新承租方之後，他們對每一瓦的在意程度會是自有時期所沒有的**。

### 首次接觸的唯一資格問題

對象為 **William Bell，EVP of Products**：

> **「你們的型錄裡從 2025 年 4 月起就掛著一個 `d3.g3` 的 GPU SKU，卻一直沒有標價——現在 RadiusDC 交割把你們變成承租方、也釋出了資本，這個 SKU 卡的是加速器選型，還是資本支出核准？交割後這個決策由誰負責？」**

這個問題證明你讀的是他們的**型錄**而不是官網，直接點名那個停滯的決策，並在一句話內逼出**預算歸屬**的答案。

### 商業現實檢核——第一次報價前務必讓團隊知道

- **其旗艦 GPU 節點由租金推導的成本天花板約 $8–12K，而街頭價 BOM 約 $14–18K（第 10 節）。他們付不起牌價。** 他們走的是 **Intel 計畫經濟**——這記載於 Supermicro 自家案例研究——因此**守住這個帳戶的路徑是 Intel 關係與計畫價，不是機殼規格。**
- **2026 年 5 月 18 日的亞利桑那州稅務法院裁定**使其伺服器租賃收入自此往後須課州、郡與鳳凰城市 TPT。**這是本季會讓他們在價格上更硬的新增毛利逆風，第一次報價前就該知道。**
- **技術切入口：** 型錄中每一個伺服器 SKU 的上限都是 **2× 25 Gbps 綁定——他們的機隊裡任何地方都沒有 100G 伺服器網卡**，這是任何多節點 AI 訓練論述的真實限制，也是與 Carmody 或 Musgrave 之間一條正當的探詢主線。
- **不要複述「L4 到 H100」的說法。** 第三方部落格如此宣稱；**phoenixNAP 自家型錄中的 NVIDIA SKU 為零**（第 6.1、7 節）。
- **不得就 GPU、Ampere、AMD 或 Xeon 6 P-core 節點陳述任何機殼供應商。** Supermicro 僅在 `d3.m6` twin node 與歷史的 BigTwin／SuperStorage 部署上獲得確認。其餘皆為 **GAP**，必須用問的，不能用講的。

### Rule 8 — 經銷通路注意事項（撥號前必讀）

**註冊「終端用戶」——Phoenix NAP, LLC，AZ ACC 檔號 L15102933，3402 E University Drive, Phoenix AZ 85034——除此之外什麼都不要註冊。** 本帳戶有四個具體陷阱：

**（a）** phoenixNAP 有透過通路交易（Insight 公開列有 phoenixNAP 合作夥伴頁），**因此可能有經銷商試圖登錄這個商機。被註冊的一方必須是終端用戶實體。**

**（b）** phoenixNAP 自己就在**銷售「hardware leasing」與 HaaS**，因此在 CRM 去重時可能被誤看成經銷商。**它不是**——亞利桑那州稅務法院已在紀錄上認定它**擁有**其出租的伺服器（[TX2024-000075](https://superiorcourt.maricopa.gov/media/yvoj0ksi/tx2024-000075.pdf)）。

**（c）不要讓這筆商機被登錄到 RadiusDC 或 IPI Partners 名下。** 2026 年第二季交割後，3402 E University Drive 會變成「**RadiusDC Phoenix I DC1**」，datacentermap 已經這樣標示了。**易主的是建物，不是運算採購方。** 註冊地址而非實體，會把這筆商機掛到錯誤的公司上。

**（d）註冊前先做關係人清查：** **Secured Servers, LLC**（2012 年被併購，商標至今仍由 Phoenix NAP LLC 持有，ASN **AS11572「SS-ATL」**仍掛在 phoenixNAP 的 ARIN org 上），以及位於 Tempe 2353 W University Drive 的 **CWIE／CCBill 集團**（Marcus Bohn 的 MarcusB@cwie.net 位址，以及公司欄位登載為「CCBill EU」、信箱卻是 @phoenixnap.com 的 ARIN POC Dragan Petrovic）——**這些都可能已經以獨立紀錄存在於 CRM 中。**

**警告——依上一段行動前務必先讀：** Rule 8 的字面條文**並不在**本檔的來源之列。上述內容套用的是**「註冊終端用戶、不註冊經銷商」**的一般原則。**送件前請對照實際條文查證。**

**順序——不得調換：** ① 執行關係人 CRM 清查並釐清通路／經銷商歸屬（Rule 8）→ ② 完成亞利桑那 UCC 查詢（第 9 節）→ ③ 註冊終端用戶實體（鳳凰城 AZ ＝ West Coast South excl. CA ＝ **T1｜T31**，一組自有轄區，可逕行註冊）→ ④ 以上述資格問題聯繫 **William Bell**，且只問這一題。

---

## 15. 查證附錄

### 15.1 單一來源支撐的說法（引用前須再驗證）

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| **PHX02／3221 E Elwood Street — 530,000 平方英尺、30 MW、2026 年第四季** | 一則 [DataCenterDynamics 文章](https://www.datacenterdynamics.com/en/news/phoenixnap-set-to-break-ground-on-second-data-center-in-phoenix-arizona/)的**搜尋結果摘要**，該文**對直接抓取回 HTTP 403** | **原文從未閱讀。** 未確認，且**可能與移轉給 RadiusDC 的「development rights for future campus expansion」重疊**——亦即它有可能根本不是 phoenixNAP 的獨立專案 |
| **HPE 在 phoenixNAP 的部署** | [2025 年 4 月 HPE 新聞稿](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)的**標題**，加上型錄佐證 | **新聞稿內文從未閱讀**——hpe.com 於 60 秒逾時且未重試。**部署規模、機型數量與是否有 phoenixNAP 高管引述皆為未讀。** *關係*已確認；*規模*未確認 |
| **3402 E University Drive 於 2009 年以約 $6.3M 購入** | 僅有新聞數字 | **未對馬里科帕郡登記處查核**（mcassessor.maricopa.gov 回 HTML，API 需 token） |
| **「9+ Tbps 全球網路骨幹」與每台伺服器內含 20 Gbps DDoS 防護** | phoenixNAP 自家網路頁 | **公司行銷宣稱，非稽核值。** PeeringDB 自行申報的數字是 500–1000 Gbps |
| **Marcus A. Bohn 的職稱「Chief Legal Officer」** | 資料商 | **並非出自申報文件。** *已申報*的事實是他為登記資料上的 care-of 當事人與具名遊說主事者 |
| **Ron Cadwell 的 CWIE 集團敘事（約 450 名員工、支付＋主機託管＋資料機房）** | [Crunchbase 個人頁](https://www.crunchbase.com/person/ron-cadwell)與自行發布之簡介文字 | **自行發布之簡介，非登記申報。** 其*職務*為高信心；集團敘事為中等 |
| **`d3.g2` GPU 節點是 Supermicro 機殼** | **本檔並未如此主張——且不得如此主張。** Supermicro 僅在 `d3.m6` twin node（拆解）與歷史的 BigTwin／SuperStorage 部署（案例研究）上獲得確認 | **GPU 節點的機殼供應商是 GAP。** 任何相反陳述都構成憑空杜撰 |
| **「phoenixNAP 提供 L4 到 H100」** | 第三方部落格（Cherry Servers、Ventus） | **被 phoenixNAP 自家型錄反證**，該型錄中 **NVIDIA SKU 為零**。**不得對客戶複述** |

### 15.2 第三方估計互相矛盾之處（呈現分歧，不擇一）

**員工數**

| 來源 | 數字 |
|---|---|
| Datanyze | **約 300** |
| ZoomInfo | **201–500** |
| Ampliz | **51–200** |
| Ron Cadwell 2017 年版簡介 | **約 450** — 但那是**更大的 CWIE／CCBill 集團，不是 phoenixNAP 單體** |
| phoenixNAP 自身之訴訟主張 | 於 2016-10 至 2020-08 期間有「**hundreds of employees and independent contractors**」操作其資料中心——訴訟攻防脈絡下的陳述，其法律主張已遭法院駁回 |

**未解決。** 三家資料商的模型橫跨 51–500 人，且皆無可見方法論。**任何引用皆須標示為「第三方估計」。**

**營收**

| 來源 | 數字 |
|---|---|
| Datanyze | **約 $25M** — 不可靠的資料商模型 |
| 由稅務紀錄推導（僅鳳凰城主機代管） | 2016–2020 年間**每年約 $23M**，由 $2,537,075.23 市 TPT ÷ 2.8% ÷ 47 個月推得 |
| 由稅務紀錄推導（僅 IaaS 伺服器租賃，**假設**州稅率 5.5%） | 2016–2020 年間**每年約 $5M** |
| 鳳凰城單一據點合計推導 | **2016–2020 年間每年約 $28M** |

**ESTIMATE — DERIVED（推導估計）。不得對客戶陳述為事實。** 州商業租賃的 $528,288.69 在 5.5% 稅率下**無法對回**同一稅基，可見分類與稅基確實不同。此推導真正確立的是：**流傳的 $25M 全公司數字，對一家六地區的全球業者而言幾乎可以確定偏低**，因為光是鳳凰城主機代管在 2019 年就可能已接近該數字。**CRM $100M 門檻：公開資料不支持——但請注意此推導只涵蓋鳳凰城，不涵蓋整個集團。**

**鳳凰城據點電力**

| 來源 | 數字 |
|---|---|
| 報導之機房數字 | **約 20 MW，並擴充至 25 MW** |
| [RadiusDC 新聞稿](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) | **DC1 擴充至 8 MW 總 IT 電力**；規劃 **DC2 達 18+ MW**（首批階段 2028 上半年）；園區最終約 **26 MW** |

**未解決——且請注意這兩個數字量的是不同的東西**（機房容量 vs 總 IT 電力）。**以「報導值」看待，不要視為已對帳。**

**GPU 地區可用性**

| 來源 | 說法 |
|---|---|
| phoenixNAP 行銷頁 | GPU「currently available in **Phoenix (AZ) and Ashburn (VA) only**」 |
| phoenixNAP 自家價格型錄 | 三個 GPU SKU 在**六個地區皆已標價且可下單** — PHX、ASH、NLD、SGP、CHI、SEA |

**型錄才是有效來源。** 行銷頁已過期。

### 15.3 未結 GAP

1. **UCC-1 融資申報——完全未解決，且是最高優先的缺口。** 亞利桑那州州務卿 UCC 入口對四個 URL 變體全數回傳 Cloudflare HTTP 403；**搜尋表單從未載入，因此未送出任何搜尋字串**，本檔中亦不存在任何 filing number、secured party、debtor、collateral description 或修訂歷程。**必須以真人瀏覽器工作階段或認證 UCC-11 申請重做。請查 9.3 節全部五組字串：** `PHOENIX NAP, LLC`、`PHOENIX NAP LLC`、`PHOENIXNAP`、`SECURED SERVERS, LLC`、`CWIE`。
2. **亞利桑那州公司委員會之幹部、經理人、股東、法定代理人與申報歷史——未取得。** `ecorp.azcc.gov` 兩次 NXDOMAIN；替代入口為 Angular 空殼，其 API 回 HTTP 401；OpenCorporates 因無 token 而拒絕。**ACC 檔號（L15102933）與設立日（2009-03-04）僅來自 GLEIF 經查核的 LEI 紀錄，不是來自申報文件本身。**
3. **所有具名主事者之 FEC 個人捐款——查詢被阻擋，未執行。** openFEC 對五個姓名於共用 DEMO_KEY 上全數回 OVER_RATE_LIMIT／HTTP 429（Retry-After 約 20 小時）；OpenSecrets 回 Cloudflare 403。**此結果明確「不是」查無紀錄。** 請以已註冊之 api.data.gov 金鑰，重跑 Cadwell（Ron／Ronald）、McClarty（Ian）、Bell（William）與 Bohn（Marcus）。
4. **`d3.g3.c2.medium` 背後的 GPU 型號——完全未知。** 它只以 $0 的 Windows 授權關聯項存在，沒有任何 metadata。**不要猜。這是本檔中最有價值的單一未知。**
5. **GPU 節點的機殼供應商——不明。** Supermicro 在 `d3.m6` twin node（實機拆解）與 BigTwin／SuperStorage（2017 案例研究）上已確認，但**沒有任何證據指出誰製造雙 Max 1100 的 `d3.g2` 節點，或 Ampere、AMD、Xeon 6 P-core 節點。**
6. **HPE 部署規模——未讀。** 2025 年 4 月 HPE 新聞稿內文從未閱讀（hpe.com 60 秒逾時，未重試）。**這一單已確認丟掉；節點數、機型與是否有 phoenixNAP 引述則未確認。**
7. **Dell 從未被評估。** 未執行針對 Dell 的專項檢索，也未出現任何附帶提及。**分級為 GAP，不是排除。**
8. **確切的伺服器與 GPU 節點數——任何地方都未揭露。** 可由 84 SKU × 6 地區把機隊下限框在數千台，但無法陳述具體數字，且**對 GPU 節點數完全沒有任何推估依據**。
9. **USPTO TSDR 商標聲明簽署人與代理人——未取得。** tmsearch.uspto.gov 對 POST 回 HTTP 405；assignment-api.uspto.gov 無回應（HTTP 000）；trademarks.justia.com 回 HTTP 403。僅由搜尋結果層級確立 Phoenix NAP LLC 持有 SECURED SERVERS（87396103）與 FLEXSERVERS（88517423），另有關聯之 HAAS 商標（85655621）。**無簽署人、無代理人、無註冊號、無狀態。**
10. **phoenixnap.com 之歷史 WHOIS——未取得。** whoisrequest.com 回 Cloudflare 403；whoxy.com 為登入牆；securitytrails 無金鑰無法觸及。僅有現行 Verisign RDAP 紀錄。**歷史登記人姓名、機構與信箱——正是能顯示該網域最初是否由 CWIE／CCBill 實體持有的關鍵資料——完全缺漏。**
11. **3402 E University Drive 與 3221 E Elwood Street 之馬里科帕郡估價／產權紀錄——未取得。** mcassessor.maricopa.gov 回傳 HTML 空殼而非 JSON，其 API 需要 token。**地號、估定價值、產權移轉鏈與 RadiusDC 之登記移轉皆未經查證。**
12. **PHX02 專案未經確認**，且可能與移轉給 RadiusDC 的開發權重疊（見 15.1）。
13. **具名之資料中心營運／採購招募主管——未識別。** 已確認鳳凰城有一則進行中的 Data Center Technician 職缺（時薪 $21–$30，2025-02-10 刊出），但**無主管姓名**。
14. **phoenixNAP 是否仍接受客製 NVIDIA 機種報價。** 2018 年的 Tesla V100／P40 專用伺服器產品線有發表紀錄，但**不在 2026 年型錄中**；第三方宣稱的「L4 到 H100」無法由任何 phoenixNAP 來源佐證，**不得對客戶複述**。
15. **BOM 六列中有四列是本檔自訂的估計區間**，不是有來源的報價（記憶體、NVMe、網卡、機殼——第 10.3 節）。只有 Xeon Gold 6442Y 的 RCP（$2,878，因 intel.com 回 403 而改由搜尋結果佐證取得）與**單一次級市場 Max 1100 觀察值**（$2,399，Dell WG7J6）有依據。**本次未取得任何 Supermicro 報價，也未憑空編造。**
16. **驅動租金推導天花板的營運成本比率（40–55%）完全是本檔的假設**，背後沒有任何 phoenixNAP 成本資料。**GPU 資源池的使用率同樣未知，且會實質改變答案。**
17. **LLC 層級以下之所有權結構。** CWIE／CCBill 關係佐證充分（共用 Tempe 地址、MarcusB@cwie.net、一位公司欄位寫著「CCBill EU」的 ARIN POC），但**查無任何確立母公司、控股公司或出資額之申報文件。** GLEIF 將直接母公司與最終母公司皆記為 reporting exceptions——**未申報任何母公司 LEI。**
18. **RadiusDC 交易是否真的完成交割。** 兩份新聞稿皆稱「expected to close in Q2 2026」，須經主管機關核准；**截至 2026-08-11 查無交割完成之確認。在會議中使用「承租方」框架之前，請先查證。**
19. **TX2024-000075 以外之法院案卷——未查詢。** 未執行 PACER 或聯邦案卷查詢。
20. **境外登記申報——未觸及。** 由登記於馬爾他（Santa Venera）與塞爾維亞（Niš、貝爾格勒）的員工可推知存在境外關聯機構，但未取得任何境外登記文件。
21. **重跑時的工具註記。** ZoomInfo MCP 連接器（以及 carta、figma、atlassian、spglobal、adobe 連接器）需要 OAuth 授權，本次非互動式工作階段中無法使用。**經 claude.ai 連接器設定授權 ZoomInfo，重跑時很可能可以補上員工數、營收估計與高階主管信箱的缺口。** 一組已註冊的 api.data.gov 金鑰可補上 FEC 缺口。一個真人瀏覽器工作階段可補上亞利桑那 UCC 與 ACC 缺口——這三個動作合起來，就能關掉本清單的大半。
