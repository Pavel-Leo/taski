# Taski

## Описание
Приложение для планирования своих задач.
В приложении настроен закрытый доступ к API.
Taski — приложение, которое написано на React.

## Перед тем как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git@github.com:Pavel-Leo/taski.git
```

```
cd taski/backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv (для mac и linux)
python -m venv venv (для windows)
```

```
source venv/bin/activate (для mac и linux)
source venv/Scripts/activate (для windows)
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip (для mac и linux)
python -m pip install --upgrade pip (для windows)
```

```
перейти в дирректорию где хранится файл requirements.txt и оттуда выполнить команду:

pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate (для mac и linux)
python manage.py migrate (для windows)
```

## Запустить проект:

Откройте первый терминал.
Перейдити в дирректорию taski/backend где хранится файл manage.py и оттуда
выполните команду:
```
python3 manage.py runserver (для mac и linux)
python manage.py runserver (для windows)
```

Откройте второй терминал.
Установите зависимости frontend приложения.
Из директории taski/frontend/ выполните команду:
```
npm i
```

Когда все зависимости установятся, выполните команду во втором терминале

```
npm run start
```
держа первый терминал запущенным.

Откроется приложение на порте 3000


