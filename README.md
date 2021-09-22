# covid19-turkiye

**Koronavirüs (Covid-19) Salgınında Türkiye'nin Durumu**

## Tanım

Türkiye'de Koronavirüs'ün (Covid-19) ilk kez **11 Mart 2020** tarihinde görülmesinden itibaren sayıların düzenli olarak tutulduğu veri setleri ve üzerinde veri analizlerini içeren repo'dur.

Genelde ayda iki defa olmak üzere yeni veri analizlerinin uygulanması amaçlanmaktadır.

Son güncelleme: **21 Eylül 2021** **/** Sayı: **40**

**Tüm analizler IPython üzerinde yapılmıştır.**

## Kaynak

Günlere ait tüm bu sayısal veriler T. C. Sağlık Bakanlığı [Covid-19 Bilgilendirme Sayfası](https://covid19.saglik.gov.tr/) **Türkiye COVID-19 Günlük Tablosu**'ndan alınmaktadır.

## Sütunlar

Veri setinin son şeklinde toplamda 15 farklı sütun bulunmaktadır: `Toplam Hasta`, `Toplam Vefat`, `Toplam İyileşen`, `Toplam Test`, `Toplam Yoğun Bakım`, `Toplam Entübe`, `Zatürre Oranı (%)`, `Ağır Hasta`, `Günlük Vaka`, `Toplam Vaka`, `1. Doz Ort(%)`, `2. Doz Ort(%)`, `1. Doz Toplam`, `2. Doz Toplam`, `3. Doz Toplam`

Ayrıca index işlevi gören `Tarih` sütunu da mevcuttur.

Analiz içerisinde oluşturulan ilave sütunlar: `Vefat Artış`, `İyileşen Artış`, `Test Artış`, `Vaka +/-`, `Vefat +/-`, `İyileşen +/-` ve `Test +/-`

## Analizler

Son yayımlanan analizde şunlar bulunmaktadır:
* Son 20 Güne Dair Sayısal Bilgiler
* Covid-19 Salgınının Başında Beri Türkiye'nin Durumu
* Covid-19 - Türkiye'de Aşılamanın Durumu
* Covid-19 - Tüm Günler Vaka, Vefat & İyileşen Artış Sayıları & Gelecek İçin Tahminler
* Son 20 Gün İçindeki Günlük Vaka Sayıları
* Son 20 Güne Dair Toplam Vaka Sayıları
* Son 20 Günün Vaka Sayısı Değişim Grafiği
* Son 20 Gün İçindeki Günlük Vefat Sayıları
* Son 20 Güne Dair Toplam Vefat Sayıları
* Son 20 Günün Vefat Sayısı Değişim Grafiği
* Son 20 Gün İçindeki Günlük İyileşen Sayıları
* Son 20 Güne Dair Toplam İyileşen Sayıları
* Son 20 Günün İyileşen Sayısı Değişim Grafiği 
* Son 20 Gün İçindeki Günlük İyileşen Sayısının Vaka Sayısına Oranı
* Son 20 Günün Toplam Aktif Vaka Sayıları
* Son 180 Güne Dair Günlük Test, Vaka, Vefat & İyileşen Sayılarının İstatistikleri ve Dağılımları
* Son 180 Güne Dair Vaka, Vefat & İyileşen Sayısı Değişimi Dair İstatistikleri ve Dağılımları
* 25 Kasım 2020 Sonrası Günlük Vaka, Vefat ve İyileşen Sayılarının Birbirleriyle İlişkileri ve Katsayıları
* Test, Vaka, Vefat ve İyileşen Artışlarının Aylık Toplamları
* Aynı Sütunların ve Değişimlerinin Aylık Ortalamaları

4 Temmuz 2021'den itibaren gösterilen yeni Günlük Covid-19 Tablosu ile artık **Hasta Sayısı**, **Zatürre Oranı** ve **Ağır Hasta** verileri paylaşılmadığından birtakım analizler en son paylaşılan analizlerden sonra yer almamaktadır!

Bunun yerine **18 Yaş Üstü Nüfus için 1. ve 2. Doz Türkiye Ortalaması (%)** ve **1., 2. ve 3. Doz Uygulanan** sayılarıyla ilgili yeni analizler gösterilmektedir.

**Son bir yıl içinde** yapılan analizler burada gösterilmektedir. Üzerinden bir yıldan fazla süre geçen analizler ise silinmektedir.

Ayrıca, Türkiye'de **illere göre haftalık vaka sayıları**nı gösteren bir veri seti daha mevcuttur. İlerleyen zamanlarda bununla ilgili analizler de yapılacaktır.

**ÖNEMLİ:** İlgili IPython sayfası yüklenirken hata ile karşılaşıyorsanız, bir ya da birkaç kere **Reload** seçeneğine basmanız gerekebilir.

## KORONAVİRÜSÜ TAMAMEN YENDİĞİMİZ GÜNLERDE BULUŞMAK DİLEĞİYLE...
