# Hangisi Daha Pahalı?

Retro arcade tarzında bir fiyat tahmin oyunu. İki ayrı oyun var: 300 fiyatlı **ana oyun** ve 257 fiyatlı **Stil & Yaşam** oyunu. Ekranda iki ürün çıkar, hangisinin daha pahalı olduğunu bulursun. Yayıncıların canlı yayında oynayabilmesi için tasarlandı.

## Oyunlar

- **Ana oyun:** Türkiye, Dünya ve Karışık paketleri (300 fiyat).
- **Stil & Yaşam:** Ana oyundan tamamen ayrı veri. Moda (Zara Türkiye), lüks çanta ve saat (Chanel, Louis Vuitton, Rolex ABD resmi fiyatları), ev ve dekorasyon (IKEA Türkiye), evcil hayvan (mama, veteriner taban ücret tarifesi), kafe (Kahve Dünyası), seyahat (müze ve saray biletleri) ve konser biletleri (Harbiye, Volkswagen Arena, Avrupa turneleri). Güzellik tarafı: Gratis ve Watsons'tan makyaj, cilt, saç, parfüm, deodorant, tıraş, ağız bakımı, güneş ürünleri ve bakım cihazları; Chanel N°5 (5 ülke), Dyson Airwrap (3 ülke), güzellik salonu hizmetleri, takı ve düğün masrafları. Kartlarda mağaza adı yazar.

## Modlar

- **Seri:** 3 can. Art arda bildikçe combo çarpanı artar.
- **10 Tur:** 10 soru, en yüksek puan.
- **Yayıncı vs Chat:** Her turda 15 saniyelik sayaç. Chat 1 ya da 2 yazar, yayıncı çoğunluğu işaretler, sonra kendi tahminini yapar.

## Fiyat paketleri

- **Türkiye:** 188 kalem. Market (sebze, çay, şeker, yağ, peynir...), sokak lezzetleri (simit, lahmacun, döner), resmi harçlar ve cezalar (pasaport, IMEI kaydı, bedelli askerlik, kırmızı ışık), ulaşım ve otoyol, eğlence (GTA 6, sinema, Süper Lig kombineleri), sigara ve rakı, berber, kira ve konut, otomobil, altın ve döviz.
- **Dünya:** 60'tan fazla ülke. 55 ülkede Big Mac, 23 ülkede iPhone 18 Pro, ABD market fiyatları (süt, yumurta, patates, kıyma, kahve...), elektrik, spor salonu, asgari ücret. Her turda iki farklı ürün, çoğunlukla iki farklı ülkeden gelir.
- **Karışık:** İkisi bir arada.

Fiyatlar Ekim 2026 itibarıyla derlendi. Yabancı fiyatlar TCMB'nin 20 Ekim 2026 döviz satış kuruyla TL'ye çevrildi; TCMB'nin yayınlamadığı para birimleri The Economist'in Temmuz 2026 dolar kuru üzerinden çevrildi. ABD fiyatlarına satış vergisi dahil değildir.

### Kaynaklar

- **Big Mac:** [The Economist Big Mac Index](https://github.com/TheEconomist/big-mac-data), Temmuz 2026 (MIT lisansı, © The Economist Newspaper).
- **ABD market ve elektrik:** U.S. Bureau of Labor Statistics ortalama fiyat verisi (FRED üzerinden).
- **Türkiye sebze:** TZOB Eylül 2026 market fiyatları. **Kıyma:** Et ve Süt Kurumu.
- **iPhone 18 Pro:** Apple lansman fiyatları (Business Today derlemesi).
- **Döviz:** TCMB, 20 Ekim 2026.

Türkiye listesi kaynaklarıyla `data/fiyatlar-ekim-2026.xlsx` ve `data/turkiye-ek-fiyatlar.csv`, dünya listesi `data/dunya-fiyatlari.csv`, Stil & Yaşam listesi `data/stil-yasam.csv` dosyasında. Big Mac verisinin MIT lisans metni `data/licenses/big-mac-data-MIT.txt` dosyasındadır. Numbeo verisi kullanılmamıştır (kullanım şartları ticari kullanıma ve otomatik veri toplamaya izin vermiyor).

## Çalıştırma

Kurulum gerekmez. `index.html` dosyasını tarayıcıda aç ya da GitHub Pages ile yayınla.

## Tur kuralları

- İki ürünün fiyat farkı her zaman en az %5'tir; tahmin edilemeyecek kadar yakın fiyatlar karşılaşmaz.
- Aynı ürünün versiyonları (iPhone kapasiteleri, Chanel N°5 boyları, Netflix paketleri, pasaport süreleri, "simit" ve "1 yıl her gün simit" gibi) aynı turda çıkmaz.
- Aynı ürünün farklı ülke ya da mağazadaki fiyatı da aynı turda çıkmaz (Big Mac Türkiye–ABD, Flormar kapatıcı Gratis–Watsons gibi).

## Kontroller

- `1` / `2` veya sol / sağ ok: kart seç
- `Boşluk` / `Enter`: sonraki tur

## Marka notu

Big Mac, iPhone, PlayStation, Netflix, Spotify, Togg ve diğer ürün adları sahiplerinin ticari markalarıdır. Oyunda yalnızca fiyat karşılaştırması için ürünü tanımlamak amacıyla geçer; logo veya marka görseli kullanılmaz ve markalarla bir bağlantı ya da sponsorluk iddiası yoktur.
