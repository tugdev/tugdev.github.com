---
layout: post
title: BOOTSTRAP NEDİR?
---
Web uygulamalarını ve web sitelerini daha hızlı,modern bir yapıyla oluşturulmasını sağlayan çok kodlamanın hazırlanmış halidir.

Bootstrap,Twitter'ın Apache 2 lisansıyla açık kaynak yaptığı CSS,HTML araç kiti.

CSS tarafından LESS'i kullanıyor.CSS ve JS hazır halde bulunuyor.

Tasarım dilinde en çok kullanılan framework uygulamasıdır.

<p><b>Neleri kapsıyor </b></p>
	-Button groups 
	-Button dropdowns 
	-Navigational tabs, pills, and lists 
	-Navbar 
	-Labels 
	-Badges 
	-Page headers and hero unit 
	-Thumbnails 
	-Alerts 
	-Progress bars 
	-Modals 
	-Dropdowns 
	-Tooltips 
	-Popovers 
	-Accordion 
	-Carousel 
	-Typeahead 

ve her geçen gün şaşırtıcı yeniliklerle geliyorlar. 

 - Bootstrap ile CSS'ye tam anlamıyla hakim olabilirsiniz.

 - Bootstrap <a href="https://github.com/twitter/bootstrap" target="_blank" > GİTHUB </a> tarafından açık kaynak olarak geliştirilmektedir.

 - Bootstrap HTML5'in tüm özelliklerini destekler.

 - Bootstrap ile oluşturulmak istenen projeler için özel olarak tasarlanmış JQuery eklentileri vardır.

<p><b>TARAYICI DESTEĞİ</b></p>

