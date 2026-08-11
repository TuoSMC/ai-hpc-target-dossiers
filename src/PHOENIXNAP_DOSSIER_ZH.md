# phoenixNAP — 銷售情報檔案
**編製對象：** Supermicro 銷售一組（美國）· 專員 US8664 Tuo Cheng · **日期：** 2026-08-11
**方法：** 以公司歷史、財務與登記資料、美國政治傾向、法案與政策立場，以及該公司與其客戶之關係為研究軸線。本公司為私有持股，證據來自各州商業登記、ARIN／PeeringDB、業者自行公布之 GPU 型錄與定價、UCC 歸檔、徵才啟事、社群論壇及 FEC 紀錄。每項事實均隨附來源與日期。GAP = 查證資料中未找到，不得憑記憶補寫。
**轄區：** 亞利桑那州鳳凰城 — West Coast South excl. CA = **T1**｜T31。一組可直接註冊。
**CRM 狀態：** 2026-08-11 於 salesleads Search（Type = All）實查為乾淨 — 無 lead、無 account、無 do-not-call。一組可註冊。

---

## 1. 結論摘要

phoenixNAP 是一家 2009 年創立、由創辦人持有的亞利桑那州裸機雲（bare-metal cloud）、主機代管與網路業者，營運 **AS12189**，總部與旗艦資料中心同址於鳳凰城 3402 E. University Drive 的 200,000 平方英尺園區，於 PeeringDB 登錄 16 個據點、橫跨五大洲，實際計費區域為六個（[ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)·[PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)）。商業上，這是一個**贏回（win-back）案，不是新開發案，也不是對陌生對手的取代案**：Supermicro 曾於 2017 年 6 月發布具名案例研究——X11 BigTwin、Simply Double 全快閃 SuperStorage、Rack Scale Design、Supermicro Server Manager，並附上總裁 **Ian McClarty** 與時任產品副總 **William Bell** 的具名引述（[Supermicro 案例研究，2017-06](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)）；ServeTheHome 在 2023 年 3 月的實機報導，也將其 Sapphire Rapids 裸機執行個體記載為 Supermicro 硬體（[ServeTheHome，2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)）。**但最近兩次平台改朝換代都被 HPE 拿走**：2023 年 8 月的 ProLiant RL300 Gen11（Ampere），以及 2025 年 4 月的 ProLiant Compute DL320 Gen12（Intel Xeon 6），兩則都由 HPE 發布，且都由 phoenixNAP 自家總裁與產品執行副總具名背書。這個客戶是溫的，而且正在流失。

