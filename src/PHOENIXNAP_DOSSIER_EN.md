# phoenixNAP — Sales Intelligence Dossier
**Prepared for:** Supermicro Sales Team 1 (USA) · Officer US8664 Tuo Cheng · **Date:** 2026-08-11
**Method:** Researched through corporate history, financial and registry records, U.S. political leanings, legislative and policy positions, and the company's relationships with its customers. Privately held — evidence comes from state business registries, ARIN/PeeringDB, the operator's own published GPU catalogue and pricing, UCC filings, job postings, community forums and FEC records. Every fact carries its source + date inline. GAP = not found in verified material. No fabrication.
**Territory:** Phoenix, Arizona — West Coast South excl. CA = **T1** | T31. Team 1 can register directly.
**CRM status:** Verified clean 2026-08-11 in salesleads Search (Type = All) — no lead, no account, no do-not-call record. Registrable by Team 1.

---

## 1. Bottom line

phoenixNAP is a 2009-founded, founder-owned Arizona bare-metal-cloud, colocation and network operator running **AS12189** out of a 200,000 sq ft flagship facility at 3402 E. University Drive, Phoenix, with sixteen registered PeeringDB facilities across five continents and six live billing regions ([ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) · [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)). Commercially this is a **win-back, not a greenfield and not a displacement of a stranger**: Supermicro published a named phoenixNAP case study in June 2017 — X11 BigTwin, Simply Double all-flash SuperStorage, Rack Scale Design, Supermicro Server Manager, with on-record quotes from President **Ian McClarty** and then-VP of Products **William Bell** ([Supermicro case study, 2017-06](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)) — and ServeTheHome documented their Sapphire Rapids bare-metal instances as Supermicro as recently as March 2023 ([ServeTheHome, 2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)). But **the last two platform refreshes both went to HPE**: ProLiant RL300 Gen11 on Ampere in August 2023 and ProLiant Compute DL320 Gen12 with Intel Xeon 6 in April 2025, both announced by HPE and both quoted by phoenixNAP's own President and EVP of Products. The account is warm and slipping.

The single most attackable line in the business is the accelerator tier. I pulled the production product/price JSON that backs phoenixNAP's own pricing pages — all 101 products — and **the only `gpuConfigurations` value in the entire file is "Intel Max 1100 GPU"**. Three SKUs, three CPU bins, one accelerator, introduced around October 2023 and untouched for roughly 34 months. **There is no NVIDIA SKU and no AMD Instinct SKU anywhere in the live catalogue** ([phoenixNAP live catalogue JSON, pulled 2026-08-10](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)). Their own marketing page admits GPU stock in only two of the six regions where the billing system prices it ([GPU servers page](https://phoenixnap.com/bare-metal-cloud/gpu-servers)). They have an AI story — a named AI customer case study, and HPE citing adtech/fintech/SLED demand — and effectively one aging accelerator to serve it with. HPE did not win that slot. Nobody did.

The timing is unusually clean. The Arizona Secretary of State UCC record shows **20 filings**, an unbroken BMO (Harris) Bank equipment-and-asset relationship since 2014, and a **~33-day median interval between new secured tranches from July 2025 to April 2026** — then a hard stop on 2026-04-02, four months of silence spanning exactly the Q2 2026 close of the RadiusDC colocation carve-out ([AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/) · [PRNewswire, 2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html)). They finance hardware with bank debt on their own balance sheet — **no Dell Financial Services, no HPEFS, no Cisco Capital, no captive lessor appears anywhere on the record** — so every dollar of node cost lands on their own depreciation and interest. Price-per-deployed-node is not a talking point for this buyer; it is the entire conversation. The next financing tranche will underwrite a bare-metal-cloud-only fleet, and the accelerator tier is the most exposed line in it.

The one thing that can kill the deal is the channel. This is a returning Supermicro buyer with a long history, so under Rule 8 the distributor position must be established **before** anyone quotes — see §13.

---

## 2. Snapshot

