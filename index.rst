
VISPEAHEN VERİ ANALİZ VE GÖRSELLEŞTİRME PLATFORMU V3
====================================================

**1. Vispeahen Kullanıcı Oluşturma**
====================================

Vispeahen’e kullanıcı adı
ve şifre bilgisi ile giriş yapılabilmektedir. Vispeahen’e giriş yapacak
kullanıcı aşağıdaki adımları izlemelidir.

*  Web tarayıcıya Vispeahen’e giriş yapılacak url eklenir.

.. figure:: ./images/1.png
   :alt: image


-  “Ücretsiz Kayıt Ol” seçeneği tıklanır.

.. figure:: ./images/2.png
   :alt: image

-  Kayıt için gerekli bilgiler girilir, “Kayıt Ol” butonuna tıklanarak
   kullanıcı kaydı gerçekleştirilir.

.. figure:: ./images/3.png
   :alt: image

.. ref:`Vispeahen Kullanıcı Oluşturma`

**2. Giriş Yapma**
==================

-  Vispeahen’e giriş yapmak için tarayıcıya belirlenen url eklenir.

.. figure:: ./images/4.png
   :alt: image



Resim 1. Vispeahen Giriş Ekranı

-  Açılan Vispeahen sayfasında kullanıcı adı ve şifre bilgisi girilir.
-  Tercih edilen dil seçilir.
-  “Giriş” butonuna tıklanarak giriş yapılır.

.. figure:: ./images/5.png
   :alt: image



**3. Açılış Ekranı**
====================

-  Kullanıcı adı ve şifre bilgisi ile giriş yaptıktan sonra açılış
   ekranı gelmektedir. Kullanıcı ile ilk defa girişte ya da herhangi bir
   label seçilmediyse açılış ekranı yönlendirme metni ile gelmektedir.

.. figure:: ./images/6.png
   :alt: image

Resim 3. Vispeahen Açılış Ekranı

Kullanıcı açılış ekranında bulunan “Etiketler” ikonuna tıkladığında;

* İlk defa giriş yapıyorsa varsayılan olarak tanımlanan etiketler görüntülenir.

.. figure:: ./images/7.png
   :alt: image


-  Daha önce tanımlamış olduğu etiket varsa o etiketleri seçenekler
   arasında görüntüleyebilir.

.. figure:: ./images/7.png
   :alt: image



Kullanıcının yetkisine göre gelen etiketlerden seçim yapıldığında açılış
ekranında seçilen etiketler ve ilgili etiketlere tanımlanan raporlar
görüntülenmektedir.

* Seçilen label’a herhangi bir rapor tanımlanmamışsa “Bu etikette hiçbir rapor bulunamadı” uyarısı yer almaktadır. Kullanıcı etiket altında olmasını istediği raporlara ilgili etiketleri tanımlamalıdır.

.. figure:: ./8.png
   :alt: image



-  Seçilen etikete rapor tanımlanmışsa tanımlanan raporlar ilgili etiket
   altında görüntülenmektedir.

Kullanıcı yetkisi dahilinde dashboardları “Arama” alanından
arayabilmektedir. Yazmış olduğu metin ilk etapta rapor isimleri olmak
üzere metadata da dahil olmak üzere gelişmiş arama özelliğine sahiptir.

Arama yapılan rapor ön izlemeleri de yer almaktadır.

.. figure:: ./images/9.png
   :alt: image




**4. Rapor Oluşturma Ekranı**
=============================

Rapor açılış ekranının solunda bulunan “+” ikonuna tıklandığında yeni
rapor oluşturma ekranına geçiş yapılmaktadır. (“+” ikonu yetki dâhilinde
gelmektedir)

.. figure:: ./images/10.png
   :alt: image



“+” ikonuna tıklandıktan sonra gelen ekran aşağıdadır:

.. figure:: ./images/11.png
   :alt: image



**1. Rapor Başlık Alanı:** Oluşturulan rapora verilen başlık bilgisinin
yer aldığı alandır.

**2. Yardım Alanı:** Vispeahen kullanımı için
yardım dokümanının bulunduğu alandır.

**3. Profil Alanı:** Kullanıcı
profil alanıdır. Yetki dâhilinde “Yönetim Paneli” sayfasına geçiş
yapılabilmektedir.

**4. Model Alanı:** Modelleme ve veri kaynağının
eklendiği alandır.

**5. Görsel Alanı:** Görsellerin listelendiği
alandır.

**6. Yenile Alanı:** Raporun yenilendiği alandır.

**7. Otomatik Yenileme Alanı:** Belirlenen sürede raporun yenilendiği alandır.

**8.Dışarı Aktar Alanı:** Excel/Pdf/Png çıktısı alınan alandır.

**10. Kaydet Alanı:** Raporun kaydedilmesi/farklı kaydedilmesi alanıdır.

**11. Rapor Sabitle Alanı:** Görsel içinde uzaklaştırma/yakınlaştırma gibi
özellikleri olan görseller için yeniden boyutlandırma özelliğini kapatmak için kullanılan alandır.

**12. Etiketler Alanı:** Raporun yer alacağı label’ın oluşturulduğu/seçildiği alandır.

**13. Ayarlar Alanı:** Raporun kişiselleştirilebilir (arkaplan rengi,gölge ekleme,…)
özelliklerinin bulunduğu alandır.

**14. Rapor Geçiş Alanı:** Yetkili olunan labellar ve raporlar arasında kolay geçişin yapılabileceği
alandır.

**15. Rapor Oluşturma Alanı:** Görsellerin eklendiği, düzenlemelerin yapıldığı alandır.

::

4.1.Veri Kaynağı Ekleme
=======================

Veri kaynağı eklemek için önce model alanına tıklamak gerekir. Rapor
oluşturma ekranı sol tarafında bulunan “Model” ikonuna tıklanır.

.. figure:: ./images/12.png
   :alt: image



Modelleme alanında model ismi yazılarak “Oluştur” butonuna tıklanır.

.. figure:: ./images/13.png
   :alt: image

Yazılan model isminden sonra kullanıcıya yardımcı metni yer almaktadır.
Veri kaynağı eklemek için “Hadi Başlayalım” butonuna tıklanarak devam
edilir.

.. figure:: ./images/14.png
   :alt: image

“Hadi Başlayalım” butonuna tıklandıktan sonra sağ tarafta yeni bir alan
açılacaktır. Sağ tarafta açılan alanda;

* Dosya Yükleme: Veri kaynağı olarak dosya (csv/excel,..) yüklenen alandır.
*  RDBMS/NoSQL: İlişkisel ya da nosql veri kaynaklarının eklendiği alandır.

.. figure:: ./images/15.png
   :alt: image



İlişkisel/NoSQL veri kaynağı eklemek için “+” ikonuna tıklanır.

.. figure:: ./images/16.png
   :alt: image

Yeni veri kaynağı ekleme ikonuna tıklandığı zaman eklenebilecek veri
kaynakları ikonları görülmektedir.

.. figure:: ./images/17.png
   :alt: image

Eklemek için veri kaynağı seçimi yapıldığında veri kaynağı bağlantı
bilgilerinin girilebileceği alan açılmaktadır.

.. figure:: ./images/18.png
   :alt: image



**1. Bağlantı için bir isim verin:** Eklenecek veri kaynağına verilecek
isim alanıdır.

**2. Ip Adresi:** Veri kaynağı hostname bilgisidir.

**3.Port:** Veri kaynağı port alanıdır. (Default port lar otomatik olarak gelmekte eklenecek veri kaynağı farklı porta sahipse
değiştirilebilmektedir)

