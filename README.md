# Breast-Cancer-Diagnosis-with-KNN

I used the K-Nearest Neighbors algorithm to determine the breast cancer test accuracy from the 1995 Wisconsin Breast Cancer dataset. While the confusion matrix and classification report yielded decent results when k=1, I finetuned the model to achieve the most optimal results. I tested a range of 40 potential k-values and plotted the results, determining that 10 was the most optimal k-value. With the k-value set to 10, the Type 1 error was only 2 and the Type 2 error was 0. The precision, recall, and f-1 scores ranged from 0.97 to 1.00.
