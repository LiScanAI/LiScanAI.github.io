---
icon: fas fa-stream
order: 1
---



# [**LiScanAI**](https://liscanai.github.io/)

LiScan.AI, the first LLM-powered framework for automated detection of license incompatibilities
for AI artifacts. It combines License-aware Model Derivation (LMD) Graphs for derivation tracking, legally validated SPDX/AI license term taxonomies, and LLM-powered semantic analysis to detect incompatibilities across 27 license terms.

## Supported Platforms

🔸Windows 11

🔸Python 3.7 or later

## Quick Start

### Step 1.Download **Liscan**

 Download all compressed parts listed on the [**liscan**](https://drive.google.com/drive/folders/11s-l5O47cfzuywNykRbK3cMuli1rwmqg) page, and extract them to obtain **main.exe**, **ailicense** etc.
 

 
### Step 2.Install Liscan

> Copy **main.exe** to any directory on your system.
{: .prompt-tip }

### Step 3.Configure Liscan Data

 > * Install **ailicense** on your system.
 > * Download the datasets of Liscan.
>  * Add it to the **same directory** as main.exe.
{: .prompt-tip }

### Step 4.Run Liscan

Open a command line window in the directory where main.exe is located and run:

```
D:\aiscanner\dist> main.exe
```

### Step 5.Obtain results

 > You can view the results in the following ways:
 > * View the folder for each model under test in the output_demo folder.
>  * Each folder for each model under test contains folders for several test pairs.
>  * Each folder for each test pair contains documentation on the test steps.
>  * The output file output_demo.csv summarizes the results.
{: .prompt-tip }

