
# API Documentation

### Метод: GET (/api)

#### Ответ:

##### Успешный ответ (200 OK)
``` json {
  "status": "ok",
  "time": "2025-03-30 11:48:09"
```

### Метод: POST (/api/process_audio)

#### Параметры запроса:
- **file**: (обязательный) Файл для обработки  
  - Тип: `file`

#### Ответ:

##### Успешный ответ (200 OK)
```json {
  "string"
```

### Метод: POST (/api/doctors-list)

#### Параметры запроса:
- **file**: (обязательный) Файл для обработки  
  - Тип: `text`
  - Ghbvth `Хирург`

#### Ответ:

##### Успешный ответ (200 OK)
```json {
[
  {
    "id": 0,
    "specialization": "string",
    "academic_degree": "string",
    "type_visit": "string",
    "price": 0
  }
]
```

### Метод: POST (/api/faq)

#### Параметры запроса:
- **file**: (обязательный) Файл для обработки  
  - Тип: `text`
  - Пример `Как подготовиться к сдаче крови?`

#### Ответ:

##### Успешный ответ (200 OK)
```json {
  "string"
```

### Метод: GET (/api/info)

#### Ответ:

##### Успешный ответ (200 OK)
```json {
  "string"
```

### Метод: POST (/api/analysis-list)

#### Параметры запроса:
- **file**: (обязательный) Файл для обработки  
  - Тип: `text`
  - Пример `УЗИ`

#### Ответ:

##### Успешный ответ (200 OK)
```json {
[
  {
    "id": 0,
    "full_text": "string",
    "price": 0
  }
]
```
