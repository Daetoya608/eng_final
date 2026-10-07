# UNIT 4–6: минимум для устного кейса за 2–3 часа

**47 коротких карточек**: все основные темы трёх файлов, плюс GPS и этика digital twins из дополнений UNIT 4. **★ — первый приоритет:** принципы, применимые ко многим кейсам. Это порядок подготовки, не прогноз билетов.

В каждой карточке: **EN** — короткий связный текст: главная мысль, механизм, пример и применение; **пример** — привязка к курсу; **в кейс** — действия и проверка; **речь** — полезные сочетания. Предлагаемые действия — твой возможный анализ, а не «официальный ответ» преподавателя. Не учи карточки целиком: запомни механизм, один пример и способ проверки.

## Сначала выучи этот каркас

**Problem → 2 possible causes → 2 solutions → fallback → testing → recommendation.** Отвечай на все Discussion Points билета. По ранее разобранному образцу: 5 минут подготовки, минимум 3 минуты речи. Точный формат своего билета проверь по его инструкции.

| Шаг | Что сказать на английском |
|---|---|
| Проблема и ущерб | The main problem is… This may lead to… |
| Возможные причины | One possible cause is… Another possibility is… |
| Решение + механизм | I would… because… This would help by… |
| Пример курса + связь | The course example of… illustrates… In this case, the same principle applies because… |
| Компромисс | However, this would not solve… / The trade-off is… |
| Безопасный запасной вариант | If the system cannot…, it should… |
| Проверка | I would test it under… and measure… |
| Выбор | I would prioritise… because… |

**Рабочая единица аргумента:** предложение → причина → механизм → проверка. Например: *“I would simplify the navigation because users miss the main function. Fewer unnecessary steps would make it easier to find. I would compare task completion and error rates before and after the change.”*

## Быстрый выбор тем под билет

| Проблема | Карточки | Что обсуждать |
|---|---|---|
| Ошибка распознавания / неверный прогноз | 4.8, 5.1, 6.5, 6.7 | Input quality, model, conditions, uncertainty, fallback |
| Неудобный интерфейс / устройство | 5.6–5.8, 5.10, 4.11 | User, task, workflow, feedback, usability test |
| Деталь ломается / материал не подходит | 4.6, 4.12, 5.15, 6.18 | Load, environment, properties, failure mode |
| Утечка / malware / опасное AI-решение | 5.3–5.5, 4.14 | Prevention, containment, recovery, data access |
| Проект задерживается / дорого обслуживать | 5.1–5.2, 5.13, 6.2, 6.4 | Requirements, dependencies, priorities, milestones |
| Дефицит энергии / выбор источника | 6.13–6.17, 6.3 | Demand, supply, storage, site, cost, maintenance |
| Объяснить технологию / убедить клиента | 4.1–4.2, 5.12, 6.9 | Audience, mechanism, analogy, value |
| Авария / ограниченные ресурсы / риск | 6.3, 6.10–6.11, 5.4 | Triage, essentials, alternatives, responsibility |
| Новая технология и её внедрение | 4.3–4.5, 5.11, 6.8 | Need, prototype, limits, controlled pilot, evidence |

## UNIT 4

### 4.1. Technical communication и определения

**EN:** A useful definition names the object, its class and its distinguishing function. Technical explanations should match the audience's knowledge and purpose. Connect each component with what it does. The course used two descriptions of a solenoid to show how terminology changes with the reader. A non-specialist needs the purpose first, while an engineer may need precise properties. For an unclear instruction, I would explain the terms and check whether the user can perform the task correctly.

**Пример:** solenoid объясняли технически и простыми словами; bench power supply — current limit защищает схему.

**В кейс:** непонятная инструкция → уточнить аудиторию и её задачу, объяснить термины, дать схему «часть → функция». Проверить, может ли пользователь выполнить действие самостоятельно; недостаточно спросить «всё понятно?».

**Речь:** *tailor the explanation* — адаптировать объяснение; *reduce ambiguity* — убрать неоднозначность; *describe the core function* — объяснить основную функцию.

### 4.2. Аналогии и PEER

**EN:** An analogy connects an unfamiliar mechanism with something familiar. Explain the useful similarity and its limits. PEER means Purpose, Example, Explanation and Recap in this course. Blood vessels were compared with roads and blood clots with traffic jams. This makes a blocked flow easier to imagine without explaining every biological detail first. In a case, I would choose a comparison the audience knows, then describe the actual process and identify where the comparison stops working.

**Пример:** blood vessels → roads; blood clots → traffic jams. Простой FDM-принтер сравнивали с hot glue gun.

**В кейс:** клиент не понимает решение → знакомая аналогия, затем реальный механизм. Проверить пересказ клиента: не возникло ли ложное представление? Не выбирать сравнение, незнакомое аудитории.

**Речь:** *use a relatable example* — дать понятный пример; *preserve accuracy* — сохранить точность; *The similarity is…, but…* — сходство в…, однако…

### 4.3. ★ 3D printing: механизм и производство

**EN:** Additive manufacturing builds an object from a digital model by adding material. FDM deposits softened filament; resin printing cures a photosensitive liquid. Process choice depends on material, geometry, speed and required quality. The resin-printing example used an oxygen-permeable window to prevent the growing object from sticking to the vat. Removing this bottleneck allowed a more continuous process. For a manufacturing problem, I would investigate the specific source of delay or weakness and compare the finished parts, production time and material consumption.

**Пример:** у DeSimone oxygen-permeable window предотвращает прилипание детали и позволяет непрерывный рост; lattice bridge уменьшает расход материала.

**В кейс:** слабая/медленная печать → найти bottleneck, выбрать подходящий process/material, изменить geometry. Проверить прочность и качество готовой детали, время и отходы. Меньше материала на изделие не гарантирует меньшее общее потребление.

**Речь:** *build layer by layer* — строить послойно; *reduce material waste* — уменьшить отходы; *remove a bottleneck* — устранить узкое место.

### 4.4. 3D printing: медицина, industry, space

**EN:** Local production can reduce dependence on supply chains. Bioprinting also requires control of cells, biomaterials and contamination. Recycling printed material can support a closed-loop manufacturing process. NASA's Refabricator illustrated used parts being recycled into filament, which matters when supplies are difficult to deliver. The medical examples involved printed skin. I would compare local production with conventional supply, checking material availability, quality and application requirements.

**Пример:** Wake Forest — skin/tissues; Desktop Metal — изготовление деталей; NASA Refabricator — used parts → filament → new parts; Stargate — rocket components.

**В кейс:** сложные поставки → оценить on-site printing и recycling. Проверить доступность материала, оборудование, качество и жизненный цикл. Для biological structures отдельно проверять biological response; показанная форма не доказывает функциональность органа.

