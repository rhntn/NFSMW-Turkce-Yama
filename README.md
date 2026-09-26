# Need for Speed Most Wanted (2005) — Türkçe Yama 2026

**Sürüm: 2026.1 · Güncelleme tarihi: 26 Eylül 2026**

**Türkçe çeviri ve 2026 düzenlemesi: Orhan Tan**

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

1. Oyunu kapatın ve mevcut oyun dosyalarınızın bir yedeğini alın.
2. İndirdiğiniz **ZIP dosyasını açın**.
3. İçindeki **tüm dosya ve klasörleri oyunun ana klasörüne kopyalayın**. “Dosyalar değiştirilsin mi?” sorusuna **Evet** deyin.
4. Oyunu açın. Türkçe yama ve Widescreen Fix hazır!

**Oyunun ana klasörü, `speed.exe` dosyasının bulunduğu yerdir.** Dosyaları bu klasörün içine kopyalayın; ayrıca bir alt klasör oluşturmayın. Dil ayarı yapmanız gerekmez.

### Oyun klasörünü nerede bulabilirim?

En kolay yol: Masaüstündeki oyun kısayoluna sağ tıklayıp **Dosya konumunu aç** seçeneğini kullanın.

2005 sürümünün kurulu olduğu klasör, seçtiğiniz diske ve kuruluma göre örneğin şuralarda olabilir:

```text
C:\Program Files (x86)\EA GAMES\Need for Speed Most Wanted\
C:\Program Files\EA GAMES\Need for Speed Most Wanted\
D:\Oyunlar\Need for Speed Most Wanted\
D:\OYUN\EA\Need for Speed Most Wanted 2005\
```

**EA app, eski Origin ve Steam klasörleri:** Oyunlar genellikle aşağıdaki kütüphanelerin içindeki kendi klasörlerinde bulunur. Bunlar genel konum örnekleridir; Most Wanted 2005'in bu platformlarda satıldığı anlamına gelmez.

```text
EA app:  C:\Program Files\EA Games\
Origin:  C:\Program Files (x86)\Origin Games\
Steam:   C:\Program Files (x86)\Steam\steamapps\common\
Başka diskte Steam: D:\SteamLibrary\steamapps\common\
```

Yamayı bu kütüphane klasörlerine doğrudan değil, **içinde `speed.exe` bulunan 2005 oyununun klasörüne** kopyalayın. Steam'e kısayol olarak eklediğiniz oyun, önceki kurulum konumunda kalır.

**Bu yama yalnızca Most Wanted 2005 PC 1.3 içindir.** [Steam mağazasındaki Most Wanted, 2012 sürümüdür](https://store.steampowered.com/app/1262560/Need_for_Speed_Most_Wanted/); bu yamayı ona kurmayın.

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

- Türkçe çeviri, 2026 düzenlemesi ve paketleme: [Orhan Tan / rhntn](https://github.com/rhntn).
- Mevcut German/Dutch Türkçe çeviri tabanı: NFSTR topluluk yaması.
- Türkçe font tabanı: **muntazam**, [Türkçe Yama 1.0.1](https://www.moddb.com/downloads/need-for-speed-most-wanted-turkish-translation-patch-v10). Bu pakette büyük Ş harfinin font ölçüleri ayrıca düzenlenmiştir.
- **ThirteenAG ve katkıda bulunanlar**: [Widescreen Fix](https://github.com/ThirteenAG/WidescreenFixesPack), [Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader). İlgili MIT lisansları `licenses` klasöründedir.
- Harf dönüşümü çalışmalarında kullanılan yardımcı araç: [emres/turkish-deasciifier](https://github.com/emres/turkish-deasciifier).

Bu, EA tarafından yayımlanmayan ve desteklenmeyen bağımsız bir topluluk yamasıdır. Oyunun tamamını veya çalıştırılabilir oyun dosyasını içermez; oyuna sahip olmanız gerekir. Oyun, marka ve üçüncü taraf bileşenlerin hakları kendi sahiplerine aittir. Widescreen Fix ve ASI Loader lisansları oyun/font dosyalarını kapsamaz.
