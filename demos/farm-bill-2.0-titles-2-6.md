# Farm Bill 2.0: goals, likely effects, implementation barriers, and forecastable outcomes

## Scope and reading conventions

This report analyzes selected high-consequence provisions in Title II (Conservation) and Title VI (Rural Development) of the supplied Agricultural Act of 2026 discussion-draft extracts. It favors provisions with a clear operative mechanism, an important implementation choice, or a plausibly resolvable outcome over thin coverage of every extension and conforming amendment.

The two source files were read in full. Short quotations below preserve the statutory wording while removing PDF line-break hyphenation.

Source limits matter:

- `farmbill_title2_conservation.txt` begins with a fragment from the prior title, then Title II starts at line 14. The file repeatedly identifies itself as “file 1 of 2” and ends in the middle of §2805(f), after “finds that”. The missing balance of §2805—including any remaining sanctions, funding, or closing language—cannot be inferred.
- `farmbill_title6_ruraldev.txt` likewise begins with a short prior-title fragment; Title VI starts at line 6 and runs through §6316.
- Neither supplied title contains a literal `RESERVED`, `TBD`, bracketed placeholder, or other explicit placeholder provision. Open-ended phrases such as “as determined by the Secretary” are delegations, not placeholders.

Labels have the following meanings:

- **[CONFIRM]** is an imputed drafter goal, phrased as staff might state it. It should be confirmed with the drafters; it is not a finding about effect.
- **[TOLD REGARDLESS]** is the best ex ante account of likely effects from the text, including mechanisms that may cut against the imputed goal.
- **Existing Thesis path** means the supplied brief establishes that the metric is reachable through an existing Thesis adapter.
- **Not yet in Thesis** means the brief expressly says it is absent.
- **Registry status unestablished** means the supplied materials do not establish whether it is registered; this report does not guess.
- **No tracked series** means no suitable recurring, officially published series was identified. A future agency report is not treated as an existing series.

For a scheduled, versioned product, “first print” should mean the first agency release captured at a preregistered lag. A rolling database or live viewer—such as USAspending, ECHO, or an administrative dashboard—has no discrete agency “first release”; for those products, the resolvable print is a Thesis-archived, dated extract taken at the fixed lag. It is not the value later returned by a revised live database. Every registration should freeze the publisher, product, field, observation date, extraction/release cutoff, geography, denominator, revision rule, and missing/suppression treatment.

One further distinction is essential: **authorization is not appropriation; appropriation is not obligation; obligation is not completion; completion is not outcome**. For authorization-only provisions, enactment cells should also preregister an appropriations path or moderator. Otherwise an “enactment” forecast bundles legislation with an unstated funding forecast.

## Title II — Conservation

### 1. §§2101, 2105, and 2401(1): Conservation Reserve Program scale, grazing infrastructure, and payments

**Provision and operative language**

Section 2101, “Conservation Reserve,” extends the program through 2031 and sets its acreage ceiling:

> “during fiscal years 2027 through 2031 not more than 27,000,000 acres.”

It also directs USDA, “to the maximum extent practicable,” to maintain at least 2,000,000 acres in the reserve at any one time in FY2027–31 and caps the land category cross-referenced in §1231(b)(3) at 12,000,000 acres. Land with cost-shared grazing infrastructure becomes eligible for consideration for reenrollment. Section 2105, “Payments,” adds cost sharing for:

> “grazing infrastructure and water infrastructure under each contract, for all practices, if grazing is included in the conservation plan and addresses a resource concern.”

Section 2105 bases a tract’s rental rate on its three predominant cropland soils, bars an inflation adjustment to payments, and raises the rental-payment limitation from $50,000 to $125,000. Section 2401(1) provides $100 million in each of FY2027–31 for the new grazing and water infrastructure cost share on “acreage not enrolled under section 1231(d)(2).”

**Imputed goals [CONFIRM]**

1. Keep CRP operating at a scale of up to 27 million acres through 2031.
2. Make enrolled land more useful during and after contracts for managed grazing while retaining conservation safeguards.
3. Make participation commercially viable for larger operations and simplify rental-rate calculation.

**Likely effects [TOLD REGARDLESS]**

- **Program scale — ceiling, not target:** The 27-million-acre number permits enrollment up to that level; it does not require USDA to reach it. Enrollment can remain below the cap if offer volume, rental-rate competitiveness, program allocation, or administrative capacity is insufficient.
- **Participation — nominal cap versus real value:** Raising the payment limit can make large contracts more attractive. All else equal, the express ban on an inflation adjustment erodes a given payment’s real value relative to an indexed payment as prices rise, likely reducing later-year offer and reenrollment rates at the margin. It does not prevent new-contract rates from changing for other statutory or market reasons.
- **Adversarial mechanism — tract averaging:** Applying one rate based on three predominant cropland soils to all enrolled land on a heterogeneous tract can overcompensate lower-productivity portions and undercompensate higher-productivity portions. It also creates an incentive to configure tract or offer boundaries around favorable soils.
- **Land-use durability — infrastructure lock-in:** Cost-shared fences and water systems can make grazing economically durable after a CRP contract. That may retain grass cover, but it also shifts part of CRP toward subsidized production and can increase conflict between forage use and habitat objectives.
- **Concentration — higher payment ceiling:** More total rental assistance can flow to a single owner or operator. Without a published recipient-distribution series, staff cannot assume that the higher ceiling mainly reaches previously constrained family-scale participants.

**Implementation barriers**

- **FSA county offices and soil/rental systems bear the burden.** They must identify the three predominant cropland soils, apply the result to heterogeneous enrolled acreage, explain disputes, and keep the method consistent across counties. The text does not say how the three-soil rule works for a tract with no cropland or fewer than three qualifying soil map units.
- **Producers and conservation planners bear a new documentation burden.** Grazing must be in the conservation plan and address a resource concern. At scale, plan amendments, practice eligibility, construction verification, and reenrollment crosswalks become the queue.
- **Program managers must reconcile composition constraints with actual demand.** The minimum and maximum acreage rules cross-reference categories in existing law; a national cap can be available while a category-specific constraint binds.

**Candidate outcome metrics**

- **Direct implementation/outcome:** USDA Farm Service Agency, **Conservation Reserve Program Statistics**, using the dated **CRP Monthly Summary** or the fixed September 30 snapshot: active enrolled acres, contracts, farms, annual rental payments, and dollars per acre by program category. Do not call the 27-million-acre ceiling a target. **Registry: the CRP acreage field is Not yet in Thesis, per the brief; status for the contract, farm, and payment fields is unestablished.**
- **Distribution and composition:** USDA FSA, **CRP Enrollment and Rental Payments by State/County** and **CRP Practices (Acres) by County**. Freeze the first workbook or PDF captured after the preregistered date because live workbooks may be replaced. **Registry: the county/practice acreage fields are Not yet in Thesis under the brief’s CRP-acreage instruction; payment-field status is unestablished.**
- **Honest gap:** No suitable recurring official series links these amendments to habitat quality, contract-level post-CRP land use, or the distribution of payments by ultimate beneficial owner. **No tracked series.**

**Conditional-cell candidates**

- `P(FSA active CRP enrolled acres at September 30 in FY2027–31 follow path a_t | enactment vs non-enactment)`
- `P(FSA CRP category shares and average annual rental dollars per acre follow path r_t | enactment vs non-enactment)`
- `P(FSA CRP contracts and enrolled acres per participating farm follow path c_t | enactment vs non-enactment)`

### 2. §§2102 and 2104: CREP water conservation and emergency haying/grazing

**Provision and operative language**

Section 2102, “Conservation Reserve Enhancement Program,” provides that an agreement permanently retiring water rights receives the irrigated-acre payment rate, while an agreement permitting dryland agricultural use receives the difference between the irrigated- and dryland-acre rates.

Section 2104, “Duties of the Secretary,” permits emergency haying “on certain practices” on no more than 50 percent of contract acres under a site-specific plan when any one of three tests is met:

> “the county is designated as D2 (severe drought) or greater according to the United States Drought Monitor”; “there is at least a 40 percent loss in forage production in the county”; or USDA, “in coordination with” the State technical committee, makes the specified natural-disaster determination.

It bars haying or grazing during the final two weeks of the primary nesting season when that use would cause long-term damage to vegetative cover for supported wildlife populations, and it provides that the new exceptions:

> “shall not be subject to the requirements of the National Environmental Policy Act of 1969.”

**Imputed goals [CONFIRM]**

