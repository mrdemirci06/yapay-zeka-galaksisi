# 📊 Proje Durumu

> Bu dosya, projenin **şu anki durumunu** ve **son yapılanları** takip eder. Her oturum sonunda güncelle.

---

## 📅 Son Güncelleme
**Tarih:** 23 Mayıs 2026 (gece)
**Versiyon:** v0.4 — Renk paleti + mobil + Konu/Araç ayrımı netleşti

---

## 🎭 PROJENİN DNA'SI (Bunu Unutma!)

- **Öğretilen Konu:** Claude (her zaman, her gezegende)
- **Pratik Aracı:** Gemini API (sadece Gezegen 1 ve 2'de sohbet için)
- **Neden bu ayrım?** Claude.ai 18+ yaş şartı, ortaokul öğrencisi üye olamaz
- **Mesaj:** "İyi prompt iyi prompttur — marka değişebilir, prensip aynı"

---

## ✅ Tamamlananlar

### Genel Yapı
- [x] Ana iskelet (HTML/CSS/JS) kuruldu
- [x] Uzay temalı tasarım uygulandı
- [x] Galaksi haritası: 8 gezegen kart yapısı
- [x] İlerleme sistemi (`window.storage` ile kayıt)
- [x] Rozet ve XP sistemi
- [x] Kilit/Açık mantığı
- [x] "İlerlemeyi sıfırla" butonu
- [x] **Proje GitHub'a taşındı** 🐙 (https://github.com/mrdemirci06/yapay-zeka-galaksisi)
- [x] CLAUDE.md baştan yazıldı (v3) — Konu/Araç ayrımı netleşti, ilk iş protokolü güçlendi
- [x] **Renk paleti v2:** WCAG AAA seviyesinde erişilebilirlik, derin uzay teması
- [x] **Yıldız efektleri:** 3 yıldız tipi (parlak/sarı/cyan), 120px kuyruklu kayan yıldız
- [x] **Mobil optimizasyon:** 2 sütun grid, dokunmatik dostu (min 48px), iOS zoom önleme

### Renk Paleti (v2 — Final)
- Arkaplan derin: `#020617` | orta: `#0f172a` | açık: `#1e293b`
- Cyan (ana tema): `#5eead4` | Pembe (aktif): `#ec4899` | Turuncu (XP): `#fb923c`
- Yeşil (başarı): `#4ade80` | Mor (bonus): `#8b5cf6` | Beyaz: `#f1f5f9` | Kilitli: `#94a3b8`

### Gezegen 1: Başlangıç (Yapay Zeka Nedir?) ✅
- [x] 4 bölüm ders + quiz + sohbet alanı + öneri çipleri
- [x] Pratik aracı: Anthropic API (artifact ortamında) — **yarın Gemini'ye çevrilecek**
- [x] Rozet: 🚀 İlk Adımlar (100 XP)

### Gezegen 2: Konuşma (Prompt Sanatı) ✅
- [x] 4 bölüm ders (Prompt nedir, İyi vs Kötü, Sihirli ipuçları, Rol verme)
- [x] Yan yana karşılaştırma kutuları
- [x] Quiz + Prompt Laboratuvarı (kırmızı/yeşil çipler)
- [x] Pratik aracı: Anthropic API — **yarın Gemini'ye çevrilecek**
- [x] Rozet: 💬 Konuşma Ustası (150 XP)

---

## 🎯 BÜYÜK KARAR: API Stratejisi (23 Mayıs)

### Problem
Öğrenciler (11-14 yaş) Claude.ai'a yaş sınırı (18+) nedeniyle üye olamıyor.
Emre kendi hesabını öğrencilerle paylaşmak istemiyor.

### Çözüm: Gemini API + PIN Kilidi
- **Sadece Gezegen 1 ve 2'de** API çağrısı (diğer gezegenlerde gerekmiyor)
- Her öğrenci kendi Gemini anahtarını alır (ai.google.dev'den ücretsiz)
- Anahtar PIN ile şifrelenip tarayıcıda saklanır
- **Konu hep Claude, pratik aracı Gemini** — bu ayrım kritik

### Akış (Yarın Uygulanacak)
1. **İlk açılış:** Modal → API anahtarı + 4 haneli PIN belirle
2. **Sonraki açılışlar:** Sadece PIN sor → galaksiye geç
3. **PIN unutulursa:** "Sıfırla" → anahtar silinir, baştan
4. **Şifreleme:** Web Crypto API (PBKDF2 + AES-GCM)
5. **Güvenlik:** 3 yanlış PIN sonrası 30sn bekleme, 5 yanlış sonrası otomatik silme

### Gemini API Detayları
- **Endpoint:** `https://generativelanguage.googleapis.com/v1beta/models/gemini-...:generateContent`
- **Model:** `gemini-2.5-flash-lite` (ücretsiz, hızlı, Türkçe iyi)
- **Limit (free tier):** 15 istek/dk, 1000 istek/gün

### Neden Sunucu Değil?
- Emre: "Sunucu kuramıyorum, sadece HTML çözüm istiyorum"
- Projenin DNA'sı: Tek dosya, kurulum yok, sade

---

## 🔄 Yarınki Hedef (24 Mayıs)

### 🥇 Ana Hedef: Gemini + PIN Altyapısı (Sadece Gezegen 1 ve 2)
Detaylı adımlar:
1. **Hoşgeldin modal'i** — API anahtarı + PIN belirleme ekranı
2. **PIN giriş modal'i** — sonraki açılışlarda
3. **Web Crypto API entegrasyonu** — şifreleme/çözme
4. **Gemini API çağrısı** — Anthropic API yerine
5. **Gezegen 1 sohbet alanını güncelle**
6. **Gezegen 2 Prompt Laboratuvarı'nı güncelle**
7. **Hata yönetimi** — yanlış PIN, anahtar bozulması, rate limit
8. **Test**

### 🥈 Sonra: Gezegen 3 (Yaratım — Artifacts)
- 4 bölüm ders — **Claude Artifacts'ı anlat**
- Galeri: 3 demo (oyun + animasyon + üçüncüsü kararlaşacak)
- Quiz + rozet
- **API çağrısı YOK** — sadece galeri ile etkileşim

---

## 📋 Sıradaki Adımlar (Orta Vadeli)

### Gezegenler (her birinde Claude'un farklı bir özelliği)
- [ ] Gezegen 3 (Yaratım) — **Claude Artifacts**, galeri pratik
- [ ] Gezegen 4 (Atölye) — **Claude Skills**, gerçek SKILL.md örnekleri
- [ ] Gezegen 5 (Köprü) — **Claude MCP**, bağlantı şeması
- [ ] Gezegen 6 (Kod) — **Claude Code**, terminal simülasyonu
- [ ] Gezegen 7 (Takım) — **Anthropic Cowork**, tanıtım/video
- [ ] Gezegen 8 (Final) — Mini proje fikri seçici

### Genel
- [ ] Final gezegeni için "mini proje yap" şablonu
- [ ] Belki: "Güvenlik Gezegeni" ekle (PIN deneyiminden esinlenerek)

---

## 💡 Bu Oturumda Öğrenilenler / Kararlar

1. **GitHub akışı:** Claude push yapamaz, Emre manuel commit eder.
2. **"Yapıldı ≠ Kaydedildi":** Local'de yapılan, GitHub'a yüklenene kadar "olmamış" sayılır.
3. **Sade kal:** Sunucu yok, tek dosya, basit kurulum.
4. **Yaş sorunu:** Claude.ai 18+, Gmail 13+ — veliler ve öğretmen rolü kritik.
5. **PIN kilidi:** Profesyonel uygulamaların standardı.
6. **Erişilebilirlik (a11y):** WCAG kontrast kuralları (4.5+ AA, 7+ AAA).
7. **Tasarım sistemi:** Her renge bir görev verildi (cyan=ana, yeşil=başarı, vb).
8. **Mobil öncelik:** Öğrenciler telefondan açacak — 2 sütun grid, dokunmatik dostu.
9. **🎭 Konu vs Araç ayrımı:** Öğretilen=Claude, pratik aracı=Gemini. Bu ayrım kritik!

---

## 🐛 Bilinen Sorunlar / Notlar

- Gezegen 1 ve 2'deki mevcut sohbet alanları **şu an Anthropic API** kullanıyor (artifact ortamında otomatik). Yarın Gemini'ye çevrilecek.
- Memory'de "HuggingFace token embedded" notu var — bu eski AFETSONAR projesiyle ilgili, bu projeyle ilgisi yok.

---

## 💭 İleride Düşünülecek Fikirler

- Öğretmen modu (sınıf yönetimi)
- Veli raporu (öğrencinin ilerlemesi)
- Sertifika oluşturma (8 gezegen biten öğrenci için PDF)
- Sesli anlatım (TTS)
- "Günün YZ ipucu" ana sayfada
- GitHub Pages'te yayınlama (öğrenciler linkle açabilsin)
