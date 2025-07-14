
# 📄 README – CMT122 Resit Coursework 1 (Part 2)

## 👨‍💻 Author:
Mohammed Bokhari  
Module: CMT122 – Machine Learning for NLP  
Assessment: Resit Coursework 1 – Part 2 (Text Classification Project)

---

## 📁 Files Included
- `codebase.ipynb`: Final Google Colab notebook containing all code and output  
- `20_Newsgroups.csv`: Input dataset (must be uploaded before running)  

---

## 🚀 How to Run the Notebook
1. Open the notebook in **Google Colab**.  
2. Upload the file `20_Newsgroups.csv` using the upload cell or `Files` panel.  
3. Run all cells **in order from top to bottom**.  

---

## 📦 Dependencies
This project uses standard Python libraries:

```
pandas  
numpy  
scikit-learn  
scipy  
re
```

In Colab, these are pre-installed. If running locally, install them with:

```bash
pip install pandas numpy scikit-learn scipy
```

---

## 📊 Output
The final classification model outputs:
- **Accuracy**: `0.848`
- **Macro Precision**: `0.856`
- **Macro Recall**: `0.852`
- **Macro F1**: `0.853`

Performance meets the coursework requirement (> 65% accuracy).

---

## 📌 Notes
- The notebook includes full **preprocessing**, **feature extraction/engineering (5 features)**, **feature selection (dimensionality reduction)**, **model training**, and **model prediction** using `LogisticRegression`.  
- Warnings about convergence are addressed by increasing `max_iter` from `1000` to `3000`.
