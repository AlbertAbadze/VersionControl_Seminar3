## Что такое Git?

Git — самая популярная в мире распределённая система контроля версий. Линус Торвальдс, разработчик ядра ОС Linux, создал этот инструмент ещё в 2005 году, а сегодня Git активно поддерживается как проект с открытым исходным кодом. Огромное количество открытых и коммерческих проектов используют Git для контроля версий.

### Перед началом работы нужно выполнить некоторые настройки:

git config --global user.name "Your Name" # указать имя, которым будут подписаны коммиты
git config --global user.email "e@w.com"  # указать электропочту, которая будет в описании коммитера

## Подготовка репозитория

Репозитории — это классы или компоненты, которые содержат логику, необходимую для доступа к источникам данных. Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием.    

## Git add

Для добавления изменений коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add <имя файла>*. Чтобы добавить изменения всех файлов - выполните команду *git add .*.

## Создание коммитов

Простыми словами, коммит — это снимок ваших локальных файлов, записанный в локальный репозиторий. 
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду *git commit -m "Сообщение"*

## Создание ветки

Для того, чтобы создать ветку необходимо использовать *git branch <имя ветки>* или *git checkout -b <имя ветки>* (во втором случае будет одновременно произведен переход на вновь созданную ветку).

### __*Список команд:*__

*git init* - инициализация __локального__ репозитория

*git status* - получение информации о текущем состоянии

*git add* - добавить файл или файлы к текущему коммиту

*git commit -m "Сообщение"* - создание коммита

*git log* - вывод на экран истории всех коммитов с их хеш-кодами

*git log graph* - вывод на экран коммитов с ASCII-представлением ветвления

 *git log --pretty=oneline --graph, где --pretty=oneline* - для каждого коммита отобразит по одной строке, состоящей из хэша и комментария, а --graph покажет небольшой граф в формате ASCII.

*git clone <Url-адрес репозитория>* - клонирование __внешнего__ репозитория на локальный ПК

*git pull* - __получение__ изменений и слияние с локальной версией 

*git push* - __отправка__ локальной версии репозитария на внешний

*git checkout* - переход от одного коммита к другому

*git diff* - оторбражение разницы между текущем файлом и закоммиченным файлом.

*git merge <название ветки>* - команда слияния с главной веткой (необходимо находить на ветке master)

![текст, который будет показан, если изображение не загрузится](имя файла, которое должно находиться в рабочей папке) - добавление изображений