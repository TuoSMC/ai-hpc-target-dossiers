# Sharon AI, Inc. — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國）· 專員 US8664 Tuo Cheng · **日期：** 2026-08-11
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有持股，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之 GPU 型錄與定價、UCC 歸檔、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 德州休士頓 — Texas Area = **T1**｜T3。一組可直接註冊。
**CRM 狀態：** 2026-08-11 於 salesleads Search（Type = All）實查為乾淨 — 無 lead、無 account、無 do-not-call。一組可註冊。

---

> ### 對表頭與原始名單的四項更正 — 請先讀完這一段
>
> 上方表頭依原文照錄。**其中四項前提是錯的，且本次研究以一手證據反證。** 這裡採取明列更正而非默默改寫，以便從源頭修正工作名單。
>
> 1. **並非私有持股。** 本公司已於 **2025-12-19** 透過與 Roth CH Acquisition Co. 的 SPAC 合併上市，屬 SEC 申報公司：**CIK 0002068385**、Commission File 001-43129、**Nasdaq: SHAZ**（Class A 普通股）與 **SHAZW**（認股權證）。Form 10-Q、4.6 MB 的 Form S-1、DEF 14A 與多份 8-K 均存在且已完整閱讀。「預期無 SEC 申報」的前提為假，且這些申報文件是本檔中最豐富的證據，差距極大（[EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json)）。
> 2. **不在休士頓。** 登記在案的主要營業處所為 **745 Fifth Avenue, Suite 500, New York, NY 10151**。任何 SEC 申報、sharonai.com 或徵才頁面中，**皆無休士頓地址**。全網查到的唯一美國實體據點，是規模很小的**德州 Austin** 財會據點（[EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json)；[Form 8-K 2026-07-24](https://www.sec.gov/Archives/edgar/data/2068385/000149315226034569/form8-k.htm)）。
> 3. **德州資料中心已經賣掉了。** Texas Critical Data Centers LLC（TCDC）——原規劃位於 Ector County／Odessa 的 250 MW 表後（behind-the-meter）案場——已於 **2026-01-13** 出售給合資夥伴 New Era Energy & Digital（NUAI）。10-Q 載明公司「ceased to have an ownership interest in TCDC or participate in the joint venture」。**德州資料中心這條線已經不存在。** 這是最重要的一項更正（[Form 10-Q，截至 2026-06-30 之一季](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)）。
> 4. **這實務上不是 T1 美國硬體機會。** 10-Q 自述公司為「an Australian neocloud operator」。幾乎全部 GPU 基礎設施都在 **NEXTDC 的墨爾本與雪梨**，另加 GreenSquareDC（澳洲）與紐西蘭。採購主體、機隊、主機代管與決策者全在澳洲——由 **SharonAI Pty Ltd** 簽署 Lenovo 的 Statement of Work 與各高階主管聘僱合約。PeeringDB 上每一個 IXP、每一個機房都在澳洲，且**完全沒有 ARIN 組織紀錄**。T1｜T3 的轄區歸屬，**掛的是一家德拉瓦州的控股殼公司與紐約登記地址，不是一支會下單的機隊**。

---

## 1. 結論摘要

Sharon AI 是一家**在那斯達克掛牌（SHAZ）、實質上是澳洲 neocloud 業者、外面套著德拉瓦州公司殼**的公司；對本組而言，誠實的判斷是應該把它轉交 APAC／澳洲轄區承接，而不是登錄為德州 lead。可註冊的美國法人是 SharonAI Holdings Inc.，設立於德拉瓦州、主要營業處所在紐約 745 Fifth Avenue；真正買硬體的法人是 **SharonAI Pty Ltd**，Lenovo 的 SOW 與所有高階主管聘僱合約都由它簽署，而整支機隊落在 NEXTDC M3（墨爾本）與 NEXTDC S3（雪梨），加上 GreenSquareDC 雪梨與一處未揭露的紐西蘭設施（[Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)；[Form S-1，2026-07-31](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)）。帳面上的規模確實巨大——2026-06-12 簽訂的六年期 NVIDIA 合作案帶來 **約 40 億美元的採購承諾**、**最高 40,000 顆 Grace Blackwell GB300 GPU**、**2027 年中前規劃部署超過 62,000 顆 GPU**、AI Factory 容量約 **132 MW**（其中 116 MW 已與終端客戶簽約）——但**今天實際安裝的約只有 2,000 顆 GPU**，且上半年營收僅 **$2,225,396**，相對於已公告的 22.7 億美元合約總值。

商業上，這是一場**硬碰硬的既有廠商替換，不是新建案；而且有四方各自有商業誘因維持現有 OEM 組合**。運算平台上 Lenovo 已確認：公司自家公布的節點規格寫著「24 x 32GB **TruDDR5** 4800MHz RAM」——TruDDR5 是 Lenovo 專屬記憶體品牌名——且 10-Q 揭露對 Lenovo Global Financial Services (Australia & New Zealand) Pty Limited 有 **$33,094 千美元**的 Equipment-as-a-Service／Device-as-a-Service 預付款，另有一份 60 個月的受管基礎設施 Statement of Work，**約 50% 於期初支付**（[sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/)；[Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)）。**World Wide Technology（WWT Australia Pty Ltd）以整合商身分持有 $256,186 千美元——即 2.562 億美元——的設備預付款。** Cisco 則是結構性綁定，而不只是商業合作：與 Cisco 具獨家技術夥伴關係的 Digital Alpha Advisors 投資最高 US$200M 並成為股東，而旗艦 B300 叢集掛的招牌就是「Australia's first Cisco Secure AI Factory」。NVIDIA 則透過 NCP 資格、DSX 參考設計，以及分潤加信用支持的架構，實質掌控 OEM 短名單。

**Supermicro 在本案的證據等級是 `circumstantial（旁證）`，對內對外都不得升格。** 在 10-Q、DEF 14A、三份 8-K 與 4.6 MB 的 S-1 全文中，Supermicro **只出現過一次**，而且不是採購關係——它只是 NVIDIA Cloud Partner 資格所帶來的 OEM 名單之一：「OEM Relationships: Facilitated engagement with OEMs such as Cisco, Lenovo, Dell, and Super Micro to support server procurement and integration」（[Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)）。沒有採購單、沒有預付款、沒有承諾、沒有具名合約，任何一份已公布的節點規格中也沒有 Supermicro 硬體。**不要對內部任何人說 Supermicro 是這家公司的既有供應商。**

唯一真實的切入點是時機與集中度風險。一家把硬體當作融資服務在消耗、同時**對單一整合商預付 2.562 億美元**、背著約 40 億美元採購承諾、卻只有 **70 人**團隊的公司，其供應鏈與預付款風險高度集中，而這張資產負債表剛募到 9 億美元。全新的財務長 **Anuj Goel 於 2026-08-24 上任**——就在本次研究日期之後兩週——而這份風險會落到他手上。可信的訴求是**針對 2027 年 4 月至 8 月 NEXTDC 五階段上線的供應來源分散與交期確定性**，不是價格、也不是規格。另外依 Rule 8，本案不得以終端客戶名義註冊：硬體流經 WWT Australia（整合商）、Lenovo Global Financial Services ANZ（融資方）與 Dicker Data Limited（代理商），因此在任何註冊動作之前必須先釐清通路歸屬。

---

## 2. 公司速覽

| 欄位 | 內容 | 證據／日期 |
|---|---|---|
| **法人名稱（母公司）** | **SharonAI Holdings Inc.** — Nasdaq **SHAZ**／**SHAZW**。舊名：Roth CH Holdings, Inc.；SharonAI Holdings, Inc.。**屬 SEC 申報公司——表頭「私有持股」之前提為誤** | [EDGAR submissions API CIK 0002068385](https://data.sec.gov/submissions/CIK0002068385.json)。Commission File **001-43129**；IRS EIN **41-2349750**；SIC **7374**；emerging growth company |
| **美國子公司／保證人** | **SharonAI Inc.**（即原始名單所稱之「Sharon AI, Inc.」）、**SharonAI Operations LLC**、**SharonAI Hosting LLC**、**SAI US No. 1 LLC** — 全部為德拉瓦州法人。澳洲：**SharonAI Pty Ltd**、**Distributed Storage Solutions Pty Ltd** | [Form S-1，2026-07-31](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) 原文：「The initial Subsidiary Guarantors are: SharonAI Inc., a Delaware corporation; SharonAI Operations LLC, a Delaware limited liability company; SharonAI Hosting LLC, a Delaware limited liability company; SAI US No. 1 LLC, a Delaware limited liability company; SharonAI Pty Ltd…; and Distributed Storage Solutions Pty Ltd.」 |
| **設立州別** | **德拉瓦州（Delaware）** — 母公司與四家美國子公司皆是。`stateOfIncorporation=DE` | [EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json)。**GAP：** 未取得德拉瓦州登記機關的直接確認——icis.corp.delaware.gov 實體查詢為 CAPTCHA 阻擋（見第 8 節） |
| **登記總部** | **745 Fifth Avenue, Suite 500, New York, NY 10151, USA。** 申報人電話 **(347) 212-5075**；EDGAR 申報人電話 949-720-7133（Roth／Newport Beach 沿用之舊號）。**任何來源皆無德州休士頓地址** | [EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json)；[Form 8-K 2026-07-24 封面](https://www.sec.gov/Archives/edgar/data/2068385/000149315226034569/form8-k.htm) |
| **澳洲營運地址** | **303/44 Miller Street, North Sydney NSW 2060, Australia** · +61 2 8201 0063 | [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588) — 登記人 ORG-SA242-AP 與 IRT-DSSL-AU |
| **美國實體據點** | 僅 **德州 Austin**，且看來屬財會職能。徵才頁面有「Austin, Texas」與「Texas, US」地點篩選；LinkedIn 有一則 Sharon AI, Inc. 於 Austin, TX 的 Technical Accountant 職缺。**GAP：無街道地址、無辦公室規模、無美國員工人數** | [sharonai.com/careers/](https://sharonai.com/careers/) |
| **成立時間** | SharonAI Inc. 於 **2024-02-15** 在德拉瓦州設立。網域 sharonai.com 建立於 **2023-05-31**。與 Roth CH 的合併於 **2025-12-19** 完成（BCA 日期 2025-01-28） | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)；WHOIS sharonai.com |
| **所有權** | 自 2025-12-19 起為公開發行公司。**James Manning** 為 **持股逾 10% 之股東**。**Digital Alpha Advisors LLC** 投資最高 **US$200M** 並為股東，且與 Cisco 具獨家技術夥伴關係 | [DEF 14A 2026-07-13](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm)；[Digital Alpha 新聞稿](https://sharonai.com/press-releases/sharon-ai-accelerates-enterprise-ai-high-performance-compute-expansion-with-an-investment-from-digital-alpha-of-up-to-us200m-and-strategic-technology-partnership-with-cisco/) |
| **員工數** | 截至 **2026-07-30** 為 **70 人**（含員工、董事、顧問與承攬人員），分布於澳洲與美國。高階主管職能 7 人（9%）。**此為一手數字，非估計值** | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) |
| **營收** | **2026 年第二季：$1,931,381**，去年同期 $376,984。**截至 2026-06-30 之六個月：$2,225,396**，去年同期 $702,077。**單位為美元本位，不是千美元。** 六個月處分 TCDC 投資之利益為 **$65,920 千美元**，遠大於本業營收 | [Form 10-Q，截至 2026-06-30 之一季，2026-08-06 申報](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **已簽約之未來營收** | 與未具名之全球 AI lab 簽訂五年期 **US$1.32 bn** 雲端合約（2026-07-16；10-Q 另以後續事項揭露其中約 $373M）· 與未具名、在亞太具重要據點之全球科技公司簽訂 **約 $950M** 合約（2026-05-13）· NVIDIA 分潤 | [ex99-1，2026-07-16](https://www.sec.gov/Archives/edgar/data/0002068385/000149315226033457/ex99-1.htm)；[Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **CRM $100M 門檻** | **以承諾採購金額而言達標——但主體錯了。** 約 40 億美元 NVIDIA 承諾、約 $765.1M 近期硬體採購承諾、約 $217.2M 的 2,048 顆 B300。**採購主體是澳洲的 SharonAI Pty Ltd，因此以 T1 美國名義註冊會造成轄區錯置，而且是一個美國團隊既服務不到、也成交不了的機會** | [Form 10-Q 承諾事項附註](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **ASN** | **AS142588** — as-name **DSSL-AS-AP**、descr「Sharon AI」、國別 **AU**、org ORG-SA242-AP。登記於 **APNIC，非 ARIN**。最後異動 2024-11-25 | [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588)；[PeeringDB net 37929](https://www.peeringdb.com/api/net?org_id=39812&depth=2) |
| **ARIN 紀錄** | **完全沒有。** 以 `Sharon*` 於 ARIN 查詢組織名稱，僅回傳不相關實體。**「Sharon Networks, LLC」（AS396856、sharon.io、Wilmington DE）是另一家完全無關的公司——不得與本標的混淆** | [whois.arin.net orgs name=Sharon*](https://whois.arin.net/rest/orgs;name=Sharon*) |
| **轄區／團隊** | 表頭記為德州休士頓 → Texas Area = **T1｜T3**。**但實際採購發生在澳洲** — 見上方更正段落與第 13 節 | Territory Map-Jan.2026 (Rev.1)，Sales Territory Assign 分頁 |

---

## 3. 領導層與所有權

本節證據等級：**primary-record（一手紀錄）**＝SEC 申報文件、網路號碼登錄機構、法院案卷、競選財務申報，或公司自家已發布頁面｜**corroborated（多方佐證）**＝兩個以上獨立來源互相印證｜**single-source（單一來源）**＝僅一個來源｜**GAP**＝已具名搜尋但查無。

進入表格前有兩項前提。第一，與典型私人業者不同，**這家公司的領導層是完整且正式揭露的**——2026-07-13 申報的 DEF 14A 載有完整的經理人與董事名冊，含年齡與完整經歷。這是很大的優勢，也是下方具名人員表格異常豐富的原因。第二，**登記機構幹部與網路聯絡人以獨立列呈現並明確標示**——但在本案中，這產生了一項必須明講的負面發現：**本公司在 APNIC 與 PeeringDB 上的每一個聯絡人都是角色帳號，不是自然人。** 公開登記資料中完全沒有具名的 NOC 或網路人員。這是真實的「不存在」，而不是研究失敗。

### 3.1 具名人員

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC 紀錄 | 來源 |
|---|---|---|---|---|---|---|
| **James Manning** | **Chief Executive Officer 兼董事**（2026-01-22 起任 CEO）；**共同創辦人**；至 2026-05-21 為董事長；**持股逾 10% 之股東**。年齡 40 | **經濟決策者／最終核准人** | **primary-record** | 未公開個人 email 或電話。經 **745 Fifth Avenue, Suite 500, New York, NY 10151** ／ **(347) 212-5075** 進入 | **UNVERIFIED — API 額度受限。** OpenFEC 以 DEMO_KEY 每次嘗試皆回傳 `OVER_RATE_LIMIT`。**不得記為「查無紀錄」。** 僅作法律脈絡註記：他常居澳洲，而非美國永久居民之外國人依 52 U.S.C. 30121 禁止對美國選舉捐輸，故查無為預期結果——**但本次並未查證** | [DEF 14A 2026-07-13](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm)；以 CEO 身分簽署 8-K — [Form 8-K 2026-06-25](https://www.sec.gov/Archives/edgar/data/2068385/000149315226030158/form8-k.htm) |
| **Daniel Mons** | **Chief Technology Officer（技術長）**（2025-05-17 起）。年齡 45。**受僱於 SharonAI Pty Ltd（澳洲法人）** | **技術決策者／伺服器平台守門人——任何硬體動作最重要的單一技術窗口** | **primary-record** | 未公開個人聯絡方式。最接近的公開技術管道為角色信箱 **networking@sharonai.com** | **UNVERIFIED — API 額度受限。** 常居澳洲；預期為查無，但未經查證 | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Andrew Leece** | **Chief Operating Officer（營運長）**（2024-02-15 起）。年齡 40。受僱於 SharonAI Pty Ltd | 部署／營運決策者 | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — API 額度受限** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Anuj Goel** | **候任財務長 — 2026-08-24 到職。** 年齡 42，逾 20 年資歷 | **新任財務核准人——一扇「新財務長重審成本與供應商」的窗口在此開啟** | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — API 額度受限** | [Form 8-K Item 5.02，2026-07-24 申報](https://www.sec.gov/Archives/edgar/data/2068385/000149315226034569/form8-k.htm) |
| **Timothy (Tim) Broadfoot** | **Chief Financial Officer、Treasurer、Corporate Secretary — 已請辭，2026-08-24 生效**（僱傭關係至 2026-08-31 終止）。年齡 34 | **即將離任——不要在此投入關係經營** | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — API 額度受限** | [Form 8-K Item 5.02，2026-07-24](https://www.sec.gov/Archives/edgar/data/2068385/000149315226034569/form8-k.htm) |
| **Nicholas Hughes-Jones** | **Head of Corporate Development**（2026 年 1 月回任）；2024-02-15 至 2025 年 5 月曾任 SVP Business Development | 交易架構／合作案影響者 | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — API 額度受限** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Tim Flahvin** | **General Counsel（法務長）**（2026 年 1 月起）兼 **Company Secretary** | 合約／MSA 之法務守門人 | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — API 額度受限** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Andrew Penn AO** | **董事兼董事長**（2026 年 5 月起任董事；**2026-05-21** 起任董事長）。年齡 63 | 董事會監督／策略贊助者 | **primary-record** | **GAP** — 未公開 | **屬外國公部門連結，已由 DEF 14A 查證——不是美國政治紀錄。** 曾主持澳洲 2020 與 2023 年 National Cyber Security Strategies 之專家諮詢委員會；2023 年獲頒 Officer of the Order of Australia (AO)；現任 Visit Victoria 主席 | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Peter Woodward** | **董事**（自合併案完成起） | **美國本地董事——最有價值的美方引薦路徑，且是真正懂資料中心整合的內行人** | **primary-record** | **GAP** — 未公開。原則上可經 **MHW Capital Management LLC** 或 **TSS, Inc.** 投資人關係接觸 | **UNVERIFIED — 優先追查。** 常居美國，因此存在真實紀錄的可能性較高。他是 MHW Capital Management LLC 創辦人，且曾任白宮 Council of Economic Advisors 經濟學家——此背景提高政治捐輸的先驗機率。**需申請正式 FEC API key 並人工重跑** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Alexander Andrew Kelton** | **董事**（**2026-01-12** 起）；**Audit and Risk Management Committee** 委員 | 技術／基礎設施面之董事會影響者 | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — API 額度受限** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Alastair Cairns** | **董事**（自合併案完成起；自 2024 年 9 月起任 SharonAI Inc. 董事）；**Audit and Risk Management Committee** 委員 | 董事會監督 | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — API 額度受限** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Benjamin Adams** | **董事**（**2026-02-22** 起）。現任 **The Western Union Company (NYSE: WU)** 之 EVP、Chief Legal Officer 兼 Corporate Secretary。**常居美國** | 董事會監督／公司治理 | **primary-record** | **GAP** — 未公開 | **UNVERIFIED — 優先追查。** 常居美國，且其職務常涉企業 PAC 事務。**值得以正式 API key 人工重跑** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Michael Schubert** | **前任 Chief Executive Officer — 2026-01-22 請辭** | **僅供歷史參考——不得視為決策者接觸** | **single-source／部分** — 姓氏與職務已由 DEF 14A 確認；**本次未逐字取得其名（given name）**，所讀章節僅出現「Mr. Schubert」 | N/A | 未檢索——已無相關性 | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **ORG-SA242-AP —「Sharon AI」** — *網路登記列* | AS142588 之 **APNIC 登記人**；地址 303/44 Miller Street、電話 **+61 2 8201 0063**、email **networking@sharonai.com** | **網路登記聯絡人（APNIC）— 組織紀錄，未具名任何自然人（GAP）** | **primary-record** | networking@sharonai.com · +61 2 8201 0063 | 不適用 | [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588) |
| **SS4419-AP —「SharonAI Support」** — *網路登記列* | AS142588 之 **admin-c**；`kind=group`；澳洲雪梨；**support@sharonai.com**；電話 +000000000 | **網路登記聯絡人（APNIC）— 角色帳號，非具名自然人（GAP）** | **primary-record** | support@sharonai.com | 不適用 | [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588) |
| **SNA102-AP —「SharonAI Network Administrator」** — *網路登記列* | AS142588 之 **tech-c**；`kind=group`；澳洲雪梨；**networking@sharonai.com** | **網路登記聯絡人（APNIC）— 角色帳號，非具名自然人（GAP）** | **primary-record** | networking@sharonai.com | 不適用 | [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588) |
| **IRT-DSSL-AU／AD1404-AP** — *網路登記列* | **事故應變小組／濫用檢舉聯絡窗口**；303/44 Miller Street, North Sydney NSW 2060；support@sharonai.com；**abuse@sharonai.com**（**2026-06-09** 完成驗證） | **網路登記聯絡人（APNIC）— 角色帳號（GAP）** | **primary-record** | abuse@sharonai.com | 不適用 | [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588) |
| **MAINT-DSSL-AU**（mnt-routes、mnt-lower）與 **APNIC-HM**（mnt-by） | AS142588 之 **route object 維護者** | **網路登記維護者 — 未具名任何自然人（GAP）** | **primary-record** | — | 不適用 | whois.apnic.net AS142588 |
| **PeeringDB 聯絡人** | — | **網路聯絡人（PeeringDB）— 完全未公開（GAP）。** net id 37929 之 `poc_set` 為**空**；不存在具名 NOC 人員 | **primary-record**（該集合為空一事） | — | 不適用 | [PeeringDB net 37929](https://www.peeringdb.com/api/net?org_id=39812&depth=2) |
| **ARIN 聯絡人** | — | **不存在 ARIN 組織紀錄。** 以 `Sharon*` 查詢僅回傳不相關實體：sharon burns、SHARON C BRANNAN CPA、Sharon Ehrig Inc、SHARON LIM DBA KIYO、**Sharon Networks LLC**、Sharon Public Library、SHARON RICHARDSON CPA、Sharon Saving Bank、Sharon Telephone Company、Sharon Towers | **primary-record**（負面發現） | — | 不適用 | [whois.arin.net orgs name=Sharon*](https://whois.arin.net/rest/orgs;name=Sharon*) |

**刻意記錄之排除項：** 任何以「Sharon」為關鍵字的網路查詢，都會出現 **Sharon Networks, LLC**（AS396856、sharon.io、Wilmington DE）與 **Sharon Telephone Company**（AS398915）。**兩者皆為完全無關之公司**，本檔刻意排除。若誤採其一，等於在本檔中塞進一個不屬於本標的的美國註冊 ASN。

### 3.2 登記紀錄

請注意界線：以下各列為 **SEC 申報文件與網路號碼登錄機構（APNIC、PeeringDB）**。**未能取得任何公司登記機關紀錄**——德拉瓦州 Division of Corporations 的實體查詢為 CAPTCHA 阻擋，因此註冊代理人、設立人與年報簽署人皆未經查證（見第 8 節與 3.4）。

| 姓名 | 身分 | 申報文件 | 申報日期 | 來源 |
|---|---|---|---|---|
| **James Manning** | **CEO — SEC 即時報告之簽署人。** 簽名欄原文：「By: /s/ James Manning, Name: James Manning, Title: CEO」 | **Form 8-K**（Items 1.01／2.03／3.02／9.01），報告 **$900M 股權發行** 與 **4.75% 可轉換公司債** | **2026-06-25**（事件日 2026-06-22） | [Form 8-K](https://www.sec.gov/Archives/edgar/data/2068385/000149315226030158/form8-k.htm) |
| **Andrew Penn；James Manning；Alastair Cairns；Peter Woodward；Alexander Andrew Kelton；Benjamin Adams** | **董事**（待選任／現任）。**Audit and Risk Management Committee** 委員載明為 **Alastair Cairns** 與 **Alexander Andrew Kelton** | **DEF 14A** 正式委託書 — 經理人與董事名冊 | **2026-07-13** | [DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) |
| **Anuj Goel**（獲聘 CFO）；**Timothy Broadfoot**（請辭 CFO） | 經理人任免 | **Form 8-K** Items 1.01、1.02、5.02、7.01、9.01 — 聘僱合約、Separation Deed（Deed of Release）、顧問合約、主管契約終止 | **2026-07-24**（事件日 2026-07-22） | [Form 8-K](https://www.sec.gov/Archives/edgar/data/2068385/000149315226034569/form8-k.htm) |
| **ORG-SA242-AP「Sharon AI」；SS4419-AP；SNA102-AP；IRT-DSSL-AU／AD1404-AP；MAINT-DSSL-AU** | **AS142588** 之 APNIC 登記人、admin-c、tech-c、abuse-c 與維護者。**全為組織或角色紀錄，未具名任何自然人** | APNIC aut-num 物件 AS142588，as-name **DSSL-AS-AP** | 最後異動 **2024-11-25**；濫用檢舉聯絡窗口於 **2026-06-09** 完成驗證 | [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588) |
| **未取得 — 德拉瓦州註冊代理人、設立人與年報簽署人** | 德拉瓦州公司登記幹部 | **德拉瓦州 Division of Corporations 實體查詢未完成** — 名稱查詢頁為 CAPTCHA 阻擋（回傳 HTML 中偵測到 2 處 captcha 標記），UCC 查詢路徑回傳 HTTP 404 | **不適用 — 2026-08-11 嘗試** | [icis.corp.delaware.gov EntitySearch](https://icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx) |

### 3.3 採購決策圈

在本研究系列中相當罕見的是，**這個採購決策圈是從委託書具名取得，而不是推論出來的**。不利之處在於這些人在哪裡：技術長、營運長、執行長與候任財務長，全都透過澳洲法人 **SharonAI Pty Ltd** 聘僱，合約也將適用澳洲法。

| 姓名 | 為何在伺服器採購上重要 | 接觸方式 |
|---|---|---|
| **Daniel Mons — 技術長** | **伺服器平台的守門人。** 逾 20 年高效能運算資歷，橫跨基礎設施設計、系統架構、資訊安全與叢集管理——曾任職於 Queensland State Government Department of Environment, Science, Energy and Innovation（「ASDI」）、Cutting Edge、Eyecon 與 Sunsuper，實際建置與管理 HPC 環境；University of Queensland 資訊科學學士。他就是那個會拿節點設計去對照 NVIDIA 參考架構的人。**任何 Supermicro 的對話，成敗都在這裡** | **以參考架構符合度、散熱與可維護性工程開場，不要談價格。** 他親手跑過叢集，所以要帶 NVIDIA 認證系統清單、支援 GB300 級密度的液冷選項，以及誠實的故障／RMA 數據。**不要以折扣開場。** 目前唯一公開管道：**networking@sharonai.com** |
| **James Manning — 執行長、董事、持股逾 10%** | **經濟決策者，也是簽名的人。** 背景極具相關性：他在 2023 年 5 月前創辦並經營 **Mawson Infrastructure Group Inc. (Nasdaq: MIGI)** ——一家數位基礎設施平台開發與營運商，代表他**親自蓋過美澳兩地的資料中心容量，不需要從零被教育伺服器廠商**。另自 2014 年 6 月起任 Vertua Limited 董事總經理、2015 年 9 月起任 Defender Asset Management Pty Ltd 董事長；經 Manning Group Pty Ltd ATF MG Office Trust 提供服務，年費 AUD$334,500。他手上握著約 40 億美元的採購承諾 | **以高階、資本效率為框架。** 他公開的策略是透過 NVIDIA 分潤模式走「capital-efficient path to scale」——所以訴求是**每顆已部署 GPU 的到岸成本，以及對硬性 RFS 日期的交期確定性**，不是功能規格。**一頁講完** |
| **Anuj Goel — 候任財務長（2026-08-24 到職）** | **一位全新的財務長，接手約 40 億美元採購承諾、約 $765.1M 近期硬體承諾，以及對單一整合商 2.562 億美元的預付款曝險。** 新任財務長通常會在上任 90 天內重啟供應商集中度的檢討。條件：底薪 AUD$650,000、STI 最高為底薪 100%、LTI 最高為底薪 200%、簽約 RSU AUD$1,352,000，自 2027 年 6 月至 2031 年 6 月逐年歸屬 | **把接觸時間押在大約 2026 年 10 月至 11 月**，等他把帳看完。訴求框架為**供應來源分散與預付款風險降低，且要量化**。**這是本案時機最好的單一切入點** |
| **Andrew Leece — 營運長** | 負責 NEXTDC／GreenSquareDC／紐西蘭據點的部署與營運。自 2021 年起（併購前）兼任 Distributed Storage Solutions Limited（ACN 646 979 222）執行長；2017–2021 年任 AirOne Media, Inc. 執行長；2007–2015 年於 **Macquarie Bank (ASX: MQG)** 企業與資產融資部門起家；自 2018 年起任大型主機受管服務商 ISI Australia 董事。**他銜接部署排程與融資架構** | **談部署排程風險。** NEXTDC 五階段 2027 年 4 月至 8 月上線，而 take-or-pay 客戶合約隱含違約代價。**賣交期與分批交付可靠度** |
| **Peter Woodward — 董事（常居美國）** | **最好的美方引薦路徑，而且實質上很有份量。** 他現任 **TSS, Inc.** 董事長兼審計委員會主席——TSS 是美國的資料中心／機櫃整合與 IT 系統整合公司——所以他比多數董事更懂整合經濟與廠商毛利結構，而且人在美國、實際可接觸。自 2005 年 9 月起創辦並經營 MHW Capital Management, LLC；1996–2005 年任 Regan Fund Management, LLC 董事總經理；2015 年 6 月至 2018 年 7 月任 Cartesian, Inc. 總裁、執行長兼董事；並任 Precision Optics Corporation 董事長兼審計委員會主席、Innovative Power, LLC 執行長；曾任白宮 Council of Economic Advisors 經濟學家。Colgate 經濟學學士、Columbia MIA、CFA | **同儕層級的對話，不是業務拜訪。** 透過 **TSS／MHW Capital** 圈子引薦、談整合經濟，遠比冷接觸雪梨更可能成立。**用來取得進入 Mons 與 Manning 的背書** |
| **Alexander Andrew Kelton — 董事** | 現任 **Leading Edge Data Centers** 非執行董事長、Locate Technologies (ASX: LOC) 非執行董事長、Superloop 非執行董事；曾任 Superloop (ASX: SLC) 執行長、Megaport (ASX: MP1) 非執行董事、T-Mobile (Nasdaq: TMUS) 執行副總、Telstra International (ASX: TLS) 董事總經理、Docusign (Nasdaq: DOCU) 資深副總；約 40 年 ICT 資歷，橫跨英國、歐洲、印度、澳紐與美國。**他在 Audit and Risk Management Committee — 供應商集中度風險就是在那裡被討論的** | **以治理角度切入** — 單一整合商與單一機房的集中度風險。**不要對非執行董事推銷產品**；把那個風險問題種下去，讓技術長之後必須回答 |
| **Nicholas Hughes-Jones — Head of Corporate Development** | 負責合作案與合資架構。逾 18 年金融市場與科技資歷；2021 年 10 月至 2022 年 11 月任 **Mawson Infrastructure Group Inc. (Nasdaq: MIGI)** 商務長，「where he helped build over 100 modular data centers across 200MW of energy infrastructure in the USA and Australia」；2022–2024 年任 Defender Asset Management Pty Ltd 投資長；2016–2021 年任 Bell Financial Group (ASX: BFG) 資深顧問。經 Inbocalupo Consulting Pty Ltd 提供服務，2026-01-01 調整後年費 AUD$236,923 | **只有當這個案子變成策略或融資架構時才相關** — 例如以廠商融資去對打 Lenovo 的 EaaS/DaaS 安排。**否則略過** |
| **Tim Flahvin — 法務長兼公司秘書** | 任何 MSA 或供應合約的合約守門人。1998 年至 2026 年 1 月於澳洲全國型法律事務所任公司法合夥人；逾 28 年合夥層級資歷，經手 IPO、增資、上市規範遵循與併購 | **在技術與商務談定後才接觸。** 預期會由 **SharonAI Pty Ltd** 以澳洲法簽約 |

### 3.4 未補上的職位 — 每一項都是 GAP

**GAP — 所有具名個人的 LinkedIn。** 本次未解析出任何一位（共十三人）的 LinkedIn 連結。因此沒有以 LinkedIn 取得的職能別人力分布，也無法辨識美國本地員工，除了那一則 Austin, TX 的 Technical Accountant 職缺。· **GAP — 具名採購／供應商管理職：** DEF 14A、S-1、徵才頁與任何申報文件中皆無此頭銜。採購權限看來直接落在執行長、營運長與財務長身上。· **GAP — 具名 NOC 或網路工程人員：** 公開登記資料中真的一個都沒有。PeeringDB `poc_set` 為空，APNIC 所有聯絡窗口（SS4419-AP、SNA102-AP、IRT-DSSL-AU）都是角色帳號。**這是負面發現而非研究失敗**——但也代表網路登記通常能產出的「真名員工」在本案並不存在。· **GAP — 德拉瓦州註冊代理人、設立人與年報簽署人：** CAPTCHA 阻擋（見第 8 節）。· **GAP — Michael Schubert 的名（given name）：** 所讀 DEF 14A 章節僅呈現「Mr. Schubert」。· **GAP — Nicholas Hughes-Jones 的年齡：** 所擷取之名冊列未載明。· **GAP — Austin, TX 的確切地址、辦公室規模與美國員工數。** · **GAP — sharonai.com 的歷史 WHOIS：** 現行 WHOIS 已隱私遮蔽（「Domain Privacy」，PO Box 119, Beaconsfield VIC 3807, AU），且未取得遮蔽前紀錄；whoisrequest.com/history、whoxy.com 與 securitytrails 未成功查詢，且多屬付費服務。**未還原任何創辦期登記人姓名。** · **GAP — USPTO 商標宣誓簽署人與通訊代理人：** tmsearch.uspto.gov API 端點回傳 S3 `NoSuchKey`／`MethodNotAllowed`，developer.uspto.gov 導向（HTTP 301），Justia 商標查詢無可解析列。**「SHARON AI」是否曾在美國註冊為商標，仍屬未知。** · **GAP — 所有具名主要人員的 FEC 紀錄：** 見第 11 節；OpenFEC API 以 DEMO_KEY 遭額度限制，**沒有任何一個人的檢索真正完成。**

### 3.5 已動用來源 — 含查無結果者

**有產出：** [EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json)（法定名稱、CIK、設立州、SIC、股票代號、營業地址、舊名——**注意：WebFetch 對 sec.gov 回傳 HTTP 403；以符合 SEC 規範之 User-Agent 使用 curl 則可通**）· [Form 10-Q，截至 2026-06-30 之一季，2026-08-06 申報](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) —— 最豐富的單一來源：營收、TCDC 處分、WWT／Lenovo／Dicker Data 預付款、NVIDIA 40 億美元承諾、NEXTDC 72 MW／$623M、GreenSquareDC 15 MW、紐西蘭 14 MW、ASE、$765.1M 與 $217.2M 採購承諾、62,000 顆 GPU 目標與關係人承攬合約 · [Form S-1，2026-07-31 申報（4.6 MB）](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) —— 業務概述、NEXTDC M3 的 1,016 顆 GPU Supercluster、NEXTDC S3 的 1,024 顆 B300、NVIDIA NCP 效益（含**唯一一處 Supermicro／Dell OEM 提及**）、Cisco 與 Digital Alpha 合作細節、德拉瓦州子公司保證人清單、截至 2026-07-30 的 70 人編制，以及 GreenSquareDC SYD1 細節 · [DEF 14A，2026-07-13 申報](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm) —— 完整經理人與董事名冊，含年齡與完整經歷 · [Form 8-K，2026-07-24 申報](https://www.sec.gov/Archives/edgar/data/2068385/000149315226034569/form8-k.htm)（Goel 任命、Broadfoot 請辭）· [Form 8-K，2026-06-25 申報](https://www.sec.gov/Archives/edgar/data/2068385/000149315226030158/form8-k.htm)（$900M 股權、4.75% 可轉債、**無擔保（senior unsecured）**子公司保證、募資用途指向 NVIDIA GB300 建置）· Form 8-K，2026-06-17 申報（內容與前者重疊）· [APNIC whois 與 RDAP，AS142588](https://rdap.apnic.net/autnum/142588) · [PeeringDB API](https://www.peeringdb.com/api/net?org_id=39812&depth=2)（net 37929、org 39812）· [CourtListener REST API v4](https://www.courtlistener.com/docket/73130742/annonio-v-new-era-energy-digital-inc/) · WHOIS sharonai.com · [Wayback Machine CDX 與 sharonai.com/cloud-pricing/ 快照](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) · [sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/) · [sharonai.com/careers/](https://sharonai.com/careers/) · [Digital Alpha／Cisco 新聞稿](https://sharonai.com/press-releases/sharon-ai-accelerates-enterprise-ai-high-performance-compute-expansion-with-an-investment-from-digital-alpha-of-up-to-us200m-and-strategic-technology-partnership-with-cisco/)。

**已觸及但在人員面查無：** [PeeringDB](https://www.peeringdb.com/api/net?org_id=39812&depth=2) —— 網路面資料完整，`poc_set` **為空** · [ARIN Whois RWS 組織名稱查詢](https://whois.arin.net/rest/orgs;name=Sharon*) —— 十個不相關組織，**本標的無 ARIN 組織紀錄** · [SEC EDGAR 對 S-1 accession 之目錄列示](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) —— 回傳的是 sec.gov 通用導覽框架而非檔案索引，因此未能循此取得 Exhibit 21 子公司清單（保證人清單改由 S-1 本文取得）· [CourtListener 以「SharonAI」檢索](https://www.courtlistener.com/) —— 計數 0，**無任何針對本公司之訴訟** · [fec.gov 個人捐輸查詢介面](https://www.fec.gov/data/receipts/individual-contributions/) —— JavaScript 渲染，無可解析結果列 · USPTO tmsearch API（兩種端點變體 —— S3 `NoSuchKey` 與 `MethodNotAllowed`）、developer.uspto.gov ibd-api（HTTP 301）、Justia 商標查詢（無可解析列）。

**被阻擋或未觸及，以及原因：** [icis.corp.delaware.gov 實體名稱查詢](https://icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx) —— HTTP/2 200、46,881 bytes、**偵測到 2 處 captcha 標記、無可擷取之 `__VIEWSTATE`**；**CAPTCHA 不予破解**，因此未曾送出任何查詢字串 · [icis.corp.delaware.gov UCC 查詢](https://icis.corp.delaware.gov/Ecorp/UccSearch/UccSearchEntity.aspx) —— **HTTP/2 404，「The resource cannot be found.」** · [Texas SOS UCC](https://www.sos.state.tx.us/ucc/index.shtml) 與 [SOSDirect 登入](https://direct.sos.state.tx.us/acct/acct-login.asp) —— 需付費帳號 · [Texas Comptroller 特許稅查詢](https://comptroller.texas.gov/taxes/franchise/account-status/search) —— JS 渲染，舊端點回傳空 body · [OpenFEC schedules/schedule_a](https://api.open.fec.gov/v1/schedules/schedule_a/) —— **DEMO_KEY 於兩次獨立嘗試中，對 MANNING JAMES、WOODWARD PETER、ADAMS BENJAMIN、BROADFOOT、HUGHES-JONES、LEECE 與 MONS DANIEL 全部回傳 `OVER_RATE_LIMIT`** · **澳洲 PPSR —— 未檢索。** 這是整份檔案中價值最高的缺口；見第 8 節與第 14 節。

**在不驚動公司的前提下，補上幹部與留置權缺口的最佳下一步：** 對 **SharonAI Pty Ltd** 與 **Distributed Storage Solutions Pty Ltd** 執行**澳洲 Personal Property Securities Register（PPSR）** 查詢，並閱讀 **2026 年 6 月 Indenture（Exhibit 4.2）** 的留置權與可承作債務條款。

---

## 4. 據點與機房

**先看地理：完全沒有美國運算據點。** 以下每一個營運據點都在澳洲或紐西蘭。美國方面僅有一個紐約登記辦公室與一個德州 Austin 的財會據點。

| 據點 | 機房營運者 | 自有／承租 | 規模／電力（僅列已公開者） | 證據 |
|---|---|---|---|---|
| **NEXTDC M3，West Footscray，墨爾本，澳洲（Tier IV）** — 已安裝的旗艦據點 | **NEXTDC Limited (ASX: NXT)** | **承租／主機代管**（不可取消之營業租賃安排） | 容納 **「SharonAI Supercluster」——依 NVIDIA 參考架構建置的 1,016 顆 GPU 部署**，目前配置 **NVIDIA H200** GPU 搭配 **NVIDIA Quantum-2 InfiniBand**。官方描述為「immediately available installed capacity」，以 **bonded 200G Ethernet** 網路提供 VM、容器或裸機 | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) 原文：「Central to this partnership is the SharonAI Supercluster, a 1,016-GPU deployment built to NVIDIA reference architecture specifications… This is co-located at NEXTDC's M3 data center in Melbourne, Australia and currently features NVIDIA H200 GPUs.」**獨立佐證**：[PeeringDB netfac 記錄 id 85369「NEXTDC M3」](https://www.peeringdb.com/api/net?org_id=39812&depth=2)，West Footscray, AU |
| **NEXTDC S3，Artarmon，雪梨，澳洲** | **NEXTDC Limited (ASX: NXT)** | **承租／主機代管** | **1,024 顆 NVIDIA B300 GPU 叢集**，預計 **2026 上半年**上線，與 **Cisco** 合作建置，定位為「Australia's first Cisco Secure AI Factory」 | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)。**佐證**：[PeeringDB netfac 記錄 id 89484「NEXTDC S3」](https://www.peeringdb.com/api/net?org_id=39812&depth=2)，Artarmon, AU，建立於 2026-07-29 |
| **NEXTDC — 墨爾本與雪梨擴充容量**（2026 年 7 月修訂重簽之服務訂單） | **NEXTDC Limited (ASX: NXT)** | **承租／已簽約容量** | **72 MW**；合約總承諾 **約 6.23 億美元**；分 **五階段自 2027 年 4 月至 8 月** 部署。另有一份於墨爾本與雪梨 **最高 87 MW** 的擴充協議 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) 原文：「In July 2026, the Company executed an amended and restated service order with NEXTDC for 72 MW of data center capacity in Australia. The arrangement represents a total contractual commitment of approximately $623 million over the term… The capacity is scheduled to be deployed in five phases commencing in April 2027 through August 2027.」風險因子：「we have secured up to 87MW of capacity through NEXTDC and rely on NEXTDC to host substantially all of our GPU infrastructure」 |
| **GreenSquareDC — SYD1 園區（亦稱 SYDGPU1），Norwest Business Park，雪梨，澳洲** | **GreenSquareDC**（Partners Group 支持） | **承租／長期資料中心服務合約** | 依 **2026 年 3 月** 簽訂之長期合約承諾 **15 MW**；自目標 Ready-for-Service 日 **2026-09-26** 起 **120 個月**初始期間；月費依已簽約 kW 計。園區完整建置設計可達 **110 MW**，支援**高密度液冷**配置 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)：「a 15 MW commitment under a long-term data center services agreement entered into in March 2026 with GreenSquareDC Entity for a facility located in Australia… targeted September 26, 2026.」SYD1／SYDGPU1 園區描述見 [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) |
| **紐西蘭 — 未揭露之設施** | **GAP — 未揭露營運者。** 受管服務由 **Andrew Sjoquist Enterprises (ASE)** 承接 | **承租／已簽約容量** | 依長期客戶服務合約取得 **14 MW** 以支援雲端運算基礎設施部署，**預計 2027 年第一季開始**。**這就是支撐 US$1.32 bn AI lab 合約的據點** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)：「The Company has also secured additional data center capacity in New Zealand for 14MW to support the deployment of cloud computing infrastructure under a long-term customer service agreement with commencement expected in Q1 2027.」ASE 承諾約 AUD$400 千元／五年，係於終止 Distributed Storage Solutions（DSS）資料中心服務安排後訂立 |
| **額外第三方容量，約 29.6 MW**（2026 年 5 月） | **GAP — 多家未揭露之第三方資料中心基礎設施供應商** | **承租／已簽約** | **約 29.6 MW** 額外容量；相關安排**預計自 2026 年底起陸續開始** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) Key Corporate Milestones：「In May 2026, the Company entered into multiple long-term agreements with third-party data center infrastructure providers for approximately 29.6 MW of additional capacity to support future operations」 |
| **Equinix SYD3 與 SYD5，雪梨（Tier III）** — **僅屬舊有／行銷宣稱** | Equinix | **承租／主機代管** | **未量化。** 官網列為機房據點，但**10-Q 與 S-1 皆未佐證**，兩份文件均指 NEXTDC 承載「substantially all」GPU 基礎設施。**視為舊有或小規模據點** | [sharonai.com](https://sharonai.com) 首頁。**任何 SEC 申報中皆未出現** |
| **Texas Critical Data Centers LLC (TCDC) — Ector County／Odessa，德州 — 已出售，不再持有** | 原為與 **New Era Energy & Digital Inc. (NUAI)** 之 50:50 合資；現由 NUAI 全數持有 | **2026-01-13 出售** | 原規劃 **250 MW** 淨零表後資料中心，搭配天然氣發電廠，位於 Permian Basin；Odessa 郊外已取得 **235 英畝**，另就相鄰 **203 英畝** 簽有 LOI（合計 438 英畝），係 2025 年公告之狀態 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)：「On January 13, 2026, the Company completed the sale of its 50% ownership interest in TCDC to NUAI. Upon completion of the transaction, the Company ceased to have an ownership interest in TCDC or participate in the joint venture.」對價包含 NUAI 之 **5,000 萬美元優先擔保可轉換本票**，年息 **10.0%**（2026-04-24 以現金全額清償，未轉換），以及 NUAI 普通股（2026-05-14 出售）。**截至 2026-06-30 之六個月認列處分利益 $65,920 千美元** |

**地理註記（這是轄區判定，不是註腳）：** 六個在營運據點全數位於澳洲或紐西蘭。**PeeringDB 上每一個機房與每一個 IXP 都在澳洲。** 沒有任何美國運算據點、沒有美國主機代管、沒有 ARIN 分配，也沒有任何形式的美國網路存在。

---

## 5. 硬體機隊

本節證據等級：**confirmed（確認）**＝SEC 申報文件或公司自家頁面的第一手具名揭露，或多方獨立佐證｜**circumstantial（旁證）**＝名稱有出現，但不是採購關係｜**inferred（推論）**＝僅由專屬元件命名等品牌線索推得｜**GAP**＝正反皆無資料。

| 廠商／類別 | 證據等級 | 證據實際說了什麼 |
|---|---|---|
| **World Wide Technology — WWT Australia Pty Ltd** | **確認 — 既有整合商，也是最大的單一硬體交易對手** | [Form 10-Q Note 10](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)：「prepayments primarily relate to deposits and milestone payments for high-performance computing equipment with **WWT Australia Pty Ltd**」——截至 2026-06-30 帳列 **$256,186 千美元（2.562 億美元）** 設備預付款。WWT 亦在 [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) 中被列為構成整合式 AI 生態系的策略夥伴之一。**這就是 HPC 設備實際採購的通路** |
| **Lenovo — Lenovo Group Limited；Lenovo Global Financial Services (Australia & New Zealand) Pty Limited** | **確認 — 五項獨立佐證** | (1) [Form 10-Q Note 10](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)：「down payments under an **Equipment-as-a-Service (EaaS)/Device-as-a-Service (DaaS)** arrangement with Lenovo Global Financial Services (Australia & New Zealand) Pty Limited」——預付 **$33,094 千美元**。(2) 10-Q 承諾事項：「On December 12, 2025, the Company entered into a **Statement of Work** with Lenovo Global Financial Services (Australia & New Zealand) Pty Limited for managed infrastructure services… term of **60 months**… upfront payment representing approximately **50% of the total contract value**.」(3) 10-Q 中出現 XBRL 標籤 `SHAZ:LenovoGlobalFinancialServicesLimitedMember`。(4) S-1 將 Lenovo Group Limited 列為策略技術夥伴之一。(5) **獨立佐證：** 公司自家公布的節點規格寫著「**24 x 32GB TruDDR5 4800MHz RAM**」——**TruDDR5 是 Lenovo 專屬記憶體品牌**，指向 Lenovo ThinkSystem 硬體（[sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/)）。**請注意 EaaS/DaaS 結構：硬體是以融資服務方式消耗，不是買斷——這是一道很深的競爭護城河** |
| **Cisco Systems Inc.** | **確認 — 而且是結構性綁定，不只是商業合作** | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)：「Cisco provides the Company with AI-ready networking infrastructure, including access to **Cisco Nexus HyperFabric AI** and **NVIDIA Spectrum-X-aligned** infrastructure.」公司為「a strategic partner of Cisco」且是「a member of the **Cisco 360 Partner Program**」，該計畫「authorizes us to build, sell, and manage integrated Cisco solutions」。NEXTDC S3 的 B300 叢集「built in partnership with Cisco and is expected to be **Australia's first Cisco Secure AI Factory**」。[Digital Alpha 新聞稿](https://sharonai.com/press-releases/sharon-ai-accelerates-enterprise-ai-high-performance-compute-expansion-with-an-investment-from-digital-alpha-of-up-to-us200m-and-strategic-technology-partnership-with-cisco/) 明列 **Cisco UCS 伺服器**、Cisco Nexus Hyperfabric 交換，以及 Cisco 資安與可觀測性堆疊。**與 Cisco 具獨家技術夥伴關係的 Digital Alpha Advisors LLC 投資最高 US$200M 並為股東。CISCO UCS 在本案是直接的伺服器競爭者** |
| **NVIDIA Corporation** | **確認** | **2026-06-12** 訂立六年期 AI 基礎設施運算合作；**約 40 億美元** 採購承諾；**最高 40,000 顆 GB300**；**NVIDIA DSX AI factory 設計**；分潤加信用支持模式。公司具 **NVIDIA Cloud Partner (NCP)** 認證，可見 NVIDIA **12 至 18 個月滾動供應鏈預測**，並取得 B200／B300 的優先取得權（[Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)） |
| **VAST Data Inc.（經 Dicker Data Limited 採購）** | **確認** | [Form 10-Q Note 10](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)：「prepayments to **Dicker Data Limited** for VAST Data software」——**$13,368 千美元**。2026-06-16 公告部署 **600PB** VAST AI Operating System。**Dicker Data 是登記在案的澳洲代理商** |
| **AMD** | **確認 — 兩種不同關係** | (1) **CPU：** 已公布之節點規格在 H100 NVL 與 L40S 兩種節點都使用「2 x AMD EPYC 32C 3.25GHz CPUs」。(2) **GPU：** 公開 GPU 型錄曾提供 **AMD MI300X**，價格 **$2.90/GPU/hr**（[sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/)） |
| **NEXTDC Limited (ASX: NXT)** | **確認 — 是機房守門人，不是伺服器廠商** | 「we rely on NEXTDC to host substantially all of our GPU infrastructure」與「we have secured up to 87MW of capacity through NEXTDC」（[Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)）。主要但非獨家之主機代管供應商 |
| **Megaport Limited** | **確認** | 於 [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) 中被列為構成整合式 AI 生態系的策略夥伴之一（連線／互連）。PeeringDB 佐證：公司在 **MegaIX Melbourne** 對接（AS142588、103.26.71.53、10 Gbps） |
| **Andrew Sjoquist Enterprises (ASE)** | **確認** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm)：受管服務供應商，依不可取消承諾 **約 AUD$400 千元／五年** 訂約，係於終止 Distributed Storage Solutions（DSS）資料中心服務安排後訂立；支援 **紐西蘭** 部署 |
| **Super Micro Computer, Inc.（Supermicro）** | **旁證 — 不得誇大。絕不可呈現為既有供應商** | 在 10-Q、DEF 14A、三份 8-K 與 4.6 MB S-1 全文中，Supermicro **只出現過一次**，而且**不是採購關係**。唯一出處是在描述 **NVIDIA Cloud Partner 資格** 效益的清單中：「**OEM Relationships: Facilitated engagement with OEMs such as Cisco, Lenovo, Dell, and Super Micro to support server procurement and integration**」（[Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)）。那是 NVIDIA 促成對一組 OEM 名單的接觸——它只能證明 Supermicro **在核可／已知的 OEM 名單之內，僅此而已**。**沒有採購單、沒有預付款、沒有承諾、沒有具名合約，任何已公布節點規格中也沒有 Supermicro 硬體。** 所有已公布節點規格都指向 Lenovo（TruDDR5）。**等級為旁證，不是確認** |
| **Dell Technologies** | **旁證** | 與 Supermicro **同一句 S-1 文字**：「OEM Relationships: Facilitated engagement with OEMs such as Cisco, Lenovo, Dell, and Super Micro」。**全網無任何採購證據。** 僅因 NVIDIA NCP 資格而被列為已知 OEM 通路（[Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)） |
| **HPE、Gigabyte、ASUS、Penguin Computing、Pure Storage、WEKA、Arista** | **GAP** | 已針對 10-Q、DEF 14A、S-1、徵才頁與產品頁明確搜尋。**上述廠商出現次數皆為零。** 正反皆無證據——記為**真實的「不存在」，而非負面發現** |

### 平台辨識，以及它代表什麼

以下直接讀自公司自家 `/ai-cloud/` 頁面的節點規格——這是由**品牌線索推得的平台證據**，不是廠商揭露：

- **已公布的節點是 Lenovo ThinkSystem，SR675 V3 等級。** 破綻在「24 x 32GB **TruDDR5** 4800MHz RAM」。TruDDR5 是 Lenovo 專屬記憶體品牌名，不會出現在白牌或 Supermicro 配置中。
- **CPU：**「2 x AMD EPYC 32C 3.25GHz CPUs」——頁面把料號寫成「3954」，幾乎可以確定是 **EPYC 9354**。
- **儲存拓撲：** 6 × 7.68TB U.2 NVMe（約 46TB）加 2 × 1.92TB M.2 NVMe 作 OS（3.84TB）。
- **型錄中的舊世代密度：** A40、L40、L40S 與 RTX3090 是最老的自有資產，也是最實際的第一批汰換標的。
- **網路是封閉的：** NEXTDC M3 為 bonded 200G Ethernet、叢集內為 NVIDIA Quantum-2 InfiniBand，並在 Cisco 合作下採用 Cisco Nexus HyperFabric AI 與 NVIDIA Spectrum-X-aligned 網路。**網路端穩固落在 Cisco／NVIDIA 手上——不是開放賽道。**

**這代表什麼：** 這支機隊**不是槓鈴型、也不是機會式自組**——它是一支**由融資支撐、單一整合商、依參考架構建置的機隊**。這與白牌業者恰恰相反，也代表 Supermicro 實際可行的切入點**不是零組件或準系統銷售**，而是**針對 2027 年批次的機櫃級 GB300 NVL72 容量**，以交期與排程保障為訴求，去對打一個已經把整個堆疊以服務方式融資掉的既有廠商。

---

## 6. GPU 型錄與 AI 佈局

> ### 重大變動 — 截至 2026-08-11 已無公開價目表
>
> 公司已**撤下公開 GPU 定價**。[`/cloud-pricing/`](https://sharonai.com/cloud-pricing/) 現在回傳 **0 bytes**；`/pricing-calculator/` **301 導向首頁**。**2025-05-28 以後的存檔快照皆不含任何 GPU 價格文字**。商業模式已轉向「Contact us for volume and term discount」、**take-or-pay 合約** 與極大額的議定合約（$373M、$950M、$1.32 bn）。**以下每一個價格都是歷史值（2024 年 10 月至 12 月），已約 20 個月未更新，不得當作現行價格陳述。**

完整擷取型錄——每一個 SKU 均附價格，依原文照錄：

| SKU | 價格 | 頁面所載供應狀態 | 來源 |
|---|---|---|---|
| **NVIDIA H200** | **$3.20 /GPU/Hr** | 「Reserve Now (Dec 24)」——即尚未安裝；針對 2024 年 12 月到貨接受預約 | [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) |
| **NVIDIA H100 NVL** | **$2.50 /GPU/Hr** | Available Now（2024-12-08 當時） | [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) |
| **NVIDIA L40S** | **$1.15 /GPU/Hr** | Available Now（2024-12-08 當時） | [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) |
| **NVIDIA A40** | **$0.50 /GPU/Hr** | Available Now——即廣告主打之入門價「As Low As $0.50 GPU/Hr」 | [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) |
| **AMD MI300X** | **$2.90 /GPU/Hr** | 「Reserve Your Capacity」／「Available Now」——2024-12-08 當時**兩種標籤同時存在** | [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) |
| **NVIDIA H200**（較早級距，2024 年 10 月） | **$3.50 /GPU/Hr**（隨用隨付）與 **$3.52 /GPU/Hr**（第二級距） | 「Reserve Now (Dec 24)」 | [Wayback 2024-10-14](http://web.archive.org/web/20241014091529/https://sharonai.com/cloud-pricing/) |
| **NVIDIA H100 NVL**（較早級距，2024 年 10 月） | **$2.90 /GPU/Hr**（隨用隨付）與 **$3.20 /GPU/Hr**（第二級距） | 第一級距為「Available Now」；第二級距為 **「Reserve Now (Sep 24)」**——**這把 H100 NVL 的採購事件定在大約 2024 年 9 月** | [Wayback 2024-10-14](http://web.archive.org/web/20241014091529/https://sharonai.com/cloud-pricing/) |
| **NVIDIA L40S**（2024 年 10 月） | **$1.27 /GPU/Hr** | Available Now | [Wayback 2024-10-14](http://web.archive.org/web/20241014091529/https://sharonai.com/cloud-pricing/) |
| **NVIDIA A40**（2024 年 10 月） | **$0.50 /GPU/Hr** | Available Now——2024 年 10 月至 12 月間**價格未變** | [Wayback 2024-10-14](http://web.archive.org/web/20241014091529/https://sharonai.com/cloud-pricing/) |
| **NVIDIA RTX3090** | **任何已擷取之價目表皆未刊價** | 現行 /ai-cloud/ 頁面仍列為產品 | [sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/) |
| **NVIDIA B200、B300、GB300** | **未刊價 — Blackwell 世代不存在任何公開價目表** | Supercluster 剩餘部分之 B200 預計 2026 上半年；NEXTDC S3 的 1,024 顆 B300 叢集預計 2026 上半年；新 AI lab 合約之 2,048 顆 B300 自 2027 年第一季起；**最高 40,000 顆 GB300** 於 2027 年 4 月至 8 月 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **現行定價狀態** | **截至 2026-08-11 不存在任何公開價目表** | `/cloud-pricing/` 回傳 0 bytes；`/pricing-calculator/` 301 導向首頁 | [sharonai.com/cloud-pricing/](https://sharonai.com/cloud-pricing/) |

### AI 佈局 — 已安裝 vs 已簽約

| 項目 | 內容 | 依據 | Supermicro 對應機種 | 來源 |
|---|---|---|---|---|
| **SharonAI Supercluster — 已安裝並營運中** | **1,016 顆 GPU**，目前為 NVIDIA **H200**、NVIDIA Quantum-2 InfiniBand，依 NVIDIA 參考架構建置，位於 **NEXTDC M3 墨爾本**。叢集其餘部分預計採 **NVIDIA B200** | S-1 揭露 | H200 SXM 8-GPU：**SYS-821GE-TNHR**／**AS-8125GS-TNHR**（8U／4U HGX H200 8-GPU）。若為 PCIe H200 NVL：**AS-4125GS-TNRT** 等級 | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) |
| **NEXTDC S3 之 B300 叢集 — 部署中** | **1,024 顆 NVIDIA B300**（Blackwell Ultra），預計 2026 上半年上線，與 Cisco 合作建置，定位為「Australia's first Cisco Secure AI Factory」 | S-1 揭露 | Supermicro HGX B300 8-GPU 系統（**SYS-A21GE-NBRT** 等級／4U 液冷 Blackwell Ultra）。**注意：本叢集具名合作方是 Cisco——這是 Cisco UCS 替換標的，不是新建案** | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) |
| **已公布之 H100 NVL 運算節點 — 目前能取得、最接近 BOM 層級的採購樣貌** | 8 × **H100 NVL (94GB)** 含 NVLink Bridge (188GB)；2 × **AMD EPYC 32C 3.25GHz** CPU（頁面寫「3954」，幾可確定為 **EPYC 9354**）；24 × 32GB **TruDDR5** 4800MHz RAM（共 768GB）；6 × 7.68TB U.2 NVMe（約 46TB）；2 × 1.92TB M.2 NVMe（3.84TB OS） | 公司自家線上頁面，逐字節點規格 | **AS-4125GS-TNRT**（4U、8× PCIe GPU、雙 AMD EPYC 9004/9005）為直接對應機種。**重要訊號：「TruDDR5」是 Lenovo 專屬記憶體品牌——獨立佐證這些是 Lenovo ThinkSystem 節點（SR675 V3 等級），不是白牌，也不是 Supermicro** | [sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/) |
| **已公布之 L40S 運算節點** | 8 × **L40S (48GB)**；2 × AMD EPYC 32C 3.25GHz CPU；24 × 32GB TruDDR5 4800MHz RAM（768GB）；6 × 7.68TB U.2 NVMe（約 46TB）；2 × 1.92TB M.2 NVMe（3.84TB OS） | 公司自家線上頁面，逐字節點規格 | **SYS-421GE-TNRT** 或 **AS-4125GS-TNRT** 搭 8 × L40S PCIe | [sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/) |
| **NVIDIA 六年期策略運算合作 — 未來最大的機隊事件** | 於澳洲建置 **72 MW AI factory**，採用 **NVIDIA DSX AI factory 設計**，規模擴充至 **最高 40,000 顆 Grace Blackwell GB300 GPU**。以 **分潤與信用支持** 架構設計：Sharon AI 銷售 NVIDIA 驅動之雲端服務，NVIDIA 取得標準產品營收加上雲端營收分潤。協議日期 **2026-06-12**。連帶承諾採購額外 HPC 硬體與相關基礎設施 **約 40 億美元** | 10-Q 承諾事項附註與 Key Corporate Milestones；8-K 募資用途 | **GB300 NVL72 機櫃級。** Supermicro 以其 GB300 NVL72 機櫃系統在此競爭。**警告：NVIDIA DSX 參考設計加上分潤／信用支持結構，代表 NVIDIA 對 OEM 短名單有強力影響力——這不是純粹開放的競標** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **已簽約 AI Factory 容量與 GPU 數量目標** | AI Factory 容量共 **約 132 MW**，其中 **116 MW 已與終端客戶簽約**，並預計 **2027 年中前部署超過 62,000 顆 NVIDIA GPU** | 10-Q 中與 ASE／紐西蘭協議相關之揭露 | 僅供 TAM 規模參考 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **近期硬體採購承諾 — 已承諾但尚未認列為負債** | 與硬體及基礎設施供應商之採購承諾 **約 7.651 億美元**，以支援已簽約之 AI 運算容量；**另加約 2.172 億美元**（含估計稅負），用於新五年期雲端合約下之 **2,048 顆 NVIDIA B300** 部署 | 10-Q 承諾事項與後續事項附註 | **這些是已經被講定的錢。任何 Supermicro 動作都必須瞄準這之後的批次，或是重新切分這些批次** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **儲存架構** | 於 AI 雲端基礎設施部署 **600PB** 的 **VAST AI Operating System**（2026-06-16 公告），公司自行換算為 **每 1,000 顆 GPU 約 6PB**，亦即依 **約 100,000 顆 GPU** 規模設計 | 10-Q Key Corporate Milestones | VAST 通常架在通用 x86 儲存節點上——**是 Supermicro 可能的鄰接機會**，但請注意 VAST 軟體是透過 **Dicker Data Limited**（澳洲代理商）採購，已預付 $13,368 千美元 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **歷史／舊型錄 SKU** | NVIDIA **H200、H100 NVL、L40S、L40、A40、RTX3090**，以及 **AMD MI300X** | 官網產品頁與存檔定價頁 | **A40／L40／L40S／RTX3090 屬舊世代密度——很可能是最老的自有資產，也是第一批汰換標的** | [sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/) |
| **網路配置** | NEXTDC M3 已安裝容量採 bonded **200G Ethernet**；Supercluster 採 **NVIDIA Quantum-2 InfiniBand**；並在 Cisco 合作下採用 **Cisco Nexus HyperFabric AI** 與 NVIDIA Spectrum-X-aligned 網路 | S-1 與線上官網 | **網路端穩固落在 Cisco／NVIDIA 手上——不是開放賽道** | [sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/) |

**判讀：** **今天約 2,000 顆 GPU 已安裝，相對於 62,000 顆以上的規劃。** 這支機隊幾乎全部**還在前方，不在後方**——這一點不尋常，也很重要。這不是一個有老舊矽晶可以替換的汰舊換新案，而是一個**建置案**：幾乎所有量都還沒下單，但那些量的 OEM 短名單，已經被 NVIDIA 的 DSX 設計、Lenovo 的 EaaS 融資與 Cisco 的股權背書合作關係先行塑形。

---

## 7. 採購時鐘

這家公司實際多久承諾一次新矽晶，以三條互相獨立、且都不依賴廠商說法的資料序列重建。

### 7.1 時間軸

| 日期 | 事件 | 類型 | 來源 |
|---|---|---|---|
| **2024 年 9 月前** | **A40、L40S、L40、RTX3090 已在服役** — 在最早可用的快照中全部標示「Available Now」 | 既有安裝基礎 | [Wayback 2024-10-14](http://web.archive.org/web/20241014091529/https://sharonai.com/cloud-pricing/) |
| **約 2024 年 9 月** | **H100 NVL 採購事件。** 2024-10-14 快照顯示一個標示 **「Reserve Now (Sep 24)」** 的級距；到 2024-12-08 時 H100 NVL 已改為 **「Available Now」** | **採購事件** — 直接由價目表定年 | [Wayback 2024-10-14](http://web.archive.org/web/20241014091529/https://sharonai.com/cloud-pricing/) · [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) |
| **約 2024 年 12 月** | **H200 採購事件。**「Reserve Now (Dec 24)」在 2024 年 10 月與 12 月兩份快照中都持續存在；到 2026 年 S-1 時，NEXTDC M3 的 1,016 顆 GPU Supercluster「currently features NVIDIA H200」 | **採購事件** | [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) · [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) |
| **2024 年 12 月前** | **AMD MI300X 加入型錄**，價格 $2.90/GPU/hr | **採購事件**（AMD GPU） | [Wayback 2024-12-08](http://web.archive.org/web/20241208161827/https://sharonai.com/cloud-pricing/) |
| **2025-12-19** | **與 Roth CH 的合併完成。** 合併完成時發行無擔保可贖回可轉換公司債 | **融資事件** — 是後續所有採購的閘門 | [EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json) |
| **2025-12-12** | 簽訂 **Lenovo Statement of Work** — 受管基礎設施服務，60 個月，約 50% 於期初支付 | **採購結構事件** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026 年 1 月** | **Digital Alpha 投資最高 US$200M**，並與 Cisco 建立策略技術夥伴關係 | **融資事件** — 也是 Cisco 結構性嵌入的時點 | [Digital Alpha 新聞稿](https://sharonai.com/press-releases/sharon-ai-accelerates-enterprise-ai-high-performance-compute-expansion-with-an-investment-from-digital-alpha-of-up-to-us200m-and-strategic-technology-partnership-with-cisco/) |
| **2026-01-13** | **TCDC（德州 Odessa，250 MW）出售予 NUAI。** 公司不再持有任何股權，也不再參與合資 | **處分** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026 上半年** | **B200**（Supercluster 其餘部分）與 **B300**（NEXTDC S3 的 1,024 顆，Cisco Secure AI Factory） | **採購事件** | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) |
| **2026-04-26／2026-05-20 完成** | **$350M 6.00% 到期日 2031 年之可轉換優先公司債** | **融資事件** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026-05-13** | 與在亞太具重要據點之全球科技公司簽訂 **約 $950M 客戶合約** | 拉動採購的需求事件 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026 年 5 月** | 簽下 **約 29.6 MW** 額外第三方容量，自 **2026 年底** 起開始 | 容量事件 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026-06-12** | **NVIDIA 六年期合作簽訂** — 最高 **40,000 顆 GB300**、**約 40 億美元** 採購承諾、DSX AI factory 設計、分潤加信用支持 | **紀錄上最大的採購承諾** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026-06-16** | 公告部署 **600PB VAST AI Operating System**（經 Dicker Data） | 儲存採購事件 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026-06-17／06-22，於 06-22–23 完成** | **$900M 股權加 4.75% 可轉換公司債**，明確指定用於 **NVIDIA GB300 建置** | **融資事件 — 就是這筆錢在買 2027 年的機隊** | [Form 8-K 2026-06-25](https://www.sec.gov/Archives/edgar/data/2068385/000149315226030158/form8-k.htm) |
| **2026-07-16** | 與未具名之全球 AI lab 簽訂五年期 **US$1.32 bn** 雲端合約；初期部署預計使用 **2,048 顆 NVIDIA B300**，架於紐西蘭基礎設施 | 需求事件 | [ex99-1](https://www.sec.gov/Archives/edgar/data/0002068385/000149315226033457/ex99-1.htm) |
| **2026 年 7 月** | **NEXTDC 修訂重簽服務訂單 — 72 MW、約 $623M、五階段 2027 年 4 月 → 8 月** | 設定 RFS 時鐘的容量事件 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2026-08-06 揭露** | 為 **2,048 顆 NVIDIA B300** 承諾 **約 2.172 億美元** — 以後續事項申報，是最新一筆增量承諾 | **最新採購承諾** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2027 年第一季** | $1.32 bn／$373M AI lab 合約之 2,048 顆 **B300** 開始產生營收；紐西蘭 14 MW 開始 | 未來 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |
| **2027 年 4 月至 8 月** | **NEXTDC 72 MW 五階段部署** | 未來 — 一切往回推算的硬性 RFS 日期 | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) |

### 7.2 節奏

**兩個時鐘重疊，而第二個已經接管了。**

- **型錄時鐘** 在 2024 年間大約 **每 3 至 6 個月推進一個 NVIDIA 新世代** —— L40S／A40 → **H100 NVL（2024 年 9 月）** → **H200（2024 年 12 月）**，幾乎即時跟上 NVIDIA 的發表節奏。這與 NCP 資格，以及其自述可見 NVIDIA 12 至 18 個月滾動供應預測相符。
- **資本時鐘現在才是主導，而且更快：七個月內四次融資事件** —— 2025 年 12 月、2026 年 1 月、2026 年 4／5 月、2026 年 6 月 —— **且每一次都立即指定用於 GPU 與基礎設施採購**。上市之後，公司已從約十萬美元級距的型錄換代，跳到 **已承諾約 $765.1M ＋ $217.2M、已簽約約 40 億美元**。

**現行有效採購節奏約為每季一次，且由募資事件驅動，而非產品週期驅動。**

**最近一次事件：** **2026-06-12** —— NVIDIA 六年期合作（約 40 億美元承諾、最高 40,000 顆 GB300），由 2026-06-22／23 完成的 $900M 股權加可轉債募資支應。最新一筆增量承諾：**為 2,048 顆 NVIDIA B300 承諾約 2.172 億美元**，於 2026-08-06 申報之 10-Q 中以後續事項揭露。

### 7.3 下一個窗口

**兩個窗口。**

- **近期 — 約 2026 年 8 月至 11 月。** 涵蓋 2026 年 5 月簽下、將於「2026 年底」開始的 **約 29.6 MW 第三方容量**、Ready-for-Service 目標為 **2026-09-26** 的 **GreenSquareDC 15 MW**，以及 2027 年第一季開始的 **紐西蘭 14 MW**。
- **主要 — 約 2026 年第四季至 2027 年第二季**，對應 **B300／GB300 批次**。推算方式為：由已揭露的 **2027 年 4 月至 8 月 NEXTDC 五階段 RFS 日期** 與 **2027 年第一季營收起算日** 往回推，扣除機櫃級 Blackwell 典型的二至三季採購與整合前置期。
- **次要（較軟） — 約 2026 年 10 月至 11 月**，即候任財務長 **Anuj Goel**（2026-08-24 到職）完成首次供應商與承諾檢討之時。

### 7.4 方法

三條互相獨立的序列交叉驗證：

**(a) Wayback Machine CDX 列舉** [sharonai.com/cloud-pricing/](https://sharonai.com/cloud-pricing/) —— **2024-09-19 至 2026-03-28 共 14 份不同快照** —— 抓取原始 `id_` 快照並擷取 SKU／價格／供應狀態表。**「Reserve Now (Sep 24)」與「Reserve Now (Dec 24)」標籤直接為採購承諾定年**，而一個 SKU 從「Reserve Now」轉為「Available Now」則為安裝時點定年。

**(b) SEC 揭露之部署里程碑與 Ready-for-Service 日期**，取自 [10-Q 承諾事項附註](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) 與 [S-1 業務章節](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)。

**(c) SEC 揭露之融資交割**，取自 8-K 系列，前提是——**8-K 的募資用途文字本身即明確載明**——每一次募資都指定用於特定硬體。採購窗口再以 **已揭露 RFS 日期減去二至三季** 估算。

**必須明說的限制：** 序列 (a) **在 2025 年年中就中斷了**，因為公司撤下公開定價。2024-09-19、2025-05-28、2025-11-26 與 2026-03-28 的快照 **均無可擷取的 GPU 或價格文字** —— 2024-09-19 那份只有 56,581 bytes，較晚的則是 JS 空殼快照。**因此 2025 年之後的時鐘只靠 (b) 與 (c)，顆粒度相對較粗。**

---

## 8. UCC 融資紀錄

**本節範圍：** SharonAI Holdings Inc. 與其四家德拉瓦州子公司 —— **SharonAI Inc.、SharonAI Operations LLC、SharonAI Hosting LLC、SAI US No. 1 LLC** —— 並旁及澳洲法人 **SharonAI Pty Ltd** 與 **Distributed Storage Solutions Pty Ltd**。

### 8.1 判定

> ### UNVERIFIED — 入口被阻擋

**請完全照字面理解。** **沒有取得、沒有轉錄、也沒有排除任何一筆 UCC-1 融資聲明。讀到的檔案數為零。** 無法回報任何 filing number、filing date、lapse／continuation 狀態、secured party、debtor、collateral description，或 amendment／assignment／termination 資料，**因為對任何 UCC 索引都未成功執行過一次檢索**。8.2 節的空白檔案集代表*什麼都沒看到*，**不代表這家公司沒有擔保債務**。絕不得對客戶回報、不得引用給徵信、也不得以「查無留置權」登錄 CRM。

**有一項管轄權要點，比阻擋本身更重要：** 母公司與四家美國子公司的 **設立州別都是德拉瓦州**，因此依 UCC §9-301／9-307，**德拉瓦州才是正確的登記機關**。**德州並非設立州別，即使德州 UCC 查詢成功，也不具決定性。**

### 8.2 在案檔案 — 每筆逐字全文照錄

**取得檔案數：0。**

以下沒有逐筆檔案區塊，因為 **任何介面都不曾回傳過任何一筆檔案**。這裡沒有壓縮、簡寫或摘要任何內容 —— 是登記簿從頭到尾沒被觸及。因此，徵信或通路決策所需的每一個逐筆欄位，對每一位債務人而言都是明確的 GAP：

| 逐筆所需欄位 | `SHARONAI HOLDINGS INC.` | `SHARONAI INC.` | `SHARONAI OPERATIONS LLC` | `SHARONAI HOSTING LLC` | `SAI US NO. 1 LLC` |
|---|---|---|---|---|---|
| Filing number | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Filing date | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Lapse date／continuation 狀態 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Secured party 名稱＋地址 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Debtor 名稱＋登記地址 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Collateral description（逐字） | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| Amendments／assignments／terminations | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |
| 紀錄連結 | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** | **GAP — 登記簿從未觸及** |

### 8.3 查詢紀錄 — 一次嘗試一列，不合併

| 入口／URL | 送出之查詢 | 逐字回應 | 替代路徑 |
|---|---|---|---|
| **德拉瓦州 UCC 查詢** — [icis.corp.delaware.gov/Ecorp/UccSearch/UccSearchEntity.aspx](https://icis.corp.delaware.gov/Ecorp/UccSearch/UccSearchEntity.aspx)。方法：HTTPS GET | **無 — 無法送出任何債務人字串。** 原意是查詢全部五個德拉瓦州債務人 | **HTTP/2 404**，body：**「The resource cannot be found.」** 該網址不存在 UCC 查詢路徑 | 以 Division of Corporations 認證查詢途徑或商業資料商，對四家德拉瓦州子公司加母公司執行付費 UCC 查詢 |
| **德拉瓦州實體名稱查詢**（作為進入 UCC 系統與確認註冊代理人之途徑） — [icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx](https://icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx)。方法：HTTPS GET，帶 cookie jar | **無 — 從未送出任何查詢字串** | **HTTP/2 200、46,881 bytes**；設定 `ASP.NET_SessionId` 與 `valid_check` cookie。頁面檢視發現 **2 處 captcha／recaptcha 標記，且無可擷取之 `__VIEWSTATE` token** —— 查詢表單為 CAPTCHA 阻擋，無法以程式驅動。**CAPTCHA 不予破解** | 由人以瀏覽器操作同一網址 —— 該挑戰是反機器人閘門，不是付費牆 |
| **Texas SOS UCC** — [sos.state.tx.us/ucc/index.shtml](https://www.sos.state.tx.us/ucc/index.shtml)。方法：HTTPS GET | **無** | **HTTP 200。** 頁面文字含：「Technical Notice: Various applications including SOSDirect and SOSUpload are experiencing intermittent issues and are actively being addressed」與「Need an SOS Portal account? SOS Portal is the hub for all our new agency online services. **You will need an SOS Portal account to access the SOS UCC Portal.**」需付費 SOSDirect／SOS Portal 帳號 | 付費 SOSDirect 帳號。**但請注意這本來就是錯的管轄地 —— 設立州別是德拉瓦州** |
| **Texas SOSDirect 登入** — [direct.sos.state.tx.us/acct/acct-login.asp](https://direct.sos.state.tx.us/acct/acct-login.asp)。方法：HTTPS GET | **無 — 未執行任何檢索** | **HTTP/2 200**，回傳登入頁，需帳號密碼 | 同上。未續行 —— 代為建立帳號與輸入密碼不在可執行範圍內 |
| **Texas Comptroller 特許稅納稅實體查詢**（作為免費替代，用以測試是否有任何 Sharon AI 實體在德州登記營業） — [mycpa.cpa.state.tx.us/coa/](https://mycpa.cpa.state.tx.us/coa/)，302 導向 [comptroller.texas.gov/taxes/franchise/account-status/search](https://comptroller.texas.gov/taxes/franchise/account-status/search) | **`Sharon AI`**、**`SharonAI`**、**`Texas Critical Data Centers`** | 導向目標為 **JavaScript 渲染的應用程式**，對三個字串 **均回傳零筆相符文字** —— 沒有結果列，**也沒有明確的「no records found」訊息**。以 POST 送至舊端點 `https://mycpa.cpa.state.tx.us/coa/coaSearchBtn`（`searchType=namesearch&taxpayerName=Sharon+AI`）回傳 **空 body**。**此為不確定，不是負面發現** | 由人以瀏覽器操作，或接受德州本非相關管轄地 |
| **澳洲 PPSR（Personal Property Securities Register）** — **本次未嘗試** | **無** | **未檢索。** 在此明列，以免此一遺漏被淹沒 | **這是本檔中價值最高的未執行檢索。** 對 **SharonAI Pty Ltd** 與 **Distributed Storage Solutions Pty Ltd** 執行 —— 真正的擔保權益幾乎可以確定在這裡 |

### 8.4 這份紀錄的意涵

以下為推論，非目視證據。每一列自陳信心水準。

| 觀察 | 意涵 | 信心 | 銷售後果 |
|---|---|---|---|
| **讀到的 UCC 檔案數為零，而德拉瓦州才是正確的登記機關。** 德拉瓦州 UCC 路徑 404，實體查詢為 CAPTCHA 阻擋。德州 —— 也就是原始名單暗示的管轄地 —— **並非本集團任何實體的設立州別** | **留置權狀態是未知，不是乾淨。** 不能從查無結果推出任何關於擔保債務的結論。任何「Sharon AI 沒有留置權」的說法都沒有依據 | **高** — 直接觀察：UCC 路徑 HTTP/2 404、實體查詢 2 處 captcha 標記且無 `__VIEWSTATE` | **絕不得讓任何人以「查無 UCC 檔案」去建構徵信或通路核准的論點。** 在任何條件決策前，對全部五個實體執行付費德拉瓦州查詢 |
| **SEC 申報文件中記載的資金結構，使傳統 UCC-1 設備留置權的重要性，低於典型自有資金 GPU 業者。** 已揭露四種機制，**沒有一種是傳統的擔保設備貸款** | 見下方四列 | **高** — 四種機制皆直接引自申報文件 | 這改變了整個徵信問題的形狀：限制來自 **indenture 條款與服務合約結構**，不是留置權順位 |
| **(1) 股權與無擔保可轉債。** $900M 股權（2026 年 6 月）、**$350M 6.00% 到期 2031 年可轉換優先公司債**（2026 年 5 月）、**4.75% 可轉債** 發行（2026 年 6 月）。2026 年 6 月之公司債明載「fully and unconditionally guaranteed on a **SENIOR UNSECURED** basis by the Subsidiary Guarantors」 | **無擔保就不會有 UCC-1 附著。** 限制來自 **indenture 的消極條款**，不是擔保權益 | **高** — 引自 [Form 8-K 2026-06-25](https://www.sec.gov/Archives/edgar/data/2068385/000149315226030158/form8-k.htm) | **去讀 2026 年 6 月的 Indenture（Exhibit 4.2）。** 其留置權與可承作債務條款界定了 **他們在合約上還能新增多少擔保設備融資** —— 也因此決定了「資本支出加融資」的提案在結構上是否可行 |
| **(2) 廠商融資式消耗。** **Lenovo Global Financial Services 的 EaaS/DaaS** 安排，加上 **60 個月受管服務 Statement of Work，約 50% 於期初支付** | 在 equipment-as-a-service 結構下，融資方通常**保留所有權**，因此曝險呈現為服務承諾，而非債務人端的擔保權益。若 Lenovo GFS 確有辦理登記，**預期會出現以 Lenovo 法人為 secured party 的預防性登記** | **中** — 結構為引用；所有權／登記機制屬商業推論 | **Supermicro 的資本支出提案，是在跟一個營運費用結構競爭。** 這比同規格報價的比較困難得多，而且必須在提案中被承認，而不是繞過去 |
| **(3) 預付款。** 對 **WWT Australia 預付 2.562 億美元**、對 **Lenovo GFS 預付 3,310 萬美元** | **預先付現金是「以資產借款」的反面，完全不產生留置權。** 但它確實製造出極大的、集中在單一整合商身上的 **交易對手與預付款風險** | **高** — 兩個數字皆引自 [Form 10-Q Note 10](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) | **這就是切入點。** 兩億五千萬美元躺在單一整合商的預付款裡，正是新任財務長會重新檢視的那種曝險。把它量化，並在 2026 年 10 月至 11 月以此開場 |
| **(4) NVIDIA 分潤與信用支持。** 六年期合作以「a revenue-sharing and credit-support model」對齊經濟利益，公司自稱為「a capital-efficient path to scale」 | NVIDIA 對 **OEM 短名單具經濟與實務影響力**。這不是純粹開放的競標 | **中高** — 結構為引用；影響力結論屬推論 | **要及早確認第二條 OEM 通路在合約上是否被允許。** 若不允許，無論轄區如何，本案都應降低優先序 |
| **交易對手壓倒性地都是澳洲法人** —— WWT Australia Pty Ltd、Lenovo GFS Australia & New Zealand Pty Limited、Dicker Data Limited、SharonAI Pty Ltd | **有意義的擔保權益會登記在澳洲 PPSR，而不是任何美國 UCC 索引。** 就算美國檢索成功也找不到 | **高** — 每一個交易對手名稱都引自申報文件 | **PPSR 檢索才是產出更高的下一步，而本次並未執行。** 在任何徵信對話之前，對 SharonAI Pty Ltd 與 Distributed Storage Solutions Pty Ltd 執行 |

### 8.5 本節 GAP — 直說

- **UCC 是未查證，不是乾淨。** 零筆檔案取得。德拉瓦州 UCC 路徑回 HTTP/2 404；德拉瓦州實體查詢為 CAPTCHA 阻擋；德州 SOSDirect 與 SOS UCC Portal 需付費帳號。**8.2 節之所以是空的，是因為什麼都沒看到 —— 絕不得回報為「無融資」。**
- **從未對任何 UCC 系統實際送出過債務人名稱查詢。** 每一次嘗試都在認證或路由層就失敗，根本沒有觸及查詢欄位。8.2 節列出的五個債務人名稱，是*原本打算送出*的字串，**不是曾對任何登記簿執行過的字串。**
- **澳洲 PPSR 未檢索** —— 本檔中價值最高的單一缺口。
- **2026 年 6 月 Indenture（Exhibit 4.2）未閱讀。** 其留置權與可承作債務條款直接決定資本支出型提案在結構上是否可行。
- **德拉瓦州註冊代理人、設立人與年報簽署人未取得**（同一 CAPTCHA 閘門）。
- **Texas Comptroller 的結果是不確定，不是負面。** 沒有結果列，也沒有明確的「no records found」訊息。**不得回報為「Sharon AI 未在德州登記」。**

---

## 9. 成本天花板

一個已部署節點對這家業者能值多少錢，以及同一台機器重建起來長什麼樣。**請先讀 9.1 —— 這個天花板是以假設為基礎的估計，不是查證事實，而且價格錨點已約 20 個月未更新。**

### 9.1 假設 — 先讀這裡，這些是假設而不是發現

以下每一項都是為本分析所選定的假設。**沒有一項來自 Sharon AI，也沒有一項可以當作對方的經濟數據呈現給客戶。**

1. **實現費率 $1.50–$2.50 /GPU/hr**，錨定於 **2024 年 12 月的 $2.50 牌價**。官網寫「Contact us for volume and term discount」，且公司現以 take-or-pay 合約銷售，故假設折扣區間為牌價的 0–40%。
2. **付費使用率 60–80%。**
3. **營運成本佔比為營收的 35–45%**，涵蓋主機代管、電力、冷卻、網路與支援，**但不含硬體**。這正是 10-Q 自己列舉的成本科目：「data center costs — comprising colocation facility fees, internet connectivity, and power consumption」。
4. **每節點 8 顆 GPU**，依公司自家公布規格。
5. **每年 8,760 小時。**
6. **回收期僅以硬體取得成本計算** —— 不含整合、備品與運費。
7. **不計殘值。**
8. **不計融資成本** —— 這個方向偏保守得不利於我方論點，因為公司實際上是透過 Lenovo EaaS/DaaS 結構消耗硬體，其中內含財務費用。

**兩項健康警告。** 第一，**價格錨點已約 20 個月未更新** —— 公開定價於 2025 年間撤下，現行商業模式是客製化的巨額合約（$373M、$950M、$1.32 bn），因此真實實現費率未知。第二，[10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) 明白示警「rising operational costs, particularly for power, colocation services, and network infrastructure, are increasing the cost base for GPU cloud providers」—— 這會把營運成本佔比推向區間**上緣**，把天花板壓向**下緣**。

### 9.2 由租金反推的天花板 — 單一 8-GPU H100 NVL 節點

| 項目 | 低情境 | 高情境 | 計算式 |
|---|---|---|---|
| **滿載牌價毛收（僅供參照 —— 沒有人真的收得到）** | — | **$175,200／節點／年** | 8 × $2.50 × 8,760 |
| **假設之每節點年度毛收** | **$63,072** | **$140,160** | 低：8 × $1.50 × 8,760 × 0.60 · 高：8 × $2.50 × 8,760 × 0.80 |
| **減：假設營運成本佔比（低情境 45%／高情境 35%）** | **−$28,382** | **−$49,056** | 主機代管費、電力、冷卻、網路連線、支援 |
| **每年可用於攤付硬體成本之金額** | **$34,690** | **$91,104** | |
| **硬體成本天花板 @ 12 個月回收** | **$34,690** | **$91,104** | |
| **硬體成本天花板 @ 18 個月回收** | **$52,035** | **$136,656** | |
| **硬體成本天花板 @ 24 個月回收** | **$69,380** | **$182,208** | |

**請以 24 個月那一列作為實際商業天花板**，因為此處的 neocloud 合約期為 **五年**，NEXTDC 租期為 **120 個月**。因此一個 8-GPU H100 NVL 等級節點，可辯護的工作區間約為 **硬體成本 $69k–$182k**；考量 10-Q 自己的成本上升警語，取該區間的下半部作為規劃假設較為安全。

### 9.3 BOM 重建 — 結構已驗證，市價未取得

**旗艦節點由公司自行逐字公布**（[sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/)）：

| 元件 | 已公布規格 | Supermicro 對應 |
|---|---|---|
| GPU | **8 × H100 NVL (94GB)** 含 NVLink Bridge (188GB) | 8 × PCIe 雙寬 GPU 插槽 |
| CPU | **2 × AMD EPYC 32C 3.25GHz** —— 頁面寫成「3954」，幾可確定為 **EPYC 9354** | 雙 AMD EPYC 9004/9005，Socket SP5 |
| 記憶體 | **24 × 32GB TruDDR5 4800MHz** ＝ 共 768GB。**「TruDDR5」是 Lenovo 專屬記憶體品牌** | 24 條 DIMM 插槽 |
| 儲存（資料） | **6 × 7.68TB U.2 NVMe**（約 46TB 可用） | NVMe 前置槽位 |
| 儲存（系統） | **2 × 1.92TB M.2 NVMe**（3.84TB） | M.2 |
| **平台辨識** | **Lenovo ThinkSystem PCIe GPU 節點，SR675 V3 等級** | **直接對應：Supermicro AS-4125GS-TNRT**（4U、8× PCIe 雙寬 GPU、雙 AMD EPYC 9004/9005、24 條 DIMM 插槽、NVMe 前置槽位）—— 在 GPU 數量、CPU 腳位型式、DIMM 數與硬碟拓撲上是真正的同級對比，因此可做乾淨的並排比較 |

第二種已公布節點為 **8 × L40S (48GB)**，CPU、記憶體與儲存配置其餘完全相同。對應機種：同一機殼或 **SYS-421GE-TNRT**。

> **誠實的 GAP —— BOM 比較在結構上完整，在財務上不完整。** 本次並未取得 H100 NVL 卡、EPYC 9354 CPU、DDR5 RDIMM、U.2／M.2 NVMe 或 Supermicro 機殼的市價，**且一個都沒有自行編造。**

**要補完，順序很重要：**

1. **先報價八張 H100 NVL 卡。** 它們大約佔節點成本的 **80–85%**，因此幾乎單靠它們就決定了比較結果。
2. 再報 **機殼＋CPU＋記憶體＋儲存** 的其餘部分，與配置好的 **AS-4125GS-TNRT** 報價對比。
3. **注意結構性限制：** GPU 卡在成本上大致與廠牌無關，因此**可爭取的價差被壓縮在節點價值的約 15–20%，也就是機殼、主機板、供電、散熱與整合的部分。** 這正是要用來對打「已經把整個堆疊以服務方式融資掉」的既有廠商的論點 —— 也就是為什麼第 13 節主張以排程與分散供應為主軸，而不是價格。

### 9.4 本節 GAP — 直說

- **由租金反推的天花板，建立在 2024 年 12 月、已約 20 個月未更新的價格錨點上。** 公開定價於 2025 年間撤下，現行不存在任何價目表。
- **9.1 的八項假設全部是為本分析所選。** 沒有一項是公司揭露。
- **未取得任何元件市價。** BOM 的每一列都是規格，不是成本。
- **10-Q 自己的成本上升語句，支持營運成本佔比落在假設區間上緣**，那會把天花板壓向 $69k 而不是 $182k。

---

## 10. 客戶與網路

### 具名客戶

**沒有。10-Q、S-1、DEF 14A 與官網中，具名終端客戶為零。** 兩筆巨額合約都**只以類別描述**。這是硬性 GAP，不是研究疏漏。

| 關係 | 等級 | 來源實際說了什麼 |
|---|---|---|
| **未具名之全球人工智慧實驗室（AI lab）** | **合約已確認，交易對手未具名** | 五年期雲端運算服務合約，合約總值 **約 US$1.32 billion**，2026-07-16 公告。10-Q 將相關安排描述為「a five-year cloud computing service agreement with a global artificial intelligence (AI) platform with an aggregate contract value of **approximately $373 million**」，以後續事項揭露，營收自 **2027 年第一季** 起算。初期部署預計使用 **2,048 顆 NVIDIA Blackwell Ultra B300 GPU**，架於 **紐西蘭** 基礎設施。**客戶名稱未揭露**（[ex99-1](https://www.sec.gov/Archives/edgar/data/0002068385/000149315226033457/ex99-1.htm)） |
| **未具名之全球科技公司（在亞太具重要據點）** | **合約已確認，交易對手未具名** | [Form 10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) Key Corporate Milestones 原文：「On May 13, 2026, the Company entered into an additional customer contract with a global technology company with major Asia-pacific presence with an aggregate total contract value of **approximately $950 million**.」**客戶名稱未揭露** |
| **目標客群** | **由公司自身定位推得，非具名 logo** | [Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) 載明公司為「enterprise, government and research organizations」提供「sovereign, low-latency access to advanced accelerated computing hardware」，目標為「AI startups, enterprises, and university researchers」與「research, government, and enterprise customers requiring GPU resources for LLM training, fine-tuning, and real-time inference」。文中引用 **NEXTDC 的 DTA（澳洲聯邦政府 Digital Transformation Agency）認證** 作為承載主權政府工作負載之基礎。NVIDIA 的「consumption desk」會把合格客戶轉介給本公司 |
| **客戶集中度** | **未揭露 — 而且實質上是完全集中** | **10-Q 中不存在客戶集中度揭露表。** 以「customer concentration」「one customer」「major customer」與營收百分比等語句搜尋，皆無結果。以上半年營收 **$2.2M** 對比已公告的 **$2.27 bn** 合約總值，集中度實質上是百分之百，但**未揭露** |

### 網路 — AS142588

- **登記：** **AS142588**，as-name **DSSL-AS-AP**，descr「Sharon AI」，國別 **AU**，org-handle ORG-SA242-AP。登記於 **APNIC，非 ARIN**。最後異動 **2024-11-25**（[APNIC RDAP](https://rdap.apnic.net/autnum/142588)）。
- **不存在 ARIN 組織紀錄。** 以 `Sharon*` 查詢僅回傳不相關實體。**「Sharon Networks, LLC」（AS396856、sharon.io、Wilmington DE）是另一家完全無關的公司，不得與本標的混淆**（[whois.arin.net](https://whois.arin.net/rest/orgs;name=Sharon*)）。
- **位址空間：** PeeringDB 記載 **6 個 IPv4 前綴與 1 個 IPv6 前綴**。**GAP —— 未自 APNIC 列舉出具體 CIDR 區塊。**
- **容量：** PeeringDB 自報 **20–50 Gbps**、流量比 **Mostly Inbound**、範圍 Global、啟用 IPv6、啟用 unicast、未啟用 multicast。另公司自行宣稱其 NEXTDC M3 已安裝容量採 **bonded 200G Ethernet**，叢集內採 **NVIDIA Quantum-2 InfiniBand**，並在 Cisco 合作下採用 Cisco Nexus HyperFabric AI 與 NVIDIA Spectrum-X-aligned 網路。**請注意 20–50 Gbps 的 PeeringDB 自我分級，與逾 62,000 顆 GPU 的規劃之間的落差 —— 公開網際網路傳輸顯然不是主要資料路徑；這些是私有／簽約的客戶部署。**
- **對接政策：** **開放** —— 任何據點皆不強制、不需簽約、啟用 route-server 對接（`allow_ixp_update` 為 true）。
- **IXP 連線 —— 兩處，皆在墨爾本：** **MegaIX Melbourne**（ixlan 779），103.26.71.53 與 2001:dea:0:30::35，**10 Gbps**，route-server peer，運作中，2026-02-02 更新 · **EdgeIX Melbourne Main**（ixlan 2762），202.77.90.71 與 2001:df0:680:6::47，**10 Gbps**，route-server peer，運作中，2026-07-30 更新。
- **機房據點 —— 兩處，皆為 NEXTDC：** **NEXTDC S3**（Artarmon, AU，fac_id 12094，2026-07-29 新增）與 **NEXTDC M3**（West Footscray, AU，fac_id 12096，2026-02-02 新增）。
- **IRR as-set：** 無紀錄。**未公布 looking glass。**
- **完全沒有美國網路存在 —— 每一個 IXP、每一個機房都在澳洲。**

來源：[PeeringDB net 37929](https://www.peeringdb.com/api/net?org_id=39812&depth=2) · [APNIC RDAP autnum 142588](https://rdap.apnic.net/autnum/142588) · [ARIN 組織查詢](https://whois.arin.net/rest/orgs;name=Sharon*)

---

## 11. 政治與公開紀錄

僅採公開紀錄。每一列均加註標籤。僅列具名主要人員。

| 對象 | 發現 | 標籤 |
|---|---|---|
| **所有具名主要人員** | **未取得任何 FEC 紀錄 —— 這是入口失敗，不是查無結果。** [OpenFEC API](https://api.open.fec.gov/v1/schedules/schedule_a/) 對 MANNING JAMES、WOODWARD PETER、ADAMS BENJAMIN、BROADFOOT、HUGHES-JONES、LEECE 與 MONS DANIEL 的每一次查詢，**在兩次獨立嘗試中，皆以 DEMO_KEY 回傳 `OVER_RATE_LIMIT`**。[fec.gov 公開查詢介面](https://www.fec.gov/data/receipts/individual-contributions/) 為 JavaScript 渲染，無可解析結果列。**對任何個人明確不記載為「查無紀錄」，因為根本沒有任何一次檢索完成。** 要補上這一塊需申請正式 FEC API key | **UNVERIFIED — API 額度受限** |
| **James Manning、Tim Broadfoot、Andrew Leece、Daniel Mons、Nicholas Hughes-Jones、Tim Flahvin、Andrew Penn、Alexander Andrew Kelton、Anuj Goel** | 常居澳洲並透過 **SharonAI Pty Ltd** 聘僱。非美國永久居民之外國人，依 **52 U.S.C. 30121** 禁止對美國選舉相關事項捐輸，因此對這一群人而言查無為法律上的預期結果。**僅作法律脈絡陳述 —— 不是已查證之檢索結果**（[DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm)） | **脈絡／未查證** |
| **Peter Woodward 與 Benjamin Adams** | 兩位明確 **常居美國** 的董事，也是具名主要人員中唯二存在實質 FEC 紀錄可能性的人。Woodward 是 MHW Capital Management LLC 創辦人，且曾任白宮 **Council of Economic Advisors** 經濟學家 —— 此背景提高政治捐輸的先驗機率。Adams 是 **The Western Union Company (NYSE: WU)** 的 EVP、Chief Legal Officer 兼 Corporate Secretary，此職務常涉企業 PAC 事務。**兩人都應以正式 FEC API key 人工重跑；這是產出最高的追查標的** | **優先追查 — 未查證** |
| **Andrew Penn AO** | 屬澳洲公共政策人物，而非美國政治捐款人。曾 **主持澳洲 2020 與 2023 年 National Cyber Security Strategies 之專家諮詢委員會**；於 2023 年澳洲國慶授勳中獲頒 **Officer of the Order of Australia (AO)**；並任維多利亞州政府觀光機構 **Visit Victoria** 主席。這與 **澳洲政府部門的接觸管道** 相關，與美國政治曝險無關（[DEF 14A](https://www.sec.gov/Archives/edgar/data/2068385/000149315226032957/formdef14a.htm)） | **外國公部門連結 — 已由 DEF 14A 查證** |
| **公司層級 — 政府曝險** | 商業策略在實質上依賴 **主權與政府工作負載**。NEXTDC 的機房具澳洲聯邦政府 **Digital Transformation Agency (DTA)「Certified Strategic」** 資格，S-1 引為承載主權政府工作負載之基礎，公司並自我行銷為「Australia's leading sovereign AI infrastructure provider」。**政府曝險屬澳洲，非美國**（[Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm)） | **外國政府市場曝險** |
| **訴訟 — 相鄰，非針對本公司** | 一件聯邦證券集體訴訟 ***Annonio v. New Era Energy & Digital, Inc.***，案號 **7:26-cv-00120**，於 **2026-04-01** 向 **美國德州西區聯邦地方法院** 提起，承審法官 **Walter David Counts III**，案由 15:78m(a) Securities Exchange Act，訴訟性質 850 Securities/Commodities。**被告是 New Era Energy & Digital —— Sharon AI 的前 TCDC 50/50 合資夥伴，也是其 TCDC 股權的買方 —— 不是 Sharon AI。** Sharon AI 出現在案卷文字中，但**未被列為被告**。以 CourtListener 檢索「SharonAI」回傳 **零筆結果**。**未發現任何針對 Sharon AI 本身的訴訟**（[CourtListener 案卷](https://www.courtlistener.com/docket/73130742/annonio-v-new-era-energy-digital-inc/)） | **相鄰訴訟 — 已查證** |

**整體判讀：** 在美國政治與公共政策這條軸線上，本公司**實質上沒有已查證的足跡，而且本次研究也無法在任一方向建立結論**。其真正的公部門曝險在**澳洲**。這裡沒有美國政治面的切入點，也沒有能被建立起來的美國政治風險 —— 但 FEC 這條線是**未查證，不是乾淨**，Woodward 與 Adams 仍屬未結。

---

## 12. 公開聯絡管道

僅採公開來源。**本節不列任何個人手機號碼與私人住址，本次也未去尋找。** 凡無已公開管道者，皆標示 GAP。

| 管道 | 內容 | 來源 |
|---|---|---|
| **主要營業處所（郵寄）** | **745 Fifth Avenue, Suite 500, New York, NY 10151, USA** | [EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json) |
| **申報人電話（SEC 封面頁）** | **(347) 212-5075** | [Form 8-K 2026-07-24](https://www.sec.gov/Archives/edgar/data/2068385/000149315226034569/form8-k.htm) |
| EDGAR 申報人電話（Roth／Newport Beach 沿用之舊號） | 949-720-7133 | [EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json) |
| **網路／技術角色信箱 —— 現存最好的技術管道**（APNIC tech-c，SNA102-AP「SharonAI Network Administrator」） | **networking@sharonai.com** | [APNIC RDAP](https://rdap.apnic.net/autnum/142588) |
| 支援角色信箱（APNIC admin-c，SS4419-AP「SharonAI Support」） | **support@sharonai.com** | [APNIC RDAP](https://rdap.apnic.net/autnum/142588) |
| 濫用檢舉信箱（APNIC IRT-DSSL-AU，2026-06-09 完成驗證） | **abuse@sharonai.com** | [APNIC RDAP](https://rdap.apnic.net/autnum/142588) |
| **澳洲營運電話**（APNIC 登記人 ORG-SA242-AP） | **+61 2 8201 0063** | [APNIC RDAP](https://rdap.apnic.net/autnum/142588) |
| **澳洲營運地址**（APNIC 登記人與 IRT） | **303/44 Miller Street, North Sydney NSW 2060, Australia** | [APNIC RDAP](https://rdap.apnic.net/autnum/142588) |
| 客戶入口 | **portal.sharonai.cloud**（舊：billing.sharonai.com/login） | [sharonai.com](https://sharonai.com) |
| **徵才／招募**（可看出公司實際在哪裡運作） | [sharonai.com/careers/](https://sharonai.com/careers/) 與 [sharonai.com/hiring-process/](https://sharonai.com/hiring-process/)。地點篩選含 **「Austin, Texas」** 與 **「Texas, US」**；LinkedIn 有一則 **Sharon AI, Inc. 於 Austin, TX 的 Technical Accountant** 職缺。已擷取之在招職缺壓倒性集中於 **雪梨、墨爾本、澳洲、紐西蘭奧克蘭與新加坡** —— Senior Sales Engineer（墨爾本／雪梨）、Technical Account Manager（雪梨與新加坡）、Network Engineer、Senior Data & Storage Engineer、GRC Analyst、Data Centre Operations Manager、VP Marketing APJ。**GAP：未公開任何具名招募主管或招募人員** | [sharonai.com/careers/](https://sharonai.com/careers/) |
| 網域註冊（隱私遮蔽） | **sharonai.com** —— 2023-05-31 建立、2025-04-22 異動、2027-05-31 到期。註冊商 **Synergy Wholesale Accreditations Pty Ltd**（澳洲）。登記人名稱：**「Domain Privacy」**，PO Box 119, Beaconsfield, VIC 3807, Australia。名稱伺服器 ARCHER.NS.CLOUDFLARE.COM 與 ARIELLA.NS.CLOUDFLARE.COM。狀態 `clientTransferProhibited`。**未曝露任何具名自然人** | WHOIS sharonai.com |
| 投資人關係／市場代碼 | **Nasdaq: SHAZ**（Class A Ordinary Common Stock，面額 $0.0001）與 **SHAZW**（認股權證）。**CIK 0002068385**。Commission File **001-43129**。IRS EIN **41-2349750**。Emerging growth company | [EDGAR submissions API](https://data.sec.gov/submissions/CIK0002068385.json) |
| **直撥或具名個人聯絡方式** | **GAP —— 十三位具名主要人員全部沒有公開直撥。** 只有申報人電話與三個角色信箱 | — |

---

## 13. Supermicro 銷售切入點

### 分類：**轄區錯置的公司殼 → 轉交 APAC／澳洲承接。不是可行的 T1 美國機會。**

**先給誠實的判斷。** CRM 乾淨、可註冊這件事會誤導人。可註冊的美國法人是 **一家德拉瓦州控股殼公司，登記地址在紐約**；採購主體是澳洲的 **SharonAI Pty Ltd**；整支機隊在 **NEXTDC 墨爾本／雪梨，加上 GreenSquareDC 與紐西蘭**；PeeringDB 上每一個 IXP 與機房都在澳洲；而 **當初大概是用來支撐 T1 歸屬的德州資料中心合資案，已於 2026-01-13 出售**。以一個**任何來源都查不到的休士頓地址**去註冊 T1 lead，就是轄區錯置；而且 $100M 門檻會由一個美國團隊既服務不到、也成交不了的機會來達成。

> **不要把五個 CRM 名額之一花在把它登錄為 T1 lead。轉交 APAC／澳洲承接 —— 並依既有作法，不要僅憑總部地點就把它結案。交給實際發生採購的那個轄區承接，維持可復活狀態，不要關掉。**

### 若由正確的轄區承接，切入點在哪裡

**替換戰，而且很硬。這不是新建案。**

- **運算平台上 Lenovo 是既有廠商，已確認。** 已公布節點規格帶著 **「TruDDR5」**（Lenovo 專屬記憶體品牌），另有一份 **60 個月受管服務 SOW，約 50% 於期初支付**，加上 **$33.1M 的 EaaS/DaaS 預付款**。
- **WWT Australia 以整合商身分持有 2.562 億美元設備預付款。**
- **Cisco 是結構性綁定，不只是商業合作。** 與 Cisco 具獨家技術夥伴關係的 Digital Alpha 投資最高 $200M 並成為股東，旗艦 B300 叢集掛的招牌是 **「Australia's first Cisco Secure AI Factory」**。
- **NVIDIA 透過 NCP 資格、DSX 參考設計、分潤加信用支持結構，實質掌控 OEM 短名單。**

**因此有四方各自有商業誘因維持現有 OEM 組合。**

### 唯一真實的切入點

這家公司**把硬體當作融資服務在消耗**，同時**對單一整合商預付 2.562 億美元**，背著 **約 40 億美元的已承諾採購**，卻只有 **70 人**團隊。這是高度集中的供應鏈與預付款風險，壓在一張剛募到 9 億美元的資產負債表上。**新任財務長 Anuj Goel 於 2026-08-24 上任，並將承接這份風險。**

可信的訴求是 **針對 2027 年 4 月至 8 月 NEXTDC 五階段上線的供應來源分散與交期確定性** —— **不是價格，也不是規格**。Supermicro 實際可主張的空間，在 **節點價值中非 GPU 卡的那約 15–20%**，加上 **在 Lenovo 與 Cisco 產能可能吃緊的規模下，GB300 NVL72 的交期與機櫃整合能量**。

### 首次接觸的鑑定問題

對 **技術長 Daniel Mons**，或經由 **Peter Woodward**：

> **「For the April-to-August 2027 NEXTDC phases, is your GB300 rack-scale allocation single-sourced through WWT and Lenovo, or are you holding a second OEM lane open for schedule protection?」**

這是**診斷式而非推銷式**的問法 —— 它會逼出「在 NVIDIA 分潤與信用支持的安排下，第二供應來源在合約上是否被允許」這個真正的閘門問題。

有用的第二個探問：

> **「Does the Lenovo EaaS structure let you take title on any tranche, or is all capacity consumption-based?」**

**若答案是全部都以服務方式消耗，資本支出型提案就無法競爭，本案應降低優先序。**

### Rule 8 — 通路注意事項（任何註冊動作前必讀）

**不得以終端客戶名義註冊 Sharon AI。** 實際交易對象不會是 Sharon AI 本身。硬體流經：

- **WWT Australia Pty Ltd** —— 整合商，**已預付 2.562 億美元**
- **Lenovo Global Financial Services (Australia & New Zealand) Pty Limited** —— 融資方
- **Dicker Data Limited** —— 代理商（VAST 軟體，已預付 $13,368 千美元）

若把一個已被代理商或整合商掌握的終端客戶登記為自己的案子，**會造成通路衝突，並可能與既有的夥伴端註冊撞號。** 在任何註冊動作**之前**，先確認澳洲的通路路徑，並查核是否已有 APAC 夥伴端的宣告。

**順序 —— 不得調換：** ① 將此紀錄改列為 APAC／澳洲轄區，並在工作名單上更正休士頓與「私有持股」兩項前提 → ② 依 Rule 8 釐清通路／代理商歸屬，含任何既有夥伴端宣告 → ③ 閱讀 2026 年 6 月 Indenture（Exhibit 4.2）並執行澳洲 PPSR 查詢 → ④ 之後才接觸，且只問上述診斷問題，時間押在 2026 年 10 月至 11 月、新任財務長已把帳看完之後。

---

## 14. 查證附錄

### 14.1 單一來源或脆弱的說法 — 引用前務必重新查證

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| **「Supermicro 是 Sharon AI 的 OEM」** | **[Form S-1](https://www.sec.gov/Archives/edgar/data/2068385/000149315226035629/forms-1.htm) 中描述 NVIDIA NCP 效益的一句話**：「OEM Relationships: Facilitated engagement with OEMs such as Cisco, Lenovo, Dell, and Super Micro」 | **那是 NVIDIA 促成對一組 OEM 名單的接觸，不是採購關係。** 沒有 PO、沒有預付款、沒有承諾、沒有合約，任何節點規格中也沒有 Supermicro 硬體。**這是業務在本案最可能犯的一個錯。** 等級：**旁證** |
| **Lenovo 平台辨識** | [sharonai.com/ai-cloud/](https://sharonai.com/ai-cloud/) 上的 **「TruDDR5」** 字串，加上四項來自 SEC 的 Lenovo 關係 | Lenovo *關係* 已由申報文件 **確認**。但具體到 *ThinkSystem SR675 V3 等級* 這件事，是**由品牌線索推得**，不是已揭露的型號。不得把型號當事實陳述 |
| **Equinix SYD3／SYD5 據點** | 僅 [sharonai.com](https://sharonai.com) 首頁 | **10-Q 與 S-1 皆未佐證**，兩份文件都說 NEXTDC 承載「substantially all」GPU 基礎設施。視為舊有或小規模的行銷文字 |
| **EPYC 9354 CPU 辨識** | 公司頁面把料號寫成 **「3954」** | 幾可確定是 EPYC 9354 的顯示錯誤，但**已公布字串並不對應任何真實料號。** 不得把「9354」當作已揭露規格引用 |
| **Michael Schubert（前執行長）** | 所擷取之 DEF 14A 章節僅顯示 **「Mr. Schubert」** | **名（given name）未經逐字查證。** 不得使用其名 |
| **$373M 與 $1.32 bn 兩個 AI lab 數字** | [ex99-1 2026-07-16](https://www.sec.gov/Archives/edgar/data/0002068385/000149315226033457/ex99-1.htm) 為約 US$1.32 bn；[10-Q](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) 後續事項附註為約 $373M | **兩個數字都是公司揭露，且本檔未予和解。** 要引用就兩個都引、各附來源，否則兩個都不要引 |
| **Texas Comptroller「查無」** | JS 渲染應用程式回傳零筆相符文字，且**無明確的「no records found」訊息** | **屬不確定，不是負面發現。** 不得回報為「Sharon AI 未在德州登記」 |

### 14.2 並列呈現、未予和解的衝突

**總部位置**

| 來源 | 位置 |
|---|---|
| SEC 封面頁、[EDGAR 營業地址](https://data.sec.gov/submissions/CIK0002068385.json) | **745 Fifth Avenue, Suite 500, New York, NY 10151** |
| [APNIC 登記人與 IRT](https://rdap.apnic.net/autnum/142588) | **303/44 Miller Street, North Sydney NSW 2060, Australia** |
| 原始工作名單 | **德州休士頓** |

**處理方式：** 紐約地址是登記在案的主要營業處所，北雪梨地址是登記在案的營運地址。**休士頓之說無任何來源支持，視為工作名單之誤。** 查到的唯一德州據點是 Austin。

**AI lab 合約金額**

| 來源 | 數字 |
|---|---|
| [ex99-1，2026-07-16](https://www.sec.gov/Archives/edgar/data/0002068385/000149315226033457/ex99-1.htm) | **約 US$1.32 billion**，五年 |
| [Form 10-Q 後續事項附註](https://www.sec.gov/Archives/edgar/data/2068385/000149315226036377/form10-q.htm) | **約 $373 million**，五年，「global artificial intelligence (AI) platform」 |

**未和解。** 兩者皆為公司揭露，可能描述同一關係下的不同範圍。

**選擇權鏈資料界線（僅在需要引用市場壓力脈絡時相關）**

| 有 | 沒有 |
|---|---|
| open interest、volume、IV、delta 類欄位 | **直接的 Change in Open Interest** —— 因此只能計算 open-interest **推估** 壓力；NSE 式的 call／put exit 主張仍被封鎖 |

### 14.3 未結缺口

1. **澳洲 PPSR —— 未檢索。本檔中價值最高的缺口。** 真正的擔保權益幾乎可以確定登記在這裡，對象為 **SharonAI Pty Ltd** 與 **Distributed Storage Solutions Pty Ltd**，因為交易對手（WWT Australia Pty Ltd、Lenovo GFS Australia & New Zealand Pty Limited、Dicker Data Limited）全是澳洲法人。**就算美國 UCC 查詢成功，也找不到它們。**
2. **UCC-1 融資聲明 —— 取得零筆。** 德拉瓦州（正確的設立州別）UCC 查詢路徑回 HTTP/2 404；德拉瓦州實體名稱查詢為 CAPTCHA 阻擋；德州 SOSDirect 與 SOS UCC Portal 需付費帳號。**判定記為 UNVERIFIED — 入口被阻擋，不是「無融資」。**
3. **FEC 個人捐輸紀錄 —— 對任何主要人員皆未查證。** OpenFEC 以 DEMO_KEY 全部回傳 `OVER_RATE_LIMIT`；fec.gov 介面為 JS 渲染。**明確不記載為「查無紀錄」。** **Peter Woodward** 與 **Benjamin Adams** —— 兩位常居美國的董事 —— 是優先重跑對象，需正式 API key。
4. **USPTO 商標資料 —— 一無所獲。** 無註冊號、序號、宣誓簽署人或通訊代理人。tmsearch.uspto.gov API 端點回傳 S3 `NoSuchKey`／`MethodNotAllowed`；developer.uspto.gov 導向；Justia 查詢無可解析列。**「SHARON AI」是否曾在美國註冊為商標，仍屬未知。**
5. **德拉瓦州註冊代理人、設立人與年報簽署人 —— 未取得**（CAPTCHA 阻擋）。
6. **歷史 WHOIS —— 未還原。** 現行 WHOIS 已隱私遮蔽（「Domain Privacy」，PO Box 119, Beaconsfield VIC 3807），未取得遮蔽前紀錄；whoisrequest.com/history、whoxy.com 與 securitytrails 未成功查詢，且多屬付費服務。**未還原任何創辦期登記人姓名。**
7. **LinkedIn —— 對任何一位具名個人皆未解析。** 3.1 節每一位都是 `linkedin: GAP`。沒有 LinkedIn 連結、沒有職能別人力分布，除了那一則 Austin TX 的 Technical Accountant 職缺之外，也無法辨識任何美國本地員工。
8. **BOM 重建之市價 —— 未取得。** 節點組成已由公司自家頁面逐字驗證，Supermicro 對應機種（AS-4125GS-TNRT）也已辨識，但本次未研究任何元件價格，**且一個都沒有自行編造**。BOM 比較因此**在結構上完整、在財務上不完整**。
9. **現行 GPU 價目表 —— 公開上不存在。** 截至 2026-08-11，`/cloud-pricing/` 回傳 0 bytes，`/pricing-calculator/` 301 導向首頁。所有擷取到的價格都來自 2024 年 10 月與 12 月，已約 20 個月未更新，這**實質削弱了第 9 節由租金反推的成本天花板。**
10. **具名終端客戶 —— 一個都沒有揭露。** 兩筆巨額合約都只以類別描述，且 **10-Q 中不存在客戶集中度表。**
11. **郡級不動產與估價紀錄 —— 未檢索。** 對 Ector County 而言已大致無意義（TCDC 已於 2026-01-13 出售），對澳洲與紐西蘭的主機代管據點也不適用，因為那些是向 NEXTDC 與 GreenSquareDC 承租而非自有。
12. **Michael Schubert 的名（given name）** —— 所擷取之 DEF 14A 章節僅確認為「Mr. Schubert」。
13. **Austin, TX 的確切地址與人數** —— 徵才頁面有「Austin, Texas」與「Texas, US」地點篩選、LinkedIn 有一則 Technical Accountant 職缺，但 **未取得街道地址、辦公室規模或美國員工數。**
14. **Indenture 條款（Exhibit 4.2，2026 年 6 月）—— 未閱讀。** 這些條款界定可設定之留置權與可承作之債務，會決定 **公司在法律上還能新增多少擔保設備融資**，直接影響資本支出型提案在結構上是否可行。
15. **AS142588 之 IP 前綴** —— PeeringDB 記載 6 個 IPv4 與 1 個 IPv6 前綴，但 **未自 APNIC 列舉出具體 CIDR 區塊。**
16. **任何公開登記資料中都不存在具名的 NOC 或網路人員。** PeeringDB `poc_set` 為空，APNIC 所有聯絡窗口（SS4419-AP、SNA102-AP、IRT-DSSL-AU）都是角色帳號。**這是真實的負面發現而非研究失敗**，但也代表原本預期能由網路來源產出的「真名員工」在本案並不存在。
17. **重跑時的工具註記** —— 數個 MCP 連接器（ZoomInfo、carta、figma、atlassian、spglobal、adobe）需 OAuth 授權，在本次非互動式工作階段中無法使用。若透過 claude.ai 連接器設定授權 ZoomInfo，重跑時很可能可以補上 LinkedIn 與美國具名員工這兩塊缺口。另請注意：**WebFetch 對 sec.gov 回傳 HTTP 403**；以符合 SEC 規範之 User-Agent 發出 curl 請求則可通，本檔所有申報文件都是循此取得。
