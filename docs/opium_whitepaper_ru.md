# Opium Protocol Whitepaper 

Opium Team 

v0.9, 1 Сентября 2020 

[TOC]

## 1 Абстрактно

Мы считаем что блокчейн индустрия нуждается в более профессиональных и децентрализованных финансовых деривативных продуктах и мы предлагаем децентрализованный протокол, позволяющий: создавать финансовые деривативы, осуществлять их сеттлмент  и трейдинг — и при этом легко интегрируемый с рынком криптовалют, традиционными финансовыми рынками и их участниками.

## 2 Вступление
Компания, разрабатывающая Opium Protocol была создана в 2017, индустрия крипто и цифровых валют сильно изменилась с тех пор. Мы были свидетелями "бычьего" и "медвежьего " циклов; зарождения "DeFi"- совершенно уникального в своем роде класса инструментов; всплеска активности эмитентов "стейбл-коинов";  многочисленных DAO с их многообразием подходов к моделям управления децентрализованными организациями... и другие инновации.
В этой секции мы проиллюстрируем явно растущий спрос на профессиональные инструменты децентрализованных деривативов и как Opium Protocol отвечает запросам рынка. 

### 2.1 Важность деривативов для эффективности финансовых рынков

Деривативы это ключевой компонент глобальной финансовой системы. Финансовые системы состоят из финансовых рынков, а финансовые рынки - суть, работа с рисками. Каждая транзакция сопровождается некоторой степенью риска для каждой из сторон сделки. Профессиональные участники рынка, такие как трейдеры, банки, инвестиционные компании стремятся минимизировать свои риски, дабы избежать финансовых потерь в случае непредвиденных\неподконтрольных обстоятельств (например высокая волатильность цены). Деривативы - это финансовые инструменты, которые позволяют участникам рынка очень гибко управлять своими рисками, ограничивая потенциальные потери без значительного урона потенциальной прибыли. Проще говоря, деривативы сглаживают прибыли и потери и, тем самым, предотвращают ликвидации системного характера и финансовые кризисы. 



### 2.2 Масштаб рынка деривативов

Рынок деривативов самый масштабный финансовый рынок мира. Например, глобальный рынок деривативов в 10 раз больше рынка кредитования и в 20 раз больше всего мирового ВВП. Общепринятое отношение размеров рынков денег\кредитов\деривативов оценивается как 1\10\100, то-есть, если взять любой финансовый рынок, то рынок его деривативов в 100 раз превышает рынок спот-сделок в этом классе активов. [1]
Когда поднимается вопрос о финансовых инструментах для риск-менеджмента, принято думать, что деривативы - это удел профессиональных трейдеров и институциональных участников рынка.
Что, безусловно, отчасти правда, однако самые обычные люди также активно вовлечены во взаимодействие и торговлю деривативами в повседневности, не придавая этому значения. Ведь деривативы - наиважнейшая составляющая большинства финансовых сервисов. Например, личный чековый счет, страховые полюса, ипотека... - всё это сервисы, которые не могли бы существовать без деривативов.[2]



###  2.3 Возможности для деривативов в DeFi.

Понятие "Децентрализованные финансы" (ил просто DeFi) подразумевает целую экосистему взаимно-совместимых (composable) протоколов , платформ и продуктов, децентрализованных (порой частично) и позволяющих конструировать финансовые продукты в этой архитектуре, без ограниченности доступа (permissionless). DeFi продукты обычно находятся где-то за пределами традиционной финансовой системы, но при этом зачастую вдохновлены оной, являясь эволюционными версиями традиционных финансовых продуктов. Эти продукты открыли и совершенно новые свойства и возможности рынку и сейчас активно тестируются. Экосистема DeFi становится платформой высоких потенциалов для финансовых деривативов благодаря присущим только ей преимуществам в сравнении с традиционными финансами. Перечислим самые значимые: 

- Апосредничество: Архитектура DeFi построена на технологии блокчейн, которая фундаментально имеет потенциал заменить некоторые ключевые функции из традиционного финансового сектора. Следовательно, деривативы на базе DeFi имеют потенциал исключить дорогие звенья прозрачными и недорогими инструментами. 
- Доступность к применению: Рынок децентрализованных деривативов по своей природе более открыт. Эти инструменты доступны любому, у кого есть интернет и Ethereum кошелек, ни ваша локация ни статус - не имеют значения. Аналогичные же инструменты в традиционном фин-секторе зачастую доступны лишь тем, кто проживает в богатых и развитых странах. Благодаря такой доступности потенциальный рынок DeFi еще обширнее, чем и без того огромный рынок традиционных финансов.
- Доступность к созданию: В традиционной финансовой системе процесс создания и размещения нового дериватива очень сложный и цена процедуры около 1 млн USD.По этому большинство деривативов создаются большими банками, монопольно диктующими свои условия и, порой предлагающие нечестные условия, повышая степень неэффективности рынка в целом. Создание же деривативов в DeFi является простой, быстрой и дешевой процедурой и может быть инициировано любым, кто умеет обращаться с интерфейсом протокола.

