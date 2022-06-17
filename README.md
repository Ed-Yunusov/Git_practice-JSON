#### Git_practice-JSON
1. Создать внешний репозиторий c названием Git_practice-JSON 
    + открыть `https://github.com`. Залогиниться. Нажать кнопку `New`. 
    + в поле Repository name ввести Git_practice-JSON, выбрать Public и Add a README file. 
    + Нажать `Create repository`.

2. Клонировать репозиторий Git_practice-JSON на локальный компьютер
    + Нажать `Code`, выбрать HTTPS, скопировать ссылку на репозиторий 
    + `git clone https://github.com/Ed-Yunusov/Git_practice-JSON.git`
    + в терминале перейти в папку Git_practice-JSON (`cd Git_practice-JSON`), в конце адреса расположения отображается main

3. Внутри локального репозитория Git_practice-JSON создать файл “new.json”
    + `touch new.json`
    + `git status` - new.json отображается красным (изменения в файле не отслеживаются)

4. Добавить файл под гит
    + `git add new.json` 
    + `git status` - new.json отображается зеленым (изменения в файле отслеживаются)

5. Закоммитить файл
    + `git commit -m "new file"` - создает снимок текущего состояния файла с комментарием "new file"

6. Отправить файл на внешний GitHub репозиторий
    + `git push`

7) Отредактировать содержимое файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON
    + `vim new.json` 
    + `insert`
	```json
	{
		"full_name":"Yunusov Eduard Alexeevich",
		"age":33,
		"number_of_pets":1,
		"future_desired_salary":"2000$"
	}
	```
    + `Esc`
    + `:wq`

8. Отправить изменения на внешний репозиторий
    + `git commit -am "added info" && git push` - "&&" -вторая команда автоматически запускается после завершения первой команды

9. Создать файл preferences.json
    + `touch preferences.json`

10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить). Всё написать в формате JSON
    + `vim preferences.json` 
    + `insert`
	```json
	{
		"Favorite movie":"Lord of the Rings",
		"Favorite serial":"Friends",
		"Favorite food":"Pizza",
		"Favorite time of the year":"Spring and summer",
		"Country I would like to visit":"The Kingdom of Thailand"
	}
	```
    + `Esc`
    + `:wq`

11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
    + `vim skills.json`
    + `insert`
	```json
	{
	"skills":[
		"Software testing theory",
		"Client-server architecture",
		"HTTP Server Request Methods",
		"HTTP server Response codes",
		"Structures of HTTP requests and responses",
		"What is JSON, XML. Their structure",
		"API testing via Postman JS, API autotests",
		"Removing and reading logs from an external server",
		"Sniffing http web traffic through Charles and Fiddler",
		"Dev Tools of web browsers Google Chrome, FireFox",
		"VPN. How it works, why you need it, how to use it, tool options",
		"Mobile testing",
		"Feature of iOS, Android, guidelines",
		"Build iOS applications on Xcode",
		"Build Android applications on Android Studio",
		"ADB management of android devices",
		"Setting up proxy and vpn on iOS and Android",
		"Interception (sniffing) of mobile traffic through Charles and Fiddler on iOS and Android",
		"Command line (terminal) Linux copy, create, view, move files on servers without a graphical interface",
		"Basics of bash scripting, automation of routine tasks on the server",
		"Access to remote servers",
		"Basics of SQL Create, Delete, Drop, Insert Into, Select, From, Where, Join",
		"Postgres database installation, configuration and use",
		"Non-relational database Redis installation, configuration and use",
		"Load testing in Jmeter",
		"Scrum development methodology"
		]
	}
	```
    + `Esc`
    + `:wq`

12. Отправить сразу 2 файла на внешний репозиторий
    + `git add . ; git commit -m "adding two files to the rep" ; git push`

