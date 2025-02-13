# OTUS. Построение End-to-End пайплайнов и сериализация моделей

Проект демонстрирует построение end-to-end ML пайплайнов и различные способы сериализации моделей машинного обучения.

## Описание

Проект включает в себя:
- Построение end-to-end ML пайплайнов с использованием scikit-learn
- Сравнение различных форматов сериализации моделей (pickle, joblib, ONNX, PMML)
- Бенчмаркинг производительности разных форматов сериализации

## Структура проекта
```
.
├── data/                               # Директория для данных
├── models/                             # Директория для сохранения моделей
├── notebooks/                          # Jupyter notebooks
│   ├── end_to_end_pipelines.ipynb      # Демонстрация пайплайнов
│   └── serialization.ipynb             # Сравнение форматов сериализации
├── requirements.txt                    # Зависимости проекта
├── pyproject.toml                      # Конфигурация Poetry
└── README.md
```
## Установка

1. Клонируйте репозиторий:
```
git clone https://github.com/your-username/otus-end-to-end-pipeline.git
cd otus-end-to-end-pipeline
```
2. Создайте виртуальное окружение и установите зависимости:

С помощью pip:
```
python -m venv .venv
source .venv/bin/activate  # для Linux/MacOS
.venv\Scripts\activate     # для Windows
pip install -r requirements.txt
```
Или с помощью Poetry:
```
poetry install
```
## Использование

1. Запустите Jupyter Notebook:
```
jupyter notebook
```
2. Откройте ноутбуки в директории notebooks/:
- end_to_end_pipelines.ipynb - для изучения построения пайплайнов
- serialization.ipynb - для сравнения форматов сериализации

## Зависимости

- Python 3.11+
- scikit-learn
- pandas
- matplotlib
- seaborn
- xgboost
- skl2onnx
- onnxruntime
- sklearn2pmml
- pypmml
- tabulate

## Лицензия

MIT

## Автор

[Nick Osipov](http://t.me/NickOsipov)