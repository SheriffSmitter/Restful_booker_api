# Проект по тестированию API Restful-booker.

><a target="_blank" href="https://restful-booker.herokuapp.com/apidoc/index.html#api-Auth">Restful-booker</a>
> 
![main page screenshot](pictures/restful_booker_main_page.png)

---
### Список проверок, реализованных в автотестах
1. Получение информации о бронировании по id.
2. Healthcheck проверка.
3. Создание бронирования.
4. Удаление бронирования.
5. Изменение существующего бронирования.

---

### Используемые инструменты
<img title="Python" src="pictures/icons/python.svg" height="40" width="40"/> <img title="Pytest" src="pictures/icons/pytest.svg" height="40" width="40"/> <img title="Allure Report" src="pictures/icons/allure_report.png" height="40" width="40"/> <img title="GitHub" src="pictures/icons/github.svg" height="40" width="40"/> <img title="Pycharm" src="pictures/icons/pycharm-original.svg" height="40" width="40"/> <img title="Telegram" src="pictures/icons/telegram.png" height="40" width="40"/> <img title="Jenkins" src="pictures/icons/jenkins-original.svg" height="40" width="40"/>  <img title="Jira" src="pictures/icons/jira.svg" height="40" width="40"/>

---

### Запуск автотестов осуществляется с использованием Jenkins
> [Ссылка на сборку в Jenkins](https://jenkins.autotests.cloud/job/Restful_booker_api/)

#### Для запуска автотестов в Jenkins
1. Открыть [задачу в Jenkins](https://jenkins.autotests.cloud/job/Restful_booker_api/)

![jenkins job main page](pictures/Jenkins_job_main_page.png)

2. Нажать "**Build Now**".

---

### Allure отчет

![allure_report page](pictures/allure_report_main_page.png)
![allure_report_graph](pictures/allure_report_graph_1.png)
![allure_report_graph](pictures/allure_report_graph_2.png)
---

### Интеграция с Allure TestOps

> [Job #4397 Vadim Korolev Petstore api](https://allure.autotests.cloud/project/4462)

![allure_testops job](pictures/allure_testops_dashboard.png)
![allure_testops job](pictures/allure_testops_test_cases.png)

---

### Интеграция с Jira
> [Задача в Jira](https://jira.autotests.cloud/browse/HOMEWORK-1331)
 
![jira task](pictures/jira_task.png)

---

### Уведомления в Телеграм

![telegram_notification](pictures/tg_notification.png)
