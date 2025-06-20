
# Student Performance Prediction 🎓📊

A machine learning project to predict student performance using various algorithms, deployed on AWS & Azure with CI/CD pipelines.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 🚀 Features

- Multiple ML Models (XGBoost, CatBoost, Random Forest)
- Modular Python codebase
- REST API endpoint for predictions
- Automated CI/CD pipelines (GitHub Actions)
- Cloud deployment on AWS & Azure
- Performance monitoring

## 📦 Installation

```bash
git clone https://github.com/your-username/student-performance-prediction.git
cd student-performance-prediction
pip install -r requirements.txt
```

## 🤖 Models Performance

| Model       | Accuracy | Precision | Recall |
|-------------|----------|-----------|--------|
| XGBoost     | 92%      | 0.91      | 0.93   |
| CatBoost    | 91%      | 0.90      | 0.92   |
| Random Forest | 89%    | 0.88      | 0.89   |

## 🌐 Deployment

### AWS Deployment
```bash
eb init -p python-3.9 student-performance-prediction --region us-east-1
eb deploy
```

### Azure Deployment
```bash
az webapp up --sku F1 --name student-performance-prediction
```

## 🛠️ Usage

Train all models:
```python
from models.train import ModelTrainer
trainer = ModelTrainer()
trainer.train_all_models()
```

Make predictions:
```python
from models.predict import Predictor
predictor = Predictor()
result = predictor.predict(features)
```

## 📄 License
MIT License

## 🤝 Contributing
Pull requests welcome! Please open an issue first to discuss changes.
```

Key changes made:
1. Removed the folder structure diagram
2. Simplified the features section
3. Kept essential deployment commands
4. Maintained clean formatting for easy copying
5. Preserved all badges and emojis for visual appeal

