# Инструкция по работе с Git 

## Что такое гит?
***Git*** - самая популярная реализация распределенной системы контроля версий(версионность поддерживается и на сервере, и у каждого клиента).Самой распространненной реализацией ***Git*** является (*GitHub*)[https://github.com]   
## Подготовка репозитория

 
 
 
 
### Создание коммита 
Для создания новой фиксации(коммита)используется команда *git commit*.Для этого в терминале с папкой-репозиторием пишем *git commit -m "<сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!*** 
  
## Перемещение между  коммитами
 

### Добавление файлов к коммиту
Для добавления файла к новому коммиту используется команда *git add*.Используется она следущим образом:в терминале с папкой-репозиторием пишем *git add <название файла>*.     
 
## Создание "сохранений"

### Перемещение между "сохранениями"
Для перемещения на другую фиксацию(коммиты)использкется команда *git chechkout*.Для этого необходимо , как показано в прошлом пункте, в журнале изменений найти необходимый коммит и его хеш(номер),после чего в терминале с папкой-репозиторием надо написать *git chechkout<хеш коммита >*. После выполнения этой команды мы попадаем в состояние **detached head**,в котором никакие следущие коммиты сохраняться не будут. Для выхода из этого состояния необходимо написать *git checkout master*. 
 
## Журнал изменений
Для просмотра истории изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git* 
## Ветка в гит



### Создание вкток в гит
Для создания новой ветки используется команда *git branch*. Для этого в терминале с папкой-репозиторием необходимо написать
*git branch <название ветки>*. 
 
### Просмотр списка веток
Для просмотра списка веток используется команда *git branch*. Для этого в терминале с папкой-репозиторием необходимо написать*git branch*.Выделенная зеленым со звездочкой ветка - это ветка, в данный момент на которой мы находимся.  
 

### Перемещение между ветками
Для перемещения на другую ветку используют команду *git checkout*. Для этого в терминале с папкой-репозиторием нужно написать
*git checkout*. Такая ветка должна ***существовать***


 



## Создание "сохранений"
 
 

 

## Ветки в гит
 

## Слияние веток и разрешение конфликтов

## Удаление веток
