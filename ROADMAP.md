# MoneyBro
App for tracking daily spendings

<img src="/mockup/page1.jpg" width="250" />
<img src="/mockup/page2.jpg" width="250" />
<img src="/mockup/page3.jpg" width="250" />


MoneyBro
========

##Main Purpose:

Апликуха для трекинга прогресса накопления средств путем отслеживания дневных/недельных/месячных трат по категориям.


##User story:

==============================================

###Главная страница (страница 1)

==============================================

При загрузке приложения юзверь создает список целей и их стоимости и сумма ежемесячного бюджета
Например:
Месячный бюджет: - 30.000 грн

Goals:
Поехать на море - 20.000 грн
Купить платьечко - 1.000 грн
Поесть в ресторане - 500 грн

======================

###Страница 2

======================
После создания списка юзверу будет дана возможность вводить количество потраченых денег в текущем дне по категориям
Категории:

- Обязательные траты (например комуналка, счета за кредиты и т.п.) - заполняется раз в месяц или в начале месяца.
- Сопутствующие расходы (Еда, вода, пивко)
- Незапланированные траты (эта шляпка мне идет)

После добавления потраченых денег:
а) Если мы вышли за пределы дневного бюджета система автоматически пересчитывает дневные бюджеты для последующих дней (красный цвет со знаком минус: -200 грн)
в) Если мы постратили меньше запланированного, выводить где-то сумму сэкономленных денег в этот день (зеленый цвет с знаком +200 грн)

После ввода потраченых денег автоматически пересчитывать наши goals.

Прогресс Goals:

Прогресс по накоплению денег на наши цели показывать как прогресс бар, синий цвет
После накопления достаточной суммы для любой из целей цвет прогресс бара становится зеленым и рядом с целью выводится мотивирующее 
сообщение о том что цель достигнута.

======================================================================

###История трат за месяц и графики. Страница 3

======================================================================

Историю трат можно посмотреть тыкнув на кнопку Spends History

Страница Spends History:

На странице подут представлен календурь в котором можно выбрать месяц и день месяца. По умолчанию будет стоять предыдущий день
Под календарем выводится таблица Daily spendings в которой выводится таже инвофрмция что и на предыдущей странице (страница 2)

Дополнительно выводится таблица Monthly Spendings в которой будет отображен балан за выбранный месяц.

После выбора нового месяца\и\или\дня недели, таблицы перерисовываются, в дейли выводится информация за выбранный день
А в монсли выводится состояние месячного баланса за выбранный день.

================================


##Фичи
На второй странице после добавления траты все totals будут пересчитываться.





