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
1.ID
2.Title
3.STR
4.Enviroment
5.Actual result
6.Expected result
7. Severity
8.Priority
Ctrl + c
```
#### 4. Запушить структуру багрепорта на внешний репозиторий
```
-git add .
-git commit -m "add new txt"
-git push
```
#### 5. Вмержить ветку Bug reports в Main
```
-git checkout main
-git merge Bug_Reports
```
#### 6. Запушить main на внешний репозиторий.
```
git push
```
#### 7.В ветке CheckLists набросать структуру чек листа
```- git checkout CheckLists
-  cat > CLstructure.txt
-Build
-Environment
-Test date
-Tester
-Test type
-Checking (names of checks)
-Result
Ctrl + c
```
#### 8. Запушить структуру на внешний репозиторий
```
-git add .
-git commit -m "add CheckList_structure.txt"
-git push
```
#### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
-Зайти в ветку main
-Нажать Compare & pull request
-Выбирать  compare: CheckLists
-Нажать Create pull request
-Нажать  merge pull request
-Нажать confirm merg
```
#### 10. Синхронизировать Внешнюю и Локальную ветки Main
```
-git checkout main
-git pull
```