### 2.4 Потребность в большем числе деривативов в DeFi

На момент написания, рынки децентрализованных финансов всё еще находятся в стадии становления. Помимо общей капитализации, одним значительным индикатором этого состояния является коэффициент отношения объемов спот рынка DeFi к рынку DeFi деривативов, который даже близко не близок к принципу "1\10\100", о которым мы упоминали ранее. Этот факт делает очевидным предположение, что рынок деривативов в DeFi имеет гигантский потенциал роста. Почвой для подобного взрывного роста могут быть следующие факторы:

- На основании того, что рынок деривативов в Defi очень мал, можно предположить, что пользование DeFi продуктами сопровождается высокими (зачастую неявными) рисками для пользователя. На момент написания, самые популярные DeFi протоколы и продукты предоставляющие "торговое плечо" на волатильный актив, опираются на он-чейн пулы ликвидности для исполнения сделок. Что, в свою очередь, создаёт системный риск с "эффектом домино" (tail risks), затрагивающий абсолютно всех участников этих протоколов, а не только тех, кто использует эти протоколы для спекулятивных  "левередж" сделок. Участники, которые осознают эти риски уже активно ищут возможности хеджирования оных, например платформу Nexus Mutual, однако они уже не справляются с растущим спросом. [3]

Рынок DeFi деривативов ожидает экспоненциальный рост по мере роста и укрепления позиций всей экосистемы DeFi, делая деривативы объектом с уникальными возможностями как для инженеров так и для инвесторов.

- На основании вышеупомянутых положительных особенностей, приобретаемых деривативами  в DeFi среде, можно смело ожидать, что DeFi поглотит часть рынка деривативов из традиционного сектора.
  
- На протяжении последних нескольких лет мы были свидетелями растущего интереса к криптовалютам со стороны институциональных игроков.[4] Однако, на этом их участие не закончится. Эти крупные профессионалы также начнут вовлекаться во всю интернет-нативную финансовую систему, следствием чего станет увеличение ликвидности, объемов и конкуренции в  этой сфере. Эти игроки вряд ли охотно заинтересуются *yield-farming* стратегиями, ввиду сопряженных с ними катастрофическими рисками с "эффектом домино", но, вполне охотно будут предоставлять ликвидность на арбитражные и прочие стабильные стратегии с самыми минимальными рисками. Вне зависимости от того "как" они это будут делать, они БУДУТ нуждаться в инструментах риск-менеджмента. Им будут нужны расширенные деривативные инструменты. Им будут нужны финансовые примитивы с понятными и четко ограниченными потенциалами движения вверх или вниз.

Подытоживая, рынок DeFi деривативов обязан выйти на иные масштабы, чтобы удовлетворить запросы для грамотного риск-менеджмента в этой экосистеме.

------------------

## 3 Opium

Opium это протокол для создания, урегулирования и торговли деривативами в децентрализованной среде. В силу своей открытости и универсальности, Opium позволяет любому желающему создавать и выпускать собственные децентрализованные финансовые деривативные контракты. Комбинируя доступные механизмы оракулов с нашими механизмами деривативов, по-сути можно создать любой мыслимый вид деривативов. Трейдеры Opium деривативов получают свои позиции в виде токенов, которые могут быть переданы другому, проданы или направлены в холодные кошельки на хранение.  

​	В этой главе мы остановимся подробнее на команде проекта, концепции и потенциальных юз-кейсах, побудивших развитие Opium Protocol.

### 3.1 О команде Opium.

Компания, создавшая Opium была основана в 2017 без привлечения сторонних инвестиций. Opium работали над децентрализованными деривативами задолго до появления DeFi,
и изначально были сфокусированы на создании продукта привлекательного и понятного для участников из традиционных финансов. С 2017, Opium Protocol разрабатывался, досконально проходил аудит на безопасность командой SmartDec и был запущен в основной сети Ethereum . Opium создали и запустили три продукта на базе Opium Protocol.

#### 3.1.1 Продукты выпущенные командой Opium

**Opium Exchange** это открытая трейдинговая платформа для децентрализованных деривативов. Ранее мы создавали рынки для  ETH futures, gas options, бинарных опционов и премаркет еще не выпущенных DeFi токенов. Opium Exchange это место для хеджирования трейдинговых рисков и спекуляций на возможностях как внутри DeFi так и вне её. Opium Exchange намерена стать "Bloomberg для децентрализованных финансов",  с листингом из тысяч финансовых деривативных продуктов, открыто торгуемых и доступных всем![5]

**Swap Rate** это платформа, на которой вы можете захеджировать или спекулировать с флуктуациями процентных ставок на рынках DeFi. Свопы процентных ставок это самый популярный тип деривативов в мире и, в тоже время, важнейший элемент для построения продуктов с фиксированной процентной ставкой. Вне всяких сомнений - этот продукт будет играть значительную роль в будущем децентрализованных финансов.[6]

