<h3 align="center"><img src="https://bilgeis.net/assets/images/product/product/web-tasariminin-temelleri-html-ve-css_1.jpg"/></h3>
<h2>HTML'e Giriş</h2>
<p>HTML, Hyper Text Markup Language ifadesinden oluşturulmuş bir İngilizce kısaltmadır ve Türkçe'ye "Hiper Metin İşaretleme Dili" şeklinde çevrilebilir. Bir işaretleme dilinin temel işlevi, bir belge içindeki metnin (text) yapısını, biçimini ve genel görünümünü tanımlayacak kuralları içermesi ve bunun uygulanmasına olanak vermesidir.</p>
<p>İşaretleme dilinin kuralları belgeye yüklendikten sonra doğal olarak belge, bu kuralları okuyup nasıl uygulayacağını bilen bir bilgisayar programı tarafından işlenmelidir. Burada oluşturulan HTML içerikleri tarayıcılar tarafından anlamlaştırılarak, gördüğümüz web sitelerinin temelini oluştururlar.</p>
<p>HTML öğrenebilmeniz için herhangi bir metin editörünü kullanmanız yeterlidir. Bu noktada size Sublime Text, Brackets ve Notepad++ gibi bazı başarılı metin editörlerini önerebiliriz. Bu editörler, HTML kodlarını yazarak bir web sitesi inşa etmek için kullanılmaktadır. Bunun dışında, görsel olarak da bir web sitesi oluşturmak mümkündür. Bunun için Microsoft Expression Web, Adobe Dreamweaver ve BlueGriffon gibi farklı araçlar kullanılabilir.</p>
<p>Bu tür uygulamalar, görsel olarak yapmış olduğunuz işlemleri, arkaplanda HTML koduna dönüştürmektedir. Dilerseniz, Web Programlama kursunu tamamladıktan sonra, WYSIWYG uygulamaları kullanarak web sitenizi geliştirebilirsiniz. Ancak; HTML kodlamayı iyi bir şekilde öğrenmek için ilk etapta bu uygulamaları kullanmamanızı, HTML kod vurgulama özelliğine sahip metin editörleri kullanmanızı tavsiye ederiz.</p>
<p>HTML dosyalarının çalıştırılması için oluşturduğunuz dosyaların sonuna .html uzantısı eklemeniz ve bir internet tarayıcısı üzerinde açmanız yeterli olacaktır. Böylelikle yazmış olduğunuz HTML kodları ile oluşturduğunuz web sitesini görüntüleyebilirsiniz.</p>
<p>HTML derslerine başlamadan önce, az önce anlattığımız olayı basit bir örnekle gösterelim:

Öncelikle istediğiniz bir metin editörünü açın ve aşağıdaki kodları yazın.{html taglari arasinda, head taglari arasinda, meta charset="utf-8", body taglari arasinda "Hello World!" metininin ekrana ciktisi sadece Hello World! seklinde olacaktir.}<html>
<head>
<meta charset="utf-8">
</head>
<body>
Hello World!
</body>
</html></p>

