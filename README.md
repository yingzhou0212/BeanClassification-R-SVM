
```markdown
# DSCC 201/401 Final Project – Bean Classification & Solar Radio Flux Prediction

This project contains two machine learning pipelines developed in R and Python as part of the final project for the DSCC 201/401 course at the University of Rochester.

```

Question1\_Ying\_Zhou.ipynb      # Bean classification using SVM (R via Jupyter)
Question1\_Ying\_Zhou.pdf
Question2-2.ipynb              # Solar flux prediction using linear regression (Python)
Question2-2.pdf
DSCC\_201\_401\_Spring\_2025\_Final\_Project.pdf   # Project instructions

```


Question 1: Bean Classification (R)

Goal: Classify 7 types of dry beans (e.g., Seker, Horoz, Dermason, etc.) using physical characteristics such as area, perimeter, and axis lengths.

- Used SVM (Support Vector Machine) with linear kernel from the `caret` package
- Included 5-fold repeated cross-validation
- Evaluated with a multi-class confusion matrix
- Predicted types for unlabeled beans in a separate dataset

Tools:  
- R 3.6.1  
- `caret`, `corrplot`, `dplyr`, `e1071`  


Question 2: Solar Radio Flux Prediction (Python)

Goal: Predict solar radio flux values based on sunspot numbers and solar flare counts.

- Cleaned and analyzed 10 years of solar observation data
- Created visualizations with `Seaborn`
- Trained a linear regression model to estimate radio flux
- Evaluated with standard regression accuracy metrics
- Included prediction for a new example input (96 sunspots + 1 C-class flare)

Tools:  
- Python 3 (Anaconda 2023)  
- `pandas`, `matplotlib`, `seaborn`, `scikit-learn`  

---

Notes

- All analyses were run on 'Bluehive' (University of Rochester's HPC environment)
- Each notebook includes all code, comments, and embedded answers
- Extra credit tasks (Keras-based neural networks) are not included in this version

---

Author

Ying Zhou
University of Rochester  
B.S. Computer Science & B.A. Psychology  
Spring 2025  