**The Art Exchange** первая в своем роде онлайн платформа для торговли деривативами на предметы изобразительного искусства и токенизированные арт-объекты. Проект явился следствием сотрудничества с The Art Newspaper; крупнейшим в мире медиа ресурсом по арте тематике и с целью сделать рынок изобразительного искусства более доступным.[7]

Помимо этого, Opium ведет переговоры с множеством организаций, заинтересованных в выпуске собственных экзотических деривативных инструментов (как то: olive oil futures, Spotify track futures, sports betting), используя Opium Protocol в качестве эмитента.[8]



#### 3.1.2 Бизнес модель

Как нейтральный, универсальный и высоко-ликвидный базовый слой для децентрализованных деривативов, Opium Protocol имеет все шансы стать своего рода "бэкендом" для множества Dapps (Decentralised Apps), создаваемых как маленькими командами так и целыми организациями по всему миру. Команда Opium продолжит заниматься разработкой и внедрением новых продуктов на базе нашего протокола. 

​	В Opium Protocol интегрирован механизм взымания комиссий, который применяется лишь к стороне, извлекшей прибыль в сделке. При этом 90% от комиссии идёт создателю деривативного контракта, а 10% остаётся внутри платформы. 

<img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20201221145912145.png" alt="image-20201221145912145" style="zoom:80%;" />Рис. 1: Opium Protocol как базовый слой для любых приложений, работающих с деривативами.



### 3.2 Преимущества протокола

Команда Opium Protocol имеет обширный опыт как в традиционных финансах так и DeFi, что позволяет нам созидать по настоящему визионерские решения в этом секторе. И это самым явным образом нашло отражение в дизайне Opium Protocol, который совершенно уникален в своём классе среди других аналогичных решений на рынке деривативов в DeFi.
В частности, уникальность Opium Protocol в его изначальной совместимости как с DeFi так и с традиционными финансовыми рынками. Большинство нынешних деривативных протоколов в DeFi подразумевают теоретически неограниченные риски вследствии полагания на он-чейн пулы ликвидности и AMM (Automatic Market Making) походы, что, на наш взгляд, скорее является шагом назад по отношению к рынку традиционных финансов. Мы, Opium, сторонники подхода, когда на самом базовом (он-чейн) уровне развернута максимально простая и прочная финансовая инфраструктура, которая в дальнейшем может бесконечно расширяться и усложняться как он-чейн так и офф-чейн, например используя Bloomberg-подобные продуктовые тикеры.

​	Opium Protocol является решением того самого прочного финансового примитива первого уровня. Более сложные механизмы(как то: ордер буки, расширенные деривативы, стратегии маркет-мейкинга, арбитраж, комбинированные ордера, динамическая цена и автоматизированные хедж-фонд стратегии) будут создаваться поверх, как "layer-2 решения". Именно такой подход позволил нам создать универсальный и стабильный протокол, на базе которого можно выпускать деривативы с полностью контролируемым риск-профилем, похожим на аналоги из традиционных финансов и отвечающим самым высоким запросам профессиональных игроков финансового рынка. 

<img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20201221152154143.png" alt="image-20201221152154143" style="zoom:67%;" />

Рис. 2: Многоуровневая архитектура деривативов



### 3.3 Примеры применения

Opium Protocol универсален и позволяет создавать любой тип деривативов. Ниже перечислим примеры продуктов, которые теоретически можно построить на базе Opium Protocol:

Options

- Call/put опционы на Ethereum gas price
-  Call/put опционы на YFI
-  Call/put опционы на BTC price
-  Call/put опционы на цену акции TSLA
-  Бинарные опционы на исход спортивных соревнований

Swaps
-  Interest rate swap на ставку по депозитам в USDC на платформе Compound 
-  Interest rate swap на ставку по займу в DAI на платформе AAVE
-  Credit default swap for Aave credit delegation lines

Pre-markets (ie. ZEPOs)
-  Premarkets for unreleased DeFi governance tokens (eg. Curve, YFI)
-  Premarkets for unreleased network tokens (eg. Polkadot, Cosmos, NEAR)

Фьючерсы
-  Futures на ETH
-  Futures на цену акции GOOGL
-  Futures на цену оливкового масла

Продвинутые комбинированные деривативы
-  Финансовая инженерия (напр. market-neutral стратегии на предоставление ликвидности)
-  Структурированные инструменты (напр. reverse convertibles захеджированные обыкновенными деривативами)

## 4 Описание Opium Protocol 

В этой секции мы остановимся на системной архитектуре Opium Protocol. Дизайн технической архитектуры Opium Protocol основан на следующих принципах:

1. Он-чейн компоненты финансовой системы даже теоретически должны исключать возможность неограниченных потерь\профитов. 

2. Одной из ключевых инноваций DeFi является возможность распределять право собственности над финансовой системой среди её пользователей. Дизайн архитектуры Opium предполагает децентрализованное управление платформой. 

