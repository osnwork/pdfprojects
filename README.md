# Ders Notu → PDF

Okullarda öğretmen ve öğrencilerin ders notlarını yazıp tek tıkla PDF olarak indirmesi için hazırlanmış, sunucu gerektirmeyen tek sayfalık bir sitedir.

## Özellikler
- Okul, ders, sınıf, öğretmen ve tarih bilgisiyle başlıklı not sayfası
- Kalın, italik, vurgulayıcı, başlık, liste ve resim ekleme
- Düz / çizgili / kareli kağıt ve büyük yazı boyutu seçeneği (küçük sınıflar için)
- A4 PDF indirme ve yazdırma
- Taslak tarayıcıda otomatik kaydedilir; veriler hiçbir sunucuya gönderilmez

## GitHub Pages ile yayınlama
1. GitHub'da yeni bir depo (repository) oluşturun.
2. `index.html` ve `README.md` dosyalarını yükleyin.
3. **Settings → Pages** bölümünde *Source* olarak `Deploy from a branch`, branch olarak `main` ve klasör olarak `/ (root)` seçin.
4. Birkaç dakika sonra site `https://KULLANICI-ADI.github.io/DEPO-ADI/` adresinde yayında olur.

## Not
PDF oluşturma için `html2pdf.js` (cdnjs) ve yazı tipleri için Google Fonts kullanılır; ilk açılışta internet bağlantısı gerekir.
