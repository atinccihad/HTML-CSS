Web sayfaları hazırlamak için kullanılan bir işaretleme dilidir. Html bir programlama dili değildir, işaretleme dilidir. (Hyper Text Markup Language)
•Html komutlarına tagdenir.
•Taglar büyüktür küçüktür işaretlerinin arasına yazılır < > Örnek: <html> <b> <u> <p>
•İstisnalar dışında tagların başlangıç ve bitişleri vardır. 
Bitiş tagları «/» işareti ile belirtilir.Örnek: <b>Merhaba</b> Nasılsın
  =============================================================================================
  Bir web sayfası oluşturmak için yapılması gerekenler
  =============================================================================================
  -Html uzantılı                       -html
   dosya oluştur                       -head
                                       -body
  =============================================================================================
  Bir web sayfasının en temel kod şablonu
<html>
<head>
<title>İlk sayfam</title>
</head>
<body>
Merhaba. Bu benim ilk web sayfam
</body>
</html>
 ==============================================================================                             
  Bir html sayfasının tarayıcılar tarafından Html5 olarak algılanabilmesi için:
  Sayfanın en üst kısmına <!doctypehtml> eklenmesi gerekir.
 ==============================================================================
 <p> : Yazıları paragraf haline getirir.
 Lorem Ipsum, adı bilinmeyen bir matbaacının bir hurufat numune kitabı oluşturmak üzere 
 bir yazı galerisini alarak karıştırdığı 1500'lerden beri 
 endüstri standardı sahte metinler olarak kullanılmıştır.
========================================================================================
<br> : Metin içinde satır başı yapmak için kullanılır
 Lorem Ipsum, adı bilinmeyen bir matbaacının bir hurufat numune kitabı oluşturmak üzere <br> 
 bir yazı galerisini alarak karıştırdığı 1500'lerden beri 
 endüstri standardı sahte metinler olarak kullanılmıştır.
 HTML kodlarken alt satıra geçmek için enter tuşuna basılmasının, 
   veya kelimeler arasında birden fazla boşluk bırakmak için space tuşuna basılmasının 
   ziyaretçi tarafında bir etkisi yoktur.
==============================================================================
 <hx> Yazıları başlık haline getirir. Standart 6 tane başlık tagı bulunmaktadır.
<h1>Başlık 1</h1>
<h2>Başlık 2</h2>
hx
head  
<h1>IT ALANINDAKİ MESLEKLER</h1>
<p>Bu yazımızda IT sektöründe uzmanlaşabileceğiniz meslekleri anlattım.</p>
<h2>Automation Engineer</h2>
<p>...</p>
<h2>Full Stack Developer</h2>
<p>.....</p>   

<hr> :  Yatay çizgi oluşturmak için kullanılır  

strong :  Metinleri kalınlaştırmak için kullanılır.
<p>Lorem Ipsum, adı bilinmeyen bir matbaacının bir <strong> hurufat numune kitabı </strong> 
  oluşturmak üzere bir yazı galerisini alarak karıştırdığı 1500'lerden beri 
  endüstri standardı sahte metinler olarak kullanılmıştır.</p>  
==============================================================================
i : Yazıyı eğik (italik) yazdırmak için kullanılır.
<i>Merhaba</i>
==============================================================================
u : Yazının altını çizmek için kullanılır.
<u>Bu yazının altını çizer</u>  
=========================================
Biçimlendirme olarak hiçbir görsel katkısı olmayan sadece html elemanlarını 
gruplamak için kullanılan taglardır.  
div :  Blok elemandır, kapladığı alan ne olursa olsun tüm satırı işgal eder.
span : Inline elemandır, sadece kapladığı alan kadar yer işgal eder.   
============================================================================
a :  Web sitelerinde,Bir sayfadan başka bir sayfaya,Farklı bir siteye,
Bağlantı vermek için <a> tagı kullanılır.
==============================================================================
img : Fotoğraf ekleme işlemleri img tagı ile yapılır.   
==============================================================================
Kullnıcıdan bilgi almak için kullanılan yapılara form denir. 
Form içinde textbox, button, radio button, checkbox vb elemanlar olabilir.
form : Tüm form elemanlarını içinde barındıran taşıyıcıdır.
input : Kullanıcıdan bilgi almak için kullanılan form elemanlarının genel ismi
label : Kullanıcıya form elemanı ile ilgili bilgi vermek için kullanılan eleman   
==============================================================================
text : Genel bilgi girişi için kullanılır
email : Sadece eposta girişlerini kabul eder 
password : Şifre girişi için kullanılır. Girilen değer gösterilmez
number : Sadece rakam girişi için kullanılır
checkbox : Birden fazla işaretleme yapılabilecek seçenekler sunar.
radio : Sadece tek seçim yapabileceği seçenekler sunar. 
    Cinsiyet gibi. Name attribute u aynı olan radio butonlar kendi aralarında 
   grup olurlar.
    file : Dosya yüklemek için kullanılır.
    select : Kullanıcıya listeden seçim yaptırmak için kullanılır. 
   Ülke, şehir gibi seçimler bu şekilde yapılır. Bunun için select tagı kullanılır. 
   Her bir seçenek ise option tagı içine konulur.  
    textarea : Çok uzun miktarda yazı girilmesini sağlayan form elemanı textarea dır. 
   Geçerli değer textarea tagları arasına yazılabilir.   
==============================================================================
    button : Genel amaç için button oluşturur. 
   Butonun default olarak bir görevi yoktur.
    submit : Form bilgilerini backend e gönderen bir buton oluşturur.
    reset : Formdaki bilgileri resetleyen bir buton oluşturur.