1. Pay enough to make permanent retirement of irrigation rights or conversion to dryland use attractive.
2. Release forage quickly during drought, flood, wildfire, and other emergencies.
3. Preserve established cover and wildlife value while removing procedural delay.

**Likely effects [TOLD REGARDLESS]**

- **Water use — parcel-level conservation:** Paying the irrigated rate for permanent retirement should increase retirement offers and reduce irrigation on enrolled parcels.
- **Adversarial mechanism — adverse selection and leakage:** Payment depends on irrigated status and administratively determined rates, not a statutory demonstration of historical consumptive use saved. Low-use or weak rights may enroll first, and saved water may be pumped or diverted elsewhere unless State law retires the consumptive entitlement at the relevant basin scale.
- **Relief — faster forage access:** A disjunctive trigger makes emergency haying available in more circumstances and can lower emergency feed and transport costs.
- **Adversarial mechanism — threshold and timing effects:** A D2 boundary creates a cliff between otherwise similar counties. Allowing use in the last two weeks of the primary nesting season can still harm late nests; the safeguard depends on a rapid prediction of “long-term” vegetative-cover damage, not direct nest outcomes.
- **Procedural tradeoff — NEPA exclusion:** Removing NEPA review can accelerate a time-sensitive response. It also removes a structured channel for identifying cumulative or repeated habitat effects and may shift disputes to later enforcement or litigation.

**Implementation barriers**

- **State water administrators, FSA, and applicants must make “permanent” real.** Water-right retirement, transfer, abandonment, and return-flow treatment differ across States. A Federal contract alone may not extinguish the relevant State-law right.
- **FSA must establish defensible irrigated and dryland rates.** A generous spread can overpay paper or rarely used rights; a narrow spread can kill take-up among high-value users.
- **County offices lack a uniform high-frequency forage-loss series.** The bill specifies a 40 percent county loss but not the data product, baseline, estimator, or appeal process. This invites inconsistent proof and delay precisely during emergencies.
- **Site-specific administration is spatially demanding.** FSA must map the 50 percent limit, determine applicable practices, and make wildlife-cover findings fast enough for hay to remain useful.

**Candidate outcome metrics**

- **Program participation:** USDA FSA, **Conservation Reserve Program Statistics / CRP Monthly Summary**, using separately published CREP acres and contracts. Do not add CREP rental payments without naming and verifying an exact official table/field. **Registry: the CREP-acre subset of CRP acreage is Not yet in Thesis; contract-field status is unestablished.**
- **Water-use context, not a direct program outcome:** USDA National Agricultural Statistics Service, **Irrigation and Water Management Survey**, for irrigated acres and water applied in an ex ante panel of pre-enactment CREP States or water-resource regions that the product actually publishes. Do not select the panel using future awards or participation. The survey is periodic, self-reported, and too coarse to identify CREP retirements. **Registry: Registry status unestablished.**
- **Trigger/exposure only:** the weekly **U.S. Drought Monitor**, published jointly by the National Drought Mitigation Center, USDA, and NOAA, for county D2+ status. It is not an outcome of the provision. **Registry: Registry status unestablished.**
- **Honest gap:** No recurring national official series was identified for acre-feet of consumptive use permanently retired, water rights retired, CRP acres actually emergency-hayed or grazed, forage obtained, or resulting wildlife-cover damage. **No tracked series.**

**Conditional-cell candidates**

- `P(FSA CREP enrolled acres and contract count follow path e_t | enactment vs non-enactment)`
- `P(NASS irrigated acres and water applied in a fixed panel of pre-enactment CREP States or published water-resource regions at each Irrigation and Water Management Survey release | enactment vs non-enactment)`

There is no defensible direct conditional cell for realized emergency haying or its habitat effect until USDA publishes a stable use-and-acreage series. D2+ exposure should be preregistered as a conditioning variable, not substituted for use.

### 3. §2401(2): the literal FY2028 conservation-funding cliff

**Provision and operative language**

Section 2401, “Funding,” replaces the first funding sequence in Food Security Act §1241(a)(3) with:

> “$2,500,000,000 for fiscal year 2027”; “$2,600,000 for fiscal year 2028”; “$2,700,000,000 for fiscal year 2029”; “$2,900,000,000 for fiscal year 2030”; and “$3,255,000,000 for fiscal year 2031.”

The $2,600,000 figure is the literal supplied text. This report does not silently turn it into $2.6 billion. The codified paragraph/program crosswalk should be verified against the underlying statute before enrollment in a registry; the surrounding title and conventional cross-reference identify this as the EQIP funding line, but the amendatory extract itself does not restate the program label.

**Imputed goals [CONFIRM]**

1. Increase the affected conservation program’s resources on a rising path through FY2031.
2. **Confirm urgently:** Was FY2028 intended to be `$2,600,000,000`?

**Likely effects [TOLD REGARDLESS]**

- **Adversarial mechanism — literal statutory cliff:** If enacted exactly as supplied, the FY2028 amount is about 99.9 percent below FY2027 and then rebounds by more than one thousandfold in FY2029. Agencies cannot cure missing zeroes through implementation guidance.
- **Pipeline disruption:** A one-year collapse would force deferrals, State allocation changes, staff and partner underutilization, and a bulge of demand in FY2029. Multiyear practice planning would not match the statutory funding path.
- **Distribution:** Scarce FY2028 dollars would intensify ranking effects. High-capacity applicants and States with ready-to-obligate projects would be better positioned to capture the residual funds.
- **Forecast risk:** Treating the number as an obvious typo rather than as law would make both budget and outcome forecasts wrong if Congress failed to correct it.

**Implementation barriers**

- **Congress bears the primary burden:** this requires a legislative correction before enactment or a later technical-corrections law.
- **NRCS bears the operational burden if it is not fixed:** it would need to unwind allocations and applicant expectations, then rebuild the pipeline for FY2029.
- **Thesis bears a version-control burden:** the registered policy must preserve whether the analyzed text is the literal draft, a manager’s amendment, or enrolled law. A forecast based on a corrected number is a different policy cell.

**Candidate outcome metrics**

- **Direct delivery:** USDA NRCS, **Financial Assistance Program Data** and the **Resource Conservation Assessment Data Viewer**, using obligations, contracts, and contracted acres for the affected program after the statutory crosswalk is confirmed. **Registry: Registry status unestablished.**
- **Federal transactions:** U.S. Treasury Bureau of the Fiscal Service, **USAspending.gov award/transaction data**, using the relevant USDA assistance listing and `federal_action_obligation`, frozen at a fixed lag after fiscal-year close. **Registry: Registry status unestablished for this program.**
- **Honest gap:** No official national series directly measures input savings or environmental benefits attributable to the funded precision-agriculture technologies in §§2201–2202. **No tracked series.**

**Conditional-cell candidates**

- `P(NRCS FY2028 obligations and new contracts under the affected §1241(a)(3)(A) program follow path q_t | enactment with the literal $2.6 million vs non-enactment)`
- `P(NRCS FY2027–31 obligations and contracted acres follow path q_t | corrected enactment vs non-enactment)`

These are separate cells. They must not be blended into one “enactment” scenario.

### 4. §§2701–2702 and 2401(3): Forest Conservation Easement Program

**Provision and operative language**

Section 2701, “Forest Conservation Easement Program,” inserts a new subtitle and directs:

> “The Secretary shall establish a program, to be known as the ‘Forest Conservation Easement Program’, for the conservation and restoration of eligible land and natural resources through the acquisition of forest land easements or forest reserve easements.”

Forest land easements protect working forests while allowing production under a forest management plan. Their ordinary Federal share is 50 percent of fair market value and may reach 75 percent for a forest of special environmental significance or land owned by a socially disadvantaged forest landowner. Forest reserve easements target listed and other at-risk species; permanent-easement plans may receive up to 100 percent of eligible restoration costs, capped at $500,000 per easement or 30-year contract. Section 2702 repeals the Healthy Forests Reserve Program but preserves existing contracts, agreements, and easements through transition rules. Section 2401 lists an FCEP path of $25 million, $50 million, $50 million, $50 million, and $65 million in FY2027–31, “to the maximum extent practicable.”

**Imputed goals [CONFIRM]**

1. Prevent conversion and fragmentation of working forests while allowing continued forest production.
2. Restore habitat for threatened, endangered, candidate, State-listed, and other at-risk species.
3. Consolidate and expand the Healthy Forests Reserve Program while improving access for Tribal and socially disadvantaged forest owners.

