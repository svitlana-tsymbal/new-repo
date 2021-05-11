Задание1 Оберни текст тегом h1. <h1>The main theme of the web page in the h1 header.</h1>
Задание2 Напиши html комментарий с текстом The commentary answers the question "Why is this part of the code written". <!--The commentary answers the question "Why is this part of the code written".-->
Задание3 Напиши в теге img два обязательных и два необязательных атрибута. Список атрибутов:src: файл, расположенный по относительному пути photo.jpg;alt: текст с описанием изображения Image example;width: ширина в 200 пикселей;height: height в 150 пикселей.
<img src="photo.jpg"
     alt="Image example"
     width="200"
     height="150">
Задание4 Используя теги ul и li перечисли 3 основные веб технологии. Порядок текста должен быть сохранен.
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
Візуальне відображення:
-HTML
-CSS
-JavaScript
Задание5 Оберни строчные теги button контейнерами div с классом buttons так, чтобы в двух рядах было по три кнопки и каждый ряд начинался с новой строки.Порядок элементов button должен быть сохранен.
<div class="buttons">
  <button type="button" class="button">inline</button>
  <button type="button" class="button">block</button>
  <button type="button" class="button">inline-block</button>
</div>
<div class="buttons">
<button type="button" class="button">HTML</button>
<button type="button" class="button">CSS</button>
<button type="button" class="button">JavaScript</button>
</div>
Задание6 В исходном коде присутсвует две ссылки с одним и тем же контентом - строкой Текст. У ссылок имеются названия классов - link-inline и link-block. Для первой ссылки (с классом link-inline): оберни контент ссылки - строку Текст строчным тегом span .Для второй ссылки (с классом link-block): оберни контент ссылки - строку Текст блочным тегом p для второй ссылки.Визуально убедись, что к каждой из ссылок применилось свойство inline или block.Порядок элементов a должен быть сохранен.
<div class="box">
  <a href="#" class="link-inline">
    <span>Text</span>
  </a>
  without line break
</div>
<div class="box">
  <a href="#" class="link-block">
    <p>Text</p>
  </a>
  with line break
</div>
Візуальне відображення 
Text without line break
Text
with line break
Задание7 Исправьте порядок нумерации удалив атрибут тега ol.Расставь элементы li в нужном порядке согласно описанию последовательности загрузки Номер 1 должен соответствовать первому файлу, который будет загружен. Номер 2 - второму, номер 3 - третьему.
<div class="card">
  <h4 class="card-title">The order in which files are loaded by the browser</h4>
  <ol reversed class="card-items">
    <li class="card-item">HTML file</li>
    <li class="card-item">Link to files inside head</li>
    <li class="card-item">Link to files inside body</li>
  </ol>
</div>
Задание8 Сгруппируй наборы тегов с помощью списка ul и элементов li.Тег ul должен иметь класс со значением (существительное во множественном числе) cards.Тег li должен иметь класс со значением (существительное в единственном числе) card.
<ul class="cards">
<li class="card">
<h4 class="card-title">Card title 1</h4>
<div class="wrp-img">
  <img class="card-image" src="photo.jpg" alt="image description" />
</div>
<p class="card-description">Description of the topic 1</p>
</li>
<li class="card">  
<h4 class="card-title">Card title 2</h4>
<div class="wrp-img">
  <img class="card-image" src="photo2.jpg" alt="image description" />
</div>
<p class="card-description">Description of the topic 2</p>
</li>
<li class="card">  
<h4 class="card-title">Card title 3</h4>
<div class="wrp-img">
  <img class="card-image" src="photo3.jpg" alt="image description" />
</div>
<p class="card-description">Description of the topic 3</p>
</li>
</ul>
Задание9 Ссылка должна открыться в новой вкладке. В целях безопасности надо разорвать связь между новой вкладкой и той вкладкой, где расположена ссылка.Для этого добавь ссылке необходимые значения атрибутов target и rel.
<a href="https://goit.global"
   rel="nofollow noreferrer noopener"
   target="_blank"> GoIT </a>
Задание10 Добавь ссылке атрибут, необходимый для скачивания файла. <a href="resume.pdf" download>Resume</a>
Приклад 
<!DOCTYPE html>
<html>
 <head>
  <meta charset="utf-8">
  <title>download</title>
 </head>
 <body>
  <p><a href="image/xxx.jpg">Открыть файл в браузере</a>
  <p><a href="image/xxx.jpg" download>Скачать файл</a>
</body>
</html>
Задание11 Добавь ссылкам специальные значения href.
<!-- Link to phone number  -->
<a href="tel:+14251234563">+1 (425) 123-45-63</a>
<!-- Link to e-mail address -->
<a href="mailto:example@gmail.com">example@gmail.com</a>
Задание12 Расставь значения атрибутов id для навигации по странице с помощью ссылок из aside.
<header id="top">
  <!-- content from logo, nav, search  -->
</header>
<main>
  <aside>
    <ul>
      <li><a href="#top">Top of the page</a></li>
      <li><a href="#page-theme">Main theme</a></li>
      <li><a href="#bottom">Footer of the page</a></li>
    </ul>
  </aside>
  <article id="page-theme">
    <!-- main page theme -->
  </article>
</main>
<footer id="bottom">
  <!-- content from logo, nav, contacts, copyright  -->
</footer>
Задание13 Размести теги внутри тега figure и контент внутри тега figcaption.
<figure>
<img src="photo.jpg" alt="photo description" /> 
<figcaption>Only one img element and any
number of text or other elements can be used inside link. You cannot use
  interactive elements inside link tag.</figcaption>
</figure>
Задание14 Два изображения должны быть ссылкой на одну и ту же страницу. Разместите теги правильно. Допускается добавление только одного элемента - еще одной ссылки.
<a href="./about"><img src="photo.jpg" alt="note in laptop"></a>
<a href="./about"><img src="photo2.jpg" alt="note on paper"></a>
Задание15 Текст в комментарии содержит описание структуры файлов и папок (директорий) для размещения на github.Чтобы проект отобразился как веб-страница веб-сервер github должен найти файл index.html и выполнить его. Т.е. нужен файл в которого произойдет запуск приложения (точка входа в приложение).Замени название файла hw.html, чтобы приложение начало выполняться с чтения именно этого файла.
Було 
<!--  TODO
* create project with the following structure:
images/logo.svg
css/style.css
about.html
hw.html
Відповідь:
<!--  TODO
* create project with the following structure:
images/logo.svg
css/style.css
about.html
index.html
-->Задание16 Файл about.html расположен в директории pages относительно файла index.html. Напиши для этого файла: путь для ссылки на файл index.html из файла about.html, путь для изображения на файл logo.png (Есть структура файлов и папок (директорий)
images/logo.png
pages/about.html
index.html)
Відповідь:
<!-- file about.html -->
<a href="../index.html">
  <img src="../images/logo.png" alt="logo" />
</a>
Задание17 В windows имена файлов не зависят от регистра: (cat.JPG и cat.jpg один и тот же файл). В linux имена файлов зависят от регистра: (cat.JPG и cat.jpg два разных файла)
Задание
Есть структура файлов и папок (директорий)
images/logo.png
pages/about.html
index.html
Есть код, который работает в windows, но не будет работать в linux. Исправь регистр букв в атрибутах href и src
Відповідь:
<!-- file about.html -->
<a href="../index.html">
  <img src="../images/logo.png"
       alt="logo">
</a>
(всі букви маленькі, тому що з великими не працює)