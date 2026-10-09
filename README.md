# Effects-of-de-Minimis-Trade
How did de minimis trade impact the fentanyl crisis?

Contributors:
  - Belen Gonzalez
# Executive summary
This project evaluates the relationship between low-value, duty-free trade (de minimis under 19 U.S.C. § 1321) and the supply of illicit synthetic opioids (fentanyl, analogues, and precursor chemicals) across U.S. jurisdictions.

While mortality and public health data are available at the state level via the CDC, official administrative data for de minimis shipments cannot be disaggregated by destination state or port of entry via standard FOIA channels. Customs and Border Protection (CBP) has formally confirmed that raw package data is technically unextractable and that port-level data is exempted from public release.

This is the information that was provided as substitution: https://www.cbp.gov/newsroom/stats/drug-seizure-statistics https://www.cbp.gov/document/foia-record/cbp-office-field-operations-statistics  https://www.cbp.gov/document/foia-record/cbp-border-patrol-statistics 

# Data collection & FOIA request timeline 
Initial Objective was a balanced state-level panel dataset (2018–2025) combining:
State-level and Port-of-Entry de minimis package counts, Entry Type 86 filings, and International Mail Facility (IMF) drug seizures. This would be obtained through an FOIA request. 

We requested 50-state, port-level, and long-panel (2000–2026) de minimis entry data and seizure logs.

> First Agency Response: Closed as "insufficiently described" and "too voluminous." CBP noted that processing billions of package records would crash their database systems.

In response we scaled back to pre-aggregated summary tables across a 2019–2024 panel focused on major logistics hub field offices.

> Second Agency Response: Granted / Denied de minimus package information.
> > FOIA Submission History & Formal CBP Determination
> > Initial Request (CBP-FO-2026-148048): Requested 50-state, port-level, and long-panel (2000–2026) de minimis entry data and seizure logs.
First Agency Response: Closed as "insufficiently described" and "too voluminous." CBP noted that processing billions of package records would crash their database systems.
Amended Scope Resubmission: Scaled back to pre-aggregated summary tables across a 2019–2024 panel focused on major logistics hub field offices 
Final CBP Determination: Granted / Denied de minimus package information.
Complete CBP Final Response Text
> > Dear Belén Gonzalez,
> > This is a final response to  Freedom of Information Act (FOIA) request to U.S. Customs and Border Protection (CBP), requesting de-minimus and seizure data.
> > CBP is granting our request under the FOIA, Title 5 U.S.C. § 552. Upon initial review of our request, we have determined that the following documents can be found on the internet at the following links:
https://www.cbp.gov/newsroom/stats/drug-seizure-statistics
https://www.cbp.gov/document/foia-record/cbp-office-field-operations-statistics (search for the drug seizures)
https://www.cbp.gov/document/foia-record/cbp-border-patrol-statistics (there is a fentanyl and drug seizures)
> > As for de-minimus data for the years We are seeking are impossible to obtain. This has been asked for by others. CBP receives a billion shipments per day and the system is not able to pull data of these imports without crashing the system. There is NO "pre-existing, macro-level annual summary tables" for this data.
> > Lastly, please be advised that no statistical or enforcement data is released at the port or "type of port" level.
> > This completes the CBP response to our request. We may contact CBP's FOIA Public Liaison, Charlyse Hoskins [...]

# Key takeaways from agency response
Technical Infeasibility: CBP does not maintain pre-calculated, state-level or port-level summary tables for Section 321 shipments. Extracting raw transaction logs is technically unfeasible due to high volume.


Policy / Enforcement Exemption: CBP explicitly maintains a policy against releasing statistical or drug seizure data disaggregated at the port or field office level.


Public Baselines: CBP directs researchers to national-level public enforcement and drug seizure statistics published on CBP.gov.

# Proposed next steps 
- Policy Shock Design: Evaluate the impact of major federal policy shifts regarding de minimus trade on national drug trends.
> The Trade Facilitation and Trade Enforcement Act of 2015 - 2016: $200 - $800 increase led to higher package volumes - did fentanyl overdoses increase at the same time?
> Synthetics Trafficking and Overdose Prevention act of 2018: postal service providers had to collect digital tracking data - did this decrease fentanyl overdoses?
> > Prior to this CBP officers had to manually inspect paper labels decreasing the ability to filter out illicit drugs
> > 
> "Addressing the Synthetic Opioid Supply Chain and Ending De Minimis for Covered Foreign Jurisdiction" 2025–2026: recent federal actions restricted or suspended de minimus duty free treatment - did the policy impact overdoses?
> > Eliminated de minimis treatment for goods originating from China and Hong Kong

