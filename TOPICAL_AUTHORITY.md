# Topical Authority — kawat.id

## Role and boundary

Kawat.id is an Indonesian reference and commercial-support property for wire products: how wire is named, specified, selected, bought, installed, inspected, maintained, and retired. The core audience is Indonesian household and project buyers, estimators, fabricators, installers, maintenance teams, contractors, and technical decision-makers.

The knowledge layer explains products and decisions. Existing `/services` and the eleven product routes own quotation, availability, delivery, and contact intent. Editorial pages must not publish unverified prices, safe working loads, structural capacities, electrical ampacity, or installation acceptance criteria.

Same-domain cannibalization is controlled here. Other Syamsul-owned domains may independently cover the same query or topic; their coverage does not remove a useful topic from Kawat.id.

## Evidence audited

- Scope and ownership: Syamsul confirmed `kawat.id` is owned and in scope.
- Canonical repository: `cfpages-adminalampintar/kawat.id`, branch `main`; inspected locally as a static WordPress export.
- Sitemap: `sitemap-complete.xml` contains **5,632 unique URLs**.
- Sitemap mix: **5,104 product-plus-location variants**, **11 product hubs**, **512 category/archive URLs**, `/`, `/about`, `/services`, `/contact`, and one Cloudflare email-protection URL.
- Root files: 5,105 root HTML files, consisting of the homepage plus 5,104 location variants. This corrects the earlier approximate interpretation of 5,105 location pages.
- Location template counts: kawat baja 211; bendrat 489; bronjong 489; duri 489; harmonika 489; loket 489; segel 489; seling 490; stainless steel 490; tembaga 490; wiremesh 489.
- Existing product hubs: `/kawat-baja`, `/kawat-bendrat`, `/kawat-bronjong`, `/kawat-duri`, `/kawat-harmonika`, `/kawat-loket`, `/kawat-segel`, `/kawat-seling`, `/kawat-stainless-steel`, `/kawat-tembaga`, and `/kawat-wiremesh`.
- Category roots: two normal labels (`kawat-baja`, `kawat-bronjong`) and nine malformed labels beginning `https-arifhana-my-id-...`; their pagination produces most archive URLs.
- Navigation and commercial routes: homepage, `/services`, product hubs, contact, about, telephone, and external messaging links.
- Primary-source families checked for editorial gates: ESDM/Gatrik PUIL 2020 and mandatory electrical SNI listings; BSN gabion standards listings; Ministry of Public Works gabion guidance; ISO 4309:2017 for crane wire-rope care/inspection/discard and ISO 16625:2025 for crane/hoist wire-rope selection. A publication must recheck current status and applicability before citing any clause.

## Existing coverage and risks

The export has enormous URL volume but little demonstrated editorial breadth. Location-swapped product pages dominate the indexable surface and should not be counted as authority coverage. Location names alone do not create distinct substance.

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Brand/product navigation | expand | Central wire knowledge hub plus `/services` | Preserve conversion paths and measure engagement |
| `/services` | Product list and commercial discovery | keep | Commercial catalogue | Confirm live quote workflow and stock language |
| Eleven `/kawat-*` product hubs | Commercial/product-intent pages with useful URL history | expand | Each route remains the product hub; informational children link upward | Check live copy, backlinks, impressions, and canonical tags |
| 5,104 `/<product>-<city>-<province>` routes | Programmatic location variants with likely doorway/duplication risk | manual review | Keep only pages with verified local inventory, delivery, case, regulation, or service difference; otherwise consolidate to product hub | GSC indexation, traffic, leads, content similarity, backlinks, canonical behavior |
| `/kawat-seling-jambi-jambi-2` and other suffix anomalies | Duplicate-slug symptom | merge | Unsuffixed verified owner or `/kawat-seling` | Find all suffix/canonical anomalies and compare content/history |
| `/category/kawat-baja/**` and `/category/kawat-bronjong/**` | Thin taxonomy and pagination | noindex | Product hubs | Confirm whether any archive has useful backlinks or unique copy |
| `/category/https-arifhana-my-id-*/**` | Malformed migrated taxonomy exposing another-domain string | remove | Relevant product hub | Verify no valuable traffic/backlinks; return 410 or redirect only when intent matches |
| `/cdn-cgi/l/email-protection` in sitemap | Utility endpoint, not content | remove | none | Remove from sitemap; retain runtime utility if required |
| `/about`, `/contact` | Trust and contact pages | keep | Existing routes | Verify organization details, response path, privacy, and freshness |
| Feed XML files | Syndication utilities outside the main sitemap | manual review | Keep only if consumed | Check subscribers and ensure feed URLs are not mistaken for articles |

