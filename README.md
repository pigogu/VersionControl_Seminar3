## Начальная работа с системой контроля версий

*git --version -команда для проверки git

*git init -инициализируем пустой репозиторий

*git status -проверяем текущие состояние файлов

*git add имя_файла_с расширением -добавляем версионность файлу

*git add . -добавляем версионность всех файлов в папке

*git commit -m "Сообщение" -команда для фиксации изменений файлов

*git commit -am "Сообщение" - фиксация изменений, не требует git add .

*git diff - вывод изменений на текущий момент по отношению к последнему коммиту

*git log - вывод истории коммитов в хронологическом порядке

*git checkout хэш_коммита - переход между изменениями

*git checkout master - возврат к текущему состоянию

*git clone ссылка* -команда для загрузки удаленного репозитория

*git push* - команда для  отправки локального репозитория в удаленный 

*git pull* - команда для подгрузки изменений из удаленного репозитория в локальный

*git branch* - посмотреть списоки веток

*git branch название_ветки* - создать новую ветку

*git checkout -b название_ветки* - перейти к другой ветке и, есле ее нет, то создать

*git branch -d название_ветки* - удалить ветку


## Что такое Git?

Git - это одна из реализаций распределенных систем контроля версий, имеющая как локальный, так и удаленный репозиторий. Является самой популярной реализацией систем контроля в мире.

## Подготовка репозитория

Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием.

## Git add 

Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add имя_файла* или *git add .*

## Создание коммитов

Для того, чтобы создать коммит (сохранение), необходимо выполнить команду *git commit -m "Сообщение"* или *git commit -am "Сообщение"*.

## Создание ветки 

Для того, чтобы создать ветку, нужно использовать *git branch имя_ветки* или *git checkout -b имя_ветки* (последняя команда еще и переместит в новую ветку).

## Git log 

Чтобы посмотреть историю комитов, нажмите *git log*. Если нужно кратко, то *git log --oneline*. Для отображения веток команда *git log --graph*.

## Слияние веток

Чтобы слить ветку в текущую, нажмите *git merge имя_ветки*.

## Проверка репозитория

Для получения информации от *git* о его текущем состоянии, нужно ввести команду *git status*.

## Отмена изменений в рабочей директории

Для отмены изменений в рабочей директории необходимо выполнить одну команду *git checkout --имя_файла*.