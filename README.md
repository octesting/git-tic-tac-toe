# git-tic-tac-toe  
Создаем ветку. Ставии крестик или нолик. Сливаем ветку. Смотрим результат.  
  
  
# Пример:  
```
git clone https://github.com/bi0morph/git-tic-tac-toe.git  
cd git-tic-tac-toe  
git checkout -b myTic  
```
Изменяем файл tic-tac-toe.txt  
```
|O| | | | | |  
| | | | | | |  
| | | | | | |  
| | | | | | |  
| | | | | | |  
```  
  
```
git add tic-tac-toe.txt  
git commit -m "Add 'O'"  
```
  
Подготовка перед слиянием  
  
```
git checkout master  
git pull  
git merge myTic
```

Отправляем изменения

```
git push
```