Primary risks are index bloat, near-duplicate location pages, malformed category archives, ambiguous product terminology, unsupported “termurah” claims, thin product copy, and unsafe advice around structural mesh, lifting ropes, gabions, electrical conductors, fence loads, corrosion, and installation.

## Coverage matrix

| Framework lens | Topic owners / rationale |
|---|---|
| Definition and vocabulary | KWT-01, KWT-12 distinguish wire, cable, mesh, rope, sealing wire, and Indonesian trade terms |
| Taxonomy and variants | KWT-01 through KWT-15 cover product families, constructions, materials, and applications |
| Anatomy and components | KWT-05, KWT-07 through KWT-13 cover mesh intersections, gabion panels, posts, fittings, rope cores/end terminations, seals, and conductor insulation |
| Materials and properties | KWT-02, KWT-04, KWT-14, KWT-15 |
| Mechanisms and science | KWT-03, KWT-04, KWT-05, KWT-07, KWT-11, KWT-13 |
| History and evolution | KWT-01 owns a concise terminology/history reference; no thin standalone nostalgia pages |
| Measurement and terminology | KWT-03 and system-specific measurement pages |
| Need recognition | KWT-01, KWT-05 through KWT-15 |
| Survey and diagnosis | KWT-07 through KWT-11, KWT-16, KWT-17 |
| Requirements and design | KWT-05, KWT-07 through KWT-11, KWT-13; professional calculations are mandatory where safety-critical |
| Comparison and selection | KWT-02, KWT-05 through KWT-15 |
| Budget and procurement | KWT-03, KWT-18 |
| Preparation | KWT-06 through KWT-13, KWT-16 |
| Installation/construction | KWT-05 through KWT-13 and KWT-16 |
| Commissioning/handover | KWT-05, KWT-07 through KWT-11, KWT-13, KWT-16 |
| Use/operation | KWT-08 through KWT-13 |
| Inspection and maintenance | KWT-04, KWT-07 through KWT-11, KWT-17 |
| Troubleshooting and repair | KWT-04, KWT-05, KWT-07 through KWT-11, KWT-17 |
| Upgrade and replacement | KWT-04, KWT-08 through KWT-11, KWT-17 |
| Stakeholders | Homeowners: KWT-01/08/09/10/13; contractors: KWT-05/06/07/16; industrial teams: KWT-11/12/14/15/17; buyers: KWT-18 |
| Building/site type | KWT-05, KWT-07 through KWT-11, KWT-13 |
| Geography and climate | KWT-04 owns humid/coastal/corrosive exposure; no city swaps |
| Scale and performance | KWT-03, KWT-05, KWT-07 through KWT-11, KWT-13 |
| New build versus retrofit | KWT-05, KWT-08, KWT-09, KWT-13, KWT-16 |
| DIY versus professional | KWT-06, KWT-08 through KWT-10, KWT-13, KWT-16 define stop conditions |
| Quality level | KWT-02, KWT-03, KWT-18 |
| Safety and health | KWT-05, KWT-07 through KWT-13, KWT-16, KWT-17 |
| Failure modes | KWT-04, KWT-05, KWT-07 through KWT-11, KWT-13, KWT-17 |
| Standards and regulation | KWT-05, KWT-07, KWT-08, KWT-09, KWT-10, KWT-11, KWT-13; current official sources required |
| Environmental impact | KWT-04, KWT-17, KWT-18 |
| Evidence quality | KWT-03, KWT-05, KWT-07 through KWT-13, KWT-18 |
| Myths and unsafe advice | KWT-01, KWT-04, KWT-05, KWT-07, KWT-11, KWT-13 |
| Fundamentals | KWT-01 through KWT-04 |
| How-to | KWT-06 through KWT-13, KWT-16; qualified review gates apply |
| Comparison | KWT-02, KWT-05, KWT-08 through KWT-15, KWT-18 |
| Diagnosis | KWT-04, KWT-05, KWT-07 through KWT-11, KWT-17 |
| Calculation/tool | KWT-03, KWT-05, KWT-07 through KWT-11, KWT-13, KWT-18 |
| Visual reference | KWT-01, KWT-03, KWT-05, KWT-07 through KWT-13, KWT-17 |
| Case study | KWT-05, KWT-07 through KWT-11, KWT-16 only from documented real projects |
| FAQ/glossary | KWT-01; short answers remain within the hub rather than thin pages |
| Commercial support | KWT-18 and existing `/services`/product hubs |
| News/trends | N/A as a parent topic: standards changes are maintained inside evergreen pages and logged by review date |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KWT-01 | Wire fundamentals and vocabulary | Identify the correct wire family and use consistent Indonesian trade terms | wire versus cable/rope/mesh; solid versus stranded; drawn wire; diameter/gauge; coils/sheets; glossary; history of trade terms; unsafe synonym assumptions | Taxonomy diagram, glossary, sourced explanation, original product photos | Does not select alloys (KWT-02), calculate quantities (KWT-03), or quote products (`/services`) | 6 |
| KWT-02 | Materials, grades, and properties | Choose a material family from service conditions without treating appearance as a grade | low/high-carbon steel; stainless families; copper; zinc/aluminium coatings; tensile/ductility concepts; magnetism myths; traceability | Manufacturer certificates, primary standards, comparison tables, metallurgist/materials-engineer review | Does not own corrosion system design (KWT-04), specialty stainless uses (KWT-14), or electrical conductor sizing (KWT-13) | 6 |
| KWT-03 | Dimensions, testing, and quantity | Read specifications, verify delivered dimensions, and estimate non-structural quantities | diameter; aperture; roll/sheet dimensions; mass per length/area; tolerances; sampling; certificates; test reports; conversion tools | Calibrated field measurement, calculation sheets, test-lab examples, current standards | Does not calculate structural capacity (KWT-05), safe lifting load (KWT-11), or electrical ampacity (KWT-13) | 6 |
| KWT-04 | Corrosion, coatings, and exposure | Match protection and maintenance to humid, coastal, chemical, or buried exposure | corrosion mechanisms; galvanizing; zinc-aluminium; polymer coatings; stainless selection; dissimilar-metal contact; coating damage; inspection; lifecycle | Exposure decision table, coating data, field photos, corrosion-specialist review, primary standards | Does not specify each finished system (KWT-05, KWT-07–KWT-11) or sell “rustproof” products (`/services`) | 6 |
| KWT-05 | Structural welded wire reinforcement | Understand when welded wire reinforcement may be used and what an engineer must specify/accept | sheet/roll identification; spacing/area; placement; laps; chairs/cover; cutting; damage; concrete interface; drawings; acceptance; failure modes | Current structural/material standards, mill certificates, engineer calculations and review, site inspection photos | Never supplies project reinforcement design or load capacity; KWT-03 owns generic measurement and `/kawat-wiremesh` owns quotes | 6 |
| KWT-06 | Tie wire and bendrat practice | Select and use tie wire for fixing without confusing it with structural reinforcement | annealed wire; diameters; tying tools; tie patterns; consumption; storage; sharp ends; precast/formwork uses; common over-tightening | Demonstration photos, ergonomics/safety checklist, field measurement, contractor review | Does not claim bendrat adds design reinforcement capacity; KWT-05 owns reinforcement design and `/kawat-bendrat` owns sales | 6 |
| KWT-07 | Gabions and erosion-control mesh | Scope a gabion project and recognize when geotechnical/hydraulic design is required | basket/mattress parts; mesh/coatings; foundation; filter/geotextile; stone; diaphragms/lacing; hydraulic/scour context; deformation; maintenance | Current BSN/SNI status, Ministry PUPR guidance, geotechnical/hydraulic calculations, engineer review, construction photos | Never provides site-specific retaining, slope, river, or scour design; `/kawat-bronjong` owns quotes | 6 |
| KWT-08 | Chain-link and perimeter fencing | Select, detail, and inspect chain-link fencing for a real site | harmonika mesh; aperture/gauge; posts/rails/tension wire; gates; terrain; wind/privacy screens; foundations; installation; repairs | Site survey, wind/load engineer review where screens or tall fences apply, details, photos, checklist | Does not own welded-panel fencing (KWT-09), deterrent toppings (KWT-10), or commercial quotes (`/kawat-harmonika`) | 6 |
| KWT-09 | Welded mesh panels, cages, and guards | Select kawat loket for enclosure, guarding, partition, and non-reinforcement uses | aperture/wire; roll/panel; frames; fixings; animal enclosure; machine guards; ventilation; edges; gates; loading; cleaning | Dimension tables, risk assessment, application photos, fabricator review, load review where safety-critical | Does not treat loket as concrete reinforcement (KWT-05) or chain-link (KWT-08); `/kawat-loket` owns quotes | 6 |
| KWT-10 | Barbed and security wire | Decide whether barbed wire is lawful, proportionate, and safe for a boundary | conventional barbed wire; placement; posts/strainers; agricultural use; public-contact risk; warning; PPE; tension; repair; alternatives | Site risk assessment, current local rules, fence professional review, installation photos | Does not cover electrified fencing, weaponization, or evasion; chain-link base fence is KWT-08 and `/kawat-duri` owns quotes | 6 |
| KWT-11 | Wire rope, slings, and lifting safety | Recognize construction, records, damage, and strict limits of self-service advice | rope construction/core/lay; selection inputs; drums/sheaves; terminations; slings; load control; inspection; discard; storage; lubrication; certification | Current ISO/ASME or applicable adopted standards, manufacturer instructions, competent lifting engineer/inspector review, inspection records | Never publishes a universal WLL/SWL or approves a lift; `/kawat-seling` owns supply and qualified lifting professionals own plans | 6 |
| KWT-12 | Sealing wire and tamper-evident systems | Select a seal system and document custody without confusing a seal with lifting hardware | sealing wire materials; lead-free/plastic seals; meter/logistics uses; numbering; tools; tamper evidence; records; disposal; attack limits | Manufacturer data, chain-of-custody template, security review, photos | Does not cover wire-rope shackles or lifting (KWT-11), cybersecurity, or quote intent (`/kawat-segel`) | 6 |
| KWT-13 | Copper wire and electrical conductors | Distinguish bare copper/craft wire from regulated electrical conductors and know when a licensed practitioner is mandatory | solid/stranded; insulation; conductor identification; voltage/current/temperature context; joints; earthing/bonding; counterfeit risk; testing; fire/shock stops | Current PUIL/SNI and ESDM sources, manufacturer data, licensed electrical engineer/installer review, test reports | No project ampacity, protection, earthing, or wiring design; `/kawat-tembaga` owns supply and KWT-14 owns stainless wire | 6 |
| KWT-14 | Stainless wire applications | Select stainless wire for food, marine, architectural, spring, or fabrication contexts | alloy family; condition; surface; chloride exposure; welding; cleaning; galling/contact; mesh/spring uses; certificates | Material certificates, corrosion data, manufacturer comparison, materials specialist review | Does not promise “stainless means rustproof”; KWT-04 owns corrosion and `/kawat-stainless-steel` owns quotes | 6 |
| KWT-15 | General steel wire and fabrication | Match carbon-steel wire condition to forming, springs, fasteners, crafts, and industrial fabrication | low/high carbon; annealed/hard drawn; straightened/cut; forming; spring concepts; heat treatment; weldability; surface; defects | Mill certificates, forming trials, diagrams, fabricator/metallurgist review | Does not own structural reinforcement (KWT-05), tie wire (KWT-06), or lifting rope (KWT-11); `/kawat-baja` owns quotes | 6 |
| KWT-16 | Site preparation and installation QA | Build a safe, documented installation workflow across wire systems | survey; drawings; utilities; access; PPE; tools; storage; sequencing; hold points; punch list; handover; stop-work conditions | Method statement template, JSA/checklist, qualified installer review, field photos | Does not replace system-specific engineering in KWT-05/KWT-07–KWT-13 or act as a sales page | 6 |
| KWT-17 | Inspection, failure, repair, and retirement | Triage visible defects and choose repair, specialist assessment, or replacement | inspection records; corrosion; broken wires; deformation; loose fixings; sharp edges; fatigue; contamination; repair limits; recycling | Defect atlas, decision tree, original photos, qualified discipline review | Does not set lifting discard criteria (KWT-11), structural acceptance (KWT-05/KWT-07), or electrical safety limits (KWT-13) | 6 |
| KWT-18 | Procurement, supplier evaluation, and lifecycle cost | Compare offers on equivalent scope and evidence, not headline price | RFQ fields; certificates; samples; tolerances; coatings; delivery; warranty; counterfeit signs; cost components; receiving inspection; lifecycle | RFQ template, bid matrix, receiving checklist, certificate examples, procurement review | No invented market prices or vendor rankings; `/services` and product hubs own availability and quotations | 6 |

