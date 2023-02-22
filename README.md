# Scopus
This code allows you to obtain information on articles published by UCSC faculty staff (RTDAs, RTDBs, Researchers, Assistant and Full Professors) from Scopus. The file "main.py" contains the code in Python language. The file "Researchers.xlsx" contains the list of all UCSC Medical School structured staff, updated to the end of 2022, and their Scopus IDs. Some researchers have more than one associated Scopus profile, and therefore the database was checked manually. Some discrepancies may exist, which please report.

To use the code you need to install the library "pybliometrics" (https://pypi.org/project/pybliometrics/) and obtain a Scopus key (https://dev.elsevier.com/)

The output files will be:
"Metriche_ricercatori.xlsl" containing with the basic metrics of the UCSC faculty members
"Paper.xlsx" containing the list of all published papers
