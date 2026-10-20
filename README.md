[README.md](https://github.com/user-attachments/files/33717786/README.md)
# Melunote · GitHub Pages paketi

Ana sayfa, destek sayfası ve gizlilik politikası. İngilizce, mobil uyumlu, bağımlılıksız statik HTML/CSS. Node, kurulum veya derleme gerekmez. Her sayfa JavaScript kapalıyken çalışır.

## Dosyalar

- `index.html`: ürün ana sayfası
- `support.html`: destek adresi, sık sorulan sorular ve veri yönetimi
- `privacy.html`: gizlilik politikası
- `assets/`: ortak stil, gerçek uygulama simgesi ve örnek verili ekran görüntüsü
- `.nojekyll`: GitHub Pages'in dosyaları doğrudan sunması için

## GitHub'a yükleme

1. GitHub hesabında `melunote` isimli bir repository oluştur.
2. Bu klasörün **içeriğini** repository köküne yükle. `index.html` doğrudan kökte olmalı; fazladan iç içe klasör oluşmamalı. `assets` klasörünü de yükle.
3. Repository → Settings → Pages → Build and deployment → Source: **Deploy from a branch** seç.
4. Branch: **main**, klasör: **/(root)** seçip Save'e bas.
5. GitHub'ın verdiği site adresinin açıldığını kontrol et. Support ve Privacy bağlantılarını da aç.

`muradiye8285` hesabında repository adı `melunote` olursa, yayımlandıktan sonra beklenen adresler:

| App Store Connect alanı | Beklenen URL |
| --- | --- |
| Marketing URL | `https://muradiye8285.github.io/melunote/` |
| Support URL | `https://muradiye8285.github.io/melunote/support.html` |
| Privacy Policy URL | `https://muradiye8285.github.io/melunote/privacy.html` |

Bunlar henüz yayımlanmış adresler olarak doğrulanmadı. Hesap/repository adını farklı seçersen URL'leri buna göre değiştir. Site içi bağlantılar göreli olduğu için farklı repository adlarında da çalışır.

## Yayına geçerken

- Destek adresi diğer uygulama sayfalarındaki `gokce8535@gmail.com` adresinden alındı. Bu adresi kullanmaya devam ettiğini doğrula. Değişirse HTML dosyalarındaki tüm görünür adresleri ve mailto bağlantılarını birlikte güncelle.
- Melunote için gerçek App Store URL'si henüz verilmedi. Bu nedenle sahte indirme düğmesi yok; ana sayfada “App Store release coming soon” yazıyor. Uygulama yayımlandığında bu metni kaldır ve gerçek App Store bağlantısını bir düğme olarak ekle. Diğer uygulamaların ID'lerini kullanma.
- Ana sayfa fiyat, abonelik, otomatik müzik analizi veya cihazlar arası senkronizasyon vaat etmez.
- Uygulama içindeki mevcut gizlilik açıklaması yereldir. Site yayımlandıktan sonra uygulamaya canlı gizlilik ve destek bağlantılarını eklemek ayrı bir uygulama güncellemesidir; bu paket Swift kodunu değiştirmez.
- Gizlilik metni 20 Ekim 2026 tarihinde incelenen yerel uygulama davranışına göre hazırlandı. Yeni analiz SDK'sı, hesap, senkronizasyon veya ödeme özelliği eklersen yayımlamadan önce metni de güncelle.
- Review için tüm URL'ler herkesçe erişilebilir ve çalışır durumda olmalı. GitHub Pages yayını uygulamanın App Store'a gönderilmesi anlamına gelmez.

## İçerik ve tasarım

Krem zemin, koyu petrol yeşili, mercan vurgular, serif başlıklar. Site takip kodu, form, harici font veya çerez eklemez. GitHub barındırmasının IP kayıtları gizlilik sayfasında ayrıca açıklanır. Destek e-postaları uygulamanın cihazdaki günlüğünden ayrı ele alınır.

Ana sayfadaki ekran görüntüsü uygulamanın önceki geliştirme sürümündeki aynı Today ekranını, açıkça etiketlenmiş örnek verilerle gösterir; eski marka adı görünmez. Küçük parça/timer/grafik çizimleri HTML/CSS ile hazırlanmış açıklayıcı örneklerdir.

## Yerel önizleme

Bu klasörde `python3 -m http.server 8080` çalıştırıp `http://localhost:8080` adresini açabilirsin. HTML dosyalarını doğrudan tarayıcıda açmak da çalışır.

## Resmî kaynaklar

- GitHub Pages yayını: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- GitHub Pages IP kayıtları: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
- Apple destek ve gizlilik URL'leri: https://developer.apple.com/app-store/review/
- Apple gizlilik politikası alanı: https://developer.apple.com/help/app-store-connect/manage-app-information/manage-app-privacy/
