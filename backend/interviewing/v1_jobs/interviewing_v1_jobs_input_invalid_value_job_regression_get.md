### Interviewing
#### interviewing_v1_jobs_input_invalid_value_job_regression_get

Тестовые данные: http://79.137.204.102:8000/api/v1/jobs/


1. Создать новый запрос в Postman, выбрать метод GET

2. Ввести URL: http://79.137.204.102:8000/api/v1/jobs/

3. Ввести в Query Params невалидное значение key=job_type, value=4564

4. Убедиться что Request URL изменился на http://79.137.204.102:8000/api/v1/jobs/?job_type=4564

5. Нажать кнопку “Send”

Ожидаемый результат: Server response status code 400 Ok


Постусловие: удалить тестовые данные
             
Автор: Василий

Тест выполнен
|     Дата    | Время | Результат|   Имя  | Баг № Trello|
|     ---     |  ---  |    ---   |   ---  |      ---    |
|  2023-08-30 | 15:43 |   Failed | Василий|       -     | 