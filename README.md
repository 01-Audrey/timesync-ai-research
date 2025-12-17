# TimeSync AI Research

ML experimentation repository for TimeSync's AI-powered attendance monitoring system.

## 🎯 Project Goal
Train LSTM neural networks to:
- Learn individual employee attendance patterns (80%+ accuracy)
- Detect anomalies in real-time
- Generate Audit Confidence Scores (0-100%) for timesheets
- Predict task durations based on historical performance

## 🗓️ Timeline
**Month 1:** LSTM pattern learning + anomaly detection  
**Month 2:** Audit confidence scoring algorithm  
**Month 3:** Task estimation + production integration

## 📊 Current Phase
**Week 1-2:** Data preparation and initial exploration

## 🔧 Tech Stack
- **Framework:** TensorFlow/Keras
- **Data:** Pandas, NumPy
- **Forecasting:** Prophet
- **Production:** FastAPI (integration phase)
- **Database:** PostgreSQL (production)

## 📂 Repository Structure
- `data/` - Training datasets (Kaggle + synthetic)
- `notebooks/` - Jupyter experiments and analysis
- `models/` - Trained models and checkpoints
- `src/` - Production-ready Python modules
- `docs/` - Technical documentation and schemas

## 🚀 Getting Started
```bash
# Clone repo
git clone [your-repo-url]
cd timesync-ai-research

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## 📈 Progress Tracking
See `docs/weekly_progress.md` for detailed sprint updates.

## 👥 Team
**AI Lead:** Audrey  
**AI Support:** Gab (integration phase)

---
*This is a research repository. Production code will be merged to `se-backend-temp/ai` after validation.*
