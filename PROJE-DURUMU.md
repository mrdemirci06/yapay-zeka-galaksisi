# 📊 Proje Durumu

> Bu dosya, projenin **şu anki durumunu** ve **son yapılanları** takip eder. Her oturum sonunda güncelle.

---

## 📅 Son Güncelleme
**Tarih:** 25 Mayıs 2026
**Versiyon:** v0.5 — Gemini API + PIN kilidi sistemi tamamlandı

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
- [x] **Proje GitHub'a taşındı** 🐙
- [x] CLAUDE.md baştan yazıldı (v3)
- [x] **Renk paleti v2:** WCAG AAA seviyesinde erişilebilirlik
- [x] **Yıldız efektleri:** 3 yıldız tipi, kayan yıldız
- [x] **Mobil optimizasyon:** 2 sütun grid, dokunmatik dostu

### Renk Paleti (v2 — Final)
- Arkaplan derin: `#020617` | orta: `#0f172a` | açık: `#1e293b`
- Cyan (ana tema): `#5eead4` | Pembe (aktif): `#ec4899` | Turuncu (XP): `#fb923c`
- Yeşil (başarı): `#4ade80` | Mor (bonus): `#8b5cf6` | Beyaz: `#f1f5f9` | Kilitli: `#94a3b8`

### 🔐 Gemini + PIN Sistemi (v0.5 — YENİ!) ✅
- [x] **Hoşgeldin modalı** — API anahtarı + 4 haneli PIN belirleme ekranı
- [x] **PIN giriş modalı** — Sonraki açılışlarda rakam tuş takımı
- [x] **Web Crypto API şifreleme** — PBKDF2 (100k iterasyon) + AES-GCM
- [x] **Gemini 2.0 Flash Lite** — Her iki sohbet alanı güncellendi
- [x] **Güvenlik:** 3 yanlış → 30sn bekleme | 5 yanlış → otomatik silme
- [x] **API testi** — Kayıt öncesi Gemini anahtarı doğrulanıyor
- [x] **Hata mesajları** — Rate limit, yanlış PIN, bağlantı hatası ayrı ayrı
- [x] **Sıfırlama** — "PIN'i unuttum" → onay sonrası tüm veriler silinir

### Gezegen 1: Başlangıç (Yapay Zeka Nedir?) ✅
- [x] 4 bölüm ders + quiz + sohbet alanı + öneri çipleri
- [x] Pratik aracı: Gemini API ✅
- [x] Rozet: 🚀 İlk Adımlar (100 XP)

### Gezegen 2: Konuşma (Prompt Sanatı) ✅
- [x] 4 bölüm ders + karşılaştırma kutuları
- [x] Quiz + Prompt Laboratuvarı
- [x] Pratik aracı: Gemini API ✅
- [x] Rozet: 💬 Konuşma Ustası (150 XP)

---

## 🎯 API Stratejisi (Kesinleşti)

### Kullanılan Sistem
- **Model:** `gemini-2.0-flash-lite` (ücretsiz, hızlı, Türkçe iyi)
- **Endpoint:** `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash-lite:generateContent`
- **Limit (free tier):** 15 istek/dk, 1000 istek/gün
- **Şifreleme:** PBKDF2 (100.000 iterasyon) + AES-GCM 256-bit

### Akış
1. **İlk açılış:** Modal → API anahtarı gir + 4 haneli PIN belirle → test edilip şifrelenerek kaydedilir
2. **Sonraki açılışlar:** PIN giriş modalı → doğru PIN → galaksiye geç
3. **PIN unutulursa:** "Sıfırla" → onay sonrası anahtar+ilerleme silinir, baştan
4. **Güvenlik:** 3 yanlış → 30sn bekleme | 5 yanlış → otomatik sıfırlama

---

## 🔄 Sıradaki Hedef

### 🥇 Gezegen 3 (Yaratım — Claude Artifacts)
- 4 bölüm ders — **Claude Artifacts'ı anlat**
- Galeri: 3 demo (oyun + animasyon + üçüncüsü kararlaşacak)
- Quiz + rozet
- **API çağrısı YOK** — sadece galeri ile etkileşim

---

## 📋 Sıradaki Adımlar (Orta Vadeli)

### Gezegenler
- [x] Gezegen 1 (Başlangıç) — Tamamlandı
- [x] Gezegen 2 (Konuşma) — Tamamlandı
- [ ] Gezegen 3 (Yaratım) — **Claude Artifacts**, galeri pratik
- [ ] Gezegen 4 (Atölye) — **Claude Skills**
- [ ] Gezegen 5 (Köprü) — **Claude MCP**
- [ ] Gezegen 6 (Kod) — **Claude Code**, terminal simülasyonu
- [ ] Gezegen 7 (Takım) — **Anthropic Cowork**
- [ ] Gezegen 8 (Final) — Mini proje fikri seçici

---

## 💡 Bu Oturumda Öğrenilenler / Kararlar

1. **Gemini 2.0 Flash Lite** seçildi — ücretsiz tier, hızlı, Türkçe yeterli
2. **Web Crypto API** — PBKDF2+AES-GCM, tarayıcı native, kütüphane gerekmez
3. **API testi önce** — Kurulum modalında kaydetmeden önce anahtar doğrulanıyor
4. **5 yanlış PIN → silme** — Güvenlik standardı uygulandı
5. **Tek callGemini() fonksiyonu** — Her iki sohbet alanı buradan çağırıyor

---

## 🐛 Bilinen Sorunlar / Notlar

- Gemini API anahtarı tarayıcının localStorage'ında AES-GCM ile şifreli saklanıyor. Farklı cihazda açıldığında kurulum modalı tekrar çıkar (beklenen davranış).
- Gezegen 3-8 henüz "Yakında!" ekranı gösteriyor.

---

## 💭 İleride Düşünülecek Fikirler

- Öğretmen modu (sınıf yönetimi)
- Veli raporu
- Sertifika oluşturma (8 gezegen biten öğrenci için PDF)
- Sesli anlatım (TTS)
- GitHub Pages'te yayınlama
