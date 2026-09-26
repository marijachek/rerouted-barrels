# rerouted-barrels
# Rerouted Barrels: Tanker Traffic Through Hormuz, Bab el-Mandeb and Suez, 2023–2026

**Question:** How did oil tanker traffic shift between the four main Gulf–Europe/Asia chokepoints after the Houthi attacks (2023), the Hormuz crisis (Feb 2026) and the Houthi blockade of Saudi shipping (July 2026)?

**Data:** IMF PortWatch, Daily Chokepoint Transit Calls and Trade Volume Estimates, 1 Jan 2023 – 20 Sep 2026.

**Method:** Python (pandas, matplotlib). Daily tanker transits and capacity compared with a pre-crisis baseline (average day, 1 Jan–15 Nov 2023) for 2024, H1 2026 and 20 Jul–20 Sep 2026.

**Key findings:**

- Hormuz: recorded tanker capacity −77% in H1 2026 and −99% after 20 July vs 2023.
- Bab el-Mandeb: tanker capacity recovered from −56% (2024) to −46% (H1 2026), then fell to −71% after the blockade.
- Cape of Good Hope: tanker capacity +51% vs 2023; tanker transits roughly doubled.

**Limitations:** AIS-based counts undercount ships sailing "dark"; transits and capacity are not barrels carried; the post-blockade window is 63 days.

**Files:**

- [Analysis notebook](rerouted_barrels.ipynb)
- [Results: % change vs baseline](results_pct_change.csv)
- [Results: daily averages](results_daily_average.csv)
- Charts: [chart 1](chart1_weekly_tankers.png), [chart 2](chart2_pct_change.png), [chart 3](chart3_tankers_vs_containers.png)
- [Read the full report (PDF)](rerouted-barrels.pdf)

**Raw data:** not included; download it from [IMF PortWatch](https://portwatch.imf.org/datasets/42132aa4e2fc4d41bdaf9a445f688931_0/about) 

**Author:** Maria Cekmariova
