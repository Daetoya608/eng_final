# UNIT 5 — рассказы по темам для устной подготовки

## Как использовать этот файл

Здесь **15 тематических рассказов на английском** по UNIT 5 *Human Factors and Ergonomics*: содержание аудиторных занятий и Homework, русский контекст, примеры из курса, словосочетания и вопросы для проговаривания. Это запас идей для ответа на разные вопросы, особенно для второго типа задания. Выбирай из него подходящий пример и объясняй его связь с проблемой билета.

Тексты — составленные пересказы, а не цитаты или расшифровки ответов преподавателя. Рекомендации и учебные примеры, добавленные для объяснения, отдельно обозначены. Не нужно говорить, что ты участвовал в обсуждении, если тебя не было: **“The course material described…” / “One case in the unit showed…”**.

Учи рассказ по схеме **понятие → как работает → пример из курса → польза → ограничение**. Прочитай русский контекст, разбери английский текст, выпиши пять опорных слов, закрой файл и перескажи. Сначала 40–60 секунд, затем около двух минут. Если времени мало, учи смысл и примеры, а не каждую фразу.

### Карта тем и занятий

| № | Тема рассказа | Где в курсе |
|---|---|---|
| 1 | Software engineering и SDLC | HA Week 6, Class 11, hw6.txt |
| 2 | Провал студенческого мобильного приложения | Class 11 |
| 3 | Как работают cyber attacks и защита | Class 11 |
| 4 | Пять спорных решений по кибербезопасности | Class 11 |
| 5 | AI, phishing, deepfakes и shadow AI | HA Week 7, hw7.txt |
| 6 | Usability vs user experience; работа UX designer | Class 12, TV Week 6 |
| 7 | Ergonomics: рабочее место кассира и системное мышление | Class 13, HA Week 7 |
| 8 | Эргономика смартфона | Class 12 |
| 9 | Googleplex и среда для сотрудников | Class 14, TV Week 7 |
| 10 | Design thinking, personas, scenarios и user flows | Class 14, TV Week 7 |
| 11 | Прототип для МФТИ и Engineering Design Contest | Weeks 8–10, Graded Task 5.3 |
| 12 | Презентации: audience, speaker, transformation | Classes 16–17, HA Week 9, hw9.txt |
| 13 | Conciseness и progress report | Classes 15 и 20, HA Weeks 8 и 10 |
| 14 | Technical description: flat-plate solar collector | Class 18 |
| 15 | The Safer, Smarter Smartphone | Additional Case Study |

UNIT 5 охватывает **Classes 11–20**. На Class 19 — финал конкурса; отдельного нового теоретического текста на этой странице нет. В HA Week 6 есть переход из UNIT 4: technical description haptic technology / 3D printer из Class 10. Его контекст уже есть в предыдущем файле UNIT 4; ниже основное внимание материалу UNIT 5.

## 1. Software engineering и жизненный цикл разработки

### О чём материал

Домашний текст **What Is Software Engineering?** объясняет, почему software engineering шире программирования: разработчик отвечает не только за код, но и за архитектуру, надёжность, безопасность, масштабируемость и сопровождение системы. В **hw6.txt** предприниматель Adam хочет интернет-магазин товаров для дома, а его cousin Mark объясняет шесть стадий SDLC. Class 11 использует эти идеи для разбора неудачного приложения.