**4.Veritabanı İsmi:** Veri kaynağı veritabanı isminin yazıldığı alandır.

**5. Şema İsmi:** Veri kaynağında bağlanılacak şema ismi alanıdır.

**6.Kullanıcı Adı:** Veri kaynağına bağlanılacak kullanıcı adı bilgisidir.

**7. Şifre:** Veri kaynağına bağlanılacak kullanıcıya ait şifre bilgisidir.

**8. Test Bağlantısı:** Belirtilen bağlantı bilgileri ile veri kaynağına bağlantının başarılı
olup olmadığının kontrol edileceği alandır. (Veri kaynağına bağlantı sağlanması durumunda “Başarılı”,
bağlantı sağlanmaması durumunda “Başarısız” olarak uyarı çıkacaktır.

**9. Kaydet:** Belirtilen bağlantı bilgileri test bağlantı alanından “Başarılı” olduğunda “Kaydet” butonu
aktif olmakta ve belirtilen isimle bağlantı bilgileri kaydedilecektir.

::

4.2. Modelleme Alanı
====================
Veri kaynağı eklenmesi için model oluşturulması gerekmektedir. Model
oluşturmanın nasıl yapıldığı veri kaynağı ekleme kısmında yer almıştır.
Veri kaynağı bağlantısı sağlandıktan sonra veri kaynağı “Yeni” olarak
görüntülenmekte ve veri kaynağına ilişkin tablolar listelenmektedir.

-  Kullanıcı isterse veri kaynağı ekleme alanının sağında bulunan silme
   ikonu ile veri kaynağını silebilir.
-  Kullanıcı isterse veri kaynağı ekleme alanı sağında bulunan düzenleme
   ikonu ile veri kaynağına ilişkin bağlantı bilgilerini düzenleyebilir.
-  Kullanıcı veri kaynağında yer alan “Arama” alanı ile veri kaynağında
   yer alan tabloları arayabilir.

Kullanıcı modelde yer almasını istediği tablolara tıklayarak modele
istediği tabloları ekleyebilmektedir.

.. figure:: ./images/19.png
   :alt: image



Oluşturulan modele eklenen tablolara tıklandığında tabloda yer alan
kolonlar listelenmektedir.

.. figure:: ./images/20.png
   :alt: image



Eklenen tabloda yer alan kolonların sağında bulunan üç noktaya
tıklandığında kolonlara ilişkin işlemler yapılabilir.

.. figure:: ./images/21.png
   :alt: image



**1.Kopyala:** Var olan kolonun aynısından ikinci bir kolon oluşturulmak
istendiğinde kullanılır.

**2.Toplama Kuralı:** Kolona toplama kurallarından (aggregation rule) eklenmek istendiğinde tıklanacak
alandır.

.. figure:: ./images/22.png
   :alt: image

4.3.1.Scatter Grafiği
=====================
.. figure:: ./images/23.png
   :alt: image



**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların
açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**6.Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**7. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde
uyarı çıkmaktadır.

**Not:** Etkileşim-Navigasyon alanları grafiklerde
ortak olduğundan ayrı başlıkta yer alacaktır.

**Scatter Grafiği Veri Alanı**

.. figure:: ./images/25.png
   :alt: image



Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan
bölümlere sürükle-bırak ile eklenir.

1. **Ara:** Tablo ve kolonların arandığı alandır.
2. **Tablo Kolon Listesi:** Seçili modelde yer alan
tablo ve kolonların yer aldığı bölümdür.

**2.Kolon Eşleştirmeleri**

    2.1.\ **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

    2.2.\ **X Değeri:** Grafiğin yatay alandaki sayısal değerin gösterileceği alandır.

    2.3.\ **Y Değeri:** Grafiğin dikey alandaki sayısal değerin gösterileceği alandır.

    2.4.\ **Grup:** Grafikte yer alan sayısal alanların kategorik olarak gruplanacağı veri alanıdır.

    2.5.\ **Renge Göre Değişim:** Bu alandaki veriye göre renk değişikliğinin sağlanacağı alandır.

    2.6.\ **Büyüklüğe Göre Değişim:** Bu alandaki veri değerine göre nokta boyutunun ayarlandığı alandır.

**Scatter Grafiği Ayarlar Alanı**

.. figure:: ./images/26.png
   :alt: image



**1. Genel Görünüm**

1. **En Büyük Nokta Boyutu:** Grafiği oluşturan noktalardan değeri en
büyük olanın boyutunun ayarlandığı alandır.

2. **En Küçük Nokta Boyutu:** Grafiği oluşturan noktalardan değeri en küçük olanın boyutunun
ayarlandığı alandır.

3. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

**4. Palet**

4.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

4.2.**Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

**2. Diğer**

2.1. **Başlık:** Grafiğe başlık verilen alandır.

2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği
alandır.

2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

2.4. **X Eksen Başlığı:** Grafiğin yatay alandaki başlığın düzenlendiği alandır.

2.5. **Y Eksen Başlığı:** Grafiğin dikey alandaki başlığın düzenlendiği alandır. 2.6. **Doğrusal Regresyon:** Grafikteki doğrusal
çizginin eklenip eklenmeme durumu belirlenir.

2.7. **Sürükleyerek Seçim:** Grafik üzerindeki birden fazla noktanın alan olarak seçilme
durumu belirlenir.

4.3.1.2.Chord Diagram
======================

.. figure:: ./images/27.png
   :alt: image

1. Araçları Aç/Kapat: Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.
#. Veri: Kullanıcının kendi verileriyle görseli şekillendireceği alandır.
#. Ayarlar: Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.
#. Etkileşim: Görselden diğer görsellere filtre verilen alandır.
#. Navigasyon: Görselden belirlenen parametreye göre navigasyon verilen alandır.
#. Yenile: Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.
#. Kaldır: Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim-Navigasyon alanları grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Chord Diagram Veri Alanı**


.. figure:: ./images/28.png
   :alt: image

**1.Tablolar ve Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1.1. **Ara:** Tablo ve kolonların arandığı alandır.

1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2.Kolon Eşleştirmeleri**
2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

2.2. **Varlıklar:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için en az iki kategorik verinin eklendiği alandır.

2.3. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

Chord Diagram Ayarlar Alanı

.. figure:: ./images/29.png
   :alt: image

**1.Genel Görünüm**

1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

**2.Palet**

2.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

2.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

**2.Diğer**

2.1. **Başlık:** Grafiğe başlık verilen alandır.

2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

4.3.1.3. Sankey grafiği
=======================

.. figure:: ./images/30.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**6. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**7. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim-Navigasyon alanları grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Sankey Grafiği Veri Alanı**

.. figure:: ./images/31.png
   :alt: image

**1. Tablolar ve Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.
Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1.1. **Ara:** Tablo ve kolonların arandığı alandır.

1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşlelştirmeleri**

2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

2.2. **Seviye:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için en az iki kategorik verinin eklendiği alandır.

2.3. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

**Sankey Grafiği Ayarlar Alanı**

.. figure:: ./images/32.png
   :alt: image

**1.Genel Görünüm**

1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

**2.Palet**

2.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

2.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

**2.Diğer**

2.1. **Başlık:** Grafiğe başlık verilen alandır.

2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.


4.3.1.4. Silindir Bar Grafiği
==============================
.. figure:: ./images/33.png
   :alt: image

**1.Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2.Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3.Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5.Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Silindir Bar Grafiği Veri Alanı**

.. figure:: ./images/34.png
   :alt: image

**1.Tablolar & Kolonlar**
Seçili modelde var olan tablo ve kolonların bulunduğu alandır.
Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.
   1.1. **Ara:** Tablo ve kolonların arandığı alandır.
   
   
   1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2.Kolon Eşleştirmeleri**
  
  2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.
  
  2.2. **Etiket:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için verinin eklendiği alandır.
  
  2.3. **Değerler:** Grafiği şekillendirmek için kullanılacak sayısal veri/verilerin eklendiği alandır.
 
**Silindir Bar Grafiği Ayarlar Alanı**

.. figure:: ./images/35.png
   :alt: image

**1. Diğer**

1. **Başlık:** Grafiğe başlık verilen alandır.

2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

4. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

4. 3. 1. 5. Yaş Piramidi
========================


.. figure:: ./images/36.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3.Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4.Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**5.Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**6.Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Yaş Piramidi Veri Alanı**

.. figure:: ./images/37.png
   :alt: image


**1.Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.
Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1.1. **Ara:** Tablo ve kolonların arandığı alandır.

1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2.Kolon Eşleştirmeleri**

2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

2.2. **Kategori:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için kategorik verinin eklendiği alandır.

2.3. **Ölçü Değeri 1:** Grafiğin sağında yer alan sayısal verinin eklendiği alandır.

2.4. **Ölçü Değeri 2:** Grafiğin solunda yer alan sayısal verinin eklendiği alandır.

2.5. **Saklı Alan:** Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır.

**Yaş Piramidi Ayarlar Alanı**

.. figure:: ./images/38.png
   :alt: image

 **1.Genel Görünüm**

1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

2. **Palet**

   2.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

   2.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

**2.Diğer**

   2.1. **Başlık:** Grafiğe başlık verilen alandır.

   2.2 **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

           
4.3.1.6.Çok Eksenli Grafik
===========================

.. figure:: ./images/39.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel ya da şekilsel biçimlendirmeler yapılan alandır.

**5. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**6. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**7. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**8. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Koşulsal Formatlama-Etkileşim-Navigasyon alanları grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Çok Eksenli Grafik Veri Alanı**

.. figure:: ./images/40.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1.1. **Ara:** Tablo ve kolonların arandığı alandır.
1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.
 
 2.2. **Kategori:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için kategorik verinin eklendiği alandır.
 
 2.3. **Kolonlar:** Grafikte çubuk (bar) olarak gösterilmek istenen sayısal verinin eklendiği alandır.

2.4. **Çizgiler:** Grafikte çizgi (line) olarak gösterilmek istenen sayısal verinin eklendiği alandır.

2.5. **Renge Göre Değişim:** Grafikte ilgili alandaki veriye göre çubuk/line renklenir.

2.6. **Saklı Alan:**Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır.

**Çok Eksenli Grafik Ayarlar Alanı**

.. figure:: ./images/41.png
   :alt: image

**Genel Görünüm**

1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

2. **Eksen Tipi:** Grafik eksenini tekli/çoklu/yığın şekilde görmek için seçilen alandır.

3. **Çizgi Değerini Göster:** Grafikte bu seçim yapıldıysa oluşan çizgi grafikte değerler görüntülenir.

4. **Bar Değerini Göster:** Grafikte bu seçim yapıldıysa oluşan çubuk (bar) grafikte değerler görüntülenir.

5. **Çizgi Değerini Renklendir:** Grafikte bu seçim yapıldıysa çizgi değerleri, oluşturulan grafikteki çizgi renkleri ile aynı olacak şekilde ayarlanır.

**6. Palet**

6.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

6.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

**7. Çizgi Kalınlığı:** Grafikte çizgi görselinin kalınlığının ayarlandığı alandır.

**8. Nokta Boyutu:** Grafikte çizgi görselinin değerinin gösterildiği nokta boyutunun ayarlandığı alandır.

 **2.Diğer**

2.1. **Başlık:** Grafiğe başlık verilen alandır.

2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

2.4. **Göstergeleri Göster:** Grafikte bu seçim yapıldıysa göstergeler grafikte yer alır.

**3.Yazı Biçimlendirme**

3.1. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.

4.3.1.7. Filtre
===============

.. figure:: ./images/42.png
   :alt: image

1. **Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

2. **Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

3. **Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

4. **Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

5. **Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

6. **Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim alanı grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Filtre Veri Alanı**

.. figure:: ./images/43.png
   :alt: image

**1.Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2.Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Filtre:** Grafikte yer alacak verinin ekleneceği alandır.

 **Filtre Ayarlar Alanı**

.. figure:: ./images/44.png
   :alt: image

 **1. Genel Görünüm**


1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

2. **Ok Rengi:** Grafik eksenini tekli/çoklu/yığın şekilde görmek için seçilen alandır.

3. **Metin Arka Plan Rengi:** Grafikte bu seçim yapıldıysa oluşan çizgi grafikte değerler görüntülenir.

4. **Filtre Seçilmeden Önce Görünecek Değer:** Grafikte bu seçim yapıldıysa oluşan çubuk (bar) grafikte değerler görüntülenir.

5. **Yer Tutucu Rengi:** Grafikte bu seçim yapıldıysa çizgi değerleri, oluşturulan grafikteki çizgi renkleri ile aynı olacak şekilde ayarlanır.

**2. Diğer**

2.1. **Başlık:** Grafiğe başlık verilen alandır.

2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

2.3. **Çoklu Seçim:** Grafik üzerinde çoklu seçim yapılabilme özelliğini aktif hale getirir.


4.3.1.8. Seçim Kutucuğu Filtresi
================================

.. figure:: ./images/45.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**6. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim alanı grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.


**Seçim Kutucuğu Filtre Veri Alanı**

.. figure:: ./images/46.png
   :alt: image


**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Filtre:** Grafikte yer alacak verinin ekleneceği alandır.

**Seçim Kutucuğu Filtre Ayarlar Alanı**

.. figure:: ./images/47.png
   :alt: image

**1. Genel Görünüm**

1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

**2. Diğer**

1. **Başlık:** Grafiğe başlık verilen alandır.

2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

4.3.1.9.Radio Buton Filtresi
============================

.. figure:: ./images/48.png
   :alt: image


**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**6. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim alanı grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

Radio Buton Filtre Veri Alanı

.. figure:: ./images/49.png
   :alt: image


**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.
 2.2. **Filtre:** Grafikte yer alacak verinin ekleneceği alandır.

Radio Buton Filtre Ayarlar Alanı

.. figure:: ./images/50.png
   :alt: image

**1. Genel Görünüm**

1.1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

**2.Diğer**

2.1. **Başlık:** Grafiğe başlık verilen alandır.

2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

4.3.1.10. Bubble Harita
=======================

.. figure:: ./images/51.png
   :alt: image

1. **Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

2. **Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

3. **Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

4. **Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

5. **Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

6. **Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

7. **Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim, Navigation alanı grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Bubble Harita Veri Alanı**

.. figure:: ./images/52.png
   :alt: image


**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.
 
 1.1. **Ara:** Tablo ve kolonların arandığı alandır.
 
 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Açıklama:** Girilen enlem ve boylamın kesiştiği yer ismidir. 

 2.3. **Boylam:** Haritada gösterilecek alanların boylam bilgisinin yer aldığı veri alanıdır.

 2.4. **Enlem:** Haritada gösterilecek alanların enlem bilgisinin yer aldığı veri alanıdır.

 2.5. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

 2.6. **Renge Göre Değişim:** Bu alandaki veriye göre renk değişikliğinin sağlanacağı alandır.

**Bubble Harita Ayarlar Alanı**

.. figure:: ./images/53.png
   :alt: image


**1. Genel Görünüm**

1.1. **Palet:** Haritada yer alan bubble’lar paletten seçilen renklere göre görselleştirilir. 

1.2. **En Küçük Bubble Yarıçapı:** Haritada yer alan en küçük değere sahip bubble için belirlenen boyuttur.

1.3. **En Büyük Bubble Yarıçapı:** Haritada yer alan en büyük değere sahip bubble için belirlenen boyuttur.

1.4. **Çizgi Kalınlığı:** Haritada yer alan bubble’ın dış çizgisinin kalınlığının belirlendiği kısımdır.

1.5. **Opaklık:** Haritada yer alan bubble’ların saydamlığının belirlendiği kısımdır.

**2. Harita Döşeme**

2.1. **Harita Döşeme:** Harita görünümü ile ilgili seçimin yapıldığı kısımdır.

2.2. **Harita Altlığı Seçimi:** Haritada altlık olarak kullanılacak harita altlığını seçebilmeyi sağlar.

2.3. **Yakın Noktaları Ayırt Et:** Haritada yer alan değere göre büyük bubble içinde kalan küçük bubble’ların ayırt edilebilmesini sağlar.

2.4. **Göstergeleri Göster:** Haritada bu seçim yapıldıysa göstergeler grafikte yer alır.

2.5. **Gösterge Konumu:** Haritada yer alan göstergenin konumunu belirlemeyi sağlar.

**3. Diğer**

3.1. **Başlık:** Haritaya başlık verilen alandır.

3.2. **Başlık Hizası:** Harita başlığının sağ/orta/sol hizalamasının seçildiği alandır.

3.3. **Başlık Yazı Stilleri:** Harita başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.


4.3.1.11.Choropleth Map
=======================

.. figure:: ./images/54.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**2. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**3. Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel ya da şekilsel biçimlendirmeler yapılan alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**6. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**7. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim, Navigation, Koşulsal Formatlama alanları grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.
 
**Choropleth Map Veri Alanı**

.. figure:: ./images/55.png
   :alt: image

**1. Tablolar & Kolonlar**


Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

 **2.Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Kod:** Grafikte yer alan ve topojson ile eşleşecek kod alanıdır. (Plaka, ilçe kodu gibi)

 2.3. **Açıklama:** Girilen kod değerine karşılık gelen yer ismidir. (Örneğin kod alanına plakalar eklenirse açıklama alanına eşleşmesi için şehir ismi eklenmelidir)

 2.4. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.
 
 2.5. **Renge Göre Değişim:** Bu alandaki veriye göre renk değişikliğinin sağlanacağı alandır.


**Choropleth Map Ayarlar Alanı**

.. figure:: ./images/56.png
   :alt: image

**1. Genel Görünüm**

1.1. **Topojson:** Coğrafi haritanın şekillenmesi için coğrafi verinin yer aldığı ve ilgili topojson’ın kullanıcı tarafından seçildiği kısımdır. (Organizasyon bünyesinde kullanılan topojson varsa eklenerek grafik üzerinde görselleştirilebilir) 

1.2. **Feature Code:** Topojson’da yer alan ve veri alanındaki kod ile eşleşecek alandır. (Örneğin; topojson olarak Türkiye İller topojson’ı seçildiği varsayılırsa Feature Code plaka olacaktır)

1.3. **Feature Description:** Topojson’da yer alan kod alanına karşılık açıklama bilgisinin seçildiği alandır. (Örneğin; topojson olarak Türkiye İller topojson’ı seçildiği varsayılırsa Feature Description il adı olacaktır)

**2.Genel Görünüm**

2.1. **Renk Ölçek Tipi:** Ölçeklendirmenin verinin en küçük - en büyük değer aralığında ya da verinin en küçük – en büyük yüzdeliği aralığında yapılacağının belirlendiği alandır.

2.2. **Opaklık:** Harita saydamlığının belirlendiği kısımdır.

2.3. **Göstergeleri Göster:** Haritada bu seçim yapıldıysa göstergeler grafikte yer alır.

2.4. **Gösterge Konumu:** Haritada yer alan göstergenin konumunu belirlemeyi sağlar.

2.5. **Çizgi Kalınlığı:** Haritada yer alan bölgeler üzerine gelindiğinde bölge çerçeve kalınlığının belirlendiği alandır.

2.6. **Boş Veri Rengi:** Harita üzerinde boş veri varsa renginin seçildiği alandır.

2.7. **Seçim Rengi:** Harita üzerinde seçim yapılan alan renginin seçildiği kısımdır.

2.8. **Palet:** Harita paletten seçilen renklere göre görselleştirilir.

2.9. **Harita Döşeme:** Harita görünümü ile ilgili seçimin yapıldığı kısımdır. 

2.10. **Harita Altlığı Seçimi:** Haritada altlık olarak kullanılacak harita altlığını seçebilmeyi sağlar.

2.11. **Başlık:** Haritaya başlık verilen alandır.

2.12. **Başlık Hizası:** Harita başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.13. **Başlık Yazı Stilleri:** Harita başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

2.14. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.


4.3.1.12. Cluster Harita
========================

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

Cluster Map Veri Alanı

.. figure:: ./images/57.png
   :alt: image


**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1.1. **Ara:** Tablo ve kolonların arandığı alandır.

1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

2.2. **Açıklama:** Girilen kod değerine karşılık gelen yer ismidir. (Örneğin kod alanına plakalar eklenirse açıklama alanına eşleşmesi için şehir ismi eklenmelidir)

2.3. **Boylam:** Haritada gösterilecek alanların boylam bilgisinin yer aldığı veri alanıdır.

2.4. **Enlem:** Haritada gösterilecek alanların enlem bilgisinin yer aldığı veri alanıdır.


**Cluster Map Ayarlar Alanı**

.. figure:: ./images/58.png
   :alt: image

**1. Genel Görünüm**

1.1. **Renk:** Haritada yer alan cluster bubble’ların renk değişikliğinin yapıldığı kısımdır. 

1.2. **Harita Döşeme:** Harita görünümü ile ilgili seçimin yapıldığı kısımdır.)
 
 **2. Diğer**