<p>Daha sonra oluşturduğunuz bu dosyayı kaydedin. Açılan diyalog penceresinde, dosya isminin sonuna .html uzantısını ekleyin. Böylelikle dosyanın bir metin dosyası değil, html dosyası olduğunu belirtmiş olduk.</p>
<p>Oluşturduğunuz html dosyasına çift tıklayın ve favori web tarayıcınızda çalıştırın.</p>
<h2>HTML sürümleri</h2>
<br>Sürüm -> Yıl
<br>HTML -> 1991
<br>HTML 2.0 -> 1995
<br>HTML 3.2 -> 1997
<br>HTML 4.01 -> 1999
<br>XHTML -> 2000
<br>HTML5 -> 2014
<h2>Bir HTML Belgesinin Yapısı</h2>
<p>Bir HTML belgesi etiket dediğimiz bileşenlerden oluşur. HTML yapısındaki temel bileşen bir elemandır. Elemanları anlatmak için her gün gördüğünüz başlıklar, paragraflar, listeler birer elemandır. Etiketler kullanılarak bu elemanlar birbirinden ayrılarak mantıklı hale gelirler. HTML etiketleri yapısı ise çok basittir. < (küçüktür işareti) etiket ve > (büyüktür işareti) işaretiyle belirtilir. Örneğin, paragraf belirtmek için p etiketini kullanırız. Paragraf etiketini kapatmak istediğimizdeyse < işareti sonrasında / işareti koymak yeterlidir.</p>
<p>HTML dili büyük küçük ayrımı yapan bir dil değildir. Bir etiketi girerken büyük, küçük ya da bir kısmı büyük bir kısmı küçük girebilirsiniz (XHTML için durum farklıdır. Tüm etiketlerin küçük harflerle yazılması gerekir) ve bu herhangi bir değişime sebep olmaz. Ancak; HTML sayfası içindeki tüm kodların küçük harfle yazılması, geliştiriciler arasında kabul görmüş bir kuraldır. Dolayısıyla etiketleri küçük harfle yazmanız tavsiye edilir.</p>
<p>Bir HTML belgesi başlıca iki kısımdan oluşur:<br>Baş (HEAD) metni<br>Gövde (BODY) metni<br>Baş metni, sayfaya ait başlıkla ilişkili ifadeleri içerir.<br>Gövde metni ise, HTML koduna ait asıl metni içerir. Bu metin,<br>Paragraflar,<br>Listeler ve <br>Diğer elemanlardan oluşur.</p>
<p>Genel olarak buraya kadar anlatılanları bir çatı altında toplayacak olursak:</p>
<p>Tüm HTML belgeleri tip deklerasyonu ile başlamak zorundadır: ! DOCTYPE html
HTML belgeleri, html etiketi ile başlar ve /html etiketi ile biter.
HTML belgesi içindeki görüntülenen kısım ise body ve /body etiketleri arasında yer alır.
<p>!DOCTYPE html Aşağıda basit bir HTML dosyası örneğini bulabilirsiniz.</p>
html
  head
    titleBasit bir HTML metni başlığı/title
    meta charset="utf-8"
  /head
  body
    h1 HTML, Web'in dilidir./h1
    P Bu metnin ilk paragrafıdır. /p
    p Bu da ikinci paragraftır. /p
  /body
/html
</p>
<p>!DOCTYPE> deklerasyonu
DOCTYPE deklerasyonu, web tarayıcıların bir web sitesini doğru bir şekilde göstermesini sağlamaktadır. Web üzerinde farklı belge tipleri bulunmaktadır:
HTML5
<!DOCTYPE html>
HTML 4.01
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
XHTML 1.0
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"></p>
<h2>En Temel HTML Etiket ve Anlamları</h2>
 - HTML etiketi<br>
 HTML etiketi, tarayıcınıza, dosyanın HTML kodu ile yüklenmiş bilgi içerdiğini bildirir. Dosya adındaki .html uzantısı ise bu dosyanın bir HTML belgesi olduğunu belirtir.
 - HEAD etiketi<br>
 Bir HTML belgesinin ilk kısmını belirler. İçinde TITLE elemanının bulunması zorunludur. Belgenin başlığını TITLE elemanı belirler.
 - TITLE etiketi<br>
 TITLE etiketi yardımıyla oluşturduğunuz web sayfasının başlığını belirleyebilirsiniz. Bu başlık, yukarıda görüldüğü gibi, başlık çubuğu üzerinde görüntülenecektir.
