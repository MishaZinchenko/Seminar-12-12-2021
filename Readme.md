# Инструкция по работе с  Git и удаленными репозиториями 

## Что такое Git?
Git - одна из реализаций распределенных систем контроля версий, имеющая как локальную версионность, так и версионнность на сервере. Git является самой популярной системой контроля версий на сегодняшний день.

## Подготовка репозитория 
Для того, чтобы созать репозиторий в указанной папке используется команда *git init*. Для этого достаточно написать *git init* в папке с будущем репозиторием.

## Создание фиксаций
### Просмотр информации о изменениях

Для того, чтобы посмотреть  информацию об изменениях, сделанных в текущей ветке, необходимо использовать команду *git status*. Для этого достаточно использовать *git status* в папке с репозитроем.

### Добавление файла к коммиту
Для того, чтобы добавить файл к новому коммиту("сохранению") необходимо использовать команду *git add*. Используется она следующим образом: в папке с репозиторием пишем команду *git add <имя файла>*


### Созданние коммитов


Для создания новой фиксации необходимо использовать команду *git commit*. Использутся она следующим образом: в папке с репозиторием пишется команда *git commit -m "<сообщение к комиту>"*. Все файлы коммита должны быть предваритльно добавлены с помощью команды*git add*. Сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**.

## Перемещение между сохранениями 
Для перемещения между коммитами необходимо использовать команду *git checkout*. Используется команда следующим образом в папке с репозиторием *git checkout <номер коммита>*.
 
## Жрунал изменений 
Для просмотра журнала изменений необходимо использовать команду *git log*. Для этого нужно в папку с репозиторием написать *git log*

##  Ветки в Git
### Просмотр списка веток 
Для того, чтобы просмотреть список веток необходимо использовать команду *git branch*. Для этого нужно  в папке с репозиторием набрать команду *git branch*

## Слияние веток и разрешение конфликтов 

## Удаление веток 