13. На веб интерфейсе создать файл bug_report.json
    + Войти в репозиторий Git_practice-JSON. Нажать кнопку `Add file`.
    + Выбрать `Create new file`. В поле Name your file ввести bug_report.json.

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit new file`.

14. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
    + Открыть файл bug_report.json, нажать на кнопку `Edit this file`.
    ```json
    {
     "ID":"1",
     "Title":"В разделе 'Помощь' не работает ссылка",
     "Project":"Сайт интернет-магазина HitechPlace",
     "STR":
     [
     "1. Открыть главную страницу (ссылка_на_сайт)",
     "2. Нажать на кнопку 'Помощь' в верхнем меню",
     "3. Нажать на кнопку 'Где можно получить больше информации?'",
     "4. Нажать на кнопку 'тут'"
     ],
     "Actual result":"Возникает ошибка 'OOPS! THAT PAGE CAN'T BE FOUND'",
     "Expected result":"Появляется страница с необходимой информацией",
     "Severity":"Major",
     "Priority":"High",
     "Status":"Open",
     "Attachments":"ссылка_на_картинку_с_багом",
     "Author":"Эдуард Юнусов"
    } 
    ```
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit changes`.

16. Синхронизировать внешний и локальный репозиторий Git_practice-JSON
    + `git pull`

#### Git_practice-XML
1. Создать внешний репозиторий c названием Git_practice-XML
    + открыть `https://github.com`. Залогиниться. Нажать кнопку `New`. 
    + в поле Repository name ввести Git_practice-XML, выбрать Public и Add a README file. 
    + Нажать `Create repository`.

2. Клонировать репозиторий Git_practice-XML на локальный компьютер
    + Нажать `Code`, выбрать HTTPS, скопировать ссылку на репозиторий 
    + `git clone https://github.com/Ed-Yunusov/Git_practice-XML.git`
    + в терминале перейти в папку Git_practice-XML(`cd Git_practice-XML`), в конце адреса расположения отображается main

3. Внутри локального Git_practice-XML создать файл “new.xml”
    + `touch new.xml`
    + `git status` - new.xml отображается красным (изменения в файле не отслеживаются)

4. Добавить файл под гит
    + `git add new.xml`
    + `git status` - new.xml отображается зеленым (изменения в файле отслеживаются)

5. Закоммитить файл
    + `git commit -m "new file"` - создает снимок текущего состояния файла с комментарием "new file"

6. Отправить файл на внешний GitHub репозиторий
    + `git push`

7. Отредактировать содержимое файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML
    + `vim new.xml`
    + `insert`
	```xml
	<information>
		<full_name>Yunusov Eduard Alexeevich</full_name>
		<age>33</age>
		<number_of_pets>1</number_of_pets>
		<future_desired_salary>2000$</future_desired_salary>
	</information>
	```
    + `Esc`
    + `:wq`

8. Отправить изменения на внешний репозиторий
    + `git commit -am "added info" && git push` - "&&" -вторая команда автоматически запускается после завершения первой команды

9. Создать файл preferences.xml
    + `touch preferences.xml`

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить). Всё написать в формате XML
	+ `vim preferences.xml` 
	+ `insert`
	```xml
	<myPreferences>
		<favorite_movie>Lord of the Rings</favorite_movie>
		<favorite_serial>Friends</favorite_serial>
		<favorite_food>Pizza</favorite_food>
		<favorite_time_of_the_year>Spring and summer</favorite_time_of_the_year>
		<country_I_would_like_to_visit>The Kingdom of Thailand</country_I_would_like_to_visit>
	</myPreferences>
	```
    + `Esc`
    + `:wq`

