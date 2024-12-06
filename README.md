# Basit Blog Sitesi

Bu proje, HTML ve CSS kullanılarak oluşturulmuş basit bir blog sitesidir. Site, bir ana sayfa ve bir blog gönderisi sayfası içerir. Her iki sayfa da stil için bir CSS dosyasını kullanır.

## Proje İçeriği

### 1. Dosya Yapısı
- `index.html`: Ana sayfa.
- `post.html`: Blog gönderisi sayfası.
- `styles.css`: Tüm sayfaların görünümünü düzenleyen CSS dosyası.
- `images/`: Blog gönderilerinde kullanılan görsellerin bulunduğu klasör.

### 2. Sayfalar
#### Ana Sayfa (`index.html`)
- **Başlık:** Sayfanın başında büyük bir başlık bulunur.
- **Menü:** Ana sayfa ve blog gönderisi sayfasına yönlendiren bağlantılar içerir.
- **Son Gönderiler:** İki blog gönderisinin özetlerini içeren kartlar yan yana sıralanmıştır.
- **Footer:** Sayfanın altında telif hakkı bilgisi yer alır.

#### Blog Gönderisi Sayfası (`post.html`)
- **Başlık:** Sayfanın başında büyük bir başlık bulunur.
- **Menü:** Ana sayfa ve blog gönderisi sayfasına yönlendiren bağlantılar içerir.
- **Blog İçeriği:** Tam blog gönderisi içeriği ortalanmış bir düzenle gösterilir.
- **Footer:** Sayfanın altında telif hakkı bilgisi yer alır.

### 3. Teknik Detaylar
- **HTML:** Yapısal işaretleme için kullanılmıştır.
- **CSS:** Stil verme ve düzenleme için kullanılmıştır.
  - Renk Paleti:
    - Arka Plan: `#f4f4f4`
    - Başlık ve Footer: `#333`
    - Metin: `#333` (başlıklar) ve `#666` (paragraflar)
  - Yazı Tipi: Arial, sans-serif
  - Blog gönderileri, yuvarlatılmış köşelere ve gölge efektine sahip kartlar olarak görüntülenir.
  - Responsive tasarım ile mobil cihazlar için uygun hale getirilmiştir.

## Kullanım

1. **Proje Klasör Yapısı**
   - Projeyi aşağıdaki şekilde yapılandırın:
     ```
     /blog-site
     |-- index.html
     |-- post.html
     |-- styles.css
     |-- /images
         |-- blog1.jpg
         |-- blog2.jpg
         |-- blog1-full.jpg
     ```

2. **Görseller**
   - `images` klasörüne uygun görselleri ekleyin.
   - Görsellerin dosya adlarını HTML dosyasında doğru bir şekilde referanslayın.

3. **Tarayıcıda Görüntüleme**
   - Proje dosyalarını bir klasöre yerleştirin.
   - `index.html` dosyasını bir tarayıcıda açarak projeyi görüntüleyebilirsiniz.

## Özelleştirme
- Daha fazla blog gönderisi eklemek için:
  1. `index.html` dosyasındaki `<div class="blog-container">` içine yeni bir `<article>` bloğu ekleyin.
  2. Yeni gönderi için bir görsel ve başlık belirleyin.
  3. Gerekirse yeni bir blog gönderisi sayfası (`post2.html` gibi) oluşturun.

- Renkler, yazı tipleri veya düzeni değiştirmek için `styles.css` dosyasını düzenleyin.

