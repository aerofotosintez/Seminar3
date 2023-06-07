# Основные команды git

> При первом использовании Git необходимо представиться.  Для этого нужно ввести в терминале 2 команды:

git config --global user.name «Ваше имя английскими буквами»

git config --global user.email ваша почта@example.com

> Команды:

✦	git init – инициализация локального репозитория

✦	git status – получить информацию от git о его текущем состоянии

✦	git add – добавить файл или файлы к следующему коммиту

✦	git commit -m “message” – создание коммита.

✦	git log – вывод на экран истории всех коммитов с их хеш-кодами

✦	git checkout – переход от одного коммита к другому

✦	git checkout master – вернуться к актуальному состоянию и продолжить работу

✦	git checkout  -b <название ветки> - создание ветки и переход к ней

✦   git checkout <название ветки> – переход к другой ветке

✦	git diff – увидеть разницу между текущим файлом и закоммиченным файлом

✦	git merge --abort - отменить слияние, которое прошло с конфликтом

✦	git log --graph - вывод на экран истории всех коммитов с их хеш-кодами в древовидной форме

✦	git commit -am “message” – добавление файлов в отслеживание и       создание коммита

✦	git log --oneline – коротенький журнал

✦	git branch – посмотреть список веток в репозитории

✦	git branch <название ветки> – создать новую ветку

✦	git branch -d <название ветки> – удалить ветку

# Инструкция работы с Marcdown

## Синтаксис

## Изображения и ссылки

* ! [ Иллюстрация к проекту ] (https://github.com/jon/coolproject/raw/master/image/image.png)

* ! [Image alt] (https://github.com/{username}/{repository}/raw/{branch}/{path}/image.png)

{username} — ваш ник на ГитХабе;
{repository} — репозиторий где хранятся картинки;
{branch} — ветка репозитория;
{path} — путь к месту нахождения картинки.

# Заметки

> Установка Git для Windows, MAC, Linux: https://git-scm.com/downloads

> Установка VSCode для Windows, MAC, Linux: https://code.visualstudio.com/Download

> Справочник по Markdown от Microsoft:
https://docs.microsoft.com/ru-ru/contribute/markdown-reference