- Logistics Gateway & Infrastructure Proxies: Utilize proxy state-level package exposure since direct port-level package counts are restricted
> Department of Transportation (DOT) Air Cargo Tonnage: International express freight landings at primary air hubs (e.g., Memphis/FedEx, Louisville/UPS, Cincinnati/DHL, JFK, LAX).
> > This method is not favorable since it requires estimation of assumption of causation

# Questions for discussion
Should we proceed with a Difference-in-Differences (DiD) design around the 2018 STOP Act or the 2025–2026 de minimis policy suspension using air cargo hub proximity as a continuous treatment variable?

Do you recommend applying for restricted researcher access through a Federal Statistical Research Data Center (FSRDC), or focusing strictly on public DOT air freight and CDC WONDER data for this term?

# Other potential projects: 
- Labor Economics & Productivity
> Topic: Synthetic Opioid Proximity and Labor Force Participation: A Spatial Panel Analysis
>
> Core Question: To what extent does localized synthetic opioid mortality depress prime-age (25–54) labor force participation rates across U.S. counties?
>
> Economic Theory: Human capital depletion, labor supply elasticity, and regional economic hysteresis.
>
> > Key Datasets: Bureau of Labor Statistics (BLS Local Area Unemployment Statistics), Bureau of Economic Analysis (BEA regional income data), CDC WONDER county-level data.

- Public Finance & Local Government Budgets
> Topic: Fiscal Strain and Local Public Service Provision in High-Overdose Jurisdictions
>
> Core Question: How do surges in county-level fentanyl overdoses affect local government spending allocations toward emergency medical services (EMS), law enforcement, and public health relative to education or infrastructure?
>
> Economic Theory: Local public goods allocation, crowd-out effects, and fiscal capacity constraints.
>
> > Key Datasets: U.S. Census Bureau Annual Survey of State and Local Government Finances,National EMS Information System (NEMSIS), CDC WONDER.

# 09/07/26 Policy research
Questions to ask: What are these policies and their objectives? Are they really able to impact de minimis trade, and are there any geograhpical differences in the implementation of these policies?

- Trade Facilitation and Trade Enforcement Act of 2015 (TFTEA)
> Description: Protects economic security through trade enforcement, collaborates with the private sector through direct engagement and streamlines and modernizes through business transformation. Specifically, it raised the deminimis value from $200 to $800 per shipment.
> > Now, de minimis rule no longer applies- any shipment even under $800 is subject to U.S. Customs duties, fees, and taxes.
   
- Synthetics Trafficking and Overdose Prevention Act of 2018 (STOP ACT)
> Description: Provides CBP the processing of central international mail shipments to require the provision of advance electronic information on international mail shipments.

- Executive Order 14295
> Description: U.S. suspended the duty free de minimis exemption for low value shipments alongside targeted tariffs to curb the supply chain of illicit synthetic opioids like fentanyl.

# Data collection outline
1. Data Collection & Dataset Building
> Search Core Databases: Go to CBP.gov's "Stats and Summaries" page for annual De Minimis Shipments numbers (volume grew from ~220M shipments in FY2016 to over 1B in FY2024).
Compile Enforcement Counts: Download CBP enforcement data specifically for fentanyl seizures in international mail facilities (IMFs) versus commercial express consignment hubs.
Retrieve Oversight Reports: Query the GAO and USPS OIG databases using keywords "STOP Act implementation", "Section 321", and "Advance Electronic Data".
2. Multi-Level Implementation Analysis Framework
> To analyze implementation across different levels of government and logistics, organize our framework along these three tiers:
> > Macro / Policy Level (Federal & Executive):Legislative intent vs. actual regulatory rules enacted by Treasury, DHS, and U.S. Postal Service.
> > Inter-agency friction (e.g., operational friction between USPS postal regulations and CBP customs enforcement).
> > Meso / Operational Level (Port & Infrastructure): How Air Cargo Advance Screening (ACAS) and Type 86 Customs entries were deployed at major ports (e.g., JFK, LAX, Cincinnati, Memphis).Capacity challenges at International Mail Facilities (IMFs) in scanning millions of daily low-value packages.
> > Micro / Private Sector & Compliance Level: Compliance burdens placed on global e-commerce platforms (Shein, Temu, Amazon) and foreign postal operators. Shift in carrier behaviors (e.g., shifting shipments from postal channels to express consignment carriers to ensure AED compliance).

