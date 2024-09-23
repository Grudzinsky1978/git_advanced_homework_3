# Git Advanced. Lesson 3. Homework
Учебный репозиторий для урока 3 Git Advance


* Создал удалённый репозиторий git_advanced_homework_3, README.md файл, .gitignore
Клонировал `git clone https://github.com/Grudzinsky1978/git_advanced_homework_3.git`
* cd git_advanced_homework_3/
* Редатировал README.md
* Коммит
Отправил изменения `git push -u origin main`
* Перенёс файлы программы
* Коммит
* `git push`

---

## Подготовка к запуску программы во Flask
```
python -m venv .venv
.venv/Scripts/activate
python -m pip install flask
pip install flask-wtf
pip install Flask-SQLAlchemy
pip install email_validator
flask init-db
```

## Тимлид
* Добавил сотрудника GrudzinskyTest1978 к своему репозиторию Settings > Collaborators
* Попросил принять приглашение пользователя GrudzinskyTest1978 (в уведомлениях)
* Добавил задание в таск-трекере: Добавить поле Отчество, переинициализировать БД, добавить тестовые записи
* Назначил исполнителем данного задания пользователя, которого ранее добавил, в комментарии указал, что надо сделать в отдельной ветке

## Сотрудник
* Клонировал `git clone https://github.com/Grudzinsky1978/git_advanced_homework_3.git`
* `cd git_advanced_homework_3/`
* Проверил `git remote -v`
* Попросил requirements.txt
* Обновил данные `git pull`
* `python -m venv .venv`
* `.venv/Scripts/activate`
* `pip install -r requirements.txt`
* Создание ветки `git switch -c 1-add-field`
* Выполнение задания
* Коммит
* Отправка ветки `git push -u origin 1-add-field`
* Сделал pull request в удалённом репозитории
* Назначил на тимлида

## Тимлид
* Проверил, слил ветку, удалил слитую ветку в удалённом репозитории
* git pull
* Коммит
* git push