**Речь:** *produce parts on site* — производить на месте; *avoid contamination* — избегать загрязнения; *reduce supply-chain dependence* — уменьшить зависимость от поставок.

### 4.5. Smart materials и soft robots

**EN:** Smart materials change shape or properties in response to a stimulus. Multi-material structures can combine flexible and supportive regions. The response must be controllable and repeatable. The lesson included silicone rubber containing iron particles that responded to a magnetic field. Different regions could produce different movements, supporting remote activation or flexible handling. I would test force, response time and repeated operation rather than assume that one successful demonstration proves dependable performance.

**Пример:** silicone rubber с iron particles реагирует на magnetic field; soft robots используют pneumatic/vacuum deformation.

**В кейс:** требуется гибкий захват или remote actuation → выбрать stimulus, material и geometry. Проверить force, repeatability, response time и поведение при пропадании воздействия. Не путать перспективное medical application с доказанным лечением.

**Речь:** *respond to a stimulus* — реагировать на воздействие; *deform in a controlled way* — управляемо деформироваться; *achieve a repeatable response* — добиться повторяемого отклика.

### 4.6. ★ Materials and properties

**EN:** Material selection starts with loads and operating conditions. Strength resists failure; hardness resists indentation; toughness concerns energy absorbed before fracture. A hard material may still be brittle. The course also distinguished ductility, which supports drawing wire, from malleability, which supports forming sheets. A broken component may need greater toughness rather than greater hardness. I would identify the load and failure mode first, then compare properties, weight, cost and manufacturing, and test the final component under realistic conditions.

**Пример:** steel — ferrous; aluminium/copper — non-ferrous; brass — copper + zinc. Ductility позволяет вытягивать wire, malleability — формировать sheet.

**В кейс:** деталь ломается → определить impact, fatigue, wear, corrosion или temperature effects. Выбрать свойства под причину, затем сравнить массу, стоимость и manufacturing. Проверять готовую деталь в рабочих условиях: «сделать твёрже» не универсальный ответ.

**Речь:** *withstand loads* — выдерживать нагрузки; *resist wear* — сопротивляться износу; *match the operating conditions* — соответствовать условиям работы.

### 4.7. ★ XR, AR, MR, VR и simulation

**EN:** AR adds digital information to the real world; VR presents a virtual environment. MR can link digital elements with physical surroundings. Coherent sensory feedback supports immersion, but visual realism alone does not prove useful learning. Walk the Plank showed how a physical board could make touch consistent with the virtual scene. AccuVein illustrated digital information placed on the body. For training, I would choose the technology according to the task and assess whether users perform better afterwards, while checking comfort and the need to see real surroundings.

**Пример:** AccuVein — информация о венах на коже; Walk the Plank — physical plank согласует touch с VR-картинкой; CERN tour — изучение установки.

**В кейс:** обучение → выбрать технологию по задаче: нужен ли вид реального окружения? Согласовать feedback, сравнить выполнение реальной задачи до/после training; проверить discomfort и ошибки переноса навыка.

**Речь:** *overlay digital information* — накладывать информацию; *provide coherent feedback* — давать согласованную обратную связь; *evaluate learning outcomes* — оценивать результат обучения.

### 4.8. ★ Digital twins и качество данных

**EN:** A digital twin connects a digital representation with information about a real system. Poor or outdated inputs can produce misleading predictions. Validate the model against real behaviour and update it as conditions change. Predictive maintenance uses information about equipment to help identify developing problems. However, equipment wear or new operating conditions can make an old model unreliable. The course compared a train with a thermostat to show different consequences of failure. I would check inputs, update the model and test important scenarios where simulation may differ from reality.

**Пример:** predictive maintenance; сравнение autonomous train и thermostat: последствия отказа задают глубину testing.

**В кейс:** неверный прогноз → разделить ошибки sensors/data и model; проверить missing data, calibration, updates и расхождение с реальностью. Испытать важные крайние сценарии. Для высокой criticality ограничить автоматические действия при uncertainty; simulation дополнить реальной validation.

**Речь:** *maintain data integrity* — сохранять целостность данных; *identify deviations* — выявлять отклонения; *validate against real-world data* — проверять по реальным данным.

### 4.9. Ready Player One и avatars

**EN:** An avatar represents a user but is not automatically an engineering digital twin. Virtual features need a purpose and must fit the environment's rules. Identity, access and corporate control affect the user's experience. Ready Player One linked the OASIS and avatars with identity, escape and corporate influence. The design activity also asked why a character's equipment was useful. In a case, I would connect each feature to a task, check its consistency with the setting and consider what control the user has over identity and information.

**Пример:** Wade/Parzival и OASIS; cybernetic arm для rescue в таблице урока — функция обосновывает design.

**В кейс:** virtual product → определить задачу пользователя и нужные capabilities, убрать декоративные features без функции. Проверить consistency и user control. Для identity/privacy отдельно обсудить, какие сведения видимы и кто управляет ими.

**Речь:** *represent user identity* — представлять личность; *justify a feature* — обосновать функцию; *fit the environment* — соответствовать среде.

### 4.10. ★ New Senses: substitution и addition

**EN:** Sensory substitution sends existing information through another sensory channel. Sensory addition provides a new type of information. Users must learn the patterns; a signal is not automatically understandable. Eagleman's vest converted sound into vibration patterns. Jonathan learned to recognise individual words, but the demonstration did not establish complete restoration of ordinary hearing. For an alternative interface, I would assess training needs, recognition accuracy and cognitive load, and distinguish the demonstrated benefit from capabilities that are still only proposed.

**Пример:** Eagleman's vest: sound → vibrations; Jonathan распознавал отдельные слова после training. Это не полное восстановление обычного hearing.

**В кейс:** недоступный канал → попробовать tactile/audio alternative. Проверить learnability, accuracy, response time и cognitive load с пользователями. Разделить demonstrated capability и hoped-for benefit; дать training, а не только hardware.

**Речь:** *use an alternative sensory channel* — использовать другой канал; *interpret patterns* — понимать закономерности; *convert sound into vibration* — превращать звук в вибрацию.

### 4.11. ★ Mechatronics, biomechatronics, biomimetics, haptics

**EN:** Mechatronics integrates mechanics, electronics, computing and control. Biomimetics borrows biological principles. Haptic feedback informs the user about contact; successful movement does not guarantee successful interaction. Bio4Eng uses biological principles to improve technology; Eng4Bio supports biological functions or people. Examples included animal-inspired robots and exoskeletons. If a device moves correctly but is difficult to use, I would examine feedback and control together, then test user accuracy and comfort.

**Пример:** Bio4Eng — bird/swimming/climbing robots; Eng4Bio — exoskeleton/walker; HAPTIX — tactile sensation.