11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
      + `vim skills.xml` 
	+ `insert`
	```xml
	<skills>
		<one>Software testing theory</one>
		<two>Client-server architecture</two>
		<three>HTTP Server Request Methods</three>
		<four>HTTP server Response codes</four>
		<five>Structures of HTTP requests and responses</five>
		<six>What is JSON, XML. Their structure</six>
		<seven>API testing via Postman JS, API autotests</seven>
		<eight>Removing and reading logs from an external server</eight>
		<nine>Sniffing http web traffic through Charles and Fiddler</nine>
		<ten>Dev Tools of web browsers Google Chrome, FireFox</ten>
		<eleven>VPN. How it works, why you need it, how to use it, tool options</eleven>
		<twelve>Mobile testing</twelve>
		<thirteen>Feature of iOS, Android, guidelines</thirteen>
		<fourteen>Build iOS applications on Xcode</fourteen>
		<fifteen>Build Android applications on Android Studio</fifteen>
		<sixteen>ADB management of android devices</sixteen>
		<seventeen>Setting up proxy and vpn on iOS and Android</seventeen>
		<eighteen>Interception (sniffing) of mobile traffic through Charles and Fiddler on iOS and Android</eighteen>
		<nineteen>Command line (terminal) Linux copy, create, view, move files on servers without a graphical interface</nineteen>
		<twenty>Basics of bash scripting, automation of routine tasks on the server</twenty>
		<twentyOne>Access to remote servers</twentyOne>
		<twentyTwo>Basics of SQL Create, Delete, Drop, Insert Into, Select, From, Where, Join</twentyTwo>
		<twentyThree>Postgres database installation, configuration and use</twentyThree>
		<twentyFour>Non-relational database Redis installation, configuration and use</twentyFour>
		<twentyFive>Load testing in Jmeter</twentyFive>
		<twentySix>Scrum development methodology</twentySix>
        </skills>
	```
    + `Esc`
    + `:wq`

12. Отправить сразу 2 файла на внешний репозиторий
    + `git add . ; git commit -m "adding two files to the rep" ; git push`

13. На веб интерфейсе создать файл bug_report.xml
    + Войти в репозиторий Git_practice-XML. Нажать кнопку `Add file`.
    + Выбрать `Create new file`. В поле Name your file ввести bug_report.xml.

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit new file`.

14. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
    + Открыть файл bug_report.xml, нажать на кнопку `Edit this file`.
	```xml	
	<bug_report>
		<ID>1</ID>
		<Title>В разделе 'Помощь' не работает ссылка</Title>
		<Project>Сайт интернет-магазина HitechPlace</Project>
		<STR> 
		<Step1>Открыть главную страницу (ссылка_на_сайт)</Step1>
		<Step2>Нажать на кнопку 'Помощь' в верхнем меню</Step2>
		<Step3>Нажать на кнопку 'Где можно получить больше информации?</Step3>
		<Step4>Нажать на кнопку 'тут'</Step4>
		</STR>
		<Actual_result>Возникает ошибка 'OOPS! THAT PAGE CAN'T BE FOUND'</Actual_result>
		<Expected_result>Появляется страница с необходимой информацией</Expected_result>
		<Severity>Major</Severity>
		<Priority>High</Priority>
		<Status>Open</Status>
		<Attachments>ссылка_на_картинку_с_багом</Attachments>
		<Author>Эдуард Юнусов</Author>
	</bug_report>
	```

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit changes`.

16. Синхронизировать внешний и локальный репозиторий Git_practice-XML
    + `git pull`



#### Git_practice-TXT
1. Создать внешний репозиторий c названием Git_practice-TXT
    + открыть `https://github.com`. Залогиниться. Нажать кнопку `New`. 
    + в поле Repository name ввести Git_practice-TXT, выбрать Public и Add a README file. 
    + Нажать `Create repository`.

2. Клонировать репозиторий Git_practice-TXT на локальный компьютер
    + Нажать `Code`, выбрать HTTPS, скопировать ссылку на репозиторий 
    + `git clone https://github.com/Ed-Yunusov/Git_practice-TXT.git`
    + в терминале перейти в папку Git_practice-TXT(`cd Git_practice-TXT`), в конце адреса расположения отображается main

3. Внутри локального Git_practice-TXT создать файл “new.txt”
    + `touch new.txt`
    + `git status` - new.txt отображается красным (изменения в файле не отслеживаются)