# 09/20/26 Policy research: who, what, where and why?
Diving deeper, we want to take a look at the definition of these policies and how exactly they have been implemented and why; for the purpose of analyzing which policy, if any, can be utilized as a lens to look at the impact of de minimis trade on fentanyl crisis.

U.S. De Minimis Trade Policy & Enforcement: TFTEA, STOP Act, and Executive Order 14295

Comparative Executive Summary
> Policy Dimension	Trade Facilitation & Trade Enforcement Act (TFTEA):
> > Signed: Feb 24, 2016 & Effective: March 10, 2016
> > 
> > Primary Implementing Agencies: U.S. Customs and Border Protection (CBP), Dept. of Treasury
> > 
> > Core Objective: Modernize trade, reduce administrative burden, raise de minimis threshold from $200 to $800.
> > 
> > Primary Enforcement Hotspots: Commercial Express Air Hubs (Memphis, Louisville, CVG) & Land Borders (Laredo)
> > 
> > Annual Volume Impact: Triggered explosive growth: 220M packages (FY16) → 1.36B packages (FY24).

> STOP Act of 2018:
> > Signed: Signed: Oct 24, 2018 & Effective: Phased through Jan 1, 2021
> >
> > On Dec 31, 2018 USPS was required to receive AED on at least 70% of all international mail shipments arriving from China. In 2019 AED was required on 100% of shipments from China. On January 1, 2021 the law mandated that 100% of all international postal packages worldwide must have AED sent prior to arrival; USPS was legally required to turn back packages that failed to comply.
> >
> > Primary Implementing Agencies: U.S. Postal Service (USPS), CBP
> >
> > How did they implement it?
> > > Prior to 2018, foreign postal operators sent physical letters and packages wrapped under Universal Postal Union (UPU) treaty agreements using paper declarations attached to sacks of mail.
> > > 
> > To comply with the STOP Act, USPS executed a complete operational and digital transformation:
> > > Diplomatic & Treaty Restructuring: USPS worked through the Universal Postal Union (UPU) in Geneva to establish global IT standards so foreign posts (e.g., China Post, Royal Mail) could capture sender/recipient data electronically at retail counters.
> > > 
> > > IT System Integration: USPS built the Customs Data System (CDS) and updated its Shipping Services File (SSF) architecture. This system ingested real-time XML data feeds from over 190 foreign postal operators before packages ever touched an aircraft bound for the U.S.
> > >
> > >
> > About USPS:
> >
> > > Data Offloading to CBP: USPS integrated its IT pipeline with CBP's Automated Targeting System (ATS). Before a plane touched down at JFK or O'Hare, ATS automatically scanned the electronic manifest text to look for high-risk red flags.
> > >
> > Physical Sorting & In-Facility Interception: At USPS International Service Centers (ISCs), USPS deployed automated barcode scanners tied directly to CBP’s ATS risk feed. When a package passed along the conveyor belt, if CBP flagged the AED as high-risk, the scanner triggered a mechanical arm to divert the package out of the mail stream into a secured CBP inspection room.
> >
> > Core Objective: Mandate Advance Electronic Data (AED) on all international mail packages.
 Primary Enforcement Hotspots: USPS International Service Centers (JFK ISC, Chicago ISC, LAX ISC)
