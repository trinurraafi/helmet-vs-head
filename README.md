# 🪖 AI Helmet Detection (Pakai Helm vs Tidak Pakai Helm)

Project ini adalah sistem AI sederhana buat ngecek apakah seseorang **pakai helm kerja atau tidak**. Cocok banget buat kebutuhan safety di area proyek, pabrik, atau tempat kerja yang wajib APD (Alat Pelindung Diri).

---

## 🚀 Tentang Project Ini

Jadi gini guys, AI ini bakal bantu deteksi orang yang:
- 🪖 **Pakai Helm Kerja (Safe)**
- ❌ **Tidak Pakai Helm (Unsafe)**

Dengan bantuan model machine learning (object detection), kamera akan langsung ngecek kondisi di lapangan secara real-time.

---

## 🧠 Cara Kerja Singkat

1. Kamera nyala (webcam)
2. AI baca objek di frame
3. Model ngecek:
   - Ada helm atau tidak
4. Hasilnya langsung muncul di layar:
   - 🟢 Safe (pakai helm)
   - 🔴 Danger (tidak pakai helm)

---

## ⚙️ Teknologi yang Dipakai

- HTML, CSS, JavaScript
- ONNX Model / Roboflow Export
- Webcam Real-time Detection
- Canvas untuk overlay bounding box

---

## 📦 Dataset & Training

Model ini dilatih menggunakan dataset gambar:
- Orang pakai helm kerja
- Orang tidak pakai helm kerja
- Berbagai sudut kamera
- Kondisi cahaya berbeda

Tahapan:
1. Kumpulin dataset
2. Labeling (helm / no-helm)
3. Training di Roboflow / Colab
4. Export ke ONNX
5. Integrasi ke web

---

## 🧪 Fitur

- Deteksi real-time via webcam
- Bounding box otomatis
- Status safety (Safe / Danger)
- Ringan dan bisa dijalankan di browser

---

## 📸 Preview

*(Tambahin screenshot di sini kalau ada biar makin keren 😎)*

---

## 🌐 Deployment

Project ini sudah **di-deploy di GitHub Pages** supaya bisa langsung diakses lewat browser tanpa install apa-apa.

---

## 👨‍💻 Dibuat oleh

- Tri Nur Raafi  
- Ragga Hafidz Fianugra  
- Ziddan Mulki Akbar  

---

## 🔥 Catatan

Project ini masih bisa dikembangkan lagi biar makin akurat, misalnya:
- Tambahin detection posisi helm (benar / miring)
- Tambahin alarm suara kalau tidak pakai helm
- Upgrade model biar lebih akurat di kondisi gelap

---

> “Safety dulu, baru kerja. Helm itu bukan gaya, tapi nyawa.” 🪖🔥
