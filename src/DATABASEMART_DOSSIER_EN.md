# Database Mart LLC (GPU Mart) — Sales Intelligence Dossier
**Prepared for:** Supermicro Sales Team 1 (USA) · Officer US8664 Tuo Cheng · **Date:** 2026-08-11
**Method:** Researched through corporate history, financial and registry records, U.S. political leanings, legislative and policy positions, and the company's relationships with its customers. Privately held — evidence comes from state business registries, ARIN/PeeringDB, the operator's own published GPU catalogue and pricing, UCC filings, job postings, community forums and FEC records. Every fact carries its source + date inline. GAP = not found in verified material. No fabrication.
**Territory:** League City, Texas — Texas Area = **T1** | T3. Team 1 can register directly.
**CRM status:** Verified clean 2026-08-11 in salesleads Search (Type = All) — no lead, no account, no do-not-call record. Registrable by Team 1.

---

## 1. Bottom line

Database Mart LLC is a 21-year-old, owner-operated Texas hosting company trading publicly as **GPU Mart** ([gpu-mart.com](https://www.gpu-mart.com/)) alongside VPS Mart, Server Mart, RDP-Servers, WinPC-Mart and Cloud Clusters, chartered in Texas on **2005-01-13** (SOS file 0800439627, taxpayer 32107118534, [Texas Comptroller taxable-entity record](https://data.texas.gov/resource/9cir-efmm.json)) and registered at **257 Westwood Dr, League City, TX 77573** — an address that property records show is a **single-family home**, not an office ([HAR listing](https://www.har.com/homedetail/257-westwood-dr-league-city-tx-77573/8020666)). All compute sits in two leased third-party colocation halls: Dallas inside **Psychz Networks**' space at 1515 Round Table Dr, and North Kansas City at 1530 Swift St behind **Wholesale Internet, Inc. (AS32097)** ([company data-center page](https://www.databasemart.com/data-center); [ARIN RDAP 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28)).

Commercially this is a **platform-conversion target with a live, dated buying window — not an incumbent-defence account.** There is no OEM incumbent to displace: a direct grep of both live homepages plus `/gpu-specs`, `/about/` and `/about-us` for Supermicro, Dell, Gigabyte, ASUS, Tyan, Inspur, Lenovo and HPE returned **zero hits on every term**. They self-integrate on secondary-market hosts. The single most important fact in this file is on their own flagship product page: the **H100 80GB HBM2e PCIe node at $2,099.00/month runs on a "36-Core Dual E5-2697v4" host** ([gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting), read 2026-08-11) — a 2016 Broadwell-EP platform whose root complex is **PCIe 3.0 only**, while the same page advertises the card as PCIe Gen5. Every one of their 26 published dedicated GPU SKUs runs on Xeon E5 v3/v4, Gold 6148 or Platinum 8160 silicon — **2014-2017 hosts, with zero current-generation platforms anywhere in the catalogue.**

That mismatch is now being stressed by their own buying. Between **2025-11-08** and **2026-04-19** they added six Blackwell SKUs — RTX PRO 6000 96GB, RTX PRO 5000 48GB, RTX PRO 4000 24GB, RTX PRO 2000 16GB, RTX 5090 and RTX 5060 — and consolidated them onto a dedicated hub page. A 600W-class, PCIe Gen5, 96GB GDDR7 card is the hardest part in their catalogue to run correctly on a Broadwell board, and they are additionally slicing it into a 32-core/84GB multi-tenant VPS at $479/month. Meanwhile they registered **38.247.128.0/18 — 16,384 IPv4 addresses — on 2026-01-21 and have never announced it** (0 of 326 RIS peers, [RIPEstat](https://stat.ripe.net/data/routing-status/data.json?resource=38.247.128.0/18)), and brought 5,120 leased RIPE addresses live on 2026-07-28. Nobody pays for a /18 they do not intend to fill.

The two things that could kill this deal are both known and both manageable: **their unit economics** (a rent-derived hardware ceiling of roughly $19K–$28K per node at 24-month payback, against an H100 card that alone costs $25K–$31K new — so a like-for-like new-platform pitch loses on arithmetic and must not be attempted), and **the channel** (no OEM named anywhere, uniform used-silicon hosts, 20–55% standing discounts on prior-generation cards — every signal points at distribution, brokers or the secondary market, so under Rule 8 the buying route must be established before anything is registered).

---

## 2. Snapshot

| Field | Value | Evidence / date |
|---|---|---|
| **Legal entity** | **DATABASE MART LLC** — Texas domestic LLC, organizational type code **CL**. No SEC filings (privately held). No Delaware registration found — see §14 | [Texas Comptroller taxable-entity record via data.texas.gov Socrata resource 9cir-efmm](https://data.texas.gov/resource/9cir-efmm.json?$where=upper(taxpayer_name)%20like%20'%25DATABASE%20MART%25): taxpayer_number **32107118534**; SOS/COA file number **0800439627**; `sos_status_code` **A** (active); `right_to_transact_business_code` **A** (active). Retrieved 2026-08-11 |
| **Registered NAICS** | **541410** as recorded in the state file — note that 541410 is **Interior Design Services**, almost certainly a stale or miscoded classification for a hosting company. **Recorded verbatim, not corrected** | [Texas Comptroller record](https://data.texas.gov/resource/9cir-efmm.json) |
| **Founded** | **2005-01-13** (Texas SOS charter date) | Charter date and `sos_status_date` both 2005-01-13 in the [Comptroller record](https://data.texas.gov/resource/9cir-efmm.json). Corroborated by the company's own [About page](https://www.databasemart.com/about/) ("Founded: January 13, 2005") and by the databasemart.com domain creation date of **2004-11-16** — two months before charter, consistent with a founder registering the domain then incorporating |
| **Registered address / HQ** | **257 Westwood Dr, League City, TX 77573** (Galveston County, county code 84). **This is a single-family residence, not a commercial office or datacenter** | The same address appears verbatim as (a) the Texas SOS/Comptroller registered address, (b) the ARIN Org DML-132 address, (c) both ARIN POC addresses, (d) the domain WHOIS registrant street, and (e) the public contact address ([contact-us](https://www.databasemart.com/contact-us)). Property records describe a **5-bed / 3.5-bath, ~4,300 sq ft single-family home built 2014, last sold 2018-01-25, Zestimate ~$482,700, not for sale** ([HAR](https://www.har.com/homedetail/257-westwood-dr-league-city-tx-77573/8020666); [Zillow](https://www.zillow.com/homedetails/257-Westwood-Dr-League-City-TX-77573/83100153_zpid/)). **The company has no separately identifiable corporate office in any public record** |
| **Trading brands** | GPU Mart ([gpu-mart.com](https://www.gpu-mart.com/)), VPS Mart, Server Mart, RDP-Servers, WinPC-Mart, Cloud Clusters | Company [About page](https://www.databasemart.com/about/) milestone timeline: 2014 vps-mart · 2016 Linux VPS · 2017 Cloud Clusters partnership · 2021 gpu-mart.com · 2023 own control panel + rdp-servers + server-mart · 2024 400K customer milestone · 2025-26 Blackwell + winpc-mart. **Wildcard queries of the Texas registry for CLOUD CLUSTERS, VPS MART, SERVER MART, GPU MART and WINPC each returned "(no records)" — these are trading names, not separate Texas entities** |
| **Ownership** | Owner-operated in appearance; **beneficial ownership, membership and equity split = GAP** | No SEC filings. The Texas Comptroller open-data record carries **no officer, director, manager, member, registered-agent or signatory fields**. [Crunchbase](https://www.crunchbase.com/organization/database-mart) shows **no funding rounds and no revenue**. "Owner-operated and self-funded" is an inference, not a documented fact |
| **Headcount** | **"80+ professionals across six departments: Billing, Marketing, Sales, Support (24/7), Operations, and R&D"** — *self-reported* | Company's own [About page](https://www.databasemart.com/about/). Third-party corroboration: [ZoomInfo](https://www.zoominfo.com/c/database-mart-llc/35457795) lists **51–200 employees**. The two are consistent. Note the composition — Support, Billing and Marketing are three of the six departments, so the technical staff who would evaluate a chassis are a minority |
| **Revenue** | **GAP — not disclosed. The band below is a modelled ESTIMATE and must not be entered into CRM as fact** | No SEC filings (none expected for a private LLC). [Crunchbase](https://www.crunchbase.com/organization/database-mart) carries no revenue figure and no funding rounds. **ESTIMATE:** at 80+ staff in low-cost commodity hosting, revenue per employee typically runs $125,000–$300,000 → roughly **$10M–$25M annually across all product lines**. Independent sanity check from the other side: 200–600 GPU nodes at ~$400–500/mo and ~80% occupancy → **~$0.8M–$3.5M/yr from GPU alone**. **$100M CRM threshold test: nothing in the public record supports a $100M+ characterisation** |
| **ASN** | **AS401479** — ARIN handle AS401479, network name **"DBM-ASN-KC"**, registered to Database Mart LLC **2024-11-07** | [ARIN Whois-RWS org DML-132 asns](https://whois.arin.net/rest/org/DML-132/asns.json); [RIPEstat as-overview](https://stat.ripe.net/data/as-overview/data.json?resource=AS401479). Only **21 months old** — they ran roughly four years on the Kansas City /22 before taking an ASN |
| **IPv4 estate** | **22,528 addresses across three pools, of which 16,384 are dormant** | OWNED (ARIN): **163.123.180.0/22** (1,024, net name DBM-NET-01, registered 2020-08-03) and **38.247.128.0/18** (16,384, net name DATABASEMART-CGNT-NET-1, registered 2026-01-21, **NOT ANNOUNCED**). LEASED (RIPE via IPXO): **93.127.128.0/20** (4,096) and **77.93.152.0/22** (1,024), both first announced 2026-07-28. [ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json); [RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) |
| **PeeringDB** | **NO RECORD AT ALL** — API returns `{"data": [], "meta": {"error": "Entity not found"}}` for asn=401479 | [peeringdb.com/api/net?asn=401479](https://www.peeringdb.com/api/net?asn=401479). For a network operating its own ASN and 22,528 addresses, total absence from PeeringDB is a notable immaturity signal |
| **CRM status** | **Verified clean** — no lead, no account, no do-not-call | salesleads Search (Type = All), verified 2026-08-11 |
| **Territory / team** | League City, TX → Texas Area = **T1 \| T3** → Team 1's own territory, can register directly | Territory Map-Jan.2026 (Rev.1), Sales Territory Assign tab |

---

## 3. Leadership & ownership

Evidence grades used in this section: **primary-record** = internet-number registry, state registry file, court docket, campaign-finance filing, or the company's own published page · **corroborated** = two or more independent secondary sources agree · **single-source** = one secondary source only, no corroboration · **GAP** = nothing found after a named search.

Two framing facts before the table. First, **this company publishes almost no names.** The About page describes the founder only by first name ("Morris"); the contact page lists role mailboxes and no individuals; and — unusually, and worth stating explicitly as a negative result — **ARIN yielded no named staff either.** The brief anticipated that OrgAdmin/OrgTech/OrgAbuse/NOC contacts would be real named humans. For Database Mart LLC they are not: ARIN Org **DML-132** has exactly two POC handles, both flagged `isRoleAccount = Y` with `kind = group` and generic `lastName` values ("Admin", "Abuse"). There is no individual person's name anywhere in the ARIN registration.

Second, **the single most useful artifact recovered from the registry layer is a phone number.** Both ARIN POCs carry Office phone **+1-409-877-4238** — a 409 area code covering Galveston/League City, matching the registered address. That number appears **nowhere** on the public website (the [contact page](https://www.databasemart.com/contact-us) lists no phone at all), so it is unlikely to route into a screened marketing queue.

### 3.1 Named people

| Name | Title | Role type | Evidence grade | Public contact route | FEC record | Source |
|---|---|---|---|---|---|---|
| **Morris Liu** | **Chief Executive Officer and Founder** | **Economic buyer / final decision maker / technical decision maker — all three collapse into one person at this company's size and ownership structure** | **corroborated** (title/role) · **single-source** (surname) | No direct personal email or direct dial located. Reachable only through role addresses **sales@databasemart.com**, **support@databasemart.com**, **marketing@databasemart.com**, **admin@databasemart.com**, and the ARIN-registered office line **+1-409-877-4238** | **UNVERIFIED — NOT "no record found".** Five OpenFEC Schedule A queries (contributor_name=Morris Liu; contributor_employer=Database Mart; contributor_name=Liu + contributor_city=LEAGUE CITY) all returned **HTTP 429 rate-limit** on the public DEMO_KEY across three attempts spread over the session. **No result was ever returned.** Re-run with a registered FEC API key before relying on it | [TheOrg company page](https://theorg.com/org/database-mart-llc/org-chart/morris-liu) lists exactly one named person: "Morris Liu — CEO", with no direct reports · the company's own [About page](https://www.databasemart.com/about/) independently describes the founder as "Morris", a **Ph.D. in Computer Science**, who "began Database Mart from his home, volunteering server expertise to local churches and nonprofits before building a global hosting platform" |
| **NAME NOT PUBLIC** | **Head of Operations** (department exists per the company's own About page) | **Technical buyer / infrastructure owner** — the person who actually specifies chassis, racks the nodes and manages the Dallas and Kansas City colo footprints | **HIGH that the role exists; ZERO on identity — do not guess a name** | **admin@databasemart.com** is the ARIN-registered routing/tech/NOC/DNS/admin role address and is the most likely inbox to reach this function | **N/A — person not identified** | Company [About page](https://www.databasemart.com/about/) states "80+ professionals across six departments: Billing, Marketing, Sales, Support (24/7), Operations, and R&D". **No individual in Operations is named anywhere in public sources reached** — not on the website, not in ARIN (all POCs are role accounts), not in press releases, not on TheOrg, and not in any job posting |
| **NAME NOT PUBLIC** | **Head of R&D** (department exists per the About page) | **Technical influencer** — likely owns the GPU platform/software stack decisions: control panel, instant-deploy tooling, GPU VPS virtualization layer | **HIGH that the function exists; ZERO on identity** | **GAP** — no function-specific address published | **N/A — person not identified** | Same About-page department list. The company built its own control panel (2023 milestone) and operates a GPU VPS product line alongside bare metal, implying a real in-house engineering function |
| **NAME NOT PUBLIC** | **Head of Sales** (department exists per the About page) | **Commercial counterpart** — relevant only as a routing path, not as the buyer of hardware | **HIGH that the function exists; ZERO on identity** | **sales@databasemart.com** | **N/A — person not identified** | [Contact page](https://www.databasemart.com/contact-us) publishes sales@databasemart.com as the pre-sales route for "custom server configurations beyond standard offerings" — the correct inbound path for a hardware conversation |
| **ADMIN7533-ARIN** — *network registry row* | **ROLE ACCOUNT, NOT A NAMED PERSON.** Routing (R), Tech (T), NOC (N), Admin (AD) and DNS (D) POC for Database Mart LLC — **all five ARIN functions point at this single handle** | **Network registry contact (ARIN)** — labelled as such | **primary-record** | **admin@databasemart.com** · **+1-409-877-4238** (Office) | n/a | [whois.arin.net/rest/poc/ADMIN7533-ARIN.json](https://whois.arin.net/rest/poc/ADMIN7533-ARIN.json). Record fields: `isRoleAccount = Y`; `lastName = "Admin"`; `kind = group`; street 257 Westwood Dr., League City, TX 77573; registered **2020-07-31**; last updated **2025-11-03**; ARIN status **"Unverified" (PU)**. Registration comment: "https://www.databasemart.com/ Professional Database and Web Hosting" |
| **ABUSE8080-ARIN** — *network registry row* | **ROLE ACCOUNT, NOT A NAMED PERSON.** Abuse (AB) POC for Database Mart LLC | **Network registry contact (ARIN)** — labelled as such | **primary-record** | **abuse@databasemart.com** · +1-409-877-4238. **Listed for completeness; not a sales route, do not use** | n/a | [whois.arin.net/rest/poc/ABUSE8080-ARIN.json](https://whois.arin.net/rest/poc/ABUSE8080-ARIN.json). `isRoleAccount = Y`; `lastName = "Abuse"`; `kind = group`; same 257 Westwood Dr address; registered **2021-01-27**; last updated **2026-01-20**; ARIN status **"Unverified" (PU)** |
| **PeeringDB contacts** | — | **Network contacts (PeeringDB) — NONE EXIST (GAP)** | **primary-record** (that the record itself is absent) | n/a | n/a | [peeringdb.com/api/net?asn=401479](https://www.peeringdb.com/api/net?asn=401479) returns `{"data": [], "meta": {"error": "Entity not found"}}`. A name search for "Database" also returns an empty data array. **Database Mart has no PeeringDB presence whatsoever**, so there is no facility list, no IX presence, no traffic self-report and no peering contact from that source |
| **NOC3077-ARIN / TEXAS1-ARIN** | OrgAdmin/OrgTech (NOC3077) and Abuse (TEXAS1) for the **Dallas IP space that Database Mart's Dallas nodes sit inside** | **UPSTREAM PROVIDER CONTACTS — NOT DATABASE MART STAFF** | **primary-record** | noc@psychz.net · +1-626-549-2801. **Do not contact. Do not register** | n/a | [rdap.arin.net/registry/ip/108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28). Psychz Networks (Org handle **PS-184**, AS40676), 20687-2 Amar Rd #312, Walnut, CA 91789. The abuse handle **TEXAS1-ARIN** is registered to **"Profuse Solutions INC", "Texas - NOC", 1515 Round Table Drive, Dallas, TX 75247** — the same street address Database Mart publishes as its Dallas datacenter. Both are role/group accounts. Listed here because they establish, unambiguously, that **Database Mart is a TENANT in Dallas, not the network operator** |
| **Wholesale Internet, Inc. (AS32097)** | Sole observed BGP upstream for AS401479, and the origin AS that actually announces Database Mart's own 163.123.180.0/22 | **UPSTREAM TRANSIT PROVIDER — NOT DATABASE MART STAFF** | **primary-record** | Not pursued — this is the provider, not the target | n/a | [peeringdb.com/api/net?asn=32097](https://www.peeringdb.com/api/net?asn=32097): Kansas City MO, open peering policy, `ix_count` 10, `fac_count` 9, `info_traffic` "1-5Tbps". [RIPEstat asn-neighbours](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) for AS401479 returns exactly one neighbour: **AS32097** (type "left", power 371, v4_peers 3320) |

**Confidence statement on the only name in this file:** **MEDIUM-HIGH** that Morris Liu is the CEO/founder and the decision maker. **HIGH** that a founder named "Morris" with a Computer Science Ph.D. runs the company. **MEDIUM** on the surname spelling — it comes from a single aggregator ([TheOrg](https://theorg.com/org/database-mart-llc/org-chart/morris-liu)), not from a primary registry filing, and the company's own site uses the first name alone. **Confirm the surname verbally on first contact.** A LinkedIn company page exists at [linkedin.com/company/database-mart](https://www.linkedin.com/company/database-mart) and a personal-format profile at [linkedin.com/in/database-mart-788a35111/](https://www.linkedin.com/in/database-mart-788a35111/) — but that second profile is branded "Database Mart - Professional Databases- Hosting Specialists", i.e. a **company-operated profile, not Morris Liu's personal profile**. **No personal LinkedIn profile for Morris Liu was located — GAP.**

### 3.2 Registry record

Note the boundary: the ARIN rows above are **internet-number registry** records. The rows below are the **corporate registry** track — and they are almost entirely negative.

| Name | Capacity | Filing | Filing date | Source |
|---|---|---|---|---|
| **NO OFFICERS, MANAGERS OR MEMBERS DISCLOSED IN ANY RECORD REACHED** | n/a | **Texas Comptroller Franchise Tax / taxable-entity record**, SOS file number **0800439627**, taxpayer number **32107118534**. The Comptroller open-data record carries the entity name, address, charter date and status but contains **NO officer, director, manager, member, registered-agent or signatory fields**. The Comptroller "Franchise Tax Account Status" **detail** view, which *does* display registered agent and officers/directors, is a JavaScript single-page application: three separate attempts (GET with `taxpayerId` param, POST with `taxpayerId` form field, and the legacy `mycpa.cpa.state.tx.us/coa/` endpoint which 302-redirects to the new host) all returned the **empty search-form shell (130,041 bytes, no result rows)** rather than a record. The page itself states "API access to this data is available. Please refer to our Public API Documentation"; the [api-doc.comptroller.texas.gov](https://api-doc.comptroller.texas.gov/public-data/) documentation page returned **truncated content and no endpoint specification** | Charter **2005-01-13**; record retrieved **2026-08-11** | [data.texas.gov/resource/9cir-efmm.json](https://data.texas.gov/resource/9cir-efmm.json) · [comptroller.texas.gov account-status search](https://comptroller.texas.gov/taxes/franchise/account-status/search) · [api-doc.comptroller.texas.gov](https://api-doc.comptroller.texas.gov/public-data/) |
| **TEXAS SOSDIRECT — FILING HISTORY AND ANNUAL-REPORT SIGNATORIES NOT RETRIEVED** | n/a | Texas **SOSDirect** is the only route to the certificate of formation, the filing history, the registered agent of record and any annual/periodic-report signatories. The login page returned HTTP 200 with the literal text: *"DIRECT ACCESS SUBSCRIBER LOGIN … SOSDirect Account Login … reenter your SOSDirect USER ID and PASSWORD and click Submit to begin."* **It is a fee-based subscriber system requiring account creation and credentials. No account was created and no credentials were entered.** The main sos.state.tx.us site additionally displayed a standing banner: *"Technical Notice: Various applications including SOSDirect and SOSUpload are experiencing intermittent issues and are actively being addressed."* | Probed **2026-08-11** | [direct.sos.state.tx.us/acct/acct-login.asp](https://direct.sos.state.tx.us/acct/acct-login.asp) · [sos.state.tx.us/corp/sosda/index.shtml](https://www.sos.state.tx.us/corp/sosda/index.shtml) |
| **DELAWARE — NO RECORD SOUGHT SUCCESSFULLY; ENTITY IS TEXAS-DOMESTIC** | n/a | Delaware Division of Corporations eCorp entity name search returned **HTTP 200 on GET** (48,034-byte ASP.NET form containing field id `ctl00_ContentPlaceHolder1_frmEntityName`) and **HTTP 411 on POST**. The form is an ASP.NET postback requiring `__VIEWSTATE` plus a CAPTCHA and **could not be driven programmatically; CAPTCHAs are not solved**. Note Delaware is very likely a dead end regardless: the Texas Comptroller record codes the entity organizational type as **CL (Texas domestic LLC)**, not as a foreign entity registered in Texas, so **Database Mart LLC is organized under Texas law and Texas — not Delaware — is the state of organization for UCC-1 purposes** | Probed **2026-08-11** | [icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx](https://icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx) |
| **Cross-check: no sibling Texas entities under the Mart brands** | n/a | A wildcard query of the same Comptroller dataset for `%MART%` limited to LEAGUE CITY returned **DATABASE MART LLC as the only matching hosting entity**. Further queries for CLOUD CLUSTERS, VPS MART, SERVER MART, GPU MART and WINPC each returned **"(no records)"** — confirming the sibling brands are **trading names, not separate Texas entities** | Retrieved **2026-08-11** | [data.texas.gov/resource/9cir-efmm.json](https://data.texas.gov/resource/9cir-efmm.json) |

### 3.3 Buying committee

Database Mart is an **owner-operated LLC with no outside investors on record, no board, no CFO named anywhere, and a private residence as the registered HQ**. There is effectively **no procurement layer** — and, unusually, no committee at all. There is one person, and everyone else executes his decision.

| Name | Why they matter for a server purchase | How to approach |
|---|---|---|
| **Morris Liu** — CEO and Founder | **He is the entire decision.** In an owner-operated ~80-person LLC with no disclosed investors, no board and no CFO, capital equipment decisions of this size do not get delegated. He holds a **Ph.D. in Computer Science**, so he is his own technical evaluator as well as his own economic buyer. He has personally driven every product-line launch since 2005 per the company's own milestone timeline | **Do not lead with a corporate capability deck.** Lead with a single specific engineering observation about his own published fleet and let him correct you — a CS-PhD founder will engage with a technical peer and disengage from a vendor pitch. The observation to lead with is the platform mismatch (§13). Route: **sales@databasemart.com** is the published pre-sales inbox and the [contact page](https://www.databasemart.com/contact-us) explicitly invites "custom server configurations beyond standard offerings" through it — a legitimate, low-friction first touch. The ARIN-registered office line **+1-409-877-4238** is a second path and is **not published on the website**, so it will not be screened as a marketing inbound. Expect direct, price-literal, unsentimental negotiation; this is a company whose entire market position is being cheaper than everyone else |
| **Head of Operations** — **NAME NOT PUBLIC** | Whoever racks and specs the nodes across the Dallas (Psychz) and North Kansas City footprints owns the constraints that will kill or carry a Supermicro deal: **rack U budget, per-rack kW ceiling in leased cages, airflow, PSU/PDU compatibility**, and whether a 600W-class Blackwell card can be cooled in whatever chassis they use today. This person cannot sign, but **can veto on physical grounds** | Reach through **admin@databasemart.com**, the ARIN routing/tech/NOC/DNS/admin role address — it lands with the infrastructure function rather than with billing. **Ask about the colo power envelope before proposing any specific chassis:** in leased cages the kW-per-rack cap, not the capex, is usually the binding constraint. **Do not attempt to name this person** — no name exists in any public source, and guessing will destroy credibility with a founder who knows his own org |
| **Head of R&D** — **NAME NOT PUBLIC** | They ship a **GPU VPS product with 8 published tiers** alongside bare metal, plus their own control panel built in 2023. A virtualization/partitioning layer therefore sits on top of the GPUs, which makes GPU choice a **software-compatibility decision as well as a hardware one** — vGPU/MIG licensing, driver stack and passthrough behaviour all differ between the Blackwell workstation-class RTX PRO cards they are now buying and datacenter parts | **Secondary.** Only engage after the platform conversation is live, and use it to widen the deal from a chassis sale into a validated-platform sale. Relevant hook: the RTX PRO 6000 96GB is being sold as a **32-core / 84GB-RAM VPS slice at $479/mo**, which implies partitioning a single card across tenants — worth asking how they are doing that and on what platform |
| **NOT A BUYING-COMMITTEE MEMBER: Psychz Networks / Wholesale Internet, Inc.** | **Explicitly flagged as NON-members to prevent a mis-registration.** Psychz Networks (AS40676, Walnut CA) supplies the Dallas colo and IP space; Wholesale Internet Inc (AS32097, Kansas City) supplies transit and announces Database Mart's own /22. **Neither buys Database Mart's GPUs.** Confusing the colo provider with the account is the single most likely way to register this lead wrong | **Do not contact. Do not register.** Use only as corroboration that Database Mart leases space and owns hardware |

### 3.4 Unfilled roles — every one a GAP

**GAP — CFO / VP Finance / Controller:** no name, ever, in any source. · **GAP — Accounts Payable / billing owner:** only the department name "Billing" from the About page and the role mailbox route. · **GAP — Procurement / purchasing / vendor manager:** no such title in any roster, job board, LinkedIn result or filing. · **GAP — CTO / VP Engineering:** the About page confirms an R&D department exists, but no individual is named and no title is published. · **GAP — Head of Operations, Head of R&D, Head of Sales:** all three functions are confirmed to exist by the company's own department list; **not one individual is named in any source reached.** · **GAP — corporate officers, managers, members and registered agent of record:** Texas does not disclose LLC members or managers in the Comptroller open-data record, and the SOSDirect filing history that would name the organizer, registered agent and annual-report signatories sits behind a **paid subscriber login**, which was not breached. · **GAP — Texas entity filing history**, including the certificate of formation and any previously listed signatories. · **GAP — named technical staff of any kind:** no careers page was located and **no job posting for Database Mart was found on any board** (Indeed, ZipRecruiter, CareerBuilder, FlexJobs, Joblist all searched), so there are no hiring managers and no technical staff names beyond the CEO. No conference bios, podcast appearances, community-forum staff accounts or blog author bylines were identified either. · **GAP — personal LinkedIn profile for Morris Liu:** not located; the `/in/database-mart-788a35111/` profile is company-operated. · **GAP — UCC-1 secured parties and debtor signatories:** the Texas UCC index sits behind the same SOSDirect paid login (see §8). · **GAP — USPTO trademark declaration signatory and correspondent:** no trademark record was retrievable at all (four API routes failed — see §14). · **GAP — historical pre-privacy WHOIS registrant for databasemart.com:** whoisrequest.com returned HTTP 403; whoxy and securitytrails were not reached.

### 3.5 Sources worked — including what returned nothing

**Productive on people:** **[TheOrg](https://theorg.com/org/database-mart-llc/org-chart/morris-liu)** — the only source of a personal name anywhere in this file; returned exactly one person, "Morris Liu — CEO", no direct reports. · **The company's own [About page](https://www.databasemart.com/about/)** — independently confirms a founder named "Morris" with a Computer Science Ph.D., the 2005-01-13 founding, the six-department structure and the 80+ headcount. · **[ARIN Whois-RWS and RDAP](https://whois.arin.net/rest/org/DML-132/pocs.json)** — enumerated the complete ARIN estate and, critically, **recovered the +1-409-877-4238 office line that appears nowhere on the website**; but returned **zero individual names**, only role accounts. · **An ARIN org-name search** (`whois.arin.net/rest/orgs;name=Database%20Mart*`) returned exactly one org (DML-132), confirming no sibling ARIN registrations. · **The [Texas Comptroller Socrata dataset](https://data.texas.gov/resource/9cir-efmm.json)** — cracked the entity question (charter date, SOS file, taxpayer number, status) and, via wildcard queries, proved the sibling brands are trading names rather than separate entities.

**Reached but returned nothing on people:** **[PeeringDB](https://www.peeringdb.com/api/net?asn=401479)** (no record exists at all — `Entity not found`) · **[CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search/?q=%22Database+Mart%22)** searched across both RECAP dockets (`type=r`) and opinions (`type=o`) — **count 0 and document_count 0 on both**; federal coverage only, Texas state courts not searched · **job boards** (Indeed, ZipRecruiter, CareerBuilder, FlexJobs, Joblist — no careers page, no postings, no named staff) · **LinkedIn** (company page exists; no personal profile for Morris Liu located; no employee list obtained) · **live homepage grep of both domains for eight OEM vendor names** (zero hits on every term — see §5).

**Blocked or not reached, and why:** **Texas Comptroller Franchise Tax Account Status detail view** — a JS SPA that returned the same 130,041-byte empty search-form shell across three query methods. · **[api-doc.comptroller.texas.gov](https://api-doc.comptroller.texas.gov/public-data/)** — content returned truncated with no endpoint specification. · **[Texas SOSDirect](https://direct.sos.state.tx.us/acct/acct-login.asp)** — fee-based subscriber login; **no account was created and no credentials were entered**, which is the single hard stop behind both the officer gap and the UCC verdict. · **[Delaware eCorp](https://icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx)** — ASP.NET postback with CAPTCHA; HTTP 411 on POST; **CAPTCHAs are not solved**. Likely moot anyway (org type CL = Texas domestic). · **[FEC OpenFEC](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=Morris%20Liu)** — five queries, all HTTP 429 on the public DEMO_KEY (see §11). · **whoisrequest.com historical WHOIS** — HTTP 403.

**Best neutral next step to close the officer gap without touching the company:** run a **Texas SOSDirect filing-history pull** on file number **0800439627** through a subscriber account or a commercial registry vendor. That single document set would deliver the certificate of formation, the registered agent, and every annual/periodic-report signatory — which in turn unblocks the FEC individual searches that are currently impossible because there are no names to search (§11).

---

## 4. Footprint

| Site | Facility operator | Owned vs leased | Size / power (published only) | Evidence |
|---|---|---|---|---|
| **Dallas, Texas** — marketed by the company as **"South US"** — **1515 Round Table Dr, Dallas, TX 75247**. Company-published test IP **108.181.95.28** | **Psychz Networks** (ARIN Org **PS-184**, AS40676), 20687-2 Amar Rd #312, Walnut, CA 91789. The ARIN abuse POC for this space, **TEXAS1-ARIN**, is registered to **"Profuse Solutions INC", "Texas - NOC", 1515 Round Table Drive, Dallas, TX 75247** — the operating entity at the building itself. **Database Mart is a customer/tenant** | **LEASED — high confidence.** Database Mart does **not** hold the IP space here: 108.181.0.0/16 is registered to Psychz Networks, not to Database Mart LLC, and Database Mart's own ARIN org (DML-132) holds **no resources in this range**. A colocation tenant that owned the facility would hold its own address space and its own abuse contact | **Facility-level specifications as published by Database Mart. These describe the BUILDING, not Database Mart's footprint within it, and must not be quoted as Database Mart's capacity:** 2× 2MW Cummins generators; 3× 600kVA Liebert UPS in **2N+1**; 12× 30-ton Liebert air-cooled units totalling **360 tons in N+2**; locking cages, video surveillance, perimeter fence; 24/7 on-site technical staff. **Database Mart's own cage size, rack count and contracted kW: GAP — not disclosed anywhere** | [Company data-center page](https://www.databasemart.com/data-center) publishes the street address, the test IP and the facility spec. [ARIN RDAP on 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28) returns Psychz Networks as registrant with the 1515 Round Table Drive abuse contact. **Two independent sources agree on the building** |
| **North Kansas City, Missouri** — marketed as **"Central US"** — **1530 Swift St, North Kansas City, MO 64116**. Company-published test IP **163.123.183.33** | **Facility operator NOT independently confirmed by name in any public record reached — GAP.** What *is* confirmed: the IP space at this site (**163.123.180.0/22**, ARIN net handle NET-163-123-180-0-1, network name **"DBM-NET-01"**) is registered **directly to Database Mart LLC** (Org DML-132), and it is announced to the global routing table by **AS32097, Wholesale Internet, Inc.** of Kansas City MO — therefore the transit provider and probable facility partner | **LEASED space, OWNED addressing.** This is the more mature of the two sites: Database Mart holds its own ARIN allocation here (unlike Dallas) and named its own ASN **"DBM-ASN-KC"** after this location. But the building is a carrier-neutral multi-tenant facility described with third-party utility relationships, and Database Mart's routing depends entirely on Wholesale Internet's AS32097 — **a facility owner would not be single-homed behind another operator's ASN** | **Facility-level specifications as published by Database Mart (again: the building, not their footprint):** N+1 natural gas generators; **"Evergy Ttier 1 customer"** status *[transcribed verbatim including the typo]*; redundant A/B/C/D power configuration; N+1 HVAC with raised floor hot/cold aisle; "100% 4K UHD cameras" with 2-angle coverage. Network: connections to **AMS-IX, DE-CIX and SIX**; providers listed as **KCFiber, Zayo, AT&T and Hurricane Electric**. **Database Mart's own cage/rack/kW: GAP** | [Company data-center page](https://www.databasemart.com/data-center) for address, test IP and spec. [ARIN RDAP on 163.123.183.33](https://rdap.arin.net/registry/ip/163.123.183.33) returns Database Mart LLC as registrant of DBM-NET-01. [RIPEstat routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=163.123.180.0/22) for 163.123.180.0/22 returns a single origin, **AS32097**, seen by **326 of 326 RIS peers**, first seen **2021-01-30** and still announced 2026-08-11 — a stable five-and-a-half-year production footprint. A **July 2023** company news item titled "Network and Power Issue in Kansas Data Center" independently confirms live production capacity there ([portal.databasemart.com/news/](https://portal.databasemart.com/news/)) |
| **257 Westwood Dr, League City, TX 77573** — registered HQ | Database Mart LLC (residential premises) | **NOT A DATACENTER. Flagged here so it is never mistaken for one** | 5-bed / 3.5-bath, ~4,300 sq ft single-family home built **2014**, last sold **2018-01-25**. **No compute is plausibly hosted here at the scale their catalogue implies** | The address appears identically as the SOS/Comptroller registered address, the ARIN Org and both ARIN POC addresses, the domain WHOIS registrant street, and the published contact address — **while property records show a residence** ([HAR](https://www.har.com/homedetail/257-westwood-dr-league-city-tx-77573/8020666); [contact-us](https://www.databasemart.com/contact-us)). **Physical mail or drop-in visits would be inappropriate** |
| **THIRD SITE / EU PRESENCE — UNRESOLVED SIGNAL** | Unknown | Unknown | Unknown | **As of 2026-07-28**, AS401479 began announcing two RIPE-region prefix families: **93.127.128.0/20** (RIPE object name "Database_Mart_LLC", ASSIGNED PA, org **ORG-DML16-RIPE**, maintainer **netutils-mnt**) and **77.93.152.0/22** (RIPE object name **"IPXO"**, SUB-ALLOCATED PA, registrant "Private Customer"). The `netutils-mnt` maintainer and the "IPXO" object name indicate this is **LEASED address space obtained through the IPXO marketplace**, not a RIPE membership of their own; both objects carry country code **US**. That is **5,120 additional IPv4 addresses brought into production within the last two weeks**. It does **NOT** by itself prove a European facility — leased RIPE space is routinely announced from US locations — but combined with the dormant /18 it is a live expansion signal and should be **the second qualifying question after platform**. [RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) · [RIPE RDAP 93.127.128.0](https://rdap.db.ripe.net/ip/93.127.128.0) · [RIPE RDAP 77.93.152.0](https://rdap.db.ripe.net/ip/77.93.152.0) |

**Footprint read:** two production sites, both leased, one of which they do not even hold the addressing for. **No owned facility, no owned building, no self-operated hall.** That matters commercially in one specific way: **every hardware decision they make is constrained by somebody else's kW-per-rack cap and somebody else's airflow design** — which is precisely why the power-envelope question in §13 is the right one to ask before naming a chassis.

---

## 5. Hardware fleet

Evidence grades used here: **CONFIRMED** = first-hand named disclosure or multiple independent corroboration · **CIRCUMSTANTIAL** = behaviour points strongly but the vendor is never named · **INFERRED** = derived only from CPU socket, platform generation or chassis form factor · **GAP** = nothing found.

| Vendor / category | Evidence grade | What the evidence actually says |
|---|---|---|
| **NO SERVER OEM NAMED ANYWHERE IN PUBLIC SOURCES** | **GAP — and this is a direct negative test, not an absence of effort** | I grepped the live homepages of both [www.gpu-mart.com](https://www.gpu-mart.com/) and [www.databasemart.com](https://www.databasemart.com/), plus `/gpu-specs`, `/about/` and `/about-us`, for the strings **Supermicro, Dell, Gigabyte, ASUS, Tyan, Inspur, Lenovo and HPE**. **Every single count was zero.** A targeted web search pairing the two domains with those vendor names returned no result referencing either domain. Their marketing describes GPUs by NVIDIA model and hosts by Intel Xeon SKU, and **never names a system builder. No hardware vendor may be stated as fact for this account** |
| **Supermicro (or an equivalent X10/X11-generation dual-socket GPU chassis builder)** | **INFERRED — explicitly NOT confirmed, and must never be represented to the customer as known** | Inference chain, stated so it can be attacked: **(1)** Every dedicated SKU in their 26-SKU catalogue runs Xeon E5 v3/v4, Gold 6148 or Platinum 8160 — 2014-2017 silicon, verified by transcription of their own [pricing page](https://www.gpu-mart.com/gpu-dedicated-server). **(2)** The flagship is specifically **"Dual E5-2697v4"** with a single double-width 350W H100, and they also publish 4× A100 and 4× RTX A6000 nodes on 44-core dual-E5 hosts. **(3)** Dual-E5-2600-v3/v4 boards carrying three-to-four double-width GPUs in 4U were, in that generation, overwhelmingly **Supermicro X10DRG-class boards in 4028GR-series chassis** — that platform dominated the secondary market for exactly this build. **(4)** Therefore the probability that some of their legacy fleet is Supermicro-built is high. **BUT:** (a) no source says so; (b) the same builds exist from Gigabyte, Tyan, ASUS and generic whitebox integrators; (c) secondary-market buyers mix chassis opportunistically by price, so the fleet is **probably heterogeneous rather than single-vendor**. **Treat as a hypothesis to test in conversation, never as an assertion** |
| **Secondary-market / refurbished sourcing as the procurement channel** (as opposed to any named OEM) | **CIRCUMSTANTIAL — strong, multi-source, but still inference** | Four independent strands converge: **(1) Platform age** — every published host CPU is 2014-2017 silicon with **zero current-generation hosts anywhere in the catalogue**; a company buying new OEM systems would have at least some recent hosts. **(2) Price-to-hardware arithmetic** — see §9; a new-card, new-platform H100 node cannot pay back inside 24 months at their published $2,099/mo, so the economics only close on secondary-market cards and near-zero-cost legacy hosts. **(3) Discount depth concentrated on older generations** — P100 **55% off**, A100 40GB **50% off**, RTX A4000 and A5000 **50% off**, 2× RTX 4090 **50% off**, RTX A6000 **40% off** — inventory acquired cheaply and cleared aggressively. **(4) A Gen5 card on a Gen3 platform** is a tell-tale of buying the card and the host separately from different markets rather than buying a validated system. **Contradicting evidence, recorded for fairness:** they were **early to Blackwell** (RTX PRO 6000 live 2025-11-08, weeks after availability), which is hard to do purely on the used market and implies **at least some new-channel access for current-generation cards** |
| **NVIDIA** | **CONFIRMED as the silicon in the fleet; UNKNOWN as a commercial relationship** | Every GPU in the published catalogue is an NVIDIA part, Pascal P1000/P100 through Blackwell RTX PRO 6000 — confirmed by transcription of their own pricing pages. **What is NOT known:** whether they buy cards through an NVIDIA partner channel, through distribution, through system integrators, or on the open/secondary market. **No NVIDIA Partner Network status, no NVIDIA-branded partner badge and no reseller relationship is visible on their site — GAP** |
| **Psychz Networks (AS40676) and Wholesale Internet, Inc. (AS32097)** | **CONFIRMED as infrastructure suppliers — but these are colocation/transit vendors, NOT hardware vendors** | Listed here only to prevent a category error. [ARIN RDAP](https://rdap.arin.net/registry/ip/108.181.95.28) confirms Psychz owns the Dallas IP space at 1515 Round Table Drive. [RIPEstat](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) confirms AS32097 is the sole BGP neighbour of AS401479 and the origin AS for Database Mart's own /22 since 2021-01-30. **Neither supplies servers. Neither is the account** |

### 5.1 The single most important technical finding

Their flagship product page ([gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting), read 2026-08-11) publishes, verbatim, an **NVIDIA H100 80GB HBM2e PCIe** card on a **"36-Core Dual E5-2697v4"** host, with 256GB RAM, 240GB SSD + 2TB NVMe + 8TB SATA, **100Mbps unmetered**, 1 dedicated IPv4, at **$2,099.00/month on a 24-month commitment**, status **Available**.

Two things are wrong with that on its own evidence:

1. **PCIe generation mismatch.** The E5-2697v4 is a **Broadwell-EP part launched in 2016** whose platform (Intel C610 / X10-generation dual-socket) provides **PCIe 3.0 only**. They are hanging a PCIe Gen5 H100 off a Gen3 root complex — the card will negotiate down to **Gen3 x16, roughly a quarter of its designed host bandwidth**. The product page **simultaneously advertises "PCIe Gen5" in the card specification while listing a CPU that cannot deliver it.**
2. **Ingest bandwidth.** **100Mbps unmetered on a $2,099/mo AI node** is an extremely thin pipe for training or dataset staging.

Both are verifiable from their own published page, which makes them **safe, non-insulting openers** — you are quoting them to themselves, not accusing them of anything.

### 5.2 CPU generations observed, and what they imply about fleet age

Read directly off the publicly sold platform mix (**INFERRED** platform-family evidence from published configurations, not vendor disclosure):

- **Host CPUs across the entire 26-SKU dedicated range:** Intel Xeon **E5 v3/v4** (2014–2016 Haswell/Broadwell), Xeon **Gold 6148** (2017 Skylake-SP), Xeon **Platinum 8160** (2017 Skylake-SP). **That is the whole list.**
- **Zero current-generation host platforms** — no Ice Lake, no Sapphire Rapids, no Emerald Rapids, no Granite Rapids, no EPYC of any generation, anywhere in the published catalogue.
- **GPU generations spanned:** Pascal (Quadro P1000, Tesla P100), Turing (GTX 1650/1660, RTX 2060), Ampere (RTX 3060 Ti, RTX A4000/A5000/A6000, A40, A100 40/80GB), Ada (RTX 4060, RTX 4090), Hopper (H100 80GB), Blackwell (RTX 5060, RTX 5090, RTX PRO 2000/4000/5000/6000).
- **Chassis form factors inferred:** 4U-class multi-GPU chassis (4× A100 40GB, 4× RTX A6000, 3× V100, 3× RTX A5000, 2× RTX 5090) and single-GPU 2U/4U hosts.

**What this implies:** the fleet is **generationally split down the middle — modern cards on ancient hosts.** They refresh GPUs aggressively and **never** refresh the platform underneath. That is the signature of an operator whose BOM is 90–95% GPU and whose host is effectively free (§9), and it means the realistic Supermicro entry point is **a current-generation PCIe Gen5 GPU platform for the Blackwell tier specifically** — not a fleet-wide replacement, which cannot be justified on their numbers.

---

## 6. GPU catalogue & AI position

**Confirmed, extensive and actively merchandised.** Database Mart sells GPU hosting as a distinct brand, gpu-mart.com, with three product families: **dedicated GPU servers (26 published SKUs)**, **GPU VPS (8 tiers)**, and **model-specific landing pages** for the flagship parts. All SKUs below were transcribed from the live catalogue on **2026-08-11**.

### 6.1 Dedicated GPU servers — all 26 SKUs, every price

| SKU (GPU · host platform) | Monthly price | Status | Source |
|---|---|---|---|
| **NVIDIA H100 80GB HBM2e PCIe** — 36-Core Dual E5-2697v4, 256GB RAM, 240GB SSD + 2TB NVMe + 8TB SATA, 100Mbps unmetered, 1 dedicated IPv4 · **24-month commitment** | **$2,099.00** | Available | [/h100-hosting](https://www.gpu-mart.com/h100-hosting) |
| **4× NVIDIA A100 40GB** — 44-Core Dual E5, 512GB RAM | **$1,899.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA A100 80GB HBM2e** — 36-Core Dual E5, 256GB RAM | **$1,559.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **4× NVIDIA RTX A6000 48GB** — 44-Core Dual E5, 512GB RAM | **$1,199.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **3× NVIDIA RTX A6000 48GB** — 36-Core Dual E5, 256GB RAM | **$899.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **2× NVIDIA RTX 5090 32GB GDDR7** — 44-Core Dual E5, 256GB RAM | **$859.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **3× NVIDIA RTX A5000 24GB** — 36-Core Dual E5, 256GB RAM | **$539.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 5090 32GB GDDR7** — 36-Core Dual E5, 256GB RAM | **$479.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **3× NVIDIA V100 16GB HBM2** — 36-Core Dual E5, 256GB RAM | **$469.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **2× NVIDIA RTX 4090 24GB GDDR6X** — 36-Core Dual E5, 256GB RAM · **50% OFF** (implied list $899.00) | **$449.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA A40 48GB GDDR6** — 36-Core Dual E5, 256GB RAM | **$439.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 4090 24GB GDDR6X** — 36-Core Dual E5, 256GB RAM | **$409.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA A100 40GB HBM2** — 36-Core Dual E5, 256GB RAM · **50% OFF** (implied list $799.00) | **$399.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX A6000 48GB GDDR6** — 36-Core Dual E5, 256GB RAM · **40% OFF** (implied list $549.00) | **$329.40** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA V100 16GB HBM2** — 24-Core Dual E5, 128GB RAM | **$229.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 3060 Ti 8GB GDDR6** — 24-Core Dual E5, 128GB RAM | **$179.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 2060 6GB GDDR6** — 40-Core Dual Gold, 128GB RAM | **$179.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX A5000 24GB GDDR6** — 24-Core Dual E5, 128GB RAM · **50% OFF** (implied list $349.00) | **$174.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 2060 6GB GDDR6** (Professional tier) — 16-Core Dual E5, 128GB RAM · **20% OFF** | **$159.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX 5060 8GB GDDR7** — 24-Core Platinum 8160, 64GB RAM | **$159.00** | Available | [/nvidia-blackwell-gpu-server](https://www.gpu-mart.com/nvidia-blackwell-gpu-server) |
| **NVIDIA RTX 4060 8GB GDDR6** — 8-Core Xeon, 64GB RAM | **$149.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA RTX A4000 16GB GDDR6** — 24-Core Dual E5, 128GB RAM · **50% OFF** (implied list $279.00) | **$139.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA GTX 1660 6GB GDDR5** — 16-Core Dual E5, 64GB RAM | **$139.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA GTX 1650 4GB GDDR5** — 8-Core Xeon, 64GB RAM | **$99.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA Tesla P100 16GB HBM2** — 16-Core Dual E5, 128GB RAM · **55% OFF** (implied list $199.00) — **the deepest discount in the catalogue** | **$89.50** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |
| **NVIDIA Quadro P1000 4GB GDDR5** — 8-Core Xeon, 32GB RAM — **cheapest dedicated GPU node** | **$64.00** | Available | [/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server) |

### 6.2 GPU VPS tiers — all 8, every price

| Tier | Monthly price | Source |
|---|---|---|
| **NVIDIA RTX PRO 6000 96GB GDDR7 (ECC)** — Enterprise GPU VPS, 32 cores, 84GB RAM, 400GB SSD, 1000Mbps unmetered | **$479.00** | [/rtx-pro-6000-hosting](https://www.gpu-mart.com/rtx-pro-6000-hosting) · [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX 5090 32GB GDDR7** — Advanced GPU VPS, 32 cores, 84GB RAM, 400GB SSD · **35% OFF** | **$291.85** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX PRO 5000 48GB GDDR7 (ECC)** — Advanced GPU VPS, 24 cores, 56GB RAM, 320GB SSD | **$269.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX PRO 4000 24GB GDDR7 (ECC)** — Advanced GPU VPS, 24 cores, 56GB RAM, 320GB SSD | **$159.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX A4000 16GB** — Professional GPU VPS, 24 cores, 28GB RAM, 320GB SSD | **$119.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX PRO 2000 16GB GDDR7** — Professional GPU VPS, 16 cores, 28GB RAM, 240GB SSD | **$99.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA RTX 5060 8GB GDDR7** — Basic GPU VPS, 16 cores, 28GB RAM, 240GB SSD | **$85.00** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |
| **NVIDIA GT730 / P600 / K620 2GB DDR3** — Express GPU VPS, 8 cores, 16GB RAM, 120GB SSD · **50% OFF** (implied list $29.00) — **cheapest GPU product they sell** | **$14.50** | [/gpu-vps](https://www.gpu-mart.com/gpu-vps) |

### 6.3 AI position — read

**This is the active buying front.** Six Blackwell SKUs went from nonexistent to fully catalogued between **November 2025 and April 2026**. The RTX PRO 6000 in particular is a **600W-class, PCIe Gen5, 96GB GDDR7** card — the single hardest part in their catalogue to run correctly on a 2016-vintage dual-E5 platform, on **both** power delivery and host bandwidth.

**Watch the price trajectory on that card.** The dedicated RTX PRO 6000 page was live at **$729.00/month on 2025-11-08** ([Wayback capture](https://web.archive.org/web/20251108102809/https://www.gpu-mart.com/rtx-pro-6000-hosting)); by 2026-08-11 the **96GB VPS tier is $479.00/month** — a ~34% reduction in about nine months. **Margin is compressing while they are still buying.** That changes what matters to them: efficiency per rack-U and per kW starts to dominate chassis capex.

**Discount depth as a fleet-age indicator.** The heavily discounted SKUs are precisely the Pascal/Turing/Ampere generations — P100 55% off, A100 40GB 50% off, RTX A4000 and A5000 50% off, 2× RTX 4090 50% off, RTX A6000 40% off. A 50% standing discount on an A100 40GB node is a strong signal that **this generation is depreciating fast in their book** and that older inventory is being cleared.

**Coverage gaps in their own line-up, worth knowing before the call:** they sell **no H200**, **no L40S**, **no datacenter-class Blackwell (B200/GB200)**, and **no AMD Instinct**. The two obvious remaining holes are a datacenter-class Blackwell part and an H200 — either of which would be a new platform purchase, not a card swap.

---

## 7. Purchase clock

How often Database Mart actually buys, reconstructed from its own published catalogue, its own dated press releases, and registry/BGP timestamps.

### 7.1 Dated event timeline

| Date | Event | Type | Source |
|---|---|---|---|
| **2004-11-16** | **databasemart.com registered** (RDAP creation date) — two months before the Texas charter | Origin | [Verisign RDAP](https://rdap.verisign.com/com/v1/domain/databasemart.com) |
| **2005-01-13** | **Texas SOS charter** — DATABASE MART LLC, file 0800439627 | Origin | [Texas Comptroller](https://data.texas.gov/resource/9cir-efmm.json) |
| **2020-06** | Company press release **"Database Mart LLC Launches Dedicated GPU Server Hosting"** — **first GPU capacity** | **Purchase event** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| **2020-07-31** | ARIN POC **ADMIN7533-ARIN** registered | Capacity | [ARIN](https://whois.arin.net/rest/poc/ADMIN7533-ARIN.json) |
| **2020-08-03** | ARIN registers **163.123.180.0/22** (1,024 addresses, DBM-NET-01) to Database Mart LLC | **Capacity event** | [ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json) |
| **2021-01-30** | **163.123.180.0/22 first announced** to the global routing table by AS32097 — Kansas City production goes live | Capacity | [RIPEstat routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=163.123.180.0/22) |
| **2021-11-15** | **gpu-mart.com registered** (RDAP creation date) — the GPU brand is spun out | Brand | [Verisign RDAP](https://rdap.verisign.com/com/v1/domain/gpu-mart.com) |
| **2023-01** | Press release **"Expands GPU Hosting Offerings"** — "4 new dedicated GPU server offerings and 1 GPU VPS offering" (GTX 1650, GTX 1660, RTX 2060, RTX 3060 Ti) | **Purchase event** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| **2023-02-08** | First Wayback capture of **/rtx-a6000-hosting** | **Purchase event** (dating anchor) | [web.archive.org](https://web.archive.org/web/20230208000000*/gpu-mart.com/rtx-a6000-hosting) |
| **2023-06-04** | Catalogue snapshot shows **12 GPU models**: A100, A40, V100, P1000, A6000, A5000, A4000, 4090, 3060, 2060, 1660, 1650 | Baseline | [web.archive.org 2023-06-04](https://web.archive.org/web/20230604000000*/gpu-mart.com/gpu-dedicated-server) |
| **2023-07** | Company news item **"Network and Power Issue in Kansas Data Center"** — independently confirms live KC production | Operational | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| **2023-11-13** | **RTX 4060** first present in a catalogue snapshot (absent 2023-06-04) | **Purchase event** | Wayback catalogue snapshot |
| **2024-03-05** | First Wayback capture of **/nvidia-a100-rental** | Dating anchor | [web.archive.org](https://web.archive.org/web/20240305000000*/gpu-mart.com/nvidia-a100-rental) |
| **2024-05-22** | **Tesla P100** first present in a catalogue snapshot (absent 2023-12-07) | **Purchase event** | Wayback catalogue snapshot |
| **2024-11-07** | ARIN registers **AS401479 "DBM-ASN-KC"** to Database Mart LLC | **Capacity event** | [ARIN asns](https://whois.arin.net/rest/org/DML-132/asns.json) |
| **2024-12-22** | First Wayback capture of **/rtx-5090-hosting** — page stood up at or just before the RTX 5090 launch window | **Purchase event** | [web.archive.org](https://web.archive.org/web/20241222000000*/gpu-mart.com/rtx-5090-hosting) |
| **2025-02-13** | First Wayback capture of **/h100-hosting** | **Purchase event** | [web.archive.org](https://web.archive.org/web/20250213000000*/gpu-mart.com/h100-hosting) |
| **2025-06-16** | Catalogue snapshot now carries **H100, RTX 5090 and RTX 5060** (none present 2024-05-22) | Confirmation | Wayback catalogue snapshot |
| **2025-11-08** | **/rtx-pro-6000-hosting live at $729.00** with an "Order Now" control — **Blackwell workstation-class enters the fleet** | **PURCHASE EVENT — start of the current burst** | [Wayback 2025-11-08](https://web.archive.org/web/20251108102809/https://www.gpu-mart.com/rtx-pro-6000-hosting) |
| **2026-01-12** | **/rtx-pro-4000-blackwell** and **/rtx-pro-5000-blackwell** first captured | **DOUBLE PURCHASE EVENT** | Wayback CDX |
| **2026-01-16** | **/rtx-pro-2000-blackwell** first captured | **PURCHASE EVENT** | Wayback CDX |
| **2026-01-21** | **ARIN registers 38.247.128.0/18 — 16,384 addresses — to Database Mart LLC** (ALLOCATION under Cogent's 38.0.0.0/8, net name DATABASEMART-CGNT-NET-1) | **MAJOR CAPACITY COMMITMENT — and it is still unrouted** | [ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json) · [RIPEstat routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=38.247.128.0/18) shows **0 of 326 RIS peers**, no origins, no first-seen |
| **2026-04-19** | **/nvidia-blackwell-gpu-server hub page first captured**; catalogue snapshot shows RTX PRO 6000 alongside H100 | **LAST CONFIRMED HARDWARE/CATALOGUE EVENT** | Wayback CDX |
| **2026-07-28** | AS401479 begins announcing leased RIPE prefixes **93.127.128.0/20** and **77.93.152.0/22** — **5,120 addresses brought live** | **CAPACITY EVENT — two weeks before this dossier** | [RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) |

### 7.2 Cadence

**Two distinct rhythms, and they are materially different.**

**(1) Steady state — incremental SKU additions every roughly 4–6 months across 2023–2025:**

| From → to | Interval |
|---|---|
| RTX 4060 (2023-11) → P100 (by 2024-05) | ~6 months |
| P100 (2024-05) → RTX 5090 page (2024-12) | ~7 months |
| RTX 5090 page (2024-12) → H100 page (2025-02) | ~2 months |
| H100 page (2025-02) → RTX 5060 + H100 in catalogue (by 2025-06) | ~4 months |

**(2) Generation-refresh burst — materially faster:**

| From → to | Interval |
|---|---|
| RTX PRO 6000 (2025-11-08) → RTX PRO 4000 + 5000 (2026-01-12) | **2.2 months** |
| RTX PRO 4000/5000 (2026-01-12) → RTX PRO 2000 (2026-01-16) | **0.1 months** |
| RTX PRO 2000 (2026-01-16) → Blackwell hub page (2026-04-19) | **3.1 months** |

**Four Blackwell SKUs inside about five months — a ~2–3 month cadence during a generation transition, versus ~5 months in steady state. The Blackwell transition is roughly doubling their buying tempo, and it is still running.**

### 7.3 Last event and next window

**Last confirmed hardware/catalogue event: 2026-04-19** — the first Wayback capture of the `/nvidia-blackwell-gpu-server` hub page consolidating the RTX PRO 2000/4000/5000/6000 and RTX 5090/5060 line-up.

**Last confirmed capacity event of any kind: 2026-07-28** — AS401479 began announcing 5,120 leased IPv4 addresses.

**Outstanding and unconsumed:** the **16,384-address /18 registered 2026-01-21 that is still not announced** to the global routing table (0 of 326 RIS peers).

> ### Next window estimate: **SEPTEMBER–DECEMBER 2026, highest probability OCTOBER–NOVEMBER 2026**

**Reasoning.** The last catalogue event was April 2026 and the observed steady-state gap is 4–6 months, which alone points to August–October. Three factors push the estimate later and make it **firmer rather than earlier**:

1. **The 2026-07-28 IP activation means network capacity was just provisioned**, and address provisioning in this shop has consistently run slightly ahead of node deployment.
2. **16,384 owned but unrouted addresses represent a paid-for capacity commitment that has to be filled to earn its keep.**
3. **The Blackwell transition is mid-flight** and the two obvious remaining gaps in their line-up are a datacenter-class Blackwell part and an H200, neither of which they currently sell.

**A first-contact attempt in late August / early September 2026 lands ahead of that window rather than inside it, which is where you want to be.**

### 7.4 Method — stated plainly, with its limits

**Primary technique:** Wayback Machine **CDX enumeration** of gpu-mart.com URLs filtered for GPU model strings (`h100`, `5090`, `6000`, `a100`, `blackwell`, `l40`), taking the **earliest captured timestamp** of each model-specific landing page as the dating anchor. Supplemented by fetching **18 raw (`id_`) snapshots** of `/gpu-dedicated-server` across 2023-06 to 2026-04 and regex-matching **26 GPU model patterns** against the de-tagged text to establish presence/absence per date. Cross-checked against the company's own dated press releases at [portal.databasemart.com/news/](https://portal.databasemart.com/news/) and against ARIN/RIPE registration and BGP-announcement timestamps for capacity events.

**Three limitations that matter:**

1. **A Wayback first-capture date is a LATEST-POSSIBLE bound, not the true launch date.** Crawl coverage is sparse and irregular, so the real page-publication date is on or before the timestamp shown, sometimes by weeks.
2. **Page publication is itself a LAGGING proxy for the purchase decision.** Hardware is ordered, delivered, racked and burned in before the product page goes live, so the actual purchase order typically **precedes the dating anchor by roughly one to three months**. Both biases run the same direction, which means **true purchase dates are EARLIER than the dates above and the derived cadence is if anything slightly conservative.**
3. **Seven of the eighteen catalogue snapshots returned zero model matches** (2024-01-18, 2024-09-15, 2024-11-27, 2024-12-22, 2025-11-26, 2026-01-11, 2026-02-08) because the archived response was a JS shell or a compressed/garbled capture. **Those dates are absent evidence, not evidence of absence**; the model-specific landing-page anchors were used to bridge those gaps, but the cadence carries that uncertainty.

**Confidence:** **Medium-high** on the 2025-11 → 2026-04 Blackwell burst (four independent landing-page anchors, tight spacing, corroborated by a live catalogue that contains all six SKUs). **Medium** on the 2023–2025 steady-state cadence (thinner archive coverage, several bridged gaps). **Medium** on the forward window, which rests on a pattern of address-provisioning-then-deployment that has held twice but is not a law.

---

## 8. UCC financing record

**Scope of this track:** DATABASE MART LLC — Texas domestic LLC, SOS file **0800439627**, taxpayer number **32107118534**, registered address 257 Westwood Dr, League City, TX 77573. **State of organization for UCC-1 purposes is TEXAS** (Comptroller organizational type code **CL** = Texas domestic LLC), so **Texas SOS is the correct and only central filing office to search — Delaware is not applicable.** No sibling debtor entity exists: registry wildcard searches for CLOUD CLUSTERS, VPS MART, SERVER MART, GPU MART and WINPC each returned "(no records)".

### 8.1 Verdict

> ### UNVERIFIED — portal blocked

**Read that exactly as written.** **Zero UCC filings were retrieved, and no debtor-name query was ever actually submitted to any Texas UCC system** — every attempt failed at the authentication or routing layer before a search field was reachable. The empty filing set in §8.2 means *nothing was seen*. It does **not** mean Database Mart has no secured debt. **It must never be reported to a customer, quoted to credit, or entered into CRM as "no liens found."** The gating here is procedural, not evidence of a clean balance sheet.

### 8.2 Filings on record — every filing, in full

**Filings retrieved: 0.**

There is no filing block below because **no filing was ever returned by any surface**. Nothing is being compressed, abbreviated or summarised away — the register was never reached. Every per-filing field required for a credit or channel decision is therefore an explicit GAP:

| Per-filing field required | `DATABASE MART LLC` |
|---|---|
| Filing number | **GAP — register never reached** |
| Filing date | **GAP — register never reached** |
| Lapse date / continuation status | **GAP — register never reached** |
| Secured party name + address | **GAP — register never reached** |
| Debtor name + address as filed | **GAP — register never reached** |
| Collateral description (verbatim) | **GAP — register never reached** |
| Amendments / assignments / terminations | **GAP — register never reached** |
| Record link | **GAP — register never reached** |

**These fields are populated only by a Texas SOS UCC-11 debtor search**, run through a SOSDirect subscriber account or a commercial lien-search vendor. Search the exact string **`DATABASE MART LLC`** and, as a second pass, unanchored **`DATABASE MART`** to catch variant registrations.

### 8.3 Search log — four queries, one row per attempt, none merged

| Portal / URL | Search string used | Literal response | Alternative route if blocked |
|---|---|---|---|
| **[Q1] Texas SOS — UCC section landing page** · [sos.state.tx.us/ucc/index.shtml](https://www.sos.state.tx.us/ucc/index.shtml) | None (reconnaissance — locate the search interface) | **HTTP 200.** Page text returned: *"…for under the Uniform Commercial Code and certain other lien notice statutes. All accepted documents are processed, recorded, filed, and made available to the public upon request through SOS Portal."* Also carried a standing banner: *"Technical Notice: Various applications including SOSDirect and SOSUpload are experiencing intermittent issues and are actively being addressed."* **No search interface is exposed on this page.** | Follow the page's own pointer to "SOS Portal" (attempted in Q4) or to SOSDirect (Q3). |
| **[Q2] Texas SOS — direct UCC debtor-search endpoint probe** · [direct.sos.state.tx.us/ucc/ucc-search.asp](https://direct.sos.state.tx.us/ucc/ucc-search.asp) | Direct attempt at a UCC debtor-name search endpoint | **HTTP 404**, final URL unchanged. Body: *"404 - File or directory not found. Server Error 404 - File or directory not found. The resource you are looking for might have been removed, had its name changed, or is temporarily unavailable."* | No anonymous UCC search route exists at this path. Proceed to the authenticated gate (Q3). |
| **[Q3] Texas SOSDirect — the gate in front of the UCC index** · [direct.sos.state.tx.us/acct/acct-login.asp](https://direct.sos.state.tx.us/acct/acct-login.asp) | None (this is the login gate; the intended debtor string `DATABASE MART LLC` was never submitted) | **HTTP 200.** Body text: *"DIRECT ACCESS SUBSCRIBER LOGIN — TEXAS SECRETARY of STATE — ROBERT S. HOWDEN — UCC | Business Organizations | Trademarks | Notary — Account | Help/Fees | Briefcase | Login — SOSDirect Account Login … reenter your SOSDirect USER ID and PASSWORD and click Submit to begin."* **This is a fee-based subscriber system requiring account creation and credentials. No account was created and no credentials were entered — creating accounts and entering credentials are actions that will not be taken on the user's behalf.** | **A SOSDirect subscriber account operated by the sales officer or by credit**, or a commercial lien-search vendor. This is the only route to the Texas UCC index. |
| **[Q4] Texas "SOS Portal" successor hostnames** · [sosportal.sos.texas.gov](https://sosportal.sos.texas.gov/) and [businessfilings.sos.texas.gov](https://businessfilings.sos.texas.gov/) | Attempting the "SOS Portal" referenced in Q1's own text as the new public access route | **curl exit with HTTP 000 (no connection to a Texas SOS server).** The body returned by the sandbox network path was an unrelated third-party 404 page (*"Not Found | Hydra Host For AI Platforms … © 2026 Hydra Host, Inc."*), i.e. **these hostnames did not resolve to a Texas SOS endpoint from this environment at all.** Additionally [sos.state.tx.us/ucc/forms/index.shtml](https://www.sos.state.tx.us/ucc/forms/index.shtml) returned **HTTP 403** with body *"Sorry, but the requested file was not found"*. | Retry from a normal network path in a human browser; otherwise fall back to SOSDirect (Q3) or a commercial vendor. |

**NET RESULT: the Texas UCC index is reachable only behind SOSDirect's paid subscriber login, which was not breached.** To close this, run a Texas SOS **UCC-11 debtor search** on the exact string `DATABASE MART LLC` and, as a second pass, on unanchored `DATABASE MART`.

### 8.4 What the blocked result does and does not license

**It licenses nothing about their financing.** I cannot say they are unlevered, and I cannot say they are levered. But the surrounding evidence supports a reasonably strong **independent hypothesis that should be TESTED by the UCC search rather than replaced by it**: this looks like a **cash-and-cashflow-funded operation, not an equipment-financed one.**

| Observation | What it implies | Confidence | Sales consequence |
|---|---|---|---|
| **21 years of continuous operation with no outside funding round on record** — [Crunchbase](https://www.crunchbase.com/organization/database-mart) carries no funding data at all | Self-funded growth; no investor governance layer; no lender-imposed covenants visible | **medium** — absence of a Crunchbase record is weak evidence, but consistent with everything else | If confirmed, **no lender consent and no intercreditor friction** — direct terms become straightforward |
| **Owner-operated LLC with the founder's home as the registered address** — the classic profile of a business that reinvests rather than borrows | Reinforces the self-funded reading | **medium** — inference from structure, not from a filing | The buyer is spending his own money, which is exactly why the cost-ceiling arithmetic in §9 is binding rather than advisory |
| **Fleet composition** — dominated by 2014-2017 host platforms and heavily discounted prior-generation GPUs. **Buying used and holding equipment past its financeable life is what companies do when they are paying cash**, since lenders generally will not write paper against secondary-market hardware of that age | Points away from equipment finance on the legacy fleet specifically | **medium-high** — the platform-age evidence is directly transcribed from their own catalogue | Do not build a lease/vendor-finance pitch around the legacy tier; it will not land |
| **The cost-ceiling arithmetic (§9)** shows their published rents **cannot service new-equipment finance on new hardware** | Either they buy cheap and pay cash, or they underwrite over a much longer horizon than 24 months | **medium-high** — arithmetic from their own published price | Price and configuration are the levers, not financing structure — **unless** the search reveals a recent lender |
| **AGAINST the hypothesis, and the reason the search still matters:** the **Blackwell burst of Nov 2025 – Apr 2026** plus a **16,384-address /18 bought in Jan 2026** represents real capital going out the door fast — and an **RTX PRO 6000 96GB fleet is exactly the kind of current-generation, high-residual-value asset a lender WILL finance** | If a UCC-1 exists, it will most likely be **recent (2025-2026)** | **medium** — commercial reasoning, not a sighted filing | **The secured party's identity would be highly informative.** A bank or equipment-finance lessor means they have **credit capacity and a procurement process that can absorb a larger platform order**. A GPU broker or integrator taking a **purchase-money security interest in specific cards** means they are **vendor-financed and effectively channel-captive**, which changes the whole approach |

**Do not present any of this as fact to the customer.**

---

## 9. Cost ceiling

What each node can be worth to Database Mart, and what the same box costs to build today.

### 9.1 Assumptions — read these first; they are assumptions, not findings

**EVERY NUMBER IN THIS SECTION IS DERIVED FROM ONE PUBLISHED PRICE PLUS STATED ASSUMPTIONS, AND MUST BE LABELLED AS SUCH IN ANY CUSTOMER-FACING USE.**

- **ANCHOR (researched, not assumed):** the flagship H100 80GB node lists at **$2,099.00/month on a 24-month commitment** ([gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting), read 2026-08-11).
- **ASSUMPTION 1 — realized revenue is 75–85% of list**, reflecting the promotional discounting visible across their own catalogue (standing discounts of 20–55% on eight SKUs) and imperfect occupancy → **$1,574–$1,784/month realized**. *Inferred from the depth and breadth of their own published discounts; NOT sourced from the company.*
- **ASSUMPTION 2 — operating-cost share is 35–50% of realized revenue**, covering leased colo space and power, IP transit, IPv4, OS/panel licensing, 24/7 support labour, payment processing and churn → leaves **$787–$1,160/month of contribution** available to service the hardware. *A general hosting-industry working assumption; NOT sourced from the company and NOT researched. Their actual colo, power and transit costs are unknown — GAP.*
- **ASSUMPTION 3 — payback windows of 12 / 18 / 24 months**, as specified in the brief. *Their actual hurdle rate, depreciation schedule and hold period are unknown — GAP. Note that the 24-month commitment term on the H100 SKU and the presence of 2016-vintage hosts still earning revenue both suggest they underwrite over a **LONGER** horizon than 24 months, which would **raise** the ceiling.*
- **CONFIRMED, not assumed:** one GPU per node for the flagship — read off the published spec.
- **DELIBERATELY GENEROUS:** 100% of contribution is applied to hardware payback with **no allowance for overhead, tax or profit**. This makes the ceiling an **UPPER bound**; a realistic ceiling is lower.
- **EXCLUDED:** the model ignores multi-GPU nodes, where fixed host cost amortizes across 3–4 cards and the per-card economics improve materially. **Their 4× A100 at $1,899/mo and 4× RTX A6000 at $1,199/mo are the SKUs where a better chassis pays for itself fastest** — a useful argument to carry into the conversation.

### 9.2 Rent-derived hardware budget ceiling — flagship H100 node

| Payback window | Hardware budget ceiling per node |
|---|---|
| **12 months** | **$9,400 – $13,900** |
| **18 months** | **$14,200 – $20,900** |
| **24 months** | **$18,900 – $27,800** |

**RANGE DISCIPLINE:** treat **$19K–$28K per node at 24-month payback as the outer envelope** for total node hardware spend, and assume **the GPU consumes 90–95% of it**.

### 9.3 The commercially decisive point

**A single new H100 PCIe card alone costs $25,000–$30,970 at 2026 US street** (see BOM below), before any host, RAM, storage, chassis or rails.

**A new-card, new-platform H100 node therefore CANNOT pay back inside 24 months at their own published rent, and cannot come close at 12 or 18 months.** The same test applied to the RTX PRO 6000 96GB at $479/month VPS pricing is tighter still.

**CONCLUSION (inference, flagged as such): their unit economics only close on secondary-market or steeply discounted GPUs mounted on near-zero-cost legacy hosts — which is precisely what their published Dual E5-2697v4 specification shows them doing. This is the constraint any Supermicro proposal has to survive.**

### 9.4 BOM rebuild of the flagship

**"Enterprise Dedicated GPU Server, H100" as published:** 1× H100 80GB HBM2e PCIe + Dual Xeon E5-2697v4 (36 cores total) + 256GB RAM + 240GB SSD + 2TB NVMe + 8TB SATA.

| # | Line item | Detail | Price | Status |
|---|---|---|---|---|
| **1** | **H100 80GB PCIe** | **SOURCED.** $25,000–$30,970 new US street as of **March 2026**, with some vendors quoting $30,000–$38,000 in tight supply. Refurbished **$21,000–$34,000**; used non-refurbished **$15,000–$28,000** | **$25,000 – $30,970 (new)** | **SOURCED** |
| **2** | Dual E5-2697v4 CPU pair | Broadwell-EP, launched 2016, long EOL, **secondary market only** | **NOT INDEPENDENTLY PRICED** | **GAP** |
| **3** | 256GB DDR4 ECC RDIMM | Secondary market | **NOT INDEPENDENTLY PRICED** | **GAP** |
| **4** | 4U dual-E5 GPU chassis with PSU and rails | X10DRG-class, secondary market | **NOT INDEPENDENTLY PRICED** | **GAP** |
| **5** | 240GB SSD + 2TB NVMe + 8TB SATA + NIC | Secondary market | **NOT INDEPENDENTLY PRICED** | **GAP** |

**STRUCTURAL CONCLUSION THAT SURVIVES THE GAPS:** items 2–5 are all **long-EOL secondary-market parts whose combined cost is immaterial next to item 1**. **The GPU is approximately 90–95% of node BOM, and the host platform is effectively free.**

**SUPERMICRO COMPARISON.** An equivalent **NEW** Supermicro system — a current-generation 4U/5U PCIe GPU platform in the **SYS-421GE / AS-4125GS** family with a current dual Xeon or EPYC, 256GB and one H100 PCIe — would carry the **identical GPU cost** but replace a near-free legacy host with a current-generation, PCIe Gen5, properly-cooled platform.

**I am NOT quoting a Supermicro list price here.** No Supermicro configurator or distributor quote was pulled this session, and inventing one would be worse than leaving it blank. **GAP — pull a live configured quote before any customer conversation.**

### 9.5 The honest read

**On a like-for-like replacement of their existing H100 node, Supermicro loses on price and cannot win a pure capex comparison, because the incumbent host cost is a few hundred dollars.**

**The comparison only becomes winnable on the Blackwell nodes, where the legacy platform physically cannot deliver PCIe Gen5 or a 600W-class thermal and power envelope.** See §13.

### 9.6 Supermicro platform crosswalk by tier

| Their tier | What they are running (inferred) | Modern Supermicro equivalent to propose | Commercial verdict |
|---|---|---|---|
| **Blackwell RTX PRO 6000 / 5000 / 4000 / 2000, RTX 5090** | 2016 dual-E5, PCIe Gen3, unknown cooling | **Blackwell-generation PCIe GPU platforms — 4U/5U workstation-and-server GPU systems capable of multiple 600W double-width cards with PCIe Gen5 x16 per slot** | **THIS IS THE CROSSWALK THAT MATTERS COMMERCIALLY.** Everything below is legacy defence |
| **H100 80GB single-GPU** | Supermicro 4028GR-TR / X10DRG-Q-class 4U equivalent (EOL, secondary market) | SYS-421GE / AS-4125GS family 4U/5U PCIe GPU systems, or 2U SYS-221GE-class for density | **Loses on capex today.** Winnable only if bundled with the Blackwell conversation |
| **4× A100 40GB / 4× RTX A6000 / 3× A6000 / 3× A5000 / 2× RTX 5090** | ~2kW nodes on dual-E5 legacy chassis — a real power and airflow problem in a leased cage | Supermicro 4U 8–10× PCIe GPU platforms (SYS-420GP-TNR family and successors) or the AS-4125GS line | **Best amortization story.** Fixed host cost spreads across 3–4 cards; this is where a purpose-built chassis pays for itself fastest |
| **A100 40GB, RTX A6000, A40, V100, RTX 4090 and below** | Legacy, heavily discounted, depreciating | **No new Supermicro sale here** | Relevant only as evidence of refresh pressure |

---

## 10. Customers & network

### 10.1 Named customers

**None. Zero named customers, zero logo wall, zero case studies, zero press releases naming clients.** This is recorded as a **deliberate negative finding**, not an oversight.

| Relationship | Grade | What the source actually says |
|---|---|---|
| **No named customer identified** | **Hard GAP — but a structurally expected one** | No logo wall, no case studies, no named-reference page and no press release naming a customer exists on [databasemart.com](https://www.databasemart.com/), [gpu-mart.com](https://www.gpu-mart.com/) or [portal.databasemart.com/news/](https://portal.databasemart.com/news/). Searches for case studies and forum references returned only review-aggregator pages. **This is entirely consistent with the business model:** a self-serve, credit-card, instant-deploy hosting provider selling **$14.50–$2,099/month** plans to individual developers and SMBs does not have named enterprise references. **Do not expect to find one**, and do not go looking for individual reviewer names — those are private individuals |
| **Customer base — self-reported aggregate** | **Self-reported, unaudited** | The company's own [About page](https://www.databasemart.com/about/) claims **"500,000+ global customers"** and **"650,000+ services delivered"**, with a **"2024: 400K+ customer milestone"**. "Customers" almost certainly means **cumulative lifetime signups rather than active paying accounts** — the 400K-to-500K jump between the 2024 milestone and the current page is large enough to warrant that reading. **Useful only as an order-of-magnitude indicator** that this is a high-volume, low-ticket, long-tail business |
| **Customer segment and sentiment — third-party review evidence** | **Third-party aggregator; solicitation bias flagged by the platform itself** | [Trustpilot](https://www.trustpilot.com/review/databasemart.com) carries **246 reviews for databasemart.com** and **13 for gpu-mart.com**. Aggregate sentiment is broadly positive on **price, support responsiveness and fast provisioning** ("RDP/VPS setup ready to connect within 5 minutes"), with a minority reporting **server instability, crashes, performance below promise, and no refunds on GPU servers**; one gpu-mart review alleges bandwidth shortfall and "bait-and-switch". **Trustpilot itself flags that the company "may be asking for reviews in a way that compromises reliability"** — treat the positive skew with caution. **COMMERCIALLY RELEVANT READ:** the recurring complaint themes are **stability and delivered performance** — exactly what a mismatched host platform and a 100Mbps pipe on a $2,099 AI node would produce. **That connects customer pain directly to the platform argument** |
| **Cloud Clusters — affiliated brand, NOT a customer** | **Company-disclosed affiliation** | The company's own milestone timeline lists **"2017: Cloud Clusters partnership"**. Their Dallas speed-test files are hosted at `speedtest-c002.cloudclusters.io` and the Kansas City one at `speedtest-kansas.cloudclusters.io`, so **cloudclusters.io is operationally theirs or a closely affiliated brand rather than an arm's-length customer**. No separate Texas entity exists under that name (registry wildcard search returned no records). **Recorded as an affiliated brand, NOT a customer** ([About page](https://www.databasemart.com/about/) · [data-center page](https://www.databasemart.com/data-center)) |

### 10.2 Scale — what can and cannot be bounded

**Servers and GPUs: NOT DISCLOSED.** No server count, GPU count, rack count or contracted kW appears in any source reached.

What **can** be bounded from evidence: they publish **26 distinct dedicated GPU SKUs plus 8 GPU VPS tiers**, all marked Available, spanning **20+ distinct GPU models** from Pascal P1000 to Blackwell RTX PRO 6000. Maintaining live inventory across that many models implies **at minimum several units per SKU — i.e. low hundreds of GPU nodes rather than tens.**

**Upper bound from addressing:** their own routed space is a single **/22 (1,024 addresses)** in Kansas City, and each dedicated server is sold with 1 dedicated IPv4. Even allowing for the separately-addressed Dallas footprint inside Psychz space and 5,120 newly-leased RIPE addresses, the total estate supports **low thousands of servers ACROSS ALL product lines** (Windows/Linux VPS, RDP, bare metal and GPU), of which GPU is a subset.

> **ESTIMATE: on the order of 200–600 GPU nodes. This is a modelled figure, not a researched one, and must not be entered into CRM as fact.**

### 10.3 Network — AS401479

- **ASN:** **AS401479**, ARIN handle AS401479, network name **"DBM-ASN-KC"**, registered to Database Mart LLC (Org **DML-132**) on **2024-11-07**, comment "https://www.databasemart.com/". [RIPEstat as-overview](https://stat.ripe.net/data/as-overview/data.json?resource=AS401479) confirms holder "DBM-ASN-KC - Database Mart LLC", `announced = true`, within the ARIN-assigned 32-bit block 401309–402332. The **"KC" suffix ties the ASN explicitly to the Kansas City site.** Note the age: **only 21 months old** — they ran roughly four years on the Kansas City /22 without their own ASN.
- **IPv4 estate — 22,528 addresses across three pools, of which 16,384 are dormant:**
  - **OWNED (ARIN Org DML-132):** **163.123.180.0/22**, net handle NET-163-123-180-0-1, name "DBM-NET-01", 1,024 addresses, registered **2020-08-03**, in continuous production announcement since **2021-01-30** and visible to **326 of 326 RIS peers** on 2026-08-11.
  - **OWNED BUT DARK:** **38.247.128.0/18**, net handle NET-38-247-128-0-1, name "DATABASEMART-CGNT-NET-1", **16,384 addresses**, type ALLOCATION under Cogent's parent NET-38-0-0-0-1, registered **2026-01-21** — and **NOT ANNOUNCED**: [routing-status](https://stat.ripe.net/data/routing-status/data.json?resource=38.247.128.0/18) returns **0 of 326 RIS peers**, no origin AS, no first-seen date.
  - **LEASED (RIPE, via the IPXO marketplace, maintainer `netutils-mnt`):** **93.127.128.0/20**, RIPE object name "Database_Mart_LLC", ASSIGNED PA, org ORG-DML16-RIPE, 4,096 addresses; and **77.93.152.0/22**, RIPE object name "IPXO", SUB-ALLOCATED PA, registrant "Private Customer", 1,024 addresses. **Both first appeared in AS401479's announcements on 2026-07-28.**
- **Bandwidth:** not disclosed. Their own product pages sell **100Mbps unmetered** on the H100 dedicated node and **1000Mbps unmetered** on the RTX PRO 6000 VPS tier — these are **per-customer allocations, not site capacity. Site capacity is a GAP.**
- **Peering: NOT IN PEERINGDB.** The API returns `{"data": [], "meta": {"error": "Entity not found"}}` for asn=401479, and a name search for "Database" returns nothing. **They have no PeeringDB presence at all** — for a network operating its own ASN and 22,528 addresses, a notable immaturity signal.
- **BGP topology is correspondingly thin.** [RIPEstat asn-neighbours](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) for AS401479 returns exactly **ONE neighbour** — **AS32097, Wholesale Internet, Inc.** (Kansas City, MO), type "left", power 371, 3,320 v4 peers. **AS401479 is single-homed.**
- **Their own /22 is not even originated by their own ASN.** Routing-status shows a single origin of **AS32097** with an ARIN route object.
- **Upstream context:** AS32097 **is** in PeeringDB with an open peering policy, `ix_count` 10, `fac_count` 9 and self-reported traffic of **1–5 Tbps**. The Dallas footprint sits inside **Psychz Networks' AS40676** space entirely (108.181.0.0/16 registered to Psychz, Org PS-184).

> **NET READ: Database Mart owns addresses and an ASN but does not really operate an independent network — transit, origination and peering are all somebody else's.** Combined with 16,384 owned-but-dark addresses, the picture is **an operator buying capacity faster than it is building network.** Unrouted address space is forward capacity waiting on hardware.

Sources: [ARIN asns](https://whois.arin.net/rest/org/DML-132/asns.json) · [ARIN nets](https://whois.arin.net/rest/org/DML-132/nets.json) · [RIPEstat announced-prefixes](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479) · [RIPEstat asn-neighbours](https://stat.ripe.net/data/asn-neighbours/data.json?resource=AS401479) · [PeeringDB](https://www.peeringdb.com/api/net?asn=401479) · [RIPE RDAP 93.127.128.0](https://rdap.db.ripe.net/ip/93.127.128.0) · [ARIN RDAP 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28)

---

## 11. Political & public record

Public records only. Every line is tagged. **Read the tags carefully — two of the three rows below are "not searched to completion", which is not the same as "nothing found".**

| Subject | Finding | Tag |
|---|---|---|
| **Morris Liu** (CEO and Founder) | **NO FEC RESULT OBTAINED — the search did not complete and no conclusion may be drawn in either direction.** Five OpenFEC Schedule A queries were attempted across three separate points in the session (`contributor_name='Morris Liu'`; `contributor_employer='Database Mart'`; `contributor_name='Liu'` + `contributor_city='LEAGUE CITY'`), all against `api.open.fec.gov/v1/schedules/schedule_a/` using the public **DEMO_KEY**. **Every call returned HTTP 429 (rate limit exceeded)**; the DEMO_KEY hourly quota was exhausted and never recovered within the session. **At no point was a zero-result response received.** This must be recorded as **UNVERIFIED, not as "no record found"** — the distinction matters because the brief explicitly asked for "no record found" only where that is the actual result | **UNVERIFIED — API rate-limited (HTTP 429), search never executed to completion.** Re-run with a registered FEC API key from api.data.gov; the three query forms above are ready to reuse. [Query form](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=Morris%20Liu) |
| **Database Mart LLC** (entity-level) | **No corporate PAC, no independent-expenditure activity and no lobbying registration was found in any source reached.** Caveat on how weak this finding is: **no dedicated FEC committee search and no Senate LDA lobbying-disclosure search was run** — this is the **absence of incidental hits during general research, not a completed negative search.** For a privately held ~80-person Texas hosting LLC with no federal contracts visible, the prior probability of any federal political activity is low, but **that is reasoning, not evidence** | **NOT SEARCHED TO COMPLETION — treat as unknown, not as absent.** [Query form](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_employer=Database%20Mart) |
| **Unnamed officers, managers and members** | **Cannot be searched at all.** Texas does not disclose LLC members or managers in the Comptroller open-data record, and the SOSDirect filing history that would name the organizer, registered agent and any annual-report signatories is behind a paid subscriber login (see §8.3 Q3). **With no names beyond Morris Liu, there is nothing to run an FEC individual-contribution search against. This is a dependency: the registry gap causes the political-research gap** | **BLOCKED UPSTREAM — resolve the SOSDirect officer/agent gap first, then re-run FEC per name.** [SOSDirect gate](https://direct.sos.state.tx.us/acct/acct-login.asp) |

**No legislative or policy position of any kind was found for this company or its principals.** Stated plainly: **on the political and public-policy axis there is nothing established here — and, unlike the WebNX-style "essentially no footprint" finding, that is because the searches did not complete, not because they came back empty.** There is nothing here to use as a wedge, and nothing here that can yet be certified as risk-free either.

**Court record, for completeness:** [CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search/?q=%22Database+Mart%22) searches for `"Database Mart"` returned **count 0** across both RECAP dockets (`type=r`) and opinions (`type=o`). **This covers federal RECAP coverage only.** Texas **state** court records — Galveston County district and county courts, and Harris County — were **NOT searched**, and CourtListener's federal docket coverage is itself incomplete.

---

## 12. Public contact channels

Public-source only. **No personal mobile numbers and no private residential contact details are listed as outreach routes, and none were sought.** Note the registered address is a private residence — it is recorded below as a registry fact, **not** as a place to visit or ship to.

| Channel | Value | Source |
|---|---|---|
| **Pre-sales email — PRIMARY RECOMMENDED FIRST TOUCH** | **sales@databasemart.com** — the contact page explicitly invites contact through the pre-sales team **"for custom server configurations beyond standard offerings"**, which is a legitimate, on-topic reason for a hardware vendor to write | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) |
| **Office telephone — NOT published on the website; recovered from ARIN** | **+1-409-877-4238** — registered as the Office phone on **BOTH** ARIN POC records (ADMIN7533-ARIN and ABUSE8080-ARIN). The **409 area code** covers the Galveston/League City area and matches the registered address. **Because this number appears nowhere on the public website (the contact page lists no phone at all), it is unlikely to be routed to a screened marketing queue** | [whois.arin.net/rest/poc/ADMIN7533-ARIN.json](https://whois.arin.net/rest/poc/ADMIN7533-ARIN.json) |
| **Infrastructure / NOC email — best route to the technical buyer** | **admin@databasemart.com** — the ARIN-registered contact for the **Routing, Tech, NOC, DNS and Admin functions simultaneously**. Whoever reads this inbox owns the network and the nodes | [whois.arin.net/rest/poc/ADMIN7533-ARIN.json](https://whois.arin.net/rest/poc/ADMIN7533-ARIN.json) |
| General support | **support@databasemart.com** · ticket system at [console.databasemart.com/ticket](https://console.databasemart.com/ticket) · live chat on site · stated 24/7 availability | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) |
| Marketing | **marketing@databasemart.com** | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) |
| Abuse / compliance | **abuse@databasemart.com** (ARIN abuse POC ABUSE8080-ARIN) — **listed for completeness; not a sales route, do not use** | [whois.arin.net/rest/poc/ABUSE8080-ARIN.json](https://whois.arin.net/rest/poc/ABUSE8080-ARIN.json) |
| Registered / mailing address | **Database Mart LLC, 257 Westwood Dr, League City, TX 77573, United States** — identical across the Texas SOS/Comptroller record, ARIN Org DML-132, both ARIN POCs, the domain WHOIS registrant street and the public contact page. **Note this is a private residence; physical mail or drop-in visits would be inappropriate** | [databasemart.com/contact-us](https://www.databasemart.com/contact-us) · [ARIN RDAP 163.123.183.33](https://rdap.arin.net/registry/ip/163.123.183.33) |
| Corporate social | LinkedIn company page [linkedin.com/company/database-mart](https://www.linkedin.com/company/database-mart) · a **company-operated** personal-format profile at [linkedin.com/in/database-mart-788a35111/](https://www.linkedin.com/in/database-mart-788a35111/) · Facebook [facebook.com/databasemart](https://www.facebook.com/databasemart/). **No personal LinkedIn profile for Morris Liu was located — GAP** | [LinkedIn](https://www.linkedin.com/company/database-mart) |
| **Press / news feed — useful for timing the next approach** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) — the company's own dated announcement feed; historically where GPU launches are announced first. **Worth monitoring for the Sep–Dec 2026 purchase window (§7.3)** | [portal.databasemart.com/news/](https://portal.databasemart.com/news/) |
| Direct-dial for any named individual | **GAP — none published.** No personal email and no direct line exists for Morris Liu or anyone else | — |

---

## 13. Supermicro sales angle

### Classification: **Self-integrator on secondary-market hosts → platform conversion on the Blackwell refresh**

**This is NOT incumbent defence, and it is NOT displacement of a rival OEM.** There is no OEM incumbent to displace. Database Mart self-integrates: every one of the 26 dedicated SKUs they publish runs on Xeon E5 v3/v4, Gold 6148 or Platinum 8160 hosts — 2014-2017 silicon, with zero current-generation platforms anywhere in the catalogue. **The competitor is not Dell or Gigabyte; it is a $700 used 4U chassis.** Accept that and the strategy becomes clear.

### Be honest about where we lose

**On a like-for-like H100 node, we lose and should not try.** Their flagship is a single H100 on a Dual E5-2697v4 host where **the GPU is 90–95% of BOM and the host is effectively free**. No new Supermicro platform beats free on capex, and the cost-ceiling model shows why they built it that way: at **$2,099/month** list, with 35–50% opex and 75–85% realization, the entire node hardware budget is **$18,900–$27,800 even at a generous 24-month payback — less than one new H100 card.** **Leading with a new-platform quote against that SKU gets the call ended.**

### Where we win — the wedge

> **The RTX PRO 6000 96GB and the rest of the Blackwell line physically break the legacy platform.**

Between **2025-11-08** and **2026-04-19** they added six Blackwell SKUs — RTX PRO 6000 (live 2025-11-08 at $729/mo), RTX PRO 5000 and 4000 (2026-01-12), RTX PRO 2000 (2026-01-16), plus RTX 5090 and 5060 — and consolidated them onto a Blackwell hub page. **Those are PCIe Gen5, 600W-class parts. Their published host cannot serve them:** the E5-2697v4 is Broadwell-EP on a PCIe 3.0 root complex.

**Their own [H100 page](https://www.gpu-mart.com/h100-hosting) proves they know the spec matters and haven't reconciled it** — it advertises "PCIe Gen5" in the card specification while listing a CPU generation that tops out at Gen3. **That is not a gotcha to wave at them; it is a shared engineering problem to open with, and a CS-PhD founder will engage with it.**

Three reinforcing pressures make the timing right:

1. **They are selling a 96GB RTX PRO 6000 as a partitioned 32-core VPS slice**, so they need a platform that validates cleanly under multi-tenant partitioning, not a scavenged board.
2. **Their price on that card has already fallen from $729 to $479 in nine months**, so margin is compressing while they are still buying — **efficiency per rack-U and per kW starts to matter more than chassis capex.**
3. **Trustpilot's recurring complaint themes are instability and performance below promise**, which is exactly what a mismatched host produces — **the platform argument is also a churn argument.**

**Secondary, quieter signal worth carrying:** they registered **38.247.128.0/18 — 16,384 addresses — on 2026-01-21 and it is still completely unrouted** (0 of 326 RIS peers). **Nobody pays for a /18 they don't intend to fill.** Combined with 5,120 leased addresses brought live on 2026-07-28, that is **forward capacity waiting on hardware.**

### The one qualifying question for first contact

> **"On the RTX PRO 6000 96GB nodes you launched in November — are those going into the same Dual E5-2697v4 platform as the H100 line, or did you move to a new chassis for them? I'm asking because of the Gen5 x16 and the 600W-class power and thermal envelope, and I want to know whether the constraint you're managing is the board or the per-rack kW cap in your colo cages."**

**Ask this, then stop talking.** It is specific, it is answerable from their own published spec, it is not a trap, and the answer immediately sorts the opportunity:

- **"Same platform"** → a live technical problem we can solve.
- **"New chassis"** → find out whose, and whether it was bought new or used.
- **"kW cap"** → the conversation is about **density and efficiency, not capex**, which is a much better conversation for us.

**Second qualifying question, held in reserve:** the RIPE-region prefixes brought live on 2026-07-28 — are those an actual European facility, a planned one, or address arbitrage announced from Kansas City? That answer sizes the forward opportunity.

### Rule 8 — distributor caution (read before dialling)

> **Establish the buying route before registering anything. Do not assume this is a direct account.**

Every signal in the evidence — **uniform 2014-2017 host silicon, 20–55% standing discounts concentrated on prior-generation cards, a GPU-dominated BOM on near-free hosts, and a fleet that mixes Pascal through Blackwell** — points to procurement through **distribution, brokers, integrators or the secondary market** rather than direct OEM purchase. **No hardware vendor is named anywhere in public sources** (a grep of both domains for eight OEM names returned **zero hits across the board**), so **the channel is genuinely unknown.**

**Before submitting:**

- **(a)** Confirm on the qualifying call **how they source chassis and cards today.**
- **(b)** If the answer is a distributor, reseller or integrator, register **Database Mart LLC as the end user** and **never the distributor** — the distributor is not the account.
- **(c)** Check whether an **existing distributor registration already covers this end user**, because a duplicate direct registration on a distribution-fulfilled deal is exactly the channel-conflict failure Rule 8 exists to prevent.
- **(d)** **Size it honestly** — a 200–600 node estate refreshing a Blackwell subset is a real but modest opportunity, **well under the $100M CRM threshold**, and it should be slotted accordingly rather than inflated to justify a direct-registration exception.

**Territory is settled:** League City, Texas is **T1** (also T3), **Team 1 can register directly**, and CRM was verified clean on **2026-08-11** — no lead, no account, no do-not-call.

**Sequence — do not reorder:** ① establish the buying route and clear the channel position (Rule 8) → ② register Database Mart LLC as the end user (T1, Team 1, direct) → ③ make contact via sales@databasemart.com or +1-409-877-4238, asking only the qualifying question above.

---

## 14. Verification appendix

### 14.1 Single-source claims — re-verify before quoting

| Claim | Only source | Risk |
|---|---|---|
| **The surname "Liu"** for the CEO | [TheOrg](https://theorg.com/org/database-mart-llc/org-chart/morris-liu) only | **Single third-party aggregator, not a primary registry filing.** The company's own site uses the first name "Morris" alone, and the Texas registry does not name him at all. **Confirm verbally on first contact before using the full name in writing** |
| **Supermicro presence in the legacy fleet** | **No source — pure inference from platform generation** | **Graded INFERRED. Must never be stated to the customer as known.** This is the single most likely error a salesperson would make on this account |
| **"80+ professionals across six departments"** | Company [About page](https://www.databasemart.com/about/), self-reported; loosely corroborated by ZoomInfo's 51–200 band | Self-reported marketing text. **Do not restate as an audited headcount** |
| **"500,000+ global customers" / "650,000+ services delivered"** | Company [About page](https://www.databasemart.com/about/) only | **Self-reported, unaudited, and almost certainly cumulative lifetime signups rather than active accounts.** Do not restate as a customer count |
| **Facility power/cooling specs at both colo sites** | Company [data-center page](https://www.databasemart.com/data-center) only | **These describe the BUILDING, not Database Mart's footprint within it.** Quoting "2× 2MW generators" or "360 tons of cooling" as Database Mart's capacity would be wrong. Note the page also contains the verbatim typo **"Evergy Ttier 1 customer"** |
| **Kansas City facility operator** | **Not named in any source** — only the transit provider (Wholesale Internet, AS32097) is established | The building operator at 1530 Swift St is a **GAP**. Do not assume Wholesale Internet owns it |
| **Trustpilot sentiment themes** | Search-result summaries of [databasemart.com](https://www.trustpilot.com/review/databasemart.com) (246 reviews) and [gpu-mart.com](https://www.trustpilot.com/review/gpu-mart.com) (13 reviews) | **Trustpilot itself flags possible review-solicitation bias.** Individual reviewers were deliberately **not** compiled — they are private individuals |
| **H100 street pricing $25,000–$30,970** | Web search across compute.exchange, cloudzero, northflank, intuitionlabs, gmicloud and others, **as of March 2026** | Multi-source but **five months stale as of this dossier**, and some vendors quote $30,000–$38,000 in tight supply. **Re-check same-day before quoting** |
| **Revenue band $10M–$25M** and **200–600 GPU nodes** | **Neither is sourced — both are modelled ESTIMATES** | Derived from headcount × revenue-per-employee and from SKU breadth × IPv4 estate respectively. **Must not be entered into CRM as fact** |

### 14.2 Conflicting or anomalous records — shown, not resolved

**Registered NAICS code**

| Source | Value |
|---|---|
| Texas Comptroller taxable-entity record | **541410 — Interior Design Services** |
| Actual business | Web/GPU hosting |

**Unresolved and recorded verbatim, not corrected.** Almost certainly a stale or miscoded classification carried since 2005. Harmless, but it means **NAICS-based screening will not find this company as a hosting business.**

**Founding date vs domain registration**

| Source | Date |
|---|---|
| Texas SOS charter · company About page | **2005-01-13** |
| databasemart.com domain creation (RDAP) | **2004-11-16** |

**Not a conflict — a sequence.** The founder registered the domain two months before incorporating. Recorded because it is corroborating rather than contradictory.

**Headcount**

| Source | Figure |
|---|---|
| Company About page (self-reported) | **80+** |
| ZoomInfo | **51–200** |

**Consistent, not conflicting.** Tag any use as "self-reported, third-party band consistent."

**Registered address**

| Source | Character |
|---|---|
| Texas SOS/Comptroller · ARIN Org DML-132 · both ARIN POCs · domain WHOIS · company contact page | **Corporate registered address** |
| HAR, Zillow, Redfin property records | **5-bed / 3.5-bath, ~4,300 sq ft single-family home built 2014** |

**Both are true.** The company's registered address is a private residence. **This is the correct characterisation and must be carried into any CRM record**, so nobody attempts a site visit or a shipment there.

### 14.3 Open gaps

1. **UCC-1 FINANCING STATEMENTS — the single biggest gap.** Zero filings retrieved; verdict is **"UNVERIFIED — portal blocked"**, not "no filings". Texas UCC records sit behind SOSDirect's paid subscriber login, which was not breached. **No filing number, date, lapse/continuation, secured party, debtor address, collateral description or amendment/assignment/termination can be reported.** **ACTION:** run a UCC-11 debtor search on `DATABASE MART LLC` and on unanchored `DATABASE MART` via a SOSDirect account or a commercial lien vendor.
2. **OFFICERS, MANAGERS, MEMBERS AND REGISTERED AGENT — completely unknown.** The Texas Comptroller open-data record carries no officer/agent fields, and the Comptroller account-status detail view is a JS SPA that returned only the empty form shell across three query methods. SOSDirect, which holds the certificate of formation, filing history and annual-report signatories, is behind the same paid login. **Morris Liu is the ONLY name in this dossier and it comes from a single third-party aggregator, not a primary filing.**
3. **FEC POLITICAL CONTRIBUTIONS — never searched to completion.** All five OpenFEC queries returned HTTP 429 on the public DEMO_KEY across three attempts. Recorded as **UNVERIFIED, explicitly not as "no record found"**. Re-run with a registered api.data.gov key.
4. **USPTO TRADEMARK — no record retrieved and no declaration signatory or correspondent identified.** Four API routes failed: `tmsearch.uspto.gov/api-v1-0-0/tmsearch` returned **HTTP 404 (NoSuchKey)** on GET and **HTTP 405** on POST; `developer.uspto.gov` endpoints returned **HTTP 301**; TMDN/TMview POST returned **HTTP 000**; `trademarks.justia.com` returned **HTTP 403**. A general web search for "Database Mart"/"GPU Mart" trademarks returned only generic explainer articles. **It is entirely possible they hold no registered mark, but that was NOT established — the search never ran.**
5. **HISTORICAL WHOIS** — whoisrequest.com returned **HTTP 403**; whoxy and securitytrails were not reached. Only **current** WHOIS/RDAP was obtained (databasemart.com created 2004-11-16, expires 2026-11-16, updated 2025-11-02; gpu-mart.com created 2021-11-15, expires 2026-11-15; both at **NetEarth One Inc. d/b/a NetEarth** with **Cloudflare** nameservers THADDEUS/VIVIENNE and clientTransferProhibited; registrant organization **REDACTED FOR PRIVACY** though the registrant street "257 Westwood Dr." is exposed; databasemart.com carries DNSSEC signedDelegation). **No historical registrant name, no pre-privacy record, no registrar-change or nameserver-change timeline.**
6. **SUPERMICRO PRICING FOR THE BOM COMPARISON** — no Supermicro configurator or distributor quote was pulled, so **no list price is stated** for the equivalent new system. **This must be filled with a live quote before any customer conversation**; the BOM comparison is structurally complete but numerically one-sided.
7. **SECONDARY-MARKET COMPONENT PRICING** — the Dual E5-2697v4 pair, 256GB DDR4 ECC RDIMM, 4U dual-E5 GPU chassis, and storage/NIC line items were **not independently priced**. Only the H100 card was sourced. **The BOM conclusion that the GPU is 90–95% of node cost is therefore reasoned, not fully priced.**
8. **HARDWARE VENDOR — no server OEM identified for any part of the fleet.** Grep of both live homepages plus `/gpu-specs`, `/about/` and `/about-us` for Supermicro, Dell, Gigabyte, ASUS, Tyan, Inspur, Lenovo and HPE returned **ZERO hits on every term**. **The Supermicro attribution in §5 is graded INFERRED and must never be stated as fact.**
9. **COLO CONTRACT TERMS** — Database Mart's own cage size, rack count, contracted kW and contract expiry at both **1515 Round Table Dr (Dallas)** and **1530 Swift St (North Kansas City)** are unknown. Only building-level facility specs were obtained, and those are **the operator's, not the tenant's**. **The Kansas City facility OPERATOR is also not confirmed by name** in any public record.
10. **SERVER AND GPU COUNTS** — not disclosed anywhere. The **200–600 GPU node figure is a modelled ESTIMATE** bounded by SKU breadth and IPv4 estate, not a researched number.
11. **REVENUE** — not disclosed. No SEC filings (none expected), no Crunchbase revenue figure, no funding rounds on record. **The $10M–$25M band is a modelled ESTIMATE** from headcount and revenue-per-employee, cross-checked against catalogue rents.
12. **COUNTY PROPERTY / ASSESSOR RECORDS** — the Galveston CAD parcel record for 257 Westwood Dr was **not pulled directly**; property characteristics came from real-estate listing aggregators (HAR, Zillow, Redfin), which establish it is a residence but **do not give the assessed value, the recorded owner name or the deed history**. No assessor record was sought for either datacenter address, since both are third-party facilities where the tenant is not the owner.
13. **COURT DOCKETS** — CourtListener searches for `"Database Mart"` across both dockets (`type=r`) and opinions (`type=o`) returned **count 0**. **This covers federal RECAP coverage only.** Texas **state** court records — Galveston County district and county courts, and Harris County — were **NOT searched**, and CourtListener's federal docket coverage is itself incomplete.
14. **JOB POSTINGS AND NAMED STAFF** — **no careers page located and no job posting for Database Mart found on any board.** No conference bios, podcast appearances, community-forum staff accounts or blog author bylines were identified. Consequently **no hiring managers and no technical staff names beyond the CEO.** The three unnamed department heads in §3.1 are inferred from the company's own department list, not from any individual source.
15. **PEERINGDB** — Database Mart has **NO PeeringDB record at all** (API returns `Entity not found` for asn=401479), so there is **no facility list, no IX presence, no traffic-level self-report and no peering contact** from that source. Their network topology had to be reconstructed **entirely from RIPEstat BGP data**.
16. **EU / THIRD-SITE FOOTPRINT** — the two RIPE-region prefix families (93.127.128.0/20 and 77.93.152.0/22, **5,120 addresses**) that AS401479 began announcing on **2026-07-28** are IPXO-leased space with **US country codes**. **Whether this corresponds to an actual European facility, a planned one, or simply address arbitrage announced from Kansas City is UNRESOLVED.**
17. **DELAWARE REGISTRATION** — the eCorp entity search could not be driven programmatically (HTTP 200 on GET returning an ASP.NET form with CAPTCHA; HTTP 411 on POST). **Likely a dead end** since the Comptroller codes the entity as organizational type **CL (Texas domestic LLC)**, meaning Texas is the state of organization — **but this was not affirmatively confirmed.**
18. **NAMED CUSTOMERS — none exist in public sources**, and this is **expected** for a self-serve SMB hosting provider. Recorded as a **structural gap rather than a research failure**. Individual Trustpilot reviewers were deliberately **not** compiled — they are private individuals.
19. **WAYBACK COVERAGE HOLES** — **seven of eighteen** catalogue snapshots (2024-01-18, 2024-09-15, 2024-11-27, 2024-12-22, 2025-11-26, 2026-01-11, 2026-02-08) returned zero model matches because the archived response was a JS shell or a gzip-garbled capture. **Those dates are absent evidence, not evidence of absence**; model-specific landing-page anchors were used to bridge them, but **the purchase-clock cadence carries that uncertainty.** One CDX call for the 2025-08 to 2026-05 window returned **HTTP 504 Gateway Time-out**. Individual landing-page snapshots for `/rtx-5090-hosting` (2024-12-22) and `/nvidia-a100-rental` (2024-03-05) came back **binary-garbled and yielded nothing**.
20. **GPU-MART.COM SITE-LEVEL GAPS** — `/gpu-specs`, `/about-us` and `/gpu-vps-hosting` returned **empty or HTTP 404**. Some catalogue detail — **per-SKU stock levels, exact discount expiry, and contract-term pricing ladders beyond the 3/12/24-month mentions** — was therefore not captured.
21. **TOOLING NOTE FOR A RE-RUN** — the ZoomInfo MCP connector (and carta, figma, atlassian, spglobal, adobe connectors) require OAuth authorisation and could not be used in this non-interactive session. **Authorising the ZoomInfo connector would likely close the revenue-estimate and named-staff gaps on a re-run.**

### 14.4 Sources worked — including what returned nothing

**HIT — highest-value sources of the session:**

- **[ARIN RDAP 163.123.183.33](https://rdap.arin.net/registry/ip/163.123.183.33)** — the single highest-value source. Returned Org **DML-132** "Database Mart LLC", net NET-163-123-180-0-1 name **"DBM-NET-01"** (163.123.180.0/22), registered 2020-08-03, address 257 Westwood Dr, plus POC handles **ADMIN7533-ARIN** and **ABUSE8080-ARIN** with office phone **+1-409-877-4238** — a number that appears nowhere on the company website.
- **[ARIN RDAP 108.181.95.28](https://rdap.arin.net/registry/ip/108.181.95.28)** — returned **Psychz Networks** (Org PS-184, AS40676, Walnut CA) as registrant of the Dallas space, with abuse POC **TEXAS1-ARIN** registered to "Profuse Solutions INC" at 1515 Round Table Drive, Dallas TX 75247. **This is what proved the Dallas site is leased, not owned.**
- **ARIN Whois-RWS** — [org DML-132 nets](https://whois.arin.net/rest/org/DML-132/nets.json), [asns](https://whois.arin.net/rest/org/DML-132/asns.json), [pocs](https://whois.arin.net/rest/org/DML-132/pocs.json), plus `/rest/poc/{ADMIN7533,ABUSE8080}-ARIN.json` and `/rest/asn/AS401479.json`. Enumerated the complete ARIN estate: ASN AS401479 "DBM-ASN-KC" (registered 2024-11-07) and two nets including the previously unknown **38.247.128.0/18** "DATABASEMART-CGNT-NET-1" registered 2026-01-21. Also confirmed **both POCs are `isRoleAccount=Y` with no individual names.**
- **ARIN org-name search** — `whois.arin.net/rest/orgs;name=Database%20Mart*` returned exactly one org (DML-132), confirming **no sibling ARIN registrations**.
- **RIPE RDAP** — [93.127.128.0](https://rdap.db.ripe.net/ip/93.127.128.0) and [77.93.152.0](https://rdap.db.ripe.net/ip/77.93.152.0). Identified the leased European-registry space and established these are **IPXO-marketplace leases, not owned space**.
- **[RIPEstat](https://stat.ripe.net/data/announced-prefixes/data.json?resource=AS401479)** — announced-prefixes, as-overview, asn-neighbours and routing-status data calls. Established that **AS401479 is single-homed behind AS32097**, that the /22 is originated by AS32097 (not by Database Mart's own ASN) continuously since 2021-01-30, that the leased RIPE prefixes went live 2026-07-28, and critically that **the 16,384-address /18 is NOT announced (0 of 326 RIS peers)**.
- **[Texas open data (Socrata)](https://data.texas.gov/resource/9cir-efmm.json)** — franchise-tax permit holders, queried with a SoQL `$where` clause on `upper(taxpayer_name)`. **The source that cracked the registry question.** Returned taxpayer_number 32107118534, SOS file 0800439627, charter date 2005-01-13, status A/A, org type CL, address 257 Westwood Dr. A second wildcard query on `%MART%` limited to LEAGUE CITY confirmed **DATABASE MART LLC is the only such entity**; further queries for CLOUD CLUSTERS, VPS MART, SERVER MART, GPU MART and WINPC each returned **"(no records)"**, proving the sibling brands are trading names.
- **[Wayback CDX API](https://web.archive.org/cdx/search/cdx)** — the backbone of the purchase clock. Produced first-capture dates for `/rtx-a6000-hosting` (2023-02-08), `/nvidia-a100-rental` (2024-03-05), `/rtx-5090-hosting` (2024-12-22), `/h100-hosting` (2025-02-13), `/rtx-pro-6000-hosting` (2025-11-08), `/rtx-pro-4000-blackwell` and `/rtx-pro-5000-blackwell` (2026-01-12), `/rtx-pro-2000-blackwell` (2026-01-16) and `/nvidia-blackwell-gpu-server` (2026-04-19).
- **Wayback raw snapshot fetches (`id_` URLs)** — 18 captures of `/gpu-dedicated-server` from 2023-06-04 to 2026-04-19, regex-matched against 26 GPU model patterns. **Eleven parsed cleanly** and dated the arrival of RTX 4060 (by 2023-11-13), P100 (by 2024-05-22) and H100/RTX 5090/RTX 5060 (by 2025-06-16). **Seven returned zero matches** (JS shell or gzip-garbled). The [2025-11-08 /rtx-pro-6000-hosting capture](https://web.archive.org/web/20251108102809/https://www.gpu-mart.com/rtx-pro-6000-hosting) yielded price "$ 729.00" and an "order now" control.
- **[gpu-mart.com/gpu-dedicated-server](https://www.gpu-mart.com/gpu-dedicated-server)** — full transcription of 26 dedicated GPU SKUs with prices, specs, discount percentages and availability. **Every host CPU is Xeon E5 v3/v4, Gold 6148 or Platinum 8160.**
- **[gpu-mart.com/h100-hosting](https://www.gpu-mart.com/h100-hosting)** — **the source of the decisive technical finding.** Confirmed the flagship is "Nvidia H100 80GB HBM2e PCIe" on a "36-Core Dual E5-2697v4" host, 256GB RAM, 240GB SSD + 2TB NVMe + 8TB SATA, 100Mbps unmetered, $2,099.00/mo on 24-month term, status Available — **a PCIe Gen5 card on a PCIe Gen3 platform.**
- **[gpu-mart.com/gpu-vps](https://www.gpu-mart.com/gpu-vps)** and **[/rtx-pro-6000-hosting](https://www.gpu-mart.com/rtx-pro-6000-hosting)** and **[/nvidia-blackwell-gpu-server](https://www.gpu-mart.com/nvidia-blackwell-gpu-server)** — eight GPU VPS tiers and the current Blackwell line-up.
- **[databasemart.com/about/](https://www.databasemart.com/about/)** — founding date 2005-01-13, founder "Morris" (Ph.D. Computer Science), full milestone timeline, 500,000+ customers, 650,000+ services, "80+ professionals across six departments".
- **[databasemart.com/contact-us](https://www.databasemart.com/contact-us)** — address, emails support@/marketing@/sales@, ticket console, 24/7 support, and **explicitly NO phone number published** (making the ARIN-sourced +1-409-877-4238 more valuable).
- **[databasemart.com/data-center](https://www.databasemart.com/data-center)** — both colo addresses, test IPs 108.181.95.28 and 163.123.183.33, and full facility power/cooling/carrier specs including the verbatim typo "Evergy Ttier 1 customer".
- **[portal.databasemart.com/news/](https://portal.databasemart.com/news/)** — dated press releases: GPU hosting launch **JUN 2020**; "Expands GPU Hosting Offerings" **JAN 2023** with 4 new dedicated GPU SKUs; "Network and Power Issue in Kansas Data Center" **JUL 2023**.
- **[TheOrg](https://theorg.com/org/database-mart-llc/org-chart/morris-liu)** — the only source of a personal name: "Morris Liu — CEO", no direct reports.
- **Domain WHOIS and Verisign RDAP** for databasemart.com and gpu-mart.com — creation/expiry dates, NetEarth One registrar, Cloudflare nameservers, REDACTED registrant organization with exposed registrant street.
- **Property records via HAR.com, Zillow and Redfin** for 257 Westwood Dr — 5-bed/3.5-bath, ~4,300 sq ft single-family home built 2014, last sold 2018-01-25, Zestimate ~$482,700 — **establishing the registered HQ is a residence.**
- **H100 street-price research** across compute.exchange, cloudzero, northflank, intuitionlabs, gmicloud and others — new US street $25,000–$30,970 (some quotes $30,000–$38,000 in tight supply) as of March 2026; refurbished $21,000–$34,000; used non-refurbished $15,000–$28,000.
- **[peeringdb.com/api/net?asn=32097](https://www.peeringdb.com/api/net?asn=32097)** — returned Wholesale Internet, Inc. with open policy, ix_count 10, fac_count 9, traffic 1–5 Tbps.

**RETURNED NOTHING:**

- **[PeeringDB for asn=401479](https://www.peeringdb.com/api/net?asn=401479)** — `{"data": [], "meta": {"error": "Entity not found"}}`. A name search for "Database" also returned an empty data array. **Database Mart has no PeeringDB presence whatsoever.**
- **[Live homepage grep for hardware vendors](https://www.gpu-mart.com/)** — curl of both homepages counting Supermicro, Dell, Gigabyte, ASUS, Tyan, Inspur, Lenovo, HPE: **zero occurrences of every term on both sites.** A supporting web search also returned nothing referencing either domain.
- **[CourtListener API v4](https://www.courtlistener.com/api/rest/v4/search/?q=%22Database+Mart%22)** — count 0 and document_count 0 on both `type=r` and `type=o`.
- **Job boards and hiring research** — Indeed, ZipRecruiter, CareerBuilder, FlexJobs, Joblist: no careers page, no job postings, no hiring managers, no named technical staff.
- **[gpu-mart.com/gpu-specs](https://www.gpu-mart.com/gpu-specs)**, `/about-us`, `/gpu-vps-hosting` — empty or HTTP 404.

**BLOCKED, and why:**

- **[Texas SOSDirect](https://direct.sos.state.tx.us/acct/acct-login.asp)** — HTTP 200 returning a **fee-based subscriber login**. No account created, no credentials entered. **The single blocker for both the UCC verdict and the officer/registered-agent gap.**
- **[Texas SOS UCC section](https://www.sos.state.tx.us/ucc/index.shtml)** (HTTP 200, informational only, no search interface) · `direct.sos.state.tx.us/ucc/ucc-search.asp` (**HTTP 404**) · [sos.state.tx.us/ucc/forms/index.shtml](https://www.sos.state.tx.us/ucc/forms/index.shtml) (**HTTP 403**). **ALL BLOCKED — no UCC search executed.**
- **Texas "SOS Portal" successor hostnames** — `sosportal.sos.texas.gov` and `businessfilings.sos.texas.gov` **did not resolve** to any Texas SOS endpoint (curl HTTP 000; the sandbox network path returned an unrelated third-party 404 page).
- **[Texas Comptroller Franchise Tax Account Status search](https://comptroller.texas.gov/taxes/franchise/account-status/search)** — reached but returned **no record**; three methods all returned the same 130,041-byte empty search-form shell. It is a JS SPA.
- **[Texas Comptroller Public API documentation](https://api-doc.comptroller.texas.gov/public-data/)** — content returned **truncated with no endpoint specification**.
- **[Delaware eCorp](https://icis.corp.delaware.gov/eCorp/EntitySearch/NameSearch.aspx)** — HTTP 200 on GET (ASP.NET form with CAPTCHA), **HTTP 411 on POST**. Not searchable programmatically; **CAPTCHAs are not solved.**
- **[FEC OpenFEC](https://api.open.fec.gov/v1/schedules/schedule_a/?contributor_name=Morris%20Liu)** — five calls across three attempts, **every one HTTP 429** on the public DEMO_KEY. **No result ever returned.**
- **USPTO** — four routes all failed: `tmsearch.uspto.gov/api-v1-0-0/tmsearch` (HTTP 404 NoSuchKey on GET, HTTP 405 on POST), `developer.uspto.gov` ibd-api and ds-api (HTTP 301), `tmdn.org/tmview/api/search/results` (HTTP 000), `trademarks.justia.com` (HTTP 403).
- **whoisrequest.com/history/databasemart.com** — **HTTP 403.** No historical WHOIS obtained; whoxy and securitytrails were not attempted.
- **ZoomInfo, Crunchbase, LinkedIn, Trustpilot** — reached only via **search-result summaries**, not direct fetch. ZoomInfo: 51–200 employees, no revenue figure. Crunchbase: no funding rounds, no revenue. LinkedIn: company page confirmed, no personal profile for Morris Liu, no employee list. Trustpilot: review counts and sentiment themes only.
