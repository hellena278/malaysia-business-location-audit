# malaysia-business-location-audit
A Malaysian business location and data quality audit project focused on verifying business listings, evaluating source reliability, identifying information inconsistencies, and assessing location accuracy using evidence-based research.
# Petaling Jaya Local Business Data Quality Audit

A structured data verification audit evaluating the accuracy of **15 Google Maps business listings** across Petaling Jaya, Selangor (covering restaurants, cafés, pharmacies, clinics, supermarkets, and retail stores) against independent primary and secondary sources.

## Audit Summary

Across **60 evaluated data fields** (4 fields per business: Name, Category, Address, Operating Hours):
* **Verified:** 43 fields (71.7%)
* **Corrected:** 12 fields (20.0%)
* **Insufficient Evidence:** 5 fields (8.3%)

| ID | Business | Verified | Corrected | Insufficient |
| :--- | :--- | :---: | :---: | :---: |
| B001 | The Gathering Beast @ PJ | 2 | 1 | 1 |
| B002 | M Dining | 3 | 1 | 0 |
| B003 | La Chica Mexican Grill PJ | 3 | 0 | 1 |
| B004 | The Meat Experts Restaurant | 4 | 0 | 0 |
| B005 | Blank Coffee PJ | 3 | 1 | 0 |
| B006 | Alpro Sugi Pharmacy | 4 | 0 | 0 |
| B007 | Mega Kulim Pharmacy | 4 | 0 | 0 |
| B008 | Medix Pharmacy (Taman Paramount) | 3 | 0 | 1 |
| B009 | Klinik Lina GP | 2 | 2 | 0 |
| B010 | Evergreen Medical Clinic | 3 | 1 | 0 |
| B011 | NSK Grocer 3 Damansara | 2 | 1 | 1 |
| B012 | Jaya Grocer | 2 | 1 | 1 |
| B013 | Amcorp Mall | 2 | 2 | 0 |
| B014 | Spiral Store | 3 | 1 | 0 |
| B015 | Weird Space SS4 PJ | 3 | 1 | 0 |
| **Total** | **15 Businesses** | **43** | **12** | **5** |

## Key Findings

### 1. Operating Hours Discrepancies
* **Formatting & Typo Errors:** Maps listed overlapping Friday hours for *NSK Grocer* (`B011`) and apparent typo session times (`11:30 AM–8:00 PM, 5:50 PM–10:00 PM`) for *M Dining* (`B002`).
* **Outdated Schedules:** Official websites showed earlier closing times for *Evergreen Medical Clinic* (`B010`) and different weekday/Saturday hours for *Klinik Lina* (`B009`).
* **Missing Schedules:** *Weird Space* (`B015`) had no hours listed on Maps, which were recovered via its official Instagram page.

### 2. Address Discrepancies
* **Branch Mismatch:** *Klinik Lina* (`B009`) listed a different street address and postcode on its official website compared to Maps.
* **Missing Unit Numbers:** *The Gathering Beast* (`B001`) omitted unit `29A-G` on Maps.
* **Unconfirmed Mall Lot Numbers:** General mall addresses were verified for *NSK Grocer* (`B011`) and *Jaya Grocer* (`B012`), but exact basement/lower-ground lot numbers lacked independent confirmation.

### 3. Name & Category Consistency
* Business names and categories were largely accurate, with minor variations caused by Maps appending location tags or generic descriptors (e.g., *"Jaya Grocer Shopping Store"*).

## Methodology & Limitations
* **Sources Used:** Official business websites, verified Facebook/Instagram pages, reservation platforms (Umai), mall directories, and local news reviews (*Malay Mail*, *The Star*, *EatDrinkKL*, *Time Out*).
* **Limitations:** Sample size is limited to 15 POIs in Petaling Jaya; verification relies solely on publicly available online records without direct phone or on-site confirmation.
