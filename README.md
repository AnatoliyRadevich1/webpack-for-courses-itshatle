# webpack-for-courses-itshatle

1. Клонировать проект https://github.com/oDASCo/webpack-for-courses-itshatle.git
2. Зайти в папку этого проекта и в терминале выполнить npm install
3. Чтобы запустить проект в терминале выполнить npm run start
4. Основной JavaScript файл проекта, куда можно подключать свои модули(другие файлы) или писать свой JS код - src/js/script.js
5. Основной файл HTML- верстки  (сейчас это src/pages/index.pug) можно задать в файле webpack.config.js в поле new HTMLWebpackPlugin({
                                                                                                                            template: "./pages/index.pug"
                                                                                                                        })
Например, можно поменять его на файл src/index.html 
6. Основной файл стилей - src/styles/main.css





//  ./node_modules/.bin/webpack //
