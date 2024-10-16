# QuakeData

QuakeData - веб-приложение для визуализации данных о движении грунта с сейсмической станции RaspberryShake. 

Приложение использует Python и несколько библиотек для сбора, обработки и отображения данных:

* **Playwright:**  Автоматизирует взаимодействие с веб-браузером для получения данных с сайта RaspberryShake.
* **Beautiful Soup:** Извлекает необходимые данные из HTML-кода страницы.
* **Pandas:**  Обрабатывает и анализирует данные, предоставляя удобные инструменты для работы с таблицами.
* **Openpyxl:**  Сохраняет данные в формате Excel для удобного доступа и анализа.
* **Dash:** Создает интерактивные графики и веб-интерфейс для визуализации данных.

QuakeData позволяет просматривать актуальные данные о движении грунта, включая ускорение, скорость и смещение, а также  скачивать их в формате Excel.