# **Отчёт о тестировании KeyValidator** # 
## **Краткое описание** ##

Дата начала: 11.12.2020 

Дата окончания: 11.12.2020

Было проведено функциональное тестирование приложения KeyValidator на основе предоставленных лицензионных ключей (См. пункт Источник тестовых данных)

**На тестирование затрачено:** 2 часа 

**В результате тестирования выявлены следующие дефекты:**

https://github.com/mariyaburtseva/Java---homework-1-1/issues/1

## **Описание процесса тестирования** ##

1. Скачать OpenJDK11 в соответствии с инструкцией по ссылке: https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md
2. Установить OpenJDK11, протестировать установку  через терминал при помощи команды: java -version
3. Скачать KeyValidator по ссылке: https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class
4. Инициализировать на своем компьютере пустой репозиторий, добавить файл с приложением KeyValidator. И файл: .gitignore, находящийся по ссылке: https://github.com/netology-code/javaqa-homeworks/blob/master/.gitignore 

5. Поочередно проверить ключи валидации, фиксируя результаты для валидных ключей - ОК, для невалидных - FAIL

В процессе тестирования использовались следующие артефакты:
* файл "KeyValidator.class"
* файл ".gitignore"

В качестве тестовых данных использовались ключи валидации размещенные здесь:
https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

Ключи для проверки:

Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a 
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

При вводе в приложении валидных ключей должно появится "ОК", при вводе невалидных - "FAIL".

Тестирование производилось в следующем окружении:

* Ноутбук Dell 
* Windows 10, X64
* Версия Java: 11.0.9.1
* Yandex.Browser 20.11.2.78 (64-bit)