На уровне ядра Opium Protocol совместим с этими принципами. Opium Protocol
исключает возможность создания инструментов с потенциально-неограниченным риском потерь\профита (благодаря фиксированному размеру обеспечения в виде **любого** ERC20 токена), протокол задеплоен в основной сети Ethereum, он полностью не-кастодиален и доступен любому.

Изначально Opium Protocol запущен в режиме централизованного управления нашей командой, чтобы на ранних стадиях максимально ускорить и упростить интеграцию. Однако постепенно управление будет целиком передано комьюнити и стейкхолдерам, методом распределения токена управления протоколом. Модель управления будет далее описана в этом документе.

### 4.1 Участники Opium Network

Opium Protocol предполагает быть использованным целой сетью участников, каждый из которых имеет свои уникальные стимулы для исполнения различных функций, которые, в классических финансах, берут на себя обычно банки и посредники.

  Точно также как на рынках классических деривативов, участниками Opium могут быть:

- Инвесторы

- Страховщики

- Спекулянты

- Маржинальные трейдеры

- Арбитражеры
  

И, в отличии от классических рынков, другие участники:

- Транспортные ноды (Relayers)

- Финансовые инженеры/дизайнеры деривативов

- Исполнители контрактов

- Брокеры, аффилированные представители и\или фронт-энд разработчики

- Держатели говерненс-токена (токен управления протоколом)

  

  ---------------------

### 4.2 Создание и матчинг ордеров

Технически, пользователи Opium Protocol заполняют ордера в соответствии с так называемой "*TMtm-спецификацией*", которая специально разработана так , чтобы быть похожей на спецификации ордеров из традиционных финансовых рынков. Спецификация предполагает, что каждый ордер содержит следующие переменные:

- T = Bid по деривативной позиции

- M = Bid по маржинальной позиции (в форме любого ERC-20 токена)

- t = Ask по деривативной позиции

- m = Ask по маржинальной позиции (в форме любого ERC-20 токена)

Каждый ордер содержит что и в каком количестве предложено и запрошено пользователем. Такой формат записи выступает универсальным методом для описания как простейших запросов, когда нужно произвести покупку\продажу актива, но в тоже время позволяет делать более комплексные запросы, например обмен актива А на актив Б с доплатой за разницу в их рыночной стоимости. Ордер далее подписывается приватным ключом пользователя и отправляется на транспортную ноду (relayer) в сети Opium Network.

TMtm-спецификация позволяет реализовать частичное исполнение ордеров с использованием даже частично-совместимых заявок. Это позволяет осуществлять свопы между открытыми позициями; что кардинально повышает эффективность ликвидности во всём протоколе и минимизирует необходимость минтинга и сжигания токенов новых позиций. В традиционных финансах профессиональные игроки исполняют комбинированные заявки через банки. Opium Protocol позволяет исполнять схожие комбинированные заявки без всяких посредников, открывая каждому участнику рынка доступ ко всей имеющейся на платформе ликвидности на равных со всеми условиях.   

Примеры TMtm запросов:

- <4xFuture | 0 | 0 | 6xUSDT> это ордер на продажу 4 Фьючерсов за 6 USDT Токенов
- <0 | 5xDAI | 10xOptions | 0> это ордер на покупку 10 Опционов за 5 DAI Токенов
- <4xFuture | 6xUSDT | 10xOptions | 0> это комбинированный ордер, производящий обмен [4 Фьючерса+6 USDT] на [10 Опционов]
- <4xFutureA | 0 | 8xFutureB | 0> это ордер на покупку 8 FutureB в обмен на 4
    FutureA
- <1xPortfolio | 0 | 0 | 1200xDAI> это ордер на продажу целого портфолио пользователя в обмен на 1200 DAI

### 4.3 Опциональные комиссии протокола

Каждый дериватив, создаваемый на базе Opium Protocol имеет параметр взымаемой комиссии. Он **может быть нулевым**. Если он отличен от нуля, то комиссию оплачивает профит-мейкер в сделке с этим контрактом. Размер комиссии устанавливается создателем дериватива и он же получает 90% комиссии. **Оставшаяся часть в размере 10% уходит в счет Opium Protocol**. 



### 4.4 Техническая схема

Opium Protocol состоит из множества системных компонент, часть которых расположены он-чейн тогда как другая часть офф-чейн. Схема ниже наглядно показывает эти компоненты, их связи и функции.

<img src="C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20201222114423079.png" alt="image-20201222114423079" style="zoom:67%;" />

Рис. 3: Техническая схема Opium Protocol



### 4.4.1 Relayer

Транспортные узлы (далее будем использовать оригинальный термин "Relayers" или "релееры") это внешние игроки, которые матчат ордера пользователей офф-чейн и затем отправляют их в блокчейн. Интерес этих участников складывается из комиссий за сделки, формируемые на их узле (размер комиссий устанавливается каждым "релеером" индивидуально и может быть нулевым), фактически узлы выступают высокоуровневым (layer-2) трейдинг-интерфейсом доступа к ликвидности протокола и они формируют собственные ордер-буки. Relayers также получают прибыль реализуя арбитражные возможности между всем рынком и платформами, к которым у них есть доступ, тем самым поднимая эффективность всего рынка в целом. Концепция "релееров" стала широко известной благодаря другому DeFi протоколу - 0x (Zero-X protocol) и имплементация их в Opium следует тому же принципу. 