## Related-domain opportunities

- Construction-focused owned domains may independently explain concrete, retaining structures, drainage, fencing, or electrical work from their own entity perspective. Kawat.id should link only when useful to readers and when an editorial relationship is intentionally disclosed.
- `Material.co.id` is vision-only according to portfolio context; do not treat it as a live canonical owner or suppress material topics here.
- Product suppliers, test laboratories, standards bodies, and qualified practitioners can provide source material, certificates, demonstrations, and reviewed case evidence. Participation must not convert neutral guides into undisclosed advertorials.
- Cross-domain matching queries are not cannibalization. Only overlaps among routes on Kawat.id enter the register in `ARTICLE_CATALOG.md`.

## Consolidation plan

1. Export GSC URL/query performance, backlink evidence, live canonicals, and lead attribution before changing legacy URLs.
2. Remove `/cdn-cgi/l/email-protection` and malformed category/archive URLs from the sitemap.
3. Set low-value category pagination to `noindex,follow` or retire it; keep product hubs crawlable.
4. Cluster the 5,104 location variants by product and normalized body similarity. Preserve a local page only when verified local substance exists.
5. For redundant location pages with no history, consolidate to the matching product hub; use redirects only when intent truly matches. Do not redirect every removed page to the homepage.
6. Resolve suffix anomalies such as `-2` against unsuffixed owners using history and canonical evidence.
7. Expand eleven product hubs as stable commercial/entity pages, then publish the bounded editorial cluster below.
8. Rebuild the sitemap from canonical indexable URLs and monitor excluded/duplicate signals after each batch.

