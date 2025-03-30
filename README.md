# API Documentation

## Endpoint: /api

### Метод: GET

#### Параметры запроса:
- **user_id**: (обязательный) Идентификатор пользователя. Используется для персонализации ответа.  
  - Тип: `string`
  - Пример: `"user123"`

- **action**: (обязательный) Действие пользователя, которое нужно выполнить.
  - Тип: `string`
  - Пример: `"start"`, `"stop"`

#### Ответ:
##### Успешный ответ (200):
{
  "status": "success",
  "message": "Action executed successfully.",
  "data": {
    "result": "Some result data"
  }
}
