# TimeSync AI Research

Machine Learning research for **Smart Timesheet Pre-fill** feature in OrasSync 2.0

## 🎯 Objective
Build a Random Forest model that predicts daily timesheet activities based on historical patterns, achieving 80%+ accuracy.

## 📊 Research Notebooks

1. **01_data_exploration.ipynb** - Analyze timesheet patterns and identify recurring activities
2. **02_feature_engineering.ipynb** - Extract ML features (frequency, consistency, trends)
3. **03_model_training.ipynb** - Train Random Forest classifier
4. **04_model_evaluation.ipynb** - Evaluate prediction accuracy

## 🛠️ Setup
```bash
# Install dependencies
pip install -r requirements-ml.txt

# Start Jupyter
jupyter notebook
```

## 📁 Project Structure
```
timesync-ai-research/
├── notebooks/              # ML research notebooks
│   ├── 01_data_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_model_evaluation.ipynb
├── data/                   # Sample and exported data
├── models/                 # Saved trained models
├── src/                    # Reusable Python modules
│   ├── feature_engineering.py
│   └── timesheet_predictor.py
├── results/                # Experiment results
└── archive-old-prophet-work/  # Previous research (archived)
```

## 🧠 ML Approach

**Model:** Random Forest Classifier

**Features:**
- Day of week
- Hour of day  
- Activity frequency
- Duration consistency
- Recent trend
- Month-end indicator

**Target:** Binary classification (should activity appear today?)

## 📈 Success Metrics
- **Accuracy:** 80%+ prediction accuracy
- **Time Savings:** 15 min → 30 sec per timesheet

## 👥 Team
- **AI Team Lead:** Audrey
- **Project:** OrasSync 2.0
- **Organization:** Lyceum of the Philippines University

## 📅 Current Phase
**Phase 1:** Data exploration and pattern analysis (Week 1)
```

**Save the file!** ✅

---

### **Step 3: Update .gitignore**

Open `.gitignore` and **replace everything** with:
```
# Jupyter
.ipynb_checkpoints/
*/.ipynb_checkpoints/*

# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python

# Virtual environments
venv/
env/
ENV/

# Models (large files)
models/*.pkl
*.h5

# Data (sensitive)
data/*.csv
data/*.json
!data/sample_*.csv

# OS
.DS_Store
Thumbs.db
