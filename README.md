# Урок 11. Flex-box. Вирівнювання та розташування flex-елементів.

1. Що таке flexbox (батьківський контейнер, дочірній блок)
2. Вісі flex-box
   - Головна вісь flex-контейнера (main-axis)
   - Поперечна вісь flex-контейнера (cross axis)
3. Основні переваги flex-box
4. Властивості батьківського контейнера:

   display: flex | line-flex;

   flex-direction: row | row-reverse | column | column-reverse; flex-wrap;

   justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;

   align-items: stretch | flex-start | flex-end | center | baseline;

   align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch;

   flex-wrap: nowrap | wrap | wrap-reverse;

<!--! ============= Flexbox ====================== -->

CSS flexbox (Flexible Box Layout Module) - модуль макету гнучкого контейнера - являє собою спосіб компонування елементів. Flex-box складається з flex-контейнера (flex-container) - батьківського контейнера та гнучких елементів (flex items) - дочірніх блоків.

<!--! ======== Вісі flex-box ====================== -->

Головна вісь flex-контейнера (main-axis) - це напрямок, в якому розташовуються його дочірні елементи. У головної осі є початок та кінець (вони позначені на схемі).
Поперечна вісь flex-контейнера (cross axis) - це напрям, перпендикулярний головній осі. У неї теж є початок та кінець.
Напрям головної осі починається зліва направо, а поперечної - зверху вниз.

<!--! ======== Основні переваги flex-box ====================== -->

Основні переваги flex-box:

- блоки легко стають гнучкими, елементи можуть стискатися та розтягуватись, заповнюючи простір;
- неважливо, в якому порядку розташовані HTML-елементи. Ми можемо змінити їх порядок через CSS;
- розташовувати елементи в одному з чотирьох напрямків: зліва направо, з права наліво, зверху вниз, знизу вгору;
- перевизначити порядок відображення елементів;
- автоматично визначати розміри елементів таким чином, щоб вони вписувались в доступний простір;
- вирішувати проблему з горизонтальним та вертикальним центруванням;
- створювати колонки однакової висоти;
- створювати "притиснутий" до низу сторінки футер.

<!--! ======== Властивості батьківського контейнера ====================== -->

display: flex | line-flex;

flex-direction: row | row-reverse | column | column-reverse; flex-wrap;

justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;

align-items: stretch | flex-start | flex-end | center | baseline;

align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch;

flex-wrap: nowrap | wrap | wrap-reverse;
