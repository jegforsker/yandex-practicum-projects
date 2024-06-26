# Анализ бизнес-показателей

## Данные
Объектом исследования является развлекательное приложение Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки.  
Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:
- лог сервера с данными об их посещениях;  
- выгрузка их покупок за этот период;  
- рекламные расходы.  

## Задача
Разобраться в причинах убытков и наметить шаги для выхода из сложившейся ситуации

## Выводы
1) Кол-во клиентов в США гораздо выше, чем во всех странах Европы вместе взятых и покупают в США чаще, чем в остальных странах, однако стоимость привлечения клиентов в США в 1.5 раза выше, чем в странах Европы.  
2) Основная причина убытков, вероятно, заключается в нецелесообразном маркетинге, при котором большАя часть средств направлена на рекламу в tiptop, faceboom и adnonsense. Реклама в этих каналах не окупается, к примеру, за исследуемый период реклама в tiptop выросла в 1.5 раза. Общая сумма расходов на tiptop и faceboom составляет более 80% (от 105 тыс. у.е.), а на tiptop было потрачено больше половины от рекламного бюджета. Стоит отметить, что пользователи faceboom и adnonsense при этом плохо удерживаются.  
3) Возможно, пользователям в США не нравится функционал приложения, поскольку показатель удержания очень низок в каналах(tiptop, faceboom), на которые направлены огромные денежные вложения и в которых велика конверсия пользователей. Либо же реклама настроена неэффективно и не попадает к целевой аудитории.  

**Рекомендации:**
1) Пересмотреть рекламную политику, особенно в США. Вероятно, стоит снизить затраты на рекламу в Tiptop, Faceboom и AdNonSense и обратить внимание на другие каналы привлечения клиентов. Для США это YRabbit, MediaTornado. Для Европы - lambdaMediaAds. У них неплохая окупаемость и низкая стоимость привлечения клиентов. Например, показатель ROI у канала YRabbit составляет почти 300% при CAC, равном 0.2 у.е.  
2) Увеличить конверсию органических пользователей - их около 30% от всех пользователей, однако проценнт платящих среди них наименьший(около 2%).  
3) Удержание пользователей в европейских страна нестабильно. Присутствуют периоды, в которых кол-во пользователей проседает до нуля. Особенно это заметно в Германии. Вероятно, стоит увеличить расходы на рекламную кампанию в европейских странах, к тому же показатель CAC там даже снизился за рассматриваемый период, а все каналы привлечения покупателей окупаются, кроме adnonsense.

## Используемые библиотеки
pandas, matplotlib, seaborn, numpy, datetime
