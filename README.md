### Base Repositories:
1. [Hisoka-Morou](https://github.com/nyx095/Hisoka-Morou)
2. [Wa-OpenAI](https://github.com/Sansekai/Wa-OpenAI)

---
# **WA-GroqAI**

Ini adalah bot WhatsApp yang menggunakan Groq API untuk memberikan respon berbasis AI, serta [Baileys](https://github.com/WhiskeySockets/Baileys) sebagai library utama untuk mengelola interaksi WhatsApp.

### Cara Penggunaan di Desktop/VPS

1. **Instal Node.js dan Git**
   - **Windows/Mac/Linux**: Unduh dan instal Node.js dari situs resmi [Node.js](https://nodejs.org/).
   - **Linux**: Instal Git dengan perintah berikut:
     - **Debian/Ubuntu**: `sudo apt install git -y`
     - **CentOS/Red Hat**: `sudo yum install git -y`

2. **Kloning Repositori**
   Jalankan perintah berikut di terminal:
   ```bash
   git clone https://github.com/maulananais/WA-GroqAI.git
   ```

3. **Masuk ke direktori proyek**
   ```bash
   cd WA-GroqAI
   ```

4. **Instal Dependensi**
   ```bash
   npm install
   ```

5. **Atur API Groq**
   Buka file `key.json` dan masukkan API key Groq yang telah Anda dapatkan:
   ```bash
   {
     "GROQ_API_KEY": "your_api_key_here"
   }
   ```

6. **Jalankan Bot**
   ```bash
   node index.js
   ```

---

### Cara Penggunaan di Termux

1. **Instal Node.js dan Git**
   ```bash
   pkg install nodejs git
   ```

2. **Kloning Repositori**
   ```bash
   git clone https://github.com/maulananais/WA-GroqAI.git
   ```

3. **Masuk ke direktori proyek**
   ```bash
   cd WA-GroqAI
   ```

4. **Instal Dependensi**
   ```bash
   npm install
   ```

5. **Atur API Groq**
   Edit file `key.json` dan masukkan API key Groq Anda.

6. **Jalankan Bot**
   ```bash
   node index.js
   ```

---

### Dokumentasi

Untuk informasi lebih lanjut tentang penggunaan Groq API, silakan kunjungi [Groq Documentation](https://groq.com/docs).

---

### Donasi

Jika Anda ingin mendukung pengembangan proyek ini, silakan berdonasi melalui [Saweria](https://saweria.co/maulananais).

---

### Terima Kasih Kepada:
- Allah SWT
- Orang tua saya
- Pacar saya
- [Groq](https://groq.com) untuk API-nya
- [Node.js](https://nodejs.org) untuk platform backend
- [Git](https://git-scm.com) untuk version control

---

### Lisensi

Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detailnya.