### 4.4.2 Opium Match 

Представляет собой смарт-контракт, который выполняет роль моста к он-чейн компонентам Opium Protocol. Смарт-контракт Opium Match проверяет валидность ордеров, заключенных в офф-чейн, и создаёт новые позиции из залоченных маржинальных токенов (чаще всего стейбл-коины, но технически могут быть любые ERC-20 токены) и исполняет свопы между Opium Position токенами и ERC-20 токенами. Пользователи дают права доступа этому смарт-контракту, чтобы он мог перемещать их токены в соответствии с деталями исполняемой заявки. В большинстве случаев "релееры" просто отправляют сматченные ими ордера на Opium Match контракт. Также можно проводить и OTC сделки, такие ордера отправляются напрямую Opium Match контракту, минуя "релееров".

-----------------------

### 4.4.3 Opium Core

Техническое сердце Opium Protocol состоит из набора смарт-контрактов в основной сети
Ethereum и мы называем это "Opium Core". Opium Core активизирует все ключевые компоненты системы на основании входящих данных и заранее он-чейн зафиксированной логики.

Контракты финансовых деривативов создающиеся на Opium Protocol состоят из двух важнейших компонент: 

- The derivative recipe 

- An oracle recipe. 

**The derivative recipe** представляет из себя набор логики, которая отвечает за то, каким образом замороженное в смарт-контракте обеспечение (margin) перераспределяется к выплате сторонам по истечении срока жизни контракта. 

**An oracle recipe** описывает то, какие именно и из каких источников берутся данные (он-чейн или офф-чейн) и как эти данные будут обработаны("поняты") системой. *Derivative*
и *oracle recipes* регистрируются в соответствующих *derivative* и *oracle* реестрах.
Данные о обеспечении(margin) позиций хранятся в *derivative register* а данные, полученные от оракулов хранятся в *oracle register* . Opium Core направляет все данные, полученные от oracle recipe в *oracle register*, чтобы затем выполнить расчеты в *derivative recipe*.

Поскольку *derivative* и *oracle recipes*  Тьюринг-полные, они могут быть подвержены любым логическим операциям. Так, например, вы можете создать деривативный продукт на волатильность цены любого актива, на факт наступления какого либо события, например банкротство, а также политические или спортивные события. Благодаря Opium пользователи могут сами создавать смарт-контракты(деривативные продукты), внутри которых заложена логика из всевозможных комбинаций *derivative recipes + oracle recipes*. Opium Core, живущий он-чейн, проверяет входные параметры  *derivative* и *oracle recipe*, такие как : maturity(срок истечения), margin(обеспечение) и, например, strike price; после чего смарт-контракт *token minter* создаёт long и short токены.

### 4.4.4 Opium Minter

Длинные и короткие позиции пользователей Opium Protocol токенизированы в виде *Opium
Derivative Tokens* в стандарте ERC-721о (на конце буква "о"). Так как токены позиций Opium обратно совместимы с ERC-721 стандартом то пользователи могут как торговать своими обеспеченными токенизированными позициями на вторичном и OTC рынке так отправлять их на холодные кошельки для хранения с повышенной безопасностью.[9]

Помимо упомянутых манипуляций, пользователи также могут конструировать и деконструировать из набора позиций токенизированные портфолио (далее *Opium Portfolio*), которое также является токеном ERC-721o стандарта. Помимо экономии газа, это позволяет пользователям, например, торговать спреды, индексы, целые портфолио и другие финансовые продукты, избегая при этом риска частичного исполнения комбинированных ордеров.

***Opium Minter*** это смарт-контракт, отвечающий за минтинг (создание) *Opium Derivative*
и *Opium Portfolio* токенов. Когда два сматченных ордера успешно прошли через *Opium Match*
и *Opium Core* смарт-контракты, смарт-контракт Opium Minter минтит новые *Opium Derivative* токены (от имени Core смарт-контракта) и также  сжигает\уничтожает их после исполнения контракта. **Minter** также занимается сборкой\разборкой и перегруппировкой *Opium derivative* токенов в *Opium portfolio* токены.



## 5 Управление Opium Protocol

Команда Opium верит, что децентрализованное управление в лице активного и заинтересованного в успешности платформы комьюнити стейкхолдеров, создаёт самый прочный и при этом гибкий фундамент для выстраивания open-finance инфраструктуры. Команда Opium держится на плечах инноваторов [10] [11] [12], помимо собственного опыта впитавших знания из различных мероприятий и команд - пионеров новых методологий и моделей управления финансовыми протоколами и грамотной децентрализацией управления оными.[13]

