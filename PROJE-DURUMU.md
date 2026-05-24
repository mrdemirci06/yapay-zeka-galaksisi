# 📊 Proje Durumu

> Bu dosya, projenin **şu anki durumunu** ve **son yapılanları** takip eder. Her oturum sonunda güncelle.

---

## 📅 Son Güncelleme
**Tarih:** 23 Mayıs 2026 (gece)
**Versiyon:** v0.3 — Renk paleti yenilendi, yıldız efektleri iyileştirildi

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
- [x] **Renk paleti yenilendi (v2):** WCAG AAA seviyesinde erişilebilirlik, derin uzay teması
- [x] **Yıldız efektleri iyileştirildi:** 3 yıldız tipi (parlak/sarı/cyan), 120px kuyruklu kayan yıldız

### Renk Paleti (v2 — Final)
- Arkaplan derin: `#020617` (neredeyse siyah, hafif mavi)
- Arkaplan orta: `#0f172a`
- Arkaplan açık: `#1e293b`
- Cyan (ana tema): `#5eead4`
- Pembe (aktif/dikkat): `#ec4899`
- Turuncu (XP/ödül): `#fb923c`
- Yeşil (başarı): `#4ade80`
- Mor (bonus/ilginç): `#8b5cf6`
- Beyaz metin: `#f1f5f9`
- Kilitli gri: `#94a3b8`

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
- **Veri gizliliği:** Google ücretsiz tier verileri eğitim için kullanır — kabul ediliyor

### Akış (Yarın Uygulanacak)
1. **İlk açılış:** Hoşgeldin modal → API anahtarı + 4 haneli PIN belirle
2. **Sonraki açılışlar:** Sadece PIN sor → galaksiye geç
3. **PIN unutulursa:** "Sıfırla" butonu → anahtar silinir, baştan
4. **Şifreleme:** Web Crypto API ile PIN-tabanlı şifreleme
5. **Güvenlik:** 3 yanlış PIN sonrası 30sn bekleme, 5 yanlış sonrası otomatik silme

### Neden Sunucu Değil?
- Emre: "Sunucu kuramıyorum, sadece HTML çözüm istiyorum"
- Projenin DNA'sı: Tek dosya, kurulum yok, sade

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

### 🥈 Sonra: Gezegen 3 (Yaratım — Artifacts)
Altyapı bittikten sonra Gezegen 3'ü yeniden ele al:
- 4 bölüm ders + galeri (3 demo) + quiz
- Galeri demolarını sıfırdan tasarla (önceki taslak local'de kalmıştı)

---

## 📋 Sıradaki Adımlar (Orta Vadeli)

- [ ] Gezegen 3 (Yaratım) — Gemini+PIN altyapısı sonrası
- [ ] Gezegen 4-7 içeriklerini sırayla ekle
- [ ] Final gezegeni için "mini proje yap" şablonu
- [ ] Belki: "Güvenlik Gezegeni" ekle (siber güvenlik, PIN deneyiminden esinle)

---

## 💡 Bu Oturumda Öğrenilenler / Kararlar

1. **GitHub akışı:** Claude push yapamaz, Emre manuel commit eder.
2. **"Yapıldı ≠ Kaydedildi":** Local'de yapılan bir özellik, GitHub'a yüklenene kadar "olmamış" sayılır.
3. **Sade kal:** Sunucu yok, tek dosya, basit kurulum. Projenin karakteri bu.
4. **Yaş sorunu:** Claude.ai 18+, Gmail 13+ — bu yüzden veliler ve öğretmen rolü kritik.
5. **PIN kilidi:** Profesyonel uygulamaların standardı. Çocuklar zaten konsol/telefonda biliyor.
6. **Erişilebilirlik (a11y):** Renk paletinde WCAG kontrast kuralları (4.5+ AA, 7+ AAA). Mor ve gri özellikle dikkat.
7. **Tasarım sistemi:** Her renge bir görev verildi (cyan=ana, yeşil=başarı, turuncu=ödül, vb).

---

## 💭 İleride Düşünülecek Fikirler

- Öğretmen modu (sınıf yönetimi)
- Veli raporu (öğrencinin ilerlemesi)
- Sertifika oluşturma (8 gezegen biten öğrenci için PDF)
- Sesli anlatım (TTS)
- "Günün YZ ipucu" ana sayfada
- GitHub Pages'te yayınlama (öğrenciler linkle açabilsin)
