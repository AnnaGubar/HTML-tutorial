- **.block** - создаст `<div class="block"></div>`
- **h1.title** - создает `<h1 class="title"></h1>`

* **CSS (Cascading Style Sheets, каскадные таблицы стилей)**

* **_ВАЖНО_** определить основную палитру цветов и записать ее

  - `:root { --primary-text-color: #2e7a70; }`
  - `body { color: var(--primary-text-color); } `

* **_селекторы_**
  - _.button.primary_ - тег имеет оба класса button и primary
  - _.button > .primary_ - тег с классом primary является _ребенком_ тега с
    классом button
  - _.button .primary_ - тег с классом primary является _потомком_ тега с
    классом button

- _:hover :focus_ - всегда вместе
- _.link:active_ - отметка текущей страницы
- _.link:visited_

- `a { text-decoration: none; }` - убирает подчеркивание
- `ul { list-style: none; }` - убирает маркировку
- `#title {...}` - _идентификатор_

- `.post-link { color: inherit; }` - унаследывает цвет родителя
- `.button.primary { background-color: var(--accent-color); border-color: transparent; }` -
  цвет рамки унаследует цвет фона
