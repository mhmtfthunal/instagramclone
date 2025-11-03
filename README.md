# Instagram Clone

Bootstrap 5 kullanılarak geliştirilmiş Instagram web arayüzü klonu. Bu proje, Patika Bootstrap eğitimi kapsamında hazırlanmıştır.

![Instagram Clone](https://img.shields.io/badge/Bootstrap-5.3.0-purple)
![FontAwesome](https://img.shields.io/badge/FontAwesome-6.4.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-orange)
![CSS3](https://img.shields.io/badge/CSS3-blue)

## 📸 Proje Hakkında

Bu proje, Instagram'ın ana sayfasının görsel ve işlevsel bir kopyasını Bootstrap framework'ü kullanarak oluşturmayı amaçlamaktadır. Responsive tasarım prensiplerine uygun olarak geliştirilmiş olup, farklı ekran boyutlarında sorunsuz çalışmaktadır.

## 🚀 Özellikler

### Navbar
- ✅ Sticky navbar - Sayfa kaydırıldığında üstte sabit kalır
- ✅ 54px yükseklik, beyaz arkaplan
- ✅ Instagram logosu
- ✅ Arama kutusu ve işlevsel placeholder
- ✅ Responsive menü ikonları (küçük ekranlarda gizlenir)

### Ana İçerik
- ✅ Hikayeler (Stories) bölümü
  - Gradient border efekti
  - Yatay scroll özelliği
  - Kullanıcı isimleri resimlerin altında
- ✅ Gönderi kartları (Posts)
  - Profil bilgileri
  - Beğeni, yorum, paylaşma ikonları
  - Kaydetme (bookmark) özelliği
  - Yorum ekleme alanı
- ✅ Responsive grid yapısı

### Sağ Panel
- ✅ Sticky sidebar - Scroll ile birlikte hareket eder
- ✅ Profil bilgileri
- ✅ Kullanıcı önerileri
- ✅ Footer linkleri

### Genel
- ✅ Instagram renk paleti (#fafafa arkaplan)
- ✅ FontAwesome ikonları
- ✅ Tam responsive tasarım
- ✅ Modern ve temiz kullanıcı arayüzü

## 🛠️ Kullanılan Teknolojiler

- **HTML5** - Semantic yapı
- **CSS3** - Custom stiller ve animasyonlar
- **Bootstrap 5.3.0** - Responsive grid sistem ve componentler
- **FontAwesome 6.4.0** - İkonlar

## 📦 Kurulum ve Kullanım

### Gereksinimler
- Modern bir web tarayıcısı (Chrome, Firefox, Safari, Edge)
- İnternet bağlantısı (CDN'ler için)

### Çalıştırma

1. Projeyi klonlayın:
```bash
git clone https://github.com/mhmtfthunal/instagramclone.git
```

2. Proje dizinine gidin:
```bash
cd instagramclone
```

3. `index.html` dosyasını tarayıcınızda açın:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Alternatif olarak, bir local server kullanabilirsiniz:
```bash
# Python 3 ile
python -m http.server 8000

# Node.js ile
npx serve
```

## 📁 Proje Yapısı

```
instagramclone/
│
├── index.html          # Ana HTML dosyası
├── css/
│   └── style.css      # Özel CSS stilleri
├── assets/            # Görseller klasörü
└── README.md          # Proje dokümantasyonu
```

## 🎨 Bootstrap Özellikleri

Projede kullanılan önemli Bootstrap class'ları:

- **Grid System**: `container`, `row`, `col-*`, `offset-*`
- **Flexbox**: `d-flex`, `flex-column`, `align-items-*`, `justify-content-*`
- **Display**: `d-none`, `d-sm-flex`, `d-md-block`
- **Spacing**: `m-*`, `p-*`, `mb-*`, `mt-*`, `ms-*`, `me-*`
- **Components**: `navbar`, `card`, `form-control`
- **Utilities**: `sticky-top`, `rounded-circle`, `text-*`, `bg-*`

## 📱 Responsive Tasarım

| Ekran Boyutu | Layout |
| Desktop (>768px) | Navbar + Posts + Sağ Panel (3 kolon) |
| Tablet (576-768px) | Navbar + Posts (2 kolon) |
| Mobile (<576px) | Tek kolon layout |

## 🌐 Demo

Proje şu anda online placeholder görseller kullanmaktadır:
- Logo: Instagram CDN
- Profil fotoğrafları: pravatar.cc
- Post görselleri: picsum.photos

## 🔧 CSS Detayları

```css
/* Instagram Renkleri */
Arkaplan: #fafafa
Muted Text: #8e8e8e
Border: #dbdbdb

/* Hikaye Gradient */
background: linear-gradient(45deg, 
  #f09433 0%, #e6683c 25%, 
  #dc2743 50%, #cc2366 75%, 
  #bc1888 100%);
```
## 📄 Lisans

Bu proje eğitim amaçlı hazırlanmıştır. Instagram ve Meta Platforms, Inc. şirketinin ticari markalarıdır.
