# Awesome E2K

В данном репозитории собраны материалы касающиеся процессоров на архитектуре Эльбрус-2000 (e2k).

---
- Книги, статьи и доклады на конференциях
	- [Книги](#книги)
	- [Статьи от сотрудников МЦСТ](#статьи-от-сотрудников-мцст)
	- [Статьи от энтузиастов и партнеров](#cтатьи-от-энтузиастов-и-партнеров)
	- [Доклады на конференциях, семинарах](#доклады-на-конференциях-семинарах)
- Операционные системы, программы и игры
	- [Операционные системы](#операционные-системы)
	- [Программы](#программы)
	- [Патчи](#патчи)
	- [Библиотеки](#библиотеки)
	- [Инструменты разработки](#инструменты-разработки)
	- [Игры](#игры)
- Форумы, чаты, wiki с постоянно обновляемым контентом
	- [Чаты и каналы в Telegram](#чаты-и-каналы-в-telegram)
	- [Youtube каналы](#youtube-каналы)
	- [Форумы и wiki](#форумы-и-wiki)

---

## Книги и статьи
### Книги

* Руководство по эффективному программированию на платформе «Эльбрус» [HTML](http://ftp.altlinux.org/pub/people/mike/elbrus/docs/elbrus_prog/html/), [PDF](http://www.mcst.ru/files/5ed39a/dd0cd8/50506b/000000/elbrus_prog_2020-05-30.pdf)
* Микропроцессоры и вычислительные комплексы семейства "Эльбрус" [PDF](http://www.mcst.ru/files/511cea/886487/1a8f40/000000/book_elbrus.pdf)

### Статьи от сотрудников МЦСТ

* [Виртуализация подсистемы прерываний микропроцессоров «Эльбрус](http://www.mcst.ru/files/5fe5bc/d4dece/619b67/33a144/s.a._rybakov_r.v._demenko_virtualizatsiya_podsistemy_preryvaniy_mikroprotsessorov_elbrus.pdf)
* [Среды программирования и оптимизирующие компиляторы для компьютеров с микропроцессорами архитектуры "Эльбрус"](http://www.mcst.ru/files/5c21fb/330cd8/50cf3f/000000/m.i._neyman-zade_v.yu._volkonskiy_sredy_programmirovaniya_i_optimiziruyushchie_kompilyatory_dlya_kompyuterov_s_mikroprotsessorami_arhitektury_elbrus.pdf)
* [Виртуализация ОС «Эльбрус»](http://www.mcst.ru/files/5fe5d1/ffdece/61aa69/33a145/rybakov_s.a._virtualizatsiya_os_elbrus.pdf)
* [МИКРОАРХИТЕКТУРА ВОСЬМИЯДЕРНОГО УНИВЕРСАЛЬНОГО МИКРОПРОЦЕССОРА «ЭЛЬБРУС-8C»](http://www.mcst.ru/files/5847d5/d90cd8/508971/000000/alfonso_d.m._demenko_r.v._kozhin_a.s._kozhin_e.s._kolychev_r.e._kostenko_v.o.__polyakov_n.yu._smirnova_e.v._smirnov_d.a.smolyanov_p.a._tihorskiy_v.v..pdf)

### Статьи от энтузиастов и партнеров

* [Статья по архитектуре Эльбрус-2000 на Wikipedia](https://ru.wikipedia.org/wiki/%D0%AD%D0%BB%D1%8C%D0%B1%D1%80%D1%83%D1%81_2000)
* Серия статей по портированию EmBox на Эльбрус 
	* [Embox начинает восхождение на Эльбрус](https://habr.com/ru/company/embox/blog/421441/)
	* [Восхождение на Эльбрус — Разведка боем. Техническая Часть 1. Регистры, стеки и другие технические детали](https://habr.com/ru/company/embox/blog/447704/)
	* [Восхождение на Эльбрус — Разведка боем. Техническая Часть 2. Прерывания, исключения, системный таймер](https://habr.com/ru/company/embox/blog/447744/)
	* [Embox на процессоре Эльбрус. Или никогда не забывайте о том, что получили при разведке](https://habr.com/ru/company/embox/blog/485694/)
* [Краткое руководство по LXC в ОС Эльбрус](https://habr.com/ru/company/rostelecom/blog/564156/)
* [На пути к вершине: Магма и Кузнечик на Эльбрусе](https://habr.com/ru/post/563308/)
* [История портирования Reindexer'а – как покорить Эльбрус за 11 дней](https://habr.com/ru/company/rostelecom/blog/562858/)
* (?) [Как мы переносили современные игры на процессор Эльбрус-8С](https://habr.com/ru/company/gaijin/blog/533380/)
* (?) [Разработка и тестирование на платформах Эльбрус программы для томографической реконструкции Smart Tomo Engine (+2 видео)](https://habr.com/ru/company/smartengines/blog/522430/)
* [Низкоуровневая оптимизация кода на платформе Эльбрус: векторное сложение uint16_t с помощью интринсиков](https://habr.com/ru/company/smartengines/blog/351134/)
* [Зачем нужна низкоуровневая оптимизация на Эльбрусе или как ускорить распознающую систему в полтора раза](https://habr.com/ru/company/smartengines/blog/438948/)
* [Оптимизация кода для платформы Эльбрус на простых примерах](https://habr.com/ru/company/smartengines/blog/317672/)
* [Распознавание паспорта РФ на платформе Эльбрус. Часть 1](https://habr.com/ru/company/smartengines/blog/304750/)
* [Оптимизация метода Виолы и Джонса для платформы Эльбрус](https://habr.com/ru/company/smartengines/blog/340918/)
* Серия статей по тестированию производительности Эльбрусов от *EntityFX*
	* [Новогодние бенчмарки компьютеров Эльбрус](https://habr.com/ru/company/icl_services/blog/534296/)
	* [Большое тестирование процессоров различных архитектур](https://habr.com/ru/company/icl_services/blog/501588/)
	* [Сравнение процессоров Байкал-М и Эльбрус-8СВ](https://habr.com/ru/company/icl_services/blog/558564/)
* [Архитектура процессора Эльбрус: стоит ли все это своих денег?](https://habr.com/ru/company/macloud/blog/566478/)
* [Процессор Эльбрус — почему статья о тупике несостоятельна](https://habr.com/ru/post/575302/)
* [Все, что известно о процессорах «Эльбрус»](https://club.dns-shop.ru/digest/54388-vse-chto-izvestno-o-protsessorah-elbrus/)
* [Результаты тестов от EntityFX на ALT Wiki](https://www.altlinux.org/%D0%AD%D0%BB%D1%8C%D0%B1%D1%80%D1%83%D1%81/%D1%82%D0%B5%D1%81%D1%82%D1%8B/%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B)

### Доклады на конференциях, семинарах

* [Архитектура процессора Эльбрус 2000 / Дмитрий Завалишин (Digital Zone) / HighLoad++ 2021](https://www.youtube.com/watch?v=6SZZ7ASOR7s)
* [Юрлин Сергей, АО "МЦСТ" - Текущий уровень и перспективы платформы Эльбрус / SECON 2021](https://www.youtube.com/watch?v=4b6c1PcH9pI)

## Операционные системы, программы и игры
### Операционные системы
В данный раздел вносятся только ОС работающие в нативном режиме.

* [ОС Эльбрус](http://www.mcst.ru/elbrus_linux)
* [Альт Рабочая станция](https://docs.altlinux.org/ru-RU/alt-workstation-e2k/9.2/html/alt-workstation-e2k/index.html)
* [Альт Сервер](https://docs.altlinux.org/ru-RU/alt-server-e2k/9.2/html/alt-server-e2k/index.html)
* [Astra Linux SE Leningrad](https://astralinux.ru/information/library/#release-leningrad)
* [EmBox](https://github.com/embox/embox)
* [ЗОСРВ «Нейтрино-Э](https://kpda.ru/products/kpda10965/)
* [ОС РВ «БагрОС-4000»](https://www.sukhoi.org/bagros/)
* [ОС Лотос](https://instreamcom.com/ru/elbrus)

### Программы
В этом разделе содержится ПО которое поставляется отдельно от дистрибутивов Linux. Для просмотрра программ идущих в вашем дистрибутиве воспользуйтесь поиском через менеджер пакетов. 
* [Kaspersky Endpoint Security 10.1.1 для Linux редакция под Эльбрус](https://support.kaspersky.com/help/KES4LinuxElbrus/10.1.2/ru-RU/187444.htm)

### Патчи
* [Патчи на производительность и исправления ошибок сборки](https://github.com/ilyakurdyukov/e2k-ports) (с) Илья Курдюков

### Инструменты разработки
* [Qemu-e2k](https://git.mentality.rip/OpenE2K/qemu-e2k) - Реализация эмулятора архитектуры e2k для QEMU.
* [Compiler Explorer](https://ce.mentality.rip/) - Реализация Compiler Explorer с поддержкой компилятора lcc, rust и llvm под архитектуру e2k

### Библиотеки
* [Koishi](https://github.com/taisei-project/koishi) - Библиотека для реализации нативных корутин с поддержкой E2K

### Игры
Игры портированные на Эльбрус.

## Форумы, чаты, wiki с постоянно обновляемым контентом
### Чаты и каналы в Telegram

* [Процессоры Эльбрус | Elbrus CPU](https://t.me/ElbrusMCST) - Официальный канал АО МЦСТ о платформе Эльбрус
* [Эльбрусы и с чем их едят](https://t.me/e2k_chat) - чат для тематического общения по Эльбрусам и смежным темам.
* [Процессоры Эльбрус | Фан-клуб](https://t.me/e2k_fans) - неофициальный канал посвященный Эльбрусам.
* [IT-Флудильня фан-клуба ⚡️МЦСТ⚡️Эльбрус⚡️](https://t.me/joinchat/E7cNDEYgqvaXkf0x)
* [imaxai | CPU Эльбрус](https://t.me/imaxairu)

### Youtube каналы
* [ElbrusTV](https://www.youtube.com/user/ElbrusTV) - официальный канал.
* [Maxim Gorshenin](https://www.youtube.com/c/MaximGorshenin) - неофициальный канал сотрудника МЦСТ.
* [Elbrus PC Test](https://www.youtube.com/c/ElbrusPCTest) - канал энтузиастов которые портирую игры на Эльбрус и делают стримы с ними.
* [EntityFX](https://www.youtube.com/user/EntityFX) - канал энтузиаста занимающегося тестами производительности отечественных процессоров, в т.ч. и Эльбрусов.
* [Домашний "Эльбрус"](https://www.youtube.com/c/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B8%D0%B9%D0%AD%D0%BB%D1%8C%D0%B1%D1%80%D1%83%D1%81) - канал энтузиаста посвященный Эльбрусам.

### Форумы и wiki
* [Платформа «Эльбрус»](http://forum.elbrus.ru/) Официальный форум пользователей, партнёров и разработчиков
* [Официальная Wiki](https://wiki.elbrus.ru/%D0%97%D0%B0%D0%B3%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F_%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0)
* [Раздел Alt Linux Wiki посвященный Эльбрусам](https://www.altlinux.org/%D0%AD%D0%BB%D1%8C%D0%B1%D1%80%D1%83%D1%81)
* [Раздел по Astra Linux Special edition](https://wiki.astralinux.ru/pages/viewpage.action?pageId=53647195) Раздел по Astra Linux Special edition со статьями в т.ч. и для эксплуатации под Эльбрус.
