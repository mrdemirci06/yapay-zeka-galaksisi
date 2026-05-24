# 🚀 YAPAY ZEKA GALAKSİSİ - Proje Talimat Dosyası

> ⚠️ **CLAUDE, BU DOSYAYI BAŞTAN SONA OKU. AŞAĞIDAKİ İLK İŞ BÖLÜMÜ ZORUNLUDUR.**

## 👋 Sevgili Claude

Bu projede bana yardım edecek bir geliştirici ortağsın. Aşağıdaki bilgileri **her oturumda mutlaka oku** ve buna göre davran.

---

## 🚨 İLK İŞ — ZORUNLU! KULLANICI MESAJINI YANITLAMADAN ÖNCE YAP!

**Kullanıcı sana ne yazarsa yazsın** (örn: "merhaba", "devam edelim", "Gemini'ye başlayalım", "şunu yap"), ilk mesajda **ZORUNLU OLARAK** şu sırayla hareket et:

### Adım 1: PROJE-DURUMU.md'yi tamamen oku
Otomatik olarak sana gelir. Burada "Yarınki Hedef" ve "Şu An Yapılıyor" bölümleri **kritik**.

### Adım 2: GitHub'dan index.html'i çek
```bash
curl -sL https://raw.githubusercontent.com/mrdemirci06/yapay-zeka-galaksisi/main/index.html -o /home/claude/index.html
```
Bu **mecburi bir adım** — index.html projeye yüklü olmadığı için sadece GitHub'da güncel hali var.

### Adım 3: Kullanıcıya KISA bir durum özeti ver
Şu formatta:
```
Merhaba Emre! Dosyaları okudum. Şu an durumumuz:

✅ Tamamlananlar: [kısa liste]
🎯 Sıradaki hedef: [PROJE-DURUMU.md'deki "Yarınki Hedef"]

[Hedefe göre 1-2 cümle ne yapacağımıza dair plan]

Başlayalım mı?
```

### Adım 4: Onay bekle, sonra başla
Kullanıcı "evet", "başla", "tamam", "devam" gibi onay verince → işe gir.

### ⚠️ KESİNLİKLE YAPMAMA:
- ❌ Kullanıcının mesajını dosyaları okumadan yorumlama
- ❌ Bağlamı bilmeden "anlamadım" deme (önce dosyaları oku!)
- ❌ Adımları atlama
- ❌ "Hangi proje?" diye sorma (CLAUDE.md ve PROJE-DURUMU.md zaten projede)

### ✅ NORMAL AKIŞ ÖRNEĞİ:
Kullanıcı: "Gemini + PIN'e başlayalım"
Claude (içinden): "Önce dosyaları oku, GitHub'dan index'i çek, sonra konuş"
Claude (dışarı): [Dosyaları okur, curl çalıştırır, özet verir, onay ister, başlar]

---

## 👤 Kim Çalışıyor?

- **Ben:** Emre, Türkçe konuşan bir öğretmen (Karabük)
- **Dil tercihi:** TÜM YANITLAR TÜRKÇE OLMALI. İngilizce yanıt verme.
- **Teknik seviye:** İleri seviye programcı değilim. Mantığı takip edebilirim ama:
  - Kısa, adım adım açıklama yap
  - Bir seferde tek bir şey üzerinde çalışalım
  - Karmaşık şeyler yapmadan önce onay iste
  - Anlamadığımı düşünüyorsan örnek ver
- **Çalışma tarzı:** Yaparak öğrenirim, teorik anlatım sıkıcı gelir
- **Oturum süresi:** Genelde 30-60 dk, kısa ve odaklı

---

## 🎯 Proje Nedir?

**Yapay Zeka Galaksisi**, ortaokul öğrencileri (11-14 yaş) için tasarlanmış, **uzay temalı interaktif bir YZ öğrenme platformu**.

