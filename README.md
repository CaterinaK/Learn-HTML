# Learn-HTML
<!DOCTYPE html>
<body>
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element" target=_blank>HTML elements reference</a>
  <a href="top"><p>Elements and Structure</p></a>
  <a href="bottom"><p>Tables</p></a>
  <hr>
<div>
  <p>HTML (<strong>H</strong>yper<strong>T</strong>ext <strong>M</strong>arkup <strong>L</strong>anguage). 
Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.
HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.</p>
  <p>Programmers use two tools to visualize the relationship between elements: <strong>whitespace</strong> and <strong>indentation</strong>. Indentation is a type of horizontal whitespace strategically used to enhance the readability of our code. For example, in HTML it is best practice to consistently indent our code to clearly illustrate nestings. Это типа отступы. 
  пустая ячейка это та, в которой нет никакого значения.</p> 
  </div>
  <div id=#top>
  <table>
      <tr> 
        <th colspan="2"><h3>Elements and Structure</h3></th>
    </tr>
    <tr>
      <td><strong>body</strong></td>
      <td>обязательный</td>
    </tr> 
    <tr>
      <td><strong>p, div</strong></td>
      <td>блоковые элементы. P параграфы, div блоки. После них новый абзац.</td>
    </tr>
    <tr>
      <td><strong>span</strong></td>
      <td>линейный элемент.</td>
    </tr>  
    <tr>
      <td><strong>br</strong></td>
      <td>пробелы между блоками.</td>
    </tr>
    <tr>
      <td><strong>h1 - h6</strong></td>
      <td>заголовки.</td>
    </tr>
    <tr>
      <td><strong>em</strong></td>
      <td>курсив.</td>
    </tr>
    <tr>
      <td><strong>strong</strong></td>
      <td>жирный.</td>
    </tr>
    <tr>
      <td><strong>ul</strong></td>
      <td>unordered list tag, каждый пункт с li.</td>
    </tr>
    <tr>
      <td><strong>ol</strong></td> 
      <td>ordered list ta.</td>
    </tr>
    <tr>
      <td><strong>li</strong></td>
      <td>для пунктов списков (любых).</td>
    </tr>
    <tr>
      <td><strong>img src= "URL"</strong></td>
      <td>изображение, self-closing tag (img.... /), обязательно с атрибутом, (<strong>u</strong>niform <strong>r</strong>esource <strong>l</strong>ocator).
      Отличие self-closing от остальных: не могут содержать контент (т.е. между открывающим и закрывающим тэгом, атрибуты контентом не считаются).</td>
    </tr>
    <tr>
      <td><strong>alt="..."</strong></td>
      <td>атрибут для описания, помогает оптимизировать поиск (поиск не видит изображения), когда не загрузилась само изображение и.т.д.</td>
    </tr>
    <tr>
      <td><strong>video</strong></td>
      <td>аналогично для видео. Нужен закрывающий тэг, но атрибуты внутри первого. Атрибуты: <strong>src</strong><strong>width</strong>, <strong>height</strong>, <strong>controls</strong>(булевой атрибут true\false, не нужен value. Это стандартные функции видео типа паузы и.т.д.)
           <br>
        Атрибут <strong>alt</strong> не используется, т.к. ссылку на альтернативное видео не сможет воспроизвести, например. Проблема обратной совместимости.
        <br> Текст между тэгами показывается только когда видео не может быть воспроизведено.</td> 
    </tr>
    </table>
  </div>
<div id=#"bottom">
  <table>
    <tr>
      <th colspan="2"><h3>Tables</h3></th>
    </tr>  
    <tr>
      <td><strong>!DOCTYPE html</strong></td>
      <td>какую версию html используем и.т.д.</td>
    </tr>
    <tr>
      <td><strong>head</strong></td>
      <td>метадата, содержит <strong>title</strong> - то, как будет называться страничка в браузере.</td> 
    </tr>
    <tr>
      <td><strong>a</strong></td>
      <td>гиперссылка, якорный элемент (anchor element), нужен атрибут <strong>href="URL"</strong>.Можно сделать не только надпись, но и ссылку на изображение. Может содержать другие тэги, но li не стоит использовать. 
        <br>Атрибут <strong>target</strong> для определения, где будет открываться ссылка. Значения: <strong>_blank</strong> (в новом окне), <strong>_self</strong> (в этом же окне, параметр по умолчанию), <strong>_parent</strong>, <strong>_top</strong> (полнооконный режим).</td>
    </tr> 
    <tr>
    <td><strong>id</strong></td>
    <td>для ссылки на части страницы нужно задать значение, например p id="top"NN p, h1 id="bottom NN h1. 
      <br>A relative path. about.html, contact.html, and index.html - обычно в одной папке. 
      <br>The ./ in ./index.html tells the browser to look for the file in the current folder.</td>
    </tr>
    <tr>
      <td><strong>!---NN---</strong></td>
      <td>комментарий\если нужно вынести текст, чтобы что-то проверить.</td>
    </tr>  
    <tr>
      <td><strong>table</strong></td>
      <td>таблица.</td>
    </tr>
    <tr>
      <td><strong>tr</strong></td>
      <td>чтобы добавить контент (table row element: tr). Этого недостаточно для добавления инфы, нужно для каждого cell элемента добавить тег.</td>
    </tr>
    <tr>
      <td><strong>td</strong></td>
      <td>the table data element: td.</td>
    </tr>
    <tr>
      <td><strong>th</strong></td>
      <td>the table heading element: th.</td>
    </tr>  
    <tr>
      <td><strong>scope</strong></td>
      <td><strong>row</strong> — this value makes it clear that the heading is for a row.
        <br>
        <strong>col</strong> — this value makes it clear that the heading is for a column.</td>
    </tr>
    <tr>
      <td><strong>border=цифра</strong></td>
      <td> для того, чтобы добавить границы, можно использовать атрибут border=цифра, но лучше не надо, т.к. это старая версия html. Сейчас границы лучше добавлять с использованием CSS.</td>
    </tr>
    <tr>
      <td><strong>colspan=цифра</strong></td>
      <td> чтобы данные занимали несколько колонок, используют атрибут colspan=число колонок. Важно  вносить по порядку.</td>
    </tr>
    <tr>
      <td><strong>rowspan</strong></td>
      <td>чтобы данные занимали несколько row, используют атрибут rowspan. можно и для <strong>th</strong>, тогда нужно использовать атрибут <strong>scope=”rowgroup”</strong>.</td>
      </tr>
    <tr> 
      <td>
        <strong>tbody</strong>
        <br>
        <strong>thead</strong>
        <br>
        <strong>tfoot</strong>
      </td>
    <td> если в таблице много данных, её можно разбить на блоки при помощи тегов tbody, thead, tfoot. С помощью css можно сделать так, чтобы верх и низ таблицы отображались при прокручивании основного массива. 
      Отличие <strong>thead</strong> и <strong>th</strong>: <strong>thead</strong> is essentially a box to hold your headings for the table. It is used along with tbody and tfoot to make up the entirety of a table - <em>header</em>, <em>body</em>, <em>footer</em>.
      On the otherhand, <strong>th</strong>is a single heading element.</td>
    </tr>
    <tr>
      <td><strong>class=...</strong></td>
      <td>
    </table>
  </body>
