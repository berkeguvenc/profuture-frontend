# Profuture Frontend

Profuture Teknoloji Dergisi'nin frontend projesi. Bu proje, kullanıcıların dergi sayılarını inceleyebileceği, makale çağrılarını görebileceği ve güncel akademik yazılara ulaşabileceği modern ve responsive bir web arayüzü sunar.

## Proje Hakkında

Profuture, teknoloji, inovasyon, dijital dönüşüm ve geleceğin üretim modelleri alanlarında özgün akademik çalışmalar yayınlayan uluslararası hakemli bir dergidir. Bu frontend projesi, derginin dijital yüzünü oluşturur.

### Özellikler

*   **Responsive Tasarım:** Mobil, tablet ve masaüstü cihazlarla tam uyumlu.
*   **Modern UI:** Bootstrap 5 ve özelleştirilmiş SCSS ile geliştirilmiş şık arayüz.
*   **Bölümler:**
    *   Anasayfa (Hero Section)
    *   Hakkında (Dergi Amacı ve Kapsamı)
    *   Dergiler (Sayılar listesi)
    *   Makale Çağrısı
    *   Güncel Yazılar

## Kurulum ve Kullanım

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin.

### Gereksinimler

*   Node.js (SCSS derlemek için)

### Adımlar

1.  Projeyi klonlayın:
    ```bash
    git clone https://github.com/berkeguvenc/profuture-frontend.git
    cd profuture-frontend
    ```

2.  Bağımlılıkları yükleyin:
    ```bash
    npm install
    ```

3.  SCSS dosyalarını derlemek için (Geliştirme modunda izleme):
    ```bash
    npm run compile-scss
    ```

4.  `index.html` dosyasını tarayıcınızda açarak projeyi görüntüleyebilirsiniz.

## Dosya Yapısı

*   `assets/`: Görseller ve diğer statik dosyalar.
*   `css/`: Derlenmiş CSS dosyaları.
*   `scss/`: SASS kaynak dosyaları.
*   `index.html`: Ana sayfa.
*   `style-guide.html`: Stil rehberi ve bileşenler.

## Kullanılan Teknolojiler

*   HTML5
*   SCSS / CSS
*   Bootstrap 5.3
*   JavaScript

## Lisans

Bu proje ISC lisansı ile lisanslanmıştır. Detaylar için `package.json` dosyasına bakabilirsiniz.
