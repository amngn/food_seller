Данный проект оказался одним из самых интересных за время обучения на ЯП. Захотелось сохранить его здесь.

Навыки и нструменты: python (pandas, numpy, plotly, matplotlib). А/A/B-тестирование.

# Сборный проект №2

## Описание проекта
Стартапу, который продаёт продукты питания нужно разобраться, как ведут себя пользователи мобильного приложения. 

Необходимо изучить воронку продаж. Узнать, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах? На каких именно?

После этого исследовать результаты A/A/B-эксперимента. Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. 

### Описание данных

Каждая запись в логе — это действие пользователя, или событие. 

- *EventName* — название события;
- *DeviceIDHash* — уникальный идентификатор пользователя;
- *EventTimestamp* — время события;
- *ExpId* — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.