**Likely effects [TOLD REGARDLESS]**

- **Land protection:** Permanent and long-duration easements should reduce development conversion on enrolled parcels and preserve working-forest uses.
- **Adversarial mechanism — additionality:** Ranking may buy easements on land that was unlikely to convert, especially when inexpensive acres maximize the reported area protected. Enrolled acres can rise without a commensurate reduction in counterfactual forest loss.
- **Selection:** Priority for land with an existing forest management plan favors owners and eligible entities already able to finance planning. Separate ranking for socially disadvantaged owners is discretionary (“may”), so it does not guarantee a portfolio share.
- **Regulatory bargain:** ESA safe-harbor or similar assurances can increase participation, but they also encourage plans built around the minimum defensible net conservation benefit rather than maximum species recovery.
- **Adversarial mechanism — extraction conflict:** Forest land easements may permit subsurface mineral development under detailed conditions. “Limited and localized” effects, remediation, impervious-surface limits, and restoration all require continuing judgment; failures may emerge long after the award.
- **Distribution and capitalization:** Payment-attribution and adjusted-gross-income limits do not apply. Some subsidy will likely capitalize into land/easement values or pay owners who would have retained forest anyway.

**Implementation barriers**

- **The eligible-entity connectors appear defective.** New §1267(2) joins subparagraph (A), a State/local agency or Indian Tribe, to subparagraph (B), an organization, with “and.” Read literally, an applicant must satisfy both categories; ordinary governments and ordinary land trusts could each fail. Within subparagraph (B), the conservation-purpose, §501(c)(3), and §509 tests are in turn joined as alternatives by “or,” potentially making the organizational test too broad if the first connector is fixed alone. The intended connector pattern needs legislative confirmation; this is a program-blocking drafting issue, not something USDA can safely cure through outreach.
- **NRCS must launch two legally different easement tracks while migrating HFRP.** Different holders, terms, plans, cost shares, appraisal rules, species criteria, and enforcement rights must work in a single national program.
- **Eligible entities carry permanent obligations under short administrative agreements.** The forest-land cost-share agreement is ordinarily three to five years, while the easement is permanent or the maximum State-law duration. Monitoring and enforcement capacity must survive staff, funding, and institutional changes.
- **Appraisals and title work will bind before dollars do.** Fair-market-value determinations, severed mineral rights, Tribal land status, surveys, and lien/easement priority can stall closings. If USDA exercises §1267D(a)(2)’s authority to limit eligibility for land owned by a foreign entity or individual from a listed foreign-adversary country, the resulting ownership screening adds another burden; the text permits that limit but does not categorically impose it.
- **Species and carbon claims lack a required public protocol.** The statute uses “measurably” improved species well-being and permits carbon sequestration as a consideration, but it does not prescribe a recurring public measurement method.
- **The portfolio is small relative to the mandate.** The listed path totals up to $240 million over five years, “to the maximum extent practicable,” for acquisition, restoration, planning, technical assistance, monitoring, and transition, with no acreage target.

**Candidate outcome metrics**

- **Legacy implementation baseline:** USDA NRCS, **Easement Program Data / Easement Program Data Download**, for published HFRP records. Start with the pre-enactment HFRP inventory and deduplicate by a stable agreement/easement identifier. The bill deems land already enrolled in HFRP to be enrolled in FCEP, so later summing HFRP and FCEP labels without record-level deduplication can count the same land twice. **Registry: legacy HFRP-field status unestablished.**
- **Downstream landscape outcome:** U.S. Geological Survey, **Annual NLCD Land Cover Change**. Use archived Collection 1.2, which ends with observation year 2025, only to fix the pre-enactment forest-county panel and baseline. Define observation year t from the first Annual NLCD release containing year t, captured at a fixed lag; alternatively preregister one common future vintage after the full horizon, but do not mix the two revision rules. “Forest-to-developed acreage” is an analyst-derived measure, so freeze the source and destination classes, pixel-area calculation, county-boundary version, and transition treatment. Annual NLCD’s CONUS coverage makes it unsuitable as a nationwide FCEP measure that includes Alaska. Forest-to-nonforest is a weaker alternative because it can reflect harvest, temporary disturbance, or classification change rather than permanent conversion. **Registry: Registry status unestablished.**
- **Honest implementation gap:** No officially published FCEP field or series exists today. Do not assume that a future download will contain acquisition-payment dollars, restoration fields, or stable program/easement-type codes. **No tracked series.**
- **Honest gap:** No recurring official, program-linked national series measures working-forest viability, fragmentation avoided, easement-level habitat quality, species recovery, or carbon sequestration. **No tracked series.**

**Conditional-cell candidates**

- `P(NRCS publishes a stable FCEP program/easement-type field with unique identifiers and closed acres by date d | enactment)` — a one-sided implementation forecast; the non-enactment observation is missing, not zero.
- Conditional on that publication protocol: `P(cumulative unique acres in the pre-enactment HFRP inventory plus genuinely new FCEP forest-reserve closures follow path f_t | enactment)`. Until then this is not first-print resolvable.
- `P(analyst-derived Annual NLCD forest-to-developed acreage, using fixed class/pixel/boundary rules and the first release containing year t, follows path l_t in a fixed pre-enactment forest-county panel | enactment vs non-enactment)` — landscape-level and likely noisy, not program-attributable by itself.

### 5. §2805: State Conservation Assistance

**Provision and operative language**

Section 2805, “State Conservation Assistance,” creates FY2027–31 grants to eligible States and Indian Tribes for programs that improve soil health or wildlife habitat or address other local resource concerns. Eligibility requires an existing or new program that is:

> “meeting or exceeding performance measures established by the State for the program.”

The eligible-Indian-Tribe definition contains the parallel phrase with “the Indian Tribe.”

Applications must describe those performance measures and expected results and promise that Federal grants will supplement rather than supplant State or Tribal spending. A grant may not exceed the lesser of $5 million and 50 percent of a State program’s cost or 75 percent of a Tribal program’s cost.

**Source truncation:** the supplied extract ends mid-§2805(f), “Effect of Noncompliance.” The full sanctions, any funding provision, and the section’s closing text are not present. They are not analyzed or reconstructed here.

**Imputed goals [CONFIRM]**

1. Let States and Tribes fund locally tailored conservation priorities and delivery models.
2. Reward programs that can demonstrate results while leveraging non-Federal resources.
3. Give Tribes a higher Federal share and the choice to apply independently or through a State.

**Likely effects [TOLD REGARDLESS]**

- **Local adaptation:** The broad eligible menu—technical and financial assistance, demonstrations, outreach, monitoring, and evaluation—can support policy experimentation fitted to local soil, habitat, and production conditions.
- **Adversarial mechanism — fiscal-capacity selection:** Match requirements and the requirement to be already implementing a program favor jurisdictions with staff, revenue, and grant systems. The places most in need of startup capacity may be least able to qualify.
- **Adversarial mechanism — metric gaming and non-comparability:** Each applicant establishes its own performance measures and is eligible by meeting or exceeding those measures. Easy targets improve eligibility and renewal prospects but prevent a comparable national account of results.
- **Scale:** A $5 million cap limits Federal exposure and spreads awards, but it may be too small to justify a new administrative and audit apparatus in large States or under-resourced Tribes.
- **Crowd-out risk:** “Supplement, not supplant” language cannot by itself stop a legislature from reducing what it otherwise would have appropriated. The counterfactual budget is unobservable.

**Implementation barriers**

- **USDA must judge unlike against unlike.** “Broadly consistent” with NRCS principles and self-defined performance measures require review across heterogeneous program rules, evidence, and time horizons.
- **States and Tribes bear fixed audit and evaluation costs.** Annual expenditure audits and Secretary-timed reviews can consume a disproportionate share of a small or first-time program’s capacity.
- **USDA must police a counterfactual.** Supplement-not-supplant enforcement requires baselines, treatment of one-time funds, and legislative-budget histories that the text does not standardize.
- **The incomplete source prevents a full burden assessment.** Staff should obtain the continuation before assessing sanctions, cure periods, recovery, or total program funding.

**Candidate outcome metrics**