Modern web tarayıcıları Chrome,Opera,Firefox 4+,Safari ve İnternet Explorer( :'( ) versiyonları destekler.

<img src="/images/tarayıcı.png" name="resim" border="1" />


<p><b>yapılması gerekenler</b></p>

Twitter-Bootstrapı <a href="https://github.com/twitter/bootstrap" target="_blank" > GİTHUB </a> sayfasından inidirin ve klasörün içine oluşturmak istediğiniz HTML sayfasını yerleştirin.
İndirmiş oldugunuz bu depo içinde Bootstrap'ın önemli dosyaları bulunmaktadır.Bu dosyalardan yararlanabilmek için HTML sayfasına bunların include edilmesi gerekmektedir.

<code>&lt;head&gt; .... &lt;/head&gt;</code>

etiketleri arasına 

<code>&lt;link rel="stylesheet" href="docs/assets/css/bootstrap.css"&gt;</code>

bu ve daha kullanmak istediğimiz diğer css dosyalarını include ediyoruz.(dosya yoluna dikkat ediniz sizinki farklı olabilir.)aynı şekilde js kodlarıda;

<code>&lt;script src="js/bootstrap.min.js"&gt;&lt;/script&gt;</code>


Twitter Bootstrap, LESS'i (<a href="http://bsaral.github.com/112/Less-Css/" target="_blank" >LESS </a>) destekliyor. LESS daha hızlı ve kolay web geliştirmek için bir CSS önişlemcisidir. O yüzden less css dosyasını ve less JS dosyasını, kendi HTML sayfanızda şu şekilde include edebilirsiniz:

<code>&lt;link rel="stylesheet/less" href="less/bootstrap.less"&gt;</code>

<p><code>&lt;script src="/path/to/less.js"&gt;&lt;/script&gt;</code> </p>

<p>Hemen birkaç örnek verelim.</p>

<h5 align="center" ><b>basit bir html sayfası oluşumu</b></h5>
<br>

	<html>
	 <head>
	  <link rel="stylesheet" href="docs/assets/css/bootstrap.css">
	  <link rel="stylesheet/less" href="less/bootstrap.less">
	 </head>
	 <body>
	  <div class="container">
	   <div class="span9">
	    <div class="hero-unit">
	      <p> MERHABA DÜNYA</p>
	    </div>
	   </div>
	  </div>
	 </body>
	</html>

<br>
<br>
<img src="/images/kod.png" name="resim" border="1" />
<br>
<br>

--
<h5 align="center" ><b>vurgulu yazılar</b></h5>
<br>

	<p class="muted">sessiz.</p>
	<p class="text-warning">uyarı.</p>
	<p class="text-error">hata.</p>
	<p class="text-info">haber.</p>
	<p class="text-success">başarı.</p>
<br>
<br>

<img src="/images/vurgu.png" name="resim" border="1" />
<br>
<br>

--
<h5 align="center" ><b>form örneği</b></h5>
<br>
	<form class="form-horizontal">
		<div class="control-group">
		  <label class="control-label" for="inputEmail">Email</label>
		  <div class="controls">
		<input type="text" id="inputEmail" placeholder="Email">
		  </div>
		</div>
		<div class="control-group">
		  <label class="control-label" for="inputPassword">Password</label>
		  <div class="controls">
		<input type="password" id="inputPassword" placeholder="Password">
		  </div>
		</div>
		<div class="control-group">
		  <div class="controls">
		<label class="checkbox">
		  <input type="checkbox"> Remember me
		</label>
		<button type="submit" class="btn">Sign in</button>
		  </div>
		</div>
	  </form>

<br>
<br>
	  
<img src="/images/form.png" name="resim" border="1" />
<br>
<br>

--
<h5 align="center" >button</h5>
<br>

	<button type="button" class="btn btn-large btn-primary">Large button</button>
	<button type="button" class="btn btn-large">Large button</button>

	<button type="button" class="btn btn-primary">Default button</button>
	<button type="button" class="btn">Default button</button>

	<button type="button" class="btn btn-small btn-primary">Small button</button>
	<button type="button" class="btn btn-small">Small button</button>

	<button type="button" class="btn btn-mini btn-primary">Mini button</button>
	<button type="button" class="btn btn-mini">Mini button</button>
			 
<br>
<br>

<img src="/images/button.png" name="resim" border="1" />
<br>
<br>

...vs.....

daha fazlası için.

- Bootstrap'ın resmi internet sitesi     <a href="http://twitter.github.com/bootstrap/" target="_blank" > buyrun </a>

- Bootstrap ile oluşturulmuş temalar <a href="http://bootswatch.com/#gallery" target="_blank" > buyrun </a>

- Bootstrap ile oluşturulmuş web sitelerine   <a href="http://builtwithbootstrap.com/" target="_blank" > buyrun </a>

- Daha detaylı bilgi için resmi blog yazısına ulaşabilirsiniz. <a href="https://dev.twitter.com/blog/bootstrap-twitter" target="_blank" >buyrun </a>

--
- Ayrıca resmi sitesinde bulunan kodları daha sade şekilde yazmaya çalıştım.kodları için github depom (depomun gh-pages dalında)<a href="https://github.com/tugdev/bootstrap/tree/gh-pages" target="_blank" > buyrun </a>

- Ve demolarını görmek için <a href="http://tugdev.github.com/bootstrap/" target="_blank" > buyrun </a>

--

<p><b>kullanım alanlarından bazıları </b></p>

 - Rails ve Bootstrap   <a href="http://railsapps.github.com/twitter-bootstrap-rails.html" target="_blank" > buyrun </a>
 
	- <a href="http://railscasts.com/episodes/328-twitter-bootstrap-basics" target="_blank" > buyrun </a>

	- <a href="http://media.railscasts.com/assets/episodes/sources/328-twitter-bootstrap-basics.zip" target="_blank" > indirmek_için </a>

	- <a href="https://github.com/seyhunak/twitter-bootstrap-rails" target="_blank" > buyrun </a>

 	- <a href="http://themeforest.net/search?utf8=%E2%9C%93&term=bootstrap" target="_blank" > temalar   </a>

 - Jekyll-Bootstrap	<a href="http://jekyllbootstrap.com/" target="_blank" > buyrun </a>

 - backbone.js + Boostrap ile Örnek Uygulaması <a href="http://coenraets.org/blog/2012/02/sample-app-with-backbone-js-and-twitter-bootstrap/" target="_blank" > buyrun </a>


      -	demosu <a href="http://coenraets.org/directory" target="_blank" > buyrun </a>
	

      -	github deposu <a href="https://github.com/ccoenraets/backbone-directory" target="_blank" > buyrun </a>
	

 - Bootstrap ile hazır sistem. <a href="http://jetstrap.com/" target="_blank" > http://jetstrap.com/ </a>

 - bootstrap ile form yardımcıları  <a href="http://vincentlamanna.com/BootstrapFormHelpers/" target="_blank" > buyrun </a>
 			






