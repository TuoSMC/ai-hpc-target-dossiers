# QuadraNet (QuadraNet Enterprises, LLC) — Sales Intelligence Dossier
**Prepared for:** Supermicro Sales Team 1 (USA) · Officer US8664 Tuo Cheng · **Date:** 2026-08-04
**Method:** Researched through corporate history, financial and registry records, U.S. political leanings, legislative and policy positions, and the company's relationships with its customers. This is a privately held company with no SEC filings — evidence comes from state business registries, ARIN/PeeringDB, the provider's own published server specifications and pricing, job postings, community forums, and FEC records. Every fact carries its source + date inline. GAP = not found in verified material. No fabrication.
**Territory:** Los Angeles, California — West Coast South California = **T1** | T2. Team 1 could register, but see the commercial verdict before spending a slot.
**CRM status:** Verified 2026-08-03 in salesleads Search (Type = All): no lead, no account, no do-not-call record — never registered.

---

## 1. Bottom line

QuadraNet is a Los Angeles bare-metal, colocation, InfraCloud/private-cloud and DDoS-mitigation provider founded in 2001 by Ilan Mishan, operating AS8100 out of the Telecom Center building at 530 W 6th Street downtown plus leased space in roughly a dozen third-party facilities across the US and one in the Netherlands. **The commercial verdict is: do not forward-sell this account** — it is a credit-risk, asset-tracking and successor-account file, not a server pipeline, because the company has effectively collapsed (sold by VSS Capital Partners to Edge Centres on 2024-04-08; the Australian parent Edge Centres Pty Ltd had a liquidator appointed 2025-06-16; 200,000+ IPv4 addresses sold to HostPapa in early 2025; LA colocation customers given roughly one week to vacate in February 2025). The single strongest piece of evidence in this file is the hardware confirmation: QuadraNet's own promotional spec sheets state the chassis vendor verbatim — "1U Supermicro Server – 4x Hot-Swap Bays" on all four published LA dedicated-server SKUs, and "Supermicro CSE" chassis with "Supermicro IPMI" on its own bare-metal specials page ([LowEndBox exclusive offers](https://lowendbox.com/blog/quadranet-exclusive-black-friday-dedi-offers-in-los-angeles/)) — so Supermicro is a confirmed incumbent platform here, first-party and verbatim. The one thing that kills any deal is the unresolved legal and operating status of the US entity after the parent's liquidation: nobody has established whether QuadraNet Enterprises, LLC and Edge Centres LLC (US) are in receivership, dissolved, on-sold or nominally trading, and until that is answered no selling hours and no credit terms of any kind should be committed.

---

## 2. Snapshot

