# ✈️ Airline Passenger Forecasting | Прогнозирование пассажиропотока авиалиний

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-lightgrey)](https://github.com/your-username/flights-analysis)

## 🌍 **Project Overview | Описание проекта**
**EN**: Time series analysis and 12-month forecast of airline passengers using Holt-Winters exponential smoothing.  
**RU**: Анализ временных рядов и прогнозирование пассажиропотока на 12 месяцев с помощью модели Холта-Винтерса.

## 📊 **Key Features | Особенности**
| **Feature**          | **Technical Details**                              |
|----------------------|---------------------------------------------------|
| **Модель**           | Triple Exponential Smoothing (Trend + Seasonality) |
| **Сезонность**       | Multiplicative (растущая амплитуда)               |
| **Данные**           | Ежемесячные (1949–1960)                           |
| **Визуализация**     | `matplotlib`                                      |

## 🛠 **Technologies | Технологии**
```python
import pandas as pd  # Анализ данных
from statsmodels.tsa.holtwinters import ExponentialSmoothing  # Модель
import matplotlib.pyplot as plt  # Графики
🚀 Quick Start | Быстрый старт
Клонировать репозиторий:

bash
git clone https://github.com/your-username/flights-analysis.git
Установить зависимости:

bash
pip install -r requirements.txt
Запустить анализ:

bash
jupyter notebook Flights_Analysis.ipynb
📈 Results | Результаты
Forecast Plot
Прогноз с учетом тренда и сезонности / Forecast with trend and seasonality

📚 Application | Применение
Оптимизация расписания рейсов

Анализ сезонного спроса

Планирование загрузки авиакомпаний
