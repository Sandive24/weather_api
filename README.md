# ☔️ WeatherApp: Real-Time Cuaca Dashboard

Aplikasi desktop GUI untuk menampilkan informasi cuaca terkini berdasarkan nama kota, dikembangkan menggunakan **Flet** dan terintegrasi dengan **WeatherAPI**.

---

## 📅 Fitur Utama

* ✅ Cek cuaca real-time berdasarkan nama kota
* ✅ Tampilkan suhu dalam °C dan °F
* ✅ Detail lokasi: kota, negara, waktu lokal
* ✅ Kecepatan & arah angin (diterjemahkan dalam Bahasa Indonesia)
* ✅ Informasi cuaca lengkap: curah hujan, deskripsi, ikon siang/malam
* ✅ Tampilan responsif, bersih, dan modern

---

## 🦠 Persyaratan Sistem

* Python 3.8 atau lebih baru
* Koneksi internet aktif
* API Key dari [WeatherAPI](https://www.weatherapi.com/)
* File konfigurasi: `apikey.json`

**Dependensi Python:**

```
requests
flet
```

---

## 🔐 Konfigurasi API Key

1. Buat file `apikey.json` di direktori utama.
2. Isi dengan format berikut:

```json
{
  "apikey": "API_KEY_ANDA"
}
```

> ⚠️ **Catatan:** Jangan unggah file ini ke repository publik.

---

## 🌐 Endpoint API

Aplikasi menggunakan endpoint berikut:

```
https://api.weatherapi.com/v1/current.json
```

**Parameter utama:**

* `key` : API Key Anda
* `q` : Nama kota (misal: Jakarta)
* `lang=id` : Bahasa Indonesia

**Contoh URL:**

```
https://api.weatherapi.com/v1/current.json?key=API_KEY_ANDA&q=Jakarta&lang=id
```

---

## ⚙️ Instalasi & Setup

```bash
# (Opsional) Buat virtual environment
python -m venv env
env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 Menjalankan Aplikasi

```bash
python main.py
```

---

## ⚠️ Disclaimer

Aplikasi ini dikembangkan sebagai media pembelajaran dan eksperimen integrasi API. Tidak disarankan untuk digunakan secara komersial.

---

*Dibuat dengan ❤️ oleh: **Ahmad Nur Ikhsan***