2.1. **Başlık:** Haritaya başlık verilen alandır.

2.2. **Başlık Hizası:** Harita başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.3. **Başlık Yazı Stilleri:** Harita başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.


4.3.1.13.Heatmap Harita
=======================

.. figure:: ./images/59.png
   :alt: image

**1.Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2.Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3.Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4.Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5.Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

Heatmap Harita Veri Alanı

.. figure:: ./images/60.png
   :alt: image

**1. Tablolar & Kolonlar**


Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1. **Ara:** Tablo ve kolonların arandığı alandır.

2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.
   
**2. Kolon Eşleştirmeleri**

2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

2.2. **Boylam:** Haritada gösterilecek alanların boylam bilgisinin yer aldığı veri alanıdır.

2.3. **Enlem:** Haritada gösterilecek alanların enlem bilgisinin yer aldığı veri alanıdır.

2.4. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

**Heatmap Harita Ayarlar Alanı**

.. figure:: ./images/61.png
   :alt: image

**1. Genel Görünüm**

  1. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.  
  2. **Yoğunluk:** Harita üzerindeki yoğunluk dağılımını yakınlaştırıp uzaklaştırmak için kullanılan alandır.
  3. **Harita Döşeme:** Harita görünümü ile ilgili seçimin yapıldığı kısımdır.