<br> Başlık içeriği, sayfanın içeriği ve işlevi ile uyumlu olmalıdır. Sayfayı tanımlayıcı nitelikte ve kısa olmalıdır.
 - META etiketi<br>
 Meta etiketiyle sayfanızın bir tanımını yapabilir ve sayfa içeriğini uygun anahtar sözcüklerle tanımlayabilirsiniz.<br>
 <h4>Bazı önemli meta etiketleri ve açıklamaları şu şekildedir:</h4><br>
  1) Keywords: Sitenizin içeriğini oluşturan kelimelerin bulunduğu etikettir.<br>
  2) Description: Bu etiket site hakkında bilgi veren temel etiketlerden biridir.<br>
  3) Author: Site yapımcısının adı, iletişim bilgilerinin bulunduğu etikettir.<br>
 - BODY etiketi
 HTML belgenizin ikinci ve en uzun parçası BODY kısmıdır. Belgenizin tüm içeriği burada yer alacaktır. Bir sonraki belgede açıklanan etiketlerin tümü BODY içinde yer  alacaktır.<br>
 <h5>Body İçerisinde Yer Alan Temel HTML Etiketleri</h5>
 - Başlıklar (Headings)<br>
 HTML metni içinde H1 ile H6 aralığında ölçeklendirilmiş 6 farklı düzeyde başlık kullanılabilir. Burada H1 en büyük başlığı, H6 ise en küçük başlığı simgelemektedir.
 <br>Bir başlık elemanının genel yazılış biçimi,<br><Hx>Başlık Metni</Hx> şeklindedir. Burada x, 1 ile 6 arasında bir tamsayıdır ve başlığın düzeyini belirlemektedir.  <br>HTML kodunuz içinde başlık düzeylerini atlatmamaya dikkat ediniz. Örneğin H1 ile başlayıp daha sonra H4'ü kullanmayın. Düzeyler birbirini sırasıyla izlemesi, arama motorları tarafından daha iyi bir konumda endekslenmeniz için de önemlidir.
 <h4>Paragraflar (Paragraphs)</h4>
Oluşturacağınız Web sayfası üzerine yerleştireceğiniz metni ayrı paragraflar şeklinde ifade etmek için p  ve /p etiketlerini kullanmalısınız.<br>
 - Listeler (Lists)<br>
 HTML, çeşitli türlerde listelerin oluşturulabilmesine olanak sağlar. Bu liste türleri,<br>
   - Numaralanmamış liste<br>
   - Numaralanmış liste<br>
   - Tanım listesi<br>
   şeklindedir.
