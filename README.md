# Python_FLAS_2025
Материалы курса Python для FLAS

# Программа курса: 
1. Знакомство с Python, git, PyCharm, Colab, Jupyter Notebook, VS Code
2. [Операторы ввода/вывода (print, display, input), списки](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_1_Intro.ipynb), [циклы](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_2_if%2C_while%2C_for.ipynb) + [бонус](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/%D0%91%D0%BE%D1%82%D1%8B_HomoDigitus.ipynb)
3. [Кортежи, множества, словари](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_3_tuple%2C_set%2C_dict.ipynb)
4. [Работа с функциями](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_4_Function.ipynb), [методы](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_5_%D0%A8%D0%BF%D0%B0%D1%80%D0%B3%D0%B0%D0%BB%D0%BA%D0%B0_%D0%BF%D0%BE_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%B0%D0%BC.ipynb)
5. [Работа с файлами, модуль os](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_6_os%2C_files.ipynb) ***(КТ)***
6. [Регулярные выражения, препроцессинг](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_7_regex.ipynb)
7. [Частотные списки и n-граммы](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_8_NLTK%2C_%D1%87%D0%B0%D1%81%D1%82%D0%BE%D1%82%D0%BD%D1%8B%D0%B5_%D1%81%D0%BF%D0%B8%D1%81%D0%BA%D0%B8%2C_n_%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B.ipynb), [Работа с Unicode](https://github.com/AnnSenina/Python_CL_2024/blob/main/notebooks/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0_%D1%81_Unicode_%D0%B2_Python.ipynb)
8. [pymorphy, mystem и др.](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_9_pymorphy%2C_mystem.ipynb)
9. [pandas, работа с датасетами](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_10_pandas.ipynb)
10. [Анализ данных и визуализация](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_11_Viz.ipynb) ***(КТ)***
11. [собираем корпус: парсеры...](https://github.com/AnnSenina/Python_FLAS_2025/blob/main/notebooks/Python_12_BeautifulSoup.ipynb)
12. Поиск -> подготовка данных. Переменные, шкалы.
13. Описательные статистики. Распределения.
14. Выбросы. Корреляционный анализ
15. Введение в машинное обучение ***(КТ)***

## Знакомство с Python, git, PyCharm, Colab, Jupyter Notebook 
Установим Python:

- для [Windows](https://www.python.org/downloads/windows/)
- [MacOS](https://www.python.org/downloads/macos/)
- [Linux](https://www.python.org/downloads/source/)
- *[Python на Android](https://pythonru.com/baza-znanij/python-na-android)*

Установка IDE (интегрированная среда разработки):
- [PyCharm](www.jetbrains.com/pycharm/download/)
- [Jupyter Notebook](https://jupyter.org/install) (тетрадь: code и markdown). **Важно!** Если есть проблемы с установкой Jupyter Notebook, можно пойти простым путем и установить [Anaconda](https://www.anaconda.com/download#downloads) (большая сборка, Jupyter Notebook в нее входит)
- [Microsoft Visual Studio Code](https://code.visualstudio.com/download)
- [Google Colab](https://colab.research.google.com) (онлайн-тетрадь, без установки)

Git и GitHub
1. Зарегистрироваться на [GitHub](https://github.com)
2. Установить [Git](https://git-scm.com/downloads)

- Windows - [скачать](https://git-scm.com/download/win), выбрав версию (32/64-разрядная система), установить как обычную программу (не менять никакие настройки при установке)  
- MacOS -  
если есть [homebrew](https://brew.sh): $ brew install git  
если нет, [ссылка](https://git-scm.com/download/mac), выбираем вариант **Binary installer**  
- Linux - команда в терминале для вашего дистрибутива со [страницы](https://git-scm.com/download/linux)  

Начало работы с Git (через командную строку) смотрим здесь:
- [githowto](https://githowto.com/ru): пошаговое обучение от git
- [скринкаст](https://youtu.be/piq5dSX7hL0), ссылка из скринкаста для создания вашего личного [токена](https://github.com/settings/tokens/new)
- [Oh my Git!](https://ohmygit.org/) (игра по Git)

## Литература
- Folgert Karsdorp, Mike Kestemont, Allen Riddell. [Humanities Data Analysis: Case Studies with Python](https://www.humanitiesdataanalysis.org/index.html)
- William J.B. Mattingly. [Introduction to Python for Humanists](http://python-textbook.pythonhumanities.com/intro.html)