- **Coarse external practice measure:** USDA NASS, **Census of Agriculture / Quick Stats**, using cover-crop acres or no-till/reduced-till acres in a fixed set of jurisdictions chosen before awards. The five-year cadence, self-reporting, Tribal geography gaps, and post-program timing make this a weak primary cell. **Registry: Registry status unestablished.**
- **Honest implementation gap:** No distinct State Conservation Assistance identifier or officially published program series exists. The supplied text also creates no standardized national soil-health or wildlife-habitat measure and does not require grantee audits or evaluations to be public or comparable. NRCS conservation-effects assessments are periodic/model-based, not a clean annual first-print series. **No tracked series.**

**Conditional-cell candidates**

- `P(USDA/Treasury publishes State Conservation Assistance awards under a distinct stable identifier by date d | enactment)` — a one-sided implementation forecast; the non-enactment observation is missing, not zero.
- `P(NASS cover-crop or no-till acres in a fixed pre-enactment jurisdiction panel for the 2027 and 2032 Census of Agriculture reference years, using each first release | enactment vs non-enactment)` — slow, indirect, and not recommended as the sole success metric.

### Other Title II drafting defects surfaced by the full read

- **§2504, de minimis easement adjustments:** the permitted list includes a building-envelope boundary change that “will result in an increase in the total area of the original building envelope boundary.” Read literally, that authorizes rather than forbids increased envelope area. If “not” was intended, the defect directly changes the conservation footprint and should be corrected.
- **§2802, emergency fencing:** one sentence refers to “the cost of the repair of replacement.” The payment rule can be understood from context, but the phrase should be conformed before enactment.
- These are drafting defects, not `RESERVED` or placeholder provisions.

## Title VI — Rural Development

### 1. §6101: Streamlining Broadband Authorities / ReConnect Program

**Provision and operative language**

Section 6101, “Streamlining Broadband Authorities,” codifies the ReConnect Program in §601 of the Rural Electrification Act. It makes three distinct threshold changes: the highest-priority benchmark rises from 10/1 Mbps to 25/3 Mbps; the share of households in a proposed service territory that must lack sufficient access rises from 50 percent to 90 percent; and minimum acceptable service rises from 25/3 Mbps to 100/20 Mbps. It also prioritizes applicants with network-operating experience and networks that can:

> “easily scale speeds over time … to meet the evolving connectivity needs of households and businesses.”

It limits applicant data, permits an investment-grade bond rating in place of financial documentation, allows alternative security in place of a Federal first lien on grant-funded assets, simplifies reporting and procurement, and creates rules for areas subject to other providers’ deployment obligations. It requires use of FCC maps and interagency data sharing. A new annual USDA report must publish award distribution, counts of locations where service was made available and used, and the highest service level made available at each covered location; it does not require a public list of location identifiers. The section authorizes $100 million for each of FY2027–31.

**Imputed goals [CONFIRM]**

1. Convert ReConnect from an appropriations pilot into a durable statutory program.
2. Fund scalable rural networks while lowering application, collateral, procurement, and reporting burdens.
3. Coordinate Federal programs and avoid paying twice for the same service territory.

**Likely effects [TOLD REGARDLESS]**

- **Access and speed:** With appropriations, higher performance requirements and scale priority should increase the number of rural locations with service capable of supporting modern applications.
- **Adversarial mechanism — 90-percent eligibility cliff:** Raising the proposed-territory unserved threshold from 50 to 90 percent excludes mixed-service areas with substantial unserved pockets. Applicants may redraw boundaries around the best qualifying blocks, leaving harder interspersed locations outside viable network designs.
- **Entry:** Alternative security for grant-funded projects and less parent/affiliate documentation can widen participation. Letting rated applicants substitute an investment-grade bond rating, however, disproportionately helps large or established firms that already have ratings.
- **Adversarial mechanism — served-on-paper lockout:** For a ReConnect grant application, a territory generally counts as served when another provider has an enforceable governmental obligation to build there. A household can therefore be excluded before it receives service; delayed or defaulted commitments can strand locations while blocking a competing grant award.
- **Adversarial mechanism — affordability gap:** New §608 says nothing authorizes USDA to regulate broadband rates. Availability can rise while subscriptions remain flat because price, contract terms, installation charges, or digital skills remain binding.
- **Adversarial mechanism — related-party costs:** The bill permits separate network ownership/operation and says USDA shall not unreasonably restrict procurement from affiliates. That can ease efficient corporate delivery, but it weakens arm’s-length price discipline and complicates audit of subsidized costs.
- **Federal grant performance/recovery risk:** Alternative security and later lien release reduce recipient burden but can leave the Government with less security for performance or recovery when a grant-funded project fails.

**Implementation barriers**

- **RUS must reconcile incompatible maps and award systems.** FCC Broadband Data Collection locations, NTIA and Treasury programs, State/local commitments, and RUS shapefiles differ in identifiers, vintages, speeds, challenge status, and completion milestones.
- **The deadlines are internally awkward.** The first annual report is due within 120 days, while regulations are due within 180 days; the appropriations pilot also sunsets and transfers unobligated balances at day 120. RUS must report and manage transition before the final rule deadline.
- **“Used” is harder than “available.”** RUS needs a consistent location-level adoption definition and provider data while protecting subscriber information. Installed capability, a passed location, an activated subscription, and actual use are different events.
- **Challenge and overlap decisions are case-intensive.** A searchable eligible-area database, detailed denial notices, complete shapefiles, and evidence-based challenges increase transparency but require staff, geospatial infrastructure, and appeal-quality records.

**Candidate outcome metrics**

- **Direct implementation:** U.S. Treasury Bureau of the Fiscal Service, **USAspending.gov award/transaction data**, awarding agency USDA/RUS, Assistance Listing 10.752. Keep award types separate: use `federal_action_obligation` for grants; use `original_loan_subsidy_cost` for the Federal budgetary cost of direct or guaranteed loans; and, if financing volume is the object, separately report `face_value_of_direct_loan_or_loan_guarantee`. Preserve negative actions and separate transferred unobligated balances from new awards. Freeze the result at a set lag, such as 90 days after fiscal-year close. **Registry: Existing Thesis path through the USAspending adapter**, per the brief.
- **Connectivity outcome:** Federal Communications Commission, **Broadband Data Collection Fixed Broadband Availability Data / National Broadband Map**, using the number or share of broadband-serviceable locations in a fixed rural geography lacking fixed terrestrial 100/20 service at each June/December collection. Hold a baseline BSL universe fixed, or use the FCC’s **Fabric Change Reports** to decompose added, removed, and attribute-changed locations; merely naming each new Fabric version does not make denominators longitudinally comparable. Pin the collection date, technology set, rural crosswalk, and denominator. This is provider-reported advertised availability, not verified performance, subscription, adoption, or affordability. **Registry: Registry status unestablished.**
- **Honest program-specific gap:** The bill requires a new public §601(k) USDA ReConnect annual report, but that report has not been published and is therefore not a current candidate series. It has no pre-enactment observation or assured schema. **No tracked series.**

**Conditional-cell candidates**

- `P(new ReConnect grant obligations and loan subsidy cost, kept as separate paths under a fixed fiscal action-date rule, follow paths o_t and s_t | enactment vs non-enactment)`
- `P(FCC BDC fixed-baseline rural broadband-serviceable locations lacking at least 100/20 service follow path b_t | enactment vs non-enactment)`
- `P(USDA publishes the §601(k) ReConnect report with separate made-available and used fields by its statutory deadline | enactment)` — a one-sided implementation forecast; the non-enactment observation is missing, not zero.

### 2. §6104: Last Mile Broadband Deployment / Last Acre Program

**Provision and operative language**

Section 6104, “Last Mile Broadband Deployment,” inserts a new §607, the “Last Acre Program.” Within one year USDA must establish competitive grants and loans to covered providers for 100/20 “qualifying connectivity” across unserved and underserved agricultural land, including field devices, wireless networks, towers, and retrofits. An application must describe:

> “the entire acreage in need of qualifying connectivity.”

The process publishes land from initial bids, allows incumbent challenges, and solicits competing bids. It directs USDA to select “the applicant that” both presents the lowest Federal cost and best demonstrates the ability to meet on-farm needs. Buildout may take up to four years. Recipients must use a layered cybersecurity defense and maintain a configuration-management plan. The section authorizes $25 million annually for FY2027–31 and orders NASS to add farm-site subscription, speed, and precision-agriculture questions to its surveys.

**Imputed goals [CONFIRM]**

1. Extend connectivity beyond the farmhouse to fields, equipment, sensors, livestock facilities, and mobile agricultural uses.
2. Enable precision-agriculture adoption, prioritizing remote and unserved acreage.
3. Use competition, milestones, sanctions, and cybersecurity conditions to control cost and performance risk.

