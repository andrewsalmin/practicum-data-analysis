# 📊 Проекты по анализу данных Яндекс Практикум

[![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)](https://www.python.org/)

[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](https://jupyter.org/)

## 📘 О репозитории
Данный репозиторий содержит учебные проекты, выполненные в рамках курса **«Инструменты анализа данных»** на платформе **Яндекс Практикум**.
В проектах использованы библиотеки Python для анализа данных — `pandas`, `matplotlib`, `seaborn`, `sklearn`.

## 📂 Содержание
| № | Название проекта | Краткое описание |
|:-:|:-----------------|:-----------------|
| 1 | 🏙️ [Исследование продаж квартир в Санкт‑Петербурге и окрестностях](#1.-Исследование-продаж-квартир-в-Санкт‑Петербурге-и-окрестностях) | Выявление факторов, влияющих на стоимость недвижимости |
| 2 | 🎮 [Исследование продаж компьютерных игр](#2.-Исследование-продаж-компьютерных-игр) | Определение закономерностей, влияющих на успешность платформ и жанров |
| 3 | ⛏️ [Прогнозирование коэффициента восстановления золота из руды](#3.-Прогнозирование-коэффициента-восстановления-золота-из-руды) | Оценка эффективности очистки золотосодержащей руды |

## 🌐 Онлайн‑просмотр
### 1. Исследование продаж квартир в Санкт‑Петербурге и окрестностях

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.jupyter.org/github/andrewsalmin/practicum-data-analysis/blob/main/saint-petersburg-real-estate.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/practicum-data-analysis/HEAD?urlpath=lab/tree/saint-petersburg-real-estate.ipynb)

### 2. Исследование продаж компьютерных игр

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.jupyter.org/github/andrewsalmin/practicum-data-analysis/blob/main/computer-games-sales.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/practicum-data-analysis/HEAD?urlpath=lab/tree/computer-games-sales.ipynb)

### 3. Прогнозирование коэффициента восстановления золота из руды

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.jupyter.org/github/andrewsalmin/practicum-data-analysis/blob/main/gold-recovery.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/practicum-data-analysis/HEAD?urlpath=lab/tree/gold-recovery.ipynb)

## ⚙️ Как запустить локально
```bash
    # Клонировать репозиторий:
    git clone https://github.com/andrewsalmin/practicum-data-analysis.git
    
    # Перейти в папку проекта:
    cd practicum-data-analysis
    
    # Создать виртуальное окружение (один раз):
    python -m venv venv
    
    # Активировать окружение:
    # Linux / macOS:
    source venv/bin/activate
    # Windows (PowerShell / CMD):
    venv\Scripts\activate
    
    # Установить зависимости в это окружение (один раз):
    pip install -r requirements.txt
    
    # Запустить Jupyter
    jupyter notebook
```