# Student Placement Analysis 🎓

A machine learning project predicting student job placement outcomes based on academic performance, internship experience, and salary expectations.

## 📊 Dataset Features
- **CGPA**: Student's academic grade point average
- **Internships**: Number of internships completed
- **Salary (INR LPA)**: Expected salary in lakhs per annum
- **Placed**: Job placement outcome (Yes/No)

## 🚀 Key Results
- **100% Accuracy** achieved with both Logistic Regression and Random Forest models
- Perfect cross-validation performance across all folds
- Strong statistical significance for all predictive features

## 🛠️ Technologies Used
- **Python**: pandas, numpy, matplotlib, seaborn, scipy, scikit-learn
- **Models**: Logistic Regression, Random Forest Classifier
- **Analysis**: Statistical testing, correlation analysis, outlier detection

## 📈 Methodology
1. **Data Preprocessing**: Missing value imputation, outlier removal using IQR
2. **Feature Engineering**: Created categorical grades for CGPA and salary levels
3. **Statistical Analysis**: Shapiro-Wilk tests, Mann-Whitney U tests, Spearman correlation
4. **Model Training**: 70/30 split with 5-fold stratified cross-validation

## 🏃‍♂️ Quick Start
```bash
git clone https://github.com/yourusername/student-placement-analysis
cd student-placement-analysis
pip install -r requirements.txt
python Student_Placement.py
```

## 📄 Files
- `Student_Placement.ip` - Main analysis script
- `Placement.csv` - Dataset

Perfect for understanding ML classification and statistical analysis! 🎯
