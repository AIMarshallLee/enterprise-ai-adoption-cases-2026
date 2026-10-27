# Case 7.4 (Japan): Healthcare — a 111-bed regional hospital runs an on-premises LLM for nursing summaries; vendor reports 54.2% time reduction from the third use onward

**Industry / scenario**: (Mid-size: social medical corporation, 111 general beds; the MHLW website's hospital profile lists 280 staff, from around FY2013 under the corporation's former name; a recruitment site lists 725 employees, undated) Oda Hospital (Yuaikai Social Medical Corporation), Kagawa Prefecture — described in the paper as a regional core hospital in Japan. Scenario: nurses writing admission/discharge nursing summaries and physicians writing referral letters.

**Pain point**: Per the vendor's press release, physicians and nurses spend time on records and reports beyond care; admission/discharge nursing summaries and referral letters are especially heavy. Other vendors' LLM services required connecting hospital systems to the internet — a costly security hurdle for hospitals with strict personal-data protection, slowing adoption. The paper also names paperwork as a major nursing burden.

**AI approach**: OPTiM built "OPTiM AI Hospital": an on-premises LLM that never touches the external internet, integrated with CSI's electronic medical record system "MI・RA・Is" to auto-generate admission/discharge nursing summaries and referral letters from EMR data.

**Outcome**: Vendor press release reports the on-premises generative AI auto-generating nursing summaries cut related work time by about 40%, published in the international journal *Nursing: Research and Reviews* (2026-03-10) (vendor-reported); Hirata R, Oda Y, et al., "On-Premises AI-Tool for Generating Nursing Care Summaries: A Phased-Implementation Study in Japan," *Nursing: Research and Reviews* 15:215–222 (2025-12-16) (academic study with vendor employees among authors). Vendor materials state a 54.2% reduction from the third use onward.

**Firm profile**: Hospitals with strict data-protection requirements that cannot use internet-connected LLM services but carry heavy fixed-format documentation loads.

*Sources: OPTiM press release (2026-03-10) (vendor-reported); Hirata et al., Nursing: Research and Reviews 15:215–222 (2025-12-16) (academic, vendor employees among authors); MHLW hospital profile (undated, scale basis); Caremap listing (undated, scale corroboration)*

> Provenance note: self-reported and vendor-reported figures are not verified by third parties — treat them as upper bounds. From *Enterprise AI Adoption Case Handbook (October 2026 edition)*, compiled by Kunlun Growth with number-by-number verification against primary sources.
