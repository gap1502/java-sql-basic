create schema netology;

create table persons (
                         name varchar(255),
                         surname varchar(255),
                         age int,
                         phone_number varchar(12),
                         city_of_living varchar(255),
                         primary key (name, surname, age)
);