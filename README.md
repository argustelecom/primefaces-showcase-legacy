# PrimeFaces Showcase

![PrimeFaces icon](https://www.primefaces.org/wp-content/uploads/2016/10/prime_logo.png)

### Введение

Демо библиотеки JSF компонентов PrimeFaces.

По умолчанию собирает версию для равёртывания в ear appserver. При этом не пакует в war lib зависимости, которые 
уже есть в ear/lib. Чтобы не тормозить запуск ear у разработчика. Такая версия выложена в корпоративный репозиторий.

Включена в профили appserver, предназначенные для разработчиков (не для заказчиков). Запускается вместе с web 
приложениями Аргус. Доступен [http://localhost:8080/primefaces-showcase/](http://localhost:8080/primefaces-showcase)

##### Запуск отдельно

```
git clone https://github.com/argustelecom/primefaces-showcase-legacy
cd showcase
mvn clean                  -- clean temp files from target folder
mvn package -Pjetty        -- create war file (under target directory)
mvn jetty:run -Pjetty      -- run showcase project locally
```

[http://localhost:8080/showcase/](http://localhost:8080/showcase)

[http://localhost:8080/showcase/mobile/index.xhtml](http://localhost:8080/showcase/mobile/index.xhtml)

### Documentation

User Guide is available at [documentation](http://www.primefaces.org/documentation) page along with other additional resoures.

### Contribution

Visit [Contribution Wiki](https://github.com/primefaces/primefaces/wiki/Contributing-to-Primefaces) page for the detailed information.

### License

Licensed under the Apache License, Version 2.0 (the "License") [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
