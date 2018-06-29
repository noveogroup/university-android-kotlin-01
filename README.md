# Android. Первая задача

В папке app/src/main/kotlin можно найти исходники проекта, с которого можно начать работу. Вы можете модифицировать код в этом проекте как вам угодно.

## Задание
Есть три типа устройств: телефоны, ноутбуки и планшеты. У каждого из них есть своя цена.
Необходимо написать несколько функций сортировки, которые могли бы сортировать по возрастанию/убыванию цены массив устройств.

### Указания:
1. Алгоритмы для реализации: сортировка пузырьком, сортировка вставками, быстрая сортировка (quicksort).
1. Для каждого  алгоритма сортировки и для каждого девайса необходимо выделить свой класс.
1. Классы сортировок должны реализовывать интерфейс Algorithm.
1. Классы устройств должны реализовывать интерфейс Device.

### Как открыть проект в Intelij IDEA:
1. Скачиваем стартовый код из данного репозитория и добавляем его в свой `gitlab` репозиторий.
1. Выбираем `File \ open ...`.
1. В появившемся диалоговом окне ищем путь до проекта, выбиарем build.gradle в корне.
1. Выбираем `Open as project`.
1. В появившемся диалоговом окне указываем JDK, если не найдена, соглашаемся со всем, ничего не меняя.
1. Открываем `app/src/main/kotlin/.../Main.kt` и жмем кнопку "play" около функции main.