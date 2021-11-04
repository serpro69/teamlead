# The cost and applicability of estimations

**[Estimation/estimating](https://www.merriam-webster.com/dictionary/estimating)** — to judge tentatively or approximately the value, worth, or significance of; to determine roughly the size, extent, or nature of; to produce a statement of the approximate cost of

The definition of ‘estimation’ states that one judges approximately the size or value of something.

**time estimation** is an attempt to determine how much time it will take for a subject to build an object.

Our industry is well-known for teamleads, product managers and others demanding estimations from the team or individual contributors.

I will try to investigate estimation limits to applicability and try to rationalise the use of the instrument.

Before considering the instrument effectiveness I need to clarify the goal — why the instrument is supposed to be used.

I’ve asked a question «why and what for do you need your team or individual contributors to estimate?», and these are the answers:
- to see team load/capacity
- public tender requires estimates
- ‘business’ needs to know ‘when’
- ‘business’ needs to understand how much the feature costs
- ‘business’ needs to be able to choose which feature to do first

I will go through each reason and dig deeper.

## To see team load/capacity

I honestly could not figure out how team load or capacity yields a necessity to gather estimates.

Companies create value for their clients and support features that clients value.

The request for the value might come from client themselves, from product manager, customer support. Also the request for support might come as a request to fix a defect.

If the team receives more requests than it can process, requests are logged, forming a backlog.

If the team is not delivering enough, there are a few ways to improve the situation:
- request less
- check the information flow in the system and optimise the processes
- hire more people

It is important to perform these activities in this particular order:

1. if hypotheses quality is improved and ‘better’ features come from product managers, there’s less need to optimise the information flow in development processes

2. if information loss is decreased in the development processes, existing team can do more and there’s no need to hire more people

3. hiring more people is the last and the least effective way of improving team performance as increasing team members count yields higher management complexity and costs

In any case I can’t see how ‘seeing team productivity’ is connected with estimations.

:heavy_minus_sign: **investing in estimations is not rationalised**

## Public tender has ‘time’ and ‘budget’ as a condition

The time and budget constraints are external to the company so if the company needs this contract it has to comply.

The company has to decide if producing the required system within required budget and time is economically beneficial.

:heavy_plus_sign: **investing in estimations is rationalised**

## Manager needs to know ‘when it will be done’

This request is very abstract.

Most common reasons for this request that I’ve heard are:

- marketing campaign starts on the X date and we need to understand if the team manages to build and launch a feature
- an external event with set date emerged (for example, FIFA world cup) and managers need to understand if certain features can be launched on time
- team coordination is required

### Marketing campaign

Marketing team works alongside IT team for the same company.

The whole company goal is to make client happier.

So why can’t these teams collaborate in a high-trust environment?

Can marketing predict exact number of sales they will generate for a certain budget (essentially, the outcome)?

If not, why does the IT team need to predict the outcome of their work?

Compare these two scenarios:
1. IT team produces some value for the clients and marketing team starts advertising this new value to potential and existing clients
2. Marketing team dictates the IT team ‘the advertising campaign will be launched on X date, you must be on time’.

To me it looks that the first scenario doesn’t provoke quality decrease and also doesn’t require spending resources on estimation.

:heavy_minus_sign: **investing in estimations is not rationalised**

### External event occurred

There might occur an external event which makes the company require estimation from the IT team.

todo: add examples?

For example, the country wins an opportunity to hold UEFA championship. Then the company needs to invest time in estimating a certain set of features to make sure it’s worthy to invest money into building those features so that they are delivered before the UEFA championshop.

If the result of estimation shows that even the minimum minimorum of features can’t be built on time, the company will decide now to even start building these features.

There’s a good question though — how often do events like this occur?

In the example of UEFA championship there are two things to weigh and compare:
1. amount of resources required to estimate + amount of resources required for ensuring the project is done on time
2. the probability of country winning the UEFA championship

If the probability (2) is high, it might be beneficial to bid on it and prepare the software in advance and just turn it on when needed.

:heavy_plus_sign:/:heavy_minus_sign: **not sure if estimation is rationalised**

## manager needs to understand how much a certain feature costs to develop

There usually are two reasons for this particular request:
1. manager wants to compare features based on their cost
2. manager wants to understand if a certain feature ‘is worth it’

These reasons are deeply intervened.

First, before any development estimation is done, product ‘estimation’ needs to be reviewed.

If a manager ‘just tells to build the feature’ with no prediction on how the feature will benefit the clients and the company, there’s absolutely no need to do any ‘estimation’ of development.

In this scenario manager just throws unsupported guesses to the development team – pure leap of faith.

So in this scenario manager doesn’t get any estimations — manager first need to explain why the company needs the feature, i.e. why the manager is going to spend development team time and effort.

If our manager does provide economical rationalisation (i.e. product estimation) for the feature, next step is to check how accurate their estimations were.

If manager’s estimation accuracy is low, there’s no need to do development estimation, it is a ‘leap of faith’ anyway.

Here’s an illustration:

Let’s suppose both manager and IT team do their estimates:
- manager estimates feature A1 to bring $100k and B1 to bring $200k
- IT team estimates feature A1 to cost $30k and B1 to cost $50k

For simplicity let’s assume pure revenue from feature A1 according to the estimates has to be $70k, from B1 — $150k.

Seeing these estimates an obvious choice would be to do feature B1 as its revenue is bigger.

However, it later turns out that:
- feature A1 brought $200k and B1 brought $100
- feature A1 costed $50k and B1 costed $60k

If manager’s estimate is off 2 times 

Прогноз прибыли: Ф1 принесёт $100k, Ф2 принесёт $200k
Прогноз стоимости: Ф1 будет стоить $30k, Ф2 будет стоить $50k
Какова точность прогнозов бизнеса? Статистика есть?

Итак, мы решили делать какую-то из фичей. Дальше часто встаёт вопрос «стоит ли овчинка выделки».

#### 2. Чтобы понять, стоит ли овчинка выделки

Определение «стоит ли овчинка выделки» — это определение целесообразности разработки.

Логично заключить, что разработка тем целесообразнее, чем больше выгоды получит компания от реализации фичи.

Стало быть, нужно сравнить прогнозируемую стоимость разработки (выраженную во времени) и прогнозируемую выгоду от реализованной фичи.

Подразумевается, что, как и в предыдущем случае, бизнес _умеет_ более-менее достоверно прогнозировать «выхлоп» от фичи.

Предположим, что выбрана была фича с прогнозируемой выручкой $1M.

Как понять, стоит ли её брать в работу?

Если прогностическая мощность гипотезы бизнеса (о выручке от фичи) базируется на статистике того, как сбывались разные другие прогнозы бизнеса, кажется логичным взять такое же по прогностической мощности предсказание сроков исполнения фичи.

Если совсем просто:
- бизнес говорит «такая фича наверное принесёт $1M, мы раньше редко ошибались в прогнозах»
- команда разработки говорит «такая фича наверное займёт 2-5 недель, мы раньше редко ошибались в прогнозах больше, чем в 2,5 раза»

Понятно ли, что ценность прогноза «слева» (у бизнеса) сильно выше, чем ценность прогноза «справа» (у команды разработки)?

Вообще получается, что если бизнес «не умеет» прогнозировать выгоду от производимой фичи, то и прогнозировать сроки исполнения на стороне разработки нет никакого смысла.

Какой смысл пытаться разобраться, займёт производство фичи три недели или три месяца, если ни та ни другая инвестиция времени в производство не оправдана?

Если же бизнес признаёт, что гипотеза «фича выстрелит» является лишь «ощущением», то есть иррациональна полностью, то вполне резонно заключить, что требовать рационального подхода к разработке просто бессмысленно — ведь велика вероятность, что бизнес целый год приносит на реализацию фичи, не приносящие никакой прибыли.

:heavy_minus_sign: **Вывод: инвестиции в оценку времени не оправданы.**

## Стоимость оценки времени

Мы разобрались с причинами, которые могут вынуждать оценивать время выполнения задач. Мы также поняли, что оценить ещё не потраченное время — значит попытаться спрогнозировать, сколько занять может разработка.

Теперь разберёмся c типами оценок:
- оценка, основанная на статистике
- оценка, основанная на экспертном мнении

### Оценка, основанная на статистике

Если сотрудник или отдел уже выполнял похожие задачи много раз, можно построить примерную картину того, сколько времени подобные задачи занимали. Полученное время можно и использовать в виде оценки.

Стоимость процедуры оценки зависит от «точности» сопоставления текущей задачи и набора каких-то подобных задач, выполненных ранее. Чем точнее нужно сопоставить, тем больше времени приходится тратить на декомпозицию и «погружение» в задачу (тем ближе этот тип оценки становится к оценке на основе экспертного мнения).

Таким образом, чем больше накоплена история выполнения разных задач, и чем точнее удаётся сопоставить оцениваемую задачу с какой-то уже выполненной, тем точнее будет полученная на основе статистики оценка.

Если подобных задач ещё не было выполнено, оценка на основе статистики не может быть выдана.

### Оценка на основе экспертного мнения

Эксперт или эксперты могут проанализировать задачу и выдать свой прогноз просто основываясь на своём опыте и знаниях. По сути, этот тип оценки похож на оценку, основанную на статистике, только статистика и «чуйка» у каждого специалиста своя.

Чем крупнее по объёму задача, и чем точнее необходимо дать оценку, тем больше объём инвестиций в декомпозицию и проектирование.

Эти два типа оценки лежат в основе практически всех систем прогнозирования.

## Стоимость и точность оценки

Точность оценки прямо пропорциональна степени «понятности» оцениваемой задачи.

«Понятность» — это степень проработанности «чертежа», «плана», «скелета» — чего-то, что гарантированно будет однозначно интерпретировано и реализовано.

Возьмём за пример проект строительства котельной в г. Анадырь. Инженерно-строительная бригада может ответить точно, сколько займёт такое строительство, потому как осуществляться оно будет по точным чертежам и готовым сметам, с уточнениями в виде «северных» поправок.

Точно такую же котельную по точно такому же плану другая инженерно-строительная бригада такой же квалификации может выполнить за то же время в г. Анадырь.

Чертежи же, схемы и сметы, вместе с принципами строительства и необходимыми материалами прорабатывают в специальном НИИ строительства.

Процесс научно-исследовательской и опытно-конструкторской фазы давным-давно выполнен другими людьми, и инженерно-строительная бригада лишь компонует готовые стандарты и подходы, гарантированно работающие вместе с гарантированными рисками.

В случае производства ПО, требования и контекст всегда различны, готовых «чертежей» и смет не существует, процесс опытно-конструкторской (а порой и научно-исследовательской) «не устаканен».

## Проблемы, порождаемые оценкой времени

- время трансформируется в сроки
- сроки трансформируются в дедлайны
- дедлайны создают стресс

## Result

Investment in estimation is only rational if the ‘ready date’ is a constraint external to the company.