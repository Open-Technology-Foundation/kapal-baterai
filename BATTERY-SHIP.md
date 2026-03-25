# Battery Ship Energy Transport: Feasibility Study

**Research Date:** 2026-03-24
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
10. [Onboard Solar and Wind Generation](#10-onboard-solar-and-wind-generation)
11. [Conclusions](#11-conclusions)

---

## 1. Reference Vessel

A Handymax/Supramax class bulk carrier was selected as the reference vessel, representing the "average" diesel cargo ship in global trade.

| Parameter | Value |
|-----------|-------|
| Length overall | ~170 m |
| Beam (width) | ~32 m |
| Draft | ~12 m |
| Deadweight tonnage (DWT) | ~50,000 t |
| Cargo holds | 5 |
| Total grain volume | ~70,000 m³ |
| Service speed | ~14 knots |
| Propulsion | Slow-speed two-stroke diesel (HFO) |
| Auxiliary engines | 3 × four-stroke diesel generators (MDO) |

These vessels are the workhorses of global trade — large enough to carry significant cargo but small enough to enter most ports worldwide.

### Cargo Hold Internal Dimensions (per hold, estimated)

| Feature | Dimension |
|---------|-----------|
| Tank top width (floor) | ~18-20 m |
| Hold length | ~18-22 m (avg ~20 m) |
| Usable height (tank top to hatch) | ~14-15 m |
| Hatch opening | ~15 m x 17-18 m |
| Floor area per hold | ~360-400 m² |
| Grain volume per hold | ~14,000 m³ |

---

## 2. Fuel Capacity and Electricity from Diesel

### Ship's Own Fuel Supply

| Fuel Type | Capacity | Approx. Weight |
|-----------|----------|----------------|
| Heavy Fuel Oil (HFO) | ~1,500 cbm | ~1,425 mt |
| Marine Diesel Oil (MDO) | ~100-150 cbm | ~85-130 mt |
| **Total** | ~1,600-1,650 cbm | **~1,500-1,550 mt** |

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

### Onboard Electrical Generation (from MDO)

The ship's own auxiliary generators (3 x ~800-1,200 kW) produce electrical power for onboard systems:

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

Data sourced from Tesla datasheets, Wikipedia, and BloombergNEF.

| Battery | Capacity | Power | Dimensions (W x D x H) | Weight | RTE | Cost | Cycle Life |
|---------|----------|-------|------------------------|--------|-----|------|-----------|
| Tesla Megapack 2 | 3.854 MWh | 1.284 MW | 7.25 x 1.60 x 2.51 m | 30,500 kg | 92% | ~$1.47M | 3,000-5,000 |
| Tesla Megapack 2XL | 3.916 MWh | 1.927 MW | 8.80 x 2.79 x 1.65 m | 38,100 kg | 85-90% | ~$1.39M | 3,000-5,000 |
| Tesla Megapack 3 (2026) | 5.0 MWh | TBC | TBC | 39,000 kg | 91% | ~$1.39M | 10,000+ |
| BYD MC Cube-T | 14.5 MWh | TBC | 20-ft container | ~45,000 kg | TBC | est. ~$3M+ | TBC |
| CATL TENER | 6.25 MWh | TBC | Container-sized | ~40,000 kg | TBC | est. ~$2M+ | TBC |

Current stationary storage pack prices: **$70/kWh** (2025, BloombergNEF — a 45% drop from 2024).

### Battery Energy Density: Current vs Diesel

| Storage Medium | Energy Density (MWh/tonne) |
|---------------|---------------------------|
| **Diesel fuel** (at 40% generator efficiency) | ~4.75 |
| Tesla Megapack 2 | ~0.126 |
| Tesla Megapack 3 | ~0.128 |
| BYD 14.5 MWh | ~0.32 |

Diesel stores roughly **37x more usable energy per tonne** than the best grid batteries available today.

### Next-Generation Batteries (~2030)

Multiple manufacturers (CATL, FAW, Samsung SDI) have demonstrated or announced 500 Wh/kg cells:

| Metric | Current (Megapack 2, LFP) | Next-Gen (~2030, Solid-State/Li-S) | Improvement |
|--------|--------------------------|-----------------------------------|-------------|
| Cell energy density | ~200 Wh/kg | ~500 Wh/kg | **2.5x** |
| System energy density | ~126 Wh/kg | ~300-375 Wh/kg | **2.5-3x** |
| Volumetric (cell) | ~400 Wh/L | ~1,000-1,200 Wh/L | **2.5-3x** |
| Projected cost | $70/kWh | $30-75/kWh | **1-2.3x** |

---

## 4. Fitting Batteries into a Cargo Ship

### Current Technology: Megapack 2 in a Standard Bulk Carrier

**Layout per cargo hold:**
- Orientation: long side (7.17 m) across the ~19 m hold width
- 2 units across width (14.8 m, leaving 4.2 m side access)
- 7 units along length (18.9 m of 20 m)
- 14 Megapacks per level
- 4 levels vertical (12 m of 14 m, with racking)
- **56 Megapacks per hold, 280 total (5 holds)**

| Metric | Single Layer | 4-Level Racking |
|--------|-------------|-----------------|
| Units per hold | 14 | 56 |
| **Total units (5 holds)** | **70** | **280** |
| Total weight | 2,135 t | 8,540 t |
| Weight capacity used | 4.4% of 48,000 t | 17.8% |
| **Energy stored** | **270 MWh** | **1,080 MWh (~1.1 GWh)** |

**Volume is the binding constraint**, not weight. The ship could carry 1,574 Megapacks by weight but can only fit ~280 by volume.

### Shipload Comparison: Diesel vs Current Batteries

| | Diesel Cargo | Megapack 2 Cargo (racked) |
|---|---|---|
| Electricity delivered | **239 GWh** | **~1.1 GWh** |
| **Shiploads to match diesel** | **1** | **~217** |

### Next-Gen Purpose-Built Battery Packs (~2030)

Purpose-built energy transport packs strip out per-unit inverter, HVAC, enclosure, and BMS overhead:

| Component | Megapack 2 (standalone) | Purpose-Built Shipping Pack |
|-----------|------------------------|---------------------------|
| Inverter | Per unit (heavy) | Centralised on ship |
| HVAC/cooling | Per unit | Ship-wide system |
| Enclosure | Weatherproof steel | Bare rack (inside hold) |
| BMS | Full per-unit | Lightweight per-pack |
| Overhead | ~35-40% of weight | ~10-15% of weight |
| **Effective density** | 126 Wh/kg | **~375 Wh/kg** |

**Next-gen shipload capacity:**

| Constraint | Calculation | Result |
|-----------|------------|--------|
| Weight limit | 48,000 t x 375 Wh/kg | **18.0 GWh** |
| Volume limit | ~50,000 m³ x 500 Wh/L | ~25 GWh |
| Binding constraint | Weight | **~18 GWh per shipload** |
| Hold volume used | ~36,000 m³ | ~72% |

**Improvement: 18 GWh vs 1.1 GWh = 16x improvement over current tech.**

Diesel comparison improves from 217:1 to **~14.5:1** (shiploads of batteries to match one shipload of diesel).

---

## 5. Charging Infrastructure: Pilbara Solar

### Why NW Australia

| Parameter | Pilbara, WA | Indonesia (comparison) |
|-----------|------------|----------------------|
| Solar irradiance | ~2,400 kWh/m²/year | ~1,700 kWh/m²/year |
| Capacity factor (tracking) | **~28-30%** | ~15-17% |
| Cloud-free days | ~300+/year | ~180-220/year |
| Daily peak sun hours | ~7-8 hrs | ~4.5-5 hrs |

The planned **Australian Renewable Energy Hub (AREH)** near Port Hedland targets **26 GW** of solar + wind across 6,500 km². Awarded Priority Project status by WA Government in December 2024.

### Charging 280 Megapack 2 Units (Current Tech)

| Parameter | Value |
|-----------|-------|
| Energy to store | 1,079 MWh |
| Input needed (92% RTE) | ~1,173 MWh |
| Max charge rate (all 280 at rated) | 359 MW |
| **Time at max rate** | **~3 hrs 16 min** |

### Renewable Source Requirements

| Solar Farm Size | Daily Output (29% CF) | Days to Charge 280 Packs |
|----------------|----------------------|--------------------------|
| 50 MW | ~348 MWh/day | ~3.4 days |
| 100 MW | ~696 MWh/day | ~1.7 days |
| 250 MW | ~1,740 MWh/day | ~16 hours |
| 500 MW | ~3,480 MWh/day | ~8 hours |

---

## 6. The Battery Tanker Fleet Model

### Concept

Ships loaded with rechargeable battery packs are charged at a solar farm in the Pilbara, sail to Jakarta, plug into the city grid, discharge, then return for recharging — a continuous cycle replacing diesel tanker deliveries.

### Shipping Route: Port Hedland to Jakarta (Tanjung Priok)

| Parameter | Value |
|-----------|-------|
| Sea distance | ~1,500 nautical miles |
| Speed | 14 knots |
| Transit time (one way) | ~4.5 days |
| Round trip at sea | ~9 days |
| Discharge time (18 GWh @ ~750 MW) | ~1 day |
| Recharge time (@ ~750 MW solar-fed) | ~1 day |
| Buffer/port ops | ~1 day |
| **Total cycle time** | **~12-14 days** |

Ship self-consumption (diesel-powered): ~1.2 GWh fuel per round trip. Net delivery: **~16.8 GWh**.

If fully electric (powered from own cargo): ~1.8 GWh propulsion. Net delivery: **~16.2 GWh**.

### Jakarta Electricity Demand

| Parameter | Value |
|-----------|-------|
| Greater Jakarta (Jabodetabek) population | ~35 million |
| Estimated daily electricity demand | **~90 GWh/day** |
| Java-Bali grid peak demand (2024) | ~32 GW |
| Indonesia total consumption (2024) | ~233 TWh/year |
| Average electricity price | ~$73/MWh |

### Fleet Size Requirements

With a 14-day round-trip cycle and ~16.5 GWh net delivery per ship:

| Jakarta Share | Daily Need | Ships Arriving/Day | Fleet Size | Solar Farm |
|:---:|:---:|:---:|:---:|:---:|
| 1% | 0.9 GWh | 1 every 18 days | **1 ship** | 150 MW |
| 5% | 4.5 GWh | 1 every 3.7 days | **4 ships** | 720 MW |
| 10% | 9 GWh | ~0.55/day | **8 ships** | 1.5 GW |
| 25% | 22.5 GWh | ~1.4/day | **20 ships** | 3.6 GW |
| 50% | 45 GWh | ~2.7/day | **39 ships** | 7.3 GW |
| 100% | 90 GWh | ~5.5/day | **78 ships** | 14.5 GW |

The AREH project at 26 GW could theoretically charge a fleet supplying all of Jakarta.

---

## 7. Economic Analysis

All costs modelled for the **10% of Jakarta** scenario (9 GWh/day = 3,285 GWh/year) unless noted.

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
| **Diesel fuel** (659,700 mt/yr x $860/mt) | **$567M** |
| Ship opex (365 days x $7,000) | $2.6M |
| Ship fuel (14 trips x 288 mt x $986/mt) | $4.0M |
| Generator O&M (500 MW x $15/kW/yr) | $7.5M |
| Port/handling fees | $0.7M |
| **Total annual opex** | **$582M** |

**LCOE: ~$188/MWh**

### Scenario B: Battery Fleet (2030 tech, $75/kWh)

**Capital costs:**

| Item | Cost |
|------|------|
| Battery ships (8 x $45M) | $360M |
| **Battery packs** (8 x 18 GWh x $75/kWh) | **$10,800M** |
| Solar farm (1.5 GW, Pilbara) | $1,275M |
| Charging infrastructure (Port Hedland) | $150M |
| Discharge infrastructure (Jakarta) | $150M |
| **Total capex** | **$12,735M** |

**Annual operating costs:**

| Item | Annual Cost |
|------|-------------|
| Ship opex (8 x $7,000/day x 365) | $20.4M |
| Ship fuel (8 ships x 26 trips x 288 mt x $986/mt) | $59M |
| Solar farm O&M (1,500 MW x $10/kW/yr) | $15M |
| Battery maintenance (~0.5% of battery capex/yr) | $54M |
| Port/grid operations | $10M |
| Insurance (~0.3% of battery value) | $32.4M |
| **Total annual opex** | **$191M** |

**LCOE: ~$453/MWh**

### Battery Cost Sensitivity

| Battery $/kWh | Total Capex | LCOE | vs. Diesel $188/MWh |
|:---:|:---:|:---:|:---:|
| $100 | $16.3B | $556/MWh | 3.0x more |
| **$75** (base) | **$12.7B** | **$453/MWh** | **2.4x more** |
| $50 | $9.1B | $340/MWh | 1.8x more |
| $30 | $6.2B | $250/MWh | 1.3x more |
| $20 | $4.8B | $207/MWh | 1.1x more |
| **$15** | **$4.1B** | **$185/MWh** | **Break-even** |

### Diesel Price Escalation (3% annual real increase)

| Year | Diesel $/mt | Diesel Cumulative | Battery Fleet Cumulative |
|:---:|:---:|:---:|:---:|
| 1 | $860 | $0.6B | $1.5B |
| 5 | $968 | $3.3B | $7.4B |
| 10 | $1,122 | $6.9B | $14.9B |
| 15 | $1,301 | $11.2B | $22.3B |
| **18** | **$1,424** | **$14.1B** | **$15.3B** (crossover) |
| 20 | $1,508 | $16.0B | $16.3B |

With 3% annual diesel escalation: **break-even at ~year 18**.
With 4% escalation: **break-even at ~year 14**.
With 5% escalation: **break-even at ~year 12**.

### Carbon Pricing Impact

Annual CO2 from diesel: 659,700 mt diesel x 3.15 = **~2.08 Mt CO2/year**.

| CO2 Price | Added Diesel Cost/yr | Diesel LCOE | Battery LCOE ($75/kWh) |
|:---:|:---:|:---:|:---:|
| $0 (today) | $0 | $188/MWh | $453/MWh |
| $50/t | $104M | $219/MWh | $453/MWh |
| $100/t | $208M | $251/MWh | $453/MWh |
| $200/t | $416M | $314/MWh | $453/MWh |
| $400/t | $832M | $441/MWh | $453/MWh (near parity) |

### Combined Optimistic Scenario (~2035)

| Factor | Value |
|--------|-------|
| Battery cost | $30/kWh |
| Diesel price | $1,200/mt (3%/yr from today) |
| Carbon price | $100/t CO2 |

| | Diesel | Battery Fleet |
|---|---|---|
| **LCOE** | **$308/MWh** | **$250/MWh** |
| | | **Battery wins by 19%** |

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
| Solar farm (1.5 GW, Pilbara) | $1.28B |
| Battery smoothing (source, 6 GWh) | $0.45B |
| Overland transmission (250 km) | $0.25B |
| HVDC converter station (Australia) | $0.50B |
| **Submarine cable** (2,800 km x $1.8M/km) | **$5.04B** |
| HVDC converter station (Jakarta) | $0.40B |
| Jakarta grid integration | $0.20B |
| **Total capex** | **$8.12B** |

**Annual opex: ~$105M** (solar O&M, cable maintenance, converter operations, grid ops).

**LCOE (40-year cable life, 8% discount): ~$239/MWh**

### Sun Cable: Real-World Reference

The Australia-Asia Power Link (AAPowerLink) by Sun Cable provides a benchmark:

- **Solar farm:** 17-20 GW (Northern Territory)
- **Battery storage:** 36-42 GWh
- **HVDC cable:** 4,300 km to Singapore, 1.75 GW approved capacity
- **Total cost:** A$30-35 billion (~US$20-24 billion)
- **Target:** ~15% of Singapore's electricity
- **Status:** Singapore conditional approval granted October 2024; project revived under Grok Ventures after 2023 administration; also planned to extend to Indonesia
- **Design life:** 70 years

---

## 9. Three-Way Comparison

### LCOE at 10% of Jakarta (9 GWh/day, 3,285 GWh/year)

| | **Diesel** | **Battery Fleet** | **Submarine Cable** |
|---|:---:|:---:|:---:|
| Total capex | $0.33B | $12.74B | $8.12B |
| Annual opex | $582M | $191M | $105M |
| Asset life | 20 yr | 20 yr | 40 yr |
| **LCOE** | **$188/MWh** | **$453/MWh** | **$239/MWh** |

### LCOE at 100% of Jakarta (90 GWh/day, 32,850 GWh/year)

| | **Diesel** | **Battery Fleet** | **Submarine Cable** |
|---|:---:|:---:|:---:|
| Total capex | $2.6B | $121.4B | $39.4B |
| Annual opex | $5,820M | $1,910M | $500M |
| **LCOE** | **$185/MWh** | **$3,815/MWh** | **$122/MWh** |

At full Jakarta scale, the submarine cable beats diesel on LCOE — and the battery fleet is economically impractical.

### Scaling Dynamics

Cable costs are dominated by fixed infrastructure (installation, converters). Doubling capacity costs ~40% more, not 100%. Battery ship costs scale linearly — each new ship needs a full $1.35B battery load.

### Cumulative Cost Over Time (10% Jakarta, 3% diesel escalation)

| Year | Diesel | Cable | Battery Fleet |
|:---:|:---:|:---:|:---:|
| 1 | $0.6B | $0.9B | $1.5B |
| 5 | $3.3B | $4.3B | $7.4B |
| **8** | **$5.6B** | **$5.6B** (crossover) | — |
| 10 | $7.3B | $6.6B | $14.9B |
| 15 | $12.0B | $9.7B | $22.3B |
| 20 | $17.6B | $12.8B | $29.8B |
| 40 | — | $20.8B | — |

Cable breaks even with diesel at **~year 8** (with 3% diesel escalation). Over 40 years (cable design life), the cable saves **~$30B+** compared to diesel.

### Energy Delivery Efficiency

| Method | Loss Pathway | Useful Energy Delivered (per 100 MWh solar) |
|--------|-------------|---------------------------------------------|
| **Diesel** | Solar to grid (0%) + generator efficiency (~42%) | ~42 MWh |
| **Battery fleet** | Battery RTE (92%) - ship fuel (~10%) | ~82 MWh |
| **Submarine cable** | Transmission loss (~11.4%) | ~89 MWh |

The cable delivers **2.1x more useful energy** per unit of solar harvested than the diesel path.

### Qualitative Assessment

| Factor | Diesel | Battery Fleet | Submarine Cable |
|--------|--------|--------------|----------------|
| Construction time | ~1 year | ~3 years | 5-8 years |
| Technology risk | Proven | High (unproven at scale) | Medium (HVDC proven) |
| Single-point failure | Low | Low | **High** |
| Route flexibility | Any port | Any port | Fixed route only |
| Scalability | Easy | Linear cost | Excellent |
| Carbon emissions | ~2 Mt CO2/yr (10%) | Near zero | Zero |
| Geopolitical risk | Oil market volatility | Low | Cable crosses sovereign waters |
| Disaster resilience | Good | Good | **Poor** (repair takes months) |
| Revenue during construction | Immediate | Partial | Zero until complete |
| Sovereignty implications | Buys fuel | Docking fees only | Dependent on foreign cable |
| Redundancy cost | Minimal | Add ships | Must duplicate cable |

---

## 10. Onboard Solar and Wind Generation

The battery fleet model loses ~18% of cargo energy per round trip (8% battery round-trip efficiency + 10% ship propulsion fuel). This section examines whether onboard renewable generation — solar panels covering the deck and ship-mounted wind turbines — can meaningfully offset those losses.

### The 18% Loss Budget (per round trip)

| Loss Component | Amount | Cause |
|----------------|--------|-------|
| Battery round-trip efficiency | ~8% of 18 GWh = 1,440 MWh | Heat during charge/discharge (unavoidable) |
| Ship propulsion fuel | ~10% of cargo = 1,800 MWh | Diesel engines driving the ship 9 days at sea |
| **Total loss** | | **~3,240 MWh per round trip** |

### Solar Panel Installation

**Available deck area:**

The reference vessel (170 m x 32 m) has the following flat surfaces:

| Surface | Usable Area |
|---------|-------------|
| Hatch covers (5 holds, ~15 m x 18 m each) | ~1,350 m² |
| Accommodation/bridge roof (minus equipment) | ~200 m² |
| Forecastle deck (partial, minus gear) | ~150 m² |
| **Standard retrofit total** | **~1,700 m²** |
| **Purpose-built battery ship** (flat continuous deck ~100 m x 28 m + superstructure) | **~3,000 m²** |

**Panel specifications (2026 best commercial):**

| Parameter | Value |
|-----------|-------|
| Panel type | SunPower Maxeon 7 or equivalent |
| Efficiency | ~24% |
| Output per m² | ~240 W peak |
| Technology | Interdigitated Back Contact (IBC) |

**At-sea derating factors:**

Panels on ships perform worse than on land due to several compounding factors:

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

For electricity generation (as opposed to propulsion-assist systems like Flettner rotors), Vertical Axis Wind Turbines (VAWTs) are the most practical ship-mounted option due to their omnidirectional wind acceptance and lower gyroscopic loading.

**VAWT specifications (100 kW rated):**

| Parameter | Value |
|-----------|-------|
| Type | H-type VAWT |
| Rotor diameter | ~5-7 m |
| Blade height | ~7-8 m |
| Weight | ~3-5 tonnes |
| Rated wind speed | ~12-14 m/s |

**Apparent wind complication:** A ship sailing at 14 knots (~7 m/s) with the wind reduces apparent wind speed experienced by the turbine, while sailing into the wind increases it. On a round trip these partially average out, but with a net reduction. Tropical average true wind is ~12-18 knots (~6-9 m/s).

**Realistic capacity factor for ship-mounted VAWT: ~20-25%.**

Note: Flettner rotors (spinning vertical cylinders using the Magnus effect) are an alternative wind technology with proven 8-20% fuel savings on cargo ships, but they assist propulsion rather than generating electricity. For a battery ship specifically seeking to recharge cargo, electricity-generating VAWTs are more relevant.

**2 x 100 kW VAWT output:**

| Parameter | Value |
|-----------|-------|
| Combined rated power | 200 kW |
| Capacity factor (at-sea average) | ~25% |
| Average continuous output | ~50 kW |
| **Daily output** | **~1.2 MWh/day** |

### Combined Solar + Wind Output

| Source | Rating | Daily Output |
|--------|--------|-------------|
| Solar (3,000 m², purpose-built) | 720 kWp | 3.6 MWh/day |
| Wind (2 x 100 kW VAWT) | 200 kW | 1.2 MWh/day |
| **Total** | | **4.8 MWh/day** |
| **Average continuous power** | | **~200 kW** |

### Impact Assessment

**Over one round trip (9 days at sea):**

| Metric | Value |
|--------|-------|
| Solar+wind generated | 9 x 4.8 = **43.2 MWh** |
| Ship propulsion needs | 1,800 MWh |
| Battery RT losses | 1,440 MWh |
| **Total losses** | **3,240 MWh** |

**Recovery ratios:**

| Comparison | Value |
|-----------|-------|
| Onboard generation vs. propulsion loss | 43.2 / 1,800 = **2.4%** |
| Onboard generation vs. total 18% losses | 43.2 / 3,240 = **1.3%** |
| Onboard generation vs. cargo capacity | 43.2 / 18,000 = **0.24%** |
| **Effective loss reduction** | **18.0% → ~17.8%** |

The solar+wind recovers roughly 1.3% of the 18% loss. The cargo is 420x larger than what the deck can generate in a voyage.

### Where Onboard Generation IS Meaningful: Hotel Load

While negligible against cargo scale, the onboard renewables closely match the ship's own electrical needs:

| Parameter | Value |
|-----------|-------|
| Ship hotel load at sea | ~280 kW continuous (6.7 MWh/day) |
| Solar+wind average output | ~200 kW continuous (4.8 MWh/day) |
| **Hotel load coverage** | **~71%** |

This substantially reduces auxiliary diesel (MDO) consumption.

**Annual fleet savings (8 ships):**

| Metric | Value |
|--------|-------|
| MDO saved per ship per trip | ~31.5 mt (3.5 mt/day x 9 days) |
| Annual MDO saved (8 ships x 26 trips) | **~6,550 mt** |
| Fuel cost saved (@ $986/mt) | **~$6.5M/year** |
| CO2 avoided (x 3.15) | **~20,600 tonnes/year** |

### Installation Cost vs. Savings

| Item | Cost (8-ship fleet) |
|------|---------------------|
| Solar panels (24,000 m² total) | ~$15-20M |
| VAWTs (16 units) | ~$8-12M |
| Marine-grade mounting, wiring, inverters | ~$15-25M |
| **Total installation** | **~$40-55M** |
| **Annual fuel savings** | **~$6.5M/year** |
| **Simple payback** | **~6-8 years** |

Over the 20-year fleet life: ~$130M in fuel savings against ~$50M installation cost. **Net benefit: ~$80M.**

### Scale Problem Visualised

```
Ship energy flows per round trip:

CARGO:     ████████████████████████████████████████  18,000 MWh
           (battery packs being transported)

PROPULSION: ███████                                   1,800 MWh
            (diesel engines moving the ship)

BATTERY RT: █████                                     1,440 MWh
LOSS        (heat during charge/discharge)

SOLAR+WIND: ▎                                            43 MWh
            (deck panels + 2 turbines, 9 days)
```

### Summary

Onboard solar+wind is a **hotel-load solution, not a cargo-recovery solution**. It pays for itself through auxiliary fuel savings (~$80M net over 20 years) and eliminates ~20,600 tonnes of CO2 annually, but it cannot meaningfully dent the 18% delivery loss. The ship simply does not have enough surface area — recovering propulsion losses alone would require ~75,000 m² of panels (25x the available deck area).

---

## 11. Conclusions

### Which approach wins where

| Scenario | Best Option | Rationale |
|----------|------------|-----------|
| **Small/remote island** (<1 GWh/day) | Diesel (now) / Battery ship (2035+) | Cable not economical; battery ship offers flexibility |
| **Medium city** (~10 GWh/day) | Submarine cable | Breaks even with diesel in ~8 years with rising fuel costs |
| **Major city** (>50 GWh/day) | Submarine cable, decisively | LCOE drops below diesel; massive long-term savings |
| **Sovereignty priority** | Battery fleet | No permanent foreign infrastructure; can reroute; energy independence |

### Battery fleet niche

The battery fleet concept occupies a specific niche where:

1. **Scale is too small** for a submarine cable to be economical (<5 GWh/day)
2. **Flexibility matters** — ability to serve multiple destinations, reroute during geopolitical disruption, or scale incrementally
3. **Sovereignty concerns** prevent permanent foreign infrastructure in territorial waters
4. **Battery costs fall below ~$30/kWh** (projected 2035+) while diesel prices and carbon costs rise

### Critical dependencies

The battery ship model depends on:

- **Battery cost reaching ~$30/kWh or below** at system level for purpose-built packs
- **500 Wh/kg energy density** becoming commercially available at scale (demonstrated but not mass-produced as of 2026)
- **Carbon pricing** reaching ~$100/t CO2 to close the gap with diesel
- **Diesel price escalation** continuing at historical rates (~3-4%/year real)

### The battery cost bottleneck

At current pricing ($75/kWh), battery packs represent **85% of total capital** for the battery fleet. Every $10/kWh reduction saves $1.44B for an 8-ship fleet. The ships, solar farm, and port infrastructure are almost rounding errors in comparison.

### Competing alternatives

The battery ship concept competes not only with diesel and submarine cables, but also with:

- **Green hydrogen/ammonia shipping** — projects like AREH (26 GW Pilbara) plan to convert solar to green hydrogen, ship as ammonia. Ammonia has ~5x the energy density of next-gen batteries by weight and uses existing bulk carrier infrastructure.
- **Submarine HVDC cables** — Sun Cable's AAPowerLink (A$35B, Darwin to Singapore) demonstrates the concept at scale. A Port Hedland to Jakarta cable (~2,800 km) would be ~40% shorter and proportionally cheaper.

### Key numbers to remember

| Fact | Value |
|------|-------|
| One shipload of diesel generates | ~239 GWh |
| One shipload of current batteries stores | ~1.1 GWh (217x less) |
| One shipload of 2030 batteries stores | ~18 GWh (14.5x less) |
| Battery fleet LCOE (base, $75/kWh) | ~$453/MWh |
| Battery fleet LCOE (optimistic, $30/kWh + carbon pricing) | ~$250/MWh |
| Diesel LCOE (current) | ~$188/MWh |
| Diesel LCOE (2035 with carbon pricing) | ~$308/MWh |
| Submarine cable LCOE (10% Jakarta) | ~$239/MWh |
| Submarine cable LCOE (100% Jakarta) | ~$122/MWh |
| Battery fleet break-even with diesel | ~2035 (with $30/kWh + $100/t CO2) |
| Cable break-even with diesel | ~Year 8 (with 3% diesel escalation) |

---

## Data Sources

- **Ship specifications:** Clarksons, Searates, Neda Maritime, Bulk Carrier Guide
- **Fuel consumption:** WPP (Worldwide Power Products), MAN Energy Solutions
- **Battery specifications:** Tesla Megapack datasheets, Wikipedia, BloombergNEF
- **Solar data:** CSIRO GenCost 2026, ARENA, AREH project documentation
- **Shipping costs:** Genco Shipping financials, Ship&Bunker, ShipNerd
- **Indonesia energy:** IESR Energy Transition Outlook 2025, Climatescope, PLN data
- **Submarine cable:** Sun Cable / AAPowerLink (Wikipedia, CSIRO HyResource), ResearchGate HVDC cost studies
- **Battery projections:** Fraunhofer ISI Roadmap 2030+, CATL, FAW announcements, NREL 2025 Cost Projections

---

*Research conducted 2026-03-24. All costs in USD unless noted. Projections are estimates based on current data and published industry forecasts.*
