# XML

1. Создать внешний репозиторий c названием XML.
>    Go to home page --> click on the button "New"(on the upper left) --> enter name "XML" --> at the bottom click "Create repository"    
2. Клонировать репозиторий XML на локальный компьютер. 
>    git clone https://github.com/vladsoltys/XML.git --> cd XML
3. Внутри локального JSON создать файл “new.xml”. 
>    touch new.xml
4. Добавить файл под гит.
>    git add new.xml
5. Закоммитить файл. 
>    git commit -m "add new xml file"
6. Отправить файл на внешний GitHub репозиторий. 
>    git push
7. Отредактировать содержание файла “new.xml” - написать информацию о себе 
     (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). 
     Всё написать в формате XML. 
>    - vim new.xml  
>    - i ***(insert)***
     
      <?xml version="1.0" encoding="UTF-8" ?>
       <root>
           <Full_name>Soltys Vladyslav Igorevich</Full_name>
           <Age>24</Age>
           <Number_of_pets>2</Number_of_pets>
           <Future_desired_salary>800-1000$</Future_desired_salary>
       </root>
                                                                                
>    - esc :wq

 8. Отправить изменения на внешний репозиторий. 
>    - git commit -am "change file new.xml"
     - git push

 9. Создать файл preferences.xml 
>    vim preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях 
     (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) 
     в формате XML.
>    - i ***(insert)***

        <?xml version="1.0" encoding="UTF-8" ?>
        <root>
            <Favourite_film>Contact</Favourite_film>
            <Favourite_series>Breaking Bad</Favourite_series>
            <Favorite_food>Mother's potato pancakes with cheese</Favorite_food>
            <Favorite_time_of_year>Summer</Favorite_time_of_year>
            <Country_you_would_like_to_visit>Cuba</Country_you_would_like_to_visit>
        </root>
        
>    - esc :wq

 11. Создать файл skills.xml,
     добавить информацию о скиллах которые будут изучены на курсе в формате XML
>    - vim skills.xml
>    - i ***(insert)***
     
        <?xml version="1.0" encoding="UTF-8" ?>
        <root>
            <skills_to_be_learned_on_the_course_1>Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC</skills_to_be_learned_on_the_course_1>
            <skills_to_be_learned_on_the_course_2>What is a client-server architecture</skills_to_be_learned_on_the_course_2>
            <skills_to_be_learned_on_the_course_3>HTTP Methods of requests to the server</skills_to_be_learned_on_the_course_3>
            <skills_to_be_learned_on_the_course_4>HTTP server response codes</skills_to_be_learned_on_the_course_4>
            <skills_to_be_learned_on_the_course_5>Structures of HTTP requests and responses</skills_to_be_learned_on_the_course_5>
            <skills_to_be_learned_on_the_course_6>What is JSON, XML. Their structure</skills_to_be_learned_on_the_course_6>
            <skills_to_be_learned_on_the_course_7>API testing via Postman (JS, API autotests)</skills_to_be_learned_on_the_course_7>
            <skills_to_be_learned_on_the_course_8>Removing and reading logs from an external server</skills_to_be_learned_on_the_course_8>
            <skills_to_be_learned_on_the_course_9>Sniffing http web traffic via Charles and Fiddler</skills_to_be_learned_on_the_course_9>
            <skills_to_be_learned_on_the_course_10>Dev Tools of web browsers (Google Chrome, FireFox)</skills_to_be_learned_on_the_course_10>
            <skills_to_be_learned_on_the_course_11>VPN. (How it works, why you need it, how to use it, tool options)</skills_to_be_learned_on_the_course_11>
            <skills_to_be_learned_on_the_course_12>Mobile testing</skills_to_be_learned_on_the_course_12>
            <skills_to_be_learned_on_the_course_13>Feature iOS, Android, guidelines</skills_to_be_learned_on_the_course_13>
            <skills_to_be_learned_on_the_course_14>Building iOS applications on XCode</skills_to_be_learned_on_the_course_14>
            <skills_to_be_learned_on_the_course_15>Building Android applications on Android Studio</skills_to_be_learned_on_the_course_15>
            <skills_to_be_learned_on_the_course_16>ADB (android device management)</skills_to_be_learned_on_the_course_16>
            <skills_to_be_learned_on_the_course_17>Setting up proxy and vpn on iOS and Android</skills_to_be_learned_on_the_course_17>
            <skills_to_be_learned_on_the_course_18>Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android</skills_to_be_learned_on_the_course_18>
            <skills_to_be_learned_on_the_course_19>Command line (terminal) Linux (copying, creating, viewing, moving files on servers without a graphical interface)</skills_to_be_learned_on_the_course_19>
            <skills_to_be_learned_on_the_course_20>Basics of bash scripting, automation of routine tasks on the server</skills_to_be_learned_on_the_course_20>
            <skills_to_be_learned_on_the_course_21>Access to remote servers</skills_to_be_learned_on_the_course_21>
            <skills_to_be_learned_on_the_course_22>SQL basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</skills_to_be_learned_on_the_course_22>
            <skills_to_be_learned_on_the_course_23>Postgres database (installation, configuration and use)</skills_to_be_learned_on_the_course_23>
            <skills_to_be_learned_on_the_course_24>Non-relational database Redis (installation, configuration and use)</skills_to_be_learned_on_the_course_24>
            <skills_to_be_learned_on_the_course_25>Load testing in Jmeter</skills_to_be_learned_on_the_course_25>
            <skills_to_be_learned_on_the_course_26>Scrum development methodology</skills_to_be_learned_on_the_course_26>
            <skills_to_be_learned_on_the_course_27>Python. (Learning the basics. Creating a client-server application)</skills_to_be_learned_on_the_course_27>
        </root>

>    - esc :wq
 12. Сделать коммит в одну строку. 
>    git add . ; git commit -m "add 2 new xml files" __OR__ git commit -am "add 2 new xml files"
 14. Отправить сразу 2 файла на внешний репозиторий.  
>    git push

 13. На веб интерфейсе создать файл bug_report.xml. 
>    - click on the button "add file" 
>    - click on the button "create new file" 
>    - in the field "Name your file..." enter the name of the file "bug_report.xml"

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>    at the bottom click "Commite new file"
 15. На веб интерфейсе модифицировать файл bug_report.xml, 
     добавить баг репорт в формате XML.
>    - click on file "bug_report.xml"
>    - click on the button "Edit this file" in the lower right
>    - copy description of the bug
   
        <?xml version="1.0" encoding="UTF-8" ?>
        <root>
            <Bug_id>26</Bug_id>
            <Summary>Loggin Page. The button 'Sigh in' not responding after clicking on it</Summary>
            <STR>
                <step_1>Open the login page</step_1>
                <step_2>Enter username and password</step_2>
                <step_3>Click on the button 'Sigh in'</step_3>
            </STR>
            <Result>The button 'Sigh in' not responding after clicking on it</Result>
            <Expected_result>After clicking the button, the user page opens</Expected_result>
            <Severity>Major</Severity>
            <Priority>High</Priority>
            <Enviroment>
                <OS>Windows 10 Pro.64-разрядная операционная система, процессор x64</OS>
                <Browser>Google Chrome v.98.0.4758.102 (Розробка) (64-розрядна версія)</Browser>
            </Enviroment>
        </root>


 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
>    at the bottom click "Commite new file"
 17. Синхронизировать внешний и локальный репозиторий XML
>    git pull
