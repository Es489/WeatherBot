# WeatherBot @WearWeatherBot
## Умный сервис прогноза погоды (Средний уровень сложности)
### Язык програмирования: 
Python 3.7
### Пользовательский интерфейс: 
Telegram chatbot
### Формат ответа: 
Данные о погоде предоставляются в двух форматах прогноз на данный момент времени и прогноз на ближайшие пять дней в текстовом формате по шаблонам "Осадки- _ Температура _ Ощущается как _ Давление _ мм рт.ст Влажность _ %" и " День _ Осадки - Температура _ Ощущается как _ Давление _ мм рт.ст. Влажность _%" и отправляются пользователю.
Так же на основе погодных условий пользователю отправляется тематическая gif и рекомендации по тому как одеваться при данной погоде в текстовом форматею 
### Процесс работы программы
*Данные приходят от пользователя через интерфейс Телеграм Мессенджера:*
  1. Сервис - чат-бот предлагает пользователю выбрать язык предоставляемых данных о погоде
  2. Чат-бот предлагает выбрать пользователю нужный для него сервис погоды: "Погода на данный момент" или "Прогноз на 5 дней"
  3. Чат-бот запрашивает у пользователя его текущую геолокацию
  
*Данные вееденные пользователем брабатываются для формирования ответа пользователю*
  1. Формируется и отправляется запрос в api.openweathermap.org
  2. Полученные данные обрабатываются и форматируются в понятный формат для пользователя
  3. После форматирования данных чат-бот отправляет ответ пользователю
  4. Пользователю отправляется gif соответсвующая тематике прогноза погоды
## Как запустить вашу программу?
  1. Вставить токены из файла .gitignore
  2. python3 main.py
## Демо

Краткое демо-видио работы чат бота [Демо](https://github.com/Es489/WeatherBot/blob/master/weatherbotdemo.MP4) - нужно скачать файл


