# Отчет о тестировании KeyValidator.

## Краткое описание
19.02.2020 было проведено тестирование KeyValidator.

На тестирование затрачено: ~ 0.5 часа.

В результате тестирования выявлены следующие дефекты:
* [Необходима доп.информация в инструкции по установке Open JDK 11](https://github.com/viktoria-sap/homework1/issues/1)
* [В руководстве использования среди валидных ключей есть невалидные](https://github.com/viktoria-sap/homework1/issues/2)
* [В руководстве использования среди невалидных ключей есть валидный](https://github.com/viktoria-sap/homework1/issues/3)

## Описание процесса тестирования:

**В качестве тестовых данных использовались данные:**
* [Инструкция по установке Open JDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

**В процессе тестирования использовались следующие артефакты:**
(из курса поняла, что артефакты (в нашем случае) - отчеты, тест планы и т.п.)
* В качестве отчета этот файл.
* Есть также issues, ссылки на них указаны выше.
* Есть своего рода тест-планы - [руководство](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md) и [инструкция](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

**Тестирование производилось в следующем окружении:**
* ПК (iOS 10.15.3 x64)
* Java: 13.0.1 (была предустановлена на моем компьютере. Не смогла удалить эту версию, чтобы установить 11ю)
* Браузер: Safari 13.0.5 (15608.5.11)