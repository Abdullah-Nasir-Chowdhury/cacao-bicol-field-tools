# Field Notes — Bicol Cacao Research

Running research log from interviews conducted in Bicol (Albay, near Mayon) in August 2026. This is the
source-of-truth reference behind the tools in this repo (`drip-pressure-planner.html`,
`drip-system-schematic.html`, `schematic-editor.html`) and behind any presentation content built from this
research. Update this file as new interviews/data come in, rather than letting findings live only in chat
history.

## Team scope decision (important — supersedes earlier framing)

Explicit team decision: focus on **(1) flood/drought resilience of the food supply chain** and **(2) pest
and disease control**. Typhoon and Mayon ashfall are deliberately deprioritized — every source (Muravah,
Tatay, the rice/dairy farm, the bamboo farm) called typhoon "unpredictable" and said they'd rather fix
pests/disease, which is tractable. Water focus is broader than the Drip Pressure Planner currently covers:
that tool addresses the drought/pressure side only. Flood/drainage resilience is a real gap in what's been
built so far.

## ⚠️ Disambiguation: two different "Tatay"s

"Tatay" is a Bikol honorific (roughly "elder/grandpa"), not a unique name. Do not conflate these two people:

- **Cacao-Tatay** (Aug 26): solo 2.5 ha grower in the **Batbat** area, cacao + Pili, ~0 kg current cacao
  yield due to pest/disease, frustrated that even subsidized fertilizer is too expensive for him.
- **Tatay Aldavis** (Aug 27): runs a thriving, diversified rice/dairy operation with an accredited farm
  school and "plenty" of government support — a completely different, unrelated farmer.

## Muravah Foundation / Mayon Gold (Albay) — cacao NGO

**Organization**
- Builds typhoon-proof homes and funds education scholarships from cacao profits.
- Agroforestry: cacao interplanted with Pili, coconut, and other cash crops for diversified income.
- Biodiversity farming with heirloom/native cacao trees.
- **No synthetic fertilizers or pesticides — biopesticides/biofertilizers only.** Hard constraint on any
  proposed solution.
- Expanding native cacao cultivation is constrained by: difficulty preserving old native trees, and hybrid
  trees cross-pollinating with natives (risk to varietal standards).

**Labor & succession**
- Aging farmer population (avg. age ~50); no government training programs for the next generation.
- Their coping mechanism: recruiting students from BU Guinubatan.

**Not a problem for them:** transportation (market is local), post-harvest hygiene, fermenting/drying,
waste management (composted as animal feed), sanitation (FDA-certified), land tenure (farmers mostly own
their land).

**Is a problem:** water (no annual drought/flood prediction; they sync planting to the monsoon and seek out
farmers with existing water access; floated a "socio-capital merry-go-round" rotating-fund idea for
water-scarce areas); roasting time varies by season.

**Losses & disasters**
- Post-harvest loss: **80–100% from pests/disease**; near 100% from typhoon in bad years.
- Typhoon recovery time: 1–2 years.
- Would rather solve pests/disease than typhoon (tractable vs. unpredictable).
- Production-cycle data study in progress across **500–1,000 farmers**; exploring precision agriculture.
- **Explicitly skeptical of AI/robotics**: "not there yet, other problems to solve," and "AI is biased
  according to the natives." Any tech proposal must be low-tech / human-in-the-loop, not
  AI-or-robotics-driven — this is a stated values position, not just a cost objection.
- Wants centralized data using both old and new methods.

**Production timeline:** flower→pod 6 months · harvest weekly Sept–Mar · pod-breaking up to 1,000 pods/hr
peak, ~5,000 pods/week typical · ferment 6 days · solar dry 1 day–1 week · post-dry storage 3–6 months (or
process immediately — delay risks humidity damage) · roast 27 min at 140°C · dehull → winnow → grind →
temper → mold → chill → sell. Facility undersized for their batch volumes.

