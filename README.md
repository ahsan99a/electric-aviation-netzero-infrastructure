# electric-aviation-netzero-infrastructure
Net-zero electric aviation infrastructure via joint battery swapping &amp; megacharging with onsite wind/PV + storage; queuing, Weibull/PV models, and economic analysis
# Net-Zero Electric Aviation via Battery Swapping & Supercharging 


**Authors:** Ahsanul Abedin, Tajwar Al Mamun, Borhan Uddin Chowdhury, Mohammad Abid Hasan  
**Course:** ENGR 5310 — Systems Engineering (Fall 2024)  
**Instructor:** Prof. Tongdan Jin  
**Report:** `report/Final_Report.pdf`

## Abstract
We design a net-zero energy infrastructure for electric aircraft (EA) using a Joint Battery Swapping & Supercharging (JBSS) station powered by onsite wind (WT) and solar PV with distributed energy storage (DESS). Methods include Weibull-based wind modeling with turbine power curves, hourly PV estimation (feature-engineered/ML), EA arrival modeling (exponential inter-arrival), JBSS queuing (M/M/s), and lifecycle/economic analysis. Results indicate feasibility with realistic wait times and energy balance for annual demand.

## Key results (from report)
- Annual energy demand: **9.85 GWh** (≈ **27 MWh/day**).
- Sizing for net-zero: **5×2 MW** wind turbines (~**8.7 GWh/yr**), **5 MW PV** (~**3.7 GWh/yr**), **DESS 10 MWh** (90% eff.).  
- JBSS performance: M/M/3 megacharger queue → avg wait ≈ **1.82 min** (with given arrival/service rates).  
- Power demand peak (illustrative): ~**6.3 MW** combined.

## Methods
- **Wind:** Weibull fit, hub-height scaling, turbine power curve → hourly/annual energy.
- **PV:** Weather features + model-based estimation → hourly PV generation.
- **Arrivals/Queue:** Exponential inter-arrival; JBSS as M/M/s for megacharging + swap logic.
- **Economics:** CAPEX/OPEX, energy balance, levelized metrics.


