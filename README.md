RFMD или идея доработки RFM-анализа

Разрабатывая какие-то маркетинговые мероприятия, проводя перед этим RFM-анализ, мы видим количественный 2D-портрет клиента - давность, частота, траты. И в этом портрете нет качественного показателя, значимости этого клиента для компании. Чтобы эффективно тратить бюджет, нужно видеть 3D-портреты наших клиентов. 

Привожу выдержку из одной статьи про RFM-анализ. 
“111 — те, кто покупают часто, на большие суммы и посетили магазин совсем недавно. В общем, идеальный тип клиента, который приносит до 80% прибыли. Ваша задача — удерживать их в таком состоянии как можно дольше.” 

А вы уверены, что таких нужно удерживать? Я - нет. Привожу пример.

Например, клиент, из сегмента “111”, который тратит по 100.000 руб в месяц, но покупает товары только с самым глубоким дисконтом для перепродажи в своем магазине принес компании 2000 руб/мес, а обычный клиент “223, который покупает раз в месяц на 10.000 без каких-либо скидок, приносит компании 3500 руб. ежемесячно. Второй интереснее для нас, не правда ли?
А если мы еще учтем величину переменных издержек пропорционально купленным объемам товаров, то разрыв увеличится еще больше.
Зачем нам удерживать и тратить деньги на такого “111”, если он и сам приходит, все находит, и знает все лучше нас?

По моему мнению, показатель, отражающий среднюю скидку всех покупок нашего клиента (назовем ее DISCOUNT) позволила бы нам лучше понять 3D-портрет клиента, а значит еще более точно настроить маркетинговые мероприятия.

В связи с этим, родилась идея уменьшить сегментацию в привычных RFM-секторах до двух (хорошо/плохо - точные параметры границы настраиваем исходя из целей компании) и добавить показатель D - discount. И вот этот показатель как раз целесообразно разделить на три сегмента
Практически без скидок (0-10%)
Средние размеры скидок (10-30%)
Глубокие скидки (>30%)

Получился RFMD-анализ.

И наши привычные RFM-сектора начинают совершенно иначе играть в разрезе данных категорий. Будем ли мы тратить деньги на клиента, средняя скидка предыдущих покупок у которого 45%, хоть он часто покупает, хоть редко, хоть недавно или давно, хоть на 10.000, хоть на 1 млн.руб, теперь это почти не имеет значения, потому что компания отдает ему товары “в ноль” и почти ничего не зарабатывает, мы начинаем видеть качественный портрет клиента.

Именно такую модель я попытался реализовать с помощью Python и синтетических данных и выборочно оформить бизнес-выводы.


