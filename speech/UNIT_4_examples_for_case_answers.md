# UNIT 4 — примеры для второго задания билета

Этот файл сохраняет примеры курса для устного разбора кейсов. Каждая карточка содержит факт материала, переносимый принцип и английскую формулировку. Английские фразы — тренировочные пересказы, а не цитаты. Используй **одну подходящую карточку на ответ** и обязательно объясняй, почему она относится к проблеме билета.

Обычно нужно 20–35 секунд: **пример → что он показывает → как этот принцип применить к кейсу**. Не говори «на занятии я делал/видел», если тебя там не было. Говори “The course material described…” или “One example from UNIT 4 is…”.

## Быстрый выбор карточки

| Если кейс про… | Подойдут карточки |
|---|---|
| Ошибки модели, датчиков, данных, тестирование | 5 Digital twins; 6 поезд и термостат; 2 power supply |
| Объяснение пользователю, непонятный интерфейс | 1 solenoid; 3 analogies/PEER; 14 GPS; 15 modifiers |
| Изготовление, экономию ресурсов, обслуживание | 4 resin printing; 7 Refabricator; 8 concrete bridge |
| Восприятие, обучение, VR, обратную связь | 9 Walk the Plank; 10 виброжилет; 11 Bio4Eng/Eng4Bio |
| Импланты и материалы | 12 biomaterials; 13 scaffold |
| Приватность и ответственное использование | 16 ethics of digital twins |

## 1. Два определения соленоида

