# Мониторинг нагрузки сервера Ubuntu с оповещением в ВК

Загружаем файл на сервер и подставляем свои значения в access_token, user_ids, text_msg
Также нужно подредактировать значение maxload основываясь на мощность своей VDS.

# Авто запуск
Теперь добавляем файл в crontab (crontab -e)

<img width="423" alt="image" src="https://user-images.githubusercontent.com/55111782/119333917-23193100-bc93-11eb-88b7-45d85d454f44.png">

___

Если Вы все сделали правильно, то теперь сервер будет проверять сам себя каждые 5 минут и в случае большой нагрузки будет отправлять Вам уведомление ВКонтакте.