> > 
> > What is AED?
> > 
> > > Advance Electronic Data (AED) is a digital message containing crucial tracking and identity information sent to border authorities before a physical package arrives in the destination country.
> > > 
> > > Under statutory regulations (19 CFR § 145.74), mandatory AED fields include:
> > > 
> > > > Sender Information: Full legal name, physical address, and origin country.
> > > >
> > > > Recipient Information: Full legal name and delivery street address in the U.S.
> > > >
> > > > Itemized Contents: Detailed item description (e.g., "Cotton Men's Shirt" vs. vague descriptions).
> > > >
> > > > Package Metrics: Declared value, gross weight, and quantity.
> > > >
> > > > Tracking & Routing: Unique S10 13-character barcode identifier and flight/routing details.
> > > >
> > How does it work?
> > 
> > > CBP's Automated Targeting System (ATS) uses machine learning and artificial intelligence to evaluate millions of AED records in seconds. It scores package risk using rules such as:
> > >
> > > > Address Matching: Cross-referencing sender or recipient names/addresses against known DEA and law enforcement databases of illicit chemical vendors and pill press buyers.
> > > >
> > > > Text & Anomaly Parsing: Flagging generic or suspicious cargo descriptions (e.g., "Plastic Toy" weighing 5 kg, or terms associated with known precursor masking strategies).
> > > >
> > > > High-Risk Origin & Route Analysis: Scoring parcels routed through known transshipment hubs or origin post codes associated with chemical manufacturing.
> > > >
> > > > When ATS flags a parcel for physical verification at an ISC or express hub, officers use advanced non-intrusive inspection hardware:
> > > >
> > > > Low-Energy & Dual-Energy Computed Tomography (CT) Scanners: Similar to medical CT scanners, these high-speed X-ray systems generate 3D volumetric images of packages moving on high-speed belts, allowing software to detect density anomalies inside sealed packages (e.g., powders hidden inside hollowed-out machinery or toys).
> > > >
> > > > Handheld Raman Spectroscopy Devices (e.g., Thermo Scientific TruNarc): Field officers use laser-based handheld chemical analyzers to identify chemical compounds through plastic bags or vials without opening the chemical packaging, instantly identifying fentanyl analogs, precursors, or synthetic cathinones in seconds.
> > > >
> > Annual Volume Impact: Closed anonymity gap for ~400M annual postal packages; established digital screening trace.
 
- Executive Order 14295:
-
> > Issued: April 2025 & Fully Enforced: August 2025
> >
> > Primary Implementing Agencies: Department of Homeland Security (DHS), CBP, Dept. of Commerce
> >
> > Core Objective: Eliminate duty-free de minimis treatment to disrupt synthetic opioid supply chains.
> >
> > Primary Enforcement Hotspots: Major Commercial Express Gateways, Postal ISCs, Southwestern Land Border POEs
> >
> > Annual Volume Impact: Reduced low-value duty-free filings by ~75%; shifted shipments to formal/informal entry.
> >
> > > Understanding this 10x growth (140M → 1.36B) explains why the U.S. government stepped in with the STOP Act (to force electronic tracking data on postal mail) and ultimately Executive Order 14295 (to dismantle or restrict duty-free de minimis access). 

# Why the STOP Act is the best choice
- Direct Causal Link: TFTEA was designed broadly for trade facilitation, and Executive Order 14295 covers tariffs and revenue. In contrast, the STOP Act was written explicitly to combat fentanyl trafficking through small mail parcels.

-  Clear Measure of Success (AED Data): The STOP Act mandated Advance Electronic Data (AED). This gives us a clear metric to study: comparing fentanyl interception rates before electronic tracking (paper mail tags) versus after full AED enforcement.

-  Focused Data Targets: It allows us to focus our empirical research on specific locations—the five USPS International Service Centers (ISCs) (JFK, O'Hare, LAX, Miami, San Francisco)—making our scope manageable and targeted.

-  Natural Policy Comparison: The STOP Act created a clear contrast between private carriers (like FedEx/UPS, which already used electronic tracking) and global postal services (USPS), giving us a well-defined comparison model for our project.
> # Primary access points for AED & package data
- Public Federal Portals & Data Catalogs
CBP Data Portal (cbp.gov/newsroom/stats): Provides monthly and annual Section 321 entry stats, Type 86 clearance volumes, and enforcement seizure metrics.
USPS Annual Reports & Financial Filings (about.usps.com): Tracks overall international inbound parcel volumes and country-level exchange metrics.
DHS Data Services (data.gov): Hosts aggregated trade datasets for cross-border package arrivals and port-of-entry statistics.
- Federal Watchdog Reports (Pre-Aggregated Data Sets)
If we need structured data on AED compliance percentages, foreign post transmission rates, or postal facility inspection rates, these agency reports include detailed tables and charts:
USPS Office of Inspector General (USPS OIG): Search white papers and audit reports on Advance Electronic Data Implementation (e.g., Report No. 20-221-R21). They publish tables detailing AED transmission rates by origin country.
U.S. Government Accountability Office (GAO): Reports like GAO-23-105 (International Mail Security) contain aggregated data on AED risk-targeting scores, inspection rates, and enforcement bottlenecks at International Service Centers (ISCs).
