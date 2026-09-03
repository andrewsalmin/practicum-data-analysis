# 📊 Проекты курса "Инструменты анализа данных" Яндекс Практикум

[![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)](https://www.python.org/)

[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](https://jupyter.org/)

## 📘 О репозитории

Данный репозиторий содержит учебные проекты, выполненные в рамках курса **«Инструменты анализа данных»** на платформе **Яндекс Практикум**.

## 📂 Содержание

|  №  | Название проекта                                                       | Краткое описание                                                      |
| :-: | :--------------------------------------------------------------------- | :-------------------------------------------------------------------- |
|  1  | 🏙️ [Исследование продаж квартир в Санкт‑Петербурге и окрестностях](#1) | Выявление факторов, влияющих на стоимость недвижимости                |
|  2  | 🎮 [Исследование продаж компьютерных игр](#2)                          | Определение закономерностей, влияющих на успешность платформ и жанров |
|  3  | ⛏️ [Прогнозирование коэффициента восстановления золота из руды](#3)    | Оценка эффективности очистки золотосодержащей руды                    |
|  4  | 🎤 [Исследование TED-конференций](#4)                                  | Рейтинги тем, стран, распределение по годам                           |

💡 Подробные выводы и промежуточные результаты приведены в Jupyter ноутбуках (.ipynb), а также на странице проекта Tableau. Проект 4 (TED-конференции) выполнен в Tableau и не содержит Jupyter-ноутбука — только исходные данные и дашборд.

## 🌐 Онлайн‑просмотр

### <a id=1></a> 1. Исследование продаж квартир в Санкт‑Петербурге и окрестностях

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.org/github/andrewsalmin/practicum-data-analysis/blob/main/notebooks/saint-petersburg-real-estate.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/practicum-data-analysis/HEAD?labpath=notebooks/saint-petersburg-real-estate.ipynb)

### <a id=2></a> 2. Исследование продаж компьютерных игр

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.org/github/andrewsalmin/practicum-data-analysis/blob/main/notebooks/computer-games-sales.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/practicum-data-analysis/HEAD?labpath=notebooks/computer-games-sales.ipynb)

### <a id=3></a> 3. Прогнозирование коэффициента восстановления золота из руды

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.org/github/andrewsalmin/practicum-data-analysis/blob/main/notebooks/gold-recovery.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/practicum-data-analysis/HEAD?labpath=notebooks/gold-recovery.ipynb)

### <a id=4></a> 4. Исследование TED-конференций

- [Данные конференций в формате CSV](data/tableau/)
- [Дашборд в Tableau](https://public.tableau.com/app/profile/andrew.salmin/viz/TED-_17301758690640/TED)

Скриншоты дашборда:

- [История конференций](screenshots/tableau/history.png)
- [Тематики выступлений](screenshots/tableau/themes.png)

## 📁 Структура проекта

```bash
    .
    |
    ├── notebooks/
    |   ├── saint-petersburg-real-estate.ipynb
    |   ├── computer-games-sales.ipynb
    |   └── gold-recovery.ipynb
    |
    ├── data/
    |   │
    |   └── tableau/
    |       ├── tableau_project_data_1.csv
    |       ├── tableau_project_data_2.csv
    |       ├── tableau_project_data_3.csv
    |       ├── tableau_project_event_dict.csv
    |       └── tableau_project_speakers_dict.csv
    |
    ├── screenshots/
    |   │
    |   └── tableau/
    |       ├── history.png
    |       └── themes.png
    |
    ├── requirements.txt
    ├── README.md
    └── LICENSE
```

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

    # Запустить Jupyter:
    jupyter notebook notebooks
```

## 🧹 Для контрибьюторов

Вывод ячеек (графики, таблицы) в ноутбуках сохраняется в git осознанно —
чтобы проекты можно было просматривать в nbviewer и на GitHub без запуска кода.
Для новых коммитов, где нужно почистить вывод, можно подключить
[nbstripout](https://github.com/kynan/nbstripout) (правило уже задано в
`.gitattributes`):

```bash
    pip install nbstripout
    nbstripout --install
```

## 📜 Лицензия

Этот проект распространяется по лицензии [MIT](https://opensource.org/licenses/MIT).
