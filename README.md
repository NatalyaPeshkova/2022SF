# Проект: "Сайт компании"

## Описание проекта и его функциональность:

Работа выполнена в рамках учебного курса Frontend-разработчик. 

Данный сайт является корпоративным сайтом компании "Repair Design Project". 
Сайт создан для продвижения услуг компании.
На данном ресурсе можно найти информацию об услугах компании, выполненных проектах, ознакомиться с отзывами клиентов.
Кроме того, на сайте можно оставить заявку или задать вопрос в формах обратной связи. 
Также можно увидеть карту проезда. 

В работе сoздана файловая структура по **БЭМ**

### Технологии
При создании данной работы были использованы следующие средства проверки и улучшения кода:
*ul  https://validator.w3.org/nu/
*ul  https://nglazov.github.io/bem-validator-page/


GitHub Pages: https://natalyapeshkova.github.io/2022SF/index.html


<!-- • Мобильная вёрстка на экранах < 1300 px. Опционально: модифицировать мобильную верстку для разрешения > 768 px.
В вашем проекте вы использовали медиа запросы для реализации адаптивной вёрстки, мобильная вёрстка выглядит корректно, всё верно!

+ 1 ИСПРАВИТЬ  Но хочу заметить, что вы ограничили ширину для body, что не является корректным, так как ограничивать нужно не ширину сайта, а ширину контента, для того чтобы ограничить ширину контента используйте контейнер.
Например:

HTML
<header class=”header”>
<div class=”container”>
<div class=”header__wrapper”>
…
</div>
</div>
</header>

<main>
<section class=”hero-section”>
<div class=”container”>
<div class=”header-section__wrapper”>
…
</div>
<div class=”hero-img”>
</section>
</main>

CSS
.container {
max-width: 1256px;
margin: 0 auto;
}

+ 2 ИСПРАВИТЬ Так же не рекомендую использовать абсолютное позиционирование для размещения блоков, например как блок “.hero-section”.

+ 3 ИСПРАВИТЬ Для позиционирования секции “online-control” лучше использовать margin-top с отрицательным значением, вместо абсолютного позиционирования.

+ 4 ИСПРАВИТЬ  Все иконки должны быть векторными. Figma позволяет экспортировать любой объект или группу.
На вашем сайте вы использовали иконки в формате svg, а так же jpg. Например кнопка и классом “button clients-element__button” имеют id, которым присвоен “ background-image”, что не является корректным, так в данном случае значения нельзя менять, а лишь поменять изображения, так же изображения имеют формат .jpg.

+ 5 ИСПРАВИТЬ Хочу заметить, что стрелки слайдера и поинты (точки) вы добавили одним изображением, корректная реализация в данном случаем будет такой, что каждая стрелка и точка, это отдельный элемент.

• Итоговую вёрстку загрузить на GitHub и предоставить ссылку на репозиторий.
Ваш проект вы опубликовали в репозитории на GitHub, всё верно.

+ 6 ИСПРАВЛЕНО   В форме обратной связи, которая имеет чёрный фон, вводимый текст в инпутах также имеет чёрный цвет, из-за чего текст сливается с фоном.

Развивайтесь и не останавливаетесь, я вижу ваш труд над этим проектом, вы хорошо постарались!
Если возникнут вопросы, Вы можете обратиться в общий канал в Slack @Илья #01-веб-верстка. Я постараюсь ответить на Ваши вопросы и помогу разобраться с моментами, которые вызывают трудности.
Вы движетесь в правильном направлении. Обучайтесь и задавайте вопросы!
Удачи в обучении!
Отзыв подготовил ментор Колосков Илья. -->