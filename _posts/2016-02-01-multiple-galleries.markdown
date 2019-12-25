---
layout: "post"
title: "Несколько галерей"
subtitle: "Краткое описание всех галерей"
active: "journal"
image:
  feature: "pc007.jpg"
date: "2016-02-01"
header-img: "img/postcover/pc007.jpg"
comments: "true"
gallery1: 
  - image_path: /img/galleries/g01/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g01/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g01/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson 
gallery2: 
  - image_path: /img/galleries/g02/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g02/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g02/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson 
gallery3: 
  - image_path: /img/galleries/g03/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g03/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g03/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson 
gallery4: 
  - image_path: /img/galleries/g04/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g04/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g04/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
gallery5: 
  - image_path: /img/galleries/g05/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g05/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g05/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson 
gallery6: 
  - image_path: /img/galleries/g06/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g06/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g06/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson 
gallery7: 
  - image_path: /img/galleries/g07/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g07/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g07/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson 
gallery8: 
  - image_path: /img/galleries/g08/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g08/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g08/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
gallery9: 
  - image_path: /img/galleries/g09/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g09/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g09/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson 
gallery10: 
  - image_path: /img/galleries/g10/bg1.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g10/bg2.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
  - image_path: /img/galleries/g10/bg3.jpg
    image-caption: Название фотографии
    image-copyright: © kiranderson
---


<html class="no-js" lang="en">
<head>
	<meta content="charset=utf-8">
</head>

    <body>

<section id="content" role="main">
		<div class="wrapper">
	<br><br>
			<h1>{{page.title}}</h1>



<br>
<h2> Театральные артисты. Интервью в РИАНОВОСТЯХ</h2>
<br>

           <!-- Gallery __-->
			
{% include subgallery.html id="gallery1" %}

<!-- end of GALLERY __ -->

<p> Добавьте столько галерей, сколько хотите, включая столько фотографий, сколько хотите. Просто отредактируйте <b>FRONT MATTER</b> поста, добавив соответствующий <b>путь</b>, <b>подпись</b> и <b>копирайт</b> информацию для каждой из ваших фотографий. </p>

<h2>Ресторанная еда</h2>
<br>
           <!-- Gallery __-->
			
{% include subgallery.html id="gallery2" %}

<!-- end of GALLERY __ -->

<h2>Сёрфингист на тренировке</h2>
<br>
{% include subgallery.html id="gallery3" %}

<h2>Интерьер квартиры</h2>
<br>
{% include subgallery.html id="gallery4" %}

<h2>Город Коломна</h2>
<br>
{% include subgallery.html id="gallery5" %}

<h2>Мурманская область</h2>
<br>
{% include subgallery.html id="gallery6" %}

<h2>Репортаж с мероприятия</h2>
<br>
{% include subgallery.html id="gallery7" %}

<h2>Ресторан</h2>
<br>
{% include subgallery.html id="gallery8" %}

<h2>Женские сумки</h2>
<br>
{% include subgallery.html id="gallery9" %}

<h2>Будни безопасности</h2>
<br>
{% include subgallery.html id="gallery10" %}

		</div><!-- end of WRAPPER __ -->
	</section>


