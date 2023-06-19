
# Проект автотестов для API-эндпоинтов 
Этот проект содержит автотесты для проверки работоспособности API-эндпоинтов. Он использует язык программирования Python и библиотеку requests для отправки HTTP-запросов к API.

***
### Требования
Для запуска проекта вам понадобятся следующие компоненты:

- Python 3.9.4
- Библиотека requests 2.31.0
- Библиотека pytest 7.3.1

***

1. Установите Python (версия 3.6 или выше) - [Ссылка на загрузку](https://www.python.org/downloads/).

2. Установите необходимые зависимости, выполнив следующую команду в командной строке/терминале:

   ```bash
   pip install requests pytest

3. Склонируйте репозиторий на вашу локальную машину:

   ```bash
   git clone https://github.com/your-username/test-api-project.git

4. Перейдите в директорию проекта: 

   ```bash
   cd test-api-project
   
5. Установите зависимости из файла requirements.txt:

   ```bash
   python -m pip install --upgrade pip
   pip install -r requirements.txt

6. Запустите автотесты с помощью команды:

   ```bash
   pytest tests/
