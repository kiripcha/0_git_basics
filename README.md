<!----- Conversion time: 1.115 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Wed Sep 18 2019 01:01:48 GMT-0700 (PDT)
* Source doc: https://docs.google.com/open?id=1sIorEva0JHPGjUlZBihoiGIootksj8HqQUjW8Vota0c
----->


## 3. Работа с удаленными репозиториями и GitHub


### Цель работы

Освоить основные навыки работы с облачными и распределенными системами контроля версий, получить навыки работы с инструментальными средствами, обеспечивающими командную работу над разработкой ПО.


### Задания для выполнения



1. Зарегистрироваться на сайте github.com
2. Установить на компьютере программу Git
3. Форкнуть данный репозиторий в свой аккаунт
![image](https://user-images.githubusercontent.com/70681104/140422291-1994d77d-386b-4b04-a6dc-e115e528a7de.png)

4. Склонировать созданный удаленный репозиторий в директорию ~/git/test
![image](https://user-images.githubusercontent.com/70681104/140423666-dae4ab78-b643-4b67-8967-5820190d9658.png)

5. На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием
![image](https://user-images.githubusercontent.com/70681104/140427296-10555d08-0ada-484a-8e07-b137ad212df4.png)

6. Фиксируем скрипт в репозитории (делаем коммит)
![image](https://user-images.githubusercontent.com/70681104/140426557-976b93ba-6b48-46f9-84df-8889c23cf6c2.png)

![image](https://user-images.githubusercontent.com/70681104/140427490-cae6318a-38d0-4b6f-bd98-40d221a6be5b.png)

7. Обновляем удаленный репозиторий репозиторий (делаем пуш)
![image](https://user-images.githubusercontent.com/70681104/140428280-ea952c45-9016-4da9-ba1c-ceaa08cb7891.png)

8. Через текстовый редактор добавить любую новую строку с комментарием
![image](https://user-images.githubusercontent.com/70681104/140428407-01a28fc2-43bd-4f58-8203-d105cd429b2a.png)

9. Сделать коммит
![image](https://user-images.githubusercontent.com/70681104/140428542-6361943b-ecf5-447a-a530-ecc7d6037910.png)

10. Вности синтаксическую ошибку в скрипт
![image](https://user-images.githubusercontent.com/70681104/140428687-162fcd4a-1527-41cd-a0a0-c05a91b37408.png)

11. Сделать коммит ошибочного скрипта
![image](https://user-images.githubusercontent.com/70681104/140428832-2bfd26fe-152a-4245-a235-836c39906d9e.png)

12. Откатываем до последней рабочей версии
![image](https://user-images.githubusercontent.com/70681104/140429237-5cfa83ac-ec52-4d45-9a78-ed64fd7ffc25.png)

![image](https://user-images.githubusercontent.com/70681104/140429471-1fa314bf-d0f4-424f-9e51-13f88a31df4f.png)

13. Просмотреть историю коммитов
![image](https://user-images.githubusercontent.com/70681104/140429560-aba5d422-c974-4f1c-9e42-4d44bb0549a6.png)

14. Добавить несколько коммитов произвольного содержимого
15. Создать пулл реквест в данный репозиторий


### Контрольные вопросы



1. Зачем нужен облачный хостинг репозиториев?
2. Какими основными функциями обладает сайт github.com?
3. Как организовать командную работу над открытым проектом?


### Дополнительные задания



1. Дополнительно оценивается, если студент продемонстрирует работу с ветками в процессе написания более-сложного программного проекта (не менее трех файлов, двух веток, десяти коммитов, как минимум одно объединение).
2. Дополнительно оценивается демонстрация командной работы. Для этого нужно склонировать репозиторий другому члену команды и коммитить от своего имени. При отправке истории на удаленный сервер (push) на сайте будет отображаться общая история. При скачивании истории с сервера (pull) общая история будет отображаться на локальном компьютере.
3. Настройте работу с git вашей интегрированной среды разработки по выбору. Для работы с python рекомендуется использовать PyCharm. Выполните задания лабораторной работы в IDE используя встроенные средства работы с системами контроля версий.

<!-- Docs to Markdown version 1.0β17 -->