**В кейс:** устройство движется, но им трудно управлять → проверить sensing, control и feedback, а не только motor. Обосновать borrowed biological principle конкретной функцией. Проверить accuracy, comfort, user performance и связь компонентов.

**Речь:** *integrate sensing and control* — объединять sensing и control; *provide tactile feedback* — давать тактильную обратную связь; *support human movement* — помогать движению.

### 4.12. ★ Biocompatibility и regenerative biomaterials

**EN:** A mechanically strong implant can fail because of an adverse biological response. Surface chemistry, wear, porosity and degradation matter. A scaffold must support tissue growth while retaining suitable mechanical properties. Porosity can improve transport and tissue growth, but too much may weaken the structure. Degradation must also suit the intended healing process. In an implant case, I would distinguish mechanical failure from inflammation, toxicity or contamination, and check the relevant properties after manufacturing and sterilisation rather than evaluate only the original material.

**Пример:** porosity помогает tissue growth/transport, но может снижать strength; bioglass — bioactive material; sterilisation может изменить свойства.

**В кейс:** implant failure → различить mechanical damage, toxicity, inflammation и contamination. Для scaffold согласовать porosity/strength и degradation/healing. Проверить после manufacturing/sterilisation в подходящем biological context; не судить по исходному материалу.

**Речь:** *minimise adverse reactions* — уменьшать нежелательные реакции; *balance strength and porosity* — согласовать прочность и пористость; *support tissue regeneration* — поддерживать восстановление тканей.

### 4.13. GPS: usefulness и новые применения

**EN:** Innovation can add a useful function to an existing technology. GPS supports navigation and tracking. Improvements should reflect user needs, not only a specification that is already adequate. The boat examples included a drift alarm and a man-overboard button that recorded a position. These connect location information with a specific action. For a product that is technically capable but unhelpful, I would identify the user's task and test whether the new function provides a timely warning or makes that task easier.

**Пример:** drift alarm предупреждает о сносе лодки; man-overboard button сохраняет позицию; tracking delivery vehicles.

**В кейс:** технология точная, но неполезная → выяснить practical need, добавить подходящие alert/action и понятный interface. Проверить timely warning, false alarms и выполнение задачи; важную функцию протестировать в realistic use.

**Речь:** *address a practical need* — решить практическую задачу; *enable users to…* — позволять пользователям…; *warn the user when…* — предупреждать, когда…

### 4.14. Ethics of digital twins и monitoring

**EN:** Monitoring can support health services but expose sensitive information. Define what data is necessary, who can access it and how the person controls its use. Technical capability alone does not justify collecting everything. The reading discussed in-body surveillance and possible risks such as identity theft. Useful monitoring therefore needs clear boundaries as well as technical protection. In a case, I would reduce unnecessary collection, define access and retention, explain the purpose and check whether the person can understand and control how the information is used.

**Пример:** in-body surveillance; риски identity theft/body hacking обсуждаются в тексте как возможные последствия.

**В кейс:** лишний сбор/утечка → ограничить collection/access, объяснить purpose, защитить хранение и передачу, определить retention. Проверить права доступа и возможность управлять данными. Балансировать service benefit и privacy; не обещать абсолютную защиту.

**Речь:** *protect sensitive data* — защищать чувствительные данные; *limit unnecessary collection* — ограничить лишний сбор; *give users control* — дать контроль пользователю.

## UNIT 5

### 5.1. ★ Software engineering и SDLC

**EN:** Software engineering covers requirements, architecture, coding, testing, deployment and maintenance. Unclear requirements or poor architecture can cause failures even when individual functions work. Release does not end responsibility. The online-store video used planning, analysis, design, implementation, testing and deployment with maintenance. Requirements explain what is needed, while architecture explains how components work together. For repeated failures, I would investigate both levels, test critical functions early and use feedback after release to guide changes instead of repeatedly repairing isolated symptoms.

**Пример:** Adam's online store: planning → analysis/SRS → design/DDS → coding → testing → deployment/maintenance.

**В кейс:** repeated bugs → определить, на каком уровне причина; согласовать requirements, review architecture, тестировать изменения до deployment. Выделить critical functions и измерять failures/maintenance costs. Добавить post-release feedback, а не только исправить текущий bug.

**Речь:** *clarify requirements* — уточнить требования; *review the architecture* — проверить архитектуру; *reduce maintenance costs* — уменьшить стоимость сопровождения.

### 5.2. Failed student application

**EN:** The student app failed after unclear requirements, weak design and limited testing. Users reported crashes, incorrect features and confusing navigation. Functional testing and usability testing address different problems. The app was intended to manage schedules, deadlines and exams within a three-month project. Its problems show that delivering code is different from delivering a usable product. I would review student needs, prioritise essential functions and compare crashes, successful task completion and navigation errors before and after changes, with realistic expectations about scope.

**Пример:** schedules/deadlines/exams; план 3 months; PM + 3 developers + 1 tester.

**В кейс:** вернуть team к user tasks; выбрать minimum core features, сделать prototype и ранние tests. Разделить «работает ли reminder» и «может ли студент настроить его». Проверить crashes, task completion и navigation errors; пересмотреть scope, если сроки нереалистичны.

**Речь:** *prioritise core functions* — выделить основные функции; *gather student feedback* — собрать feedback; *test realistic tasks* — проверить реальные задачи.

### 5.3. ★ Cyber attacks и layered protection

**EN:** Attackers may exploit vulnerabilities or use malware. Updates support prevention; segmentation limits spread; backups support recovery. Recovering files cannot undo a confidentiality breach. Ransomware can block data access; infected devices may join a botnet. Protective measures address different incident stages. I would connect updates to entry points, segmentation to containment and backups to recovery, then verify access controls and restoration instead of relying on antivirus alone.

**Пример:** ransomware; botnet; компания с missing updates, poor segmentation и no backups.

**В кейс:** связать меру с риском: patch → entry point, segmentation → spread, access controls/encryption → data protection, backup → recovery. Проверить restore и security после изменения. Antivirus полезен, но отсутствие alert не доказывает отсутствие атаки.

**Речь:** *exploit a vulnerability* — использовать уязвимость; *contain an infection* — ограничить заражение; *restore from a backup* — восстановить из копии.

### 5.4. ★ Пять cybersecurity cases: что доказывает каждый

**EN:** Passing tests does not prove complete security. A performance-neutral bug may still be dangerous. Availability, latency, confidentiality and honest disclosure are separate requirements. Invisible Bug showed the risk of postponing repair to avoid downtime. Backup Paradox showed why recovery cannot undo disclosure. I would compare operational benefits with security consequences, investigate uncertainty and communicate limitations before recommending a fix and validation.

