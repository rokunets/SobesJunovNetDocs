main_page

main_page_choose_job_get_negative

Ввод невалидных параметров

Тестовые данные: http://79.137.204.102:8000/api/v1/jobs/

1.Создать новый запрос в Postman
2.Выбрать метод GET
3.Ввести URL http://79.137.204.102:8000/api/v1/jobs/
4.Ввести невалидный параметр query params 

Key = job_type

Value = тест1

Проверить URL должен измениться на http://79.137.204.102:8000/api/v1/jobs/?job_type=тест1

5.Отправить запрос

Ожидаемый результат

Server response 400 ОК


Постусловие: удалить тестовые данные

Автор: Ирина

Тест выполнен

|     Дата    | Время | Результат|   Имя  | Баг № Trello|
|     ---     |  ---  |    ---   |   ---  |      ---    |
|  2023-08-31 | 10:38 |   Passed |  Ирина |       -     | 