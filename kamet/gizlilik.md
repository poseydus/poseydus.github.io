---
title: Kamet Gizlilik Politikası
permalink: /kamet/gizlilik/
---

# Kamet · Gizlilik Politikası

Son güncelleme: 8 Kasım 2026

Kamet, iPhone ve Apple Watch için bir namaz vakti uygulamasıdır. Bu sayfa, uygulamanın hangi veriyi nerede tuttuğunu ve
nereye gönderdiğini olduğu gibi anlatır. Uygulamanın içindeki **Söz Sayfası › Gizlilik Defteri** aynı
bilgiyi, o ay gerçekten açılan bağlantıların sayısıyla birlikte gösterir.

## Kısaca

- Kamet'in kendi sunucusu yoktur. Hiçbir kaydın bize ya da üçüncü bir tarafa gelmez.
- Hesap açılmaz; ad, e-posta ya da telefon numarası istenmez.
- Analitik, reklam ya da takip SDK'sı yoktur. Uygulama izleme yapmaz.
- Konumun telefonda kalır. Yalnızca yakın camiler aramasında ve Kıble haritasında bulunduğun bölge Apple Haritalar'a gider
  (ayrıntı aşağıda, "Konum" bölümünde).
- Mushaf'ta bir ayeti dinlediğinde ses dosyaları Islamic Network'ün sunucusundan (cdn.islamic.network) akar; o sunucu
  IP adresini görür (ayrıntı aşağıda, "Kur'an tilaveti" bölümünde).

## Cihazda tutulan veriler

Aşağıdakiler yalnızca telefonunda durur:

- Seçtiğin il/ilçe ve hesaplanan vakit tablosu (12 aya kadar, çevrimdışı çalışsın diye).
- Bildirim tercihlerin, Fecir Alarmı ve bayram namazı alarmı ayarın, "Bugün sessiz" durumu, Apple Watch ön-titreşim tercihin.
- Kaza defteri, zikir sayacı, ibadet yolu ve Cüz Yoldaşı kayıtları.
- Kişisel defterler: Helallik, Dua Emaneti, Ruhuna Fatiha, Şükür, Hatır, "Ne engel oldu", Mahrem Mod ve
  kendi eklediğin zikir metinleri. Bunlar korumalı özel klasörde durur; iCloud'a da cihaz yedeğine de girmez. Telefonu kaybedersen
  dışa aktarmadığın notlar geri gelmez.
- Sessiz Girih deseninin bu aya ait kaydı.

Kaza defterini ve zikir toplamını istediğin an düz metin (CSV) olarak dışa aktarabilirsin.

**Hata kaydı:** Kamet çökerse ya da takılırsa iOS, Apple'ın MetricKit çerçevesiyle ertesi açılışta kısa bir tanı verir.
Kamet bundan yalnız çağrı yığınını ve sürüm bilgisini (uygulama, iOS, cihaz modeli) tutar; en çok 20 kayıt, 30 gün.
Kayıt telefonda kalır, Kamet hiçbir yere göndermez. Ayarlar › Hata kaydı'ndan istersen paylaşırsın; nereye gideceğini sen seçersin.

**Tanı dosyası:** Ayarlar › Tanıyı paylaş, bir aksaklığı anlatman için düz metin bir dosya hazırlar: uygulama ve iOS
sürümü, cihaz modeli, dil, saat dilimi, bildirim izni, bekleyen bildirim sayısı, hata kaydının özeti ve bu oturumun son
24 saatindeki Kamet günlükleri. Konum, yer adı ve ibadet kaydı içinde yoktur. Dosyayı paylaşmadan önce görürsün;
Kamet göndermez, yalnız sen paylaşırsan çıkar.

## Konum

"Konumumu kullan" dediğinde telefon konumunu yalnızca en yakın ilçeyi bulmak için bir kez okur; nokta
saklanmaz, saklanan yalnızca seçilen ilçenin kimliğidir. Konum izni vermeden de il/ilçe listesinden seçim
yapabilirsin. Kıble için pusula verisi anlık kullanılır, kaydedilmez.

Yakın camiler aramasında ve Kıble haritasında seçili yerin (il/ilçe merkezinin) çevresi Apple Haritalar'a gönderilir:
arama ve harita karoları Apple'dan gelir. Bu istekler Kamet'e gelmez, Kamet bunları kaydetmez ve isteğe telefonun kesin
konum noktasını eklemez. Konum bunun dışında hiçbir yere gönderilmez.

## Apple Watch

