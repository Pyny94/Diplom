# Дипломная работа: Сравнительный анализ библиотек визуализации данных в Python

**Описание проекта:**

Данная дипломная работа посвящена сравнительному анализу трех популярных библиотек для визуализации данных в Python: Matplotlib, Seaborn и Plotly.  Работа направлена на определение сильных и слабых сторон каждой библиотеки, а также на разработку рекомендаций по выбору наиболее подходящего инструмента для решения различных задач визуализации.

**Цель работы:**

Провести комплексный анализ функциональных возможностей, простоты использования и производительности библиотек Matplotlib, Seaborn и Plotly при визуализации данных, а также определить оптимальный выбор инструмента для решения конкретных задач.

**Задачи работы:**

* **Изучение теоретических основ:**  Анализ архитектуры и возможностей каждой из рассматриваемых библиотек.
* **Экспериментальная часть:** Создание множества графиков различных типов (гистограммы, диаграммы рассеяния, ящики с усами, линейные графики, и другие) с использованием каждой библиотеки.  Визуализации должны быть построены на основании выбранного набора данных (например, набор ирисов из scikit-learn).
* **Сравнение библиотек:** Анализ кода, производительности, качества визуализации, гибкости настройки и интерактивности для каждого типа графиков.
* **Выявление сильных и слабых сторон:**  Определение ситуаций, в которых каждая библиотека наиболее эффективна.
* **Разработка рекомендаций:**  Формирование практических рекомендаций по выбору библиотеки для конкретных задач визуализации данных.
* **Документация:**  Создание подробной документации, включающей примеры кода, графиков, и подробные пояснения к каждому этапу работы.

**Набор данных:**

В работе используется набор данных набор данных ирисов (Iris) из scikit-learn.  Этот набор предоставляет возможность для визуализации и сравнения результатов, полученных с помощью различных библиотек.

**Используемые технологии:**

* Python
* Matplotlib
* Seaborn
* Plotly
* Pandas
* NumPy
* Scikit-learn (для загрузки набора данных)


**Структура работы:**

1. **Введение:** Обзор проблемы, актуальность, цель и задачи работы.
2. **Теоретическая основа:** Описание принципов работы, функциональных возможностей и сильных/слабых сторон каждой библиотеки.
3. **Методология:** Описание используемых методов анализа и сравнения библиотек.
4. **Экспериментальная часть:**  Подробный анализ результатов визуализации с примерами кода и графиков для каждого типа визуализации.
5. **Результаты и обсуждение:** Сравнение полученных результатов, обсуждение преимуществ и недостатков каждой библиотеки.
6. **Рекомендации:**  Рекомендации по выбору библиотеки для решения различных задач визуализации данных.
7. **Заключение:** Краткое резюме полученных результатов и перспектив дальнейшего исследования.



**Описание файлов проекта (если применимо):**

* `.ipynb` - скрипт(ы) Python с кодом для визуализации.



**Как использовать:**

Для воспроизведения результатов данной дипломной работы необходимо выполнить следующие шаги:


**1. Установка необходимых библиотек:**

Убедитесь, что на вашем компьютере установлены все необходимые библиотеки Python.  Для этого используйте менеджер пакетов `pip`:


pip install matplotlib seaborn plotly pandas numpy scikit-learn


**2. Загрузка набора данных:**

Набор данных, используемый в работе (“ирисы”), можно загрузить несколькими способами:

Встроенный в scikit-learn:                Если это набор данных ирисов, то его можно загрузить напрямую из библиотеки sklearn:
from sklearn.datasets import load_iris
iris = load_iris()

Из файла: Если набор данных находится в отдельном файле (например, CSV, JSON), то его нужно загрузить с помощью pandas:

import pandas as pd

df = pd.read_csv("path/to/your/data.csv") # Замените "path/to/your/data.csv" на путь к вашему файлу


**3. Запуск кода:**

