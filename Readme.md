```markdown
# 🚀 E-Learning HTML5 Şablon Deposu (Storyline 360 Uyumlu)

Bu depo (repository), eğitim teknolojileri (E-Learning) projelerinde kullanılmak üzere geliştirilmiş, yüksek etkileşimli, tam duyarlı (responsive) ve Articulate Storyline 360 ile haberleşebilen modüler HTML5 etkinlik/konu anlatımı şablonlarını içerir.

Bu projenin temel amacı; eski, kırılgan ve hardcoded (sabit kodlu) yazılmış eğitim materyallerini; **veriye dayalı (data-driven)**, **hata toleranslı (zırhlı)** ve **kolay özelleştirilebilir** tek sayfalık HTML şablonlarına dönüştürmektir.

---

## 📁 Klasör ve Dosya Mimarisi

Proje dizini aşağıdaki gibi organize edilmiştir:

```text
E-Learning-Deposu/
│
├── index.html                       # Tüm arşivi tek ekranda sunan, iFrame tabanlı önizleme ve yönetim paneli.
│
├── 📂 Orijinal_Referanslar/         # Eski, dönüştürülmemiş "Ham" kaynak kodları. AI modelleri için referans niteliğindedir.
│   ├── Etkinlik_Ham/                # Eski etkinlik JS/HTML dosyaları
│   └── Konu_Anlatimi_Ham/           # Eski konu anlatımı JS/HTML dosyaları
│
├── 📂 Sablonlar_Etkinlik/           # YAPAY ZEKA TARAFINDAN OPTİMİZE EDİLMİŞ ŞABLONLAR
│   ├── etk_01_bosluk_doldurma.html  # Temel Boşluk Doldurma, Sınıflandırma
│   ├── etk_02_dogru_yanlis.html     # Temel Doğru/Yanlış ve Eşleştirme Varyasyonları (02-12)
│   ├── etk_13_coktan_secmeli...     # Çoktan Seçmeli, Test ve İnteraktif Buton etkinlikleri
│   ├── etk_18_cengel_bulmaca...     # Kompleks Veri Girişi, Grid Bulmacalar ve Şifre Çözme
│   └── etk_20_zaman_cizelgesi...    # Gelişmiş Sıralama (Timeline), Gruplama ve Akordeon Testler
│
└── 📂 Sablonlar_Konu_Anlatimi/      # (Gelecekte Eklenecek) Optimize edilmiş konu anlatım modülleri.

