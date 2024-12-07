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
git clone https://github.com/YOGESHWAR-PRABHU/P3-Spam-Email-Classification-Using-NLP-And-Machine-Learning.git
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
jupyter notebook "Spam Email Detector.ipynb"
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
![Screenshot 2024-12-07 194522](https://github.com/user-attachments/assets/e84695fa-60df-41bd-b544-5afaf682299e)
![Screenshot 2024-12-07 194544](https://github.com/user-attachments/assets/eb9a0d6b-1249-4ea5-b0e3-2310ad1f2362)
![Screenshot 2024-12-07 194557](https://github.com/user-attachments/assets/65370a7b-df73-41d2-8bb8-9d6d11ad09fe)
![Screenshot 2024-12-07 194657](https://github.com/user-attachments/assets/1dce6859-f322-4c6b-b8d6-a1874d5a3f36)
![Screenshot 2024-12-07 194919](https://github.com/user-attachments/assets/5065f1ac-0efb-4788-a936-50b7533f4a17)
![Screenshot 2024-12-07 194933](https://github.com/user-attachments/assets/ae39cc7c-cca4-4426-bb89-682560c168ad)
![Screenshot 2024-12-07 195021](https://github.com/user-attachments/assets/5ee7a0e6-a1f1-434f-8d2a-410c9483ede7)
![Screenshot 2024-12-07 195033](https://github.com/user-attachments/assets/0fbf3561-e5c3-4ea8-b305-d0264c835dc4)

---
