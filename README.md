# Learning Python for beginner
Python - це багатоцільова мова програмування. Можна використувати її, для безліч різних завдань, які ви можете використовувати python для машинного навчання та штучного інтелекту.
# Змінні Python
## Змінні - Variables
Змінні є контейнерами для зберігання значень даних.
## Створення змінних -  Creating Variables
Python не має команди для оголошення змінної.Змінна створюється в той момент, коли ви вперше присвоюєте їй значення.
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/bcc9fbe1-6fa0-4311-bca3-6606b47ff12f)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/cb45aae8-e441-4b70-b5e6-395c4ba5eeba)
Змінні не потрібно оголошувати з певним типом , і вони навіть можуть змінювати тип після того, як їх було встановлено.
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/c7a81934-7e3d-4e51-a690-5ed35fc8854a)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/4176f9c0-ea18-4aab-adaf-5b5348ed9d33)
## Кастинг - Casting
Якщо ви хочете вказати тип даних змінної, це можна зробити за допомогою приведення.
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/a3e39b7c-6c8b-428c-8ce2-6e40af99e04a)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/904d0523-6037-4713-a630-bb3d1f0b6513)
## Отримайте тип - Get the Type
Ви можете отримати тип даних змінної за допомогою type() функції.
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/c05cf347-03f7-4894-b0fc-18472000bacb)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/9011012d-7c79-42c4-8b73-b300a45aefbb)
Ви дізнаєтеся більше про типи даних(https://www.w3schools.com/python/python_datatypes.asp) і приведення(https://www.w3schools.com/python/python_casting.asp) пізніше в цьому посіьнику.
## Одинарні чи подвійні лапки - Single or Double Quotes
Рядкові змінні можна оголошувати за допомогою одинарних або подвійних лапок:
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/e9037fae-937c-43d5-99d2-f501c91cce07)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/74a4eb8f-1236-4194-86e0-847cce90fcdb)
З урахуванням регістру - Case-Sensitive
Імена змінних чутливі до регістру.
### Приклад
це створить дві змінні:
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/abb0dbed-489f-463f-ae6f-eb32375c734c)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/34acfbc9-f967-400e-8d68-f4681bfa72e0)
# Python - імена змінних - Variable Names
## Імена змінних - Variable Names
Змінна може мати коротку назву (наприклад, x і y) або більш описову назву (age, carname, total_volume). Правила для змінних Python:
* Ім'я змінної має починатися з літери або символу підкреслення
* Ім'я змінної не може починатися з числа
* Ім’я змінної може містити лише буквено-цифрові символи та підкреслення (Az, 0–9 та _)
* Назви змінних чутливі до регістру (age, Age і AGE три різні змінні)
* Ім'я змінної не може бути жодним із ключових слів Python(https://www.w3schools.com/python/python_ref_keywords.asp).
### Приклад
Правові назви змінних:
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/98037331-c70b-447a-9e51-2711d4178c29)
### Приклад 
Неприпустимі імена змінних:
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/67129ae6-08c3-4264-8b20-6b944848ad3a)
Пам'ятайте, що імена змінних чутливі до регістру.
## Багатослівні імена змінних - Multi Words Variable Names
Назви змінних, які містять більше одного слова, можуть бути складними для читання. Щоб зробити їх більш читабельними, можна скористатися кількома прийомами:
* Верблюдачий регістр - Camel Case
  Кожне слово, крім першого, починається з великої літери:
  ![image](https://github.com/ksnvtg/demo-repo/assets/130612714/6b6ec73d-e692-4901-80b5-f29ee49c70f9)
* Паскальовий регістр - Pascal Case
  Кожне слово починається з великої літери:
  ![image](https://github.com/ksnvtg/demo-repo/assets/130612714/4ba5d89f-2b39-4a46-82c6-472b6524a54f)
* Зміїний регістр - Snake Case
  Кожне слово відокремлюється символом підкреслення:
  ![image](https://github.com/ksnvtg/demo-repo/assets/130612714/3294b99c-c22c-43de-b452-ab96a8eb184e)
# Призначення кількох значень - Assign Multiple Values
## Багато значень для кількох змінних - Many Values to Multiple Variables
Python дозволяє призначати значення декільком змінним в одному рядку:
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/197c3541-208d-48c1-a3fb-6961846cce3a)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/77d70601-876a-44f9-9deb-7945ae2bee3f)
!Примітка. Переконайтеся, що кількість змінних відповідає кількості значень, інакше ви отримаєте помилку.
## Одне значення для кількох змінних - One Value to Multiple Variables
І ви можете призначити те саме значення кільком змінним в одному рядку:
### Приклад 
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/681f5dc0-6abf-4d42-9282-541b39fd1400)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/437e8cfe-7a15-4038-8934-5567f0833848)
## Розпакуйте колекцію - Unpack a collection
Якщо у вас колекція значень у списку, кортежі тощо, Python дозволяє видобувати значення у змінні. Це називається розпакуванням.
### Приклад
Розпакуйте список:
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/75a415ea-086c-4a70-a197-d035338a90da)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/2eec7c9a-d31e-43cf-8003-f1e8845c3f2c)
Дізнайтеся більше про розпакування в нашому розділі "Розпакування кортежів" https://www.w3schools.com/python/python_tuples_unpack.asp. 
# Вихідні змінні - Output Variables
Функція Python print() часто використовується для виведення змінних.
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/83da4f6a-aa98-4c98-bd8f-f2f293efff5c)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/d6b2b8b3-94c0-4856-8a0f-ebf99b7ed31d)
У print() функції виводиться кілька змінних, розділених комою:
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/ee8cbcde-fa4e-4ace-9ca6-b4e9ce5c3a7c)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/b72f429c-e414-437d-8981-ac09d21aa0e1)
Ви також можете використовувати + оператор для виведення кількох змінних:
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/1c97f2bb-f87b-4803-853f-75a3794f91be)
Зверніть увагу на пробіль після "Python " та "is ", без них результат був би "Pythonisawesome".
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/284e30af-a096-42d0-8c77-c6b76819a1d0)
Для чисел + символ працює як математичний оператор:
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/a3f9be05-fe57-45c3-9461-bf5e8b2e921b)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/45e91f57-360c-4c6f-b54c-4e15cc159623)
У print() функції, коли ви намагаєтеся поєднати рядок і число з + оператором, Python видасть вам помилку:
### Приклад 
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/f03751a7-528c-4762-b69d-6d14506e4206)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/d1f19b98-d79b-4bc2-a7b3-9f58fdf14c71)
Найкращий спосіб виводити кілька змінних у print() функції - розділяти їх комами, що навіть підтримує різні типи даних:
### Приклад
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/8adf3534-7cd4-4e2f-b5aa-bb19c2485c87)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/a82c023d-86a0-4aaf-b0ca-8e1985fb9d97)
# Глобальні змінні - Global Variables
Глобальні змінні - це змінні, створені поза функцією (як у всіх прикладах на попередніх сторінках), відомі як глобальні змінні.
Глобальні змінні можуть використовуватися всіма як усередині функцій, так і поза ними.
### Приклад
Створіть змінну поза функцією та використовуйте її всередині функції
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/ef3d80a2-b1e2-4ab1-872b-d948fc21f9f6)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/875a1668-4d96-4005-bafd-e06dea50507d)
Якщо ви створюєте змінну з таким же ім'ям у функції, ця змінна буде локальною та може використовуватися лише всередині функції. Глобальна змінна з такою ж назвою залишиться такою, якою була, глоальною та з початковим значенням.
### Приклад
Створіть змінну всередині функції з тим самим іменем, що й глобальна змінна
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/02309581-6b87-421a-9642-120e37428823)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/03326cb1-752e-452c-abc1-a1bf887d06f4)
## Глобальне ключове слово - The global Keyword
Зазвичай, коли ви створюєте змінну всередині функції, ця змінна є локальною та може використовуватися лише всередині цієї функції.
Щоб створити глобальну змінну всередині функції, ви можете використати global ключове слово.
### Приклад 
Якщо використовуєте global ключове слово, змінна належить до глобальної області:
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/64072a20-2500-4de5-8ec1-5e6ec86c68fa)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/d9baccb0-56e7-4b81-9fcd-900256f3150e)
Крім того, використовуйте global ключове слово, якщо ви хочете змінити глобальну змінну всередині функції.
### Приклад
Щоб змінити значення глобальної змінної всередині функції, зверніться до змінної за допомогою global ключового слова:
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/c4e9f629-c678-4b39-b7e3-1ac63898b60b)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/521501a8-6aac-45bd-9c73-c9c34721c99f)
# Типи даних - Python Data Types
## Вбудовані типи даних - Built-in Data Types
У програмуванні тип даних є важливим поняттям. Змінні можуть зберігати дані різних типів, і різні типи можуть виконувати різні дії. За замовчуванням Python має вбудовані такі типи даних у цих категоріях:
- Тип тексту: str
- Числові типи: int, float, complex
- Типи послідовностей: list, tuple, range
- Тип відображення: dict
- Типи наборів: set, frozenset
- Логічний тип: bool
- Двійкові типи: bytes, bytearray, memoryview
- Немає Тип: NoneType
## Отримання типу даних - Getting the Data Type
Ви можете отримати тип даних будь-якого об'єкта за допомогою функції type():
## Приклад
Вивести тип даних змінної x:
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/ae2734ee-5e14-4556-9a92-e46b69a0ecfd)
![image](https://github.com/ksnvtg/demo-repo/assets/130612714/641ca2ef-9fae-412e-be5b-ef12f1bfb3e9)
## Встановлення тип даних - Setting the Data Type
У Python тип даних встановлюється, коли ви присвоюєте значення змінній:
* x =  "Hello World" -> str
* x = 20             -> int
* x = 20.5           -> float
* x = 1j             -> complex
* x = ["apple", "banana", "cherry"] -> list
* x = ("apple", "banana", "cherry") -> tuple
* x = range(6)       -> range
* x = {"name" : "John", "age" : 36} -> dict
* x = {"apple", "banana", "cherry"} -> set
* x = frozenset({"apple", "banana", "cherry"}) -> frozenset
* x = True           -> bool
* x = b"Hello"       -> bytes
* x = bytearray(5)   -> bytearray
* x = memoryview(bytes(5))  -> memoryview
* x = None           -> NoneType
## Встановлення конкретного типу даних - Settein the specific data type
Якщо ви хочете вказати тип даних, ви можете використовувати наступні функції конструктора:
