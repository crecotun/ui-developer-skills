# Что должен уметь HTML-верстальщик?

Этот репозиторий создан на основе [статьи](http://krekotun.ru/ui-developer-skills).  
Я бы хотел, чтобы у каждого была возможность внести свой вклад в список — добавить полезные ссылки, дополнить описание или добавить новые разделы. Так мы сможем поддерживать список в актуальном состоянии.


## Коротко

- [Английский язык](#Английский-язык)
- [HTML и CSS](#html-и-css)
- [Графические редакторы](#Графические-редакторы)
- [Инструменты разработчика в браузере](#Инструменты-разработчика-в-браузере)
- [Emmet](#emmet)
- [Семантика и доступность](#accessibility)
- [Правильное именование](#naming)
- [Responsive/adaptive верстка](#responsive)
- [jQuery](#jquery)
- [Подключение шрифтов](#fonts)
- [Сборка спрайтов](#sprites)
- [Оптимизация изображений](#image-optimization)
- [Работа с SVG](#svg)
- [SVG-спрайты](#svg-sprites)
- [CSS-анимации и плавные переходы](#animations)
- [CSS-методологии](#css-methodologies)
- [CSS-фреймворки](#css-frameworks)
- [Верстка писем](#email)
- [Командная строка](#cli)
- [Git](#git)
- [CSS-препроцессоры](#css-preprocessors)
- [Шаблонизаторы](#templates)
- [Автоматизация: таск-раннеры](#task-runners)
- [Тестирование верстки](#testing)

## Подробно

### <span id="english"></span> Английский язык
Очень важно уметь читать и понимать по-английски, чтобы иметь доступ к актуальной информации. Лишь небольшой процент статей переводится на русский язык, а документация к плагинам и инструментам в основном представлена на английском.  
Это не блокирующий навык, можно вполне успешно учиться и работать без него, но он является огромным плюсом.

- [engVid](http://www.engvid.com/)
- [Native English](http://www.native-english.ru/)
- [Lingualeo](https://lingualeo.com)
- [duolingo](https://ru.duolingo.com/)

### <span id="html-css"></span> HTML и CSS
- [Уроки по HTML и CSS](https://webref.ru/layout/learn-html-css) (бывший [htmlbook](http://htmlbook.ru/))
- [Самоучитель HTML4](http://htmlbook.ru/samhtml)
- [Самоучитель CSS](http://htmlbook.ru/samcss)
- [Основы CSS/CSS3](https://www.youtube.com/playlist?list=PL026CCEB5125879C2)
- [HTML Academy](https://htmlacademy.ru/)
- [Codecademy](https://www.codecademy.com/)

### <span id="ui-editors"></span> Графические редакторы
Самые популярные: Photoshop и Sketch.  
В ~90% случаев Photoshop'а будет достаточно, дизайнеры только недавно начали переходить на Sketch.
Sketch вообще под Windows не работает, но есть почти-решение в лице [zeplin](https://zeplin.io/)  

Необходимый минимум, чтобы начать работать:

- нарезка и экспорт графических элементов;
- работа со стилями слоя;
- информация о тексте (размер, шрифт, цвет, межстрочный интервал и тд.).

<span></span>

* [Photoshop для кодера](http://xiper.net/learn/photoshop/)
* [Photoshop для HTML‑верстальщика](http://nicothin.pro/page/photoshop-dlja-html-verstalshhika)
* [Photoshop экшены для верстальщика](http://vovanr.com/posts/photoshop-actions/)
* [Photoshop - пример нарезки макета для верстки](http://gearmobile.github.io/photoshop/photoshop-example-cutting-mockup/)
* [Нарезка в Photoshop — New Layer Based Slice](http://paulradzkov.com/2012/photoshop_new_layer_based_slice/)
* [Экспорт слоев из Photoshop в один клик!](http://jnet.kz/httml/2014/03/13/eksport-sloev-iz-photoshop-v-odin-klik.html)
* [The Ultimate Front-End Developer's Guide to Photoshop](https://www.netguru.co/blog/photoshop-for-front-end-developers)
* [A Web Developer’s Guide to Photoshop](http://rafaltomal.com/a-web-developerss-guide-to-photoshop/)

### <span id="devtools"></span> Инструменты разработчика в браузере
Это набор инструментов, помогающих быстро найти и исправить ошибку. Верстальщиками часто используется для поиска ответа на вопросы: “почему не отображается?”, “откуда такие размеры?”, “я же его перекрасил” и тд.  
Умение пользоваться этими инструментами сохранит вам кучу времени и нервов.

- [Chrome DevTools](https://developer.chrome.com/devtools)
- [Курс от codeschool](http://discover-devtools.codeschool.com/)
- [Chrome DevTools, в помощь верстальщику](https://www.youtube.com/watch?v=eqJDcbNVe54)
- [Инструменты разработчика Firefox](https://developer.mozilla.org/ru/docs/Tools)

<figure class="-negative">
<img src="/images/ui-developer-skills/devtools.png" alt="Chrome DevTools">
<figcaption>Chrome DevTools</figcaption>
</figure>

### <span id="emmet"></span> Emmet
Набор сниппетов для HTML и CSS, дающий супер-скорость.  
Лучше 1 раз почитать [документацию](http://docs.emmet.io/) и сразу начать использовать.

### <span id="accessibility"></span> Семантика и доступность
- [Семантическая вёрстка. Часть первая](https://pepelsbey.net/2008/04/semantic-coding-1/)
- [Искусство семантики HTML, часть 1](http://frontender.info/the-art-of-html-semantics-pt1/)
- [Семантический HTML — рекомендация с большими выгодами](http://www.xiper.net/learn/tegofenshuj/about-semantic.html)
- [Продвинутая семантика и доступность](https://webref.ru/layout/advanced-html-css/semantics-accessibility)
- [Подстраховка web-доступности семантических областей HTML5 через роли WAI-ARIA](https://habrahabr.ru/post/240065/)

### <span id="naming"></span> Правильное именование
Имена должны нести в себе смысл. Цель — сделать код хорошо читаемым и легко поддерживаемым.  
У новичков часто можно встретить `<b class="b">`, `<div class="div13>"` и все в таком духе. Это неправильно.
Также нельзя использовать транслитерацию `<div class="shapka">`.  
Общепринятый язык для именования — английский.

- [Слова, часто используемые в CSS-классах](https://github.com/yoksel/common-words)
- [How to name CSS classes](http://www.bdavid.xyz/how-to-name-css-classes/)

### <span id="responsive"></span> Responsive/adaptive верстка
Больше половины трафика в интернете приходится на мобильные телефоны и сделать адаптивный сайт порой намного проще и быстрее, чем разработать отдельную версию под мобильные. Очень важно уметь делать этот вид работ, чтобы быть конкурентноспособным.  
Большое преимущество — умение релизовывать поведение на мобильных устройствах без наличия макетов от дизайнера.

- [Адаптивно-отзывчивый: разбираемся в терминологии](http://frontender.info/adaptive-vs-responsive-terminology/)
- [Наглядно для заказчика: адаптивный и отзывчивый сайт — в чем разница](http://blog.sibirix.ru/2015/04/21/adaptive-responsive/)
- [Beginner’s Guide to Responsive Web Design](http://blog.teamtreehouse.com/beginners-guide-to-responsive-web-design)

<figure>
<img src="/images/ui-developer-skills/responsive.png" alt="Респонсив" style="width: 500px">
</figure>

### <span id="jquery"></span> jQuery
Вы должны знать jquery хотя бы на начальном уровне, чтобы подключать и настраивать тонны плагинов, написанные за многие годы популярности этой библиотеки.

- [Учебник “jQuery для начинающих”](http://anton.shevchuk.name/jquery-book/)

### <span id="fonts"></span> Подключение шрифтов
- [Загрузка своего шрифта](https://webref.ru/layout/html5-css3/text/font-face)
- [Как подключить шрифт](http://site4business.net/css/kak-podklyuchit-shrift.html)
- [Подключение шрифта к странице: как нужно делать сейчас](http://nicothin.pro/page/web-fonts)

### <span id="sprites"></span> Сборка спрайтов
Спрайт — графический файл, в котором сгруппировано много изображений небольшого размера. Такая организация графики позволяет минимизировать количество запросов за сервер и ускорить загрузку сайта.  

- [Введение в CSS спрайты для чайников](http://onjee.ru/css-sprites/)
- [Верстка с использованием CSS спрайтов](https://marahtanov.ru/edu/webp/reports/css_sprite.html)
- [CSS Sprites: Image Slicing’s Kiss of Death](http://alistapart.com/article/sprites)
- [CSS Sprites: What They Are, Why They’re Cool, and How To Use Them](https://css-tricks.com/css-sprites/)

<figure>
<img src="/images/ui-developer-skills/sprite-2x.png" alt="Пример спрайта" style="width: 225px">
<figcaption>Пример спрайта</figcaption>
</figure>

### <span id="image-optimization"></span> Оптимизация изображений
Во времена быстрого интернета легко забыть о том, что нужно оптимизировать изображения. Недавно я проверял работу начинающего разработчика и прогнал изображения через оптимизатор. Картинки похудели на 86% (16 мегабайт). Вдумайтесь.  
Также важно уметь выбрать оптимальный формат графики (jpg, png, gif, svg).

- [Всё, что нужно знать об оптимизации изображений для сайта](http://ru.wix.com/blog/2014/07/%D0%BE%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B9-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B0%D0%B9%D1%82%D0%B0/)
- [Оптимизация изображений](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization?hl=ru)

### <span id="svg"></span> Работа с SVG
- [Использование SVG](http://frontender.info/using-svg/)
- [SVG](http://css.yoksel.ru/svg/)
- [SVG в HTML — из иллюстратора в браузер](https://www.youtube.com/watch?v=S0OnkpIoEyQ)

### <span id="svg-sprites"></span> SVG-спрайты
- [SVG-спрайты](http://nicothin.pro/page/svg-sprites)
- [Масштабируем CSS спрайты с SVG, убивая сразу трех зайцев](https://habrahabr.ru/post/141654/)
- [SVG спрайты — 4 способа использования векторных спрайтов](https://www.youtube.com/watch?v=S_wZSjLiUog)

### <span id="animations"></span> CSS-анимации и плавные переходы
- [Плавные переходы (transition)](https://www.youtube.com/watch?v=QKRmRpq5CQc)
- [Css Animation](http://css.yoksel.ru/css-animation/)
- [Очень простое руководство по CSS3-анимациям](http://frontender.info/ochen-prostoe-rukovodstvo-po-css-animatsiyam/)

### <span id="css-methodologies"></span> CSS-методологии
Сотни их: OOCSS, BEM, SMACSS и тд. Не обязательно все использовать, но вы должны иметь представление о лучших практиках css-архитектуры.

- [БЭМ](https://ru.bem.info/)
- [SMACSS](https://smacss.com/)
- [An Introduction To Object Oriented CSS (OOCSS)](https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/)
- [Методологии верстки: БЭМ, AMCSS, OOCSS, Atomic CSS, OPOR, MCSS, SMACSS, FUN, DoCSSa](http://html5.by/blog/bem-amcss-oocss-atomiccss-opor-mcss-smacss-fun-docssa-video/)

### <span id="css-frameworks"></span> CSS-фреймворки
Я не рекомендую верстать на базе фреймворков, они предназначены, в первую очередь, для прототипирования. Их полезно изучать и понимать как реализованы компоненты.

- [Bootstrap](http://getbootstrap.com/)
- [Foundation](http://foundation.zurb.com/sites.html)
- [Pure](http://purecss.io/)
- [Skeleton](http://getskeleton.com/)

### <span id="email"></span> Верстка писем
Ад мира HTML-верстки. Привет из нулевых. Тут свои правила и до сих пор верстка таблицами. Звучит плохо, на деле еще хуже.

- [Верстка email рассылок от А до Я для чайников](https://habrahabr.ru/post/252279/)
- [How-to: Правила вёрстки email-писем](https://habrahabr.ru/company/pechkin/blog/255819/)
- [Основы профессиональной верстки электронных писем](https://habrahabr.ru/post/180013/)

### <span id="cli"></span> Командная строка
Необходимый инструмент для доступа к радостям жизни: препроцессорам, компиляции шаблонов, запуску таск-раннеров, git и другим полезным вещам.

- [Командная строка (cmd) для веб-мастера](http://gearmobile.github.io/web-tools/webmaster-command-line/)

### <span id="git"></span> Git
Популярная система для хранения истории изменений и синхронизации результатов работы между участниками в проекте.

- [Git - для новичков - #1 - основы](https://www.youtube.com/watch?v=PEKN8NtBDQ0)
- [Github Tutorial](https://try.github.io/)
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials/)
- [Git How To](https://githowto.com/)
- [Моя шпаргалка по работе с Git](http://eax.me/git-commands/)
- [Шпаргалка по консольным командам Git](https://github.com/nicothin/web-development/tree/master/git)
- [Pro Git, второе издание](https://github.com/progit/progit2-ru)
- [Коллекция часто задаваемых вопросов по Git с возможностью поиска](http://firstaidgit.ru/)

### <span id="css-preprocessors"></span> CSS-препроцессоры
Препроцессоры ускоряют работу, упрощают жизнь и позволяют использовать много возможностей, которые еще не реализованы в браузерах.  

- [Sass](http://sass-lang.com/)
- [Stylus](http://stylus-lang.com/)
- [Less](http://lesscss.org/)
- [PostCSS](http://postcss.org/) + [PreCSS](https://github.com/jonathantneal/precss) (одна из связок)
- [Как работать с CSS-препроцессорами и БЭМ](http://nicothin.github.io/idiomatic-pre-CSS/)

### <span id="templates"></span> Шаблонизаторы
Представьте у вас 10 страниц и на каждой надо внести изменения в один и тот же блок. Это больно и долго.  
Одна из возможностей шаблонизаторов — выделять повторяющиеся блоки в отдельные файлы. Вынесли блок, подключили на нужны страницах и все — теперь вы делаете в 10 раз меньше работы.

- [Pug](http://jade-lang.com/) (бывший Jade)
- [HAML](http://haml.info/)
- [Twig](http://twig.sensiolabs.org/)
- [Blade](https://laravel.com/docs/5.1/blade)

### <span id="task-runners"></span> Автоматизация: таск-раннеры
Вся рутина должна быть автоматизирована. Примеры автоматизации — запуск препроцессоров и шаблонизаторов, оптимизация графики, сборка спрайтов, сжатие css и js.

- [Gulp](http://gulpjs.com/)
- [Скринкаст по Gulp](https://learn.javascript.ru/screencast/gulp)
- [Gulp for Beginners](https://css-tricks.com/gulp-for-beginners/)
- [Getting started with gulp](https://markgoodyear.com/2014/01/getting-started-with-gulp/)
- [Продолжаем бороться с frontend-рутиной](https://habrahabr.ru/company/2gis/blog/269743/)
- [Grunt](http://gruntjs.com/)
- [A Simple Guide to Getting Started With Grunt](https://scotch.io/tutorials/a-simple-guide-to-getting-started-with-grunt)

### <span id="testing"></span> Тестирование верстки
Плох тот разработчик, который не тестирует свою работу.

- [Чек-лист вёрстки. Что можно отдавать клиенту, а что надо переделывать](https://habrahabr.ru/post/114256/)
- [Тестирование верстки](http://xiper.net/collect/weekdays-front-end-dev/the-work-in-general/testing-layout)
- [Автоматизированное тестирование верстки веб-сайтов](http://sqadays.com/talk/37161)
