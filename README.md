# Deneyap Telegram Güvenlik Sistemi

Bu proje **Deneyap Kart 1A V2**, **Deneyap Kamera** ve **Deneyap Hareket Sensörü** kullanılarak geliştirilmiştir.  
Amaç: Hareket algılandığında fotoğraf çekip Telegram botu üzerinden kullanıcıya göndermek.

## Özellikler
- Hareket algılandığında Telegram üzerinden bildirim gönderir.
- Kamera ile fotoğraf çekip Telegram botuna iletir.
- Sensör aktif/pasif komutları Telegram üzerinden kontrol edilir.
- Kullanıcı komutları:
  - `/start` → Bot hakkında bilgi
  - `/photo` → Fotoğraf çek
  - `/SensorAktif` → Hareket sensörünü aktif et
  - `/SensorPasif` → Hareket sensörünü pasif et
  - 
## Donanım
- Deneyap Kart 1A V2
- Deneyap Kamera
- Deneyap Hareket Sensörü

## Kullanılan Kütüphaneler
- WiFi.h
- WiFiClientSecure.h
- esp_camera.h
- Deneyap_HareketAlgilama.h
- DeneyapCam.h
- UniversalTelegramBot.h

## Kurulum
1. Arduino IDE’ye gerekli kütüphaneleri ekleyin.
2. Kodda WiFi SSID ve şifreyi güncelleyin.
3. Telegram bot token ve chat_id bilgilerini girin.
4. Kodu Deneyap Kart 1A V2’ye yükleyin.
5. Telegram üzerinden komutları kullanarak sistemi test edin.

## Çalışma Mantığı
- Hareket sensörü algılama yaptığında bot otomatik olarak fotoğraf çeker.
- Fotoğraf Telegram üzerinden kullanıcıya gönderilir.
- Kullanıcı manuel olarak da `/photo` komutuyla fotoğraf isteyebilir.


