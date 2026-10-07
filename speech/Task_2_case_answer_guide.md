# Как подготовиться ко второму заданию билета

## 1. Что именно от тебя требуется

В присланном билете второе задание — устный разбор инженерного кейса: **5 минут подготовки, минимум 3 минуты выступления, понятная структура, анализ проблемы, предложенные решения и Target Vocabulary семестра**. Вопросы под кейсом задают обязательные направления ответа.

Первое задание — письменное описание механизма 3D-печати на 250–300 слов. Этот лимит НЕ относится ко второму заданию. Для второго важнее длительность, полнота и связность речи. Официальной подробной шкалы оценивания в примере нет; рекомендации ниже — стратегия подготовки, а не дополнительные требования экзаменатора.

Кейс образца: беспилотный автомобиль неправильно распознаёт stop signs в сильный дождь. Нужно объяснить влияние погоды на точность датчиков, дополнительные меры безопасности и проверку обновлённой системы.

Твоя задача — предложить обоснованное решение при недостатке данных. Не требуется угадать единственную реальную неисправность. Полезно сказать: “The case does not provide enough information to identify a single cause, so I would investigate two possibilities.” Это демонстрирует анализ, а не незнание.

## 2. Каркас ответа на три минуты

Запомни шесть шагов: **Problem → Causes → Solutions → Safeguard → Testing → Conclusion**.

| Часть | Примерное время | Что сказать |
|---|---|---|
| Problem | 20 секунд | Что происходит, почему это важно, какой результат нужен |
| Causes | 40 секунд | Две возможные причины и механизм каждой |
| Solutions | 60 секунд | Два решения; как они действуют; подходящий пример курса |
| Safeguard | 20 секунд | Что делать, если основное решение всё же не сработало |
| Testing | 30 секунд | Условия проверки, показатели успеха и безопасный порядок тестов |
| Conclusion | 10 секунд | Приоритетная рекомендация и оговорка |

Это ориентир, а не секундомер для каждого абзаца. На тренировке лучше получить **3:10–3:30**, чтобы не закончить раньше минимума из-за волнения. Речь должна оставаться понятной; не растягивай её искусственно долгими паузами.

Если говоришь со скоростью 90–110 слов в минуту, три минуты — примерно 270–330 слов. Собственную скорость проверь записью: прочитай или расскажи 100 слов и измерь время. Английский образец ниже — около 300 слов; он может занять меньше трёх минут у человека, который говорит быстро.

## 3. Что делать в пять минут подготовки

**0:00–0:30 — прочитать ситуацию и все Discussion Points.** Подчеркни объект, сбой, условие и последствие. Для образца: car / misinterprets stop signs / heavy rain / collision risk.

**0:30–1:30 — выделить две причины.** Раздели их по уровням: датчики или материал; обработка данных или конструкция; эксплуатация или процесс. Для образца: poor visual input + insufficient model robustness. Сразу обозначь их как possibilities, если фактов недостаточно.

**1:30–2:30 — подобрать два решения.** Каждая причина должна получить своё решение. Камера загрязняется — улучшить состояние оптики; модель плохо работает на дождливых данных — улучшить данные, обработку и проверить модель. «Добавить AI» без механизма ничего не объясняет.

**2:30–3:30 — придумать safeguard и testing.** Что система делает при неопределённости? В каких условиях проверяется? Какой результат должен улучшиться? На этом этапе убедись, что закрыты все вопросы билета.

**3:30–4:30 — добавить один пример UNIT 4 и 5–8 знакомых выражений.** Например: digital twin → simulated vs real-world behaviour; accuracy; troubleshoot; enhance; prevent; ensure. Термины должны помогать объяснению. Пять уместных слов полезнее пятнадцати случайных.

**4:30–5:00 — подготовить начало и последнюю фразу.** Проверь логику и порядок. Записывай опорные слова, а не полный текст: иначе потратишь всё время на письмо.

### Как должны выглядеть заметки

