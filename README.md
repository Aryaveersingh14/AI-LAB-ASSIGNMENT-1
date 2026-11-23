# 🛡️ Cybersecurity Message Classification and Risk Detection System

## 📌 Project Overview

The **Cybersecurity Message Classification and Risk Detection System** is a Python-based project designed to identify and classify potentially harmful messages using keyword-based detection techniques.

The system analyzes message content and categorizes messages into four different classes: **Safe, Phishing, Malware, and Ransomware**. It also calculates keyword scores, determines risk levels, and recommends appropriate security actions.

This project demonstrates how basic data analysis and rule-based classification can help identify suspicious messages and improve cybersecurity awareness.

## 🎯 Objectives

- Identify potentially malicious messages.
- Detect phishing, malware, and ransomware-related keywords.
- Classify messages into predefined security categories.
- Calculate keyword scores for each message.
- Assign risk levels based on classification results.
- Generate recommended actions for suspicious messages.
- Visualize message classification results.

## ✨ Key Features

- **Message Classification:** Classifies messages into Safe, Phishing, Malware, and Ransomware.
- **Keyword Detection:** Identifies suspicious words and phrases in message content.
- **Keyword Scoring:** Calculates the number of matched keywords.
- **Risk Assessment:** Assigns Low, Medium, or High risk levels.
- **Security Recommendations:** Provides recommended actions based on detected risks.
- **Accuracy Evaluation:** Compares predicted categories with actual categories.
- **Data Visualization:** Generates a bar chart showing predicted message categories.
- **CSV Export:** Saves the final classification results into a CSV file.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data processing and analysis |
| Matplotlib | Data visualization |
| Scikit-learn | Accuracy evaluation |
| Jupyter Notebook | Development environment |

## 📂 Project Structure

```text
Cybersecurity-Message-Classification/
│
├── Untitled3(1).ipynb
├── simple_cyber_messages.csv
├── Lab1_Final_Result.csv
└── README.md
```

## ⚙️ How It Works

1. **Dataset Loading:** Loads cybersecurity messages from a CSV dataset.
2. **Keyword Identification:** Searches messages for predefined suspicious keywords.
3. **Message Classification:** Identifies the category with the highest keyword score.
4. **Prediction Evaluation:** Compares predicted categories with actual categories.
5. **Risk Assessment:** Assigns risk levels based on the predicted category and keyword score.
6. **Visualization:** Displays a bar chart of predicted message categories.
7. **Result Export:** Saves the final results in `Lab1_Final_Result.csv`.

## 📊 Classification Categories

| Category | Description |
|---|---|
| Safe | No predefined suspicious keywords detected |
| Phishing | Detects suspicious login, password, OTP, or verification-related terms |
| Malware | Detects virus, trojan, spyware, or executable-related terms |
| Ransomware | Detects encryption, ransom, bitcoin, or file-restoration-related terms |

## 🚨 Risk Assessment

The system assigns three risk levels:

| Risk Level | Condition | Recommended Action |
|---|---|---|
| Low | Safe message | Continue normal caution. |
| Medium | Suspicious category with fewer than two matched keywords, excluding ransomware | Do not interact; verify the sender and report. |
| High | Ransomware or two or more matched keywords | Do not click/open; isolate if required and report. |

## 📈 Output

The system generates:
- Predicted message category.
- Matched suspicious keywords.
- Keyword score.
- Correct or incorrect prediction status.
- Risk level.
- Recommended security action.
- Classification accuracy.
- Bar chart of predicted message categories.

**Output File:** `Lab1_Final_Result.csv`

## 💻 Installation and Execution

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd Cybersecurity-Message-Classification
```

### 3. Install Required Libraries

```bash
pip install pandas matplotlib scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebook

Open `Untitled3(1).ipynb` and execute the cells sequentially.

**Note:** Keep `simple_cyber_messages.csv` in the same directory as the notebook.

## 🔐 Responsible Use

- **Privacy:** Remove personal identifiers before analyzing messages.
- **Bias:** Keyword lists may not cover every writing style.
- **False Alarms:** Safe messages may contain suspicious keywords.
- **Accountability:** Humans remain responsible for security decisions.
- **Human Review:** High-risk or unclear messages must be checked.

## ⚠️ Limitations

- Uses predefined keywords rather than machine-learning-based classification.
- May generate false positives and false negatives.
- Cannot guarantee detection of all malicious messages.
- Classification depends on the quality of the keyword lists and dataset.

## 🚀 Future Improvements

- Integrate machine learning algorithms.
- Develop a real-time message detection system.
- Create a web-based cybersecurity dashboard.
- Improve keyword detection using Natural Language Processing (NLP).
- Add email and SMS threat detection.

## 👨‍💻 Author

**Aryaveer Singh**

## 📄 License

This project is intended for educational and learning purposes.
