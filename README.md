# PP25-Rural-Road-Prioritization
Python–SQLite decision-support system for rural road upgrading prioritization using Utility Value and Network Performance Index (NPI) methods with reproducible case-study dataset.
1. Overview
PP25 is a Python–SQLite based infrastructure decision-support system developed to support systematic prioritization of rural road upgrading projects. The tool integrates multi-criteria indicators including:
•	Road length
•	Population served
•	Service accessibility/connectivity
•	Network Performance Index (NPI)
The system generates automated ranking outputs to support transparent and reproducible infrastructure planning decisions.
2. Research Context
This repository accompanies the research paper submitted to:
Journal of Infrastructure Systems
Special Collection: Planning and Development of Urban Transportation Infrastructure Systems in Transitional Economies
Case Study:
Ambernath Block, Thane District, Maharashtra, India
25 rural road links analyzed.
3. Methodology Implemented
The tool implements:
1.	Utility Value Method
2.	Network Performance Index (NPI)
3.	Correlation-based validation
Outputs include:
•	Priority ranking
•	Comparative scoring
•	Validation statistics
4. Repository Structure
PP25/
│
├── src/                 # Python source code
├── database/            # SQLite database file
├── data/                # Input dataset (CSV format)
├── results/             # Output ranking tables
├── LICENSE.txt
└── README.md
5. Data Availability
The dataset provided corresponds to the 25-road case study used in the published research. The repository enables reproducibility of ranking results.
6. License
Copyright © 2025 [Pravinkumar Jagtap,Dr.Prashant P. Nagrale]
All Rights Reserved.
This software is shared for academic transparency only. Commercial use is not permitted without written permission.
7. Contact
For academic queries:
[psjagtap80@gmail.com,p_nagrale@spce.ac.in ]
