# НАУЧИТЬСЯ УЧИТЬСЯ

https://ksenia-beznos.github.io/how-to-learn/

![Alt-шапка](/images/Header.png)

>> Ни в школе, ни в институте нас не учат тому, как правильно изучать материал. Мы готовимся к экзаменам и учим билеты. Мы тренируемся решать однообразные задачи, чтобы лучше сдать тест, но часто в итоге это не дает нам реального знания. Зубрежка быстро выветривается и не приносит пользы. **Вывод:** учиться тоже нужно уметь, но почему-то этому мало где учат.



Именно этой проблеме посвящен проект **«Научиться учиться»**.
Он представляет собой лендинг, состоящий из 11 блоков:
- **_Header_** - шапка сайта (1 блок).
- **_Content_** - основня информация (9 блоков).
- **_Footer_** - подвал сайта (1 блок).

____

В проекте представлены техники и методы эффективного обучения, с помощью которых можно освоить новую профессию или получить полезные знания и навыки в интересующей вас сфере.


Информация, представленная на сайте, даст вам понять, что учиться можно легко и в удовольствие. И что любой навык можно развить с нуля, при условии, что вы учитесь **ПРАВИЛЬНО**.


![Alt-Факты](/images/Facts.png)


Сайт написан с нуля по итогам четырехнедельного обучения в **Яндекс Практикум**.
За эти 4 недели было изучено множество различных техник и свойств, которые позволили сверстать данный сайт, используя **CSS** и **HTML**.

____

## **КАКИЕ ТЕХНОЛОГИИ ИСПОЛЬЗОВАЛИСЬ?**


### :heavy_check_mark: _Анимация элемента_

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

### :heavy_check_mark: _Вставка видео с использованием iframe_

```html
<div class="video__iframes">
  <iframe class="video__iframe" src="https://www.youtube.com/embed/arj7oStGLkU" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  <iframe class="video__iframe" src="https://www.youtube.com/embed/5MgBikgcWnY" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```

### :heavy_check_mark: _Flexbox вёрстка_

![Alt-Флекс](/images/Flexbox.png)

____

## **ЧТО ЕЩЕ?**

:white_check_mark: Псевдокласс _:hover_ для ссылкок;

:white_check_mark: Тег _span_ для выделения фразы внутри строки;

:white_check_mark: Вставка _ссылок_ в текст;

:white_check_mark: Вставка _изображений_ (имиджевых и декоративных);

:white_check_mark: Использование _мнемоники_;

:white_check_mark: _Позиционирование_ элементов относительно блока и относительно друг друга;

____

## **ЧТО В ПЛАНАХ?**

- [ ] Добавить на сайт формы;
- [ ] Сделать сайт многостраничным;
- [ ] Сделать сайт адаптивным;
- [ ] Внедрить Java Script.

____

Структура сайта и организация файлов составлена по технологии **БЭМ**.

**Автор сайта**: Ксения Безнос.