**2. Diğer**

  2.1. **Başlık:** Haritaya başlık verilen alandır.
  
  2.2. **Başlık Hizası:** Harita başlığının sağ/orta/sol hizalamasının seçildiği alandır.

  2.3. **Başlık Yazı Stilleri:** Harita başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.


4.3.1.14.Oklu Türkiye Haritası
==============================

.. figure:: ./images/62.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2.Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3.Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4.Etkileşim:** Görselden diğer görsellere filtre verilen alandır.Yenile: Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5.Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Oklu Türkiye Haritası Veri Alanı**

.. figure:: ./images/63.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.
  1. **Ara:** Tablo ve kolonların arandığı alandır.
  
  2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

2. **Çıkış İl Plakası:** Haritada bir ilden başka ile gidiş oklarla gösterilmektedir. Çıkış il plakası okun başlangıç yerinin gösterildiği ilin plaka alanıdır.

3. **Çıkış İlin Enlemi:** Haritada gösterilecek okun başlangıç ilinin enlem bilgisinin yer aldığı veri alanıdır.

4. **Çıkış İlin Boylamı:** Haritada gösterilecek okun başlangıç ilinin boylam bilgisinin yer aldığı veri alanıdır.

5. **Varış İl Plakası:** Haritada bir ilden başka ile gidiş oklarla gösterilmektedir. Varış il plakası okun bitiş yerinin gösterildiği ilin plaka alanıdır.

