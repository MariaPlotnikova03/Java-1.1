# Отчёт о тестировании приложения «KeyValidator»

## Краткое описание

31.08.2020 было проведено инсталляционное тестирование  приложения KeyValidator.

На тестирование затрачено: 0,5 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/MariaPlotnikova03/Java-1.1/issues/1
* https://github.com/MariaPlotnikova03/Java-1.1/issues/2
* https://github.com/MariaPlotnikova03/Java-1.1/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
*	Документация: "Руководство использования KeyValidator"
* Установочный файл приложения: KeyValidator.class

В качестве тестовых данных использовались данные из руководства использования KeyValidator:

Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Ожидаемый результат при проверке валидных ключей - OK

Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Ожидаемый результат при проверке невалидных ключей - FAIL

Тестирование производилось в следующем окружении:
* Компьютер на базе х64
* Windows 10 Pro версия 1909 ( Сборка ОС 18363.1016)
* openjdk version "11.0.8" 2020-07-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)