Saat uygulaması seçili yeri, üç günün vakitlerini, "kılındı" işaretini ve zikir sayımını telefondan alır;
paket Apple'ın WatchConnectivity'siyle doğrudan telefonla saat arasında gider, ağa çıkmaz, sunucuya uğramaz.
Saatten telefona yalnızca "Kıldım" ve sayım komutları döner. Saatteki kıble pusulası için konum anlık
kullanılır, kaydedilmez.

## Cihazdan çıkan tek şey: senin Apple hesabın

Kamet'e değil, **senin Apple hesabına** giden veriler:

- **iCloud yedeği:** yalnızca kaza defteri, zikir sayacı, ibadet yolu ve Cüz Yoldaşı; Apple'ın iCloud
  anahtar-değer deposuyla senin öbür cihazlarına eşitlenir. Kamet bu veriyi göremez.
- **App Store:** Levha Plus aboneliği ve tek seferlik destek satın alımları Apple'ın StoreKit'iyle yapılır;
  ödeme bilgin Kamet'e ulaşmaz.
- **Apple Haritalar:** "Yakın camiler" araması ve kıble haritası Apple Haritalar'ı kullanır; seçili yerin çevresi
  Apple'a gider, Kamet'e gitmez.
- **Kamet'ten duyurular:** Kamet ara sıra (günde en çok bir kez) bir duyuru bildirimi gönderebilir. Duyuru Kamet'in
  herkese açık iCloud veritabanına (Apple CloudKit) yazılır, bildirimi Apple teslim eder. Abonelik senin iCloud
  hesabınla Apple'da kurulur; Kamet cihaz kimliğini ya da kim olduğunu görmez. Ayarlar › Vakit bildirimleri ›
  "Kamet'ten duyurular" kapatılınca abonelik silinir.

Bu bağlantıların her biri uygulamanın içindeki Gizlilik Defteri'nde ay bazında sayılır.

## Kur'an tilaveti

Mushaf'ta "Bu ayetten dinle" dediğinde kârinin kaydı ayet ayet Islamic Network'ün içerik dağıtım ağından
(`cdn.islamic.network`, alquran.cloud) akıtılır. Kayıtlar Kral Fahd Mushaf Basım Külliyesi'nindir. Bu bağlantıda
gönderilen tek şey hangi ayetin dosyasının istendiğidir; her internet bağlantısında olduğu gibi sunucu IP adresini
görür. Ad, hesap, konum ya da ibadet kaydı gitmez; Kamet ne dinlediğini kimseye göndermez ve dosyaları toplu indirmez. Dinlemezsen
bu bağlantı hiç kurulmaz. Gizlilik Defteri her ayet dosyasını "Kur'an tilaveti" satırında sayar.

Sonuna kadar dinlediğin ayetin sesi telefonda önbelleğe yazılır; aynı ayeti yeniden dinlerken bağlantı kurulmaz,
çevrimdışı da çalar. Önbellek telefonda kalır, yedeğe girmez, en çok 200 MB tutar. Ayarlar › Depolama'dan silinir.

## Uzaktan özellik anahtarı

Yayındaki bir sürümde bir özellik sorun çıkarırsa Kamet onu uzaktan kapatabilir (şimdilik yalnız ayet sesi). Uygulama
açılışta ve öne gelişte, en çok on dakikada bir, Kamet'in herkese açık iCloud veritabanından (Apple CloudKit) bu
anahtarları okur. Okuma iCloud hesabı istemez; senden hiçbir veri gönderilmez. Gizlilik Defteri bu okumayı
"Kamet özellik anahtarları" satırında sayar.

## İzinler

Uygulama yalnızca gerektiğinde ve gerekçesini söyleyerek izin ister: konum (vakit ve kıble), bildirim
(vakit bildirimleri), hareket (yüzüstü sayaç ve AirPods ile kıble), Face ID (Mühürlü Zarf), kamera
(Kıble'de "Kamerayla bak"; görüntü kaydedilmez, telefondan çıkmaz), takvim (boş aralık önerisi;
etkinlik başlıkları okunmaz, takvime yazılmaz), alarm (Fecir Alarmı). Hiçbirini vermeden de vakitler
ve Levha çalışır.

## Çocuklar

Kamet çocuklara yönelik değildir ve hiç kimseden kişisel veri toplamaz.

## Değişiklikler

Bu sayfadaki maddeler değişirse 12 ay önce uygulamanın Söz Sayfası'ndan duyurulur ve mevcut kullanıcılar
etkilenmez. Sayfanın üstündeki tarih son değişikliği gösterir.

## İletişim

Soru ve istekler için: [work.kaanyildirim@gmail.com](mailto:work.kaanyildirim@gmail.com)
