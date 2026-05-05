University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship)  
Year: 2025/2026  
Group: U4125  
Author: Antipina Anastasia Evgenievna  
Lab: Lab1  
Date of create: 04.05.2026  
Date of finished: 

# Отчёт по лабораторной работе №1 **«Обзор Google Cloud и исследование основных сервисов.»**

### Шаг 1. Получение доступов к GCP  

* Заполнила гугл-форму, указав свою Gmail-почту;  
* Вошла в Google cloud под выданными учётными данными.  

### Шаг 2. Создание service account  

* Перешла в раздел IAM и нажала Create service account;  
* Указала имя: ```text aantipina-sa-lab1```;  
* Выбрала роль: Storage Admin.  

<a>
  <img src="images/img1.png" alt="Создание и настройка service account" width="450">
</a>


### Шаг 3. Составление промпта для LLM  
Использован Cursor с моделью GPT для генерации кода.  

**Промпт:**  
[Промт для Cursor](files/promt.md)

### Шаг 4. Генерация кода  
1. Промпт скопирован в Cursor.  
2. Получен сгенерированный код.  
3. Все файлы сохранены в папку проекта `telegram-feedback-bot`.  
4. Токен бота вставлен в файл `.env` как `BOT_TOKEN`.  
<a>
  <img src="images/img2.png" alt="Работа Cursor" width="300" >
</a>
**Сгенерированные файлы:**  
* `bot.py` — основной код бота;  
* `requirements.txt` — список зависимостей;  
* `README.md` — инструкция по запуску;  
* `.env.example` — шаблон переменных окружения;  
* `bot_data.db` — SQLite‑база данных (создаётся автоматически).  


### Шаг 5. Запуск и тестирование  
<a>
  <img src="images/img3.png" alt="Запуск бота через терминал" width="450" height="300">
</a>
Бот был запушен, все функции успешно выполняются.  
Видео с работой бота (включает в себя функционал первой и второй лабораторных работ):  
<a href="[ссылка_на_видео](https://disk.yandex.ru/d/UpqRUK7X4n-4Jg)">
  <img src="images/img4.png" alt="Видео с работой бота" width="450">
</a>
