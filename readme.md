# Political Sentiment Analysis - NAACL DravidaLangTech (Task 4)

This repository contains the code and models used for Task 4 (Political Sentiment Analysis) in the **NAACL DravidaLangTech 2025** competition. The objective of this task is to classify political sentiment in Tamil code-mixed tweets.

## 📌 Project Overview  
The dataset consists of code-mixed Dravidian text labeled for political sentiment (7 classes). Various machine learning and deep learning models have been explored to achieve the best classification performance.

## 🚀 Best Performing Model  
The best-performing model in this project is **LaBSE + SVM**, which achieved the highest F1 Score among all tested approaches.

## 📂 Repository Structure  

```
📦 Project Root  
 ┃ ┣ 📜 .gitignore  
 ┃ ┣ 📜 bert_base_cased.ipynb     # Fine-tuned BERT-base-cased for classification  
 ┃ ┣ 📜 cleaned_PS_train.csv      # Preprocessed training dataset  
 ┃ ┣ 📜 cleaned_PS_dev.csv        # Preprocessed validation dataset  
 ┃ ┣ 📜 cleaned_PS_test.csv       # Preprocessed test dataset  
 ┃ ┣ 📜 fasttext.ipynb            # FastText-based classification  
 ┃ ┣ 📜 indic_bert.ipynb          # IndicBERT fine-tuning  
 ┃ ┣ 📜 indic_bert_nohashtag.ipynb # IndicBERT without hashtags  
 ┃ ┣ 📜 muril_nohashtag.ipynb     # MuRIL without hashtags  
 ┃ ┣ 📜 preprocess.ipynb          # Data preprocessing pipeline  
 ┃ ┣ 📜 PS_train.csv              # Original training dataset  
 ┃ ┣ 📜 PS_dev.csv                # Original validation dataset  
 ┃ ┣ 📜 PS_test_without_labels.csv # Test dataset without labels  
 ┃ ┣ 📜 submission.csv            # Final submission file  
 ┃ ┣ 📜 svm_sbert.ipynb           # SVM model using SBERT embeddings  
 ┃ ┣ 📜 tamil_sbert_nohashtag.ipynb # Tamil SBERT without hashtags  
```

## 🏆 Models Used  

- **LaBSE + SVM (Best Model)**
- **BERT-base-cased**  
- **IndicBERT**  
- **MuRIL**  
- **FastText**  
- **SBERT-based models**  
- **SVM-based models**  
- **XLM-Roberta**

All SVM-based models, are implemented in `svm.ipynb` where embeddings are first extracted and then a SVM classifier is trained. The other notebooks correspond to fine-tuned versions of their respective models for classification.

## 🛠️ Setup & Usage  

### 1️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 2️⃣ Run Preprocessing  
```python
# Open preprocess.ipynb and execute the preprocessing pipeline
```

### 3️⃣ Train Models  
Execute the respective notebooks (`.ipynb`) for training different models.


## 📝 Notes  
- LaBSE+SVM performed the best among all models.  
- Other SVM models are located in `svm.ipynb`.  
- Different models were fine-tuned for classification based on their respective architectures.  
- Due to dataset scarcity SVM based methods performed better

## 📧 Contact  
For any queries, feel free to reach out.

- [@nithishariyha](https://github.com/ariyha)  
- [@eshwanthkarti](github.com/eshwanthkartitr)  
- [@vikash](https://github.com/vikash22092004)
- [@yeshwanthbalaji](https://github.com/YeshwanthBalaji2022)


---

