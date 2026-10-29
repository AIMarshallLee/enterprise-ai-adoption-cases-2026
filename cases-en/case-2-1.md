# Case 2.1 (Germany): Electronics Manufacturing — Siemens' Amberg plant uses AI to predict which circuit boards need X-ray inspection and to warn of equipment failures 12 to 36 hours in advance

**Industry / scenario**: (Large enterprise: Siemens Electronics Works Amberg; Siemens materials from 2017 put the workforce at about 1,200) The plant produces Simatic industrial control products, with a portfolio of about 1,200 products and about 17 million units a year. The scenario is X-ray inspection on the PCB line and predictive maintenance of critical equipment.

**Pain point**: The automated X-ray inspection station at the end of the PCB line was a bottleneck, and buying an additional X-ray machine would cost about EUR 500,000. In addition, the milling spindles used to depanel (separate) circuit boards often malfunctioned because of milling dust, causing unplanned downtime.

**AI solution**: Sensor and process-parameter data from the production line are sent to the cloud to train a model, which is deployed on edge devices in the plant; based on process parameters, the model predicts whether a board's solder joints are good and whether the board needs final inspection. For the milling spindles, the team identified two parameters correlated with unplanned downtime — spindle speed and drive current — and used pre-trained algorithms on edge devices to detect anomalies, with the results displayed in Insights Hub (formerly MindSphere).

**Results**: According to Siemens presentation materials from 2019, necessary X-ray inspections were reduced by up to 30%, saving the EUR 500,000 investment in an additional X-ray machine; milling spindle failures can be predicted 12 to 36 hours in advance. (Basis: company self-reported — Siemens website and Siemens presentation materials from the ETSI AI Summit)

**Who this fits**: Electronics and precision manufacturers whose inspection stations have become capacity bottlenecks, whose critical-equipment downtime is costly, and who already collect process parameters.

*Sources: Siemens website, "Digital transformation: Leading by example" (Siemens Electronics Works Amberg feature page, undated); Siemens Corporate Technology, Dieter Wegener, "AI – Artificial Intelligence: Industrial applications" (ETSI Summit on AI, 2019-04-04); Siemens, "Leading as the Digital Enterprise" brochure (2017; source for headcount) (all company self-reported)*

> Provenance note: company self-reported and vendor-reported figures are not verified by third parties — treat them as upper bounds. Translated from the verified Chinese original in /cases (the Chinese text is authoritative). From the *Enterprise AI Adoption Case Handbook (October 2026 edition)* by Kunlun Growth (增长飞轮AI). Full edition (43 chapters, 235 cases) available on request via WeChat: MarshallPD.
