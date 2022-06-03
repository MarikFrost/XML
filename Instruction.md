# XML
Training XML
 21. Создать внешний репозиторий c названием XML.
	- donr 
 22. Клонировать репозиторий XML на локальный компьютер.
 	- git clone

 23. Внутри локального XML создать файл “new.xml”.
 	- touch new.xml

 24. Добавить файл под гит.
 	- git add new.xml

 25. Закоммитить файл.
 	- git commit new.xml -m "first xml commit"

 26. Отправить файл на внешний GitHub репозиторий.
 	- git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 	- vim new.xml

 28. Отправить изменения на внешний репозиторий.
 	- git commit -am "personal data"
	- git push

 29. Создать файл preferences.xml
 	- touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 	- vim preferences.xml

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 	- touch skills.xml
	- vim skills.xml

 32. Сделать коммит в одну строку.
 	- git add preferences.xml skills.xml | git commit -m "favorite and skill commit"

 33. Отправить сразу 2 файла на внешний репозиторий.
 	- git push

 34. На веб интерфейсе создать файл bug_report.xml.
 	- done

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 	- done

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 	- done

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 	- done

 38. Синхронизировать внешний и локальный репозиторий XML
	- git pull https://github.com/MarikFrost/XML.git
