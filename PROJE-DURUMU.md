# 📊 Proje Durumu

> Bu dosya, projenin **şu anki durumunu** ve **son yapılanları** takip eder. Her oturum sonunda güncelle.

---

## 📅 Son Güncelleme
**Tarih:** 23 Mayıs 2026 (akşam)
**Versiyon:** v0.2 — Gezegen 2 tamamlandı, GitHub'a taşındık, API stratejisi belirlendi

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
- [x] CLAUDE.md baştan yazıldı (v2) — GitHub akışı, oturum açılış adımları, tuzaklar dahil

### Gezegen 1: Başlangıç (Yapay Zeka Nedir?) ✅
- [x] 4 bölüm ders + quiz + Claude sohbeti + öneri çipleri
- [x] Rozet: 🚀 İlk Adımlar (100 XP)

### Gezegen 2: Konuşma (Prompt Sanatı) ✅
- [x] 4 bölüm ders (Prompt nedir, İyi vs Kötü, Sihirli ipuçları, Rol verme)
- [x] Yan yana karşılaştırma kutuları
- [x] Quiz + Prompt Laboratuvarı (kırmızı/yeşil çipler)
- [x] Rozet: 💬 Konuşma Ustası (150 XP)

---

## 🎯 BÜYÜK KARAR: API Stratejisi (23 Mayıs)

### Problem
Öğrenciler (11-14 yaş) Claude.ai'a yaş sınırı (18+) nedeniyle üye olamıyor.
Emre kendi hesabını öğrencilerle paylaşmak istemiyor.

### Çözüm: Gemini API + PIN Kilidi
- **Model değişikliği:** Anthropic API → Google Gemini API (ücretsiz tier)
- **Anahtar yönetimi:** Her öğrenci kendi Gemini anahtarını alır
- **Güvenlik:** Anahtar PIN ile şifrelenip tarayıcıda saklanır
- **Veri gizliliği:** Google ücretsiz tier verileri eğitim için kullanır — kabul ediliyor (içerikler ders sınırlı)

### Akış (Yarın Uygulanacak)
1. **İlk açılış:** Hoşgeldin modal → API anahtarı + 4 haneli PIN belirle
2. **Sonraki açılışlar:** Sadece PIN sor → galaksiye geç
3. **PIN unutulursa:** "Sıfırla" butonu → anahtar silinir, baştan
4. **Şifreleme:** Web Crypto API ile PIN-tabanlı şifreleme
5. **Güvenlik:** 3 yanlış PIN sonrası 30sn bekleme, 5 yanlış sonrası otomatik silme

### Neden Sunucu Değil?
- Emre: "Sunucu kuramıyorum, sadece HTML çözüm istiyorum"
- Projenin DNA'sı: Tek dosya, kurulum yok, sade
- Bu karara sadık kal!

---

## 🟡 Yarım Kalanlar / Test Bekleyenler

### Gezegen 3: Yaratım (Artifacts) — TASLAK (GitHub'a yüklenmedi)
**Not:** Gezegen 3 sadece Claude'un local'inde taslak olarak duruyor, **GitHub'a hiç yüklenmedi**. Yarın baştan ele alınacak.

Plan:
- 4 bölüm ders (Artifact nedir, Neler yapabilir, Sihirli kelimeler, İterasyon)
- Galeri: 3 demo (oyun + animasyon + ???)
- 3. demo kararsız — Emre "kart oluşturucu" yerine başka bir şey istiyor olabilir
- Quiz + rozet

---

## 🔄 Yarınki Hedef (24 Mayıs)

### 🥇 Ana Hedef: Gemini + PIN Altyapısı
Detaylı adımlar:
1. **Hoşgeldin modal'i** — API anahtarı + PIN belirleme ekranı
2. **PIN giriş modal'i** — sonraki açılışlarda
3. **Web Crypto API entegrasyonu** — şifreleme/çözme
4. **Gemini API çağrısı** — Anthropic API yerine
5. **Mevcut Gezegen 1 ve 2 sohbet alanlarını güncelle**
6. **Hata yönetimi** — yanlış PIN, anahtar bozulması, rate limit
7. **Test**

### 🥈 Sonra: Gezegen 3
Altyapı bittikten sonra Gezegen 3'ü yeniden ele al. 3. demo'yu Emre ile birlikte karar ver.

---

## 📋 Sıradaki Adımlar (Orta Vadeli)

- [ ] Gezegen 3 (Yaratım) — altyapı sonrası
- [ ] Gezegen 4-7 içeriklerini sırayla ekle
- [ ] Final gezegeni için "mini proje yap" şablonu
- [ ] Belki: "Güvenlik Gezegeni" ekle (siber güvenlik konusu, PIN deneyiminden esinle)

---

## 💡 Bu Oturumda Öğrenilenler / Kararlar

1. **GitHub akışı:** Claude push yapamaz, Emre manuel commit eder. Bu öğrenme fırsatı.
2. **"Yapıldı ≠ Kaydedildi":** Local'de yapılan bir özellik, GitHub'a yüklenene kadar "olmamış" sayılır.
3. **Sade kal:** Sunucu yok, tek dosya, basit kurulum. Projenin karakteri bu.
4. **Yaş sorunu:** Claude.ai 18+, Gmail 13+ — bu yüzden veliler ve öğretmen rolü kritik.
5. **PIN kilidi:** Profesyonel uygulamaların standardı. Çocuklar zaten konsol/telefonda biliyor.

---

## 🐛 Bilinen Sorunlar / Notlar

- API anahtarı şu an artifact ortamında otomatik geliyor (Anthropic). Yarın Gemini'ye geçince bu değişecek.
- Memory'de "HuggingFace token embedded" diye bir not var — bu eski AFETSONAR projesiyle ilgili, bu projeyle ilgisi yok.

---

## 💭 İleride Düşünülecek Fikirler

- Öğretmen modu (sınıf yönetimi)
- Veli raporu (öğrencinin ilerlemesi)
- Sertifika oluşturma (8 gezegen biten öğrenci için PDF)
- Sesli anlatım (TTS)
- "Günün YZ ipucu" ana sayfada
- GitHub Pages'te yayınlama (öğrenciler linkle açabilsin)
