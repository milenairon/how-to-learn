# Проект "Научиться учиться"

---

<div align="center">
<img src='./images/Научиться-учиться.gif' alt='котик за компьютером'>
</div>

---

## Оглавление

1. Описание
2. Как запустить проект
3. Функциональность
4. Технологии
5. Ссылка на GitHub Pages

---

## 1. Описание

Данный проект - это одностраничный сайт, рассказывающий о современных и эффективных подходах к обучению.

В проекте были применены новые изученные технологии такие, как:

- анимация;
- шрифты;
- фреймы;
- файловая структура проекта по правилам Nested БЭМ;
- сгругление картинки;
- добавление линейности блочным элементам.
  Более подробно см. п.Технологии

---

## 2. Как запустить проект

Как запустить проект:

### Вариант 1. Запустить через gh-pages.
Перейдите по ссылке https://milenairon.github.io/how-to-learn/

### Вариант 2. Скачать и запустить кликом index.html 
1. Скачайте из репозитория https://github.com/milenairon/how-to-learn папку, нажав на кнопку Code → Download ZIP
2. Извлеките данные из папки.
3. Вариант 1. Откройте проект, нажав левой кнопкой мыши 2 раза на файл index.html.

### Вариант 3. Скачать и запустить через Live Server
1. Скачайте из репозитория https://github.com/milenairon/how-to-learn папку, нажав на кнопку Code → Download ZIP
2. Извлеките данные из папки.
3. Если у вас VS Code, то откройте папку при помощи этого приложения. Скачайте расширение для VS Code Live Server. 
4. Откройте проект, нажав правой кнопкой мыши 1 раз на файл index.html в VS Code и выберите Open with Live Server.

---

## 3. Функциональность

Данный сайт обладает следующими критериями функциональности:

- дизайн;
- контент;
- структура;
- доступные функции;

Под функциями понимаются следующие возможности:

- переход на фрагмент страницы с целью узнать о современных и эффективных подходах обучения;
- просмотра текта и видео-материала без перехода на сторонние сайты;
- получения дополнительного полезного материала;
- переход на другую страницу с целью ознакомления с наставниками, концепции и главной страницы Практикума;
- переход на другую страницу с целью ознакомления с соцсетями Практикума.

---

## 4. Технологии

### а. Анимация

```
CSS:
@keyframes rotation {
to {...}
from {...}
}
.rotation {
animation-name:...;
animation-duration:...;
animation-iteration-count:...;
}
```

### б. Шрифты

Возможность подключения любых шрифтов в свободное время (один из пунктов стратегии улучшения проекта в будущем).

### в. Фреймы

```
HTML:
<iframe class="..." allowfullscreen title="..." frameborder="..." width="..." height="..." src="..."></frame>
```

### Файловая структура проекта по правилам Nested БЭМ;

```
папка "блок"
    папка "__элемент"
        папка "_ключ модификатора"
            папка "_значение модификатора"
                файл  "блок__элемент_значение модификатора"
    файл "блок__элемент.css"
файл "блок.css"
```

### Сгругление картинки

```
border: radius(...%)
```

### Добавление линейности блочным элементам;

```
display: inline-block
```

или

```
display: inline
```

---

## 5. Ссылка на GitHub Pages

https://milenairon.github.io/how-to-learn/
