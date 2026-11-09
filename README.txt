PSP MAX - Android telefon için PWA paketi

DOSYALAR
- index.html: uygulama arayüzü
- manifest.json: ana ekrana eklenme bilgileri
- sw.js: temel çevrimdışı önbellek
- icon.svg: uygulama simgesi

TELEFONDAN KULLANMA
Bu paket doğrudan ZIP içinden uygulama olarak kurulmaz. PWA kurulumu için dosyaların HTTPS destekleyen bir web alanında yayımlanması gerekir.
1. ZIP'i telefonda çıkar.
2. Dosyaları GitHub'da yeni bir depoya yükle (index.html kök dizinde olsun).
3. Depo Settings > Pages bölümünden GitHub Pages'i etkinleştir.
4. Verilen https://...github.io/... adresini Chrome ile aç.
5. Chrome menüsünden "Uygulamayı yükle" veya "Ana ekrana ekle" seçeneğini seç.

SINIRLAMA
Bu PWA oyun kütüphanesidir, PSP ISO/CSO dosyalarını çalıştırmaz. Gerçek emülasyon için ayrıca Android yerel uygulama katmanı ve uygun emülatör motoru gerekir. Sadece HTML/JS ile PPSSPP işlevi elde edilemez.
