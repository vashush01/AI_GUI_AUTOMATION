# 🧹 Dynamic Data Cleaning Automation using Python GUI

A Python-based GUI application that automates common Excel data cleaning tasks. The application allows users to browse an Excel file, select the desired cleaning operations through a simple graphical interface, and generate a cleaned Excel file with just one click.

---

## 🚀 Features

- 📂 Browse and select Excel (.xlsx) files
- 🗑️ Remove duplicate rows
- ❌ Remove blank rows
- ✂️ Remove leading and trailing spaces from text columns
- 🔠 Convert text columns to Title Case
- 💾 Save the cleaned file automatically in the selected output folder
- 🖥️ Simple and user-friendly Tkinter GUI

---

## 🛠️ Technologies Used

- Python
- Tkinter
- Pandas
- OpenPyXL

---

## 📁 Project Structure

```
Dynamic-Data-Cleaning-Automation/
│
├── GUI.py
├── requirements.txt
├── README.md
├── Raw_Data/
├── Clean_File/
└── Screenshots/
```

---

# ▶️ How to Run

### Step 1

Clone this repository

```bash
git clone https://github.com/yourusername/Dynamic-Data-Cleaning-Automation.git
```

### Step 2

Install the required libraries

```bash
pip install pandas openpyxl
```

### Step 3

Run the application

```bash
python GUI.py
```

---

# 📖 How It Works

### 1️⃣ Run the Program

Launch the Python file.

A popup window for the **Dynamic Data Cleaning Automation** application will appear.

---

### 2️⃣ Select Input Excel File

Click the **Browse** button under **Input Excel File** and select your raw Excel dataset.

> Example:

- raw_sales_data.xlsx

---

### 3️⃣ Choose Cleaning Options

Select one or more data cleaning operations:

- ✅ Remove duplicate rows
- ✅ Remove blank rows
- ✅ Remove leading & trailing spaces
- ✅ Convert text columns to Title Case

---

### 4️⃣ Select Output Folder

Click **Browse** under **Output Folder** and choose where you want to save the cleaned file.

---

### 5️⃣ Clean the Data

Click the **Clean Data** button.

The application processes the file automatically.

---

### 6️⃣ Output Generated

A success message will appear showing the location of the cleaned Excel file.

The cleaned file is saved inside the selected output folder.

---

# 📸 Project Screenshots

## Raw Dataset

<img width="1917" height="897" alt="image" src="https://github.com/user-attachments/assets/8d084630-d9ce-4c1e-b563-9d3d3267ac47" />


---

## GUI Interface

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/71d048bc-0d57-4512-9db8-3d2f304c97aa" />


---

## Selecting Cleaning Options

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/299e8bda-20f8-4b5c-9140-694219a53344" />


---

## Success Message

<img width="516" height="215" alt="image" src="https://github.com/user-attachments/assets/20879e95-6434-44a8-9cb9-b6c6cebf1f20" />


---

## Cleaned Output File
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/cdd81112-154e-4b79-adce-fa4c30749a0f" />


---

# ✅ Example Cleaning Performed

Before Cleaning

```
Customer Name :  "  karan yadav "
City          :  "CHENNAI"
Duplicate Rows : Present
Blank Rows     : Present
```

After Cleaning

```
Customer Name : "Karan Yadav"
City          : "Chennai"
Duplicate Rows : Removed
Blank Rows     : Removed
```

---

# 🎯 Future Improvements

- Drag & Drop Excel file support
- Progress Bar
- Dark Theme
- CSV File Support
- Data Validation Report
- Export Cleaning Log
- Column Selection Feature

---

# 👨‍💻 Author

**Vashu Sharma**

Aspiring Data Analyst | Python Developer | SQL | Excel | Power BI

GitHub: https://github.com/vashush01

LinkedIn: https://www.linkedin.com/in/vashu-sharma01/

---

## ⭐ If you found this project useful, don't forget to give it a Star!
