# 🌤️ Aplikasi Cek Cuaca - Python + Flet + WeatherAPI

Aplikasi desktop GUI untuk menampilkan informasi cuaca berdasarkan nama kota. Dibuat dengan framework **[Flet](https://flet.dev/)** dan mengambil data dari **[WeatherAPI](https://www.weatherapi.com/)**.

---

## 📦 Fitur Utama

✅ Cek cuaca saat ini berdasarkan nama kota  
✅ Mendukung suhu dalam °C dan °F  
✅ Tampilkan informasi seperti:
- Kota, negara, waktu lokal
- Kecepatan & arah angin
- Curah hujan
- Deskripsi kondisi cuaca
- Icon siang/malam

✅ Arah angin ditampilkan dalam bahasa Indonesia  
✅ Antarmuka responsif dan modern

---

## 🧰 Persyaratan

- Python 3.8+
- Koneksi internet aktif
- API Key dari [WeatherAPI.com](https://www.weatherapi.com/)  
  **Sekarang disimpan di file `apikey.json` untuk alasan privasi**
- Library Flet & Requests

---

## 🔑 Cara Menyimpan API Key

1. Buat file baru bernama `apikey.json` di direktori utama project.
2. Isi file tersebut dengan format berikut:
   ```json
   {
     "apikey": "API_KEY_ANDA"
   }
   ```
   Ganti `API_KEY_ANDA` dengan API key milik Anda dari WeatherAPI.

---

## 🌐 Endpoint WeatherAPI

Aplikasi ini menggunakan endpoint berikut untuk mengambil data cuaca:
```
https://api.weatherapi.com/v1/current.json
```
Parameter yang digunakan:  
- `key` (API Key Anda)
- `q` (nama kota)
- `lang=id` (bahasa Indonesia)

Contoh request:
```
https://api.weatherapi.com/v1/current.json?key=API_KEY_ANDA&q=Jakarta&lang=id
```

---

## ⚙️ Instalasi

1. **Clone atau download project ini**
2. **(Opsional) Buat virtual environment**  
   ```bash
   python -m venv API_Env
   API_Env\Scripts\activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Simpan API key Anda di file `apikey.json` seperti petunjuk di atas**

---

## 🚀 Menjalankan Aplikasi

```bash
python main.py
```

---

## Ahmad Nur Ikhsan