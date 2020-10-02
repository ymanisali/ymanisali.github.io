# ProMans Tekstil Bilgi Yönetim Sistemi

## Nayka Tekstil San. ve Tic. Ltd. Şti.

[`Yenilikler`](#yenilikler)
[`Scripting`](#scripting)

### Yenilikler

#### 1.0.0.10 ()
- Aksesuar Detay formunda tedarikçi ekleme yapabilmek için ilgili kısma ***Yeni*** butonu eklendi. Bununla bir diyalog formu ile yeni firmanın bilgileri alınıp sisteme ekleniyor.
- *Müşteri ve Firma* tanımlamada otomatik sayaç eklendi.
- 

#### 1.0.0.9 (14 Ağustos 2020)
- Renk/Baskı listesinde kumaş tedarikçiler de eklendi.
- Müşteri Adres ve İletişim bilgilerinin tanımlanmasında boş karakterler bırakılabiliyor, bunları düzeltecek değişiklikler yapıldı.
- Aksesuar Özellik sisteminde iyileştirmeler yapıldı.
- Koliler için hacim ve dara özellikleri eklendi.
- Renk/Baskı listesinde *Müşteri* ve *Firma Id*'leri için alanlar değiştirildi.
- Renk/Baskı listesine *Türkçe Ad* alanı eklendi.

#### 1.0.0.8 (20 Temmuz 2020)
- Aksesuar Grup tanımlamada `Null` hatası düzeltildi.
- Aksesuar Tanımlama listesinde *Tanım* alanı kilitli hale getirildi.
- Aksesuar Detay Formunun düzeninde değişiklikler yapıldı.
- Aksesuar Belge eklenmesinde *Ekleyen Kullanıcı*, *Eklenme Tarihi* detayları eklendi.
- Aksesuar Çoğaltma işlemine detaylar ve belgeler eklendi.

#### 1.0.0.7 (15 Temmuz 2020)
- Aksesuar Grup tanımlamada düzeltmeler yapıldı.
- Scripting notlarına eklemeler yapıldı.
- Sayaçlara otomatik id ataması için *Atama* sütunu eklendi.
- Aksesuar Tanımlamada düzeltmeler yapıldı.
- Aksesuar Detay formu tasarlandı, Grup tanımlama da yapılanlara göre güncellendi.
- MinIO döküman sunucusu çalışmaya başladı.
- Aksesuar Detay formunda dökümanların eklenmesi ile ilgili işlemler eklendi.

#### 1.0.0.6 (06 Temmuz 2020)
- Müşteri Tanımlamada *Id* hatası düzeltildi. Eksik alanlar eklendi.
- Gereksiz uzunluktaki alanlar temizlendi.

#### 1.0.0.5 (06 Temmuz 2020)
- Firma kartında *Id* izin hatası giderildi.
- Kullanıcı kartında yetki eklemede oluşan sorun giderildi.
- **Ödeme Kodlama** eklendi. *Tanımlamalar* menüsü altında bulabilirsiniz.
- **Döviz Cinsi** tanımları programa sabitlenmiş bir şekilde eklendi.
- **Teslim Şekli** tanımlamaları programa sabitlenmiş şekilde eklendi.
> Sabitlenmiş bölümler program kodunun içerisine kodlanmış halde tasarlanıyor, bunlarda bir değişiklik yapılması gerekiyorsa programda güncelleme ile yapılabilir.

#### 1.0.0.4 (03 Temmuz 2020)
- **Müşteri Tanımlamaları** ile **Firma Tanımlamaları** birbirinden ayrıldı. Database'deki ayırma işlemleri yapıldı.
> 01.07.2020 tarihli görüşmemizde müşteri firmalar için **Teslim Şekli**, **Ödeme Şekli** ve **Döviz Cinsi** alanlarının müşteri için gerekli olduğunu tespit ettik. Tedarikçi firmalar için böyle bir durum gerekli değil. Ayrıca birden fazla adres, telefon ve referans tedarikçiler için gerekli değil. Bu cari kart tiplerinin gerekli oldukları bölümler de birbirinden farklı olduğu için böyle bir işlem yapıldı.

#### 1.0.0.3 (30 Haziran 2020)
- Yenilikler diyaloğu daha anlaşılır olması için web formatına taşındı.
> Tüm bilgisayarlar Windows 10 olmadığı için dahili formda çalışmıyor.
- **Grup Kodlama** tanımlamalar menüsünü eklendi. Bu bölüm içinde *Scripting Engine* eklendi.
- **Aksesuar Kodlama** menüye eklendi. İçeriği aktif değil.
- Kullanıcı Tanımlamalarında *Çoğaltma* ve *Yetki* dağıtma için fonksiyonlar eklendi. Bölümdeki `İşlem` menüsünden bu fonksiyonlara erişilebilir.
- Sistemin günlük olarak eklediği kurları görüntüleyen **Kur** bölümü `Sistem` menüsü altında *admin* veya *root* yetkisine sahip kullanıcılar görüntüleyebilir. Talep gelirse bu yetki durumunu değiştirebiliriz.
- Sunucu değişimi yapıldı. Bununla ilgili ayarlamalar da yapıldı.

#### 1.0.0.2 (15 Haziran 2020)
- Taşıyıcı formun açılış tipi düzeltildi.
- Firma kategorileri için altyapı eklendi.
- Yetki dağıtım altyapısı aktif hale getirildi.
- **Firma Kodlama** eklendi. Detay formu aktif halde.
- **Kumaş Kodlama** eklendi. Detay formu eklendi.
- **Renk ve Baskı Kodlama** eklendi.
- Kumaş ve Renk/Baskı için **Çoğaltma** fonksiyonları tamamlandı.

#### 1.0.0.1 (2 Haziran 2020)
- **Başlangıç Formu** fonksiyonları tanımlandı.
- **Yenilikler** diyaloğu eklendi.
> Başlangıç formunda sağ alt köşede buton ile ulaşılabilir.

#### 1.0.0.0 (29 Mayıs 2020)
- Başlangıç versiyonu.
- Taşıyıcı ve giriş formları hazırlandı.
- Setup formları eklendi.
- Sistem fonksiyonları çalışır hale getirildi.
- Logger, Data Model eklendi.

### Scripting

#### Özellikler
Bu kısımda aksesuar kartlarının özellikleri için çalışacak olan kod düzenlenebilir. Sol taraftaki özellik listesini düzenleyebiliriz. *Örnek* sütununda yazılan değerler script'i test etmek için kullanılabilir. Sağ üstte yer alan *Örnek* butonu ile script çalıştırılıp test edilebilir. *Test* butonu şu anda aktif değildir. Yapılan örnek testin sonucu altta yer alan kutuda görüntülenir.

#### Örnek Kodlar
Malzemenin özelliklerine ulaşmak için, 
```csharp
Dictionary["ÖzellikAdı"]
```
şeklinde kullanım yapılabilir. İlgili aksesuarın koduna ve adına `Code` ve `Name` ifadeleri ile ulaşılabilir. `Message` ifadesi kullanarak aksesuar kartı kodlayana ekran mesajı iletilebilir.
Etiket için örnek kod bloğu:
```csharp
var result = Dictionary["Katlama"] + " " + Dictionary["Karışım"];
return result;
```
Hacim hesaplama örneği:
```csharp
var hacim = (Convert.ToInt32(Dictionary["En (mm)"]) / 100) * (Convert.ToInt32(Dictionary["Boy (mm)"]) / 100) * (Convert.ToInt32(Dictionary["Yükseklik (mm)"]) / 100);
Dictionary["Hacim"] = hacim.ToString();
var result = Dictionary["Kalite"] + " " + Dictionary["Özellik"];
```
Kodlama yapan kullanıcıya mesaj bildirmek ve malzemenin özelliklerine ulaşmak için alttaki kod kullanılabilir.
```csharp
var result = Dictionary["Katlama"] + " " + Dictionary["Karışım"];
Message = Code + " kod'lu malzeme tanımlaması yapıyorsunuz";
return result;
```
Alttaki örnek özelliklerin boş olup olmadıklarını kontrol ediyor:
```csharp
var result = Dictionary["Malzeme"];

if (!String.IsNullOrEmpty(Dictionary["Katlama"]))
    result = result + " (" + Dictionary["Katlama"] + " Katlama)";

if (!String.IsNullOrEmpty(Dictionary["Karışım"]))
    result = result + " {" + Dictionary["Karışım"] + "}";

return result;

// Code             ==> XYZ-123
// Name             ==> PROMANS
// Description      ==> JAPON AKMAZ (ORTA Katlama) {%90PAMUK %10POLYESTER}     
// Group            ==> BASKI ETİKET
// Message          ==> ""
```

#### Referans

##### Temel Değişkenler
Kod                         | İşlevi
--------------------------- | ---------------------------------
Dictionary["ÖzellikKodu"]   | Girişi yapılan aksesuarın tırnak içinde belirtilen özelliğine erişim sağlar.
Code                        | İlgili aksesuarın koduna erişim sağlar.
Name                        | İlgili aksesuarın kullanıcı tarafından serbestçe yazabildiği isme ulaşır.
Description                 | Buraya yazılacak kod tarafından otomatik olarak oluşturulacak ifadenin yerleştirileceği alandır.
Group                       | İlgili aksesuarın grup adına ulaşım sağlar.
Message                     | Aksesuar Detay bölümünde ilgili kart üzerinde düzenleme yaparken kullanıcıya mesaj iletmek için kullanılabilir.

Bunların dışında kodun içinde kullanmak için değişken tanımlanabilir. Bunu `var`, `string`, `int`, `float` değişken tanımlamaları ile oluşturabilirsiniz.

##### Metin İşleme Komutları
Bu ifadeler yukarıda belirtilen veya "Metin" türündeki değişkenlere uygulanabilir. Değişkenlerin sonuna alttaki gibi nokta koyularak erişilir.
Kod            | İşlevi
---------------|------------------------------------------------------------
.Trim()        | İfadenin sonundaki ve başındaki fazla boşlukları kaldırır.
.ToUpper()     | İfadenin tamamını büyük harfe çevirir.
.ToLower()     | İfadenin tamamını küçük harfe çevirir.
.ToString()    | Sayısal türde oluşan verileri metin türüne çevirir.

Alttaki örnek ilgili aksesuarın *Katlama* özelliğine erişip ifadenin sonunda ve başında var ise fazla karakterleri silip alır.
```csharp
Dictionary["Katlama"].Trim();
```

##### Kontrol ve Dönüştürme İfadeleri
Kod                          | İşlevi
-----------------------------|---------------------------
String.IsNullOrEmpty(İfade)  | İfade ile belirtilen değişkenin boş olup olmadığını kontrol eder. *if* ile kullanılır.
Convert.ToInt32(İfade)       | İfade ile belirtilen değişkeni sayısal türde veriye dönüştürür. Çarpma, bölme gibi matematiksel işlemlerde kullanılır.
String.Join(Array, ',')      | Array adındaki dizideki bilgileri sağda belirtilen karakter ile birleştirip tek bir ifade oluşturur.
.Split(';')                  | Bu ifade birleştirilmiş ifadeleri belirtilen karakterden bölmek için kullanılır. Çıktı olarak bir dizi verir.

Alttaki örnek *Katlama* özelliğinin boş olup olmadığını kontrol eder. Boş ise `true` değerini döndürdüğü için ifadenin başında `!` işareti bulunur. Bu ifadenin tersini alır. Yani alan boş değilse `{`, `}` parantezleri arasındaki ifade çalıştırılır. Bu ifade de var ise fazla boşlukları atıp özellikteki yazan bilgiyi `Description` alanına ekler.
```csharp
if (!String.IsNullOrEmpty(Dictionary["Katlama"]))
{
	Description += Dictionary["Katlama"].Trim();
}
```
##### Karşılaştırma Operatörleri
Altta yer alan tablodaki ifadeler `if` kontrol bloğu içinde kullanılabilen karşılaştırma operatörleridir.
Operatör | İşlevi
-------- | --------------------------------------
==       | Eşitlik kontrolü yapar. Sağındaki ve solundaki ifade eşit ise `true` değeri verir.
>        | Büyüklük kontrolü yapar. Soldaki değer, sağdakinden büyük ise `true` değeri verir.
<        | Küçüklük kontrolüdür. Üsttekinin tam tersi.
>=       | Büyük eşittir.
<=       | Küçük eşittir.
!=       | Eşit değildir. Sağdaki ve soldaki ifadeler farklı ise `true` değeri verir.
!        | Değildir operatörü, yukarıdaki örnekte yer almıştı, tek bir ifadenin tersini alır.
&&       | Ve karşılaştırma operatörü (AND)
II      | Veya operatörü (OR)

##### Atama Operatörleri
Altta yer alan operatörler atama yapmak için kullanılır.
Operatör | İşlevi
-------- | --------------------------------------
=        | Atama operatörü, sağ taraftaki ifadeyi soldakine yerleştirir.
+=       | Ekleme yaparak atama yapar, yani sağdaki ifade soldakinin üzerine eklenir. Sayısal alanlarda toplama yapar, metin ifadelerde sonuna ekleme yapar.
-=       | Çıkarma yaparak atama yapar.
