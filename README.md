# Fraud Detection using Machine Learning and Deep Learning 

Machine Learning and Deep Learning 
Final Assignment

Students:  
Eleni Kalema: ID - 175891  
Florencia Cecilia Brazionis - ID 175974  
Lucia Argudin - ID 175893  

---

## Description

This project is designed to investigate the effectiveness of various machine learning and deep learning algorithms in detecting fraud within a highly imbalanced dataset.  
Using Logistric Regression, Random Forest, XGBoost and MLP.

---

## Dataset Access

Due to the large size of the dataset, we were unable to upload it directly to this repository.  
Instead, it has been uploaded to a **public Google Drive folder** for easy access. We apologize for any inconvenience this may cause.

**[Download the dataset from Google Drive](https://drive.google.com/file/d/1OMuIqQVbgDzGoOybqaGhj-iGWQZddwjB/view?usp=drive_link)**

You can also download it directly in code using the `gdown` Python package:

```python
import gdown

file_id = '1OMuIqQVbgDzGoOybqaGhj-iGWQZddwjB'
url = f'https://drive.google.com/uc?id={file_id}'
output = 'AIML Dataset.csv'
gdown.download(url, output, quiet=False)


```
