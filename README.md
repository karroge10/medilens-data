# MediLens site data

Parquet tables and JSON files behind the MediLens website, published as release assets
(release `site-data`). They are derived from the U.S. FDA Adverse Event Reporting System
(FAERS) through openFDA, which is public-domain data.

The files are read by the website in the browser with HTTP range requests. Nothing here is
medical advice: FAERS holds voluntary reports, a count shows what was reported, not how often
a reaction happens, and a report does not prove a drug caused it.
