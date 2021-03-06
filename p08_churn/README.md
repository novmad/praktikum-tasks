# Отток клиентов

## Постановка задачи

Построить модель для прогноза ухода клиента из банка в ближайшее время. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Матрика - *F1*-меры (min 0.59), *AUC-ROC* .

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Описание данных

***Признаки***
* _RowNumber_ — индекс строки в данных
* _CustomerId_ — уникальный идентификатор клиента
* _Surname_ — фамилия
* _CreditScore_ — кредитный рейтинг
* _Geography_ — страна проживания
* _Gender_ — пол
* _Age_ — возраст
* _Tenure_ — количество недвижимости у клиента
* _Balance_ — баланс на счёте
* _NumOfProducts_ — количество продуктов банка, используемых клиентом
* _HasCrCard_ — наличие кредитной карты
* _IsActiveMember_ — активность клиента
* _EstimatedSalary_ — предполагаемая зарплата

***Целевой признак***
* _Exited_ — факт ухода клиента