```

---

## 🎯 Pedagojik Kullanım Rehberi (Hangi Şablon Nerede Kullanılmalı?)

İçerik geliştiriciler ve Yapay Zeka (AI) ajanları, bir kazanımı veya konuyu dijitalleştirecekleri zaman konunun yapısına uygun şablonu bu listeden seçmelidir:

### 1. Temel Etkinlikler (Kavrama, Hatırlama ve İlişkilendirme)

* **`etk_01_bosluk_doldurma.html` (Sürükle-Bırak Boşluk Doldurma):** Tanımları, temel terimleri ve okuduğunu anlama metinlerini ölçmek için kullanılır. Metin içindeki kilit kelimelerin akılda kalmasını sağlar.
* **`etk_02_dogru_yanlis.html` (Temel D/Y Seçimi):** Yaygın yanılgıları çürütmek ve hızlı bilgi kontrolü yapmak için idealdir.
* **`etk_03_eslestirme_temel.html` (Metin-Metin Eşleştirme):** Kavram-Açıklama, Yazar-Eser gibi birebir ilişkili soyut bilgilerin öğrenilmesinde kullanılır.
* **`etk_04_eslestirme_gorselli.html` (Görsel-Metin Eşleştirme):** Görsel tanıma (visual recognition) gerektiren konular için (Örn: harita, anatomi, işaretler) kullanılır.
* **`etk_05_kategori_gruplama.html` (Sürükle-Bırak Sınıflandırma):** Maddeleri ortak özelliklerine göre ayırma (Örn: Canlı/Cansız) gibi tasnif yeteneğini geliştirir.
* **`etk_06_dogru_yanlis_grup.html` (Çoklu Doğru/Yanlış Listesi):** Birden fazla ifadenin ardışık olarak değerlendirildiği, öğrencinin bir bütün içindeki doğruları ve yanlışları hızlıca ayırt etmesini sağlayan tarama testleridir.
* **`etk_07_dogru_yanlis_gorselli.html` (Görsel Odaklı D/Y):** Doğrudan bir şema, fotoğraf veya grafik verilerek öğrencinin "Görseldeki durum doğru mu, yanlış mı?" kararını vermesini sağlayan görsel okuryazarlık etkinlikleridir.
* **`etk_08_dogru_yanlis_anlik.html` (Anında Dönütlü D/Y):** Sınav amacı gütmeyen, öğrenci butona bastığı anda açıklama baloncuğu açarak konuyu o an öğreten (formative) pekiştirme kurgularıdır.
* **`etk_09_eslestirme_surukle_birak.html` (Serbest Sürüklemeli Eşleştirme):** Öğrencinin terimleri fiziksel olarak taşıyıp hedeflerin üzerine bıraktığı, motor becerileri ve etkileşimi en üst düzeye çıkaran eşleştirmelerdir.
* **`etk_10_eslestirme_cizgili.html` (Çizgi Çekerek Eşleştirme):** İki farklı sütundaki öğeler arasında dijital bir kalemle bağ/çizgi kuruyormuş hissi veren, sebep-sonuç ilişkilerini görselleştiren mekaniktir.
* **`etk_11_eslestirme_tablo.html` (Matris/Tablo Eşleştirme):** Satır ve sütunların kesiştiği noktalarda (Örn: Maddenin halleri ve özellikleri) çoklu eşleştirme yaptıran analitik düşünme şablonudur.
* **`etk_12_eslestirme_kavram.html` (Kavram Ağı Eşleştirme):** Terimlerin alt alta değil, bir zihin haritası veya işlem şeması üzerinde doğru kutulara yerleştirildiği sentez aşaması etkinlikleridir.

### 2. Çoktan Seçmeli Serisi (Analiz ve Karar Verme)

* **`etk_13_coktan_secmeli_grid.html` (Izgara Tipi Çoklu Seçim):** Bir soruya ait birden fazla doğru cevabın olduğu durumlarda (Örn: "Hangileri yenilenebilir enerji kaynağıdır?") kullanılır.
* **`etk_14_gorsel_uzeri_nokta_secimi.html` (Görsel Hotspot):** Geometri, harita okuma veya anatomide tam bir koordinat/bölge seçtirmek için kullanılır.
* **`etk_15_resimli_kart_secimi.html` (Yatay Resimli Kartlar):** Fotoğraflara bakarak doğru olan(lar)ı seçtirmek için tasarlanmış görsel odaklı testlerdir.
* **`etk_16_coktan_secmeli_liste.html` (Klasik Liste Testi):** Yanda veri/grafik varken, diğer yanda klasik A, B, C, D şıklarının bulunduğu test formlarıdır.

### 3. Kompleks Girişler ve Oyunlaştırma (Uygulama ve Sentez)

* **`etk_17_sesli_ilerleme_listesi.html` (İnteraktif Kavram Öğreticisi):** Bir konuya giriş yaparken, terimleri sesli olarak dinletmek ve kontrollü ilerleme (Tutorial) sağlamak için kullanılır.
* **`etk_18_cengel_bulmaca.html` (Çengel Bulmaca):** Ünite sonlarında kelime dağarcığını oyunlaştırma ile test eden interaktif ızgara sistemidir.
* **`etk_19_test_ve_ozet_ekrani.html` (Özet Raporlu Mini Deneme):** Bölüm sonlarında öğrencinin genel performansını ölçmek ve dairesel grafikli bir karne (dashboard) sunmak için kullanılır.

### 4. Sıralama ve İleri Gruplama (Mantıksal Çıkarım)

* **`etk_20_zaman_cizelgesi_siralama.html` (Timeline Order):** Olayları, deney adımlarını veya tasarım süreçlerini kronolojik/mantıksal bir sıraya koymak için kullanılır.
* **`etk_21_gelismis_gruplandirma.html` (Çeldiricili Gruplama):** Hiçbir gruba ait olmayan (çeldirici) elemanların konduğu, ezberi bozan ileri seviye sınıflandırma etkinlikleridir.
* **`etk_22_yatay_slider_test.html` (Adım Adım Senaryo Testi):** Birbirine bağlı soruların sorulduğu ve ekranın yatay olarak kaydığı hikayeleştirilmiş problem çözüm arayüzüdür.
* **`etk_23_satir_tipi_secim.html` (Satır Bazlı Karar Verme):** Listelenen her bir satır için ayrı ayrı hesaplama ve karar verilmesi gereken yoğun pratik şablonudur.

---

## 🧠 Yapay Zeka İçin Geliştirici Rehberi (AI Developer Guide)

> **CRITICAL INSTRUCTION FOR AI AGENTS:**
> If you are an AI assistant reading this repository to modify or create new templates, you MUST adhere to the following architectural rules.

Bu depodaki tüm güncel şablonlar (`Sablonlar_Etkinlik` klasörü) aşağıdaki 4 temel prensibe göre inşa edilmiştir:

### 1. Tek Dosya Yapısı (Single-File Architecture)

Şablonlar harici CSS veya JS dosyası çağırmaz. Tüm stil işlemleri **Tailwind CSS (CDN)** ve `<style>` etiketleri ile, tüm mantık `<script>` etiketi içinde tek bir `.html` dosyasında tutulur. Bu, Storyline (Web Object) entegrasyonunu kolaylaştırır.

### 2. Değişken ve Veri Odaklılık (Data-Driven Logic)

Javascript dosyalarının içine ASLA statik doğru cevap (Örn: `if (cevap == "Elma")`) yazılmaz. Doğru cevaplar HTML elemanlarının `data-*` niteliklerinde tutulur.

* **Doğru Kullanım:** `<div class="card" data-ans="true" data-val="elma">`
* Şablon oluşturulurken dinamik alanlar `{{DEGISKEN_ADI}}` formatında bırakılır ki, kullanıcı daha sonra bu alanları kolayca bulup değiştirebilsin.

### 3. Zırhlı Ölçeklendirme (Responsive Scale-to-Fit)

İçeriklerin bozulmasını engellemek için tüm şablonlarda sabit bir kanvas (`960x540`) kullanılır. Ekran boyutu değiştiğinde elementler kaymaz, tüm `<div id="scale-container">` matematiksel olarak `transform: scale()` ile boyutlandırılır.

```javascript
function applyScale() {
    const sc = Math.min(window.innerWidth/960, window.innerHeight/540);
    document.getElementById('scale-container').style.transform = `translate(-50%, -50%) scale(${sc})`;
}
window.addEventListener('resize', applyScale);