6. **Varış İlin Enlemi:** Haritada gösterilecek okun bitiş ilinin enlem bilgisinin yer aldığı veri alanıdır.

7. **Varış İlin Boylamı:** Haritada gösterilecek okun bitiş ilinin boylam bilgisinin yer aldığı veri alanıdır

8. **Değer:** Haritayı şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

9. **Saklı Alan:** Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır


**Oklu Türkiye Haritası Ayarlar Alanı**

.. figure:: ./images/64.png
   :alt: image

**1.Genel Görünüm**


  1.1. **Tema:** Harita ön tanımlı temalar seçilerek görselleştirilir.

**2.Diğer**

  2.1. **Başlık:** Haritaya başlık verilen alandır.

  2.2. **Başlık Hizası:** Harita başlığının sağ/orta/sol hizalamasının seçildiği alandır.

  2.3. **Başlık Yazı Stilleri:** Harita başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.


4.3.1.15.Türkiye Haritası
==========================

.. figure:: ./images/65.png
   :alt: image


**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**6. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.


 **Türkiye Haritası Veri Alanı**

.. figure:: ./images/66.png
   :alt: image


**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1. **Ara:** Tablo ve kolonların arandığı alandır.

2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**Kolon Eşleştirmeleri**

1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

2. **Değer:** Haritayı şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

3. **Şehir Kimliği:** Haritanın görselleştirileceği il kodu (plaka) bilgisinin yer aldığı alandır.

4. **Şehir Adı:** Haritanın görselleştirileceği il adı bilgisinin yer aldığı alandır.

5. **İlçe Kimliği:** Haritada görselleştirilen illere karşılık gelen ilçe kodu bilgisinin yer aldığı alandır.


**Türkiye Haritası Ayarlar Alanı**

**1. Genel Görünüm**

1.1. **Tema:** Harita ön tanımlı temalar seçilerek görselleştirilir.

1.2. **Seçim Rengi:** Harita üzerinde seçim yapılan alan renginin seçildiği kısımdır

**2. Diğer**

2.1. **Başlık:** Haritaya başlık verilen alandır.

2.2. **Başlık Hizası:** Harita başlığının sağ/orta/sol hizalamasının seçildiği alandır.

2.3. **Başlık Yazı Stilleri:** Harita başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

2.4. **Çoklu Seçim:** Harita üzerinde çoklu seçim yapılabilme özelliğini aktif hale getirir.

4.3.1.16. Dünya Haritası
========================

.. figure:: ./images/67.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**6. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Dünya Haritası Veri Alanı**

.. figure:: ./images/68.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1. **Ara:** Tablo ve kolonların arandığı alandır.

2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**Kolon Eşleştirmeleri**

**1. Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

**2. Değer:** Haritayı şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

**3. Ülke Kodu:** Haritanın görselleştirileceği ülkeye ilişkin kod bilgisinin yer aldığı alandır.

**4. Ülke Adı:** Haritanın görselleştirileceği ülke adı bilgisinin yer aldığı alandır.

**5. Şehir Kimliği:** Haritada görselleştirilen ülkelere karşılık gelen şehirlere ilişkin kod bilgisinin yer aldığı alandır.

Dünya Haritası Ayarlar Alanı

.. figure:: ./images/69.png
   :alt: image

**1. Genel Görünüm**

1.1. **Tema:** Harita ön tanımlı temalar seçilerek görselleştirilir.

1.1. **Seçim Rengi:** Harita üzerinde seçim yapılan alan renginin seçildiği kısımdır.

**2.Diğer**

**1. Başlık:** Haritaya başlık verilen alandır.

**2.Başlık Hizası:** Harita başlığının sağ/orta/sol hizalamasının seçildiği alandır.

**3. Başlık Yazı Stilleri:** Harita başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

**4. Çoklu Seçim:** Harita üzerinde çoklu seçim yapılabilme özelliğini aktif hale getirir.


4.3.1.17.Measure Tile
=====================

.. figure:: ./images/70.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel biçimlendirmeler yapılan alandır

**5. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır

**6. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**7. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Navigasyon grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

 **Measure Tile Veri Alanı**

.. figure:: ./images/71.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1. **Ara:** Tablo ve kolonların arandığı alandır.

2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**Kolon Eşleştirmeleri**

**1. Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

**2. Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

**3. Saklı Alan:** Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır.

**Measure Tile Ayarlar Alanı**

.. figure:: ./images/72.png
   :alt: image

**1. Yazı Biçimlendirme**
   
   **1. Boyut:** Measure Tile yazı boyutunun girildiği alandır.
   
   **2. Yazı Tipi:** Measure Tile yazı font değişikliğinin yapıldığı alandır.
   
   **3. Renk:** Measure Tile yazı renginin değiştirilebildiği alandır.

**2.Görsel Ekle**

   **2.2.İkon:** Measure Tile’a var olan ikonlardan eklenmek istendiğinde kullanılan alandır.

   **2.3.Resim Mi?:**  Measure Tile’a resim eklenmek istendiğinde kullanılan alandır.

.. figure:: ./images/73.png
   :alt: image

* Resim alanı işaretlendiğinde yukarıda yer alan seçenekler çıkmaktadır.

* Resim Yükle: Measure Tile’a bilgisayar üzerinde bulunan resim eklenmek istendiğinde “Gözat” tıklanarak belirlenen resim eklenir.

* Resim Kaynağı: Eklenecek resim herhangi bir internet sitesindeyse ilgili alana gerekli url bilgisi eklenir.

* Genişlik: Eklenecek resme verilecek genişlik alanıdır.

* Yükseklik: Eklenecek resme verilecek yükseklik alanıdır.

**3.Genel Görünüm**

**3.1. Başlık:** Grafiğe başlık verilen alandır.

**3.2. Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

**3.3. Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

**3.4. Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

**3.5. Animasyon:** Measure Tile ile görselleştirilen verinin ekrana getirilme süresinin girildiği alandır.

4.3.1.18.Bayrak
===============

.. figure:: ./images/74.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Bayrak Veri Alanı**

.. figure:: ./images/75.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

   1. **Ara:** Tablo ve kolonların arandığı alandır.

   2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**Kolon Eşleştirmeleri**

   1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

   2. **Ülke ID:** Grafiği şekillenmesi için ülke kodlarının eklendiği alandır. Eklenen ülke kodunun bayrağı görüntülenmektedir.

 **Bayrak Ayarlar Alanı**

 .. figure:: ./images/76.png
   :alt: image

