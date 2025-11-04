# Client-level-analysis

## Description

This repository contains automated scripts designed to run client to client and field to field  level analysis across different reports such as **RADET**, **HTS**, **PMTCT_HTS** and many more.

## 🚀 Getting Started

### 1\. Prerequisites

* **Python 3** or **Google Colab**

### 2\. How to Run the Script

1.  **Download** the specific script you need.

2.  **Open** the file in any text editor (VS Code, Notepad, Sublime Text, etc.).

3.  **Edit the required variables** at the very top of the script (see the next section).

4.  **Save** the file.

5.  **Run the saved file in your Terminal or Command Prompt or on google colab.**


## 📝 Required Variable Changes

Each script is pre-configured with placeholder variables. You **MUST** update these variables inside the Python file to point to your local machine's folders:

| Variable Name | Purpose | Example Value to Change |
| :--- | :--- | :--- |
| **`folder_Client`** | The **input directory for Client report** containing the raw data files from `client` that the script needs to check. | `"C:/Users/oluwabukola.arowolo/OneDrive - Palladium International, LLC/Documents/DataFi/Client_level_analysis/RADET"` |
| **`folder_centralsync`** | The **input directory for Centralsync report** containing the raw data files from `centralsync` that the script needs to check. | `"CC:/Users/oluwabukola.arowolo/OneDrive - Palladium International, LLC/Documents/DataFi/Client_level_analysis/Centralsync"` |
| **`output_path`** | The **output directory** where the final aggregate data will be saved. | `"C:/Users/oluwabukola.arowolo/OneDrive - Palladium International, LLC/Documents/DataFi/Project_Export_Quality_Check"` |


**⚠️ IMPORTANT:**
  
  * Keep the **quotes** around the file paths\!

-----

## 📁 Available Scripts

This repository contains the following aggregating indicator scripts:

| Script Filename | Indicators | Description |
| :--- | :--- | :--- |
| **`Client-level-analysis-(ip-radet-VS-sync).py`** | Treatment and Prevention | aggregates indicators specific to RADET report. |
| **`Client-level-analysis-(ip-radet-VS-ndr).py`** | HTS | aggregates indicators specific to HIV Testing Services (HTS) report. |
| **`Client-level-analysis-(ip-tb-VS-sync).py`** | PMTCT_HTS | aggregates indicators specific to Prevention of Mother-to-Child Transmission (PMTCT) report. |
| **`Client-level-analysis-(pmtct_hts-VS-sync).py`** | HTS_INDEX | aggregates indicators specific to HTS_INDEX report. |
| **`Client-level-analysis-(ip-prep-long-VS-sync).py`** | PrEP | aggregates indicators specific to PrEP report. |
| **`Client-level-analysis-(ip-prep-cross sectional-VS-sync).py`** | Treatment and Prevention | aggregates indicators specific to RADET report. |
| **`Client-level-analysis-(ip-pmtct-maternal-VS-sync).py`** | HTS | aggregates indicators specific to HIV Testing Services (HTS) report. |
| **`Client-level-analysis-(ip-pharmacy-VS-sync).py`** | PMTCT_HTS | aggregates indicators specific to Prevention of Mother-to-Child Transmission (PMTCT) report. |
| **`Client-level-analysis-(ip-laboratory-VS-sync).py`** | HTS_INDEX | aggregates indicators specific to HTS_INDEX report. |
| **`Client-level-analysis-(ip-hts-VS-sync).py`** | PrEP | aggregates indicators specific to PrEP report. |
| **`Client-level-analysis-(ip-family-index-VS-sync).py`** | Treatment and Prevention | aggregates indicators specific to RADET report. |
| **`Client-level-analysis-(ip-eac-VS-sync).py`** | HTS | aggregates indicators specific to HIV Testing Services (HTS) report. |
| **`Client-level-analysis-(ip-clinic-VS-sync).py`** | PMTCT_HTS | aggregates indicators specific to Prevention of Mother-to-Child Transmission (PMTCT) report. |
| **`Client-level-analysis-(ip-client-verification-VS-sync).py`** | HTS_INDEX | aggregates indicators specific to HTS_INDEX report. |
| **`Client-level-analysis-(ip-biometrics-VS-sync).py`** | PrEP | aggregates indicators specific to PrEP report. |
| **`Client-level-analysis-(ip-ahd-VS-sync).py`** | Treatment and Prevention | aggregates indicators specific to RADET report. |


-----

## ❓ Troubleshooting & Support

  * **Error running the script?** Double-check that your `folder_client`, `folder_centralsync`, and `output_path` are correctly formatted and enclosed in quotes.

## Authors & Acknowledgement
-----
## 👥 Main Contributors

  * **[Arowolo Oluwabukola]** ([@Haddy-Oluwabukola](https://github.com/Haddy-Oluwabukola))
  

For further assistance, please contact the main contributor or open an **Issue** on this GitHub page.