### Hedefler:
1. Öğrencilerime sınıfta ve evde kullanabilecekleri eğlenceli bir araç sunmak
2. Sıkıcı teori yerine **oyunlaştırılmış görevlerle** öğrenmek
3. Yapay Zeka → Claude.ai → Claude Code → Cowork yolculuğunu adım adım göstermek

### Hedef Kitle:
- **Birincil:** Ortaokul öğrencileri (11-14 yaş)
- **İkincil:** Türkçe YZ eğitimi arayan diğer öğretmenler ve veliler

### Kullanım Yeri:
- Sınıfta projeksiyondan birlikte
- Öğrenciler kendi cihazlarından evde
- Web tarayıcısında, kurulum gerekmez

---

## 🎭 KRİTİK AYRIM: Öğretilen Konu vs Pratik Aracı

Bu projenin **DNA**'sı! Karıştırma:

### 🎓 ÖĞRETİLEN KONU = Claude
Tüm gezegenlerde **Claude'u** anlatıyoruz:
- Claude.ai (chat interface)
- Claude Code (terminal aracı)
- Artifacts (görsel üretim)
- Skills (özel yetenekler)
- MCP (bağlantı protokolü)
- Cowork (yeni Anthropic ürünü)
- Anthropic firması, güvenlik felsefesi, vb.

### 🛠️ PRATİK ARACI = Gemini (sadece Gezegen 1 ve 2'de)
Gemini sadece **prompt yazma deneyimi** için kullanılır çünkü:
- Claude.ai 18+ yaş, öğrenciler üye olamaz
- Öğrenciye somut bir "YZ ile konuşma" deneyimi gerekli
- "Beceri" evrenseldir — marka değişebilir, prensip aynı

### Hangi Gezegende Gemini Çağrısı?
- ✅ **Gezegen 1** (Başlangıç) — ilk YZ sohbet deneyimi
- ✅ **Gezegen 2** (Konuşma) — Prompt Laboratuvarı
- ❌ **Gezegen 3-8** — Sadece içerik, galeri, görseller, kavramsal anlatım

### Öğrenciye Söylenecek Cümle (örnek):
> *"Bu uygulamada **Claude'u öğreniyoruz** ama prompt pratik için **Gemini** kullanıyoruz. Çünkü Claude.ai 18 yaş kuralı var. Ama unutma — iyi prompt iyi prompttur, hangi YZ'ye yazarsan yaz."*

Bu **dürüst, pedagojik ve evrensel** bir mesaj.

---

## 🐙 GitHub & Çalışma Akışı

### Repo Bilgisi
- **URL:** https://github.com/mrdemirci06/yapay-zeka-galaksisi
- **Sahip:** mrdemirci06
- **Ana branch:** `main`
- **Görünürlük:** Public (sen okuyabilirsin)

### Dosya Yapısı (GitHub'da)
```
yapay-zeka-galaksisi/
├── CLAUDE.md          → Bu dosya (sana her oturumda gelir)
├── PROJE-DURUMU.md    → Son durum, ne yapıldı, sırada ne var
├── index.html         → Ana uygulama (tek dosya — HTML+CSS+JS hepsi içinde)
└── README.md          → GitHub otomatik, şimdilik boş
```

### Dosya Güncelleme Akışı

**ÖNEMLİ:** Senin doğrudan GitHub'a push yapma yetkin yok.

1. Sen kodu local'inde üretirsin (`/home/claude/` veya `/mnt/user-data/outputs/`)
2. Bana `present_files` ile gösterirsin
3. Ben dosyayı indirip GitHub'a manuel yüklerim (web arayüzünden, kalem ✏️ ikonu)
4. Bir sonraki oturumda sen `raw.githubusercontent.com`'dan güncel halini okursun

### "Yapıldı" vs "Kaydedildi" Farkı (UNUTMA!)

⚠️ Bir özelliği local'de kodlamak ≠ projenin durumu değişti. **GitHub'a commit olana kadar olmamış say.**

Yani PROJE-DURUMU.md'yi güncellemeden önce şunu sor: "Bu özellik GitHub'a yüklendi mi?"