**Примеры:** Successful Upgrade → утечка после tests; Invisible Bug → repair отложили ради uptime; Backup Paradox → восстановление не отменяет раскрытия; Network Efficiency → malware spread; Ethical Grey Zone → недостоверная comprehensive-protection claim.

**В кейс:** назвать immediate benefit и hidden risk, сравнить ущерб/repair disruption. Не угадывать причину утечки без investigation. Выбрать staged fix, containment и verification; сообщить ограничения affected stakeholders.

**Речь:** *balance availability and security* — согласовать доступность и защиту; *assess potential impact* — оценить ущерб; *disclose limitations* — раскрыть ограничения.

### 5.5. ★ AI, phishing, deepfakes, shadow AI

**EN:** AI can make phishing more convincing and help defenders analyse incidents. Deepfakes weaken trust in voice and video. Shadow AI can expose data, while hallucinations require verification and human review. The historical video described a fake CFO meeting linked to a large money transfer and an incorrect AI calculation. These examples show why convincing presentation is not proof of authenticity or accuracy. I would independently verify sensitive requests, define approved tools and data rules, and require review when an AI output affects an important decision.

**Пример:** в историческом видео fake CFO meeting → $25m transfer; AI дал неправильный running-pace conversion.

**В кейс:** sensitive request → независимая verification через известный канал. AI deployment → approved tools, правила данных, проверка output, escalation. Проверить errors и information exposure; confidence модели не считать доказательством accuracy.

**Речь:** *verify a sensitive request* — проверить важный запрос; *expose confidential information* — раскрыть сведения; *keep a human in the loop* — сохранить участие человека.

### 5.6. ★ Usability vs UX

**EN:** Usability concerns effectiveness, efficiency and satisfaction for a specific task. UX includes the whole journey and perceived value. A feature can exist and work while remaining hard to find or understand. Effectiveness asks whether the goal is achieved; efficiency concerns the effort required. The course connected UX work with interviews, wireframes, mockups and testing. For a confusing interface, I would observe actual tasks, remove unnecessary steps or unclear wording and compare completion, time, errors and satisfaction, rather than judge the redesign only by appearance.

**Пример:** UX designer использует research, wireframes/mockups, usability tests и post-release analysis.

**В кейс:** observe task → найти roadblock → изменить wording/navigation/steps → повторить test. Измерить completion, time, errors и satisfaction. Не заменять пользовательское исследование мнением команды или красивым redesign.

**Речь:** *identify roadblocks* — выявить препятствия; *refine the interaction* — доработать взаимодействие; *improve task completion* — улучшить выполнение задачи.

### 5.7. ★ Ergonomics: cashier workstation

**EN:** Ergonomics connects the person, the task and the working environment. Workstation design should reduce avoidable strain without creating new difficulties. Observe the workflow before changing equipment. The retail-chain case asked teams to justify a solution and explain their thinking. Reaching, posture and repeated movements are possible investigation points, not confirmed classroom findings. I would compare layout or adjustability options and test comfort, errors and task time with different users.

**Пример:** consultancy/retail-chain case; cashier specifications; team solution + LOOPY thinking map. Точный очный сценарий неизвестен.

**В кейс:** проверить reach, posture, repetition и equipment placement; предложить layout/adjustability и изменение процесса. Сравнить comfort, errors и task time у разных пользователей. Учесть space/cost; проверить возможную fatigue→errors связь, а не объявлять её доказанной.

**Речь:** *reduce physical strain* — уменьшить нагрузку; *adjust the workstation* — настроить рабочее место; *analyse repetitive movements* — анализировать повторяющиеся движения.

### 5.8. Smartphone ergonomics

**EN:** A larger screen may improve viewing but make one-handed use harder. Width, grip, bezel and control placement must be considered together. Usability depends on the task and the user. The lesson questions considered flat and curved screens, accidental touches and video viewing. These activities create different priorities: comfortable viewing does not guarantee easy access to controls. In a case, I would compare layouts or dimensions using representative users, measure accidental inputs and completion, and explain which benefit is gained at what cost.

**Пример:** вопросы урока: flat/curved screen, accidental touches, one-handed use on the move, video viewing; точного winner нет.

**В кейс:** сравнить users/tasks, изменить placement или geometry, проверить reach, accidental inputs и comfort. Не выбирать размер только по диагонали или внешнему виду; сопоставить benefit и trade-off.

**Речь:** *operate with one hand* — управлять одной рукой; *reduce accidental input* — уменьшить случайный ввод; *provide a comfortable grip* — обеспечить удобный хват.

### 5.9. Googleplex: working environment

**EN:** A working environment should support the activities people perform. Amenities improve comfort; facilities serve particular purposes. Attractive spaces are useful when they address real needs. The Googleplex discussion connected the environment with creativity and well-being. Concentration, collaboration and recovery may require different arrangements; these are design considerations rather than a verified campus list. I would gather staff feedback and test a change against its intended activity.

**Пример:** Googleplex questions: creativity, energy, well-being; точный список объектов видео неизвестен.

**В кейс:** разделить concentration/collaboration/rest needs, собрать staff feedback, проверить pilot layout. Оценить distractions, access, comfort и полезность; не считать наличие дорогих amenities автоматической причиной productivity.

**Речь:** *seek feedback* — искать feedback; *support employee well-being* — поддерживать благополучие; *improve the working environment* — улучшать рабочую среду.

### 5.10. ★ Design thinking, persona, scenario, user flow

**EN:** A persona describes who the user is; a scenario explains the task and context; a user flow maps the steps. Iterative design uses feedback to revise assumptions and prototypes. The happy path is not the only path. The online-shopping example moved from the home page through products and the cart to checkout and confirmation. Real users can return, compare or encounter errors. For an unclear problem, I would define the user's goal, map the difficult step, test a small prototype and revise the design using evidence instead of assumptions.

**Пример:** e-commerce: home → category → product → cart → checkout → confirmation.

**В кейс:** «сделать удобнее» → reframe as конкретная user goal; map steps, найти failure point, prototype, test. Добавить alternative/error paths. Persona должна опираться на research; возраст и фото сами по себе не объясняют requirements.

**Речь:** *reframe the problem* — уточнить постановку; *map the user flow* — описать путь; *challenge assumptions* — проверить допущения.

### 5.11. Engineering prototype / MIPT contest

**EN:** A prototype should address a credible user problem. Link persona, pain point, scenario and technical specifications. Novelty matters only when the proposal is useful and feasible. The MIPT contest connected user research with a storyboard and a technical solution. The prototype could be a wireframe, drawing or physical model. I would test the smallest useful version, explain its mechanism and check technical feasibility separately from whether users like the idea.

**Пример:** MIPT learning environment, EdTech, campus/dormitories; research → storyboard → prototype → presentation.

