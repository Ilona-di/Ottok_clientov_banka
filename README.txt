Из «Бета-Банка» стали уходить клиенты. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.
Небходимо построить модель с предельно большим значением F1-меры. И проверить F1-меру на тестовой выборке.
Дополнительно будем измерять AUC-ROC, сравнивать её значение с F1-мерой.
Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

Мы попробовали три разные модели для предсказаний: решающее дерево, случайный лес и логистическую регрессию. 
По результатам всех проверок наилучший результат показала модель RandomForestClassifier. 