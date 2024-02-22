# Подсказки по гиту

```sh
## Задать имя пользователя

git config --global user.name "Tara Routr"
```

```sh
##Задать адрес электронной почты

git config --global user.email "dev@tararoutray.com"
```

```sh
## Инициализация репозитория 

git init
```


```sh
## Добавление отдельных файлов

git add ( somefile.js - Заменить на свое имя)
```

```sh
## Проверка статуса репозитория

git status
```

```sh
## Внесение изменений однострочным сообщением или через редактор

git commit -m "Your short summary about the commit"
```

```sh
## Просмотр истории коммитов с изменениями

git log -p
```

```sh
## Просмотр заданного коммита

git show 1af17e73721dbe0c40011b82ed4bb1a7dbe3ce29

Также можно использовать сокращённый хеш.

git show 1af17e
```

```sh
##Просмотр изменений до коммита

git diff

```sh
## Удаление отслеживаемых файлов из текущего рабочего дерева

git rm dirname/somefile.js
```

```sh
## Отмена подготовленных и неподготовленных изменений

git checkout somefile.js
```
 
