# EU Cybersecurity Regulatory Brief — Week ending Monday, 26 October 2026

Prepared by: EU Cybersecurity Regulatory Intelligence (automated weekly)
Coverage window: 20–26 October 2026 (and in-force items where materially relevant)
Classification labels used: **In force** · **Transposing** · **Proposed** · **Guidance**

---

## Executive summary

- **Council agrees Omnibus VII mandate (21 Oct 2026)** — the Council replaced the Commission's proposed EU-level single incident-reporting entry point with a **national entry point in each Member State plus an EU-level information point**, and endorsed moves toward a harmonised cross-border incident-notification framework. This reshapes how NIS2, DORA, GDPR, eIDAS, CER and CRA reporting will converge. **Proposed** ([Consilium press release](https://www.consilium.europa.eu/en/press/press-releases/2026/10/21/digital-rulebook-council-agrees-position-to-simplify-data-protection-privacy-and-cyber-reporting-rules/)).
- **CSA2 (Cybersecurity Act revision) rapporteur positions published (8 Oct 2026)** — ITRE rapporteur Markéta Gregorová (Greens/EFA, CZ) tabled her draft reports on both CSA2 and the targeted NIS2 amendments: **mandatory certification by default**, a new mandatory cyber-posture certification scheme for all NIS2 essential entities within 12 months, individual (not country-level) assessments of high-risk suppliers, and a single reporting entry point across NIS2/DORA/GDPR/eIDAS/CRA/CER. **Proposed** ([Agence Europe](https://agenceurope.eu/en/bulletin/article/13955/9/rapporteur-on-cybersecurity-act-2-proposes-mandatory-certification-by-default-to-meps), [EUR-Lex CELEX:52026PC0011](https://eur-lex.europa.eu/legal-content/EN/AUTO/?uri=CELEX%3A52026PC0011)).
- **Germany signals NIS2 enforcement wave** — BSI announced a **Q4 2026 registration-enforcement initiative** and **individual audits from Q1 2027**, after only ~20,373 of an expected ~30,000 entities registered by 30 September 2026. **Transposing / enforcement** ([Sightadel](https://www.sightadel.com/en/news/nis2-bsi-announces-enforcement-and-first-audits/), [ad-hoc-news](https://www.ad-hoc-news.de/wirtschaft/nis2-pflichten-bsi-plant-ab-dem-vierten-quartal-2026-durchsetzung/70395716)). Romania's DNSC issued the **first NIS2 sanction** (≈€10,000) on 30 September 2026 ([NNDKP](https://privacyoutloud.ro/2026/10/01/romanian-cybersecurity-authority-announces-first-sanction-for-failure-to-comply-with-nis2-registration-notification-requirements/)).
- **CRA Single Reporting Platform v1.2.1 released (20 Oct 2026)** — ENISA updated the SRP (Secondary Assigned Representatives invitation flow). CRA Art. 14 reporting obligations have been live since 11 September 2026; manufacturer awareness remains uneven, with only Finland, Hungary and Malta having adopted full national CRA implementation acts to date. **In force / Guidance** ([ENISA SRP](https://www.enisa.europa.eu/topics/product-security/vulnerability-services/eu-incident-response-and-cyber-crisis-management/single-reporting-platform-srp), [CRA Response Center](https://cra-response-center.com/news/2026-10-19-cra-implementation-member-states/)).
- **PQC drumbeat accelerates ahead of the 31 Dec 2026 roadmap deadline** — Germany published the joint BMDS/BMI/BSI national PQC implementation guideline (12 Oct 2026); ENISA ran its Estonia-focused PQC webinar on 22 Oct 2026. **Guidance** ([BSI](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Krypto/Leitlinie-Umstellung-PQC.html), [ENISA event](https://www.enisa.europa.eu/events/enisa-pqc-webinars-how-is-estonia-approaching-the-post-quantum-cryptography-transition)).
- **Operational incident of the week** — a 21 Oct 2026 joint statement (DG CNECT, ENISA, CERT-EU, Europol EC3, CSIRTs Network) called for immediate patching of **two critical PHP RCE vulnerabilities (CVE-2026-109618, CVE-2026-109619)**. This is the first high-profile stress test of CRA Art. 14 reporting flows ([ENISA](https://www.enisa.europa.eu/news/joint-statement-on-critical-php-vulnerabilities)).
- **ENISA SBOM Technical Advisory published (22 Oct 2026)** — new SME-oriented guidance aligned with the ENISA Secure-by-Design and Default Playbook, directly relevant for CRA Annex I §2 vulnerability-handling and NIS2 Art. 21(d) supply-chain controls. **Guidance** ([ENISA publication](https://www.enisa.europa.eu/publications/enisa-technical-advisory-for-software-bill-of-materials)).

---

## 1. NIS2 Directive — Directive (EU) 2022/2555

### Discussion
- The **Council's Omnibus VII mandate (21 Oct 2026)** is the week's defining signal for NIS2 reporting mechanics: Member States preferred national entry points over an EU-level single point, with an added EU information point to support cross-border notification harmonisation ([Consilium](https://www.consilium.europa.eu/en/press/press-releases/2026/10/21/digital-rulebook-council-agrees-position-to-simplify-data-protection-privacy-and-cyber-reporting-rules/)). The Parliament's position (via Gregorová's CSA2/NIS2 reports, 8 Oct) differs: a **single EU reporting entry point** across NIS2/DORA/GDPR/eIDAS/CRA/CER, with national CSIRTs still receiving notifications ([Agence Europe](https://agenceurope.eu/en/bulletin/article/13955/9/rapporteur-on-cybersecurity-act-2-proposes-mandatory-certification-by-default-to-meps)). Trilogues are expected in 2027.
- Rapporteur Gregorová additionally proposes **ransomware-specific reporting** and clearer scope/definition language in the targeted NIS2 amendments bundled with CSA2.

### Implementation agenda
- **In force / Transposing** — Germany (NIS2UmsuCG applied 6 Dec 2025), Italy (D.Lgs. 138/2024 applied 16 Oct 2024), Austria (NISG 2026 applied 1 Oct 2026), Netherlands (Cbw applied 15 Aug 2026) ([Dazr compliance review, 19 Oct 2026](https://compliance.dazr.eu/news/nis2-transposition-october-2026); [Linklaters, Oct 2026](https://www.linklaters.com/insights/blogs/digilinks/2026/october/the-netherlands-new-nis2-cyber-law-finally-implemented)).
- **Infringement proceedings** — Ireland, Spain, France, Netherlands referred to the CJEU on 8 Jul 2026; the Netherlands has since legislated but the referral stands.
- **Germany, enforcement timeline** — BSI (Tagesspiegel-cited plan, picked up 9 Oct 2026): Q4 2026 start registration-enforcement outreach; Q1 2027 begin targeted individual-entity audits under §61(1) BSIG; general evidence-request power under §61(3) BSIG from Dec 2028. Fines: up to €500,000 for registration breaches; up to €7 million for Art. 21 breaches by important entities ([Sightadel](https://www.sightadel.com/en/news/nis2-bsi-announces-enforcement-and-first-audits/)).
- **Romania — first NIS2 sanction** (DNSC, 29 Sep 2026, announced 30 Sep 2026): ~€10,000 against a central-public-administration body for missed registration notification.

### Organizational impact
- **Essential and important entities** in transposed MS — verify registration status now; German-headquartered groups face the clearest enforcement runway. Multi-country operators must map **differing national registration portals, deadlines and fines**.
- **Groups spanning NIS2 + DORA + CER + CRA** — build a **single operational register of regulated entities and reporting obligations**; both Council and Parliament are moving to harmonised reporting mechanics.
- **SMEs** classified as important entities — late registration is no longer low-risk after Romania's €10,000 sanction and Germany's upcoming audits.

---

## 2. DORA — Regulation (EU) 2022/2554

### Discussion
- No DORA-specific legislation this week. The **Omnibus VII** mandate indirectly affects DORA reporting mechanics (national entry point design).
- The **ESAs 2026 Joint Committee work programme** frames 2026 as the **first full oversight cycle for Critical ICT Third-Party Providers (CTPPs)**: designation by end-2025, individual annual oversight plans, multi-annual strategic plan, and first on-site examinations ([ESMA JC 2025 33](https://www.esma.europa.eu/sites/default/files/2025-10/JC_2025_33_Joint_Committee_of_the_European_Supervisory_Authotities_2026_Work_programme.pdf)).

### Implementation agenda
- **In force** since 17 Jan 2025.
- **Guidance** — ESAs' DORA major-incident reporting **Operational Instructions** (16 Sep 2026) remain the most recent operational benchmark; competent authorities continue to apply ITS 2025/302 and RTS 2025/301, RTS 2024/1772 ([ESMA](https://www.esma.europa.eu/sites/default/files/2026-09/DORA_Incident_reporting_-_Operational_instructions.pdf)).
- **Register of information** — EBA acceptance rate rose from 40% (2025) to **94% (2026)**; AFM flagged persistent gaps in ICT policies, preventive controls, detection/reporting and subcontracting ([AFM DORA update 7, Aug 2026](https://www.afm.nl/~/profmedia/files/publicaties/2026/dora-update-7-en.pdf); [Norton Rose Regulation Tomorrow](https://www.regulationtomorrow.com/2026/08/afm-update-on-dora/)).
- **EU-SCICF** — Oversight Forum continues coordination testing with EU-CyCLONe, G7 CEG and CERT-EU for the pan-European Systemic Cyber Incident Coordination Framework.

### Organizational impact
- **Financial entities** — expect a wave of **CTPP-driven information requests** as Joint Examination Teams begin examinations; prepare sub-contracting-chain visibility and concentration-risk evidence.
- **CTPPs** should finalise **Lead Overseer engagement protocols** and designate the DORA Art. 31 contact point; non-designated providers servicing CTPPs should prepare for upstream information requests.
- **Insurance intermediaries with mixed activities** — reaffirm proportionality analysis per ESAs guidance (AFM Update 7).
- **Priority 2026 audit themes**: logical access, patch and vulnerability management, incident-detection coverage, group-level mapping of DORA policies to each licensed entity.

---

## 3. eIDAS 2.0 — Regulation (EU) 2024/1183 and EUDI Wallet

### Discussion
- No new ARF release this week. Discussion continues upstream: **Topic AA refinement round v0.8** (SCA / payments, 14 Oct 2026) and prior topics (AB Digital Signature v1.1 on 16 Sep; Topic E v1.3 on 23 Sep) are informative working documents, not adopted requirements ([GitHub releases](https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/releases); [EUDI ARF Discussion Topics index](https://atlas.credimi.io/documents/EUDI-ARF-DISCUSSION-TOPICS/)).
- No new EUR-Lex eIDAS implementing/delegated acts in the past 7 days.

### Implementation agenda
- **In force** — Regulation (EU) 2024/1183 and the first wave of implementing regulations (CIR 2024/2977, /2979, /2980, /2982 and /2025/848) remain the operative baseline. **Guidance** — ARF v3.0.0 (23 Jul 2026) remains the current reference ([v3.0.0 release notes](https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/releases/tag/v3.0.0)).
- Amending CIRs **2026/1730, /1731, /1735** (adopted earlier in 2026) are not yet consolidated in EUR-Lex; the ARF continues to reference original acts.
- Member State wallet deployment deadline remains **by end of 2026** per Regulation (EU) 2024/1183 Art. 5a(1).

### Organizational impact
- **Relying parties** — plan Relying Party registration (ARF §3.11.2 / Topic 44) and LoTE + Trusted List retrieval.
- **QTSPs** — confirm FCAF conformance readiness (ARF §7.5, [conformance.eudi.dev](https://conformance.eudi.dev)).
- **Payments / SCA** — track Topic AA; expect formalisation in a future ARF v3.1.
- **Member States** behind on wallet pilots should expect Commission pressure as the end-2026 deadline approaches.

---

## 4. Cybersecurity Act 2 — COM(2026)11 (proposal to repeal Regulation (EU) 2019/881)

### Discussion
- Rapporteur **Markéta Gregorová** (ITRE, Greens/EFA, CZ) tabled her draft report on 8 Oct 2026. Headline amendments:
  - **Mandatory certification by default** across the European Cybersecurity Certification Framework (ECCF).
  - **New certification scheme on cyber posture of NIS2 essential entities**, with a 12-month development window and a **presumption of NIS2 compliance** for certified entities.
  - **Individual (evidence-based) assessment of high-risk suppliers** rather than country-level designation; shortened phase-out timelines in mobile networks (24 months); new **Annex 2A** adding inverters, smart meters, home routers, port cranes and medical imaging devices to covered equipment.
  - **FOSS communities** explicitly exempted from "commercial supplier" classification.
  - **Single reporting entry point** aligning NIS2/DORA/GDPR/eIDAS/CER/CRA notification mechanics ([Agence Europe, 8 Oct 2026](https://agenceurope.eu/en/bulletin/article/13955/9/rapporteur-on-cybersecurity-act-2-proposes-mandatory-certification-by-default-to-meps); [RIPE Labs, Oct 2026](https://labs.ripe.net/author/romain-bosc/dna-progress-nis2-amendments-csa-20-and-more-eu-regulation-update-october-2026/)).
- **Council** position (still forming) tilts the other way: Member State influence over high-risk-supplier designation, more flexible/risk-based phase-outs, and the Omnibus VII preference for **national rather than EU-level** incident reporting ([Consilium](https://www.consilium.europa.eu/en/press/press-releases/2026/10/21/digital-rulebook-council-agrees-position-to-simplify-data-protection-privacy-and-cyber-reporting-rules/)).
- Expect **trilogues in 2027** once both institutions finalise mandates.

### Implementation agenda
- **Proposed** — COM(2026)11 (CELEX:52026PC0011) published 20 Jan 2026 ([EUR-Lex](https://eur-lex.europa.eu/legal-content/EN/AUTO/?uri=CELEX%3A52026PC0011); [EP briefing EPRS_BRI(2026)789345](https://www.europarl.europa.eu/thinktank/en/document/EPRS_BRI(2026)789345)). The proposal **repeals** Regulation (EU) 2019/881 and reforms the ECCF; it also expands ENISA's mandate with additional operational tasks and increased financial/human resources, and widens ECCF scope to cover **ICT products, services, processes, managed security services, and the cyber posture of entities**.
- **In parallel** — targeted amendments to **NIS2** on scope, definitions, ransomware reporting and cross-border supervision are bundled with CSA2.

### Organizational impact
- **NIS2 essential entities** — assume a **cyber-posture certification obligation is realistic in 2–3 years**; inventory evidence for governance, risk management, supply chain and reporting readiness.
- **Vendors to EU critical infrastructure** — prepare for **individual** supplier risk assessments; map licensing, white-label and intermediary relationships (anti-circumvention amendments).
- **MSSPs** — the ongoing ENISA EU MSS certification consultation remains relevant; expect formalisation under CSA2.
- **Conformity assessment bodies** — expect reduced duplication across CRA / NIS2 / CSA2, but transition rules will matter (track Articles 71–78).

---

## 5. Quantum / Post-Quantum Cryptography

### Discussion
- **EU Coordinated Implementation Roadmap for the Transition to Post-Quantum Cryptography** (NIS Cooperation Group, June 2025) remains the authoritative EU-level framing ([EC digital-strategy page](https://digital-strategy.ec.europa.eu/en/policies/post-quantum-cryptography)).
- **Germany** published the **joint BMDS/BMI/BSI national PQC implementation guideline** on 12 Oct 2026, aligning the national timeline with the EU roadmap ([BSI](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Krypto/Leitlinie-Umstellung-PQC.html)).
- **ENISA PQC webinar series** — Estonia-focused session on 22 Oct 2026 (cryptographic inventory, phased transition planning) ([ENISA event](https://www.enisa.europa.eu/events/enisa-pqc-webinars-how-is-estonia-approaching-the-post-quantum-cryptography-transition)).
- **EUCC cryptography guidance** — the ECCG Agreed Cryptographic Mechanisms **version 3** is in advanced review (public review closed end of July 2026) and includes a dedicated analysis of **PQC/traditional hybridisation** ([ENISA Certification](https://certification.enisa.europa.eu/publications/eucc-guidelines-cryptography_en)).

### Implementation agenda
- **Guidance** — EU Roadmap milestones:
  - **31 Dec 2026** — Member State national PQC roadmaps in place; planning underway for high- and medium-risk use cases.
  - **21 Dec 2030** — High-risk use cases migrated (energy, water, health, finance, transport); quantum-safe software/firmware upgrades by default.
  - **31 Dec 2035** — All migrations completed across risk levels ([ENISA/EC presentation](https://www.enisa.europa.eu/sites/default/files/2026-04/NEW-Fabiana_Da_Pieve_EC-for-sharing.pdf)).
- **CRA linkage** — the Roadmap hooks explicitly into CRA Annex I essential cybersecurity requirements and lifecycle vulnerability handling.

### Organizational impact
- **Critical infrastructure operators** (NIS2 Annex I) — build cryptographic inventories now; set a 2029 interim target so 2030 is achievable.
- **ICT and product manufacturers (CRA scope)** — plan **quantum-safe upgrade paths by default by 2030**; prefer hybrid PQC/classical schemes; design crypto-agility into product update frameworks.
- **QTSPs** — align with ACM v3 once adopted; track EUCC guidance for PQC-eligible algorithms.
- **Financial entities (DORA)** — map PQC exposure in third-party contracts and in ICT risk-management policies ahead of 2027 oversight examinations.

---

## Adjacent instruments (material items this week)

- **Cyber Resilience Act — Regulation (EU) 2024/2847 — In force (reporting)**
  - **CRA SRP v1.2.1** released 20 Oct 2026 (changed Secondary Assigned Representatives invitation flow) ([ENISA SRP](https://www.enisa.europa.eu/topics/product-security/vulnerability-services/eu-incident-response-and-cyber-crisis-management/single-reporting-platform-srp)).
  - Reporting deadlines: **24h early warning / 72h notification / 14 days final (vulns) or 1 month final (incidents)** ([EC CRA reporting policy](https://digital-strategy.ec.europa.eu/en/policies/cra-reporting)).
  - National implementation status (as of 19 Oct 2026): **adopted** in Finland (Act 439/2026), Hungary (Act CXXXV/2025), Malta (LN 238/2026); **adopted but not yet promulgated** in Germany (Bundestag 15 Oct 2026, Bundesrat pending); in parliament in the Netherlands, France, Slovakia; government drafts in Italy and Denmark; early stage in Czechia, Spain, Sweden ([CRA Response Center](https://cra-response-center.com/news/2026-10-19-cra-implementation-member-states/)).
  - **ENISA SBOM Technical Advisory** (22 Oct 2026) materially supports Annex I §2 vulnerability handling ([ENISA publication](https://www.enisa.europa.eu/publications/enisa-technical-advisory-for-software-bill-of-materials)).
  - **Operational test**: PHP CVE-2026-109618 / -109619 joint statement (21 Oct 2026) is the first high-profile incident likely to drive Art. 14 reporting volumes.

- **AI Act — Regulation (EU) 2024/1689 — In force (phased)**
  - No new cybersecurity-specific developments this week. Reminder: **Annex III high-risk** systems apply **2 Dec 2027**; **Annex I product-integrated** systems apply **2 Aug 2028**. Article 15 cybersecurity obligations (data/model poisoning, adversarial examples, confidentiality attacks) remain stable ([AI Act Service Desk Art. 15](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-15); [EC AI Act timeline](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)).

- **CER Directive — Directive (EU) 2022/2557 — Transposing** — no new EU-level development; NL Wwke entered into force 15 Aug 2026 alongside Cbw. Overlap with NIS2 Art. 21 and DORA remains the main operational burden.

- **GDPR + Omnibus VII — In force / Proposed** — Council general approach **21 Oct 2026** covers GDPR simplification and e-Privacy cookies modernisation. GDPR security obligations unchanged in substance, but the **single reporting pathway** will touch Art. 33 breach-reporting mechanics ([Consilium](https://www.consilium.europa.eu/en/press/press-releases/2026/10/21/digital-rulebook-council-agrees-position-to-simplify-data-protection-privacy-and-cyber-reporting-rules/)).

- **EU Cyber Solidarity Act — Regulation (EU) 2025/38 — In force** — 2027 CoI for National and Cross-Border Cyber Hubs now open; deadline **16 Mar 2027** ([ECCC](https://cybersecurity-centre.europa.eu/funding-opportunities/call-expressions-interest_en)). ECA Special Report 19/2026 flagged delays and limited information sharing.

- **Data Act — Regulation (EU) 2023/2854 — In force** — no cybersecurity-specific action this week.

---

## Cross-cutting themes

- **The reporting-single-point tug of war.** The Parliament rapporteur wants **one EU front door**; the Council (via Omnibus VII mandate) wants **one national front door per MS plus EU information point**. Industry outcome either way: fewer templates and clearer routing, but entities need to track at least two parallel scenarios until trilogues conclude.
- **NIS2 + DORA + CRA overlap is now operational, not theoretical.** The CRA SRP, DORA major-incident ITS 2025/302 and NIS2 CSIRT portals are all live simultaneously. Integrated incident classification/decision trees are essential — especially where a single ICT event triggers multiple notifications.
- **Enforcement is shifting from "map the obligations" to "prove the registrations".** Germany's Q4 2026 initiative and Romania's first sanction both target the **registration step**, which is the cheapest for authorities to enforce. Any entity still debating applicability is now firmly in the risk zone.
- **Supply-chain security is converging around three mechanisms**: (1) NIS2 Art. 21(d) risk-managed supplier relationships; (2) CRA Annex I §2 vulnerability handling + SRP; (3) CSA2 cyber-posture certification and Annex 2A high-risk equipment list. The ENISA SBOM Technical Advisory (22 Oct) is a practical bridge across all three.
- **PQC is becoming a near-term compliance item** for NIS2 Annex I sectors — the 31 Dec 2026 "national roadmaps" deadline is 9 weeks out and will cascade into procurement questionnaires in Q1 2027.
- **FOSS clarification matters** — Gregorová's FOSS carve-out in CSA2 and the CRA stewards' Dec 2027 obligation together begin to clarify where open-source projects sit. Treat it as still-moving until trilogues.

---

## What changed since last week

(No prior run; this is the first brief. Items below are published or in force within the 20–26 Oct 2026 window.)

- **21 Oct 2026** — Council general approach on Omnibus VII (digital rulebook simplification; single national reporting entry point + EU information point).
- **21 Oct 2026** — Joint ENISA / EC / CERT-EU / Europol / CSIRTs Network statement on critical PHP vulnerabilities (CVE-2026-109618, -109619).
- **22 Oct 2026** — ENISA Technical Advisory for Software Bill of Materials published.
- **22 Oct 2026** — ENISA PQC webinar on Estonia's national roadmap.
- **20 Oct 2026** — CRA Single Reporting Platform upgraded to v1.2.1.
- **19 Oct 2026** — Dazr / CRA Response Center mid-October reviews confirm NIS2 and CRA national transposition still highly uneven.
- **15 Oct 2026** — German CRA implementation act adopted by Bundestag (Bundesrat second passage pending).
- **14 Oct 2026** — EUDI ARF Topic AA (SCA / payments) refinement round v0.8 discussion paper released.
- **12 Oct 2026** — German BMDS/BMI/BSI joint national PQC guideline published.
- **8–9 Oct 2026** — ITRE rapporteur Gregorová's draft CSA2 / NIS2-amendment reports; German BSI's NIS2 enforcement plan surfaced.
- **1 Oct 2026** — Romania DNSC first NIS2 sanction (announced 1 Oct, imposed 29 Sep 2026).

(Deltas vs. last run will be computed in the next brief using `last-brief-snapshot.md`.)

---

## Recommended actions (prioritised)

### Next 30 days
- **CISO / Risk** — Re-run the NIS2 scoping test and ensure registration in every Member State where entities operate; prioritise Germany (BSI Q4 enforcement) and Austria (new NISG 2026).
- **CISO / Product security** — Validate CRA Art. 14 reporting workflow against the SRP v1.2.1 flow; dry-run the 24h / 72h / 14-day timeline against a real near-miss (e.g., the PHP CVE pattern).
- **Legal / Compliance** — Map existing reporting obligations (NIS2 / DORA / GDPR / eIDAS / CER / CRA) to both Parliament and Council Omnibus VII scenarios; brief executives on likely 2027 reconfiguration.
- **Crypto / Architecture** — Pull a cryptographic inventory; identify high-risk use cases per the EU PQC Roadmap definition and align with the applicable **national roadmap** due by 31 Dec 2026.
- **Vendor management** — Begin collecting SBOMs from material software suppliers per the ENISA 22 Oct advisory; add CRA-eligibility and PQC-readiness questions to vendor assessments.

### Next 90 days
- **DORA** — Prepare for CTPP engagements: refresh the register of information, review subcontracting chain depth, close AFM-flagged gaps (patch / vulnerability management, logical access, group-entity policy independence).
- **CRA (manufacturers)** — Finalise SRP user roles including Secondary Assigned Representatives under the new v1.2.1 flow; publish an internal CRA reporting playbook; prepare for 11 Dec 2027 Annex I obligations with security-by-design evidence packages.
- **eIDAS 2.0** — Decide relying-party registration path and FCAF test strategy; track ARF v3.1 and Topic AA for SCA/payments impacts.
- **CSA2 / cyber-posture certification** — Scenario-plan a **presumption-of-NIS2-compliance** certification exercise (self-assessment against Art. 21 controls, governance, supply chain, reporting readiness); nominate a certification-programme owner.
- **Boards / Executive** — Add quarterly cyber-regulatory agenda item covering NIS2 enforcement posture, DORA oversight exposure, CRA reporting KPIs, PQC migration status, and CSA2 trilogue outlook.

---

## Uncertainty flags

- **BSI NIS2 enforcement timeline** is sourced from Tagesspiegel-reported statements, not a BSI press release; treat precise dates as indicative.
- **Omnibus VII** provisions remain under negotiation; both Parliament and Council positions can shift materially before trilogues.
- Several Member State **CRA national acts** have been adopted at ministerial or committee stage but not yet promulgated in official gazettes.

---

*End of brief — EU Cybersecurity Regulatory Intelligence, 26 October 2026.*
