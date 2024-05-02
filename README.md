Установить зависимости 
``` shell
pip3 install -r requirements.txt
```
Запустить все тесты  tests
```shell
pytest tests --alluredir=allure_results
```
Посмотреть отчет в веб версии
``` shell
allure serve allure_results
```
