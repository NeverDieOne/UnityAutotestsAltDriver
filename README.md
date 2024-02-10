# Автоматизация тестирования Unity с помощью NUnit


## Как настроить проект

[Ссылка](https://alttester.com/docs/sdk/latest/pages/get-started.html) на офф доку:

1. Скачиваем (AltTester for Desktop)[https://alttester.com/tools/]
2. Устанавливаем из него `.unitypackage`
3. Добавляем зависимости в `manifest.json`:
   1. `"com.unity.nuget.newtonsoft-json": "3.0.1"`
   2. `"com.unity.editorcoroutines": "1.0.0"`
4. Добавляем в зависимости `inputsystem`:
   1. `"testables": ["com.unity.inputsystem"]`
5. Устанавливаем `AltTester Desktop`
6. Запускаем игру в редакторе
7. Подключаемся с помощью `AltTester Desktop` к игре
8. В окне `AltTester` в игре нажимаем `Refresh`
9. PROFIT! Подключаемся из кода.

## Плюсы

1. Автотесты можно писать на C#, Java и Python
2. Автотесты и проект с игрой разнесены по разным репозиториям
3. Selenium-like API у AltTester 

## Минусы

1. Сложное подключение
2. Ограниченный пул языков
3. Непонятно насколько легко расширять возможности AltTester