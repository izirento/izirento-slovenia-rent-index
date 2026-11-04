# Slovenia: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Slovenia: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- EU rent price change for all 27 member states: [izirento-eu-rent-index](https://github.com/izirento/izirento-eu-rent-index)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Housing Act (Stanovanjski zakon, SZ-1), as summarised by the Ministry on the "Najemna razmerja" (rental relations) page. | [Ministry of Natural Resources and Spatial Planning of Slovenia (PIS spatial information portal)](https://pis.eprostor.gov.si/pis/stanovanja/najemna-razmerja) |
| contract_form | Form and content | A dwelling is let by a written lease for a fixed or indefinite term. The lease must contain at least: description of the dwelling, owner and tenant details, termination grounds under Art. 103 SZ-1, type of rental category, amount of rent and how and when it is paid, how running costs are charged, and the duration if fixed-term. | [Ministry of Natural Resources and Spatial Planning of Slovenia (PIS spatial information portal)](https://pis.eprostor.gov.si/pis/stanovanja/najemna-razmerja) |
| landlord_duties | Owner obligations | The owner must hand over the dwelling in a state allowing normal use, maintain the dwelling and common parts throughout the lease, and answer for legal and physical defects. | [Ministry of Natural Resources and Spatial Planning of Slovenia (PIS spatial information portal)](https://pis.eprostor.gov.si/pis/stanovanja/najemna-razmerja) |
| termination | Tenant notice | Unless agreed otherwise, the tenant may terminate without giving reasons by written notice with a 60-day notice period. | [Ministry of Natural Resources and Spatial Planning of Slovenia (PIS spatial information portal)](https://pis.eprostor.gov.si/pis/stanovanja/najemna-razmerja) |
| termination | Owner notice and eviction | The owner terminates with a notice period of not less than 60 days and cannot demand the tenant move out before repaying the tenant's investments; disputes are decided by court action, and the court sets a move-out period of 30 to 60 days. | [Ministry of Natural Resources and Spatial Planning of Slovenia (PIS spatial information portal)](https://pis.eprostor.gov.si/pis/stanovanja/najemna-razmerja) |
| termination | Fault-based grounds and warning | The owner may terminate for fault-based grounds listed in Art. 103 SZ-1 (for example, rent or costs not paid within the contract deadline or, if none, within 60 days of receiving the invoice; unauthorised sub-letting; refusing entry). The tenant must first receive a written warning naming the breach and giving at least 15 days to remedy it; for the same breach the owner warns only once unless more than a year passes between two breaches. | [Ministry of Natural Resources and Spatial Planning of Slovenia (PIS spatial information portal)](https://pis.eprostor.gov.si/pis/stanovanja/najemna-razmerja) |
| tenant_duties | Owner access | The tenant must allow the owner or representative to enter to check proper use, at most twice a year. | [Ministry of Natural Resources and Spatial Planning of Slovenia (PIS spatial information portal)](https://pis.eprostor.gov.si/pis/stanovanja/najemna-razmerja) |
| rent_level_change | Rent price change, 2025 annual average (HICP actual rentals for housing) | 1.9 percent (2024: 6.3 percent) | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_aind?format=JSON&lang=EN&coicop=CP041&unit=RCH_A_AVG&geo=SI&time=2025) |
| rent_level_change | Rent price change, December 2025 year on year (HICP actual rentals for housing) | 0.4 percent | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_manr?format=JSON&lang=EN&coicop=CP041&unit=RCH_A&geo=SI&time=2025-12) |

## Slovenščina

**Slovenija.** Odprti podatki o najemu in obveznostih najemodajalca: varščina, zvišanje najemnine, odpovedni roki in najemna pogodba, pri vsaki vrednosti povezava do uradnega vira.

*Podatki so na voljo takšni, kot so, brez kakršne koli odgovornosti. Le urejamo, kar objavljajo uradni viri. Zakoni se spreminjajo: vsako vrednost preverite v povezanem primarnem viru.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `slovenia_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |
| (Eurostat rows) | The last rows of the CSV hold the Eurostat rent price change for this country (HICP actual rentals, item CP041) |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Rent price change is the Eurostat HICP index of rents actually paid. It shows how rents moved, not what they cost. The API responses used were last updated by Eurostat on 6 February 2026, so the latest period is December 2025.
4. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Slovenia: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-slovenia-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