## Internal-link architecture

- `/` becomes the central directory and links to all eighteen topic hubs plus `/services`.
- Each topic hub links to its six children; every child links back using descriptive anchor text.
- Product-specific editorial pages link to the matching product route only when the reader reaches a legitimate supply decision.
- Diagnostic pages link to prevention, inspection, repair limits, replacement, and the appropriate qualified-professional stop condition.
- Comparison pages link to individual entity pages, not to a repeated generic list.
- KWT-03 measurement tools support KWT-05 through KWT-15; KWT-04 corrosion supports all exposed metal systems; KWT-16 and KWT-17 form the cross-system install-to-retirement path.
- KWT-18 receives contextual links from specification and receiving-inspection pages, then links to `/services` for a quote.
- No article is published until its related IDs exist or are changed to an existing route/topic reference, preventing orphaned placeholders.

## Evidence and editorial standards

- Verify standards status and applicability on the publication/review date; never copy a clause number from a secondary source.
- Structural mesh, gabions, fence loads, foundations, anchors, and safety-critical guards require calculation or review by an appropriately qualified engineer for the actual site. Generic calculators must display assumptions and cannot produce construction approval.
- Wire rope, sling, termination, lifting selection, inspection, and discard content requires current applicable standards, manufacturer instructions, and review by a competent lifting professional. Never infer capacity from diameter alone.
- Electrical conductor content requires current PUIL/SNI/ESDM sources and review by a licensed/qualified electrical practitioner. No DIY live work, universal ampacity tables, or improvised connections.
- Corrosion/coating claims require material/coating data and qualified review when failure affects structure, lifting, electrical safety, security, or public exposure.
- Installation guidance must include prerequisites, PPE, utility/site checks, hold points, verification, and clear stop-work conditions.
- Use mill/test certificates, calibrated measurements, original diagrams/photos, and documented real cases. Do not fabricate field experience, test data, prices, regulations, or before/after results.
- Separate neutral explanation from supply intent. Disclose commercial relationships and dates.

