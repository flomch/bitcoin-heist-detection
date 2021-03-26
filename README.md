
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1k7cx67jdkQmr3odcc-eHV6UwnDL2nPQd?usp=sharing)


# Oh gosh! Is that a bitcoin heist?!     
This repo documents a project where I try to detect ransomware bitcoin transactions with machine learning.    

# Data
Active bitcoin transactions collected over a 24hr period from [UCI data repository](https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset). Only 20% of the data was sampled, because I don't have access to a lot of computing power.

# Findings 
Of the 3 model tested: random forest, logistic regression, and extra tree forest, random forest showed the most promising results. The model was pretty great about not missing ransomware bitcoin accounts (recall), but was rather lackluster about not mislabelling white accounts (precision). This is a classic example of the rivalry between precision and recall. 