**Mortality/waste**
- **60% pod-handling mortality** when not handled carefully; Mayon ashfall increases this further.
- Diseased/dried plant parts must be manually removed and burned.
- More laborers does not increase profit — pest/disease pressure caps yield regardless of labor input,
  which discourages farmers from investing more work.

**Economics**
- Farmer income: ~₱2,000–10,000/month range.
- Possible lever: "organic" labeling to justify a price premium.
- Core tension: organic certification + export access vs. simply maximizing income.
- Pest control named as problem #1 overall.

## Farmer "Tatay" (cacao smallholder, Aug 26, Batbat area)

- Farm located in the **Batbat** area/barangay.
- 2.5 ha, sole operator (children work in the cities); 100% organic.
- Cacao yield: 500 kg/year historically, ₱75–100/kg. Pili: ₱60–70/kg, split 50/50 owner/picker.
- **Currently ~0 kg cacao yield** due to pest/disease; potential ~2,000 kg/year if resolved — a 4x recovery,
  the single largest lever in the whole dataset.
- Disease agent named: *Phytophthora* (transcribed "pytophthora calibra" — almost certainly *Phytophthora
  palmivora*, the classic cacao black pod disease; matches the described symptom pattern).
- Pests: birds; also observed viral disease affecting pod production.
- Cacao flowering is **year-round**, not seasonal — pest/disease pressure is continuous.
- Water: 2.5 ha, no sprinklers; his framing is that water *pressure*, not volume, is the constraint — he
  can't estimate how many sprinklers his source could support. Open to drip irrigation and rainwater
  collection. (Attribution correction: the pilot-study-and-investors framing, and all proposed
  solutions, are the team's own conclusions from its investigations, not Tatay's suggestions. He
  described the problems and constraints; the ideas are ours.)
- Health problems compounding — limited personal capacity for labor-intensive interventions.
- Believes there's real money in agriculture; younger generation should be encouraged.
- Confirms government programs exist, but input cost (fertilizer) is a barrier even with subsidies.

## Cacao processing facility

- **Power outages are their #1 problem** (not pests directly) — but they're "sometimes out of supply for
  cacao," meaning farm-level pest/disease losses upstream directly destabilize their production runs.
- Otherwise profitable. Roasting machine is underpowered; solar panels too expensive to run their
  equipment. Supplement income via backyard farming. Community scale: ~385 families, ~1,000 people.

## Cross-regional precedent (other Bicol farms/programs — proven working models, not hypotheticals)

**Rice/dairy farm (Tatay Aldavis, Aug 27)** — thriving, government-supported, accredited farm school.
No major pest/disease problem despite organic practice:
- Herbal pesticide sprays; ducks grazing on snails (low-tech biocontrol); chemical pesticides only as a
  last-resort fallback.
- **Caution:** they introduced "golden kohol" (golden apple snail) as a biocontrol predator, and it became
  a pest itself — a real cautionary tale about introducing new organisms for pest control.
- Small-scale drip irrigation in a cucumber greenhouse. Interviewer's own skepticism noted: they claim
  greenhouses control pests, but also grow cucumbers at large scale *without* greenhouses — the real
  explanation for their pest-control success is unclear (possibly the duck/herbal/companion-planting combo
  rather than the greenhouse itself).
- Companion planting: dragonfruit + eggplant + cassava; dragonfruit allegedly repels animals (unconfirmed).
- Composter + shredder for organic fertilizer. Also poultry.

**Bamboo farm** — no problems reported except typhoon. Contact: "Bula masarig," a bamboo engineer.

**Taro (general)** — was banned in some countries over salmonella contamination signs; responded by
implementing research-based harvesting principles.

**Honey (stingless bees)** — 3 products: honey, bee, propolis. Propolis is the most valuable — antibiotic,
antibacterial, antiviral, analgesic; used as a wound tincture, mouthwash, and in toothpaste.

**Neonormal Agventure (taro production/processing project)**
- Enterprise-readiness framework: Quality, Food Safety Compliance, Capacity, Market Understanding — "a
  buyer may be interested, but export happens only with consistent quality, quantity, documentation, and
  reliability."
