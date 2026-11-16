# FitNotes+ Personal — MVP

## İçerik
- Koyu temalı, mobil öncelikli antrenman takip arayüzü
- Set/ağırlık/tekrar kaydı, rutinler, geçmiş, hacim grafiği, dinlenme sayacı ve PR tahmini
- JSON yedekleme ve geri yükleme
- localStorage ile yerel tarayıcı depolaması
- PWA manifest ve service worker (HTTPS yayınlandığında ana ekrana eklenebilir ve çevrimdışı açılabilir)

## iPhone'da kullanım
1. Bu klasörü HTTPS destekleyen bir statik web barındırma servisine yükle (ör. kendi hosting'in).
2. Yayınlanan adresi iPhone Safari'de aç.
3. Paylaş > Ana Ekrana Ekle.
4. İlk açılıştan sonra çevrimdışı açılışı test et.
5. Ayarlar bölümünden düzenli JSON yedeği al.

## Önemli
- Bu ilk MVP'dir; veriler yalnızca aynı tarayıcı/uygulama kurulumunun yerel depolamasında tutulur.
- Safari verilerini silmek veya cihazı değiştirmek kayıtları kaybettirebilir. JSON yedeklerini sakla.
- PR, setin tahmini 1RM değerine (Epley formülü) göre belirlenir; gerçek maksimum kaldırış değildir.
- Gerçek kullanım öncesinde geliştirme/test yapılması önerilir.
