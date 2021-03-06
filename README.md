# Dictionaries of Japanese terms and MeSH UIDs appeared in LitCovid
## Curated.xlsx
Curated Japanese terms for MeSH UIDs that appear 50 or more times in LitCovid set on PubAnnotation that are automatically annotated by PubTator (http://pubannotation.org/projects/LitCovid-PubTator-PubMed) as of BLAH7 (https://blah7.linkedannotation.org/).
### Note
* The UIDs actually appeared on the set are on the rows where  'MESH' is indicated in column A.
* The rows where column A is null are added for following reasons.
* 'Covid-19' (and its aliases) are assigned  UID C000657245 in MeSH2020 and also in LitCovid-PubTator set. However, the entry for Covid-19 is moved in MeSH2021 and its UID is now D000086382. We added row 1041 for the new UID.
* 'C093415' (row 488) was annotated to appearances of pO2 (partial pressure of oxygen) on documents such as PMID:33139142 (http://textae.pubannotation.org/editor.html?mode=edit&source=http://pubannotation.org/projects/LitCovid-PubTator-PubMed/docs/sourcedb/PubMed/sourceid/33139142/annotations.json) while UID C093415 (https://meshb.nlm.nih.gov/record/ui?ui=C093415) is for a kind of saponin.  We left row 488 as-is, and added row 1042 for the UID for partial pressure of oxygen. Note that MeSH Heading for UID D001785 is actually 'Blood Gas Monitoring, Transcutaneous' and its Japanese translation would be '経皮的血液ガスモニタリング' or '経皮血液ガスモニタリング' .
## Curated.tsv
Tab-separated file for (row E, row B) of Curated.xlsx to be uploaded to Pubdictionaries. Encoded in UTF-8.
## All.xlsx
Curated entries for count≧50 (same as Curated.xlsx) and uncurated entries for count<50 in separate sheets.
## WikidataMeSH.ipynb
Jupyter  (Google Colab) notebook for extracting MeSH UIDs and labels from wikidata. Needs SPARQLWrapper. 
