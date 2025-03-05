# MY PROJECT
## 📌 Анализ Параллелепипедов

### 📖 Описание проекта
Этот проект предназначен для анализа параллелепипедов. Он считывает их размеры из JSON-файла, вычисляет характеристики (диагональ, объём, площадь поверхности) и сохраняет результаты в JSON-отчёты.

---

## 🚀 Как запустить

### 1️⃣ Клонирование репозитория
```bash
git clone <URL-репозитория>
cd my_project
```

### 2️⃣ Установка зависимостей (если есть)
```bash
pip install -r requirements.txt
```

### 3️⃣ Запуск программы
```bash
python main.py
```

---

## 📂 Структура проекта
```
my_project/
├── main.py                 # Главный скрипт
├── parallelepipeds.json    # Входные данные (размеры параллелепипедов)
├── utils/
│   ├── __init__.py         # Инициализация пакета
│   ├── functions.py        # Функции для вычислений
│   ├── statistics.py       # Анализ данных
└── outputs/                # Выходные файлы
    ├── characteristics.json
    ├── statistics.json
```

---

## 📊 Выходные файлы
- **`characteristics.json`** – данные по каждой фигуре (диагональ, объём, площадь и т. д.).
- **`statistics.json`** – статистика по всем фигурам (средний объём, средняя диагональ и т. д.).

---

## ⚙ Настройки
- **Изменить входные данные** – `parallelepipeds.json`
- **Изменить алгоритмы расчётов** – `utils/functions.py`

---

## ❗ Возможные ошибки и их решения
1. **Ошибка JSON?** – Проверь формат входного файла `parallelepipeds.json`.
2. **Не работает Python?** – Убедись, что используешь **Python 3.6+**.

---

✍ **Автор:** _<Марсияна>_