| Field | Value | Evidence / date |
|---|---|---|
| **Legal entity** | **PHOENIX NAP, LLC** (styled "phoenixNAP"; ARIN org name "PhoenixNAP LLC", handle **PHOEN-56**). Affiliated/co-obligor entities proven by UCC: **SECURED SERVERS, LLC** (holds the 131.153.0.0/16 IP block, ARIN handle SSL-65) · **CC PROPERTY INVESTMENTS, LLC** (property arm, Tempe AZ) · **PHOENIX NAP MANAGEMENT RESOURCES LLC** (separate BMO Harris debtor since 2019). "PHOENIXNAP" also appears as co-debtor with **ALTAY CORPORATION** on a 2022 Express Computer Systems filing | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) · [AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/), 20 filings transcribed in §8 |
| **State of organisation** | **Arizona (domestic).** No Delaware operating or holding entity was found. Delaware appears only as the venue of an unrelated 2016 bankruptcy adversary proceeding (*Stanziale v. Phoenixnap*). **GAP: the Delaware registry itself was not searched** — see §14 | Arizona is the correct UCC filing office for an Arizona LLC under UCC §9-301/§9-307, which is why all 20 filings sit in Arizona |
| **Registry evidence** | **BLOCKED AT THE REGISTRY ITSELF.** Legacy portal `ecorp.azcc.gov` no longer resolves (**NXDOMAIN**). Its replacement returns **HTTP 403** to non-browser clients and, driven in a real browser with Business Name = "PHOENIX NAP", interposes a **6-character image CAPTCHA** ("User validation required to continue") before releasing results. **CAPTCHAs are not solved**, so no officer, manager, member, statutory-agent record, no annual-report signatory and no filing history were obtained. OpenCorporates (HAProxy CAPTCHA) and Bizapedia (security check) were also blocked. **The entity map above is evidenced by the UCC record and ARIN RDAP, NOT by the corporate registry** | [ArizonaBusinessCenter.azcc.gov/businesssearch](https://arizonabusinesscenter.azcc.gov/businesssearch), attempted 2026-08-10 |
| **Founded** | **2009** — four independent anchors: Supermicro's June 2017 case study states "Founded in 2009, phoenixNAP…"; domain phoenixnap.com created **2009-02-26**; the Phoenix DC property at 3402 E University Dr was purchased in **2009 for USD 6.3m**; ARIN autnum **AS12189 registered 2009-07-23** | [Supermicro case study](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf) · [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) · Verisign RDAP for phoenixnap.com |
| **HQ (verified address)** | **3402 E. University Drive, Suite 420, Phoenix, AZ 85034-7200** — flagship datacenter and corporate HQ on the same campus. Secondary/affiliate address used on filings: **2353 W University Drive, Tempe, AZ 85281-7223** (CC Property Investments, Secured Servers, Phoenix NAP Management Resources) | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) (org PHOEN-56) · AZ SOS UCC file **2026-003-2810-7**, which renders the Suite 420 form of the address |
| **Ownership** | **Founder-owned, no disclosed outside equity.** New Project Media reports the company was "established in 2009 by Stephanie Cadwell and Ron Cadwell"; Infralogic reports third-party equity backing was **not clear**. **GAP: no cap table, no equity split, no ownership filing obtained** | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) · [ION Analytics / Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/) |
| **Headcount** | **~183 (third-party estimate — Zippia aggregation).** LinkedIn and other aggregator ranges vary. **Honest working band: 150–300.** Engineering is split Phoenix AZ / Belgrade / Malta — evidenced by +381 and +356 phone numbers on named ARIN technical contacts | [Zippia](https://www.zippia.com/phoenixnap-careers-1559024/revenue/) (estimate) · [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) (primary, for the geography) |
| **Revenue** | **TWO IRRECONCILABLE SOURCES, and the low one is almost certainly wrong.** Aggregators (Zippia, Kona Equity) put revenue at **$18–25m — treat as unreliable third-party estimates**. Against that, trade press covering a live sale process reports **USD 70m marketed EBITDA** (up from USD 50m the prior year) with first-round bids **topping USD 1bn at 14.3x EV/EBITDA**. A business with $70m EBITDA is not an $18m-revenue business. **This dossier discards the aggregator figures and asserts no precise revenue number**; the defensible working assumption is low-to-mid hundreds of millions USD | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) · [ION Analytics / Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/) · [Zippia](https://www.zippia.com/phoenixnap-careers-1559024/revenue/) |
| **CRM $100M threshold** | On the trade-press figures this account plausibly **clears** the $100M threshold. On the aggregator figures it does not. **The two cannot both be true — do not enter a revenue figure in CRM as fact until one is sourced authoritatively.** Note the marketed EBITDA is a *sell-side marketing* number reported by trade press, not an audited disclosure | See §14 for the side-by-side |
| **ASN** | **AS12189 — PhoenixNAP LLC.** ARIN handle PHOEN-56, autnum registered **2009-07-23**, last changed **2026-04-06**. IRR AS-SET **LEVEL3::AS-PHOENIXNAP**. Separately, **131.153.0.0/16 is registered to SECURED SERVERS LLC** (ARIN handle SSL-65) with identical phoenixNAP technical contacts | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) · [ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **Structural event in progress** | **RadiusDC is acquiring the Phoenix data center and colocation business** — announced 2026-03-12, expected to close Q2 2026. phoenixNAP retains what it describes as **approximately 80% of its global business**, explicitly including Bare Metal Cloud and the network platforms, and **remains a tenant** in the facility | [PRNewswire, 2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) · [DataCenterDynamics](https://www.datacenterdynamics.com/en/news/radiusdc-enters-arizona-acquires-phoenixnap-facility-in-phoenix/) |
| **CRM status** | **Verified clean 2026-08-11** — no lead, no account, no do-not-call | salesleads Search (Type = All) |
| **Territory / team** | Phoenix, AZ → West Coast South excl. CA = **T1 \| T31** → Team 1's own territory, direct registration | Territory Map-Jan.2026 (Rev.1), Sales Territory Assign tab |

---

## 3. Leadership & ownership

Evidence grades used in this section: **primary-record** = internet-number registry, court docket, campaign-finance filing, official state filing, or the company's own published page · **corroborated** = two or more independent secondary sources agree · **single-source** = one secondary source only · **aggregator-only** = third-party data vendor with no primary confirmation, **do not use in an email until verified** · **GAP** = nothing found after a named search.

Two framing facts before the table. First, **phoenixNAP publishes no leadership page** — `phoenixnap.com/company/leadership` returns **HTTP 404**. Every executive name below therefore comes from a vendor press release, a trade-press M&A report, an official filing, or an aggregator, and each is graded accordingly. Second, **registry officers and network contacts are listed as rows in their own right and labelled as such**: an ARIN OrgTech is a named human being who personally validated a published, legitimately public contact route, and on this account those five engineers are the highest-confidence named people in the entire file — higher than most of the executives.

### 3.1 Named people

| Name | Title | Role type | Evidence grade | Public contact route | FEC record | Source |
|---|---|---|---|---|---|---|
| **Ron Cadwell** | **Founder & Chief Executive Officer** | **Economic buyer / ultimate owner** | **corroborated** (two independent trade-press reports plus the company's own blog byline) | No published direct address. Corporate switchboard **+1-480-422-2022** (the ARIN admin POC number). [LinkedIn](https://www.linkedin.com/in/ron-cadwell-0b747313b/). **Derived, unverified** email pattern would give `ronca@phoenixnap.com` — see the pattern row in §12 and **do not use it as confirmed** | **UNVERIFIED — portal/API blocked, NOT "no record found".** `api.open.fec.gov` schedule_a returned `{"error":{"code":"OVER_RATE_LIMIT"}}` on the shared DEMO_KEY across three attempts, and the fec.gov results page rendered no data rows to fetch | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) · [ION Analytics / Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/) · [phoenixNAP blog byline](https://phoenixnap.com/blog/ron-cadwell-devops) |
| **Stephanie Cadwell** | **Co-founder (2009)** | Owner / non-operating | **single-source** | **GAP** — no LinkedIn located, no published route | **UNVERIFIED — not searched.** The surname spelling is itself unresolved across sources, so a search would not have been reliable | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) — **note the same article inconsistently renders the surname "Caldwell" in body text while the company uses "Cadwell"** |
| **Ian McClarty** | **President** (and co-founder per several profiles) | **Champion / senior sponsor for hardware decisions** | **primary-record** — quoted by name in four separate dated vendor communications spanning 2017–2026 | No published direct address. [LinkedIn](https://www.linkedin.com/in/mcclarty). Forbes Technology Council profile is public | **UNVERIFIED — portal/API blocked** (same OVER_RATE_LIMIT condition) | [Supermicro case study, 2017-06](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf) · [NVIDIA Tesla press release, 2018-10-01](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus) · [HPE RL300 Gen11 release, 2023-08-03](https://www.hpe.com/us/en/newsroom/press-release/2023/08/phoenixnap-powers-expanded-ai-and-cloud-services-with-energy-saving-ampere-based-servers-from-hewlett-packard-enterprise.html) · [RadiusDC release, 2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) |
| **William Bell** | **Executive Vice President of Products** (VP of Products in 2017–2018 material) | **Technical / product decision maker — the real hardware selector** | **primary-record** — quoted on the specific silicon in three separate generations | No published direct address. [LinkedIn](https://www.linkedin.com/in/williamb) | **UNVERIFIED — portal/API blocked.** Note also that "BELL, WILLIAM" is a **high-collision name**; any hit would require employer, occupation and Phoenix-metro address matching before attribution | [Supermicro case study, 2017-06](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf) · [NVIDIA Tesla press release, 2018-10-01](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus) · [HPE DC-MHS / Xeon 6 release, 2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html) |
| **Robert Carmody** — *network registry row* | **ARIN technical contact, handle CARMO67-ARIN** | **Operational / network engineering — verifiable direct line** | **primary-record** — self-published operational contact, not scraped | **robertca@phoenixnap.com · +1-480-506-0120** | Not searched — operational staff, out of scope for principal screening | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) · [ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **Brian Musgrave** — *network registry row* | **ARIN technical contact, handle MUSGR48-ARIN** | Operational / network engineering | **primary-record** | **brianmu@phoenixnap.com · +1-480-401-0309** | Not searched — operational staff | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Dragan Petrovic** — *network registry row* | **ARIN technical contact, handle PETRO182-ARIN** | Operational / network engineering — **EMEA** | **primary-record** | **draganp@phoenixnap.com · +356 77548965 (Malta) · +381 621448366 (Serbia)** | Not searched — operational staff | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Milos Ilic** — *network registry row* | **ARIN technical contact, handle ILICM-ARIN** | Operational / network engineering — Serbia | **primary-record** | **milosi@phoenixnap.com · +381 615494754** | Not searched — operational staff | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Adrian Montebello** — *network registry row* | **ARIN technical contact, handle MONTE41-ARIN** | Operational / network engineering — Malta | **primary-record** | **adrianm@phoenixnap.com · +356 79305305** | Not searched — operational staff | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **"Admin" (group)** — *network registry row* | **ARIN OrgAdmin, handle ADMIN1723-ARIN**, for AS12189 and the Secured Servers 131.153.0.0/16 object | **Registry contact — ROLE ACCOUNT, NO INDIVIDUAL NAMED (GAP)** | **primary-record** (that it is a role account) | **ipadmin@phoenixnap.com · +1-480-422-2022 ·** 3402 E. University Dr. Suite 420, Phoenix AZ 85034 | n/a | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **"IPADMIN"** — *network registry row* | **Technical POC, handle IPADM294-ARIN**, on the **Secured Servers LLC** 131.153.0.0/16 net object | **Registry contact — ROLE ACCOUNT (GAP)** | **primary-record** | **ipadmin@phoenixnap.com** | n/a | [ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **"Abuse" / "Tech" (groups)** — *network registry row* | **OrgAbuse ABUSE2349-ARIN and ABUSE1536-ARIN; NOC/support group POC TECH357-ARIN** | **Registry contacts — ROLE ACCOUNTS (GAP)** | **primary-record** | **abuse@phoenixnap.com · +1-480-422-2022** · **support@phoenixnap.com · +1-480-646-5362** | n/a | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **PeeringDB contacts** — *network registry row* | — | **Network contacts (PeeringDB) — NONE PUBLISHED (GAP)** | **primary-record** (that the set is empty) | `poc_set` on net 2932 is **empty**; record last updated **2026-03-25**. No policy, technical or NOC individual is published there | n/a | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932) |
| **Marcus Bohn** | **Chief Legal Officer** *(claimed)* | Legal / contract gate on any master purchase or financing agreement | **aggregator-only — LOW.** Not confirmed on any phoenixNAP-published page. **Do not use this title in an email until verified** | **GAP** | **UNVERIFIED — not searched** | [RocketReach management listing](https://rocketreach.co/phoenixnap-management_b5c0b21bf42e087f) |
| **Cindy Anastasi** | **Human Resources Director** *(claimed)* | Non-buying | **aggregator-only — LOW** | **GAP** | **UNVERIFIED — not searched** | [RocketReach management listing](https://rocketreach.co/phoenixnap-management_b5c0b21bf42e087f) |
| **Frank Eickenhorst** | **VP, Support Services & Data Center Operations** *(claimed)* | Operations — influences rack, thermal and serviceability requirements | **aggregator-only — LOW.** No phoenixNAP-published confirmation obtained | **GAP** | **UNVERIFIED — not searched** | [Tracxn profile](https://tracxn.com/d/companies/phoenixnap/__mD8bU1wR9YlaxJnT-i3Qsq2RAnC6xvg1lhsYqyiFn0g) |
| **Seow Lim** | **VP of Architecture and Platform** *(claimed)* | Technical architecture — platform / BMC design authority | **aggregator-only — LOW** | **GAP** | **UNVERIFIED — not searched** | [Tracxn profile](https://tracxn.com/d/companies/phoenixnap/__mD8bU1wR9YlaxJnT-i3Qsq2RAnC6xvg1lhsYqyiFn0g) |

**Explicit warning on the FEC rows:** every "UNVERIFIED" above means the query was **rate-limited or rendered nothing**, not that a clean search came back empty. `api.open.fec.gov` returned `OVER_RATE_LIMIT` on the shared DEMO_KEY on every attempt, and the fec.gov browse UI returned the search form with no data rows. **No principal on this account has actually been screened. Do not record any of these as "no record found."**

### 3.2 Registry record

Note the boundary carefully. **The Arizona Corporation Commission — the corporate registry that would name officers, managers, members, the statutory agent and annual-report signatories — was NOT reached.** Everything below is either an **internet-number registry** (ARIN) or the **Arizona Secretary of State UCC register**, which is registry-adjacent official record but is a lien index, not a corporate register.

| Name | Capacity | Filing | Filing date | Source |
|---|---|---|---|---|
| **NO OFFICER RECORD OBTAINED** | n/a | **Arizona Corporation Commission — Arizona Business Center (formerly eCorp) business search.** Legacy host `ecorp.azcc.gov` returns **NXDOMAIN**; current host `arizonabusinesscenter.azcc.gov` returns **HTTP 403** to curl and presents a **6-character image CAPTCHA** in-browser before releasing results. `ecorptestonline.azcc.gov/EntitySearch` renders a live landing page but every search route 404s. **No annual report, no articles of organization, no manager/member list, no statutory agent, no signatory captured.** Delaware `icis.corp.delaware.gov` **not reached** | attempted **2026-08-10** | [arizonabusinesscenter.azcc.gov/businesssearch](https://arizonabusinesscenter.azcc.gov/businesssearch) |
| **PHOENIX NAP, LLC** | **Debtor of record** (Arizona Secretary of State UCC) | **18 UCC-1 financing statements** name PHOENIX NAP, LLC as debtor — full text of every one in §8. Address of record migrates from **2353 W. University Drive** (2014) → **3402 E University Dr** (2022 onward) → **3402 E University Dr. Suite 420** (2026) | **2014-07-08 through 2026-07-22** | [AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/) |
| **SECURED SERVERS, LLC** | **Co-debtor on every BMO facility 2014–2026**; separately the **ARIN registrant (handle SSL-65) of 131.153.0.0/16** | Named as co-debtor on 16 BMO filings: 201400214595, 202200504921, 202200505528, 202400214184, 202400278438, 202400409257, 202500024233, 202500258880, 202500298428, 202500335016, 202500404699, 202500459045, 202600027546, 202600124616, 202600124750, 202600151100. Address **2353 W UNIVERSITY DR, TEMPE, AZ 85281-7223** | 2014-07-08 through 2026-04-02 | [AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/) · [ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |
| **CC PROPERTY INVESTMENTS, LLC** | **Co-debtor on every BMO facility 2014–2026** (property / real-asset arm; the initials are **plausibly** Cadwell — *inference, not a filing*) | Named as co-debtor on the same 16 BMO filings as Secured Servers. Address **2353 W UNIVERSITY DR, TEMPE, AZ 85281-7223** | 2014-07-08 through 2026-04-02 | [AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/) |
| **PHOENIX NAP MANAGEMENT RESOURCES LLC** | **Separate debtor entity**, BMO Harris Bank N.A. | UCC file **201900069940**, new filing 2019-02-13, continued 2023-12-26, expires 2029-02-13. Address **2353 W UNIVERSITY DR, TEMPE, AZ 85281** | 2019-02-13 | [AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/) |
| **PhoenixNAP LLC** | **ARIN Org handle PHOEN-56** — registrant of AS12189 and 12 network objects | ARIN Org record, 3402 E. University Drive, Phoenix AZ 85034 | autnum registered **2009-07-23**; last changed **2026-04-06** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) · [ARIN RDAP entity PHOEN-56](https://rdap.arin.net/registry/entity/PHOEN-56) |
| **Secured Servers LLC** | **ARIN Org handle SSL-65** — registrant of 131.153.0.0 – 131.153.247.255, with **identical phoenixNAP technical contacts**. This is what proves the affiliation independently of the UCC record | ARIN network object | as retrieved 2026-08-10 | [ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0) |

### 3.3 Buying committee

phoenixNAP is a **founder-owned company with no publicly named CFO**, financing hardware monthly through two banks. The path from technical validation to signature is short, but the technical gate is real: the same EVP of Products has been quoted on the silicon in every generation since 2017, and he is the person who decides what the next accelerator is.

| Name | Why they matter for a server purchase | How to approach |
|---|---|---|
| **William Bell** — EVP of Products | **He is the decision.** The only executive quoted across all four hardware generations: Supermicro X11 in 2017, NVIDIA Tesla V100/P40 in 2018, HPE/Ampere in 2023, HPE/Intel Xeon 6 in 2025. He owns the instance catalogue, so he owns what the next GPU SKU is. He has publicly framed cost as the constraint — that high cost should never inhibit innovation or performance | **Lead with the catalogue, not the company.** Open on two verifiable facts: `d3.g2.*` has not been refreshed since late 2023, and **there is no NVIDIA or AMD accelerator SKU in the live BMC price catalogue at all**. Offer a node-level TCO model for a Supermicro GPU chassis that fits inside the **$920–$1,778/mo/node price envelope he already publishes**. Do not open with a product deck |
| **Ian McClarty** — President | Signs the vendor relationship and appears in the vendor press. He **personally endorsed Supermicro in 2017** on exactly the criteria that still matter to a multi-region operator — global distribution network, spares, onsite service teams. He is also the named phoenixNAP voice on the RadiusDC divestiture, so he owns the post-divestiture story | **Reactivate, do not pitch cold.** Reference his own 2017 criteria back to him and ask what changed. The honest question is whether **Supermicro lost the 2023–2025 refresh cycles to HPE on supply and finance terms or on product**, because both new generations went to HPE |
| **Ron Cadwell** — Founder & CEO | Owner-operator with no disclosed outside equity, running a business marketed at ~USD 70m EBITDA with first-round bids above USD 1bn, that has just carved out its Phoenix colo. Any multi-million-dollar fleet commitment in the next 12 months is his call, and it is now a **pure bare-metal-cloud capital decision** rather than a colo one | **Do not approach first.** Approach only after Bell has validated a config, then frame it as capital efficiency: dollars-per-deployed-GPU-node and payback months **against his own published rate card**, not as a product pitch |
| **Frank Eickenhorst** — VP Support Services & Data Center Operations **(title unverified — aggregator-only)** | Owns serviceability, spares depots and the 24×7 floor across PHX/ASH/CHI/SEA/AMS/BEG/SGP. In 2017 the deciding factor was explicitly **global distribution and replacement parts**, not spec sheets | **Bring the logistics answer, not the compute answer:** RMA turnaround by region, spares depot coverage for AMS/BEG/SGP, rack-integration options. **Confirm the title before using it** |
| **Robert Carmody / Brian Musgrave** — named ARIN technical contacts | Real, self-published engineers with direct phone lines. They are **not** the buyers, but they are the fastest verifiable route to whoever specifies the GPU node, and they can tell you in one call whether the Max 1100 fleet is being refreshed | **Single qualifying call, no pitch.** These are network/IP contacts — keep the ask narrow and technical, then hand off to the product org |
| **Marcus Bohn** — Chief Legal Officer **(unverified — aggregator-only)** | Only relevant late. **BMO Bank N.A. holds a rolling blanket of equipment financing statements**, so any new hardware purchase has to be papered against or alongside that facility | **Do not contact directly.** Expect him at the master-agreement stage; be ready for lender consent and intercreditor language given the BMO filings |

### 3.4 Unfilled roles — every one a GAP

**GAP — NO CFO / VP FINANCE / CONTROLLER IDENTIFIED.** For a company that finances its fleet roughly monthly through two banks, the absence of a named finance leader is the single biggest hole in this buying committee. No name appears in any vendor release, trade-press report, aggregator listing or filing. · **GAP — no procurement, supply-chain or vendor-management name of any kind.** · **GAP — no CTO or VP Engineering named**; the senior technical title that does exist publicly is EVP of Products. · **GAP — no leadership page exists at all**: `phoenixnap.com/company/leadership` returns HTTP 404, so there is no company-published roster to work from. · **GAP — corporate officers, managers, members and statutory agent of record**: the Arizona Corporation Commission search is CAPTCHA-gated and **CAPTCHAs are not solved**; OpenCorporates and Bizapedia were also blocked. · **GAP — annual-report signatory and filing history for PHOENIX NAP, LLC.** · **GAP — the four secondary executives (Bohn, Anastasi, Eickenhorst, Lim) are aggregator-only** and none is confirmed by a phoenixNAP-published page. · **GAP — Stephanie Cadwell's operating role, if any**, and even the spelling of her surname, which one source renders "Caldwell". · **GAP — USPTO declaration signatory, correspondent and attorney of record**: search results indicate Phoenix NAP L.L.C. owns at least **SECURED SERVERS** (serial 87396103) and **HAAS** (serial 85655621), but `tsdrapi.uspto.gov` now returns **HTTP 401** requiring a registered API key, `tmsearch.uspto.gov` rejected the query with **HTTP 405**, and `uspto.report` returned **403** — **no owner address, no signatory, no filing or renewal date was obtained from any primary source**. · **GAP — historical WHOIS registrant** for phoenixnap.com: whoisrequest.com returned Cloudflare 403 and whoxy/securitytrails require paid keys, so only the current privacy-protected RDAP record exists. · **GAP — no named hiring manager or recruiter** in the only job posting found.

### 3.5 Sources worked — including what returned nothing

**Productive.** **[ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189)** was the highest-yield single source for people in this file — it returned the full record plus **six named technical and admin contacts with emails and direct phone numbers**. **[ARIN RDAP entity PHOEN-56](https://rdap.arin.net/registry/entity/PHOEN-56)** returned 12 network objects. **[ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0)** proved Secured Servers LLC is a phoenixNAP entity independently of the UCC. **[AZ SOS UCC Lien Search](https://apps.azsos.gov/apps/ucc/search/)**, driven in a real browser, returned **all 20 filings** with every debtor and secured party transcribed. **[Supermicro's own 2017 case study](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)** — recovered by manually inflating the PDF content streams, no pdftotext available in the environment — supplied both executive quotes and the historical fleet. **[New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/)** and **[ION Analytics / Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/)** supplied ownership and the founder pair. **[CourtListener REST v4](https://www.courtlistener.com/)** returned 17 dockets (metadata only — see §14).

**Reached but returned nothing on people.** **[PeeringDB net/2932](https://www.peeringdb.com/api/net/2932)** is fully populated on the network side but its **`poc_set` is empty** — no individual contacts published. **`phoenixnap.com/company/leadership`** returns **HTTP 404** — no leadership page exists. **ZipRecruiter and Indeed** returned only a generic Phoenix Data Center Technician req at $21–30/hr with **no named hiring manager**. **`api.open.fec.gov`** returned `OVER_RATE_LIMIT` on every attempt, so **no principal was screened**.

**Blocked, and why.** **Arizona Corporation Commission** — HTTP 403 to curl, **6-character image CAPTCHA** in-browser; CAPTCHAs are not solved, so this is a hard stop, not an oversight. **`ecorp.azcc.gov`** — DNS **NXDOMAIN**, portal retired. **OpenCorporates** — HAProxy CAPTCHA. **Bizapedia** — security check. **opengovus.com** Arizona mirror — HTTP 404. **All USPTO surfaces** — 401 / 405 / 403 / connection failure. **whoisrequest.com** — Cloudflare 403. **[mcassessor.maricopa.gov](https://mcassessor.maricopa.gov)** — result grids are AJAX-populated and the `/mcs/api/` endpoints return the HTML shell without an auth token, so **no parcel, APN, valuation or deed data** was obtained for either University Drive address.

**Best neutral next step to close the officer gap without touching the company:** order an Arizona Corporation Commission entity record through the **AZ SOS / ACC public counter or by phone**, and pair it with the **UCC-11 certified copies** described in §8 — the same trip closes both the officer gap and the collateral gap.

---

## 4. Footprint

Six of these sites are **priced billing regions** in the live Bare Metal Cloud catalogue (PHX, ASH, NLD, SGP, CHI, SEA); the rest are network nodes. That distinction matters more than the raw facility count, because only a priced region can take a new server SKU.

| Site | Facility operator | Owned vs leased | Size / power (published only) | Evidence |
|---|---|---|---|---|
| **Phoenix, AZ — 3402 E University Drive (DC1, flagship + HQ)** | Built and operated by phoenixNAP since 2010. **BEING SOLD to RadiusDC** — announced 2026-03-12, expected to close Q2 2026. **phoenixNAP remains a tenant** | **Owned** (property purchased **2009 for USD 6.3m**) → **converting to leased/tenant** after the RadiusDC close. Property-holding is consistent with **CC PROPERTY INVESTMENTS, LLC** appearing as co-debtor on every BMO facility | **~200,000 sq ft**, opened 2010. RadiusDC plans to expand the existing facility to **8 MW IT load** and add a second building (DC2) of up to **18 MW**, **~26 MW campus total**, with DC2 initial phases from **H1 2028**. *(Note: an 8 MW target for the existing building implies current occupied IT load is well under 8 MW.)* | [PRNewswire, 2026-03-12](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html) — acquisition includes the colocation facility, interconnection infrastructure and campus development rights; **~80% of phoenixNAP's global business continues under independent ownership, explicitly including Bare Metal Cloud and the network platforms**. Advisors: J.P. Morgan + Gibson Dunn + Snell & Wilmer for RadiusDC; **BofA Securities + Cleary Gottlieb for phoenixNAP**. Also listed as facility "PhoenixNAP, Phoenix US" in [PeeringDB netfac_set](https://www.peeringdb.com/api/net/2932) |
| **Ashburn, VA** | **Third-party** — Equinix DC1–DC15 / DC21–DC22 and **DataBank Ashburn (IAD1)** | Leased / colocated | **GAP** — not published | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932). **ASH is a full BMC region**: every server SKU including all three GPU SKUs is priced for location ASH in the [live catalogue](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) |
| **Chicago, IL** | Equinix **CH3**, Elk Grove Village | Leased / colocated | **GAP** | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932); **CHI is a priced BMC region including GPU SKUs** |
| **Seattle, WA** | Equinix **SE2 / SE3** | Leased / colocated | **GAP** | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932); **SEA is a priced BMC region including GPU SKUs** |
| **Amsterdam, NL** | **Iron Mountain Data Center — Amsterdam (AMS-1)** | Leased / colocated | **GAP.** phoenixNAP's own locations page calls Amsterdam its **second data center** (as opposed to a network node), i.e. a full-service site | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932) · [phoenixNAP locations](https://phoenixnap.com/global-it-services/locations); **NLD is a priced BMC region including GPU SKUs** |
| **Singapore** | Equinix **SG1** and Equinix **SG3** | Leased / colocated | **GAP** | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932); **SGP is a priced BMC region including GPU SKUs** |
| **Belgrade, Serbia** | **Cetin Data Center** | Leased / colocated | **GAP.** Also an **engineering hub** — two named ARIN technical POCs carry +381 numbers | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932) · [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Atlanta, GA** | **Digital Realty ATL13** | Leased / colocated | **GAP.** **Note:** ATL is in the facility list *and* in the 2017 Supermicro case study, but is **NOT a priced BMC region** in the live catalogue — network node only | [PeeringDB net/2932](https://www.peeringdb.com/api/net/2932); absent from the six BMC pricing locations |
| **Los Angeles CA · Frankfurt DE · Madrid ES · Milan IT · Warsaw PL · Sydney AU** | Equinix **LA1**, **FR7**, **MD2**, **ML2**, **WA1**, **SY1/SY2** | Leased / colocated — **network nodes** | **GAP** | [PeeringDB netfac_set](https://www.peeringdb.com/api/net/2932) (16 facilities total). phoenixNAP's own [locations page](https://phoenixnap.com/global-it-services/locations) describes these as network nodes rather than data centers, alongside **São Paulo, Helsinki, Sofia and Taipei**, for which **no PeeringDB facility is registered** |

**Staleness caveat on the facility list:** the PeeringDB record for AS12189 was last updated **2026-03-25**, but the **facility list itself was last updated 2021-10-01**. The facility set may therefore understate or misstate the current footprint and must not be used alone to size this account.

**Structural note (talking point, not a defect claim):** on close of the RadiusDC transaction, **RadiusDC becomes phoenixNAP's landlord and colocation provider in Phoenix**. Whatever gets racked in Phoenix after Q2 2026 lands in someone else's building, on someone else's power roadmap. That changes the density and delivery conversation and is a legitimate reason to ask about rack-integration and staging options.

---

## 5. Hardware fleet

Evidence grades used here: **confirmed** = first-hand named disclosure or multiple independent corroboration · **circumstantial** = behaviour or an undated page points strongly but nothing dated names the vendor · **contradicted** = evidence runs the other way · **GAP** = nothing found in any direction, and nothing is asserted.

| Vendor / category | Evidence grade | What the evidence actually says |
|---|---|---|
| **Supermicro** | **CONFIRMED (historical, 2017–2023) / CIRCUMSTANTIAL (current)** | **CONFIRMED historical:** Supermicro published a full named case study in **June 2017** — **X11 Building Block Solutions, 2U 4-node BigTwin, Simply Double all-flash NVMe SuperStorage, Supermicro Rack Scale Design and Supermicro Server Manager (SSM)** — with on-record quotes from **Ian McClarty (President)** and **William Bell (VP Products)**. phoenixNAP also participated in **Intel's Early Ship / Early Deployment programme THROUGH Supermicro** ([case study](https://www.supermicro.com/CaseStudies/CaseStudy_PhoenixNAP.pdf)). **CONFIRMED 2023:** ServeTheHome's March 2023 hands-on of the phoenixNAP BMC `d3.m6.xlarge` instance is titled and framed as **Supermicro Sapphire Rapids hardware**, and notes phoenixNAP was a **launch cloud provider for 4th Gen Xeon** ([ServeTheHome, 2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)). **CIRCUMSTANTIAL current:** phoenixNAP still runs a live [Supermicro ecosystem landing page](https://phoenixnap.com/offers/supermicro-servers) saying it utilises Supermicro solutions for Bare Metal Cloud, and co-ran a Supermicro webinar dated **19 June 2025** — but **that page carries no model numbers and no date**, and **BOTH new generations announced since 2023 went to HPE**. **No 2024–2026 announcement of a new Supermicro platform at phoenixNAP was found.** |
| **Hewlett Packard Enterprise (HPE)** | **CONFIRMED — and displacing** | Two dated HPE press releases name phoenixNAP. **(1) 2023-08-03:** phoenixNAP expands Bare Metal Cloud with **HPE ProLiant RL300 Gen11 servers on Ampere processors**, stated as deploying across its network of 18 data centers on five continents, quoted by **Ian McClarty**. This maps to the live **`a1.c5.*` Ampere Altra Q80-30** SKUs ([HPE release](https://www.hpe.com/us/en/newsroom/press-release/2023/08/phoenixnap-powers-expanded-ai-and-cloud-services-with-energy-saving-ampere-based-servers-from-hewlett-packard-enterprise.html)). **(2) 2025-04-04:** phoenixNAP adopts **HPE ProLiant Compute DL320 Gen12 with Intel Xeon 6** — HPE's first DC-MHS/OCP disaggregated hardware — quoted by **William Bell, EVP of Products**, citing adtech, fintech and SLED demand. This maps to the **`s4.x6.*` and `s5.x6.*`** SKUs ([HPE release](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)). phoenixNAP also runs a dedicated [HPE ProLiant RL300 product page](https://phoenixnap.com/bare-metal-cloud/hpe-proliant-rl300) on its own site. **HPE has won the last two platform refreshes.** |
| **Intel (silicon + accelerator, and probable co-marketing)** | **CONFIRMED** | Intel silicon dominates the catalogue — **72 of 82 server SKUs**. The only accelerator sold anywhere is the **Intel Data Center GPU Max 1100**, promoted on a dedicated phoenixNAP offer landing page with the explicit claim of **no additional licensing fees for Intel MAX GPU features** ([offer page](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc)). phoenixNAP participated in Intel's Early Deployment / Early Ship programme (via Supermicro) in 2017 and was a launch provider for 4th Gen Xeon in 2023. **A dedicated vendor-branded offer page plus a preorder push in September 2023 is the signature of an Intel-subsidised or seeded deployment** — that is an inference, but a well-supported one |
| **NVIDIA** | **CONTRADICTED (for the current fleet)** | phoenixNAP publicly launched **NVIDIA Tesla V100 (4× and 8× with NVLink) and Tesla P40** dedicated servers on **2018-10-01** ([press release](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus)). Seven and a half years later the **live Bare Metal Cloud product catalogue contains no NVIDIA SKU of any kind** — the only `gpuConfigurations` entry across all 101 products is **"Intel Max 1100 GPU"** ([live catalogue](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json), pulled 2026-08-10). **Third-party listicles claiming phoenixNAP offers "L4 to H100" are not supported by phoenixNAP's own pricing system — treat those as aggregator noise** |
| **Ampere Computing** | **CONFIRMED as silicon, delivered via HPE** | **Ampere Altra Q80-30 (`a1.c5.*`)** and **AmpereOne A96-36X (`a2.c9.*`)** are both live, priced SKUs. The Altra generation is documented as arriving on **HPE ProLiant RL300 Gen11**. **The chassis vendor for the newer AmpereOne A96-36X SKUs is NOT disclosed anywhere reachable — that is an open competitive slot** |
| **AMD** | **CONFIRMED as silicon only; chassis vendor unknown** | **EPYC 4345P and EPYC 4565P** single-socket SKUs (`s4.c3.medium`, `s4.c6.large/medium/xlarge`, `s4.s2.large`) are live and priced. **No vendor announcement identifies who supplies these chassis. Another open slot** ([live catalogue](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)) |
| **Express Computer Systems (Irvine, CA)** | **CIRCUMSTANTIAL** | Secured party on Arizona UCC file **202200315262**, filed **2022-05-19**, against debtors **ALTAY CORPORATION** (Los Angeles) and **PHOENIXNAP** (3402 East University Drive). Express Computer Systems is a hardware reseller/lessor. **This is the only non-bank equipment secured party on record** and suggests at least one reseller-financed hardware tranche in 2022. **Collateral text is not exposed by the AZ portal, so what was financed is unproven** ([AZ SOS UCC](https://apps.azsos.gov/apps/ucc/search/)) |
| **Pliops** | **CIRCUMSTANTIAL** | A dedicated SKU **`d2.c4.db1.pliops1`** (2× Xeon Gold 6336Y, 4× 4 TB NVMe) exists in the live catalogue, implying deployed Pliops storage-accelerator cards. Small and niche, but it confirms **willingness to qualify third-party PCIe accelerators** |
| **Netris (network layer)** | **CONFIRMED** | **Netris SoftGate 1G/10G/25G** appear as billable products (`netris/softgate_*`), i.e. **software-defined gateways rather than proprietary appliances**. Read this as an operator receptive to disaggregated, non-locked-in hardware |
| **Dell / Lenovo / ODM (Inspur, Wiwynn, Quanta)** | **GAP** | **No evidence found in any direction. Not asserted.** No source worked returned any Dell, Lenovo, Inspur, Wiwynn or Quanta reference in connection with phoenixNAP. See §3.5 and §14 for the full list of what was checked |

### CPU generations observed, and what they imply about fleet age

Read directly off the live product catalogue — **82 distinct server SKUs across 101 products** ([live catalogue JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json), pulled 2026-08-10):

- **Current generation:** Intel Xeon 6 P-core **6527P / 6767P / 6770P** (`s5.x6.*`) · Intel Xeon 6 E-core **6731E** (`s4.x6.*`) · **AmpereOne A96-36X** (`a2.c9.*`) · AMD **EPYC 4345P / 4565P** (`s4.c3/c6.*`) · Intel **Core i9 14900K** (`s3.c3.*`)
- **Mid-life:** Intel **Emerald Rapids** 6536 / 6540 / 6542Y (`d3.c1/c2/c3`, `d3.m1/m2/m3`) · Intel **Sapphire Rapids** 5418Y / 6426 / 6430 / 6436 / 6442Y / 8452Y (`d3.*`, including all three GPU SKUs) · **Ampere Altra Q80-30** (`a1.c5.*`) · Intel **E-2356G / E-2388G** (`s2.*`)
- **Legacy:** Intel **Ice Lake** 5315Y / 5317 / 6326 / 6336Y / 8352Y (`d2.*`) · Intel **Cascade Lake-R 6258R** (`d1.*`) · Intel **E-2276G / E-2288G** (`s1.*`) · Intel **E3 v3** (`s0.*`)

**What this implies.** The **`d1` + `d2` Cascade Lake / Ice Lake fleet is 26 SKUs and 4–6 years old** — that is the natural consolidation target, and phoenixNAP has already run **Supermicro X11 BigTwin**, so **X11 BigTwin → X14 BigTwin is the literal same-family upgrade**, not a platform migration. The presence of **AMD EPYC 4000-series and Core i9 desktop-class parts** shows they will buy single-socket workstation-class silicon when the price/perf works — which is exactly the segment where a chassis vendor can differentiate. And the two **dense storage SKUs** — `d3.s5.xlarge` (2× Xeon Gold 6430, 6× 15.36 TB NVMe + 1 TB boot) and `s5.x6.s5.large` (Xeon 6767P, 6× 15 TB NVMe + 1 TB boot) — map directly onto Supermicro Petascale / SSG all-NVMe, and they **already ran Supermicro "Simply Double" SuperStorage** per the 2017 case study. That is a re-entry point with proven history rather than a cold pitch.

---

## 6. GPU catalogue & AI position

**This is the weakest and most exposed part of the business, and it is the reason to call.**

The entire accelerator catalogue is **three trims of one node**. All three carry the identical accelerator: **2× Intel Data Center GPU Max 1100** (48 GB HBM2e each, 56 Xe cores per card, Intel Xe Link bridge). Every price below is read from phoenixNAP's own **production price/product JSON** — the file that feeds their public pricing pages — pulled **2026-08-10**, and cross-checked against the rendered GPU page.

| SKU | Full spec | Hourly | 1-month | 12-month | 24-month | 36-month | Availability |
|---|---|---|---|---|---|---|---|
| **d3.g2.c1.xlarge** | 2× **Intel Max 1100**; 2× Xeon Gold **6426** (32c total @2.9 GHz); **512 GB** RAM; **4× 2 TB NVMe**; 2× 25 Gbps (50 Gbps bonded) + 20 Gbps DDoS; 15 TB bandwidth included | **$2.49/hr** | **$1,646.72/mo** | **$998.26/mo** | **$880.11/mo** | **$808.21/mo** | Priced in **PHX, ASH, NLD, SGP, CHI, SEA** — identical price in every region. Marketing page claims stock only in **Phoenix (AZ) and Ashburn (VA)**, "More Coming Soon…" |
| **d3.g2.c2.xlarge** | 2× **Intel Max 1100**; 2× Xeon Gold **6436** (40c total @2.7 GHz); **512 GB** RAM; **4× 2 TB NVMe**; 2× 25 Gbps | **$2.60/hr** | **$1,726.02/mo** | **$1,065.66/mo** | **$947.52/mo** | **$875.63/mo** | Priced in all six regions; marketed as **PHX + ASH** |
| **d3.g2.c3.xlarge — FLAGSHIP GPU SKU** | 2× **Intel Max 1100**; 2× Xeon Gold **6442Y** (48c total @2.6 GHz); **512 GB** RAM; **4× 2 TB NVMe**; 2× 25 Gbps | **$2.67/hr** | **$1,778.49/mo** | **$1,110.27/mo** | **$992.12/mo** | **$920.23/mo** | Priced in all six regions; marketed as **PHX + ASH**. **This is the node to price against** |
| **NVIDIA — any model** | **NOT OFFERED.** No NVIDIA SKU exists anywhere in the 101-product live catalogue | — | — | — | — | — | **None.** Last NVIDIA offering was the **Oct 2018 Tesla V100 / P40** dedicated-server line, long retired |
| **AMD Instinct — any model** | **NOT OFFERED** | — | — | — | — | — | **None** |

Sources for the table: [phoenixNAP live catalogue JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) (the file behind [/bare-metal-cloud/instances](https://phoenixnap.com/bare-metal-cloud/instances)) · [GPU servers page](https://phoenixnap.com/bare-metal-cloud/gpu-servers) · [Intel Max 1100 offer page](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc) · [2018 NVIDIA Tesla press release](https://phoenixnap.com/press/dedicated-servers-with-nvidia-tesla-gpus).

### Non-GPU price anchors — for BOM and margin triangulation

| SKU | Spec | Hourly | 1-month | 12-month | 24-month | 36-month |
|---|---|---|---|---|---|---|
| **s5.x6.m9.xlarge** — nearest current-gen CPU node | Xeon **6770P** (64c), 512 GB, 2× 4 TB NVMe | **$3.11/hr** | **$2,111.26/mo** | **$1,316.31/mo** | **$1,111.50/mo** | **$968.14/mo** |
| **d3.m6.xxlarge** — the CPU-only node closest in cost to a GPU node | 2× Platinum **8452Y** (72c), **1 TB** RAM, 2× 4 TB NVMe | **$2.56/hr** | **$1,650.20/mo** | **$1,416.32/mo** | **$1,301.44/mo** | **$1,208.43/mo** |

Both are available in all six regions. Source: [live catalogue JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json).

### The marketing/billing disagreement — and what it tells you

The GPU marketing page says availability is **Phoenix (AZ) and Ashburn (VA), "More Coming Soon."** The live billing catalogue prices all three GPU SKUs in **six** locations — PHX, ASH, NLD, SGP, CHI, SEA — **at identical prices in every region**. That is not a contradiction to score against them; it is an honest tell. **Prices are provisioned globally but stock is claimed only in two US sites.** Read it as a **small, concentrated GPU fleet**. A refresh would therefore be a **modest unit count, which favours a fast pilot rather than a mega-deal** — and a pilot is a much easier first close on an account that has to paper every purchase against a bank facility.

### AI position, stated plainly

phoenixNAP has a real AI demand story and a thin AI fleet to serve it. **Kaligent** is a named phoenixNAP case study explicitly about bringing AI into client-facing tools ([customer experience page](https://phoenixnap.com/customer-experience)); HPE's April 2025 release cites **adtech, fintech and SLED** demand; **UC Berkeley's Department of Statistics** is a named academic/research-compute reference, which is precisely the buyer profile for the Max 1100 tier. Against that: **one accelerator model, three trims, no refresh in ~34 months, no NVIDIA option, no AMD option, and stock admitted in two of six priced regions.** HPE did not take that slot. It is empty.

---

## 7. Purchase clock

How often phoenixNAP actually buys, read two independent ways: **(A)** when a new silicon generation first appears in their own published catalogue, and **(B)** when they draw a new secured equipment tranche. The two streams corroborate each other.

### 7.1 Stream A — catalogue-generation first appearance

Dated from Wayback Machine snapshots of [phoenixnap.com/bare-metal-cloud/instances](https://phoenixnap.com/bare-metal-cloud/instances). Each generation is **bracketed between a known-absent and a known-present snapshot**, then cross-checked against dated vendor press releases.

| Generation / SKU family | Absent at | First present at | Bracket | Corroboration |
|---|---|---|---|---|
| **`d2.*` Intel Ice Lake** | 2021-07-07 | **2021-09-28** | ~12 weeks | — |
| **`d3.*` Intel Sapphire Rapids** | 2023-01-30 | **2023-05-08** | ~14 weeks | phoenixNAP was a **launch cloud provider for 4th Gen Xeon**; [ServeTheHome, 2023-03-31](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/) documents the instance as **Supermicro** hardware |
| **`a1.c5.*` Ampere Altra Q80-30** | 2023-05-08 | **2023-09-13** | ~18 weeks | Matches the **[HPE ProLiant RL300 Gen11 release, 2023-08-03](https://www.hpe.com/us/en/newsroom/press-release/2023/08/phoenixnap-powers-expanded-ai-and-cloud-services-with-energy-saving-ampere-based-servers-from-hewlett-packard-enterprise.html)** |
| **`d3.g2.*` Intel Max 1100 GPU** *(and `s3.c3.*` Core i9 14900K, same window)* | 2023-09-13 | **2023-11-09** | **~8 weeks — the tightest bracket in the study** | Consistent with the phoenixNAP **preorder push of 2023-09-19** and the dedicated [Intel Max 1100 offer page](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc) |
| **`s4.x6.*` Intel Xeon 6 E-core (6731E)** | 2024-08-06 | **2024-12-07** | ~17 weeks | — |
| **`s5.x6.*` Intel Xeon 6 P-core (6527P / 6767P / 6770P)** | 2025-03-27 | **2025-08-15** | ~20 weeks | Matches the **[HPE ProLiant DL320 Gen12 / DC-MHS release, 2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)** |
| **`a2.c9.*` AmpereOne A96-36X** | — | **in the live billing catalogue on 2026-08-10** | **DATE NOT PINNED** | **Never appeared on the instances page in any archived snapshot.** Newest addition; see §14 for how to pin it |

### 7.2 Stream B — financing events (Arizona UCC-1 origination dates)

Every **new** UCC-1 against **PHOENIX NAP, LLC** is treated as a financed purchase event. **Amendments and continuations are excluded** — they restate rather than add collateral. **The 2026-07-22 UBS AG Aviation & Yacht Finance filing is excluded — it is not IT equipment.**

| Year | New UCC-1 origination dates | Count |
|---|---|---|
| 2014 | 2014-07-08 | 1 |
| 2022 | 2022-05-19 · 2022-09-02 · 2022-09-02 | 3 |
| 2023 | — | **0** |
| 2024 | 2024-05-10 · 2024-06-21 · 2024-09-25 | 3 |
| 2025 | 2025-01-10 · 2025-07-03 · 2025-08-06 · 2025-09-04 · 2025-10-15 · 2025-12-01 | **6** |
| 2026 (to date) | 2026-01-13 · 2026-02-13 · 2026-03-18 · 2026-04-02 · 2026-04-02 | 5 |

### 7.3 Cadence

**Hardware-generation refresh:** roughly **every 7–9 months a new CPU family enters the catalogue** — May 2023 Sapphire Rapids → Sep 2023 Ampere Altra + Intel Max 1100 GPU → Aug/Dec 2024 Xeon 6 E-core → Apr/Aug 2025 Xeon 6 P-core.

**Financing cadence is faster and was accelerating.** Intervals between consecutive **new** UCC-1s from July 2025 through April 2026:

| From → to | Days |
|---|---|
| 2025-07-03 → 2025-08-06 | 34 |
| 2025-08-06 → 2025-09-04 | 29 |
| 2025-09-04 → 2025-10-15 | 41 |
| 2025-10-15 → 2025-12-01 | 47 |
| 2025-12-01 → 2026-01-13 | 43 |
| 2026-01-13 → 2026-02-13 | 31 |
| 2026-02-13 → 2026-03-18 | 33 |
| 2026-03-18 → 2026-04-02 | 15 |

**MEDIAN ≈ 33 days.** Read together with Stream A: **they refresh a silicon generation two to three times per two years and draw a fresh secured equipment tranche roughly monthly to pay for it.**

**Last event.** Last **IT-equipment financing event: 2026-04-02** — two simultaneous BMO Bank N.A. UCC-1s (files **2026-001-2461-6** and **2026-001-2475-0**, both 6 pages, both naming Phoenix NAP LLC + CC Property Investments + Secured Servers). Last **catalogue addition** detectable: the **AmpereOne A96-36X** SKUs, present in the live billing catalogue as of 2026-08-10 but never seen on an archived instances page. **Last GPU purchase signal: nothing since the Intel Max 1100 introduction in about October 2023 — 34 months with no accelerator refresh.**

### 7.4 Next window — OVERDUE AND OPENING NOW

Against a 33-day median, the 2026-04-02 filing should have been followed by a new tranche in **May 2026**. Instead there has been a **four-month gap with nothing IT-related**, spanning exactly the **Q2 2026 close of the RadiusDC colocation divestiture**. The honest read is a **deliberate capital pause while the Phoenix colo carve-out completed, not a decline in the business** — and note that a brand-new **U.S. Bank Equipment Finance** line was opened on 2026-03-18 against **Phoenix NAP LLC alone**, without the property-holding co-obligors, three weeks before the RadiusDC deal was announced. That is exactly what separating financeable IT equipment from the real estate being sold looks like.

**Estimated next window: September to December 2026.** The highest-probability trigger is **the first post-divestiture bare-metal-cloud fleet plan**, and the single most exposed line item in that plan is **the accelerator tier — no refresh since 2023, no NVIDIA or AMD alternative**.

**Confidence: MEDIUM.** This is derived from **filing spacing and catalogue archaeology, not from any statement by the company.**

### 7.5 Method — and its limits

**(1) Catalogue.** Enumerated all Wayback CDX snapshots of the phoenixNAP **instances** and **gpu-servers** pages (52 and 54 snapshots respectively), downloaded about **35** of them via `web.archive.org` raw `id_` captures, gunzipped them, and regex-tested each for SKU prefixes and CPU part numbers to bracket each generation between a known-absent and a known-present snapshot; then cross-checked every bracket against dated vendor press releases. **(2) Financing.** Searched the Arizona Secretary of State UCC Lien Search — Organization = `PHOENIX NAP`, Wildcard, Party = Debtor, Filter = All (including lapsed) — transcribed every origination date, treated each new UCC-1 as a financed purchase event, and computed inter-event intervals. **(3) Exclusions.** Amendments and continuations excluded from the cadence; the UBS aviation/yacht filing excluded as non-IT.

**Limits, stated plainly.** A **UCC-1 proves a financing draw, not a delivery date**. The **AZ portal does not expose collateral text**, so **no specific tranche can be tied to specific hardware**. Wayback rate-limited repeated raw-capture requests, so several snapshots returned truncated or blocked bodies. And the price file `api-data.json` only began being archived in **October 2025**, so the AmpereOne introduction could not be dated — see §14.

---

## 8. UCC financing record

**Scope:** debtor searches against **PHOENIX NAP, LLC** and its affiliated entities in **Arizona**, which is the correct filing office for an Arizona-organised LLC under UCC §9-301 / §9-307. A **Delaware search was NOT run**, and was not warranted on the evidence — no Delaware entity was found — but see the caveat in §14.

### 8.1 Verdict

> ### **20 FILINGS — RETRIEVED AND TRANSCRIBED**
>
> **…but the collateral descriptions are NOT available.** Every filing below is reproduced exactly as the Arizona Secretary of State public viewer presents it: file number, origination, expiry, lien type, every amendment/continuation with filed and entered dates and page count, and every debtor and secured party with full address. **The viewer does not render collateral text and does not serve filing images to the public search.** No collateral clause was seen, so none is transcribed and **none is paraphrased**.

### 8.2 Filings on record — every filing, in full

**1) File 2019-000-6994-0** — origination **2019-02-13**, expires **2029-02-13**, Standard.
· New Filing 2019-02-13, entered 2019-02-26, **3 pages**. Continuation filed 2023-12-26, entered 2023-12-26, 1 page.
· **DEBTOR:** PHOENIX NAP MANAGEMENT RESOURCES LLC, 2353 W UNIVERSITY DR, TEMPE, AZ 85281.
· **SECURED PARTY:** BMO HARRIS BANK N.A., 770 N WATER ST 8TH FL, MILWAUKEE, WI 53202.
· **COLLATERAL:** *not rendered by the portal — see §8.4.*

**2) File 2014-002-1459-5** — origination **2014-07-08**, expires **2029-07-08**, Standard.
· New Filing 2014-07-08, entered 2014-07-10, **2 pages**. Continuation 2019-04-16, entered 2019-05-16, 1 page. Continuation 2024-05-02, entered 2024-05-02, 1 page.
· **DEBTORS:** PHOENIX NAP, LLC / SECURED SERVERS, LLC / CC PROPERTY INVESTMENTS, LLC — all at 2353 W. UNIVERSITY DRIVE, PHOENIX, AZ 85281.
· **SECURED PARTY:** BMO HARRIS BANK, N.A., 111 WEST MONROE, CHICAGO, IL 60603.
· **COLLATERAL:** *not rendered by the portal.*
· **Note:** this is the **oldest live filing** and has been continued twice — it is unlapsed after twelve years.

**3) File 2022-005-0492-1** — origination **2022-09-02**, expires **2027-09-02**, Standard.
· New Filing 2022-09-02, **2 pages**. Amendment 2022-12-20, **2 pages**.
· **DEBTORS:** PHOENIX NAP, LLC, 3402 E UNIVERSITY DR, PHOENIX, AZ 85034-7200 / CC PROPERTY INVESTMENTS, LLC and SECURED SERVERS, LLC, both 2353 W UNIVERSITY DR, TEMPE, AZ 85281-7223.
· **SECURED PARTY:** BMO HARRIS BANK N.A., 790 N. WATER STREET, 14TH FLOOR, MILWAUKEE, WI 53202.
· **COLLATERAL:** *not rendered by the portal.*

**4) File 2022-005-0552-8** — origination **2022-09-02**, expires **2027-09-02**, Standard.
· New Filing 2022-09-02, **2 pages**. **No amendments.**
· **DEBTORS:** same three — PHOENIX NAP, LLC / CC PROPERTY INVESTMENTS, LLC / SECURED SERVERS, LLC.
· **SECURED PARTY:** BMO HARRIS BANK N.A., 790 N. WATER STREET, 14TH FLOOR, MILWAUKEE, WI 53202.
· **COLLATERAL:** *not rendered by the portal.*

**5) File 2024-002-1418-4** — origination **2024-05-10**, expires **2029-05-10**, Standard.
· New Filing 2024-05-10, **2 pages**. Amendment 2024-06-11, **5 pages**.
· **DEBTORS:** same three.
· **SECURED PARTY:** BMO BANK N.A., 790 N. WATER STREET, 15TH FLOOR, MILWAUKEE, WI 53202.
· **COLLATERAL:** *not rendered by the portal.*
· **Note:** first filing under the **"BMO Bank N.A."** name (previously BMO Harris) and the 15th-floor address.

**6) File 2024-002-7843-8** — origination **2024-06-21**, expires **2029-06-21**, Standard.
· New Filing 2024-06-21, **2 pages**. Amendment 2024-09-05, **2 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 790 N. WATER STREET, 15TH FLOOR, MILWAUKEE, WI 53202.
· **COLLATERAL:** *not rendered by the portal.*

**7) File 2024-004-0925-7** — origination **2024-09-25**, expires **2029-09-25**, Standard.
· New Filing 2024-09-25, **2 pages**. Amendment 2024-12-17, **2 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.*

**8) File 2025-000-2423-3** — origination **2025-01-10**, expires **2030-01-10**, Standard.
· New Filing 2025-01-10, **2 pages**. Amendment 2025-03-26, **5 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.*

**9) File 2025-002-5888-0** — origination **2025-07-03**, expires **2030-07-03**, Standard.
· New Filing 2025-07-03, **2 pages**. Amendment 2025-07-23, **4 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.*

**10) File 2025-002-9842-8** — origination **2025-08-06**, expires **2030-08-06**, Standard.
· New Filing 2025-08-06, **16 PAGES — by far the largest single UCC-1 on this record.** **No amendment.**
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.* **A 16-page UCC-1 implies a long itemised equipment schedule** — this is the highest-value certified-copy order on the whole list.

**11) File 2025-003-3501-6** — origination **2025-09-04**, expires **2030-09-04**, Standard.
· New Filing 2025-09-04, **2 pages**. Amendment 2025-09-23, **7 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.*

**12) File 2025-004-0469-9** — origination **2025-10-15**, expires **2030-10-15**, Standard.
· New Filing 2025-10-15, **5 pages**. **No amendment.**
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.*

**13) File 2025-004-5904-5** — origination **2025-12-01**, expires **2030-12-01**, Standard.
· New Filing 2025-12-01, **2 pages**. Amendment 2025-12-19, **7 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.*

**14) File 2026-000-2754-6** — origination **2026-01-13**, expires **2031-01-13**, Standard.
· New Filing 2026-01-13, **2 pages**. Amendment 2026-01-28, **10 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 15th Floor.
· **COLLATERAL:** *not rendered by the portal.*

**15) File 2026-001-5110-0** — origination **2026-02-13**, expires **2031-02-13**, Standard.
· New Filing 2026-02-13, **entered late on 2026-04-21**, **6 pages**.
· **DEBTORS:** same three. **SECURED PARTY:** BMO BANK N.A., 790 N. WATER STREET, 15TH FLOOR.
· **COLLATERAL:** *not rendered by the portal.*

**16) File 2026-001-0311-3** — origination **2026-03-18**, expires **2031-03-18**, Standard. **FIRST NEW LENDER SINCE 2022.**
· New Filing 2026-03-18, **2 pages**.
· **DEBTOR:** PHOENIX NAP, LLC, 3402 E UNIVERSITY DR, PHOENIX, AZ 85034 — **SOLE DEBTOR. No Secured Servers, no CC Property Investments.**
· **SECURED PARTY:** U.S. BANK EQUIPMENT FINANCE, A DIVISION OF U.S. BANK NATIONAL ASSOCIATION, 1310 MADRID STREET, MARSHALL, MN 56258.
· **COLLATERAL:** *not rendered by the portal.*

**17) File 2026-001-2461-6** — origination **2026-04-02**, expires **2031-04-02**, Standard.
· New Filing 2026-04-02, **6 pages**.
· **DEBTORS:** PHOENIX NAP, LLC, 3402 E UNIVERSITY DR, PHOENIX, AZ 85034 / CC PROPERTY INVESTMENTS, LLC and SECURED SERVERS, LLC, 2353 W UNIVERSITY DR, TEMPE, AZ 85281.
· **SECURED PARTY:** BMO BANK N.A., 790 NORTH WATER STREET, 14W, MILWAUKEE, WI 53202.
· **COLLATERAL:** *not rendered by the portal.*

**18) File 2026-001-2475-0** — origination **2026-04-02**, expires **2031-04-02**, Standard. **MOST RECENT IT-EQUIPMENT FILING.**
· New Filing 2026-04-02, **6 pages**.
· **DEBTORS and SECURED PARTY:** identical to #17.
· **COLLATERAL:** *not rendered by the portal.*

**19) File 2026-003-2810-7** — origination **2026-07-22**, expires **2031-07-22**, Standard. **NOT IT EQUIPMENT.**
· New Filing 2026-07-22, entered 2026-07-30, **2 pages**.
· **DEBTOR:** PHOENIX NAP, LLC, **3402 E UNIVERSITY DR. SUITE 420**, PHOENIX, AZ 85034.
· **SECURED PARTY:** UBS AG, AVIATION & YACHT FINANCE (IVV2), BAHNHOFSTRASSE 45, ZURICH, ZU 8001, CHE.
· **COLLATERAL:** *not rendered by the portal.* An aircraft or vessel financing booked against the operating company. **Excluded from the purchase-clock cadence in §7.**

**20) File 2022-003-1526-2** — origination **2022-05-19**, expires **2027-05-19**, Standard. **THE ONLY NON-BANK EQUIPMENT SECURED PARTY ON RECORD.**
· New Filing 2022-05-19, entered 2022-05-31, **1 page**.
· **DEBTORS:** ALTAY CORPORATION, 4470 W SUNSET BLVD SUITE 697, LOS ANGELES, CA 90027 / **PHOENIXNAP**, 3402 EAST UNIVERSITY DRIVE, PHOENIX, AZ 85034.
· **SECURED PARTY:** EXPRESS COMPUTER SYSTEMS, 1733 KAISER AVENUE, IRVINE, CA 92614.
· **COLLATERAL:** *not rendered by the portal.*

**Across all 20 records: no terminations and no assignments appear. Every filing is unlapsed.**

### 8.3 Query log

| Portal / URL | Query string used | Response (verbatim where quoted) | Alternative route if blocked |
|---|---|---|---|
| **AZ SOS UCC Liens Viewer** — [apps.azsos.gov/apps/ucc/search/LiensViewerView.aspx](https://apps.azsos.gov/apps/ucc/search/LiensViewerView.aspx), via automated fetch | Attempted to load the lien detail viewer directly | **HTTP 403 Forbidden.** No data | Drive the same URL in a real browser (next row) |
| **AZ SOS UCC Liens Viewer** — same URL, real browser, cold session | Attempted to reach lien detail without a prior search | Page rendered with header **"View Liens"** and the line **"Results from this search contain all UCC records filed on or prior to unknown"** — **no data.** This viewer requires a prior search session | Run the search first, then invoke the View postback |
| **AZ SOS UCC landing** — [azsos.gov/business/ucc](https://azsos.gov/business/ucc) | Read-only: locate the authoritative search URL | **HTTP 200.** Extracted the authoritative link: **"UCC Lien Search ⇒ https://apps.azsos.gov/apps/ucc/search/"** | n/a — this call succeeded |
| **AZ SOS UCC Lien Search** — [apps.azsos.gov/apps/ucc/search/](https://apps.azsos.gov/apps/ucc/search/), real browser | Form rendered: Organization + Standard/Wildcard + Party (Debtor/Secured Party); Individual Last/First/Middle + Party; File Number; Search Filter Unlapsed / All (including lapsed); Begin/End date | **HTTP 200.** Banner reads **"Results from this search contain all UCC records filed on or prior to Thursday, April 9, 2026"** — **note this banner is STALE**, since the result set includes a **2026-07-22** filing | n/a |
| **AZ SOS UCC Lien Search — THE EXECUTED SEARCH** | **Organization = `PHOENIX NAP` · Search Type = Wildcard · Party = Debtor · Search Filter = All (including lapsed) · no date filter** | **"20 entries found"**, grouped as **PHOENIX NAP MANAGEMENT RESOURCES LLC (1) · PHOENIX NAP, LLC (18) · PHOENIXNAP (1)** | n/a — this is the search that produced §8.2 |
| **AZ SOS UCC Lien Search — detail retrieval** | Selected all 20 via the grid's "Select first 100 items" checkbox and invoked the View postback | **"20 entries selected"**, then the full multi-record **View Liens** page — transcribed in §8.2 | n/a |
| **NOT RUN — secured-party-side search on "BMO"** | — | — | Would enumerate BMO filings against any additional phoenixNAP-affiliated debtor name not caught by the `PHOENIX NAP` wildcard. **Free. Should be run** |
| **NOT RUN — Individual-name searches** | — | — | Would catch any filing indexed against a Cadwell/McClarty personal guarantee. **Free. Worth one pass** |
| **NOT RUN — Delaware UCC search** | — | — | **Deliberately not run.** phoenixNAP is Arizona-organised, so Arizona is the correct filing office under UCC §9-301/§9-307. A Delaware search would only be warranted if a Delaware holdco existed, and none was found — **but the Delaware corporate registry was also not searched**, so this is an assumption resting on an unchecked premise. See §14 |
| **COLLATERAL TEXT — not obtainable from this portal** | — | The AZ SOS public UCC viewer (`LiensViewerView.aspx`) renders **file number, dates, lien type, filing-event type, page count, and full debtor and secured-party names and addresses**. It does **NOT** render collateral text and does not serve the filing images to the public search | **UCC-11 information request or certified copy order** from **AZ SOS Business Services Division, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187** |

### 8.4 What the record means

This is the clearest signal in the entire file, and it is unambiguous.

| Observation | What it implies | Confidence | Sales consequence |
|---|---|---|---|
| **BMO (Harris) Bank N.A. has been the equipment and asset lender since at least 2014** — twelve years, three address changes at BMO's end, **eighteen filings**. Every substantive facility **cross-collateralises three entities together**: Phoenix NAP LLC (opco), Secured Servers LLC (the IP-address holder), and CC Property Investments LLC (the property arm) | The lender is secured across **operating equipment, network assets and real property simultaneously** — a classic owner-operator borrowing base, **not a lease line** | **High** — directly read off 18 transcribed filings | Expect a **relationship-bank approval path**, not a vendor-credit path. The CFO-side conversation will be about **lien position within an existing blanket**, which for them is routine |
| **They do NOT lease their fleet from an OEM captive.** There is **no Dell Financial Services, no HPEFS, no Cisco Capital, no CIT/DLL/Key Equipment** anywhere on the record | The fleet is **bought with bank debt against their own balance sheet.** This is exactly the "buys its own fleet" profile | **High** — absence across 20 filings is meaningful because the register was fully retrieved | **The vendor conversation is a purchase conversation, not a consumption conversation.** Price-per-node lands directly on their cash, their depreciation and their interest expense. **They will be extremely price-per-node sensitive** |
| **The cadence changed character in mid-2025.** From July 2025 to April 2026 they drew a new secured tranche roughly **every 33 days**, with amendment page counts climbing **2 → 5 → 7 → 10**, and a **16-page original in August 2025** | Growing schedules mean growing equipment lists. **Something was being bought hard and steadily through that period** | **Medium-High** — page counts are a proxy for schedule length, not proof | Whatever was bought in that window is **now 12–18 months old and already financed**. The refresh conversation is about **what comes next**, not about replacing what they just paid for |
| **Two new lenders appeared in 2026:** U.S. Bank Equipment Finance on **2026-03-18** (notably against **Phoenix NAP LLC ALONE**, without the Secured Servers and CC Property co-obligors) and UBS AG Aviation & Yacht Finance on 2026-07-22 | The U.S. Bank filing is the interesting one — **a standalone opco equipment line, arriving three weeks before the RadiusDC deal was announced and structured so it does not touch the property entity.** That is exactly what you would expect if they were deliberately **separating financeable IT equipment from the real estate being sold** | **Medium-High** — the structure and timing are directly observed; the intent is inference | **There is now a second, IT-only equipment line with no property entanglement.** That is the facility a new hardware order would most naturally be papered against, and it is brand new and presumably undrawn |
| **Then everything stops.** No IT-equipment UCC-1 since **2026-04-02**, against a **33-day median. Four months of silence** | Combined with the **Q2 2026 colo divestiture close**, the reasonable inference is **a financing pause during the carve-out, with a restart pending**. When it restarts it will be a **bare-metal-cloud-only borrowing base**, backed by BMO and now U.S. Bank, and the collateral will be **servers rather than a building** | **Medium** — the stop is observed; the reason is inference | **This is the timing argument for the whole account.** Reach out ahead of the restart, not after. See §7.4 |
| **No terminations and no assignments on any of the 20 records; every filing is unlapsed** | The **collateral pool is fully committed.** There is no restored borrowing capacity sitting free | **High** — directly observed | A new purchase will need to be **accommodated within, or subordinated to, the existing blanket.** If a purchase-money security interest is wanted on shipped hardware, **PMSI notice mechanics and the 20-day equipment perfection clock have to be planned before hardware ships, not after** |
| **Collateral descriptions were never seen** | It is **not known** whether the BMO filings are blanket ("all assets, wherever located, now owned or hereafter acquired") or specific-equipment schedules. That difference is **the entire commercial question** for a new vendor | **High** — this is a statement about what the evidence does not contain | **Order certified copies before any terms discussion.** Start with **2025-002-9842-8** (16 pages), **2026-001-2461-6** and **2026-001-2475-0** (6 pages each), and **2026-001-0311-3** (the U.S. Bank line). Contact: **AZ SOS Business Services, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187** |

**Practical selling consequence, in one line:** their purchase capacity is **real and bank-backed**, their approval path runs through a lender who **already holds a blanket**, and a new hardware order **will be papered as an equipment tranche**. Expect the finance and legal conversation about lien position and vendor invoicing to be **routine for them rather than an obstacle** — and expect them to be **unforgiving on price per node**, because they carry the depreciation and the interest themselves.

### 8.5 GAP — UCC track, stated plainly

- **COLLATERAL TEXT IS THE SINGLE BIGGEST GAP IN THIS FILE.** All 20 filings were located and their parties, dates and amendments transcribed, but the AZ SOS public viewer **does not render collateral descriptions and does not serve filing images**. **Not one collateral clause was seen, and none is paraphrased.** Page counts are the only proxy. **Resolution:** UCC-11 information requests or certified copies from **AZ SOS Business Services Division, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187**, starting with files **2025-002-9842-8**, **2026-001-2461-6**, **2026-001-2475-0** and **2026-001-0311-3**.
- **NO SECURED-PARTY-SIDE SEARCH WAS RUN.** A search on "BMO" as secured party would catch filings against any phoenixNAP-affiliated debtor string the `PHOENIX NAP` wildcard missed. **Free, not run.**
- **NO INDIVIDUAL-NAME SEARCHES WERE RUN.** Any personal guarantee filed against Ron Cadwell, Stephanie Cadwell or Ian McClarty would not appear in an organisation-name search. **Free, not run.**
- **DELAWARE UCC WAS NOT SEARCHED, and that rests on an unverified premise.** Arizona is the correct filing office **for an Arizona LLC**, and no Delaware entity was found — but **the Delaware corporate registry was itself never searched** (`icis.corp.delaware.gov` not reached), and **Cleary Gottlieb acting as sell-side counsel on the RadiusDC deal makes a holdco structure plausible**. If a Delaware holdco exists, there could be filings nobody in this file has seen.
- **THE PORTAL'S OWN COVERAGE BANNER IS STALE.** It reads "all UCC records filed on or prior to Thursday, April 9, 2026" while returning a 2026-07-22 filing. The index is evidently more current than it claims, but **the true coverage cut-off is unknown**, so a filing between April and August 2026 could in principle be missing.
- **THE ALTAY CORPORATION RELATIONSHIP IS UNEXPLAINED.** File 2022-003-1526-2 names "PHOENIXNAP" as co-debtor with a Los Angeles company against a hardware reseller. **What the relationship is, and what was financed, is unknown.**

---

## 9. Cost ceiling

What one GPU node can be worth to phoenixNAP, and what the same box costs to build. This section answers one question: **at what hardware acquisition cost does their flagship GPU SKU still pay for itself?**

**Target node:** **`d3.g2.c3.xlarge`** — 2× Intel Max 1100, 2× Xeon Gold 6442Y, 512 GB, 4× 2 TB NVMe, 2× 25 GbE. **Published rate card, Phoenix:** $2.67/hr on demand; **$1,778.49/mo** at 1-month; **$1,110.27/mo** at 12-month; **$992.12/mo** at 24-month; **$920.23/mo** at 36-month reservation ([live catalogue JSON](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json)).

### 9.1 Assumptions — read these first. They are assumptions, not findings.

**EVERY NUMBER IN §9.2 IS AN ASSUMPTION-DRIVEN MODEL, NOT A RESEARCHED FACT. phoenixNAP publishes no cost data and none was found.**

1. **List rate card = realised revenue.** In reality enterprise customers negotiate, so realised revenue is likely **10–25% lower**, which **tightens the ceiling further**.
2. **Operating-cost share of revenue is 45–60%.** This covers power at an assumed 1.2–1.6 kW per node, space and rack, the 15 TB of included bandwidth, 20 Gbps DDoS scrubbing, 24×7 NOC and support, provisioning automation, and allocated SG&A. **None of these inputs was sourced.** The true share could plausibly be 35% or 70%.
3. **100% utilisation of the node.** Any idle or unsold capacity reduces the ceiling proportionally — and **their own marketing page admitting GPU stock in only 2 of 6 priced regions suggests utilisation is the real constraint.**
4. **No financing cost.** In fact they borrow (BMO, U.S. Bank), so **add interest and the true ceiling drops another 5–10%.**
5. **A 12/18/24-month payback horizon is a convention, not their policy.** A bank-financed owner-operator on **5-year UCC terms** may in practice accept **36–48 months**, which would roughly **double the top of the band**.

**Anyone using these numbers in front of the customer must present them as "here is the model, correct my inputs" — never as a claim about their economics.**

### 9.2 Rent-derived ceiling — `d3.g2.c3.xlarge`

| Case | Revenue basis | Share available to hardware | $/mo to hardware | Ceiling @ 12 mo | Ceiling @ 18 mo | Ceiling @ 24 mo |
|---|---|---|---|---|---|---|
| **LOW** | $920.23/mo realised (36-month reservation) | 40% | **$368** | **$4,416** | **$6,624** | **$8,832** |
| **MID** | $1,110.27/mo realised (12-month reservation) | 50% | **$555** | **$6,663** | **$9,995** | **$13,327** |
| **HIGH** | $1,778.49/mo realised (1-month rate) | 55% | **$978** | **$11,738** | **$17,607** | **$23,476** |

**Defensible working band for hardware acquisition cost per GPU node: roughly $6,700 at a hard 12-month payback up to about $23,500 at a generous 24-month payback on undiscounted monthly pricing.**

**The number to quote against in a first meeting is the MID 18-month figure: approximately $10,000 per node.**

### 9.3 BOM rebuild at street prices — and the critical finding

Reconstruction of `d3.g2.c3.xlarge`. **Sourced items are marked. Unsourced items are marked and left blank — they are not invented.**

| Component | Part | Street price | Status |
|---|---|---|---|
| **CPU × 2** | **Intel Xeon Gold 6442Y** (24c, 60 MB, 2.60 GHz) | **$5,580.56 each = $11,161.12** | **SOURCED** — Newegg single-unit street listing. **Note:** [Intel ARK SKU 232380](https://www.intel.com/content/www/us/en/ark.html) returned specifications but **no published 1KU recommended customer price**; volume and OEM tray pricing will be materially below street, but no sourced figure for it exists |
| **GPU × 2** | **Intel Data Center GPU Max 1100** (48 GB HBM2e, 300 W, PCIe double-width) | **~$8,000 each = ~$16,000** | **SOURCED** — starting retail approximately $8,000 as of **April 2025** (CpuTronic spec/price page, which benchmarks it against an ~$15,000 NVIDIA H100) |
| **Memory** | 512 GB DDR5 RDIMM | — | **NOT SOURCED. Must be quoted.** |
| **Storage** | 4× 2 TB U.2 / E1.S NVMe | — | **NOT SOURCED. Must be quoted.** |
| **Platform** | Dual-socket board, 2U/4U GPU chassis with 300 W-capable double-width slots, redundant Titanium PSUs, BMC, rails | — | **NOT SOURCED. Must be quoted.** |
| **Network** | 2× 25 GbE NIC | — | **NOT SOURCED. Must be quoted.** |
| **SOURCED SUBTOTAL (CPU + GPU only)** | — | **≈ $27,161 per node at street** | — |

> ### **THE CRITICAL FINDING**
>
> **The sourced CPU-plus-GPU street subtotal of ≈$27,161 EXCEEDS the entire rent-derived acquisition ceiling — $6,700 mid-case at 18 months, and $23,476 even in the most generous 24-month case — BEFORE any memory, storage, chassis, network or integration cost is added.**

Three explanations are possible, and **all three are commercially useful**:

**(a) phoenixNAP acquired these GPUs far below street.** Intel programme or seeding pricing is **highly likely** given the dedicated [Intel-branded offer landing page](https://phoenixnap.com/offers/intel-data-center-max-gpu-1100-bmc), the "no additional licensing fees" messaging, and their documented history of participating in Intel's Early Ship / Early Deployment programme through Supermicro.
**(b) They are amortising over 36–60 months rather than 12–24**, consistent with their **5-year UCC terms**.
**(c) The GPU fleet is deliberately small and strategic rather than a profit centre**, consistent with stock being admitted in only 2 of 6 priced regions.

**All three point to the same conclusion: their accelerator tier is not economically self-supporting at market hardware prices. That is precisely why a credible price-per-node proposal is interesting to them.**

### 9.4 The Supermicro equivalent — and the comparison that actually matters

The like-for-like substitute is a **Supermicro X13/X14 dual-socket 2U or 4U PCIe GPU SuperServer taking 2–4 double-width 300–350 W accelerators with 512 GB DDR5 and 4× U.2 NVMe.** **No Supermicro list or street price for that configuration is held in this file and none is fabricated — that is the quote to build.**

**The comparison to run for them is NOT "Supermicro versus HPE on the same Intel Max 1100."** It is: **at the same monthly rate card they already publish, what accelerator can a Supermicro chassis carry and still clear an 18-month payback?** On the $6,700–$10,000 mid-case ceiling that is a **single-GPU or dual-mid-range-GPU node, not a flagship AI box** — and **that reframing is the whole sales conversation.**

### 9.5 GAP — cost-ceiling track

- **Only two BOM line items were sourced**: the two Xeon Gold 6442Y (Newegg street $5,580.56 each) and the Intel Max 1100 (~$8,000 starting retail, an **April 2025** datapoint that is now 16 months old). **No sourced price exists for the 512 GB DDR5 RDIMM set, the 4× 2 TB NVMe, the dual-socket GPU chassis, the PSUs or the 25 GbE NIC. The comparison is partial by design rather than fabricated.**
- **No Supermicro list or street price** for the equivalent chassis was obtained.
- **All operating-cost inputs are assumptions**: power draw per GPU node, Phoenix and Ashburn power rates, rack cost, and utilisation. **None were sourced. The cost ceiling band is a model, not a finding.**
- **Street prices are upper bounds.** phoenixNAP buys at distributor or contract pricing, and — given the Intel offer page and their programme history — **possibly far below street on the accelerator specifically**. The direction of the conclusion (the accelerator tier does not pay for itself at market prices) is robust; the magnitude would compress under real contract pricing.
- **The payback horizon is a convention.** Their five-year UCC terms suggest they may in practice tolerate 36–48 months, which would roughly double the top of the band and change the entire arithmetic. **Ask them what payback they underwrite to — it is a legitimate discovery question and it is the single input that moves this model most.**

---

## 10. Customers & network

### Named customers

Unlike most operators in this territory, phoenixNAP **does publish named customer references**. All four below come from the company's own [customer experience page](https://phoenixnap.com/customer-experience).

| Name | Grade | What the source actually says |
|---|---|---|
| **chuck-stack** | **Company-published case study** | An SMB ERP provider that moved off AWS to Bare Metal Cloud and reports **cutting cloud infrastructure cost by about 75%** — described as a high-performance hybrid cloud at a quarter of the price of AWS or Azure |
| **UC Berkeley, Department of Statistics** | **Company-published case study** | Academic and research compute, cited for cloud solution plus support and billing experience. **Relevant because academic statistics and ML teaching workloads are exactly the buyer for the Intel Max 1100 tier** |
| **Kaligent** | **Company-published case study** | **Explicitly an AI use case** — using Bare Metal Cloud to bring AI into their client-facing tools. **This is the named reference for their accelerator business** |
| **TPilot** | **Company-published case study** | Used phoenixNAP to stand up their first US-based hosting footprint for premium clients |
| **Ubersmith** | **Third-party published, and a systems detail rather than a customer** | Ubersmith publishes a [phoenixNAP case study](https://ubersmith.com/case-studies/phoenixnap/), indicating phoenixNAP runs **Ubersmith for subscription billing and provisioning** of the bare-metal business |
| **Vertical mix (stated, not named)** | **Vendor-published + third-party** | HPE's April 2025 release states phoenixNAP is meeting demand across **advertising technology, financial technology, and state/local/education (SLED)**. ServeTheHome's 2023 facility coverage reports cages serving **financial, healthcare and governmental** clients. phoenixNAP has also publicised completing **AzRAMP**, Arizona's state cloud authorisation, consistent with SLED exposure ([HPE, 2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html) · [ServeTheHome](https://www.servethehome.com/putting-the-bare-metal-server-in-the-phoenixnap-bare-metal-cloud-intel-xeon-sapphire-rapids-supermicro/)) |
| **RadiusDC** | **Press release — a counterparty, not a customer** | Becomes phoenixNAP's **landlord and colocation provider in Phoenix** on close of the Q2 2026 transaction; phoenixNAP is explicitly stated to **remain a tenant**. Not a customer, but a new counterparty that will influence where future racks land ([PRNewswire](https://www.prnewswire.com/news-releases/radiusdc-to-acquire-phoenixnaps-phoenix-data-center-and-colocation-business-302711634.html)) |

### Network — AS12189

- **Registry:** **AS12189 (PhoenixNAP LLC)**, ARIN handle PHOEN-56, autnum registered **2009-07-23**, last changed **2026-04-06**. IRR AS-SET **LEVEL3::AS-PHOENIXNAP** ([ARIN RDAP](https://rdap.arin.net/registry/autnum/12189))
- **Address space registered to PhoenixNAP LLC (PHOEN-56):** 144.90.0.0/16 · 192.240.192.0/18 · 125.253.64.0/20 + /21 + /22 + /23 · 103.67.200.0/22 · 104.244.52.0/22 (PNAP-03) · 199.201.104.0/21 (SC-ASH) · 69.160.32.0/20 · 64.38.220.0/23 (PNAP-01) · 23.235.242.0/24 and 23.235.243.0/24 · IPv6 **2607:6000::/28** (PHOENIXNAP-V6) and **2607:3000::/32** (SECURED-CLOUD) ([ARIN RDAP entity PHOEN-56](https://rdap.arin.net/registry/entity/PHOEN-56))
- **Separately registered:** **131.153.0.0 – 131.153.247.255 to SECURED SERVERS LLC** (ARIN handle SSL-65), **with the same phoenixNAP technical contacts** ([ARIN RDAP 131.153.36.0](https://rdap.arin.net/registry/ip/131.153.36.0))
- **Capacity:** **500–1000 Gbps** declared traffic level · **Heavy Outbound** ratio · **Global** scope · **Content** network type · IPv6 enabled, no multicast · **1,000 IPv4 and 100 IPv6 prefixes** declared ([PeeringDB net/2932](https://www.peeringdb.com/api/net/2932))
- **Customer-facing ports:** every modern bare-metal SKU ships **2× 25 Gbps bonded**; GPU nodes are marketed at **50 Gbps with 20 Gbps of DDoS scrubbing and 15 TB of included transfer**
- **Peering policy:** **Selective**, preferred at locations, **no contract required, not ratio-dependent**
- **IX presence — 10 connections, ≈650 Gbps of declared port capacity:** Equinix Ashburn **100G** · AMS-IX **100G** · DE-CIX Frankfurt **100G** · SIX Seattle **100G** · BIX.BG **100G** · DE-CIX Phoenix **100G** · Equinix Chicago **20G** · Equinix Los Angeles **10G** · Equinix IX Milan **10G** · Ninja-IX Phoenix **10G**
- **No published looking glass, no route server, and no individual PoCs in PeeringDB**
- **Secondary ASN caveat — UNRESOLVED:** third-party BGP tooling attributes **AS59210** (for prefix 131.153.46.0/23) and **AS207134** (labelled "PHOENIX NAP, LLC." by IPinfo) to phoenixNAP. **ARIN RDAP resolves 59210 into an APNIC block and 207134 into a RIPE block** — both are out-of-region registrations that **could not be confirmed at source**. **Treat AS12189 as the only verified ASN**; the out-of-region ASN and prefix footprint is unmapped

**Staleness caveat:** the PeeringDB record was last updated **2026-03-25**, but its **facility list was last updated 2021-10-01**. Do not size this account from PeeringDB alone.

---

## 11. Political & public record

Public records only. Every line is tagged. Named principals only.

| Subject | Finding | Tag |
|---|---|---|
| **Ron Cadwell** (Founder & CEO) | **FEC individual-contribution search NOT COMPLETED.** `api.open.fec.gov` schedule_a queries returned `{"error":{"code":"OVER_RATE_LIMIT"}}` on the shared DEMO_KEY across three separate attempts, and the fec.gov browse page returned the search form with no populated data rows. **This is a tooling failure, NOT a finding — do not record it as "no record found"** ([API query](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=CADWELL%2C+RON) · [fec.gov browse](https://www.fec.gov/data/receipts/individual-contributions/)) | **unverified — portal/API blocked** |
| **Ian McClarty** (President) | **FEC individual-contribution search NOT COMPLETED** — same OVER_RATE_LIMIT condition. **No result either way** ([API query](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=MCCLARTY%2C+IAN)) | **unverified — portal/API blocked** |
| **William Bell** (EVP Products) | **FEC individual-contribution search NOT COMPLETED** — same condition. Note also that **"BELL, WILLIAM" is a high-collision name**; any hit would require employer, occupation and Phoenix-metro address matching before being attributed ([API query](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=BELL%2C+WILLIAM)) | **unverified — portal/API blocked** |
| **Stephanie Cadwell** (co-founder) | **Not searched.** The surname spelling is itself unresolved across sources — **Cadwell vs Caldwell** — so a search would not have been reliable ([New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/)) | **not searched** |
| **phoenixNAP** (entity) | **Relevant non-federal posture, sourced and positive:** phoenixNAP **completed AzRAMP**, Arizona's state cloud security authorisation programme, publicised by Ian McClarty. That is a **state-government procurement credential**, and HPE's 2025 release confirms **SLED as a named demand vertical**. **There is no evidence of a corporate PAC**, and **state-level campaign-finance databases (Arizona SOS, City of Phoenix) were NOT searched** ([AzRAMP announcement](https://www.linkedin.com/posts/mcclarty_phoenixnap-successfully-completes-azramp-activity-6867186225674108928-wEPk) · [HPE, 2025-04-04](https://www.hpe.com/us/en/newsroom/press-release/2025/04/phoenixnap-advances-cloud-services-using-hpe-disaggregated-data-center-modular-hardware-system-servers-with-intel-xeon-6.html)) | **government-adjacent business posture verified; campaign finance not searched** |

**Stated plainly: no principal on this account has actually been screened for federal political contributions.** Every FEC row above is a **tooling failure, not a clean result**. Closing this requires a personal `api.data.gov` key and a rerun on Ron Cadwell, Ian McClarty, William Bell and Stephanie Cadwell/Caldwell.

**On the positive side of the public record:** the AzRAMP credential plus the confirmed SLED vertical means **government procurement is a live part of their book**, which in turn means supply-chain provenance, country-of-origin and TAA-style questions may come up in any hardware conversation. **Be ready for them; do not be surprised by them.**

---

## 12. Public contact channels

Public-source only. **No personal mobile numbers and no private residential addresses are listed here, and none were sought.** GAP is shown where no published channel exists.

| Channel | Value | Source |
|---|---|---|
| **Corporate switchboard / IP admin** | **+1-480-422-2022** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Support / NOC** | **+1-480-646-5362 · support@phoenixnap.com** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **IP administration (role mailbox)** | **ipadmin@phoenixnap.com** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Abuse (role mailbox)** | **abuse@phoenixnap.com** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Named engineer — Robert Carmody**, ARIN OrgTech (US) | **robertca@phoenixnap.com · +1-480-506-0120** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Named engineer — Brian Musgrave**, ARIN OrgTech (US) | **brianmu@phoenixnap.com · +1-480-401-0309** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Named engineer — Dragan Petrovic**, ARIN OrgTech (EMEA) | **draganp@phoenixnap.com · +356 77548965 · +381 621448366** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Named engineer — Milos Ilic**, ARIN OrgTech (Serbia) | **milosi@phoenixnap.com · +381 615494754** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Named engineer — Adrian Montebello**, ARIN OrgTech (Malta) | **adrianm@phoenixnap.com · +356 79305305** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **HQ postal (ship-to and site-visit)** | **phoenixNAP, 3402 E. University Drive, Suite 420, Phoenix, AZ 85034-7200** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) · AZ SOS UCC file 2026-003-2810-7 |
| **LinkedIn — Ian McClarty, President** | [linkedin.com/in/mcclarty](https://www.linkedin.com/in/mcclarty) | LinkedIn |
| **LinkedIn — William Bell, EVP Products** | [linkedin.com/in/williamb](https://www.linkedin.com/in/williamb) | LinkedIn |
| **LinkedIn — Ron Cadwell, CEO** | [linkedin.com/in/ron-cadwell-0b747313b](https://www.linkedin.com/in/ron-cadwell-0b747313b/) | LinkedIn |
| **LinkedIn — company page** | [linkedin.com/company/phoenix-nap](https://www.linkedin.com/company/phoenix-nap) | LinkedIn |
| **Live pricing and product catalogue** (use to track whether the GPU tier changes) | [phoenixnap.com/bare-metal-cloud/instances](https://phoenixnap.com/bare-metal-cloud/instances) — prices are JS-injected; the underlying feed is [api-data.json](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) | phoenixNAP |
| **Email pattern — DERIVED, NOT VERIFIED** | Six independently published ARIN addresses (`robertca`, `brianmu`, `draganp`, `milosi`, `adrianm`) give the pattern **firstname + first two letters of surname @phoenixnap.com**. Applied to the executives this predicts **ianmc@phoenixnap.com** and **williamb@phoenixnap.com**. **DERIVED. NOT CONFIRMED. Do not treat as verified and do not put a cold email on it without a fallback route** | [ARIN RDAP autnum 12189](https://rdap.arin.net/registry/autnum/12189) |
| **Direct-dial for any executive** | **GAP — none published.** Only the switchboard, the support line and the five named engineers' direct numbers exist | — |
| **Named CFO or procurement contact** | **GAP — none identified anywhere** | — |

---

## 13. Supermicro sales angle

### Classification: **incumbent defence that has already partially failed → WIN-BACK, not greenfield and not displacement of a stranger**

Supermicro is **not a new vendor here.** Supermicro published a named case study on phoenixNAP in **June 2017** with quotes from the President and the VP of Products, deployed **X11 BigTwin and Simply Double SuperStorage plus Rack Scale Design and Supermicro Server Manager globally**, and got phoenixNAP into **Intel's Early Ship programme**. As recently as **March 2023**, ServeTheHome documented their Sapphire Rapids bare-metal instances as Supermicro, and phoenixNAP still runs a **live Supermicro ecosystem page** and co-ran a Supermicro webinar in **June 2025**.

**But the last two platform refreshes both went to HPE:** ProLiant RL300 Gen11 for Ampere in **August 2023**, and ProLiant Compute DL320 Gen12 DC-MHS for Intel Xeon 6 in **April 2025**. Two consecutive generations lost, announced by HPE, quoted by phoenixNAP's own President and EVP of Products. **The account is warm and slipping, not cold.**

### The opening that is unique to this operator

**Their accelerator tier is frozen and undefended.** The entire GPU catalogue is **three trims of one node** built around **2× Intel Data Center GPU Max 1100**, introduced around **October 2023** and untouched for **~34 months**. **There is no NVIDIA SKU and no AMD SKU anywhere in their live billing catalogue** — the production product JSON that feeds their own pricing pages, all 101 products, contains exactly one `gpuConfigurations` value: **"Intel Max 1100 GPU"**. Meanwhile their own marketing page admits **GPU stock in only two of the six regions where the billing system prices it**.

They have an AI story — the **Kaligent** case study, the **UC Berkeley Statistics** reference, the **adtech/fintech/SLED** demand HPE cites — and effectively **one aging accelerator** to serve it with. **HPE did not win that slot. Nobody did.**

### The money argument — run their own rate card back at them

`d3.g2.c3.xlarge` lists at **$920.23/mo on a 36-month reservation** and **$1,778.49/mo monthly**. Even generously modelled (§9), that supports roughly **$6,700–$10,000 of hardware at an 18-month payback per node**. Two Xeon Gold 6442Y at street plus two Max 1100 at street is already **about $27,000 before memory, NVMe, chassis or NIC**.

**Their current GPU node cannot pay for itself at market hardware prices.** That means it was bought on programme pricing, or it is being amortised over five years, or it is a strategic loss-leader. **All three are reasons to talk about a different node.**

And because the UCC record shows they **buy with bank debt on their own balance sheet** — BMO Bank N.A. continuously since 2014, plus **U.S. Bank Equipment Finance new in March 2026** — rather than leasing from an OEM captive, **every dollar of node cost lands on their interest expense and depreciation. Price-per-deployed-node is not a talking point for this buyer, it is the entire conversation.**

### Timing

The **RadiusDC transaction closed in Q2 2026** and took the Phoenix colo with it, leaving phoenixNAP as roughly **80% of its former self** and structurally a **bare-metal-cloud and network company**. Their UCC-1 cadence ran at a **~33-day median from July 2025 to April 2026, then stopped dead on 2026-04-02** — four months of silence during the carve-out. **That pause is ending.** The next financing tranche will underwrite a **BMC-only fleet**, and the accelerator tier is the most exposed line in it. **Reach out now, ahead of the September–December window.**

### The one qualifying question for first contact

Ask this, to **William Bell, EVP of Products**, and ask nothing else:

> **"Your GPU catalogue has been three trims of the same dual Max 1100 node since late 2023, and there's no NVIDIA or AMD option in it at all — when you refresh the accelerator tier post-divestiture, is the constraint the silicon supply, the chassis, or the price you can put on a node and still clear payback against your published rate card?"**

That question is **unanswerable without revealing which of three fights this is**: procurement economics (**Supermicro's fight to win**), platform standardisation on HPE (**a harder fight, worth knowing early**), or an Intel commercial arrangement (**in which case position the Supermicro chassis as the vehicle rather than attacking the silicon choice**).

### Rule 8 — distributor caution (read before dialling)

**This is a returning Supermicro buyer with a long, documented history**, so **assume there is an existing route to market and find it BEFORE quoting anything.** Do not price direct into this account without first establishing **whether their historical and current Supermicro purchases flow through a distributor or VAR, and whether an existing partner has standing on the account.**

If a partner is in place, **register the opportunity with that partner named and let the quote go through them.** Going around them to win a node price will cost more in channel damage than the deal is worth, and **it will surface immediately** — their procurement and legal already run everything through a papered lender facility, so an unexpected direct invoice is not something that slips by.

**Sequence — do not reorder:** ① clear the channel/distributor position under Rule 8 → ② register the lead (Phoenix AZ = West Coast South excl. CA = **T1 | T31**, Team 1's own territory, **CRM verified clean 2026-08-11 with no lead, no account, no do-not-call**) → ③ make contact with the single qualifying question above. **Territory is clean for registration — register it, but register it with the channel question answered rather than assumed.**

---

## 14. Verification appendix

### 14.1 Single-source and low-grade claims — re-verify before quoting

| Claim | Only source | Risk |
|---|---|---|
| **Marcus Bohn = Chief Legal Officer** · **Cindy Anastasi = HR Director** | [RocketReach management listing](https://rocketreach.co/phoenixnap-management_b5c0b21bf42e087f) | **Aggregator only. No phoenixNAP-published confirmation. Do not use these titles in an email until verified** |
| **Frank Eickenhorst = VP Support Services & DC Ops** · **Seow Lim = VP Architecture & Platform** | [Tracxn profile](https://tracxn.com/d/companies/phoenixnap/__mD8bU1wR9YlaxJnT-i3Qsq2RAnC6xvg1lhsYqyiFn0g) | **Aggregator only.** Eickenhorst in particular is named in the buying committee — **confirm the title before using it** |
| **Stephanie Cadwell as co-founder** | [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) | **Single source, and the same article inconsistently spells the surname "Caldwell" in body text.** Low-medium confidence |
| **Headcount ~183** | [Zippia](https://www.zippia.com/phoenixnap-careers-1559024/revenue/) | **Third-party estimate with no visible methodology.** Use the 150–300 band, tagged as an estimate |
| **Revenue $18–25m** | Zippia / Kona Equity | **Almost certainly wrong** — irreconcilable with a marketed USD 70m EBITDA. **Do not enter in CRM** |
| **Phoenix property bought 2009 for USD 6.3m; ~200,000 sq ft** | [DataCenterDynamics](https://www.datacenterdynamics.com/en/news/radiusdc-enters-arizona-acquires-phoenixnap-facility-in-phoenix/) — **HTTP 403 on direct fetch; obtained from search snippets only** | Secondary press figure, **not verified at source and not confirmed by any county record** |
| **Continued Supermicro use in 2024–2026** | [phoenixnap.com/offers/supermicro-servers](https://phoenixnap.com/offers/supermicro-servers) | **The page carries no model numbers and no date.** Graded **circumstantial**. **Do not state current Supermicro deployment as fact** |
| **Third-party listicles claiming phoenixNAP offers "L4 to H100"** | Various aggregators | **Contradicted by phoenixNAP's own pricing system.** Aggregator noise — **do not repeat** |

### 14.2 Conflicting figures — shown side by side, not resolved

**Revenue**

| Source | Figure |
|---|---|
| Zippia / Kona Equity (aggregators) | **$18–25m** |
| [New Project Media](https://newprojectmedia.com/ma-phoenixnap-sale-process-moves-into-second-round-with-bids-topping-usd-1bn/) — live sale process | **USD 70m marketed EBITDA**, first-round bids **topping USD 1bn** at **14.3x EV/EBITDA** (prior-year EBITDA reported as USD 50m) |
| [ION Analytics / Infralogic](https://ionanalytics.com/insights/infralogic/goldman-run-sale-for-colo-firm-slated-for-early-2025/) | Goldman Sachs preparing a **whole-company sale for 1Q25** |

**Assessment, not a resolution:** a business with $70m of EBITDA is not an $18m-revenue business. **The aggregator figures should be discarded.** A defensible working assumption is **revenue in the low-to-mid hundreds of millions USD** with ~$70m EBITDA **as marketed** — and note that after the RadiusDC carve-out phoenixNAP retains what it describes as **approximately 80% of its global business**. **No authoritative revenue figure was obtained.**

**GPU region availability**

| Source | Regions |
|---|---|
| [GPU marketing page](https://phoenixnap.com/bare-metal-cloud/gpu-servers) | **Phoenix (AZ) and Ashburn (VA)**, "More Coming Soon" |
| [Live billing catalogue](https://phoenixnap.com/wp-content/themes/bootscore-child/cache/api-data.json) | **PHX, ASH, NLD, SGP, CHI, SEA** — all six, at identical prices |

**Not a contradiction to score against them — read it as a small, concentrated fleet with globally provisioned pricing.** See §6.

**Secondary ASNs**

| Source | Claim |
|---|---|
| Third-party BGP tooling / IPinfo | **AS59210** and **AS207134** belong to phoenixNAP |
| [ARIN RDAP](https://rdap.arin.net/registry/autnum/12189) | AS59210 resolves into an **APNIC** block; AS207134 resolves into a **RIPE** block — **neither confirmed at source** |

**Unresolved. Treat AS12189 as the only verified ASN.**

### 14.3 Open gaps

1. **UCC COLLATERAL TEXT — the single biggest gap.** All 20 Arizona filings located and transcribed, but the AZ SOS public viewer **does not render collateral descriptions or serve filing images**. **No collateral clause was seen and none is paraphrased.** Page counts are the only proxy (the 2025-08-06 filing runs **16 pages**, the 2026-01-28 amendment **10 pages** — long equipment schedules). **Close it:** UCC-11 information requests or certified copies from **AZ SOS Business Services, 1700 W Washington St Fl 2, Phoenix AZ 85007, 602-542-6187**, starting with files **2025-002-9842-8**, **2026-001-2461-6**, **2026-001-2475-0** and **2026-001-0311-3**.
2. **ARIZONA CORPORATION COMMISSION REGISTRY — no officers, managers, members, statutory agent, annual-report signatories or filing history obtained.** Legacy `ecorp.azcc.gov` is **NXDOMAIN**; the replacement returns **403** to non-browsers and gates results behind a **6-character image CAPTCHA**, which is not solved. OpenCorporates (HAProxy CAPTCHA) and Bizapedia (security check) were also blocked. **The entity map in this file comes from UCC and ARIN, not the registry.**
3. **DELAWARE — `icis.corp.delaware.gov` was not searched.** No Delaware entity was found by other means, and Arizona is the correct UCC filing office for an Arizona LLC, but **a Delaware holdco cannot be ruled out**, and **Cleary Gottlieb as sell-side counsel on the RadiusDC deal makes a holdco structure plausible**.
4. **HISTORICAL WHOIS — not obtained.** whoisrequest.com returned **Cloudflare 403**; whoxy and securitytrails require paid API keys. Current RDAP only: phoenixnap.com created **2009-02-26**, expires 2027-02-26, last changed 2026-01-27, registrar **NameCheap**, nameservers **Cloudflare (ALEENA / MICAH)**, registrant **privacy-protected**. **No historical registrant names or addresses.**
5. **USPTO — no trademark record retrieved at source.** `tsdrapi.uspto.gov` returns **HTTP 401** (registered API key now required); `tmsearch.uspto.gov` rejected the query with **HTTP 405**; `uspto.report` returned **403**; `assignment-api.uspto.gov` connection failed. Search results indicate **Phoenix NAP L.L.C. owns at least SECURED SERVERS (serial 87396103) and HAAS (serial 85655621)**, but **no declaration signatory, no correspondent or attorney of record, no filing or renewal dates and no owner address** were obtained from a primary source.
6. **FEC — NO PRINCIPAL WAS ACTUALLY SCREENED.** `api.open.fec.gov` returned **OVER_RATE_LIMIT** on the shared DEMO_KEY on every attempt and the fec.gov browse UI rendered no data rows. **Recorded as unverified, not as "no record found."** Needs a personal `api.data.gov` key and a rerun on Ron Cadwell, Ian McClarty, William Bell and Stephanie Cadwell/Caldwell. **State-level Arizona and City of Phoenix campaign-finance databases were also not searched.**
7. **MARICOPA COUNTY ASSESSOR — no parcel record obtained** for 3402 E University Dr or for 2353 W University Dr (Tempe). `mcassessor.maricopa.gov` search results are AJAX-loaded and the `/mcs/api/` endpoints return the HTML shell without an auth token. **No APN, no assessed value, no recorded deeds, no mortgage recordings and no record of the RadiusDC conveyance.** The only figures held are the secondary press ones (USD 6.3m in 2009, ~200,000 sq ft).
8. **SERVER AND GPU UNIT COUNTS — completely unknown.** No public number exists and **none is invented**. Only bounds are available: **6 billing regions, 82 server SKUs, 16 PeeringDB facilities, GPU stock admitted in 2 regions**, ARIN allocations on the order of **low-hundreds-of-thousands of IPv4 addresses**, and a ~200,000 sq ft flagship whose planned 8 MW expansion implies current occupied IT load is **well under 8 MW**.
9. **BOM COMPONENT PRICING — only two line items sourced.** Xeon Gold 6442Y at **$5,580.56** street (Newegg) and Intel Max 1100 at **~$8,000** starting retail (April 2025 datapoint). **No sourced price for the 512 GB DDR5 RDIMM set, the 4× 2 TB NVMe, the dual-socket GPU chassis, PSUs or the 25 GbE NIC, and no Supermicro list or street price for the equivalent chassis.**
10. **OPERATING COST INPUTS — all assumptions.** Power draw per GPU node, Phoenix and Ashburn power rates, rack cost and utilisation were **not sourced**. **The cost ceiling band in §9 is a model, not a finding.**
11. **GPU NODE CHASSIS VENDOR — unattributed.** Nobody has published who builds the `d3.g2.*` Intel Max 1100 nodes. HPE is confirmed for Ampere Altra (RL300 Gen11) and Xeon 6 (DL320 Gen12); Supermicro is confirmed for X11 BigTwin and circumstantial for Sapphire Rapids. **The GPU chassis, the AmpereOne A96-36X chassis and the AMD EPYC 4000-series chassis are all unattributed — three open competitive slots.**
12. **AmpereOne `a2.c9.*` INTRODUCTION DATE — not pinned.** Present in the live billing catalogue on 2026-08-10 but **absent from every archived instances-page snapshot**. Wayback only began capturing the `api-data.json` price file in **October 2025**; a diff across those ~50 snapshots would pin it **and would also produce a precise price-change history**. **Not done for time — this is the highest-value cheap follow-up in the file.**
13. **GPU FIRST-APPEARANCE PRECISION** — bracketed to between **2023-09-13 (absent)** and **2023-11-09 (present)**, corroborated by a phoenixNAP preorder push dated 2023-09-19. **Not narrowed further because Wayback rate-limited repeated raw-capture requests.**
14. **EXECUTIVE ROSTER BELOW THE TOP THREE — aggregator-only.** Marcus Bohn, Cindy Anastasi, Frank Eickenhorst and Seow Lim come from RocketReach, Comparably and Tracxn only. **No phoenixNAP-published leadership page exists** — `phoenixnap.com/company/leadership` returns **404**. **Titles unconfirmed; do not use in an email until verified.**
15. **NO CFO IDENTIFIED.** For a company that finances its fleet monthly through two banks, **this is a real hole in the buying committee**.
16. **JOB POSTINGS — thin.** Only a generic **Data Center Technician** req in Phoenix ($21–30/hr) was found. **No procurement, supply-chain, capacity-planning or GPU/ML-infrastructure reqs located**, which would have been the best leading indicator of a fleet build.
17. **COURT DOCKETS — metadata only, filings not read.** CourtListener returned **17 matches**. Two are directly about phoenixNAP: ***Phoenix NAP LLC v. Poofless LLC et al.***, D. Ariz. **2:19-cv-05005**, filed 2019-08-21, terminated 2020-06-03 (phoenixNAP as **plaintiff**; defendants include Poofless LLC, Poofless1 LLC, Cosmic Games ULC, Preston Arsement, Joe Melsha and Anthony Uckon); and ***Stanziale, Jr. v. Phoenixnap***, Bankr. D. Del. **16-50054**, filed 2016-02-19, terminated 2016-07-11 (adversary proceeding tied to the EP Liquidation LLC estate, **almost certainly a preference clawback**). **Neither docket was read. No Maricopa County Superior Court search was run at all.**
18. **REVENUE — irreconcilable.** See §14.2. **No authoritative number obtained.**
19. **OUTCOME OF THE SALE PROCESS — UNRESOLVED, and it matters commercially.** The whole-company sale ran through 2025 with bids above USD 1bn; **the only thing that visibly completed is the Phoenix colo carve-out to RadiusDC in Q2 2026.** Whether the rest of the company was **sold, partially recapitalised, or withdrawn from market is unknown — and it directly determines who signs the next capex plan.** This should be the first thing checked before any executive outreach.
20. **SECONDARY ASNs — unmapped.** See §14.2.
21. **HPE NEWSROOM PAGES TIMED OUT ON DIRECT FETCH.** Both the 2023-08-03 and 2025-04-04 HPE releases **timed out twice** and curl produced no file; their content was recovered via **search snippets and mirrors** (InsideHPC, DCD, Morningstar, Nasdaq, Silicon UK, HostingJournalist). The quotes and product names are consistent across mirrors, but **the primary HPE pages were not read directly**.
22. **TOOLING NOTE FOR A RE-RUN.** The ZoomInfo MCP connector — along with carta, figma, atlassian, spglobal and adobe — requires OAuth authorisation and could not be used in this non-interactive session. **Authorising the ZoomInfo connector via claude.ai connector settings would likely close the revenue-estimate, CFO and named-staff gaps on a re-run.**