Источники: [HA Week 6](https://lms.mipt.ru/mod/page/view.php?id=238512), [Class 11](https://lms.mipt.ru/mod/page/view.php?id=238229), hw6.txt.

### Рассказ на английском

Software engineering is the systematic design, development, testing and maintenance of software systems. Programming is part of it, but an engineer also has to consider reliability, security and the future development of the product. A program may work today and still be difficult or expensive to maintain later.

The homework text described the relationship between hardware, the operating system and applications. Hardware provides resources such as memory and processors. The operating system manages these resources, while applications allow users to perform tasks. Software architecture defines how the components of an application are organised and communicate.

The homework video explained the software development life cycle through an online store project. Adam wanted to sell home decoration products, and Mark explained six stages. Planning identifies the purpose and intended users. Requirement analysis turns these needs into detailed specifications, including security requirements. Design defines the architecture. Implementation produces the code. Testing checks the product in different environments. Deployment makes it available, and maintenance deals with problems and improvements after release.

The video mentioned an SRS, or Software Requirements Specification, and a DDS, or Design Document Specification. These documents help people agree on what they are building and how they will build it.

The main lesson is that successful development requires coordination across the whole life cycle. Testing and feedback should influence the design, and releasing a product does not end the engineer's responsibility.

### Ещё детали для контекста

- В видео при анализе требований обсуждаются validation, security и риски; это не только список экранов.
- При coding упоминаются языки программирования, guidelines, compilers и debuggers.
- Найденные QA ошибки возвращаются разработчикам: testing → debugging → повторная проверка.
- Схема видео выглядит последовательной, но реальные изменения и результаты проверки могут возвращать команду к предыдущим решениям.
- **Scalable** — система выдерживает рост нагрузки; **maintainable** — её можно исправлять и развивать без чрезмерных затрат.

### Что перенести в кейс

Если приложение постоянно ломается, проверь требования, архитектуру и тестирование. «Нанять ещё программиста» не объясняет, почему проблема возникла и как её предотвратить.

**Сочетания:** clarify requirements — уточнить требования; design the architecture — спроектировать архитектуру; deploy an application — выпустить приложение; maintain a software system — сопровождать систему; respond to changing user needs — учитывать меняющиеся потребности.

**Проговори:** чем software engineering отличается от coding? Что делают на каждой стадии SDLC? Почему maintenance начинается после релиза, но должна учитываться заранее?

## 2. Failed Mobile Application Project

### О чём материал

Конкретный кейс Class 11: небольшая технологическая компания разрабатывала приложение для студентов — расписание, дедлайны и экзамены. Планировалось закончить за три месяца. Команда: **one project manager, three developers, one tester**. Требования были неясными, дизайн слабым, тестирование ограниченным. Пользователи жаловались на crashes, неправильную работу функций и неудобный touchscreen interface; выросли maintenance costs.

Источник: [Class 11](https://lms.mipt.ru/mod/page/view.php?id=238229).

### Рассказ на английском

One case in Unit 5 described an unsuccessful mobile application for university students. The application was intended to help them manage their schedules, deadlines and exams. The project was expected to take three months, and the team included a project manager, three developers and one tester.

Several problems appeared during development. The requirements were unclear, the design was weak and testing was limited. After release, users reported crashes, features that did not work correctly and a confusing touchscreen interface. Maintaining the application became expensive.

This case shows how problems at different stages of development can reinforce each other. If the team does not understand students' needs, it may implement the wrong functions. If the architecture is poorly planned, later changes may introduce more bugs. If testing happens too late, serious problems may only become visible after release.

My proposed response would be to review the requirements with students and the university client. The team could identify the most important tasks and create a simple prototype before adding more features. Developers and the tester should check core functions regularly, while usability testing should reveal whether students understand the interface.

The project manager would need to coordinate priorities and communicate realistic progress. Success should be measured through reliable task completion, understandable navigation and manageable maintenance costs. The lesson is that delivering an application quickly is not enough: it must solve the user's problem and remain dependable.

### Ещё детали для контекста

- Проблемы и состав команды — факты учебного кейса. Предложенный план исправления в рассказе — подготовленное рассуждение, а не опубликованное «официальное решение».
- Для преподавателя удобно различать **functional testing**: работает ли напоминание, и **usability testing**: может ли студент найти и настроить его.
- Возможная проверка решения: число crashes, доля успешно выполненных задач, ошибки навигации, время выполнения. В LMS исходных численных результатов нет.
- Роли: university client формулирует потребность; PM согласует объём и сроки; software engineer проектирует и реализует; tester проверяет.

### Что перенести в кейс

Это универсальный пример для тем requirements, software architecture, teamwork, user feedback и iterative refinement. Объясняй цепочку причины и последствия, а затем способ проверки.

**Сочетания:** unclear requirements — неясные требования; limited testing — недостаточное тестирование; frequent crashes — частые сбои; prioritise core functions — выделить основные функции; reduce maintenance costs — уменьшить затраты на сопровождение.

**Проговори:** где именно мог начаться провал? Почему работающий код не гарантирует хороший продукт? Кто должен собирать обратную связь?

## 3. Cyber attacks: уязвимости, malware и защита

### О чём материал

Текст **How Cyber Attacks Work** связывает software bugs, unauthorized access, malware, networks и servers. Вредоносные программы могут распространяться между машинами, заражённые устройства могут входить в botnet; ransomware лишает доступа к данным. Обсуждается, почему antivirus недостаточно и почему нужны updates и backups. Отдельно предлагается оценить риски компании с 50 сотрудниками.

Источник: [Class 11](https://lms.mipt.ru/mod/page/view.php?id=238229).

### Рассказ на английском

Cybersecurity concerns the protection of systems and information against unauthorised access, damage and disruption. The reading in Unit 5 explained that attackers may exploit software bugs to enter a system. A small defect can have serious consequences if it allows access to sensitive information.

Malware is software designed to cause harm or perform unauthorised actions. The lesson mentioned viruses, spyware and ransomware. Spyware can collect information, while ransomware can make data inaccessible and demand payment. Infected machines may also become part of a botnet, a group of devices used for coordinated malicious activity.

Networks connect systems, so an infection may spread beyond the first device. Servers can be attractive targets because they may hold information belonging to many users. This means that the consequences of an attack depend on both individual devices and the wider system design.

The text discussed antivirus software, upgrades and backups. Antivirus can detect some threats, but it cannot guarantee complete protection. Security updates address vulnerabilities, while backups help recover data after an incident. However, restoring files does not undo the disclosure of confidential information.

The class also considered a company with fifty employees and weaknesses such as missing updates, poor network segmentation and no backups. My conclusion is that protection requires several measures working together. Engineers should consider prevention, detection, containment and recovery, and employees should understand how their actions can affect security.

### Ещё детали для контекста

- В списке рисков компании: no regular upgrades, no antivirus, poor segmentation, unencoded storage и no backups. Приоритет зависит от данных, вероятности и ущерба; в материалах нет универсальной правильной сортировки.
- **Bug** — ошибка; **vulnerability** — слабость, которую можно использовать для атаки. Не каждая ошибка обязательно является уязвимостью.
- В LMS слово **encode** местами используется широко. Для конфиденциальности точнее **encrypt**: шифровать; простое изменение формата/кодирование не гарантирует защиты.
- Backups помогают recovery, segmentation — containment, updates — prevention. Ни одна мера не заменяет все остальные.
- **Cybercrime** — преступная деятельность; не стоит автоматически использовать hacker как синоним любого преступника вне конкретного кейса.

### Что перенести в кейс

Когда требуется улучшить безопасность, свяжи каждую меру с риском. Объясни, что именно обновление предотвращает, что сегментация ограничивает и что резервная копия восстанавливает.

**Сочетания:** exploit a vulnerability — использовать уязвимость; gain unauthorised access — получить несанкционированный доступ; retrieve data — извлечь данные; install security updates — установить обновления безопасности; contain an infection — ограничить распространение заражения.

**Проговори:** почему сервер важен для атакующего? Чем отличаются prevention и recovery? Почему «антивирус ничего не нашёл» не равно «атаки нет»?

## 4. Пять кейсов о решениях по кибербезопасности

### О чём материал

Class 11 предлагает не только термины, но и пять ситуаций с конфликтом целей: **Successful Upgrade; Invisible Bug; Backup Paradox; Network Efficiency vs Security; Ethical Grey Zone**. Они полезны для второго задания: показывают, как обсуждать риск, сроки, стоимость, эффективность и профессиональную ответственность.

Источник: [Class 11](https://lms.mipt.ru/mod/page/view.php?id=238229).

### Рассказ на английском

The cybersecurity cases in Unit 5 showed that technical decisions often involve competing priorities. In the Successful Upgrade case, a company upgraded its servers and network and passed its tests. Three months later, confidential information leaked, although antivirus software reported no obvious problem. The case suggests that a successful test does not prove that every vulnerability has been removed.

The Invisible Bug case involved a minor bug that did not affect performance. Fixing it required several hours of server downtime, so the repair was postponed for two weeks. An attacker then used the bug to enter the system. This illustrates the difficulty of balancing availability with security.

In the Backup Paradox case, fast recovery encouraged management to reduce preventive protection. However, customer information was later exposed. Backups helped with recovery but could not protect confidentiality after disclosure.

Another case concerned network efficiency. Simplifying security reduced latency, but later malware spread quickly through the network. The final case considered a company whose antivirus product could not detect a certain type of attack, although it was marketed as comprehensive protection.

These examples show why engineers should examine more than immediate performance. They should assess possible consequences, communicate limitations and explain trade-offs to decision-makers. My proposed approach would be to investigate the cause, compare options and define how the chosen solution will be checked. Hiding uncertainty can create greater technical and ethical problems later.

### Ещё детали для контекста

- **Successful Upgrade:** по условиям нельзя установить точный способ утечки. Не говори уверенно, что это phishing, insider или конкретная уязвимость: сначала investigation.
- **Invisible Bug:** важен security impact, даже если performance impact мал. Дедлайн не делает ошибку безопасной.
- **Backup Paradox:** часть customer data была публично раскрыта. Нельзя «отменить» утечку восстановлением системы.
- **Network Efficiency vs Security:** быстрые операции и ограничение распространения атак — разные критерии качества.
- **Ethical Grey Zone:** вопрос честного раскрытия ограничений продукта и возможного риска для клиентов. Нет готовой реплики, которую надо выдавать за позицию преподавателя.

### Что перенести в кейс

Удобная схема: **immediate benefit → hidden risk → affected stakeholders → safer option → validation**. Не просто «security is important», а конкретное объяснение ущерба и компромисса.

**Сочетания:** balance availability and security — сопоставить доступность и безопасность; postpone a repair — отложить исправление; disclose limitations — сообщить об ограничениях; assess the potential impact — оценить возможный ущерб; make an informed decision — принять обоснованное решение.

**Проговори:** почему успешное обновление не гарантирует защиты? Как объяснить руководителю необходимость downtime? В чём этическая проблема рекламы антивируса?

## 5. AI и cybersecurity: материал видео из Homework

### О чём материал

**hw7.txt соответствует Cybersecurity Trends в HA Week 7.** Это видео IBM Technology о прогнозах **на 2025 год и далее**, а не актуальный обзор на дату экзамена. Speaker обсуждает AI-powered phishing, deepfakes, hallucinations, shadow AI, атаки на AI systems и применение AI защитниками. Важная пара: **security for AI** и **AI for security**.

Источники: [HA Week 7](https://lms.mipt.ru/mod/page/view.php?id=225436), hw7.txt.

### Рассказ на английском

The homework video discussed cybersecurity trends for 2025 and beyond. Its central idea was that artificial intelligence can help both attackers and defenders. We should understand these as the speaker's discussion and predictions, rather than assume that every prediction has already come true.

AI can make phishing messages more convincing and personalised. Poor grammar is therefore not a reliable way to identify every suspicious message. Deepfakes create another problem by imitating a person's voice or appearance. The speaker described a case in which a fake video meeting appeared to involve a chief financial officer and led to a transfer of twenty-five million dollars.

The video also introduced shadow AI: employees using AI tools without organisational approval. Such use may expose confidential information or introduce unreliable outputs into business decisions. AI systems themselves can also become targets, so organisations need security for AI as well as AI for security.

On the defensive side, AI can help analysts summarise incidents and identify priorities. However, the speaker discussed hallucinations, meaning confident but incorrect outputs. Human review and checking against reliable information remain necessary.

Another concern was the collection of encrypted information for possible decryption in the future using more powerful technologies. The broader lesson is that organisations should understand changing risks, verify sensitive requests through trusted channels and evaluate AI tools before relying on them. A useful tool still needs clear rules and informed supervision.

### Ещё детали для контекста

- История о deepfake CFO и $25 million — пример, приведённый speaker. Не превращай её в рассказ о личном опыте или подтверждённую тобой текущую статистику.
- Пример hallucination: неправильный перевод бегового темпа из min/km в min/mile. Он показывает, что уверенная форма ответа не гарантирует правильность.
- **Security for AI:** защищать данные и саму AI-систему; **AI for security:** использовать AI для анализа инцидентов и помощи специалисту.
- **Attack surface:** совокупность точек, через которые можно атаковать систему. Добавление нового инструмента создаёт дополнительные зависимости и риски.
- **Prompt injection** в видео — попытка направить поведение модели вопреки её назначению. Здесь нужен смысл термина, а не способы проведения атаки.
- **Harvest now, decrypt later:** собирать шифротекст сейчас в расчёте на будущее расшифрование. Видео обсуждает quantum-safe/post-quantum переход; оно не доказывает, что все современные системы уже взломаны.
- В расшифровке есть неоднозначные формулировки и числа. Они не использованы как точная статистика или универсальные прогнозы.

### Что перенести в кейс

Если организация внедряет AI, обсуждай approved tools, data handling, verification и human oversight. Для подозрительного запроса — независимая проверка через заранее известный канал; голос или изображение сами по себе не гарантируют подлинность.

**Сочетания:** convincing phishing messages — убедительные фишинговые сообщения; impersonate a trusted person — выдавать себя за доверенное лицо; expose confidential information — раскрыть конфиденциальные сведения; verify a sensitive request — проверить важный запрос; keep a human in the loop — сохранить участие человека в проверке.

**Проговори:** чем AI полезен защитнику и атакующему? Что такое shadow AI? Почему грамотное письмо и видеозвонок не дают полной уверенности?

## 6. Usability vs user experience и работа UX designer

### О чём материал

Текст **Usability vs User Experience** различает выполнение конкретной задачи и опыт пользователя в целом. В usability важны **effectiveness, efficiency, satisfaction** в определённом контексте. UX охватывает путь пользователя, понятность, ценность, доступность и впечатления. Вторая часть текста — обязанности UX designer: research, wireframes, mockups, testing и post-release analysis.

Источник: [Class 12](https://lms.mipt.ru/mod/page/view.php?id=225365), TV_Week_6_RU.pdf.

### Рассказ на английском

Usability describes how effectively, efficiently and satisfactorily particular users can complete particular tasks in a given context. Effectiveness concerns whether they achieve the goal. Efficiency concerns the effort and resources required. Satisfaction concerns how acceptable the interaction is to them.

User experience is broader. It includes the user's journey, expectations, feelings and perception of value. A product may allow a task to be completed and still create frustration through confusing information or an unpleasant overall experience.

The reading in Unit 5 described several ways to improve UX. Designers should make the value of a product clear, use understandable wording and imagery, support accessibility and organise navigation logically. They should refine interactions, remove unnecessary steps and question assumptions about what users actually do.

The text also explained the work of a UX designer. Research and interviews help identify needs. Wireframes show the structure of an interface, while mockups communicate its appearance. Usability testing reveals where users get confused, and analysis after release helps identify further roadblocks in the workflow.

For example, a student application might contain all the required information, but students may struggle to find the next exam. This is an illustrative example of the distinction: the feature exists, yet the interaction needs improvement. My conclusion is that design should be evaluated through real tasks and feedback, rather than appearance alone. Understanding the whole journey helps engineers create products that people can use and want to use.

### Ещё детали для контекста

- Пример с поиском экзамена — пояснение, связанное с кейсом Class 11; отдельного такого результата UX testing в тексте Class 12 нет.
- **Value proposition:** почему продукт полезен именно этому пользователю. **Onboarding:** первые шаги и освоение продукта.
- Accessibility связана в тексте с пользователями, имеющими physical limitations. Понятная навигация и wording тоже влияют на доступность.
- Wireframe — схема структуры; mockup — представление внешнего вида; prototype может позволять проверять взаимодействие. Это связанные, но не тождественные вещи.
- Текст упоминает skills в graphic layout, language, иногда HTML/CSS; основной акцент — понимание задач человека и проверка решений.
- **Imagery** здесь можно понимать как визуальные образы в интерфейсе. Не ограничивай его литературной «образностью» из словарной дефиниции.

### Что перенести в кейс

Раздели «функция существует», «пользователь может её выполнить» и «весь опыт приемлем». Предложи наблюдать реальные задачи и проверить, уменьшились ли roadblocks.

**Сочетания:** improve task completion — улучшить выполнение задачи; refine the interaction — доработать взаимодействие; challenge assumptions — проверять допущения; identify roadblocks — выявлять препятствия; gather user feedback — собирать обратную связь.

**Проговори:** чем usability отличается от UX? Что делают до и после релиза? Зачем тестировать интерфейс, если дизайнеру всё понятно?

## 7. Ergonomics: рабочее место кассира

### О чём материал

В HA Week 7 описана **Applied Ergonomics and Engineering Problem-Solving Thinking**. Engineering consultancy получила заказ крупной retail chain и отбирает сотрудников через реальные задачи. Подготовка посвящена ergonomic specifications для **retail cashier**; команда должна обосновать решение и показать карту своего мышления. В Class 13 — Graded Task 5.1 и ссылка на LOOPY.

Источники: [Class 13](https://lms.mipt.ru/mod/page/view.php?id=225363), [HA Week 7](https://lms.mipt.ru/mod/page/view.php?id=225436). В LMS указаны справочники *Osha Supermarkets* и *Ergonomics: Design Reference Guide*; ограничения доступа к ним перечислены в конце файла.

### Рассказ на английском

Ergonomics concerns the relationship between people, their tasks and the systems they use. An ergonomic design should help people work comfortably and efficiently while reducing avoidable strain. It requires attention to the user and the working context.

The case-study preparation in Unit 5 focused on a retail cashier. An engineering consultancy had received a commission from a major retail chain and wanted to assess candidates' problem-solving, learning and teamwork abilities. Students were expected to use ergonomic reference materials, develop a justified solution and present a map of their thinking process.

To explain how I would approach such a problem, I would first observe the cashier's workflow. Relevant questions include how often the person reaches for items, where the scanner is placed and whether the work requires repeated awkward movements. These are proposed analysis questions, rather than findings from a completed classroom investigation.

A solution might involve changing the layout, making equipment adjustable or improving the movement of goods through the workstation. However, it should also consider space, cost and the needs of different workers. The team would need to test whether the change actually reduces difficulty without creating another problem.

LOOPY was suggested as a tool for documenting relationships in the system. The main lesson is that ergonomic problem-solving involves connected factors. A convincing proposal should explain the cause of the difficulty, the reason for the design change and the evidence needed to judge its success.

### Ещё детали для контекста

- Реальные факты подготовительного сценария: consultancy, retail chain, отбор кандидатов, problem-solving, quick learning, teamwork, команды 3–4 человека, обоснование и thinking process map.
- Конкретное описание рабочего случая должно было выдаваться на очной сессии. В доступном тексте Class 13 оно не раскрыто; невозможно восстановить данные конкретной команды.
- Scanner, reach, posture, repetitive movements и adjustable workstation — полезные понятия для объяснения возможного анализа, а не сообщённые результаты занятия.
- В схеме LOOPY можно показать предполагаемую связь workload → fatigue → errors. Это **учебная гипотеза**, которую нужно проверить, а не доказанный график из курса.
- Не заучивай придуманные высоты стола или допустимые веса: численные нормативы из справочников в этом файле не воспроизводятся.

### Что перенести в кейс

Для неудобного рабочего места сначала анализируй задачу и движения человека. Связывай design change с конкретным источником трудности и проверяй результат с реальными пользователями.

**Сочетания:** ergonomic workstation — эргономичное рабочее место; repetitive movements — повторяющиеся движения; reduce physical strain — уменьшить физическую нагрузку; adjust the layout — изменить расположение; substantiate a solution — обосновать решение.

**Проговори:** что наблюдать у кассира? Почему одной удобной мебели недостаточно? Как показать связь решения с причиной проблемы?

## 8. Ergonomic evaluation of smartphone usability

### О чём материал

В Class 12 есть видео **Ergonomic Evaluation of Smartphone Usability**. Доступные вопросы посвящены ширине устройства, размеру экрана, bezel, использованию одной рукой на ходу, flat vs curved screens, accidental touches и просмотру видео. Полная расшифровка этого видео не прикреплена; hw7.txt — другое видео, о cybersecurity.

Источник: [Class 12](https://lms.mipt.ru/mod/page/view.php?id=225365).

### Рассказ на английском

Smartphone usability connects physical design with the tasks people want to perform. The questions in the Unit 5 lesson considered screen size, device width, the bezel and the difference between flat and curved screens. They also asked about one-handed use while moving and accidental touches.

A larger screen may make content easier to view, but it can also make a device harder to hold or operate with one hand. A narrow bezel changes the relationship between the screen and the user's grip. These features should therefore be evaluated together, rather than treated as separate improvements.

Different activities also create different priorities. Watching a video and quickly selecting a control while walking are different contexts of use. A design that supports one activity may be less convenient for another person or task.

I would evaluate a smartphone by asking representative users to perform realistic tasks. Possible measures would include successful completion, accidental inputs, time and reported comfort. These are my suggested evaluation methods; the available lesson questions do not provide the video's complete results.

The broader lesson is that specifications alone cannot explain usability. Engineers should connect physical dimensions, interface controls and actual user behaviour. They should also recognise variation between users instead of assuming that one design is ideal for everyone. This topic links ergonomics with UX because both require an understanding of the person, the task and the context.

### Ещё детали для контекста

- **Bezel** — рамка вокруг экрана; **accidental touch** — случайное касание; **one-handed use** — использование одной рукой.
- Нельзя утверждать по одним вопросам, что конкретный размер или curved screen «победил» в исследовании.
- Возможный trade-off: большая видимая область ↔ удобство хвата и достижимость элементов. Это логика анализа, не восстановленный вывод speaker.
- Для решения проблемы можно обсуждать физическую форму и расположение controls; не сводить всё к диагонали.

### Что перенести в кейс

Если устройство неудобно, уточни пользователей и tasks. Сравни несколько решений через realistic use, а не только через список features.

**Сочетания:** operate with one hand — управлять одной рукой; accidental input — случайный ввод; comfortable grip — удобный хват; context of use — контекст использования; evaluate user behaviour — оценивать поведение пользователя.

**Проговори:** всегда ли больший экран лучше? Что проверять при one-handed use? Какие данные нужны перед выбором размера устройства?

## 9. Googleplex: рабочая среда, amenities и facilities

### О чём материал

Class 14 обсуждает видео **What's Inside Google Headquarters — Googleplex**: как amenities, организация среды и внимание к physical/mental well-being связаны с творчеством и работой staff. Словарь TV Week 7 закрепляет staff/stuff, amenity/facility, seek и back on track. Ни один из присланных hw-файлов не является расшифровкой Googleplex.

Источник: [Class 14](https://lms.mipt.ru/mod/page/view.php?id=225367), TV_Week_7_RU.pdf.

### Рассказ на английском

The Googleplex topic in Unit 5 connected the working environment with employee experience. The lesson questions asked how amenities and the organisation of a campus could support creativity, energy and well-being. This places ergonomics in a wider context than the design of a single chair or device.

The vocabulary distinguished staff from stuff. Staff means the people employed by an organisation, while stuff is an informal word for things or materials. Another distinction was between an amenity and a facility. An amenity makes a place more pleasant or comfortable. A facility is a building, service or piece of equipment provided for a particular purpose. The meanings can overlap in some contexts.

To discuss this topic, I would consider how an environment supports different activities. People may need quiet concentration, collaboration, access to equipment and opportunities to recover between demanding tasks. These are general design considerations, rather than a list of features verified from the complete Googleplex video.

The same approach could be applied to a university campus. Before proposing an improvement, engineers should seek feedback from students and staff and identify the difficulty they want to address. An attractive space is useful when it supports actual needs.

The main lesson is that the experience of employees or students depends on both physical conditions and how activities are organised. Improvements should be evaluated through their practical effects, rather than assumed to work because they look impressive.

### Ещё детали для контекста

- Вопросы LMS упоминают campus, food, creativity, energy, safety и mental health. В файле нет непроверенного перечня объектов или точного количества столовых.
- **Seek** — искать: seek feedback / seek a solution; **back on track** — снова идти по плану после проблемы, удобно для progress report.
- Amenity/facility не всегда противопоставляются: один объект может рассматриваться и как удобство, и как помещение с определённой функцией.
- Примеры улучшений кампуса в рассказе — перенос идеи на МФТИ, а не заявленные факты о Google.

### Что перенести в кейс

Для улучшения learning/working environment объясни, какую деятельность поддерживает изменение. Обсуди разные потребности и способ собрать feedback.

**Сочетания:** support employee well-being — поддерживать благополучие сотрудников; provide useful amenities — создавать полезные удобства; seek feedback — искать обратную связь; improve the working environment — улучшить рабочую среду; get a project back on track — вернуть проект к выполнению плана.

**Проговори:** чем отличаются staff и stuff? Что считать amenity? Как проверить пользу нового пространства в университете?

## 10. Design thinking, personas, scenarios и user flows

### О чём материал

Текст **User-Centered vs Goal-Centered UX Design** объясняет non-linear, iterative design thinking: понять пользователей, проверить assumptions, переосмыслить ill-defined problem, создать и протестировать решение. Далее — **persona**, **scenario** и **user flow**. Конкретный пример flow: e-commerce, от home page через category/product/cart/checkout к confirmation.

Источник: [Class 14](https://lms.mipt.ru/mod/page/view.php?id=225367), TV_Week_7_RU.pdf.

### Рассказ на английском

Design thinking is an iterative and non-linear approach to understanding people and developing solutions. The reading in Unit 5 explained that designers may need to challenge assumptions and reframe a problem before deciding what to build. This is useful when the original problem is ill-defined.

A persona represents an archetypal user with relevant needs, goals and characteristics. It helps the team consider a particular perspective rather than design for an imaginary average person. However, a persona should be connected to research and useful tasks, rather than invented only to decorate a presentation.

A scenario describes a person using a product or service to complete a task. It gives context to the goal and shows why the interaction matters. A user flow maps the steps through an interface. The course gave an online shopping example: the user enters the home page, chooses a category, opens a product, adds it to the cart, checks out and receives confirmation.

This simple sequence is a happy path. Real users may compare products, check delivery information or return to an earlier step. A flowchart can make these decisions and alternative paths visible.

For a university project, the team could consider students, teachers or visitors and investigate their different goals. The main lesson is that research, personas, scenarios and flows support each other. They help articulate requirements and reveal roadblocks before the team invests heavily in implementation.

### Ещё детали для контекста

- **Non-linear**: не обязательно проходить стадии один раз строго по порядку. **Iterative**: повторять и улучшать на основе результата.
- **Reframe** — изменить постановку проблемы. В PDF английская дефиниция этой строки ошибочно повторяет *not clearly described*, относящееся к **ill-defined**; для подготовки используй корректный смысл.
- **Ideation** — генерация идей; **articulate** — ясно сформулировать; **depict** — изобразить/описать; **node** — узел схемы; **path** — путь.
- Scenario даёт историю и контекст; flow показывает шаги и переходы. Persona показывает, **кто** действует.
- Happy path не описывает всех пользователей и ошибок. Для realistic design нужны alternative paths.
- Название текста не означает, что user-centered и goals исключают друг друга: в доступном содержании пользовательские цели связываются с персонами и сценариями.

### Что перенести в кейс

Если задача звучит «сделать удобнее», уточни для кого и для какой цели. Затем опиши scenario, путь пользователя, место затруднения и маленький prototype для проверки.

**Сочетания:** reframe an ill-defined problem — уточнить постановку неясной проблемы; articulate user requirements — ясно сформулировать требования; create a user persona — создать портрет пользователя; map the user flow — изобразить путь пользователя; refine a prototype iteratively — последовательно дорабатывать прототип.

**Проговори:** чем отличаются persona, scenario и flow? Что такое happy path? Почему после тестирования можно вернуться к постановке проблемы?

## 11. Engineering prototype для МФТИ и конкурс

### О чём материал

Graded Task 5.3 соединяет предыдущие темы: исследование пользователей → persona → pain points → technological solution → scenario storyboard → prototype → presentation. Можно было выбрать learning environment, EdTech, campus/dormitories, entertainment/CultTech либо проект своей школы/кафедры. Подготовка идёт в Week 8, первый тур — Week 9, финал — Week 10.

Источники: [Engineering Design Contest](https://lms.mipt.ru/mod/page/view.php?id=238230), [HA Week 8](https://lms.mipt.ru/mod/page/view.php?id=225440), [Week 9](https://lms.mipt.ru/mod/page/view.php?id=239794), [Week 10](https://lms.mipt.ru/mod/page/view.php?id=239793).

### Рассказ на английском

The engineering design contest in Unit 5 brought together user research, technical design and communication. Students could develop a project related to MIPT, such as a learning environment, an educational platform or a campus improvement. Another option was a prototype related to their field of study.

The first step was to research the target audience and create a persona. The instructions asked for information such as personality, technologies, frustrations and goals. The team then had to identify a pain point and propose a technological solution.

A user scenario and storyboard showed how the solution would affect a person's experience. This helped connect the technical idea to a real task. The prototype could be represented through a drawing, a wireframe or a physical model. Its rationale and technical specifications needed to be explained, including relevant materials, properties, technologies or programming languages.

The presentation was expected to last five to seven minutes. The assessment considered the credibility of the persona and story, the clarity of the problem, the quality of the prototype and its practical applicability. Visuals, technical communication and interaction with the audience also mattered.

The main lesson is that a prototype should have a clear reason to exist. A convincing engineering proposal explains who needs it, what difficulty it addresses, how it works and whether it could realistically be implemented. Technical features become more meaningful when they are connected to the user's situation.

### Ещё детали для контекста

- Это работа individually или in pairs, максимум два человека в команде конкурса. Не путай с группами 3–4 в эргономическом кейсе.
- Persona должна включать не меньше шести разделов: photo, name, personality, technologies, frustrations, goals/pain points and gains.
- Scenario storyboard построен через story mountain. Конкретного готового студенческого проекта в общих инструкциях нет.
- На слайде рекомендовано не более двух шагов сценария, чтобы он читался. Prototype может быть визуальным, физическая готовая машина не обязательна.
- В критериях: visuals 4; technical communication 2; English 4; prototype design 4; novelty/applicability 2; performance 4 — всего 20.
- Важны rationale, technical specifications, novelty и реалистичность применения. Инструкции подчёркивают speaking, без чтения слайдов.

### Что перенести в кейс

Собирай объяснение **user → pain point → solution → mechanism → limitation → test**. Это помогает не перечислять features без причины.

**Сочетания:** address a pain point — решить конкретную трудность; explain the rationale — объяснить обоснование; specify technical requirements — указать технические требования; demonstrate practical applicability — показать практическую применимость; develop a credible scenario — создать правдоподобный сценарий.

**Проговори:** что делает prototype убедительным? Как связать user research и technical specifications? Что отличает полезное решение от красивого концепта?

## 12. Презентации: audience, speaker, transformation

### О чём материал

**hw9.txt** — фрагмент лекции **3 Magic Ingredients of Amazing Presentation**. Три компонента: аудитория, сам speaker, изменение audience после выступления. Class 16 сравнивает good/bad presentation на примере Ranjit; HA Week 9 и Class 17 добавляют **Jump Start techniques** для начала выступления. Основная идея: сообщить информацию недостаточно, нужно понимать цель общения.

Источники: [Classes 15–16](https://lms.mipt.ru/mod/page/view.php?id=238236), [HA Week 9](https://lms.mipt.ru/mod/page/view.php?id=225444), [Class 17](https://lms.mipt.ru/mod/page/view.php?id=239794), hw9.txt.

### Рассказ на английском

The presentation video in the homework described three important ingredients: the audience, the speaker and transformation. The first ingredient means adapting the message to the people in front of you. The audience needs to understand why the topic matters to them, not only what the speaker knows.

The second ingredient is the speaker. Relevant experience, motivation and stories can make a presentation more personal and credible. This does not mean discussing unrelated details about yourself. It means showing why you are presenting this idea and what you can contribute.

The third ingredient is transformation. A presentation should have a desired effect on what the audience believes, feels or does. The video used a startup pitch as an example. Giving investors information is not the complete goal: the speaker wants to build confidence and encourage support.

The course also discussed jump-start techniques. A speaker can begin with a question, a relevant story, a striking visual or an invitation to imagine a situation. The opening should connect to the message and the audience rather than attract attention for its own sake.

For an engineering presentation, I would start with a user's difficulty, explain the proposed mechanism and show its benefit and limitations. Delivery also matters: clear speech, appropriate body language and interaction with slides help the audience follow the reasoning. The main lesson is to plan the intended effect before choosing the content and presentation style.

### Ещё детали для контекста

- В видео аудитория спрашивает **“So what?” / “What's in it for me?”**. Ответ — смысл и польза конкретно для этих людей.
- Speaker должен внести релевантную личную причину/опыт; история «что ел на завтрак» без связи с темой не помогает.
- Transformation может затрагивать belief, feeling, action. Стартап-питч оценивается не только количеством переданной информации.
- Список LMS: provocative statement, curiosity, shock, story, imagine, authenticity, influential quote, relevant joke, captivating visual, question, prop.
- Пример собственного начала для проекта: **“Imagine arriving at an unfamiliar building and having only five minutes to find your classroom.”** Это учебная заготовка, а не цитата видео.
- В Class 16 обсуждается Ranjit: первое выступление, feedback, улучшенная версия; уверенность, body language и движение. Полной расшифровки этого ролика нет.
- Provocative/shocking introduction требует правдивости и связи с темой. Не запоминай примеры фраз из заданий как проверенные статистические факты.

### Что перенести в кейс

Если нужно убедить клиента или объяснить решение неспециалисту, сначала выясни, что ему важно. Покажи проблему, последствия и пользу; технические детали подбирай под цель аудитории.

**Сочетания:** tailor the message to the audience — адаптировать сообщение; capture attention — привлечь внимание; tell a relevant story — рассказать уместную историю; build confidence — укрепить доверие; explain the intended outcome — объяснить желаемый результат.

**Проговори:** зачем presentation нужна transformation? Как внести личный опыт без ухода от темы? Каким opening начать инженерное предложение?

## 13. Conciseness и progress report

### О чём материал

В HA Week 8 текст **Technical Writing Style** объясняет conciseness и wordiness. Class 15 и отдельная страница **How to write a Progress Report** учат сообщать состояние инженерного проекта так, чтобы manager/client мог принять решение: что сделано, что в работе, проблемы, изменение требований, дальнейшие шаги и overall assessment. В Class 20 писали такой отчёт о своём prototype.

Источники: [HA Week 8](https://lms.mipt.ru/mod/page/view.php?id=225440), [Class 15](https://lms.mipt.ru/mod/page/view.php?id=238236), [Progress Report](https://lms.mipt.ru/mod/page/view.php?id=240133), [Class 20](https://lms.mipt.ru/mod/page/view.php?id=239793), [HA Week 10](https://lms.mipt.ru/mod/page/view.php?id=225445).

### Рассказ на английском

Technical writing should provide the information the reader needs clearly and efficiently. The homework text explained that conciseness means removing unnecessary words without losing useful detail. A long report can still be concise if its information is relevant and well organised.

The text identified causes of wordiness, including repeated meanings, unnecessary introductory structures and indirect expressions. However, removing too much information can make writing unclear or too abrupt. The aim is readable communication, not simply the smallest possible word count.

The progress report topic applied this principle to an engineering project. A report should identify the project, the reporting period, the team and the intended reader. It then explains the background, completed work, work in progress and remaining tasks.

The course example involved a prototype enclosure. The team had finalised a CAD model, printed two PLA samples and checked the fit of a PCB. Current work included updating mounting holes and drafting an assembly guide. Planned work included a thermal test and revised drawings.

A useful report also explains problems, their impact and the response. Changes in requirements and the overall project status should be stated realistically. A manager needs to know whether the project is on track, behind schedule or at risk, and what support or decision is required. The main lesson is that reporting progress means connecting evidence, consequences and next steps, rather than listing activities without explaining their significance.

### Ещё детали для контекста

- **Conciseness ≠ brevity:** краткость — небольшой объём; conciseness — отсутствие лишнего при сохранении необходимого.
- Примеры redundant wording из текста: basic essentials, completely finished, final outcome; coordinated synonyms: each and every, basic and fundamental.
- **Gobbledygook** — запутанный, перегруженный жаргоном/канцеляризмами язык; **circumlocution** — длинное обходное выражение простой мысли.
- Разделы подробного шаблона: Introduction/title details → Project Description → Progress Summary → Problems Encountered → Changes in Requirements → Overall Assessment.
- Progress Summary можно строить по tasks, по periods или tasks + status. Главное — читатель различает done / in progress / scheduled.
- В примерном отчёте CAD v1.3, две PLA samples, PCB fit, mounting holes, assembly guide и 2-hour thermal test. Это **пример шаблона**, не результаты проекта пользователя.
- Class 15 предлагает video segments problem→solution→device; app→transfer→processing→visualisations; challenges→next steps. Без транскрипции нельзя достоверно назвать конкретное устройство и его результаты.

### Что перенести в кейс

Для задержки проекта объясни **problem → impact → response → new milestone**. Для увеличения объёма устного ответа добавляй evidence, example и limitation; повторение одной мысли противоречит conciseness.

**Сочетания:** report measurable progress — сообщить измеримый прогресс; meet a milestone — достичь контрольной точки; remain on track — идти по плану; encounter a blocker — столкнуться с препятствием; revise the schedule — пересмотреть график.

**Проговори:** чем progress report отличается от рекламы проекта? Что делать, если проблема не решена? Почему длинный ответ может быть concise?

## 14. Technical description: flat-plate solar collector

### О чём материал

Class 18 объясняет **mechanism description**: overall appearance, function/purpose, components и взаимодействие частей. Важна audience analysis: homeowners, engineers и informed laypersons нуждаются в разной детализации. Главный образец — **standard flat-plate solar collector**, преобразующий солнечное излучение в тепло.

Источник: [Class 18](https://lms.mipt.ru/mod/page/view.php?id=239794).

### Рассказ на английском

A technical description of a mechanism explains what an object is, what it does and how its parts work together. The writer should select significant details and organise them logically. Audience analysis determines how much explanation and technical data are needed.

The example in Unit 5 described a standard flat-plate solar collector. It is a device that absorbs sunlight and converts it into heat. The description first gave an overview and then explained five main parts: the enclosure, glazing and frame, absorber plate, flow tubes with transfer fluid, and insulation.

The enclosure holds the other components. Transparent glazing allows sunlight to reach the absorber plate and helps retain heat. The black-coated metallic absorber plate converts incoming radiation into heat. Fluid moving through attached tubes receives this heat and carries it away. Insulation around the collector reduces heat loss.

The operating cycle connects these components. Sunlight passes through the glazing and heats the plate. The circulating fluid becomes warm and travels to a heat exchanger, where it transfers heat to water for domestic use. The cooled fluid returns to the collector and the cycle continues.

The lesson distinguished homeowners, engineers and informed non-specialists. They may need different information about the same mechanism. The main lesson is to explain the relation between structure and function. Listing parts is useful only when the reader also understands why they are present and how they interact.

### Ещё детали для контекста

- Структура образца: **Definition → Overview → Components and explanations → operating cycle → Visuals → Conclusion**.
- В overview конкретной модели: rectangular, ten feet long, four feet wide, four inches high. Это размеры **описанного образца**, не стандарт для любых collectors.
- В тексте: металлический или polymer enclosure; glass/plastic glazing; black-coated plate; treated water как типичный transfer medium; polyurethane insulation.
- Это **solar thermal collector**, не photovoltaic panel: в данном механизме объясняется производство тепла, не электричества.
- Доля отопления/горячей воды в образце зависит от географического положения. Не переноси проценты текста на произвольное здание без расчёта.
- Для engineers полезны точные свойства материалов и R&D data; для homeowners — понимание применения; для informed laypersons — понятный принцип и labelled diagrams.

### Что перенести в кейс

Это прямой контекст первого типа задания и полезный способ объяснить техническое решение во втором: **part → function → interaction → result**. Подбирай терминологию под аудиторию.

**Сочетания:** absorb solar radiation — поглощать солнечное излучение; transfer heat to a fluid — передавать тепло жидкости; circulate through tubes — циркулировать по трубкам; retain heat — удерживать тепло; describe the operating cycle — описать рабочий цикл.

**Проговори:** что делают пять частей? Чем этот collector отличается от solar cell? Что изменится в описании для инженера и домовладельца?

## 15. The Safer, Smarter Smartphone

### О чём материал

Дополнительный кейс UNIT 5 связывает smartphone design с materials science из UNIT 4. Задача — повысить **safety, sustainability, durability**, сохранив functionality. В условии выделены lithium-ion battery, display glass, housing и internal components. Нужно аргументировать свойства альтернативных материалов и их ограничения; готового решения кейс не даёт.

Источник: [Additional Case Study](https://lms.mipt.ru/mod/page/view.php?id=225377).

### Рассказ на английском

The additional case in Unit 5 concerned a safer and more sustainable smartphone. It asked students to examine the materials used in the battery, display, housing and internal components. The goal was to improve safety and durability without losing the device's functionality.

The case identified several concerns. A lithium-ion battery can overheat or catch fire if damaged or charged improperly. Battery materials such as cobalt can also raise ethical and supply-chain questions. Battery performance degrades over time, which affects the useful life of the product.

Other parts create different problems. Display glass can break into sharp fragments. Some housing materials may have environmental or durability limitations, while internal components can be difficult or expensive to recycle.

The task was to propose alternative materials and justify them through their properties. However, an alternative should not be described as automatically better. Engineers need to consider performance, manufacturing, cost and possible new limitations. A change that improves one property may make another requirement harder to meet.

My proposed approach would be to compare options for each component, define the safety and performance requirements and plan appropriate validation before recommending a final design. The course did not provide one approved material combination.

The main lesson is that responsible design connects materials, risks and the product's life cycle. A convincing recommendation explains the expected improvement and the evidence needed to show that functionality, durability and sustainability have been preserved.

### Ещё детали для контекста

- **Overheating, combustion, explosion** — риски, обсуждаемые в условии при повреждении/неправильной зарядке; не утверждение, что любой исправный телефон обязательно опасен.
- **Ethically sourced** — материалы с учётом этических вопросов происхождения; **recyclable** — пригодный к переработке; **robust** — стойкий к условиям эксплуатации.
- Требования затрагивают весь аппарат. Улучшенная housing не решает автоматически риск battery.
- Конкретные альтернативы батарей или защитные покрытия в общем условии не выбраны. Для контекста достаточно объяснить критерии сравнения; не нужно выдавать модный материал за доказанную замену.
- Связь с UNIT 4: material properties → component function → safety/application → limitation.

### Что перенести в кейс

Для выбора материала сопоставь нужное свойство, ожидаемую пользу и возможный trade-off. Добавь validation и влияние на весь life cycle изделия.

**Сочетания:** minimise safety risks — уменьшить риски безопасности; withstand daily use — выдерживать ежедневную эксплуатацию; preserve functionality — сохранить функциональность; compare material properties — сравнить свойства материалов; consider the product life cycle — учитывать жизненный цикл изделия.

**Проговори:** какие четыре группы компонентов рассматриваются? Почему безопаснее не всегда дешевле или проще? Как обосновывать выбор материала?

## Мостики между темами для устного ответа

Используй один-два подходящих мостика, затем конкретный пример. Это заготовки для объяснения связи, не цитаты уроков.

| Связь | Фраза для ответа |
|---|---|
| Software → UX | A feature may work correctly, but users may still struggle to find or understand it. |
| Requirements → failed app | Unclear requirements can lead to the wrong features and expensive changes later. |
| UX → ergonomics | Both require us to consider the user, the task and the context of use. |
| Usability → smartphone | Physical dimensions affect how easily a person can operate the interface. |
| Persona → prototype | The persona helps explain whose problem the prototype is intended to solve. |
| Design thinking → SDLC | Feedback can reveal that we need to revise the requirements or the design. |
| Cybersecurity → engineering decisions | We should compare immediate performance benefits with possible security consequences. |
| AI → human factors | A convincing message can influence human judgement, so verification remains necessary. |
| Progress report → teamwork | Clear reporting helps the team coordinate work and ask for support before a problem becomes worse. |
| Presentation → audience analysis | The explanation should reflect what the audience needs to understand or decide. |
| Materials → smartphone | A material should be chosen for its function and limitations, not only for one attractive property. |
| Technical description → case answer | Explaining how the parts interact makes the proposed solution easier to evaluate. |

### Пять особенно полезных примеров из курса

1. **Failed student app:** unclear requirements + weak design + limited testing → crashes, confusing interface, expensive maintenance.
2. **Invisible Bug:** ошибка почти не влияет на скорость → исправление откладывают ради availability → attacker получает доступ.
3. **Backup Paradox:** быстро восстановить данные ≠ вернуть конфиденциальность после раскрытия.
4. **E-commerce flow:** home → category → product → cart → checkout → confirmation; happy path нуждается в проверке alternative paths.
5. **Flat-plate collector:** glazing → absorber → fluid → heat exchanger → return; объяснение системы через взаимодействие частей.

Дополнительно: deepfake CFO из Homework; cashier workstation из подготовки к кейсу; CAD/PLA/PCB из образца progress report. Помни, где условие, где speaker's example, где шаблон, а где собственное предложение.

## Грамматика UNIT 5, которую удобно вставить в речь

Основные темы курса: **Gerund and Infinitive — Complex Forms** и **Emphasis**. Не усложняй каждое предложение. Один правильно построенный пример лучше нескольких ненадёжных конструкций.

Источники: [Gerund/Infinitive](https://lms.mipt.ru/mod/page/view.php?id=225481), [Emphasis](https://lms.mipt.ru/mod/page/view.php?id=225482), Classes 14–15.

### Gerund / infinitive

| Конструкция | Учебный пример по темам юнита | Смысл |
|---|---|---|
| Gerund как подлежащее | Testing with real users helps identify roadblocks. | Тестирование помогает… |
| Предлог + gerund | The team improved the layout after observing the workflow. | После наблюдения… |
| Verb + infinitive | We need to clarify the requirements. | Нужно уточнить… |
| Simple passive infinitive | The prototype needs to be tested. | Нужно протестировать… |
| Perfect infinitive | The bug appears to have caused the failure. | Вероятно, уже вызвал… |
| Continuous infinitive | The team seems to be testing the prototype. | Кажется, сейчас тестирует… |
| Perfect gerund | They regretted having postponed the repair. | Сожалели о прежнем решении… |
| Passive gerund | Users dislike being asked to repeat unnecessary steps. | Не любят, когда их просят… |

Perfect forms показывают более раннее/завершённое действие; continuous infinitive — процесс. После **avoid**: *avoid adding unnecessary steps*, после **decide**: *decide to redesign the interface*. Не выбирай -ing или to только по русскому переводу.

### Emphasis

- **What users need is clear navigation.** Выделение нужды через what-clause.
- **It was limited testing that allowed serious bugs to remain.** Выделение причины через it-cleft; это возможный анализ, не установленная единственная причина кейса.
- **The design does improve readability.** *Does + base verb* подчёркивает утверждение.
- **Not only does the design reduce unnecessary steps, but it also makes the process clearer.** После вынесенного *not only* — auxiliary + subject.
- **Rarely do users follow exactly the path that designers expect.** Пример формы inversion, а не статистический результат исследования.

Самые удобные безопасные заготовки для устной речи: **“What matters most is…”**, **“What we need to test is…”**, **“The main problem appears to be…”**.

## Как повторить UNIT 5 за один день

План примерно на **5 часов активной работы**, плюс перерывы. Если есть меньше времени, сначала темы 1–7, 10 и 13: они дают больше всего понятий и примеров для рассуждения. Остальные просмотри хотя бы по русскому контексту и последним вопросам.

| Блок | Время | Что сделать | Проверка без текста |
|---|---:|---|---|
| Software | 45 мин | Темы 1–2: SDLC, архитектура, failed app | Назови шесть стадий и объясни две причины провала |
| Cybersecurity | 50 мин | Темы 3–5: атаки, пять кейсов, AI | Объясни Backup Paradox и security for AI / AI for security |
| Human factors | 45 мин | Темы 6–9: usability, UX, кассир, смартфон, среда | Различи usability/UX; назови контекст и критерии проверки |
| UX → prototype | 40 мин | Темы 10–11: persona, scenario, flow, конкурс | На своём примере свяжи пользователя, цель и решение |
| Communication | 45 мин | Темы 12–14: презентация, отчёт, collector | Назови 3 ingredients; объясни отчёт и цикл collector |
| Связи и материалы | 25 мин | Тема 15, мостики, грамматика | Свяжи smartphone с material properties и ergonomics |
| Устная репетиция | 50 мин | 4 случайные темы без чтения, затем один мини-кейс | В каждом ответе понятие + course example + limitation |

**Метод одного блока:** 10–15 минут чтения и разбора → 5 минут выписать collocations → закрыть файл → два коротких пересказа → посмотреть только забытое. Не трать весь день на перечитывание.

Для второго задания тренируй перенос: возьми ситуацию «интерфейс неудобен / проект задерживается / данные утекли / рабочее место вызывает усталость». Дай **problem → likely cause → two options → reasoned choice → validation**, включив один релевантный пример UNIT 5. Не пересказывай весь юнит вместо ответа на ситуацию.

### Минимальный словарный набор

- **Software:** requirements, architecture, deployment, maintenance, reliable, scalable.
- **Cybersecurity:** vulnerability, malware, ransomware, segmentation, backup, confidentiality.
- **AI:** phishing, deepfake, shadow AI, attack surface, hallucination, human oversight.
- **UX / ergonomics:** wording, imagery, assumption, refinement, wireframe, mockup, workflow, roadblock, ergonomic, scanner.
- **Design:** non-linear, iterative, tackle, ill-defined, reframe, user behaviour, feature, ideation, articulate, depict, persona, scenario, user flow, node.
- **Environment / reporting:** staff, stuff, amenity, facility, seek, back on track, milestone, blocker, on track, behind schedule.

Учи слово в сочетании: **clarify requirements**, **challenge an assumption**, **refine a prototype**, **tackle a roadblock**, **depict a user flow**, **report a blocker**. Для увеличения объёма добавляй причину, пример, последствия, ограничение и проверку: это содержательные новые мысли.

## Источники и границы полноты

Изучены доступные текстовые страницы аудиторных занятий UNIT 5 (Classes 11–20), общая страница конкурса и Additional Case Study; Homework Weeks 6–10; отдельная страница Progress Report; обе грамматические страницы; присланные **TV_Week_6_RU.pdf**, **TV_Week_7_RU.pdf**, **hw6.txt**, **hw7.txt**, **hw9.txt**. Содержание задач использовано, чтобы определить тему и пример; сами упражнения и ответы тестов сюда не включены.

Сопоставление файлов: **hw6 → SDLC**, **hw7 → Cybersecurity Trends**, **hw9 → 3 Magic Ingredients**. Номер файла не означает, что он расшифровывает все видео соответствующей недели.

Не удалось извлечь текст двух справочников из LMS: **Osha Supermarkets** ([resource](https://lms.mipt.ru/mod/resource/view.php?id=225438)) и **Ergonomics: Design Reference Guide** ([resource](https://lms.mipt.ru/mod/resource/view.php?id=225439)). Первый открывается как PDF без доступного текстового представления; полный текст обоих здесь не подтверждён. Поэтому тема кассира основана на опубликованном вводном сценарии, а конкретные параметры рабочего места и численные нормативы не выдуманы.

Полных расшифровок нет для **Googleplex**, **smartphone ergonomic evaluation**, вступительного видео об usability, примера **Ranjit**, аудио HA Week 8 и видеосегментов progress report. Где доступны вопросы и пояснения LMS, использован только их подтверждённый контекст. Отсутствующие рисунки/постеры и индивидуальные результаты очных команд не восстановлены по догадке.

Основные темы UNIT 5 разобраны выше, но этот файл не является полной транскрипцией всех мультимедийных материалов курса. Особенно для Googleplex и конкретного очного кейса кассира различай **известный контекст занятия** и **неполученные подробности**.