Мы предлагаем модель управления с применением токена управления ($OPIUM). Модель управления, как и токеномика управляющего токена будут подробно раскрыты в этой секции.

### 5.1 О управлении Opium 

Opium Protocol нуждается в активном децентрализованном управлении множества параметров, чтобы по-настоящему создать протокол, несущий ценность своему комьюнити. Результатом этого станет создание соответствующих децентрализованных деривативов с достаточной ликвидностью, что в свою очередь привлечет еще больше пользователей и ликвидности в экосистему Opium. 

Модель управления основана на DAO (decentralised autonomous organisation) и
AragonDAO в качестве основного референса. Токенхолдеры $OPIUM взаимодействуют с DAO через подачу предложений (governance proposals) и голосования за\против ранее опубликованных предложений. Принятые предложения оказывают самое непосредственное влияние как на Opium Protocol так и на поведение стейкхолдеров.

Одним из ключевых параметров, который будет подконтролен токенхолдерам $OPIUM, это объем выделяемых из фонда проекта токенов управления $OPIUM. В интересах экосистемы Opium - каждую неделю фиксированное число $OPIUM токенов высвобождается из фонда и распределяется среди ***активных пользователей*** протокола. Этот механизм похож на уже хорошо зарекомендовавший себя в DeFi среде т.н "майнинг ликвидности" (liquidity mining), но имеет более широкие возможности благодаря своей особенности при необходимости изменять критерии термина "активный пользователь". Ниже перечислим несколько сценариев, которые могут быть реализованы через этот механизм:

- Предоставление ликвидности в ордербуке для рынка деривативов

- Выпуск CDSs и опционов

- Увеличение TVL (Total Value Locked) в протоколе Opium.

- Разработка значимых (пользующихся высоким спросом) деривативных продуктов на Opium

- Стимулирование провайдеров ликвидности в пулах и проектах, работоспособность которых особенно выгодна экосистеме Opium  (например деривативы в качестве обеспечения, Balancer пулы с $OPIUM)

Токенхолдеры $OPIUM голосуют за предложения, которые определяют *ликвидити-майнинг* логику и распределение управляющего токена. 

С момента запуска механизма децентрализованного управления протоколом, ему будут подчинены абсолютно все аспекты Opium Protocol: изменение параметров DAO и права доступа, исполнение действий от имени DAO, управление средствами фонда активных пользователей, а также внесение изменений в код Opium Protocol. Любые новые параметры, добавленные к механизму управления в результате изменения кодовой базы протокола, также будут целиком подчинены Opium DAO .

### 5.2 Токеномика $OPIUM 

Выпущено будет 100.000.000 $OPIUM. распределение планируется следующим образом:

#### 5.2.1 60%: Активные пользователи

Этот фонд будет использован для распределения управления среди активных пользователей протокола во благо всей экосистемы Opium, как было описано ранее. Само определение термина **"активный пользователь"** имеет динамический характер и будет периодически уточняться через голосование Opium Protocol DAO. Часть токенов фонда может быть направлена на решение конкретных задач, например - предоставление ликвидности на том или ином инструменте; в качестве средств за создание новых инструментов на платформе и любые другие необходимые активности. Токены фонда будут высвобождаться постепенно и ретроспективно распределяться среди *активных участников* комьюнити на основании критериев, заложенных в этот термин. 

#### 5.2.2 16%: Инвесторы и адвайзеры

Средства фонда также будут использованы в качестве вознаграждения ранних инвесторов и адвайзеров за их поддержку и вклад в развитие Opium. Эта часть будет высвобождаться (Vesting) на протяжении последующих 2х лет.

#### 5.2.3 14%: Команда Opium 

Эта часть фонда будет направлена на погашение затрат текущей команды проекта, а также на расширение команды по мере необходимости. Часть этих токенов пойдет непосредственно текущим членам команды. Период высвобождения этой части фонда составляет 4 года. 

#### 5.2.4 10%: Резервный фонд управления 

Этот фонд будет использован для стимулирования внешних инициатив и партнёрств, которые выгодны экосистеме Opium и потенциально помогают её росту и процветанию. Эта часть фонда целиком подконтрольна Opium Protocol DAO и используется через процедуры предложений и голосований держателями токена $OPIUM .

## 6 Дорожная карта

Opium Protocol и текущие продукты, созданные на его базе уже были аудированы и доступны в основной сети Ethereum. Однако, команда Opium видит большой простор для улучшения Opium Network. В этой секции остановимся на ключевых технических задачах в дорожной карте команды Opium.

### 6.1 Opium Protocol v2

Большая часть ключевых компонент Opium Protocol базируются на open-source смарт-контрактах расположенных в основной сети Ethereum. Чтобы улучшить совместимость Opium Protocol с другими DeFi протоколами, а также добиться эффективной работы механизмов децентрализованного управления, предстоит произвести рефакторинг некоторых ключевых смарт-контрактов. Самые очевидные улучшения, которые можно ожидать от второй версии протокола включают в себя имплементацию DAO механик и поддержку токенизированных открытых позиций других протоколов(например aDAI).