```text
P: stop signs / heavy rain / unsafe decision
C1: camera image → water + visibility ↓
C2: model/data → rain examples insufficient?
S1: protect/clean optics + image processing
S2: suitable data + sensor fusion / confidence
SAFE: low confidence → slow down / safe stop if appropriate
TEST: simulation → track; rain/night/glare; missed signs + false alarms
U4: digital twins / real-world mismatch
END: layered solution + validate before use
```

Это план конкретного кейса; в другом билете меняются содержательные пункты, но порядок сохраняется.

## 4. Как строить тезисы и аргументы

**Тезис** — мысль, которую ты утверждаешь: “The system needs a backup strategy.” **Аргумент** — объяснение, почему это верно: “A single sensor can fail in poor weather.” **Пример** — конкретизация: “Water on the camera lens can hide part of a sign.” **Вывод** — связь с решением: “Therefore, the vehicle should not rely on one uncertain visual detection.”

Для каждого важного пункта используй цепочку:

**Claim → Reason → Mechanism → Example → Implication.**

По-русски: **что предлагаю → почему → как это поможет → пример → что изменится**. Не всегда нужны все пять звеньев, но причина и механизм нужны почти всегда.

### От слабого тезиса к аргументу

Слабо: “We should improve the sensors.”

Сильнее: “I would improve the reliability of the camera input because rain can reduce image quality. For example, water on the lens may hide the outline of a stop sign. Protecting and cleaning the lens could help the system receive clearer data. However, this would not solve every software problem, so I would also review the recognition model.”

Здесь есть предмет решения, причина, пример, ожидаемая польза и ограничение. Получается содержательный абзац, а не длинный список обещаний.

### Как быстро придумать свою позицию

Задай себе вопросы:

1. Что именно мешает системе выполнить функцию?
2. Можно ли убрать причину или только уменьшить последствия?
3. Какие два решения воздействуют на разные причины?
4. Какое решение я внедрял бы первым и почему?
5. За что придётся заплатить: деньги, масса, время, сложность, точность, удобство?
6. Какие данные покажут, что решение действительно работает?

Позиция может быть умеренной: “I would prioritise a reliable fallback first, then improve performance.” Не нужно спорить ради спора или давать категоричный ответ без данных.

### Универсальные направления поиска причин

| Уровень | Что спросить себя |
|---|---|
| Physical input / material | Что мешает датчику или материалу нормально работать: вода, температура, износ, нагрузка? |
| Data / software | Достаточны ли данные? Есть ли ошибка обработки? Совпадают ли условия обучения и применения? |
| Design / integration | Правильно ли согласованы части? Есть ли зависимость от единственного слабого элемента? |
| Human / operating conditions | Понимает ли пользователь сигнал? Соблюдены ли условия эксплуатации? |
| Manufacturing / maintenance | Есть ли дефект производства, загрязнение, пропущенное обслуживание? |

Выбирай только подходящие уровни. Не надо обсуждать все пять в каждом ответе.

## 5. Универсальный английский шаблон

Квадратные скобки заменяешь содержанием кейса. Это тренировочная заготовка; произносить все фразы подряд не обязательно.

> The main problem in this case is [failure]. This is important because it may lead to [consequence]. The goal should be to [desired result] while maintaining [important requirement].
>
> I can see two possible causes. First, [cause one]. This can affect [component or process] by [mechanism]. Second, [cause two]. For example, [short illustration]. We would need [evidence] to determine which cause is more important.
>
> To address the first issue, I would [solution one]. This would help [benefit] because [mechanism]. A relevant example from the course is [example]. It illustrates [principle that applies here].
>
> To address the second issue, I would [solution two]. Compared with [alternative], this approach could [advantage]. However, it may also [cost or limitation], so [condition or compromise].
>
> I would also add [safeguard]. If [failure or uncertainty], the system should [fallback]. This would reduce the risk of [consequence].
>
> Finally, I would test the updated system under [conditions]. I would measure [performance indicator] and also check [undesired side effect]. I would start with [controlled method] and then compare the results with [real-world evidence].
>
> Overall, I would prioritise [main recommendation] because [reason]. The solution should be introduced only after [validation condition].