**1. Diğer**

   1. **Başlık:** Grafiğe başlık verilen alandır.
   
   2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.
   
   3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

4.3.1.19.I-Frame
================
.. figure:: ./images/77.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır 

**3. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**4. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.


**I-Frame Veri Alanı**

I-Frame veri alanı bulunmamaktadır.

**I-Frame Ayarlar Alanı**

.. figure:: ./images/78.png
   :alt: image

**1. Genel Görünüm**

   **1.1. İç Genişlik:** Grafikte gösterilen url’deki görselin genişlik bilgisinin ayarlandığı alandır.
   
   **1.2. İç Yükseklik:** Grafikte gösterilen url’deki görselin yükseklik bilgisinin ayarlandığı alandır.

**2. Diğer**

   **1. Link Alanı:** Grafikte gösterilecek görselin link bilgisinin yer aldığı kısımdır.

   **2. Başlık:** Grafiğe başlık verilen alandır.

   **3. Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   **4. Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

4.3.1.20. Resim
===============

.. figure:: ./images/79.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır 

**3. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**4. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.


**Resim Ayarlar Alanı**

.. figure:: ./images/80.png
   :alt: image

**1. Genel Görünüm**

   **1. Bağlantı:** Grafikte gösterilecek resim herhangi bir internet sitesindeyse ilgili alana gerekli url bilgisi eklenir.

   **2. Resim Yükle:** Grafiğe bilgisayar üzerinde bulunan resim eklenmek istendiğinde “Gözat” tıklanarak belirlenen resim eklenir.

4.3.1.21. Başlık
================

.. figure:: ./images/81.png
   :alt: image

**1.Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2.Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır 

**3.Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**4.Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Başlık Ayarlar Alanı**

.. figure:: ./images/82.png
   :alt: image


**1. Genel Görünüm**

   **1.1.** Başlık: Grafiğe başlık verilen alandır.
   
   **1.2.** Font Boyutu: Grafik yazı boyutunun girildiği alandır.
   
   **1.3. Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.
   
   **1.4. Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.
   
   **1.5. Font Rengi:** Grafik yazı renginin girildiği alandır.

   **1.6. Link Alanı:** Başlık grafiği üzerine tıklandığında gidilecek sayfanın link bilgisinin yer aldığı kısımdır.

   **1.7. Yazı Tipi:** Grafik yazı font değişikliğinin yapıldığı alandır.

4.3.1.22.Pasta Grafiği
======================

.. figure:: ./images/83.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel biçimlendirmeler yapılan alandır

**5. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**6. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**7. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**8. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Koşulsal Formatlama, Etkileşim ve Navigasyon grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.


**Pasta Grafiği Veri Alanı**

.. figure:: ./images/84.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Kategori:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için kategorik verinin eklendiği alandır.

 2.3. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

**Pasta Grafiği Ayarlar Alanı**

.. figure:: ./images/85.png
   :alt: image

**1. Genel Görünüm**

**1. İç Yarıçap:** Grafikte merkezden (iç yarıçap) itibariyle ne kadar boş olacağının belirlendiği kısımdır. 

**2. Palet**

   2.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

   2.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

3. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

**2.Diğer**

   2.1. **Başlık:** Grafiğe başlık verilen alandır.

   2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

   2.4. ** Ölçüm Gösterimi:** Grafikte görselleştirilen sayısal alanların gösterim biçiminin (sayısal/yüzde/sayısal-yüzde) seçildiği alandır.

   2.5. **Göstergeleri Göster:** Grafikte bu seçim yapıldıysa göstergeler grafikte yer alır.

   2.6. **Ölçümleri Oklar ile Grafiğin Dışında Göster:** Grafikte görselleştirilen sayısal alanların grafik dilimlerinden okla gösterilmesi için kullanılır.

   2.7. **Ölçümleri Pasta Dilimlerinin Üzerinde Göster:** Grafikte görselleştirilen sayısal alanların grafik dilimlerinin üzerinde gösterilmesi için kullanılır.

   2.8. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.


4.3.1.23.Radyal İlerleme
========================

.. figure:: ./images/86.png
   :alt: image


**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Radyal İlerleme Grafiği Veri Alanı**

.. figure:: ./images/87.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2.Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

2.3. **Hedef:** Grafikte hedef olarak gösterilen sayısal alandır. Grafiğin şekillendirilmesi için ölçü değerinden büyük sayısal değerdir. 

2.4. **Saklı Alan:** Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır.

**Radyal İlerleme Grafiği Ayarlar Alanı**

.. figure:: ./images/88.png
   :alt: image

**1. Yazı Biçimlendirme**

   1.1. **Yazı Tipi:** Grafik yazı font değişikliğinin yapıldığı alandır.

   1.2. **Başlık:** Grafiğe başlık verilen alandır.

   1.3. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   1.4. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

**2. Genel Görünüm**

 **2.1. Palet**
  
  2.1.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

  2.1.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

  2.2. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

  2.3. **Süre:** Grafikte görselleştirilen verinin ekrana getirilme süresinin girildiği alandır.

**3. Diğer**

   3.1. **Yuvarlatılmış Köşeler:** Grafikte yer alan renklendirilmiş alanın köşelerinin yuvarlak hale dönüştürülmesini sağlayan seçenektir.


4.3.1.24. Sunburst

.. figure:: ./images/89.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2.Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3.Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.Koşulsal Formatlama: Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel biçimlendirmeler yapılan alandır

**4. Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel biçimlendirmeler yapılan alandır

**5. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**6. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**7. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**8. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Koşulsal Formatlama, Etkileşim ve Navigasyon grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Sunburst Grafiği Veri Alanı**


.. figure:: ./images/90.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Seviye:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için kullanılan alandır. (Birden fazla kategorik alan gösterimi iç içe geçmiş halkalar şeklinde gösterilmektedir)

 2.3. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.


**Sunburst Grafiği Ayarlar Alanı**

.. figure:: ./images/91.png
   :alt: image

**1. Genel Görünüm**

  1.1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

  2.2. **Palet**

      1.2.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

      1.2.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

**2. Diğer**

  2.1. **Başlık:** Grafiğe başlık verilen alandır.

  2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

  2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

  2.4. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.
  
  2.5. **Göstergeleri Göster:** Grafikte bu seçim yapıldıysa göstergeler grafikte yer alır.


4.3.1.25. Sıvı Ölçek
====================

.. figure:: ./images/92.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.


**Sıvı Ölçek Grafiği Veri Alanı**

.. figure:: ./images/93.png
   :alt: image

**1.Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

 2.3. **Hedef:** Grafikte hedef olarak gösterilen sayısal alandır. Grafikte hedef olarak belirlenen sayısal veriden küçük olan ölçü değeri eklendiğinde hedef değere göre sıvı ölçeğin bulunduğu hiza belirlenir.

 2.4. **Saklı Alan:** Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır.


 Sıvı Ölçek Grafiği Ayarlar Alanı

.. figure:: ./images/94.png
   :alt: image

**1.Genel Görünüm**

   **1.1.Çember Kalınlığı:** Grafik dış çember kalınlığının belirlendiği alandır.

   **1.2. Yazı Pozisyonu (Dikey):** Grafik üzerinde sayısal değer gösterilmektedir. Sayısal değerin grafik üzerinde dikey olarak nerede gösterileceğinin belirlendiği alandır. 

   **1.3. Minimum Değer:** 

   **1.4. Dalga Yüksekliği:** 

   **1.5. Çember Doldurma Boşluğu:** Grafikte çember ile dalga arasındaki boşluk boyutunun girildiği alandır.

   **1.6. Dalga Sayısı:** 

