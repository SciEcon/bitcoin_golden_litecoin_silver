# Litecoin is Considered Silver to Bitcoin's Gold
Paper: 
## Supplymentary resources, data, and code

## Dataset on Harvard Dataverse

Yu, Haoyang; Yutong Sun; Yulin Liu; Luyao Zhang, 2023, "Replication Data for: Bitcoin Gold, Litecoin Silver: An Introduction to Cryptocurrency’s Valuation and Trading Strategy", https://doi.org/10.7910/DVN/AFIM6U, Harvard Dataverse, V1, UNF:6:0xBxaVg2w8KFLw6GsvtpZg== [fileUNF]

```
@data{DVN/AFIM6U_2023,
author = {Yu, Haoyang and Yutong Sun and Yulin Liu and Luyao Zhang},
publisher = {Harvard Dataverse},
title = {{Replication Data for: Bitcoin Gold, Litecoin Silver: An Introduction to Cryptocurrency’s Valuation and Trading Strategy}},
UNF = {UNF:6:0xBxaVg2w8KFLw6GsvtpZg==},
year = {2023},
version = {V1},
doi = {10.7910/DVN/AFIM6U},
url = {https://doi.org/10.7910/DVN/AFIM6U}
}
```

### Colab Notebook:
Code for generating the result of .csv file that used for generating the UTXO figure:

Bitcoin: https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/UTXO_%26_STXO_Visualization_Bitcoin.ipynb

Litecoin: https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/UTXO_%26_STXO_Visualization_Litecoin.ipynb

Code for generating the UTXO figure based on the .csv file:
https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/UTXO_Visualizations.ipynb

### Transaction Data Source:
Provided by Ethereum Blockchain Public Datasets:
https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/Transaction%20Datasets%20Source.md

## Instruction to the Process of Acquiring the UTXO and STXO data files:

### Overall Illustrasion:
<img src="https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/figures/Steps%20Illustrasion.png" width="1200" height="450"/>

### After the pre-work, before the first code(UTXO_Automatic_Updater):
1. Note down your project ID in the Google Cloud

2. Note down the altercoin's full name and brief name that to be researched

3. Determine the date to update the data to

<img src="https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/figures/figure1.jpg" width="1200" height="400"/>

1. Change the red rectangle to the altercoin's full name

2. Change the yellow rectangle to the altercoin's brief name

3. Change the green rectangle to the date to be updated to (form: y-m-d)

4. Change the blue rectangle to your project ID
