---
layout: post
title: BOOTSTRAP NEDİR?
---
Web uygulamalarını ve web sitelerini daha hızlı,modern bir yapıyla oluşturulmasını sağlayan çok kodlamanın hazırlanmış halidir.

CSS,HTML,formlar,düğmeler,tablolar,navigasyon,ızgaralar,uyarılar,açılır pencereler,sekmeler ve daha fazlasını arayanlar için tasarım dilinde en çok kullanılan framework uygulamasıdır.

 --Bootstrap ile CSS'ye tam anlamıyla hakim olabilirsiniz.

 --Bootstrap <a href="https://github.com/twitter/bootstrap" target="_blank" >GİTHUB </a> tarafından açık kaynak olarak geliştirilmektedir.

 --Bootstrap HTML5'in tüm özelliklerini destekler.

 --Bootstrap ile oluşturulmak istenen projeler için özel olarak tasarlanmış JQuery eklentileri vardır.

<p>TARAYICI DESTEĞİ</p>

Modern web tarayıcıları Chrome,Opera,Firefox 4+,Safari ve İnternet Explorer( :( ) versiyonları destekler.

<img src="/images/tarayıcı.png" name="resim" border="1" />


<p>yapılması gerekenler</p>

Twitter-Bootstrapı <a href="https://github.com/twitter/bootstrap" target="_blank" > GİTHUB </a> sayfasından inidirin ve klasörün içine oluşturmak istediğiniz HTML sayfasını yerleştirin.İndirmiş oldugunuz bu depo içinde Bootstrap'ın önemli dosyaları bulunmaktadır.Bu dosyalardan yararlanabilmek için HTML sayfasına bunların include edilmesi gerekmektedir.

<code>&lt;head&gt;&lt;/head&gt;</code>

etiketleri arasına 

<code>&lt;link rel="stylesheet" href="docs/assets/css/bootstrap.css"&gt;</code>

bu ve daha kullanmak istediğimiz diğer css dosyalarını include ediyoruz.(dosya yoluna dikkat ediniz sizinki farklı olabilir.)aynı şekilde js kodlarıda;

<code>&lt;script src="js/bootstrap.min.js"&gt;&lt;/script&gt;</code>


Twitter Bootstrap, LESS'i (<a href="http://bsaral.github.com/112/Less-Css/" target="_blank" >LESS </a>) destekliyor. LESS daha hızlı ve kolay web geliştirmek için bir CSS önişlemcisidir. O yüzden less css dosyasını ve less JS dosyasını, kendi HTML sayfanızda şu şekilde include edebilirsiniz:

<code>&lt;link rel="stylesheet/less" href="less/bootstrap.less"&gt;</code>

<code>&lt;script src="/path/to/less.js"&gt;&lt;/script&gt;</code> 

<p>Hemen birkaç örnek verelim.</p>

<b>basit bir kodla html sayfası;</b>

	<html>

	<head>
	<link rel="stylesheet" href="docs/assets/css/bootstrap.css">
	<link rel="stylesheet/less" href="less/bootstrap.less">
	</head>
	<body>
	<div class="container">
	<div class="span9">
	<div class="hero-unit">
	<p> MERHABA DÜNYA </p>
	</div>
	</div>
	</div>
	</body>
	</html>
				
			&lt;/div&gt;
			
		&lt;/div&gt;
		<!-- /container -->
		
	<code>&lt;/body&gt;
	<code>&lt;/html&gt;


<img src="/images/kod.png" name="resim" border="1" />

<b>vurgulu yazılar;</b>

		&lt;p class="muted"&gt;sessiz.&lt;/p&gt;

		&lt;p class="text-warning"&gt;uyarı.&lt;/p&gt;

		&lt;p class="text-error"&gt;hata.&lt;/p&gt;

		&lt;p class="text-info"&gt;haber.&lt;/p&gt;

		&lt;p class="text-success"&gt;başarı.&lt;/p&gt;

<img src="/images/vurgu.png" name="resim" border="1" />

<b>form örneği </p>

		&lt;form class="form-horizontal"&gt;
		  &lt;div class="control-group"&gt;
			&lt;label class="control-label" for="inputEmail"&gt;Email&lt;/label&gt;
			&lt;div class="controls"&gt;
			  &lt;input type="text" id="inputEmail" placeholder="Email"&gt;
			&lt;/div&gt;
		  &lt;/div&gt;
		  &lt;div class="control-group"&gt;
			&lt;label class="control-label" for="inputPassword"&gt;Password&lt;/label&gt;
			&lt;div class="controls"&gt;
			  &lt;input type="password" id="inputPassword" placeholder="Password"&gt;
			&lt;/div&gt;
		  &lt;/div&gt;
		  &lt;div class="control-group"&gt;
			&lt;div class="controls"&gt;
			  &lt;label class="checkbox"&gt;
				&lt;input type="checkbox"&gt; Remember me
			  &lt;/label&gt;
			  &lt;button type="submit" class="btn"&gt;Sign in&lt;/button&gt;
		   &lt;/div&gt;
		  &lt;/div&gt;
		&lt;/form&gt;

<img src="/images/form.png" name="resim" border="1" />

<b>button-tip</b>


		&lt;p&gt;
		  &lt;button class="btn btn-large btn-primary" type="button"&gt;Large button&lt;/button&gt;
		  &lt;button class="btn btn-large" type="button"&gt;Large button&lt;/button&gt;
		&lt;/p&gt;
		&lt;p&gt;
		  &lt;button class="btn btn-primary" type="button"&gt;Default button&lt;/button&gt;
		  &lt;button class="btn" type="button"&gt;Default button&lt;/button&gt;
		&lt;/p&gt;
		&lt;p&gt;
		  &lt;button class="btn btn-small btn-primary" type="button"&gt;Small button&lt;/button&gt;
		  &lt;button class="btn btn-small" type="button"&gt;Small button&lt;/button&gt;
		&lt;/p&gt;
		&lt;p&gt;
		  &lt;button class="btn btn-mini btn-primary" type="button"&gt;Mini button&lt;/button&gt;
		  &lt;button class="btn btn-mini" type="button"&gt;Mini button&lt;/button&gt;
		&lt;/p&gt;


<img src="/images/button.png" name="resim" border="1" />

...vs vs vs .....

daha fazlası için.

Bootstrap'ın resmi internet sitesi     <a href="http://twitter.github.com/bootstrap/" target="_blank" >buyrun </a>

Bootstrap ile oluşturulmuş temalar <a href="http://bootswatch.com/#gallery" target="_blank" >buyrun </a>

Bootstrap ile oluşturulmuş web sitelerine   <a href="http://builtwithbootstrap.com/" target="_blank" >buyrun </a>

Daha detaylı bilgi için resmi blog yazısına ulaşabilirsiniz. <a href="https://dev.twitter.com/blog/bootstrap-twitter" target="_blank" >buyrun </a>

ayrıca resmi sitesinde bulunan kodları daha sade şekilde yazmaya çalıştım.kodları için github depom (depomun gh-pages dalında)<a href="https://github.com/tugdev/bootstrap/tree/gh-pages" target="_blank" >buyrun </a>

ve demolarını görmek için <a href="http://tugdev.github.com/bootstrap/" target="_blank" >buyrun </a>