### Commit Mesajları

Bana commit mesajı önerirken **kısa ve açıklayıcı** ol:
- `Gezegen X eklendi: konu adı`
- `Bug düzeltildi: ne düzeltildi`
- `İyileştirme: hangi kısım`

---

## 🎨 Tasarım Kuralları (Bunlara Sadık Kal!)

- **Tema:** Uzay & macera (gezegenler, yıldızlar, kâşif)
- **Renkler:** Koyu uzay arkaplan + neon vurgular (cyan, pembe, sarı, yeşil, mor)
- **Fontlar:** Orbitron (başlık), Space Grotesk (gövde), Press Start 2P (retro vurgu)
- **Ton:** Eğlenceli ama saçma değil. Emoji'li ama abartısız. Ortaokul seviyesi.
- **Hareket:** Yıldız parıltıları, kayan yıldızlar, hover animasyonları — ama abartma

**NE YAPMA:**
- Sıkıcı kurumsal görünüm
- Standart "AI tutorial" estetiği (mor degrade, beyaz arkaplan)
- Çok ciddi akademik dil
- Uzun cümleler ve paragraflar

---

## 🪐 Galaksi Yapısı (8 Gezegen)

| # | Gezegen | Konu (öğretilen) | Pratik Aracı | Durum |
|---|---------|------|------|-------|
| 1 | 🌍 Başlangıç | Yapay Zeka Nedir? Claude da bir YZ | 🛠️ Gemini sohbet | ✅ Tamamlandı |
| 2 | 🪐 Konuşma | Claude'a iyi prompt nasıl yazılır | 🛠️ Gemini (Prompt Lab) | ✅ Tamamlandı |
| 3 | ✨ Yaratım | **Claude Artifacts** | 🖼️ Sadece galeri | 🔄 Sırada |
| 4 | 🛠️ Atölye | **Claude Skills** | 📜 Sadece içerik | ⏳ Bekliyor |
| 5 | 🌐 Köprü | **Claude MCP** | 📊 Sadece şema/görsel | ⏳ Bekliyor |
| 6 | 💻 Kod | **Claude Code** | 🎬 Sadece ekran görüntüsü | ⏳ Bekliyor |
| 7 | 🤝 Takım | **Anthropic Cowork** | 📺 Sadece tanıtım | ⏳ Bekliyor |
| 8 | ⭐ Final | Mini proje fikri | 🧠 Konsept | ⏳ Bekliyor |

**ÖNEMLİ:** "Pratik Aracı" = uygulamada öğrencinin ne yaptığı. "Konu" = öğretilen şey (her zaman Claude).

Gemini sadece **Gezegen 1 ve 2**'de API çağrısı yapar. Diğer gezegenlerde API yok — sadece içerik, görsel, kavramsal anlatım.

**NOT:** Bu tablo durumun **özeti**. Detaylar PROJE-DURUMU.md'de.

---

## 🧩 Her Gezegenin Standart Yapısı

Her gezegende şunlar olmalı:
1. **Hoşgeldin başlığı** — emoji ve neon başlık
2. **Konu anlatımı** — 3-5 kısa bölüm (lesson-section), Claude'u anlatan
3. **En az 1 "İlginç Bilgi" kutusu** (fun-fact)
4. **Mini quiz** — 1 soru, 4 şık, yanlış cevapta tekrar şansı
5. **Pratik alan** — gezegene göre değişir (aşağıya bak)
6. **Görev Tamamla butonu** — quiz + pratik tamamlanmalı
7. **Rozet ve XP ödülü**

### Pratik Alan Çeşitliliği (Her Gezegende Aynı Olmasın!)
Sadece **Gezegen 1 ve 2**'de Gemini API çağrısı var. Diğerleri farklı pratik biçimi:

