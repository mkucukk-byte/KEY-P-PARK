# KEYİF PARK bulut aktarım görevi

Durum: hazırlık dosyaları; GitHub'a yüklenip bir çalışma bağlantısıyla doğrulanana kadar aktif bulut görevi değildir.

Üreticinin ana ürün sayfasında görülen kategori/seri/ürün bağlantılarını izler. URL tahmin etmez. Ürün sayfası metnini, kaynak HTML'ini, ürün görsellerini, srcset alternatiflerini ve bağlantısı bulunan teknik belgeleri saklar. Görselleri küçültmez. Dosya kaynakları ve SHA256 özetleri kaydedilir. Her sayfadan sonra kuyruk kaydedilir. HTTP/erişim hataları raporlanır; en fazla üç deneme yapılır. Captcha çözmez veya güvenlik denetimini atlatmaz.

GitHub Actions örneği main dalına yüklemede veya elle başlatmada çalışır. PC açık olmak zorunda değildir. Bir koşu 90 dakika/1 GiB ile sınırlıdır. Son artifact'ten dosyaları geri yükler. Artifact'ler 30 gün saklanır; kalıcı depolama değildir. Sınırsız ücretli çalışma veya abonelik oluşturmaz. Hesabın ücretsiz kota/bütçe ayarları çalıştırmadan önce kontrol edilmelidir. Otomatik takvim bu sürümde kurulmadı; sonraki çalışma elle başlatılır. Kod geliştiren genel amaçlı AI ajanı değildir.

Çıktılar: catalog/status.json, catalog/state.json, catalog/pages/*.json ve *.html, catalog/originals/*.

Kaynakta daha büyük bir dosya bağlantısı veya srcset yoksa yapay çözünürlük üretmez. Gizli/orijinal üretici arşivlerine erişim iddia etmez. Genel katalog bağlantısının ayrı kontrolü gerekir.
