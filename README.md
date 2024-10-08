# Итоговое задание основы React

<p>Проект React простейший сервис просмотра информации о погоде. Создан через команду npx create-react-app</p>
<p>Главный файл рендеринга находится по пути './src/App.js'</p>
<p>В проекте используется геолокация, файл который находится по пути './src/components/userLocation.js'</p>
<p>Данны запрашиваются через <a href="https://openweathermap.org/api">One Call API OpenWeather</a></p>
<p>Используется библиотека http-запросов Axios.</p>
<p>При запуске проекта запрашивается у пользователя разрешение на определения его местоположения для показа погоды. Так же имеется возможность выбрать из списка город.</p>
<p>Прогноз погоды показывает текущую погоду и на ближайшие 5 дней (по дням на 5 суток)</p>
<p>Список городов можно редактировать, для это нужно перейти в файл по пути './src/components/listCities.js' Если изначально по местоположению не отображается название вашего города, значит его нету в списке, необходимо его добавить в файл в <strong>cityNames!</strong></p>

## Как запустить проект

Перейти в директорию проекта, где находятся файлы package.json и т.д.\
Прописать в терминале команду `npm install`, для установки библиотек, которые используются в проекте.\
`Внимание!` В проекте использутся API ключ от <a href="https://openweathermap.org/api">One Call API OpenWeather</a>, для корректной работы проекта, нужно иметь дуйствующий API ключ. В директории проекта, нужно создать файл .env и прописать внутри него - `REACT_APP_API_KEY=ваш API ключ!`\
Запустить проект командой `npm start`