**2. Diğer**

   2.1. **Başlık:** Grafiğe başlık verilen alandır.

   2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

   2.4. **Dalga Yükselme Süresi:** Dalganın yükselme süresinin girilmesi gereken alandır.

   2.5. **Dalga Animasyon Süresi:** Animasyon süresi olarak girilen sürede dalga hareketi yenilenmektedir.

   2.6. **Dalga Yükseklik Boyutlandırması:**

   2.7. **Çember Doldurma Boşluğu:** Çember ile dalga arasındaki boşluk bilgisinin girildiği alandır.

   2.8. **Yüzdeli Göster:** Grafikteki sayısal değerin yüzdelik olarak gösterilme seçeneğidir. 


4.3.1.26. Radar
================

.. figure:: ./images/95.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**5. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.


**Radar Grafiği Veri Alanı**

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Kategori:** Grafiğin kategorik alana göre değişiminin görselleştirilmesi için kategorik verinin eklendiği alandır.

 2.3. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

**Radar Grafiği Ayarlar Alanı**

.. figure:: ./images/96.png
   :alt: image


**1. Genel Görünüm**

   1.1. **Boyut:** Grafik boyutunun ayarlandığı alandır.

   1.2. **Seviyeler:** Grafikte gösterilen yuvarlak çizgi (seviye) sayısının kaç tane olacağının belirlendiği alandır. 

   1.3. **Nokta Boyutu:** Grafik üzerinde gösterilen değerin eksen ile birleştiği yerdeki nokta boyutunun belirlendiği alandır.

   1.4. **Opaklığı Doldur:** Grafik içinde yer alan bölgenin saydamlık değerinin girildiği alandır.

   1.5. **Dış Çizgi Opaklığı:** Grafik dış çizgisinin saydamlık değerinin girildiği alandır.

   1.6. **Palet**

     1.6.1. **Tema:** Grafik ön tanımlı temalar seçilerek görselleştirilir.

     1.6.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

**2. Diğer**

   2.1. **Başlık:** Grafiğe başlık verilen alandır.

   2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

   2.4. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

   2.5. **Göstergeleri Göster:** Grafikte bu seçim yapıldıysa göstergeler grafikte yer alır.

   2.6. **Birbirinden Ayrı Ölçek:** Birden fazla ölçüm değeri mevcutsa her ölçüm değeri için ölçeklendirmenin yapılabileceğinin belirlendiği alandır.


4.3.1.27. Pivot Tablo
======================

.. figure:: ./images/97.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel biçimlendirmeler yapılan alandır

**5. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**6. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**7. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**8. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Koşulsal Formatlama, Etkileşim ve Navigasyon grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Pivot Tablo Grafiği Veri Alanı**

.. figure:: ./images/98.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Satırlar:** Grafik satır alanında yer alması gereken kolonların eklendiği alandır.

 2.3. **Sütunlar:** Grafik sütun alanında yer alması gereken kolonların eklendiği alandır.

 2.4. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

 2.5. **Saklı Alan:** Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır.


**Pivot Tablo Grafiği Ayarlar Alanı**


.. figure:: ./images/99.png
   :alt: image

**1. Özellik**

   1.1. **Gelişmiş Mod:** Pivot Tablo Enhanced moda geçiş için kullanılan alandır. Pivot enhanced modda birçok özellik bulunmaktadır.

      1.1.1. **Pivot Enhanced Mod**

**2. Yazı Biçimlendirme**

   2.1. **Kolon Genişliği:** Yazılan boyutta pivot tablo kolonlarının başlık boyutu ayarlanmaktadır.

   2.2. **Kolon Yüksekliği:** Pivot kolon başlıklarının yüksekliğini belirlemektedir. Yazılan genişlik oranında pivot tablo kolon başlığını ayarlamaktadır.

   2.3. **Toplam Kolonunu Göster:** Pivot tabloda yer alan satır ve sütunların toplamlarını göstermesinin belirlendiği alandır.

   2.4. **Değerleri Kolon Olarak Seç:** Ölçü değerlerini kolon olarak göstermeyi sağlar.

**3. Genel Görünüm**

   3.1. **Otomatik Boyutlandır:** Pivot tabloyu var olan grid içerisinde otomatik olarak boyutlandırmayı sağlar.

   3.2. **Kontrole İzin Ver:** Son kullanıcı tarafından değişiklik yapılmasını sağlayan butonun görünürlüğünün belirlendiği alandır.

   3.3. **Ara Toplam:** Grafikte ara toplam yapılmasına olanak sağlar. (Gruplanan her satır kolonuna ara toplam eklenmesini sağlar) Bu özelliğin kullanılması için satır alanına en az bir veri eklenmesi gerekmektedir.

   3.4. **Başlıkları Sar:** Grafik kolon başlıkları beklenenden uzun geldiğinde boşluklara uygun olarak alt satıra geçirir.

   3.5. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.

**4.Diğer**

   4.1. **Başlık:** Grafiğe başlık verilen alandır.

   4.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   4.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

   4.4. **Toplamları Seç:** Satır toplamı/sütun toplamı/Satır ve Sütun toplamı bilgilerinin grafikte gösterileceği seçmeli alandır.

   4.5. **Görselleştirme Tipi:** Pivot Tablo görselleştirilirken tablo şeklinde ya da Tablo Çubuk Grafiği ile grafik değerlerine göre çubukların oluşacağı seçiminin yapıldığı alandır.

   4.6. **Tema Rengi:** Grafik genel görünümde yapılacak renk değişikliği alanıdır.

   4.7. **Pivot Tablo Açıklama:** Grafiğe açıklama/bilgi amaçlı yazılacak notların eklendiği alandır.  


4.3.1.28. Tablo

.. figure:: ./images/100.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel biçimlendirmeler yapılan alandır

**5. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**6. Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.

**7. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**8. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Koşulsal Formatlama, Etkileşim ve Navigasyon grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Tablo Grafiği Veri Alanı**

.. figure:: ./images/101.png
   :alt: image


**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Kolon:** Grafikte yer alması gereken kolonların eklendiği alandır. (Sayısal/sayısal olmayan kolonlar ayrımı olmaksızın eklenir)

 2.3. **Saklı Alan:** Grafikte gösterilmeyen default filtrede, formülde kullanılmak üzere verinin eklendiği alandır.

 
  **Tablo Grafiği Ayarlar Alanı**

  .. figure:: ./images/102.png
   :alt: image

**1. Yazı Biçimlendirme**

  1.1. **Kolon Yüksekliği:** Yazılan boyutta tablo kolonlarının başlık boyutu ayarlanmaktadır.

  1.2. **Satır Yüksekliği:* Tabloda verilerin bulunduğu alan yüksekliğinin belirlendiği kısımdır.

  1.3. **Yazı Tipi:** Grafikte bulunan kolon başlıkları, verilerin yer aldığı kısımlara ilişkin yazı font değişikliğinin yapıldığı alandır.

  1.4. **Font Boyutu:** Tablo grafiğindeki yazı boyutunun girildiği alandır.

  1.5. **Toplam Göster:** Tabloda yer alan sayısal alanların toplamının tablo göstermenin belirlendiği alandır.

  1.6. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.

**2. Sayfalama**

  2.1. **Sayfalamayı Etkinleştir:** Tablo plugininde satır sayısı arttığında tek seferde değil sayfalara bölerek gösterilmek istendiğinde bu alan işaretlenmelidir.

  2.2. **Her Sayfada Gösterilecek Veri Sayısı:** Tablo plugininde sayfalama etkinleştirildiğinde her sayfada gösterilebilecek satır sayısı bilgisinin girildiği alandır. 