**Likely effects [TOLD REGARDLESS]**

- **Production technology:** Connected irrigation, machinery, sensors, and farm offices can increase precision-agriculture adoption and reduce some input, labor, and monitoring costs.
- **Adversarial mechanism — strategic delay:** A provider gets 45 business days to challenge, while USDA’s deadline to adjudicate runs 90 business days from the original posting date and therefore overlaps that challenge window; competing bidders then get 120 days, USDA gets another 30 business days to evaluate, and no award may issue before all challenges are resolved. An incumbent can delay an entrant even when claimed service is marginal.
- **Adversarial mechanism — map mismatch:** FCC maps describe broadband-serviceable locations, principally structures, while this program asks whether an entire farm’s acreage, devices, and mobility needs are served. A mapped farmhouse can coexist with dead zones across fields.
- **Adversarial mechanism — network fragmentation:** Funds may not serve a residence already shown as serviceable or provide commercial service to surrounding areas outside eligible land. Preventing duplication can also eliminate shared-network revenue and require artificial network or accounting boundaries, weakening the business case for remote builds.
- **Reverse-auction risk:** The conjunctive lowest-cost and best-capability tests encourage aggressive bidding; an apparent winner can later produce quality shortfalls, change requests, or sanctions.
- **Match and documentation:** A 20 percent non-Federal share can screen out cash-poor farms. USDA may raise the Federal share to 90 percent for a limited-resource farmer or rancher, but that reduction is discretionary; proving the status requires two years of farm-sales and household-income information.

**Implementation barriers**

- **USDA must invent an acreage-level service test.** A 100/20 speed at one point does not establish capacity, latency, uptime, or mobility across an entire parcel. Drive testing, device testing, or coverage modeling is not specified.
- **The bid-selection connector can block an award.** The text requires one applicant to be both lowest-cost and the best demonstration of capability, but supplies no rule when different bidders win those tests and no tie-breaking or tradeoff method. USDA cannot safely turn the conjunction into weighted factors without legislative or regulatory risk.
- **The portal is both a procurement and privacy system.** It must identify land to potential bidders without disclosing protected farm or proprietary business information, then maintain challenge-quality evidence.
- **Providers bear a bespoke application cost for small awards.** Parcel-specific engineering, farm engagement, maps, cybersecurity certification, and four-year milestones may cost more than the expected subsidy on difficult properties.
- **Cybersecurity terms are underspecified.** “Layered defense strategy” and a “regularly updated” plan have no incorporated standard, audit interval, or minimum control set.

**Candidate outcome metrics**

- **Farm connectivity:** USDA NASS, **Technology Use (Farm Computer Usage and Ownership)**, for existing computer, internet-access, connection-method, and internet-use fields. It does not supply the existing precision-agriculture measure. The bill-created farm-site subscription and upload/download fields have not yet been published and are not current candidate series. **Registry: Registry status unestablished for existing fields.**
- **Precision-agriculture adoption:** USDA NASS, **2022 Census of Agriculture, Table 41**, for the count/share of farms reporting use of precision-agriculture practices. This item was new for 2022—2017 is not a baseline—and has a five-year Census cadence. It is distinct from the bill-created question conditioned on a broadband subscription being used for precision agriculture, which has not been published. **Registry: Registry status unestablished.**
- **Honest program-process gap:** The bill requires a future public §607(i) USDA annual report covering initial-bid parcels, challenges and dispositions, competing bids, and amounts awarded. It has not been published, and even when published it need not report completed buildout, served acreage, tested speed, uptime, subscriptions, or precision-agriculture use. **No tracked series.**
- **Honest gap:** FCC BDC data do not measure coverage across farm acreage or devices. No recurring official series currently measures agricultural acres with reliable 100/20 field connectivity, realized precision-agriculture connectivity, or uptime. **No tracked series.**

**Conditional-cell candidates**

- `P(NASS share of farms reporting internet access follows path n_t | enactment vs non-enactment)` — comparable but too broad to be a stand-alone Last Acre outcome.
- `P(NASS Census of Agriculture count/share of farms using precision-agriculture practices in the 2027 reference year, from its first release, relative to the fixed 2022 baseline follows path p_t | enactment vs non-enactment)` — only one pre-enactment observation and a five-year cadence.
- `P(NASS publishes the bill-created farm-site subscription, speed, and broadband-conditioned precision-agriculture-use fields by date d | enactment)` — a one-sided measurement-availability forecast; do not splice those fields into the existing Census item.
- `P(USDA publishes the §607(i) Last Acre report with initial-bid, challenge, and award fields by date d | enactment)` — a one-sided implementation forecast; the non-enactment observation is missing, not zero. Treat future bill-created survey fields the same way until they have an observed release.

No direct outcome cell should be described as resolved until USDA or another official publisher releases completed-acreage, tested-speed, uptime, and use data.

### 3. §6206: Rural Water and Wastewater Cybersecurity Circuit Rider Program

**Provision and operative language**

Section 6206 creates a circuit-rider program, structured like the existing water circuit-rider authority, to provide rapid cyber assessments, reasonable protocols, help with inadequate protection plans, and documentation of protection for rural water supplies. Providers must have:

> “the necessary experience and certification to effectively carry out the activities … as determined by the Secretary.”

Funded entities report annually to USDA which utilities and communities they served and which activities they performed. The section authorizes $10 million in each of FY2027–31 and permits essential work to continue during a funding lapse using previously appropriated unobligated balances.

**Imputed goals [CONFIRM]**

1. Give small rural utilities access to cyber expertise they cannot economically retain on staff.
2. Identify vulnerabilities quickly and move utilities toward defensible protocols and response capacity.
3. Keep work necessary to prevent imminent harm operating during a shutdown.

**Likely effects [TOLD REGARDLESS]**

- **Capacity:** Shared specialists can raise baseline cyber hygiene, incident planning, and awareness at utilities with very small staffs.
- **Adversarial mechanism — assessment without remediation:** The statute funds assessments and assistance but sets no remediation deadline or capital funding rule. It can produce a growing inventory of known vulnerabilities without the money, downtime, or staff to fix them.
- **Adversarial mechanism — specialist capture:** A narrow pool of certified cyber and water-system professionals can absorb much of a small national authorization through travel and consulting costs, leaving sparse repeat coverage.
- **Information risk:** Detailed vulnerability records held by circuit riders or utilities are operationally useful but sensitive. The required USDA report covers utilities/communities served and activities performed, not detailed findings; a centralized Federal “threat map” risk arises only if USDA separately requires or receives granular assessment records.
- **Thin accountability:** Required reports count utilities and activities, not reduced vulnerabilities, response time, incidents, or service continuity.

**Implementation barriers**

- **USDA must define the credential market.** “Necessary experience and certification” does not identify acceptable cyber, control-system, or operator credentials, reciprocity, conflicts, or continuing education.
- **Rural utilities bear remediation and coordination burdens.** Staff must grant system access, validate inventories, schedule downtime, procure fixes, and maintain protocols after a rider leaves.
- **Scale breaks at follow-through.** A rapid first assessment can be standardized; remediation across legacy control systems, unsupported software, vendor contracts, and scarce operators cannot.
- **The shutdown carve-out is narrower than it sounds.** Work must be necessary to prevent imminent harm and can use only previously appropriated unobligated balances; someone must make and document that classification during the lapse.

**Candidate outcome metrics**

- **Not a substitute:** EPA’s **ECHO SDWA Dataset** and **EPA/State Drinking Water Dashboard**, sourced from SDWIS, track regulatory compliance, not cyber incidents or readiness.
- **Unpublished administrative data:** annual grantee submissions to USDA will identify utilities/communities served and activities performed, but the text does not require USDA to publish them, standardize a denominator, or report outcomes.
- **Honest gap:** No recurring, officially published national series was identified for rural water cyber incidents, vulnerability closure, readiness, recovery time, or cyber-caused outages. **No tracked series.**

**Conditional-cell candidates**

- No defensible public outcome cell exists now.
- `P(USDA publishes standardized circuit-rider coverage and remediation-follow-up fields by date d | enactment)` is a possible one-sided measurement-availability forecast. Without that publication protocol, a coverage or remediation outcome cell is not resolvable and should not be registered.

### 4. §§6201, 6203, 6210, and 6213: rural water access, regionalization, and affordability finance

**Provision and operative language**

