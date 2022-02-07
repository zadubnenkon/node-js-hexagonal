# Node.js application. Hexagonal architecture

## Описание
Данное приложение было создано в процессе просмотра видоурока "Реализация гексагональной архитектуры на node.js и nest".
- [Ссылка на канал](https://www.youtube.com/channel/UCTSVfbCKN3nZbogPtOCHcMg)
- [Ссылка на часть 1](https://www.youtube.com/watch?v=sMWwO9yRrCc)
- [Ссылка на часть 2](https://www.youtube.com/watch?v=vX5keKH6iZU)

## Подготовка к запуску
> Данное приложение работает только на версиях node не меньше 10 и не больше 14.  
> Работа проверялась на node v14.15.0.

Устанавливаем все необходимые модули node.js:
```bash
$ npm install
```

## Запуск приложение
```bash
# product
# localhost:8080
$ npm start
```

## Функционал

Перечислить с одного аккаунта на другой:
```
/account/send/?sourceAccountId=#SOURCE_ID#&targetAccountId=#TARGET_ID#&amount=#AMOUNT#

Например:
/account/send/?sourceAccountId=41&targetAccountId=42&amount=100
```