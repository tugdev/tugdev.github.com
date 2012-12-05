---
layout: post
title: BOOTSTRAP GOODİES
---
Twitter Bootstrap Cms (web uygulamaları)için hızlı prototipleme ve varsayılan stil için güzel,donanımlı bir kütüphanedir.Popüler kullanıcı arayüzü bileşenleri ve etkileşimleri için basit ve esnek HTML, CSS ve Javascript bulunuyor.

Bir önceki yazımda <a href="http://tugdev.github.com/111/BOOTSTRAP/" >Twitter-Bootstrap</a> hakkında bilgi vermiştim.

   Twitter Bootstrap javascript eklentileri ile birlikte geliyor. Ancak, sonunda, bazı ortak javascript eklentileri datepicker gibi,eksik bulabilirsiniz. Burada birçok yararlı araçlar, eklentiler ve Twitter Bootstrap için özel olarak oluşturulan temalardan VE javascript eklentilerinden de bahsedeceğiz.
<br>
 
<li><a href="#İCON">ÖZEL TWİTTER SİMGE SETLERİ</a></li><br>
<li><a href="#DÜĞME"> BOOTSTRAP DÜĞMESİ</a></li><br>
<li><a href="#STYLE">STYLE-BOOTSTRAP </a></li><br>
<br>

###<a id="İCON"> 1- ÖZEL TWİTTER SİMGE SETLERİ </a>
Yapmanız gereken çok basit. <a href="http://favbulous.com/post/1006/create-custom-icons-for-twitter-bootstrap-easily"> bu sayfadan </a> indirme yapınız.

yaptıgınız klasör içinde iconlara ait bir css dosyası buluncak bunu sayfanıza include ediniz ve eger gerekliyse iconların bulundugu png dosyasının yolunu değiştirniz.
	
<code> &lt;button class="btn btn-danger"&gt;&lt;i class="cus-exclamation"&gt;&lt;/i&gt; Exclamation&lt;/button&gt; </code>

yukardaki örnekteki gibi kullanabilirsiniz.<a href="http://favbulous.com/demo/twitter-bootstrap-custom-icons/"> demosu için  </a>
<br>


	<div class="btn-toolbar">
		<div class="btn-group">
		<a class="btn" href="#"><i class="cus-text-padding-left"></i></a>
		<a class="btn" href="#"><i class="cus-text-padding-top"></i></a>
		<a class="btn" href="#"><i class="cus-text-padding-right"></i></a>
		<a class="btn" href="#"><i class="cus-text-align-justify"></i></a>	   
		</div>
	</div>


	<div class="btn-toolbar">
		<div class="btn-group">
		<a class="btn" href="#"><i class="cus-add"></i>Add</a>
		<a class="btn" href="#"><i class="cus-building-edit"></i>Edit</a>
		<a class="btn" href="#"><i class="cus-page-save"></i>Save</a>
		<a class="btn" href="#"><i class="cus-delete"></i>Delete</a>   
		</div>

	</div>


	<div>
		<button class="btn btn-primary"><i class=" cus-arrow-refresh"></i> refresh</button>
		<button class="btn btn-danger"><i class="cus-exclamation"></i> Exclamation</button>
		<button class="btn btn-success"><i class="cus-user-add"></i> user-add</button>
		<button class="btn btn-warning"><i class="cus-folder-error"></i> hata</button>
		<button class="btn btn-inverse"><i class="cus-bomb"></i> inverse</button>
		<button class="btn btn-link"><i class="cus-chart-pie-link"></i> link</button>
		<button class="btn btn"><i class="cus-tux"></i> linux</button>
	
	</div>	
<br>
<br>

<img src="/images/icons.png" name="resim" border="1" />
<br>
<br>

	<div>
	<ul class="nav nav-list">
		<li class="active"><a href="#"><i class="cus-application-home"></i> Home</a></li>
		<li><a href="#"><i class="cus-application-osx-terminal"></i> terminal</a></li>
		<li><a href="#"><i class=" cus-application-form-edit"></i> Applications</a></li>
	</ul>
	</div>
	
	<form>
	<div class="input-prepend">
		<span class="add-on"><i class="cus-email-go"></i></span>
	        <input class="span2" type="text" placeholder="Email address">
	</div>
	<div class="input-prepend">
		<span class="add-on"><i class="cus-key-go"></i></span>
	        <input class="span2" type="password" placeholder="Password">
	</div>
	</form>
<br>
<br>
<img src="/images/icons2.png" name="resim" border="1" />
<br>
<br>
###<a id="DÜĞME"> 2- BOOTSTRAP DÜĞMESİ </a>
Bu araç mevcut düğme stilini değiştirmek için özel bir düğme oluşturabilirsiniz.<a href="http://charliepark.org/bootstrap_buttons/">burada </a>sizin hassasiyetinize göre sağ tarafta oluşan classı css sayfanıza eklemek.

örneğin ben <code>btn-tugdev</code> adında class oluştudum ve bunu css sayfama ekledim;
<br>
<br>
<img src="/images/class.png" name="resim" border="1" />
<br>

<code> &lt;button class="btn btn-tugdev"&gt;&lt;i class="cus-tux"&gt;&lt;/i&gt; linux&lt;/button&gt; </code>
<br>
<img src="/images/yeni.png" name="resim" border="1" /> <br> ve tıklarken butona <br> <img src="/images/yeni1.png" name="resim" border="1" />
<br>
<br>
ve <a href="http://www.plugolabs.com/twitter-bootstrap-button-generator/">burda </a> ise istediğiniz button şeklini,rengini,iconunu kendiniz belirliyorsunuz ve size hazır kodunu gösteriyor.Tek yapmanız gereken sayfanızda buttonu yerleştirmek istediğiniz yere sağ tarafta çıkan kodu yerleştirmek :))
<br>
<br>
###<a id="STYLE">3-STYLE-BOOTSTRAP </a>
css dosyasını en baştan kendiniz yapmak istermisiniz.Bootstrapta gördüğünüz tüm özellikleri arkaplan renginden tutunda button rengine kadar css kodunuzu hazır oluşturmak için <a href="http://stylebootstrap.info/"> buyrun gökkuşağına:)) </a> 
Bu web sitesi kendinize benzersiz tasarım oluşturmak için izin verir. Bu iyi bir arayüze sahip ve yeni stilinizi hızlı bir şekilde oluşturur.bu işlemi yaptıktan sonra,sayfanın el altında bulunan butona tıklayın ,tıkladıktan sonra yeni bir sayfa gelicek ve oluşturduğunuz css dosyanızı size verecek:)