Section 6201, “Water, Waste Disposal, and Wastewater Facility Grants,” lets demonstrated-need grants cover up to 100 percent of the cost of developing a complete application and raises specified project limits and authorizations. Section 6203, “Rural Water, Wastewater, and Waste Disposal Facility Direct Loans,” gives highest priority to a qualifying direct-loan or grant application:

> “in a low-income rural community with a population of less than 10,000.”

Section 6210, “Assistance to Provide Water and Wastewater Services in Financially Distressed Rural Areas,” lets an experienced nearby association serve a distressed system that voluntarily agrees, including through governance/management consolidation or a regional partnership. Only the distressed system’s population counts for eligibility after consolidation, and its financial assistance must benefit residents of that service area.

Section 6213, “Additional Assistance for Rural Water Systems,” permits grants up to 75 percent, zero-percent loans, one-percent loans for up to 100 percent of project cost, refinancing, and forgiveness of principal or interest on existing loans. USDA must establish either a residential affordability indicator based on average household cost as a percentage of median household income or distress factors.

**Imputed goals [CONFIRM]**

1. Help low-income communities clear the application and match barriers to water and wastewater capital.
2. Preserve safe service when a small system lacks financial, technical, or managerial capacity.
3. Create economies of scale through voluntary regionalization and lower rates or debt burdens through flexible finance.

**Likely effects [TOLD REGARDLESS]**

- **Access and compliance:** Up-front application support and concessionary finance should move some previously infeasible projects into the pipeline and help systems address health-based deficiencies.
- **Scale economies:** A capable neighboring association can spread operators, procurement, billing, compliance, and emergency capacity over a larger base.
- **Adversarial mechanism — governance holdout:** Participation is voluntary. Distressed-system leaders or customers may resist loss of control; a stronger neighbor may demand protection against inherited liabilities. The systems with the greatest need can remain orphaned.
- **Adversarial mechanism — cost shifting:** Customers of the stronger association can inherit operating or capital risk. Conversely, the rule that §6210 financial assistance benefit only residents of the distressed service area forces difficult cost allocation across an integrated system and can deter the stronger partner.
- **Eligibility-boundary effects:** Counting only the distressed service area’s population prevents a regional merger from automatically losing eligibility. It also encourages transaction structures and boundary choices designed to preserve rural status.
- **Adversarial mechanism — debt-relief expectations:** Discretionary forgiveness can save a failing system, but repeated use may weaken incentives to maintain reserves or set adequate rates and can appear to penalize systems that acted earlier.
- **Distribution hidden by averages:** Average cost as a share of median income can label a system affordable while its lowest-income households face severe burdens.

**Implementation barriers**

- **USDA must define threshold terms:** “low-income,” “economically distressed,” “contiguous,” “in the locality,” “reasonable user rates,” and financial/managerial incapacity all drive eligibility but lack a common operational test here.
- **Applicants face State-law and infrastructure integration:** utility commission approval, debt covenants, labor and operator licenses, asset condition, rate harmonization, governance, and interconnection engineering can outlast the Federal award cycle.
- **Integrated systems need auditable cost allocation:** §6210 restricts financial assistance under its subparagraph (B)(i)—not the separate technical-assistance grants—to the distressed-area residents’ benefit even when facilities and staff serve both systems.
- **The flexible authorities do not reserve a funding pool.** Regionalization, refinancing, forgiveness, and concessionary loans compete for available rural-water program resources; statutory eligibility does not ensure an award.
- **Data identifiers do not align:** USDA borrower and award records must be crosswalked to EPA public-water-system IDs and service areas; county location is not the same as the population actually served.
- **Neither affordability nor regionalization is required to be published as a standard series.**

**Candidate outcome metrics**

- **Program delivery:** U.S. Treasury, **USAspending.gov award/transaction data**, USDA/RUS, Assistance Listing 10.760. Keep grant `federal_action_obligation`, direct-loan `original_loan_subsidy_cost`, and `face_value_of_direct_loan_or_loan_guarantee` as separate series rather than pooling Federal budgetary cost and financing volume. Loan modifications or forgiveness may not be consistently observable. **Registry: Registry status unestablished.**
- **Public-water outcome:** Environmental Protection Agency, **ECHO SDWA Dataset** and **EPA/State Drinking Water Dashboard**, sourced from SDWIS, using the share of active community water systems with at least one health-based violation in calendar year t. “Rural” is not a directly published EPA field: it requires a preregistered analyst crosswalk from system/service-area geography to a fixed rural definition. Archive a dated extract; preregister system-weighted versus population-weighted denominators and late corrections. Private wells are excluded. **Registry: Registry status unestablished.**
- **Capital-need context:** EPA, **Drinking Water Infrastructure Needs Survey and Assessment**. It is official and useful for scale, but periodic and too slow for a primary near-term first-print forecast. **Registry: Registry status unestablished.**
- **Honest gap:** No recurring official national series measures rural household water bills as a share of income at the service-area level. USDA’s new affordability indicator is not required to be public. **No tracked series.**

**Conditional-cell candidates**

- `P(share of active rural community water systems with at least one EPA health-based violation follows path v_t | enactment vs non-enactment)`
- `P(USDA/RUS Water and Waste Disposal grant obligations and direct-loan subsidy cost follow separate paths g_t and d_t | enactment vs non-enactment)` — implementation/input; any loan face-value path is a third, separately labeled financing measure.
- `P(share of a fixed rural public-water-system panel in EPA ECHO Serious Violator/enforcement-priority status follows path x_t | enactment vs non-enactment)`

### 5. §6216: Healthy Drinking Water Affordability Assistance / Healthy H2O

**Provision and operative language**

Section 6216 inserts §306F, the “Healthy Drinking Water Affordability Assistance Program.” Within 180 days USDA must establish grants for qualified testing and for certified point-of-use or point-of-entry treatment products, installation, replacement filters, and maintenance. Eligible end users need documented contamination and generally must be at or below 80 percent of the State or territory’s nonmetropolitan median household income, using the most recent decennial census. Private wells receive priority. The bill specifies third-party product standards and installer qualifications and authorizes $10 million annually for FY2027–31. USDA must publish an annual report with test counts, treatment types, affordability, operation, efficacy, lifecycle performance, and contamination trends.

The operative purpose is:

> “to provide grants to eligible grant recipients to improve drinking water quality of eligible end users.”

**Imputed goals [CONFIRM]**

1. Reduce rural exposure to lead, arsenic, nitrate, PFAS, and other health contaminants faster than system-scale replacement alone can.
2. Reach low-income households and private-well users that public-water programs miss.
3. Pay for testing and lifecycle maintenance, not merely the initial filter, while building evidence on rural drinking-water needs.

**Likely effects [TOLD REGARDLESS]**

- **Speed:** Point-of-use or point-of-entry treatment can reduce exposure much faster than a new public system, source remediation, or well replacement.
- **Adversarial mechanism — source-remediation substitution:** A filter grant can defer well repair, public-system extension, or upstream pollution control. It treats exposure at the tap while the source remains contaminated.
- **Adversarial mechanism — maintenance cliff:** Protection decays when filters are not replaced or systems are not maintained after assistance ends. The program may create a recurring household cost that eligible families still cannot bear.
- **Adversarial mechanism — rural vendor bottleneck:** Accredited certifiers, enumerated standards, qualified third-party installers, State/local licenses, continuing education, certified labs, and manufacturer instructions narrow the supplier pool. Travel and compliance costs can consume a large share of a small grant.
- **Targeting error:** A Statewide nonmetropolitan median and the most recent decennial census can be stale and geographically coarse. Households with similar resources can fall on opposite sides of the threshold.
- **Measurement response:** More funded baseline tests can increase detected contamination even if exposure falls. A rising contamination count may therefore indicate better discovery rather than worse water.

**Implementation barriers**

- **Applicants and nonprofits face a documentary chain:** income, rural status, a qualified baseline test or other contamination documentation satisfactory to USDA, contaminant interpretation, product/standard match, installer qualifications, installation, maintenance, and replacement components.
- **USDA must build a product-and-professional compliance regime in 180 days.** Statutory references to specific NSF/ANSI and ISO-based certification arrangements can age or change; the successor-standard clause helps but still requires active determinations.
- **Private household data are sensitive.** Water-test results, addresses, income, tenancy, and child-care-facility status need access controls and a clear publication aggregation rule.
- **Landlord/tenant incentives conflict.** A renter may qualify while the property owner controls plumbing and installation; the bill does not resolve consent, ownership, or post-tenancy maintenance.
- **The reporting mandate outruns the measurement design.** A “qualified water quality test” is defined as a baseline analysis; standardized post-installation tests and a fixed eligible-household denominator are not clearly required.

