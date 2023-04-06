# 1.Temel CSS Kavramları

CSS temel olarak, web sayfalarının görünümünü değiştirmek için kullanılan bir stil dilidir. CSS dosyaları HTML dosyalarına dahil edilir ve belirli öğelere stil özellikleri eklenerek görünümleri değiştirilebilir.

## Seçiciler
CSS'de seçiciler, belirli HTML öğelerinin stil özelliklerini belirlemek için kullanılır. Aşağıdaki örneklerde, HTML öğelerini seçmek için kullanılan bazı seçici örnekleri verilmiştir:

Öğe adı seçici: h1, p, div vb.
Sınıf seçici: .ornek-sinif, .buyuk-baslik vb.
Kimlik seçici: #ornek-kimlik, #menu vb.
Özellikler
CSS'de stil özellikleri, HTML öğelerinin görünümünü değiştirmek için kullanılır. Aşağıda, bazı sık kullanılan stil özellikleri verilmiştir:

Renk: color
Metin boyutu: <p style="color:purple;">font-size</p>
Metin ağırlığı: font-weight
Arka plan rengi: background-color
Kenarlık: border

### Değerler
CSS'de stil özelliklerinin aldığı değerler farklı olabilir. Örneğin, bir renk, RGB, RGBA, HSL veya HEX formatında belirtilebilir. Metin boyutu piksel, yüzde veya em cinsinden belirtilebilir.

# 2.CSS'in Temel Yapısı
CSS dosyaları, stil özellikleri için kurallar içeren bir dizi CSS kuralından oluşur. Her CSS kuralı, bir seçici ve stil özellikleri içerir. Örneğin, aşağıdaki CSS kodu, tüm başlık öğelerinin metin rengini kırmızıya ayarlar:

CSS kuralları, HTML belgesinin head bölümünde <style> etiketi kullanılarak içeride veya harici bir CSS dosyası olarak yazılabilir.

# 3.Box Model
Box model, her HTML öğesinin bir kutu olarak düşünüldüğü bir konsepttir. Kutu, içerik, dolgu, kenarlık ve marjla çevrelenir. Bu kutunun boyutları, içerik boyutu, dolgu boyutu, kenarlık boyutu ve marjlar tarafından belirlenir.

### İçerik Kutusu
İçerik kutusu, HTML öğes'nin içeriğini içerir. İçerik kutusunun boyutu, öğenin belirtilen genişlik ve yüksekliğine eşittir.
Dolgu Kutusu
Dolgu kutusu, içerik kutusunun etrafındaki bir boşluktur. Dolgu, içerik ve kenarlık arasında yer alır. Dolgu, öğenin arka plan rengi veya resmiyle dolu olabilir. Dolgu kutusunun boyutu, dolgu özellikleriyle belirlenir.

### Kenarlık Kutusu
Kenarlık kutusu, öğenin içeriğini ve dolgusunu çevreleyen bir kenarlık çizgisidir. Kenarlık kutusunun boyutu, kenarlık özellikleriyle belirlenir.

### Marj Kutusu
Marj kutusu, HTML öğesinin etrafında bir boşluktur. Marj, öğenin komşu öğelerden olan uzaklığını belirler. Marj kutusunun boyutu, marj özellikleriyle belirlenir.

# 4.Düzenleme ve Konumlandırma
CSS, öğelerin düzenlenmesi ve konumlandırılması için birçok seçenek sunar. Aşağıda, en sık kullanılan düzenleme ve konumlandırma yöntemleri verilmiştir:

## Positioning (Pozisyonlama)
CSS'de, öğelerin pozisyonu, position özelliği kullanılarak belirlenebilir. Positioning'in kullanımı için position özelliğinin farklı değerleri vardır:

