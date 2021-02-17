# sars-cov-2_sra_mdata

Collection of sra records that are missing certain metadata. I will try to update this as much as possible. 

## files
	Folder that contains the gzipped tsv files.

### SrrNoArticVInfo.tsv.gz
	A three column table ('BIOPROJECT', 'SRR_ID', 'AmpliconStrategy') containing SRR ids that did not have version number of ARTIC primer.

### SrrNoCountryInfo.tsv.gz
	A three column table ('BIOPROJECT', 'SRR_ID', 'ORIGIN_COUNTRY') containing SRR ids that did not have information on country name.

### SrrV4ArticInfo.tsv.gz
	A three column table ('BIOPROJECT', 'SRR_ID', 'AmpliconStrategy') containing SRR ids that have ARTIC primer version as 4.