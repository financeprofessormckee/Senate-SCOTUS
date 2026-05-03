# Federal Judge Confirmation & Database Crosswalk (1946–2025)

This repository contains a linking file connecting federal judges to their confirmation dates, Senate party control at the time of confirmation, and major judicial decision databases.

The dataset is designed to facilitate empirical research linking judicial biographies to judicial decision-making databases.

# Overview
This file allows researchers to:

- Link a federal judge’s confirmation date with which political party held a majority in the U.S. Senate on the day of confirmation.
- Connect Supreme Court Justices, Circuit Court Judges, and District Court Judges to:
  - Their Federal Judicial Center (FJC) biographical information
  - The Supreme Court Database (SCDB)
  - The Songer Courts of Appeals Database
  - The Carp–Manning District Court Database

The linking file enables consistent cross-database identification of judges for empirical research.

# Data Structure

The Excel file is organized into five sheets:

**1. Readme**

Provides: 
- Data source descriptions
- Variable definitions
- Documentation of methodology

**2. Senate Majority Periods**

Contains:
- Start and end dates (inclusive) of each Senate majority period
- Political party holding the Senate majority during each period

This information is based on historical data published by the U.S. Senate.

If the Senate was evenly divided, the majority is assigned to the same party as the President, reflecting the Vice President’s tiebreaking authority.

**3. Supreme Court Justices Linking Table**

Includes:

- Justices included in the modern Washington University Supreme Court Database (SCDB)
- Exact confirmation date (from Federal Judicial Center biographies)
- Party holding the Senate majority on the day of confirmation
- SCDB unique identifier
- Federal Judicial Center (FJC) identifier

This enables linking biographical information to Supreme Court decisions.

**4. Circuit Court Judges Linking Table**

Includes:

- Judges included in the Songer Courts of Appeals Database
- Songer identifying variable
- Federal Judicial Center identifying variable

This allows linking appellate decision data to biographical records.

**5. District Court Judges Linking Table**

Includes:

Judges included in the Carp–Manning District Court Database

- Carp–Manning identifying variable
- Federal Judicial Center identifying variable

This enables linking district court decisions to biographical data.

# Time Period Covered

1946–2025.

The underlying research focused on post–World War II judicial decisions. Judges may not be included unless they authored decisions in one of the databases after 1945.

# Data Sources

This dataset links information derived from publicly available sources, including:

- Federal Judicial Center (FJC) Biographical Directory
- Supreme Court Database (Washington University)
- Songer Courts of Appeals Database
- Carp–Manning District Court Database
- U.S. Senate historical majority records
  
No raw source datasets are redistributed in this repository.

Users should consult the original sources for applicable licensing terms.

# Disclaimer

This data was gathered for use in academic research.

Despite careful compilation, the dataset may contain errors. The dataset is periodically updated as corrections are identified.

If you discover an error, please contact the repository author.

# Terms of Use

This linking file has been used in the following research:

> McKee, Eric; Macy, Anne; Zhang, Wei.  
> *With the Advice and Consent of the Senate He Shall Appoint Judges of the Supreme Court: The Importance of the Senate in Measuring Judicial Ideology.*  
> March 4, 2026. SSRN Working Paper.  
> [SSRN Abstract](https://ssrn.com/abstract=5155147)  
> [DOI: 10.2139/ssrn.5155147](https://doi.org/10.2139/ssrn.5155147)

If you use this dataset, please cite the relevant published paper(s).

# Version Information

- Time Period Covered: 1946–2025
- Last Updated: March 14, 2026

Future updates will document corrections and additions.

# License

The compilation and structure of this dataset are provided for academic research purposes.

Underlying source data remain subject to the terms of their original providers.
