### Копирование файлов
```
git clone URL
```
#
### Скачать обновновленный репозиторий
```
git pull
```
#
### Выложить проект на гитхаб
```
git init
git add .
git commit -m "Комментарий"
git branch -M Название ветки
git push -u origin main
```
#
### Создать ветку и переключиться на неё
```
git branch brnch
git checkout brnch
```
#
### Файл .gitignore
```
### Игнорирует файлы при добавлении

ignore /
        .idea
        .venv
        .env
        info.txt
        ......
```
#
### Удаление ветки

```
git branch --delete НазваниеВетки # удаляем ветку локально
git push origin --delete НазваниеВетки # удаляем ветку на сервере
```
#
### Настройка учетной записи
```
git config --global user.email = "почта@gmail.com"
git config --global user.name = "Имя"
```
#