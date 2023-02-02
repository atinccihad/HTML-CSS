<h3 align="center"><img src="https://miro.medium.com/max/4800/1*lJ32Bl-lHWmNMUSiSq17gQ.webp"/></h3>
<h2>HTML'e Giriş</h2>
<p>HTML, Hyper Text Markup Language ifadesinden oluşturulmuş bir İngilizce kısaltmadır ve Türkçe'ye "Hiper Metin İşaretleme Dili" şeklinde çevrilebilir. Bir işaretleme dilinin temel işlevi, bir belge içindeki metnin (text) yapısını, biçimini ve genel görünümünü tanımlayacak kuralları içermesi ve bunun uygulanmasına olanak vermesidir.</p>
<p>İşaretleme dilinin kuralları belgeye yüklendikten sonra doğal olarak belge, bu kuralları okuyup nasıl uygulayacağını bilen bir bilgisayar programı tarafından işlenmelidir. Burada oluşturulan HTML içerikleri tarayıcılar tarafından anlamlaştırılarak, gördüğümüz web sitelerinin temelini oluştururlar.</p>
<p>HTML öğrenebilmeniz için herhangi bir metin editörünü kullanmanız yeterlidir. Bu noktada size Sublime Text, Brackets ve Notepad++ gibi bazı başarılı metin editörlerini önerebiliriz. Bu editörler, HTML kodlarını yazarak bir web sitesi inşa etmek için kullanılmaktadır. Bunun dışında, görsel olarak da bir web sitesi oluşturmak mümkündür. Bunun için Microsoft Expression Web, Adobe Dreamweaver ve BlueGriffon gibi farklı araçlar kullanılabilir.</p>
<p>Bu tür uygulamalar, görsel olarak yapmış olduğunuz işlemleri, arkaplanda HTML koduna dönüştürmektedir. Dilerseniz, Web Programlama kursunu tamamladıktan sonra, WYSIWYG uygulamaları kullanarak web sitenizi geliştirebilirsiniz. Ancak; HTML kodlamayı iyi bir şekilde öğrenmek için ilk etapta bu uygulamaları kullanmamanızı, HTML kod vurgulama özelliğine sahip metin editörleri kullanmanızı tavsiye ederiz.</p>
<p>HTML dosyalarının çalıştırılması için oluşturduğunuz dosyaların sonuna .html uzantısı eklemeniz ve bir internet tarayıcısı üzerinde açmanız yeterli olacaktır. Böylelikle yazmış olduğunuz HTML kodları ile oluşturduğunuz web sitesini görüntüleyebilirsiniz.</p>
<p>HTML derslerine başlamadan önce, az önce anlattığımız olayı basit bir örnekle gösterelim:

Öncelikle istediğiniz bir metin editörünü açın ve aşağıdaki kodları yazın.{html taglari arasinda, head taglari arasinda, meta charset="utf-8", body taglari arasinda "Hello World!" metininin ekrana ciktisi sadece Hello World! seklinde olacaktir.}
<html>
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
Aşağıda basit bir HTML dosyası örneğini bulabilirsiniz.</p>
<p>!DOCTYPE html
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
HTML etiketi<br>
HTML etiketi, tarayıcınıza, dosyanın HTML kodu ile yüklenmiş bilgi içerdiğini bildirir. Dosya adındaki .html uzantısı ise bu dosyanın bir HTML belgesi olduğunu belirtir.
HEAD etiketi<br>
Bir HTML belgesinin ilk kısmını belirler. İçinde TITLE elemanının bulunması zorunludur. Belgenin başlığını TITLE elemanı belirler.
TITLE etiketi<br>
TITLE etiketi yardımıyla oluşturduğunuz web sayfasının başlığını belirleyebilirsiniz. Bu başlık, yukarıda görüldüğü gibi, başlık çubuğu üzerinde görüntülenecektir.

