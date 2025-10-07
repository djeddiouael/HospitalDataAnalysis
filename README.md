# 🏥 Hospital Data Analysis

This project aims to analyze patient data using **Python** and data science tools.  
It demonstrates data loading, cleaning, visualization, and simple statistical exploration.

---

## 📁 Project Structure

HospitalDataAnalysis/
│
├── data/ # CSV datasets (e.g., patients.csv)
├── notebooks/ # Jupyter notebooks for exploration
├── scripts/ # Python scripts for data analysis
├── env/ # Conda virtual environment (ignored by Git)
├── .gitignore # Files and folders to exclude from Git
└── README.md # Project documentation

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/djeddiouael/HospitalDataAnalysis.git
cd HospitalDataAnalysis
```

### 2. Create and activate the Conda environment

If you have the exported environment file (`environment.yml`):

```bash
conda env create -f environment.yml
conda activate ds_env
```

Otherwise, install dependencies manually:

```bash
conda create --name ds_env python=3.11
conda activate ds_env
conda install pandas numpy matplotlib scikit-learn jupyter
```

---

## 📊 How to Run the Project

### Option 1 — Using Jupyter Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `notebooks/patients_analysis.ipynb`.

Run all cells to see the results.

### Option 2 — Using Python Scripts

Run your analysis script directly:

```bash
python scripts/patients_analysis.py
```

---

## 📈 Example Analysis

- Load patient data using Pandas
- Explore descriptive statistics (`df.describe()`)
- Analyze categorical distributions (e.g., Sex, Diagnosis)
- Visualize trends using Matplotlib (e.g., Cholesterol vs Age)

---

## 📦 Export Environment (for sharing)

To let others recreate the same environment:

```bash
conda env export > environment.yml
```

To recreate on another computer:

```bash
conda env create -f environment.yml
```

---

## 👨‍💻 Author

**Ouâel Djeddi**  
🎓 Master’s Student in Applied Artificial Intelligence, University of Boumerdes

---

## 📄 License

This project is open source and available under the MIT License.