**Candidate outcome metrics**

- **Not substitutes:** EPA SDWIS excludes private wells; USGS **National Water Information System** water-quality samples are official but not a representative household before/after-treatment series.
- **Honest gap:** The bill requires a public §306F(g) USDA annual report with qualified-test counts and treatment/filter types, but no such product exists yet and the statute does not guarantee a standardized post-treatment contaminant-reduction field. No recurring official nationwide series measures point-of-consumption private-well contaminants before and after household treatment. **No tracked series.**

**Conditional-cell candidates**

- `P(USDA publishes the §306F(g) report with a numeric qualified-water-test field by its statutory deadline | enactment)` — a one-sided implementation forecast; the non-enactment observation is missing, not zero. Do not add a numeric product or treatment count unless USDA actually publishes one with a stable definition.

No health-improvement cell is defensible unless USDA standardizes and publishes post-treatment results and a denominator.

### 6. §§6301 and 6311: rural care-economy priorities and operating support

**Provision and operative language**

Section 6301, “Improving the Rural Care Economy; Prioritizations,” maps different FY2027–31 priorities to different programs. USDA must prioritize Distance Learning and Telemedicine projects providing substance-use-disorder or mental/behavioral-health services; Community Facilities projects developing health-care or mental/behavioral-health facilities; and, separately, Community Facilities projects developing child-care facilities. USDA may prioritize the listed child-care activities in specified rural business programs. Community Facilities child-care awards may use:

> “not more than 25 percent of the direct loan or grant funds for staffing purposes.”

At least 10 percent of Business and Industry guaranteed-loan funding must be made available to support child care and health care. Section 6301(a)(1)(B) says USDA “shall not make any reprioritizations” within the affected Community Facilities and Distance Learning and Telemedicine programs during FY2027–31. Read literally, that conflicts with §6301(a)(2)(B)’s later command that USDA make the Community Facilities child-care priority; the text does not say “other” reprioritizations.

Section 6311, “Distance Learning and Telemedicine,” permits up to 15 percent of assistance for reasonable operating and administrative expenses and requires a non-Federal match waiver for demonstrated need, substantial burden, or a federally recognized Indian Tribe.

**Imputed goals [CONFIRM]**

1. Expand rural mental-health, substance-use, telehealth, health-care, and child-care capacity.
2. Treat operating cost and match requirements—not only construction—as barriers to viable rural services.
3. Reserve credit and program priority for care infrastructure that rural labor markets and communities need.

**Likely effects [TOLD REGARDLESS]**

- **Access and take-up:** Match waivers and limited operating/staff support should help low-capacity and Tribal applicants open or sustain projects that capital-only awards would not.
- **Adversarial mechanism — zero-sum priority:** Most provisions redirect existing loan/grant programs rather than create commensurate new budget authority. More care projects can mean fewer fire, public-safety, library, utility, or other community-facility projects.
- **Adversarial mechanism — operating cliff:** One-time staffing or operating assistance can open slots or services that close when the award ends. Using debt proceeds for payroll can also weaken repayment capacity.
- **Pipeline mismatch:** A fixed 10 percent credit reservation can go underused if care projects cannot satisfy underwriting, or can displace stronger non-care projects if administrators press to fill it.
- **Adversarial mechanism — statutory freeze:** The ban on any reprioritizations through FY2031 reduces agency flexibility in a new disaster, economic shock, or emerging rural need and may collide with the same section’s later child-care instruction.
- **Eligibility lock:** One alternative child-care definition turns on providers licensed, regulated, or registered “on the date of enactment.” Later entrants must fit the separately incorporated eligibility route or risk exclusion.

**Implementation barriers**

- **USDA must stack priorities without a ranking rule.** Health care, behavioral health, child care, existing statutory priorities, and geography can all claim preference.
- **The internal reprioritization conflict needs a legislative answer.** USDA is told both to make a Community Facilities child-care priority and not to make any Community Facilities or DLT reprioritizations in the same years. Reading “any” as “any additional” would insert language that is not in the draft.
- **Underwriters must treat temporary operating support as nonrecurring.** Staffing plans need a post-award revenue source; otherwise the Federal investment creates unusable capacity.
- **State, Tribal, and territorial licensing systems differ.** USDA must verify provider status and “appropriate expertise and training” without a national child-care license.
- **The required two-year child-care evaluation lacks a fixed outcome definition, baseline, comparison group, and express publication/schema requirement.**
- **Award coding is weak for evaluation.** Official program fields may not reliably distinguish child-care or health use; free-text classification would be an analyst-created measure, not an official series.

**Candidate outcome metrics**

- **Labor-market proxy:** Bureau of Labor Statistics, **Quarterly Census of Employment and Wages (QCEW)**, NAICS 624410 Child Day Care Services, using annual-average establishments and employment in a fixed pre-enactment rural-county panel from the first annual QCEW release for calendar year t. Freeze the release lag and missing/suppression treatment; do not interchange quarterly and annual-average paths. QCEW omits self-employed and some home providers; jobs are not child-care slots or affordability. **Registry: Registry status unestablished.**
- **Program input:** Treasury **USAspending.gov**, USDA Community Facilities Loans and Grants, Assistance Listing 10.766, and **Distance Learning and Telemedicine Loans and Grants**, Assistance Listing 10.855. Analyze current DLT grant `federal_action_obligation` separately; for Community Facilities keep grant obligations, direct-loan `original_loan_subsidy_cost`, and loan face value separate. A care-specific split is suitable only if an official structured purpose code exists; text mining does not become an official series merely because the source is official. **Registry: Registry status unestablished.**
- **Unregistrable care split:** Treasury **USAspending.gov**, Business and Industry Loans, Assistance Listing 10.768, can support separate total guaranteed-loan subsidy-cost and face-value series. No established structured care-sector field was identified, so it cannot currently resolve the bill’s child-care/health-care share. **No tracked series for the care-specific split.**
- **Honest gap:** No standardized recurring Federal series measures national rural child-care slots, waitlists, prices, hours, or travel time. The §6301 evaluation is not specified as a recurring public data product. **No tracked series.**

**Conditional-cell candidates**

- `P(QCEW annual-average child-day-care establishments and employment in a fixed rural-county panel, from the first annual release for calendar year t, follow path k_t | enactment vs non-enactment)`
- `P(DLT grant obligations and Community Facilities grant obligations/direct-loan subsidy cost follow separate paths j_t, c_t, and l_t | enactment vs non-enactment)` — program inputs, not care-specific unless official coding permits; do not pool loan financing with grant obligations.

Do not register a Business and Industry care-sector share unless an official structured field is published; if that occurs, specify whether the dollar measure is Federal subsidy cost or guaranteed-loan face value.

### 7. §§6302–6303: Rural Hospital Revitalization and Rural Health Care Facility Assistance

**Provision and operative language**

Section 6302 inserts §310A, directing USDA to make temporary zero-interest Community Facilities direct loans to eligible rural hospitals for replacement, renovation, or improvement. Default eligibility includes a county below 20,000 residents; a distance, Critical Access Hospital, or Rural Emergency Hospital test; at least 30 years of continuous local licensure; specified project need; and ordinarily at least 30 days cash on hand and a projected debt-service-coverage ratio of 1.2. The last financial tests may be waived for sufficient community impact. Zero interest is not a payment holiday: principal is repaid during the first five years on an amortization schedule of up to 40 years. After five years USDA assesses whether to refinance at prevailing Community Facilities rates; one renewal is available in specified circumstances.

Section 6303 broadens refinancing and technical assistance from rural hospitals to a defined set of rural health-care facilities and authorizes up to $2 million annually for technical assistance in FY2027–31. Its stated technical-assistance goals include:

> “to improve the long-term financial position and operational efficiency”; “to prevent the closure”; and “to strengthen the delivery of health care in rural areas.”

The amendments take effect when USDA’s implementing regulations do, but the text supplies no rulemaking deadline.

**Imputed goals [CONFIRM]**

1. Preserve geographically isolated hospitals by financing aging facilities at zero interest during a stabilization period.
2. Combine capital relief with operational and financial technical assistance.
3. Prevent closures and extend help to a broader rural health-care facility set.

**Likely effects [TOLD REGARDLESS]**

