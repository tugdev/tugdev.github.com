---
layout: post
title: BOOTSTRAP GOODİES
---
Twitter Bootstrap Cms (web uygulamaları)için hızlı prototipleme ve varsayılan stil için güzel,donanımlı bir kütüphanedir.Popüler kullanıcı arayüzü bileşenleri ve etkileşimleri için HTML, CSS ve Javascript bulunuyor.

Bir önceki yazımda <a href="http://tugdev.github.com/111/BOOTSTRAP/" >Twitter-Bootstrap</a> hakkında bilgi vermiştim.

   Twitter Bootstrap javascript eklentileri ile birlikte geliyor. Ancak, sonunda, bazı ortak javascript eklentilerini datepicker gibi,eksik bulabilirsiniz. Burada birçok yararlı araçlar, eklentiler ve Twitter Bootstrap için özel olarak oluşturulan temalardan ve javascript eklentilerinden de bahsedeceğiz.
<br>
 
<li><a href="#İCON">ÖZEL TWİTTER SİMGE SETLERİ</a></li><br>
<li><a href="#DÜĞME"> BOOTSTRAP DÜĞMESİ</a></li><br>
<li><a href="#STYLE">STYLE-BOOTSTRAP </a></li><br>
<li><a href="#COLOR">COLORPİCKER</a></li><br>
<li><a href="#DATA">DATAPİCKER</a></li><br>
<li><a href="#WYSIWYG">WYSIWYG EDİTOR FOR BOOTSTRAP</a></li><br>
<li><a href="#BOOTBOX">BOOTBOX-JS</a></li><br>
<li><a href="#FONT">YAZI TİPİ</a></li><br>
<li><a href="#TEMA">TEMA VE STİLLERİ</a></li><br>




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
<img src="/images/yeni.png" name="resim" border="1" /> 
ve tıklarken butona <br> <img src="/images/yeni1.png" name="resim" border="1" />
<br>
<br>
ve <a href="http://www.plugolabs.com/twitter-bootstrap-button-generator/">burda </a> ise istediğiniz button şeklini,rengini,iconunu kendiniz belirliyorsunuz ve size hazır kodunu gösteriyor.Tek yapmanız gereken sayfanızda buttonu yerleştirmek istediğiniz yere sağ tarafta çıkan kodu yerleştirmek :))
<br>
<br>
###<a id="STYLE">3-STYLE-BOOTSTRAP </a>
css dosyasını en baştan kendiniz yapmak istermisiniz.Bootstrapta gördüğünüz tüm özellikleri arkaplan renginden tutunda button rengine kadar css kodunuzu hazır oluşturmak için <a href="http://stylebootstrap.info/"> buyrun gökkuşağına:)) </a> 
Bu web sitesi kendinize özgü tasarım oluşturmanıza izin verir.Güzel bir arayüze sahip ve stilinizi hızlı bir şekilde oluşturur.bu işlemi yaptıktan sonra,sayfanın en altında bulunan butona tıklayın ,tıkladıktan sonra yeni bir sayfa gelicek ve oluşturduğunuz css dosyanızı size verecek:)
<br>
<br>
###<a id="COLOR"> 4- COLORPİCKER</a>
Bootstrap stiline uyan bir colorpicker bulunuyor.Bu eklenti kendi alanına veya herhangi bir öğeye renk seçici eklemenize izin verir ve birden fazla renk formatlarını destekler: hex, RGB, RGBA, hsl, HSLA . Bu eklentiyi kullanmak için <a href="http://www.eyecon.ro/bootstrap-colorpicker/" >bu sayfadan </a> dosyalarını indiriniz ve kendi sayfanıza include ediniz.js dosyalarının yanında js ile colorpickerı aramak lazım.<br>
<code> $('.colorpicker').colorpicker() </code>
<br>
<br>
	

	<input type="text" class="span1" value="#8fff00" id="cp1" > 
	<input type="text" class="span3" value="rgb(0,194,255,0.78)" id="cp2" data-color-format="rgba" >

	<div class="input-append color" data-color="rgb(255, 146, 180)" data-color-format="rgb" id="cp3">
		<input type="text" class="span2" value="" readonly >
		<span class="add-on"><i style="background-color: rgb(255, 146, 180)"></i></span>
	</div>


	<a href="#" class="btn small" id="cp4" data-color-format="hex" data-color="rgb(255, 255, 255)">
	arkaplan rengini değiştir</a>