### 6.2 Opium Exchange v2

Opium Exchange был запущен в Мае 2020 и является флагманским продуктом, созданный на базе Opium Protocol. Команда Opium получила ценнейшие отклики от пользователей за это время, которые будут учтены при создании полноценной новой версии Opium Exchange .

### 6.3 Интеграция Hummingbot

Hummingbot это open-source маркет-мейкер бот институционального класса, который позволит профессиональным маркет-мейкерам получить необходимый и достаточный функционал для предоставления ликвидности в Opium Protocol с применением автоматических маркет-мейкинг стратегий. Интеграция через API и заложенные базовые маркет-мейкинг стратегии позволят подключить маркет-мейкеров из круга профессиональной сети команды Opium.

### 6.4 Имплементация L2 решений для масштабирования

Opium Protocol построен на базе блокчейна Ethereum, чья пропускная способность имеет свои пределы. Даже несмотря на то, что Opium Protocol высоко-оптимизирован на уровне ядра и потребляет минимум газа и использует такие методы оптимизаций газа, как офф-чейн мета-транзакции - пользователи в конечном итоге всё равно оперируют с блокчейном Ethereum и, как следствие - стоимость транзакций порой бывает чрезмерно высокой. Имплементация решений масштабирования второго уровня (layer 2 scaling solution) на уровне протокола является одной из первоочередных наших технических задач, поскольку это кардинально скажется на улучшении юзабилити всей платформы для пользователей а также сделает платформу значительно интереснее для институциональных игроков из традиционных финансовых рынков.  Команда Opium изучает все имеющиеся на рынке L2-решения (в том числе zkRollups) и тестирует их готовность для применения в продакшене.

## 7 Резюме

Финансовые деривативы это важнейший компонент любого взрослого финансового рынка, поскольку они позволяют реализовывать риск-менеджмент. Рынок децентрализованных финансовых деривативов ожидает экспоненциальный рост относительно роста сектора децентрализованных финансов в целом и, как следствие, ему необходима прочная финансовая инфраструктура.

Opium это финансовый протокол для построения децентрализованных финансовых деривативных продуктов. Opium Protocol полностью некастодиален и выстроен на базе открытого исходного кода смарт-контрактов. Будучи с одной стороны максимально выдержанным в философии децентрализованных финансов и полностью совместимым со всей DeFi экосистемой, Opium Protocol, с другой стороны, с самых первых строк кода разрабатывался так, чтобы стать понятным институциональным игрокам и совместимым с традиционным финансовым сектором.

Неотъемлемым свойством каждого финансового деривативного инструмента, созданного на базе Opium Protocol является ограничение в размерах потенциальных потерь (и выигрыше, соответственно) а также автоматический листинг инструмента в виде Bloomberg-подобных тикеров. Благодаря управленческому токену $OPIUM и механизмам управления DAO, Opium Protocol и вся экосистема проекта со временем полностью перейдёт под контроль управления распределенной группой индивидуалов и организаций по всему миру.

## 8 Приложение

### 8.1 FAQ

Эта секция содержит некоторые часто задаваемые вопросы относительно Opium Protocol и ответы н них.

**Что такое деривативы?**

