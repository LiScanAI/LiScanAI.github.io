---
# the default layout is 'page'
icon: fas fa-info-circle
order: 3
---
# Experimental datasets

## RQ1
> we collected data from models meeting four criteria: 
> * README files documenting component licenses and clauses (testing unstructured data extraction); 
> * Derivation from existing base models (enabling compatibility analysis);
> * Use of at least one AI license (validating AI-specific clause comprehension);
> * 1,000+ downloads (balancing representativeness and manual review costs).
{: .prompt-tip }
[**Download datasets in RQ1**](https://github.com/LiScanAI/LiScanAI.github.io/blob/main/datasets/RQ1.csv)
## RQ2
```
RQ2: Hierachical Licensing Status: LiScan.AI extracted primary licenses and additional clauses, enabling thorough consistency analysis between global and component licenses. 28601 IDs filtered on the Hugging Face used in Structured Analytic Hierarchy Process
```
{: .prompt-tip }
[**Download datasets in RQ2**](https://github.com/LiScanAI/LiScanAI.github.io/blob/main/datasets/RQ2.zip)
## RQ3
> RQ3: Large scale analysis of 184394 IDs used on the Hugging Face platform
{: .prompt-tip }

[**Download datasets in RQ3**](https://github.com/LiScanAI/LiScanAI.github.io/blob/main/datasets/RQ3.csv)
## RQ4
We submitted 114 issue reports covering 7 types of incompatible license combinations: 
>(1) AI license → AI license (10/114);
>(2) SPDX license → SPDX license (12/114);
>(3) SPDX license → AI license (58/114);
>(4) AI license → SPDX license (11/114);
>(5) Custom license → AI/SPDX license (6/114);
>(6) AI/SPDX license → Custom license (3/114);
>(7) derivative model or base model lack license declarations (14/114)
{: .prompt-tip }

[**Download datasets in RQ4**](https://github.com/LiScanAI/LiScanAI.github.io/blob/main/datasets/RQ4.xlsx)
## Download Ground truth

> RQ1_Ground truth: 
From 160 qualifying models, manual analysis identified 26 distinct licenses—including 17 AI licenses (major official and custom variants), 9 SPDX licenses (common on Hugging Face), and 12 additional clauses.
{: .prompt-tip }
[**Download 26 licenses in RQ1**](https://github.com/LiScanAI/LiScanAI.github.io/blob/main/datasets/ground%20truth%E8%AE%B8%E5%8F%AF%E8%AF%81%E6%96%87%E6%A1%A3.zip)

[**Download license terms in RQ1**](https://github.com/LiScanAI/LiScanAI.github.io/blob/main/datasets/ground_truth_rq1.xlsx)

