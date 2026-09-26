# Need for Speed Most Wanted (2005) — Türkçe Yama 2026

**Sürüm: 2026.1 · Güncelleme tarihi: 26 Eylül 2026**

Türkçe metinleri elden geçirilmiş, Türkçe karakter desteği ve Widescreen Fix içeren topluluk yaması.

## Özellikler

- Çeviri, anlam, yazım ve terim tutarlılığı düzeltmeleri.
- Menü ve oyun metinlerinde Türkçe karakter desteği: ç, ğ, ı, İ, ö, ş, ü.
- Türkçe harfler için düzenlenmiş fontlar; büyük Ş harfinin görüntülenme düzeltmesi.
- Birlikte sunulan Widescreen Fix ile geniş ekran, HUD oranı ve görüş açısı düzeltmeleri.
- Açılış videoları atlanmaz. Klavye kullanımında gamepad START yönlendirmesini zorlayan seçenek kapalıdır.

**Upscaled HUD pakete dahil değildir.** Widescreen Fix'in HUD oranı düzeltmesi, Upscaled HUD modundan farklıdır. Ara sahne yükseltme paketi ve Türkçe dublaj içermez.

## İndirme

[Son sürümü indir](https://github.com/rhntn/NFSMW-Turkce-Yama/releases/latest).
Sürüm sayfasındaki **NFSMW-Turkce-Yama-2026.1.zip** dosyasını indirin. GitHub'ın otomatik oluşturduğu “Source code” arşivleri kurulum paketi değildir.

## Kurulum

1. Need for Speed Most Wanted **2005 PC sürümünü** kapatın. Paket, oyunun 1.3 sürümü için hazırlanmıştır; 2012 yapımı Most Wanted için değildir.
2. Oyun ana klasörünü, yani **speed.exe** dosyasının bulunduğu klasörü açın.
3. Değiştirilecek dosyalarınızı yedekleyin. Özellikle aşağıdaki klasörler içindeki aynı adlı dosyaları, `dinput8.dll` dosyasını ve mevcut Widescreen Fix ayarlarınızı saklayın.
4. ZIP'i çıkarın. İçindeki **CREDITS, FRONTEND, GLOBAL, LANGUAGES, MEMCARD, scripts** klasörlerini ve **dinput8.dll** dosyasını doğrudan oyun ana klasörüne kopyalayın. Aynı adlı dosyaların değiştirilmesini kabul edin. İç içe ikinci bir oyun klasörü oluşturmayın.
5. Oyunu normal şekilde başlatın.

Paketteki `scripts/NFSMostWanted.WidescreenFix.ini` dosyasında `Language = German` seçilidir. Türkçe metinler German dilinin yerini alır; Dutch dil dosyası da aynı Türkçe içerikle sunulur. Oyunu ayrıca İngilizceye veya Lehçeye ayarlamanız gerekmez.

Dil ve font dosyalarını birlikte kurun. Yalnızca German.bin dosyasını kopyalamak Türkçe karakterlerin hatalı görünmesine neden olabilir.

## Ayarlar ve uyumluluk

- Widescreen Fix bu pakete dahildir; ayrıca kurmanız gerekmez.
- `SkipIntro = 0`: açılış videoları gösterilir.
- `ImproveGamepadSupport = 0`: gamepad düğme gösterimi zorlanmaz.
- `ShadowsRes = 4096`: yüksek çözünürlüklü gölgeler. Performans sorunu yaşarsanız 2048 veya 1024 deneyebilirsiniz.
- `ConsoleGamma = 1`: paketteki tercih edilen gamma ayarıdır.
- Font, dil, arayüz veya ASI yükleyici dosyalarını değiştiren diğer modlar aynı dosyaların üzerine yazabilir. Daha önce kurduğunuz modların ayarlarını kurulumdan önce yedekleyin.

## Kaldırma

Oyunu kapatıp kurulumdan önce aldığınız yedekleri aynı konumlara geri koyun. Önceden bulunmayan, yalnızca bu paketle eklenen dosyaları kaldırın. Başka modların kullandığı `scripts` klasörünü topluca silmeyin.

## Geri bildirim

[Sorun bildir](https://github.com/rhntn/NFSMW-Turkce-Yama/issues). Hatalı metnin ekran görüntüsünü ve hangi menü/görevde görüldüğünü ekleyin. Metin taşmaları veya gözden kaçan çeviri hataları geri bildirimlerle düzeltilebilir.

## Emeği geçenler ve kaynaklar

- 2026 düzenlemesi ve paketleme: [Orhan / rhntn](https://github.com/rhntn).
- Mevcut German/Dutch Türkçe çeviri tabanı: NFSTR topluluk yaması.
- Türkçe font tabanı: **muntazam**, [Türkçe Yama 1.0.1](https://www.moddb.com/downloads/need-for-speed-most-wanted-turkish-translation-patch-v10). Bu pakette büyük Ş harfinin font ölçüleri ayrıca düzenlenmiştir.
- **ThirteenAG ve katkıda bulunanlar**: [Widescreen Fix](https://github.com/ThirteenAG/WidescreenFixesPack), [Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader). İlgili MIT lisansları `licenses` klasöründedir.
- Harf dönüşümü çalışmalarında kullanılan yardımcı araç: [emres/turkish-deasciifier](https://github.com/emres/turkish-deasciifier).

Bu, EA tarafından yayımlanmayan ve desteklenmeyen bağımsız bir topluluk yamasıdır. Oyunun tamamını veya çalıştırılabilir oyun dosyasını içermez; oyuna sahip olmanız gerekir. Oyun, marka ve üçüncü taraf bileşenlerin hakları kendi sahiplerine aittir. Widescreen Fix ve ASI Loader lisansları oyun/font dosyalarını kapsamaz.
