# План по проверке и автоматизации мобильного приложения

## Цель проекта:
Тестирование мобильного приложения «Мобильный хоспис»

 * Описание приложения:

Приложение даёт функционал по работе с претензиями хосписа и включает в себя:

* информацию о претензиях и функционал для работы с ними;
* новостную сводку хосписа;
* тематические цитаты.

## Планирование:

 * Определние «границ» приложения.
   Приложение состоит из:
       1. Главного меню (отображается тремя горизонтальными полосами)
       2. Тематических цитат (отображаются в виде бабочки)
       3. Личного кабинета или профиля(отображается в виде портрета)
       4. Рабочего экрана (по умолчанию при запуске отображается инфо из Тематических цитат)

 * Реализованный функционал.

    1. Вкладки Главного меню с соответствующим наполнением:
      * Main (Главное)
      * Claims (Жалобы)
      * News (Новости)
      * About (Инфо о программе)

    2. Авторизация пользователя.

    3. Тематические цитаты.

 * План тестирования приложения.
    1. Проведение ручного тестирования приложения.
    2. Составления чек-листа для тестирования.
    3. Составление тест-кейсов для тестирования.
    4. Автоматизация тест-кейсов по чек-листу.
    5. Составление отчета по тестированию.

## Перечень используемых инструментов

   1. Git-hub - для хранения кода и автотестов.
   2. Android Studio - интегрированная среда разработки для работы с платформой Android. Имеет такие возможности для тестирования, как логирование и Debug-режим, установка сборки на устройство, слои в приложении, производительность, симуляция Out of Memory, уровень заряда батареи, входящие звонки и СМС, Android Emulator девайсов, повороты экрана и различные датчики.
   3. Java 8 - широко используемый язык написания автотестов.
   4. VSCode -инструмент позволяющий легко редактировать код.
   5. Allure - фреймворк, предназначенный для создания визуально наглядной картины выполнения тестов.
   6. Record Espresso Test - Тестовый  фреймворк для создание тестов пользовательского интерфейса. Входит в программу Android Studio.

## Интервальная оценка временных затрат с учетом рисков

С учётом непредвиденных ситуаций,форс-мажорных обстоятельств,решений организационных  и технических вопросов,а так же непредвиденных ситуаций.

 * Временные затраты на проект составят:  230 часов