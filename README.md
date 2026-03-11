# Car-Price-Predictor
This model will help in predicting Car Price based on some data through user.

# 🚗 Car Price Predictor

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.31.0-red)](https://streamlit.io/)
[![XGBoost](https://img.shields.io/badge/XGBoost-2.0.3-orange)](https://xgboost.ai/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/car-price-predictor/blob/main/quiker_predictor.ipynb)

An intelligent machine learning web application that predicts the market value of used cars based on their specifications. Built with Python and deployed using Streamlit.

![Car Price Predictor Demo](https://via.placeholder.com/800x400.png?text=Car+Price+Predictor+Demo)

## 📋 Table of Contents
- [✨ Features](#-features)
- [🎯 Use Cases](#-use-cases)
- [🛠️ Technology Stack](#️-technology-stack)
- [📊 Dataset](#-dataset)
- [🚀 Quick Start](#-quick-start)
- [📁 Project Structure](#-project-structure)
- [🔧 Installation](#-installation)
- [💻 Usage](#-usage)
- [🤖 Model Training](#-model-training)
- [📈 Model Performance](#-model-performance)
- [🎨 Demo](#-demo)
- [🔮 Future Enhancements](#-future-enhancements)
- [🤝 Contributing](#-contributing)
- [📝 License](#-license)
- [📧 Contact](#-contact)

## ✨ Features

✅ **Interactive Web Interface** - User-friendly Streamlit application with modern UI/UX  
✅ **Real-time Predictions** - Instant price estimates based on user inputs  
✅ **Comprehensive Dataset** - Trained on 900+ real used car listings from the Indian market  
✅ **Accurate Model** - XGBoost regression with 92% R² score  
✅ **Data Visualization** - Interactive charts and graphs for data analysis  
✅ **Similar Cars Comparison** - Compare with similar cars from the database  
✅ **Confidence Intervals** - Price predictions with 10% margin of error  
✅ **Mobile Responsive** - Works seamlessly on all devices  

## 🎯 Use Cases

- **Car Buyers**: Get fair market value before purchasing
- **Car Sellers**: Price your car competitively
- **Dealerships**: Quick valuation for trade-ins
- **Insurance Companies**: Estimate vehicle values
- **Financial Institutions**: Assess loan amounts

## 🛠️ Technology Stack

### Core Technologies
| Technology | Version | Purpose |
|------------|---------|---------|
| Python | 3.8+ | Core programming language |
| Streamlit | 1.31.0 | Web application framework |
| XGBoost | 2.0.3 | Machine learning model |
| Scikit-learn | 1.3.2 | Data preprocessing & metrics |
| Pandas | 2.1.4 | Data manipulation |
| NumPy | 1.24.3 | Numerical computations |
| Plotly | 5.18.0 | Interactive visualizations |
| Matplotlib | 3.8.2 | Static visualizations |
| Seaborn | 0.13.0 | Statistical visualizations |

### Development Tools
- **Jupyter Notebook** - Model development & experimentation
- **Git** - Version control
- **VS Code** - Code editor
- **Pickle** - Model serialization

## 📊 Dataset

The model is trained on real used car data scraped from [quikr.com](https://www.quikr.com), one of India's largest classifieds platforms.

### Dataset Features
| Feature | Description | Data Type |
|---------|-------------|-----------|
| `name` | Car model name (first 3 words) | Categorical |
| `company` | Manufacturing company | Categorical |
| `year` | Year of purchase/manufacture | Numerical |
| `kms_driven` | Total kilometers driven | Numerical |
| `fuel_type` | Type of fuel (Petrol/Diesel/LPG) | Categorical |
| `Price` | Target variable - car price (in ₹) | Numerical |

### Dataset Statistics
- **Total Records**: 900+ car listings
- **Unique Car Models**: 200+
- **Companies**: 20+ manufacturers
- **Price Range**: ₹30,000 - ₹31,00,000
- **Year Range**: 1995 - 2020

## 🚀 Quick Start

### One-Click Setup (Recommended)
```bash
# Clone the repository
git clone https://github.com/yourusername/car-price-predictor.git
cd car-price-predictor

# Run the automated setup script
python run_all.py
