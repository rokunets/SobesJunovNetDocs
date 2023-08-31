### Interviewing
#### interviewing_v1_hr_questions_input_invalid_value_page_regression_get

Тестовые данные: http://79.137.204.102:8000/api/v1/hr-questions/


1. Создать новый запрос в Postman, выбрать метод GET

2. Ввести URL: http://79.137.204.102:8000/api/v1/hr-questions/

3. Ввести в Query Params невалидное значение key=page, value=two

4. Убедиться что Request URL изменился на http://79.137.204.102:8000/api/v1/hr-questions/?page=two

5. Нажать кнопку “Send”

Ожидаемый результат: Server response status code 400 Ok

Body response:

{
    "detail": "Неправильная страница"
}

Постусловие: удалить тестовые данные
             
Автор: Василий

Тест выполнен
|     Дата    | Время | Результат|   Имя  | Баг № Trello|
|     ---     |  ---  |    ---   |   ---  |      ---    |
|  2023-08-30 | 15:36 |   Passed | Василий|       -     | 