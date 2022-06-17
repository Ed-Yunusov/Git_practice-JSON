#### Git_practice-JSON
1. Создать внешний репозиторий c названием Git_practice-JSON 
    + открыть `https://github.com`. Залогиниться. Нажать кнопку `New`. 
    + в поле Repository name ввести Git_practice-JSON, выбрать Public и Add a README file. 
    + Нажать `Create repository`.

2. Клонировать репозиторий Git_practice-JSON на локальный компьютер
    + Нажать `Code`, выбрать HTTPS, скопировать ссылку на репозиторий, в Gitbash зайти в папку (в которой будет размещен репозиторий), 
    + `git clone https://github.com/Ed-Yunusov/Git_practice-JSON.git`
    + в терминале перейти в папку Git_practice-JSON (`cd Git_practice-JSON`), в конце адреса расположения отображается main

3. Внутри локального репозитория Git_practice-JSON создать файл “new.json”
    + `touch new.json`
    + `git status` - new.json отображается красным (изменения в файле не отслеживаются)

4. Добавить файл под гит
    + `git add new.json` 
    + `git status` - new.json отображается зеленым (изменения в файле отслеживаются)

5. Закоммитить файл
    + `git commit -m "new file"` - создает снимок текущего состояния файла с комментарием new file

6. Отправить файл на внешний GitHub репозиторий
    + `git push`

7) Отредактировать содержимое файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON
    + `vim new.json` 
    + `insert`
	```json
	{
		"full_name":"Yunusov Eduard Alexeevich",
		"age":33,
		"number_of_pets": 1,
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
		"Favorite movie": "Lord of the Rings",
		"Favorite serial": "Friends",
		"Favorite food": "Pizza",
		"Favorite time of the year": "Spring and summer",
		"Country I would like to visit": "The Kingdom of Thailand"
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
		"client-server architecture",
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

#### XML
1. Создать внешний репозиторий c названием XML
    + открыть `https://github.com`. Залогиниться. Нажать кнопку New. 
    + в поле Repository name ввести XML, выбрать Public и Add a README file. 
    + Нажать `Create repository`.

2. Клонировать репозиторий XML на локальный компьютер
    + Нажать `Code`, выбрать HTTPS, скопировать ссылку на репозиторий, в gitbash зайти в папку(в которой будет размещен репозиторий), 
    + `git clone https://github.com/lvnnew/XML.git`
    + в терминале перейти в папку XML(cd XML), в конце адреса расположения отображается main

3. Внутри локального XML создать файл “new.xml”
    + `touch new.xml`
    + `git status` - new.xml отображается красным (изменения в файле не отслеживаются)

4. Добавить файл под гит
    + `git add new.xml`
    + `git status` - new.xml отображается зеленым (изменения в файле отслеживаются)

5. Закоммитить файл
    + `git commit -m "add new.xml"` - создает снимок текущего состояния файла с комментарием add new.json

6. Отправить файл на внешний GitHub репозиторий
    + `git push`

7. Отредактировать содержимое файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML
    + `vim new.xml`
    + `insert`
	```xml
	<aboutme>
		<fullName>Vladimir Nikolaevich Leshenko</fullname>
		<age>30</age>
		<pets>
			<number>1</number>
			<kindOfPet>cat</kindofpet>
			<name>Peppa</name>
		<pets>
		<desiredSalary>400$</desiredSalary>
	</aboutme>
	```
    + `Esc`
    + `:wq`

8. Отправить изменения на внешний репозиторий
    + `git add new.xml ; git commit -m "modified new.xml" ; git push` - в качестве склейки используется ;

9. Создать файл preferences.xml
    + `cat > preferences.xml`

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
	```xml
	<myPreferences>
		<Movie>Green Mile<Movie>
		<TvSeries>Good Doctor</TvSeries>
		<Food>Pizza</Food>
		<Season>Summer</Season>
		<Country>Montenegro</Country>
	</myPreferences>
	```
    + `Enter`
    + `Ctrl + D`

11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
    + `cat > skills.xml`
	```xml
	<skills>
		<one>software testing theory</one>
		<two>client-server architecture</two>
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
		<twentySeven>Python. Learning the basics. Building a client-server application</twentySeven>
        </skills>
	```
    + `Enter`
    + `Ctrl + D`

12. Отправить сразу 2 файла на внешний репозиторий
    + `git add . ; git commit -m "add preferences.xml and skills.xml" ; git push`