static: Öğe varsayılan konumda kalır.
relative: Öğenin pozisyonu, öğenin normal konumundan itibaren belirlenen bir mesafeyle değiştirilir.
absolute: Öğenin pozisyonu, en yakın position: relative veya position: absolute öğesi olan üst öğeyle ilişkili olarak belirlenir.
fixed: Öğe, tarayıcı penceresinin konumuna göre belirlenir ve kaydırıldığında bile sabit bir konumda kalır.
Floats (Yüzenler)
Floats, öğelerin birbirine göre konumlandırılması için kullanılan bir CSS özelliğidir. float özelliği kullanılarak, öğe sağa veya sola doğru kaydırılabilir. Yüzen öğelerin etrafındaki öğeler, yüzen öğelerin etrafına sarılır. Bu özellik, genellikle sayfada resim veya metin konumlandırmak için kullanılır.

### Display (Görüntüleme)
display özelliği, bir HTML öğesinin görünümünü değiştirmek için kullanılır. display özelliğinin farklı değerleri vardır:

block: Öğe, belirtilen genişlikte ve yükseklikte tam bir blok olur. Diğer blok öğeleri, önceki blok öğesinin altında görüntülenir.

inline: Öğe, içeriğin boyutuna göre genişler ve yüksekliği, içeriğin yüksekliğiyle sınırlıdır. Diğer iç içe geçmiş iç içe geçirilebilir öğelerle birlikte kullanılır.
inline-block: Öğe, içeriğin boyutuna göre genişler ve yüksekliği, içeriğin yüksekliğiyle sınırlıdır, ancak öğe, diğer öğelerle birlikte satıra sığabilecek bir blok olarak davranır.
none: Öğe, hiçbir şey görüntülemez.


# 5.Renk ve Arka Plan
CSS, öğelerin arka plan rengini ve öğelerin yazı rengini değiştirmek için kullanılır. Aşağıda en sık kullanılan renk özellikleri verilmiştir:

Color (Renk)
color özelliği, metin rengini belirler. Özelliğe, hex kodu, RGB değeri veya önceden tanımlanmış renk ismi gibi bir değer atanabilir.

### Background (Arka Plan)
background özelliği, bir HTML öğesinin arka plan rengini veya resmini belirler. Arka plan, renk veya resim gibi bir değer alabilir. Aşağıda en sık kullanılan arka plan özellikleri verilmiştir:

background-color: Arka plan rengini belirler.
background-image: Arka plan resmini belirler.
background-repeat: Arka plan resminin tekrarlanma şeklini belirler.
background-position: Arka plan resminin konumunu belirler.


# 6.Yazı Stili
CSS, öğelerin yazı tipi, boyutu, stili ve diğer yazı özelliklerini değiştirmek için kullanılır. Aşağıda en sık kullanılan yazı özellikleri verilmiştir:

Font (Yazı Tipi)
font özelliği, bir HTML öğesinin yazı tipini, boyutunu ve stilini belirler. Font özelliği, alt özelliklere sahiptir:

font-family: Kullanılacak yazı tipini belirler.
font-size: Yazı boyutunu belirler.
font-style: Yazı stili (normal, italic, oblique) belirler.
font-weight: Yazı kalınlığını belirler.
Text (Metin)
text özellikleri, metnin görüntülenme şeklini belirler. Aşağıda en sık kullanılan text özellikleri verilmiştir:

text-align: Metnin hizalanma şeklini belirler (sol, sağ, merkez, tamamlama).
text-decoration: Metin süsleme özelliklerini belirler (altı çizili, çizgili).
text-transform:Metnin büyük veya küçük harflere dönüştürülmesini belirler.

text-shadow: Metin gölgesini belirler.
text-indent: İlk satır girintisini belirler.


# 7.Düzen
CSS, öğelerin düzenini değiştirmek için kullanılır. Aşağıda en sık kullanılan düzen özellikleri verilmiştir:

### Box Model
Box model, bir HTML öğesinin boyutunu ve konumunu belirlemek için kullanılır. Box model, öğenin içeriği, dolgu, kenarlık ve dış kenarlık olmak üzere dört bileşenden oluşur.