## First bounded publication cluster

Wave W1 contains twelve assets:

1. KWT-01-01 — central family selector.
2. KWT-03-01 — diameter/aperture measurement.
3. KWT-04-01 — Indonesian exposure/corrosion selector.
4. KWT-05-01 — structural wiremesh specification reading.
5. KWT-05-04 — wiremesh placement inspection.
6. KWT-07-01 — gabion system anatomy and design inputs.
7. KWT-08-01 — chain-link site selection.
8. KWT-11-01 — wire-rope construction and record identification.
9. KWT-11-04 — inspection and quarantine workflow.
10. KWT-13-01 — copper wire versus regulated conductor.
11. KWT-16-01 — pre-installation survey and method statement.
12. KWT-18-01 — comparable wire-product RFQ.

The cluster is coherent because it begins with classification and measurement, covers the highest-risk existing product families, adds installation control, and ends with an evidence-based procurement path. Monitor canonical indexation, impressions separated by intent, useful tool/checklist completion, engaged navigation to product hubs, qualified enquiries, query/URL duplication, and any safety correction requests. Ranking alone is not success.

## Definition of done

- All eighteen parent topics have six genuinely distinct briefs in `ARTICLE_CATALOG.md`.
- Topic IDs, article IDs, titles, and slugs are unique; related IDs resolve.
- Existing and proposed same-domain overlaps are consolidated, bounded, or registered.
- Safety-critical drafts pass the named primary-evidence and qualified-review gate before publication.
- The W1 cluster is published as connected hubs/spokes with tested canonicals, schema where appropriate, and no orphan pages.
- Sitemap indexation is reduced to canonical useful pages; legacy changes are evidence-led and monitored.
- Success is reviewed using indexation, intent-level impressions, task completion/engagement, qualified leads, and collected commercial outcomes where attributable.
