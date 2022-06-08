# Вайпан Мари Сергеевна
### Junior Frontend-developer
### Контактная информация:
* **Телефон:** +79190565166
* **E-mail:** avemari98@gmail.com
* **Telegram:** @marifog

### Обо мне:
Ещё со школы меня заинтересовала математика и физика, перевод в физико-математически класс означал, что я хочу связать свою жизнь и будующую профессию с технической сферой. С первого раза не удалось сделать правильный выбор учебного заведения, я ошибочно полагала, что мне понравится учиться на инженера в области радиотехники, после попыток заставить себя разбираться в материале университет пришлось оставить. Затем месяцы размышлений о том, чем я хочу заниматься, вспоминаю, что в школе мне также нравилось решать задачи на программирование. Поиск в интернете на предмет областей разработки, которые мне бы пришлись по душе, привёл меня к профессии frontend-разработчика. Первые попытки вёрстки и изучения JavaScript принесли мне большое удовольствие, хотелось узнавать больше, разбираться в документации, пробовать новые методы решения задач. Надеюсь в скором времени стать хорошим специалистом и иметь возможность работать заграницей.
У меня есть опыт самостоятельного обучения, с помощью платных и бесплатных курсов, на данный момент хочу попробовать программу Rolling Scopes School.

### Технологии:
* HTML
* CSS
* JavaScript
* Git
* SASS, LESS
* Figma
* Webpack
* npm-пакеты
 
* Английский язык — B2
* Русский язык — Родной

### Пример кода:
*Разметка, отображающая карточки товаров, реализованная на JavaScript:*
```const sectionWrapper = document.querySelector('.products__wrapper');

window.addEventListener('DOMContentLoaded', function() {
    let displayMenu = menu.map(function(item) {
        return `
        <div class="product__item">
        <div class="product__visual">                        
            <img src="${item.img}" alt="${item.title}" class="product__img">
            <div class="product__price">${item.price}₽</div>
            <div class="product__weight">${item.weight} г</div>
        </div>
        <div class="product__details">
            <h1 class="product__name">${item.title}</h1>
            <div class="product__desc">${item.desc}</div>
         </div>
    </div>
        `;
    });
    displayMenu = displayMenu.join('');
    sectionWrapper.innerHTML = displayMenu;
})```