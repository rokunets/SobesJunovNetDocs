### Interviewing
#### interviewing_v1_jobs_choose_job_regression_get

Тестовые данные: http://79.137.204.102:8000/api/v1/jobs/


1. Создать новый запрос в Postman, выбрать метод GET

2. Ввести URL: http://79.137.204.102:8000/api/v1/jobs/

3. Ввести в Query Params значение существующей специальности key=job_type, value=Разработка на Python

4. Убедиться что Request URL изменился на http://79.137.204.102:8000/api/v1/jobs/?job_type=Разработка на Python

5. Нажать кнопку “Send”

Ожидаемый результат: Server response status code 200 Ok

Body response:

[
    {
        "job_type": "Разработка на Python"
    }
]

Постусловие: удалить тестовые данные
             
Автор: Василий

Тест выполнен
|     Дата    | Время | Результат|   Имя  | Баг № Trello|
|     ---     |  ---  |    ---   |   ---  |      ---    |
|  2023-08-30 | 15:38 |   Passed | Василий|       -     | 