4. Добавить файл под гит
    + `git add new.txt`
    + `git status` - new.txt отображается зеленым (изменения в файле отслеживаются)

5. Закоммитить файл
    + `git commit -m "new file"` - создает снимок текущего состояния файла с комментарием "new file"

6. Отправить файл на внешний GitHub репозиторий
    + `git push`

7. Отредактировать содержимое файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT
    + `vim new.txt` 
    + `insert`
        + Full name: Yunusov Eduard Alexeevich
        + Age: 33
        + Number of pets: 1
        + Future desired salary: 2000$

    + `Esc`
    + `:wq`

8. Отправить изменения на внешний репозиторий
    + `git commit -am "added info" && git push` - "&&" -вторая команда автоматически запускается после завершения первой команды

9. Создать файл preferences.txt
    + `touch preferences.txt`

10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить). Всё написать в формате TXT
    + `vim new.txt` 
    + `insert`
        + Favorite movie: Lord of the Rings
        + Favorite serial: Friends
        + Favorite food: Pizza
        + Favorite time of the year: Spring and summer
        + Country I would like to visit: The Kingdom of Thailand

    + `Esc`
    + `:wq`

11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
    + `vim new.txt` 
    + `insert`
    + skills:
        + Software testing theory
        + Client-server architecture
        + HTTP Server Request Methods
        + HTTP server Response codes
        + Structures of HTTP requests and responses
        + What is JSON, XML. Their structure
        + API testing via Postman JS, API autotests
        + Removing and reading logs from an external server
        + Sniffing http web traffic through Charles and Fiddler
        + Dev Tools of web browsers Google Chrome, FireFox
        + VPN. How it works, why you need it, how to use it, tool options
        + Mobile testing
        + Feature of iOS, Android, guidelines
        + Build iOS applications on Xcode
        + Build Android applications on Android Studio
        + ADB management of android devices
        + Setting up proxy and vpn on iOS and Android
        + Interception (sniffing) of mobile traffic through Charles and Fiddler on iOS and Android
        + Command line (terminal) Linux copy, create, view, move files on servers without a graphical interface
        + Basics of bash scripting, automation of routine tasks on the server
        + Access to remote servers
        + Basics of SQL Create, Delete, Drop, Insert Into, Select, From, Where, Join
        + Postgres database installation, configuration and use
        + Non-relational database Redis installation, configuration and use
        + Load testing in Jmeter
        + Scrum development methodology

    + `Enter`
    + `Ctrl + D`

12. Отправить сразу 2 файла на внешний репозиторий
    + `git add . ; git commit -m "adding two files to the rep" ; git push`

13. На веб интерфейсе создать файл bug_report.txt
    + Войти в репозиторий Git_practice-TXT. Нажать кнопку `Add file`.
    + Выбрать `Create new file`. В поле Name your file ввести bug_report.txt.

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit new file`.

15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
    + Открыть файл bug_report.txt, нажать на кнопку `Edit this file`.
    	+ ID: 1
    	+ Title: В разделе 'Помощь' не работает ссылка
    	+ Project: Сайт интернет-магазина HitechPlace
    	+ STR:
    	+ 1.Открыть главную страницу (ссылка_на_сайт)
    	+ 2.Нажать на кнопку 'Помощь' в верхнем меню
    	+ 3.Нажать на кнопку 'Где можно получить больше информации?'
    	+ 4.Нажать на кнопку 'тут'
    	+ Actual result: Возникает ошибка 'OOPS! THAT PAGE CAN'T BE FOUND'
    	+ Expected result: Появляется страница с необходимой информацией
    	+ Severity: Major
    	+ Priority: High
    	+ Status: Open
    	+ Attachments: ссылка_на_картинку_с_багом
    	+ Author: Эдуард Юнусов

16. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit changes`.

17. Синхронизировать внешний и локальный репозиторий TXT
    + `git pull`

