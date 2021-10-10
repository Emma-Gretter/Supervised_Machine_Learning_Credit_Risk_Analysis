# Credit_Risk_Analysis

## Overview:

The purpose of this analysis is to determine which machine learning model best predicts credit risk.

## Results: 

- Naive Random Oversampling

Balanced Acuuracy Score - 0.640324421824783

Precision & Recall

<img width="300" alt="Screen Shot 2021-10-10 at 2 07 37 PM" src="https://user-images.githubusercontent.com/84678564/136711575-3caa7436-a4ed-4250-822e-607866abf9c1.png">


- SMOTE Oversampling

Balanced Acuuracy Score - 0.6514992150524688

Precision & Recall

<img width="291" alt="Screen Shot 2021-10-10 at 2 09 32 PM" src="https://user-images.githubusercontent.com/84678564/136711624-7d963e0d-0fb0-44af-b4dd-3be174b74790.png">


- Undersampling

Balanced Acuuracy Score - 0.6550612907408608

Precision & Recall

<img width="308" alt="Screen Shot 2021-10-10 at 2 10 46 PM" src="https://user-images.githubusercontent.com/84678564/136711651-61754a10-c7f1-4e29-8e1b-d76cf096a69c.png">


- Combination Sampling

Balanced Acuuracy Score - 0.5447046721744204

Precision & Recall

<img width="308" alt="Screen Shot 2021-10-10 at 2 10 46 PM" src="https://user-images.githubusercontent.com/84678564/136711673-3e08896b-ce7e-478b-a21d-3d3cb85fab9b.png">


- Balanced Random Forest Classifier

Balanced Acuuracy Score - 0.7885466545953005

Precision & Recall

<img width="310" alt="Screen Shot 2021-10-10 at 2 12 36 PM" src="https://user-images.githubusercontent.com/84678564/136711693-a5f97dfd-6417-4134-8c90-d0fa72632274.png">


- Easy Ensemble AdaBoost Classifier

Balanced Acuuracy Score - 0.9316600714093861

Precision & Recall

<img width="306" alt="Screen Shot 2021-10-10 at 2 12 58 PM" src="https://user-images.githubusercontent.com/84678564/136711708-b64af8bc-0c19-4fae-83ee-22837cd4a666.png">


## Summary: 

None of the models were able to reliably predict high-risk loans. Of the models tested I would suggest adaptive boosting since this model had the hights high-risk F1 score at 16%. 
