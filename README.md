# 🔥 Angular + Firebase Starter

A simple Angular application integrated with Firebase services via **AngularFire**.

## 🧩 Features

- 🔐 **Authentication** using Firebase (Email/Password, Google Sign-In)
- 🗄️ **Cloud Firestore** for secure, scalable database operations
- ☁️ **Cloud Storage** for uploading and serving user-generated files
- 🌐 **Firebase Hosting** deployment (optional)
- 🔔 **Cloud Messaging** and **Performance Monitoring** support

## 🚀 Requirements

- Node.js (v14+ recommended)
- Angular CLI (`npm install -g @angular/cli`)
- Firebase CLI (`npm install -g firebase-tools`)

## 📥 Installation & Setup

1. Clone the repo  
   ```bash
   git clone https://github.com/YusufTufan/angular_firebase.git
   cd angular_firebase
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Add Firebase to your Angular project  
   ```bash
   ng add @angular/fire
   ```
   - Choose Authentication, Firestore, Storage, Hosting
   - Insert your Firebase config into `environment.ts`

4. Log in to Firebase CLI and link your project  
   ```bash
   firebase login
   firebase use --add
   ```

5. (Optional) Deploy to Firebase Hosting:
   ```bash
   firebase init hosting
   firebase deploy
   ```

## ▶️ Development

```bash
ng serve
```

Runs the app at `http://localhost:4200`.

---

# 🧠 Angular + Firebase Başlangıç Projesi

Basit bir Angular uygulaması olup, **AngularFire** ile Firebase servislerine entegredir.

## 🧩 Özellikler

- 🔐 Firebase kimlik doğrulama (E‑posta/Şifre, Google ile Giriş)
- 🗄️ Cloud Firestore veritabanı
- ☁️ Cloud Storage dosya yükleme ve indirme
- 🌐 Firebase Hosting deploy
- 🔔 Cloud Messaging ve Performans İzleme desteği

## 🚀 Gereksinimler

- Node.js (v14+ tavsiye edilir)
- Angular CLI (`npm install -g @angular/cli`)
- Firebase CLI (`npm install -g firebase-tools`)

## 📥 Kurulum & Yapılandırma

1. Repoyu klonla  
2. `npm install` ile bağımlılıkları yükle  
3. `ng add @angular/fire` komutuyla Firebase entegrasyonu  
4. `firebase login` ve `firebase use --add` ile projeyi bağla  
5. (Opsiyonel) `firebase init hosting` ve `firebase deploy`

## ▶️ Geliştirme

```bash
ng serve
```

`http://localhost:4200` adresinde açılır.

---

## 👨‍💻 Developer

**Yusuf Tufan**  
