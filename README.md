# Diagnostics_of_equipment_malfunctions (Frontend_of_web_service)
Система позволяет создавать и управлять множеством взаимосвязанных отказов, каждый из которых имеет свой набор матриц, связанных с ним данных, таких как список отказов предшественников, список отказов последователей, список связанных причин и список связанных диагностических признаков.

Основные возможности:
1. Создание и управление множеством отказов.
2. Ведение подробной информации, связанной с каждым отказом, включая матрицы, предшественники, последователи, причины и диагностические признаки.
3. Интерактивное редактирование матриц, с возможностью добавления, удаления и изменения ячеек.
4. Автоматическое обновление матриц при изменении связанных данных (предшественники, последователи, причины, диагностические признаки).
5. Интуитивно понятный пользовательский интерфейс для управления отказами и их данными.
6. Страницы авторизации и регистрации для управления доступом к системе.
7. Страница истории результатов, отображающая ранее созданные отказы и связанные с ними данные.
8. Страница вывода графа, позволяющая визуализировать взаимосвязи между отказами, их предшественниками, последователями, причинами и диагностическими признаками.
9. Возможность экспорта данных в формате JSON для дальнейшего использования или резервного копирования.

Технологии:
- React.js
- JavaScript
- HTML/CSS
- Firebase (для авторизации и хранения данных)
- D3.js (для визуализации графа)

Установка и использование:
1. Клонируйте репозиторий.
2. Установите зависимости с помощью npm install.
3. Настройте подключение к Firebase.
4. Запустите приложение с помощью npm start.
5. Начните работу с системой управления отказами.
