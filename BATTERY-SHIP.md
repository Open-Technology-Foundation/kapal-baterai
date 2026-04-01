# Battery Ship Energy Transport: Feasibility Study

**Original Research:** 2026-03-24
**Revised:** 2026-04-01
**Concept:** Exporting solar electricity from NW Australia to Jakarta via ships loaded with rechargeable battery packs, as an alternative to diesel fuel shipping and submarine power cables.

---

## Table of Contents

1. [Reference Vessel](#1-reference-vessel)
2. [Fuel Capacity and Electricity from Diesel](#2-fuel-capacity-and-electricity-from-diesel)
3. [Grid-Scale Battery Technology](#3-grid-scale-battery-technology)
4. [Fitting Batteries into a Cargo Ship](#4-fitting-batteries-into-a-cargo-ship)
5. [Charging Infrastructure: Pilbara Solar](#5-charging-infrastructure-pilbara-solar)
6. [The Battery Tanker Fleet Model](#6-the-battery-tanker-fleet-model)
7. [Economic Analysis](#7-economic-analysis)
8. [Submarine Cable Alternative](#8-submarine-cable-alternative)
9. [Three-Way Comparison](#9-three-way-comparison)
10. [Maritime Regulatory Environment](#10-maritime-regulatory-environment)
11. [Onboard Solar and Wind Generation](#11-onboard-solar-and-wind-generation)
12. [Conclusions](#12-conclusions)

---

## 1. Reference Vessel

A Handymax/Supramax class bulk carrier was selected as the reference vessel, representing the "average" diesel cargo ship in global trade.

| Parameter | Value |
|-----------|-------|
| Length overall | ~170-190 m |
| Beam (width) | ~32 m |
| Draft | ~12-14 m |
| Deadweight tonnage (DWT) | ~50,000 t |
| Cargo holds | 5 |
| Total grain volume | ~60,000-80,000 m³ |
| Service speed | ~14 knots |
| Propulsion | Slow-speed two-stroke diesel (HFO) |
| Auxiliary engines | 3 × four-stroke diesel generators (MDO) |

These vessels are the workhorses of global trade — large enough to carry significant cargo but small enough to enter most ports worldwide. As of 2025, Supramax/Ultramax vessels have a newbuild cost of approximately $30-40M.

### Cargo Hold Internal Dimensions (per hold, estimated)

| Feature | Dimension |
|---------|-----------|
| Tank top width (floor) | ~18-20 m |
| Hold length | ~18-22 m (avg ~20 m) |
| Usable height (tank top to hatch) | ~14-15 m |
| Hatch opening | ~15 m × 17-18 m |
| Floor area per hold | ~360-400 m² |
| Grain volume per hold | ~12,000-16,000 m³ |

---

## 2. Fuel Capacity and Electricity from Diesel

### Ship's Own Fuel Supply

| Fuel Type | Capacity | Approx. Weight |
|-----------|----------|----------------|
| Heavy Fuel Oil (HFO) | ~1,500 m³ | ~1,425 mt |
| Marine Diesel Oil (MDO) | ~100-150 m³ | ~85-130 mt |
| **Total** | ~1,600-1,650 m³ | **~1,500-1,550 mt** |

### Daily Consumption at Sea

- Laden (loaded): ~25-30 mt/day at ~14 knots
- Ballast (empty): ~20-25 mt/day at ~14 knots
- Range: ~50-55 days at sea on full fuel

### Diesel as Cargo: Electricity Generation

If the ship carries 48,000 mt of diesel as cargo (after reserving ~1,500 mt for propulsion and ~500 mt for stores/water), the electricity yield depends on the generator type:

| Generator Type | Efficiency (SFC) | Electrical Output |
|---------------|-------------------|-------------------|
| Small (20-200 kW) | ~250-280 g/kWh (~30-34%) | ~172 GWh |
| Medium (500-1,000 kW) | ~220-240 g/kWh (~35-38%) | ~205 GWh |
| Large industrial (1-2.5 MW) | ~210-230 g/kWh (~37-40%) | ~222 GWh |
| **Power plant grade (5+ MW)** | **~190-210 g/kWh (~40-44%)** | **~239 GWh** |

**Baseline: One shipload of diesel = ~239 GWh of electricity** (at power-plant efficiency).

### Fuel Price Context (2026)

Marine fuel prices are volatile and affect all comparisons in this study. Reference prices used throughout:

| Fuel | Price ($/mt) | Basis |
|------|-------------|-------|
| Diesel cargo | ~$800 | Wholesale gasoil, Q1 2026 |
| MDO (ship fuel) | ~$900 | Singapore bunker hub, Q1 2026 |
| HFO 380 CST | ~$450-585 | Global average |

Brent crude averaged ~$75/bbl in 2025, with the EIA projecting $55-75/bbl for 2026. Diesel cargo prices track crude with a $20-30/bbl premium. The sensitivity analysis in Section 7 models fuel escalation at 3-5% per year to account for long-term trends.

### Onboard Electrical Generation (from MDO)

The ship's own auxiliary generators (3 × ~800-1,200 kW) produce electrical power for onboard systems:

| Operating Mode | Electrical Load |
|----------------|----------------|
| At quay (port) | ~230 kW |
| At sea (hotel load) | ~280-400 kW |
| Cargo operations | ~800-1,500 kW |
| Peak (thrusters + cargo) | ~2,000+ kW |

From ~100-130 mt of MDO, the ship can generate ~500-650 MWh of electricity, sufficient for ~70-90 days of onboard electrical needs.

---

## 3. Grid-Scale Battery Technology

### Current Technology (2025-2026)

Data sourced from Tesla datasheets, manufacturer announcements, Wikipedia, and BloombergNEF (December 2025 survey).

| Battery | Capacity | Power | Dimensions (L × W × H) | Weight | RTE | Cost | Cycle Life |
|---------|----------|-------|------------------------|--------|-----|------|-----------|
| Tesla Megapack 2 | 3.854 MWh | 1.927 MW | 7.25 × 1.63 × 2.51 m | 30,500 kg | 92-94% | ~$1.47M | 3,000-5,000+ |
| Tesla Megapack 2XL | 3.916 MWh | 1.927 MW | 8.80 × 2.79 × 1.65 m | 38,100 kg | 85-90% | ~$1.39M | 3,000-5,000+ |
| Tesla Megapack 3 | 5.0 MWh | TBC | TBC | 39,000 kg | 91% | TBC | 10,000+ |
| BYD MC Cube-T | 6.432 MWh | TBC | 20-ft container | ~45,000 kg | TBC | TBC | 6,000+ |
| CATL TENER | 6.25 MWh | TBC | 20-ft container | ~40,000 kg | TBC | TBC | 5+ yrs zero degradation |
| CATL TENER Stack | 9.0 MWh | TBC | Stacked half-containers (4.7 m H) | ~72,000 kg | TBC | TBC | TBC |

**Notes on individual products:**

- **Megapack 3** was announced in September 2025 and uses new 2.8-litre LFP cells. Expected to begin shipping from Tesla's Houston factory in H2 2026. Its 25-year projected lifetime and 10,000+ cycle rating make it particularly relevant for the deep-cycling required by energy transport. Tesla also announced Megablock (20 MWh, 4× Megapack 3 with integrated transformer), planned for H2 2026.
- **BYD MC Cube-T** uses BYD's Blade battery (LFP) with Cell-to-System (CTS) integration, eliminating conventional module-level packaging. BYD has also announced a 2.3 MWh sodium-ion container system.
- **CATL TENER Stack** (May 2025) achieves 45% better volume utilisation and 50% higher energy density than traditional 20-ft container systems by stacking two half-height containers. Set for mass production.
- **Fluence Smartstack**: Up to 7.5 MWh with ~30% higher density than previous AC-based systems.

### Battery Pack Pricing

| Metric | $/kWh | Source |
|--------|-------|--------|
| Stationary storage packs (average) | **$70** | BNEF Dec 2025 |
| LFP packs (all segments) | $81 | BNEF Dec 2025 |
| NMC packs (all segments) | $128 | BNEF Dec 2025 |
| Lowest observed LFP pack (stationary) | **$50** | BNEF Dec 2025 |
| Lowest observed LFP cell | **$36** | BNEF Dec 2025 |
| Overall Li-ion average (all segments) | $108 | BNEF Dec 2025 |

The $70/kWh stationary storage average represents a **45% decline from 2024**, driven primarily by Chinese manufacturing overcapacity — 557 GWh of stationary storage cell production in 2025, more than double global installations. Stationary storage is now the **lowest-priced battery segment** for the first time. The lowest observed LFP pack price of $50/kWh suggests that purpose-built transport packs, stripped of per-unit grid-integration hardware, could already approach $40-50/kWh at volume.

### Battery Energy Density: Current vs Diesel

| Storage Medium | Energy Density (MWh/tonne) |
|---------------|---------------------------|
| **Diesel fuel** (at 42% generator efficiency) | ~4.97 |
| Tesla Megapack 2 | ~0.126 |
| Tesla Megapack 3 | ~0.128 |
| CATL TENER | ~0.156 |
| BYD MC Cube-T | ~0.143 |

Diesel stores roughly **32-39× more usable energy per tonne** than the best grid batteries available today (32× vs the best-in-class CATL TENER; 39× vs the widely deployed Megapack 2).

### Next-Generation Batteries

Multiple manufacturers have demonstrated cells at 400-500 Wh/kg, but none has achieved commercial-scale production at these densities. The realistic timeline has two phases:

**Near-term (~2028-2030): Semi-solid state, ~400 Wh/kg cells**

- CATL: trial production of 20 Ah solid-state cells began November 2024; semi-solid mass production targeting 2026-2027, with full solid-state in small batches by 2027
- Samsung SDI: demonstrated 500 Wh/kg and 900 Wh/L; mass production target 2027 (luxury EVs first)
- QuantumScape: Eagle Line pilot production inaugurated February 2026; QSE-5 cell achieving 844 Wh/L
- FAW/CANEB: semi-solid-state battery exceeding 500 Wh/kg fitted into prototype cars (February 2026), with pack-level density of ~340 Wh/kg

**Advanced (~2032-2035): All-solid-state, ~500 Wh/kg cells**

- China's official battery roadmap: 400 Wh/kg by 2030, 500 Wh/kg by 2035
- McKinsey projects 400-450 Wh/kg by 2030 at ~$100/kWh
- Toyota: production approval received October 2025; first solid-state EV targeting 2028 (history of repeated delays)
- BYD: targeting 400 Wh/kg, large-scale mass production by 2030

| Metric | Current (Megapack 2, LFP) | Near-Term (~2030) | Advanced (~2033-2035) |
|--------|--------------------------|-------------------|----------------------|
| Cell energy density | ~200 Wh/kg | ~400 Wh/kg | ~500 Wh/kg |
| System energy density | ~126 Wh/kg | ~300-330 Wh/kg | ~375-425 Wh/kg |
| Volumetric (cell) | ~400 Wh/L | ~800-1,000 Wh/L | ~1,000-1,200 Wh/L |
| Projected cost (pack) | $50-70/kWh | $30-50/kWh | $20-40/kWh |
| System overhead | ~35-40% of weight | ~15-25% | ~15-20% |

**Note on lithium-sulfur:** Theoretical energy density of ~2,600 Wh/kg, but cycle life remains at 300-500 cycles — far too low for an energy transport application requiring thousands of deep cycles. Not considered further.

**Note on sodium-ion:** CATL's "Naxtra" brand (mass production from late 2025) achieves 160-200 Wh/kg at $55-70/kWh cell level. Excellent cycle life (8,000+) and temperature range (-40°C to +60°C), but lower energy density makes it less suitable for weight-constrained shipping. Could be relevant for cost-optimised stationary hubs.

### Real-World Battery Ship Projects

The battery ship concept is no longer purely theoretical:

**PowerX Battery Tanker "X" (Japan)** — the most directly comparable project to this feasibility study:

| Parameter | Value |
|-----------|-------|
| Developer | PowerX Manufacturing (Japan) |
| Partners | Imabari Shipbuilding, NYK Line, Kyushu Electric Power |
| Length | 140 m |
| Battery capacity | 241 MWh (96 containerised LFP batteries) |
| Cell lifespan | 6,000+ cycles |
| Speed | 10 knots |
| Status | Proof-of-concept vessel targeting 2025 completion, field testing 2026 |
| Subsidiary | Ocean Power Grid Inc. (maritime power transmission) |

PowerX's 241 MWh is modest — roughly one-quarter of our reference vessel's 1.1 GWh current-tech capacity, and targeting short-distance island-to-island routes in Japan. But it validates the core engineering concept: a purpose-built vessel carrying containerised batteries for grid discharge at destination ports.

**Other developments:**
- **Fleetzero (US):** $43M Series A (January 2026), modular 3.8 MWh battery units at 25% the footprint of standard containers. Hybrid conversion vessel targeting mid-2026.
- **CATL CAEV:** Nearly 900 fully electric ships delivered with CATL battery systems since 2017, including the world's largest fully electric inland passenger ship. CATL expects ocean-going battery-electric vessels within 3 years (~2028-2029).
- **Yara Birkeland:** Autonomous electric container ship, operational since 2022, 250+ voyages completed, replacing ~35,000 diesel truck journeys.
- Over **1,000 vessels worldwide** are now fitted with large battery systems for propulsion, with ~550 more on order.

---

## 4. Fitting Batteries into a Cargo Ship

### Current Technology: Megapack 2 in a Standard Bulk Carrier

**Layout per cargo hold:**
- Orientation: long side (7.25 m) across the ~19 m hold width
- 2 units across width (14.5 m, leaving ~4.5 m side access)
- 7 units along length (~17.6 m of 20 m, with access gaps)
- 14 Megapacks per level
- 4 levels vertical (~11 m of 14 m, with racking and fire clearance)
- **56 Megapacks per hold, 280 total (5 holds)**

| Metric | Single Layer | 4-Level Racking |
|--------|-------------|-----------------|
| Units per hold | 14 | 56 |
| **Total units (5 holds)** | **70** | **280** |
| Total weight | 2,135 t | 8,540 t |
| Weight capacity used | 4.4% of 48,000 t | 17.8% |
| **Energy stored** | **270 MWh** | **1,080 MWh (~1.1 GWh)** |

**Volume is the binding constraint**, not weight. The ship could carry ~1,574 Megapacks by weight alone but can only fit ~280 by volume.

### Shipload Comparison: Diesel vs Current Batteries

| | Diesel Cargo | Megapack 2 Cargo (racked) |
|---|---|---|
| Electricity delivered | **239 GWh** | **~1.1 GWh** |
| **Shiploads to match diesel** | **1** | **~217** |

### Next-Gen Purpose-Built Battery Packs

Purpose-built energy transport packs strip out per-unit inverter, HVAC, enclosure, and BMS overhead, replacing them with centralised ship-wide systems:

| Component | Megapack 2 (standalone) | Purpose-Built Shipping Pack |
|-----------|------------------------|---------------------------|
| Inverter | Per unit (heavy) | Centralised on ship |
| HVAC/cooling | Per unit | Ship-wide system |
| Enclosure | Weatherproof steel | Bare rack (inside hold) |
| BMS | Full per-unit | Lightweight per-pack + ship-level master |
| Marine monitoring | None | Vibration, tilt, salt spray sensors |
| Overhead | ~35-40% of weight | ~15-25% of weight |

Marine BMS requirements (vibration monitoring, tilt compensation, salt environment) add modest weight compared to the savings from removing individual inverters and enclosures.

**Two scenarios for next-gen shipload capacity:**

**Near-term (~2030): 400 Wh/kg cells, ~330 Wh/kg system**

| Constraint | Calculation | Result |
|-----------|------------|--------|
| Weight limit | 48,000 t × 330 Wh/kg | **15.8 GWh** |
| Volume limit | ~50,000 m³ × 800 Wh/L | ~40 GWh |
| Binding constraint | Weight | **~16 GWh per shipload** |
| Diesel comparison | 239 / 16 | **~15:1** |

**Advanced (~2033-2035): 500 Wh/kg cells, ~400 Wh/kg system**

| Constraint | Calculation | Result |
|-----------|------------|--------|
| Weight limit | 48,000 t × 400 Wh/kg | **19.2 GWh** |
| Volume limit | ~50,000 m³ × 1,000 Wh/L | ~50 GWh |
| Binding constraint | Weight | **~19 GWh per shipload** |
| Hold volume used | ~38,400 m³ | ~77% |
| Diesel comparison | 239 / 19 | **~13:1** |

**For the fleet model and economic analysis below, we use 18 GWh as the central estimate** — achievable with 450 Wh/kg cells at ~20% system overhead, consistent with the 2030-2035 window. This gives a diesel comparison ratio of ~13.5:1.

**Improvement over current tech: 16-18× (from 1.1 GWh to 16-19 GWh per shipload).**

---

## 5. Charging Infrastructure: Pilbara Solar

### Why NW Australia

| Parameter | Pilbara, WA | Indonesia (comparison) |
|-----------|------------|----------------------|
| Solar irradiance | ~2,400 kWh/m²/year | ~1,700 kWh/m²/year |
| Capacity factor (tracking) | **~28-30%** | ~15-17% |
| Cloud-free days | ~300+/year | ~180-220/year |
| Daily peak sun hours | ~7-8 hrs | ~4.5-5 hrs |

### Australian Renewable Energy Hub (AREH)

The AREH near Port Hedland is the Pilbara's flagship renewable project:

| Parameter | Value |
|-----------|-------|
| Planned capacity | **26 GW** solar + wind |
| Area | 6,500 km² |
| Status | Priority Project (WA Government, December 2024) |
| FID target | **2028** |
| First power | **2030** |
| Focus | **Green hydrogen and ammonia export** |

**Critical update:** BP withdrew from AREH in July 2025, relinquishing its 63.57% operating stake. InterContinental Energy (~26%) has assumed operational control, with CWP Global (~10%) remaining. In February 2026, ARENA awarded A$21.5 million for a pre-FEED study covering renewable hydrogen production for up to 1 GW. At full capacity, AREH aims to produce ~1.6 million tonnes of green hydrogen or ~9 million tonnes of green ammonia per year.

AREH's hydrogen/ammonia focus does not preclude electricity export via battery ships. The solar and wind infrastructure is fungible — the same megawatts that feed electrolysers could charge battery vessels, depending on market conditions and offtake agreements.

### Charging 280 Megapack 2 Units (Current Tech)

| Parameter | Value |
|-----------|-------|
| Energy to store | 1,079 MWh |
| Input needed (92% RTE) | ~1,173 MWh |
| Max charge rate (all 280 at rated) | ~540 MW |
| **Time at max rate** | **~2 hrs 10 min** |

### Renewable Source Requirements

| Solar Farm Size | Daily Output (29% CF) | Days to Charge 280 Packs |
|----------------|----------------------|--------------------------|
| 50 MW | ~348 MWh/day | ~3.4 days |
| 100 MW | ~696 MWh/day | ~1.7 days |
| 250 MW | ~1,740 MWh/day | ~16 hours |
| 500 MW | ~3,480 MWh/day | ~8 hours |

### Utility-Scale Solar Costs

IRENA's 2024 data (published July 2025) reports a global weighted average LCOE of $43/MWh for utility-scale solar, with installed costs averaging ~$691/kW (an 11% year-on-year decline). Australian-specific capex is higher at ~$850M-$1.2B per GW, reflecting remoteness and labour costs. O&M costs average $10/kW/year globally (IRENA, a 62% decline from 2010). CSIRO's GenCost 2025-26 draft notes an 8% upward revision for Australian solar capex, described as "cost volatility rather than a new trend."

---

## 6. The Battery Tanker Fleet Model

### Concept

Ships loaded with rechargeable battery packs are charged at a solar farm in the Pilbara, sail to Jakarta, plug into the city grid, discharge, then return for recharging — a continuous cycle replacing diesel tanker deliveries.

### Shipping Route: Port Hedland to Jakarta (Tanjung Priok)

| Parameter | Value |
|-----------|-------|
| Sea distance | **~1,270 nautical miles** |
| Speed | 14 knots |
| Transit time (one way) | **~3.8 days** |
| Round trip at sea | **~7.5 days** |
| Discharge time (18 GWh @ ~750 MW) | ~1 day |
| Recharge time (@ ~750 MW solar-fed) | ~1 day |
| Buffer/port ops | ~1 day |
| **Total cycle time** | **~11 days** |
| **Trips per year** | **~33** |

**Propulsion model (diesel-powered):** Ship fuel per round trip: ~200 mt HFO (~1.0 GWh thermal), charged as an operating cost. Net battery delivery: 18 GWh × 92% RTE = **~16.5 GWh** (round-trip efficiency loss only; propulsion is from the ship's own fuel tanks, not the cargo).

**Alternative (fully electric, from cargo):** ~1.5 GWh drawn from batteries for propulsion. Net delivery: 18 − 1.5 = **~16.5 GWh**. Eliminates ship fuel cost but reduces deliverable energy by ~8%.

Both models yield ~16.5 GWh net per trip. **The economic analysis below uses the diesel-propulsion model**, with ship fuel as a separate line item.

**Overall energy efficiency:** Considering both battery and propulsion losses from a primary energy perspective, the battery ship pathway loses ~16% (8% RTE + ~8% propulsion energy equivalent). This compares favourably with the 58% loss inherent in diesel generation and the ~11% loss in a submarine power cable.

### Jakarta Electricity Demand

| Parameter | Value |
|-----------|-------|
| Greater Jakarta (Jabodetabek) population | ~35 million |
| Estimated daily electricity demand | **~90 GWh/day** |
| Java-Bali grid peak demand (2024) | ~32 GW |
| Indonesia total consumption (2024) | ~371 TWh/year |
| Average electricity price | ~$73/MWh |

**Port capacity:** Tanjung Priok handled 7.6 million TEUs in 2024. Phase 2 expansion (ground broken November 2024, $1.5 billion, completing Q2 2026) will raise capacity to 12.5 million TEUs, with total port investment of $4.6 billion. Dedicated battery discharge berths would represent a minor fraction of this capacity.

### Fleet Size Requirements

With an ~11-day round-trip cycle and ~16.5 GWh net delivery per ship:

| Jakarta Share | Daily Need | Ships Arriving/Day | Fleet Size | Solar Farm |
|:---:|:---:|:---:|:---:|:---:|
| 1% | 0.9 GWh | 1 every 18 days | **1 ship** | ~140 MW |
| 5% | 4.5 GWh | 1 every 3.7 days | **3 ships** | ~700 MW |
| 10% | 9 GWh | ~0.55/day | **6 ships** | ~1.4 GW |
| 25% | 22.5 GWh | ~1.4/day | **15 ships** | ~3.5 GW |
| 50% | 45 GWh | ~2.7/day | **30 ships** | ~7.0 GW |
| 100% | 90 GWh | ~5.5/day | **61 ships** | ~14.0 GW |

The AREH project at 26 GW could theoretically charge a fleet supplying all of Jakarta's electricity.

---

## 7. Economic Analysis

All costs modelled for the **10% of Jakarta** scenario (9 GWh/day = 3,285 GWh/year) unless noted. Fuel prices are Q1 2026 benchmarks.

### Scenario A: Diesel Tanker Supply (Baseline)

**Capital costs:**

| Item | Cost |
|------|------|
| Diesel tanker (1 dedicated ship) | $33M |
| Power generators (500 MW @ $500/kW) | $250M |
| Port fuel storage/infrastructure | $50M |
| **Total capex** | **$333M** |

**Annual operating costs:**

| Item | Annual Cost |
|------|-------------|
| **Diesel fuel** (661,000 mt/yr × $800/mt) | **$529M** |
| Ship opex (365 days × $7,000) | $2.6M |
| Ship fuel (14 trips × 200 mt × $900/mt) | $2.5M |
| Generator O&M (500 MW × $15/kW/yr) | $7.5M |
| Port/handling fees | $0.7M |
| **Total annual opex** | **$542M** |

**LCOE: ~$175/MWh**

### Scenario B: Battery Fleet (18 GWh ships, $75/kWh)

**Capital costs:**

| Item | Cost |
|------|------|
| Battery ships (6 × $45M) | $270M |
| **Battery packs** (6 × 18 GWh × $75/kWh) | **$8,100M** |
| Solar farm (1.4 GW, Pilbara, @ $850/kW) | $1,190M |
| Charging infrastructure (Port Hedland) | $150M |
| Discharge infrastructure (Jakarta) | $150M |
| **Total capex** | **$9,860M** |

**Annual operating costs:**

| Item | Annual Cost |
|------|-------------|
| Ship opex (6 × $7,000/day × 365) | $15.3M |
| Ship fuel (6 ships × 33 trips × 200 mt × $900/mt) | $35.6M |
| Solar farm O&M (1,400 MW × $10/kW/yr) | $14.0M |
| Battery maintenance (~0.5% of battery capex/yr) | $40.5M |
| Port/grid operations | $10.0M |
| Insurance (~0.3% of battery value) | $24.3M |
| **Total annual opex** | **$140M** |

**LCOE: ~$348/MWh**

### Battery Cost Sensitivity

| Battery $/kWh | Total Capex | LCOE | vs. Diesel $175/MWh |
|:---:|:---:|:---:|:---:|
| $100 | $12.6B | $439/MWh | 2.5× more |
| **$75** (base) | **$9.9B** | **$348/MWh** | **2.0× more** |
| $50 | $7.2B | $258/MWh | 1.5× more |
| $30 | $5.0B | $186/MWh | 1.1× more |
| **$27** | **$4.7B** | **$175/MWh** | **Break-even** |
| $20 | $3.9B | $150/MWh | 14% cheaper |
| $15 | $3.4B | $132/MWh | 25% cheaper |

Battery packs represent **82% of total capital** at the base case ($75/kWh). Every $10/kWh reduction saves ~$1.08B for the 6-ship fleet. The ships, solar farm, and port infrastructure are almost rounding errors in comparison.

### Diesel Price Escalation (3% annual real increase from $800/mt)

| Year | Diesel $/mt | Diesel Cumulative | Battery Fleet Cumulative |
|:---:|:---:|:---:|:---:|
| 1 | $800 | $0.9B | $10.0B |
| 5 | $901 | $3.2B | $10.6B |
| 10 | $1,045 | $6.5B | $11.3B |
| 15 | $1,211 | $10.4B | $12.0B |
| **17** | **$1,301** | **$12.1B** | **$12.2B** (crossover) |
| 20 | $1,404 | $14.8B | $12.7B |

Cumulative figures include initial capital expenditure at year 0 plus operating costs (with fuel escalation for diesel).

With 3% annual diesel escalation: **break-even at ~year 17**.
With 4% escalation: **break-even at ~year 12**.
With 5% escalation: **break-even at ~year 10**.

### Carbon Pricing Impact

Annual CO₂ from diesel: 661,000 mt diesel × 3.15 = **~2.08 Mt CO₂/year**.

| CO₂ Price | Added Diesel Cost/yr | Diesel LCOE | Battery LCOE ($75/kWh) |
|:---:|:---:|:---:|:---:|
| $0 (today) | $0 | $175/MWh | $348/MWh |
| $50/t | $104M | $207/MWh | $348/MWh |
| $100/t | $208M | $238/MWh | $348/MWh |
| $200/t | $416M | $302/MWh | $348/MWh |
| $350/t | $728M | $397/MWh | $348/MWh (near parity) |

### Combined Optimistic Scenario (~2035)

| Factor | Value |
|--------|-------|
| Battery cost | $30/kWh |
| Diesel price | $1,075/mt (3%/yr from $800 for 10 years) |
| Carbon price | $100/t CO₂ |

| | Diesel | Battery Fleet |
|---|---|---|
| **LCOE** | **$294/MWh** | **$186/MWh** |
| | | **Battery wins by 37%** |

### Maritime Regulatory Impact on Economics

Three regulatory developments significantly strengthen the battery ship case:

**IMO Net-Zero Framework (NZF):** Approved at MEPC 83 in April 2025 — the first global framework combining mandatory emissions limits and GHG pricing for an entire industry sector. Adoption delayed to October 2026, expected in force from 2027. Applies to ships above 5,000 GT. Will impose carbon costs on all diesel tanker operations.

**EU Emissions Trading System (EU ETS):** Extended to shipping from January 2024, reaching **100% compliance from January 2026**. All large ships (5,000+ GT) entering EU ports must purchase carbon allowances. Carbon price: EUR 65-90/tonne (2024-25), forecast to reach EUR 122 by 2030 (BNEF). While the Port Hedland–Jakarta route does not transit EU waters, the EU ETS establishes a global precedent and benchmark.

**FuelEU Maritime:** Active from January 2025, mandating a 2% GHG intensity reduction in 2025, increasing to 6% by 2030. Reporting requirements and compliance documents in force from mid-2026.

These regulations create a **rising floor price for carbon** in international shipping. As carbon costs are internalised globally, the economics shift steadily toward zero-emission energy transport. A battery ship delivering clean electricity faces none of these costs.

---

## 8. Submarine Cable Alternative

### Route: Port Hedland to Jakarta via HVDC Submarine Cable

| Parameter | Sun Cable (reference) | Port Hedland to Jakarta |
|-----------|----------------------|------------------------|
| Submarine cable distance | 4,300 km (to Singapore) | **~2,800 km** |
| Overland transmission | 800 km (to Darwin) | ~250 km |
| Total distance | ~5,100 km | **~3,050 km** |
| Sea depth challenges | Timor Trough (~3,300 m) | Java Trench + straits |

The Port Hedland to Jakarta route is **~40% shorter** than Sun Cable's Darwin to Singapore path.

### HVDC Cable Depth Limitations

The Java Trench (Sunda Trench) reaches a maximum depth of **7,290 metres** — far exceeding the current state of the art for submarine HVDC cable installation. As of early 2026:

| Milestone | Depth | Project |
|-----------|-------|---------|
| Operational record | **2,150 m** | Nexans, Tyrrhenian Link (Italy), December 2025 |
| Sea trial record | **3,000 m** | Nexans, 525 kV MI HVDC cable, early 2026 |
| Java Trench maximum | **7,290 m** | — |

A direct cable route from Pilbara to Jakarta must avoid the deepest sections by routing through the Timor Sea, south of Timor-Leste, through the Savu Sea, between Bali and Lombok (relatively shallow passages), and across the Java Sea (average depth ~46 m). The Timor Trough (~3,300 m) remains a challenge along this route and exceeds the current proven operational depth.

### HVDC Transmission Losses

| Component | Loss |
|-----------|------|
| Converter station (Australia) | ~1.5% |
| Cable (2,800 km @ ~3%/1,000 km) | ~8.4% |
| Converter station (Jakarta) | ~1.5% |
| **Total** | **~11.4%** |

### Cable Capital Costs (10% Jakarta, 500 MW)

| Item | Cost |
|------|------|
| Solar farm (1.4 GW, Pilbara) | $1.19B |
| Battery smoothing (source, 6 GWh @ $50/kWh) | $0.30B |
| Overland transmission (250 km) | $0.25B |
| HVDC converter station (Australia) | $0.50B |
| **Submarine cable** (2,800 km × $2.0M/km) | **$5.60B** |
| HVDC converter station (Jakarta) | $0.40B |
| Jakarta grid integration | $0.20B |
| **Total capex** | **$8.44B** |

Cable cost of $2.0M/km is a mid-range estimate. Current data shows $1-4M/km for submarine HVDC (installed), with deep-water routes toward the upper end. The NeuConnect UK-Germany cable (725 km, 1,400 MW) works out to roughly $2.1M/km.

**Annual opex: ~$110M** (solar O&M, cable maintenance, converter operations, grid ops).

**LCOE (40-year cable life, 8% discount): ~$249/MWh**

### Sun Cable: Real-World Reference

The Australia-Asia Power Link (AAPowerLink) by Sun Cable provides a benchmark:

| Parameter | Value |
|-----------|-------|
| Solar farm | 17-20 GW (Northern Territory) |
| Battery storage | 36-42 GWh |
| HVDC cable | 4,300 km to Singapore, 1.75 GW approved capacity |
| Total cost | **A$35 billion** (~US$23 billion) |
| Target | ~15% of Singapore's electricity |
| Singapore conditional approval | October 2024 |
| FID target | **2027** |
| First power | **Early 2030s** |
| Design life | 70 years |

**2025 milestones:** Indonesian development approvals and permits secured for the subsea transmission system. Cross Border Electricity Trade (CBET) framework agreed between Singapore and Australian Prime Ministers. 70-year Indigenous Land Use Agreement signed. Sun Cable is investing **$2.5 billion in Indonesia** as part of the project — the cables transit largely through Indonesian waters (~2 GW capacity, ~4,200 km). Sun Cable has described potential to extend service to Indonesia at a later stage.

### Other Submarine Cable Projects (2025-2026)

| Project | Route | Distance | Capacity | Status |
|---------|-------|----------|----------|--------|
| Viking Link | UK–Denmark | 765 km | 1,400 MW | Operational Dec 2023 |
| NeuConnect | UK–Germany | 725 km | 1,400 MW | Construction; operational 2028 |
| Tyrrhenian Link | Italy (Sardinia–Sicily) | — | — | Record 2,150 m depth (Dec 2025) |

No cable longer than 800 km is currently operational. Sun Cable's proposed 4,300 km would be unprecedented by a factor of five.

---

## 9. Three-Way Comparison

### LCOE at 10% of Jakarta (9 GWh/day, 3,285 GWh/year)

| | **Diesel** | **Battery Fleet** | **Submarine Cable** |
|---|:---:|:---:|:---:|
| Total capex | $0.33B | $9.86B | $8.44B |
| Annual opex | $542M | $140M | $110M |
| Asset life | 20 yr | 20 yr | 40 yr |
| **LCOE** | **$175/MWh** | **$348/MWh** | **$249/MWh** |

### Scaling Dynamics

Cable costs are dominated by fixed infrastructure (installation, converters). Doubling capacity costs ~40% more, not 100%. Battery ship costs scale linearly — each new ship needs a full battery load at ~$1.35B ($75/kWh). At full Jakarta scale (90 GWh/day), the submarine cable LCOE drops below $130/MWh, while the battery fleet remains above $340/MWh.

### Energy Delivery Efficiency

| Method | Loss Pathway | Useful Energy Delivered (per 100 MWh primary input) |
|--------|-------------|---------------------------------------------|
| **Diesel** | Generator efficiency (~42%) | ~42 MWh |
| **Battery fleet (all-electric)** | Battery RTE (92%) − propulsion from cargo (~8%) | ~84 MWh |
| **Battery fleet (diesel-propelled)** | Battery RTE (92%) only; propulsion is separate fossil fuel | ~92 MWh (but consumes ~200 mt HFO per round trip) |
| **Submarine cable** | Transmission loss (~11.4%) | ~89 MWh |

On a pure solar-to-grid basis, the all-electric battery fleet delivers **2× more useful energy** per unit of sunshine harvested than the diesel pathway. The diesel-propelled variant delivers even more grid energy per solar unit but is not fully decarbonised.

### Qualitative Assessment

| Factor | Diesel | Battery Fleet | Submarine Cable |
|--------|--------|--------------|----------------|
| Construction time | ~1 year | ~3 years | 5-8 years |
| Technology risk | Proven | High (unproven at scale) | Medium (HVDC proven; depth unproven) |
| Single-point failure | Low | Low | **High** |
| Route flexibility | Any port | Any port | Fixed route only |
| Scalability | Easy | Linear cost | Excellent (sub-linear) |
| Carbon emissions | ~2 Mt CO₂/yr (10%) | Near zero | Zero |
| Geopolitical risk | Oil market volatility | Low | Cable crosses sovereign waters |
| Disaster resilience | Good | Good | **Poor** (repair takes months) |
| Revenue during construction | Immediate | Partial | Zero until complete |
| Sovereignty implications | Buys fuel | Docking fees only | Dependent on foreign cable |
| Redundancy cost | Minimal | Add ships | Must duplicate cable |
| Regulatory exposure | Rising (IMO NZF, carbon pricing) | Minimal | Minimal |

---

## 10. Maritime Regulatory Environment

The international regulatory landscape is tightening around maritime emissions, with three developments particularly relevant to the battery ship concept:

### IMO Net-Zero Framework (2025)

The IMO approved its Net-Zero Framework at MEPC 83 in April 2025 — the first global framework combining mandatory emissions limits with a GHG pricing mechanism for any industry sector. A coalition of 87 shipping companies, ports, and fuel producers is urging adoption at MEPC 84 in October 2026, with entry into force expected from 2027.

Key targets:
- **2030:** Reduce maritime GHG at least 20%, striving for 30% (vs 2008 baseline)
- **2040:** Reduce at least 70%, striving for 80%
- **2050:** Net zero

### EU ETS and FuelEU Maritime

- **EU ETS for shipping:** 100% compliance from January 2026; methane and nitrous oxide included alongside CO₂. Carbon allowance price: EUR 65-90/tonne, forecast EUR 122 by 2030.
- **FuelEU Maritime:** Active from January 2025; 2% GHG intensity reduction in 2025, rising to 6% by 2030.

### Implications for Battery Ships

Every regulatory tightening adds cost to diesel energy transport and leaves battery ship operations unaffected. A diesel tanker delivering 48,000 mt of fuel, combined with the ~661,000 mt burned annually at destination generators, creates roughly 2.08 Mt CO₂/year for the 10% Jakarta scenario alone. At a carbon price of EUR 100/tonne (plausible by 2030), that adds ~$208M/year to diesel costs — equivalent to raising the diesel LCOE from $175 to $238/MWh.

The battery fleet has no direct carbon emissions and faces no carbon pricing exposure.

### Battery Safety at Sea: Regulatory Gap

Maritime transport of large-scale battery cargo faces an acknowledged regulatory gap:

- The IMDG Code classifies Li-ion batteries as Class 9 (miscellaneous hazardous) but has **no specific regulations** on state of charge for batteries at sea
- DNV updated rules for maritime battery systems in July 2025 (effective January 2026), with a published "Handbook for Maritime and Offshore Battery Systems"
- CINS (Cargo Incident Notification System) published guidelines for shipping Li-ion cells in June 2025
- PowerX's battery tanker is seeking DNV and Class NK certification — the resulting framework will inform future regulation

Thermal runaway risks are non-trivial: a single 100 kWh battery can release ~20 kg of hydrogen fluoride and up to 6,000 litres of vapour per kWh. Purpose-built battery ships would require dedicated gas emission control, fire suppression, and real-time monitoring systems — engineering challenges, not fundamental barriers.

---

## 11. Onboard Solar and Wind Generation

From a total energy perspective, the battery fleet pathway loses ~16% per round trip: 8% to battery round-trip efficiency and ~8% equivalent to ship propulsion. In the diesel-propulsion economic model, only the 8% RTE loss reduces delivered energy; the propulsion loss manifests as fuel cost (~$180K per round trip). This section examines whether onboard renewable generation can offset either component.

### The Loss Budget (per round trip)

| Loss Component | Amount | Nature |
|----------------|--------|--------|
| Battery round-trip efficiency | ~8% of 18 GWh = 1,440 MWh | Reduces delivered energy (unavoidable) |
| Ship propulsion fuel | ~1,500 MWh equivalent (~200 mt HFO) | Separate fuel cost in diesel model |
| **Total energy cost** | | **~2,940 MWh per round trip** |

### Solar Panel Installation

**Available deck area:**

| Surface | Usable Area |
|---------|-------------|
| Hatch covers (5 holds, ~15 m × 18 m each) | ~1,350 m² |
| Accommodation/bridge roof (minus equipment) | ~200 m² |
| Forecastle deck (partial, minus gear) | ~150 m² |
| **Standard retrofit total** | **~1,700 m²** |
| **Purpose-built battery ship** (flat continuous deck ~100 m × 28 m + superstructure) | **~3,000 m²** |

**Panel specifications (2026 best commercial):**

| Parameter | Value |
|-----------|-------|
| Panel type | SunPower Maxeon 7 or equivalent |
| Efficiency | ~24% |
| Output per m² | ~240 W peak |
| Technology | Interdigitated Back Contact (IBC) |

**At-sea derating factors:**

| Factor | Loss | Reason |
|--------|------|--------|
| Flat mounting (no tilt) | ~12% | Cannot angle toward sun |
| Ship motion (pitch/roll) | ~7% | Dynamic misalignment, intermittent mast shading |
| Temperature (tropical) | ~8% | Panel efficiency drops in 35-45°C ambient |
| Salt spray/soiling | ~5% | Marine environment, limited cleaning access |
| **Combined derating** | **~28%** | Multiplicative |

**Solar output on equatorial route (~5.5 raw peak sun hours/day):**

| Configuration | Peak Power | Effective Daily Output |
|--------------|-----------|----------------------|
| Standard retrofit (1,700 m²) | 408 kWp | ~2.1 MWh/day |
| **Purpose-built (3,000 m²)** | **720 kWp** | **~3.6 MWh/day** |

### Ship-Mounted Wind Turbines

Vertical Axis Wind Turbines (VAWTs) are the most practical ship-mounted option due to omnidirectional wind acceptance and lower gyroscopic loading.

**2 × 100 kW VAWT output:**

| Parameter | Value |
|-----------|-------|
| Combined rated power | 200 kW |
| Capacity factor (at-sea average) | ~25% |
| Average continuous output | ~50 kW |
| **Daily output** | **~1.2 MWh/day** |

Note: Flettner rotors (spinning vertical cylinders using the Magnus effect) are an alternative with proven 8-20% fuel savings on cargo ships, but they assist propulsion rather than generating electricity. For a battery ship seeking to recharge cargo, electricity-generating VAWTs are more relevant.

### Combined Solar + Wind Output

| Source | Rating | Daily Output |
|--------|--------|-------------|
| Solar (3,000 m², purpose-built) | 720 kWp | 3.6 MWh/day |
| Wind (2 × 100 kW VAWT) | 200 kW | 1.2 MWh/day |
| **Total** | | **4.8 MWh/day** |
| **Average continuous power** | | **~200 kW** |

### Impact Assessment

**Over one round trip (7.5 days at sea):**

| Metric | Value |
|--------|-------|
| Solar+wind generated | 7.5 × 4.8 = **36 MWh** |
| Ship propulsion needs | ~1,500 MWh |
| Battery RT losses | 1,440 MWh |
| **Total losses** | **~2,940 MWh** |

**Recovery ratios:**

| Comparison | Value |
|-----------|-------|
| Onboard generation vs. propulsion loss | 36 / 1,500 = **2.4%** |
| Onboard generation vs. total 16% losses | 36 / 2,940 = **1.2%** |
| Onboard generation vs. cargo capacity | 36 / 18,000 = **0.20%** |
| **Effective loss reduction** | **16.3% → ~16.1%** |

The cargo is **500× larger** than what the deck can generate in a voyage.

### Where Onboard Generation IS Meaningful: Hotel Load

While negligible against cargo scale, the onboard renewables closely match the ship's own electrical needs:

| Parameter | Value |
|-----------|-------|
| Ship electrical load at sea (hotel + cargo monitoring) | ~400-500 kW continuous |
| Solar+wind average output | ~200 kW continuous |
| **Auxiliary load coverage** | **~40-50%** |

This substantially reduces auxiliary diesel (MDO) consumption during the voyage.

**Annual fleet savings (6 ships):**

| Metric | Value |
|--------|-------|
| MDO saved per ship per trip | ~10-15 mt |
| Annual MDO saved (6 ships × 33 trips) | **~2,000-3,000 mt** |
| Fuel cost saved (@ $900/mt) | **~$2-3M/year** |
| CO₂ avoided (× 3.15) | **~6,000-9,000 tonnes/year** |

### Installation Cost vs. Savings

| Item | Cost (6-ship fleet) |
|------|---------------------|
| Solar panels (18,000 m² total) | ~$10-15M |
| VAWTs (12 units) | ~$6-9M |
| Marine-grade mounting, wiring, inverters | ~$10-18M |
| **Total installation** | **~$26-42M** |
| **Annual fuel savings** | **~$2-3M/year** |
| **Simple payback** | **~9-14 years** |

Over the 20-year fleet life: ~$50-60M in fuel savings against ~$35M installation cost. **Net benefit: ~$15-25M.**

### Scale Problem Visualised

```
Ship energy flows per round trip:

CARGO:     ████████████████████████████████████████  18,000 MWh
           (battery packs being transported)

PROPULSION: ██████                                    1,500 MWh
            (diesel engines moving the ship)

BATTERY RT: █████                                     1,440 MWh
LOSS        (heat during charge/discharge)

SOLAR+WIND: ▎                                            36 MWh
            (deck panels + 2 turbines, 7.5 days)
```

### Summary

Onboard solar+wind is a **hotel-load solution, not a cargo-recovery solution**. It pays for itself through auxiliary fuel savings and eliminates several thousand tonnes of CO₂ annually, but it cannot meaningfully dent the 16% delivery loss. Recovering propulsion losses alone would require ~60,000 m² of panels (20× the available deck area).

---

## 12. Conclusions

### Which approach wins where

| Scenario | Best Option | Rationale |
|----------|------------|-----------|
| **Small/remote island** (<1 GWh/day) | Diesel (now) / Battery ship (2030+) | Cable not economical; battery ship offers flexibility and subsidy relief |
| **Medium city** (~10 GWh/day) | Submarine cable | Breaks even with diesel in ~15 years with rising fuel costs |
| **Major city** (>50 GWh/day) | Submarine cable, decisively | LCOE drops below diesel; massive long-term savings; sub-linear scaling |
| **Sovereignty priority** | Battery fleet | No permanent foreign infrastructure; can reroute; energy independence |

### Battery fleet niche

The battery fleet concept occupies a specific niche where:

1. **Scale is too small** for a submarine cable to be economical (<5 GWh/day)
2. **Flexibility matters** — ability to serve multiple destinations, reroute during disruption, or scale incrementally
3. **Sovereignty concerns** prevent permanent foreign infrastructure in territorial waters
4. **Battery costs fall below ~$30/kWh** (projected mid-2030s) while diesel prices and carbon costs rise

### Critical dependencies

The battery ship model depends on:

- **Battery cost reaching ~$27/kWh or below** at system level for break-even with current diesel prices (achieved at ~$30/kWh when combined with diesel escalation and carbon pricing)
- **400-500 Wh/kg energy density** becoming commercially available at scale (demonstrated in prototypes but not mass-produced as of 2026; realistic timeline 2030-2035)
- **Carbon pricing** reaching ~$100/t CO₂ globally (EU ETS already at EUR 65-90; IMO NZF expected from 2027)
- **Diesel price escalation** continuing at historical rates (~3-4%/year real)

### The battery cost bottleneck

At current pricing ($75/kWh), battery packs represent **82% of total capital** for the battery fleet. Every $10/kWh reduction saves ~$1.08B for the 6-ship fleet. The ships, solar farm, and port infrastructure are almost rounding errors in comparison. The trajectory is encouraging: BNEF's lowest observed stationary LFP pack price of $50/kWh in 2025 suggests purpose-built transport packs could reach $30-40/kWh by 2030.

### Competing alternatives

The battery ship concept competes not only with diesel and submarine cables, but also with:

- **Green hydrogen/ammonia shipping** — projects like AREH (26 GW Pilbara) plan to convert solar to green hydrogen, ship as ammonia. Ammonia has ~5× the energy density of next-gen batteries by weight and uses existing bulk carrier infrastructure. But the full round-trip efficiency is poor: **58-77% of input energy is lost** in the production-shipping-reconversion cycle, compared to ~16% for battery ships. Ammonia is also toxic and ammonia-to-power technology remains largely pre-commercial. Green hydrogen costs $2.50-5.00/kg unsubsidised (2025-26), projected to fall to $1.50-2.00/kg in favourable locations by 2030.
- **Submarine HVDC cables** — Sun Cable's AAPowerLink (A$35B, Darwin to Singapore) demonstrates the concept at scale. A Port Hedland to Jakarta cable (~2,800 km) would be ~40% shorter, but faces the depth challenge of the Timor Trough (~3,300 m) exceeding current proven cable depth (2,150 m operational, 3,000 m tested). No submarine cable longer than ~800 km is currently operational.
- **Nuclear-powered merchant ships** — HD Korea Shipbuilding received approval-in-principle from DNV for a 15,000 TEU nuclear container ship in 2025. Early pilot vessels projected for mid-2030s. A long-term competitor to all fuel alternatives, but 10+ years from commercial deployment and lacking a regulatory framework.

### Key numbers to remember

| Fact | Value |
|------|-------|
| One shipload of diesel generates | ~239 GWh |
| One shipload of current batteries stores | ~1.1 GWh (217× less) |
| One shipload of ~2030 batteries stores | ~16 GWh (15× less) |
| One shipload of ~2035 batteries stores | ~19 GWh (13× less) |
| Battery fleet LCOE (base, $75/kWh) | ~$348/MWh |
| Battery fleet LCOE (optimistic, $30/kWh + carbon pricing) | ~$186/MWh |
| Diesel LCOE (current, $800/mt) | ~$175/MWh |
| Diesel LCOE (2035 with carbon pricing) | ~$294/MWh |
| Submarine cable LCOE (10% Jakarta) | ~$249/MWh |
| Battery fleet break-even with diesel | ~2035 (with $30/kWh + $100/t CO₂) |
| Battery fleet break-even battery price (no carbon) | ~$27/kWh |
| Cable break-even with diesel | ~Year 15 (with 3% diesel escalation) |
| Port Hedland–Jakarta distance | ~1,270 nautical miles |
| Fleet for 10% Jakarta | 6 ships, ~1.4 GW solar |

---

## Data Sources

- **Ship specifications:** Clarksons, Searates, HandyBulk, Marine Insight, Bulk Carrier Guide
- **Ship operating costs:** Star Bulk Carriers Q3 2025 financials, HandyBulk charter rates
- **Fuel prices:** Ship & Bunker (Singapore hub), Bunker Index, EIA short-term energy outlook
- **Battery specifications:** Tesla Megapack datasheets (2025), BYD MC Cube-T (CnEVPost), CATL TENER and TENER Stack announcements, Wikipedia
- **Battery pricing:** BloombergNEF Lithium-Ion Battery Price Survey (December 2025), NREL Cost Projections 2025
- **Battery technology:** CATL, Samsung SDI, QuantumScape, Toyota, FAW announcements; McKinsey battery roadmap; Fraunhofer ISI Roadmap 2030+
- **Solar data:** CSIRO GenCost 2025-26 draft, IRENA Renewable Power Generation Costs 2024, ARENA, AREH project documentation
- **Shipping costs:** Star Bulk Carriers, Genco Shipping, ShipNerd, Breakwave Advisors
- **Battery ship projects:** PowerX Manufacturing (Japan), Fleetzero (US), CATL CAEV, Yara Birkeland
- **Indonesia energy:** IESR Energy Transition Outlook 2025, Climatescope, PLN data, CREA RUPTL analysis, MEMR regulations
- **Submarine cable:** Sun Cable / AAPowerLink, Nexans (Tyrrhenian Link depth records), NeuConnect, ResearchGate HVDC cost studies
- **Maritime regulation:** IMO MEPC 83 (Net-Zero Framework), European Commission (EU ETS for shipping), DNV (FuelEU Maritime), DNV Maritime Battery Handbook
- **Green hydrogen:** IRENA Green Hydrogen Cost Reduction (2023), IndexBox ammonia shipping economics, ICCT hydrogen cost analysis
- **Shipping routes:** SeaRoutes distance calculator

---

*Research originally conducted 2026-03-24; revised 2026-04-01 with corrected route distance, updated fuel prices, latest battery technology data, and new regulatory developments. All costs in USD unless noted. Projections are estimates based on current data and published industry forecasts.*
