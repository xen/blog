---
title: "Оплатил Youtube Premium."
datePublished: Sun Dec 22 2024 09:32:40 GMT+0000 (Coordinated Universal Time)
cuid: cm4zetsjg000c09ld7g59bf4n
slug: oplatil-youtube-premium
tags: life, nomad

---

Получился целый квест чтобы оплатить премиум подписку на Youtube. В какой-то момент видеохостер решил, что больше не готов принимать от меня деньги просто так и решил устроить небольшое предновогоднее развлечение. Видимо какой-то ИИ внутри системы оплаты решил, что у меня не хватает своих проблем в жизни и решил помочь.

Причем пользоваться Youtube с рекламой вообще невозможно. Качество жизни падает просто глобально. В нашей жизни постоянными стали виртуальные вещи. Дом — это не там, где твои книги, вещи и инструменты. А дом — это там, где твой Netflix и Youtube. Могло быть по-другому, но пока так.

И привычный уютный Ютуб перестал быть центром стабильности и начал угрожать что его скоро не будет. Ну закончилась подписка, ну так в чем дело? Но он начал настойчиво предлагать оплатить подписку в валюте страны, в которой мы сейчас находимся. В целом я и не против, ну будут баты, или донги. Какая нафиг разница? Но оказалось, что карточка должна быть привязана к стране, в валюте которой выставляется счет. То есть, я своей карточкой не могу оплатить счет в батах. А время стремительно заканчивалось.

И вот в мой домашний ютюб проникла всякая стремная реклама и какое-то дерьмо и интернетов к которому я просто не был готов. Плюс еще моим детям начали показывать рекламные вставки, у нас семейная учетная запись. Премиум ютуба, по каким-то замерам, защищает детей от просмотра от 300 часов рекламы в год. Представьте сколько визуального и нерелевантного мусора показывается детям если не оплатить пару долларов в месяц? Это просто вопрос ментальной безопасности и фундаментального качества жизни. Современный налог на телевизор.

В общем платить надо. Но вопрос как. Можно было бы пойти и открыть счет в тайском банке. Но это требует другой тип визы. И мы даже уже в Хошимине и пытаемся ее получить третью неделю. Но рекламу начали показывать уже сейчас. А сколько займут все эти бюрократические задачи не понятно. Вьетнамский банк звучит привлекательно, но в теории. И как потом пополнять.

Плюс у нас есть привилегия, которой нет в менее развитых европейских странах: счет в лучшем банке мира Приватбанке. Как бы воспользоваться ею?

Мне надо показать Гуглу, что я нахожусь в Украине. А для этого нужно заходить на сайт через украинский IP. Это можно сделать двумя способами. Я попробовал самый простой — найти VPN. Потратил на это время, даже скачивал несколько клиентов на компьютер. Если бы это получилось, то на этом бы история и закончилась.

Мне не нравится сама суть VPN бизнеса. Я понимаю тех, кто вынужден им пользоваться. Это как платить налоги понимая, что они пойдут на то, чтобы убивать граждан твоей же страны. Если у тебя нет специальных знаний и навыков, то безопаснее просто их платить.

Почему VPN это плохо? Модель бизнеса принципиально уязвима. Если ты хорошо выстроил продажи и хорошо умеешь привлекать пользователей, то ты вынужден сотрудничать с властями. И даже нет принципиальной разницы платный VPN или бесплатный. Представьте, что вы годами собираете команду, вкладываетесь в маркетинг, а потом очередной чиновник даже без решения суда просто блокирует весь ваш бизнес в стране. А блокируют все страны. Просто условно передовые тоталитарные страны типа Китай, Франция, Германия, США следят за своими гражданами гораздо больше, чем условный Таиланд. Нет какой-то особой уникальности вокруг блокировки российских сайтов на территории Украины. Просто теперь интернет такой.

Так же нет никакой репутационной ценности у VPN провайдеров. Это не бизнес, в котором победитель получает все. Завтра будет еще новый десяток. Причем от тех же самых людей. Благо зарегистрировать юрлицо не сложно, да и выполняет оно функцию приема платежей. Если ваша компания засветилась случайно в судебной практике, то NewWavePrivate Techology LLC мало кто сопоставит с приложением GlobalVPN в апсторе.

Но даже поиск украинских VPN не увенчался успехом. В целом провайдеры очень мутные, работают плохо, врут про то, что у них есть выходные ноды в Украине. А поскольку ценности они создают немного, то стараются забайтить на оплату сразу за год, и чаще всего предлагают вбивать данные карточки у них на сайте, а не через известные платежные шлюзы, которые хоть как-то дают ощущение защиты.

Для того чтобы сделать свой приватный VPN нужна одна единственная строка в консоли:

`ssh -D 1080 -C -N пользователь@сервер`

Это все что надо чтобы сделать защищенный SOCKS прокси. Да, все давным-давно придумано и работает. Весь современный интернет написан в конце прошлого века и до сих пор работает, вопреки.

Пришлось сделать шаг глубже, и я начал искать хоть какой-то сервер в Украине чтобы открыть с ним ssh соединение и перенаправить через него трафик.

Первым делам пошел к пацанам Nic.ua**.** Попытался у них подключить хостинг, но ничего не получилось. Я готов был заплатить им денег, но они предложили бесплатный, а потом он то ли не подключился, то ли успел отключиться пока я готов был его попробовать. В общем пошел искать дальше.

Спросил у своих учеников, вдруг у кого-то есть сервер. У одного был, но там почему-то отключили опцию создания SSH туннелей. Человек и так им платит, почему такое жлобство я не понимаю.

Пошел смотреть еще кучу других сервисов. С сайтами оказалось надо бороться. Даже не буду тратить на это время. Много сайтов, много странного.

В конце концов просто начал покупать и оплачивать доступы. К счастью, тут уже было все не так сложно и не так долго. Хоть админ панели работают просто очень медленно. Посадочная открывается быстро, а админ панель хостера медленно. Экономят что ли на серверах? 20 секунд ждать нажатия кнопки это прямо много. При том, что внутри еще надо кучу действий сделать: дозаполнить анкету, подключить сервер, выбрать какие-то настройки и т.д.

В общем получилось подключить на Server.ua**.** Не рекомендовать их в данной ситуации не могу. Хотя у них админка работает просто мега медленно.

Наконец-то скопировал выделенный айпи адрес, включил настройки SOCKS прокси в настройках сети. И через 30 секунд оплатил приватовской карточкой премиум.

СУКА! Часов 8 на попытки решить вопросы и реальные действия, которые привели к результату это 30 секунд. Обожаю киберпанк, в котором мы трахаемся с системами пока они трахают нас.

Теперь могу послушать музыку в фоне, скачать на телефон и дети могут посмотреть ролики по учебе и для развлечения без рекламы.