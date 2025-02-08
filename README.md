# Apple Stock Price Prediction with LSTM and Optuna Optimization

 
## 概述
使用LSTM神经网络和Optuna超参数优化进行苹果股票价格预测。通过动态时间窗口（10-60天）和多种技术指标（MA5/MA20/RSI），实现验证集MSE降低27%，年化收益达18.7%（对标标普500指数9.5%）<br>

## 主要功能
### 📈 从Yahoo Finance获取2010-2023年苹果股票数据
### 🔧 特征工程：添加MA5/MA20移动平均线和RSI技术指标
### 🧠 动态LSTM架构：支持1-3层可配置LSTM网络
### ⚙️ Optuna自动化超参数优化：
1. 时间窗口自适应（10-60天）
2. 单元数（64/128/256）
3. Dropout率（0.1-0.5）
4. 学习率（1e-5 - 1e-2）
### 📊 交互式可视化：使用Plotly生成动态价格预测图
### 📉 性能指标：MSE/RMSE/MAE + 年化收益率计算<br>

## 使用
`git clone https://github.com/HKJoker-Z/apple-stock-prediction.git](https://github.com/HKJoker-Z/Apple-Stock-Price-Prediction-with-LSTM-and-Optuna-Optimization`  
`cd Apple-Stock-Price-Prediction-with-LSTM-and-Optuna-Optimization`  


## 结果
### 性能指标

| Metric      | Value |
| ----------- | ----------- |
| MSE      | 2.34       |
| RMSE     | 1.53       |
| MAE      | 1.12       |
| Annual Return	     | 18.7%      |

<br>
<br>
<br>
<br>
<br>
<br>





## Overview
LSTM-based stock price prediction system with Optuna hyperparameter optimization. 
Achieves 27% MSE reduction on validation set and 18.7% annualized return (vs S&P 500 9.5%) through dynamic time window (10-60 days) and technical indicators.<br>

## Features
### 📈 Historical data from Yahoo Finance (2010-2023)
### 🔧 Feature engineering with MA5/MA20/RSI indicators
### 🧠 Dynamic LSTM architecture (1-3 configurable layers)
### ⚙️ Optuna hyperparameter optimization:
1. Adaptive time window (10-60 days)
2. Units per layer (64/128/256)
3. Dropout rate (0.1-0.5)
4. Learning rate (1e-5 - 1e-2)
### 📊 Interactive visualization with Plotly
### 📉 Performance metrics: MSE/RMSE/MAE + Annualized Return<br>

## Usage
`git clone https://github.com/HKJoker-Z/apple-stock-prediction.git](https://github.com/HKJoker-Z/Apple-Stock-Price-Prediction-with-LSTM-and-Optuna-Optimization`  
`cd Apple-Stock-Price-Prediction-with-LSTM-and-Optuna-Optimization`  


## Results
### Performance Metrics
| Metric      | Value |
| ----------- | ----------- |
| MSE      | 2.34       |
| RMSE     | 1.53       |
| MAE      | 1.12       |
| Annual Return	     | 18.7%      |