<h5>Numaralanmamış liste</h5>
Numaralanmamış listeyi oluşturmak için ul ve /ul etiketleri kullanılır. Bu etiketler arasına liste elemanlarını yerleştirmek için <li> etiketi kullanılır. Bu etiketi izleyen yere liste elemanı yerleştirilmelidir. li etiketinin /li etiketiyle kapatılması zorunlu değildir.<br>
<h5>İç İçe Listeler</h5>
Listeleri iç içe de kullanabilirsiniz. Hatta, tek bir liste kalemi içinde iç içe listeler içeren paragraflar da düzenleyebilirsiniz.<br>
Ornek:{syntax'in belli olmasi icin alttaki taglari cevreleyen "< >" silinmistir.!!}<br> 
html
  head
    title TÜRKİYE'DE BÜYÜK ŞEHİRLER VE İLÇELER /title
  /head
  body   
      h3 TÜRKİYE-ŞEHİRLER /h3
       ul
          li ISTANBUL'UN ÖNEMLİ İLÇELERİ /li
              ul
                 li Fatih /li
                 li Bakırköy /li
                 li Kadıköy /li
              /ul
          li ANKARA'NIN ÖNEMLİ İLÇELERİ /li
              ul
                li Çankaya /li
                li Yenimahalle /li
        /ul
    /ul
  /body
/html
<p>
  <html>
  <head>
    <title>TÜRKİYE'DE BÜYÜK ŞEHİRLER VE İLÇELER</title>
  </head>
  <body>   
      <h4>TÜRKİYE-ŞEHİRLER</h4>
       <ul>
          <li>ISTANBUL'UN ÖNEMLİ İLÇELERİ</li>
              <ul>
                 <li>Fatih</li>
                 <li>Bakırköy</li>
                 <li>Kadıköy</li>
              </ul>
          <li>ANKARA'NIN ÖNEMLİ İLÇELERİ</li>
              <ul>
                <li>Çankaya</li>
                <li>Yenimahalle</li>
        </ul>
    </ul>
  </body>
 </html>
</p>
<h4>Çok Kullanılan Body Etiketleri</h4>
<ul>
<h5><li> pre etiketi</li></h5>
<h5><li> br etiketI</li></h5>
<h5><li> hr etiketi</li></h5>
<h5><li> s ve strike etiketleri</li></h5>
<h5><li> strong etiketi</li></h5>
<h5><li> u etiketi</li></h5>
</ul>
<p>Sabit genişlikli bir yazıtipi içinde bir metin oluşturmak istediğiniz takdirde, HTML'in " pre /pre (elmaslar icinde yazacak sekilde<>)" etiketini kullanabilirsiniz. pre terimi, İngilizce preformatted (önceden biçimlendirilmiş) sözcüğünden alınmıştır.Bu etiket ayrıca metin içindeki boşlukları, satır başlarını ve tab'ları da anlamlı hale getirir.</p>
<p>pre etiketi, width özelliğiyle birlikte kullanılarak bir satır içinde yer alabilecek en fazla karakter sayısı da belirlenebilir.pre /pre etiketleri arasında hiperlinkler (hyperlink) kullanılabilir.Bununla birlikte, pre /pre etiketleri arasında, diğer etiketlerin kullanılmasından kaçınmak gerekir.</p>
<p>Aşağıdaki örnekte ülkeler ve nüfusları önceden belirlenmiş bir biçimde web sayfası üzerine yerleştirilmek isteniyor.HTML kodunda ilerde daha ayrıntılı olarak ele alacağımız hiperlink oluşturma ve bu bağlantı tıklandığı takdirde buna bağlı dosyayı ekranda görüntülemeyle ilişkili küçük bir örnek de yer almaktadır.</p>
<p>Aşağıdaki HTML kodu çağrılınca ekranda alt çizgili ve mavi renkte bir "DAHA FAZLA BİLGİ İÇİN" ifadesi belirecektir.Bu bir hiperlink'tir ve tıklandığında X.htm dosyası çağrılmaktadır.</p>
pre etiketinin kullanımını hiperlink ile birlikte anlatan örneğimiz aşağıdadır:<br>
<p>
  <html>
  <head>
  <meta charset="UTF-8">
  </head>
<body> 
  <h3>ÜLKELER VE NÜFUSLARI</h3>
    <h4>TÜRKİYE-ŞEHİRLER</h4>
  </body>
    </html>
    </p>
<pre>
ÜLKE ADI       NÜFUSU (MİLYON KİŞİ)
TÜRKİYE           65  
AVUSTURYA         8
ABD               230
ALMANYA           80
<a href="X.htm">DAHA FAZLA BİLGİ İÇİN</a>
</pre>
<p>Yukardaki sayfa ekrana geldiği zaman, fareyle DAHA FAZLA BİLGİ İÇİN hiperlinkini tıkladığınızda, X.htm adlı HTML dosyası çağırılacaktır.</p>
Aşağıda ise, X.htm adlı HTML dosyasının içeriği görülmektedir:<br>
<pre>
    <html>
     <head>
      <meta charset="UTF-8">
      ÜLKELER VE NÜFUSLARI
     </head>
     <body>
      <h3>TÜRKİYE-ŞEHİRLER</h3>
      <h3>ÜLKELER VE NÜFUSLARI</h3>
       <pre>
        ÜLKE ADI       NÜFUSU (MİLYON KİŞİ)       KBMG($)     KITA
        TÜRKİYE        65                         3100        AVRUPA-ASYA          
        AVUSTURYA      8                          25000       AVRUPA
        ABD            230                        32000       KUZEY AMERİKA
        ALMANYA        80                         29000       AVRUPA
     </body>
   </html>
   </pre>
</pre>
<h5><li> br etiketI</li></h5>
br etiketi, bulunduğu konumdan itibaren bir satırı sona erdirerek yeni bir satırın başına geçilmesini sağlar.<br>
Aşağıdaki örnek kod incelenerek br etiketinin kullanımı görülebilir:<br>
<html>
  <head>
  <meta charset="UTF-8">
  <title>ÜLKELER VE NÜFUSLARI</title>
    </head>
  <body>   
    <h3>ÜLKELER VE NÜFUSLARI</h3>
   <p>Avusturya 8 milyon nüfuslu bir Orta Avrupa <br>ülkesidir.
   Almanca resmi dilidir. Doğası itibariyle <br>dünyanın en güzel 
ülkelerinden biridir.</p>
  <p>Macaristan bir diğer Orta Avrupa <br>ülkesidir.
  Nüfusu 10 milyondur. Komşuları genelde dağlık <br>birer ülke 
olmalarına karşın Macaristan düz ovaları ve atlarıyla ünlüdür.</p>
    </body>
</html>

<h3> em etiketi</h3>
<p>Bir metnin istenilen kısmını belirgin hale getirmek için kullanılır.<em> ve </em> etiketleri arasındaki kısım tipik olarak italik biçimde görüntülenir.</p>
em etiketinin nasıl kullanıldığını görmek için aşağıdaki örneği inceleyelim:<br>
<html>
  <head>
  <meta charset="UTF-8">
  <title>ALGORİTMA TANIMI</title>
    </head>
  <body>   
    <dfn>ALGORİTMA </dfn>
    <p>Algoritma bir problemi çözmek için izlenmesi gereken<em> işlem adımları kümesidir.</em></p>
    </body>
</html>
em etiketi etkisindeki kısım “işlem adımları kümesidir” şeklinde italik olarak belirgin hale getirilmiştir.<br>
  <h6>s ve strike etiketleri</h6><br>
 Uygulandıkları metnin üzerine bir çizgi çizilmesini sağlarlar.<br>
 s ve strike kullanımı için aşağıdaki örneği inceleyebilirsiniz:<br>
<html>
  <head>
  <meta charset="UTF-8">
  <title>title taglari arasi</title>
    </head>
  <body>
    <h3>TEKNOKRATLAR</h3> 
     <s>Bütün mimarlar</s> yüksek, mühendisler de <br>
     Bir sen kaldın<strike> alçak mimar</strike> ey Sinan Usta!<br>
     Cemal Süreya<br>
    </body>
  </html>
<h6>strong etiketi</h6><br>
 İşaret edilen metni özellikle vurgulamak için kullanılır. Bu vurgulama bold (koyu) yazı karakteriyle gerçekleştirilir.<br>
strong etiketinin kullanımını aşağıdaki örnekten görebilirsiniz.<br>

<html>
  <head>
  <meta charset="UTF-8">
  <title>ÖRNEKLER</title>
    </head>
  <body>
    <h3> DİVAN EDEBİYATI </h3> 
    <dfn>FUZULİ</dfn><br><br>
    <strong>Öyle sermestemki idrak etmezem dünya nedür<br>
            Men kimem saki olan kimdür mey-i sahbah nedür</strong>
    </body>
</html>
<h6>u etiketi</h6><br>
 İşaretlediği metnin altına bir alt çizgi çekilmesini sağlar.<br>
 u etiketinin nasıl kullanıldığını aşağıdaki örnekten görebilirsiniz:<br>
<html>
  <head>
  <meta charset="UTF-8">
  <title>ÖRNEKLER</title>
    </head>
  <body>
    h3 ÖNCE uDÜRÜST/u OLUNUZ /h3 
    <h3> ÖNCE <u>DÜRÜST</u> OLUNUZ </h3> 
    h3BUNUN DIŞINDAKİ uHER ŞEY İKİNCİ PLANDADIR/u /h3 
    <h3>BUNUN DIŞINDAKİ <u>HER ŞEY İKİNCİ PLANDADIR</u> </h3> 
  </body>    
  </html>
<h3>Çeşitli Yazı Biçimlendirmeleri</h3>
  <h6>b etiketi</h6>
b ve /b etiketleri arasına alınan metin, koyu(bold) hale getirilir.<br>
b etiketinin nasıl kullanılacağını aşağıdaki örnekten görebilirsiniz.<br>
html  
<html>
  head
  <head>
    title Modern Türk Edebiyatı /title
   <title>Modern Türk Edebiyatı</title>
  /head  
  </head>
  body
  <body>
    h3Attila İlhan/h3
    <h3>Attila İlhan</h3>
    Ne b kadınlar sevdim /b ,zaten  b yoktular/b br
    Ne <b>kadınlar sevdim</b>,zaten <b>yoktular</b><br>
    Böyle bir sevmek b görülmemiştir /b
    Böyle bir sevmek <b>görülmemiştir</b>
  /body
  </body>
/html  
</html>
  <h6>i etiketi</h6>
i ve /i etiketleri arasına alınan metin, italik(eğik yazı biçimi) hale getirilir.<br>
i etiketinin nasıl kullanılacağını aşağıdaki örnekten görebilirsiniz:<br>
<html>
  <head>
    <title>Modern Türk Edebiyatı</title>
  </head>
  <body>
    <h3>Behçet Necatıgil</h3>
    Her çocuk bir b i nur topudur/i /b br
    Her çocuk bir <b><i>nur topudur</i></b><br>
    Paçavralar içine bile düşse<br>
    Bir nur topudur<br>
    <b><i>Dar çağlara</i></b> 
    gelmese<br>
    Değmese hoyrat ayaklar<br>
    Çamurlara belenmese<br>
    Her çocuk bir nur topudur<br>
  </body>
</html>
u etiketi<br>
İşaretlediği metnin altına alt çizgi çekilmesini sağlar.<br>
u etiketiyle ilgili örneğimiz aşağıdadır:<br>
<html>
  <head>
  <title>writeTitle</title>
    </head>
  <body>
    <h3>Önce <u>Dürüst</u> olunuz</h3>
    <h3>Bunun dışındaki <u>Her şey ikinci plandadır</u></h3>
  </body>
  </html></html></body>
  <h3>Link Olusturmak</h3>
  <p>HTML'in önemli özelliklerinden biri, bir metin parçası ya da bir resim üzerinden başka bir belgeye bağlantı kurabilmesidir. Bu bağlantı, link adı verilen yapılar sayesinde gerçekleştirilmektedir. Bir resim ya da metnin rengi değiştirilerek ya da metin alt çizgili hale getirilerek bu resim ya da metnin bir hipermetin linki (hypertext link) ya da sadece link olduğu belirtilir.</p>
  <p>Bir link oluşturmak için aşağıdaki adımlar izlenmelidir:</p>
  
  
  a sembolü ile başlanır.<br>
href="DosyaAdı" ifadesi yerleştirilir. Burada DosyaAdı parametresi, oluşturulan link yardımıyla çağrılacak olan dosyanın adıdır.<br>
> sembolünü yerleştiriniz.<br>
Linki oluşturacak metni giriniz.<br>
/A etiketiyle ifadeyi tamamlayınız.<br>
a href="http://gelecegiyazanlar.turkcell.com.tr" Anasayfa /a <br>
<a href="http://gelecegiyazanlar.turkcell.com.tr">Anasayfa</a> <br>
Yukarıdaki örnekte anasayfa adında bir link oluşturulmakta ve bu bağlantıya fareyle tıklandığında portalın anasayfasını çağırmaktadır. <br>



<h5>URL yapısı</h5><br>
URL, bir adres bilgisidir. Web tarayıcıya işaret edilen dosyanın nerede bulunduğunu gösterir. URL'ler, dosyaların Web ya da yerel sabit diskiniz üzerindeki yerini işaret eder.<br>

Bir URL'in genel yapısı aşağıdaki gibi üç kısımdan oluşur:<br>

 - Erişilecek olan kaynağın tipi (Web, FTP vb.)<br>
 - Sunucunun adresi<br>
 - Dosyanın yeri<br>
 Bir URL'in yazılış biçimi aşağıdaki gibidir:<br>

KaynakTipi://host.saha [:port]/yol/DosyaAdı<br>
KaynakTipi parametresi aşağıdakilerden biri olabilir:<br>

file: Yerel sisteminizdeki bir dosya adıdır. Yerel erişim söz konusudur.<br>
ftp: Erişilecek kaynak bir FTP sunucusundaki dosyadır.<br>
http: Erişilecek kaynak World Wide Web üzerindeki bir sunucuda bulunan dosyadır.<br>
 

Target özelliği<br>
Target özelliği sayesinde, bağlanan web sitesinin nerede açılacağını belirleyebilirsiniz. Örneğin adresin yeni bir sayfada açılmasını sağlamak için aşağıdaki HTML<br> kodunu girmek gerekir.<br>

<a href="http://gelecegiyazanlar.turkcell.com.tr" target="_blank">Turkcell Geleceği Yazanlar</a>
Aşağıdaki tabloda, target özelliği ile kullanabileceğiniz parametrelerin listesi yer almaktadır:<br>

Özellik	Tanım<br>
_blank 	sayfayı yeni bir pencere ya da sekmede açar.<br>
_self	sayfayı aynı çerçevede açar. (öntanımlı olan özelliktir)<br>
_parent 	sayfayı bir üst çerçevede açar.<br>
_top	sayfayı en üst çerçevede açar.<br>