width: Öğenin genişliğini belirler.
height: Öğenin yüksekliğini belirler.
padding: Öğenin içeriği ile kenarlığı arasındaki boşluğu belirler.
border: Öğenin kenarlığını belirler.
margin: Öğenin dış kenarlığını belirler.

### Position (Konum)
position özelliği, bir HTML öğesinin konumunu belirler. Aşağıda en sık kullanılan position özellikleri verilmiştir:

static: Öğe normal akışta yer alır.
relative: Öğenin konumu normal akışa göre ayarlanır, ancak öğe, diğer öğelerin üzerinde veya altında konumlandırılabilir.
absolute: Öğenin konumu, en yakın pozisyonu belirtilmiş üst öğeye göre ayarlanır.
fixed: Öğe, belirtilen konumda sabitlenir ve sayfa kaydırıldığında bile konumunu korur.
Display (Görünüm)
display özelliği, bir HTML öğesinin görüntülenme şeklini belirler. Aşağıda en sık kullanılan display özellikleri verilmiştir:

block: Öğe, ayrı bir blok olarak görüntülenir. Diğer blok öğeleri, önceki blok öğesinin altında görüntülenir.
inline: Öğe, içeriğin boyutuna göre genişler ve yüksekliği, içeriğin yüksekliğiyle sınırlıdır. Diğer iç içe geçmiş iç içe geçirilebilir öğelerle birlikte kullanılır.
inline-block: Öğe, içeriğin boyutuna göre genişler ve yüksekliği, içeriğin yüksekliğiyle sınırlıdır, ancak öğe, diğer öğelerle birlikte satıra sığabilecek bir blok olarak davranır.
none: Öğe, hiçbir şey görüntülemez.

# 8.Medya Sorguları
Medya sorguları, bir web sayfasının görüntülenme şeklini belirlemek için kullanılır. CSS medya sorgular


# 9.Animasyonlar
CSS, web sayfalarında animasyonlar oluşturmak için kullanılır. Aşağıda en sık kullanılan animasyon özellikleri verilmiştir:

animation-name: Animasyonun adını belirler.
animation-duration: Animasyonun süresini belirler.
animation-delay: Animasyonun ne zaman başlayacağını belirler.
animation-iteration-count: Animasyonun kaç kez tekrarlanacağını belirler.
animation-direction: Animasyonun hangi yönde oynatılacağını belirler.
  
  
# 10. Responsive Tasarım
Responsive tasarım, web sayfalarının farklı cihazlarda (mobil, tablet, masaüstü vb.) doğru şekilde görüntülenmesini sağlamak için kullanılır. Aşağıda en sık kullanılan responsive tasarım özellikleri verilmiştir:

max-width: Belirtilen genişlikten daha küçük ekranlarda öğenin boyutunu sınırlar.
min-width: Belirtilen genişlikten daha büyük ekranlarda öğenin boyutunu sınırlar.
media queries: Belirli bir medya türünde veya genişlikte özel CSS kuralları uygular.
  
  
# 11.Önemli Notlar
CSS, HTML ile birlikte kullanılır ve stil sayfaları genellikle .css uzantılı dosyalarda saklanır.

CSS, her zaman style etiketi içinde yer alır. Bu etiket, ya head etiketi içinde ya da doğrudan HTML etiketleri içinde kullanılabilir.

CSS, önceden tanımlanmış sınıfları kullanarak, belirli öğeler için aynı stil kurallarını birden fazla kez belirtmek yerine, tekrar kullanımı en aza indirir.

CSS, web sayfalarını daha erişilebilir hale getirmek için kullanılan ARIA (Accessible Rich Internet Applications) etiketlerini de destekler.
  

# 12.Sonuç
Bu Github dokümantasyonu, CSS'nin temellerini kapsamaktadır. CSS, web sayfalarının görünümünü ve düzenini belirlemek için çok önemlidir. CSS ile web sayfalarınızı daha etkileyici, daha okunaklı ve daha kullanışlı hale getirebilirsiniz.




