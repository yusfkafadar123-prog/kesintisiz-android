# KESİNTİSİZ v0.1 — Android başlangıç projesi

Bu paket, Android Studio'da açılabilecek bir başlangıç iskeletidir. İlk ekran sentetik vaka koduyla yerel vaka oluşturma ve vaka listesini Room/SQLite üzerinden görüntüleme amacı taşır.

## Durum ve sınırlar
- Bu paket burada Android derleyicisiyle derlenmedi ve gerçek Android cihazda test edilmedi.
- Çevrimdışı güvenilirlik henüz doğrulanmış değildir; Room kullanımı tek başına güvenilirlik garantisi vermez.
- Şifreleme, personel kimlik doğrulaması, güvenli yedekleme, değiştirilemez denetim günlüğü ve gerçek devir makbuzu henüz uygulanmamıştır.
- Yalnızca sentetik verilerle deneyin. Gerçek hasta veya gizli operasyonel bilgi girmeyin.

## Açma
1. Android Studio'da `KESINTISIZ_v0_1_Android_Starter` klasörünü açın.
2. Gradle senkronizasyonunu tamamlayın.
3. Bir Android emülatörü veya test cihazı seçip çalıştırın.
4. Sentetik bir vaka kodu girin ve **Vaka oluştur** düğmesine basın.
5. Uygulamayı kapatıp tekrar açarak kaydın görünüp görünmediğini test edin. Bu test yapılmadan çevrimdışı kalıcılık doğrulanmış sayılmaz.

## İlk adımda yer alanlar
- Kotlin + Jetpack Compose
- Room / SQLite vaka tablosu
- Yerel vaka oluşturma ve listeleme
- Basit, sentetik vaka kodu kontrolü

## Sonraki geliştirme adımları
1. Klinik olay tablosu ve eklemeli olay günlüğü.
2. Olay zamanı, kayıt zamanı, kaynak ve bilgi durumu.
3. Düzeltme bağlantıları ve çelişki görünümü.
4. Devir makbuzu ve teslim alınan sürüm.
5. Veritabanı işlemleri, migration ve hata kurtarma testleri.
6. Güvenlik incelemesi ve kurum izinleri.