<br>Başlık içeriği, sayfanın içeriği ve işlevi ile uyumlu olmalıdır. Sayfayı tanımlayıcı nitelikte ve kısa olmalıdır.
META etiketi<br>
Meta etiketiyle sayfanızın bir tanımını yapabilir ve sayfa içeriğini uygun anahtar sözcüklerle tanımlayabilirsiniz.<br>
Bazı önemli meta etiketleri ve açıklamaları şu şekildedir:<br>
Keywords: Sitenizin içeriğini oluşturan kelimelerin bulunduğu etikettir.<br>
Description: Bu etiket site hakkında bilgi veren temel etiketlerden biridir.<br>
Author: Site yapımcısının adı, iletişim bilgilerinin bulunduğu etikettir.<br>
<h3>BODY etiketi</h3>
HTML belgenizin ikinci ve en uzun parçası BODY kısmıdır. Belgenizin tüm içeriği burada yer alacaktır. Bir sonraki belgede açıklanan etiketlerin tümü BODY içinde yer alacaktır.<br>
<h3>Body İçerisinde Yer Alan Temel HTML Etiketleri</h3>
<h4>Başlıklar (Headings)</h4><br>
HTML metni içinde H1 ile H6 aralığında ölçeklendirilmiş 6 farklı düzeyde başlık kullanılabilir. Burada H1 en büyük başlığı, H6 ise en küçük başlığı simgelemektedir.

Bir başlık elemanının genel yazılış biçimi,

<Hx>Başlık Metni</Hx>

şeklindedir. Burada x, 1 ile 6 arasında bir tamsayıdır ve başlığın düzeyini belirlemektedir.

HTML kodunuz içinde başlık düzeylerini atlatmamaya dikkat ediniz. Örneğin H1 ile başlayıp daha sonra H4'ü kullanmayın. Düzeyler birbirini sırasıyla izlemesi, arama motorları tarafından daha iyi bir konumda endekslenmeniz için de önemlidir.
<h4>Paragraflar (Paragraphs)</h4>
Oluşturacağınız Web sayfası üzerine yerleştireceğiniz metni ayrı paragraflar şeklinde ifade etmek için <p>  ve </p> etiketlerini kullanmalısınız.<br>
<h4>Listeler (Lists)</h4>
HTML, çeşitli türlerde listelerin oluşturulabilmesine olanak sağlar. Bu liste türleri,<br>
Numaralanmamış liste<br>
Numaralanmış liste<br>
Tanım listesi<br>
şeklindedir.
<h4>Numaralanmamış liste</h4>
Numaralanmamış listeyi oluşturmak için ul ve /ul etiketleri kullanılır. Bu etiketler arasına liste elemanlarını yerleştirmek için <li> etiketi kullanılır. Bu etiketi izleyen yere liste elemanı yerleştirilmelidir. li etiketinin /li etiketiyle kapatılması zorunlu değildir.
<h4>İç İçe Listeler</h4>
Listeleri iç içe de kullanabilirsiniz. Hatta, tek bir liste kalemi içinde iç içe listeler içeren paragraflar da düzenleyebilirsiniz.
Ornek:{syntax'in belli olmasi icin alttaki taglari cevreleyen "< >" silinmistir.!!}<br> 
html
  head
    title TÜRKİYE'DE BÜYÜK ŞEHİRLER VE İLÇELER</title>
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
<p><html>
  <head>
    <title>TÜRKİYE'DE BÜYÜK ŞEHİRLER VE İLÇELER</title>
  </head>
  <body>   
      <h3>TÜRKİYE-ŞEHİRLER</h3>
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
</html></p>
<h4>Çok Kullanılan Body Etiketleri</h4>
<ul><h5><li> pre etiketi</li></h5>
<h5><li> br etiketI</li></h5>
<h5><li> hr etiketi</li></h5>
<h5><li> s ve strike etiketleri</li></h5>
<h5><li> strong etiketi</li></h5>
<h5><li> u etiketi</li></h5></ul>

<p></p>
