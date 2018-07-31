# Learn-HTML
<body>
<h2>Elements and Structure</h2>
<br>
<br>
<div>HTML (<strong>H</strong>yper<strong>T</strong>ext <strong>M</strong>arkup <strong>L</strong>anguage). 
Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.
HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.</div>
<br>
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
      <li><strong>img</strong> - изображение, self-closing tag (img.... /). 
        <ul>
          <li>Нужен атрибут <strong>src= "URL"</strong> (uniform resource locator).</li> 
          <li><strong>alt="..."</strong> для описания, помогает оптимизировать поиск (он не видит изображения), когда                     не загрузилась само изображение и.т.д.</li>
        </ul>
      <li><strong>video</strong> - аналогично для видео. Нужен закрывающий тэг, но атрибуты внутри первого. Атрибуты: 
        <ul>
          <li><strong>src</strong>, <strong>width</strong>, <strong>height</strong>,<strong>controls</strong> (булевой атрибут true\false, не нужен value это стандартные функции типа паузы и.т.д.) 
            <br>
            Атрибут alt не используется, т.к. ссылку на альтернативное видео не сможет воспроизвести, например. Проблема обратной совместимости.
            <br>
Текст между тэгами показывается только когда видео не может быть воспроизведено. 
        </ul>
            
Отличие self-closing от остальных: не могут содержать контент (т.е. между открывающим и закрывающим тэгом, атрибуты контентом не считаются). 
</body>
