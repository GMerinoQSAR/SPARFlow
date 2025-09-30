# SPARFlow
This repository contains all information relating to SPARFlow, an open-source KNIME workflow for SAR/SPR analysis. The workflow guides users through the process of loading and cleaning chemical datasets, and then calculating key metrics for assessing structure-activity or structure-property relationships. It consists of seven main sections:

(1) data entry and validation,

(2) chemical curation using the QSAR-compatible workflow;

(3) generation of an NSG; (4) clustered MCS search;

(5) decomposition of R groups and conversion into fragment descriptors;

(6) detection of activity discontinuities;

(7) calculation of modelability metrics (SARI and MODI* or RMODI).

Input files must follow a defined structure. The first column contains the chemical structures and the second contains the property or activity (potency) values, which can be binary, categorical or continuous. These potency values cannot be on a logarithmic scale. Additional columns are permitted, but the order of the first two columns must be maintained.
