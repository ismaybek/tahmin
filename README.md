# Hangisi Daha Pahalı?

Retro arcade tarzında bir fiyat tahmin oyunu. Ekranda iki ürün çıkar, hangisinin daha pahalı olduğunu bulursun. Yayıncıların canlı yayında oynayabilmesi için tasarlandı.

## Modlar

- **Seri:** 3 can. Art arda bildikçe combo çarpanı artar.
- **10 Tur:** 10 soru, en yüksek puan.
- **Yayıncı vs Chat:** Her turda 15 saniyelik sayaç. Chat 1 ya da 2 yazar, yayıncı çoğunluğu işaretler, sonra kendi tahminini yapar.

## Fiyat paketleri

- **Türkiye:** Market, ulaşım, akaryakıt, teknoloji, abonelik, otomobil, kira, altın ve döviz fiyatları.
- **Dünya:** 60'tan fazla ülke. 55 ülkede Big Mac, 23 ülkede iPhone 18 Pro, ABD market fiyatları (süt, yumurta, patates, kıyma, kahve...), elektrik, spor salonu, asgari ücret. Turların çoğu "aynı ürün, farklı ülke" karşılaştırmasıdır.
- **Karışık:** İkisi bir arada. Aynı ürünün Türkiye ve yurt dışı fiyatları sık sık karşılaşır.

Fiyatlar Ekim 2026 itibarıyla derlendi. Yabancı fiyatlar TCMB'nin 20 Ekim 2026 döviz satış kuruyla TL'ye çevrildi; TCMB'nin yayınlamadığı para birimleri The Economist'in Temmuz 2026 dolar kuru üzerinden çevrildi. ABD fiyatlarına satış vergisi dahil değildir.

### Kaynaklar

- **Big Mac:** [The Economist Big Mac Index](https://github.com/TheEconomist/big-mac-data), Temmuz 2026 (MIT lisansı, © The Economist Newspaper).
- **ABD market ve elektrik:** U.S. Bureau of Labor Statistics ortalama fiyat verisi (FRED üzerinden).
- **Türkiye sebze:** TZOB Eylül 2026 market fiyatları. **Kıyma:** Et ve Süt Kurumu.
- **iPhone 18 Pro:** Apple lansman fiyatları (Business Today derlemesi).
- **Döviz:** TCMB, 20 Ekim 2026.

Türkiye listesi kaynaklarıyla `data/fiyatlar-ekim-2026.xlsx`, dünya listesi `data/dunya-fiyatlari.csv` dosyasında. Big Mac verisinin MIT lisans metni `data/licenses/big-mac-data-MIT.txt` dosyasındadır. Numbeo verisi kullanılmamıştır (kullanım şartları ticari kullanıma ve otomatik veri toplamaya izin vermiyor).

## Çalıştırma

Kurulum gerekmez. `index.html` dosyasını tarayıcıda aç ya da GitHub Pages ile yayınla.

## Kontroller

- `1` / `2` veya sol / sağ ok: kart seç
- `Boşluk` / `Enter`: sonraki tur

## Marka notu

Big Mac, iPhone, PlayStation, Netflix, Spotify, Togg ve diğer ürün adları sahiplerinin ticari markalarıdır. Oyunda yalnızca fiyat karşılaştırması için ürünü tanımlamak amacıyla geçer; logo veya marka görseli kullanılmaz ve markalarla bir bağlantı ya da sponsorluk iddiası yoktur.
