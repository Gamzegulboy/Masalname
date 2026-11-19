# Masalname — Her Masal Bir Dünya

**Programlamaya Giriş | Türk Masalları Derlemesi Web Sayfası**

Masalname, Türk masallarını dijital bir kitaplıkta bir araya getirdiğim web sitesi projemdir. Geleneksel resimli masal kitaplarının havasını, sade ve rahat kullanılabilen bir okuma arayüzüyle birleştirmeyi amaçladım. Masalların kapaklarını ayrı ayrı hazırlayarak her hikâyenin kendine özgü bir görünümü olmasına dikkat ettim.

## Projede neler var?

- 10 Türk masalından oluşan koleksiyon ve masallara özel kapak görselleri
- Masal adına göre arama ve kategori filtreleri
- Favorilere masal ekleme ve favorileri görüntüleme
- Masalları ayrı bir okuma ekranında açma
- Gece/gündüz görünümü ve yazı boyutu ayarı
- Okuma ilerlemesini görme, kaldığım yerden devam etme
- Bilgisayar ve dar ekranlara uyumlu sayfa düzeni

## Dosya yapısı

Önceki vize sürümünde HTML, CSS ve JavaScript tek dosyada bulunuyordu. Bu çalışmada aynı web sayfasını **üç ayrı dosyaya** ayırdım:

```text
Masalname/
├── index.html   # Sayfanın HTML yapısı ve içerik alanları
├── style.css    # Renkler, tipografi, yerleşim, animasyonlar ve mobil görünüm
├── script.js    # Masal verileri ve etkileşimler
└── README.md    # Projenin açıklaması ve çalıştırma bilgisi
```

`index.html` dosyası CSS'yi `<link rel="stylesheet" href="style.css">`, JavaScript'i ise `<script src="script.js"></script>` yoluyla çağırır. Yani stil ve betik kodları artık **haricî dosyalardadır**. Proje yine tek sayfalık bir web sitesidir; yalnızca kodlar daha düzenli dosyalara ayrılmıştır.

## Nasıl çalıştırılır?

1. GitHub'da **Code → Download ZIP** seçeneğiyle depo içeriğini indirip ZIP'i ayıkla.
2. `index.html`, `style.css` ve `script.js` dosyalarının **aynı klasörde** olduğundan emin ol.
3. `index.html` dosyasına çift tıklayarak Chrome, Edge veya Firefox'ta aç.

İnternet bağlantısı ve ayrı bir kurulum gerekmiyor. Masal kapak görselleri proje koduna gömülüdür; ek bir görsel klasörü indirmen gerekmez. Yalnızca `index.html` dosyasını tek başına indirirsen tasarım ve etkileşimler eksik kalır; üç dosya birlikte tutulmalıdır.

## Kullanılan teknolojiler

**HTML5:** Başlık, masal koleksiyonu, arama/filtre alanları ve okuma ekranının yapısı.

**CSS3 (`style.css`):** Renk paleti, tipografi, kartlar, geçişler, esnek yerleşim ve farklı ekran genişliklerine uyum.

**JavaScript (`script.js`):** Masal verilerinin ekrana getirilmesi, arama ve kategori filtreleme, favoriler, okuma ayarları, ilerleme takibi ve etkileşimlerin yönetimi. Tercihlerin bir kısmı tarayıcının `localStorage` alanında saklanır.

Herhangi bir hazır web sitesi şablonu veya haricî JavaScript kütüphanesi kullanılmamıştır.

## Tasarım ve geliştirme süreci

Masal kitabı hissini korumak için sıcak kâğıt tonları, belirgin başlık tipografisi ve hikâyelere özgü illüstrasyonları tercih ettim. Okuma alanında yazıların rahat takip edilebilmesi, masallara kolay ulaşılması ve telefon ekranında da kullanılabilmesi benim için önemliydi. Tasarımı geliştirirken arama, kartlar, favoriler ve okuma ekranı gibi bölümleri kontrol edip görünüm ve kullanım sorunlarını düzelttim.

Vize projesinden bu çalışmaya geçerken sayfanın görünümünü ve işlevlerini değiştirmeden CSS ve JavaScript kodlarını ayrı dosyalara taşıdım. Bunun amacı dosya yapısını düzenlemek ve kodun bakımını kolaylaştırmaktı.

## Yapay zekâ kullanımı

Projenin kod ve görsel geliştirme aşamalarında **ChatGPT** ve görsel üretiminde **Gemini** desteğinden yararlandım. Tasarım tercihlerini, proje içeriğini, kullanılan özellikleri ve yapılan düzeltmeleri çalışmanın ihtiyacına göre belirledim. Bu araçların kullanımına ilişkin açıklamalar vize raporunda da yer almaktadır.

## Proje bağlantıları

- **GitHub deposu:** https://github.com/Gamzegulboy/Masalname
- **Vize sunum videosu:** https://youtu.be/fQR0D-7Fplk

## Proje bilgileri

- **Hazırlayan:** Gamze Gülboy
- **Öğrenci numarası:** 86230031
- **Üniversite:** İstanbul Medipol Üniversitesi
- **Bölüm:** Görsel İletişim Tasarımı
- **Ders:** Programlamaya Giriş

Bu depo, vize projesinin haricî CSS ve JavaScript dosyalarıyla yeniden düzenlenmiş sürümünü içerir. Önceki vize raporu ve sunum videosu da proje arşivinde bulunmaktadır.
