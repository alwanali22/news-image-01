# News Infographic: The World in One Day (13 November 2026)

This entry provides a high-impact, professional daily news infographic summarizing major global events of Friday, 13 November 2026.

## What the Image Shows
The 1024x1024 infographic features:
- **Top Bar:** Date header ("FRIDAY 13 NOVEMBER 2026") and edition title ("THE WORLD IN ONE DAY").
- **Banner Headline:** "EUROPE JOINS UKRAINE PEACE TALKS" detailing the largest prisoner swap of the war, US envoys meeting Putin in Moscow, and European leaders briefing in Dublin.
- **Six Core News Panels (Grid Layout):**
  1. *Hormuz / Iran Claims:* IRAN CLAIMS RADAR HIT, TANKER MINED IN HORMUZ (unverified claims, Brent crude $96).
  2. *Microsoft Outage:* MICROSOFT OUTAGE ENTERS DAY 2 (74 countries affected, Exchange Online failure).
  3. *Nvidia CEO:* NVIDIA CEO HUANG OUT, SENATE CALLS TESTIMONY (Jensen Huang resigns after 33 years; shares fall again on Friday).
  4. *Markets / Inflation:* US INFLATION +6.5%, BITCOIN BELOW $70K (October PPI hits highest annual rate since 2022; crypto slides; December Fed hike expected).
  5. *Starship:* STARSHIP ORBITS, BOOSTER CATCH OFF (Flight 15 reaches orbit from Starbase; 26 Starlink V3 satellites deployed).
  6. *FAA Ground Stop:* FAA GROUNDS ALL U.S. FLIGHTS (telecom outage halts 1,000+ flights across Air Route Traffic Control Centers).
- **Bottom Ticker:** Breaking sports news (Kane's record 126th cap; Pegula saves match point into WTA semis).
- **Footer:** Source citations (Reuters, AP, BLS, Microsoft, Nvidia, FAA, SpaceX).

## Implementation & Determinism
- Written in Python using **only the Python standard library** (`base64`, `os`, `sys`).
- Reads the output directory from the `MAKEFUN_OUTPUT_DIR` environment variable (falling back to `/output` if unset) and deterministically writes `entry.png` byte-for-byte identical every time.
