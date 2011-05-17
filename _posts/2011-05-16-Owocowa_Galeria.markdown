---
layout: post
title: Owocowa Galeria
---

# {{ page.title }}
## Wersja 1

Wybieram zdjęcia i wstawiam je na stronę:

{% highlight ruby %} 
	<ul><li><a href="#nogo"> <img src="../../../../images/d1.jpg"
	 alt="Owocek1" title="Owocek1" /</a></li>
	<li><a href="#nogo"> <img src="../../../../images/d2.jpg"
	 alt="Owocek2" title="Owocek2" /></a></li>
	<li><a href="#nogo"> <img src="../../../../images/d3.jpg"
	 alt="Owocek3" title="Owocek3" /></a></li>
	<li><a href="#nogo"> <img src="../../../../images/d3.jpg" 
	alt="Owocek4" title="Owocek4" /></a></li>
	<li><a href="#nogo"> <img src="../../../../images/d5.jpg" 
	alt="Owocek5" title="Owocek5" /></a></li>
	<li><a href="#nogo"> <img src="../../../../images/d6.jpg" 
	alt="Owocek6" title="Owocek6" /></a></li>
	<li><a href="#nogo"> <img src="../../../../images/d7.jpg" 
	alt="Owocek7" title="Owocek7" /></a></li></ul>
{% endhighlight %}


<a href="../../../../strony/galeria1.html" title="Galeria wersja 1" >Galeria 1</a>

Tworzę CSS dla galerii.
Dla pewności pozycjonuję galerię do lewej. Ustawiam zdjęcia w pionowym bloku, tak aby zachodziły na siebie.

{% highlight ruby %} 
	#galeria li {
	float:left;
	}
	#galeria li a {
	display:block; 
	height:50px; 
	width:320px; 
	}
{% endhighlight %}


<a href="../../../../strony/galeria2.html" title="Galeria wersja 2" >Galeria 2</a>

Zdjęcia zostają ściśnięte do bardziej kompaktowego bloku.

{% highlight ruby %}
	#galeria li a img {
	height:50px;
	width:320px;
	border:0;
	}
{% endhighlight %}


<a href="../../../../strony/galeria3.html" title="Galeria wersja 3" >Galeria 3</a>

Przygotowuję miejsce do wyświetlania zdjęć. 
Wyrzucam kropki wypunktowujące listę. 
Dodaję cienką ramkę. 
Pozycjonuję galerię.

{% highlight ruby %} 
	#galeria {
  	padding:0; 
  	margin-left: 150px; 
  	list-style-type:none;  
  	width:320px; 
 	 height:545px; 
  	border:1px solid #72677C; 
  	}
{% endhighlight %}


<a href="../../../../strony/galeria4.html" title="Galeria wersja 4" >Galeria 4</a>

Dodaję rozwinięcie białego tła po wskazaniu myszką i rozwinięcie zdjęcia w tym miejscu.
Dodaję też odpowiednio dopasowane zdjęcie jako tło w do tej pory białej ramce.

{% highlight ruby %}
	#galeria li a:hover {
	background:#eee; 
	height:239px;
	}
	#galeria li a:hover img {
	height:239px;
	}
	#galeria {
	background:#fff url(images/d10.jpg);
  	}
{% endhighlight %}


<a href="../../../../strony/galeria5.html" title="Galeria wersja 5" >Galeria 5</a>

