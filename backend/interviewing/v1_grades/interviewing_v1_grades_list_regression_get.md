### Interviewing
#### interviewing_v1_grades_list_regression_get

Тестовые данные: http://79.137.204.102:8000/api/v1/grades/


1. Создать новый запрос в Postman, выбрать метод GET

2. Ввести URL: http://79.137.204.102:8000/api/v1/grades/

3. Нажать кнопку “Send”

Ожидаемый результат: Server response status code 200 Ok

Body response:

[
    {
        "grade_type": "junior"
    },
    {
        "grade_type": "middle"
    },
    {
        "grade_type": "senior"
    },
    {
        "grade_type": "lead"
    }
]
Постусловие: удалить тестовые данные

Автор: Василий

Тест выполнен
|     Дата    | Время | Результат|   Имя  | Баг № Trello|
|     ---     |  ---  |    ---   |   ---  |      ---    |
|  2023-08-30 | 15:46 |   Passed | Василий|       -     | 