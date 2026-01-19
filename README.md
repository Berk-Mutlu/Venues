# Venues (MekanBul)

**Venues**, kullanıcıların konum tabanlı olarak mekanları keşfetmesini, yorum yapmasını ve mekan eklemesini sağlayan modern bir Full-Stack web uygulamasıdır.
## 🔗 Canlı Demo
- **Frontend**: [https://web-s7ma.vercel.app/](https://web-s7ma.vercel.app/)
- **Backend API**: [https://web-gamma-orpin-77.vercel.app/](https://web-gamma-orpin-77.vercel.app/)
## 🌟 Özellikler (Features)
- **Mekan Keşfi**: Yakın çevredeki mekanları listeleme.
- **Detaylı Bilgi**: Mekanların puanlarını, adreslerini ve imkanlarını görüntüleme.
- **Kullanıcı Etkileşimi**: Yorum ve puan ekleme/silme/güncelleme.
- **Yönetim**: Yeni mekan ekleme ve düzenleme.
- **Güvenli Giriş**: JWT ve Passport.js tabanlı kullanıcı kimlik doğrulama (Register/Login).

## 🛠️ Teknolojiler (Tech Stack)

### Frontend
- **React**: Kullanıcı arayüzü kütüphanesi.
- **Redux Toolkit**: Durum yönetimi (State management).
- **Vite**: Hızlı geliştirme ve build aracı.
- **Axios**: API istekleri için.
- **React Router**: Sayfa yönlendirmeleri.

### Backend
- **Node.js & Express**: Sunucu tarafı uygulama çatısı.
- **MongoDB & Mongoose**: Veritabanı ve ORM.
- **Passport.js & JWT**: Kimlik doğrulama.

## 🚀 Kurulum (Installation)

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin.

### 1. Projeyi Klonlayın
```bash
git clone https://github.com/Berk-Mutlu/Venues.git
cd Venues
```

### 2. Backend Kurulumu
```bash
cd mekanbul-backend-main
npm install
```
`.env` dosyanızı oluşturun ve gerekli değişkenleri ekleyin (DB URI, JWT Secret vb.).
```bash
npm run start
```
Sunucu varsayılan olarak `localhost:3000` (veya ayarladığınız portta) çalışacaktır.

### 3. Frontend Kurulumu
Yeni bir terminal açın ve frontend klasörüne gidin:
```bash
cd mekanbul-frontend-main
npm install
npm run dev
```
Uygulama `localhost:5173` adresinde çalışacaktır.



