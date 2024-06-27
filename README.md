# Домашнее задание к занятию "`Базы данных`" - `Андрющенко Вячеслав`


---

### Задание 1  

Опишите не менее семи таблиц, из которых состоит база данных:

какие данные хранятся в этих таблицах;

какой тип данных у столбцов в этих таблицах, если данные хранятся в PostgreSQL.

Приведите решение к следующему виду:

Сотрудники (

идентификатор, первичный ключ, serial,

фамилия varchar(50),
...
идентификатор структурного подразделения, внешний ключ, integer).


### Решение 1 

Сотрудники( 

идентификатор, первичный ключ, serial,

ФИО сотрудника (varchar(100)) 

Идентификатор зарплатных данных, внешний ключ integer

Идентификатор должности, внешний ключ integer

Идентификатор типа подразделения, внешний ключ integer

Идентификатор структурного подразделения, внешний ключ integer 

Дата найма (date) 

Идентификатор филиала, внешний ключ integer 

Идентификатор проекта, внешний ключ integer 

)



Структурные подразделения (

идентификатор, первичный ключ, serial, 

Наименование подразделения (varchar(100))

)


Проекты (  

идентификатор, первичный ключ, serial,

Наименование проекта (varchar(100))

    
)

Должности (

идентификатор, первичный ключ, serial, 

Наименование должности (varchar(100))

)

Филиалы (

идентификатор, первичный ключ, serial,

Адрес филиала (varchar(200))


)

Типы подразделений (

идентификатор, первичный ключ, serial,

Наименование типа подразделения (varchar(50))

)

Зарплатные данные (

идентификатор, первичный ключ, serial,

Данные об окладах сотрудников (numeric(10, 2))

)
