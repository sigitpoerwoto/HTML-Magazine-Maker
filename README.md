# 📖 Flip Magazine: Standalone HTML Zine Creator

[🇺🇸 English Version](#english-version) | [🇮🇩 Versi Indonesia](#versi-indonesia)

---

<a id="english-version"></a>
## 🇺🇸 English Version

**Flip Magazine** is a privacy-first, purely frontend web application designed to help you curate, read, and export your personal digital magazines. 

Instead of relying on cloud databases or social accounts, Flip Magazine stores everything locally on your browser and allows you to export your entire curated magazine into a **Single Standalone HTML File**. You can share this file via email, USB, or WhatsApp, and anyone can open it in their browser—complete with interactive swipe gestures, videos, and aesthetic layouts—without needing to install any app.

### ✨ Core Features
* **100% Local & Private:** No backend, no database, no accounts. Everything is saved in your browser's `localStorage`.
* **Standalone HTML Export:** Download your magazine as a single `.html` file. It retains all videos, images, and reading logic.
* **Smart Layout Engine:** * Automatically splits long text into multiple pages (Auto-Pagination).
    * Intelligently arranges images based on orientation (Landscape = 1 per page, Portrait = 2 per page).
    * Z-Pattern reading flow (alternating left-right content).
* **Rich Media Support:** Embed direct image links, MP4 videos, HLS streams (`.m3u8`), and YouTube videos.
* **Dynamic Color Palette:** Automatically generates aesthetic pastel or dark background colors based on your content if no images are provided.
* **Immersive Reading Mode:** Swipe left/right, use keyboard arrows, and auto-hiding UI for distraction-free reading.
* **Dark Mode & Safe Mode:** Eye-friendly dark theme and an NSFW toggle to hide sensitive collections when in public.

### 🆚 Flip Magazine vs. Flipboard
Flip Magazine serves as a decentralized, private alternative to social curation platforms like Flipboard.

| Feature | Flipboard | Flip Magazine (This App) |
| :--- | :--- | :--- |
| **Curation Style** | Algorithm-driven & RSS Feeds | 100% Manual, Intentional Curation |
| **Privacy** | Cloud-based, tracks reading habits | Local-first, zero tracking, total privacy |
| **Access** | Requires App / Account / Internet | No App needed, runs offline via Exported HTML |
| **Sharing** | Share a link to a cloud server | Share an actual `.html` file (Self-contained) |
| **Content Limits** | Bound by platform policies | You own the file, no censorship or limits |

### 🎯 Use Cases
1.  **Personal Mood Boards:** Curate design inspirations, architecture references, or fashion ideas without uploading them to public servers like Pinterest.
2.  **Offline Portfolios:** Photographers and designers can create a beautiful portfolio and send the HTML file directly to clients.
3.  **Private Clipping & Research:** Collect news articles, YouTube essays, and research notes into a neat offline bundle.
4.  **Digital Zines:** Create independent, underground digital magazines and distribute the HTML file through peer-to-peer networks.

### 💡 Tips and Tricks
* **Force UI Toggle:** When reading, the UI auto-hides. If your mouse gets stuck over a YouTube video and the UI won't appear, press `M` or `ESC` on your keyboard, or click the persistent 👁️ (Eye) icon in the bottom right corner.
* **Quick Page Reordering:** In the Magazine inside view, hover over a page thumbnail to reveal the `❮` and `❯` arrows to instantly swap page orders.
* **Collage Magic:** Paste up to 8 image links at once in the form, and leave the text blank. The Smart Layout Engine will automatically split them into a beautiful multi-page aesthetic collage.
* **Backup Often:** Since data is stored in your browser, clearing your cache will delete your magazines. Always use the **📦 BACKUP (.JSON)** button to save your raw data.

---
---

<a id="versi-indonesia"></a>
## 🇮🇩 Versi Indonesia

**Flip Magazine** adalah aplikasi web frontend yang mengutamakan privasi, dirancang untuk membantu Anda mengkurasi, membaca, dan mengekspor majalah digital pribadi Anda.

Daripada bergantung pada *cloud* atau akun sosial media, Flip Magazine menyimpan semuanya secara lokal di *browser* Anda dan memungkinkan Anda mengekspor seluruh majalah menjadi **Satu File HTML Mandiri (Standalone)**. Anda dapat membagikan file ini via email, flashdisk, atau WhatsApp, dan siapa pun bisa membukanya di *browser* mereka—lengkap dengan animasi geser, video, dan tata letak estetik—tanpa perlu menginstal aplikasi apa pun.

### ✨ Fitur Utama
* **100% Lokal & Privat:** Tanpa *backend*, tanpa *database*, tanpa akun. Semuanya disimpan di `localStorage` browser Anda.
* **Ekspor HTML Mandiri:** Unduh majalah Anda sebagai satu file `.html`. File ini mempertahankan semua video, gambar, dan logika membaca.
* **Mesin Tata Letak Pintar (Smart Layout):** * Memecah teks panjang secara otomatis menjadi beberapa halaman (Auto-Pagination).
    * Menyusun gambar berdasarkan orientasi (Landscape = 1 per halaman, Portrait = 2 per halaman).
    * Alur baca *Z-Pattern* (konten kiri-kanan berselang-seling).
* **Dukungan Multi-Media:** Mendukung tautan gambar langsung, video MP4, *live stream* HLS (`.m3u8`), dan YouTube.
* **Palet Warna Dinamis:** Otomatis menghasilkan warna latar pastel atau gelap yang estetik berdasarkan konten Anda jika tidak ada gambar yang diberikan.
* **Mode Membaca Imersif:** Geser kiri/kanan, gunakan panah *keyboard*, dan UI yang otomatis bersembunyi.
* **Mode Gelap & Mode Aman:** Tema gelap yang nyaman di mata, dan sakelar NSFW untuk menyembunyikan koleksi sensitif saat di tempat umum.

### 🆚 Flip Magazine vs. Flipboard
Flip Magazine hadir sebagai alternatif privat dan terdesentralisasi dari platform kurasi sosial seperti Flipboard.

| Fitur | Flipboard | Flip Magazine (Aplikasi Ini) |
| :--- | :--- | :--- |
| **Gaya Kurasi** | Disuapi algoritma & *Feed* RSS | 100% Manual, kurasi niat sendiri |
| **Privasi** | Berbasis *cloud*, melacak kebiasaan baca | Berbasis lokal, tanpa pelacakan, privasi total |
| **Akses** | Butuh Aplikasi / Akun / Internet | Tanpa aplikasi, berjalan *offline* via HTML |
| **Berbagi** | Membagikan tautan ke server *cloud* | Membagikan wujud asli file `.html` |
| **Batas Konten** | Terikat kebijakan platform/sensor | Anda pemilik filenya, bebas sensor & batasan |

### 🎯 Usecase (Skenario Penggunaan)
1.  **Mood Board Pribadi:** Mengumpulkan inspirasi desain, referensi arsitektur, atau ide *fashion* tanpa harus mengunggahnya ke server publik seperti Pinterest.
2.  **Portofolio Offline:** Fotografer dan desainer dapat membuat portofolio yang indah dan mengirimkan file HTML-nya langsung ke klien.
3.  **Kliping & Riset Pribadi:** Mengumpulkan artikel berita, esai YouTube, dan catatan riset ke dalam satu bundel *offline* yang rapi.
4.  **Zine Digital Independen:** Membuat majalah digital bawah tanah (indie) dan mendistribusikan file HTML-nya melalui jaringan *peer-to-peer* atau grup chat.

### 💡 Tips & Tricks
* **Panggil Paksa Navigasi:** Saat membaca, antarmuka (UI) akan bersembunyi otomatis. Jika *mouse* Anda tersangkut di atas video YouTube dan menu tidak mau muncul, tekan `M` atau `ESC` di *keyboard* Anda, atau klik ikon 👁️ (Mata) di pojok kanan bawah.
* **Tukar Urutan Cepat:** Di menu *Daftar Halaman*, arahkan kursor (*hover*) ke salah satu halaman untuk memunculkan panah `❮` dan `❯`. Klik untuk menukar urutan halaman secara instan.
* **Sihir Kolase:** Masukkan hingga 8 tautan gambar sekaligus di dalam formulir, dan kosongkan bagian teks. Mesin *Smart Layout* akan otomatis memecahnya menjadi kolase estetik multi-halaman.
* **Sering Lakukan Backup:** Karena data disimpan di *browser* Anda, menghapus *cache/history* akan menghapus majalah Anda. Selalu gunakan tombol **📦 BACKUP (.JSON)** untuk menyimpan data mentah Anda ke komputer.