Все скрипты с кодом для построения графиков находятся в директории. Вы можете запустить их по одному или все сразу в вашей среде разработки Python (например, Jupyter Notebook). Обратите внимание, что для отображения интерактивных графиков Plotly вам потребуется запустить код в среде, поддерживающей JavaScript (например, Jupyter Notebook).

**4. Воспроизведение графиков:**

Каждый скрипт содержит код для построения различных типов графиков. Запустив скрипт, вы получите соответствующие графики. 
![image](https://github.com/user-attachments/assets/c393364a-5767-43a3-9c72-31929055e4f9)
![image](https://github.com/user-attachments/assets/153966a1-caa6-4e07-a82f-1f20307fb90a)

**5. Интерпретация результатов:**

**Seaborn:**

![image](https://github.com/user-attachments/assets/9980b637-c361-473f-b73c-55f23f42acda)
![image](https://github.com/user-attachments/assets/756c1d59-f97b-4d21-97ca-3ae74f4b445b)
![image](https://github.com/user-attachments/assets/f1a3e588-15f8-4816-b86a-67118b8f008b)
![image](https://github.com/user-attachments/assets/117ad02f-1d24-46ef-991a-62fe8862e0a1)
![image](https://github.com/user-attachments/assets/049d44c5-e08a-46ea-ac93-05a8d0c5b18d)
![image](https://github.com/user-attachments/assets/8e7f5e68-325e-4efc-90ed-4dd0629c46fe)
![image](https://github.com/user-attachments/assets/576cd08e-434b-4b85-8f39-841d8a15c8c7)
![image](https://github.com/user-attachments/assets/5aeae56f-62dd-4842-a70d-c968e579f7f6)
![image](https://github.com/user-attachments/assets/67abec9d-6ee3-4f49-b421-9eb7d35bbbae)

**Matplotlib:**

![image](https://github.com/user-attachments/assets/bf7ef63e-8f68-46e8-9613-543d131dd6ab)
![image](https://github.com/user-attachments/assets/78cda204-0323-4705-ac60-8c4e4e3ce49f)
![image](https://github.com/user-attachments/assets/d400d4f6-c6c6-4441-a9bc-2052caad0205)
![image](https://github.com/user-attachments/assets/808dd3dd-2e4d-4690-993d-500d5bf91acd)
![image](https://github.com/user-attachments/assets/43200543-4b3a-4c0b-b010-98ce298d1977)
![image](https://github.com/user-attachments/assets/8ff8fe9b-c09a-4cb9-be25-b2bfbf3c3acb)
![image](https://github.com/user-attachments/assets/a99dc5f4-8b96-4ce2-bc55-7753deaa10e5)
![image](https://github.com/user-attachments/assets/52ed32e6-6537-4745-9a45-d95ee3641b93)
![image](https://github.com/user-attachments/assets/01377ccd-7fd6-4058-96d7-6f88e690237f)
![image](https://github.com/user-attachments/assets/a357b2ff-9958-432e-b434-d851e95d5829)

**Plotly:**

![image](https://github.com/user-attachments/assets/f7d8346e-c351-40bf-90e4-c75dac34d58e)
![image](https://github.com/user-attachments/assets/85378173-f81f-4ed8-9366-12c03e52b5e3)
![image](https://github.com/user-attachments/assets/43383e19-4d92-4c9a-a49c-ce5e050b2f4c)
![image](https://github.com/user-attachments/assets/bc04454f-2477-4281-8b46-4479c5695526)
![image](https://github.com/user-attachments/assets/c57dbb38-d97d-4d70-9e64-c8985927d508)
![image](https://github.com/user-attachments/assets/72e8bfd7-b86d-4800-b8f0-b4196530be3d)
![image](https://github.com/user-attachments/assets/b3d432a9-c15e-4dfb-a829-eba92648ebfb)
![image](https://github.com/user-attachments/assets/90964c12-e2cf-49f9-a38f-ca1adc4d8ef8)
![image](https://github.com/user-attachments/assets/cbcc1b76-18b8-4055-a530-1dc1cbf41fc9)
![image](https://github.com/user-attachments/assets/a27baadc-b3ba-47d5-838c-5563619730c9)








































