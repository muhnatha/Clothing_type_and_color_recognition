# Clothing_type_and_color_recognition
This repository contains the Jupyter Notebook used for my data science project during the national-scale data science competition, **Hology**. The goal of this project is to identify clothes is it Tshir or hoodie and which color is it, red, white, black, or blue. The notebook demonstrates the application of various data science techniques, including data preprocessing, feature engineering, machine learning, and result analysis. 

# Dataset :
You can obtain the dataset by executing the following command in your terminal:
```sh
kaggle competitions download -c penyisihan-hology-7-data-mining-competition
```

Dataset Description:

The dataset consists of 1,111 product images of T-shirts and hoodies, collected manually from various online stores in Indonesia, with the following details:

train.zip: 

Contains 777 images of T-shirts and hoodies in 5 different colors for training data.

train.csv: 

A CSV file containing labels for each product image in the training data:

- id: A unique ID for each product image in the training data.
- jenis: Type of clothing (0: T-shirt, 1: Hoodie).
- warna: Clothing color (0: Red, 1: Yellow, 2: Blue, 3: Black, 4: White).
test.zip: Contains 334 product images of T-shirts and hoodies for classification purposes.

submission.csv: 

Example of a submission file in CSV format:

- id: A unique ID for each product image in the test data.
- jenis: Type of clothing (0: T-shirt, 1: Hoodie).
- warna: Clothing color (0: Red, 1: Yellow, 2: Blue, 3: Black, 4: White).
