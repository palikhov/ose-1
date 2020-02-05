# Монстры

Монстры описываются набором параметров. 

::: details Пример монстра
### Берсерк

Бойцы, сражающиеся с особой яростью. Они никогда не сдаются в плен и не просят пощады.

**КБ** 7 [12], **КЗ** 1+1* (5 ПЗ), **Атаки** 1 × оружие (1d8 или значение оружия), **АПОКБ0** 18 [+1], **СД** 120’ (40’), **Исп** C12 Ж13 П14 Д15 З16 (1), **БД** 12, **Мир** Н, **ПО** 19, **Кол-во** 1d6 (3d10), **ТС** P (B)

- **Боевая ярость:** +2 к атаке по людям и другим гуманоидам. В пылу ярости могут атаковать своих союзников.
- **Клад:** Имеют тип сокровищ B только при столкновении в дикой местности.
:::

### Класс брони (КБ)

Способность монстра избегать получения урона в бою.

**Восходящий класс брони:** В квадратных скобках указывается ВКБ, если используется [опциональный вариант восходящего класса брони](/characters/game-statistics.md#класс-брони-кб).

### Кость здоровья (КЗ)

Число костей d8, используемых для определения максимальных пунктов здоровья (ПЗ). 

**Звёздочки:** Одна или несколько звёздочек после КЗ показывает число особых способностей монстра, учитываемых при [подсчёте пунктов опыта (ПО)](temp).

**Модификаторы:** Модификатор КЗ (например +3 или -1) применяется к максимальным пунктам здоровья после броска костей d8.

**Дробная кость здоровья:** Некоторые монстры имеют меньше 1 КЗ, например в случае ½ нужно бросить 1d4 для определения ПЗ.

**Средние пункты здоровья:** Средние показатели ПЗ указываются в скобках.

### Атаки за раунд (Атаки)

Атаки монстра, которые он может использовать каждый раунд с указанием урона в скобках. Атаки монстров и их урон не зависят от СИЛ и ЛВК, если только не сказано другого.

**Альтернативные атаки:** В квадратных скобках иногда указаны альтернативные атаки, которые может провести монстр.

### Испытания (Исп)

Показатели испытаний монстра:

- **С:** Смертью или ядом.
- **Ж:** Жезлом или устройством.
- **П:** Параличом или окаменением.
- **Д:** Дыханием.
- **З:** Заклинанием, скипетром или посохом.

**Испытание как КЗ:** КЗ при котором монстр проходит испытание указана в скобках (ОЧ обозначает обычного человека). Это значение не всегда равно КЗ монстра — неразумные монстры обычно проходят испытания при половине своей КЗ, тогда как магические монстры могут проходить испытания выше своей КЗ.

Некоторые монстры проходят испытания как класс персонажа. В этом случае в скобках будет указано сокращение класса и уровень: В=Воин, Д=Дворф, Ж=Жрец, М=Маг, П=Плут, п=Полурослик, Э=Эльф.

#### Испытания в зависимости от КЗ монстра

|  КЗ   |   С   |   Ж   |   П   |   Д   |   З   |
| :---: | :---: | :---: | :---: | :---: | :---: |
|  ОЧ   |  14   |  15   |  16   |  17   |  18   |
|  1-3  |  12   |  13   |  14   |  15   |  16   |
|  4-6  |  10   |  11   |  12   |  13   |  14   |
|  7-9  |   8   |   9   |  10   |  10   |  12   |
| 10-12 |   6   |   7   |   8   |   8   |  10   |
| 13-15 |   4   |   5   |   6   |   5   |   8   |
| 16-18 |   2   |   3   |   4   |   3   |   6   |
| 19-21 |   2   |   2   |   2   |   2   |   4   |
|  22+  |   2   |   2   |   2   |   2   |   2   |

### «Атака для попадания по КБ 0» (АПОКБ0)

Способность монстра попадать по противнику [в сражении](/adventuring/combat.md) определяется его костью здоровья (КЗ).

**Бонус атаки:** Бонус атаки монстра указан в скобках после АПОКБ0, если используется опциональный вариант [восходящего класса брони](/characters/game-statistics.md#класс-брони-кб).

#### Матрица атаки в зависимости от КЗ монстра или АПОКБ0

|    КЗ     | АПОКБ0  |  -3   |  -2   |  -1   |   0    |   1   |   2   |   3   |   4   |   5   |   6   |   7   |   8   |   9   |
| :-------: | :-----: | :---: | :---: | :---: | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|    ОЧ     | 20 [-1] |  20   |  20   |  20   | **20** |  19   |  18   |  17   |  16   |  15   |  14   |  13   |  12   |  11   |
|   До 1    | 19 [0]  |  20   |  20   |  20   | **19** |  18   |  17   |  16   |  15   |  14   |  13   |  12   |  11   |  10   |
|  1+ до 2  | 18 [+1] |  20   |  20   |  19   | **18** |  17   |  16   |  15   |  14   |  13   |  12   |  11   |  10   |   9   |
|  2+ до 3  | 17 [+2] |  20   |  19   |  18   | **17** |  16   |  15   |  14   |  13   |  12   |  11   |  10   |   9   |   8   |
|  3+ до 4  | 16 [+3] |  19   |  18   |  17   | **16** |  15   |  14   |  13   |  12   |  11   |  10   |   9   |   8   |   7   |
|  4+ до 5  | 15 [+4] |  18   |  17   |  16   | **15** |  14   |  13   |  12   |  11   |  10   |   9   |   8   |   7   |   6   |
|  5+ до 6  | 14 [+5] |  17   |  16   |  15   | **14** |  13   |  12   |  11   |  10   |   9   |   8   |   7   |   6   |   5   |
|  6+ до 7  | 13 [+6] |  16   |  15   |  14   | **13** |  12   |  11   |  10   |   9   |   8   |   7   |   6   |   5   |   4   |
|  7+ до 9  | 12 [+7] |  15   |  14   |  13   | **12** |  11   |  10   |   9   |   8   |   7   |   6   |   5   |   4   |   3   |
| 9+ до 11  | 11 [+8] |  14   |  13   |  12   | **11** |  10   |   9   |   8   |   7   |   6   |   5   |   4   |   3   |   2   |
| 11+ до 13 | 10 [+9] |  13   |  12   |  11   | **10** |   9   |   8   |   7   |   6   |   5   |   4   |   3   |   2   |   2   |
| 13+ до 15 | 9 [+10] |  12   |  11   |  10   | **9**  |   8   |   7   |   6   |   5   |   4   |   3   |   2   |   2   |   2   |
| 15+ до 17 | 8 [+11] |  11   |  10   |   9   | **8**  |   7   |   6   |   5   |   4   |   3   |   2   |   2   |   2   |   2   |
| 17+ до 19 | 7 [+12] |  10   |   9   |   8   | **7**  |   6   |   5   |   4   |   3   |   2   |   2   |   2   |   2   |   2   |
| 19+ до 21 | 6 [+13] |   9   |   8   |   7   | **6**  |   5   |   4   |   3   |   2   |   2   |   2   |   2   |   2   |   2   |
|    21+    | 5 [+14] |   8   |   7   |   6   | **5**  |   4   |   3   |   2   |   2   |   2   |   2   |   2   |   2   |   2   |

### Скорость движения (СД)

Скорость с которой передвигается монстр. У каждого монстра есть ***базовая скорость движения*** и ***скорость движения в бою*** (треть от базовой скорости движения, указана в скобках).

**Способы передвижения:** Если монстр имеет несколько разных способов передвижения (ходьба, полёт, плавание и т.п.), то они указываются раздельно через наклонную черту.

### Боевой дух (БД)

[Боевой дух](/adventuring/morale.md) отражает способность монстра продолжать сражение, не сбегая и не сдаваясь.

### Мировоззрение (Мир)

Предрасположенность монстра к Порядку (П), Нейтралитету (Н) или Хаосу (Х). Если указано Любое (Л), то рефери определяет мировоззрение броском кости или назначает сам.

### Пункты опыта (ПО)

Награда в пунктах опыта за победу над монстром.

### Количество (Кол-во)

Количество монстров в группе указывается двумя числами, второе из которых в скобках.

**Нули:** Если первое число равно нулю, то монстры этого вида обычно не встречаются в подземельях. Если второе число равно нулю, то монстры этого вида обычно не встречаются в дикой местности и не имеют логова.

**Использование:** Используйте значение количества в ситуациях, когда происходят столкновения с монстрами:

- **Блуждающие монстры в подземелье:** Первое число показывает количество монстров, бродящих на уровне подземелья, равном КЗ монстра. Если монстр был встречен на уровне подземелья выше, чем его КЗ, то количество монстров в группе может быть увеличено. И наоборот, если уровень подземелья ниже КЗ монстра – группа монстров будет меньше.
- **Логово монстра в подземелье:** Второе число показывает количество монстров в логове в подземелье.
- **Блуждающие монстры в дикой местности:** Второе число показывает количество монстров, бродящих по дикой местности.
- **Логово монстра в дикой местности:** Второе число умноженное на 5 показывает количество монстров в логове в дикой местности.

### Тип сокровищ (ТС)

Количество и типа сокровищ во владении монстра определяются буквенный кодом латинского алфавита (см. [Типы сокровищ](/docs/treasures/treasure-types.md)). Указанный код используются следующим образом:

- **От A до O:** Обозначает клад: совокупность сокровищ крупного монстра или группы малых монстров. Клад, как правило, запрятан в логове. Для монстров, обитающих в логове в количестве больше 1d4, объём сокровищ в кладе может быть уменьшен, если группа монстров меньше среднего количества.
- **От P до V:** Если указано для разумного монстра, то обозначает сокровища, переносимые одним существом (от P до T) или группой (U, V). Если указано для неразумного монстра, то обозначает сокровища на телах жертв этого монстра.

## Общие примечания