## 6. Конструктор предложений

### Определить проблему

- “The main issue is that…” — главная проблема в том, что…
- “The system fails to…” — система не выполняет…
- “This creates a risk of…” — это создаёт риск…
- “The goal is to improve X without reducing Y.” — цель улучшить X, сохранив Y.

Пример: “The system fails to recognise a stop sign reliably in heavy rain.”

### Объяснить возможную причину

- “One possible cause is…”
- “This may be due to…”
- “When X happens, Y becomes less reliable.”
- “X can reduce the quality of Y, which makes Z more difficult.”

Пример: “Rain can reduce image quality, which makes sign recognition more difficult.”

### Предложить и объяснить решение

- “I would recommend improving…”
- “One way to address this issue is to…”
- “This would allow the system to…”
- “The purpose of this change is to…”
- “This could reduce the risk of…”

Пример: “Combining different sources of information could reduce dependence on one unreliable input.”

### Добавить пример курса

- “A relevant example from UNIT 4 is…”
- “The course material illustrates this principle through…”
- “This example shows why…”
- “The same principle could apply here because…”

Пример: “The digital-twin material shows why simulated results must be checked against real-world behaviour.”

### Обсудить компромисс

- “The main advantage is…, but the drawback is…”
- “Although this could improve X, it might increase Y.”
- “The choice depends on…”
- “I would prioritise X because…”

Пример: “Although extra sensors could improve reliability, they would also increase cost and system complexity.”

### Описать тестирование

- “I would test the system under…”
- “The tests should include both X and Y.”
- “I would compare the updated system with the original version.”
- “Success would mean fewer X without an unacceptable increase in Y.”

Пример: “Success would mean fewer missed stop signs without too many false alarms.”

### Сделать вывод

- “Overall, I would use a combination of…”
- “My first priority would be…”
- “The final decision should depend on the test results.”

Не начинай каждый пункт с “I think”. Один раз обозначь позицию, затем объясняй её.

## 7. Как увеличить объём ответа

Увеличивай число смысловых связей вокруг тезиса. Удобный алгоритм: **одна мысль → объяснение причины → работа механизма → конкретный случай → ограничение**. Получается 40–70 слов вместо 5–10.

### Способ 1 — раскрыть причину

Коротко: “Rain affects cameras.”

Развёрнуто: “Heavy rain can reduce visibility and leave water on the camera lens. As a result, the outline of a sign may be harder to recognise. This means that the system receives less reliable visual information.”

### Способ 2 — разделить проблему на два уровня

“There are two issues here: the quality of the sensor input and the way the software interprets it. Improving only one of them may leave the other problem unresolved.”

Переход от списка к отношениям между частями — естественный способ добавить содержание.

### Способ 3 — показать сценарий

“For example, the vehicle may detect a sign correctly in light rain but fail when the lens is partly covered with water. The updated system should be tested in both situations.”

Это гипотетический сценарий; слово may не выдаёт предположение за установленный факт.

### Способ 4 — добавить компромисс

“An additional sensor may provide useful information, but it also increases cost and complexity. Therefore, I would check whether it improves performance in the specific conditions described in the case.”

### Способ 5 — объяснить критерий успеха

“I would not evaluate the system only by its average accuracy. I would also check how often it misses a stop sign in heavy rain and how often it produces an unnecessary warning.”

### Способ 6 — использовать пример курса и связать его с кейсом

“In UNIT 4, the digital-twin material discussed differences between simulated and real-world behaviour. This is relevant here because a system that works in a simplified simulation may still fail in rain. Therefore, simulation should be followed by controlled physical tests.”

Само упоминание названия статьи не является аргументом. Обязательно добавь “This is relevant because…” или “This shows why…”.

