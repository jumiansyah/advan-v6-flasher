# 🛠️ Advan V6 & ZLT S50 Flasher

![Project Banner](assets/banner.png)

### **Flasher Firmware MOD High-Performance untuk Modem CPE Advan V6 / ZLT S50.**
> Optimalkan performa modem Anda dengan kemudahan instalasi melalui Termux.

---

## 🛑 PRASYARAT WAJIB (BACA DULU!)
Agar instalasi berjalan sukses tanpa hambatan, pastikan Anda telah memenuhi poin-poin berikut:

> [!IMPORTANT]
> **Registrasi Serial Number (SN)**
> Anda **WAJIB** mendaftarkan SN Modem Advan V6 Anda melalui link Facebook berikut:
> 👉 [Daftar SN di Sini (IHABT Group)](https://fb.com/share/p/1CDswtfsiY/)

*   📱 **HP Android**: Wajib menggunakan perangkat Android untuk proses flashing.
*   📡 **Koneksi Stabil**: Modem harus memiliki akses internet (minimal kuota 500MB).
*   🔄 **Fresh Reboot**: Reboot modem Anda sebelum memulai agar sistem dalam kondisi segar.
*   🛑 **Idle Mode**: Pastikan modem tidak sedang digunakan secara intensif saat flashing.

---

## 📥 Cara Instalasi (Step-by-Step)

Ikuti urutan langkah di bawah ini dengan teliti:

1.  **Install Termux**: Download dan install aplikasi **Termux** dari Play Store atau F-Droid.
2.  **Koneksi Wifi**: Hubungkan HP Android Anda ke Wifi dari Modem Advan V6 (Wajib).
3.  **Eksekusi Command**: Copy perintah di bawah ini, lalu paste ke dalam aplikasi Termux dan tekan **ENTER**:

```bash
pkg update && pkg upgrade -y && pkg install wget && \
wget https://raw.githubusercontent.com/armarchindo/advan-v6-flasher/main/advanv6_flasher -O advanv6_flasher && \
chmod +x ./advanv6_flasher && ./advanv6_flasher
```

4.  **Konfirmasi**: Tekan **ENTER** pada setiap petunjuk (Next) hingga selesai.
5.  **Finish**: Tunggu hingga modem melakukan restart secara otomatis.

---

## 🔧 Fitur Opsional (Telnet & SSH)
Ingin mengaktifkan fitur **Telnet** dan **SSH**? Gunakan utility khusus kami:

```bash
pkg update && pkg upgrade -y && pkg install wget && \
wget https://raw.githubusercontent.com/armarchindo/advan-v6-flasher/main/advanv6_utility -O advanv6_utility && \
chmod +x ./advanv6_utility && ./advanv6_utility
```

---

## 👥 Komunitas & Dukungan
Butuh bantuan atau ingin melihat detail penggunaan firmware ini? Bergabunglah dengan komunitas kami:

[![Facebook Group](https://img.shields.io/badge/Facebook-Group-blue?style=for-the-badge&logo=facebook)](https://fb.com/share/p/1CDswtfsiY/)

---
<p align="center">
  Disusun dengan ❤️ oleh komunitas <b>IHABT</b>
</p>
