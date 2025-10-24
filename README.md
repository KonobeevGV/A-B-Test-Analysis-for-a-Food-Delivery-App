# Анализ A/B/n тестов для приложения доставки еды

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![Statsmodels](https://img.shields.io/badge/Statsmodels-0.13%2B-green)
![Pingouin](https://img.shields.io/badge/Pingouin-0.5%2B-purple)

## 📊 О проекте

Статистический анализ двух A/B тестов для приложения доставки готовых продуктов:
- **Тест 1**: Сравнение форматов фотографий блюд (3 группы)
- **Тест 2**: Оценка нового дизайна кнопки заказа с учетом сегментации пользователей

## 🎯 Результаты

### 📷 Тест с фотографиями
- **Лучший формат**: Квадратные фотографии (Группа B)
- **Увеличение заказов**: +27% vs худший формат
- **Метод**: One-way ANOVA + критерий Тьюки

### 🔘 Тест с кнопкой  
- **Решение**: Выкатываем новую версию
- **Прирост заказов**: +65% в low-сегменте, +17% в high-сегменте
- **Метод**: Two-way ANOVA + попарные сравнения

## 📁 Структура проекта

| Директория/Файл | Описание |
|----------------|----------|
| `data/photo_test.csv` | Данные A/B/n теста с форматами фотографий |
| `data/button_test.csv` | Данные A/B теста с дизайном кнопки |
| `notebooks/ab_test_analysis.ipynb` | Jupyter notebook с полным анализом |
| `README.md` | Документация проекта |
| `requirements.txt` | Список зависимостей Python |


## 🚀 Быстрый старт

1. Клонируйте репозиторий:
```bash
git clone https://github.com/KonobeevGV/***Anomaly-Analysis-in-London-Bike-Rental-Data***
```
Установите зависимости:
```bash
pip install -r requirements.txt
```
