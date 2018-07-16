# Modules description

# 001_index_download:
This module downloads html data from Pubmed ids.

# 002_metadata_download:
This mk downloads, fom the results of the first module, the metadata (title of paper, authors, and body of the text).

# 003a_pdf_download:
Download module which use wget and Firefox browser for the download of scientific papers registered in Pubmed Central (PMC).

# 003b_pdf_converter:
Convert any pdf file contained in this folder to text

# 004a_snps_finder_from_pdf:
This module uses the pdf downloaded converted to text and search the SNPs with grep and regular expressions

# 004b_ordered_snp:
Merge all the data into a table

# config.mk:
Necessary URLs.
# PUBMED_DOWNLOADER