**3. Genel Görünüm**

  3.1. **Arkaplan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

  3.2. **Filtrelemeyi Gizle:** Tablo plugini üzerinde bulunan “Arama” alanının gösterilmesinin belirlendiği ksıımdır.

  3.3. **Başlıkları Sar:** Grafik kolon başlıkları beklenenden uzun geldiğinde boşluklara uygun olarak alt satıra geçirir.

  3.4. **Hücreleri Sar:** Tablo içinde yer alan verilerin 

**4.Başlık Ayarları**

   4.1. **Başlık:** Grafiğe başlık verilen alandır.

   4.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

   4.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

   4.4. **Başlık Yazı Tipi:** Grafik başlığına ilişkin yazı font değişikliğinin yapıldığı alandır.

   4.5. **Başlık Font Boyutu:** Grafik başlığına ilişkin yazı font boyutunun değiştirildiği alandır.

   4.6. **Başlık Font Rengi:** Grafik başlığı font rengi değişikliğinin yapıldığı alandır.

   4.7. **Başlık Özelliklerini Rapordaki Diğer Pluginlere Uygula:** Grafik başlığına uygulanan tüm değişikliklerin rapor ekranında bulunan tüm grafiklere uygulanmasını sağlar. 

**5. Diğer**

   5.1. **Tema Rengi:** Grafik genel görünümde yapılacak renk değişikliği alanıdır.

   5.2. **Excel Olarak İndirmek İstediğiniz Veri Sayısı:** Excel export alındığında tablo plugininden kaç satır veri indirileceğinin belirlendiği alandır.

   5.3. **Tablo Açıklama:** Grafiğe açıklama/bilgi amaçlı yazılacak notların eklendiği alandır.

   5.4. **Link Alanı:** Link verisi bulunan kolon isminin yazıldığı kısımdır. Bu alana link olarak yer alan kolon ismi yazıldığında, tablo grafiğinde bu alanda bulunan linklere gidilebilmektedir.

   5.5. **Link Tasviri:** Tabloda yer alan linkler için açıklama alanıdır. Yazılan metin tüm satırlarda aynı şekilde görüntülenmektedir. Bu alana yazılan “Tıklayınız” gibi tasvirlerle kolonun link olduğu ve tıklandığında ilgili linke gidilebileceği anlaşılmaktadır.

   5.6. **Resimli Link Alanı:** Resim verisi bulunan kolon isminin yazıldığı kısımdır. Bu alana resim olarak yer alan kolon ismi yazıldığında, tablo grafiğinde resimler gösterilmektedir.

   5.6. **Resim Satır Genişliği:** Tablo grafiğinde yer alması istenen resmin tablodaki satır genişliği bilgisinin girildiği alandır.


4.3.1.29. Ağaç Haritası
========================

.. figure:: ./images/103.png
   :alt: image

1. **Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

2. **Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.
   
3. **Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.
   
4. **Koşulsal Formatlama:** Grafik üzerinde tanımlanan belirli bir kural neticesinde verileri gözle daha kolay bir şekilde taramak için renksel biçimlendirmeler yapılan alandır.
   
5. **Etkileşim:** Görselden diğer görsellere filtre verilen alandır.
   
6. **Navigasyon:** Görselden belirlenen parametreye göre navigasyon verilen alandır.
   
7. **Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.
   
8. **Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.
   
**Not:** Koşulsal Formatlama, Etkileşim ve Navigasyon grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Ağaç Harita Grafiği Veri Alanı**

.. figure:: ./images/104.png
   :alt: image

**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

1.1. **Ara:** Tablo ve kolonların arandığı alandır.
 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Grup:** Grafiğin belirlenen grup alanına göre değişiminin görselleştirilmesi için verinin eklendiği alandır.

 2.3. **Ölçü Değeri:** Grafiği şekillendirmek için kullanılacak sayısal verinin eklendiği alandır.

 2.4. **Renge Göre Değişim:** Bu alandaki veriye göre renk değişikliğinin sağlanacağı alandır.

 **Ağaç Harita Grafiği Ayarlar Alanı**

 .. figure:: ./images/105.png
   :alt: image

**1. Genel Görünüm**

 1.1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

 1.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

 1.3. **Font Boyutu:** Grafik yazı boyutunun girildiği alandır.

 1.4. **Yuvarlatılmış Köşeler:** Grafik köşelerinin kenar seçiminin yuvarlak olma durumunun seçildiği alandır.

**2. Diğer**

 2.1. **Başlık:** Grafiğe başlık verilen alandır.

 2.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

 2.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

 2.4. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.


4.3.1.30. Kelime Bulutu
=======================

.. figure:: ./images/106.png
   :alt: image

**1. Araçları Aç/Kapat:** Görsel ile ilgili düzenleme yapılan ikonların açıp kapatıldığı ikondur.

**2. Veri:** Kullanıcının kendi verileriyle görseli şekillendireceği alandır.

**3. Ayarlar:** Görselin renk/başlık gibi biçimsel özelliklerinin değiştirildiği alandır.

**4. Etkileşim:** Görselden diğer görsellere filtre verilen alandır.

**5. Yenile:** Veri alanı ile grafiğin çalışması ve grafiğin yenilenmesini sağlar.

**6. Kaldır:** Görseli silmek için kullanılan alandır. “Kaldır” ikonuna tıklandığında “Bu görseli silmek istiyor musunuz?” şeklinde uyarı çıkmaktadır.

**Not:** Etkileşim grafiklerde ortak olduğundan ayrı başlıkta yer alacaktır.

**Kelime Bulutu Grafiği Veri Alanı**

.. figure:: ./images/107.png
   :alt: image


**1. Tablolar & Kolonlar**

Seçili modelde var olan tablo ve kolonların bulunduğu alandır.

Tablolar & Kolonlar bölümünde yer alan kolonlar, sağ tarafta bulunan bölümlere sürükle-bırak ile eklenir.

 1.1. **Ara:** Tablo ve kolonların arandığı alandır.

 1.2. **Tablo Kolon Listesi:** Seçili modelde yer alan tablo ve kolonların yer aldığı bölümdür.

**2. Kolon Eşleştirmeleri**

 2.1. **Sıralama:** Kolon verisinin artan/azalan şekilde sıralamasının yapıldığı alandır.

 2.2. **Word:** Kolonda bulunan 

  **Ağaç Harita Grafiği Ayarlar Alanı**

.. figure:: ./images/108.png
   :alt: image

**3. Genel Görünüm**

 3.1. **Arka Plan Rengi:** Grafiğe arka plan rengi verilen alandır. Paletten arka plan rengi seçilebilmektedir.

 3.2. **Palet:** Grafik paletten seçilen renklere göre görselleştirilir.

 3.3. **Font Boyutu:** Grafik yazı boyutunun girildiği alandır.

 3.4. **Yuvarlatılmış Köşeler:** Grafik köşelerinin kenar seçiminin yuvarlak olma durumunun seçildiği alandır.

**4. Diğer**

 4.1. **Başlık:** Grafiğe başlık verilen alandır.

 4.2. **Başlık Hizası:** Grafik başlığının sağ/orta/sol hizalamasının seçildiği alandır.

 4.3. **Başlık Yazı Stilleri:** Grafik başlığının kalın/italik/altı çizili olmasının belirlendiği kısımdır.

 4.4. **Koşulsal Formatlamayı Göster:** Koşulsal formatlama varsa ve bu kısım seçildiyse koşullar grafikte gösterilir.

4.3.1.31. Özel
===============