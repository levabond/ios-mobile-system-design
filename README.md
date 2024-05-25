## Для чего этот форк?
Хочется обогатить его в контексте iOS разработчика с упором дополнений из
- https://www.mobilesystemdesign.com/
- https://www.mobileatscale.com/
- Множество других инструментов и книг из соседних платформ (бэк, фронт, андроид)
- Сбор мнений и валидация через комьюнити экспертов https://t.me/iosmakesmehate

## Простой мобильный фреймворк для System Design
Ниже представлена ​​простая схема собеседований по проектированию мобильных систем. В качестве примера мы собираемся использовать вопрос «Дизайн ленты Twitter». Предлагаемое решение далеко от совершенства, но оно не является целью собеседования по проектированию системы: никто не ожидает, что вы создадите надежную систему всего за 30 минут - интервьюер в основном ищет конкретные «сигналы» из вашего мыслительного процесса и коммуникация. Все, что вы говорите или делаете, должно демонстрировать ваши сильные стороны и помогать интервьюеру оценить вас как кандидата.

## Disclaimer
Изучение фреймворка не гарантирует прохождение собеседования. Структура процесса собеседования зависит от личного стиля интервьюера. Диалог действительно важен — убедитесь, что вы понимаете, что ищет интервьюер. Не делайте предположений и задавайте уточняющие вопросы.

## Цель интервью
Проверяем что кандидат умеет и понимает, как строить архитектуру клиент-сервер или проектировать клиентское приложение.
Важно, что мы хотим проверить как кандидат двигается по процессу. Нет задачи оценивать финальное решение, потому что за час невозможно спроектировать идеальную систему.
Главное, как он принимает решение, какие вопросы задает, какие компромиссы находит.

## Процесс собеседования
- 2–5 мин - знакомства
- 5 мин - постановка задачи и сбор требований
- 10 мин - обсуждение на высоком уровне
- 20-30 мин - подробное обсуждение
- 5 мин - вопросы интервьюеру


## Как проводить интервью?
Проверяем умения:
- Собирать и уточнять требования и ограничения
- Строить разумные предположения в условиях неопределённости
- Предлагать варианты решений и компромиссы
- Проектировать решение задачи и визуализировать его
- Объяснять решение другому человеку так, чтобы он понял

## Как начать интервью
Сегодня у нас с тобой секция проектирования. Мы попробуем спроектировать %экран / библиотеку / кусок функциональности%. Сразу оговорюсь, что в этой секции нет единственно правильного ответа, ход твоих мыслей так же важен, как итоговый результат. Нужно задавать вопросы, говорить про плюсы и минусы решений, озвучивать почему ты принял те или иные решения.

## Подготовка к проведению интервью
До проведения интервью HR должен рассказать, как будет проходить секция и сообщить следующую информацию:
Понадобится использовать онлайн-доску и шарить экран. Рекомендуемые инструменты: доска для рисования Miro, Whimsical или Draw.io или другой подходящий инструмент. Желательно зарегистрироваться заранее (если это необходимо) и немного освоиться с инструментом до собеседования.

Интервью проходит в формате беседы, где интервьюер - заказчик. Он даёт задание и отвечает на вопросы кандидата, предоставляя информацию о требованиях, условиях и ограничениях.
Мы ожидаем увидеть архитектурную схему решения. Начинаем с простого варианта, если останется время, то поговорим про расширение и усложнение требований и адаптацию решения под них.
Можно использовать в качестве нотации диаграмму классов UML но в целом схему можно нарисовать в свободном формате, это не влияет на итоговый результат. Можно даже накидывать интерфейсы и комментарии в IDE или текстовом редакторе, если кандидату так проще и в итоге получится понятно для интервьюера.


## Инструменты
Онлайн whiteboard: [Draw.io](https://draw.io/), [Miro](https://miro.com/), Whimsical или Excalidraw



## Additional Information
More System Design exericses [here](/exercises)!

### Junior, Middle, Senior, and Staff level interviews
The system design experience would be different depending on the candidate's target level. An approximate engineering level breakdown can be found [here](https://candor.co/articles/tech-careers/google-promotions-the-real-scoop-on-leveling-up).  

_NOTE: There's no clear mapping between years of experience and seniority - some ranges might exist but it largely depends on the candidate's background._

#### Junior engineers
The system design round of junior engineers is optional since it's pretty unlikely they would have experience designing software systems.

#### Middle level engineers
The middle-level engineering design round might be heavy on the implementation side. The interviewer and the candidate would mostly talk about building a specific component using platform libraries.

#### Senior level engineers
The senior-level engineering design round could be more high-level compared to the previous levels. The interviewer and the candidate would mostly talk about multiple components and how they communicate with each other. The implementation details could be less important unless the candidate needs to make a decision that drastically affects the application performance. The candidate should also be able to select a technical stack and describe its advantages and trade-offs.

#### Staff level engineers
The staff-level engineering design round moves away from technical to strategic decisions. The candidate might want to discuss the target audience, available computational and human resources, expected traffic, and deadlines. Instead of thinking in terms of implementation tasks - the candidate should put business needs first. For example, being able to explain how to reduce product time-to-market; how to safely rollout and support features; how to handle OMG situations and large-scale outages. The user privacy topics and their legal implications become extremely important and should be discussed in great detail.

## Looking for more content?
### System Design Exercises
Check out the [collection](/exercises) of mobile system design exercises.
### Common System Design Interview Mistakes
Check the guide [here](/common-interview-mistakes.md).
### Mock Interviews
Check out the mock interview [archive](https://www.youtube.com/playlist?list=PLaMN-JyH50OYAfxJEpiQTYTD-gxTf7x9d) or [sign-up](https://forms.gle/Cez2R31wqtgp3RsX9) to be a candidate yourself!

## Consider "starring" the repository to help other people discover the guide! Thank you!
