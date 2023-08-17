# НАУЧИТЬСЯ УЧИТЬСЯ

### Описание
Проект посвящен верстке лендинга, состоящего из 11-ти блоков.


>> Ни в школе, ни в институте нас не учат тому, как правильно изучать материал. Мы готовимся к экзаменам и учим билеты. Мы тренируемся решать однообразные задачи, чтобы лучше сдать тест, но часто в итоге это не дает нам реального знания. Зубрежка быстро выветривается и не приносит пользы. **Вывод:** учиться тоже нужно уметь, но почему-то этому мало где учат.

![Alt-шапка](/images/Header.png)

Сайт написан с нуля по итогам четырехнедельного обучения в **Яндекс Практикум**.
За эти 4 недели было изучено множество различных техник, которые позволили сверстать данный сайт, используя **CSS** и **HTML**.

### **Какие технологии использовались**


* ### Анимация элемента

```css
@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
.rotation {
  animation-name: rotation;
  animation-duration: 20s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
```

* ### Вставка видео с использованием iframe

```html
<div class="video__iframes">
  <iframe class="video__iframe" src="https://www.youtube.com/embed/arj7oStGLkU" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  <iframe class="video__iframe" src="https://www.youtube.com/embed/5MgBikgcWnY" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

* ### Flexbox

![Alt-Флекс](/images/Flexbox.png)

* Методология БЭМ;
* Файловая структура БЭМ Nested.

### **Бриф проекта**
* [Бриф 1](https://code.s3.yandex.net/web-developer/project-1/sprint-1-brief.pdf)
* [Бриф 2](https://code.s3.yandex.net/web-developer/project-1/sprint-2-brief.pdf)

### **Ссылка на сайт**
https://ksenia-beznos.github.io/how-to-learn/

**Автор сайта**: Ксения Безнос.
