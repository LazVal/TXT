# TXT
### _1. Создать внешний репозиторий c названием TXT._
### _2. Клонировать репозиторий TXT на локальный компьютер._
```
    git clone https://github.com/LazVal/TXT.git
```
### _3. Внутри локального TXT создать файл “new.txt”._
```
    cd txt
    touch new.txt
```
### _4. Добавить файл под гит._
```
    git add new.txt
```
### _5. Закоммитить файл._
```
    git commit -m "new.txt"
```
### _6. Отправить файл на внешний GitHub репозиторий._
    
    git push

### _7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT._
### _8. Отправить изменения на внешний репозиторий._
     
     git add new.txt
     git commit -m "update new.txt"

### _9. Создать файл preferences.txt_
    
    cat>preferences.txt

### _10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT._

### _11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT_
    
    cat > skills.txt

### _12. Сделать коммит в одну строку._
    
    git add . 
    
    git commit -a -m "add new"

### _13. Отправить сразу 2 файла на внешний репозиторий._
    
    git push
### _14. На веб интерфейсе создать файл bug_report.txt._
### _15. Сделать Commit changes (сохранить) изменения на веб интерфейсе._
### _16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT._
### _17. Сделать Commit changes (сохранить) изменения на веб интерфейсе._
### _18. Синхронизировать внешний и локальный репозиторий TXT_
    
    git pull