<br>
<br>
<br>
<br>



	<script>
		$(function(){
			window.prettyPrint && prettyPrint()
			$('#cp1').colorpicker({
				format: 'hex'
			});
			$('#cp2').colorpicker();
			$('#cp3').colorpicker();
			var bodyStyle = $('body')[0].style;
			$('#cp4').colorpicker().on('changeColor', function(ev){
			bodyStyle.backgroundColor = ev.color.toHex();
			});

		});
	</script>
<br>
<br>
<img src="/images/colorpicker.png" name="resim" border="1" />
<br><br>
diğer yöntemlerinide bu<a href="http://www.eyecon.ro/bootstrap-colorpicker/" >adresten </a> görebilirsiniz.

<br>
ayrıca diğer bir colorpicer eklentisi için <a href="https://github.com/tkrotoff/jquery-simplecolorpicker"> bu adresten </a> bakabilirsiniz.gerçekten mükemmel:)
<br>
<br>
###<a id="DATA"> 5-DATAPİCKER </a>
Bu eklenti alanına veya herhangi bir öğe için datapicker eklemenize izin verir.Formatları:dd, d, mm, m, yyyy, yy . Bu eklentiyi kullanmak için <a href="http://www.eyecon.ro/bootstrap-datepicker/" >bu sayfadan </a> dosyalarını indiriniz ve kendi sayfanıza include ediniz.js dosyalarının yanında js ile datapickerı aramak lazım.<br>
<code> $('.datepicker').datepicker() </code>
<br>
<br>
<br>





	<input type="text" class="span2" value="02-16-2012" id="dp1" >


	<input type="text" class="span2" value="02/16/12" data-date-format="mm/dd/yy" id="dp2" >



	<div class="input-append date" id="dp3" data-date="12-02-2012" data-date-format="dd-mm-yyyy">
		<input class="span2" size="16" type="text" value="12-02-2012" readonly>
		<span class="add-on"><i class="icon-calendar"></i></span>
	</div>


	<div class="input-append date" id="dpMonths" data-date="102/2012" data-date-format="mm/yyyy" 
	data-date-viewmode="years" data-date-minviewmode="months">
		<input class="span2" size="16" type="text" value="02/2012" readonly>
		<span class="add-on"><i class="icon-calendar"></i></span>
	</div>

	<div class="alert alert-error" id="alert">
		<strong>hata var tarihi değiştirin!</strong>
	</div>
		<table class="table">
			<thead>
			<tr>
			<th>Start date<a href="#" class="btn small" id="dp4" data-date-format="yyyy-mm-dd" 
	data-date="2012-02-20">Change</a></th>
			<th>End date<a href="#" class="btn small" id="dp5" data-date-format="yyyy-mm-dd"
 	data-date="2012-02-25">Change</a></th>
			</tr>
			</thead>
			<tbody>
			<tr>
			<td id="startDate">2012-02-20</td>
			<td id="endDate">2012-02-25</td>
			</tr>
			</tbody>
			</table>




<br>
<br>



	<script>
	$(function(){
		window.prettyPrint && prettyPrint();
		$('#dp1').datepicker({
			format: 'mm-dd-yyyy'
		});
		$('#dp2').datepicker();
		$('#dp3').datepicker();
		$('#dp3').datepicker();
		$('#dpYears').datepicker();
		$('#dpMonths').datepicker();
			
			
		var startDate = new Date(2012,1,20);
		var endDate = new Date(2012,1,25);
		$('#dp4').datepicker()
			.on('changeDate', function(ev){
				if (ev.date.valueOf() > endDate.valueOf()){
					$('#alert').show().find('strong')
					.text('The start date can not be greater then the end date');
				} else {
					$('#alert').hide();
					startDate = new Date(ev.date);
					$('#startDate').text($('#dp4').data('date'));
				}
				$('#dp4').datepicker('hide');
			});
		$('#dp5').datepicker()
			.on('changeDate', function(ev){
				if (ev.date.valueOf() < startDate.valueOf()){
					$('#alert').show().find('strong')
					.text('The end date can not be less then the start date');
				} else {
					$('#alert').hide();
					endDate = new Date(ev.date);
					$('#endDate').text($('#dp5').data('date'));
				}
				$('#dp5').datepicker('hide');
			});
	});
	</script>



