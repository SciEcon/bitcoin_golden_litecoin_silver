# Litecoin is Considered Silver to Bitcoin's Gold
Paper: 
## Supplymentary resources, data, and code

### Author List:

Yulin Liu, Haoyang Yu, and Luyao Zhang

(Alphabetic order of surname)

### Colab Notebook:
Code for generating the result of .csv file that used for generating the UTXO figure:
https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/UTXO_Automatic_Updater.ipynb

Code for generating the UTXO figure based on the .csv file:
https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/UTXO_Visualizations.ipynb

### Transaction Data Source:
Provided by Ethereum Blockchain Public Datasets:
https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/Transaction%20Datasets%20Source.md

## Instruction to the Process of Acquiring the UTXO Figure:

### Overall Illustrasion:
<img src="https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/figures/overall%20illustrasion.png" width="1200" height="600"/>

### After the pre-work, before the first code(UTXO_Automatic_Updater):
1. Note down your project ID in the Google Cloud

2. Note down the altercoin's full name and brief name that to be researched

3. Determine the date to update the data to

<img src="https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/9401656491651_.pic.jpg" width="1200" height="400"/>

1. Change the red rectangle to the altercoin's full name

2. Change the yellow rectangle to the altercoin's brief name

3. Change the green rectangle to the date to be updated to (form: y-m-d)

4. Change the blue rectangle to your project ID

### After the first code, before the second code(UTXO_Visualizations):
Note down the link to the raw file of "altercoinResultUTXOyyyy-mm-dd.csv" and "altercoinResultSTXOyyyy-mm-dd.csv" that saved in a public Github repository. If you followed the instruction in the overall illustrasion, the two files can be found along the path "Github repository-UTXO-altercoin_UTXO".
Click the "Raw" bottom, the webpage will jump to the raw file page.
 <img src="https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/9461656493843_.pic.jpg" width="1200" height="300"/>
 
Change the yellow rectangle to the date to be updated to (form: yyyy-mm-dd)
 <img src="https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/9421656492997_.pic.jpg" width="1200" height="500"/>

1. Enter the altercoin's full name to the red rectangle, and brief name to the yellow rectangle.
2. Copy the links of the two raw .csv files, then paste them correspondingly to the blue and green rectangle.(STXO for STXOaddress, UTXO for UTXOaddress).
3. Change the function name in the second red rectangle to the altercoin's fullname. 
4. Change the second yellow rectangle to the altercoin's fullname, so that the function is "altercoin.Dist_UTXO()"
 <img src="https://github.com/SciEcon/bitcoin_golden_litecoin_silver/blob/main/9441656493147_.pic.jpg" width="1200" height="400"/>
