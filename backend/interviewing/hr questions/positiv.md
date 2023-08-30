Функционал прохождения собеседования

Пройти собеседование

Тестовые данные: http://79.137.204.102:8000/api/v1/hr-questions/

1.Создать новый запрос в Postman

2.Выбрать метод GET для Request

3.Ввести URL: http://79.137.204.102:8000/api/v1/hr-questions/

4.Query params 

Key - Page

Value - 1

5. Отправить Request

Ожидаемый результат: 200 ok

Response body

{
  "count": 3,
  
  "next": "http://79.137.204.102:8000/api/v1/hr-questions/?page=2",
  
  "previous": null,
  
  "results": [
  
    {
      "question": "Тестовый вопрос 1",
      
      "answer": "Тестовый ответ 1"
    }
  ]
}

Тест выполнен

|     Дата    | Время | Результат|   Имя  | Баг № Trello|
|     ---     |  ---  |    ---   |   ---  |      ---    |
|  2023-08-30 | 15:40 |   Passed | Юлия|       -     | 

Автор: Юлия

