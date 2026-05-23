# 🚀 YAPAY ZEKA GALAKSİSİ - Proje Talimat Dosyası

## 👋 Sevgili Claude

Bu projede bana yardım edecek bir geliştirici ortağsın. Aşağıdaki bilgileri **her oturumda mutlaka oku** ve buna göre davran.

---

## 👤 Kim Çalışıyor?

- **Ben:** Emre, Türkçe konuşan bir öğretmen
- **Dil tercihi:** TÜM YANITLAR TÜRKÇE OLMALI. İngilizce yanıt verme.
- **Teknik seviye:** İleri seviye programcı değilim. Mantığı takip edebilirim ama:
  - Kısa, adım adım açıklama yap
  - Bir seferde tek bir şey üzerinde çalışalım
  - Karmaşık şeyler yapmadan önce onay iste
  - Anlamadığımı düşünüyorsan örnek ver
- **Çalışma tarzı:** Yaparak öğrenirim, teorik anlatım sıkıcı gelir

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

| # | Gezegen | Konu | Durum |
|---|---------|------|-------|
| 1 | 🌍 Başlangıç | Yapay Zeka Nedir? | ✅ Tamamlandı |
| 2 | 🪐 Konuşma | Claude.ai ve prompt yazma | ⏳ Bekliyor |
| 3 | ✨ Yaratım | Artifacts | ⏳ Bekliyor |
| 4 | 🛠️ Atölye | Skills | ⏳ Bekliyor |
| 5 | 🌐 Köprü | MCP | ⏳ Bekliyor |
| 6 | 💻 Kod | Claude Code | ⏳ Bekliyor |
| 7 | 🤝 Takım | Cowork | ⏳ Bekliyor |
| 8 | ⭐ Final | Mini proje | ⏳ Bekliyor |

---

## 🧩 Her Gezegenin Standart Yapısı

Her gezegende şunlar olmalı:
1. **Hoşgeldin başlığı** — emoji ve neon başlık
2. **Konu anlatımı** — 3-5 kısa bölüm (lesson-section), basit dilde
3. **En az 1 "İlginç Bilgi" kutusu** (fun-fact)
4. **Mini quiz** — 1 soru, 4 şık, yanlış cevapta tekrar şansı
5. **Pratik alan** — Claude ile sohbet, artifact denemesi, vb.
6. **Görev Tamamla butonu** — quiz + pratik tamamlanmalı
7. **Rozet ve XP ödülü**

---

## 💻 Teknik Detaylar

### Dosya Yapısı
```
yapay-zeka-galaksisi/
├── CLAUDE.md          ← Bu dosya
├── PROJE-DURUMU.md    ← Son durum
├── index.html         ← Ana dosya (tek dosyalı uygulama)
└── gezegenler/        ← İçerik notları (Markdown)
```

### Kullanılan Teknolojiler
- **Pure HTML/CSS/JS** (React YOK, çünkü öğrenciler kolayca açabilsin)
- **window.storage** — ilerleme kaydı (kalıcı)
- **Anthropic API** — uygulama içi Claude sohbeti
- **Google Fonts** — Orbitron, Space Grotesk, Press Start 2P

### İlerleme Kayıt Şeması (window.storage)
```javascript
{
  completedPlanets: [1, 2, 3],  // tamamlanan gezegen ID'leri
  badges: [{icon, title, desc}],
  xp: 450,
  currentQuizAnswered: {}
}
```

### Kilitli/Açık Mantığı
- Gezegen N, sadece Gezegen N-1 tamamlanmışsa açılır
- Gezegen 1 her zaman açıktır

---

## 🤝 Birlikte Çalışma Kuralları

Claude, bana yardım ederken şunları yap:

1. **Önce planı söyle, sonra yap.** Büyük değişikliklerde "şunu şöyle yapacağım, devam edeyim mi?" diye sor.

2. **Tek seferde 1-2 dosya üret.** Beni bunaltma. Adım adım gidelim.

3. **Türkçe açıkla.** Her teknik kararın arkasındaki "neden"i kısa söyle.

4. **Test ediyorsam beklet.** "Test ettin mi, çalışıyor mu?" diye sor.

5. **CLAUDE.md ve PROJE-DURUMU.md'yi güncel tut.** Yeni bir gezegen ekleyince tabloyu güncelle.

6. **Hata yaparsam savunma yapma.** "Şu an karmaşık geldi" dersem, basitleştir.

---

## 📝 Yeni Bir Gezegen Eklerken Akış

Sırasıyla:
1. Önce o gezegenin **içerik taslağını** Markdown olarak yazalım (gezegenler/ klasöründe)
2. Birlikte içeriği okuyup eksikleri kapatalım
3. Sonra HTML'e gömelim (index.html'deki gezegen sistemine)
4. Test edelim
5. CLAUDE.md tablosunu güncelleyelim

---

## 🎁 Bonus Hedefler (Sonra)

- [ ] Öğretmen modu (sınıf yönetimi)
- [ ] Veli raporu (öğrencinin ilerlemesi)
- [ ] Çoklu kullanıcı desteği (her öğrencinin ayrı ilerlemesi)
- [ ] Sertifika oluşturma (8 gezegen biten öğrenci için PDF)
- [ ] Sesli anlatım (TTS)
- [ ] Karanlık/Aydınlık tema (şu an karanlık)

---

## ⚠️ Önemli Notlar

- **API anahtarı:** Uygulama içi sohbet için Anthropic API kullanıyor. Artifact ortamında otomatik çalışır, ama dışarı dağıtırsam (öğrencilerin tarayıcısında) API anahtarı yönetimine bakmam lazım.
- **Yaş uyumu:** İçerikler ortaokul seviyesi olmalı — ne çok çocukça, ne çok teknik
- **Türkçe karakter:** Tüm metinlerde Türkçe karakterler doğru kullanılmalı (ç, ş, ğ, ı, ö, ü)

---

*Son güncelleme: Bu projenin ilk versiyonu. PROJE-DURUMU.md dosyasından son ilerlemeyi takip et.*