**В кейс:** сформулировать pain point, сравнить concept options, сделать smallest useful prototype. Проверить функцию с users и technical feasibility отдельно. Указать requirements, cost/maintenance limits; не перечислять technologies без rationale.

**Речь:** *address a pain point* — решить трудность; *explain the rationale* — обосновать решение; *demonstrate feasibility* — показать осуществимость.

### 5.12. Presentations: audience, speaker, transformation

**EN:** Adapt the message to the audience, explain your relevant contribution and define the desired effect. A presentation should change understanding or action, not merely transfer information. An opening must connect with the message. The three ingredients were audience, speaker and transformation. A startup pitch aims to build confidence and encourage support, not simply describe a company. For an engineering proposal, I would start with the audience's problem, explain the relevant benefit and evidence, disclose limitations and make the intended next action clear.

**Пример:** 3 Magic Ingredients; startup pitch → confidence/support; jump start: question/story/imagine/visual.

**В кейс:** stakeholder resistance → выяснить priorities, показать user problem, benefit и evidence. Выбрать opening по контексту, честно назвать limits, дать понятный next step. Проверить понимание и решение аудитории, а не только applause.

**Речь:** *tailor the message* — адаптировать сообщение; *build confidence* — укрепить доверие; *explain why it matters* — объяснить значимость.

### 5.13. ★ Conciseness и progress report

**EN:** A progress report separates completed, current and planned work. Report problems, their impact, the response and the next milestone. Conciseness removes repetition, not useful evidence. The enclosure example reported a CAD model, printed samples and PCB fit checks before remaining work and a thermal test. This connects activity with evidence. For a delay, I would explain the blocker, its impact, mitigation and required support, then give a realistic milestone.

**Пример:** enclosure report: CAD model → PLA samples/PCB fit → mounting-hole update → planned thermal test.

**В кейс:** delay → назвать blocker, effect on time/cost/quality, mitigation и realistic new date. Определить, какое решение/support нужен от manager. Подтверждать progress deliverables/test results; «мы много работали» не показатель.

**Речь:** *remain on track* — идти по плану; *revise the schedule* — пересмотреть график; *report measurable progress* — сообщить измеримый результат.

### 5.14. Flat-plate solar collector / mechanism description

**EN:** Glazing lets sunlight reach the absorber; the absorber heats circulating fluid; a heat exchanger transfers heat to water. Insulation reduces heat loss. This is solar heating, not photovoltaic electricity generation. The enclosure holds the components, and the fluid returns to the collector after releasing heat through the exchanger. The mechanism therefore depends on both heat capture and circulation. If output is low, I would examine the input, transfer and losses along this chain, then compare measured performance under similar conditions after making a change.

**Пример:** enclosure, glazing/frame, absorber, flow tubes/fluid, insulation.

**В кейс:** низкий output → проверить input, heat transfer и losses по цепочке, а не менять всё устройство. Объяснить part→function→interaction; сравнить measured temperatures/output до/после. География и условия влияют на пользу.

**Речь:** *transfer heat* — передавать тепло; *reduce heat loss* — уменьшать потери; *explain the operating cycle* — объяснить рабочий цикл.

### 5.15. Safer, Smarter Smartphone

**EN:** Material choices affect safety, durability, sustainability and performance. Battery, display, housing and internal components create different risks. Improving one property may worsen cost, manufacture or another function. The case identified battery overheating and degradation, broken display glass, sourcing issues and recycling difficulties. It did not provide one approved material combination. I would link each proposed change to a specific risk, compare its properties and manufacturing requirements, and validate durability and function rather than assume that a newer material is automatically safer.

**Пример:** battery overheating/degradation, cobalt sourcing, glass fragments, recycling difficulties; готовой комбинации материалов нет.

**В кейс:** сопоставить hazard каждой части с material/design response; сравнить properties и manufacturing. Проверить thermal/impact performance, lifespan, repair/recycling и сохранение функций. Не объявлять любой «новый» battery material безусловно safer.

**Речь:** *minimise safety risks* — уменьшить риски; *preserve functionality* — сохранить функции; *consider the life cycle* — учитывать жизненный цикл.

## UNIT 6

### 6.1. Aerospace engineering

**EN:** Aeronautical engineering concerns atmospheric flight; astronautical engineering concerns space. Aerodynamics, propulsion, structures and materials interact. The mission and environment determine design requirements. Aircraft interact with air; spacecraft may operate in a vacuum. Materials or propulsion changes affect connected systems. I would define conditions and payload, check components and interfaces, and validate the adaptation against mission requirements.

**Пример:** lunar version требует иных решений, чем аппарат для Earth atmosphere.

**В кейс:** определить atmosphere/gravity/temperature, payload и mission. Проверить adaptation всех connected systems и interfaces; увеличение одного параметра не гарантирует успех whole vehicle. Материалы выбирать под реальные loads/conditions.

**Речь:** *meet mission requirements* — выполнить требования; *provide propulsion* — обеспечивать тягу; *maintain structural integrity* — сохранять целостность.

### 6.2. Artemis / lunar Starship / orbital refuelling

**EN:** In the video's plan, SLS/Orion transport the crew and lunar Starship provides landing. Lunar conditions require changes to the vehicle. Orbital refuelling adds dependencies involving tankers, docking and propellant transfer. The historical video discussed landing equipment and an elevator to move crew and cargo between a high entrance and the surface. It also called for an uncrewed demonstration. For a complex project, I would identify supporting operations, verify interfaces and allow for their effects on time and cost, instead of evaluating the vehicle alone.

**Пример:** elevator для crew/cargo; отсутствие атмосферы меняет control; uncrewed demonstration перед crewed use. Планы видео исторические.

**В кейс:** перечислить critical dependencies, проверить interfaces и failure response. Test components → integrated operation → uncrewed demonstration. Учитывать supporting infrastructure в schedule/cost, а не оценивать только vehicle power.

**Речь:** *refuel in orbit* — дозаправляться на орбите; *deliver a payload* — доставить груз; *verify critical operations* — проверить критические операции.

### 6.3. ★ Moon/planetary base design

**EN:** A base needs shelter, energy, resources, life support and transportation. Local resources are useful only if they can be accessed and processed. Critical systems must remain dependable when supply or equipment fails. The class asked students to adapt these systems to a chosen planet or moon, considering gravity, atmosphere, temperature and resources. Processing local water or materials also needs equipment and power. I would define life-critical requirements, compare supply options and plan appropriate reserves or redundancy, then test the base's response to degraded conditions.

**Пример:** Graded Task 6.1: выбрать planet/moon и адаптировать design к gravity, atmosphere, temperature, resources.

**В кейс:** сначала life-critical requirements, затем power/resources/maintenance dependencies. Предложить reserves или redundancy для нужных функций. Проверить degraded conditions и resource budget; не предлагать geothermal/ice без данных выбранного места.