| Field | Value |
|---|---|
| **Legal entity** | **QuadraNet Enterprises, LLC (California)** — ARIN registers AS8100 to "QuadraNet Enterprises LLC" and [PeeringDB fac/3825](https://www.peeringdb.com/fac/3825) lists the same organisation as owner of the QuadraNet LAX facility. The trade name **"QuadraNet, Inc."** also appears in a Dun & Bradstreet directory listing and in FEC records; whether it is a separate legal entity or a legacy/DBA name is **GAP**. California SOS entity number, formation date, status and agent for service of process = **GAP** (bizfileonline.sos.ca.gov exposes only opaque image-API endpoints; Bizapedia served a security interstitial; OpenCorporates served a HAProxy CAPTCHA, not bypassed). |
| **HQ (verified address)** | **530 W 6th Street, Penthouse, Los Angeles, CA 90014** — the "Telecom Center" building in downtown LA, adjacent to One Wilshire ([Yelp business listing](https://www.yelp.com/biz/quadranet-los-angeles)). Some directories render the ZIP as 90017; cloudandcolocation gives 530 West 6th Street, CA 90014. A Tarzana, CA association exists (RocketReach profile; the 2012 FEC record for Ilan Mishan) but is **not corroborated as a corporate HQ — treat as unverified**. |
| **Founded** | **2001, Los Angeles, by Ilan Mishan** — corroborated independently by the HostingAdvice CEO feature, the Mergr/Preqin deal records and the cxponent vendor profile. |
| **Ownership** | Founder-owned (Ilan Mishan) → **VSS Capital Partners (Veronis Suhler Stevenson)** private equity → sold to **Edge Centres** on **2024-04-08** (terms undisclosed). Current parent **Edge Centres Pty Ltd (ACN 647 483 476)** had a winding-up order and liquidator appointed **2025-06-16** ([ASIC published notice](https://publishednotices.asic.gov.au/browsesearch-notices/notice-details/Edge-Centres-Pty-Ltd-647483476/8f031111-abd0-4700-9a06-56f8b484a5e2)). Whether the US "Edge Centres LLC" is separately solvent = **GAP**. |
| **Headcount** | **28 employees — THIRD-PARTY ESTIMATE, source [RocketReach](https://rocketreach.co/quadranet-enterprises-llc-profile_b5cd1cf9f42e0ad1), not a company disclosure.** Crunchbase, ZoomInfo, PitchBook and D&B were paywalled or returned HTTP 403 and could not corroborate it. Post-liquidation headcount = **GAP, almost certainly far below 28**. |
| **Revenue** | **$8.8M annual — THIRD-PARTY ESTIMATE, source [RocketReach](https://rocketreach.co/quadranet-enterprises-llc-profile_b5cd1cf9f42e0ad1), vintage unknown.** Almost certainly pre-2024 and no longer representative after the 2025 asset sales, customer evictions and parent liquidation. No audited or disclosed financials exist; the VSS sale price was never disclosed. **Do not present this number as fact.** |
| **ASN** | **AS8100** — ASName ASN-QUADRANET-GLOBAL, ARIN-allocated 2009-10-22, org QuadraNet Enterprises LLC; PeeringDB "aka" field reads "FKA AS29761". IRR AS-SET: AS-SET-QUADRANET. **Network effectively dismantled**: bgp.he.net shows a single originated IPv4 prefix (198.55.111.0/24, now attributed to HostPapa) and ipinfo.io reports 0 announced IPv4 prefixes ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| **CRM status** | **Never registered.** Verified 2026-08-03 in salesleads Search (Type = All): no lead, no account, no do-not-call record. |
| **Territory / team** | Los Angeles, CA → **West Coast South California = T1 \| T2** per "Territory Map-Jan.2026 (Rev.1)" Sales Territory Assign tab → Team 1's own territory (T2 may also work it), **but the target itself has collapsed**. |

---

## 3. Corrections to the working list

Only the rows that concern QuadraNet. Read these before any first contact — opening on a wrong premise loses credibility immediately.

| # | Working-list claim | Verdict | Evidence and the correct wording |
|---|---|---|---|
| 4 | QuadraNet is located at One Wilshire | **Partly confirmed — but the framing must be fixed** | PeeringDB does list "CoreSite - Los Angeles (LA1) One Wilshire" among AS8100's private peering facilities, so **there genuinely is a network/peering presence inside One Wilshire**. But the flagship self-operated datacenter is **not** in One Wilshire — it is **next door at 530 W 6th Street (Telecom Center)**, where QuadraNet has been a tenant since 2004, is described as the largest tenant, and occupies space on 6 different floors. Correct wording: **an interconnection presence inside One Wilshire, with the real datacenter volume in the building next door** ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). Further caveat: this whole footprint is now historical — LA colocation customers were told in February 2025 to vacate within roughly one week. |
| 5 | QuadraNet sites: LA, Dallas, Miami, Atlanta, **NYC** | **Partly confirmed (NYC is wrong)** | LA, Dallas (TierPoint Dallas), Miami (South Reach Networks) and Atlanta (CoreSite AT1) are all confirmed by PeeringDB. **No New York City facility exists in any source** — the New-York-metro presence is in **Secaucus, New Jersey** (H5 Data Centers Secaucus and InterServer Teb2), which QuadraNet itself marketed as "New Jersey". The claim also **understates** the footprint: it omits Chicago (Equinix CH3), Seattle/Tukwila (WowRack) and Woerden, Netherlands (HostSlim) ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| 9 | QuadraNet uses Supermicro and/or Dell hardware | **Confirmed (Supermicro) / partly confirmed (Dell)** | **Supermicro is first-party and verbatim**: the spec line "1U Supermicro Server – 4x Hot-Swap Bays" appears on all four LA dedicated-server SKUs (X3450, E3-1241v3, dual E5620, E-2124G), and QuadraNet's own specials_baremetal page listed **"Supermicro CSE"** chassis with **"Supermicro IPMI"** (that URL returned HTTP 404 on direct test 2026-08-03; content captured via search index). **Dell is inferred only**: the sole basis is that the bare-metal specials page offered out-of-band management as either "Dell Enterprises iDRAC" or "Supermicro IPMI", and iDRAC is Dell-exclusive — so some PowerEdge inventory must exist, **but model, generation and fleet share are all GAP and must not be stated as known**. Note also that the entire documented fleet runs Nehalem through Broadwell/Coffee Lake — **already 5–10 years behind current silicon before the company collapsed**. |
| 13 | All six working-list providers are Supermicro customers (implicit premise) | **Contradicted as a blanket premise; QuadraNet is one of the two that hold up** | Across the six-provider study only **two** are confirmed Supermicro (ReliableSite and QuadraNet — and QuadraNet has collapsed); one is strong circumstantial; one is an inference signal only; one is entirely unverified; one is confirmed **Lenovo**. For QuadraNet specifically the premise is correct — but correct about a company that no longer functions. |

---

## 4. Leadership & ownership

| Person / entity | Role | Evidence and grade |
|---|---|---|
| **Ilan Mishan** | **Founder & CEO** (from 2001, pre-PE era) | "QuadraNet was originally formed in 2001 in Los Angeles by founder Ilan Mishan"; described as co-founder & CEO responsible for day-to-day operations and product/technology strategy. Corroborated by a LowEndBox CEO interview and the [HostingAdvice CEO feature](https://www.hostingadvice.com/blog/quadranet-hosting-solutions-help-businesses-evolve/). **His current status after the 2024 sale is unconfirmed**; a RocketReach profile associates him with "NEO Investment Group, LLC" as Managing Partner — **unverified**. |
| **VSS Capital Partners (Veronis Suhler Stevenson)** | Prior private-equity owner / seller, exited April 2024 | [MergerLinks](https://app.mergerlinks.com/transactions/2024-04-08-quadranet/dealmakers) records "Edge Centres completed the acquisition of QuadraNet from VSS" dated **2024-04-08**; Mergr and Preqin both record Veronis Suhler Stevenson as the selling party. **Deal terms were not disclosed.** |
| **Edge Centres LLC / Edge Centres Pty Ltd** | Acquirer and current parent (April 2024) — **parent now in court liquidation** | The acquisition added 10 facilities to Edge Centres' US footprint and, combined with its July 2023 Multacom acquisition, supported a claim of 100,000+ sq ft of California white space. ASIC published notice dated 2025-06-17 that **Edge Centres Pty Ltd (ACN 647 483 476) was subject to a winding-up order with a liquidator appointed 2025-06-16** ([ASIC notice](https://publishednotices.asic.gov.au/browsesearch-notices/notice-details/Edge-Centres-Pty-Ltd-647483476/8f031111-abd0-4700-9a06-56f8b484a5e2)). **The ASIC notice covers the Australian Pty Ltd entity; whether the US "Edge Centres LLC" is separately solvent = GAP.** |
| **Jonathan Eaves** | Founder of Edge Centres (ultimate parent at time of acquisition) | Edge Centres described as a Series A company based in Grafton, Australia, founded 2021 by Jonathan Eaves; he posted publicly on LinkedIn about the QuadraNet acquisition. **Community / third-party search-summary sourced**; his current status relative to the liquidation = **GAP** ([Tracxn profile](https://tracxn.com/d/companies/edgecentres/__E6n2qW0H3JimCz2rtct9NQW22tA5XiWisvLJp-Wa4Ts)). |
| **Kiarash Jahangiri** | CEO of QuadraNet appointed post-acquisition (2024) — **CONFLICTING REPORTS** | [DataCenterDynamics](https://www.datacenterdynamics.com/en/news/edge-centres-acquires-quadranet/) reporting on the acquisition states Edge Centres' CTO Kiarash Jahangiri was appointed QuadraNet's CEO. **Conflict: a separate search-index summary attributes the 2024 CEO role to Tim Caulfield.** The DCD article returned HTTP 403 on direct fetch, so the conflict could not be adjudicated — **tag: unverified conflict**. |
| **Michael Lowe** | Chief Revenue Officer | Identified as QuadraNet's CRO in an August 2024 LowEndTalk billing-dispute thread, where he responded publicly to the complainant and then went unresponsive. **Community-sourced; current employment status unknown** ([LowEndTalk thread](https://lowendtalk.com/discussion/197081/edge-centres-quadranet-owes-us-13-000)). |
| **Ken Lee** | CFO | Listed as CFO of QuadraNet Enterprises, LLC on a [RocketReach company profile](https://rocketreach.co/quadranet-enterprises-llc-profile_b5cd1cf9f42e0ad1). **Third-party data-broker sourced, not company-confirmed; tenure and current status unverified.** |
| **HostPapa** | Acquirer of QuadraNet's **IPv4 address assets** (early 2025) — **not an equity owner** | HostPapa acquired "over 200,000" IPv4 addresses from QuadraNet; QuadraNet's ARIN profile then fell to roughly **6,656** IPv4 addresses from close to 300,000. Independently corroborated: bgp.he.net now attributes QuadraNet's last originated prefix 198.55.111.0/24 to HostPapa. **This is an asset-stripping signal, not a share transfer** ([LowEndBox report](https://lowendbox.com/blog/hostpapa-acquires-nearly-all-quadranet-ips/)). |

---

## 5. Footprint — sites and datacenters

With the sole exception of QuadraNet DTLA and QuadraNet LAX, **every one of these sites is leased space inside a third-party operator's facility — QuadraNet is not a datacenter owner at those locations.** Present-day operational status of any of them is unverified after the January 2025 multi-day outages and the February 2025 LA evictions.

| Site | Facility operator / owned vs leased | Size & power | Evidence |
|---|---|---|---|
| **LA Downtown HQ — 530 W 6th Street, Los Angeles, CA 90014** (Telecom Center, adjacent to One Wilshire) | **Leased building, self-operated datacenter suites.** Marketed as "privately-owned and operated datacenter space" but QuadraNet is a **building tenant, not the owner** — tenant since 2004, described as the largest tenant, on 6 different floors. **Landlord identity = GAP.** | Company/marketplace listings claim "over 60,000 square feet"; a datacenters.com listing for the same address cites 300,000 sq ft total building with 80,000 sq ft raised floor. **Figures conflict — 60,000 is QuadraNet's own suite claim, the larger numbers are whole-building.** Power = **GAP** (marketing references redundant UPS and ATS units, no numbers). | PeeringDB lists "QuadraNet DTLA" and "Telecom Center LA" as private peering facilities for AS8100. Flagship site; went offline for multiple days from **2025-01-23**; in **February 2025** QuadraNet emailed LA colocation customers giving roughly one week to vacate ([datacenterHawk listing](https://datacenterhawk.com/marketplace/providers/quadranet/530-w-6th-street/141073)). |
| **QuadraNet LAX — 6171 W Century Blvd, Basement, Los Angeles, CA 90045** | Self-operated facility (PeeringDB facility record owned by org "QuadraNet Enterprises LLC"); underlying real estate almost certainly leased — **ownership = GAP**. | **GAP / GAP** — no square footage or power published anywhere reachable. | [PeeringDB facility ID 3825](https://www.peeringdb.com/fac/3825), coordinates 33.945894/-118.393553, last updated 2025-09-26. **Eight networks listed present** including QuadraNet AS8100, ServerMania AS55286, Eonix AS62904, 24Shells AS55081, HostingInside AS9678, rixCloud AS64271, Navice AS137490, Xlitt AS22298 — i.e. QuadraNet was reselling space to other hosts here. |
| **CoreSite LA1 — One Wilshire, Los Angeles, CA** | **Leased** (third-party carrier hotel operated by CoreSite) | **GAP** — QuadraNet's footprint inside One Wilshire is not published. Power **GAP**. | PeeringDB lists "CoreSite - Los Angeles (LA1) One Wilshire" among AS8100's private peering facilities — this is the direct evidence for the One Wilshire claim. Also present at Equinix LA1 ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| **Dallas, TX — 3004 Irving Blvd, Dallas, TX 75247** | **Leased** — PeeringDB shows the Dallas private peering facility as **TierPoint Dallas**. | 68,000 sq ft cited by cloudandcolocation (**likely the whole facility, not QuadraNet's suite**). Power = **GAP on MW**; marketing claims an "industry-leading power-to-space ratio" and 80 Gbps of bandwidth capacity, no absolute figure. | Dallas was among the locations users reported as suffering outages in January 2025 alongside LA and Chicago ([cloudandcolocation](https://cloudandcolocation.com/colocation-provider/quadranet/)). |
| **Miami, FL — 2115 NW 22nd St, Miami, FL 33142** | **Leased** — PeeringDB shows the Miami private peering facility as **South Reach Networks**. | 50,000 sq ft cited by cloudandcolocation (whole-facility figure). Power = **GAP on MW**; facility marketed as Tier III certified and "built to withstand a Category 5 hurricane". | QuadraNet also peers at FL-IX (Miami) at 10G per PeeringDB; Miami consistently appears in QuadraNet's own location lists ([cloudandcolocation](https://cloudandcolocation.com/colocation-provider/quadranet/)). |
| **Atlanta, GA — CoreSite AT1** | **Leased** (space in CoreSite's Atlanta carrier hotel) | **GAP / GAP** | PeeringDB lists "CoreSite - Atlanta (AT1)" as an AS8100 private peering facility. QuadraNet marketed Atlanta dedicated servers — **quadranet.com/atlanta-dedicated-servers now returns HTTP 404 (tested 2026-08-03)** ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| **Chicago, IL — Equinix CH3, Elk Grove Village** | **Leased** (Equinix) | **GAP / GAP** | PeeringDB lists Equinix CH3 Elk Grove Village as an AS8100 private peering facility. **Chicago was among the January 2025 outage locations** ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| **Secaucus, NJ (New York metro) — H5 Data Centers Secaucus and InterServer Teb2** | **Leased** (two separate third-party operators) | **GAP / GAP** | PeeringDB lists both as AS8100 private peering facilities. **This is the physical basis of the "New Jersey" / New-York-metro marketing — there is no Manhattan/NYC-proper facility in any source found** ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| **Seattle area — WowRack, Tukwila, WA** | **Leased** (WowRack third-party facility) | **GAP / GAP** | PeeringDB lists WowRack (Tukwila) as an AS8100 private peering facility; Seattle appears in QuadraNet's own dedicated-server and InfraCloud marketing ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| **Woerden, Netherlands (Amsterdam metro) — HostSlim** | **Leased** (HostSlim third-party facility) | **GAP / GAP** | PeeringDB lists HostSlim (Woerden, NL) as an AS8100 private peering facility — **the only non-US location**. QuadraNet marketed Amsterdam dedicated servers and KVM InfraCloud ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)). |
| **Reston, VA and St. Louis, MO** | **GAP — presumed leased third-party colo, unverified** | **GAP / GAP** | A search-derived summary of the Preqin/Mergr acquisition records lists QuadraNet facilities in "Los Angeles, Atlanta, Chicago, Dallas, Miami, New Jersey, Reston, St. Louis, and Seattle". **Reston and St. Louis do NOT appear in PeeringDB for AS8100 and do not appear on any QuadraNet page reachable — tag: unverified** ([Mergr transaction record](https://mergr.com/transaction/edge-centres-acquires-quadranet)). |

---

## 6. Hardware fleet — vendors with explicit evidence grade

| Vendor | Evidence grade | What is documented |
|---|---|---|
| **Supermicro** | **CONFIRMED — primary / dominant platform. Direct, first-party, verbatim. Not inferred.** | "**1U Supermicro Server – 4x Hot-Swap Bays**" is the chassis line used verbatim across QuadraNet's entire published LA dedicated-server range. Confirmed configurations: Intel Xeon X3450 quad-core 2.66GHz / 16GB DDR3 ECC Registered / 1TB SATA 7.2k; Intel Xeon E3-1241v3 quad-core 3.50GHz / 16GB DDR3 ECC Reg / 1TB; Dual Intel Xeon E5620 quad-core 2.40GHz / 64GB DDR3 ECC Reg / 1TB; Intel Xeon E-2124G quad-core 3.40GHz / 32GB DDR4 ECC Reg / 1TB — all four listed with "Integrated IPMI, KVM over IP, Remote Power Control". QuadraNet's own specials page listed **"Supermicro CSE"** chassis for higher-end bare metal: dual E5-2698 v4 / 256GB RAM / 4× 2TB SSD / 10Gbps uplink / hardware RAID / **Supermicro IPMI** at **$249/mo** (from $299), and dual E5-2650 v2 / 128GB RAM / 4× 2TB SSD / Supermicro IPMI at **$139/mo** (from $199). Also documented: "1U Supermicro Servers with 2x HDD Bays" with hardware RAID-1, 15,000RPM SAS drives on hardware RAID, dual Xeon E5-2620v4 (2× 8-core @2.10GHz) / 32GB DDR4 / 2TB at **$379/mo**, and dual E5-2650 configurations. Source: [LowEndBox exclusive offers, 2020-11-28](https://lowendbox.com/blog/quadranet-exclusive-black-friday-dedi-offers-in-los-angeles/); the quadranet.com/specials_baremetal page returned HTTP 404 on direct test 2026-08-03, content captured via search index. |
| **Dell** | **CIRCUMSTANTIAL / INFERRED — do not state as known.** | **No Dell PowerEdge SKU or generation is named anywhere.** The only Dell signal is that QuadraNet's bare-metal specials page offered out-of-band management as either "**Dell Enterprises iDRAC**" or "Supermicro IPMI" depending on configuration — iDRAC is Dell-exclusive, so at least part of the fleet must be Dell PowerEdge. **Inferred from management-controller naming, not from a chassis or model statement. Specific models, generation and fleet share are GAP. Do not represent Dell share as known** ([quadranet.com/specials_baremetal](https://quadranet.com/specials_baremetal), now HTTP 404). |
| **Adaptec (RAID controllers)** | **CONFIRMED — component level, direct.** | **Adaptec 2405** hardware RAID controller used for RAID-1 in 1U Supermicro 2-bay servers; higher-end bare-metal SKUs advertised customer-selectable "hardware RAID"; 15,000 RPM SAS drives on hardware RAID in some configurations. Named explicitly in QuadraNet promotional spec copy. **Confirms they buy discrete RAID HBAs rather than relying purely on onboard SATA** — relevant if pitching integrated storage platforms to any successor entity ([LowEndBox offer post](https://lowendbox.com/blog/quadranet-30tb-of-bandwidth-on-an-e3-for-only-45-mo-in-los-angeles/)). |
| **AMD** | **UNVERIFIED — third-party marketing mention only, no confirmed SKU.** | A third-party vendor marketplace profile describes QuadraNet bare metal as ranging "from entry-level Intel Xeon/AMD EPYC builds to high-end multi-processor systems with NVMe storage". **No AMD EPYC SKU, generation or price appears in any QuadraNet-authored source. Every QuadraNet-authored configuration recovered is Intel Xeon. Treat AMD EPYC presence as unverified** ([cxponent marketplace profile](https://cxponent.com/marketplace/software/vendor/quadranet)). |
| **HPE** | **GAP** | No HPE, ProLiant or iLO reference found in any QuadraNet spec page, offer post, forum thread, job posting or facility listing across all searches performed. |

**CPU generations observed and what they imply about fleet age:** Nehalem/Lynnfield (X3450), Westmere (E5620), Haswell (E3-1241v3), Ivy Bridge (E5-2650 v2), Broadwell (E5-2620v4 / E5-2698 v4), Coffee Lake (E-2124G). **Nothing newer than Broadwell/Coffee Lake is documented anywhere.** That means the fleet was **already 5–10 years behind current silicon before the company collapsed** — a refresh-starved estate rather than a mid-cycle one.

---

## 7. GPU & AI position

**Hard negative — no GPU, no accelerated compute, no AI product line. This is a confirmed absence, not merely a missing page.**

- **GPU models:** **GAP — zero GPU SKUs found.** No RTX 4000/5000, no L40S, no A100, no H100, no A40/A6000, no Tesla, no MI-series. **Every documented QuadraNet configuration is CPU-only Intel Xeon** with SATA/SAS/SSD/NVMe storage.
- **Pricing:** **GAP — no GPU pricing exists because no GPU product exists.**
- **Evidence:** A dedicated search for QuadraNet GPU/NVIDIA dedicated-server offerings **returned no QuadraNet results at all** — only competing providers (gpu-mart, hostkey, databasemart, hostcolor). QuadraNet's entire product surface (dedicated servers, colocation, InfraCloud KVM cloud, DDoS mitigation) contains **no accelerated-compute line in any recovered page or offer** ([cxponent marketplace profile](https://cxponent.com/marketplace/software/vendor/quadranet)). The most recent CPU generation documented anywhere in the fleet is Broadwell/Coffee Lake.
- **Sales implication:** **There is no AI upsell hook at this account.** QuadraNet never made the transition to accelerated compute, and that failure is itself part of why the business became uncompetitive. **Any AI/GPU opportunity at these addresses belongs to a successor operator** — Edge Centres' remaining US assets, HostPapa which took the IP space, or whoever takes over the LA suites — **not to QuadraNet.**

---

## 8. Customers & network

### Named customers

| Customer | Evidence and grade |
|---|---|
| **HostMantis (Livonia, Michigan)** — shared/VPS/reseller hosting provider | Subject of QuadraNet's own published DDoS-mitigation case study, quoting: "QuadraNet was continuously helpful in assisting us block the attacks and keep our servers online and our clients unaffected." HostMantis also consolidated equipment from two separate locations into a single QuadraNet datacenter. **This is the only named, company-published customer reference found. Note the source page ([blog.quadranet.com case study](https://blog.quadranet.com/case-study-hostmantis-utilizes-quadranet-ddos-solution/)) no longer resolves as of 2026-08-03.** |
| **ServerMania Inc (AS55286)** | Listed in PeeringDB as a network present in the QuadraNet LAX facility (6171 W Century Blvd). **Facility co-tenancy is strong evidence of a colocation/wholesale relationship but is not a contract confirmation — tag: inferred from facility presence** ([PeeringDB fac/3825](https://www.peeringdb.com/fac/3825)). |
| **Eonix N.A. Region (AS62904), 24Shells Inc (AS55081), HostingInside LTD (AS9678), rixCloud Inc (AS64271), Navice Consulting (AS137490), Xlitt (AS22298)** | All listed in PeeringDB as networks present in QuadraNet's own LAX facility alongside AS8100 — **consistent with QuadraNet operating a wholesale/colocation model selling space and transit to other hosting providers. Same caveat: facility co-presence, not confirmed contracts.** This tenant mix (small hosting resellers) is consistent with the Enlyft finding that 82% of QuadraNet's customers have under 50 employees ([PeeringDB fac/3825](https://www.peeringdb.com/fac/3825)). |
| **Sandler Partners** — master agent / channel partner, **not an end customer** | QuadraNet Enterprises announced a strategic partnership with Sandler Partners to give agents support and resources for complex business challenges — a channel/reseller distribution agreement announced via PRWeb and confirmed on Sandler Partners' own site ([Sandler Partners announcement](https://sandlerpartners.com/quadranet-enterprises-announces-a-strategic-partnership-with-sandler-partners/)). |
| **Aggregate customer base (unnamed)** | "QuadraNet has more than **1,000 active customers**" as recorded in coverage of the April 2024 Edge Centres deal; vertical positioning was media, gaming and financial services. **Individual enterprise logos are a GAP — no enterprise customer names were ever published** ([Mergr transaction record](https://mergr.com/transaction/edge-centres-acquires-quadranet)). |

### Network, capacity, peering and IX presence

- **ASN:** **AS8100** — ASName ASN-QUADRANET-GLOBAL, ARIN-allocated **2009-10-22**, org QuadraNet Enterprises LLC. PeeringDB "aka" field reads "FKA AS29761". IRR AS-SET: **AS-SET-QUADRANET**. BGP communities published via RADB include 8100:6666 (blackhole), 8100:1 / 8100:2 / 8100:3 (prepend), 8100:9 (global no-export).
- **CRITICAL — the network has effectively been dismantled:** bgp.he.net shows AS8100 originating just **1 IPv4 prefix (198.55.111.0/24, 256 IPs, flagged IRR Invalid and ROA Signed Invalid, now attributed to HostPapa)** plus 1 IPv6 prefix (2602:fed2:708d::/48, attributed to Free Range Cloud Hosting); **ipinfo.io reports 0 announced IPv4 prefixes and 0 hosted domains**. Historical scale was **~300,000 IPv4 addresses, reduced to ~6,656** after the HostPapa transfer in early 2025.
- **Capacity:** PeeringDB self-reported traffic level **100–200Gbps**, Balanced ratio, North America scope, info_type Content. A third-party marketplace profile claims "over 300Gbps of capacity" — **treat as marketing, unverified**. Historical PeeringDB prefix limits were 18,500 IPv4 / 4,500 IPv6. **Actual present-day usable capacity is a GAP and, given the teardown, likely near zero.**
- **Peering:** Policy Open, locations Not Required, contracts Not Required. **Three internet exchanges, all at 10G with route-server support: Any2West (CoreSite, Los Angeles), Equinix Los Angeles, and FL-IX (Miami).** Thirteen private peering facilities per PeeringDB: CoreSite LA1 One Wilshire, Equinix LA1, QuadraNet DTLA, QuadraNet LAX, Telecom Center LA, CoreSite Atlanta AT1, Equinix CH3 Elk Grove Village, H5 Data Centers Secaucus, InterServer Teb2 Secaucus, South Reach Networks Miami, TierPoint Dallas, WowRack Tukwila, and HostSlim Woerden NL.
- **Current BGP relationships are minimal:** upstream/transit from **AS29802 (Hivelocity)**; peer **AS35916 (Multacom Corporation** — the LA provider Edge Centres acquired in July 2023, **confirming intra-group interconnection**). Historically also received from AS7393 (Cybercon) and AS6424 (Edgoo Networks), and provided transit to AS915 (Siligom USA). **Downstream count is now zero** ([PeeringDB asn/8100](https://www.peeringdb.com/asn/8100)).

---

## 9. Political & public record

Named principals only. Every item tagged.

- **Ilan Mishan (Founder & CEO)** — **[public-record]**: FEC individual contribution record — contributor "**MISHAN, ILAN**", **Tarzana, CA**; employer listed as "**QUADRANET INC**"; occupation listed as "**SYSTEM ENGINEER**"; amount **$250.00**; contribution receipt date **2012-10-03**; recipient committee "**ROMNEY FOR PRESIDENT INC.**" Retrieved from the FEC's own Schedule A API. **This is the sole FEC record surfaced for this name.** Note: the self-reported occupation ("System Engineer") differs from his executive title, which is common in FEC self-reporting and **does not by itself indicate a different individual** — the identity match rests on the QuadraNet employer field plus the Tarzana, CA location, which matches the Tarzana address separately associated with QuadraNet Enterprises LLC in a RocketReach profile ([FEC Schedule A API](https://api.open.fec.gov/v1/schedules/schedule_a/?api_key=DEMO_KEY&contributor_name=Ilan+Mishan) · [FEC individual-contributions search](https://www.fec.gov/data/receipts/individual-contributions/?contributor_name=Ilan+Mishan)).
- **Michael Lowe (CRO), Ken Lee (CFO), Kiarash Jahangiri (post-acquisition CEO), Jonathan Eaves (Edge Centres founder)** — **[gap]**: **no FEC individual contribution records were searched or found for these individuals.**
- **QuadraNet Enterprises LLC / QuadraNet Inc as legal entities** — **[gap]**: **no lobbying registrations, PAC affiliations, government contracts or other political-exposure records were located.**
- **Consistency note:** all political material in this file comes from public records only (FEC Schedule A API, ASIC published notices, state business registries) and is tagged `public-record`, `unverified` or `gap`. Where nothing exists, that is stated plainly rather than characterised as "no donations" — for the four names above, this is a **not-searched / not-found** result, not a proven negative.

---

## 10. Public contact channels

**Public-source only. No personal mobile numbers and no private addresses are recorded in this file. GAP is shown where no published channel exists.** Given the company's state, most of these are degraded or dead — each is flagged.

| Channel | Value | Source |
|---|---|---|
| Sales email | **sales@quadranet.com** — **CAUTION**: surfaced from the search-index snippet of QuadraNet's contact page. **That hostname no longer resolves (NXDOMAIN observed 2026-08-03), so deliverability is unverified and likely broken.** | [blog.quadranet.com/contact](https://blog.quadranet.com/contact) |
| Main phone (toll-free) | **(888) 578-2372**; a second number, **+1 833-471-7100**, appears in directory listings for pricing enquiries. **Neither was dial-verified; given the company's state, assume both may be dead.** | [Yelp business page](https://www.yelp.com/biz/quadranet-los-angeles) |
| HQ / mailing address | **530 W 6th Street, Penthouse, Los Angeles, CA 90014** (Telecom Center building, downtown LA) | [Yelp business page](https://www.yelp.com/biz/quadranet-los-angeles) |
| Support | Marketed as 24/7/365 support with a "24x7 NOC Task Force"; status page historically at status.quadranet.com. **No direct support email or NOC phone number was published in any reachable source — GAP.** | [StatusGator service page](https://statusgator.com/services/quadranet) |
| Named staff — **Ilan Mishan, Founder & CEO** | Public routes only: LowEndBox interview, HostingAdvice CEO feature, Equilar ExecAtlas bio page (people.equilar.com/bio/person/ilan-mishan-quadranet/28399146), Crunchbase person profile. A RocketReach profile associates him with NEO Investment Group LLC as Managing Partner — **unverified**. **No direct email or phone confirmed in public sources — GAP.** | [HostingAdvice CEO feature](https://www.hostingadvice.com/blog/quadranet-hosting-solutions-help-businesses-evolve/) |
| Named staff — **Michael Lowe, Chief Revenue Officer** | Identified in an August 2024 LowEndTalk billing-dispute thread where he responded publicly then went unresponsive. **Community-sourced. No direct contact details published; current employment status unknown — GAP.** | [LowEndTalk thread](https://lowendtalk.com/discussion/197081/edge-centres-quadranet-owes-us-13-000) |
| Named staff — **Ken Lee, CFO** | Listed as CFO on a third-party data-broker company profile. **Not company-confirmed; tenure and current status unverified.** | [RocketReach company profile](https://rocketreach.co/quadranet-enterprises-llc-profile_b5cd1cf9f42e0ad1) |
| Named staff — **Kiarash Jahangiri, CEO (post-acquisition)** | Edge Centres CTO reported as appointed QuadraNet CEO after the April 2024 acquisition. **Conflicting report names Tim Caulfield — unresolved. No direct contact route found — GAP.** | [DataCenterDynamics](https://www.datacenterdynamics.com/en/news/edge-centres-acquires-quadranet/) |
| Parent company LinkedIn | **https://www.linkedin.com/company/edgecentres** — the parent's page. **QuadraNet's own LinkedIn company page URL = GAP; it was not directly verified and the slug will not be guessed.** Third-party staff-directory aggregators exist at contactout.com/company/quadranet-enterprises-llc-1290391 and signalhire.com/companies/quadranet-enterprises-llc. | [Edge Centres LinkedIn](https://www.linkedin.com/company/edgecentres) |
| Company website (degraded) | **https://quadranet.com** — serves only a logo stub as of 2026-08-03. **Directly observed: /dedicated-servers HTTP 404, /specials_baremetal HTTP 404, /atlanta-dedicated-servers HTTP 404; blog.quadranet.com fails DNS resolution (NXDOMAIN); squiggly.quadranet.com refuses TCP connections (ECONNREFUSED to 198.55.111.55 — an address inside the /24 that now belongs to HostPapa).** | [quadranet.com](https://quadranet.com) |

---

## 11. Supermicro sales angle

### Classification: **NOT A FORWARD-SELLING TARGET** — credit risk and asset tracking only

Supermicro is a **confirmed, first-party incumbent platform** at this account — but the account itself has collapsed. The pre-sales warning is the whole angle:

> Sold by VSS Capital Partners to Edge Centres on **2024-04-08**; the Australian parent **Edge Centres Pty Ltd (ACN 647 483 476) had a liquidator appointed 2025-06-16** ([ASIC notice](https://publishednotices.asic.gov.au/browsesearch-notices/notice-details/Edge-Centres-Pty-Ltd-647483476/8f031111-abd0-4700-9a06-56f8b484a5e2)); **200,000+ IPv4 addresses sold to HostPapa in early 2025** (from ~300,000 down to ~6,656); **multi-day outages across LA / Chicago / Dallas from 2025-01-23**; **LA colocation customers told in February 2025 to vacate within roughly one week**. Directly tested 2026-08-03: quadranet.com serves only a logo stub, /dedicated-servers, /specials_baremetal and /atlanta-dedicated-servers all return HTTP 404, blog.quadranet.com is NXDOMAIN, squiggly.quadranet.com refuses connections, and AS8100 announces effectively no IPv4.

**There is no AI upsell hook** — QuadraNet never had a single GPU product, so the usual accelerated-compute wedge does not exist here. **The only realistic commercial angle is asset succession**: who now controls the physical Supermicro estate in the LA suites, and whether the successor (Edge Centres' remaining US assets, HostPapa which took the IP space, or whoever takes over the suites) becomes a new account in its own right.

**Do not spend selling hours, and do not extend credit terms in any form, until the legal status of the US entity is established.** If the account is registered at all, register it as an asset-tracking record with the credit-risk note attached.

### The qualifying question to ask on first contact

> **"Which legal entity currently controls the datacenter suites — and the equipment inside them — at 530 W 6th Street and 6171 W Century Blvd?"**

**This question is put to the asset successor, not to QuadraNet.** It is the single question that decides whether there is anything here at all.

### Rule 8 distributor caution — read before anyone dials

QuadraNet ran a sizeable fleet across roughly a dozen facilities, an ASN with ~300,000 IPv4 addresses at peak, and 1,000+ active customers — **yet it has never once appeared in the CRM (verified 2026-08-03: no lead, no account, no do-not-call record).** The same pattern holds across the whole bare-metal layer studied. The only reasonable inference is that **these providers bought their servers through distribution, not direct from the manufacturer.**

**Under Rule 8, a distributor may cross territory boundaries, but only with advance approval and a "do not call" flag applied.** So the sequence is fixed: **confirm the channel position first** — establish whether QuadraNet (or its successor) is already an existing account of a distributor and obtain the cross-territory approval plus do-not-call flag — **then register the lead, and only then make contact.** Reversing that order creates channel conflict. For this provider specifically, the channel check is cheap and should happen anyway, because it may also reveal who holds the outstanding receivable and therefore who controls the hardware.

---

## 12. Verification appendix

### 12.1 Single-source claims — re-verify before quoting

| Claim | Sole source | Risk |
|---|---|---|
| Post-acquisition CEO is **Kiarash Jahangiri** | [DataCenterDynamics](https://www.datacenterdynamics.com/en/news/edge-centres-acquires-quadranet/) report | **A separate search summary names Tim Caulfield instead; the DCD article returned HTTP 403 on direct fetch so the conflict could not be adjudicated. Unresolved.** |
| **Ken Lee, CFO** | [RocketReach company profile](https://rocketreach.co/quadranet-enterprises-llc-profile_b5cd1cf9f42e0ad1) | **Third-party data-broker source, not company-confirmed; tenure and current status unverified.** |
| **Reston, VA and St. Louis, MO** facilities | Preqin/Mergr acquisition-record summary | **Absent from PeeringDB and from every QuadraNet-authored page. Unverified.** |
| **HostMantis** as a named customer | QuadraNet's own case study | **Company-published and therefore first-party, but the source page (blog.quadranet.com) no longer resolves (NXDOMAIN, 2026-08-03) — the text was recovered via search index.** |
| **Dell** presence in the fleet | The "Dell Enterprises iDRAC" OOB-management option on one specials page | **Inference from a management-controller name only. No PowerEdge model, generation or share. Must not be stated as a known vendor fact.** |
| **AMD EPYC** presence | [cxponent marketplace profile](https://cxponent.com/marketplace/software/vendor/quadranet) marketing copy | **Third-party marketing, not a QuadraNet spec page. Every QuadraNet-authored configuration recovered is Intel Xeon. Unverified.** |

### 12.2 Conflicting third-party estimates — shown side by side, not resolved

**Headcount**

| Source | Figure |
|---|---|
| RocketReach | **28** (third-party estimate) |
| Crunchbase / ZoomInfo / PitchBook / D&B | **No usable figure** — all paywalled or HTTP 403 |

**Single third-party source, no cross-corroboration. Post-liquidation headcount is almost certainly far below 28 — GAP.** Separately, Enlyft's profiling of QuadraNet's *customer base* (not its own staff) indicates its customers skew small: 82% under 50 employees, 11% mid-size, 6% over 1,000 employees.

**Revenue**

| Source | Figure |
|---|---|
| RocketReach | **$8.8M annual** (third-party estimate, vintage unknown) |
| Any audited or disclosed figure | **None exists** — private company, VSS sale price never disclosed |

**Vintage unknown, almost certainly pre-2024, and no longer representative after the 2025 asset sales, customer evictions and parent liquidation. Do not present as fact.**

**LA square footage — two different things being measured**

| Source | Figure | What it measures |
|---|---|---|
| QuadraNet / marketplace listings | "over **60,000 sq ft**" | QuadraNet's own **suite** claim |
| datacenters.com (same address) | **300,000 sq ft** total building, **80,000 sq ft** raised floor | **Whole building** |

**These are not reconcilable and should not be mixed.** The same pattern applies to Dallas (68,000 sq ft) and Miami (50,000 sq ft) — both are facility totals, not QuadraNet's occupied footprint.

**Network capacity**

| Source | Figure |
|---|---|
| PeeringDB self-report | **100–200 Gbps** traffic level |
| Third-party marketplace profile | "over **300 Gbps** of capacity" — **marketing, unverified** |

**Different measurements; and both are historical — actual present-day usable capacity is a GAP and likely near zero given the network teardown.**

### 12.3 Open gaps

1. **California SOS entity/file number, formation date, current status and agent for service of process** — all three access routes blocked (bizfileonline.sos.ca.gov exposes only opaque image-API endpoints; Bizapedia served a security interstitial; OpenCorporates served a HAProxy CAPTCHA, not bypassed). Also unresolved: whether "QuadraNet, Inc." is a separate legal entity from "QuadraNet Enterprises, LLC" or a legacy/DBA name. No NV, UT, WA or DE registration was located.
2. **Current legal and operating status of the US entity after the parent's collapse** — whether the US "Edge Centres LLC" and QuadraNet Enterprises LLC are in receivership, dissolved, sold on, or still nominally trading. **The liquidator's name and the disposition of the US assets are GAP.**
3. **Power capacity at every single site** — no MW, kW, amperage, UPS or generator figure is published for any QuadraNet facility. Marketing references "redundant UPS & ATS units" and an "industry-leading power-to-space ratio" with no absolute numbers.
4. **Server count, rack count and cabinet count** — never published. Only indirect proxies exist (1,000+ customers pre-acquisition; a LowEndBox estimate that the residual 6,656 IPs would support roughly 1,300 customers at 5 IPs each, implying the surviving fleet is small).
5. **Dell fleet detail** — no PowerEdge model, generation or share of fleet; existence inferred solely from the "Dell Enterprises iDRAC" OOB option.
6. **AMD EPYC presence** — asserted only in third-party marketplace marketing copy; unverified.
7. **GPU/accelerated compute** — a **hard negative** rather than a data gap, but restated for clarity: no GPU product line, no NVIDIA/AMD accelerator SKU, no AI/HPC offering anywhere.
8. **Post-acquisition CEO identity** — Kiarash Jahangiri vs Tim Caulfield conflict unresolved (DCD article HTTP 403).
9. **Named enterprise customers** — only one company-published case study exists (HostMantis, and its source page is now NXDOMAIN). The seven networks co-present in QuadraNet LAX per PeeringDB are inferred wholesale/colo relationships, not confirmed contracts. The claimed media/gaming/financial-services verticals have no named logos.
10. **Headcount and revenue are third-party estimates only** (28 employees, $8.8M revenue via RocketReach, vintage unknown). Crunchbase, ZoomInfo, PitchBook, D&B and Bloomberg were all paywalled or returned HTTP 403.
11. **QuadraNet's own LinkedIn company page URL** — not directly verified, so not reported. Only the parent's page was confirmed.
12. **Reston VA and St. Louis MO facilities** — appear in acquisition-record summaries only; absent from PeeringDB and every QuadraNet-authored page.
13. **Ownership/landlord of the 530 W 6th Street Telecom Center building**, and the lease terms and expiry for QuadraNet's suites there and at 6171 W Century Blvd.
14. **Who now controls the physical Supermicro estate in the LA suites** after the February 2025 colocation evictions and the parent's liquidation. **This is the only realistic commercial angle at this account and it cannot be resolved from public sources.**
15. **Historical QuadraNet job postings could not be retrieved** (a LowEndBox analysis noted the careers page still carried 2019-vintage listings as a decay signal), so no hiring-manager names or hardware-purchasing contacts were recoverable from job ads.

### 12.4 Tool and access limitations affecting this file

- **HTTP-blocked sources:** WebHostingTalk (403), datacenters.com (403), ZoomInfo (403), Crunchbase (403), HostingAdvice (403), DataCenterDynamics (403), bizfileonline.sos.ca.gov (403), Bizapedia / OpenCorporates (security check / CAPTCHA, not bypassed). **Any finding that depends on these is tagged in this file as community-sourced, secondary-capture or third-party estimate.**
- **JavaScript-only interfaces that cannot be queried programmatically:** fec.gov individual-contribution search and OpenSecrets donor search. The FEC record for Ilan Mishan was obtained via the FEC's own Schedule A API and is therefore solid; the absence of records for the other four named individuals is a **not-searched/not-found result, not a proven negative**.
- **OAuth-gated connectors:** the ZoomInfo MCP connector available in this environment requires authorization that could not be completed in a non-interactive session. **Authorizing it (via claude.ai connector settings, or /mcp in an interactive session) would likely close the headcount, revenue and named-contact gaps on a re-run.**