<br>
<br>
<img src="/images/datapicker.png" name="resim" border="1" />
<br><br>
diğer yöntemlerinide bu<a href="http://www.eyecon.ro/bootstrap-datepicker/" > adresten </a> görebilirsiniz.
<br>
<br>

###<a id="WYSIWYG"> 6- WYSIWYG EDİTOR FOR BOOTSTRAP </a>
Bootstrap-wysihtml5 <a href="https://github.com/xing/wysihtml5">wysihtml5</a> ve <a href="http://twitter.github.com/bootstrap/">Twitter Bootstrap </a>yardımıyla basit, güzel wysiwyg editörlerini oluşturmayı çok kolay bir hale getiren javascript eklentisidir.<br>

Kullanılıcaklar:)
<br>

- <a href="https://raw.github.com/jhollingworth/bootstrap-wysihtml5/master/src/bootstrap-wysihtml5.js">bootstrap-wysihtml5.js</a>

- <a href="https://raw.github.com/jhollingworth/bootstrap-wysihtml5/master/src/bootstrap-wysihtml5.css">bootstrap-wysihtml5.css</a>

- <a href="http://jhollingworth.github.com/bootstrap-wysihtml5/lib/js/wysihtml5-0.3.0.js">wysihtml5-0.3.0.js</a>
<br>
<br>

yukarıdaki bağlantıları sayfamıza include ettikten sonra 

<br>
<br>


	<textarea class="textarea" placeholder="Enter text ..." style="width: 810px; height: 200px"></textarea>


<br>
<br>


	<script>
		$('.textarea').wysihtml5();
	</script>

<br>
<br>
<img src="/images/wys-editörü.png" name="resim" border="1" />
<br>
<br>

###<a id="BOOTBOX"> 7-BOOTBOX-JS </a>
Bootbox.js Twitter'ın Bootstrap modellerini kullanarak basit programlı iletişim kutuları oluşturmaya olanak sağlayan küçük bir JavaScript kütüphanesi.küçük dendiğine bakmayın çok iyi işler başarmış. <a href="http://bootboxjs.com/">buradan</a> ulaşabilirsiniz.
"***###"


<br>
<br>
###<a id="FONT"> 8-YAZI TİPİ </a>
SVG tabanlı yazı tipi simgeleri ile mevcut simgeleri büyütmek için kullanılır..<br>
<a href="http://fortawesome.github.com/Font-Awesome/"> bu adresten </a> içeriğine bakabilirsiniz.
<br>
<br>
### <a id="TEMA">9-TEMA VE STİLLERİ </a>
<br>
- jQuery UI widget Twitter Bootstrap'a güzellik getiriyor.<a href="http://addyosmani.github.com/jquery-ui-bootstrap/">jQuery UI widget Twitter Bootstrap</a>

- CSS stilleri indirerek kolayca Twitter bootstrap tarzını değiştirin.<a href="http://bootswatch.com/">CSS stilleri-Twitter bootstrap</a>

- Tipik facebook görünüm tarzı için temel CSS ve HTML içerir. <a href="http://ckrack.github.com/fbootstrapp/">facebook-bootstrap</a>

- Twitter Bootstrap için Koyu Tema.<a href="http://danneu.com/darkstrap/darkstrap.html#">demo</a> ve <a href="http://danneu.com/posts/4-darkstrap-css-a-dark-theme-for-twitter-bootstrap-2">tema</a>

- temaları, donanımları ve diğer güzellikleri ile Twitter Bootstrap'ın tam bir sürümü.incelemenizi kesinlikle tavsiye ederim.
  - <a href="http://ajkochanowicz.github.com/Kickstrap/index.html">anasayfa</a>
  - <a href="http://getkickstrap.com/apps/">uygulamalar</a>
  - <a href="http://getkickstrap.com/themes/">temalar</a>
  - <a href="http://getkickstrap.com/docs/1.1/first-steps/">döküman</a>
  - <a href="http://getkickstrap.com/docs/1.2/extend/">eklenti geliştirme</a>
<br>
<br> 

ve diğer js eklentileri için <a href="http://www.queness.com/post/13029/extend-twitter-bootstrap-javascript-plugins">bu sayfaya</a> bakınız.
