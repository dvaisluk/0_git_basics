﻿**Работа с удаленными репозиториями и GitHub**

**Цель работы**

Освоить основные навыки работы с облачными и распределенными системами контроля версий, получить навыки работы с инструментальными средствами, обеспечивающими командную работу над разработкой ПО.

**Задания для выполнения**

1. Зарегистрироваться на сайте github.com!
![](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.001.png)
2. Установить на компьютере программу Git
![](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.002.png)

3. Форкнуть данный репозиторий в свой аккаунт!
![](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.003.png)
4. Склонировать созданный удаленный репозиторий в директорию ~/git/test 
![](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.004.png)
5. На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием 
![](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.005.png)

6. Фиксируем скрипт в репозитории (делаем коммит) 

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.006.png)

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.007.png)

7. Обновляем удаленный репозиторий репозиторий (делаем пуш) 

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.008.png)

8. Через текстовый редактор добавить любую новую строку с комментарием 

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.009.png)

9. Сделать коммит 

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.010.png)

10. Внести синтаксическую ошибку в скрипт 
![](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.011.png)

11. Сделать коммит ошибочного скрипта 
![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.012.png)

12. Откатываем до последней рабочей версии 
![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.013.png)

13. Просмотреть историю коммитов 
![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.014.png)

14. Добавить несколько коммитов произвольного содержимого 

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.015.png)

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.016.png)

![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.017.png)

15. Создать пулл реквест в данный репозиторий 
![Изображение выглядит как текст Автоматически созданное описание](https://github.com/dvaisluk/0_git_basics/raw/master/images/Aspose.Words.1f887781-5bf5-486c-801f-fb0ff4f93cd1.018.png)

**Контрольные вопросы**

1. Зачем нужен облачный хостинг репозиториев?

Облачный хостинг репозиториев нужен для того, чтобы к репозиторию могли иметь доступ сразу несколько разработчиков вне зависимости от того, включена физическая машина с данными репозитория или нет

2. Какими основными функциями обладает сайт github.com?

С помощью сайта github.com можно загружать репозитории, клонировать, делать ответвления для тестирования, делиться репозиторием.

3. Как организовать командную работу над открытым проектом?

Из корневого репозитория разработчики независимо друг от друга могут делать ответвления в свой профиль и работать над определенной частью проекта, после чего отправить отредактированную копию репозитория для дальнейшего слияния/отладки.

