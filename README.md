# Extracting x, y, Symbols, and Output from a Document

This guide walks you through extracting `x`, `y`, `symbols`, and the final `output` from a document using Python.

---

## 📄 Prerequisites

- Python version **3.6 or higher** must be installed.
- Access to the Google Document: [Click here](https://docs.google.com/document/d/1ZLAi03Onqt5mHFjeLvMHaGf7trZNm0y07WzVRncaZAU/edit?tab=t.0)

---

## 🛠 Steps

### 1️⃣ Step 1 (Optional): Clean the Document
- Open the linked document.
- Remove all unnecessary text.
- **Keep only the table** that you want to work on.

### 2️⃣ Step 2 (Optional): Save as Text File
- Download the cleaned version of the document as `text.txt`.

### 3️⃣ Step 3: Ensure Python is Installed
Run the following command to check your Python version:

```bash
python --version
### 4️⃣ Step 4: Choose the Correct Python Script
- Use the appropriate script based on how you've handled the document:
  - If you cleaned the document and saved it as `text.txt`, use: **`AI2030Code.py`**
  - If you're using the original document without changes, use: **`FinalCode.py`**

### 5️⃣ Step 5: Set File Path (Only for `AI2030Code.py`)
- If using `AI2030Code.py`, update the script with the correct file path to your `text.txt` file:

### 6️⃣ Step 6: Run the Script
- Open a terminal or command prompt.
- Navigate to the directory where your Python script is located.
- Run the script with one of the following commands:

```bash
python AI2030Code.py
# or
python FinalCode.py
