## Важно:
#### Приложение необходимо запускать на порту **8088**, т.к. используются статические ресурсы _(css -файл)_.

---

# Задача: **PP 2.3.1.**

---

#### Тема: _10 Spring_
#### № **ITMPJ-2766**
#### Наименование: _Spring_
#### Дедлайн: _27/10/2024_
#### Код модуля: _PP2_

---
# Spring

## Условие:

Перейдем к созданию рабочего _web-приложения_. Все ключевые моменты были рассмотрены в предыдущих задачах.

Теперь вам требуется их сопоставить и связать в один проект.

Используя наработки по `mvc` и `hibernate` соберите _CRUD-приложение_.

## Задание:

1. Написать `CRUD-приложение`. Использовать `Spring MVC` + `Hibernate`.
2. Должен быть класс `{{User }}` с произвольными полями (`id`, `name` и т.п.).
3. В приложении должна быть страница, на которую выводятся все юзеры 
с возможностью добавлять, удалять и изменять юзера.
4. Конфигурация `Spring` через `{{JavaConfig }}` и аннотации, по аналогии 
с предыдущими проектами. Без использования `xml`. Без `Spring Boot`.
5. Внесите изменения в конфигурацию для работы с базой данных. 
Вместо SessionFactory должен использоваться `EntityManager`.

## Ссылки:

Статья на `habr.com` "[Spring изнутри. Этапы инициализации контекста](https://habr.com/ru/articles/222579/)"

Мануал на `baeldung.com` "[A Guide to JPA with Spring](https://www.baeldung.com/the-persistence-layer-with-spring-and-jpa)"

### Вложенные файлы

![Step1. Подключение модулей](/imgs/1.png)
![Step2. Добавление зависимостей](/imgs/2.png)
![Step3. Перейти в конфигурирование запуска](/imgs/3.png)
![Step4. Настроить конфигурацию запуска](/imgs/4.png)

[Ссылка на оригинальную страницу](http://jira.it-mentor.tech/browse/ITMPJ-2766)