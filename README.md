# Learn-HTML

<h1>Elements and Structure</h1>
<br>
<br>
HTML (<strong>H</strong>yper<strong>T</strong>ext <strong>M</strong>arkup <strong>L</strong>anguage). 
Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.
HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.

<h2>List</h2>
<br>
<br>
<>(body)</em> - обязательный
(p) (div) - блоковые элементы. P параграфы, div блоки. После них новый абзац. 
(span) - линейный элемент.   
(br) - пробелы между блоками.   
(h1) - (h6) - заголовки
(em) -  курсив
(strong) - жирный  
unordered list tag (ul) - каждый пункт с (li)
ordered list tag (ol) 
(img) - изображение, self-closing tag (img.... /). Нужен атрибут src= URL (uniform resource locator) 
                                                   alt="..." для описания, помогает оптимизировать поиск (он не видит изображения), когда                                                      не загрузилась само изображение и.т.д.

(video) - аналогично для видео. Нужен закрывающие тэг, но атрибуты внутри первого. Атрибуты: src, width, height, controls (булевой атрибут true\false, не нужен value это стандартные функции типа паузы и.т.д.) Атрибут alt не используется, т.к. ссылку на альтернативное видео не сможет воспроизвести, например. Проблема обратной совместимости.
текст между тэгами показывается только когда видео не может быть воспроизведено. 

Отличие self-closing от остальных: не могут содержать контент (т.е. между открывающим и закрывающим тэгом, атрибуты контентом не считаются). 
