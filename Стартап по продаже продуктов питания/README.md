# Стартап по продаже продуктов питания
## Цель исследования:
- изучить поведение пользователей мобильного приложения (на каких этапах пользователи "застревают");
- протестировать изменения, связанные со сменой шрифта в рекомендательной системе.
## Задачи:
- изучить воронку продаж;
- исследовать результаты А/А/В-эксперимента по смене шрифта в приложении. Для этого пользователей разделить на 3 группы: 2 контрольные и одну экпериментальную.
### Описание данных:

Каждая запись в логе — это действие пользователя, или событие.

- `EventName` — название события;
- `DeviceIDHash` — уникальный идентификатор пользователя;
- `EventTimestamp` — время события;
- `ExpId` — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.
## Библиотеки, используемые в проекте:
- pandas,
- matplotlib,
- plotly,
- math,
- scipy.