<div align="center">
<h1>Sberbank Patcher</h1>

![downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/ru.bluecat.sberbankpatcher/total)
[![GitHub release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/ru.bluecat.sberbankpatcher)](https://github.com/Xposed-Modules-Repo/ru.bluecat.sberbankpatcher/releases)
[![GitHub Release Date](https://img.shields.io/github/release-date/Xposed-Modules-Repo/ru.bluecat.sberbankpatcher)](https://github.com/Xposed-Modules-Repo/ru.bluecat.sberbankpatcher/releases)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-blue.svg?logo=telegram)](https://t.me/lsposed_workshop)
[![Telegram Group](https://img.shields.io/badge/Telegram-Group-blue.svg?logo=telegram)](https://t.me/lsposed_workshop_forum)
[![4PDA](https://img.shields.io/badge/4PDA-Topic-blue)](https://4pda.to/forum/index.php?showtopic=603033&view=findpost&p=123542189)
[![Donate](https://img.shields.io/badge/Donate_Form-blue)](https://pay.cloudtips.ru/p/85f8cf00)

<p>Различные модификации в приложении <a href="https://www.rustore.ru/catalog/app/ru.sberbankmobile">СберБанк</a></p>
</div>

### Общее:
- Запуск настроек: Экран ввода пин кода, кнопка смены пользователя. Работает только при включённой настройке иконка лаунчера.

### Контролируемый функционал:
- Антивирус Касперского
- Система самообновления
- Аналитика
- Ориентация
- Скрытие не убираемых разделов
- Бета
- Экосистема сбера
- СберПрайм
- Ассистент
- Информационные и обучаемые карточки
- Подсказки при переводах
- Баннеры с персональными предложениями
- Удерживание экрана для карт лояльности
- Платежи. Номер по умолчанию для СБП переводов
- Платежи. Раздел благотворительности
- Профиль. Что нового
- Профиль. Реклама в разделе недвижимость
- Поиск. Скрытие предложений и каналов
- Карты. СберСпасибо
- История. Очистка истории транзакций от рекламы и сервисный уведомлений
- История. Скрытие микро кредитования
- Push. Глушение информационно-рекламного канала
- Push. Фильтрация по ключевым словам(чёрный/белый список)
- Push. Логирование информационно-рекламного канала
- Push. Очистка истории push уведомлений
- Push. Скрытие кнопок действий в истории уведомлений

### Не контролируемый функционал(всегда включён):
- Промо на главном экране
- Запрос оценить приложение и другие разделы приложения
- Запрос разрешения телефонии (Android 9 и ниже)
- Безопасность устройства. Проверка на root и целостности устройства для SberPay
- VPN статус
- История. Увеличено количество скрываемых транзакций до 300
- Активирован номер по умолчанию / скрыто напоминание выдать доступ к контактам  в новом разделе переводов на главной

### Аналитика:
- Внутренняя аналитика
- Firebase Analytics

### Требования:
- Android 8.0+
- Установленное приложение [Сбербанк](https://www.rustore.ru/catalog/app/ru.sberbankmobile)

### Обратите внимание:
- Модульная часть использует рут возможности для завершения процесса и работой с файлами в личной папке Сбербанка.
- Модуль имеет возможность работать в режиме [LSPatch](https://github.com/JingMatrix/LSPatch), требуются некоторые подготовительные процессы, подробнее смотрите в telegram канале.

## For non-Russian users:
This is a module for the russian banking application [Sberbank](https://www.rustore.ru/catalog/app/ru.sberbankmobile). You don't need to use it, app working only in Russia. This module has support only for the Russian language.
