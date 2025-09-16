## Вуйко Ярослава

### Описание проекта:
Простой HTTP-сервер на Go с базовыми эндпоинтами для тестирования и демонстрации.

### Команда запуска:
```
go run ./cmd/server
```

### Сборка и запуск бинарного файла
```
go build -o helloapi.exe ./cmd/server
.\helloapi.exe
```

### Запросы:
- http://localhost:8081/hello
- http://localhost:8081/user
- http://localhost:8081/health

### Структура проекта:
```
.
├── cmd/
│   └── server/
│       └── main.go 
├── go.mod
├── go.sum
└── README.md
```

По умолчанию порт 8080, можно изменить с помощью переменной окружения $env:APP_PORT

**go version / git version**

<img width="537" height="129" alt="image" src="https://github.com/user-attachments/assets/15e719e6-5b27-4189-a08e-119762851842" />

**Запрос http://localhost:8081/hello**

<img width="1158" height="438" alt="image" src="https://github.com/user-attachments/assets/7e85ec97-1446-4b6a-a4ff-bbc91f9fed9b" />

**Запрос http://localhost:8081/user**

<img width="1103" height="497" alt="image" src="https://github.com/user-attachments/assets/449b7892-5638-4b73-93c1-00c159486357" />

**Запрос http://localhost:8081/health**

<img width="1103" height="495" alt="image" src="https://github.com/user-attachments/assets/e21f8c54-7350-4d3b-9ad4-f19211000b6c" />
