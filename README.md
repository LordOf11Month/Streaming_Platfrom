# 🎥 Video Streaming Platformu

Kullanıcıların video yükleyip izleyebileceği, modern arayüze sahip bir streaming servisidir. Angular tabanlı frontend ve Node.js/Express backend ile geliştirilmiştir.

---

## 🚀 Temel Özellikler (MVP)

- **Sürükle & Bırak Video Yükleme**
- **MP4/WebM Video Oynatıcı**
- **Video Metadata Yönetimi** (Başlık, açıklama)
- **Mobil Uyumlu Responsive Tasarım**
- **MongoDB ile Basit Metadata Saklama**
- **FFmpeg ile Temel Video Dönüşümleri**

---

## ⚙️ Teknoloji Stack

| Katman      | Teknoloji                |
|-------------|-------------------------|
| Frontend    | Angular 17, Material UI |
| Backend     | Node.js, Express        |
| Dosya Yükle | Multer                  |
| Video İşleme| FFmpeg                  |
| Veritabanı  | MongoDB                 |

---

## 📂 Dosya Yapısı

```
/src
├── /server           # Node.js + Express backend
│   ├── app.js        # Ana sunucu dosyası
│   ├── /routes       # API rotaları (upload, stream, vs.)
│   ├── /controllers  # Yükleme, streaming mantığı
│   ├── /models       # MongoDB şema ve modelleri
│   └── /utils        # FFmpeg, dosya işlemleri
├── /client           # Angular frontend
│   ├── /src
│   │   ├── /app
│   │   │   ├── /components  # Yükleme, oynatıcı, liste vs.
│   │   │   └── app.module.ts
│   │   └── index.html
│   └── angular.json
└── README.md
```


## 🧑‍💻 Katkı Sağlama

1. Repoyu fork'layın
2. Yeni bir branch açın: `git checkout -b feature/yeni-ozellik`
3. Değişikliklerinizi commit'leyin
4. Branch'i push'layın: `git push origin feature/yeni-ozellik`
5. Pull Request açın

---


## 🔮 Eklenebilir Özellikler

-  AI ile otomatik içerik tanıma
-  Zaman damgalı tag yönetimi

---