**Речь:** *provide life support* — обеспечить жизнеобеспечение; *use local resources* — использовать местные ресурсы; *plan for supply interruptions* — учитывать перебои снабжения.

### 6.4. Russian–Chinese lunar station

**EN:** The 2024 article described three stages: research, creation and operations. Construction included control infrastructure, cargo delivery and precise landing. A published plan is not proof of completed implementation. The article also referred to five planned missions and cooperation with international partners. Research establishes needs, construction provides infrastructure and operations use and verify the result. In a project case, I would assign objectives and responsibilities to stages, check readiness before proceeding and distinguish achieved progress from future intentions and unresolved dependencies.

**Пример:** five planned missions; international partners; technology verification during operations.

**В кейс:** разделить project на milestones с objectives, responsible teams и validation. Проверить readiness перед следующим этапом; согласовать partner interfaces. Отдельно назвать achieved progress, remaining work и uncertainty.

**Речь:** *coordinate partners* — согласовать партнёров; *verify technologies* — проверить технологии; *develop the project in stages* — развивать поэтапно.

### 6.5. ★ LiDAR и self-driving perception

**EN:** LiDAR emits laser pulses and uses return time to estimate distance. Multiple measurements describe shape and position. Accurate sensing still requires interpretation, and optical measurements can be affected by poor conditions. The video used returns from different parts of a moose's antlers to explain shape measurements. For a car misreading signs in rain, I would separate degraded sensor input from weaknesses in recognition, consider complementary measurements and define a safe response to uncertainty. Testing should measure missed detections, false alarms and the vehicle's behaviour in realistic conditions.

**Пример:** moose antlers: разные return times; car на dark country road; article camera/ultrasonics/radar/lidar.

**В кейс:** распознавание в rain → проверить optics/visibility и model/data separately. Рассмотреть complementary sensors, uncertainty detection и safe fallback. Проверить missed detections/false alarms в rain/night/glare; improved resolution не гарантирует safety.

**Речь:** *detect an obstacle* — обнаружить препятствие; *interpret sensor data* — понимать данные; *handle low-confidence detections* — обрабатывать неуверенное распознавание.

### 6.6. Integrated photonics / Mach–Zehnder

**EN:** The modulator splits light into two paths, changes their phase difference and recombines them. Interference controls the output. Integrated photonics can reduce the size of optical components and mechanical scanning needs. The video compared interference with ripples that reinforce or cancel each other. Controlling the light allows precise pulses without simply switching the laser itself on and off. In a measurement case, I would check signal timing, detection and processing, and assess whether a smaller design retains the performance required by the application.

**Пример:** ripples on water поясняют reinforcement/cancellation; precise pulses помогают depth measurements.

**В кейс:** объяснить signal generation→control→detection; при measurement error проверять timing и detector, не только software. Miniaturisation оценить вместе с accuracy, reliability и integration. Аналогия иллюстрирует механизм, но не доказывает performance.

**Речь:** *split light into two paths* — разделить свет; *control the phase difference* — управлять разностью фаз; *steer a beam* — направлять луч.

### 6.7. ★ 5G / V2V / V2X

**EN:** V2V connects vehicles; V2X includes infrastructure and other surroundings. Low latency helps time-sensitive communication. Network-dependent functions need a response to lost coverage or delayed information. The article's chicken-and-egg problem was manufacturers waiting for coverage and providers waiting for demand. Connected functions need coordinated investment. I would distinguish onboard capability from external services, test lost or delayed messages and define an operating area and fallback.

**Пример:** chicken-and-egg: manufacturers ждут coverage, carriers ждут demand.

**В кейс:** разделить onboard capability и external service dependency. Предложить defined operating area, outage handling и staged infrastructure rollout. Проверить loss/delay/corrupted data. Не утверждать, что любая автономность невозможна без 5G.

**Речь:** *reduce latency* — уменьшить задержку; *lose network coverage* — потерять покрытие; *define a safe fallback* — определить безопасный запасной режим.

### 6.8. ★ Autonomous transport / regulation / news

**EN:** Potential benefits need evidence under realistic conditions. Deployment requires clear limits, responsibility and monitoring. Separate observed events from unconfirmed explanations of their cause. The news role play distinguished presenter, reporter, engineer and eyewitness, separating events from interpretation. I would define intended use and affected people, begin with a controlled pilot, collect safety evidence and review failures before expansion rather than assume automation removes all errors.

**Пример:** news role play: presenter/reporter/engineer/eyewitness; regulation questions Waymo, Uber, Wing; полных видео нет.

**В кейс:** определить intended use, risks, affected people и ответственность. Controlled pilot → collect evidence → review → wider rollout. Для malfunction сохранить факты и investigate; don't blame a single cause без данных. «Automation» не устраняет все ошибки.

**Речь:** *test under controlled conditions* — проверять в контролируемых условиях; *clarify responsibility* — определить ответственность; *investigate a malfunction* — расследовать сбой.

### 6.9. InfiniteGraph / analogy for non-specialists

**EN:** The course text describes adding and querying distributed data at the same time. A library network makes distribution and simultaneous activity easier to understand. An analogy explains a function but does not prove performance claims. The analogy described connected library branches adding books while people continued searching and borrowing. It illustrated continuous activity and access across locations. For a non-specialist, I would explain the problem and function before terminology. For a purchase decision, I would also require tests using the actual workload rather than treat the analogy as a benchmark.

**Пример:** branches добавляют books, оставаясь открытыми; общая сеть позволяет искать connected information.

**В кейс:** stakeholder не понимает system → объяснить problem/function, дать analogy, уточнить limits. Для выбора system нужны workload-specific tests, downtime и response time; рекламные claims не заменить benchmark.

**Речь:** *handle incoming data* — обрабатывать входящие данные; *avoid downtime* — избегать простоя; *make the mechanism clear* — объяснить механизм.

### 6.10. ★ The Martian: triage, survival, resources

**EN:** Stabilise life-critical functions before solving long-term problems. Assess damage, supplies and constraints. A scientific solution may create a new hazard, so its risks must also be evaluated. The film covered mission abort, suit damage, oxygen, the habitat and food shortages. These have different urgency. I would address immediate danger, establish a resource plan and evaluate new failure modes before proceeding. The film is an illustration, not a practical safety procedure.

**Пример:** storm/mission abort; suit breach/oxygen/pressure; HAB; limited food, water production и выращивание пищи.

**В кейс:** immediate risk → emergency repair → resource plan → longer-term action. Сначала oxygen/power/pressure, если они критичны; оценить reserves и новые failure modes. Проверять incremental changes, не использовать film procedure как реальную инструкцию.

**Речь:** *assess the damage* — оценить повреждения; *prioritise critical systems* — выделить критические системы; *manage limited supplies* — управлять запасами.

