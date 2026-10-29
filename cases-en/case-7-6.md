# Case 7.6 (United States, FAILURE CASE): Healthcare — External validation of Epic's sepsis prediction model: it missed 67% of patients while alerting on 18% of hospitalized patients

**Industry / scenario**: (Size undisclosed: a proprietary model from electronic health record vendor Epic, whose headcount is not public; the model is deployed at hundreds of US hospitals) The sepsis early-warning model built into US hospitals' electronic health record systems (the Epic Sepsis Model).

**Pain point**: Sepsis must be recognized as early as possible and treated with antibiotics; hospitals hoped to rely on the model built into the electronic health record for timely warnings.

**Why it failed**: The model is the vendor's proprietary model, and its previously published performance figures (AUC 0.76–0.83) came from the vendor's internal documentation. Michigan Medicine, the University of Michigan's academic health system, ran an external validation on its own data and found that the model's discrimination (hospitalization-level AUC) was only 0.63, far below the level the vendor reported.

**Outcome**: The study covered 38,455 hospitalizations of 27,697 patients, of which 7% involved sepsis. The model missed 1,709 patients with sepsis (67%) while issuing alerts for 18% of hospitalized patients; among sepsis patients whom clinicians did not treat with antibiotics in time, the model identified only 183 additional patients (7%). The study was published in JAMA Internal Medicine in 2021. Epic responded that the authors had chosen a lower threshold in a hypothetical configuration; that each health system has to set its own threshold, trading off missed cases against false alarms; and that, going by the paper's example, the model used in real time could have identified 183 patients who might otherwise have been missed.

**Lessons**: When buying a predictive model built into a vendor's product, validate it independently on your own data and calibrate its threshold before go-live, and keep monitoring alert volume against actual benefit; do not take the vendor's performance metrics at face value.

*Sources: Wong A, et al., "External Validation of a Widely Implemented Proprietary Sepsis Prediction Model in Hospitalized Patients," JAMA Internal Medicine 2021;181(8) (PMC full text) (independent research); Healthcare IT News, "Research suggests Epic Sepsis Model is lacking in predictive power" (Kat Jercich, 2021-06-22) (media report, includes Epic's statement)*

> Provenance note: company self-reported and vendor-reported figures are not verified by third parties — treat them as upper bounds. Translated from the verified Chinese original in /cases (the Chinese text is authoritative). From the *Enterprise AI Adoption Case Handbook (October 2026 edition)* by Kunlun Growth (增长飞轮AI). Full edition (43 chapters, 235 cases) available on request via WeChat: MarshallPD.