- **Liquidity and capital:** Five years without interest can reduce near-term debt service and make deferred renovation feasible, but scheduled principal repayment begins immediately; the provision does not preserve the full loan amount as operating cash for five years.
- **Adversarial mechanism — need versus bankability:** Requiring 30 days cash and a 1.2 projected debt-service ratio can exclude hospitals closest to failure. A discretionary community-impact waiver favors applicants able to document impacts and navigate USDA underwriting.
- **Eligibility cliffs and use restriction:** A county population of 19,999 versus 20,001, distance tests, and 30 continuous licensed years can separate otherwise similar hospitals, including newer but essential facilities. Separately, loan proceeds may not be used for facilities significantly improved during the preceding ten years; that is a project-use restriction, not a categorical bar on hospital eligibility.
- **Adversarial mechanism — refinancing cliff:** The loan can move from zero interest to prevailing rates after five years, or during or after a one-time renewal of up to five additional years. An interest-rate-protection renewal may refinance during that period once the applicable rate is 2.5 percent or less. Higher debt service may arrive before patient volume, reimbursement, or workforce conditions improve.
- **Capital substitution:** A new building cannot by itself solve weak reimbursement, clinician shortages, low volume, payer mix, or management problems. It can lock a declining system into excess fixed capacity.
- **Portfolio crowd-out:** Section 6302 uses the existing Community Facilities direct-loan program and supplies no separate loan pool in the extracted text. Zero-interest hospital loans can consume loan-subsidy or portfolio capacity otherwise available to other rural community facilities.
- **Path dependence:** §6303 gives priority to existing USDA borrowers and grant recipients, reinforcing access for facilities already inside USDA’s administrative network.

**Implementation barriers**

- **USDA must verify unusual eligibility facts:** historical licensure, nearest-hospital distance and terrain, prior capital improvement, payer mix, cash, debt coverage, and “meaningful economic impact.”
- **Underwriting and health regulation use different records.** USDA must reconcile applications with CMS provider numbers, cost reports, facility conversions, and State licenses.
- **Year-five reassessment creates a large future queue.** Every loan needs a reproducible stability test, renewal or refinancing decision, and appeal-quality record.
- **§6303 has no regulatory deadline.** Because effectiveness waits for the regulations, delay can postpone the entire expanded refinancing/technical-assistance scheme without violating a date certain.
- **Committee reports are not a clean public series.** §6303 requires annual project descriptions, outcomes, costs, and effectiveness reports to Congress, but does not expressly require a standardized machine-readable public release.

**Candidate outcome metrics**

- **Facility continuity:** Centers for Medicare & Medicaid Services, **Provider of Services File — Quality Improvement and Evaluation System (QIES)**, using active hospital, Critical Access Hospital, and Rural Emergency Hospital status for a fixed, pre-specified eligible-county/facility panel. Archive each first release and crosswalk CMS Certification Numbers so conversion to Rural Emergency Hospital status is not counted as closure. **Registry: Registry status unestablished.**
- **Financial/operating outcome:** CMS, annual **Hospital Provider Cost Report**, for financial-statement components, inpatient/outpatient volume, and payer mix. Total margin and days cash are analyst-derived ratios, not published fields, so preregister the exact worksheet lines, formula, fiscal-period treatment, missing-data rule, and the first archived annual dataset release—not the hospital’s first filing. Cost reports are revised and resubmitted. **Registry: Registry status unestablished.**
- **Unresolved program input:** Treasury **USAspending.gov**, Community Facilities Assistance Listing 10.766, publishes the broader portfolio, but no established structured hospital-purpose field was identified. Free-text descriptions are not official coding. If USDA creates a field, report `original_loan_subsidy_cost` as Federal budgetary cost and `face_value_of_direct_loan_or_loan_guarantee` separately as financing volume. **No tracked hospital-specific series.**
- **Honest gap:** CMS does not publish a single clean recurring “rural hospital closure” series; current provider status, termination, and conversion must be carefully distinguished. **No tracked series for the clean closure construct.**

**Conditional-cell candidates**

- `P(CMS active eligible rural-hospital/CAH/REH facility count follows path m_t | enactment vs non-enactment)`
- `P(total margin derived by a fixed formula and service volume from the first archived annual CMS Hospital Provider Cost Report release for a fixed eligible-hospital panel follow path i_t | enactment vs non-enactment)`

No hospital-loan input cell should be registered until USDA publishes an official structured hospital-purpose field under Assistance Listing 10.766.

## Cross-title implementation findings

Five design patterns recur across the two titles:

1. **The bill often lowers one barrier by creating another verification layer.** Examples include simpler ReConnect applications paired with multi-program overlap checks, Last Acre subsidies paired with provider challenges and income proof, and Healthy H2O access paired with lab/product/installer certification chains.
2. **Hard thresholds create cliffs and strategic behavior.** D2 drought status, 25/3 and 100/20 broadband definitions, rural population cutoffs, income ratios, hospital distance, grant caps, and match rates all turn continuous need into binary eligibility.
3. **Local flexibility reduces comparability.** State-defined conservation metrics, USDA-determined water distress, site-specific CRP findings, and flexible easement terms may improve fit but make national evaluation harder.
4. **Policy-created measurement is not a symmetric forecast outcome.** ReConnect and Last Acre reports, new NASS questions, Healthy H2O reports, and grantee submissions may exist only after enactment. Their non-enactment path is missing, not zero.
5. **Several intended outcomes lack an official recurring series.** Where this report says “No tracked series,” the correct next step is a data-publication requirement or a narrower implementation cell—not an invented proxy.

## Recommended first Thesis registrations

| Priority | Metric and official product | What it resolves | Thesis status from supplied materials | Principal preregistration risk |
|---|---|---|---|---|
| 1 | ReConnect grant obligations and loan subsidy cost, kept separate, Treasury **USAspending.gov**, AL 10.752 | Federal implementation/input | **Existing Thesis path** via USAspending adapter | Award-type separation, negative actions, action-date rule, pilot/statutory code continuity, live revisions |
| 2 | Active CRP enrolled acres at September 30, USDA FSA **CRP Monthly Summary** | Direct program participation | **Not yet in Thesis** | Archive/freeze first publication; category definitions; cap is not target |
| 3 | Fixed-baseline rural BSLs lacking fixed terrestrial 100/20, FCC **Broadband Data Collection** plus **Fabric Change Reports** | Broadband availability | Registry status unestablished | Fabric churn, challenges, rural crosswalk, advertised availability, price/adoption gap |
| 4 | Analyst-derived forest-to-developed acres from USGS **Annual NLCD Land Cover Change** in a fixed forest-county panel | Downstream landscape outcome | Registry status unestablished | Collection 1.2 is baseline only; fixed transition/pixel/boundary rules; CONUS only; revisions; not program-attributable |
| 5 | Analyst-crosswalked rural community-water-system health-based-violation rate, EPA **ECHO SDWA Dataset** | Public-water compliance outcome | Registry status unestablished | Dated snapshots, late corrections, service-area crosswalk, denominator, private-well exclusion |
| 6 | Rural child-day-care establishments/employment, BLS **QCEW** | Care-economy proxy | Registry status unestablished | Suppression, revisions, home/self-employed exclusions, jobs are not slots |
| 7 | Active eligible rural hospitals, CMS **Provider of Services File — Quality Improvement and Evaluation System (QIES)** | Facility continuity | Registry status unestablished | Certification lag, CCN changes, REH conversion versus closure |

The first three are the strongest near-term cells. The FCEP, water, child-care, and hospital cells are usable only with the stated caveats and should not be presented as program-attributable without a design that fixes geography and exposure before outcomes are observed.

## Outcomes that should not yet be registered as if a tracked series existed

- CRP acres actually emergency-hayed or grazed, forage obtained, or wildlife-cover damage.
- Consumptive water rights or acre-feet permanently retired through CREP.
- Last Acre whole-field/device coverage, tested 100/20 performance, uptime, or realized precision-agriculture use.
- A standardized national State Conservation Assistance soil-health or habitat result.
- Rural water-system cyber readiness, incidents, vulnerabilities closed, or cyber-caused outage duration.
- Rural household water-bill affordability at service-area resolution.
- Nationwide private-well contamination before and after household treatment.
- National rural child-care slots, waitlists, prices, hours, or travel time.
- FCEP-linked species recovery, fragmentation avoided, or carbon sequestration.

For these outcomes, the forecastable object should remain explicitly “unavailable” until an agency publishes a recurring product with a stable definition, first-release archive, geography, and denominator.
