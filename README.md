# bts_project_hse
Проект создан студентами ВШЭ по заказу Columbia Pictures
/// ///

Проект выполнен студентами ФЭН НИУ ВШЭ: 

Сотникова Ангелина

Муртазалиева Арина 

Рафф Антон


Цель проекта: выявить связь между фьючерсом на Bitcoin и фьючерсом на индекс S&P 500 и ввести переменную, прогнозирующую движение одного актива в зависимости от движения другого.

Для анализа использовались открытые данные с сайта Investing.com
Исследовали дату сделок, цену актива, наибольшее и наименьшее значения, объем дневных торгов и изменению цены в процентах

На данный момент имеет следующие выводы:

1) Цена фьючерса на Bitcoin и цена фьючерса на индекс S&P 500 не связаны. Используем для проверки гипотезы линейную регрессию и такой алгоритм машинного обучения, как случайный лес. 
2) Объем торгов фьючерса на Bitcoin и объем торгов фьючерса на S&P 500 не связаны. Используем для проверки гипотезы линейную регрессию и такой алгоритм машинного обучения, как случайный лес. 
3) В дальнейшем создаем переменную "Volatility" для каждого из рассматриваемых инструментов, в которой будет произведена классификация на "low", "high", "medium". H0 состоит в том, что по состоянию фондового рынка нельзя определить, как ведет себя рынок криптовалют.

