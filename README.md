# ЭФМО-01-25 Буров М.А. ПР1

# Описание проекта
Данный проект предназначен для пробного развертывания сервера на Go.

# Требования к проекту
* Go 1.25+
* Git

# Версия Go
<img width="358" height="90" alt="image" src="https://github.com/user-attachments/assets/02135d6c-bdc0-4184-b5bb-3c09eecd464a" />

# Сборка
Для сборки проекта необходимо выполнить команду из директории helloapi:
```
go build -o executableFileName.exe ./cmd/server
```
# Запуск
Для запуска без компиляции выполняется команда из директории helloapi:
```
go run ./cmd/server
```
Для запуска скомпилированного файла выполняется команда из директории helloapi:
```
.\executableFileName.exe
```
# Проверка работоспоcобности
Для проверки работоспособности необходимо обратиться к разворачиваему API с помощью:
```
curl http://localhost:8080/hello
curl http://localhost:8080/user
```
При обращению по первому адресу результат должен быть такой:
<img width="763" height="226" alt="image" src="https://github.com/user-attachments/assets/44d36a45-c795-4022-8309-f961f2252eeb" />

При обращении по второму адресу результат должен быть аналогичный:
<img width="763" height="226" alt="image" src="https://github.com/user-attachments/assets/0076f257-5f57-4f81-9f23-5e22dc7dab30" />

# Структура проекта
Дерево структуры проекта: 
<img width="488" height="249" alt="image" src="https://github.com/user-attachments/assets/4a6eef36-0ab3-4888-98f2-4430fe687669" />
