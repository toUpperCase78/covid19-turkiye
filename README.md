# covid19-turkiye

**Koronavirüs (Covid-19) Salgınında Türkiye'nin Durumu**

## Tanım

Türkiye'de Koronavirüs'ün (yani Covid-19'un) ilk kez **11 Mart 2020** tarihinde görülmesinden itibaren sayıların düzenli olarak tutulduğu veri setleri ve üzerinde veri analizlerini içeren repo'dur.

Sonraki günlere ait verilerin mevcut olmasıyla beraber haftada bir ya da on günlük aralıklarla veri analizinin güncellenmesi amaçlanmaktdır.

Son güncelleme: **12 Ağustos 2020**

**Tüm bu analizler IPython Shell kullanılarak yapılmıştır.**

## Sütunlar

Veri setinde sayıları bulunduran 6 farklı sütun bulunmaktadır: `Toplam Vaka`, `Toplam Vefat`, `Toplam İyileşen`, `Toplam Test`, `Toplam Yoğun Bakım`, `Toplam Entübe`

29 Temmuz'dan sonra yeni verilerin paylaşılmasıyla birlikte 2 yeni sütun daha eklenmiştir: `Hastalarda Zatürre Oranı (%)` ve `Ağır Hasta`

Ayrıca index işlevi gören `Tarih` sütunu da mevcuttur.

Analiz içerisinde oluşturulan ilave sütunlar şunlardır: `Vaka Artış`, `Vefat Artış`, `İyileşen Artış`, `Test Artış`, `Vaka +/-`, `Vefat +/-`, `İyileşen +/-`

## Analizler

Son yayımlanan analizde şunlar bulunmaktadır:
* Son 14 Güne Dair Sayısal Bilgiler
* Tüm Günler Türkiye'nin Durumu
* Son 2 Haftaya Dair Vaka Sayısı Grafiği
* Son 2 Haftaya Dair Vefat Sayısı Grafiği
* Son 2 Haftaya Dair İyileşen Hasta Sayısı Grafiği
* Vaka, Vefat, İyileşen & Test Artışlarına Dair İstatistikler
* Tüm Günler - Vaka, Vefat & İyileşen Artış Sayıları + Sonraki 28 Güne Ait Tahminler
* Son 2 Hafta İçindeki Vaka Sayısı Artışları
* Son 2 Hafta İçindeki Vefat Sayısı Artışları
* Son 2 Hafta İçindeki İyileşen Hasta Sayısı Artışları
* Son 2 Hafta İçindeki Günlük İyileşen Sayısının Vaka Sayısına Oranı
* Tüm Günler Vaka/Vefat/İyileşen Sayılarının Birbirleriyle İlişkileri ve Katsayıları
* Her Gün Vaka, Vefat & İyileşen Sayısı Değişimine Dair İstatistikler
* Son 2 Haftadaki Vaka Sayısı Değişim Grafiği
* Son 2 Haftadaki Vefat Sayısı Değişimi Grafiği
* Son 2 Haftadaki İyileşen Sayısı Değişim Grafiği
* Son 2 Haftadaki Toplam Aktif Vaka Sayıları
* 27 Mart-28 Temmuz Tarihleri Arasında Toplam Yoğun Bakım ve Entübe Hasta Sayılarına Dair İstatistikler
* 1-28 Temmuz Tarihlerinde Toplam Yoğun Bakım & Entübe Hasta Sayıları
* 29 Temmuz ve Sonrasında Hastalarda Zatürre Oranı ve Ağır Hasta Sayıları Grafiği
* Vaka, Vefat, İyileşen & Test Artışlarının Haftalık Toplamları
* Aynı Sütunların ve Değişimilerinin Haftalık Ortalamaları

## Kaynak

Günlere ait tüm bu sayısal veriler T. C. Sağlık Bakanlığı ve Sağlık Bakanı Dr. Fahrettin Koca'nın Twitter'da yayımladığı **Türkiye Günlük Koronavirüs Tablosu**'ndan alınmaktadır.

### Virüsü tamamen yendiğimiz günlerde buluşmak dileğiyle...
