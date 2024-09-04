Парсинг задач с сайта https://codeforces.com/

Программа загружает задачи в базу данных postgres.
Пользователь взаимодействует с программой через телеграм бота

Взаимодействие с ботом:

1. Выберите сложность

2. Выберите категию/тему
для поиска используйте кнопки навигации «Вперед» «Назад» или введите текст

3. После выбора категории появляется список из 10 задач выбраной сложности и категории.
для просмотра списка задач используте кнопки «Вперед» «Назад».

Для поиска конкретной задачи нажмите «Уточнить поиск» или введите название задачи в строку поиска


Настройка программы.
1. Клонировать проект

2. Создать виртуальное окружение, установить библиотеки
pip install -r  requirements.txt

3. Создать БД postgres скрипт Create.sql.

4. Регистрация бота в BotFather.

5. Создайте файл с переменными окружения в файле .env. Пример файла .env.sample

