# AVID README

The **AI Vulnerability Database (AVID)** is an open-source project, housing a knowledge base of vulnerabilities for large-scale AI/ML models. There are two parts AVID: a taxonomy and a database. These efforts are complimentary to each other in enabling data scientists and ML engineers proactively screen their ML systems for potential harms in an efficient manner.

## Taxonomy
The AVID taxonomy consists of categories and subcategories of potential harms encompassing coordinates of trustworthy ML, such as fairness, robustness, privacy, explainablity, and reliability, and alignment. Similar to the [MITRE ATT&CK](http://attack.mitre.org/) framework for cybersecurity risks and [MITRE ATLAS](https://atlas.mitre.org/) for adversarial ML threats, the AVID taxonomy will set a common, open standard to evaluate ML systems for downstream responsible behavior. Compared to MITRE ATLAS which pertains to intentional _attacks_ on ML systems, the AVID taxonomy will cover the area of _ML failures_ that are often unintentional in nature.

## Database
This will house full-fidelity information (model metadata, harm metrics, measurements, benchmarks, and mitigation techniques if any) on evaluation use cases of a harm (sub)category defined by the taxonomy. The aim here is transparent and reproducible model evaluations. Because of their ready availability and widespread use, we shall start by evaluating large-scale NLP models that are either open-source, or accessible through APIs. This database will be expandable to account for novel and hitherto unknown vulnerabilities, so that ML developers can freely share evaluation use cases for the benefit of the community. Contributions to this database will follow standardized formats, and will be vetted and curated.

## Contributors
The AVID Contribution Guide is coming soon!

## LICENSE
AVID is licensed under the [MIT License](https://opensource.org/licenses/MIT).

