# STM32F103 Custom PCB Design

Bu repo, yaz stajım sırasında tasarladığım **STM32F103C8T6 tabanlı özel PCB** projesini içermektedir. Tasarım, **KiCad** kullanılarak gerçekleştirilmiştir.

## Proje Özeti

Bu kart, STM32F103C8T6 mikrodenetleyicisini temel alan kompakt bir geliştirme kartı  olarak tasarlanmıştır. Kart üzerinde temel güç yönetimi, programlama ve haberleşme arayüzleri bulunmaktadır.

## Kart Üzerindeki Temel Bileşenler

- **STM32F103C8T6** mikrodenetleyici
- **AMS1117-3.3** lineer regülatör
- **16 MHz kristal osilatör**
- **USB Micro-B** konnektör
- **SWD** programlama arayüzü
- **UART** bağlantı header'ı
- **I2C** bağlantı header'ı
- **BOOT0** anahtarı
- Güç gösterge LED’i
- Filtreleme ve decoupling kapasitörleri
- Montaj delikleri

## Tasarım Özellikleri

- Çift katmanlı PCB tasarımı
- 3.3V regülasyon yapısı
- USB üzerinden besleme
- SWD ile programlama/debug desteği
- UART ve I2C pinlerinin dışarı alınması
- Kompakt yerleşim ve uygun yönlendirme

## Kullanılan Araçlar

- **KiCad** – Şematik ve PCB tasarımı
- **STM32CubeIDE / STM32 ekosistemi** – Mikrodenetleyici geliştirme süreci için



## Not

Bu repo, yaz stajı boyunca yapılan PCB tasarım çalışmalarını belgelemek amacıyla oluşturulmuştur.
