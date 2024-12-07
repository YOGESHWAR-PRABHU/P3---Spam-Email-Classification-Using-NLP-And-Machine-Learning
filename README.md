# **Spam Email Classification with Machine Learning**

This project demonstrates an end-to-end implementation of a spam email classification system using **Natural Language Processing (NLP)** and **machine learning techniques**. The model is built using Python libraries such as `scikit-learn`, `pandas`, and `numpy`, and features a user-friendly GUI application created with `Tkinter`. The system helps classify emails as either **Spam** or **Not Spam**, offering an intuitive solution to secure inboxes.

---

## **Features**

- **Email Classification**: Detect and classify emails into two categories: Spam and Not Spam.  
- **Naive Bayes Model**: A lightweight and effective classification algorithm trained on a labeled dataset.  
- **Interactive GUI**: A simple interface for users to input email content and view classification results.  
- **Speech Output**: The system provides audible feedback using text-to-speech functionality.  
- **Model Persistence**: Save and load the trained model using `pickle` for reusability.

---

## **How It Works**

1. **Data Preprocessing**:
   - The dataset is loaded and cleaned by removing unnecessary columns.
   - Email messages are converted into numerical vectors using **CountVectorizer**.
   - Labels (`ham` and `spam`) are mapped to binary values (0 and 1).

2. **Model Training**:
   - A **Multinomial Naive Bayes classifier** is trained on the dataset.
   - The model is evaluated using metrics such as accuracy.

3. **GUI Interface**:
   - Built with `Tkinter`, the interface allows users to input email content.
   - The result is displayed on the screen and read aloud using text-to-speech.

---

## **Installation**

### **1. Clone the Repository**

```bash
https://github.com/YOGESHWAR-PRABHU/P3-Spam-Email-Classification-Using-NLP-And-Machine-Learning.git
cd P3-Spam-Email-Classification-Using-NLP-And-Machine-Learning

```

### **2. Install Required Libraries**

Ensure you have Python installed on your system. Install the required dependencies using:

```bash
pip install -r requirements.txt
```

### **3. Run the Jupyter Notebook**

To execute the code and train the model, open the Jupyter Notebook and run each cell sequentially:

```bash
jupyter notebook spam_email_classifier.ipynb
```

### **4. Launch the GUI Application**

After training the model, run the GUI code cell in the Jupyter Notebook to launch the interactive application.

---

## **Usage**

1. Enter an email message in the input field of the GUI.  
2. Click the **Classify** button to process the message.  
3. View the classification result, which is displayed on the screen and spoken aloud.  
4. Use the saved model (`spam_model.pkl`) for further predictions without retraining.

---

## **Dependencies**

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- tkinter  
- pywin32  

Install these libraries via `pip` if they are not already installed.

---

## **Sample Input and Output**

### Input:  
*"Congratulations! You've won $500. Click here to claim your prize."*

### Output:  
**This is a Spam Email.**

---

## **Screenshots**

### GUI Interface  
*(Add an image of your GUI application here once ready.)*

---
