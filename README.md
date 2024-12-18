# HW1_prediction_price
# ПРЕДПОЛОГАЮ,ЧТО ЭТО КОТИК САБРИНЫ
# Отчет по выполненной работе

## 1. EDA (Exploratory Data Analysis)
В рамках анализа данных выполнено:
- **Первичный анализ данных:** изучение структуры, пропусков, распределений данных.
- **Обработка признаков:** заполнение пропусков, преобразование форматов данных.
- **Построение графиков:** визуализация распределения данных и ключевых зависимостей.
- **Анализ взаимосвязей:** изучены зависимости признаков с целевой переменной `selling_price`.

---

## 2. Построение моделей
В рамках данного этапа были выполнены следующие задачи:
- **Модели на вещественных признаках:** реализованы модели, работающие с числовыми признаками.
- **GridSearchCV:** выполнен подбор гиперпараметров моделей для улучшения их качества.
- **Кодирование категориальных признаков:** применен метод кодирования OneHotEncoding.
- **Лучшая модель:** определена лучшая модель — **Ridge**.
- **Оценка бизнес-метрики:** произведены расчеты бизнес-метрик для моделей.

---

## 3. Реализация сервиса FastAPI
- Разработан API-сервис для прогнозирования.
- Созданы два эндпоинта:
  - `/predict_item` — прогнозирует цену для одного объекта.
  - `/predict_items` — принимает CSV-файл с объектами и возвращает файл с прогнозами.
## 4. Отчет по реализации сервиса
<img width="1155" alt="Снимок экрана 2024-12-03 в 20 47 17" src="https://github.com/user-attachments/assets/d26288a5-abd9-45b9-9947-6a55e95709fa">

<img width="1425" alt="Снимок экрана 2024-12-03 в 20 24 58" src="https://github.com/user-attachments/assets/74241837-c746-49e3-aef1-2e30189353be">

<img width="1470" alt="Снимок экрана 2024-12-03 в 20 26 58" src="https://github.com/user-attachments/assets/3ed7ef9f-c7b0-42c3-a770-b9d2ae39f902">

