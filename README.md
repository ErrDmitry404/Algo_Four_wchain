Код задачi: WCHAIN (Ланцюжок зi слiв)

Двоє учасникiв грають у лiнгвiстичну гру. На початку гри дано список iз N слiв. Перший гравець обирає довiльне слово w1 i викреслює з нього одну довiльну лiтеру так, щоб отримати iнше слово w2 з цього списку. Пiсля цього хiд переходить до iншого гравця, i вiн намагається зробити те саме зi словом w2.

Гра завершується в одному з двох випадкiв:

• Залишається слово з однiєї лiтери.

• Неможливо викреслити жодну лiтеру так, щоб отримати iнше слово зi словника.

Визначте довжину максимального ланцюжка, якого можна досягти в цiй грi при заданих словах.

Вхiднi данi Вхiдний файл wchain .in складається з N + 1 рядкiв.

• Перший рядок мiстить N — кiлькiсть слiв у словнику, 1 ≤ N ≤ 105

• Кожен з наступних N рядкiв мiстить слово довжиною вiд 1 до 50 символiв, яке складається з малих латинських лiтер вiд a до z.

Вихiднi данi Вихiдний файл wchain .out повинен мiстити одне число — довжина максимального ланцюжка.

Приклад 1 wchain .in 10 crates car cats crate rate at ate tea rat a wchain .out 6 Пояснення: Можливий ланцюжок: crates > crate > rate > ate > at > a.

Приклад 2 wchain .in 5 b bcad bca bad bd wchain .out 4 Пояснення: Можливий ланцюжок: bcad > bad > bd > b.

Приклад 3 wchain .in 3 word anotherword yetanotherword wchain .out 1 Пояснення: Оскiльки можна стирати лише одну лiтеру за хiд, маємо три можливих ланцюжки, кожен довжиною в 1 слово.

To run application:

Download project, go to target directory and run from main

To run tests:

Go to target directory and run

Additional indo: there are also two files included wchain.in.txt wchain.out.txt

They needed to work properly with buffered reader, "out" will give you the result of this task