13. На веб интерфейсе создать файл bug_report.xml
    + Войти в репозиторий XML. Нажать кнопку `Add file`.
    + Выбрать `Create new file`. В поле Name your file ввести bug_report.xml.

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit new file`.

14. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
    + Открыть файл bug_report.json Выбрать редактирование. Ввести текст
	```xml	
	<bugReport>
		<summary>[9] button it always is disable on panel of calculator however digits 9 can enter from keyboard</summary>
		<descriprion>When calculator is run button always is disable on panel of calculator however digits 9 can enter from keyboard. It is unfriendly behavior for users</descriprion>
		<actualResult>[9] button is disable</actualResult>
		<expectedResult>[9] button is enable</expectedResult>
		<reproducedOn>Win 7</reproducedOn>
		<reproducibility>always</reproducibility>
		<attachment>https://yadi.sk/i/4IBhTrDF3VxXhR</attachment>
		<stepsToReproduce>
			<one>Run calc.exe</one>
			<two>Click [9] button</two>
		<stepsToReproduce>
		<severity>minor</severity>
		<priority>low</priority>
	</bugReport>
	```

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit changes`.

16. Синхронизировать внешний и локальный репозиторий XML
    + `git pull`



#### TXT
1. Создать внешний репозиторий c названием TXT
    + открыть `https://github.com`. Залогиниться. Нажать кнопку New. 
    + в поле Repository name ввести TXT, выбрать Public и Add a README file. 
    + Нажать `Create repository`.

2. Клонировать репозиторий TXT на локальный компьютер
    + Нажать `Code`, выбрать HTTPS, скопировать ссылку на репозиторий, в gitbash зайти в папку(в которой будет размещен репозиторий), 
    + `git clone https://github.com/lvnnew/TXT.git`
    + в терминале перейти в папку TXT(cd TXT), в конце адреса расположения отображается main

3. Внутри локального TXT создать файл “new.txt”
    + `touch new.txt`
    + `git status` - new.txt отображается красным (изменения в файле не отслеживаются)

4. Добавить файл под гит
    + `git add new.txt`
    + `git status` - new.txt отображается зеленым (изменения в файле отслеживаются)

5. Закоммитить файл
    + `git commit -m "add new.txt"` - создает снимок текущего состояния файла с комментарием add new.txt

6. Отправить файл на внешний GitHub репозиторий
    + `git push`

7. Отредактировать содержимое файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT
    + `vim new.txt` 
    + `insert`

        + full_name: Vladimir Nikolaevich Leshenko
        + age:30,
        + pets: 1 cat Peppa
        + desired_Salary: 400$

    + `Esc`
    + `:wq`

8. Отправить изменения на внешний репозиторий
    + `git add new.txt ; git commit -m "modified new.txt" ; git push` - в качестве склейки используется ;

9. Создать файл preferences.txt
    + `cat > preferences.txt`

10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT

    + favorite movie : Green Mile
	+ favorite series: Good Doctor
	+ favorite food: Pizza
	+ favorite season: Summer
    + country you would like to visit: Montenegro

    + `Enter`
    + `Ctrl + D`

11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
    + `cat > skills.txt`

    + skills:
        + software testing theory
        + client-server architecture
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
        + Python. Learning the basics. Building a client-server application

    + `Enter`
    + `Ctrl + D`

12. Отправить сразу 2 файла на внешний репозиторий
    + `git add . ; git commit -m "add preferences.txt and skills.txt" ; git push`

13. На веб интерфейсе создать файл bug_report.txt
    + Войти в репозиторий TXT. Нажать кнопку `Add file`.
    + Выбрать `Create new file`. В поле Name your file ввести bug_report.txt.

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit new file`.

15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
    + Открыть файл bug_report.txt Выбрать редактирование. Ввести текст
	     
    + Summary:[9] button it always is disable on panel of calculator however digits 9 can enter from keyboard
    + Descriprion: When calculator is run button always is disable on panel of calculator however digits 9 can enter from keyboard. It is unfriendly behavior for users
    + Actual result: [9] button is disable
    + Expected result: [9] button is enable
    + Reproduced on: Win 7
    + Reproducibility: always
    + For more details see attachment: `https://yadi.sk/i/4IBhTrDF3VxXhR`
    + Steps to reproduce:    
            + 1: Run calc.exe
            + 2: Click [9] button
    + Severity: minor
    + Priority: low

16. Сделать Commit changes (сохранить) изменения на веб интерфейсе
    + Нажать кнопку `Commit changes`.

17. Синхронизировать внешний и локальный репозиторий TXT
    + `git pull`