Финансовые дериватив это соглашение между двумя (или более) сторонами, стоимость которого зависит от цены набора финансовых активов(т.н "базовые активы), зафиксированных условиями этого соглашения. Изменение цены базового актива отражается в цене деривативного договора по той логике, которая зафиксирована в договоре.

**Опасны ли деривативы и могут ли они быть причиной финансового кризиса?**

Финансовые деривативы часто осуждают в связи с кризисом 2008 года, при этом, однако, зачастую забывая о существенной разнице между разными видами деривативов. Финансовые деривативы с хорошим обеспечением (collateralized and overcollateralized derivatives) в действительности наоборот - помогают избежать финансовых кризисов, не требуют риск-менеджмента и идеально подходят для он-чейн сеттлментна. Тогда как деривативы с частичным обеспечением (Undercollateralized), требуют грамотного риск-менеджмента, процедур маржин-колов и, безусловно, повышают риски возникновения кризисных ситуаций с "эффектом домино". Все деривативы, созданные на базе первого уровня Opium Protocol, полностью обеспечены фиксированной маржой, при этом полностью прозрачны, поскольку используют блокчейн Ethereum в качестве сеттлмент слоя. По этому, любой может проверить качество обеспечения любого дериватива, выпущенного на Opium Protocol.

**В чем преимущество Opium Protocol относительно традиционного фин-сектора?**

Opium Protocol позволяет создавать децентрализованные деривативы, рынок которых значительно более доступен и открыт нежели рынки традиционных финансов. Любой, у кого есть доступ к интернет и кошелек в блокчейне Ethereum, имеет доступ к рынку децентрализованных финансов, вне зависимости от локации и социального статуса. 

Другим очевидным преимуществом является стоимость, скорость и простота, с которой любой может создавать собственные деривативные продукты на Opium Protocol. В традиционной финансовой системе процесс создания и листинга нового деривативного продукта крайне сложный и требует внушительных финансовых затрат, которые имеют категории сотен тысяч долларов. По этому, подавляющее большинство деривативов создаются большими банками, которые, в свою очередь, могут делать это на условиях своих локальных интересов, делая правила игры нечестными для других участников рынка и, как следствие - деля рынок в целом менее эффективным по отношению к DeFi.

**В чем отличие Opium от других протоколов деривативов в DeFi?**

Уникальность Opium Protocol в том, что он изначально совместим со стандартами профессионального рынка традиционных финансов.
Вместо того, чтобы опираться на он-чейн пулы ликвидности, которые несут с собой теоретический риск неограниченных потерь и профитов, Opium предлагает простой и устойчивый финансовый примитив. Трейдеры могут гибко настраивать свой экспожер на рынок благодаря комбинированию финансовых примитивов (например используя опционы с фиксированным обеспечением).

Opium также предлагает инструменты и программы стимулирования для провайдеров ликвидности как для участников DeFi так и профессионалов из традиционных финансов.

И наконец, Opium предоставляет листинг продуктов в виде Bloomberg-подобных тикеров.

**Как Opium Protocol планирует привлечь провайдеров ликвидности?**

Три фактора призваны оказать положительный эффект на решение этой задачи:

1. Преимущество ранних участников растущего рынка: Экспоненциальный рост рынка DeFi
и стремительные инновации происходящие в этом секторе создают органический спрос на востребованные финансовые деривативы(например пре-маркет на еще невыпущенные токены)
2. Распределение токенов управления: $OPIUM токен и модель управления Opium
предполагают возможность реализации всевозможных инициатив для привлечения провайдеров ликвидности там, где это необходимо.
3. Привлечение профессиональных маркет-мейкеров из традиционных финансов: Благодаря  интеграции автоматизированных маркет-мейкинг ботов (как Hummingbot) и активного привлечения профессиональных трейдеров, будет привлечена ликвидность извне DeFi.

**Могу ли я создать деривативный продукт на Opium Protocol ?**
Протокол открыт и не требует чьего либо разрешения для работы с ним, по этому любой может создать финансовый дериватив на базе Opium Protocol. Техническая документация будет доступна на Opium
Gitbook.[14]

**В чем заключается бизнес модель при создании продуктов на Opium Protocol ?**

Opium Protocol предоставляет своим пользователям механизм для взымания комиссий, которые уплачиваются той стороной, которая получила профит в сделке. Создатель деривативного контракта сам определяет размер комиссий, при этом 90% всех комиссий сгенерированных этим инструментом получает создатель контракта. Оставшиеся 10% остаются внутри протокола.

**Насколько безопасно пользоваться Opium Protocol ?**

Opium Protocol прошел аудит на известные бреши по безопасности независимой организацией
SmartDec. Отчёт доступен онлайн. [15]

## Ссылки

[1] J. Maverick, “How big is the derivatives market?.” https://www.investopedia.com/ ask/answers/052715/how-big-derivatives-market.asp. 

[2] “The global derivatives market, deutsche b¨orse group.” https://www.math.nyu.edu/ faculty/avellane/global_derivatives_market.pdf. 

[3] “Nexus mutual, application.” https://app.nexusmutual.io/#/SmartContractCover. 

[4] “Growing number of institutional investors believe that digital assets should be a part of their investment portfolios, according to new research from fidelity digital assets, fielity investments.” https://www.fidelitydigitalassets.com/bin-public/ 060_www_fidelity_com/documents/FDAS/institutional-investor-study.pdf. 

[5] “Opium exchange, application.” https://opium.exchange/. 

[6] “Swap rate, application.” http://swaprate.finance/. 

[7] “The art exchange, application.” https://theart.exchange/. 

[8] F. Quiros, “Nace en espa˜na un mercado financiero descentralizado de futuros y opciones sobre el aceite de oliva.” https://es.cointelegraph.com/news/ a-decentralized-financial-market-for-olive-oil-futures-and-options-is-born-in-spain. 

[9] “Erc720o token standard.” https://github.com/OpiumProtocol/erc721o. 

[10] R. Leshner, “Compound governance announcement.” https://medium.com/ compound-finance/compound-governance-decentralized-b18659f811e0. 

[11] S. Kulechov, “Aavenomics announcement.” https://medium.com/aave/ aavenomics-eeab650cccc2. 

[12] A. Cronje, “Yfi announcement.” https://medium.com/iearn/yfi-df84573db81. 

[13] J. Walden, “Progressive decentralization.” https://a16z.com/2020/01/09/ progressive-decentralization-crypto-product-management/. 

[14] “Opium gitbook.” https://docs.opium.network/. 

[15] “Opium protocol security audit report.” https://blog.smartdec.net/ opium-smart-contracts-security-analysis-4c1857cfd93f.