#  rfidemo

Демонстрационное приложение для работы с [библиотекой для работы с Alba РФИ банка](https://github.com/RFIBANK/iOS-SDK).

<img src="https://github.com/kei-sidorov/rfidemo/blob/master/screenshot.png?raw=true" width="320" height="568" />

### Настройка

В файле ViewController.m впишите ваш ID сервиса и приватный ключ.

### Зависимости

Проект использует CocoaPods для управления зависимостями.

Проект использует [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) для отображения индикатора загрузки. 

После клонирования из репозитория необходимо выполнить инициализацию
``` sh 
$ pod install
```