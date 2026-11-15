# Spam and Scam Message Checker
Checks an SMS/WhatsApp message and says if it looks like spam or a scam, with highlighted words and warning signs.

## How to run
1. Open https://colab.research.google.com and choose File > Upload notebook.
2. Upload Spam_Message_Checker.ipynb.
3. Click Runtime > Run all.
4. In Section 5, edit the message box and run the cell to check your own message.

## Tech
Python, scikit-learn (TF-IDF + Logistic Regression), pandas, matplotlib, Google Colab.

## Results
155 labelled messages. 95% accuracy on a 39-message held-out test set; cross-validated macro F1 0.93.
The dataset is small, so real-world accuracy will be lower.
