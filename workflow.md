---
layout: page
title: Workflow
permalink: /workflow/
---

### Main Work Flow

1. Business Domain Expert Consultancy
2. Data Warehouse Expert Consultancy
3. Cruft DDA (Discovery Data Analysis) with raw data
4. Data Sanity (filter relevant and consistent raw data)
5. ETL
6. Development loop (generally each ticket falls in one of the following category):
    * Data Cleansing (different from the data sanity)
    * feature engineering
    * feature selection
    * model
    * model selection
    * validation testing
    * scalability
    * benchmarking
    * I/O
7. Automated entry point(s)
8. Demo / Staging
9. Release into production
10. A/B testing (if applicable)
    1. Collect response data
    2. Results analysis (stakeholder review)
    3. Feedback into the model


### Development loop
1. Cruft DDA (discovery data analysis) specific to the open problem
2. Automated EDA (produce data summary reports and validate hypothesis)
3. modelling / problem details definition
4. unit tests / acceptance criteria
5. implementation
6. validation / benchmarking
7. outcome analysis
8. external documentation (wiki)
9. external review (code, logic and outcome)