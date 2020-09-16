# RESUME

### 1. My photo, First Name, Last Name
![Photo: Anastasiia Stepakhina](https://telleq.github.io/rsschool-cv/img/photo.jpg)

__Anastasiia Stepakhina__

### 2. Contact info

* *E-mail*: STEP.Nst@gmail.com
* *Telegram*: @yenast
* *LinkedIn*: Anastasiia Stepakhina

### 3. Summary

All my life I wanted to start programming, while studying at school, I was studied the design and layout of sites on ucoz service, but later abandoned it. For the last year my life has changed a lot and I have been doing self-development in front-end. I have a great wish for learning front-end develop, and i am doiing all for this. I can on my own find information in Internet, I can quickly master many information.

### 4. Skills

* HTML&CSS
* Basics knowledge
  * JavaScript
  * Grid
  * Git
* Bootstrap
* Zeplin
* Marsy
* Plugins jQuery
  * jQueryUI
  * jQuery Slick
* Soft
  * Figma
  * Adobe Photoshop
  * Adobe Illustrator
  * Visual Studio Code

### 5. Code

```
<!DOCTYPE html>
	<html lang="en">
	<head>
	<meta charset="UTF-8">
	<title>Списки</title>
	<link rel="stylesheet" href="css/reset.css">
	<link rel="shortcut icon" type="image/png" href="img/favicon.png">
	<link href="https://fonts.googleapis.com/css2?family=Source+Serif+Pro:ital,wght@0,400;0,700;1,300&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="css/all.css">
	<link rel="stylesheet" href="style.css">
	<style>
	
	@font-face {
	font-family: Caveat;
	src: url("css/fonts/Caveat-Regular.woff") format("woff"), url("css/fonts/Caveat-Regular.ttf") format("ttf");
	}
	
	html {
	font-size: 39,0625%;
	}
	
	h1 {
	font-family: "Source Serif Pro";
	font-size: 20px;
	color: #CDDC39;
	}
	
	h2 {
	list-style-type: none; 
	color: #212121;
	font-family: "Caveat";
	font-size: 22px;
	text-shadow: -2px 0px 3px#B2EBF2;
	}
	
	body {
	font-family: "Source Serif Pro", serif;
	max-width: 1200px;
	margin: 0 auto;
	background-color: #0097A7;
	color: #FFFFFF;
	font-size: 14px;
	}
	
	.up {
	color: #B2EBF2;
	position: fixed;
	bottom: 10px;
	left: 20px;
	display: none;
	font-size: 50px;
	}
	
	.up:hover {color: #CDDC39;}
	
	/* Навигационное меню */
	header {
	width: 100%;
	display: flex;
	flex-wrap: wrap; /*перенос строки */
	justify-content: flex-start; /*прижимает содержимое к краям */
	align-items: center; /*выравнивает элементы по центру на вертикальной */
	box-sizing: border-box;
	list-style: none;
	margin: 0;
	padding: 0;
	}
	
	header .home {
	padding-right: 20px;
	padding-bottom: 10px;
	}
	
	.home .fa-home {
	padding-right: 10px;
	}
	
	.dropbtn {
	width: 400px;
	height: 50px;
	background-color: #B2EBF2;
	color: #0097A7;
	font-size: 16px;
	text-transform: uppercase;
	border: none;
	font-weight: bold;
	}
	
	.dropdown {
	position: relative;
	padding: 15px 0px 30px 0px;
	}
	
	#icon {
	color: #B2EBF2;
	font-size: 28px;
	
	}
	
	#icon:hover {color: #CDDC39;}
	
	.dropdown-content {
	display: none;
	position: absolute;
	background-color: #B2EBF2;
	min-width: 190px;
	box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
	z-index: 1;
	font-size: 16px;
	}
	
	.dropdown-content .current {
	color: #212121;
	padding-left: 10px;  
	}
	
	.dropdown-content a {
	color: #0097A7;
	padding: 12px 16px;
	text-decoration: none;
	display: block;
	}
	
	.dropdown-content a:hover {background-color: #CDDC39; color: #0097A7; cursor: pointer;}
	
	.dropdown:hover .dropdown-content {display: block;}
	
	.dropdown:hover .dropbtn {background-color: #CDDC39; color: #0097A7;}
	
	kbd {
	border: 1px solid;
	border-radius: 5px;
	padding: 3px;
	color: white;
	background-color: #757575;
	}
	
	dt {
	font-style: italic;
	font-weight: bold;
	}
	
	code {
	color: #00BCD4;
	padding: 2px 2px;
	background-color: #212121;
	border: 1px solid;
	}
	
	</style>
	</head>
	<body>
	<header>
	
	 <div class="home">
		<a href="index.html" target="Перейдете на головну сторінку"><i class="fa fa-home" id="icon"></i></a>
		<a href="form.html" target="Реєстрація"><i class="fa fa-user-astronaut" id="icon"></i></a>
	 </div>
	
	 <div class="dropdown">
		<button class="dropbtn">Знайомство з HTML і CSS</button>
		<div class="dropdown-content">
		  <a href="pochatok.html" target="Знайомство з тегами, атрибутами тегів">Знайомство з тегами, атрибутами тегів</a>
		  <a href="http://cpto.dp.ua/public_html/posibnyky/basic_html/urok1.html" target="Структура HTML документа">Структура HTML документа</a>
		  <a href="http://cpto.dp.ua/public_html/posibnyky/basic_html/urok1.html" target="Розмітка тексту">Розмітка тексту</a>
		  <a href="lists.html" target="Списки" title="Списки">Списки</a>
		  <a href="tabs.html" target="Таблиці" title="Самостійне створення таблиць">Таблиці</a>
		</div>
	 </div>
	 
	 <div class="dropdown">
		<button class="dropbtn">Мультимедіа та гіперпосилання</button>
		<div class="dropdown-content">
		  <b class="current">Гіперпосилання</b> 
		  <a href="picture.html" target="Графічні зображення" title="Додавання зображень на сайт">Графічні зображення</a> 
		  <a href="media.html" target="Відео та звук">Відео та звук</a> 
		</div>
	 </div>
	</header>
	
	<h1>Теги для розмітки таблиць</h1>
	<h2>Для чого веб розробники використовують таблиці</h2>
	<p>
	Тривалий час таблиці використовувались для розташування елементів вебсторінки. З розвитком HTML i CSS таблиці повернули собі свою сутність і використовуються для структурованого розташування на вебсторінці
	<ul>
	 <li>текстової інформації</li>
	 <li>числової інформації</li>
	 <li>зображень</li>
	 <li>гіперпосилань</li>
	 <li>інших таблиц, тощо</li>
	</ul>
	</p>
	
	<h2>Один зі способів додати таблицю на вебсторінку</h2>
	<ol start="3" type = "A">
	 <li>  Додайте в <code>html</code>-код теги <code>&lt;table&gt;&lt;/table&gt;</code></li>
	 <li>Встановіть курсор між ними, додайте код <code>tr*n</code> і натисніть <kbd>Tab</kbd>; <code>n</code> &minus; це число рядків у таблиці</li>
	 <li>Встановіть курсор між тегами, які позначають рядок шапки таблиці, додайте <code>th*n</code> і натисніть <kbd>Tab</kbd>; тут <code>n</code> &minus; це число клітинок у першому рядку таблиці</li>
	 <li>Аналогічно додайте клітинки <code>&lt;td&gt;&lt;/td&gt;</code> у наступні рядки</li>
	 <li>Заповніть клітинки контентом</li>
	</ol>
	
	<h2>Деякі інші теги</h2>
	<dl>
	 <dt><code>&lt;caption&gt;</code></dt>
		<dd>− парний тег, додає назву таблиці, розташовується відразу за тегом <code>&lt;table&gt;</code></dd>
	 <dt><code>&lt;col&gt;</code></dt>
		<dd>− одиночний тег, задає ширину і інші характеристики однієї або декількох колонок таблиці; при наявності цього тега браузер починає показувати вміст таблиці, не чекаючи її повного завантаження; можна використовувати спільно з тегом &lt;colgroup&gt;, який задає групу колонок зі спільними властивостями.</dd>
	 <dt><code>&lt;thead&gt;, &lt;tbody&gt;, &lt;tfoot&gt;</code></dt>
		<dd>−парні теги, які огортають рядки відповідно  верхнього колонтитула (шапки), основної частини та нижнього колонтитула (підсумкового рядка) таблиці.</dd>
	</dl>
	
	<h2>Ответы на контрольные вопросы:</h2>
	<p>1. Для создания списков используются теги <code>&lt;ul&gt;</code> (маркированный список), <code>&lt;ol&gt;</code> (нумерованый список), <code>&lt;dl&gt;</code> (помещает в себе 2 элемента - термин и значение).</p>
	<p>2. <code>&lt;type&gt;</code> - устанавливает вид маркера списка. <code>&lt;start&gt;</code> - задаёт число, с которого будет начинаться нумерованный список.</p>
	<p>3. Необходимо использовать атрибут <code>&lt;start&gt;</code>.</p>
	<p>4. Используется атрибут <code>&lt;type&gt;</code>.</p>
	<p>5. Можно использовать <code>&lt;dl&gt;</code>, для выделения термина использовать <code>&lt;dt&gt;</code>, для определения термина <code>&lt;dd&gt;</code>.</p>
	
	<a href="lists.html#start" class="up" style="display: inline;"><i class="fa fa-angle-double-up"></i><!-- <img src="/img/arrow.png" alt="Стрелка для перемещения в самый верх сайта" height="80px"> --></a>
	</body>
	</html>
```

### 6. Education

Period | Place
------------ | -------------
2011 - 2014  | "Radio Instrument-Making College", specialty "Radio Engineering", honors degree.
2014 - 2017| "Kyiv State University of Telecommunications", specialty "Information Networks", bachelor's degree.
2020|Additional education: Courses on the website www.udemy.com - "WEB-developer 2020".

### 7. English

My level is A2, courses by Friends English Club.