### 6.11. The Martian: communication, rescue, ethics

**EN:** Communication connects individual survival with collective problem-solving. Rescue decisions involve risk, responsibility and limited information. Compare alternatives and explain who is affected by the decision. The lesson discussed satellite information, slow communication, secrecy and risking many lives to save one astronaut. Technical feasibility meets ethics. I would establish shared information, assign roles, compare options and communicate uncertainty, explaining how changes affect the wider plan and participants.

**Пример:** satellite images, slow communication, rescue teamwork; «risk many lives to save one?» и secrecy.

**В кейс:** проверить information flow, allocate roles, share critical updates. Сравнить expected benefit и risk для всех участников; объяснить uncertainty и consent/knowledge. Решение менять только с пониманием влияния на whole plan.

**Речь:** *restore communication* — восстановить связь; *weigh the risks* — сопоставить риски; *share critical information* — делиться важной информацией.

### 6.12. Interstellar: time и consequences

**EN:** Time and environmental conditions constrain mission choices. Near the black hole in the film, little time for the visiting astronauts corresponds to much more elapsed time elsewhere. A fictional mechanism is not a demonstrated technology. The course connected Earth's crop failures with the search for another habitat, and time dilation with consequences for the crew and family. In a mission case, I would account for delays, resources and the cost of choosing one strategy over another. The film supports discussion of responsibility, while its speculative transport should remain an illustration.

**Пример:** Earth crop failures; wormhole near Saturn; Miller planet time dilation; последствия для Cooper/Murph.

**В кейс:** учесть delays и opportunity cost, сравнить стратегии и последствия для stakeholders. Отличить assumption от evidence. Фильм использовать для аргумента о planning/responsibility, не как доказательство возможности wormhole transport.

**Речь:** *account for time constraints* — учитывать ограничения времени; *consider long-term consequences* — учитывать последствия; *question an assumption* — проверить допущение.

### 6.13. ★ Electricity demand / electrification

**EN:** Power is the rate of energy use: one watt equals one joule per second. Electrification increases electricity needs and should be linked with cleaner generation. Supply requires generation, grids and storage. The video traced coal through heat, steam, a turbine and a generator to the grid. It discussed electric cars, heat pumps and industrial heating as sources of growing demand. For a shortage, I would identify whether generation, transmission or timing is the bottleneck and compare supply with peak demand, losses and the need for storage.

**Пример:** coal → furnace → steam → turbine → generator → grid; cars, heat pumps, industrial heat.

**В кейс:** shortage → найти bottleneck: generation, transmission или timing. Сопоставить demand profile с usable supply, рассмотреть efficiency/storage/grid upgrade. Проверять peak periods и outages. W — мощность; kWh/J — энергия за период.

**Речь:** *meet electricity demand* — покрыть потребность; *upgrade the grid* — обновить сеть; *reduce energy waste* — уменьшить потери энергии.

### 6.14. ★ Energy sources / fission / fusion

**EN:** Renewable and low-carbon are different properties. Wind and solar output varies with conditions; storage and grids can help. Fission splits nuclei, while fusion combines light nuclei; no source solves every requirement. Renewable describes replenishment, while low-carbon concerns emissions. A source can have environmental effects even when it is renewable. For an energy proposal, I would compare availability, cost, waste and reliability at the chosen site, then consider a suitable combination of sources and storage instead of choosing only from one attractive property.

**Пример:** homework compares wind/solar, fossil fuels, nuclear; fusion обсуждается как перспектива.

**В кейс:** сравнить availability, reliability, emissions, cost, waste и site. Выбрать mix/backup под demand. Не утверждать zero impact у renewables, constant output у hydro или отсутствие любых hazards у fusion.

**Речь:** *harness renewable energy* — использовать энергию; *store surplus energy* — хранить избыток; *compare environmental impacts* — сравнить воздействие.

### 6.15. ★ Virunga Power / rural electrification

**EN:** Affordable and reliable electricity requires more than generation. Virunga's article combines run-of-river hydro, local grids, financing and partnerships. Local conditions and a sustainable operating model determine usefulness. The 2020 article argued that rural communities needed a practical distribution system and an affordable service, not merely a power plant. Kelly's infrastructure-financing experience informed the model. In a case, I would assess the resource, seasonal supply, customer needs and operating costs, and check whether the project can be maintained and financed over time.

**Пример:** Brian Kelly, статья 2020; мегаваттные hydro projects и rural distribution; smart metering/mobile payments.

**В кейс:** rural supply → оценить local resource, demand, distribution, affordability и maintenance. Сравнить scale options, партнёров и funding; проверить seasonal output и service cost. Старые target prices не переносить как current tariff.

**Речь:** *provide affordable power* — дать доступную электроэнергию; *serve rural communities* — обслуживать сообщества; *finance infrastructure* — финансировать инфраструктуру.

### 6.16. Wind turbines / engineering criteria

**EN:** Wind turns the rotor; the generator converts mechanical input into electricity. Reliable equipment may still have insufficient output at a particular site. Compare effectiveness, efficiency, suitability and life-cycle cost separately. The lesson's offshore discussion raised questions about materials, maintenance and lifespan. Effective means achieving the result; efficient means using resources well; sufficient means enough for the need. I would assess the wind resource and access for maintenance, compare total costs over service life and plan integration if variable output does not match demand.

**Пример:** offshore materials/maintenance/lifespan discussion; FAQ для factories/hospitals/campuses. Конкретный material winner неизвестен.

**В кейс:** site wind, obstacles, maintenance access, exposure и demand → options → test expected output. Сравнить total cost за lifespan, не только purchase price. Для variable supply предусмотреть integration/storage, если нужно.

**Речь:** *select a suitable site* — выбрать место; *assess expected output* — оценить выработку; *compare service life* — сравнить срок службы.

### 6.17. Solar tower / solar chimney

**EN:** Sunlight heats air under a glass enclosure. Buoyancy-driven airflow rises through a chimney and drives turbines. Increasing scale also increases structural and maintenance demands. The text described the stack effect and a proposed tower, not a confirmed installation. This uses moving warm air, not photovoltaics. I would examine heating, airflow and generation together, comparing output with site conditions, structural loads, cost and maintenance.

**Пример:** Solar Tower text в Physical Forces; kilometre-high proposal, не подтверждённый completed project.

**В кейс:** проверить heat→airflow→turbine conversion и structural loads; сравнить useful output, site и construction cost. Увеличение height не считать готовым решением. Это updraft chimney, а не PV или mirror/receiver tower.

**Речь:** *create an upward airflow* — создать восходящий поток; *drive a turbine* — вращать турбину; *account for structural loads* — учитывать нагрузки.

### 6.18. ★ Physical forces / space elevator / maglev / airships

