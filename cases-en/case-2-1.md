# Case 2.1 (Germany): Electronics manufacturing — Siemens Amberg plant predicts which PCBs need X-ray inspection and warns of equipment failures 12–36 hours ahead

**Industry / scenario**: (Large enterprise: Siemens Electronics Works Amberg, ~1,200 employees per 2017 Siemens material) The plant produces Simatic industrial control products, ~1,200 product variants and ~17M units per year. Scenario: X-ray inspection on the PCB line and predictive maintenance of critical equipment.

**Pain point**: The automated X-ray inspection station at the end of the PCB line was the bottleneck; an additional X-ray machine would cost ~€500,000. Milling spindles used for PCB depaneling also suffered unplanned downtime from milling dust.

**AI approach**: Line sensor and process-parameter data was sent to the cloud to train models deployed on factory edge devices, predicting whether solder joints pass and whether final inspection is needed. For the spindles, the team identified spindle speed and drive current as the parameters linked to unplanned stops, with edge-deployed pretrained algorithms detecting anomalies, visualized in Insights Hub (formerly MindSphere).

**Outcome**: Per Siemens 2019 presentation materials, necessary X-ray inspections fell by up to 30%, avoiding the €500,000 investment; milling spindle failures could be predicted 12–36 hours ahead. (Provenance: company self-reported — Siemens website and Siemens ETSI AI Summit talk.)

**Firm profile**: Electronics and precision-manufacturing firms where inspection is the capacity bottleneck, downtime is costly, and process parameters are already being collected.

*Sources: Siemens website "Digital transformation: Leading by example" (Amberg topic page, undated); Dieter Wegener (Siemens Corporate Technology), "AI – Artificial Intelligence: Industrial applications," ETSI Summit on AI, 2019-04-04; Siemens "Leading as the Digital Enterprise" handbook (2017, headcount basis) — all company self-reported*

> Provenance note: self-reported and vendor-reported figures are not verified by third parties — treat them as upper bounds. From *Enterprise AI Adoption Case Handbook (October 2026 edition)*, compiled by Kunlun Growth with number-by-number verification against primary sources.
