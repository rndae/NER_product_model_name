# 🛍️ NER for Product Titles: Brand and Model Name Recognition

## Overview
<img src="https://github.com/user-attachments/assets/da72d1b1-5b52-4b9d-9631-2bc0850db412" alt="NER Model" width="420">

<img src="https://github.com/user-attachments/assets/d075a828-3f16-48b6-85d4-2a8dbceb38a8" alt="NER Inference" height="150">

This project implements Named Entity Recognition (NER) to extract brand and model names from product titles using a BI-LSTM-CRF model. The performance of the model is measured by its f-1 score, achieving high accuracy with both Flair and spaCy implementations.

## 🚀 Key Results

- **Flair Implementation**
  - **Micro f-1 Score:** 97.6%
  - **Macro f-1 Score:** 86%
  - Efficient for non-overlapping listings and robust for specific dataset types.

- **spaCy Implementation**
  - **Overall f-1 Score:** 98.7%
  - Handles unexpected product listings better and provides higher accuracy.

## 🧪 Technologies Used

- Python
- TensorFlow
- Flair
- spaCy
- RNN
- BI-LSTM-CRF
- Amazon Berkeley Object (ABO) Dataset
- Jupyter Notebook

## 📂 Repository

[🔗 GitHub: rndae/NER_product_model_name](https://github.com/rndae/NER_product_model_name)

## 📜 Abstract

This article explains an implementation to recognize brand and model names in product titles using an RNN network, a BI-LSTM-CRF model. The performance of the model is measured by its f-1 score, which for our amazon product listings it scores 97.6% at the micro level and 86% at the macro level with a Flair implementation, while we have an overall f-1 score of 98.7% using a spaCy implementation.

## 🔍 Conclusion

Overall, our Flair model seems very efficient as it is with its f-1 (macro) score of 86%, however this is specific for the type of data in our dataset and for non-overlapping listings. Comparing Flair with spaCy, we can see that Flair has more options to understand the model and is more robust and technical for our purpose. But still, spaCy handles the solution to our problem better with its 98.7% f-1 score and with its performance to unexpected product listings.
