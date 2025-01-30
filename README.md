# Modern Kayıt Formu Projesi

Bu proje, modern ve kullanıcı dostu bir kayıt formu uygulamasıdır. HTML ve CSS kullanılarak oluşturulmuş, responsive tasarıma sahip bir web formudur.

## Özellikler

- Kişisel bilgi girişi (ad, soyad)
- E-posta doğrulama
- Güvenli parola alanı
- Cinsiyet seçimi
- Favori meyve seçimi
- Mesaj alanı
- Form doğrulama
- Responsive tasarım
- Modern görsel arayüz
- Başarılı/Hatalı durum bildirimleri

## Kullanılan Teknolojiler

- HTML5
- CSS3
- Modern CSS özellikleri (Flexbox, Grid, Transitions)
- Form validasyonu

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/ahmetemreari/PracticeFormElements
```

2. Proje dizinine gidin:
```bash
cd kayit-formu
```

3. `index.html` dosyasını bir web tarayıcısında açın.

## Dosya Yapısı

```
kayit-formu/
│
├── index.html          # Ana HTML dosyası
├── form-styles.css     # CSS stil dosyası
└── README.md          # Proje dokümantasyonu
```

## Kullanım

1. Form alanlarını doldurun:
   - Ad ve soyad bilgilerinizi girin
   - Geçerli bir e-posta adresi girin
   - Güvenli bir parola oluşturun
   - Cinsiyetinizi seçin
   - Favori meyvenizi seçin
   - İsteğe bağlı mesajınızı yazın

2. "Gönder" butonuna tıklayın.

3. Form doğrulama sonucuna göre başarılı/hatalı mesajını görüntüleyin.

## Örnek Form Verileri

```html
Ad: Ahmet
Soyad: Yılmaz
E-posta: ornek@email.com
Şifre: ********
Cinsiyet: Erkek
Favori Meyve: Elma
Mesaj: Merhaba, form testi...
```

## Özelleştirme

### CSS Değişiklikleri

Formun görünümünü özelleştirmek için `form-styles.css` dosyasını düzenleyebilirsiniz:

```css
/* Ana renk değişimi */
:root {
    --primary-color: #3498db;
    --secondary-color: #2ecc71;
}

/* Farklı yazı tipi kullanımı */
body {
    font-family: 'Your-Font', sans-serif;
}
```

### HTML Değişiklikleri

Form alanlarını özelleştirmek için `index.html` dosyasını düzenleyebilirsiniz:

```html
<!-- Yeni form alanı ekleme -->
<div class="form-group">
    <label for="newField">Yeni Alan:</label>
    <input type="text" id="newField" name="newField" required>
</div>
```

## Tarayıcı Desteği

- Chrome (son 3 versiyon)
- Firefox (son 3 versiyon)
- Safari (son 2 versiyon)
- Edge (son 3 versiyon)

## Katkıda Bulunma

1. Bu projeyi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'inize push yapın (`git push origin feature/yeniOzellik`)
5. Pull Request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.

## İletişim

AHMET EMRE ARI info@aemreari.com.tr

Proje Linki: https://github.com/ahmetemreari/PracticeFormElements
