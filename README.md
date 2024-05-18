Решение кейса от Альфа банка на хакатоне IT Purple hack 2024.
Задача состояла в прогнозировании перехода клиента в один из 12 продуктовых кластеров
на 6 месяцев вперед
Данная модель решала проблему прогнозирования принадлежности клиентов к какому-либо кластеру, итоговый скор по метрике взвешенный ROC-AUC на трейне 0.91. На тесте -  0.894

Для того, чтобы воспроизвести наше решение необходимо установить все библиотеки из файла requirements.txt.
После установки библиотек, необходимо последовательно запускать нотбуки:
data_prep.ipynb -> line.ipynb -> predict_start_cluster_3month.ipynb -> fit_predict_target.ipynb

Нотбук stacking.ipynb иллююстрирует подход объединения моделей для создания одной мета-модели,
этот подход оказался не самым эффективным, тем не менее, это часть нашей работы во время хакатона
