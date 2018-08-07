# Learn-HTML
<!DOCTYPE html>
<body>
<h2>Elements and Structure</h2>
<div>HTML (<strong>H</strong>yper<strong>T</strong>ext <strong>M</strong>arkup <strong>L</strong>anguage). 
Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.
HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.</div>
<br>
  <div>
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
<strong>h1 - h6</strong> - заголовки.
 <strong>em</strong> -  курсив.
<strong>strong</strong> - жирный.
  unordered list tag <strong>ul</strong> - каждый пункт с li.
ordered list tag <strong>ol</strong>.
<strong>li</strong> - для пунктов списков (любых).
<strong>img</strong> - изображение, self-closing tag (img.... /). 
      
Нужен атрибут <strong>src= "URL"</strong> (uniform resource locator).
<strong>alt="..."</strong> для описания, помогает оптимизировать поиск (он не видит изображения), когда                     не загрузилась само изображение и.т.д.

<strong>video</strong> - аналогично для видео. Нужен закрывающий тэг, но атрибуты внутри первого. Атрибуты: 

<strong>src</strong>, <strong>width</strong>, <strong>height</strong>,<strong>controls</strong> (булевой атрибут true\false, не нужен value. Это стандартные функции видео типа паузы и.т.д.) 
            <br>
            Атрибут alt не используется, т.к. ссылку на альтернативное видео не сможет воспроизвести, например. Проблема обратной совместимости.
            <br>
Текст между тэгами показывается только когда видео не может быть воспроизведено. 
            
Отличие self-closing от остальных: не могут содержать контент (т.е. между открывающим и закрывающим тэгом, атрибуты контентом не считаются). 

<h2>Learn HTML: Tables</h2>
<strong>!DOCTYPE html</strong> - какую версию html используем и.т.д.
<strong>head</strong> - метадата
содержит title - то, как будет называться страничка в браузере. 
a - гиперссылка, якорный элемент, нужен атрибут href="URL".
Можно сделать не только надпись, но и ссылку на изображение. Может содержать другие тэги, но li не стоит использовать. 

For a link to open in a new window, the target attribute requires a value of _blank. The target attribute can be added directly to the opening tag of the anchor element, just like the href attribute.
Yes, there are 4 different values the target attribute can have: _self (в том же окне, это по умолчанию), _blank, _parent, or _top (полнооконный режим). 

A relative path. about.html, contact.html, and index.html - обычно в одной папке. The ./ in ./index.html tells the browser to look for the file in the current folder. 

Ссылки на части страницы. In order to link to a target on the same page, we must give the target an id, like this:
p id="top"NN p
h1 id="bottom NN h1

Programmers use two tools to visualize the relationship between elements: whitespace and indentation. Indentation is a type of horizontal whitespace strategically used to enhance the readability of our code. For example, in HTML it is best practice to consistently indent our code to clearly illustrate nestings. Это типа отступы. 

Comments begin with !-- and end with -- Или комментарий, если если хочется вынести какой-то текст, чтобы что-то проверить.  

https://developer.mozilla.org/en-US/docs/Web/HTML/Element

table -таблица
чтобы добавить контент table row element: tr. Этого недостаточно для добавления инфы, нужно для каждого cell элемента добавить тег. 
the table data element: td. 
the table heading element: th.
Note, also, the use of the scope attribute, which can take one of two values:

row - this value makes it clear that the heading is for a row.
col - this value makes it clear that the heading is for a column.

для того, чтобы добавить границы, можно использовать атрибут border=цифра, но лучше не надо, т.к. это старая версия html. Сейчас границы лучше добавлять с использованием CSS. 

чтобы данные занимали несколько колонок, используют атрибут colspan=число колонок. важно по порядку вносить. 
чтобы данные занимали несколько row, используют атрибут rowspan. можно и для th, тогда нужно использовать атрибут scope=”rowgroup”. 

пустая ячейка это та, в которой нет никакого значения. 

если в таблице много данных, её можно разбить на блоки при помощи тегов tbody, thead, tfoot. с помощью css можно сделать так, чтобы верх и низ таблицы отображались при прокручивании основного массива. 

Отличие thead и th: thead 22 is essentially a box to hold your headings for the table. It is used along with tbody and tfoot to make up the entirety of a table - header, body, footer.
On the otherhand, th 15 is a single heading element.

атрибуты классы (left, например)



The table element creates a table.
The tr element adds rows to a table.
To add data to a row, you can use the td element.
Table headings clarify the meaning of data. Headings are added with the th element.
Table data can span columns using the colspan attribute.
Table data can span rows using the rowspan attribute.
Tables can be split into three main sections: a head, a body, and a footer.
A table's head is created with the <thead> element.
A table's body is created with the <tbody> element.
A table's footer is created with the <tfoot> element.
All the CSS properties you learned about in this course can be applied to tables and their data.
  </body>