全公司最可攻擊的一條線是加速器層。本次直接抓取了支撐其官方定價頁的正式產品／價格 JSON——全部 101 項產品——**整份檔案中 `gpuConfigurations` 欄位的唯一值就是「Intel Max 1100 GPU」**。三個 SKU、三種 CPU 分級、一款加速器，約於 2023 年 10 月導入，此後約 34 個月未動。**現行型錄中完全沒有任何 NVIDIA SKU，也沒有任何 AMD Instinct SKU**（[phoenixNAP 現行型錄 JSON，2026-08-10 抓取](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)）。而其自家行銷頁只敢宣稱六個計費區域中的兩個有現貨（[GPU 伺服器頁](https://phoenixnap.com/bare-metal-cloud/gpu-servers)）。他們有 AI 故事——一個具名 AI 客戶案例，加上 HPE 引用的 adtech／fintech／SLED 需求——卻只有一款逐漸老化的加速器可供支撐。這個位置 HPE 沒有拿下，任何人都沒有拿下。

時機點異常乾淨。亞利桑那州州務卿 UCC 紀錄顯示共 **20 筆歸檔**、自 2014 年起與 BMO（Harris）Bank 未曾中斷的設備與資產融資關係，且 **2025 年 7 月至 2026 年 4 月之間，新增擔保撥款的間隔中位數約 33 天**——然後在 2026-04-02 硬生生停止，四個月毫無動靜，時間正好涵蓋 RadiusDC 主機代管切割案於 2026 年 Q2 完成交割（[AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/)·[PRNewswire，2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html)）。他們用銀行債務在自己的資產負債表上買硬體——**紀錄上完全沒有 Dell Financial Services、沒有 HPEFS、沒有 Cisco Capital、沒有任何原廠融資子公司**——因此每一塊錢的單機成本，都直接落在他們自己的折舊與利息上。對這個買家而言，「每台部署成本」不是話術，而是整場對話本身。下一筆融資撥款將用來支撐一支純裸機雲機隊，而加速器層是其中最外露的一條科目。

唯一可能讓這筆生意破局的是通路。這是一個有長期歷史的回頭 Supermicro 買家，因此依 Rule 8，**必須在任何報價之前**先確認經銷商歸屬——見第 13 節。

---

## 2. 公司速覽

| 欄位 | 內容 | 證據／日期 |
|---|---|---|
| **法人名稱** | **PHOENIX NAP, LLC**（品牌書寫為 phoenixNAP；ARIN 組織名稱為 PhoenixNAP LLC，代號 **PHOEN-56**）。經 UCC 證實之關係企業／共同債務人：**SECURED SERVERS, LLC**（持有 131.153.0.0/16 位址區塊，ARIN 代號 SSL-65）·**CC PROPERTY INVESTMENTS, LLC**（不動產部門，Tempe AZ）·**PHOENIX NAP MANAGEMENT RESOURCES LLC**（自 2019 年起獨立之 BMO Harris 債務人）。另有「PHOENIXNAP」與 **ALTAY CORPORATION** 於 2022 年一筆 Express Computer Systems 歸檔中並列為共同債務人 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)·[AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/)，20 筆歸檔全文見第 8 節 |
| **設立州別** | **亞利桑那州（本州設立）。** 未查得 phoenixNAP 的德拉瓦州營運或控股實體。德拉瓦州僅以一件無關的 2016 年破產附屬程序（*Stanziale v. Phoenixnap*）之管轄地出現。**GAP：德拉瓦州登記機關本身未查詢** — 見第 14 節 | 依 UCC §9-301／§9-307，亞利桑那 LLC 之正確歸檔機關即為亞利桑那州，這也是 20 筆歸檔全在亞利桑那的原因 |
| **登記機關證據** | **在登記機關本身即遭封鎖。** 舊入口 `ecorp.azcc.gov` 已無法解析（**NXDOMAIN**）。替代入口對非瀏覽器用戶端回 **HTTP 403**；以真實瀏覽器輸入 Business Name =「PHOENIX NAP」時，會先跳出 **6 字元圖形 CAPTCHA**（「User validation required to continue」）才釋出結果。**本檔不解 CAPTCHA**，因此**未取得任何幹部、經理人、成員、法定代理人紀錄，也未取得年報簽署人與歸檔沿革**。OpenCorporates（HAProxy CAPTCHA）與 Bizapedia（security check）亦遭封鎖。**上列實體關係圖係由 UCC 紀錄與 ARIN RDAP 佐證，而非由公司登記機關佐證** | [ArizonaBusinessCenter.azcc.gov/businesssearch](https://arizonabusinesscenter.azcc.gov/businesssearch)，2026-08-10 嘗試 |
| **創立年份** | **2009** — 四個獨立錨點：Supermicro 2017 年 6 月案例研究載明「Founded in 2009, phoenixNAP…」；網域 phoenixnap.com 建立於 **2009-02-26**；鳳凰城 3402 E University Dr 廠房於 **2009 年以 USD 6.3m 購入**；ARIN autnum **AS12189 註冊於 2009-07-23** | [Supermicro 案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)·[ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)·phoenixnap.com 之 Verisign RDAP |
| **總部（實查地址）** | **3402 E. University Drive, Suite 420, Phoenix, AZ 85034-7200** — 旗艦資料中心與公司總部同一園區。歸檔上使用之次要／關係企業地址：**2353 W University Drive, Tempe, AZ 85281-7223**（CC Property Investments、Secured Servers、Phoenix NAP Management Resources） | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)（組織 PHOEN-56）·AZ SOS UCC 檔號 **2026-003-2810-7**，該筆呈現含 Suite 420 之地址形式 |
| **所有權** | **創辦人持有，無已揭露之外部股權。** New Project Media 報導公司「established in 2009 by Stephanie Cadwell and Ron Cadwell」；Infralogic 報導第三方股權背景**不明確**。**GAP：未取得股權結構、持股比例或任何所有權申報** | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/)·[ION Analytics／Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/) |
| **員工數** | **約 183 人（第三方估計 — Zippia 彙整）。** LinkedIn 與其他資料商區間不一。**誠實區間：150–300 人。** 工程團隊分布於鳳凰城／貝爾格勒／馬爾他，證據是具名 ARIN 技術聯絡人所登錄之 +381 與 +356 電話號碼 | [Zippia](https://www.zippia.com/phoenixnap-careers-1559024/revenue/)（估計值）·[ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)（地理分布之一手證據） |
| **營收** | **兩組無法調和的來源，而且低的那一組幾乎確定是錯的。** 資料商（Zippia、Kona Equity）給 **$18–25m — 視為不可靠之第三方估計**。相對地，報導其出售程序的產業媒體給出 **USD 70m 之對外行銷 EBITDA**（前一年為 USD 50m），第一輪出價 **突破 USD 1bn，倍數 14.3x EV/EBITDA**。一家 EBITDA 有 $70m 的公司不會是營收 $18m 的公司。**本檔捨棄資料商數字，且不主張任何精確營收值**；可辯護的工作假設是數億美元等級（low-to-mid hundreds of millions USD） | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/)·[ION Analytics／Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/)·[Zippia](https://www.zippia.com/phoenixnap-careers-1559024/revenue/) |
| **CRM $100M 門檻** | 依產業媒體數字，本案**很可能跨過** $100M 門檻；依資料商數字則否。**兩者不可能同時為真——在取得權威來源之前，不得將任何營收數字以事實形式登錄 CRM。** 另請注意，該 EBITDA 是**賣方行銷數字**經產業媒體轉述，不是經查核之揭露 | 併陳比較見第 14 節 |
| **ASN** | **AS12189 — PhoenixNAP LLC。** ARIN 代號 PHOEN-56，autnum 註冊於 **2009-07-23**，最後異動 **2026-04-06**。IRR AS-SET 為 **LEVEL3::AS-PHOENIXNAP**。另外，**131.153.0.0/16 登記於 SECURED SERVERS LLC**（ARIN 代號 SSL-65），技術聯絡人與 phoenixNAP 完全相同 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)·[ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **進行中的結構性事件** | **RadiusDC 收購其鳳凰城資料中心與主機代管事業** — 2026-03-12 宣布，預計 2026 年 Q2 交割。phoenixNAP 保留其自述之**約 80% 全球業務**，明確包含 Bare Metal Cloud 與網路平台，並**以承租戶身分續留該設施** | [PRNewswire，2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html)·[DataCenterDynamics](https://www.datacenterdynamics.com/en/news/radiusdc-enters-arizona-acquires-phoenixnap-facility-in-phoenix/) |
| **CRM 狀態** | **2026-08-11 實查為乾淨** — 無 lead、無 account、無 do-not-call | salesleads Search（Type = All） |
| **轄區／團隊** | Phoenix, AZ → West Coast South excl. CA = **T1｜T31** → 一組自有轄區，可逕行註冊 | Territory Map-Jan.2026 (Rev.1)，Sales Territory Assign 分頁 |

---

## 3. 領導層與所有權

本節證據等級：**primary-record（一手紀錄）**＝網路號碼登錄機構、法院案卷、聯邦競選財務申報、官方州級歸檔，或公司自家已發布頁面｜**corroborated（多方佐證）**＝兩個以上獨立來源互相印證｜**single-source（單一來源）**＝僅一個次級來源｜**aggregator-only（僅資料商）**＝第三方資料商，無任何一手佐證，**未經查證前不得用於信件**｜**GAP**＝已具名搜尋但查無。

進入表格前有兩項前提。第一，**phoenixNAP 完全沒有公開的領導層頁面**——`phoenixnap.com/company/leadership` 回 **HTTP 404**。因此以下每一位高階主管的姓名，都來自供應商新聞稿、產業媒體併購報導、官方歸檔或資料商，並逐一標示等級。第二，**登錄機關幹部與網路聯絡人以獨立列呈現並明確標示**：ARIN OrgTech 是本人親自驗證過、公開合法的真實聯絡管道；在這個客戶上，那五位工程師是全檔**可信度最高的具名人員——高於多數高階主管**。

### 3.1 具名人員

| 姓名 | 職稱 | 角色類型 | 證據等級 | 公開聯絡管道 | FEC 紀錄 | 來源 |
|---|---|---|---|---|---|---|
| **Ron Cadwell** | **Founder & Chief Executive Officer（創辦人暨執行長）** | **經濟決策者／最終所有權人** | **corroborated**（兩則獨立產業媒體報導，加上公司自家部落格署名） | 無公開直撥。總機 **+1-480-422-2022**（ARIN 管理聯絡人號碼）。[LinkedIn](https://www.linkedin.com/in/ron-cadwell-0b747313b/)。依推導之信箱規則會得到 `ronca@phoenixnap.com`——**屬推導、未經查證**，見第 12 節，**不得視為已確認** | **UNVERIFIED — 入口／API 遭阻，不等於「查無紀錄」。** `api.open.fec.gov` schedule_a 三次嘗試均回 `{"error":{"code":"OVER_RATE_LIMIT"}}`，fec.gov 結果頁亦未渲染任何資料列 | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/)·[ION Analytics／Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/)·[phoenixNAP 部落格署名](https://phoenixnap.com/blog/ron-cadwell-devops) |
| **Stephanie Cadwell** | **共同創辦人（2009）** | 所有權人／非營運 | **single-source** | **GAP** — 未查得 LinkedIn，無任何公開管道 | **UNVERIFIED — 未查詢。** 其姓氏拼法在來源間本身即未定，查詢結果不具可靠性 | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) — **請注意同一篇文章內文將姓氏寫為「Caldwell」，而公司使用「Cadwell」** |
| **Ian McClarty** | **President（總裁）**，多份側寫另記為共同創辦人 | **內部支持者／硬體決策的高層贊助人** | **primary-record** — 於 2017–2026 年間四則具日期之供應商公開文件中具名引述 | 無公開直撥。[LinkedIn](https://www.linkedin.com/in/mcclarty)。Forbes Technology Council 側寫為公開 | **UNVERIFIED — 入口／API 遭阻**（同一 OVER_RATE_LIMIT 狀況） | [Supermicro 案例研究，2017-06](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)·[NVIDIA Tesla 新聞稿，2018-10-01](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus)·[HPE RL300 Gen11 新聞稿，2023-08-03](https://www.hpe.com/us/en/newsroom/press-release/2023/08/phoenixnap-powers-expanded-ai-and-cloud-services-with-energy-saving-ampere-based-servers-from-hewlett-packard-enterprise.html)·[RadiusDC 新聞稿，2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) |
| **William Bell** | **Executive Vice President of Products（產品執行副總）**；2017–2018 年資料中為 VP of Products | **技術／產品決策者——真正挑硬體的人** | **primary-record** — 三個世代的具體矽晶皆由他具名發言 | 無公開直撥。[LinkedIn](https://www.linkedin.com/in/williamb) | **UNVERIFIED — 入口／API 遭阻。** 另請注意「BELL, WILLIAM」是**高度撞名**的姓名；任何命中都必須先以雇主、職業與鳳凰城都會區地址交叉比對，才可歸屬 | [Supermicro 案例研究，2017-06](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)·[NVIDIA Tesla 新聞稿，2018-10-01](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus)·[HPE DC-MHS／Xeon 6 新聞稿，2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html) |
| **Robert Carmody** — *網路登錄列* | **phoenixNAP 技術聯絡人，ARIN 代號 CARMO67-ARIN** | **營運／網路工程——可驗證的直通管道** | **primary-record** — 自行公布之營運聯絡資料，非爬取所得 | **robertca@phoenixnap.com · +1-480-506-0120** | 未查詢——營運人員，不在主要人員政治篩查範圍 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)·[ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **Brian Musgrave** — *網路登錄列* | **phoenixNAP 技術聯絡人，ARIN 代號 MUSGR48-ARIN** | 營運／網路工程 | **primary-record** | **brianmu@phoenixnap.com · +1-480-401-0309** | 未查詢——營運人員 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Dragan Petrovic** — *網路登錄列* | **phoenixNAP 技術聯絡人，ARIN 代號 PETRO182-ARIN** | 營運／網路工程 — **EMEA** | **primary-record** | **draganp@phoenixnap.com · +356 77548965（馬爾他）· +381 621448366（塞爾維亞）** | 未查詢——營運人員 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Milos Ilic** — *網路登錄列* | **phoenixNAP 技術聯絡人，ARIN 代號 ILICM-ARIN** | 營運／網路工程 — 塞爾維亞 | **primary-record** | **milosi@phoenixnap.com · +381 615494754** | 未查詢——營運人員 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Adrian Montebello** — *網路登錄列* | **phoenixNAP 技術聯絡人，ARIN 代號 MONTE41-ARIN** | 營運／網路工程 — 馬爾他 | **primary-record** | **adrianm@phoenixnap.com · +356 79305305** | 未查詢——營運人員 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **「Admin」（群組）** — *網路登錄列* | **ARIN OrgAdmin，代號 ADMIN1723-ARIN**，適用 AS12189 與 Secured Servers 131.153.0.0/16 物件 | **登錄聯絡人 — 群組帳號，未具名任何個人（GAP）** | **primary-record**（就其為群組帳號而言） | **ipadmin@phoenixnap.com · +1-480-422-2022 ·** 3402 E. University Dr. Suite 420, Phoenix AZ 85034 | 不適用 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **「IPADMIN」** — *網路登錄列* | **技術 POC，代號 IPADM294-ARIN**，位於 **Secured Servers LLC** 之 131.153.0.0/16 網路物件 | **登錄聯絡人 — 群組帳號（GAP）** | **primary-record** | **ipadmin@phoenixnap.com** | 不適用 | [ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **「Abuse」／「Tech」（群組）** — *網路登錄列* | **OrgAbuse ABUSE2349-ARIN 與 ABUSE1536-ARIN；NOC／support 群組 POC TECH357-ARIN** | **登錄聯絡人 — 群組帳號（GAP）** | **primary-record** | **abuse@phoenixnap.com · +1-480-422-2022**；**support@phoenixnap.com · +1-480-646-5362** | 不適用 | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **PeeringDB 聯絡人** — *網路登錄列* | — | **網路聯絡人（PeeringDB）— 完全未公布（GAP）** | **primary-record**（就其為空集合而言） | net 2932 之 `poc_set` 為**空**；紀錄最後更新 **2026-03-25**。無任何政策、技術或 NOC 個人聯絡人 | 不適用 | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932) |
| **Marcus Bohn** | **Chief Legal Officer（法務長）**《主張值》 | 法務／任何主約或融資合約之關卡 | **aggregator-only — 低。** 未於任何 phoenixNAP 官方頁面獲得確認。**查證前不得於信件中使用此職稱** | **GAP** | **UNVERIFIED — 未查詢** | [RocketReach 管理層列表](https://rocketreach.co/phoenixnap-management_b5c0b21bf42e087f) |
| **Cindy Anastasi** | **Human Resources Director（人資總監）**《主張值》 | 非採購 | **aggregator-only — 低** | **GAP** | **UNVERIFIED — 未查詢** | [RocketReach 管理層列表](https://rocketreach.co/phoenixnap-management_b5c0b21bf42e087f) |
| **Frank Eickenhorst** | **VP, Support Services & Data Center Operations（支援服務與資料中心營運副總）**《主張值》 | 營運——影響機櫃、散熱與可維修性需求 | **aggregator-only — 低。** 未取得任何 phoenixNAP 官方確認 | **GAP** | **UNVERIFIED — 未查詢** | [Tracxn 側寫](https://tracxn.com/d/companies/phoenixnap/__mD8bU1wR9YlaxJnT-i3Qsq2RAnC6xvg1lhsYqyiFn0g) |
| **Seow Lim** | **VP of Architecture and Platform（架構與平台副總）**《主張值》 | 技術架構——平台／BMC 設計權責 | **aggregator-only — 低** | **GAP** | **UNVERIFIED — 未查詢** | [Tracxn 側寫](https://tracxn.com/d/companies/phoenixnap/__mD8bU1wR9YlaxJnT-i3Qsq2RAnC6xvg1lhsYqyiFn0g) |

**FEC 各列之明確警語：** 上表所有「UNVERIFIED」皆代表**查詢遭速率限制或頁面未渲染任何資料**，**不代表查詢乾淨且結果為空**。`api.open.fec.gov` 在共用 DEMO_KEY 下每次都回 `OVER_RATE_LIMIT`，fec.gov 瀏覽介面只回搜尋表單、無資料列。**本案沒有任何一位主要人員實際完成篩查。不得將上列任何一筆記為「查無紀錄」。**

### 3.2 登錄紀錄（Registry record）

請務必注意界線。**亞利桑那州公司委員會（Arizona Corporation Commission）——也就是唯一會列出幹部、經理人、成員、法定代理人與年報簽署人的公司登記機關——並未觸及。** 以下內容不是**網路號碼登錄機構**（ARIN），就是**亞利桑那州州務卿 UCC 登記簿**；後者屬登記機關性質之官方紀錄，但它是留置權索引，不是公司登記簿。

| 名稱 | 身分 | 歸檔 | 歸檔日期 | 來源 |
|---|---|---|---|---|
| **未取得任何幹部紀錄** | 不適用 | **亞利桑那州公司委員會 — Arizona Business Center（前身 eCorp）商業搜尋。** 舊主機 `ecorp.azcc.gov` 回 **NXDOMAIN**；現行主機 `arizonabusinesscenter.azcc.gov` 對 curl 回 **HTTP 403**，於瀏覽器中則在釋出結果前跳出 **6 字元圖形 CAPTCHA**。`ecorptestonline.azcc.gov/EntitySearch` 雖有存活的到達頁，但所有搜尋路徑皆 404。**未取得年報、設立章程、經理人／成員名單、法定代理人或任何簽署人。** 德拉瓦州 `icis.corp.delaware.gov` **未觸及** | 嘗試日 **2026-08-10** | [arizonabusinesscenter.azcc.gov/businesssearch](https://arizonabusinesscenter.azcc.gov/businesssearch) |
| **PHOENIX NAP, LLC** | **在案債務人**（亞利桑那州州務卿 UCC） | **18 筆 UCC-1 融資聲明**以 PHOENIX NAP, LLC 為債務人——全文見第 8 節。在案地址由 **2353 W. University Drive**（2014）→ **3402 E University Dr**（2022 起）→ **3402 E University Dr. Suite 420**（2026） | **2014-07-08 至 2026-07-22** | [AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/) |
| **SECURED SERVERS, LLC** | **2014–2026 年每一筆 BMO 授信之共同債務人**；同時是 **131.153.0.0/16 的 ARIN 登記人（代號 SSL-65）** | 於 16 筆 BMO 歸檔中列為共同債務人：201400214595、202200504921、202200505528、202400214184、202400278438、202400409257、202500024233、202500258880、202500298428、202500335016、202500404699、202500459045、202600027546、202600124616、202600124750、202600151100。地址 **2353 W UNIVERSITY DR, TEMPE, AZ 85281-7223** | 2014-07-08 至 2026-04-02 | [AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/)·[ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **CC PROPERTY INVESTMENTS, LLC** | **2014–2026 年每一筆 BMO 授信之共同債務人**（不動產／實體資產部門；縮寫 CC **可能**指 Cadwell——*屬推論，非歸檔記載*） | 與 Secured Servers 同樣出現在上述 16 筆 BMO 歸檔。地址 **2353 W UNIVERSITY DR, TEMPE, AZ 85281-7223** | 2014-07-08 至 2026-04-02 | [AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/) |
| **PHOENIX NAP MANAGEMENT RESOURCES LLC** | **獨立債務人實體**，債權人 BMO Harris Bank N.A. | UCC 檔號 **201900069940**，新申報 2019-02-13，2023-12-26 續期，2029-02-13 到期。地址 **2353 W UNIVERSITY DR, TEMPE, AZ 85281** | 2019-02-13 | [AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/) |
| **PhoenixNAP LLC** | **ARIN 組織代號 PHOEN-56** — AS12189 與 12 個網路物件之登記人 | ARIN 組織紀錄，3402 E. University Drive, Phoenix AZ 85034 | autnum 註冊 **2009-07-23**；最後異動 **2026-04-06** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)·[ARIN RDAP entity PHOEN-56](https://rdap.arin.net/registry/entity/PHOEN-56) |
| **Secured Servers LLC** | **ARIN 組織代號 SSL-65** — 131.153.0.0 – 131.153.247.255 之登記人，**技術聯絡人與 phoenixNAP 完全相同**。這是獨立於 UCC 之外、能證明兩者關係的證據 | ARIN 網路物件 | 2026-08-10 取得 | [ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |

### 3.3 採購決策圈（Buying committee）

phoenixNAP 是一家**創辦人持有、公開資料中沒有具名財務長**的公司，並且以近乎每月一次的頻率透過兩家銀行融資買硬體。從技術驗證到簽核的路徑很短，但技術關卡是真的：自 2017 年以來每一個世代的矽晶，都是同一位產品執行副總在對外發言，而他就是決定下一代加速器是什麼的人。

| 姓名 | 為何對伺服器採購重要 | 接觸方式 |
|---|---|---|
| **William Bell** — EVP of Products | **他就是那個決策。** 唯一橫跨四個硬體世代都被引述的高階主管：2017 年 Supermicro X11、2018 年 NVIDIA Tesla V100/P40、2023 年 HPE／Ampere、2025 年 HPE／Intel Xeon 6。他掌管執行個體型錄，所以下一個 GPU SKU 是什麼由他決定。他也公開把成本框定為限制條件——高成本不應阻礙創新與效能 | **從型錄切入，不要從公司切入。** 用兩個可查證的事實開場：`d3.g2.*` 自 2023 年底以來未曾更新；**現行 BMC 計費型錄中完全沒有任何 NVIDIA 或 AMD 加速器 SKU**。提出一份 Supermicro GPU 機箱的單機 TCO 模型，落在他自己已公開的 **$920–$1,778／月／台** 價格區間內。不要用產品簡報開場 |
| **Ian McClarty** — President | 簽署供應商關係，並且是出現在供應商新聞稿裡的人。他在 **2017 年親自為 Supermicro 背書**，理由正是今天對一家多區域業者仍然關鍵的三件事：全球配銷網路、備品、現場服務團隊。他也是 RadiusDC 切割案中 phoenixNAP 的具名發言人，因此他掌握切割後的敘事 | **是重新啟動，不是冷接觸。** 把他自己 2017 年的判準原封不動講回去，然後問：後來變了什麼。誠實的問題是——**Supermicro 是在供貨與財務條件上、還是在產品上輸掉 2023–2025 這兩輪改朝換代**，因為兩個新世代都給了 HPE |
| **Ron Cadwell** — Founder & CEO | 無外部股權的業主型經營者，公司以約 USD 70m EBITDA 對外行銷、第一輪出價突破 USD 1bn，而且剛把鳳凰城主機代管事業切出去。未來 12 個月任何數百萬美元等級的機隊承諾都是他點頭，而且現在這是**純裸機雲的資本決策**，不再是主機代管決策 | **不要第一個找他。** 等 Bell 驗證過組態之後再找，並且以資本效率的語言包裝：每台部署的美元成本、以及對照他自家公開牌價的回收月數——不是產品推銷 |
| **Frank Eickenhorst** — VP Support Services & Data Center Operations **（職稱未經查證，僅資料商來源）** | 掌管 PHX／ASH／CHI／SEA／AMS／BEG／SGP 的可維修性、備品倉與 24×7 機房現場。2017 年的決定性因素明確是**全球配銷與替換零件**，不是規格表 | **帶物流答案去，不要帶運算答案去：** 各區 RMA 週轉時間、AMS／BEG／SGP 的備品倉覆蓋、機櫃整合方案。**使用職稱前先確認** |
| **Robert Carmody／Brian Musgrave** — 具名 ARIN 技術聯絡人 | 真實、自行公開、有直撥電話的工程師。他們**不是**買方，但卻是通往「誰在規格化 GPU 節點」最快且可驗證的路徑，而且一通電話就能知道 Max 1100 機隊是否正在更新 | **一通資格確認電話，不推銷。** 這是網路／IP 聯絡人，把提問限縮在窄而技術的範圍，然後轉交產品組織 |
| **Marcus Bohn** — Chief Legal Officer **（未經查證，僅資料商來源）** | 只在後段相關。**BMO Bank N.A. 持有一組滾動式設備融資聲明**，因此任何新硬體採購都必須對照或並行於該授信額度立約 | **不要直接接觸。** 預期他會在主約階段出現；鑑於 BMO 的歸檔，請預先準備債權人同意與債權人間協議（intercreditor）條款 |

### 3.4 未能具名之職位——每一項皆為 GAP

**GAP — 完全未識別出 CFO／財務副總／財務主管。** 對一家幾乎每月透過兩家銀行融資買機隊的公司而言，這是本採購決策圈最大的破口。任何供應商新聞稿、產業媒體報導、資料商列表或官方歸檔中都沒有這個名字。·**GAP — 沒有任何採購、供應鏈或供應商管理的具名人員。**·**GAP — 沒有具名的 CTO 或工程副總**；公開存在的最高技術職稱就是 EVP of Products。·**GAP — 根本沒有領導層頁面**：`phoenixnap.com/company/leadership` 回 HTTP 404，沒有官方名冊可用。·**GAP — 在案幹部、經理人、成員與法定代理人**：亞利桑那州公司委員會搜尋受 CAPTCHA 阻擋，**本檔不解 CAPTCHA**；OpenCorporates 與 Bizapedia 亦遭封鎖。·**GAP — PHOENIX NAP, LLC 之年報簽署人與歸檔沿革。**·**GAP — 四位次要高階主管（Bohn、Anastasi、Eickenhorst、Lim）僅有資料商來源**，無任一由 phoenixNAP 官方頁面確認。·**GAP — Stephanie Cadwell 是否擔任任何營運職務**，甚至連姓氏拼法都未定（有來源寫成「Caldwell」）。·**GAP — USPTO 宣誓書簽署人、通訊代理人與代理律師**：搜尋結果顯示 Phoenix NAP L.L.C. 至少持有 **SECURED SERVERS**（序號 87396103）與 **HAAS**（序號 85655621），但 `tsdrapi.uspto.gov` 現回 **HTTP 401**（需註冊 API key）、`tmsearch.uspto.gov` 回 **HTTP 405**、`uspto.report` 回 **403**——**未從任何一手來源取得所有權人地址、簽署人、申請或展延日期**。·**GAP — phoenixnap.com 之歷史 WHOIS 登記人**：whoisrequest.com 回 Cloudflare 403，whoxy／securitytrails 需付費金鑰，因此僅有現行且已隱私保護的 RDAP 紀錄。·**GAP — 唯一查得之徵才啟事中無具名招募主管或招募人員。**

### 3.5 已實際查詢之來源——含「查無」者

**有產出者。** **[ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)** 是本檔在「人」這個面向上產出最高的單一來源——回傳完整紀錄外，還附上**六位具名技術與管理聯絡人，含電子郵件與直撥號碼**。**[ARIN RDAP entity PHOEN-56](https://rdap.arin.net/registry/entity/PHOEN-56)** 回傳 12 個網路物件。**[ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0)** 獨立於 UCC 之外證明 Secured Servers LLC 屬 phoenixNAP 體系。**[AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/)** 以真實瀏覽器操作，回傳**全部 20 筆歸檔**與所有債務人、擔保權人資料。**[Supermicro 2017 年案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)**——因環境無 pdftotext，係以手動解壓 PDF content stream 取得——提供了兩位高階主管引述與歷史機隊內容。**[New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/)** 與 **[ION Analytics／Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/)** 提供所有權與創辦人組合。**[CourtListener REST v4](https://www.courtlistener.com/)** 回傳 17 件案卷（僅 metadata，見第 14 節）。

**有觸及但在「人」的面向查無者。** **[PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)** 網路面資料完整，但 **`poc_set` 為空**——未公布任何個人聯絡人。**`phoenixnap.com/company/leadership`** 回 **HTTP 404**——不存在領導層頁面。**ZipRecruiter 與 Indeed** 僅回一則鳳凰城 Data Center Technician 職缺（$21–30/hr），**無具名招募主管**。**`api.open.fec.gov`** 每次都回 `OVER_RATE_LIMIT`，因此**沒有任何主要人員完成篩查**。

**遭封鎖者及原因。** **亞利桑那州公司委員會**——對 curl 回 HTTP 403，瀏覽器中出現 **6 字元圖形 CAPTCHA**；本檔不解 CAPTCHA，因此這是硬停止，不是疏漏。**`ecorp.azcc.gov`**——DNS **NXDOMAIN**，入口已退役。**OpenCorporates**——HAProxy CAPTCHA。**Bizapedia**——security check。**opengovus.com** 亞利桑那鏡像——HTTP 404。**所有 USPTO 端點**——401／405／403／連線失敗。**whoisrequest.com**——Cloudflare 403。**[mcassessor.maricopa.gov](https://mcassessor.maricopa.gov)**——結果表格由 AJAX 載入，`/mcs/api/` 端點在無授權 token 時只回 HTML 外殼，因此**兩處 University Drive 地址皆未取得任何地號、APN、估價或登記文件**。

**在不驚動客戶的前提下，補齊幹部缺口的最佳中性做法：** 透過 **AZ SOS／ACC 臨櫃或電話**調閱亞利桑那州公司委員會的實體紀錄，並與第 8 節所述之 **UCC-11 認證影本**一併辦理——同一趟即可同時補上幹部缺口與擔保品缺口。

---

## 4. 據點與機房

以下有六處是現行 Bare Metal Cloud 型錄中的**計費區域**（PHX、ASH、NLD、SGP、CHI、SEA），其餘為網路節點。這個區別比據點總數重要得多，因為只有計費區域才吃得下新的伺服器 SKU。

| 據點 | 設施營運者 | 自有／租用 | 面積／電力（僅列已公開者） | 證據 |
|---|---|---|---|---|
| **鳳凰城 AZ — 3402 E University Drive（DC1，旗艦＋總部）** | 自 2010 年起由 phoenixNAP 自建自營。**正出售予 RadiusDC** — 2026-03-12 宣布，預計 2026 年 Q2 交割。**phoenixNAP 續留為承租戶** | **自有**（廠房於 **2009 年以 USD 6.3m 購入**）→ RadiusDC 交割後**轉為租用／承租戶**。不動產持有與 **CC PROPERTY INVESTMENTS, LLC** 出現在每一筆 BMO 授信中的共同債務人身分一致 | **約 200,000 平方英尺**，2010 年啟用。RadiusDC 規劃將現有設施擴充至 **8 MW IT 負載**，並增建第二棟（DC2）最高 **18 MW**，園區合計 **約 26 MW**，DC2 首期自 **2028 上半年**起。*（注意：既有建物目標為 8 MW，反推目前實際佔用 IT 負載遠低於 8 MW。）* | [PRNewswire，2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) — 收購範圍含主機代管設施、互連基礎設施與園區開發權；**phoenixNAP 約 80% 全球業務仍在獨立所有權下持續營運，明確包含 Bare Metal Cloud 與網路平台**。顧問：RadiusDC 方為 J.P. Morgan＋Gibson Dunn＋Snell & Wilmer；**phoenixNAP 方為 BofA Securities＋Cleary Gottlieb**。[PeeringDB netfac_set](https://www.peeringdb.com/api/net/2932) 亦列有「PhoenixNAP, Phoenix US」 |
| **Ashburn, VA** | **第三方** — Equinix DC1–DC15／DC21–DC22 與 **DataBank Ashburn（IAD1）** | 租用／代管 | **GAP** — 未公開 | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)。**ASH 為完整 BMC 區域**：包含三個 GPU SKU 在內的所有伺服器 SKU 均對 ASH 定價（[現行型錄](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)） |
| **Chicago, IL** | Equinix **CH3**，Elk Grove Village | 租用／代管 | **GAP** | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)；**CHI 為含 GPU SKU 之計費 BMC 區域** |
| **Seattle, WA** | Equinix **SE2／SE3** | 租用／代管 | **GAP** | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)；**SEA 為含 GPU SKU 之計費 BMC 區域** |
| **Amsterdam, NL** | **Iron Mountain Data Center — Amsterdam（AMS-1）** | 租用／代管 | **GAP。** phoenixNAP 自家據點頁將阿姆斯特丹稱為其**第二座資料中心**（相對於網路節點），亦即完整服務據點 | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)·[phoenixNAP 據點頁](https://phoenixnap.com/global-it-services/locations)；**NLD 為含 GPU SKU 之計費 BMC 區域** |
| **Singapore** | Equinix **SG1** 與 Equinix **SG3** | 租用／代管 | **GAP** | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)；**SGP 為含 GPU SKU 之計費 BMC 區域** |
| **Belgrade, Serbia** | **Cetin Data Center** | 租用／代管 | **GAP。** 同時是**工程據點**——兩位具名 ARIN 技術 POC 使用 +381 號碼 | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)·[ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Atlanta, GA** | **Digital Realty ATL13** | 租用／代管 | **GAP。注意：** ATL 同時出現在據點清單*與* 2017 年 Supermicro 案例研究中，但在現行型錄中**不是計費 BMC 區域**——僅為網路節點 | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)；未出現在六個 BMC 定價區域中 |
| **洛杉磯 CA·法蘭克福 DE·馬德里 ES·米蘭 IT·華沙 PL·雪梨 AU** | Equinix **LA1**、**FR7**、**MD2**、**ML2**、**WA1**、**SY1/SY2** | 租用／代管——**網路節點** | **GAP** | [PeeringDB netfac_set](https://www.peeringdb.com/api/net/2932)（合計 16 個據點）。phoenixNAP 自家[據點頁](https://phoenixnap.com/global-it-services/locations)將其描述為網路節點而非資料中心，同列的還有**聖保羅、赫爾辛基、索菲亞與台北**，這些地點**未登錄任何 PeeringDB 設施** |

**據點清單之時效性警告：** AS12189 的 PeeringDB 紀錄最後更新於 **2026-03-25**，但**據點清單本身最後更新於 2021-10-01**。該清單可能低估或誤述目前的實際版圖，**不得單憑 PeeringDB 推估本客戶規模**。

**結構性註記（可作為談話切入點，非指摘）：** RadiusDC 交割後，**RadiusDC 將成為 phoenixNAP 在鳳凰城的房東與主機代管供應商**。2026 年 Q2 之後在鳳凰城上架的任何設備，都落在別人的建築、別人的電力路線圖上。這會改變機櫃密度與交付的談法，也是詢問機櫃整合與集併（staging）方案的正當理由。

---

## 5. 硬體機隊

本節證據等級：**confirmed（確認）**＝第一手具名揭露或多方獨立佐證｜**circumstantial（旁證）**＝行為或未標日期之頁面強烈指向，但無任何具日期文件具名該供應商｜**contradicted（反證）**＝證據方向相反｜**GAP**＝各方向皆查無，且不作任何主張。

| 供應商／類別 | 證據等級 | 證據實際說了什麼 |
|---|---|---|
| **Supermicro** | **CONFIRMED（歷史，2017–2023）／CIRCUMSTANTIAL（現況）** | **歷史面已確認：** Supermicro 於 **2017 年 6 月**發布完整具名案例研究——**X11 Building Block Solutions、2U 四節點 BigTwin、Simply Double 全快閃 NVMe SuperStorage、Supermicro Rack Scale Design 與 Supermicro Server Manager（SSM）**——並附 **Ian McClarty（President）** 與 **William Bell（VP Products）** 具名引述。phoenixNAP 亦**透過 Supermicro 參與 Intel 的 Early Ship／Early Deployment 計畫**（[案例研究](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)）。**2023 年面已確認：** ServeTheHome 2023 年 3 月對 phoenixNAP BMC `d3.m6.xlarge` 執行個體的實機報導，標題與內文均以 **Supermicro Sapphire Rapids 硬體**呈現，並指出 phoenixNAP 是 **4th Gen Xeon 的首發雲端供應商**（[ServeTheHome，2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)）。**現況為旁證：** phoenixNAP 仍維持一個線上的 [Supermicro 生態系頁面](https://phoenixnap.com/offers/supermicro-servers)，聲明其 Bare Metal Cloud 採用 Supermicro 方案，並於 **2025 年 6 月 19 日**共同舉辦 Supermicro 網路研討會——但**該頁面沒有任何型號、也沒有日期**，而且**2023 年之後宣布的兩個新世代都給了 HPE**。**未查得 2024–2026 年間任何 phoenixNAP 導入新 Supermicro 平台的公告。** |
| **Hewlett Packard Enterprise（HPE）** | **CONFIRMED — 且正在取代** | 兩則具日期的 HPE 新聞稿具名 phoenixNAP。**(1) 2023-08-03：** phoenixNAP 以 **HPE ProLiant RL300 Gen11（Ampere 處理器）**擴充 Bare Metal Cloud，聲明部署於其橫跨五大洲、18 座資料中心的網路，並由 **Ian McClarty** 具名引述。對應現行 **`a1.c5.*` Ampere Altra Q80-30** SKU（[HPE 新聞稿](https://www.hpe.com/us/en/newsroom/press-release/2023/08/phoenixnap-powers-expanded-ai-and-cloud-services-with-energy-saving-ampere-based-servers-from-hewlett-packard-enterprise.html)）。**(2) 2025-04-04：** phoenixNAP 採用 **HPE ProLiant Compute DL320 Gen12（Intel Xeon 6）**——HPE 首款 DC-MHS／OCP 解構式硬體——由 **William Bell, EVP of Products** 具名引述，並點名 adtech、fintech 與 SLED 需求。對應 **`s4.x6.*` 與 `s5.x6.*`** SKU（[HPE 新聞稿](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)）。phoenixNAP 官網另設有 [HPE ProLiant RL300 專屬產品頁](https://phoenixnap.com/bare-metal-cloud/hpe-proliant-rl300)。**HPE 已連續拿下最近兩次平台更新。** |
| **Intel（矽晶＋加速器，且極可能有共同行銷）** | **CONFIRMED** | Intel 矽晶主導型錄——**82 個伺服器 SKU 中有 72 個**。全型錄唯一販售的加速器就是 **Intel Data Center GPU Max 1100**，並設有專屬 offer 到達頁，明確主張 **Intel MAX GPU 功能無額外授權費**（[offer 頁](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc)）。phoenixNAP 於 2017 年（透過 Supermicro）參與 Intel Early Deployment／Early Ship 計畫，2023 年為 4th Gen Xeon 首發供應商。**一個供應商品牌專屬 offer 頁，加上 2023 年 9 月的預購推廣，是 Intel 補貼或種子部署的典型特徵**——此為推論，但支撐紮實 |
| **NVIDIA** | **CONTRADICTED（就現行機隊而言）** | phoenixNAP 曾於 **2018-10-01** 公開推出 **NVIDIA Tesla V100（4 卡與 8 卡 NVLink）與 Tesla P40** 專用伺服器（[新聞稿](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus)）。七年半後，**現行 Bare Metal Cloud 產品型錄中沒有任何 NVIDIA SKU**——101 項產品中唯一的 `gpuConfigurations` 值是 **「Intel Max 1100 GPU」**（[現行型錄](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)，2026-08-10 抓取）。**第三方清單文章聲稱 phoenixNAP 提供「L4 到 H100」，並不被 phoenixNAP 自家定價系統支持——視為資料商雜訊** |
| **Ampere Computing** | **CONFIRMED（矽晶層級，經由 HPE 交付）** | **Ampere Altra Q80-30（`a1.c5.*`）** 與 **AmpereOne A96-36X（`a2.c9.*`）** 皆為現行已定價 SKU。Altra 世代有文件證明係經 **HPE ProLiant RL300 Gen11** 導入。**較新的 AmpereOne A96-36X SKU 之機箱供應商未在任何可觸及來源中揭露——這是一個空著的競爭位置** |
| **AMD** | **CONFIRMED（僅矽晶層級；機箱供應商不明）** | **EPYC 4345P 與 EPYC 4565P** 單路 SKU（`s4.c3.medium`、`s4.c6.large/medium/xlarge`、`s4.s2.large`）皆為現行已定價項目。**沒有任何供應商公告指出這些機箱由誰供應。又一個空位**（[現行型錄](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)） |
| **Express Computer Systems（Irvine, CA）** | **CIRCUMSTANTIAL** | 亞利桑那 UCC 檔號 **202200315262** 之擔保權人，**2022-05-19** 申報，債務人為 **ALTAY CORPORATION**（洛杉磯）與 **PHOENIXNAP**（3402 East University Drive）。Express Computer Systems 為硬體經銷／租賃商。**這是紀錄上唯一的非銀行設備擔保權人**，顯示 2022 年至少有一批經銷商融資的硬體。**擔保品文字未由 AZ 入口呈現，因此融資標的無從證實**（[AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/)） |
| **Pliops** | **CIRCUMSTANTIAL** | 現行型錄中存在專屬 SKU **`d2.c4.db1.pliops1`**（2× Xeon Gold 6336Y、4× 4 TB NVMe），意味已部署 Pliops 儲存加速卡。規模小且利基，但足以證明**他們願意驗證第三方 PCIe 加速卡** |
| **Netris（網路層）** | **CONFIRMED** | **Netris SoftGate 1G／10G／25G** 以可計費產品形式存在（`netris/softgate_*`），亦即**採用軟體定義閘道而非專有設備**。可解讀為：這是一家對解構式、不被單一供應商鎖定的硬體抱持開放態度的業者 |
| **Dell／Lenovo／ODM（浪潮、緯穎、廣達）** | **GAP** | **各方向皆查無證據，本檔不作任何主張。** 所有已查詢來源中，均未出現任何與 phoenixNAP 有關的 Dell、Lenovo、Inspur、Wiwynn 或 Quanta 記載。已查詢清單見 3.5 與第 14 節 |

### 觀察到的 CPU 世代，以及對機隊年齡的意涵

直接讀自現行產品型錄——**101 項產品中含 82 個獨立伺服器 SKU**（[現行型錄 JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)，2026-08-10 抓取）：

- **當世代：** Intel Xeon 6 P-core **6527P／6767P／6770P**（`s5.x6.*`）·Intel Xeon 6 E-core **6731E**（`s4.x6.*`）·**AmpereOne A96-36X**（`a2.c9.*`）·AMD **EPYC 4345P／4565P**（`s4.c3/c6.*`）·Intel **Core i9 14900K**（`s3.c3.*`）
- **中生代：** Intel **Emerald Rapids** 6536／6540／6542Y（`d3.c1/c2/c3`、`d3.m1/m2/m3`）·Intel **Sapphire Rapids** 5418Y／6426／6430／6436／6442Y／8452Y（`d3.*`，含全部三個 GPU SKU）·**Ampere Altra Q80-30**（`a1.c5.*`）·Intel **E-2356G／E-2388G**（`s2.*`）
- **老舊：** Intel **Ice Lake** 5315Y／5317／6326／6336Y／8352Y（`d2.*`）·Intel **Cascade Lake-R 6258R**（`d1.*`）·Intel **E-2276G／E-2288G**（`s1.*`）·Intel **E3 v3**（`s0.*`）

**意涵。** **`d1` 加 `d2` 的 Cascade Lake／Ice Lake 機隊共 26 個 SKU，機齡 4–6 年**——這是天然的整併標的；而 phoenixNAP **已經跑過 Supermicro X11 BigTwin**，因此 **X11 BigTwin → X14 BigTwin 是字面上的同族升級**，不是平台遷移。型錄中出現 **AMD EPYC 4000 系列與 Core i9 桌上型等級零件**，代表只要價格／效能划算，他們願意買單路工作站級矽晶——而這正是機箱供應商能做出差異的區段。另外兩個**高密度儲存 SKU**——`d3.s5.xlarge`（2× Xeon Gold 6430、6× 15.36 TB NVMe＋1 TB 開機碟）與 `s5.x6.s5.large`（Xeon 6767P、6× 15 TB NVMe＋1 TB 開機碟）——直接對應 Supermicro Petascale／SSG 全 NVMe，而依 2017 年案例研究，他們**已經跑過 Supermicro「Simply Double」SuperStorage**。這是有歷史基礎的重返切入點，不是冷推銷。

---

## 6. GPU 型錄與 AI 佈局

**這是全公司最弱、最外露的一塊，也是打這通電話的理由。**

整個加速器型錄就是**同一台機器的三個分級**。三者搭載完全相同的加速器：**2× Intel Data Center GPU Max 1100**（每張 48 GB HBM2e、56 Xe cores、Intel Xe Link 橋接）。以下每一個價格都讀自 phoenixNAP 自家的**正式產品／價格 JSON**——支撐其公開定價頁的那一份檔案——於 **2026-08-10** 抓取，並與渲染後的 GPU 頁面交叉核對。

| SKU | 完整規格 | 每小時 | 1 個月 | 12 個月 | 24 個月 | 36 個月 | 供應狀況 |
|---|---|---|---|---|---|---|---|
| **d3.g2.c1.xlarge** | 2× **Intel Max 1100**；2× Xeon Gold **6426**（合計 32 核 @2.9 GHz）；**512 GB** RAM；**4× 2 TB NVMe**；2× 25 Gbps（bonding 後 50 Gbps）＋20 Gbps DDoS；含 15 TB 流量 | **$2.49/hr** | **$1,646.72/mo** | **$998.26/mo** | **$880.11/mo** | **$808.21/mo** | 於 **PHX、ASH、NLD、SGP、CHI、SEA** 定價——**各區域價格完全相同**。行銷頁僅宣稱 **Phoenix (AZ) 與 Ashburn (VA)** 有現貨，「More Coming Soon…」 |
| **d3.g2.c2.xlarge** | 2× **Intel Max 1100**；2× Xeon Gold **6436**（合計 40 核 @2.7 GHz）；**512 GB** RAM；**4× 2 TB NVMe**；2× 25 Gbps | **$2.60/hr** | **$1,726.02/mo** | **$1,065.66/mo** | **$947.52/mo** | **$875.63/mo** | 六個區域均定價；行銷為 **PHX＋ASH** |
| **d3.g2.c3.xlarge — 旗艦 GPU SKU** | 2× **Intel Max 1100**；2× Xeon Gold **6442Y**（合計 48 核 @2.6 GHz）；**512 GB** RAM；**4× 2 TB NVMe**；2× 25 Gbps | **$2.67/hr** | **$1,778.49/mo** | **$1,110.27/mo** | **$992.12/mo** | **$920.23/mo** | 六個區域均定價；行銷為 **PHX＋ASH**。**這是要拿來對價的那一台** |
| **NVIDIA — 任何型號** | **未提供。** 101 項產品的現行型錄中不存在任何 NVIDIA SKU | — | — | — | — | — | **無。** 最後一次 NVIDIA 產品是 **2018 年 10 月的 Tesla V100／P40** 專用伺服器線，早已退場 |
| **AMD Instinct — 任何型號** | **未提供** | — | — | — | — | — | **無** |

上表來源：[phoenixNAP 現行型錄 JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)（[/bare-metal-cloud/instances](https://phoenixnap.com/bare-metal-cloud/instances) 背後的檔案）·[GPU 伺服器頁](https://phoenixnap.com/bare-metal-cloud/gpu-servers)·[Intel Max 1100 offer 頁](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc)·[2018 年 NVIDIA Tesla 新聞稿](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus)。

### 非 GPU 價格錨點——供 BOM 與毛利三角驗證

| SKU | 規格 | 每小時 | 1 個月 | 12 個月 | 24 個月 | 36 個月 |
|---|---|---|---|---|---|---|
| **s5.x6.m9.xlarge** — 最接近的當世代 CPU 機種 | Xeon **6770P**（64 核）、512 GB、2× 4 TB NVMe | **$3.11/hr** | **$2,111.26/mo** | **$1,316.31/mo** | **$1,111.50/mo** | **$968.14/mo** |
| **d3.m6.xxlarge** — 成本上最接近 GPU 機種的純 CPU 機種 | 2× Platinum **8452Y**（72 核）、**1 TB** RAM、2× 4 TB NVMe | **$2.56/hr** | **$1,650.20/mo** | **$1,416.32/mo** | **$1,301.44/mo** | **$1,208.43/mo** |

兩者於六個區域均可供應。來源：[現行型錄 JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)。

### 行銷與計費系統的不一致——以及它說明了什麼

GPU 行銷頁寫的供應區域是 **Phoenix (AZ) 與 Ashburn (VA)**，「More Coming Soon」。現行計費型錄則對三個 GPU SKU 在**六個**地點定價——PHX、ASH、NLD、SGP、CHI、SEA——**且各區價格完全相同**。這不是可以拿來指摘的矛盾，而是一個誠實的線索：**價格是全球性佈建的，但現貨只敢認兩個美國據點。** 應解讀為**規模小而集中的 GPU 機隊**。因此一次更新會是**不大的台數，這反而有利於快速試點而非大單** ——對一家每次採購都必須對照銀行授信立約的客戶而言，試點是遠比大單容易成交的第一步。

### AI 佈局，如實陳述

phoenixNAP 有真實的 AI 需求故事，卻只有一支很薄的 AI 機隊。**Kaligent** 是 phoenixNAP 自家具名案例，明確關於把 AI 放進客戶端工具（[客戶實績頁](https://phoenixnap.com/customer-experience)）；HPE 2025 年 4 月新聞稿點名 **adtech、fintech 與 SLED** 需求；**加州大學柏克萊分校統計系**是具名的學術／研究運算客戶，而那正是 Max 1100 這一級最典型的買家輪廓。相對於此：**一款加速器、三個分級、約 34 個月未更新、沒有 NVIDIA 選項、沒有 AMD 選項，而且只在六個計費區域中的兩個承認有現貨。** 這個位置 HPE 沒有拿走，它是空的。

---

## 7. 採購時鐘

phoenixNAP 實際上多久買一次，用兩條互相獨立的線索讀：**(A)** 新矽晶世代何時首次出現在他們自家公開型錄中；**(B)** 何時新增一筆擔保設備融資撥款。兩條線互相佐證。

### 7.1 線索 A — 型錄世代首次出現

以 [phoenixnap.com/bare-metal-cloud/instances](https://phoenixnap.com/bare-metal-cloud/instances) 的 Wayback Machine 快照定年。每一個世代都**夾在一個「確定未出現」與一個「確定已出現」的快照之間**，再與具日期的供應商新聞稿交叉核對。

| 世代／SKU 家族 | 未出現於 | 首次出現於 | 區間 | 佐證 |
|---|---|---|---|---|
| **`d2.*` Intel Ice Lake** | 2021-07-07 | **2021-09-28** | 約 12 週 | — |
| **`d3.*` Intel Sapphire Rapids** | 2023-01-30 | **2023-05-08** | 約 14 週 | phoenixNAP 為 **4th Gen Xeon 首發雲端供應商**；[ServeTheHome，2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/) 記載該執行個體為 **Supermicro** 硬體 |
| **`a1.c5.*` Ampere Altra Q80-30** | 2023-05-08 | **2023-09-13** | 約 18 週 | 對應 **[HPE ProLiant RL300 Gen11 新聞稿，2023-08-03](https://www.hpe.com/us/en/newsroom/press-release/2023/08/phoenixnap-powers-expanded-ai-and-cloud-services-with-energy-saving-ampere-based-servers-from-hewlett-packard-enterprise.html)** |
| **`d3.g2.*` Intel Max 1100 GPU**（同一視窗另含 `s3.c3.*` Core i9 14900K） | 2023-09-13 | **2023-11-09** | **約 8 週——全研究中最緊的區間** | 與 phoenixNAP **2023-09-19 的預購推廣**及專屬 [Intel Max 1100 offer 頁](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc) 一致 |
| **`s4.x6.*` Intel Xeon 6 E-core（6731E）** | 2024-08-06 | **2024-12-07** | 約 17 週 | — |
| **`s5.x6.*` Intel Xeon 6 P-core（6527P／6767P／6770P）** | 2025-03-27 | **2025-08-15** | 約 20 週 | 對應 **[HPE ProLiant DL320 Gen12／DC-MHS 新聞稿，2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)** |
| **`a2.c9.*` AmpereOne A96-36X** | — | **2026-08-10 已在現行計費型錄中** | **日期無法確定** | **從未出現在任何已存檔的 instances 頁面快照中。** 最新導入項目；如何補上日期見第 14 節 |

### 7.2 線索 B — 融資事件（亞利桑那 UCC-1 起始日）

對 **PHOENIX NAP, LLC** 的每一筆**新** UCC-1 視為一次融資採購事件。**修正與續期排除**——它們是重述而非新增擔保品。**2026-07-22 的 UBS AG Aviation & Yacht Finance 歸檔排除——那不是 IT 設備。**

| 年度 | 新 UCC-1 起始日 | 筆數 |
|---|---|---|
| 2014 | 2014-07-08 | 1 |
| 2022 | 2022-05-19·2022-09-02·2022-09-02 | 3 |
| 2023 | — | **0** |
| 2024 | 2024-05-10·2024-06-21·2024-09-25 | 3 |
| 2025 | 2025-01-10·2025-07-03·2025-08-06·2025-09-04·2025-10-15·2025-12-01 | **6** |
| 2026（至今） | 2026-01-13·2026-02-13·2026-03-18·2026-04-02·2026-04-02 | 5 |

### 7.3 採購節奏

**硬體世代更新：** 大約**每 7–9 個月會有一個新 CPU 家族進入型錄**——2023 年 5 月 Sapphire Rapids → 2023 年 9 月 Ampere Altra＋Intel Max 1100 GPU → 2024 年 8／12 月 Xeon 6 E-core → 2025 年 4／8 月 Xeon 6 P-core。

**融資節奏更快，而且曾在加速。** 2025 年 7 月至 2026 年 4 月間，相鄰**新** UCC-1 的間隔：

| 起 → 迄 | 天數 |
|---|---|
| 2025-07-03 → 2025-08-06 | 34 |
| 2025-08-06 → 2025-09-04 | 29 |
| 2025-09-04 → 2025-10-15 | 41 |
| 2025-10-15 → 2025-12-01 | 47 |
| 2025-12-01 → 2026-01-13 | 43 |
| 2026-01-13 → 2026-02-13 | 31 |
| 2026-02-13 → 2026-03-18 | 33 |
| 2026-03-18 → 2026-04-02 | 15 |

**中位數約 33 天。** 與線索 A 合讀：**他們每兩年更新兩到三個矽晶世代，並且大約每個月動用一筆新的擔保設備撥款來支付。**

**最後事件。** 最後一筆 **IT 設備融資事件為 2026-04-02** — 同日兩筆 BMO Bank N.A. UCC-1（檔號 **2026-001-2461-6** 與 **2026-001-2475-0**，各 6 頁，債務人均為 Phoenix NAP LLC＋CC Property Investments＋Secured Servers）。可偵測到的最後**型錄新增**：**AmpereOne A96-36X** SKU，2026-08-10 已在現行計費型錄中，但從未出現在任何已存檔的 instances 頁面。**最後一次 GPU 採購訊號：自 2023 年 10 月左右導入 Intel Max 1100 之後就沒有了——34 個月沒有加速器更新。**

### 7.4 下一個視窗 — 已逾期，且正在開啟

以 33 天中位數計，2026-04-02 之後理應在 **2026 年 5 月**再出現一筆新撥款。實際上是**四個月完全沒有任何 IT 相關動作**，時間正好涵蓋 **RadiusDC 主機代管切割案於 2026 年 Q2 交割**。誠實的讀法是：**這是切割期間刻意的資本暫停，不是業務衰退**——而且請注意，2026-03-18 新開了一條 **U.S. Bank Equipment Finance** 額度，債務人**只有 Phoenix NAP LLC 一家**，不含不動產共同債務人，時間點在 RadiusDC 宣布前三週。那正是「把可融資的 IT 設備與待售不動產分開」該有的樣子。

**預估下一個視窗：2026 年 9 月至 12 月。** 最高機率的觸發點是**切割後第一份裸機雲機隊計畫**，而該計畫中最外露的一條科目就是**加速器層——自 2023 年起未更新，且沒有 NVIDIA 或 AMD 的替代方案**。

**信心水準：中等。** 這是**由歸檔間距與型錄考古推導而來，不是公司的任何陳述**。

### 7.5 方法——及其限制

**(1) 型錄。** 列舉 phoenixNAP **instances** 與 **gpu-servers** 兩頁的所有 Wayback CDX 快照（分別 52 與 54 筆），透過 `web.archive.org` 原始 `id_` 擷取下載約 **35** 筆、解壓縮後以 regex 檢測 SKU 前綴與 CPU 型號，把每個世代夾在「確定未出現」與「確定已出現」之間；再逐一與具日期的供應商新聞稿交叉核對。**(2) 融資。** 於亞利桑那州州務卿 UCC Lien Search 查詢——Organization =`PHOENIX NAP`、Wildcard、Party = Debtor、Filter = All（含已失效）——抄錄每一筆起始日，將每一筆新 UCC-1 視為一次融資採購事件，並計算事件間距。**(3) 排除。** 修正與續期不計入節奏；UBS 航空／遊艇歸檔以非 IT 排除。

**限制，如實列出。** **UCC-1 只能證明一次融資動撥，不能證明交付日期。** **AZ 入口不呈現擔保品文字**，因此**無法把任何一筆撥款對應到特定硬體**。Wayback 對重複的原始擷取請求施加速率限制，因此有數個快照回傳截斷或被擋的內容。另外，價格檔 `api-data.json` 自 **2025 年 10 月**才開始被存檔，因此 AmpereOne 的導入日期無法定年——見第 14 節。

---

## 8. UCC 融資紀錄

**範圍：** 於**亞利桑那州**針對 **PHOENIX NAP, LLC** 及其關係企業進行債務人查詢；依 UCC §9-301／§9-307，亞利桑那州是亞利桑那 LLC 的正確歸檔機關。**未執行德拉瓦州查詢**，且依現有證據亦無必要——未查得任何德拉瓦實體——但請見第 14 節之但書。

### 8.1 判定

> ### **20 筆歸檔 — 已取得並逐筆抄錄**
>
> **……但擔保品內容不可得。** 以下每一筆均按亞利桑那州州務卿公開檢視器呈現的內容原樣重現：檔號、起始日、到期日、留置權類型、每一筆修正／續期及其申報日、登錄日與頁數，以及每一位債務人與擔保權人之完整名稱與地址。**該檢視器不呈現擔保品文字，也不對公開查詢提供歸檔影像。** 本次未看到任何一條擔保品條款，因此**不抄錄，也不改寫轉述**。

### 8.2 已在案之申報——每筆完整列出

**1）檔號 2019-000-6994-0** — 起始 **2019-02-13**，到期 **2029-02-13**，Standard。
· 新申報 2019-02-13，登錄 2019-02-26，**3 頁**。續期申報 2023-12-26，登錄 2023-12-26，1 頁。
· **債務人：** PHOENIX NAP MANAGEMENT RESOURCES LLC, 2353 W UNIVERSITY DR, TEMPE, AZ 85281。
· **擔保權人：** BMO HARRIS BANK N.A., 770 N WATER ST 8TH FL, MILWAUKEE, WI 53202。
· **擔保品：** *入口未呈現 — 見 8.4。*

**2）檔號 2014-002-1459-5** — 起始 **2014-07-08**，到期 **2029-07-08**，Standard。
· 新申報 2014-07-08，登錄 2014-07-10，**2 頁**。續期 2019-04-16，登錄 2019-05-16，1 頁。續期 2024-05-02，登錄 2024-05-02，1 頁。
· **債務人：** PHOENIX NAP, LLC／SECURED SERVERS, LLC／CC PROPERTY INVESTMENTS, LLC — 均位於 2353 W. UNIVERSITY DRIVE, PHOENIX, AZ 85281。
· **擔保權人：** BMO HARRIS BANK, N.A., 111 WEST MONROE, CHICAGO, IL 60603。
· **擔保品：** *入口未呈現。*
· **註：** 這是**現存最久的有效歸檔**，已續期兩次，滿十二年仍未失效。

**3）檔號 2022-005-0492-1** — 起始 **2022-09-02**，到期 **2027-09-02**，Standard。
· 新申報 2022-09-02，**2 頁**。修正 2022-12-20，**2 頁**。
· **債務人：** PHOENIX NAP, LLC, 3402 E UNIVERSITY DR, PHOENIX, AZ 85034-7200／CC PROPERTY INVESTMENTS, LLC 與 SECURED SERVERS, LLC，均為 2353 W UNIVERSITY DR, TEMPE, AZ 85281-7223。
· **擔保權人：** BMO HARRIS BANK N.A., 790 N. WATER STREET, 14TH FLOOR, MILWAUKEE, WI 53202。
· **擔保品：** *入口未呈現。*

**4）檔號 2022-005-0552-8** — 起始 **2022-09-02**，到期 **2027-09-02**，Standard。
· 新申報 2022-09-02，**2 頁**。**無修正。**
· **債務人：** 同上三家 — PHOENIX NAP, LLC／CC PROPERTY INVESTMENTS, LLC／SECURED SERVERS, LLC。
· **擔保權人：** BMO HARRIS BANK N.A., 790 N. WATER STREET, 14TH FLOOR, MILWAUKEE, WI 53202。
· **擔保品：** *入口未呈現。*

**5）檔號 2024-002-1418-4** — 起始 **2024-05-10**，到期 **2029-05-10**，Standard。
· 新申報 2024-05-10，**2 頁**。修正 2024-06-11，**5 頁**。
· **債務人：** 同上三家。
· **擔保權人：** BMO BANK N.A., 790 N. WATER STREET, 15TH FLOOR, MILWAUKEE, WI 53202。
· **擔保品：** *入口未呈現。*
· **註：** 這是第一筆以 **「BMO Bank N.A.」** 名義（原為 BMO Harris）並使用 15 樓地址的歸檔。

**6）檔號 2024-002-7843-8** — 起始 **2024-06-21**，到期 **2029-06-21**，Standard。
· 新申報 2024-06-21，**2 頁**。修正 2024-09-05，**2 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 790 N. WATER STREET, 15TH FLOOR, MILWAUKEE, WI 53202。
· **擔保品：** *入口未呈現。*

**7）檔號 2024-004-0925-7** — 起始 **2024-09-25**，到期 **2029-09-25**，Standard。
· 新申報 2024-09-25，**2 頁**。修正 2024-12-17，**2 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。*

**8）檔號 2025-000-2423-3** — 起始 **2025-01-10**，到期 **2030-01-10**，Standard。
· 新申報 2025-01-10，**2 頁**。修正 2025-03-26，**5 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。*

**9）檔號 2025-002-5888-0** — 起始 **2025-07-03**，到期 **2030-07-03**，Standard。
· 新申報 2025-07-03，**2 頁**。修正 2025-07-23，**4 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。*

**10）檔號 2025-002-9842-8** — 起始 **2025-08-06**，到期 **2030-08-06**，Standard。
· 新申報 2025-08-06，**16 頁 — 全紀錄中篇幅最大的單筆 UCC-1。****無修正。**
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。* **一份 16 頁的 UCC-1 意味著一份很長的逐項設備清冊**——這是整份清單中最值得優先調閱認證影本的一筆。

**11）檔號 2025-003-3501-6** — 起始 **2025-09-04**，到期 **2030-09-04**，Standard。
· 新申報 2025-09-04，**2 頁**。修正 2025-09-23，**7 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。*

**12）檔號 2025-004-0469-9** — 起始 **2025-10-15**，到期 **2030-10-15**，Standard。
· 新申報 2025-10-15，**5 頁**。**無修正。**
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。*

**13）檔號 2025-004-5904-5** — 起始 **2025-12-01**，到期 **2030-12-01**，Standard。
· 新申報 2025-12-01，**2 頁**。修正 2025-12-19，**7 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。*

**14）檔號 2026-000-2754-6** — 起始 **2026-01-13**，到期 **2031-01-13**，Standard。
· 新申報 2026-01-13，**2 頁**。修正 2026-01-28，**10 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 15 樓。
· **擔保品：** *入口未呈現。*

**15）檔號 2026-001-5110-0** — 起始 **2026-02-13**，到期 **2031-02-13**，Standard。
· 新申報 2026-02-13，**遲至 2026-04-21 才登錄**，**6 頁**。
· **債務人：** 同上三家。**擔保權人：** BMO BANK N.A., 790 N. WATER STREET, 15TH FLOOR。
· **擔保品：** *入口未呈現。*

**16）檔號 2026-001-0311-3** — 起始 **2026-03-18**，到期 **2031-03-18**，Standard。**自 2022 年以來第一家新債權人。**
· 新申報 2026-03-18，**2 頁**。
· **債務人：** PHOENIX NAP, LLC, 3402 E UNIVERSITY DR, PHOENIX, AZ 85034 — **唯一債務人。無 Secured Servers，無 CC Property Investments。**
· **擔保權人：** U.S. BANK EQUIPMENT FINANCE, A DIVISION OF U.S. BANK NATIONAL ASSOCIATION, 1310 MADRID STREET, MARSHALL, MN 56258。
· **擔保品：** *入口未呈現。*

**17）檔號 2026-001-2461-6** — 起始 **2026-04-02**，到期 **2031-04-02**，Standard。
· 新申報 2026-04-02，**6 頁**。
· **債務人：** PHOENIX NAP, LLC, 3402 E UNIVERSITY DR, PHOENIX, AZ 85034／CC PROPERTY INVESTMENTS, LLC 與 SECURED SERVERS, LLC, 2353 W UNIVERSITY DR, TEMPE, AZ 85281。
· **擔保權人：** BMO BANK N.A., 790 NORTH WATER STREET, 14W, MILWAUKEE, WI 53202。
· **擔保品：** *入口未呈現。*

**18）檔號 2026-001-2475-0** — 起始 **2026-04-02**，到期 **2031-04-02**，Standard。**最近一筆 IT 設備歸檔。**
· 新申報 2026-04-02，**6 頁**。
· **債務人與擔保權人：** 與第 17 筆完全相同。
· **擔保品：** *入口未呈現。*

**19）檔號 2026-003-2810-7** — 起始 **2026-07-22**，到期 **2031-07-22**，Standard。**非 IT 設備。**
· 新申報 2026-07-22，登錄 2026-07-30，**2 頁**。
· **債務人：** PHOENIX NAP, LLC, **3402 E UNIVERSITY DR. SUITE 420**, PHOENIX, AZ 85034。
· **擔保權人：** UBS AG, AVIATION & YACHT FINANCE (IVV2), BAHNHOFSTRASSE 45, ZURICH, ZU 8001, CHE。
· **擔保品：** *入口未呈現。* 這是掛在營運公司名下的一筆航空器或船舶融資。**已自第 7 節的採購節奏中排除。**

**20）檔號 2022-003-1526-2** — 起始 **2022-05-19**，到期 **2027-05-19**，Standard。**紀錄上唯一的非銀行設備擔保權人。**
· 新申報 2022-05-19，登錄 2022-05-31，**1 頁**。
· **債務人：** ALTAY CORPORATION, 4470 W SUNSET BLVD SUITE 697, LOS ANGELES, CA 90027／**PHOENIXNAP**, 3402 EAST UNIVERSITY DRIVE, PHOENIX, AZ 85034。
· **擔保權人：** EXPRESS COMPUTER SYSTEMS, 1733 KAISER AVENUE, IRVINE, CA 92614。
· **擔保品：** *入口未呈現。*

**20 筆紀錄中，沒有任何一筆出現終止（termination）或讓與（assignment）。每一筆都仍然有效。**

### 8.3 查詢紀錄

| 入口／URL | 使用之查詢字串 | 回應（引號內為原文） | 遭阻時之替代途徑 |
|---|---|---|---|
| **AZ SOS UCC 留置權檢視器** — [apps.azsos.gov/apps/ucc/search/LiensViewerView.aspx](https://apps.azsos.gov/apps/ucc/search/LiensViewerView.aspx)，自動化抓取 | 嘗試直接載入留置權明細檢視器 | **HTTP 403 Forbidden。** 無資料 | 以真實瀏覽器操作同一 URL（見下列） |
| **AZ SOS UCC 留置權檢視器** — 同一 URL，真實瀏覽器、冷啟動 | 嘗試在沒有先行查詢的情況下取得明細 | 頁面渲染出標頭 **「View Liens」** 與一行 **「Results from this search contain all UCC records filed on or prior to unknown」**——**無資料。** 此檢視器需要先有查詢工作階段 | 先執行查詢，再觸發 View postback |
| **AZ SOS UCC 到達頁** — [azsos.gov/business/ucc](https://azsos.gov/business/ucc) | 唯讀：定位權威查詢網址 | **HTTP 200。** 取得權威連結：**「UCC Lien Search ⇒ https://apps.azsos.gov/apps/ucc/search/」** | 不適用——此次呼叫成功 |
| **AZ SOS UCC Lien Search** — [apps.azsos.gov/apps/ucc/search/](https://apps.azsos.gov/apps/ucc/search/)，真實瀏覽器 | 表單渲染內容：Organization＋Standard／Wildcard＋Party（Debtor／Secured Party）；Individual Last／First／Middle＋Party；File Number；Search Filter Unlapsed／All（含已失效）；起訖日期 | **HTTP 200。** 橫幅寫著 **「Results from this search contain all UCC records filed on or prior to Thursday, April 9, 2026」**——**請注意此橫幅已過時**，因為結果集中包含一筆 **2026-07-22** 的歸檔 | 不適用 |
| **AZ SOS UCC Lien Search — 實際執行之查詢** | **Organization =`PHOENIX NAP`·Search Type = Wildcard·Party = Debtor·Search Filter = All（含已失效）·未設日期篩選** | **「20 entries found」**，分組為 **PHOENIX NAP MANAGEMENT RESOURCES LLC（1）· PHOENIX NAP, LLC（18）· PHOENIXNAP（1）** | 不適用——8.2 節即由此查詢產出 |
| **AZ SOS UCC Lien Search — 明細取得** | 以表格之「Select first 100 items」核取方塊全選 20 筆，觸發 View postback | **「20 entries selected」**，隨後取得完整多筆 **View Liens** 頁面——已抄錄於 8.2 | 不適用 |
| **未執行——以「BMO」為擔保權人端之查詢** | — | — | 可列出 `PHOENIX NAP` 萬用字元未涵蓋之其他 phoenixNAP 關係債務人名稱下的 BMO 歸檔。**免費，應該執行** |
| **未執行——個人姓名查詢** | — | — | 可捕捉任何以 Cadwell／McClarty 個人保證形式索引的歸檔。**免費，值得跑一次** |
| **未執行——德拉瓦州 UCC 查詢** | — | — | **刻意未執行。** phoenixNAP 於亞利桑那州設立，依 UCC §9-301／§9-307，亞利桑那州為正確歸檔機關。只有在存在德拉瓦控股公司時才需要查德拉瓦，而本次未查得——**但德拉瓦公司登記機關本身也未查詢**，因此這是一個建立在未經檢驗前提上的假設。見第 14 節 |
| **擔保品文字——此入口不可得** | — | AZ SOS 公開 UCC 檢視器（`LiensViewerView.aspx`）呈現**檔號、日期、留置權類型、申報事件類型、頁數，以及完整債務人與擔保權人名稱與地址**。它**不**呈現擔保品文字，也不對公開查詢提供歸檔影像 | 向 **AZ SOS Business Services Division, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187** 提出 **UCC-11 資訊請求或認證影本申請** |

### 8.4 這份紀錄的意涵

這是整份檔案中最清楚的訊號，而且毫不含糊。

| 觀察 | 意涵 | 信心 | 對銷售的後果 |
|---|---|---|---|
| **BMO（Harris）Bank N.A. 自 2014 年起就是其設備與資產債權人** — 十二年、BMO 端三次換地址、**十八筆歸檔**。每一筆實質授信都**同時以三家實體交叉擔保**：Phoenix NAP LLC（營運公司）、Secured Servers LLC（IP 位址持有者）、CC Property Investments LLC（不動產部門） | 債權人同時對**營運設備、網路資產與不動產**設有擔保——典型的業主型經營者借款基礎，**不是租賃額度** | **高** — 直接讀自 18 筆已抄錄歸檔 | 預期是**主往來銀行的核准路徑**，不是供應商信用路徑。財務端的對話會落在**既有整批擔保之下的留置權順位**，對他們而言是例行公事 |
| **他們不向原廠融資子公司租機隊。** 紀錄上**完全沒有 Dell Financial Services、沒有 HPEFS、沒有 Cisco Capital、沒有 CIT／DLL／Key Equipment** | 機隊是**用銀行債務、在自己的資產負債表上買下來的。** 這正是「自購機隊」型客戶 | **高** — 因為登記簿已完整取得，20 筆中的「不存在」才具有意義 | **供應商對話是採購對話，不是用量對話。** 每台價格直接落在他們的現金、折舊與利息上。**他們對每台單價會極度敏感** |
| **2025 年年中節奏性質改變。** 2025 年 7 月至 2026 年 4 月間大約**每 33 天**動用一筆新的擔保撥款，修正頁數從 **2 → 5 → 7 → 10** 攀升，並在 2025 年 8 月出現一筆 **16 頁的原始申報** | 清冊變長代表設備清單變長。**那段期間有東西在被大量且穩定地採購** | **中高** — 頁數是清冊長度的代理指標，不是證明 | 那段期間買的東西**現在機齡 12–18 個月且已完成融資**。更新對話的主題是**接下來要買什麼**，不是換掉剛付完錢的東西 |
| **2026 年出現兩家新債權人：** U.S. Bank Equipment Finance（**2026-03-18**，值得注意的是債務人**只有 Phoenix NAP LLC**，不含 Secured Servers 與 CC Property 共同債務人）以及 UBS AG Aviation & Yacht Finance（2026-07-22） | U.S. Bank 那一筆才是關鍵——**一條獨立的營運公司設備額度，出現在 RadiusDC 案宣布前三週，且結構上完全不碰不動產實體。** 這正是**刻意把可融資的 IT 設備與待售不動產分離**該有的樣子 | **中高** — 結構與時序為直接觀察；意圖為推論 | **現在存在第二條「純 IT、不牽涉不動產」的設備額度。** 那正是新硬體訂單最自然會對照的授信，而且它是全新的、推測尚未動用 |
| **接著一切停止。** 自 **2026-04-02** 起沒有任何 IT 設備 UCC-1，對照 **33 天中位數，等於四個月靜默** | 合併 **2026 年 Q2 主機代管切割交割**來看，合理推論是**切割期間的融資暫停，重啟待定**。重啟後將是**純裸機雲的借款基礎**，由 BMO 與現在的 U.S. Bank 支撐，擔保品會是**伺服器而不是建築物** | **中** — 停止是觀察值；原因是推論 | **這是整個客戶的時機論證。** 在重啟之前接觸，不要在之後。見 7.4 |
| **20 筆紀錄中沒有任何終止或讓與；每一筆都仍然有效** | **擔保品池已被完全綁住。** 沒有任何已釋放、可自由再質押的借款能量 | **高** — 直接觀察 | 新採購必須**在既有整批擔保之內被容納，或對其次順位**。若要對出貨硬體取得購買價金擔保權（PMSI），**PMSI 通知程序與 20 日設備完善期限必須在出貨前規劃好，而不是出貨後** |
| **擔保品內容從未被看到** | **無從得知** BMO 各筆歸檔究竟是整批擔保（「all assets, wherever located, now owned or hereafter acquired」）還是特定設備清冊。這個差別對新供應商而言**就是整個商業問題** | **高** — 這是關於「證據裡沒有什麼」的陳述 | **在任何條件洽談之前先調閱認證影本。** 從 **2025-002-9842-8**（16 頁）、**2026-001-2461-6** 與 **2026-001-2475-0**（各 6 頁）以及 **2026-001-0311-3**（U.S. Bank 那條額度）開始。聯絡：**AZ SOS Business Services, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187** |

**一句話的實務結論：** 他們的採購能力**是真的、有銀行支撐**；核准路徑要經過一位**已經握有整批擔保**的債權人；而新硬體訂單**會以設備撥款的形式立約**。財務與法務關於留置權順位與供應商請款的對話，對他們而言**是例行而非障礙**——但也請預期他們**在每台單價上毫不讓步**，因為折舊與利息都是他們自己扛。

### 8.5 GAP — UCC 軌，如實列出

- **擔保品文字是本檔最大的單一缺口。** 20 筆歸檔全數定位、當事人／日期／修正全數抄錄，但 AZ SOS 公開檢視器**不呈現擔保品描述、也不提供歸檔影像**。**一條擔保品條款都沒有看到，也沒有任何改寫轉述。** 頁數是唯一的代理指標。**解法：** 向 **AZ SOS Business Services Division, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187** 申請 UCC-11 資訊請求或認證影本，優先順序為 **2025-002-9842-8**、**2026-001-2461-6**、**2026-001-2475-0** 與 **2026-001-0311-3**。
- **未執行擔保權人端查詢。** 以「BMO」為擔保權人查詢，可捕捉 `PHOENIX NAP` 萬用字元未涵蓋的關係債務人名稱。**免費，未執行。**
- **未執行個人姓名查詢。** 任何以 Ron Cadwell、Stephanie Cadwell 或 Ian McClarty 個人保證形式歸檔者，不會出現在組織名稱查詢中。**免費，未執行。**
- **未查詢德拉瓦州 UCC，而且這建立在一個未經查證的前提上。** 亞利桑那州是**亞利桑那 LLC** 的正確歸檔機關，且未查得任何德拉瓦實體——但**德拉瓦公司登記機關本身從未查詢**（`icis.corp.delaware.gov` 未觸及），且 **Cleary Gottlieb 擔任 RadiusDC 案賣方律師，使控股架構具相當可能性**。若確有德拉瓦控股公司，可能存在本檔完全未見的歸檔。
- **入口自己的資料涵蓋橫幅已過時。** 橫幅寫「all UCC records filed on or prior to Thursday, April 9, 2026」，卻回傳了一筆 2026-07-22 的歸檔。索引顯然比它自稱的更新，但**真正的涵蓋截止日不明**，因此理論上 2026 年 4 月至 8 月間仍可能有遺漏。
- **ALTAY CORPORATION 的關係未獲解釋。** 檔號 2022-003-1526-2 將「PHOENIXNAP」與一家洛杉磯公司並列為對硬體經銷商的共同債務人。**兩者關係為何、融資標的為何，均不明。**

---

## 9. 成本天花板

一台 GPU 機種對 phoenixNAP 能值多少錢，以及同一台機器要花多少成本組出來。本節只回答一個問題：**在什麼樣的硬體取得成本之下，他們的旗艦 GPU SKU 才付得起自己？**

**標的機種：** **`d3.g2.c3.xlarge`** — 2× Intel Max 1100、2× Xeon Gold 6442Y、512 GB、4× 2 TB NVMe、2× 25 GbE。**公開牌價（鳳凰城）：** $2.67/hr 隨需；1 個月 **$1,778.49/mo**；12 個月 **$1,110.27/mo**；24 個月 **$992.12/mo**；36 個月 **$920.23/mo**（[現行型錄 JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)）。

### 9.1 假設——請先讀這一段；這些是假設，不是查證發現

**9.2 節中的每一個數字都是假設驅動的模型，不是查證發現。phoenixNAP 未公布任何成本資料，本次也未查得任何成本資料。**

1. **牌價＝實現營收。** 實際上企業客戶會議價，實現營收很可能**低 10–25%**，這只會**讓天花板更低**。
2. **營運成本佔營收 45–60%。** 涵蓋假設每台 1.2–1.6 kW 的電力、空間與機櫃、內含的 15 TB 流量、20 Gbps DDoS 清洗、24×7 NOC 與支援、佈建自動化，以及分攤的管銷。**這些輸入值一項都沒有查證來源。** 真實比例可能是 35%，也可能是 70%。
3. **假設機器 100% 使用率。** 任何閒置或未售出的產能都會等比壓低天花板——而**他們自家行銷頁只承認六個計費區域中的兩個有現貨，暗示使用率才是真正的限制**。
4. **未計融資成本。** 但他們實際上是借款的（BMO、U.S. Bank），**加上利息後真實天花板再降 5–10%**。
5. **12／18／24 個月的回收期是慣例，不是他們的政策。** 一家用 **5 年 UCC 期限**融資的業主型業者，實務上可能接受 **36–48 個月**，那會讓區間上緣大致**翻倍**。

**任何人在客戶面前使用這些數字時，都必須說成「這是模型，請糾正我的輸入值」，絕不可說成對他們經濟結構的斷言。**

### 9.2 由租金推導之天花板 — `d3.g2.c3.xlarge`

| 情境 | 營收基礎 | 可用於硬體之比例 | 每月可攤硬體金額 | 12 個月天花板 | 18 個月天花板 | 24 個月天花板 |
|---|---|---|---|---|---|---|
| **低** | $920.23/mo 實現（36 個月預約） | 40% | **$368** | **$4,416** | **$6,624** | **$8,832** |
| **中** | $1,110.27/mo 實現（12 個月預約） | 50% | **$555** | **$6,663** | **$9,995** | **$13,327** |
| **高** | $1,778.49/mo 實現（1 個月牌價） | 55% | **$978** | **$11,738** | **$17,607** | **$23,476** |

**每台 GPU 機種硬體取得成本的可辯護工作區間：以未折現月費計算，約自 12 個月硬回收的 $6,700，到 24 個月寬鬆回收的約 $23,500。**

**首次會議要拿來對價的數字，是中情境 18 個月的那一格：每台約 $10,000。**

### 9.3 街頭價 BOM 重建——以及關鍵發現

重建 `d3.g2.c3.xlarge`。**有來源者標示清楚；無來源者亦標示清楚並留白——不憑空編造。**

| 元件 | 品項 | 街頭價 | 狀態 |
|---|---|---|---|
| **CPU × 2** | **Intel Xeon Gold 6442Y**（24 核、60 MB、2.60 GHz） | **每顆 $5,580.56 ＝ $11,161.12** | **有來源** — Newegg 單顆街頭價。**註：**[Intel ARK SKU 232380](https://www.intel.com/content/www/us/en/ark.html) 回傳規格但**未公布 1KU 建議客戶價**；量產與 OEM tray 價格必然顯著低於街頭價，但無任何可引用數字 |
| **GPU × 2** | **Intel Data Center GPU Max 1100**（48 GB HBM2e、300 W、PCIe 雙寬） | **每張約 $8,000 ＝ 約 $16,000** | **有來源** — 2025 年 4 月起始零售價約 $8,000（CpuTronic 規格／價格頁，該頁同時以約 $15,000 的 NVIDIA H100 作對照） |
| **記憶體** | 512 GB DDR5 RDIMM | — | **無來源。必須報價取得。** |
| **儲存** | 4× 2 TB U.2／E1.S NVMe | — | **無來源。必須報價取得。** |
| **平台** | 雙路主機板、可支援 300 W 雙寬插槽之 2U／4U GPU 機箱、備援 Titanium 電源、BMC、滑軌 | — | **無來源。必須報價取得。** |
| **網路** | 2× 25 GbE 網卡 | — | **無來源。必須報價取得。** |
| **有來源之小計（僅 CPU＋GPU）** | — | **每台約 $27,161（街頭價）** | — |

> ### **關鍵發現**
>
> **僅 CPU 加 GPU 的街頭價小計約 $27,161，就已經超過整個由租金推導的取得成本天花板——中情境 18 個月為 $6,700，即使最寬鬆的 24 個月情境也只有 $23,476——而且這還沒有計入任何記憶體、儲存、機箱、網路或整合成本。**

有三種可能的解釋，而**三種在商業上都有用**：

**(a) phoenixNAP 以遠低於街頭價取得這些 GPU。** 考量到那個 [Intel 品牌專屬 offer 到達頁](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc)、「無額外授權費」的訴求，以及他們透過 Supermicro 參與 Intel Early Ship／Early Deployment 計畫的紀錄，**Intel 計畫價或種子價的可能性很高**。
**(b) 他們以 36–60 個月而非 12–24 個月攤提**，與其 **5 年 UCC 期限**一致。
**(c) GPU 機隊本來就刻意做小、屬於策略性而非利潤中心**，與只在六個計費區域中的兩個承認有現貨一致。

**三者指向同一個結論：他們的加速器層在市場硬體價格下無法自給自足。這正是一份可信的「每台價格」提案會讓他們感興趣的原因。**

### 9.4 Supermicro 對應機種——以及真正該做的比較

對等替代品是 **Supermicro X13／X14 雙路 2U 或 4U PCIe GPU SuperServer，可容納 2–4 張 300–350 W 雙寬加速器，搭配 512 GB DDR5 與 4× U.2 NVMe。** **本檔沒有該組態的 Supermicro 定價或街頭價，也不虛構——那正是要去做的報價。**

**要為他們做的比較，不是「同樣裝 Intel Max 1100，Supermicro 對 HPE」。** 而是：**在他們已經公開的同一份月費牌價之下，一台 Supermicro 機箱能裝什麼樣的加速器，並且仍然能在 18 個月內回收？** 在 $6,700–$10,000 的中情境天花板下，答案是**單張 GPU 或雙張中階 GPU 的機種，不是旗艦 AI 機箱**——而**這個重新框定，就是整場銷售對話本身**。

### 9.5 GAP — 成本天花板軌

- **BOM 僅有兩項有來源**：兩顆 Xeon Gold 6442Y（Newegg 街頭價每顆 $5,580.56），以及 Intel Max 1100（約 $8,000 起始零售價，該資料點為 **2025 年 4 月**，距今已 16 個月）。**512 GB DDR5 RDIMM 組、4× 2 TB NVMe、雙路 GPU 機箱、電源與 25 GbE 網卡皆無來源價格。此比較是刻意做成不完整，而不是編造補齊。**
- **未取得對等機箱的 Supermicro 定價或街頭價。**
- **所有營運成本輸入值皆為假設**：每台 GPU 機種耗電、鳳凰城與 Ashburn 電價、機櫃成本、使用率。**一項都未查證。第 9 節的成本天花板區間是模型，不是查證發現。**
- **街頭價是上限。** phoenixNAP 以經銷或合約價採購，而且——考量 Intel offer 頁與其計畫歷史——**在加速器這一項上可能遠低於街頭價**。結論的方向（加速器層在市場價格下無法自給自足）是穩健的；**幅度**在真實合約價下會壓縮。
- **回收期是慣例。** 他們的五年 UCC 期限暗示實務上可能容忍 36–48 個月，那會讓區間上緣大致翻倍、整個算式改觀。**直接問他們用什麼回收期核算——這是正當的探詢問題，也是這個模型中影響最大的單一輸入值。**

---

## 10. 客戶與網路

### 已具名客戶

與本轄區多數業者不同，phoenixNAP **確實公布具名客戶案例**。以下四家均出自公司自家的[客戶實績頁](https://phoenixnap.com/customer-experience)。

| 名稱 | 等級 | 來源實際說了什麼 |
|---|---|---|
| **chuck-stack** | **公司自行發布之案例研究** | 一家中小企業 ERP 供應商，自 AWS 移轉至 Bare Metal Cloud，回報**雲端基礎設施成本降低約 75%**——描述為以 AWS 或 Azure 四分之一價格取得的高效能混合雲 |
| **UC Berkeley, Department of Statistics** | **公司自行發布之案例研究** | 學術與研究運算，內容涵蓋雲端方案、支援與計費體驗。**之所以重要，是因為學術統計與 ML 教學工作負載，正是 Intel Max 1100 這一級最典型的買家** |
| **Kaligent** | **公司自行發布之案例研究** | **明確為 AI 用例**——使用 Bare Metal Cloud 將 AI 導入其面客工具。**這是他們加速器業務的具名參考客戶** |
| **TPilot** | **公司自行發布之案例研究** | 透過 phoenixNAP 為其高階客戶建立第一個美國主機據點 |
| **Ubersmith** | **第三方發布，且屬系統面而非客戶** | Ubersmith 發布了一則 [phoenixNAP 案例研究](https://ubersmith.com/case-studies/phoenixnap/)，顯示 phoenixNAP **以 Ubersmith 作為裸機事業的訂閱計費與佈建平台** |
| **產業組合（有陳述、未具名）** | **供應商發布＋第三方** | HPE 2025 年 4 月新聞稿指出 phoenixNAP 正在滿足 **廣告科技、金融科技與州／地方政府暨教育（SLED）** 的需求。ServeTheHome 2023 年的機房報導指出其機籠服務**金融、醫療與政府**客戶。phoenixNAP 亦公開宣布完成 **AzRAMP**（亞利桑那州雲端授權），與 SLED 曝險一致（[HPE，2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)·[ServeTheHome](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)） |
| **RadiusDC** | **新聞稿——是交易對手，不是客戶** | 2026 年 Q2 交割後成為 phoenixNAP 在鳳凰城的**房東與主機代管供應商**；phoenixNAP 明確**續留為承租戶**。不是客戶，但會影響未來機櫃落在哪裡（[PRNewswire](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html)） |

### 網路 — AS12189

- **登錄：** **AS12189（PhoenixNAP LLC）**，ARIN 代號 PHOEN-56，autnum 註冊於 **2009-07-23**，最後異動 **2026-04-06**。IRR AS-SET 為 **LEVEL3::AS-PHOENIXNAP**（[ARIN RDAP](https://rdap.arin.net/registry/autnum/12189)）
- **登記於 PhoenixNAP LLC（PHOEN-56）之位址空間：** 144.90.0.0/16·192.240.192.0/18·125.253.64.0/20＋/21＋/22＋/23·103.67.200.0/22·104.244.52.0/22（PNAP-03）·199.201.104.0/21（SC-ASH）·69.160.32.0/20·64.38.220.0/23（PNAP-01）·23.235.242.0/24 與 23.235.243.0/24·IPv6 **2607:6000::/28**（PHOENIXNAP-V6）與 **2607:3000::/32**（SECURED-CLOUD）（[ARIN RDAP entity PHOEN-56](https://rdap.arin.net/registry/entity/PHOEN-56)）
- **另行登記：** **131.153.0.0 – 131.153.247.255 登記於 SECURED SERVERS LLC**（ARIN 代號 SSL-65），**技術聯絡人與 phoenixNAP 完全相同**（[ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0)）
- **容量：** 自報流量等級 **500–1000 Gbps**·比例 **Heavy Outbound**·範圍 **Global**·網路類型 **Content**·啟用 IPv6、無 multicast·宣告 **1,000 個 IPv4 與 100 個 IPv6 前綴**（[PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)）
- **面客連接埠：** 所有現代裸機 SKU 皆配 **2× 25 Gbps bonding**；GPU 機種行銷為 **50 Gbps，含 20 Gbps DDoS 清洗與 15 TB 內含流量**
- **對接政策：** **Selective**，於特定據點優先，**不需簽約、不看流量比例**
- **IX 佈點——10 條連線、宣告埠容量約 650 Gbps：** Equinix Ashburn **100G**·AMS-IX **100G**·DE-CIX Frankfurt **100G**·SIX Seattle **100G**·BIX.BG **100G**·DE-CIX Phoenix **100G**·Equinix Chicago **20G**·Equinix Los Angeles **10G**·Equinix IX Milan **10G**·Ninja-IX Phoenix **10G**
- **無公開 looking glass、無 route server，PeeringDB 中亦無任何個人 PoC**
- **次要 ASN 但書——未解：** 第三方 BGP 工具將 **AS59210**（對應前綴 131.153.46.0/23）與 **AS207134**（IPinfo 標為「PHOENIX NAP, LLC.」）歸屬於 phoenixNAP。**ARIN RDAP 將 59210 解析到 APNIC 區塊、將 207134 解析到 RIPE 區塊**——兩者皆為境外註冊且**無法在來源端確認**。**請將 AS12189 視為唯一經查證之 ASN**；境外 ASN 與前綴版圖尚未測繪

**時效性但書：** PeeringDB 紀錄最後更新於 **2026-03-25**，但其**據點清單最後更新於 2021-10-01**。不得單憑 PeeringDB 推估本客戶規模。

---

## 11. 政治與公開紀錄

僅限公開紀錄。每一列均標示等級。僅列具名主要人員。

| 對象 | 查得內容 | 標籤 |
|---|---|---|
| **Ron Cadwell**（創辦人暨執行長） | **FEC 個人捐獻查詢未完成。** `api.open.fec.gov` schedule_a 查詢在共用 DEMO_KEY 下三次嘗試皆回 `{"error":{"code":"OVER_RATE_LIMIT"}}`，fec.gov 瀏覽頁僅回搜尋表單、無任何資料列。**這是工具層失敗，不是查證結果——不得記為「查無紀錄」**（[API 查詢](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=CADWELL%2C+RON)·[fec.gov 瀏覽](https://www.fec.gov/data/receipts/individual-contributions/)） | **unverified — 入口／API 遭阻** |
| **Ian McClarty**（總裁） | **FEC 個人捐獻查詢未完成** — 同一 OVER_RATE_LIMIT 狀況。**正反皆無結果**（[API 查詢](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=MCCLARTY%2C+IAN)） | **unverified — 入口／API 遭阻** |
| **William Bell**（產品執行副總） | **FEC 個人捐獻查詢未完成** — 同一狀況。另請注意 **「BELL, WILLIAM」屬高度撞名姓名**；任何命中都必須先以雇主、職業與鳳凰城都會區地址比對後才可歸屬（[API 查詢](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=BELL%2C+WILLIAM)） | **unverified — 入口／API 遭阻** |
| **Stephanie Cadwell**（共同創辦人） | **未查詢。** 其姓氏拼法在來源間本身即未定——**Cadwell 對 Caldwell**——查詢不具可靠性（[New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/)） | **not searched** |
| **phoenixNAP**（法人） | **相關的非聯邦層面姿態，有來源且屬正面：** phoenixNAP **完成 AzRAMP**，亦即亞利桑那州雲端資安授權計畫，由 Ian McClarty 對外公布。這是一項**州政府採購資格**，而 HPE 2025 年新聞稿確認 **SLED 為具名需求垂直領域**。**未發現任何公司政治行動委員會（PAC）**，且**未查詢州級競選財務資料庫（亞利桑那州州務卿、鳳凰城市政府）**（[AzRAMP 公告](https://www.linkedin.com/posts/mcclarty_phoenixnap-successfully-completes-azramp-activity-6867186225674108928-wEPk)·[HPE，2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)） | **政府相關業務姿態已查證；競選財務未查詢** |

**如實陳述：本案沒有任何一位主要人員實際完成聯邦政治獻金篩查。** 上表每一列的 FEC 結果都是**工具層失敗，不是乾淨結果**。要補上這個缺口，需要個人的 `api.data.gov` 金鑰，並對 Ron Cadwell、Ian McClarty、William Bell 與 Stephanie Cadwell／Caldwell 重跑一次。

**公開紀錄的正面意義：** AzRAMP 資格加上已確認的 SLED 垂直領域，代表**政府採購是他們業務中真實存在的一塊**；反過來說，任何硬體對話都可能出現供應鏈來源、原產國與 TAA 類型的問題。**請預先準備，不要被問倒。**

---

## 12. 公開聯絡管道

僅限公開來源。**本節不列任何個人手機號碼與私人住址，本次亦未蒐集。** 無公開管道者標示為 GAP。

| 管道 | 內容 | 來源 |
|---|---|---|
| **總機／IP 管理** | **+1-480-422-2022** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **支援／NOC** | **+1-480-646-5362 · support@phoenixnap.com** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **IP 管理（群組信箱）** | **ipadmin@phoenixnap.com** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **濫用通報（群組信箱）** | **abuse@phoenixnap.com** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **具名工程師 — Robert Carmody**，ARIN OrgTech（美國） | **robertca@phoenixnap.com · +1-480-506-0120** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **具名工程師 — Brian Musgrave**，ARIN OrgTech（美國） | **brianmu@phoenixnap.com · +1-480-401-0309** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **具名工程師 — Dragan Petrovic**，ARIN OrgTech（EMEA） | **draganp@phoenixnap.com · +356 77548965 · +381 621448366** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **具名工程師 — Milos Ilic**，ARIN OrgTech（塞爾維亞） | **milosi@phoenixnap.com · +381 615494754** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **具名工程師 — Adrian Montebello**，ARIN OrgTech（馬爾他） | **adrianm@phoenixnap.com · +356 79305305** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **總部通訊地址（送貨與到訪）** | **phoenixNAP, 3402 E. University Drive, Suite 420, Phoenix, AZ 85034-7200** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)·AZ SOS UCC 檔號 2026-003-2810-7 |
| **LinkedIn — Ian McClarty, President** | [linkedin.com/in/mcclarty](https://www.linkedin.com/in/mcclarty) | LinkedIn |
| **LinkedIn — William Bell, EVP Products** | [linkedin.com/in/williamb](https://www.linkedin.com/in/williamb) | LinkedIn |
| **LinkedIn — Ron Cadwell, CEO** | [linkedin.com/in/ron-cadwell-0b747313b](https://www.linkedin.com/in/ron-cadwell-0b747313b/) | LinkedIn |
| **LinkedIn — 公司頁** | [linkedin.com/company/phoenix-nap](https://www.linkedin.com/company/phoenix-nap) | LinkedIn |
| **現行定價與產品型錄**（用來追蹤 GPU 層是否改版） | [phoenixnap.com/bare-metal-cloud/instances](https://phoenixnap.com/bare-metal-cloud/instances) — 價格由 JS 注入；底層資料為 [api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) | phoenixNAP |
| **信箱規則 — 推導值，未經查證** | 六個獨立公開的 ARIN 信箱（`robertca`、`brianmu`、`draganp`、`milosi`、`adrianm`）得出規則：**名字＋姓氏前兩字母 @phoenixnap.com**。套用到高階主管會得出 **ianmc@phoenixnap.com** 與 **williamb@phoenixnap.com**。**屬推導，未經確認。不得視為已查證，也不要在沒有備援管道的情況下據此發冷信** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **任何高階主管之直撥** | **GAP — 未公開。** 僅有總機、支援專線與五位具名工程師的直撥號碼 | — |
| **具名 CFO 或採購聯絡人** | **GAP — 全網未識別** | — |

---

## 13. Supermicro 銷售切入點

### 分類：**既有客戶防守已部分失守 → 贏回（WIN-BACK），不是新開發，也不是對陌生對手的取代**

Supermicro **在這裡不是新供應商。** Supermicro 曾於 **2017 年 6 月**發布具名 phoenixNAP 案例研究，附總裁與產品副總引述，並在全球部署 **X11 BigTwin 與 Simply Double SuperStorage，加上 Rack Scale Design 與 Supermicro Server Manager**，還把 phoenixNAP 帶進 **Intel Early Ship 計畫**。近至 **2023 年 3 月**，ServeTheHome 仍將其 Sapphire Rapids 裸機執行個體記載為 Supermicro；phoenixNAP 至今仍維持一個**線上的 Supermicro 生態系頁面**，並在 **2025 年 6 月**共同舉辦 Supermicro 網路研討會。

**但最近兩次平台更新都被 HPE 拿走：** 2023 年 8 月的 Ampere ProLiant RL300 Gen11，以及 2025 年 4 月的 ProLiant Compute DL320 Gen12（DC-MHS）。連續兩個世代，由 HPE 發布，由 phoenixNAP 自家總裁與產品執行副總具名背書。**這個客戶是溫的、正在流失，不是冷的。**

### 這個業者獨有的切入口

**他們的加速器層被凍結，而且無人防守。** 整個 GPU 型錄是**同一台機器的三個分級**，圍繞 **2× Intel Data Center GPU Max 1100** 打造，約於 **2023 年 10 月**導入，此後 **約 34 個月**未動。**現行計費型錄中完全沒有任何 NVIDIA SKU，也沒有任何 AMD SKU**——支撐其自家定價頁的正式產品 JSON，全部 101 項產品中，`gpuConfigurations` 只有一個值：**「Intel Max 1100 GPU」**。同時，他們自家行銷頁只承認**六個計費區域中的兩個有 GPU 現貨**。

他們有 AI 故事——**Kaligent** 案例、**UC Berkeley 統計系**參考客戶、HPE 引用的 **adtech／fintech／SLED** 需求——卻只有**一款逐漸老化的加速器**可以支撐。**這個位置 HPE 沒有拿走。任何人都沒有拿走。**

### 金錢論證——把他們自己的牌價講回去

`d3.g2.c3.xlarge` 的牌價是 **36 個月預約 $920.23/mo**、**單月 $1,778.49/mo**。即使用寬鬆的模型（第 9 節），這也只支撐得起**每台約 $6,700–$10,000、18 個月回收**的硬體。而兩顆 Xeon Gold 6442Y 街頭價加上兩張 Max 1100 街頭價，**已經約 $27,000，還沒算記憶體、NVMe、機箱或網卡**。

**他們現在這台 GPU 機種，在市場硬體價格下付不起自己。** 那代表它要嘛是用計畫價買的、要嘛是用五年攤提、要嘛就是策略性的賠本引流。**這三種都是「該談另一台機器」的理由。**

而因為 UCC 紀錄顯示他們是**用銀行債務在自己的資產負債表上買**——BMO Bank N.A. 自 2014 年起未曾中斷，加上 **2026 年 3 月新增的 U.S. Bank Equipment Finance**——而不是向原廠融資子公司租，**每一塊錢的單機成本都落在他們的利息費用與折舊上。對這個買家而言，「每台部署成本」不是話術，而是整場對話本身。**

### 時機

**RadiusDC 交易於 2026 年 Q2 交割**，帶走了鳳凰城主機代管事業，讓 phoenixNAP 剩下**約 80% 的自己**，在結構上成為一家**裸機雲與網路公司**。他們的 UCC-1 節奏在 **2025 年 7 月至 2026 年 4 月間中位數約 33 天，然後在 2026-04-02 硬停**——切割期間四個月靜默。**這段暫停正在結束。** 下一筆融資撥款將支撐一支**純 BMC 機隊**，而加速器層是其中最外露的一條科目。**現在就接觸，趕在 9 月至 12 月的視窗之前。**

### 首次接觸的唯一資格問題

只問這一題，對象是 **William Bell, EVP of Products**：

> **「你們的 GPU 型錄從 2023 年底以來就是同一台雙 Max 1100 機器的三個分級，而且裡面完全沒有 NVIDIA 或 AMD 的選項——切割案之後要更新加速器層時，限制是矽晶供貨、是機箱，還是『能放在一台機器上、又能對照你們公開牌價回本』的那個價格？」**

這個問題**不回答就無法迴避地暴露出這是三場仗中的哪一場**：採購經濟學（**Supermicro 該贏的仗**）、已在 HPE 上的平台標準化（**比較難打的仗，但值得早點知道**），或是 Intel 的商業安排（**若是如此，就把 Supermicro 機箱定位為載具，而不是去攻擊矽晶選擇**）。

### Rule 8 — 經銷通路注意事項（撥號前必讀）

**這是一個有長期且有據可查歷史的回頭 Supermicro 買家**，因此**請預設已有既有的市場通路，並在任何報價之前先找出來。** 在尚未確認**他們歷史上與目前的 Supermicro 採購是否經由經銷商或 VAR、以及是否已有夥伴在此客戶上具備立場**之前，不要直接對其報價。

若已有夥伴在位，**請以具名該夥伴的方式登錄此機會，並讓報價經由該夥伴走。** 為了搶一個單機價格而繞過對方，付出的通路代價會超過這筆生意的價值，而且**一定會立刻曝光**——他們的採購與法務本來就把所有事情都對照一份已立約的授信在跑，一張沒預期到的直接發票不可能悄悄過關。

**順序——不得調換：** ① 依 Rule 8 釐清通路／經銷商歸屬 → ② 登錄 lead（Phoenix AZ ＝ West Coast South excl. CA ＝ **T1｜T31**，一組自有轄區，**CRM 於 2026-08-11 實查為乾淨，無 lead、無 account、無 do-not-call**）→ ③ 以上述唯一資格問題進行接觸。**轄區可乾淨註冊——請註冊，但要在通路問題有答案之後註冊，而不是假設它沒問題。**

---

## 14. 查證附錄

### 14.1 單一來源與低等級說法（引用前須再驗證）

| 說法 | 唯一來源 | 風險 |
|---|---|---|
| **Marcus Bohn ＝ 法務長**·**Cindy Anastasi ＝ 人資總監** | [RocketReach 管理層列表](https://rocketreach.co/phoenixnap-management_b5c0b21bf42e087f) | **僅資料商，無任何 phoenixNAP 官方確認。查證前不得於信件中使用這些職稱** |
| **Frank Eickenhorst ＝ VP Support Services & DC Ops**·**Seow Lim ＝ VP Architecture & Platform** | [Tracxn 側寫](https://tracxn.com/d/companies/phoenixnap/__mD8bU1wR9YlaxJnT-i3Qsq2RAnC6xvg1lhsYqyiFn0g) | **僅資料商。** Eickenhorst 已被列入採購決策圈——**使用職稱前務必確認** |
| **Stephanie Cadwell 為共同創辦人** | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) | **單一來源，且同一篇文章內文將姓氏寫成「Caldwell」。** 信心低至中 |
| **員工數約 183** | [Zippia](https://www.zippia.com/phoenixnap-careers-1559024/revenue/) | **無可見方法論的第三方估計。** 請用 150–300 區間並標示為估計值 |
| **營收 $18–25m** | Zippia／Kona Equity | **幾乎確定是錯的**——與對外行銷 EBITDA USD 70m 無法調和。**不得登錄 CRM** |
| **鳳凰城廠房 2009 年以 USD 6.3m 購入；約 200,000 平方英尺** | [DataCenterDynamics](https://www.datacenterdynamics.com/en/news/radiusdc-enters-arizona-acquires-phoenixnap-facility-in-phoenix/) — **直接抓取回 HTTP 403，內容僅由搜尋摘要取得** | 次級媒體數字，**未於來源端查證，亦未經任何郡級紀錄佐證** |
| **2024–2026 年仍在使用 Supermicro** | [phoenixnap.com/offers/supermicro-servers](https://phoenixnap.com/offers/supermicro-servers) | **該頁面沒有型號、沒有日期。** 等級為 **circumstantial（旁證）**。**不得將「目前部署 Supermicro」陳述為事實** |
| **第三方清單文章稱其提供「L4 到 H100」** | 各家資料商 | **與 phoenixNAP 自家定價系統相牴觸。** 屬資料商雜訊——**不得複述** |

### 14.2 互相矛盾的數字（併陳，不擇一）

**營收**

| 來源 | 數字 |
|---|---|
| Zippia／Kona Equity（資料商） | **$18–25m** |
| [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) — 進行中之出售程序 | **對外行銷 EBITDA USD 70m**，第一輪出價**突破 USD 1bn**，倍數 **14.3x EV/EBITDA**（前一年 EBITDA 報導為 USD 50m） |
| [ION Analytics／Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/) | Goldman Sachs 籌備 **2025 年 Q1 的全公司出售** |

**判斷，非結論：** 一家 EBITDA 有 $70m 的公司不會是營收 $18m 的公司。**資料商數字應予捨棄。** 可辯護的工作假設是**營收在數億美元等級**、EBITDA 約 $70m（**對外行銷值**）——並請注意 RadiusDC 切割之後，phoenixNAP 保留其自述之**約 80% 全球業務**。**本次未取得任何權威營收數字。**

**GPU 區域供應**

| 來源 | 區域 |
|---|---|
| [GPU 行銷頁](https://phoenixnap.com/bare-metal-cloud/gpu-servers) | **Phoenix (AZ) 與 Ashburn (VA)**，「More Coming Soon」 |
| [現行計費型錄](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) | **PHX、ASH、NLD、SGP、CHI、SEA** — 六個全有，價格相同 |

**這不是可以拿來指摘的矛盾——應讀為規模小而集中的機隊，搭配全球佈建的定價。** 見第 6 節。

**次要 ASN**

| 來源 | 主張 |
|---|---|
| 第三方 BGP 工具／IPinfo | **AS59210** 與 **AS207134** 屬 phoenixNAP |
| [ARIN RDAP](https://rdap.arin.net/registry/autnum/12189) | AS59210 解析到 **APNIC** 區塊；AS207134 解析到 **RIPE** 區塊——**兩者皆未於來源端確認** |

**未解。請將 AS12189 視為唯一經查證之 ASN。**

### 14.3 未結 GAP

1. **UCC 擔保品文字——最大的單一缺口。** 20 筆亞利桑那歸檔全數定位並抄錄，但 AZ SOS 公開檢視器**不呈現擔保品描述、也不提供歸檔影像**。**一條擔保品條款都沒看到，也沒有任何改寫轉述。** 頁數是唯一代理指標（2025-08-06 那筆長達 **16 頁**，2026-01-28 修正為 **10 頁**——都是長清冊）。**解法：** 向 **AZ SOS Business Services, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187** 申請 UCC-11 資訊請求或認證影本，優先 **2025-002-9842-8**、**2026-001-2461-6**、**2026-001-2475-0**、**2026-001-0311-3**。
2. **亞利桑那州公司委員會登記——未取得任何幹部、經理人、成員、法定代理人、年報簽署人或歸檔沿革。** 舊 `ecorp.azcc.gov` 為 **NXDOMAIN**；替代入口對非瀏覽器回 **403**，並以 **6 字元圖形 CAPTCHA** 阻擋結果，本檔不解 CAPTCHA。OpenCorporates（HAProxy CAPTCHA）與 Bizapedia（security check）亦遭封鎖。**本檔的實體關係圖來自 UCC 與 ARIN，不是來自登記機關。**
3. **德拉瓦州——`icis.corp.delaware.gov` 未查詢。** 其他途徑未查得德拉瓦實體，且亞利桑那 LLC 的正確 UCC 歸檔機關就是亞利桑那，但**無法排除德拉瓦控股公司**，而 **Cleary Gottlieb 擔任 RadiusDC 案賣方律師，使控股架構具相當可能性**。
4. **歷史 WHOIS——未取得。** whoisrequest.com 回 **Cloudflare 403**；whoxy 與 securitytrails 需付費 API 金鑰。僅有現行 RDAP：phoenixnap.com 建立於 **2009-02-26**，2027-02-26 到期，最後異動 2026-01-27，註冊商 **NameCheap**，名稱伺服器 **Cloudflare（ALEENA／MICAH）**，登記人**隱私保護**。**無任何歷史登記人姓名或地址。**
5. **USPTO——未於來源端取得任何商標紀錄。** `tsdrapi.uspto.gov` 回 **HTTP 401**（現需註冊 API 金鑰）；`tmsearch.uspto.gov` 回 **HTTP 405**；`uspto.report` 回 **403**；`assignment-api.uspto.gov` 連線失敗。搜尋結果顯示 **Phoenix NAP L.L.C. 至少持有 SECURED SERVERS（序號 87396103）與 HAAS（序號 85655621）**，但**未從任何一手來源取得宣誓書簽署人、通訊代理人或代理律師、申請或展延日期、所有權人地址**。
6. **FEC——沒有任何主要人員實際完成篩查。** `api.open.fec.gov` 在共用 DEMO_KEY 下每次都回 **OVER_RATE_LIMIT**，fec.gov 瀏覽介面未渲染資料列。**記為未查證，而非「查無紀錄」。** 需個人 `api.data.gov` 金鑰，對 Ron Cadwell、Ian McClarty、William Bell 與 Stephanie Cadwell／Caldwell 重跑。**州級（亞利桑那州州務卿）與鳳凰城市級競選財務資料庫亦未查詢。**
7. **馬里科帕郡估價官——未取得地籍紀錄**，3402 E University Dr 與 2353 W University Dr（Tempe）皆無。`mcassessor.maricopa.gov` 搜尋結果由 AJAX 載入，`/mcs/api/` 端點在無授權 token 時只回 HTML 外殼。**無 APN、無估價、無登記契據、無抵押設定紀錄，也沒有 RadiusDC 移轉的任何紀錄。** 目前僅有次級媒體數字（2009 年 USD 6.3m、約 200,000 平方英尺）。
8. **伺服器與 GPU 台數——完全未知。** 沒有任何公開數字，**本檔亦不虛構**。僅有邊界值：**6 個計費區域、82 個伺服器 SKU、16 個 PeeringDB 據點、僅 2 個區域承認 GPU 現貨**、ARIN 配置量級約為**數十萬個 IPv4 位址**，以及一座約 200,000 平方英尺的旗艦廠房——其 8 MW 擴充目標反推目前佔用 IT 負載**遠低於 8 MW**。
9. **BOM 元件價格——僅兩項有來源。** Xeon Gold 6442Y 街頭價 **$5,580.56**（Newegg），Intel Max 1100 約 **$8,000** 起始零售（2025 年 4 月資料點）。**512 GB DDR5 RDIMM 組、4× 2 TB NVMe、雙路 GPU 機箱、電源與 25 GbE 網卡皆無來源價格，對等機箱的 Supermicro 定價或街頭價亦無。**
10. **營運成本輸入值——全為假設。** 每台 GPU 機種耗電、鳳凰城與 Ashburn 電價、機櫃成本、使用率**皆未查證。第 9 節的成本天花板區間是模型，不是查證發現。**
11. **GPU 機種的機箱供應商——無從歸屬。** 沒有任何人公開過 `d3.g2.*` Intel Max 1100 機種由誰製造。HPE 在 Ampere Altra（RL300 Gen11）與 Xeon 6（DL320 Gen12）上已確認；Supermicro 在 X11 BigTwin 上已確認、在 Sapphire Rapids 上為旁證。**GPU 機箱、AmpereOne A96-36X 機箱與 AMD EPYC 4000 系列機箱三者皆無歸屬——三個空著的競爭位置。**
12. **AmpereOne `a2.c9.*` 導入日期——未能定年。** 2026-08-10 已在現行計費型錄中，但**未出現在任何已存檔的 instances 頁面快照**。Wayback 自 **2025 年 10 月**才開始擷取 `api-data.json` 價格檔；對那約 50 個快照做 diff 即可定年，**同時還能產出精確的價格變動史**。**因時間限制未執行——這是本檔 CP 值最高的後續動作。**
13. **GPU 首次出現的精確度**——夾在 **2023-09-13（未出現）**與 **2023-11-09（已出現）**之間，並由 2023-09-19 的 phoenixNAP 預購推廣佐證。**因 Wayback 對重複原始擷取施加速率限制，未能再收斂。**
14. **前三位以下的高階主管名冊——僅資料商。** Marcus Bohn、Cindy Anastasi、Frank Eickenhorst 與 Seow Lim 僅來自 RocketReach、Comparably 與 Tracxn。**phoenixNAP 沒有官方領導層頁面**——`phoenixnap.com/company/leadership` 回 **404**。**職稱未確認；查證前不得用於信件。**
15. **未識別出 CFO。** 對一家每月透過兩家銀行融資買機隊的公司而言，**這是採購決策圈的實質破口。**
16. **徵才啟事——資料很薄。** 僅查得一則鳳凰城 **Data Center Technician** 職缺（$21–30/hr）。**未查得任何採購、供應鏈、產能規劃或 GPU／ML 基礎設施職缺**，而那本來會是機隊擴建最好的領先指標。
17. **法院案卷——僅 metadata，未讀取書狀。** CourtListener 回 **17 筆**。其中兩筆直接關於 phoenixNAP：***Phoenix NAP LLC v. Poofless LLC et al.***，D. Ariz. **2:19-cv-05005**，2019-08-21 立案、2020-06-03 終結（phoenixNAP 為**原告**；被告含 Poofless LLC、Poofless1 LLC、Cosmic Games ULC、Preston Arsement、Joe Melsha 與 Anthony Uckon）；以及 ***Stanziale, Jr. v. Phoenixnap***，Bankr. D. Del. **16-50054**，2016-02-19 立案、2016-07-11 終結（與 EP Liquidation LLC 破產財團相關之附屬程序，**幾乎可以確定是偏頗行為追回**）。**兩件案卷皆未讀取。馬里科帕郡高等法院完全未查詢。**
18. **營收——無法調和。** 見 14.2。**未取得權威數字。**
19. **出售程序的結果——未解，而且在商業上很重要。** 全公司出售程序在 2025 年進行、出價突破 USD 1bn；**唯一明確完成的只有 2026 年 Q2 將鳳凰城主機代管事業切給 RadiusDC。** 公司其餘部分究竟是**已出售、部分再資本化，還是撤出市場，並不清楚——而這直接決定下一份資本支出計畫由誰簽核。** 這應該是任何高層接觸前第一件要查清楚的事。
20. **次要 ASN——未測繪。** 見 14.2。
21. **HPE 新聞室頁面直接抓取逾時。** 2023-08-03 與 2025-04-04 兩則 HPE 新聞稿**兩次抓取皆逾時**、curl 亦未產出檔案，內容係經**搜尋摘要與鏡像站**（InsideHPC、DCD、Morningstar、Nasdaq、Silicon UK、HostingJournalist）取得。各鏡像的引述與產品名稱一致，但**HPE 一手頁面並未直接讀取**。
22. **重跑時的工具備註。** ZoomInfo MCP 連接器——連同 carta、figma、atlassian、spglobal 與 adobe——需要 OAuth 授權，本次非互動式工作階段無法使用。**透過 claude.ai 連接器設定授權 ZoomInfo 連接器，重跑時很可能可以補上營收估計、CFO 與具名人員的缺口。**