```

### 4. Storyline 360 Haberleşmesi ve Hata Yönetimi

* **API Entegrasyonu:** Tüm etkinlikler tamamlandığında SCORM/Storyline motoruna bilgi gönderilir. Lokalde (tarayıcıda) test edilirken çökmemesi için `try-catch` bloğu kullanılır:
```javascript
function setVar(n, v) { 
    try { parent.GetPlayer().SetVar(n, v); } 
    catch(e) { console.log(`(Lokal Test) ${n} = ${v}`); } 
}

```


* **Otomatik Çözüm (Auto-Solve):** Etkinliklerde kullanıcıya belirli bir hata hakkı verilir. Hak bittiğinde motor; kullanıcıyı kilitlemeli, doğru cevapları animasyonlu göstermeli ve 10 saniyelik bir "İnceleme Süresi" sayacı başlatıp ardından bir sonraki slayta geçiş izni vermelidir.
* **Dahili Ses Efektleri (SFX):** Ses dosyası yüklemeye gerek kalmadan tarayıcının yerleşik `AudioContext` API'si ile `playSfx('click')`, `playSfx('success')`, `playSfx('error')` fonksiyonları kullanılır.

## 🚀 Nasıl Kullanılır?

1. Depoyu bilgisayarınıza indirin.
2. Ana dizindeki **`index.html`** dosyasını herhangi bir modern tarayıcıda (Chrome, Edge, Safari) açın.
3. Sol menüden `Sablonlar_Etkinlik` sekmesini açarak tüm etkinlikleri tarayıcı üzerinde canlı olarak test edin. Hangi şablonu kullanacağınıza pedagojik rehbere bakarak karar verin.
4. Kullanmak istediğiniz şablonun `.html` dosyasını bir kod editörüyle açıp `{{...}}` ile işaretlenmiş alanları kendi içeriklerinizle değiştirin.

```

```