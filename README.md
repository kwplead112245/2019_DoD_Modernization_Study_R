# 2019 DoD Modernization Study

This repository contains analysis completed in 2019 as part of graduate-level
coursework examining U.S. Department of Defense cybersecurity policy in relation
to private-sector industry standards.

The study used basic text mining techniques in R to explore prevailing themes,
key terms, and policy emphases across publicly available DoD and industry
cybersecurity documents. The work is descriptive in nature and reflects the
tools, methods, and skill level at the time it was completed.

## Research Focus
- How U.S. Department of Defense cybersecurity policy has evolved since the
  establishment of U.S. Cyber Command
- The extent to which industry cybersecurity standards are reflected in DoD
  policy language
- High-level similarities and differences between DoD and industry policy
  emphasis

## Data
The dataset was constructed from publicly available policy and standards
documents, including:
- Department of Defense CIO policy publications
- Joint Chiefs of Staff doctrinal publications
- U.S. Cyber Command materials
- NIST Special Publications
- MITRE Common Vulnerabilities and Exposures (CVE)
- NERC cybersecurity standards and guidance

Source PDFs are not included in this repository.

## Methods
- Text cleaning and preprocessing (lowercasing, punctuation removal, stop-word
  removal, stemming)
- Term frequency analysis
- Identification of common 2- and 3-word phrases
- Dictionary-based categorization of cybersecurity policy themes
- Comparative analysis between DoD and industry corpora

## Tools
- R
- tm
- quanteda
- ggplot2

## Repository Purpose
This repository is maintained for archival and illustrative purposes. It serves
as documentation of prior experience working with policy datasets and basic NLP
methods rather than as a representation of current analytical practice.

## Notes
Findings were exploratory and intended to support comparative discussion of
policy emphasis rather than to produce definitive conclusions about policy
alignment or effectiveness.