### Чего избегать

- Повторения одного утверждения разными словами без нового объяснения.
- Длинного вступления про “the modern world” и “the importance of technology”.
- Ложных цифр, несуществующих исследований и выдуманных личных впечатлений.
- Формул “always”, “never”, “100% safe”, если материал их не оправдывает.
- Обещания “AI will solve the problem” без входных данных, механизма и проверки.

Если ответ слишком короткий, расширяй **solutions и testing**, затем добавляй trade-off. Эти части непосредственно отвечают задаче.

## 8. Как быстро подтянуть словарный запас

Учи **готовые сочетания**, которые можно вставить в разные кейсы. Тебе нужен небольшой активный запас, который ты можешь произнести без долгого поиска слова.

### Ядро из лексики UNIT 4

| Сочетание | Перевод | Где использовать |
|---|---|---|
| improve sensor accuracy | повысить точность датчиков | Диагностика и тесты |
| enhance system performance | улучшить работу системы | Решение |
| troubleshoot a problem | найти и устранить неисправность | Причины |
| simulate operating conditions | смоделировать условия работы | Тестирование |
| compare simulated and real-world behaviour | сравнить поведение модели и реальной системы | Проверка модели |
| maintain data integrity | сохранять целостность данных | Digital twin/data |
| monitor the system in real time | наблюдать за системой в реальном времени | Контроль |
| prevent errors from occurring | предотвращать ошибки | Назначение решения |
| enable the device to function | позволить устройству работать | Механизм |
| ensure that the system works correctly | обеспечить правильную работу системы | Цель проверки |
| withstand repeated stress | выдерживать повторяющиеся нагрузки | Материалы |
| improve wear resistance | повысить износостойкость | Материалы |
| select a suitable material | выбрать подходящий материал | Конструкция |
| reduce contamination | уменьшить загрязнение | Биопечать/производство |
| balance strength and porosity | согласовать прочность и пористость | Scaffold |
| provide haptic feedback | обеспечить тактильную обратную связь | Интерфейс/протез |
| reap the benefits of a technology | получить пользу от технологии | Вывод |
| assess the implications | оценить последствия | Анализ |

Слова в таблице связаны с UNIT 4; сочетания составлены для практики. Дополнительные полезные слова кейса: **reliability, safeguard, fallback, sensor fusion, false alarm, missed detection, confidence, validation**. Они помогают ответу, но я не утверждаю, что все входят в официальный Target Vocabulary UNIT 4.

### Что означают accuracy, precision и reliability

**Accuracy** — насколько результат соответствует действительности. **Precision** — насколько повторяемы измерения. **Reliability** — насколько стабильно система выполняет нужную функцию в заданных условиях. Датчик может стабильно давать неверное значение: высокая повторяемость не гарантирует точность.

### Тренировка на 30 минут

1. 5 минут: выбери 10 сочетаний и прочитай вслух с переводом.
2. 10 минут: для каждого скажи одно предложение по кейсу.
3. 5 минут: закрой английскую колонку и восстанови сочетания по русскому смыслу.
4. 5 минут: расскажи один абзац, используя три сочетания.
5. 5 минут: повтори только то, на чём запнулся.

Для произношения не обязательно учить транскрипцию всех слов. Отработай вслух те, которые действительно используешь: accuracy, simulate, reliability, biocompatibility, scaffold, haptic.

### Если забыл слово

- troubleshoot → “find and fix the problem”;
- wear resistance → “the ability to resist damage during repeated use”;
- scaffold → “a structure that supports growing cells”;
- sensor fusion → “combining information from different sensors”;
- biocompatibility → “how safely a material interacts with the body”.

Перефразирование лучше, чем остановка на полминуты. При этом часть активной лексики курса всё же нужно употребить: это прямое требование билета.

## 9. Несколько грамматических конструкций с большим эффектом

**Причина и следствие:** “X happens because Y.” / “X may lead to Y.” / “As a result,…”