- **Gezegen 1** (Başlangıç): 🛠️ Gemini ile **açık sohbet** — ilk YZ deneyimi
- **Gezegen 2** (Konuşma): 🛠️ Gemini ile **Prompt Laboratuvarı** — kötü/iyi karşılaştırma
- **Gezegen 3** (Yaratım): 🖼️ **Galeri** — hazır Claude artifact örnekleri iframe ile
- **Gezegen 4** (Atölye): 📜 **Skill örnekleri** — gerçek SKILL.md dosya görüntüleri, açıklamalı
- **Gezegen 5** (Köprü): 📊 **Bağlantı şeması** — Claude ↔ Google Drive vb. görsel
- **Gezegen 6** (Kod): 🎬 **Terminal simülasyonu** — sahte terminal, "böyle görünür" deneyimi
- **Gezegen 7** (Takım): 📺 **Tanıtım/video** — Cowork ne yapar, görsel anlatım
- **Gezegen 8** (Final): 🧠 **Mini proje fikri seçici** — öğrenci kendi projesini düşünür

---

## 💻 Teknik Detaylar

### Kullanılan Teknolojiler
- **Pure HTML/CSS/JS** (React YOK — öğrenciler kolayca açabilsin)
- **Tek dosya** (`index.html`) — CSS+JS hepsi içinde
- **window.storage** — ilerleme kaydı (kalıcı)
- **Google Gemini API** — SADECE Gezegen 1 ve 2'deki sohbet pratiği için (Claude.ai yaş sınırı nedeniyle)
- **Web Crypto API** — anahtarı PIN ile şifreleyip tarayıcıda saklamak için
- **Google Fonts** — Orbitron, Space Grotesk, Press Start 2P

### İlerleme Kayıt Şeması (window.storage)
```javascript
{
  completedPlanets: [1, 2, 3],   // tamamlanan gezegen ID'leri
  badges: [{icon, title, desc}], // kazanılan rozetler
  xp: 450,                       // toplam puan
  currentQuizAnswered: {}        // (şimdilik kullanılmıyor)
}
```
Kayıt anahtarı: `yz_galaksisi_progress`

### Kilitli/Açık Mantığı
- Gezegen N, sadece Gezegen N-1 tamamlanmışsa açılır
- Gezegen 1 her zaman açıktır

### Gemini API Çağrıları
- **Endpoint:** `https://generativelanguage.googleapis.com/v1beta/models/gemini-...:generateContent`
- **Model:** `gemini-2.5-flash-lite` (ücretsiz tier, hızlı, Türkçe iyi)
- **Anahtar:** Kullanıcının kendi API anahtarı (PIN ile şifrelenmiş, tarayıcıda saklı)
- **Limit (free tier):** 15 istek/dk, 1000 istek/gün, 250K token/dk paylaşımlı
- Her gezegenin sohbet alanı için system prompt'u **o gezegene özel** olsun
- Türkçe konuşma vurgusu sistem prompt'una eklenmiş olmalı

### PIN/Anahtar Akışı
- **İlk açılış:** Modal → API anahtarı + 4 haneli PIN belirle
- **Sonraki açılışlar:** Sadece PIN sor → galaksiye geç
- **PIN unutulursa:** "Sıfırla" → anahtar silinir, baştan
- **Şifreleme:** Web Crypto API (PBKDF2 + AES-GCM)
- **Güvenlik:** 3 yanlış PIN sonrası 30sn bekleme, 5 yanlış sonrası otomatik silme

---

## 🤝 Birlikte Çalışma Kuralları

Claude, bana yardım ederken şunları yap:

1. **Önce planı söyle, sonra yap.** Büyük değişikliklerde "şunu şöyle yapacağım, devam edeyim mi?" diye sor.

2. **Tek seferde 1-2 dosya üret.** Beni bunaltma. Adım adım gidelim.

3. **Türkçe açıkla.** Her teknik kararın arkasındaki "neden"i kısa söyle.

4. **Test ediyorsam beklet.** "Test ettin mi, çalışıyor mu?" diye sor.