- Philosophy: "start with what you have, don't wait until it's perfect"; "invest in quality before chasing
  volume."
- **Direct critique this raises for cacao:** cacao processing facilities "sometimes don't get enough cacao
  to produce chocolate" (unstable supply) — precisely because the upstream pest/disease crisis prevents
  farmers from being able to invest in quality before volume the way Neonormal recommends. This is a
  supply-chain aggregation problem, not just a farm-yield problem.
- They do more active research/collaboration than Mayon Gold appears to (worth noting as a contrast, even
  though Mayon Gold says it uses "researched methods").
- **Pest control: a strict 15-day treatment schedule prevents most pest problems under organic methods** —
  routine discipline, not new chemistry, is what works for them.
- Snail control: homemade fermented spray of "cool amino acids mixed with molasses" (Korean Natural
  Farming-style bio-concoction).
- Their own honest caveat, preserved here: cacao pods grow on trees (arboreal), unlike taro/rice (ground
  crops), so direct transfer of ground-application techniques is **unproven** — would need adaptation (e.g.
  foliar/trunk application, timing to cacao's year-round flowering), not a straight copy.

**Indigenous crops in Bicol** (regional/cultural context): Biasong (*Citrus micrantha*), Bungkukan, Burot,
Dawa, Dosol, Faba beans, Galyang, Hagnaya, **Kakaw** (cacao — already part of Bicol's own indigenous-crop
heritage, useful empathy framing: cacao isn't foreign here), Kamatis, Lubi-lubi, Namu, Sili, Talinum, Tibig,
Tuba-tuba, Ube, Uraro. Note: take cacao tree height into account for any harvesting-method design.

**San Miguel Bay Offshore Wind Project** (regional infrastructure context, Aug 28)
- Location: San Miguel Bay, offshore Camarines Sur/Norte (Sipocot, Cabusao, Libmanan, Calabanga, Tinambac,
  Siruma). Capacity 901 MW–1 GW. ~23,307 ha marine space. ~USD 3B (~₱170B+) investment. Developers:
  Copenhagen Infrastructure Partners + ACEN (Ayala Group, 25% stake). Targeted 2028–2030.
- Advantages: strong steady wind, in-bay shelter reduces typhoon/wave exposure vs. open ocean, shallow
  bathymetry lowers install cost.
- Impact: feeds the Luzon grid toward PH renewable targets (35% by 2030, 50% by 2040); ~2,500+ direct jobs;
  drives port upgrades (e.g. Pambuhan Port).
- Relevance to cacao: mostly regional-context background — shows Bicol investing heavily in climate-resilient
  energy infrastructure, on a much longer timeline (2028–2030) than any near-term cacao fix.

**Zambales Solar Farm (San Marcelino)** — largest PH solar farm, a former citrus plantation
- Tension: solar buildout competing with agricultural land, raising food-security concerns.
- **Proposed resolution: agrivoltaics** — co-locate food + energy production on the same land. Named
  applications: solar-powered irrigation, fish hatchery/egg incubation, cold storage.
  → **Directly relevant**: solar-powered irrigation addresses Tatay's water-pressure problem; cold storage
  addresses the "accumulates humidity, gets spoilt" post-dry storage risk.
- **Solis** (Ginlong Technologies): a real, existing hardware/software platform for solar PV + hybrid
  storage management — a concrete answer to "what software exists" for an off-grid irrigation/power angle,
  and relevant to the processing facility's power-outage and weak-roasting-machine-energy problems.
- Panel sizing is demand-calculated per hectare, not rule-of-thumb — methodology parallel to how the Drip
  Pressure Planner approaches sizing (calculate, don't guess).
- Funding benchmark: proud of ₱10 million in funding for their project — useful reference point for what
  funding scale exists regionally for a comparable agri-tech pilot (context for "investors are a problem,"
  per Tatay).
- Lifecycle caveat worth carrying into any solar-irrigation proposal: standard panels weigh 18–22 kg, have
  a 25–30 year design life, degrade to 80–85% efficiency by end of warranty; some are replaced early
  (10–15 yrs); waste is ~70–75% glass, 10–15% aluminum, 5–10% polymers/silicon/copper/silver; IRENA
  projects up to 78 million metric tons of cumulative global solar waste by 2050.

**Unnamed youth/agritourism program**
- Goals: sustainable ag practices, promote technology, rekindle youth interest in farming, connect society
  to smart farming. Zero-waste focus; Soil Science Discovery Park.
- Youth engagement via visible, hands-on features: Edible Landscaping, Butterfly Garden, AgriMuseum —
  directly relevant model for the aging-farmer/succession problem, beyond Muravah's student-recruiting
  approach.
- Other components: Agriville Plantations (fish, sheep/goat), an agrivoltaic project, coconut nursery.
- Asked directly if they could help cacao farmers: **no**, limited capacity, little exposure to cacao
  farmers specifically — though they believe there's a future for cacao farming.
- **Notable finding:** the speaker didn't know how badly Mayon-area cacao farmers were doing — a real
  visibility gap between cacao's crisis and the region's broader, well-resourced agri-innovation ecosystem.
- Open question, still unresolved: is this cacao crisis Bicol-specific, or nationwide?
- **Claim to flag:** a speaker at this stop (attribution unconfirmed — best guess is this program's own
  speaker, consistent with their stated belief that "there's a future for cacao farming," but re-check
  against the raw interview audio/notes before citing) said cacao would become **Bicol's biggest
  agricultural production**. Team's own skeptical reaction (opinion, not data — keep this framing in any
  slide/deck use): *"Is that actually achievable given cacao's current production levels?"* — worth holding
  up against the dataset's actual numbers (Tatay at ~0 kg/yr actual vs. 2,000 kg/yr potential; 80–100%
  pest/disease loss regionally) before repeating the claim uncritically.

## Solar / agrivoltaics — panel orientation note (Aug 28, own observation)

- **Vertical panel placement is inefficient for sunlight collection** — flagged as a design consideration
  for any agrivoltaic or solar-irrigation proposal built on the Zambales precedent above. This is the
  team's own engineering observation, not something a source stated in an interview.
- Supporting photo captured at the Aug 28 agrivoltaics site visit: vertically mounted panels lining the field (images/vertical-panel.jpg in the repo; shown on the vertical-panels slide).

## Quick-reference numbers

| Metric | Value |
|---|---|
| Post-harvest loss — pests/disease | 80–100% |
| Post-harvest loss — typhoon (bad year) | ~100% |
| Pod handling mortality (careless) | 60% |
| Typhoon recovery time | 1–2 years |
| Tatay's potential vs. actual cacao yield | 2,000 kg vs. ~0 kg |
| Farmer income range | ₱2,000–10,000/month |
| Average farmer age | ~50 |
| Farmers in Muravah's data study | 500–1,000 |
| Processing facility community | ~385 families / ~1,000 people |
| Roast spec | 140°C, 27 minutes |
| Ferment time | 6 days |
| Flower-to-harvest | 6 months |
| Taro project's pest-prevention schedule | every 15 days |
| Zambales solar project funding | ₱10 million |
| San Miguel Bay wind investment | ~USD 3B / ~₱170B+ |

## Team

- Nancy — Humanities & Social Sciences → empathy / interview-synthesis narrative
- Masa — Data Engineering → precision-agriculture / data-centralization angle Muravah wants
- Keisuke — Modern Philosophy → tradeoffs (organic-vs-export-vs-income, Muravah's AI-bias concern,
  agrivoltaic land-use ethics)
- Ash — presents the "claim worth checking" callout and the conclusion recap in the web presentation
- Ria — from Bicol, Philippines; studies at Bicol University (BU) → grounds the team's outsider read of
  the interviews against lived local/regional knowledge; narrates the field-visit slides in the pitch deck
- Chow — Computer Science → the tools in this repo

See `SPEAKER-NOTES.md` for who presents which section of `Bicol-Cacao-Pitch.pptx`.
