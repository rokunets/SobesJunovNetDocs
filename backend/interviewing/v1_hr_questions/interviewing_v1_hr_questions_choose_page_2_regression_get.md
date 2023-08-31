### Interviewing
#### interviewing_v1_hr_questions_choose_page_2_regression_get

Тестовые данные: http://79.137.204.102:8000/api/v1/hr-questions/


1. Создать новый запрос в Postman, выбрать метод GET

2. Ввести URL: http://79.137.204.102:8000/api/v1/hr-questions/

3. Ввести в Query Params значение существующей страницы key=page, value=2

4. Убедиться что Request URL изменился на http://79.137.204.102:8000/api/v1/hr-questions/?page=2

5. Нажать кнопку “Send”

Ожидаемый результат: Server response status code 200 Ok

Body response:

{
    "count": 3,
    "next": "http://79.137.204.102:8000/api/v1/hr-questions/?page=3",
    "previous": "http://79.137.204.102:8000/api/v1/hr-questions/",
    "results": [
        {
            "question": "Тестовый вопрос 2",
            "answer": "Тестовый ответ 2"
        }
    ]
}

Постусловие: 1. проверить Body response, в поле previous и next есть ссылки на предидущую и следующую страницу
             2. удалить тестовые данные

Автор: Василий

Тест выполнен
|     Дата    | Время | Результат|   Имя  | Баг № Trello|
|     ---     |  ---  |    ---   |   ---  |      ---    |
|  2023-08-30 | 15:27 |   Passed | Василий|       -     | 