**EN:** Tension pulls, compression pushes inward, torsion twists and shear acts parallel to a section. Pressure is force per unit area. Match material properties to the actual loads and environment. The related examples included a tether-based space elevator, magnetic support for maglev and buoyancy for airships. Each needs supporting systems and suitable conditions; maglev still faces air resistance. For a structural problem, I would identify the failure mode, select properties and geometry for combined loads, and validate the complete design rather than one material parameter.

**Примеры:** space elevator — tether/tension/rotation; maglev — magnetic support, но остаётся air resistance; airship — buoyancy, rigid/non-rigid structure.

**В кейс:** определить load/failure mode, подобрать strength/stiffness/toughness и geometry, проверить combined loads. Для elevator — feasibility tether/support systems; maglev — infrastructure/power; airship — weather/control. Не обещать реализованный full-scale space elevator.

**Речь:** *withstand tensile loads* — выдерживать растяжение; *resist deformation* — сопротивляться деформации; *maintain structural stability* — сохранять устойчивость.

## 12 фраз, которые помогают развернуть ответ без повторений

1. **The case does not identify a single cause, so I would investigate…** — не делаю неподтверждённый вывод.
2. **This matters because…** — объясняю значимость.
3. **The mechanism is…** — раскрываю, как решение работает.
4. **A relevant course example is…** — ввожу пример.
5. **The same principle applies here because…** — связываю пример с билетом.
6. **The first option addresses…, while the second addresses…** — различаю решения.
7. **This would reduce…, but it would not eliminate…** — называю предел.
8. **The main trade-off is between… and…** — сравниваю конкурирующие цели.
9. **If this component fails, the system should…** — даю fallback.
10. **I would compare… before and after the change.** — предлагаю проверку.
11. **Success would mean…** — определяю критерий успеха.
12. **I would prioritise… because it addresses the most serious risk.** — обосновываю выбор.

Не вставляй все 12 подряд. Выбирай нужные по логике ответа.

### Слова, которые дают точность

| Различие | Что помнить |
|---|---|
| Effective / efficient | Достигает результата / экономно расходует ресурсы |
| Reliable / sufficient | Работает надёжно / хватает для потребности |
| Hard / tough | Устойчив к вдавливанию / поглощает энергию до разрушения |
| Accuracy / resolution | Близость результата к истинному / различение деталей |
| Latency / data rate | Задержка / объём данных за время |
| Prevention / recovery | Предотвращение / восстановление после проблемы |
| Encoding / encryption | Изменение представления / шифрование для защиты |
| Usability / UX | Выполнение задачи / весь пользовательский опыт |
| Biocompatible / bioactive / biodegradable | Подходит для контакта / вызывает полезный ответ / разлагается |
| Renewable / low-carbon | Возобновляется / низкие выбросы; признаки различаются |
| Energy / power | J или kWh / W; количество / скорость передачи |
| Autonomous / automotive | Самостоятельное управление / относящийся к автомобилям |

## Как использовать три минуты: один пример, много анализа

**Пример билета:** autonomous car misreads stop signs in heavy rain. Ниже тезисы для речи; это не полный ответ на три минуты.

- **Problem:** Incorrect recognition may cause an unsafe decision.
- **Cause 1:** Rain or water on the optics may reduce input quality.
- **Cause 2:** The model may not handle wet-weather examples reliably.
- **Solution 1:** Protect/clean the optics and check sensor performance.
- **Solution 2:** Review training/validation data and consider complementary sensors.
- **Course:** LiDAR explains sensing limits; digital twins show why simulation must match reality.
- **Limit:** Better data cannot guarantee correct behaviour in every situation; extra sensors add cost and complexity.
- **Fallback:** Low confidence should trigger a defined safe response appropriate to the traffic situation.
- **Test:** Simulation → controlled track → realistic conditions. Measure missed signs, false alarms and whole-vehicle behaviour in rain/night/glare.
- **Choice:** Prioritise the highest safety risk and validate before wider deployment.

Расширение: на каждой причине/решении объясни **why/how**, затем один пример и limitation. Три минуты получаются из reasoning, а не из длинного definition LiDAR.

## Подготовка за 120–180 минут

**Первые 120 минут — основной маршрут:**

| Минуты | Действие |
|---|---|
| 0–10 | Каркас ответа + таблица выбора тем. Воспроизвести 6 шагов без файла. |
| 10–35 | UNIT 4: прочитать все карточки; на ★ запомнить principle + example + test. |
| 35–60 | UNIT 5: такой же проход; особенно risk, usability, SDLC. |
| 60–85 | UNIT 6: такой же проход; особенно sensing, energy, critical systems. |
| 85–100 | Закрыть файл. Пересказать 5 ★ карточек по 40–60 секунд; проверить только забытое. |
| 100–120 | Два мини-кейса: 5 минут заметок + 3 минуты речи + 2 минуты проверки для каждого. |

**Если есть третий час:** 20 минут — только слабые темы; 20 минут — ещё два кейса по той же схеме; 10 минут — words/phrases; 10 минут — повторить 8 course examples. Перерывы можно взять из этого часа. Не возвращайся к длинным исходным рассказам, если уже понимаешь тему.

**Мини-кейсы для тренировки:** uncomfortable workstation; cracked component; unreliable prediction; leaked customer data; project delay; insufficient energy supply. Это придуманные ситуации, не дополнительные билеты LMS.

### Восемь примеров для последнего повторения

| Пример | Какой аргумент поддерживает |
|---|---|
| DeSimone resin printing | Устранять конкретный bottleneck процесса |
| Digital twin: train vs thermostat | Testing должен соответствовать criticality |
| Vibrating vest / Jonathan | Alternative input требует training; evidence ограничено |
| Scaffold | Porosity ↔ strength; biological и mechanical requirements |
| Failed student app | Requirements + design + testing влияют на качество |
| Backup Paradox | Recovery не отменяет confidentiality breach |
| 5G chicken-and-egg | Инфраструктура зависит от согласования участников |
| Virunga hydro + grids | Generation, affordability, financing и operation работают вместе |

**Готовность:** можешь назвать проблему, две возможные причины, два связанных решения, один course example, limitation и measurable test. Не обязан помнить все имена и даты.

## На что не тратить время

Даты патентов, точные размеры collector, число tanker launches, старые тарифы, карьера speaker, конкурсные баллы и имена всех персонажей не нужны для большинства аргументов. Важнее mechanism, trade-off, example и validation.

Источник — три ранее составленных файла UNIT_4/5/6_spoken_topic_texts.md и разобранный Task_2_case_answer_guide.md. Исторические планы/claims и фильмы остаются примерами материала курса, не текущими фактами. Неполученные подробности видео не восстановлены. Численные нормы ergonomics и гарантии medical performance здесь не добавлены.
