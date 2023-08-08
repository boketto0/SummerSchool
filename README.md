##Описание проекта 
Проект представляет собой веб-приложение, которое на данном этапе может использоваться в качестве рабочего инструмента для дизайнерских агенств. Развитие приложения предполагает его использование для улучшения инфраструктуры города. Сайт позволяет пользователям загружать картинки для дальнейшей обработки и анализа и предоставляет им обратную связь о качестве загруженных картинок. Проект имеет две основные части: бэкэнд, написанный на Python Django, и фронтенд, написанный на React JS с использованием Node.js для управления зависимостями и сборки проекта.

Возможности проекта:

Окно регистрации пользователя: Входной точкой для пользователей является окно регистрации, где они могут ввести свой номер телефона, имя и фамилию для создания учетной записи.

Загрузка картинок: Зарегистрированные пользователи могут загружать картинки через фронтенд. После загрузки, картинки отправляются на бэкэнд с помощью библиотеки Axios, где они подвергаются обработке.

Обработка картинок на бэкэнде: Бэкэнд, написанный на Python Django, обрабатывает полученные картинки.

Диаграммы-показатели качества картинки: После обработки бэкэнд возвращает данные в формате JSON. Фронтенд использует эти данные для построения диаграмм-показателей качества картинки с помощью библиотеки react-minimal-pie-chart.

Описание картинки: В зависимости от показателей картинки (хорошие, средние, низкие), проект предоставляет описание картинки, которое помогает пользователям понять, какие улучшения можно внести.

Рабочие ссылки для дополнительной информации: В проекте присутствуют рабочие ссылки, которые пользователи могут использовать для получения более детальной информации по конкретной теме.


##Запуск react приложения

## Available Scripts

### `npm install` - install node_modules

### `npm install react@latest` - install react

### `npm start` - run project

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

