---
layout: "post"
title: "Несколько галерей"
subtitle: "Пост с несколькими галереями, организованными с помощью ISOTOPE"
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
---


<html class="no-js" lang="en">
<head>
	<meta content="charset=utf-8">
</head>

    <body>

<section id="content" role="main">
		<div class="wrapper">
	<br><br>
			<h2>{{page.title}}</h2>




<p> Содержание вашего сообщения находится ЗДЕСЬ </p>

<p> Добавьте столько абзацев среди своих галерей, сколько хотите. </p>


           <!-- Gallery __-->
			
{% include subgallery.html id="gallery1" %}

<!-- end of GALLERY __ -->

<p> Добавьте столько галерей, сколько хотите, включая столько фотографий, сколько хотите. Просто отредактируйте <b>FRONT MATTER</b> поста, добавив соответствующий <b>путь</b>, <b>подпись</b> и <b>копирайт</b> информацию для каждой из ваших фотографий. </p>

           <!-- Gallery __-->
			
{% include subgallery.html id="gallery2" %}

<!-- end of GALLERY __ -->

		</div><!-- end of WRAPPER __ -->
	</section>


Фотография взята с: <a href="https://unsplash.com/photos/j0g8taxHZa0">UNSPLASH</a>