**Рекомендация:** “I would improve…” / “The system should include…” / “One possible solution would be to…”

**Условие:** “If the input is unreliable, the system should use a fallback strategy.”

**Контраст:** “Although X could help, it would also increase Y.”

**Относительное предложение:** “A digital twin is a model that represents a real system.”

**Функция:** “This allows the user to…” / “This prevents the device from…”

**Participle clause из UNIT 4:** “Using a digital twin, engineers can test different scenarios.” Здесь using относится к engineers. Не говори “Using a digital twin, the problems become clear”, если непонятно, кто использует модель.

Для уверенного ответа достаточно хороших because, if, which и although. Причастные обороты можно добавлять после того, как основные предложения получаются без ошибок.

### Типичные ошибки

| Неудачно | Лучше |
|---|---|
| I recommend to improve the system. | I recommend improving the system. / I would recommend that the team improve the system. |
| This allows to detect signs. | This allows the system to detect signs. |
| This prevents errors to happen. | This prevents errors from happening. |
| The system depends from the weather. | The system depends on weather conditions. |
| More better sensors. | Better sensors. / More reliable sensors. |
| Although it is expensive, but it helps. | Although it is expensive, it helps. |
| We must do researches. | We need to do more research. |
| This technology is actual. | This technology is relevant. |

## 10. Полный образец ответа на кейс из билета

Это учебное предложение для обсуждения, а не готовая спецификация системы автономного вождения. Возможные причины обозначены как гипотезы. Другие датчики могут помогать оценке окружения, но нельзя автоматически считать, что любой radar или lidar умеет читать надпись STOP.

> The main problem is that the vehicle misinterprets stop signs in heavy rain. This creates a safety risk because the car may make an incorrect decision at a junction. I would investigate both the sensor input and the recognition software.
>
> First, rain can reduce visibility and leave water on the camera lens. This may hide important features of a sign. Second, the software may not have been trained or tested on enough difficult weather conditions. These are possible causes, so I would check recorded data before choosing a fix.
>
> My first solution would be to improve the quality of the visual input, for example by protecting and cleaning the camera lens. My second solution would be to improve the recognition model using suitable rainy-weather examples. I would also consider sensor fusion. Other sensors may help the vehicle understand its surroundings, although they do not automatically recognise the meaning of a stop sign.
>
> An additional safeguard should deal with uncertainty. If the system cannot make a reliable decision, it should follow an appropriate fallback strategy, such as slowing down or stopping safely when the situation allows it. Extra sensors and safeguards can increase cost and complexity, so their benefits need to be measured.
>
> For testing, I would start with simulations and then use a controlled test track. The tests should include different rain intensities, lighting conditions and partially obscured signs. I would measure missed stop signs, false alarms and the vehicle's response. The digital-twin material in UNIT 4 is relevant because it highlights differences between simulated and real-world behaviour.
>
> Overall, I would combine better input, improved software and a reliable fallback. No single change should be assumed to solve every failure. The updated system should be validated under realistic conditions before it is used on public roads.

### Почему этот ответ работает

Он закрывает все три Discussion Points. Причины отделены от установленных фактов. Для решений объяснены механизмы и ограничения. Есть пример курса с конкретной связью с кейсом. Тестирование содержит условия, показатели и последовательность. Вывод выбирает подход, а не повторяет вступление дословно.

Не обязательно повторять именно эти технические решения. Можно выбрать другие обоснованные меры и объяснить их тем же способом.

## 11. Как отвечать на дополнительные вопросы

**“Why is your solution better?”** Назови один критерий сравнения и ограничение: “It addresses the input problem directly. However, it would still need to be combined with software testing.”

**“What if it does not work?”** Вернись к safeguard и диагностике: “I would review the failure data and check whether the remaining problem comes from the input or the model.”

**“Is it expensive?”** Не выдумывай стоимость: “The case does not give cost data. I would compare the additional cost with the measured improvement in reliability.”

