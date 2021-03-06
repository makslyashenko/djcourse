# Табличні дані і графіки

Графіки є одним із головних компонент візуалізації. Сьогодні ми навчимося робити декілька простих типів графіків 
за допомогою онлайн інструменту під назвою [ChartBuilder](https://quartz.github.io/Chartbuilder/)

Однак перед тим як почати, поговоримо про дані, без яких графіки неможливі. Будь ласка, запам"ятайте наступну пораду: завжди
зберігайте ваші дані у файлі, для того щоб у майбутньому можна було до них повернутися, доповнити або
виправити, і швидко перебудувати графік. Якщо ви втратите початкові дані, вам прийдеться кожного разу будувати графік з нуля

Моя рекомендація - використовуйте для зберігання даних електронні таблиці з вашого офісного пакету, або GoogleSheets - щоб дані були доступними онлайн, і зберігайте їх у форматі CSV - простий формат, в якому у кожній строці значення різних змінних відокремлені комами. Для просунутих користувачів я пропоную подивитися на [CSVKit](https://csvkit.readthedocs.io/en/0.9.1/)
У чому переваги саме CSV? ...

Отже ви знайшли дані, записали їх у електронну табличку. Записуйте дані наступним чином - по горизонталі, в рядках 
ми записуємо повний набір значень для всіх змінних що є в наших даних (наприклад, назва, кількість населення, ВВП на душу, інфляція за останній рік, тощо для якоїсь конкретної країни ). По вертикалі в колонках, йдуть значення кожної конкретної змінної із наших даних, наприклад інфляція для всіх країн. (((іллюстрація)))

Однак перед тим, як безпосередньо будувати графік, потрібно впевнитися, що дані 
мають коректну форму. Проста перевірка:
* Кожна колонка повинна містити значення лише одної змінної з ваших даних.
* кількість колонок повинна бути фіксована і однакова для всього файлу (колонки/змінні не з"являються і не щезають), комірки не можна роздвоювати) 
* В кожній колонці тип даних має бути однаковим (якщо числа - то всі числа, якщо текст - то весь час текст)
* формат для чисел повинен підходити під інструмент для побудови графіків - наприклад, для ChartBuilder потрібно використовувати точку у якості роздільного знака між цілою та дробною частиною, а не кому


## ChartBuilder 
Нагадати для чого підходять різні типи графіків під час показу інтерфейсу

