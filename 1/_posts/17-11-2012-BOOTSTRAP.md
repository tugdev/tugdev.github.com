---
layout: post
title: BOOTSTRAP NEDİR?
---
Web uygulamalarını ve web sitelerini daha hızlı,modern bir yapıyla oluşturulmasını sağlayan çok kodlamanın hazırlanmış halidir.

CSS,HTML,formlar,düğmeler,tablolar,navigasyon,ızgaralar,uyarılar,açılır pencereler,sekmeler ve daha fazlasını arayanlar için tasarım dilinde en çok kullanılan framework uygulamasıdır.

 - Bootstrap ile CSS'ye tam anlamıyla hakim olabilirsiniz.

 - Bootstrap <a href="https://github.com/twitter/bootstrap" target="_blank" >GİTHUB </a> tarafından açık kaynak olarak geliştirilmektedir.

 - Bootstrap HTML5'in tüm özelliklerini destekler.

 - Bootstrap ile oluşturulmak istenen projeler için özel olarak tasarlanmış JQuery eklentileri vardır.

<p>TARAYICI DESTEĞİ</p>

Modern web tarayıcıları Chrome,Opera,Firefox 4+,Safari ve İnternet Explorer( :( ) versiyonları destekler.

<img src="/images/tarayıcı.png" name="resim" border="1" />


<p>yapılması gerekenler</p>

Twitter-Bootstrapı <a href="https://github.com/twitter/bootstrap" target="_blank" > GİTHUB </a> sayfasından inidirin ve klasörün içine oluşturmak istediğiniz HTML sayfasını yerleştirin.
İndirmiş oldugunuz bu depo içinde Bootstrap'ın önemli dosyaları bulunmaktadır.Bu dosyalardan yararlanabilmek için HTML sayfasına bunların include edilmesi gerekmektedir.

<code>&lt;head&gt;&lt;/head&gt;</code>

etiketleri arasına 

<code>&lt;link rel="stylesheet" href="docs/assets/css/bootstrap.css"&gt;</code>

bu ve daha kullanmak istediğimiz diğer css dosyalarını include ediyoruz.(dosya yoluna dikkat ediniz sizinki farklı olabilir.)aynı şekilde js kodlarıda;

<code>&lt;script src="js/bootstrap.min.js"&gt;&lt;/script&gt;</code>


Twitter Bootstrap, LESS'i (<a href="http://bsaral.github.com/112/Less-Css/" target="_blank" >LESS </a>) destekliyor. LESS daha hızlı ve kolay web geliştirmek için bir CSS önişlemcisidir. O yüzden less css dosyasını ve less JS dosyasını, kendi HTML sayfanızda şu şekilde include edebilirsiniz:

<code>&lt;link rel="stylesheet/less" href="less/bootstrap.less"&gt;</code>

<code>&lt;script src="/path/to/less.js"&gt;&lt;/script&gt;</code> 

<p>Hemen birkaç örnek verelim.</p>

<h5 align="center" >basit bir kodla html sayfası:</h5>
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

<h5 align="center" >vurgulu yazılar:</h5>
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

<h5 align="center" >form örneği </h5>
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


<h5 align="center" >button-tip</h5>
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

...vs vs vs .....

daha fazlası için.

- Bootstrap'ın resmi internet sitesi     <a href="http://twitter.github.com/bootstrap/" target="_blank" >buyrun </a>

- Bootstrap ile oluşturulmuş temalar <a href="http://bootswatch.com/#gallery" target="_blank" >buyrun </a>

- Bootstrap ile oluşturulmuş web sitelerine   <a href="http://builtwithbootstrap.com/" target="_blank" >buyrun </a>

- Daha detaylı bilgi için resmi blog yazısına ulaşabilirsiniz. <a href="https://dev.twitter.com/blog/bootstrap-twitter" target="_blank" >buyrun </a>

--
- Ayrıca resmi sitesinde bulunan kodları daha sade şekilde yazmaya çalıştım.kodları için github depom (depomun gh-pages dalında)<a href="https://github.com/tugdev/bootstrap/tree/gh-pages" target="_blank" >buyrun </a>

- Ve demolarını görmek için <a href="http://tugdev.github.com/bootstrap/" target="_blank" >buyrun </a>




