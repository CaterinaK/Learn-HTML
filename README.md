# Learn-HTML
<!DOCTYPE html>
<body>
<h2>Elements and Structure</h2>
<div>HTML (<strong>H</strong>yper<strong>T</strong>ext <strong>M</strong>arkup <strong>L</strong>anguage). 
Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.
HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.</div>
<br>
  <div>
    <ul>
      <li><strong>body</strong> - обязательный</li>
      <li><strong>p, div</strong> - блоковые элементы. P параграфы, div блоки. После них новый абзац.</li>
      <li><strong>span</strong> - линейный элемент.</li>   
      <li><strong>br</strong> - пробелы между блоками.</li>   
      <li><strong>h1 - h6</strong> - заголовки.</li>
      <li><strong>em</strong> -  курсив.</li>
      <li><strong>strong</strong> - жирный.</li>  
      <li>unordered list tag <strong>ul</strong> - каждый пункт с li.</li>
      <li>ordered list tag <strong>ol</strong>.</li> 
      <li><strong>li</strong> - для пунктов списков (любых).</li>
      <li><strong>img</strong> - изображение, self-closing tag (img.... /). 
        <ul>
          <li>Нужен атрибут <strong>src= "URL"</strong> (uniform resource locator).</li> 
          <li><strong>alt="..."</strong> для описания, помогает оптимизировать поиск (он не видит изображения), когда                     не загрузилась само изображение и.т.д.</li>
        </ul>
      <li><strong>video</strong> - аналогично для видео. Нужен закрывающий тэг, но атрибуты внутри первого. Атрибуты: 
        <ul>
          <li><strong>src</strong>, <strong>width</strong>, <strong>height</strong>,<strong>controls</strong> (булевой атрибут true\false, не нужен value. Это стандартные функции видео типа паузы и.т.д.) 
            <br>
            Атрибут alt не используется, т.к. ссылку на альтернативное видео не сможет воспроизвести, например. Проблема обратной совместимости.
            <br>
Текст между тэгами показывается только когда видео не может быть воспроизведено. 
        </ul>
            
Отличие self-closing от остальных: не могут содержать контент (т.е. между открывающим и закрывающим тэгом, атрибуты контентом не считаются). 

!DOCTYPE html - какую версию html используем и.т.д.
head - метадата
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

</body>
