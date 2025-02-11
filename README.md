# C Epoch Time Calculator

Bu proje, iki farklı tarih ve saat bilgisi arasında geçen zaman farkını hesaplayan bir **C** programıdır. Kullanıcıdan tarih ve saat bilgilerini alır, bu bilgileri epoch (Unix) zamanına çevirir ve iki zaman arasındaki farkı saniye cinsinden hesaplar.

## Özellikler

- Kullanıcıdan iki tarih ve saat bilgisi alır.
- Tarih ve saat bilgilerini epoch zamanına çevirir.
- İki tarih ve saat arasındaki zaman farkını hesaplar ve ekrana yazdırır.
- Basit tarih/saat doğrulama işlemi yapar (örn. yıl, ay, gün sınırları).

## Gereksinimler

- **C Compiler**: Programı derlemek için bir C derleyicisi (örn. `gcc`).
- **Standart Kütüphaneler**: `stdio.h`, `time.h`, `stdlib.h`, `math.h`.

## Kurulum

1. Kaynak kodu bir dosyaya yapıştırın (örn. `epoch_calculator.c`).
2. Aşağıdaki komutla derleyin:

   ```bash
   gcc -o epoch_calculator epoch_calculator.c -lm
