# Simply_business
Below is a detailed explanation of each file and its purpose within the project.

## `Data_Extraction.ipynb`
This notebook performs two primary tasks:

1.Downloading Decision Files and Extracting Information:Download decision files and utilizes the GPT-3.5-turbo API to extract relevant information, resulting in the creation of `data_all.csv`.

2.Embedding Text Data: Downloads decision files and embeds the text data to generate the dataset required for the Neural Network model, resulting in the creation of `embeddings_num_df.csv`.

## `EDA.ipynb`
This notebook focuses on the first part of the report, which involves analyzing customer complaints to improve customer satisfaction. It includes exploratory data analysis (EDA) to uncover insights and patterns in the data.

## `Classification_Models.ipynb`
This notebook trains three classification models: Logistic Regression, Random Forest, and Neural Network

## `scrape.py`
This script is to scrape decision files from the Financial Ombudsman Service (FOS) website. 

## `enquiry_2023_2024.csv`
This CSV file records the number of enquiries received by the FOS regarding insurance products during the period of 2023-2024. 

## `pictures.xlsx`
Due to some limitations in the visualization within `EDA.ipynb`, some plots and charts were created using Excel to ensure better presentation and clarity.

## `data_all.csv`
This dataset is obtained from `Data_Extraction.ipynb` and contains the extracted information from the decision files. It is used for various analyses and modeling tasks within the project.

## `nn_tuning`
This file stores the results of the hyperparameter tuning process for the Neural Network model.

## `embeddings_num_df.rar`
Since the file is too large, I have uploaded it as rar file. When running the code, you will need to manually extract the contents.
This dataset is also obtained from `Data_Extraction.ipynb` and contains the embedded text data required for training the Neural Network model.