5. **CLAUDE.md ve PROJE-DURUMU.md'yi güncel tut.** Yeni bir gezegen ekleyince tabloyu güncelle. (Ama GitHub'a yüklenene kadar "tamamlandı" deme!)

6. **Hata yaparsam savunma yapma.** "Şu an karmaşık geldi" dersem, basitleştir.

7. **Soru sorarken `ask_user_input_v0` aracını kullan.** Mobilde yazmak zor, tıklanabilir seçenekler ver.

8. **Karıştırırsam düzelt.** "Şunu güncellemeyelim" dersem, durumu tekrar tara, yanlışı bulup düzelt.

---

## 📝 Yeni Bir Gezegen Eklerken Akış

Sırasıyla:
1. **İçerik taslağını sohbette yaz** (4 bölüm + quiz + pratik fikri + rozet)
2. **Onay al** — "Bu plan uygun mu?"
3. **HTML'e göm** (index.html'deki gezegen sistemine)
4. **Çıktıyı sun** (`present_files` ile yeni index.html)
5. **Ben test ederim**, sen bekle
6. **Test başarılıysa** GitHub'a yüklerim
7. **Sonra** CLAUDE.md tablosu ve PROJE-DURUMU.md güncellenir

---

## 🎁 Bonus Hedefler (Sonra)

- [ ] Öğretmen modu (sınıf yönetimi)
- [ ] Veli raporu (öğrencinin ilerlemesi)
- [ ] Çoklu kullanıcı desteği (her öğrencinin ayrı ilerlemesi)
- [ ] Sertifika oluşturma (8 gezegen biten öğrenci için PDF)
- [ ] Sesli anlatım (TTS)
- [ ] Karanlık/Aydınlık tema (şu an karanlık)

---

## ⚠️ Önemli Notlar / Tuzaklar

### Genel
- **Yaş uyumu:** İçerikler ortaokul seviyesi olmalı — ne çok çocukça, ne çok teknik
- **Türkçe karakter:** Tüm metinlerde Türkçe karakterler doğru kullanılmalı (ç, ş, ğ, ı, ö, ü)
- **Repo public:** Hassas bilgi koyma, API anahtarı gömme

### API Anahtarı
- **Gemini API anahtarı** kullanılır — Anthropic değil!
- Her kullanıcı kendi anahtarını alır (ai.google.dev → Get API key)
- Anahtar **kullanıcının tarayıcısında PIN ile şifreli** saklanır (Web Crypto API)
- Kod içinde **asla anahtar gömme** — repo public!
- Memory'de eski bir projeden kalan HuggingFace token notu var — bu projeyle ilgisi yok

### Kod Yazarken
- **Template literal (backtick) escape:** HTML içinde JS template kullanırken `${}` çakışmalarına dikkat
- **Iframe srcdoc:** Demoları iframe ile gösterirken JS string olarak gömüldüğünde escape sorunları olabilir
- **Mobil:** Öğrenciler telefondan da açabilir — responsive olmalı

### Karar Verirken
- Şüphedeysen **sade tut**. "3 örnek mi 5 örnek mi?" diye sorarken sade hep daha iyi.
- "Test etmeden ekleyelim mi?" → **Hayır.** Önce test, sonra commit.

---

## 🧠 Memory'de Olanlar (Hatırlatma)

Memory sistemimde benim hakkımda şu bilgiler var:
- Türkçe öğretmen, Karabük'te
- Programlama geçmişim yok ama mantığı takip ederim
- Günlük kısa pratiklerle öğrenirim
- Daha önce yapılmış projeler: AFETSONAR (TÜBİTAK), TeknoKarabük line follower robot, mobil oyunlar, vb.
- Bu projenin geçmiş oturumlarındaki kararlar memory'de yok — **tüm proje geçmişi için PROJE-DURUMU.md'ye bak.**

---

*Son güncelleme: 23 Mayıs 2026 — GitHub'a taşınma sonrası tam revizyon (v2)*
