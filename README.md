## Личная информация
<img align="right" src="https://github.com/ilyachase/curriculum_vitae/blob/master/img/me.jpg?raw=true" alt="ilya.chase"/>

- ФИО: Левин Илья Викторович
- Дата рождения: 06.12.1992
- Семейное положение: холост
- Локация: г. Челябинск
- Контактный телефон: +7 900 026 4321
- Адрес электронной почты: ilya.chase@yandex.ru

## Образование
Высшее: факультет Вычислительной математики и информатики (ВМИ) ЮУрГУ, направление «Фундаментальная информатика и информационные технологии». Очно, бюджет.

## Опыт работы
- *Май 2016 – октябрь 2019.*
- *Компания: «[Hearst Shkulev Digital Regional Network](http://www.hearst-shkulev-media.ru/projects/rn/)».*
- *Должность: PHP-программист, Ведущий PHP-программист, Тимлид.*

## О себе
### Кратко о карьере
Сразу после защиты диплома получил должность PHP-программиста в 74.ru. Хотел именно туда, потому что 74.ru – это хайлоад, сложный продукт, разрабатываемый крутой командой. Уже к концу года получил повышение до Ведущего PHP-программиста. После интеграции 74.ru и NGS.ru, занимался такими проектами, как [НГС.Знакомства](https://love.ngs.ru/), [НГС.Афиша](https://afisha.ngs.ru/), [НГС.Форум](https://forum.ngs.ru/), [НГС.Объявления](https://do.ngs.ru/) и другими. Последний год занимал должность Тимлида.
Занимался все спектром разработки – не только код, но и инфраструктура, архитектура и дизайн приложений, CI\CD, улучшение процесса разработки (внедрял SCRUM), внедрение стандартов разработки. В свободное время [занимаюсь фрилансом](https://www.upwork.com/freelancers/~012c6b4205549a7dc4) на зарубежной бирже.

### О компетенциях
#### Код
В момент устройства в 74.ru, наша команда активно развивала проект, на котором «крутились» все сайты [сети Rugion](https://rugion.ru/stat/): 74.ru, 72.ru, 63.ru и остальные. Помимо новостных ресурсов, на том же коде работали classified-площадки: domchel.ru (сейчас интегрирован с N1), autochel.ru (сейчас интегрирован с auto.ru) и их зеркала на других регионах.

Код представлял собой рукописный фреймворк с более чем 1 300 000 строк (без учёта вендоров). В тот момент для меня это была самая сложная система, над которой я когда-либо работал. В результате, получил скачкообразный рост, познакомился со многими подходами (реализация отказоустойчивости, распределение нагрузки, организация кода в мульти-доменной многосервисной системе) и хайлоадными «фишками» (изменение структуры очень горячих таблиц, работа с «долгими» скриптами (от нескольких дней), умный stale-кэшинг и т.д.).

<img align="center" src="https://github.com/ilyachase/curriculum_vitae/blob/master/img/stanok_code_stats.jpg?raw=true" alt="Stanok code stats"/>

Далее были проекты вертикали НГС: Знакомства, Афиша, Форум, Объявления. Они были написаны давно на внутреннем фреймворке. По сути, все стандартные элементы любого фреймворка, но написанные руками: роутинг, request\response, ORM, CLI-команды.
Для НГС.Афиши писали новое API на фреймворке Slim, описывали Swagger'ом.

Последний год с новой командой, в которой я был Тимлидом, работали над всеми Форумами HSD RN (74.ru, NGS.RU, NN.RU и E1). Из наиболее запомнившегося можно выделить исходный код NN.RU, который в части сложности, запутанности и количества легаси переплюнул всё, с чем приходилось работать до этого. Приняли решение переписывать его постепенно, внедрив рядом микро-фреймворк Slim. Тем самым, бизнес-задачи не стопорились, а код постепенно переносился на новые рельсы. Опыт успешний, сделали несколько довольно крупных задач (например, рездизайн страницы темы на форуме), количество «живого» кода на новых рельсах увеличивалось, а стоимость разработки уменьшалась.

Помимо этого, имею представление о современном фронте: на [мобильную версию](https://m.love.ngs.ru/) НГС.Знакомств внедряли Webpack + Vue.js. Немного сам умею в Javascript: начинал как и все с jQuery, затем перешёл на ES6 и Vanilla. HTML, CSS, разумеется, знаю. Проявляю интерес к Golang (есть выполненные фриланс-заказы на нём).

#### Фреймворки
yii2, laravel, symfony, slim -> clean architecture
#### Инфраструктура
Nginx, haproxy, http, vim, mysql, ngrep, telnet. Sharding, replication
#### Тестирование
tests are awesome
#### Хранилища
relative, mongodb, no-sql, search engines
#### Мониторинг
Sentry, grafana
