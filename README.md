# covid19-turkiye

**Koronavirüs (Covid-19) Salgınında Türkiye'nin Durumu**

## Tanım

Türkiye'de Koronavirüs'ün (Covid-19) ilk kez **11 Mart 2020** tarihinde görülmesinden itibaren sayıların düzenli olarak tutulduğu veri setleri ve üzerinde veri analizlerini içeren repo'dur.

Genelde ayda iki defa yeni veri analizlerinin uygulanması amaçlanmaktadır.

Son güncelleme: **3 Temmuz 2021** **/** Sayı: **37**

**Tüm bu analizler IPython üzerinde yapılmıştır.**

## Kaynak

Günlere ait tüm bu sayısal veriler T. C. Sağlık Bakanlığı [Covid-19 Bilgilendirme Sayfası](https://covid19.saglik.gov.tr/) **Türkiye COVID-19 Hasta Tablosu**'ndan alınmaktadır.

## Sütunlar

Veri setinin son şeklinde toplamda 10 farklı sütun bulunmaktadır: `Toplam Hasta`, `Toplam Vefat`, `Toplam İyileşen`, `Toplam Test`, `Toplam Yoğun Bakım`, `Toplam Entübe`, `Zatürre Oranı (%)`, `Ağır Hasta`, `Günlük Vaka` ve `Toplam Vaka`

Ayrıca index işlevi gören `Tarih` sütunu da mevcuttur.

Analiz içerisinde oluşturulan ilave sütunlar şunlardır: `Hasta Artış`, `Vefat Artış`, `İyileşen Artış`, `Test Artış`, `Hasta +/-`, `Vefat +/-`, `İyileşen +/-`, `Vaka +/-` ve `Test +/-`

## Analizler

Son yayımlanan analizde şunlar bulunmaktadır:
* Son 20 Güne Dair Sayısal Bilgiler
* Covid-19 - Türkiye'nin Durumu
* Son 20 Güne Dair Hasta Sayısı Grafiği
* Son 20 Güne Dair Vaka Sayısı Grafiği
* Son 20 Güne Dair Vefat Sayısı Grafiği
* Son 20 Güne Dair İyileşen Sayısı Grafiği
* Son 120 Güne Dair Hasta, Vaka, Vefat, İyileşen & Test Artışları İstatistikleri ve Dağılımları
* Tüm Günler - Hasta, Vaka, Vefat & İyileşen Artış Sayıları + Sonraki Günlere Ait Tahminler
* Son 20 Gün İçindeki Hasta Sayısı Artışları
* Son 20 Gün İçindeki Günlük Vaka Sayısı
* Son 20 Gün İçindeki Vefat Sayısı Artışları
* Son 20 Gün İçindeki Hasta Sayısı Artışları
* Son 20 Gün İçindeki Günlük İyileşen Sayısının Vaka Sayısına Oranı
* Tüm Günler Hasta/Vefat/İyileşen/Günlük Vaka Sayılarının Birbirleriyle İlişkileri ve Katsayıları
* Son 120 Güne Dair Hasta, Vaka, Vefat & İyileşen Sayısı Değişimine Dair İstatistikler
* Son 20 Günün Hasta Sayısı Değişim Grafiği
* Sün 20 Günün Vaka Sayısı Değişim Grafiği
* Son 20 Günün Vefat Sayısı Değişim Grafiği
* Son 20 Günün İyileşen Sayısı Değişim Grafiği
* Son 20 Günün Toplam Aktif Vaka Sayıları
* Son 30 Gün için Hastalarda Zatürre Oranı ve Ağır Hasta Sayıları
* Hasta, Vefat, İyileşen, Test ve Vaka Artışlarının Aylık Toplamları
* Aynı Sütunların ve Değişimilerinin Aylık Ortalamaları

4 Temmuz 2021'den itibaren gösterilen yeni Günlük Covid-19 Tablosu ile artık **Hasta Sayısı**, **Zatürre Oranı** ve **Ağır Hasta** verileri paylaşılmadığından birtakım analizler en son paylaşılan sayıdan sonra yer almayacaktır!

Bunun yerine **18 Yaş Üstü Nüfus için 1. ve 2. Doz Türkiye Ortalaması (%)** ve **1., 2. ve 3. Doz Uygulanan** sayılarıyla ilgili yeni analizler gösterilecektir.

Ayrıca, Türkiye'de **illere göre haftalık vaka sayıları**nı gösteren bir veri seti daha mevcuttur. İlerleyen zamanlarda bununla ilgili analizler de yapılacaktır.

**ÖNEMLİ:** İlgili IPython sayfası yüklenirken hata ile karşılaşıyorsanız, bir ya da birkaç kere **Reload** seçeneğine basmanız gerekebilir.

## KORONAVİRÜSÜ TAMAMEN YENDİĞİMİZ GÜNLERDE BULUŞMAK DİLEĞİYLE...
