# Laptop Prices Predictions

A machine learning project designed to predict laptop prices based on various hardware specifications and features.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This project develops predictive models to estimate laptop prices using machine learning algorithms. It analyzes various laptop specifications such as processor type, RAM, storage, display size, and other hardware components to accurately forecast market prices.

## ✨ Features

- **Multiple ML Models**: Implementation of various regression algorithms for price prediction
- **Feature Engineering**: Comprehensive data preprocessing and feature extraction
- **Data Visualization**: Interactive plots and insights into laptop price trends
- **Model Evaluation**: Detailed performance metrics and comparisons
- **Easy-to-Use Interface**: Simple scripts for making predictions on new data

## 📊 Dataset

The project uses laptop specifications data including:
- **Processor**: CPU model and specifications
- **RAM**: Memory capacity (GB)
- **Storage**: SSD/HDD capacity and type
- **Display**: Screen size and resolution
- **GPU**: Graphics card information
- **Battery**: Battery capacity and life
- **Brand**: Manufacturer
- **Price**: Target variable (in USD or local currency)

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip or conda package manager

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Osamahfm/Laptop-Prices-Predictions.git
cd Laptop-Prices-Predictions
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 💻 Usage

### Training the Model

```bash
python train.py
```

### Making Predictions

```bash
python predict.py --processor "Intel i7" --ram 16 --storage 512 --display 15.6
```

### Exploring the Data

```bash
jupyter notebook notebooks/exploratory_analysis.ipynb
```

## 📈 Model Performance

Current model metrics (to be updated with actual results):

| Model | R² Score | RMSE | MAE |
|-------|----------|------|-----|
| Linear Regression | - | - | - |
| Random Forest | - | - | - |
| Gradient Boosting | - | - | - |
| Neural Network | - | - | - |

## 📁 Project Structure

```
Laptop-Prices-Predictions/
├── data/
│   ├── raw/                    # Original dataset
│   └── processed/              # Cleaned and processed data
├── notebooks/
│   └── exploratory_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── models.py
│   └── utils.py
├── train.py                    # Training script
├── predict.py                  # Prediction script
├── requirements.txt
├── README.md
└── LICENSE
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

**Happy predicting! 🚀**
