# Создание схемы данных в Oracle

### Пример скрипта для наката схемы
liquibase.bat --driver=org.postgresql.Driver --chanLogFile=/liquibase/master.xml --url=<адрес базы> --username=<username из под которого планируется накат> --password=<password> update


### Пример скрипта для отката схемы
liquibase.bat --driver=org.postgresql.Driver --chanLogFile=/liquibase/master.xml --url=<адрес базы> --username=<username из под которого планируется накат> --password=<password> rollback <TAG тег до которого необходимо произвести откат>

