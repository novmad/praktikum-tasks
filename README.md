# Ya.Praktikum

Репозиторий с учебными проектами курса Яндекс.Практикум Data Scientist.


| Название               | Описание                                                                                                                                |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| p03_bank_debts         | [Исследование надёжности заёмщиков](https://github.com/novmad/praktikum-tasks/blob/master/p03_bank_debts)                               |
| p04_apartments         | [Исследование объявлений о продаже квартир](https://github.com/novmad/praktikum-tasks/tree/master/p04_apartments)                       |
| p05_tariffs            | [Определение перспективного тарифа для телеком компании](https://github.com/novmad/praktikum-tasks/tree/master/p05_tariffs)             |
| p06_games              | [Выявление закономерностей, определяющих успешность компьютерных игр](https://github.com/novmad/praktikum-tasks/tree/master/p06_games)  |
| p07_users_behavior     | [Рекомендация тарифов](https://github.com/novmad/praktikum-tasks/tree/master/p07_users_behavior)                                        |
| p08_churn              | [Отток клиентов](https://github.com/novmad/praktikum-tasks/tree/master/p08_churn)                                                       |
| p09_geo                | [Определение скважины для разработки](https://github.com/novmad/praktikum-tasks/tree/master/p09_geo)                                    |
| p10_gold_recovery      | [Восстановление золота из руды](https://github.com/novmad/praktikum-tasks/tree/master/p10_gold_recovery)                                |
| p11_insurance          | [Преобразование данных клиентов страховой компании](https://github.com/novmad/praktikum-tasks/tree/master/p11_insurance)                |
| p12_autos              | [Определение рыночной стоимости автомобиля](https://github.com/novmad/praktikum-tasks/tree/master/p12_autos)                            |
| p13_taxi               | [Прогноз количества заказов такси](https://github.com/novmad/praktikum-tasks/tree/master/p13_taxi)                                      |
| p14_toxic_comments     | [Определение токсичности комментария](https://github.com/novmad/praktikum-tasks/tree/master/p14_toxic_comments)                         |
| p15_flights            | [Исследование спроса на авиабилеты](https://github.com/novmad/praktikum-tasks/tree/master/p15_flights)                                  |


Для воспроизведения проектов требуется выполнить следующие действия (приведены для ОС Linux):

### Установка окружения

```bash
# установка python версии 3.7
sudo apt update
sudo apt install python3.7 python3.7-venv

# перейти в каталог проекта
cd <project catalogue>

# установка виртуального окружения 
python3.7 -m venv ./venv
source ./venv/bin/activate

# установка зависимостей
pip install -r requirements.txt
pip install jupyter notebook

```

### Запуск проекта

```bash
jupyter-notebook $(find . -name "*.ipynb")

```

