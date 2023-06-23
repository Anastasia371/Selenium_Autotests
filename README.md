# Selenium_Autotests
Автотесты в Selenium на Python, с отчетом в Allure.

Allure следует предварительно скачать и сохранить в одной папке с проектом.

Для запуска автотестов необходимо установить следующие модули (команда pip install в терминале):
pytest
selenium
webdriver_manager
allure-pytest

Для создания каталога с отчетами - команда:
mkdir my_allure_results

Для запуска сервера отчетов - команды:

1) cd <путь до каталог allure\bin> 
2) .\allure.bat 
3) .\allure serve <путь до каталога с результатами> 