**“Can you give a course example?”** Достань одну карточку из отдельного файла и объясни переносимый принцип. Не пересказывай весь юнит.

**“What would you do first?”** Выбери порядок: “First, I would analyse the recorded failures. That would help us choose a targeted fix rather than replace components without evidence.”

Если вопрос неясен: “Could you clarify whether you mean the sensor design or the software?” Если нужно время: “Let me consider the main trade-off.” Эти фразы помогают собраться, но не должны заменять содержательный ответ.

## 12. Подробный план тренировки на три часа

План даёт 160 минут работы и 20 минут перерывов. Он посвящён форме ответа; содержание юнита нужно учить по отдельному конспекту.

| Минуты от начала | Действие | Результат |
|---|---|---|
| 0–15 | Прочитать требования, каркас и пятиминутную подготовку | Можешь назвать шесть частей без подсказки |
| 15–35 | Выучить 10 сочетаний из раздела 8 | По одному собственному предложению на каждое |
| 35–60 | Взять 3 тезиса и развернуть через причину, механизм, пример и ограничение | Три абзаца по 40–70 слов |
| 60–70 | Перерыв | |
| 70–90 | Разобрать образец про автомобиль; пометить функции предложений | Видишь, зачем нужно каждое предложение |
| 90–115 | 5 минут подготовиться по билету, записать ответ на 3+ минуты, прослушать и исправить | Первая самостоятельная запись |
| 115–125 | Перерыв | |
| 125–150 | Новый тренировочный кейс: неточные данные цифрового двойника | Переносишь структуру на другую тему |
| 150–170 | Ещё один кейс: прочный, но проблемный биоматериал | Используешь причину, компромисс и пример UNIT 4 |
| 170–180 | Повторить начало, вывод и 5 полезных слов; проверить ошибки | Короткая памятка перед экзаменом |

Тренировочные кейсы здесь придуманы для подготовки и не являются найденными официальными билетами.

### Что исправлять после записи

Сначала проверь содержание: все ли вопросы закрыты, есть ли две разные причины и объяснённые решения. Затем структуру: понятен ли порядок. После этого длительность и связность. Только потом исправляй повторяющиеся языковые ошибки. Не пытайся сразу переписать всё в сложный «идеальный» английский.

Если можешь выделить время на следующий день: 10 минут воспроизвести сочетания, затем один ответ с 5 минутами подготовки и 3 минутами речи. Повторение без конспекта важнее ещё одного пассивного чтения.

## 13. Если до комиссии остался только час

10 минут — каркас и шаблон; 10 минут — восемь сочетаний; 10 минут — три примера из отдельного файла; 15 минут — ответ по образцу билета с записью; 10 минут — ответ по другому кейсу; 5 минут — проверить ошибки allow/enable/prevent и повторить вывод.

Приоритет: **связность и конкретика → лексика курса → правильные простые предложения → разнообразие грамматики**.

## 14. Короткая самопроверка

- Назвал ли я проблему и её последствие?
- Не выдаю ли гипотезу о причине за факт?
- Есть ли минимум две содержательные причины или направления анализа?
- Каждое решение связано с причиной?
- Объяснил ли я, как решение работает?
- Есть ли safeguard и один trade-off?
- Тесты проверяют именно заявленную проблему и нежелательные последствия?
- Есть ли один конкретный пример курса с объяснением связи?
- Использовал ли я знакомую Target Vocabulary?
- Длится ли ответ хотя бы три минуты?

## 15. Памятка из шести строк

**The problem is… and this matters because…**

**Two possible causes are… and…**

**I would address them by… because…**

**If the system still fails, it should…**

**I would test… and measure…**

**Overall, I would prioritise… because…**

Источник требований: присланный файл «ПримерБилета_ДифЗачет .docx». Примеры UNIT 4 основаны на ранее прочитанных материалах LMS и предоставленных расшифровках и словарях. Отдельный банк аргументов: **UNIT_4_examples_for_case_answers.md**.
