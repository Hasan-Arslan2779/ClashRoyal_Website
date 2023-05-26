# ClashRoyal_Website

Bu proje HTML, CSS3 ,JavaScript ve ScrollReveal adlı bir animasyon kütüphanesini kullanarak Clash Royal oyununun web sitesini oluşturmayı amaçlamaktadır.
## Gif
<img src="https://github.com/Hasan-Arslan2779/ClashRoyal_Website/blob/master/ezgif.com-video-to-gif%20(1).gif" alt="Logo" />
## Kurulum

Proje dosyalarını bilgisayarınıza indirdikten sonra, projenin ana dizininde bulunan `index.html` dosyasını bir web tarayıcısıyla açabilirsiniz. 

## Kullanım

ScrollReveal kütüphanesi, web sayfalarında kaydırma olayına tepki veren animasyonlar oluşturmayı sağlar. Bu projede, ScrollReveal kütüphanesini şu adımları izleyerek kullanabilirsiniz:

1. `index.html` dosyasını açın.
2. Kütüphanenin bağlantısını ekleyin. Bunun için aşağıdaki kodu `<head>` etiketi içerisine ekleyin:

    ```html
    <script src="scrollreveal.min.js"></script>
    ```
   
3. Animasyonları uygulamak istediğiniz HTML öğelerine bir sınıf veya kimlik atayın. Örneğin, bir `<div>` öğesine `sr` sınıfını ekleyebilirsiniz:

    ```html
    <div class="sr"></div>
    ```

4. JavaScript dosyasında ScrollReveal'u yapılandırın ve animasyonları tanımlayın. Örneğin, `main.js` dosyasına aşağıdaki kodu ekleyebilirsiniz:

    ```javascript
    // ScrollReveal kütüphanesini başlatma
    ScrollReveal().reveal('.sr', {
      duration: 1000,  // Animasyon süresi (milisaniye cinsinden)
      distance: '20px',  // Öğenin hareket edeceği mesafe
      easing: 'ease-out',  // Animasyon eğrisi
      origin: 'bottom',  // Öğenin nereden başlayacağı
    });
    ```

Bu adımları takip ettikten sonra, web sayfanızdaki öğelerin ScrollReveal animasyonlarıyla görüneceğini görebilirsiniz.

## Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen GitHub deposuna bir "pull request" gönderin. Yeni özellikler ekleyebilir, hataları düzeltebilir veya dokümantasyonu geliştirebilirsiniz.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.


