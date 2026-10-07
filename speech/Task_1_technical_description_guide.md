# Первое задание билета — technical description

## 1. Что хотят в билете и что объясняли в LMS

В примере билета: **“Write a mechanism description of a 3D-Printing technology tailored for a semi-technical or technical audience. 250–300 words.”** Значит, нужно объяснить механизм конкретной технологии 3D-печати, адаптировать язык к выбранной аудитории и уложиться в объём.

На странице [Writing: Technical Description](https://lms.mipt.ru/mod/page/view.php?id=225352) дана структура:

**1. Topic sentence → 2. Device/Technology characteristics → 3. Solution to a Problem → 4. Functionality.**

Там же выделяются **product description** — изделие и его характеристики, и **process description** — как работает процесс. Для билета с mechanism description важно связать их: назвать основные части и объяснить, каким образом их взаимодействие даёт результат.

На [занятии Classes 9–10](https://lms.mipt.ru/mod/page/view.php?id=225350) предлагали описать haptic technology или 3D printer для semi-technical audience, уделяя внимание структуре, стилю, clarity, coherence и cohesive devices. Учебное упражнение было на **70–100 слов**. В твоём билете нужен **другой объём — 250–300 слов**: сохраняем принципы, но подробнее объясняем устройство и механизм.

На странице Writing отдельно объясняют:

- **Definition** классифицирует: что это за тип устройства или процесса.
- **Description** характеризует устройство и его работу.
- **Summary** сообщает, что произошло или что было сделано.

Поэтому история изобретения, общие рассуждения о будущем и пересказ видео не должны занимать место механизма. Определение полезно в начале, но само по себе не составляет technical description.

**Что подтверждено материалами:** четыре структурных элемента, адаптация к аудитории, ясность, связность, объяснение характеристик и функций; обычно настоящее время. **Мои рекомендации для экзамена:** четыре абзаца, ориентиры по словам, план подготовки и самопроверка. Это удобная реализация схемы, а не дополнительные официальные правила. Полная рубрика оценивания и содержимое преподавательской презентации в доступном текстовом материале не восстановлены.

## 2. Какую технологию выбрать

Если задание разрешает выбрать технологию 3D-печати, проще описывать **FDM — fused deposition modelling**: подача термопластичной нити, нагрев, экструзия, послойное построение. Здесь легко объяснить компоненты и причинные связи знакомыми словами.

Не смешивай в одном механизме filament, vat of resin и laser sintering:

| Метод | Исходный материал | Основной механизм |
|---|---|---|
| FDM | Термопластичная нить — filament | Нагрев и выдавливание материала через сопло |
| SLA | Фоточувствительная смола — resin | Отверждение выбранных участков светом; традиционно лазером |
| SLS | Порошок | Спекание выбранных участков лазером |

Выбери один метод и назови его. Если в другом билете задан другой объект, следуй именно его формулировке. Выбор FDM — рекомендация для текущего примера, не универсальный ответ на все темы.

## 3. Аудитория — как выбирать язык

**Semi-technical audience:** человек знаком с общими техническими понятиями, но не обязан знать устройство конкретного принтера. Можно использовать CAD, nozzle, filament, extrusion, но ключевые термины нужно раскрыть при первом употреблении.

**Technical audience:** можно опираться на большее число известных терминов и точнее обсуждать процессы и параметры. При этом сложность слов не заменяет ясного описания.

Пример для semi-technical: “A slicer is software that divides the model into layers and generates movement instructions.”

Для более технической аудитории: “The slicer generates toolpaths and process settings from the digital model.”

Лучший выбор для подготовки за короткое время — semi-technical: понятные предложения и несколько объяснённых терминов. Не превращай текст в детское сравнение с «магическим принтером». Аналогия допустима, если помогает, но в билете механизм должен быть объяснён буквально.

**PEER** в UNIT 4 использовали для объяснения технологий общей аудитории и poster session. Для этого письменного задания опирайся прежде всего на схему technical description из Writing, а не автоматически копируй PEER как обязательную структуру.

## 4. Рабочая структура на 250–300 слов

Цель — около **270–285 слов**: остаётся запас для исправлений. Достаточно 14–18 содержательных предложений. Это ориентир, а не требование к их количеству.

| Абзац | Элемент LMS | Примерный объём | На какие вопросы отвечает |
|---|---|---|---|
| 1 | Topic sentence | 35–45 слов | Что это? К какому классу относится? Что создаёт? |
| 2 | Characteristics | 55–65 слов | Какие основные части и материалы? Зачем они нужны? |
| 3 | Solution to a problem | 35–45 слов | Какую практическую потребность закрывает? Где полезно? |
| 4 | Functionality | 120–135 слов | Откуда берутся инструкции? Как поступает и меняется материал? Как формируется объект? |

Например, 40 + 60 + 40 + 130 = **270 слов**. Главная часть — механизм. Текст может иметь другую разбивку на абзацы, если все элементы ясно присутствуют и последовательность понятна.

### Абзац 1 — дать определение и функцию

Схема: **название → класс → отличительная функция → результат**.

“Fused deposition modelling is an additive manufacturing process that creates objects by depositing thermoplastic material layer by layer.”

Это отвечает «что это и что делает». Добавь цифровую модель как источник геометрии. Не начинай с “Nowadays technology is very important in our lives”: такое вступление почти не помогает описанию.

### Абзац 2 — связать части с функциями

Не просто “It has a nozzle, a motor and a platform”, а **component + function**:

- Extruder — подаёт filament.
- Heated nozzle — нагревает и наносит материал.
- Build platform — поддерживает растущий объект.
- Motors — обеспечивают относительное движение печатающей головки и платформы.
- Controller — выполняет инструкции, задающие движение и условия печати.

Сведения о форме, размере, цвете нужны только если помогают понять механизм. Не выдумывай модель принтера, мощность или размер сопла.

### Абзац 3 — назвать конкретную пользу

Проблема может быть потребностью, а не аварией: инженеру нужен физический прототип, индивидуальная деталь или проверка геометрии до изготовления оснастки.

Хорошо: “The process allows engineers to evaluate a prototype before investing in dedicated tooling.”

Слабо: “This technology solves many problems and makes life better.”

Один пример применения достаточен. Если добавляешь ограничение, оно должно быть конкретным и связанным с механизмом: допустим, качество зависит от параметров печати. Ограничение не названо отдельным обязательным элементом схемы LMS; оно полезно при наличии места.

### Абзац 4 — объяснить причинную последовательность

Для FDM:

**Digital model → slicing → instructions → filament feeding → heating/extrusion → deposition → cooling/bonding → next layer → finished object.**

Описывай не только порядок, но и физический переход: нить размягчается, через сопло выходит материал, на платформе формируется слой, соседние дорожки и слои соединяются. Именно это превращает перечень этапов в описание механизма.

Назови support structures, если объясняешь overhangs. В конце можно указать снятие детали и удаление поддержек после охлаждения. Не нужно добавлять длинный общий вывод — последнее предложение может завершать процесс.

## 5. Универсальный шаблон

Заменяй скобки сведениями о своей технологии. Этот каркас нужно разворачивать до требуемого объёма, а не сдавать как короткую заготовку.

> [Technology] is a [class of process/device] that [core function]. It uses [input/material] to produce [output]. The process is suitable for [specific purpose].
>
> The main components include [A], [B] and [C]. [A] is responsible for [function], while [B] [function]. [C] allows [component/system] to [action]. The system uses [material/property] because [relevant reason].
>
> The technology addresses the need for [practical need]. It enables [users] to [useful action] without [specific difficulty, if true]. For example, [brief application]. Its performance depends on [important condition].
>
> First, [preparation/input stage]. Next, [processing stage]. During this stage, [component] [action], which causes [physical effect]. The resulting [material/signal] is [next action]. As [process happens], [effect]. This sequence is repeated until [completion condition]. Finally, [output or finishing stage].

Для другого механизма та же логика: **input → transformation → transfer/control → output**. Например, для виброжилета: sound → digital processing → patterns for motors → vibrations on the skin → perceived information. Для цифрового двойника: sensor data → model update → simulation/analysis → monitoring output. Это примеры адаптации, а не готовые ответы на неизвестные билеты.

## 6. Конструктор предложений

### Определение

- “[X] is a device that…”
- “[X] is a process in which…”
- “[X] refers to a method of…”
- “The core function of [X] is to…”

### Части и материалы

- “The system consists of…”
- “The main components include…”
- “The [component] is connected to…”
- “The [part] is made of [material].”
- “A [material property] enables the part to…”

**Consists of** удобно для полного состава; **includes** — если перечисляешь лишь главные элементы. Не называй перечень из трёх частей полной конструкцией сложного устройства.

### Связь части с функцией

- “The [component] feeds/heats/transmits/controls…”
- “[X] allows [Y] to…”
- “[X] enables [Y] to…”
- “[X] prevents [Y] from…”
- “[X] ensures that…”
- “[X] is designed to…”

### Преобразование

- “[X] converts [input] into [output].”
- “[X] is heated until…”
- “As [X] cools, it…”
- “The material is deposited onto…”
- “The signal is transmitted to…”
- “This causes/enables…”

### Последовательность

- “First,…”
- “Next,…”
- “During this stage,…”
- “Once [condition],…”
- “The process continues until…”
- “Finally,…”

Чередуй связи, но не ставь отдельную вводную фразу перед каждым предложением. Однозначные ссылки вроде “the material”, “this layer” и “the resulting signal” тоже создают связность.

## 7. Как писать связно по требованиям LMS

Страница Writing отдельно называет **referencing, repetitions, substitutions** в разделе Coherence and Cohesion. В практическом тексте это работает так:

**Referencing:** местоимение или указательное выражение с ясным предметом. “The nozzle heats the material. This heating softens the polymer.” Понятно, что означает this heating.

**Repetition:** повтор точного термина там, где он нужен. Не заменяй nozzle на пять разных «красивых» слов: читателю может показаться, что появились новые детали.

**Substitution:** разумная замена уже введённого предмета: “the process”, “the device”, “the printed part”. Подмена должна сохранять смысл.

**Coherence:** мысли идут от определения к устройству, применению и работе. **Cohesion:** предложения связаны языковыми средствами. Текст может иметь много however/therefore и всё равно быть нелогичным, если его факты не связаны.

### Пример исправления

Слабо: “The printer has a nozzle. Plastic is used. The model is on a computer. It is useful. The object appears.”

Лучше: “The printer uses a digital model to control material deposition. The extruder feeds thermoplastic filament into a heated nozzle, where it softens. The nozzle then deposits the material along the path specified by the software, forming a layer of the object.”

Здесь читатель понимает связь модели, деталей принтера и материала.

## 8. Стиль и грамматика

### Present Simple для обычной работы

“The motor moves the print head.” / “The material cools after deposition.”

Описываешь регулярный механизм, поэтому не нужны постоянные will и рассказ в Past Simple. Будущее подходит для прогноза, прошлое — для исторического эпизода, но оба обычно не являются центром задания.

### Passive, когда важен процесс

“The model is divided into layers.” / “The material is deposited onto the platform.”

Active, когда важна функция детали: “The extruder feeds the filament.” Чередовать их естественно. Не нужно переводить каждое предложение в passive ради формальности.

### Относительные предложения

“The nozzle, which contains a heater, softens the material.”

“A slicer is software that generates printing instructions.”

Они позволяют объяснить термин без отдельного длинного отступления.

### Причастные конструкции из UNIT 4

“Controlled by the software, the print head follows a programmed path.”

“Using a digital model, the printer builds the object layer by layer.”

Оборот должен относиться к правильному подлежащему. Неудачно: “Heating the filament, the object is formed.” Получается, что объект нагревает нить. Лучше: “The nozzle heats the filament, which is then deposited to form the object.”

### Точность без преувеличения

“can”, “typically”, “depending on the design” подходят там, где работа различается между системами. Не надо добавлять их к каждому факту. Не пиши “FDM always produces perfectly accurate parts” или “3D printing creates no waste”.

### Регистр

Нейтральный технический стиль: “The process enables…” вместо “I think this amazing technology…”. Первое лицо не запрещено самим текстом билета, но обычно не требуется описанию механизма. Сокращения типа “doesn't” лучше заменить на “does not” в формальном письменном ответе.

## 9. Как набрать 250–300 слов содержательно

Не расширяй описание за счёт истории человечества или общих похвал. Есть пять полезных направлений:

1. **Назови функцию каждой важной части.** Не только extruder, а что и куда он подаёт.
2. **Раскрой один ключевой термин.** Что такое slicing или filament.
3. **Объясни физическое изменение.** Как нагрев позволяет материалу пройти через сопло, а охлаждение помогает форме сохраняться.
4. **Укажи причинную связь.** Почему поддержки нужны для некоторых нависающих участков.
5. **Добавь одно конкретное применение и условие качества.** Прототип и зависимость от настроек.

### Пример развертывания

Коротко: “The nozzle prints plastic.”

Содержательно: “The extruder feeds thermoplastic filament into a heated nozzle. The heater softens the polymer so that it can pass through the nozzle opening. The material is then deposited along a programmed path, forming a thin layer of the object.”

Каждое предложение добавляет новый элемент механизма. Если после него читатель не узнал ничего нового, расширение, скорее всего, лишнее.

## 10. Словарь для описания FDM

| Сочетание | Смысл |
|---|---|
| additive manufacturing | аддитивное производство |
| fabricate a physical object | изготовить физический объект |
| a digital model / CAD model | цифровая модель / модель системы автоматизированного проектирования |
| thermoplastic filament | термопластичная нить |
| feed the filament into a nozzle | подать нить в сопло |
| a heated nozzle | нагреваемое сопло |
| extrude the material | выдавить материал |
| deposit material onto a platform | нанести материал на платформу |
| follow a programmed path | следовать запрограммированной траектории |
| build the object layer by layer | строить объект слой за слоем |
| bond with the previous layer | соединиться с предыдущим слоем |
| support structures / overhangs | поддержки / нависающие участки |
| rapid prototyping | быстрое создание прототипов |
| dimensional accuracy | точность размеров |
| surface finish | качество поверхности |
| remove the completed part | снять готовую деталь |

Часть слов есть в Target Vocabulary UNIT 4; технические сочетания добавлены для описания выбранного механизма. Не все выражения в таблице названы официальной активной лексикой курса.

Проверяй пары: **material** — материал, **materials** — разные материалы; **technology** — технология, **technique** — метод; **manufacturing** — производство, **manufacturer** — производитель; **melt/soften** — плавиться/размягчаться, **cure** — отверждаться в контексте смолы.

## 11. Полный пример для билета

**Тема:** Fused Deposition Modelling. **Аудитория:** semi-technical. **Объём: 266 слов**, если считать дефисные сочетания одним словом; заголовок не учитывается. Текст ниже следует четырём элементам схемы LMS; заголовок и пояснения не являются частью ответа.

### Fused Deposition Modelling

> Fused deposition modelling, or FDM, is an additive manufacturing process that produces three-dimensional objects from thermoplastic filament. Instead of removing material from a solid block, the printer deposits material layer by layer according to a digital model. The finished object reproduces the shape specified in that model.
>
> An FDM printer typically includes a filament spool, an extruder, a heated nozzle, a build platform and a motion system. The extruder feeds filament into the nozzle, where a heater softens the polymer. Motors move the print head and platform relative to each other, while a controller coordinates movement and temperature.
>
> The process addresses the need to produce prototypes and customised parts without dedicated moulds. For example, an engineer can fabricate a model to evaluate its shape and dimensions before conventional production. However, the quality of the part depends on the material, geometry and printing settings.
>
> First, the digital model is prepared in computer-aided design software and processed by a slicer. This software divides the model into thin layers and generates instructions for the printer. Next, the extruder pushes filament through the heated nozzle. The nozzle deposits the softened material along a programmed path on the build platform. As the material cools, it becomes solid and bonds with neighbouring strands and the previous layer. The printer then changes the relative height of the nozzle and platform to create the next layer. This sequence continues until the complete object is formed. Where necessary, temporary support structures prevent overhanging sections from collapsing during printing. Finally, the part is allowed to cool, removed from the platform and finished by removing the supports.

### Как разобрать пример

**Абзац 1:** определение, отличие от удаления материала, результат. Сразу ясно, какой метод описывается.

**Абзац 2:** главные части и их функции. Ничего не перечислено просто ради перечисления.

**Абзац 3:** потребность в прототипах и индивидуальных деталях; конкретное применение; короткое условие качества.

**Абзац 4:** цифровые инструкции → подача → нагрев → нанесение → охлаждение и соединение → следующий слой → завершение. “As”, “then”, “until” и “finally” связывают механизм. Supports объяснены через функцию.

Здесь намеренно нет истории изобретения, перечня всех отраслей и обещания идеальной точности. Описывается один процесс. Формулировка про относительное движение подходит разным конструкциям FDM-принтеров, где головка и платформа могут двигаться по-разному.

## 12. Частые ошибки и исправления

| Ошибка | Почему мешает | Исправление |
|---|---|---|
| Описать «3D-печать вообще» через все методы сразу | Получается смешанный механизм | Выбрать и назвать FDM, SLA или другой метод |
| Перечислить части без функций | Читатель не понимает взаимодействия | Component → action → effect |
| “It allows to create objects.” | После allow нужен объект | “It allows engineers to create objects.” |
| “It prevents the material to collapse.” | Неверная конструкция | “It prevents the structure from collapsing.” |
| “The printer consist of…” | Нет окончания третьего лица | “The printer consists of…” |
| “The model is divide…” | Нет past participle | “The model is divided…” |
| “The filament is feed…” | Неверная форма | “The filament is fed…” |
| “3D printing is a technology who…” | Who для людей | “…a technology that…” |
| “It” после нескольких разных деталей | Неясная отсылка | Повторить “the nozzle” или “the controller” |
| “Firstly” перед каждым этапом | Нет реальной последовательности | First → next → during this stage → finally |
| “It guarantees perfect accuracy.” | Необоснованное обещание | Назвать конкретное свойство и условие |
| Общий вывод на 60 слов | Вытесняет механизм | Завершить результатом процесса |

## 13. План написания на экзамене

В примере билета время на письменную часть не указано. Поэтому следующий план — тренировочная схема, которую надо адаптировать к реальному регламенту. При условных **30 минутах**: 5 минут на план, 20 минут на текст, 5 минут на проверку. Если времени меньше, сохраняй все три стадии и сокращай их.

### До написания

1. Прочитай точную тему и аудиторию.
2. Выбери один механизм, если выбор разрешён.
3. Запиши 4–5 частей устройства и функции.
4. Запиши цепочку input → transformation → output.
5. Разметь четыре абзаца и примерный объём.

### Во время написания

Пиши простыми правильными предложениями. Для каждого компонента скажи действие, для каждого этапа — результат. Если забываешь термин, объясни его функцию: “software that divides the model into layers” лучше пустого места.

### После написания

Сначала проверь механизм и порядок, затем грамматику и слова. Подсчитай объём. При ручном письме считать проще по абзацам или строкам с заранее известной средней длиной, но окончательная проверка по словам точнее. Не считай 270 слов правилом вместо диапазона 250–300.

## 14. Как подготовиться за два часа

| Время | Действие | Результат |
|---|---|---|
| 0–15 мин | Прочитать требования, структуру и разбор примера | Знаешь четыре элемента LMS |
| 15–30 мин | Нарисовать механизм FDM и подписать детали | Можешь объяснить процесс по схеме |
| 30–45 мин | Выучить 10 сочетаний и 4 конструкции функций | По одному собственному предложению |
| 45–70 мин | Написать свой текст по опорным словам без копирования | Первая версия на 250–300 слов |
| 70–80 мин | Перерыв | |
| 80–100 мин | Проверить механизм, связность, формы глаголов и объём | Исправленная версия |
| 100–115 мин | Написать заново слабейший абзац без подсказки | Навык объяснения, а не память о тексте |
| 115–120 мин | Составить памятку из четырёх строк | Каркас перед экзаменом |

На следующем повторении перепиши тему с другими формулировками. Не учи весь пример побуквенно: другая формулировка билета может потребовать иной технологии или аудитории. Учить стоит структуру, механизм и сочетания.

## 15. Самопроверка перед сдачей

- 250–300 слов?
- Назван конкретный метод или устройство?
- Аудитория учтена, ключевые термины понятны?
- Есть definition/topic sentence, characteristics, practical need и functionality?
- Названные компоненты связаны с функциями?
- Можно проследить вход, преобразование и результат?
- Объяснено, почему этапы дают нужный эффект?
- Нет смешения процессов FDM/SLA/SLS?
- Present Simple и passive используются правильно?
- Allow/enable + somebody/something + to; prevent + from + -ing?
- Все it/this/which относятся к ясному предмету?
- Нет выдуманных параметров, абсолютных обещаний и лишних общих рассуждений?

## Памятка из четырёх строк

**What it is and what it does.**

**What it consists of and what the parts do.**

**What practical need it addresses.**

**How the input becomes the output step by step.**

Источники: присланный пример билета; страницы LMS Writing: Technical Description и Classes 9–10; механизм FDM из материала [Class 3, Jigsaw Reading](https://lms.mipt.ru/mod/page/view.php?id=225340). Пример текста и план тренировки составлены для подготовки по этим требованиям.
