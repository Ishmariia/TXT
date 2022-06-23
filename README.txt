1. Создать внешний репозиторий c названием TXT.
В GitHub нажать справа кнопку New > в названии Repository написать название ТХТ >
вибрать пункт Public > поставить галочку рядом с Добавить файл README. Внизу нажать кнопку Создать репозиторий

 2. Клонировать репозиторий TXT на локальный компьютер.
https://github.com/Ishmariia/TXT.git
 3. Внутри локального TXT создать файл “new.txt”.
touch new.txt
 4. Добавить файл под гит.
git add .
 5. Закоммитить файл.
git commit -m "new file.txt"
 6. Отправить файл на внешний GitHub репозиторий.
git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
vim new.txt
Full name: Ishchenko Maria Viktorovna
I'm 28 years old
I don't have any animals, but I want a cat and a dog.
Desired salary of manual tester - 700$ - 1000$
 8. Отправить изменения на внешний репозиторий.
git add .
git commit -m "change in new file txt"
git push
 9. Создать файл preferences.txt
touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
vim preferences.txt 
Favorite movie: 1 + 1,
Favorite TV series: Friends,
Favorite food: pasta,
Favorite time of year: spring,
Сountry I want to visit: Spain.
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
cat >> sklls.txt
 12. Сделать коммит в одну строку.
git add .
git commit - m "new file sklls.txt & preferences.txt"
 13. Отправить сразу 2 файла на внешний репозиторий.
git push
 14. На веб интерфейсе создать файл bug_report.txt.
В репозитории GitHub нажать на кнопку "add file"> выбрать create new file > создать bug_report.txt
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сохранить в  github
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
ID 696
     Title: Parameters of the "Send e-mail" button, do not send data to e-mail when the data is entered correctly
 
      Severity: Major
      Priority: Medium
      Environment: 1)Xiaomi mi 9 Lite,  Android 10
		      		     
      Precondition: Installed app on the device
      STR:  
         1. Open the APP
         2.Fill in the field with the data to send 
         3. Tap “Send Email” button
                 
     AR: App return different links not related to sending email
     ER: App return  links related to sending emai
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Сохранить в  github
 18. Синхронизировать внешний и локальный репозиторий TXT
git pull


JSON
 4. Создать внешний репозиторий c названием JSON.
В GitHub нажать справа кнопку New > в названии Repository написать название JSON >
вибрать пункт Public > поставить галочку рядом с Добавить файл README. Внизу нажать кнопку Создать репозиторий
 5. Клонировать репозиторий JSON на локальный компьютер. (В репозитории в правом верхнем углу нажать кнопку "Code" скопировать ссылку HTTPS>в рабочей папке открыть GitBash Here и вставит в терминал>нажать "Enter")  
git clone https://github.com/Ishmariia/JSON.git

 6. Внутри локального JSON создать файл “new.json”.
touch new.json
 7. Добавить файл под гит.

git add new.json
 8. Закоммитить файл.
git commit -m "add new.json file"
 9. Отправить файл на внешний GitHub репозиторий.
git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 vim new.json
{