**Источник:** Class 1, [Introduction to Technical Communication](https://lms.mipt.ru/mod/page/view.php?id=225336).

**Что было:** для специалиста solenoid определялся через inductance coil и electromagnet; для широкой аудитории — через металлическую катушку, превращающую электрическую энергию в магнитную для выполнения механической функции.

**Принцип:** точность объяснения зависит не от количества сложных слов, а от соответствия языку и знаниям аудитории.

**Подходит:** непонятные инструкции, коммуникация с клиентом, обучение пользователя, объяснение технологии.

**Фраза:** “The course used two definitions of a solenoid for different audiences. This shows that technical information should be adapted to the reader's background. In this case, I would explain the function first and introduce specialised terms only when they are needed.”

**Лексика:** audience, definition, technical communication, clarity, function.

## 2. Лабораторный источник питания и ограничение тока

**Источник:** Class 1, описание Card 1 на той же странице.

**Что было:** прибор даёт регулируемое DC-питание. Один регулятор задаёт voltage, другой — current limit, чтобы защищать чувствительные схемы. Индикаторы позволяют видеть напряжение и ток во время тестирования.

**Принцип:** устройство должно не только выполнять основную функцию, но и ограничивать опасное воздействие; наблюдаемость помогает контролировать процесс.

**Подходит:** safeguards, защита оборудования, контролируемые испытания, мониторинг.

**Фраза:** “The bench power supply in the course had a current limit to protect sensitive circuits. This illustrates the value of a built-in safeguard. Similarly, I would add a limit or a fallback that reduces damage when the system operates outside reliable conditions.”

**Оговорка:** ограничение тока — конкретная защита электрической схемы. Для автомобиля переносится принцип ограничения риска, а не предлагается буквально поставить такой же регулятор.

**Лексика:** current limit, protect, monitor, prevent, sensitive circuits.

## 3. Дороги и кровеносные сосуды; PEER

**Источник:** Class 2, [Connecting with general audiences](https://lms.mipt.ru/mod/page/view.php?id=225364); [PEER](https://lms.mipt.ru/mod/page/view.php?id=219368).

**Что было:** blood vessels сравнивались с roads/highways, blood cells — с cars, blood clots — с traffic jams. PEER: Purpose, Example, Explanation, Recap.

**Принцип:** знакомый пример помогает объяснить новый механизм, но аналогия требует ограничения и научного уточнения.

**Подходит:** сложная технология для неспециалиста, инструкции, обучение, объяснение предложения комиссии.

**Фраза:** “The analogy between blood vessels and roads made an unfamiliar process easier to understand. I would use a similar approach here: explain the purpose, give a familiar example, describe the mechanism and recap the main point. However, I would also explain where the analogy becomes inaccurate.”

**Лексика:** analogy, metaphor, audience, accuracy, explanation.

## 4. Кислородная dead zone при печати смолой

**Источник:** Class 3, [Jigsaw Reading, Card 2](https://lms.mipt.ru/mod/page/view.php?id=225340).

**Что было:** фоточувствительная смола отверждается светом; кислородопроницаемое окно подавляет отверждение в тонкой зоне у дна. Деталь не прилипает к окну, и платформа может подниматься непрерывно. В тексте метод Joseph DeSimone связывается с ускорением печати.

**Принцип:** улучшение процесса может убрать конкретное узкое место; сначала надо понять, что ограничивает работу системы.

**Подходит:** низкая производительность, прилипание материала, оптимизация производства, targeted fix.

**Фраза:** “The resin-printing text described an oxygen-permeable window that prevents the part from sticking to the bottom of the vat. This removed a specific limitation of the process. I would apply the same reasoning here: identify the bottleneck and change the part of the process that causes it.”

**Оговорка:** кислородная зона подавляет отверждение локально, а не делает всю смолу непригодной для отверждения.

**Лексика:** resin, vat, cure, prevent, continuous, manufacturing.

## 5. Digital twin и расхождение с реальностью

**Источник:** Class 7, [текстовые фрагменты о digital twins](https://lms.mipt.ru/mod/page/view.php?id=225343).

**Что было:** оборудование изнашивается, среда и процессы меняются; двойник требует обновления. Важны data integrity, качество данных и поиск расхождений между simulated и real-world behaviour.

**Принцип:** модель полезна только в пределах проверенной связи с реальностью. Симуляция не заменяет все физические испытания.

**Подходит:** беспилотный автомобиль из образца билета, ошибки данных, удалённый мониторинг, проверка обновлённой системы.

**Фраза:** “The digital-twin material emphasised that simulated and real-world behaviour can diverge. This is relevant because a system may work in a simplified model but fail in difficult conditions. I would update the input data and compare simulation results with controlled real-world tests.”

**Лексика:** digital twin, simulated, diverge, static, data integrity, accurate, troubleshoot.

## 6. Автономный поезд и бытовой термостат

**Источник:** тот же Class 7, фрагмент Testing.

**Что было:** управление автономным поездом связано с гораздо большей прямой ответственностью, чем управление домашним термостатом. Число, характер и сложность тестов зависят от criticality системы.

**Принцип:** требования к проверке должны соответствовать тяжести последствий сбоя.

**Подходит:** безопасность транспорта, медицинское устройство, аргумент против слишком простых тестов.

**Фраза:** “The course compared an autonomous train with a residential thermostat. The consequences of failure are different, so the tests should not be equally demanding. In this case, I would focus on the failures that could cause the most serious harm.”

**Оговорка:** это сравнение требований и ответственности, не утверждение, что термостат не требует проверки.

**Лексика:** liability, testing, criticality, real-world behaviour, ensure.

## 7. NASA Refabricator

**Источник:** Class 3 / Homework Week 2, видео *3D Printing Is Changing the World*, полная расшифровка hw2.txt.

**Что было:** машина объединяет 3D-печать и переработку. Использованную деталь можно переработать в filament для нового изделия. Связано с экономией ресурсов и уменьшением зависимости космических миссий от поставок с Земли.

**Принцип:** проектировать нужно весь цикл использования материала, включая переработку и повторное применение.

**Подходит:** sustainability, удалённая эксплуатация, нехватка ресурсов, waste, supply chains.

**Фраза:** “NASA's Refabricator combined a 3D printer with a recycler. Used parts could become filament for new objects, creating a closed-loop life cycle. This example suggests that we should consider reuse and maintenance, not only the initial production of a device.”

**Оговорка:** это пример конкретного подхода, а не доказательство, что любой материал можно перерабатывать бесконечно без ухудшения свойств.

**Лексика:** filament, closed-loop life cycle, recycle, supply chain, enabling technology.

## 8. Напечатанный бетонный мост и решётчатая структура

**Источник:** Class 3, Jigsaw Reading, Card 3.

**Что было:** мост в Alcobendas возле Мадрида, 12 м, установлен в 2016 году; lattice structure проектировали алгоритмами для прочности при меньшем расходе материала. Текст отдельно оговаривал: более доступное строительство может привести к росту количества сооружений.

**Принцип:** оптимизация геометрии помогает экономить материал; экологический эффект нужно оценивать на уровне общего применения технологии.

**Подходит:** structural design, лёгкость/прочность, carbon footprint, строительство.

**Фраза:** “The concrete-bridge text described a lattice structure designed to maintain strength while using less material. This shows that geometry can be as important as material selection. However, the text also warned that cheaper construction could encourage more building, so the overall environmental effect needs to be assessed.”

**Лексика:** lattice structure, strength, fabricate, implications, carbon footprint.

## 9. Walk the Plank и согласованность чувств

**Источник:** [Homework Week 3, текст Beyond AR vs. VR](https://lms.mipt.ru/mod/page/view.php?id=225428).

**Что было:** VR-высота может вызвать настоящий страх даже при понимании, что среда цифровая. Добавление реальной доски под ноги связывает touch со зрением и слухом и усиливает immersion.

**Принцип:** реальные реакции пользователя зависят от совокупности сенсорных сигналов. Интерфейс нельзя оценить только по качеству картинки.

**Подходит:** VR training, интерфейсы, haptic feedback, дискомфорт, восприятие пользователя.

**Фраза:** “The Walk the Plank example showed that adding a physical plank makes a virtual experience more immersive. The visual and tactile signals support each other. For this case, I would check whether the different forms of feedback are coherent and help the user understand what is happening.”

**Лексика:** immersive, coherent, perception, tactile, virtual reality.

## 10. Виброжилет Jonathan

**Источник:** Class 7 / Homework Week 4, *New Senses for Humans*, полная расшифровка hw4.txt.

**Что было:** звук с планшета преобразуется в рисунок вибраций на жилете. Глухой участник Jonathan после четырёх дней тренировок по два часа в день распознавал отдельные слова в показанной демонстрации.

**Принцип:** информацию можно передавать через другой сенсорный канал; работа интерфейса требует обучения и проверки с пользователем.

**Подходит:** accessibility, sensory substitution, новые интерфейсы, feedback, обучение.

**Фраза:** “David Eagleman's talk described a vest that translated sound into vibration patterns. A deaf participant learned to recognise individual words through these patterns. This suggests that an alternative sensory channel can be useful, but the interface must be tested and users may need training.”

**Оговорка:** не говори, что он получил обычный слух за четыре дня. В демонстрации показано распознавание отдельных слов; дальнейшие эффекты были ожиданиями исследователей.

**Лексика:** sensory substitution, perception, vibration, haptic, electrochemical signals, Umwelt.

## 11. Bio4Eng и Eng4Bio

**Источник:** Class 7; домашний текст Biomechatronics.

**Что было:** Bio4Eng — использование биологии для инженерии, например bird-like robot eNandu и adhesive gripper TaCare. Eng4Bio — инженерные системы для биологии и человека, например exoskeleton Leviaktor и walker eRolli.

**Принцип:** важно определить направление заимствования: копируем полезный принцип природы или создаём систему для помощи живому организму.

**Подходит:** робототехника, протезы, экзоскелеты, biomimetics, multidisciplinary design.

**Фраза:** “UNIT 4 distinguished biology for engineering from engineering for biology. A bird-like robot uses a biological idea to improve a machine, while an exoskeleton uses engineering to support a person. For this case, I would first clarify which function we want to reproduce or assist.”

**Лексика:** biomimetics, biomechatronics, exoskeleton, mimic, multidisciplinary.

## 12. Прочный имплант может оказаться неподходящим

**Источник:** Class 8, [Engineering Considerations for Biomaterials in Life Sciences](https://lms.mipt.ru/mod/page/view.php?id=236809).

**Что было:** отличная механическая конструкция не устраняет immune response, toxicity, allergenicity или infection. Материал, поверхность, изготовление и стерилизация влияют на итоговую безопасность.

**Принцип:** качество изделия определяется несколькими взаимодействующими требованиями; улучшение одного показателя не гарантирует успеха всей системы.

**Подходит:** material selection, импланты, contamination, отказ медицинского устройства.

**Фраза:** “The biomaterials article explained that an implant can fail even when its mechanical design is excellent. Engineers must also consider immune reactions, toxicity, allergies and infection. Therefore, I would evaluate both the functional performance and the interaction with the biological environment.”

**Оговорка:** биосовместимость оценивается для конкретного применения; «безопасный материал» не означает автоматически пригодный для любого места и срока контакта.

**Лексика:** biocompatibility, adverse reactions, inflammation, contamination, antimicrobial coatings.

## 13. Scaffold и компромисс между пористостью и прочностью

**Источник:** Class 8, статья и словарь Biocompatibility.

**Что было:** поры помогают tissue ingrowth, vascularization и переносу веществ; их размер и количество нужно выбирать под применение. Временный каркас должен разлагаться в соответствии с ростом ткани.

**Принцип:** «больше полезного свойства» не всегда лучше: рост пористости может ухудшить механическую прочность. Нужен баланс требований.

**Подходит:** tissue engineering, porous structures, drug delivery, optimisation, trade-offs.

**Фраза:** “A tissue scaffold must support cell growth while maintaining enough mechanical strength. Higher porosity can improve transport, but it may weaken the structure. I would therefore choose the geometry and degradation rate according to the needs of the target tissue.”

**Лексика:** scaffold, porosity, biodegradation, strength, vascularization, bioactive.

## 14. GPS и новое полезное применение

**Источник:** Homework Week 5, полный разговор hw5.txt; [technical description](https://lms.mipt.ru/mod/page/view.php?id=225352).

**Что было:** помимо navigation, GPS применяется для tracking; drift alarm предупреждает о сносе лодки, man-overboard button сохраняет позицию падения человека. В разговоре подчёркивается поиск новых полезных применений технологии, точность которой пользователю уже достаточно хороша.

**Принцип:** решение проблемы не обязательно требует новой фундаментальной технологии; иногда достаточно подходящей функции и понятного действия пользователя.

**Подходит:** product improvement, функциональность, предупреждения, user needs, prioritisation.

**Фраза:** “The GPS conversation described a man-overboard function that saves a location so the boat can return to it. The innovation was a useful application of existing technology. In this case, I would first ask whether a practical new feature could solve the user's problem before developing an entirely new system.”

**Лексика:** core function, allow, enable, ensure, prevent, tracking.

## 15. Misplaced modifiers и точность инструкции

**Источник:** Class 7, примеры Microsoft Style Guide на странице занятия.

**Что было:** расположение only меняет ограничение высказывания; “that can’t be removed” может ошибочно или двусмысленно относиться к files либо disk.

**Принцип:** двусмысленность технической инструкции — возможный источник неправильного действия, даже если сама технология работает.

**Подходит:** инструкции, human error, технические описания, интерфейсы предупреждений.

**Фраза:** “The modifier examples showed how word placement can make a technical instruction ambiguous. I would rewrite the message so that the action and its target are clear. Then I would check whether users interpret it in the intended way.”

**Лексика:** clear, coherent, technical description, modifier, user.

## 16. Этические риски цифровых двойников

**Источник:** [Classes 9–10, дополнительный текст](https://lms.mipt.ru/mod/page/view.php?id=225350).

**Что было:** цифровые двойники людей и здоровья могут поддерживать новые сервисы, но создают вопросы приватности, human dignity и контроля. Текст обсуждал in-body surveillance, body hacking, кражу медицинских данных и identity theft; подчёркивал участие людей в управлении данными.

**Принцип:** полезность системы нужно оценивать вместе с последствиями сбора и использования данных.

**Подходит:** мониторинг здоровья, персональные данные, digital twins, social implications.

**Фраза:** “The ethical reading warned that digital twins of human health could expose sensitive personal data. A useful monitoring system therefore needs appropriate protection and clear control over data use. I would consider who can access the data and whether collecting it is necessary for the stated purpose.”

**Оговорка:** это аргумент из учебного текста, а не утверждение, что все описанные риски уже реализовались в конкретном устройстве кейса.

**Лексика:** peril, dilemma, implications, human dignity, personal data, surveillance.

## Три тренировочных переноса на новые кейсы

Эти ситуации придуманы для тренировки и не являются официальными билетами.

### A. Цифровой двойник оборудования даёт неправильный прогноз

**Тезис:** сначала проверить качество данных и актуальность модели.

**Аргумент:** оборудование изнашивается; модель может оставаться прежней и перестать отражать текущую систему.

**Пример:** карточка 5, simulated vs real-world behaviour.

**Решение:** проверить входные данные, обновить параметры, сравнить прогноз с измерениями; определить границы надёжного использования.

**Английская связка:** “The course material explains why a digital twin must evolve with the physical system. I would check whether the model still represents the current equipment before relying on its predictions.”

### B. Пористый каркас хорошо поддерживает клетки, но слишком слаб

**Тезис:** нужно пересмотреть геометрию и баланс требований.

**Аргумент:** транспорт и рост ткани улучшаются не независимо от механической прочности.

**Пример:** карточка 13, scaffold.

**Решение:** подобрать структуру и материал под нагрузки и ткань; проверить механическую работу, транспорт и темп разложения.

**Английская связка:** “The scaffold example shows that increasing porosity can create a mechanical trade-off. I would optimise the structure rather than maximise one property in isolation.”

### C. Пользователь не понимает предупреждение нового устройства

**Тезис:** пересмотреть сообщение и форму обратной связи.

**Аргумент:** сложные термины или двусмысленность не дают человеку понять действие; дополнительные сигналы помогают только при ясном смысле.

**Пример:** карточка 1 или 15; если речь об осязании — карточка 10.

**Решение:** писать под аудиторию; явно назвать действие; проверить понимание с пользователями.

**Английская связка:** “The solenoid definitions show why the explanation must match the user's background. I would simplify the warning and test whether users understand what action they should take.”

## Минимум для заучивания

Если запоминаешь только четыре карточки, возьми **5 — digital twins, 10 — виброжилет, 13 — scaffold, 14 — GPS**. Они покрывают моделирование, интерфейсы, материалы и полезность технологии. Для билета о машине особенно подходят **5 и 6**; это связь по принципу проверки и ответственности, а не утверждение, что UNIT 4 подробно изучал автомобильный алгоритм.

Помни: факт курса → принцип → применение к кейсу. Этой цепочки достаточно, чтобы пример стал аргументом.
