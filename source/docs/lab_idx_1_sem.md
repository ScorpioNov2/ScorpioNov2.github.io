# Лабораторные работы 1-го семестра (Python)

![Версия](https://img.shields.io/badge/версия-1.0.0-blue)
![Лицензия](https://img.shields.io/badge/лицензия-MIT-green)
![Python](https://img.shields.io/badge/python-3.9-blue)

Сборник лабораторных работ, выполненных в первом семестре обучения в Университете ИТМО. Работы охватывают основы программирования на Python, алгоритмы, структуры данных, а также клиент-серверное взаимодействие и работу с базами данных.

---

## 📦 Содержание

- [Описание](#описание)
- [Особенности](#особенности)
- [Индексы](#индексы)
- [Установка](#установка)
- [Структура проекта](#структура-проекта)
- [Зависимости](#зависимости)
- [Лицензия](#лицензия)
- [Контакты](#контакты)
---

## 📖 Описание <a href="описание"></a>

Проект представляет собой набор из 10 лабораторных работ, каждая из которых посвящена определённой теме. Все работы выполнены на Python 3.9 и сопровождаются подробными комментариями и отчётами.

![Пример работы](https://via.placeholder.com/800x400?text=Скриншот+лабораторной)

---

## ✨ Особенности <a href="особенности"></a>

- ⚡ Изучение рекурсивных и нерекурсивных алгоритмов
- 🔒 Работа с бинарными деревьями
- 📊 Профайлинг и сравнение производительности
- 🐞 Логирование и обработка ошибок
- 🌐 Клиент-серверное приложение с Jinja2
- 🗄️ CRUD с SQLite
- ⚙️ Ускорение кода с помощью Cython

---

## Индексы <a id="индексы"></a>

🔹 Лаба 1: **[Сумма двух](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_1)** – вводная задача на сложение чисел.  
🔹 Лаба 2: **[Угадай число](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_2)** – игра с угадыванием числа, генерация случайных чисел.  
🔹 Лаба 3: **[Рекурсивное бинарное дерево](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_3)** – построение и обход дерева рекурсивно.  
🔹 Лаба 4: **[Сравнение работы функций. Профайлинг](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_4)** – измерение времени выполнения и оптимизация.  
🔹 Лаба 5: **[Нерекурсивное бинарное дерево](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_5)** – итеративная реализация.  
🔹 Лаба 6: **[Сравнение реализаций построения бинарного дерева](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_6)** – рекурсивный vs нерекурсивный подход.  
🔹 Лаба 7: **[Логирование и обработка ошибок в Python](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_7)** – модули `logging` и `try-except`.  
🔹 Лаба 8: **[Клиент-серверное приложение на Python с использованием Jinja2](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_8)** – простой HTTP-сервер и шаблонизатор.  
🔹 Лаба 9: **[CRUD для приложения отслеживания курсов валют c SQLite базой данных](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_9)** – создание, чтение, обновление, удаление записей.  
🔹 Лаба 10: **[Cython](https://github.com/ScorpioNov2/PythonLabs/tree/main/PythonLabs_year_1th/1_semester/PyLab_10)** – ускорение вычислений с помощью Cython.

---

## 🚀 Установка <a id="установка"></a>

### Требования

- Python 3.9 или выше
- pip

### Пошаговая инструкция

1.Клонируйте репозиторий:  

```bash
git clone https://github.com/ScorpioNov2/PythonLabs.git  
```

2.Перейдите в папку первого семестра:  

```bash
cd PythonLabs/PythonLabs_year_1th/1_semester  
```

3.(Опционально) Создайте виртуальное окружение:  

```bash
python -m venv venv
source venv/bin/activate  # для Linux/Mac 
venv\Scripts\activate     # для Windows 
```

4.Установите общие зависимости (если есть):  

```bash
pip install -r requirements.txt  
```  

(файл requirements.txt может отсутствовать – зависимости указываются в каждой лабораторной отдельно)

## 📁 Структура проекта <a id="структура-проекта"></a>
1_semester/  
├── PyLab_1/               # Сумма двух  
├── PyLab_2/               # Угадай число  
├── PyLab_3/               # Рекурсивное дерево  
├── PyLab_4/               # Профайлинг  
├── PyLab_5/               # Нерекурсивное дерево  
├── PyLab_6/               # Сравнение деревьев  
├── PyLab_7/               # Логирование  
├── PyLab_8/               # Клиент-сервер + Jinja2  
├── PyLab_9/               # CRUD валюты + SQLite  
├── PyLab_10/              # Cython  
└── README.md              # Этот файл  

## 📚 Зависимости <a id="зависимости"></a>

Общие зависимости могут включать:
- jinja2 – для лабораторной №8
- sqlite3 – встроен в Python
- cython – для лабораторной №10
Более детально – в каждой папке лабораторной.

## 📃 Лицензия <a id="лицензия"></a>
Проект распространяется под лицензией MIT. Подробнее см. в файле [LICENSE](../about/license/).

## 📬 Контакты <a id="контакты"></a>
Автор: Мань Зыонг  
Email: [daomanhduong2112005@gmail.com](mailto:daomanhduong2112005@gmail.com)  
GitHub: [ScorpioNov2.github.io](https://scorpionov2.github.io/)  


