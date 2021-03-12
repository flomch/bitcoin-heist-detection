
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/flomch/bitcoin-heist-detection/blob/main/bitcoin-heist-detection.ipynb)


# Oh gosh! Is that a bitcoin heist?!
Hi there! I'm Flora - currently a MS Data Science student at University of San Fracisco.    
     
This repo documents a project where I try to detect ransomware bitcoin accounts with machine learning.    

# Data
Active bitcoin accounts collected over a 24hr period from UCI data repository. Only 20% of the data was sampled, because I don't have access to a lot of computing power 🤷🏻‍
https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset    

# Findings 
Of the 3 model tested: random forest, logistic regression, and extra tree forest, random forest showed the most promising results. The model was pretty great about not missing ransomware bitcoin accounts (recall), but was rather lackluster about not mislabelling white accounts (precision). This is a classic example of the rivalry between precision and recall. 
