* Уберем ручное создание бина в конфигурационном файле `applicationContext` и добавим строчку которая включит XMLсканирование компонентов в Spring `<context:component-scan base-package="springcourse.practice" />` теперь Сканирование пакетов Spring обнаружит все классы с `@Component`, аннотация указывает что класс является компонентом (бином) 
