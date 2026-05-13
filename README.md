<div align="center">

# 👋 Merhaba, ben Ahmet Buğra Kaplan

### Yazılım Mühendisliği Öğrencisi · Backend Geliştirici · Robotik & Bilgisayarlı Görü Meraklısı

![Profile Views](https://komarev.com/ghpvc/?username=AhmetBugraKaplan&label=Profile%20views&color=0e75b6&style=flat)
![Followers](https://img.shields.io/github/followers/AhmetBugraKaplan?label=Followers&style=social)
![Stars](https://img.shields.io/github/stars/AhmetBugraKaplan?label=Stars&style=social)

</div>

---

## 🚀 Hakkımda

- 🎓 **İstanbul Topkapı Üniversitesi** — Yazılım Mühendisliği öğrencisiyim
- 🏦 Şu anda **VakıfBank ATM geliştirme ekibinde** stajyer olarak gerçek bir banka simülasyonu üzerinde çalışıyorum
- 🤖 **Drone otonomi, SLAM, bilgisayarlı görü ve 3B haritalama** konularına ilgi duyuyorum
- 🛰️ Akademik BAP projesi **Kâşif** kapsamında GPS bağımsız otonom UAV sistemleri geliştiriyorum
- 🌱 Şu sıralar **ROS 2 Humble, PX4 SITL ve LVI-SAM** üzerinde derinleşiyorum
- 💡 Backend mimari (Clean Architecture, BFF pattern), ML pipeline tasarımı ve gerçek zamanlı sistemler ilgi alanlarımın merkezinde

---

## 🛠️ Kullandığım Teknolojiler

### Backend & API
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

### Frontend & Mobile
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

### Veritabanı
![MSSQL](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Entity Framework](https://img.shields.io/badge/EF%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

### AI / ML / Computer Vision
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

### Robotik & Donanım
![ROS](https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6A00?style=for-the-badge&logo=gazebo&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white)

### Araçlar
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 📌 Öne Çıkan Projelerim

### 🏦 [BankaSimulasyonAPI](https://github.com/AhmetBugraKaplan/BankaSimulasyonAPI)
VakıfBank stajım kapsamında geliştirdiğim **gerçek bir ATM simülasyonu**. Tüm katmanları (backend, BFF/middleware, frontend, veritabanı) kıdemli mühendis denetiminde tek başıma kurguladım.

- **Stack:** Angular 17+ → BFF (AraKatman) → CoreAPI → MSSQL
- **Mimari:** Clean Architecture, Stored Procedure tabanlı CRUD, atomik SP tasarımı
- **Güvenlik:** JWT (ipAdresi claim), MemoryCache token blacklist, IpControlMiddleware
- **Pipeline:** Exception → Logging → RateLimit → Auth & Authorization → IpControl
- **Özellikler:** Para çekme/yatırma, havale, kartsız işlem, OTP doğrulama, banknote dağıtım algoritması

---

### ☀️ [SolarPanelProblemDetectionDrone](https://github.com/AhmetBugraKaplan/SolarPanelProblemDetectionDrone) ⭐ 4
Kendi yaptığımız drone'a takılı **ESP32-CAM** ile güneş panellerini tespit edip arıza analizini yapan tam donanım + yazılım projesi.

- **Donanım:** Özel tasarım drone + ESP32-CAM modülü
- **Görü:** YOLO tabanlı panel tespiti ve hata sınıflandırma
- **Kapsam:** Hem hardware integration hem Python tarafı CV pipeline

---

### 🧠 [Fraud-Detection-With-Deep-Learning](https://github.com/AhmetBugraKaplan/Fraud-Detection-With-Deep-Learning) ⭐ 4
Telefon dolandırıcılığını tespit eden uçtan uca bir sistem.

- **Model:** TensorFlow / Keras üzerinde derin öğrenme
- **API:** Flask ile servis katmanı
- **Mobil:** Kotlin + Jetpack Compose ile MVVM mimarisinde Android uygulaması

---

### 🚗 [CarRecommendationSystem](https://github.com/AhmetBugraKaplan/CarRecommendationSystem) ⭐ 5
Otomobil fiyat tahmini ve öneri sistemi.

- **Modeller:** Random Forest, Gradient Boosting
- **Performans:** %98 R² skoru
- **Pipeline:** Veri temizleme, feature engineering, model karşılaştırması

---

### 💊 [DrugClassificationMobileApp](https://github.com/AhmetBugraKaplan/DrugClassificationMobileApp) ⭐ 5
İlaç sınıflandırması yapan mobil uygulama için makine öğrenmesi modeli.

---

### ⚡ [EnergyMonitorWithMLModel](https://github.com/AhmetBugraKaplan/EnergyMonitorWithMLModel) ⭐ 3
ML destekli enerji tüketimi izleme sistemi.

---

## 🛰️ Üzerinde Çalıştığım Akademik Projeler

### Kâşif — GPS Bağımsız Otonom UAV (BAP GAP-2026-006)
**İstanbul Topkapı Üniversitesi** bünyesinde, kapalı ve kültürel açıdan kıymetli mekânların 3B haritalanması için geliştirdiğim otonom hava aracı.

- **Platform:** Ubuntu 22.04 + ROS 2 Humble + PX4 SITL + Gazebo
- **SLAM:** LVI-SAM (RealSense D455 ile dokulu 3B çıktı)
- **Engel kaçınma:** RRT* (global) + MPPI (local) + VFH+ (reactive)
- **Doğrulama:** Total station, ArUco markers, ICP, CloudCompare C2C, ATE/RTE (`evo`)

---

## 📊 GitHub İstatistikleri

<div align="center">

![Ahmet's GitHub stats](https://github-readme-stats.vercel.app/api?username=AhmetBugraKaplan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AhmetBugraKaplan&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=AhmetBugraKaplan&theme=tokyonight&hide_border=true)

</div>

---

## 🏆 Trophy Koleksiyonu

<div align="center">

![Trophy](https://github-profile-trophy.vercel.app/?username=AhmetBugraKaplan&theme=tokyonight&no-frame=true&row=1&column=7)

</div>

---

## 📫 İletişim

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AhmetBugraKaplan)

</div>

---

<div align="center">

### ✨ "Kod yazmak değil, problem çözmek için yazılım yapıyorum." ✨

⭐️ Beğendiysen yıldız bırakmayı unutma!

</div>
