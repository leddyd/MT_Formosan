# MT Formosan
End-to-end machine translation for low-resource languages spoken by the indigenous peoples of Taiwan.

# Credits
This project was created by Hunter Scheppat, Dylan Leddy, Junhao Yan, Zelig Riyanto, and Christopher DiScala at Boston College.

# Prerequisites
* Google Drive account
* Colab compute hours
* Optional DeepL API key 

# Package Dependencies
```
BeautifulSoup
Selenium
Sacremoses
Sacrebleu
Sentencepiece
Transformers v.4.33
Datasets
Ipynb
Import-ipynb
```
Installations are handled through the notebooks.

# Usage
- Download the files in src and upload them to your Google Drive. Modify code directly in the Colab notebooks.
- We include our raw data (data/raw) - feel free to inspect them. Though, the only data you need for working with this project are the CSV files in data/unprocessed and data/processed.
- If you plan on using the pivot script, you'll need your own DeepL API key.
- Translator.ipynb is unfinished. Instead, use NLLB-fine-tuning.ipynb in src/scripts.

# Hugging Face models
- Amis to English | hunterschep/amis-english
- English to Amis | dylan-leddy/nllb-eng-ami-reverse
- Paiwan to English | hunterschep/paiwan-english
- English to Paiwan | hunterschep/english-paiwan
   
