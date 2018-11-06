<div align="center">
  <img width="130" alt="Логотип веб-компонентов" src="/logos/web-components.svg">
</div>

<h1 align="center">Мои примеры веб-компонентов</h1>

Мои примеры веб-компонентов, созданных для понимания данной технологии

> В примерах используется Yarn, поэтому советую [установить](https://yarnpkg.com/en/docs/install) и [попробовать](https://yarnpkg.com/en/docs/getting-started) его. Вы можете безболезненно [мигрировать](https://yarnpkg.com/lang/en/docs/migrating-from-npm/) с NPM на Yarn, однако ничего не мешает использовать NPM

<h2 align="center">Зачем?</h2>

Данный репозиторий создан для понимания принципа работы веб-компонентов и библиотек на их основе. А также для понимания инструментов для создания веб-компонентов, к которым можно отнести: [Stencil](https://github.com/ionic-team/stencil), [Polymer](https://github.com/Polymer/polymer), [Lit-html](https://github.com/Polymer/lit-html), [Hybrids](https://github.com/hybridsjs/hybrids) и т.п.

Этот проект не является гайдом или введением в веб-компоненты и все что с ними связано

Это всего лишь репозиторий с тестовыми примерами и ссылками на статьи, который может быть заброшен в любое время

<h2 align="center">Введение</h2>

> Это краткое введение, более подробное можно посмотреть на [webcomponents.org](https://www.webcomponents.org/introduction) [EN]

Веб-компоненты - это семейство API, предназначенных для описания новых элементов DOM, подходящих для повторного использования. Функционал таких элементов отделён от остального кода, их можно применять в веб-приложениях собственной разработки

Существует четыре технологии, относящиеся к веб-компонентам:

- [Shadow DOM](https://w3c.github.io/webcomponents/spec/shadow/) (Теневой DOM)
- [HTML Templates](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element/) (HTML-шаблоны)
- [Custom Elements](https://w3c.github.io/webcomponents/spec/custom/) (Пользовательские элементы)
- [ES Modules](https://html.spec.whatwg.org/multipage/webappapis.html#integration-with-the-javascript-module-system) (ES-модули)

Ранее были [HTML Imports](https://www.w3.org/TR/html-imports/) (HTML-импорты), однако вместо них теперь используются ES Modules, по [причине](https://developer.mozilla.org/ru/docs/Web/Web_Components/HTML_Imports) отказа поддержки этой технологии в Firefox

<h2 align="center">Лицензия</h2>

[MIT](/LICENSE)
