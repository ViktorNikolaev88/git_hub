#### 1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag reports
- SQL
- Charles
- Mobile testing
```
git branch Postman 
git branch Jmeter
git branch CheckLists
git branch Bug_reports
git branch SQL
git branch Charles
git branch Mobile_testing
```
#### 2.  Запушить все ветки на внешний репозиторий
```
git push -u origin Bug_reports Charles CheckLists Jmeter Mobile_testing Postman SQL
```
#### 3. В ветке Bag reports сделать текстовый документ со структурой баг репорта
```
- git checkout Bug_reports
- cat > BRstructure.txt
```
#### 4. Add changes to indexed files section
```
git add .
```
#### 5. Commit the file
```bash
git commit -m "commit message"
```
#### 6. Push the file to the external GitHub repository
```
git push
```
#### 7. Edit the content of the file 'new.xml' - write information about yourself (name, age, number of pets, future desired salary). Everything is written in xml format
```xml
<?xml version="1.0" encoding="UTF-8"?>
<student_1>
  <name>Anna</name>
  <surname>Gvozdeva</surname>
  <age>31</age>
  <pets>0</pets>
  <desired_salary>100000$</desired_salary>
</student_1>
```
#### 8. Push changes the an external repository
```bash
git add .
git commit -m "commit message"
git push
```
#### 9. Create a file 'preferences.json'
```bash
cat > preferences.xml
```
#### 10. In the file 'preferences.xml', add information about your preferences (favorite movie, favorite TVshow, favorite food, favorite season, country you would like to visit). In xml format
```xml
<?xml version="1.0" encoding="UTF-8"?>
<student_1_hobbies>
  <fav_movie>Midnight in Paris</fav_moviee>
  <fav_TVshow>The Sopranos</fav_TV_show>
  <fav_food>Italian cuisine</fav_food>
  <fav_season>Spring</fav_season>
  <country_to_visit>China</country_to_visit>
</student_1_hobbies>
```
#### 11. Create a file 'skills.xml' and add information about the skills that will be studied in the course. In xml format
```xml
 <?xml version="1.0" encoding="UTF-8"?>
 <my_future_skills>
    <skill_1>QA_Theory</skill_1>
    <skill_2>HTTP</skill_2>
    <skill_3>GIT</skill_3>
    <skill_4>Postman</skill_4>
    <skill_5>Charles</skill_5>
    <skill_6>DevTools<skill_6>
    <skill_7>VPN</skill_7>
    <skill_8>Android_Studio</skill_8>
    <skill_9>Xcode</skill_9>
    <skill_10>Terminal</skill_10>
    <skill_11>SQL</skill_11>
 </my_future_skills>"
```
#### 12. Send two files at once to the external repository 
```bash
git add .
git commit -m "commit message"
git push
```
#### 13. On the web interface, create a file 'bug_report.xml'
```
➡️ Add file ➡️ Create new file
```
#### 14. Press 'Commit changes', save changes on the web interface
```
➡️ Commit new file
```
#### 15. On the web interface, modify the file 'bug_report.xml' and add file. In xml format
```xml
<bug_report_01>
  <ID>01</ID>
  <Title>No notification, in the authorization form, about the successful registration of a new user</Title>
  <STR>
      <step_1>Go to the main page of the site (link)</step_1>
		  <step_2>Enter data in the  \"Login\" field</step_2>
		  <step_3>Enter data in the \"Password\" field</step_3>
		  <step_4>Press \"Register\"</step_4>
  </STR>
  <Environment>
		  <OS>iOS 16.2 iPhone 12 Pro</OS>
		  <Browser>Safari 16.2</Browser>
	</Environment>
  <Actual result>A message appears, about successful registration</Actual result>
	<Expected result>A user has no understanding of the registration result</Expected result>
	<Severity>Minor</Severity>
	<Priority>Low</Priority>
	<Attachments>Link to the image or video with the bug</Attachments>
</bug_report_01>
```
#### 16. Press 'Commit changes' and save changes on the web interface
```
➡️ Commit changes 
```
#### 17. Synchronize the external and the local 'xml' repository
```bash
git pull
```
